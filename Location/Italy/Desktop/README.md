BSD in Italy - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for BSD in Italy.

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

Total: 359

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Dell          | 0MGK50 A02                  | [fe0b9484f5](https://bsd-hardware.info/?probe=fe0b9484f5) | Jan 05, 2025 |
| HP            | 18E7                        | [fdac2d0362](https://bsd-hardware.info/?probe=fdac2d0362) | Jan 03, 2025 |
| SJRC          | ADLN-6L                     | [90498561c8](https://bsd-hardware.info/?probe=90498561c8) | Jan 02, 2025 |
| NF692         | 1.0                         | [b129c164c5](https://bsd-hardware.info/?probe=b129c164c5) | Dec 24, 2024 |
| Protectli     | VP2420                      | [6fe419fedc](https://bsd-hardware.info/?probe=6fe419fedc) | Dec 24, 2024 |
| Unknown       | Unknown                     | [94d37d7a1e](https://bsd-hardware.info/?probe=94d37d7a1e) | Dec 13, 2024 |
| Unknown       | Unknown                     | [806188d557](https://bsd-hardware.info/?probe=806188d557) | Dec 13, 2024 |
| Intel         | X79_PLUS                    | [0382eb3cd4](https://bsd-hardware.info/?probe=0382eb3cd4) | Dec 10, 2024 |
| Huanan        | X58-RX3.0 V110              | [7aa0eb6533](https://bsd-hardware.info/?probe=7aa0eb6533) | Dec 07, 2024 |
| Unknown       | Unknown                     | [5c01d44547](https://bsd-hardware.info/?probe=5c01d44547) | Dec 07, 2024 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [827453a946](https://bsd-hardware.info/?probe=827453a946) | Dec 06, 2024 |
| HP            | 0A64h                       | [4d668a54a4](https://bsd-hardware.info/?probe=4d668a54a4) | Dec 01, 2024 |
| Intel         | B75 V1.5                    | [a579cb0709](https://bsd-hardware.info/?probe=a579cb0709) | Nov 29, 2024 |
| Shenzhen M... | AHWSA                       | [90f5e4c5de](https://bsd-hardware.info/?probe=90f5e4c5de) | Nov 23, 2024 |
| HP            | 802F                        | [7685aa4970](https://bsd-hardware.info/?probe=7685aa4970) | Nov 20, 2024 |
| Unknown       | Unknown                     | [0d7c205328](https://bsd-hardware.info/?probe=0d7c205328) | Nov 20, 2024 |
| HP            | 0A64h                       | [132bd7b8cc](https://bsd-hardware.info/?probe=132bd7b8cc) | Nov 16, 2024 |
| Unknown       | Unknown                     | [a656bb922f](https://bsd-hardware.info/?probe=a656bb922f) | Nov 12, 2024 |
| ASRock        | X570 PG Velocita            | [2a30e356a7](https://bsd-hardware.info/?probe=2a30e356a7) | Nov 12, 2024 |
| Unknown       | Unknown                     | [d205d862c1](https://bsd-hardware.info/?probe=d205d862c1) | Nov 01, 2024 |
| HP            | 8062                        | [3a8dfb73b6](https://bsd-hardware.info/?probe=3a8dfb73b6) | Oct 31, 2024 |
| Quantum en... | HackBoard 2                 | [77f7cc8b05](https://bsd-hardware.info/?probe=77f7cc8b05) | Oct 27, 2024 |
| Intel         | D2500CC AAG81477-401        | [0c7e857ac8](https://bsd-hardware.info/?probe=0c7e857ac8) | Oct 27, 2024 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [35c1fa9e04](https://bsd-hardware.info/?probe=35c1fa9e04) | Oct 26, 2024 |
| Gigabyte      | A620M H                     | [c1e5a0fe6f](https://bsd-hardware.info/?probe=c1e5a0fe6f) | Oct 22, 2024 |
| Lenovo        | Win8 Pro DPK TPG            | [96bf4191cc](https://bsd-hardware.info/?probe=96bf4191cc) | Oct 17, 2024 |
| ASUSTek       | PRIME B650-PLUS             | [6d6ba6974b](https://bsd-hardware.info/?probe=6d6ba6974b) | Oct 12, 2024 |
| Shenzhen M... | AHWSA                       | [549e8b3887](https://bsd-hardware.info/?probe=549e8b3887) | Oct 12, 2024 |
| Intel         | DENLOW_REFRESH_WS           | [87cd1c965c](https://bsd-hardware.info/?probe=87cd1c965c) | Oct 07, 2024 |
| MSI           | MS-7D16                     | [e9bddb011d](https://bsd-hardware.info/?probe=e9bddb011d) | Oct 01, 2024 |
| Shenzhen M... | AHWSA                       | [3a5bb1ef92](https://bsd-hardware.info/?probe=3a5bb1ef92) | Sep 28, 2024 |
| MACHINIST     | X99-MR9A PRO MAX V1.2       | [71545c2b0e](https://bsd-hardware.info/?probe=71545c2b0e) | Sep 24, 2024 |
| HP            | 213D A01                    | [edc8edec39](https://bsd-hardware.info/?probe=edc8edec39) | Sep 22, 2024 |
| Pegatron      | 2ACF                        | [eeb702f96d](https://bsd-hardware.info/?probe=eeb702f96d) | Aug 29, 2024 |
| Unknown       | Unknown                     | [2e271c0d9e](https://bsd-hardware.info/?probe=2e271c0d9e) | Aug 19, 2024 |
| ASUSTek       | SABERTOOTH Z77              | [942d148e6e](https://bsd-hardware.info/?probe=942d148e6e) | Aug 17, 2024 |
| MW            | GMLK-2_5G4L                 | [c78e39d7b2](https://bsd-hardware.info/?probe=c78e39d7b2) | Aug 04, 2024 |
| Unknown       | Unknown                     | [059091972d](https://bsd-hardware.info/?probe=059091972d) | Jul 31, 2024 |
| iEi           | B508 V1.00                  | [5286578613](https://bsd-hardware.info/?probe=5286578613) | Jul 30, 2024 |
| Unknown       | Unknown                     | [0c003d992b](https://bsd-hardware.info/?probe=0c003d992b) | Jul 26, 2024 |
| Unknown       | Unknown                     | [52ce09a582](https://bsd-hardware.info/?probe=52ce09a582) | Jul 25, 2024 |
| Unknown       | Unknown                     | [c33fd5610f](https://bsd-hardware.info/?probe=c33fd5610f) | Jul 23, 2024 |
| Protectli     | V1210                       | [f22c04d928](https://bsd-hardware.info/?probe=f22c04d928) | Jul 14, 2024 |
| Protectli     | VP2420                      | [5dab536cca](https://bsd-hardware.info/?probe=5dab536cca) | Jul 05, 2024 |
| Unknown       | Unknown                     | [5766ba4f99](https://bsd-hardware.info/?probe=5766ba4f99) | Jun 28, 2024 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | [52b02922bc](https://bsd-hardware.info/?probe=52b02922bc) | Jun 27, 2024 |
| ASRock        | X300M-STX                   | [2c4cc4c744](https://bsd-hardware.info/?probe=2c4cc4c744) | Jun 26, 2024 |
| Unknown       | YL-SKUL6                    | [e6e7050b09](https://bsd-hardware.info/?probe=e6e7050b09) | Jun 25, 2024 |
| Unknown       | Unknown                     | [14bd339dfc](https://bsd-hardware.info/?probe=14bd339dfc) | Jun 18, 2024 |
| Lenovo        | NOK                         | [9ae535f558](https://bsd-hardware.info/?probe=9ae535f558) | Jun 11, 2024 |
| AZW           | EQ                          | [4b940b4e22](https://bsd-hardware.info/?probe=4b940b4e22) | Jun 07, 2024 |
| Unknown       | Unknown                     | [6e4e779799](https://bsd-hardware.info/?probe=6e4e779799) | Jun 05, 2024 |
| ASRock        | J5040-ITX                   | [dfb7f31242](https://bsd-hardware.info/?probe=dfb7f31242) | Jun 02, 2024 |
| Unknown       | Unknown                     | [002ead7053](https://bsd-hardware.info/?probe=002ead7053) | May 24, 2024 |
| Apple         | Mac-F221BEC8                | [169fdec0c9](https://bsd-hardware.info/?probe=169fdec0c9) | May 22, 2024 |
| MW            | GMLK-2_5G4L                 | [0ba0e09a89](https://bsd-hardware.info/?probe=0ba0e09a89) | May 20, 2024 |
| ASUSTek       | PRIME B650-PLUS             | [3e01e5ffbf](https://bsd-hardware.info/?probe=3e01e5ffbf) | May 03, 2024 |
| Quantum en... | HackBoard 2                 | [a7b0ea1eca](https://bsd-hardware.info/?probe=a7b0ea1eca) | Apr 28, 2024 |
| Dell          | 096JG8 A01                  | [a696ddada6](https://bsd-hardware.info/?probe=a696ddada6) | Apr 20, 2024 |
| PC Engines    | apu1                        | [cceec3e9bd](https://bsd-hardware.info/?probe=cceec3e9bd) | Apr 14, 2024 |
| Unknown       | Unknown                     | [a9c935db85](https://bsd-hardware.info/?probe=a9c935db85) | Apr 09, 2024 |
| Gigabyte      | X570 AORUS ELITE            | [426677818b](https://bsd-hardware.info/?probe=426677818b) | Apr 07, 2024 |
| Unknown       | Unknown                     | [1af73d4146](https://bsd-hardware.info/?probe=1af73d4146) | Apr 04, 2024 |
| Unknown       | Unknown                     | [b9c567bdde](https://bsd-hardware.info/?probe=b9c567bdde) | Mar 21, 2024 |
| HP            | 2B5E                        | [35b1572267](https://bsd-hardware.info/?probe=35b1572267) | Mar 17, 2024 |
| PC Engines    | APU2                        | [9cd0068a06](https://bsd-hardware.info/?probe=9cd0068a06) | Mar 13, 2024 |
| PC Engines    | APU2                        | [891b69ea9c](https://bsd-hardware.info/?probe=891b69ea9c) | Mar 13, 2024 |
| Unknown       | Unknown                     | [7f49c436eb](https://bsd-hardware.info/?probe=7f49c436eb) | Feb 27, 2024 |
| PC Engines    | APU2                        | [bd47726af7](https://bsd-hardware.info/?probe=bd47726af7) | Feb 25, 2024 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | [8f0a5d2d0a](https://bsd-hardware.info/?probe=8f0a5d2d0a) | Feb 16, 2024 |
| PC Engines    | APU2                        | [df18317865](https://bsd-hardware.info/?probe=df18317865) | Feb 14, 2024 |
| PC Engines    | APU2                        | [251265d29e](https://bsd-hardware.info/?probe=251265d29e) | Feb 12, 2024 |
| Unknown       | Unknown                     | [19e59c140c](https://bsd-hardware.info/?probe=19e59c140c) | Feb 09, 2024 |
| PC Engines    | APU2                        | [6d52e4dad5](https://bsd-hardware.info/?probe=6d52e4dad5) | Feb 07, 2024 |
| PC Engines    | APU2                        | [591ead54fc](https://bsd-hardware.info/?probe=591ead54fc) | Jan 30, 2024 |
| Unknown       | Unknown                     | [f2406d4352](https://bsd-hardware.info/?probe=f2406d4352) | Jan 29, 2024 |
| Unknown       | Unknown                     | [4ff002fe77](https://bsd-hardware.info/?probe=4ff002fe77) | Jan 26, 2024 |
| Unknown       | Unknown                     | [de7d99595c](https://bsd-hardware.info/?probe=de7d99595c) | Jan 23, 2024 |
| HP            | 1494                        | [45c45d492a](https://bsd-hardware.info/?probe=45c45d492a) | Jan 18, 2024 |
| ASUSTek       | TUF Gaming H470-PRO         | [e0d9f347e9](https://bsd-hardware.info/?probe=e0d9f347e9) | Jan 13, 2024 |
| Unknown       | Unknown                     | [df4f6b185b](https://bsd-hardware.info/?probe=df4f6b185b) | Jan 09, 2024 |
| PC Engines    | APU2                        | [b08ca32731](https://bsd-hardware.info/?probe=b08ca32731) | Jan 07, 2024 |
| Protectli     | VP2420                      | [5368ee9cc8](https://bsd-hardware.info/?probe=5368ee9cc8) | Dec 24, 2023 |
| Pegatron      | 2ACF                        | [2556fa3be1](https://bsd-hardware.info/?probe=2556fa3be1) | Dec 22, 2023 |
| Unknown       | Unknown                     | [7b24999fbb](https://bsd-hardware.info/?probe=7b24999fbb) | Dec 22, 2023 |
| Protectli     | VP2420                      | [74c1ede426](https://bsd-hardware.info/?probe=74c1ede426) | Dec 10, 2023 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | [4a74f06217](https://bsd-hardware.info/?probe=4a74f06217) | Dec 06, 2023 |
| PC Engines    | APU2                        | [6bbcef15d3](https://bsd-hardware.info/?probe=6bbcef15d3) | Dec 05, 2023 |
| Unknown       | Unknown                     | [ca548efdec](https://bsd-hardware.info/?probe=ca548efdec) | Dec 04, 2023 |
| PC Engines    | APU2                        | [46fa133d51](https://bsd-hardware.info/?probe=46fa133d51) | Dec 04, 2023 |
| HP            | 1825                        | [3edf79b1ba](https://bsd-hardware.info/?probe=3edf79b1ba) | Dec 03, 2023 |
| Unknown       | Unknown                     | [5631aa6b68](https://bsd-hardware.info/?probe=5631aa6b68) | Nov 27, 2023 |
| YANYU         | ITX-M9F VER:1.3 baytrail    | [c9e7bbc120](https://bsd-hardware.info/?probe=c9e7bbc120) | Nov 23, 2023 |
| Lenovo        | ThinkCentre M720s 10SUSB... | [a44a9f3526](https://bsd-hardware.info/?probe=a44a9f3526) | Nov 23, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | [98fac2d452](https://bsd-hardware.info/?probe=98fac2d452) | Nov 15, 2023 |
| YENTEK        | D41SL                       | [8cb79449c8](https://bsd-hardware.info/?probe=8cb79449c8) | Nov 10, 2023 |
| IceWhale T... | ZimaBoard 432 ZMB           | [018805dc37](https://bsd-hardware.info/?probe=018805dc37) | Nov 03, 2023 |
| ASUSTek       | P8Z77-V LX                  | [7077dec0a1](https://bsd-hardware.info/?probe=7077dec0a1) | Nov 01, 2023 |
| YANYU         | M9F baytrail                | [746772e77b](https://bsd-hardware.info/?probe=746772e77b) | Oct 30, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [bb195148f7](https://bsd-hardware.info/?probe=bb195148f7) | Oct 29, 2023 |
| Dell          | PowerEdge T110 II           | [f93395bc11](https://bsd-hardware.info/?probe=f93395bc11) | Oct 28, 2023 |
| YANYU         | M9F baytrail                | [f9e833a5f9](https://bsd-hardware.info/?probe=f9e833a5f9) | Oct 27, 2023 |
| HP            | 213D A01                    | [6a023bfe9f](https://bsd-hardware.info/?probe=6a023bfe9f) | Oct 14, 2023 |
| ASRock        | X300M-STX                   | [fbc9fe11b1](https://bsd-hardware.info/?probe=fbc9fe11b1) | Oct 13, 2023 |
| ANGXUN        | X79-VG2 V1.3                | [c823cbad48](https://bsd-hardware.info/?probe=c823cbad48) | Oct 10, 2023 |
| Unknown       | Unknown                     | [1bb43f3258](https://bsd-hardware.info/?probe=1bb43f3258) | Oct 10, 2023 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | [9e99e33fa3](https://bsd-hardware.info/?probe=9e99e33fa3) | Oct 09, 2023 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | [08dab02121](https://bsd-hardware.info/?probe=08dab02121) | Oct 09, 2023 |
| Unknown       | Unknown                     | [af88ff7c18](https://bsd-hardware.info/?probe=af88ff7c18) | Oct 07, 2023 |
| ASUSTek       | P8Z77-V LX                  | [9190b85f99](https://bsd-hardware.info/?probe=9190b85f99) | Oct 04, 2023 |
| ASUSTek       | P8Z77-V LX                  | [914de9ed88](https://bsd-hardware.info/?probe=914de9ed88) | Oct 04, 2023 |
| ASUSTek       | P8Z77-V LX                  | [ba9a892240](https://bsd-hardware.info/?probe=ba9a892240) | Oct 04, 2023 |
| Unknown       | Unknown                     | [002103bb3a](https://bsd-hardware.info/?probe=002103bb3a) | Oct 02, 2023 |
| ASUSTek       | PRIME A520M-A II            | [29bcb3ca3e](https://bsd-hardware.info/?probe=29bcb3ca3e) | Sep 29, 2023 |
| ASRock        | H270 Pro4                   | [cba80ecde3](https://bsd-hardware.info/?probe=cba80ecde3) | Sep 24, 2023 |
| Unknown       | Unknown                     | [dcf1ebd901](https://bsd-hardware.info/?probe=dcf1ebd901) | Sep 20, 2023 |
| AZW           | U59                         | [ae0d8568d1](https://bsd-hardware.info/?probe=ae0d8568d1) | Sep 15, 2023 |
| AZW           | U59                         | [7e094459f9](https://bsd-hardware.info/?probe=7e094459f9) | Sep 14, 2023 |
| PC Engines    | APU2                        | [3d3b16c0cf](https://bsd-hardware.info/?probe=3d3b16c0cf) | Aug 25, 2023 |
| AZW           | U59                         | [e08540ab36](https://bsd-hardware.info/?probe=e08540ab36) | Aug 25, 2023 |
| Protectli     | FW4B                        | [4b358b0106](https://bsd-hardware.info/?probe=4b358b0106) | Aug 24, 2023 |
| BESSTAR Te... | IB9                         | [c9f5ede507](https://bsd-hardware.info/?probe=c9f5ede507) | Aug 18, 2023 |
| Intel         | Q3XXG4-P V1.0               | [f0398bfb85](https://bsd-hardware.info/?probe=f0398bfb85) | Aug 10, 2023 |
| Unknown       | Unknown                     | [28f0d503fd](https://bsd-hardware.info/?probe=28f0d503fd) | Aug 07, 2023 |
| Unknown       | Unknown                     | [6238337b24](https://bsd-hardware.info/?probe=6238337b24) | Aug 07, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [d3fac2e3fe](https://bsd-hardware.info/?probe=d3fac2e3fe) | Aug 06, 2023 |
| MW            | GMLK-2_5G4L                 | [155f885c95](https://bsd-hardware.info/?probe=155f885c95) | Aug 01, 2023 |
| ASUSTek       | P8P67                       | [0e10359af8](https://bsd-hardware.info/?probe=0e10359af8) | Jul 29, 2023 |
| ASUSTek       | PRIME B650-PLUS             | [e74d459c5a](https://bsd-hardware.info/?probe=e74d459c5a) | Jul 28, 2023 |
| Dell          | 0PTTT9 A01                  | [a3624fdcfc](https://bsd-hardware.info/?probe=a3624fdcfc) | Jul 24, 2023 |
| Dell          | 0PTTT9 A01                  | [0f55bad1af](https://bsd-hardware.info/?probe=0f55bad1af) | Jul 08, 2023 |
| MSI           | H510I PRO WIFI              | [743d249ba5](https://bsd-hardware.info/?probe=743d249ba5) | Jul 07, 2023 |
| Dell          | 0WMJ54 A01                  | [48fcb6e4ab](https://bsd-hardware.info/?probe=48fcb6e4ab) | Jul 05, 2023 |
| Protectli     | FW4B                        | [a3cf476fe8](https://bsd-hardware.info/?probe=a3cf476fe8) | Jul 03, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [c30f91d5cc](https://bsd-hardware.info/?probe=c30f91d5cc) | Jul 01, 2023 |
| ASUSTek       | N3700T                      | [16b73b05ef](https://bsd-hardware.info/?probe=16b73b05ef) | Jun 26, 2023 |
| Unknown       | Unknown                     | [229e573059](https://bsd-hardware.info/?probe=229e573059) | Jun 13, 2023 |
| Unknown       | Unknown                     | [9d271bc94c](https://bsd-hardware.info/?probe=9d271bc94c) | Jun 12, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [fe412825f2](https://bsd-hardware.info/?probe=fe412825f2) | Jun 10, 2023 |
| Dell          | 0WR7PY A03                  | [c8496622be](https://bsd-hardware.info/?probe=c8496622be) | Jun 03, 2023 |
| Dell          | 0WR7PY A03                  | [b9f7e3e209](https://bsd-hardware.info/?probe=b9f7e3e209) | Jun 03, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [d08f309c4c](https://bsd-hardware.info/?probe=d08f309c4c) | May 26, 2023 |
| Intel         | Q3XXG4-P V1.0               | [9160d45441](https://bsd-hardware.info/?probe=9160d45441) | May 25, 2023 |
| Unknown       | Unknown                     | [8b5ec8c5f4](https://bsd-hardware.info/?probe=8b5ec8c5f4) | May 23, 2023 |
| Gigabyte      | A520M S2H                   | [582dc6ab9f](https://bsd-hardware.info/?probe=582dc6ab9f) | May 15, 2023 |
| Unknown       | Unknown                     | [b26eac2277](https://bsd-hardware.info/?probe=b26eac2277) | May 13, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [1dac5a7bb2](https://bsd-hardware.info/?probe=1dac5a7bb2) | May 13, 2023 |
| Unknown       | Unknown                     | [bf8246ecb5](https://bsd-hardware.info/?probe=bf8246ecb5) | May 11, 2023 |
| ASUSTek       | PRIME B650-PLUS             | [be83fbb0f2](https://bsd-hardware.info/?probe=be83fbb0f2) | May 09, 2023 |
| Unknown       | Unknown                     | [5c6c169e73](https://bsd-hardware.info/?probe=5c6c169e73) | May 01, 2023 |
| Unknown       | Unknown                     | [d572f5ff91](https://bsd-hardware.info/?probe=d572f5ff91) | May 01, 2023 |
| Unknown       | HX90                        | [b3300c45bc](https://bsd-hardware.info/?probe=b3300c45bc) | May 01, 2023 |
| Unknown       | Unknown                     | [1774da050f](https://bsd-hardware.info/?probe=1774da050f) | Apr 29, 2023 |
| HP            | 82B4                        | [9ec1e6d6f4](https://bsd-hardware.info/?probe=9ec1e6d6f4) | Apr 23, 2023 |
| Intel         | SKYBAY                      | [03dd920110](https://bsd-hardware.info/?probe=03dd920110) | Apr 22, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [d343800c53](https://bsd-hardware.info/?probe=d343800c53) | Apr 16, 2023 |
| PC Engines    | apu4                        | [9217e1982f](https://bsd-hardware.info/?probe=9217e1982f) | Apr 14, 2023 |
| ASRock        | G31M-S                      | [fed4a42c32](https://bsd-hardware.info/?probe=fed4a42c32) | Apr 08, 2023 |
| ASRock        | G31M-S                      | [4596f78aee](https://bsd-hardware.info/?probe=4596f78aee) | Apr 08, 2023 |
| Unknown       | Unknown                     | [5168183b15](https://bsd-hardware.info/?probe=5168183b15) | Apr 06, 2023 |
| Fujitsu       | D3028-A1 S26361-D3028-A1    | [45f590d129](https://bsd-hardware.info/?probe=45f590d129) | Apr 04, 2023 |
| Fujitsu       | D3028-A1 S26361-D3028-A1    | [ab0643727f](https://bsd-hardware.info/?probe=ab0643727f) | Apr 02, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [fb6477d43e](https://bsd-hardware.info/?probe=fb6477d43e) | Mar 31, 2023 |
| YANYU         | H17SL                       | [0f9829ebe4](https://bsd-hardware.info/?probe=0f9829ebe4) | Mar 26, 2023 |
| ASUSTek       | F1A55                       | [91ad5bab75](https://bsd-hardware.info/?probe=91ad5bab75) | Mar 25, 2023 |
| Unknown       | Unknown                     | [a7e98f9a10](https://bsd-hardware.info/?probe=a7e98f9a10) | Mar 23, 2023 |
| T-bao         | MINI PC V1.0                | [eb2bc1cd51](https://bsd-hardware.info/?probe=eb2bc1cd51) | Mar 23, 2023 |
| ASUSTek       | PRIME H410M-A               | [cbbeb5c41c](https://bsd-hardware.info/?probe=cbbeb5c41c) | Mar 22, 2023 |
| HP            | 8054                        | [6e5a18f346](https://bsd-hardware.info/?probe=6e5a18f346) | Mar 20, 2023 |
| YANYU         | H17SL                       | [37a549331f](https://bsd-hardware.info/?probe=37a549331f) | Mar 14, 2023 |
| MSI           | 0A48                        | [815f019a8c](https://bsd-hardware.info/?probe=815f019a8c) | Mar 14, 2023 |
| AZW           | U59                         | [5a6ef3fb8d](https://bsd-hardware.info/?probe=5a6ef3fb8d) | Mar 14, 2023 |
| Dell          | 0WMJ54 A01                  | [7949f20162](https://bsd-hardware.info/?probe=7949f20162) | Mar 12, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [a3f921de9a](https://bsd-hardware.info/?probe=a3f921de9a) | Mar 12, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [2050921c3d](https://bsd-hardware.info/?probe=2050921c3d) | Mar 12, 2023 |
| Gigabyte      | B450M K                     | [0d0433284e](https://bsd-hardware.info/?probe=0d0433284e) | Mar 11, 2023 |
| NF692         | 1.0                         | [16fa0b0102](https://bsd-hardware.info/?probe=16fa0b0102) | Mar 11, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [6729453203](https://bsd-hardware.info/?probe=6729453203) | Mar 09, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [6dee276a48](https://bsd-hardware.info/?probe=6dee276a48) | Mar 07, 2023 |
| Gigabyte      | H97M-HD3                    | [77a58527da](https://bsd-hardware.info/?probe=77a58527da) | Mar 01, 2023 |
| Stonesoft     | FW-315-C1                   | [e8a2206ad2](https://bsd-hardware.info/?probe=e8a2206ad2) | Feb 28, 2023 |
| Intel         | JSL MRD                     | [1587ea95da](https://bsd-hardware.info/?probe=1587ea95da) | Feb 18, 2023 |
| Unknown       | SKYBAY                      | [df7f4524d7](https://bsd-hardware.info/?probe=df7f4524d7) | Feb 12, 2023 |
| Unknown       | Unknown                     | [7f9208dc11](https://bsd-hardware.info/?probe=7f9208dc11) | Feb 06, 2023 |
| HP            | 213D A01                    | [659939cc8b](https://bsd-hardware.info/?probe=659939cc8b) | Jan 26, 2023 |
| Unknown       | Unknown                     | [aa940792fc](https://bsd-hardware.info/?probe=aa940792fc) | Jan 25, 2023 |
| Gigabyte      | A520M S2H                   | [803a152afc](https://bsd-hardware.info/?probe=803a152afc) | Jan 23, 2023 |
| ASUSTek       | PRO A520M-C                 | [bebcd1a008](https://bsd-hardware.info/?probe=bebcd1a008) | Jan 20, 2023 |
| Gigabyte      | H270M-DS3H-CF               | [d0e2e85346](https://bsd-hardware.info/?probe=d0e2e85346) | Jan 17, 2023 |
| Unknown       | SKYBAY                      | [c1e1ba5558](https://bsd-hardware.info/?probe=c1e1ba5558) | Jan 16, 2023 |
| Supermicro    | X9SCI/X9SCA                 | [942d966486](https://bsd-hardware.info/?probe=942d966486) | Jan 11, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [2265227a5c](https://bsd-hardware.info/?probe=2265227a5c) | Dec 26, 2022 |
| MSI           | MS-7922                     | [95dbf4f7a8](https://bsd-hardware.info/?probe=95dbf4f7a8) | Dec 19, 2022 |
| Pegatron      | 2ACF                        | [511f2a6d16](https://bsd-hardware.info/?probe=511f2a6d16) | Dec 19, 2022 |
| Gigabyte      | N3160ND3V                   | [c84bedc821](https://bsd-hardware.info/?probe=c84bedc821) | Dec 15, 2022 |
| Dell          | 0WMJ54 A01                  | [435807287e](https://bsd-hardware.info/?probe=435807287e) | Dec 15, 2022 |
| AZW           | U59                         | [9b22c68e98](https://bsd-hardware.info/?probe=9b22c68e98) | Dec 13, 2022 |
| ASUSTek       | PRIME Z390M-PLUS            | [7329e04c22](https://bsd-hardware.info/?probe=7329e04c22) | Nov 27, 2022 |
| ASUSTek       | P11C-X Series               | [6860cd72f8](https://bsd-hardware.info/?probe=6860cd72f8) | Nov 26, 2022 |
| ASUSTek       | P11C-X Series               | [cfdb06e761](https://bsd-hardware.info/?probe=cfdb06e761) | Nov 26, 2022 |
| Dell          | 0PTTT9 A01                  | [74575d6dfe](https://bsd-hardware.info/?probe=74575d6dfe) | Nov 25, 2022 |
| Dell          | 0VD5HY A00                  | [1a0df311e3](https://bsd-hardware.info/?probe=1a0df311e3) | Nov 07, 2022 |
| Gigabyte      | H270M-DS3H-CF               | [5784d8bed6](https://bsd-hardware.info/?probe=5784d8bed6) | Nov 04, 2022 |
| Acer          | Veriton X2610G              | [e4289c3f15](https://bsd-hardware.info/?probe=e4289c3f15) | Oct 24, 2022 |
| Unknown       | Unknown                     | [1188b56e14](https://bsd-hardware.info/?probe=1188b56e14) | Oct 19, 2022 |
| Unknown       | Unknown                     | [915c66f8bd](https://bsd-hardware.info/?probe=915c66f8bd) | Oct 19, 2022 |
| PC Engines    | apu4                        | [20cfd8a3c8](https://bsd-hardware.info/?probe=20cfd8a3c8) | Oct 17, 2022 |
| Pegatron      | 2ACF                        | [c57cc3a923](https://bsd-hardware.info/?probe=c57cc3a923) | Oct 17, 2022 |
| ASRock        | Q1900M                      | [7d0380e2d0](https://bsd-hardware.info/?probe=7d0380e2d0) | Oct 15, 2022 |
| ASRock        | J3355B-ITX                  | [d802705c1d](https://bsd-hardware.info/?probe=d802705c1d) | Oct 10, 2022 |
| ASRock        | B75M R2.0                   | [a28ea59f1f](https://bsd-hardware.info/?probe=a28ea59f1f) | Oct 07, 2022 |
| Unknown       | Unknown                     | [bdabafdcb1](https://bsd-hardware.info/?probe=bdabafdcb1) | Oct 01, 2022 |
| ASRock        | Q1900B-ITX                  | [81722a937a](https://bsd-hardware.info/?probe=81722a937a) | Sep 13, 2022 |
| HP            | 8648                        | [e7e610794c](https://bsd-hardware.info/?probe=e7e610794c) | Sep 12, 2022 |
| Dell          | 0WMJ54 A01                  | [b54e6663f9](https://bsd-hardware.info/?probe=b54e6663f9) | Sep 10, 2022 |
| Intel         | J1900                       | [a95dd12c65](https://bsd-hardware.info/?probe=a95dd12c65) | Sep 06, 2022 |
| HP            | 1496                        | [7cd97bd330](https://bsd-hardware.info/?probe=7cd97bd330) | Sep 05, 2022 |
| PC Engines    | APU2                        | [d9216cb730](https://bsd-hardware.info/?probe=d9216cb730) | Sep 05, 2022 |
| HP            | 1496                        | [94e8713f6d](https://bsd-hardware.info/?probe=94e8713f6d) | Sep 03, 2022 |
| HP            | 1496                        | [1567aa1c21](https://bsd-hardware.info/?probe=1567aa1c21) | Sep 01, 2022 |
| Unknown       | HX90                        | [568468e95b](https://bsd-hardware.info/?probe=568468e95b) | Sep 01, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [2349014a6c](https://bsd-hardware.info/?probe=2349014a6c) | Aug 29, 2022 |
| PC Engines    | APU2                        | [b3d60c2790](https://bsd-hardware.info/?probe=b3d60c2790) | Aug 22, 2022 |
| ASUSTek       | M4A87TD EVO                 | [c03da8657e](https://bsd-hardware.info/?probe=c03da8657e) | Aug 17, 2022 |
| PC Engines    | APU2                        | [028dc7aa20](https://bsd-hardware.info/?probe=028dc7aa20) | Aug 17, 2022 |
| Dell          | 0WMJ54 A01                  | [1d4ccaabda](https://bsd-hardware.info/?probe=1d4ccaabda) | Aug 13, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [17dc06ed68](https://bsd-hardware.info/?probe=17dc06ed68) | Aug 12, 2022 |
| Unknown       | Unknown                     | [af3d9689c2](https://bsd-hardware.info/?probe=af3d9689c2) | Aug 11, 2022 |
| Unknown       | Unknown                     | [5049417b7b](https://bsd-hardware.info/?probe=5049417b7b) | Aug 11, 2022 |
| Intel         | SKYBAY                      | [c7010b7ebc](https://bsd-hardware.info/?probe=c7010b7ebc) | Aug 09, 2022 |
| Shenzhen M... | AHWSA                       | [21cda0eb5d](https://bsd-hardware.info/?probe=21cda0eb5d) | Aug 09, 2022 |
| Intel         | SKYBAY                      | [bc7d4d8e1e](https://bsd-hardware.info/?probe=bc7d4d8e1e) | Aug 08, 2022 |
| Unknown       | Unknown                     | [df3667156b](https://bsd-hardware.info/?probe=df3667156b) | Aug 02, 2022 |
| Lex           | Pineview-D                  | [7d7195024e](https://bsd-hardware.info/?probe=7d7195024e) | Aug 02, 2022 |
| Intel         | Q3XXG4-P V1.0               | [d6a3d57165](https://bsd-hardware.info/?probe=d6a3d57165) | Jul 29, 2022 |
| PC Engines    | APU2                        | [bb5d45a75d](https://bsd-hardware.info/?probe=bb5d45a75d) | Jul 29, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [e3655742ba](https://bsd-hardware.info/?probe=e3655742ba) | Jul 18, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [4b9e0bb7bb](https://bsd-hardware.info/?probe=4b9e0bb7bb) | Jul 18, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [af1e80d15d](https://bsd-hardware.info/?probe=af1e80d15d) | Jul 18, 2022 |
| ASUSTek       | M4A785TD-M EVO              | [def87ec245](https://bsd-hardware.info/?probe=def87ec245) | Jul 18, 2022 |
| ASUSTek       | PRIME H410M-A               | [7b6faf5301](https://bsd-hardware.info/?probe=7b6faf5301) | Jul 14, 2022 |
| ASUSTek       | PRIME H410M-A               | [ba243fa7c4](https://bsd-hardware.info/?probe=ba243fa7c4) | Jul 09, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [d3aba12432](https://bsd-hardware.info/?probe=d3aba12432) | Jul 09, 2022 |
| ASRock        | B75M R2.0                   | [6011c70ca4](https://bsd-hardware.info/?probe=6011c70ca4) | Jul 07, 2022 |
| HP            | 0A98h                       | [655fc531fb](https://bsd-hardware.info/?probe=655fc531fb) | Jun 30, 2022 |
| Pegatron      | 2ACF                        | [e461a4559d](https://bsd-hardware.info/?probe=e461a4559d) | Jun 29, 2022 |
| HP            | 304Bh                       | [8a3151b3cd](https://bsd-hardware.info/?probe=8a3151b3cd) | Jun 16, 2022 |
| NF692         | 1.0                         | [e87866bf5a](https://bsd-hardware.info/?probe=e87866bf5a) | Jun 10, 2022 |
| ASUSTek       | PRIME H410M-E               | [8099e7abaf](https://bsd-hardware.info/?probe=8099e7abaf) | Jun 03, 2022 |
| HP            | ProLiant MicroServer Gen... | [4b3b7a0929](https://bsd-hardware.info/?probe=4b3b7a0929) | May 31, 2022 |
| HP            | ProLiant MicroServer Gen... | [5d3db8382f](https://bsd-hardware.info/?probe=5d3db8382f) | May 31, 2022 |
| T-bao         | MINI PC V1.0                | [a89b2081bb](https://bsd-hardware.info/?probe=a89b2081bb) | May 25, 2022 |
| ASUSTek       | PRIME B550M-K               | [ce5ddde5ad](https://bsd-hardware.info/?probe=ce5ddde5ad) | May 18, 2022 |
| Protectli     | FW4B Ver                    | [2769c8f286](https://bsd-hardware.info/?probe=2769c8f286) | May 17, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [5ff176fff8](https://bsd-hardware.info/?probe=5ff176fff8) | May 05, 2022 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [12cc40cc60](https://bsd-hardware.info/?probe=12cc40cc60) | Apr 23, 2022 |
| Pegatron      | Benicia                     | [9045b4f449](https://bsd-hardware.info/?probe=9045b4f449) | Apr 16, 2022 |
| ASUSTek       | PRIME Z390M-PLUS            | [680303f943](https://bsd-hardware.info/?probe=680303f943) | Apr 16, 2022 |
| ASUSTek       | PRIME Z390M-PLUS            | [47d17d48a7](https://bsd-hardware.info/?probe=47d17d48a7) | Apr 15, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | [fbdd8d4f48](https://bsd-hardware.info/?probe=fbdd8d4f48) | Apr 05, 2022 |
| HP            | 212B                        | [33e7c65907](https://bsd-hardware.info/?probe=33e7c65907) | Apr 04, 2022 |
| Gigabyte      | X570 AORUS PRO              | [3877a33214](https://bsd-hardware.info/?probe=3877a33214) | Apr 02, 2022 |
| Gigabyte      | X570 AORUS PRO              | [3da637e3c6](https://bsd-hardware.info/?probe=3da637e3c6) | Apr 02, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [7b79164c18](https://bsd-hardware.info/?probe=7b79164c18) | Apr 01, 2022 |
| Unknown       | Unknown                     | [bddd5d8963](https://bsd-hardware.info/?probe=bddd5d8963) | Mar 18, 2022 |
| Unknown       | Unknown                     | [65ada9d5da](https://bsd-hardware.info/?probe=65ada9d5da) | Mar 11, 2022 |
| HP            | 3397                        | [841ed56816](https://bsd-hardware.info/?probe=841ed56816) | Mar 02, 2022 |
| Pegatron      | 2ACF                        | [e098f52d51](https://bsd-hardware.info/?probe=e098f52d51) | Feb 19, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [df6278638e](https://bsd-hardware.info/?probe=df6278638e) | Feb 15, 2022 |
| Intel         | Q3XXG4-P V1.0               | [ea7cf2885f](https://bsd-hardware.info/?probe=ea7cf2885f) | Feb 13, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [6997de25f9](https://bsd-hardware.info/?probe=6997de25f9) | Feb 11, 2022 |
| MW            | GMLK-2_5G4L                 | [7a3744a41a](https://bsd-hardware.info/?probe=7a3744a41a) | Feb 07, 2022 |
| Dell          | 0TK7TF A00                  | [d13ca7163c](https://bsd-hardware.info/?probe=d13ca7163c) | Jan 30, 2022 |
| Intel         | D2500CC AAG81477-401        | [f4d8bd7979](https://bsd-hardware.info/?probe=f4d8bd7979) | Jan 30, 2022 |
| Fujitsu       | D3028-A1 S26361-D3028-A1    | [f7e7df9416](https://bsd-hardware.info/?probe=f7e7df9416) | Jan 30, 2022 |
| Fujitsu       | D3028-A1 S26361-D3028-A1    | [fc63aa695e](https://bsd-hardware.info/?probe=fc63aa695e) | Jan 27, 2022 |
| PC Engines    | APU2                        | [52bd5dc1ce](https://bsd-hardware.info/?probe=52bd5dc1ce) | Jan 26, 2022 |
| ASUSTek       | BM6835_BM6635_BP6335        | [73562aa169](https://bsd-hardware.info/?probe=73562aa169) | Jan 25, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [ed9f5d1a27](https://bsd-hardware.info/?probe=ed9f5d1a27) | Jan 15, 2022 |
| PC Engines    | APU2                        | [c2b05fc937](https://bsd-hardware.info/?probe=c2b05fc937) | Jan 14, 2022 |
| ASRock        | B75M R2.0                   | [7b99b0eaa6](https://bsd-hardware.info/?probe=7b99b0eaa6) | Jan 10, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [7a43524381](https://bsd-hardware.info/?probe=7a43524381) | Dec 13, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [50fba6deda](https://bsd-hardware.info/?probe=50fba6deda) | Dec 11, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [a084ff48c2](https://bsd-hardware.info/?probe=a084ff48c2) | Dec 09, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [17b557d792](https://bsd-hardware.info/?probe=17b557d792) | Dec 08, 2021 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [ddcab97db2](https://bsd-hardware.info/?probe=ddcab97db2) | Dec 03, 2021 |
| T-bao         | MINI PC V1.0                | [4ee7de3597](https://bsd-hardware.info/?probe=4ee7de3597) | Nov 12, 2021 |
| Intel         | Q3XXG4-P V1.0               | [22a18ba45e](https://bsd-hardware.info/?probe=22a18ba45e) | Nov 08, 2021 |
| Pegatron      | 2ACF                        | [ca23d3bbf0](https://bsd-hardware.info/?probe=ca23d3bbf0) | Oct 13, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | [b3b31d25b0](https://bsd-hardware.info/?probe=b3b31d25b0) | Oct 13, 2021 |
| Pegatron      | 2ACF                        | [97aa5e56e4](https://bsd-hardware.info/?probe=97aa5e56e4) | Oct 12, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | [5a7c1871b1](https://bsd-hardware.info/?probe=5a7c1871b1) | Oct 11, 2021 |
| Acer          | Veriton X2610G              | [1e9ed23164](https://bsd-hardware.info/?probe=1e9ed23164) | Oct 03, 2021 |
| ASRock        | B75M R2.0                   | [51b47d9321](https://bsd-hardware.info/?probe=51b47d9321) | Sep 27, 2021 |
| ASRock        | B75M R2.0                   | [de031313ff](https://bsd-hardware.info/?probe=de031313ff) | Sep 27, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [9b046b157e](https://bsd-hardware.info/?probe=9b046b157e) | Sep 17, 2021 |
| ASRock        | B75M R2.0                   | [0d23147c7d](https://bsd-hardware.info/?probe=0d23147c7d) | Sep 17, 2021 |
| ASRock        | B75M R2.0                   | [e0ae9af4ab](https://bsd-hardware.info/?probe=e0ae9af4ab) | Sep 15, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [bc2a287495](https://bsd-hardware.info/?probe=bc2a287495) | Sep 13, 2021 |
| Protectli     | FW4B                        | [861a1f7012](https://bsd-hardware.info/?probe=861a1f7012) | Aug 25, 2021 |
| MSI           | MS-B1591                    | [679b2010e9](https://bsd-hardware.info/?probe=679b2010e9) | Aug 03, 2021 |
| MSI           | MS-B1591                    | [b370a74ec0](https://bsd-hardware.info/?probe=b370a74ec0) | Aug 02, 2021 |
| Gigabyte      | P55A-UD3                    | [dc1b4d8a6b](https://bsd-hardware.info/?probe=dc1b4d8a6b) | Jul 16, 2021 |
| ASRock        | B75M R2.0                   | [d51149c1d5](https://bsd-hardware.info/?probe=d51149c1d5) | Jul 13, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [6cf3337855](https://bsd-hardware.info/?probe=6cf3337855) | Jul 01, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [f0e80b0788](https://bsd-hardware.info/?probe=f0e80b0788) | Jun 28, 2021 |
| PC Engines    | APU2                        | [dde9077545](https://bsd-hardware.info/?probe=dde9077545) | Jun 24, 2021 |
| Unknown       | Unknown                     | [822df8eb91](https://bsd-hardware.info/?probe=822df8eb91) | May 11, 2021 |
| Unknown       | Unknown                     | [cc17eea606](https://bsd-hardware.info/?probe=cc17eea606) | May 10, 2021 |
| ASUSTek       | IP4BL-ME-Oli                | [e26ecef661](https://bsd-hardware.info/?probe=e26ecef661) | May 03, 2021 |
| MSI           | B450-A PRO                  | [ed656e816f](https://bsd-hardware.info/?probe=ed656e816f) | May 01, 2021 |
| Unknown       | Unknown                     | [df793cf09f](https://bsd-hardware.info/?probe=df793cf09f) | Apr 08, 2021 |
| Unknown       | Unknown                     | [f8ba0ba112](https://bsd-hardware.info/?probe=f8ba0ba112) | Apr 08, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [62376c16a4](https://bsd-hardware.info/?probe=62376c16a4) | Mar 31, 2021 |
| Intel         | CRESCENTBAY                 | [5a7ba137e0](https://bsd-hardware.info/?probe=5a7ba137e0) | Mar 27, 2021 |
| Acer          | EG43M                       | [0bc978756c](https://bsd-hardware.info/?probe=0bc978756c) | Mar 27, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [f9c3fc3b84](https://bsd-hardware.info/?probe=f9c3fc3b84) | Mar 19, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [5ae508dfa8](https://bsd-hardware.info/?probe=5ae508dfa8) | Mar 19, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | [0a3b290f9f](https://bsd-hardware.info/?probe=0a3b290f9f) | Mar 15, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [1c30f7523f](https://bsd-hardware.info/?probe=1c30f7523f) | Mar 15, 2021 |
| PC Engines    | APU3                        | [822a83f208](https://bsd-hardware.info/?probe=822a83f208) | Mar 11, 2021 |
| ASUSTek       | IP4BL-ME-Oli                | [c672201bcb](https://bsd-hardware.info/?probe=c672201bcb) | Mar 10, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [66a223add9](https://bsd-hardware.info/?probe=66a223add9) | Mar 08, 2021 |
| Dell          | 0R849J A00                  | [1bd1dc24c9](https://bsd-hardware.info/?probe=1bd1dc24c9) | Mar 06, 2021 |
| Foxconn       | 2ADA                        | [10d02d0982](https://bsd-hardware.info/?probe=10d02d0982) | Mar 03, 2021 |
| Intel         | MAHOBAY                     | [3c5bd7b7f8](https://bsd-hardware.info/?probe=3c5bd7b7f8) | Mar 02, 2021 |
| Intel         | MAHOBAY                     | [04e66ca239](https://bsd-hardware.info/?probe=04e66ca239) | Mar 02, 2021 |
| Intel         | MAHOBAY                     | [50652a4263](https://bsd-hardware.info/?probe=50652a4263) | Feb 26, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | [58c6bf426e](https://bsd-hardware.info/?probe=58c6bf426e) | Feb 22, 2021 |
| Intel         | MAHOBAY                     | [5257239fdc](https://bsd-hardware.info/?probe=5257239fdc) | Feb 20, 2021 |
| HARDKERNEL    | ODROID-H2                   | [6fe9279f1f](https://bsd-hardware.info/?probe=6fe9279f1f) | Feb 18, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | [c996e74ebc](https://bsd-hardware.info/?probe=c996e74ebc) | Feb 14, 2021 |
| Dell          | 06NWYK A00                  | [32acfb4467](https://bsd-hardware.info/?probe=32acfb4467) | Feb 13, 2021 |
| ASUSTek       | P8H61-M LE                  | [b861820636](https://bsd-hardware.info/?probe=b861820636) | Feb 13, 2021 |
| Dell          | 06NWYK A00                  | [2ff05af403](https://bsd-hardware.info/?probe=2ff05af403) | Feb 13, 2021 |
| ASUSTek       | P8H61-M LE                  | [3a3d7d0701](https://bsd-hardware.info/?probe=3a3d7d0701) | Feb 12, 2021 |
| ASUSTek       | P8Z77-V PRO/THUNDERBOLT     | [6fdcef7c9e](https://bsd-hardware.info/?probe=6fdcef7c9e) | Feb 10, 2021 |
| ASUSTek       | PRIME X470-PRO              | [a77e980850](https://bsd-hardware.info/?probe=a77e980850) | Feb 09, 2021 |
| ASUSTek       | IP4BL-ME-Oli                | [4d225e7ebe](https://bsd-hardware.info/?probe=4d225e7ebe) | Feb 04, 2021 |
| Intel         | CRESCENTBAY                 | [f813782c8a](https://bsd-hardware.info/?probe=f813782c8a) | Jan 29, 2021 |
| Sun Micros... | Ultra 24 50                 | [622589c8e7](https://bsd-hardware.info/?probe=622589c8e7) | Jan 22, 2021 |
| Sun Micros... | Ultra 24 50                 | [7a3cb6a061](https://bsd-hardware.info/?probe=7a3cb6a061) | Jan 22, 2021 |
| ASUSTek       | M4A87TD EVO                 | [12ea57f317](https://bsd-hardware.info/?probe=12ea57f317) | Jan 22, 2021 |
| Dell          | 088DT1 A01                  | [fcc759e013](https://bsd-hardware.info/?probe=fcc759e013) | Jan 21, 2021 |
| ASRock        | H81 Pro BTC                 | [afb7cd1f1a](https://bsd-hardware.info/?probe=afb7cd1f1a) | Jan 20, 2021 |
| Intel         | CRESCENTBAY                 | [92577053eb](https://bsd-hardware.info/?probe=92577053eb) | Jan 20, 2021 |
| Intel         | CRESCENTBAY                 | [33a6dda088](https://bsd-hardware.info/?probe=33a6dda088) | Jan 20, 2021 |
| PC Engines    | APU2                        | [a178f8eb47](https://bsd-hardware.info/?probe=a178f8eb47) | Jan 19, 2021 |
| MSI           | Boston                      | [aa9d7bae21](https://bsd-hardware.info/?probe=aa9d7bae21) | Jan 17, 2021 |
| MSI           | Boston                      | [f21954fa35](https://bsd-hardware.info/?probe=f21954fa35) | Jan 17, 2021 |
| Supermicro    | X8STi                       | [7d0e121099](https://bsd-hardware.info/?probe=7d0e121099) | Jan 15, 2021 |
| Unknown       | Unknown                     | [8668b1d651](https://bsd-hardware.info/?probe=8668b1d651) | Dec 17, 2020 |
| Unknown       | Unknown                     | [d2cdc0fc7f](https://bsd-hardware.info/?probe=d2cdc0fc7f) | Nov 29, 2020 |
| Unknown       | Unknown                     | [aee9f448af](https://bsd-hardware.info/?probe=aee9f448af) | Nov 25, 2020 |
| Intel         | D945GCLF2                   | [58678b0643](https://bsd-hardware.info/?probe=58678b0643) | Oct 30, 2020 |
| Intel         | D945GCLF2                   | [3354fb903b](https://bsd-hardware.info/?probe=3354fb903b) | Oct 30, 2020 |
| Gigabyte      | X570 AORUS ELITE            | [973b62551f](https://bsd-hardware.info/?probe=973b62551f) | Oct 30, 2020 |
| AZW           | BT3 X                       | [b9f23ee753](https://bsd-hardware.info/?probe=b9f23ee753) | Oct 30, 2020 |
| ASRock        | 990FX Extreme9              | [6c0bba6d4f](https://bsd-hardware.info/?probe=6c0bba6d4f) | Jun 26, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| OpenBSD 7.1       | 8        | 2.76%   |
| helloSystem 0.8.1 | 8        | 2.76%   |
| helloSystem 0.4.0 | 7        | 2.41%   |
| OPNsense 22.7     | 6        | 2.07%   |
| helloSystem 0.7.0 | 6        | 2.07%   |
| OPNsense 24.7.10  | 5        | 1.72%   |
| OPNsense 24.1.9   | 5        | 1.72%   |
| OPNsense 23.7.9   | 5        | 1.72%   |
| OPNsense 23.1.5   | 5        | 1.72%   |
| OPNsense 23.1.11  | 5        | 1.72%   |
| OPNsense 24.7.8   | 4        | 1.38%   |
| OPNsense 24.7     | 4        | 1.38%   |
| OPNsense 24.1.8   | 4        | 1.38%   |
| OPNsense 23.7.7   | 4        | 1.38%   |
| OPNsense 23.7.5   | 4        | 1.38%   |
| OPNsense 23.7.12  | 4        | 1.38%   |
| OPNsense 23.1.6   | 4        | 1.38%   |
| OPNsense 22.7.9   | 4        | 1.38%   |
| OPNsense 22.7.6   | 4        | 1.38%   |
| OPNsense 22.1     | 4        | 1.38%   |
| OPNsense 21.1     | 4        | 1.38%   |
| OpenBSD 7.2       | 4        | 1.38%   |
| helloSystem 0.9.0 | 4        | 1.38%   |
| helloSystem 0.5.0 | 4        | 1.38%   |
| OPNsense 24.7.7   | 3        | 1.03%   |
| OPNsense 24.7.4   | 3        | 1.03%   |
| OPNsense 24.1.1   | 3        | 1.03%   |
| OPNsense 23.7.10  | 3        | 1.03%   |
| OPNsense 23.1.9   | 3        | 1.03%   |
| OPNsense 23.1.7   | 3        | 1.03%   |
| OPNsense 23.1.4   | 3        | 1.03%   |
| OPNsense 23.1.1   | 3        | 1.03%   |
| OPNsense 23.1     | 3        | 1.03%   |
| OPNsense 22.7.3   | 3        | 1.03%   |
| OPNsense 22.7.11  | 3        | 1.03%   |
| OPNsense 22.7.10  | 3        | 1.03%   |
| OPNsense 22.1.9   | 3        | 1.03%   |
| OPNsense 22.1.10  | 3        | 1.03%   |
| OPNsense 21.7.3   | 3        | 1.03%   |
| OpenBSD 7.3       | 3        | 1.03%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 124      | 59.9%   |
| helloSystem | 31       | 14.98%  |
| OpenBSD     | 23       | 11.11%  |
| FreeBSD     | 22       | 10.63%  |
| NetBSD      | 4        | 1.93%   |
| NomadBSD    | 2        | 0.97%   |
| XigmaNAS    | 1        | 0.48%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| amd64   | 202      | 98.06%  |
| evbarm  | 2        | 0.97%   |
| sparc64 | 1        | 0.49%   |
| i386    | 1        | 0.49%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Console       | 133      | 63.94%  |
| helloDesktop  | 38       | 18.27%  |
| XFCE          | 16       | 7.69%   |
| TWM           | 5        | 2.4%    |
| MATE          | 4        | 1.92%   |
| Openbox       | 2        | 0.96%   |
| KDE5          | 2        | 0.96%   |
| fvwm          | 2        | 0.96%   |
| Enlightenment | 2        | 0.96%   |
| CTWM          | 2        | 0.96%   |
| xfwm          | 1        | 0.48%   |
| LXDE          | 1        | 0.48%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 136      | 65.7%   |
| X11     | 71       | 34.3%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 167      | 80.29%  |
| SLiM    | 37       | 17.79%  |
| LightDM | 3        | 1.44%   |
| XDM     | 1        | 0.48%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Desktops | Percent |
|------------------|----------|---------|
| Unknown          | 153      | 72.51%  |
| en_US            | 22       | 10.43%  |
| it_IT            | 14       | 6.64%   |
| C                | 13       | 6.16%   |
| fr_FR            | 5        | 2.37%   |
| it_IT.ISO8859-15 | 1        | 0.47%   |
| it               | 1        | 0.47%   |
| fi_FI            | 1        | 0.47%   |
| en               | 1        | 0.47%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 177      | 85.1%   |
| BIOS | 31       | 14.9%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Ufs    | 96       | 44.65%  |
| Zfs    | 81       | 37.67%  |
| Ffs    | 23       | 10.7%   |
| Cd9660 | 15       | 6.98%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 188      | 89.95%  |
| MBR     | 14       | 6.7%    |
| Unknown | 7        | 3.35%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| Unknown                              | 35       | 16.99%  |
| ASUSTek Computer                     | 33       | 16.02%  |
| Hewlett-Packard                      | 18       | 8.74%   |
| Intel                                | 13       | 6.31%   |
| Dell                                 | 12       | 5.83%   |
| PC Engines                           | 11       | 5.34%   |
| Gigabyte Technology                  | 11       | 5.34%   |
| ASRock                               | 11       | 5.34%   |
| MSI                                  | 8        | 3.88%   |
| Protectli                            | 6        | 2.91%   |
| Fujitsu                              | 6        | 2.91%   |
| Lenovo                               | 5        | 2.43%   |
| AZW                                  | 4        | 1.94%   |
| YANYU                                | 3        | 1.46%   |
| Supermicro                           | 2        | 0.97%   |
| Pegatron                             | 2        | 0.97%   |
| NF692                                | 2        | 0.97%   |
| MW                                   | 2        | 0.97%   |
| IceWhale Technology                  | 2        | 0.97%   |
| Acer                                 | 2        | 0.97%   |
| YENTEK                               | 1        | 0.49%   |
| T-bao                                | 1        | 0.49%   |
| Sun Microsystems                     | 1        | 0.49%   |
| Stonesoft                            | 1        | 0.49%   |
| SJRC                                 | 1        | 0.49%   |
| ShenZhen MinWin Technology           | 1        | 0.49%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.49%   |
| Quantum engineering                  | 1        | 0.49%   |
| MACHINIST                            | 1        | 0.49%   |
| Lex                                  | 1        | 0.49%   |
| iEi                                  | 1        | 0.49%   |
| Huanan                               | 1        | 0.49%   |
| HARDKERNEL                           | 1        | 0.49%   |
| Fujitsu Siemens                      | 1        | 0.49%   |
| Foxconn                              | 1        | 0.49%   |
| BESSTAR Tech                         | 1        | 0.49%   |
| Apple                                | 1        | 0.49%   |
| ANGXUN                               | 1        | 0.49%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                              | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Unknown                                           | 35       | 16.99%  |
| PC Engines APU2                                   | 7        | 3.4%    |
| ASUS PRIME B650-PLUS                              | 4        | 1.94%   |
| Protectli VP2420                                  | 3        | 1.46%   |
| Fujitsu FUTRO S920                                | 3        | 1.46%   |
| ASUS PRIME H410M-A                                | 3        | 1.46%   |
| Protectli FW4B                                    | 2        | 0.97%   |
| PC Engines apu4                                   | 2        | 0.97%   |
| NF692 1.0                                         | 2        | 0.97%   |
| MW GMLK-2_5G4L                                    | 2        | 0.97%   |
| MSI MS-7D16                                       | 2        | 0.97%   |
| MSI MS-7B86                                       | 2        | 0.97%   |
| Lenovo ThinkCentre M83 10AHS35Q00                 | 2        | 0.97%   |
| Intel Q3XXG4-P V1.0                               | 2        | 0.97%   |
| Intel NCB-4210WG                                  | 2        | 0.97%   |
| HP t620 PLUS Quad Core TC                         | 2        | 0.97%   |
| Gigabyte X570 AORUS ELITE                         | 2        | 0.97%   |
| Gigabyte A520M S2H                                | 2        | 0.97%   |
| Dell OptiPlex 3020                                | 2        | 0.97%   |
| AZW U59                                           | 2        | 0.97%   |
| ASUS P8Z77-V LX                                   | 2        | 0.97%   |
| ASUS M4A88TD-V EVO/USB3                           | 2        | 0.97%   |
| ASUS IP4BL-ME                                     | 2        | 0.97%   |
| YENTEK D41SL                                      | 1        | 0.49%   |
| YANYU M9F baytrail                                | 1        | 0.49%   |
| YANYU ITX-M9F VER:1.3 baytrail                    | 1        | 0.49%   |
| YANYU H17SL                                       | 1        | 0.49%   |
| T-bao MINI PC                                     | 1        | 0.49%   |
| Supermicro X9SCI/X9SCA                            | 1        | 0.49%   |
| Supermicro X8STi                                  | 1        | 0.49%   |
| Sun Microsystems Ultra 24                         | 1        | 0.49%   |
| Stonesoft FW-315-C1                               | 1        | 0.49%   |
| SJRC ADLN-6L                                      | 1        | 0.49%   |
| ShenZhen MinWin MW-NANO-APL-4L                    | 1        | 0.49%   |
| Shenzhen Meigao Electronic Equipment Venus Series | 1        | 0.49%   |
| Quantum engineering HackBoard 2                   | 1        | 0.49%   |
| Protectli V1210                                   | 1        | 0.49%   |
| Pegatron Pro 3405 Series                          | 1        | 0.49%   |
| Pegatron KX629AA-ABZ a6561.it                     | 1        | 0.49%   |
| PC Engines APU3                                   | 1        | 0.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Unknown                        | 35       | 16.99%  |
| ASUS PRIME                     | 13       | 6.31%   |
| PC Engines APU2                | 7        | 3.4%    |
| Dell OptiPlex                  | 6        | 2.91%   |
| Lenovo ThinkCentre             | 5        | 2.43%   |
| HP Compaq                      | 5        | 2.43%   |
| Fujitsu FUTRO                  | 4        | 1.94%   |
| Protectli VP2420               | 3        | 1.46%   |
| HP ProDesk                     | 3        | 1.46%   |
| Gigabyte X570                  | 3        | 1.46%   |
| ASUS P8Z77-V                   | 3        | 1.46%   |
| Protectli FW4B                 | 2        | 0.97%   |
| PC Engines apu4                | 2        | 0.97%   |
| NF692 1.0                      | 2        | 0.97%   |
| MW GMLK-2                      | 2        | 0.97%   |
| MSI MS-7D16                    | 2        | 0.97%   |
| MSI MS-7B86                    | 2        | 0.97%   |
| Intel Q3XXG4-P                 | 2        | 0.97%   |
| Intel NCB-4210WG               | 2        | 0.97%   |
| IceWhale ZimaBoard             | 2        | 0.97%   |
| HP t620                        | 2        | 0.97%   |
| HP EliteDesk                   | 2        | 0.97%   |
| Gigabyte A520M                 | 2        | 0.97%   |
| Fujitsu ESPRIMO                | 2        | 0.97%   |
| Dell Precision                 | 2        | 0.97%   |
| Dell PowerEdge                 | 2        | 0.97%   |
| AZW U59                        | 2        | 0.97%   |
| ASUS M4A88TD-V                 | 2        | 0.97%   |
| ASUS IP4BL-ME                  | 2        | 0.97%   |
| YENTEK D41SL                   | 1        | 0.49%   |
| YANYU M9F                      | 1        | 0.49%   |
| YANYU ITX-M9F                  | 1        | 0.49%   |
| YANYU H17SL                    | 1        | 0.49%   |
| T-bao MINI                     | 1        | 0.49%   |
| Supermicro X9SCI               | 1        | 0.49%   |
| Supermicro X8STi               | 1        | 0.49%   |
| Sun Microsystems Ultra         | 1        | 0.49%   |
| Stonesoft FW-315-C1            | 1        | 0.49%   |
| SJRC ADLN-6L                   | 1        | 0.49%   |
| ShenZhen MinWin MW-NANO-APL-4L | 1        | 0.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2023    | 24       | 11.65%  |
| 2014    | 21       | 10.19%  |
| 2021    | 18       | 8.74%   |
| 2016    | 18       | 8.74%   |
| 2022    | 17       | 8.25%   |
| 2018    | 14       | 6.8%    |
| 2012    | 14       | 6.8%    |
| 2017    | 11       | 5.34%   |
| 2019    | 10       | 4.85%   |
| 2011    | 10       | 4.85%   |
| 2010    | 10       | 4.85%   |
| 2020    | 9        | 4.37%   |
| 2013    | 7        | 3.4%    |
| 2024    | 5        | 2.43%   |
| 2009    | 5        | 2.43%   |
| 2008    | 5        | 2.43%   |
| Unknown | 4        | 1.94%   |
| 2015    | 2        | 0.97%   |
| 2007    | 1        | 0.49%   |
| 2006    | 1        | 0.49%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 206      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 195      | 94.2%   |
| Yes  | 12       | 5.8%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 83       | 39.34%  |
| 4.01-8.0    | 45       | 21.33%  |
| 16.01-24.0  | 42       | 19.91%  |
| 32.01-64.0  | 17       | 8.06%   |
| 2.01-3.0    | 10       | 4.74%   |
| 64.01-256.0 | 6        | 2.84%   |
| 24.01-32.0  | 3        | 1.42%   |
| 0.51-1.0    | 3        | 1.42%   |
| 3.01-4.0    | 2        | 0.95%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 116      | 55.5%   |
| 0.51-1.0 | 66       | 31.58%  |
| 1.01-2.0 | 17       | 8.13%   |
| 4.01-8.0 | 4        | 1.91%   |
| Unknown  | 4        | 1.91%   |
| 2.01-3.0 | 2        | 0.96%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 135      | 63.38%  |
| 0      | 29       | 13.62%  |
| 2      | 25       | 11.74%  |
| 3      | 11       | 5.16%   |
| 4      | 9        | 4.23%   |
| 10     | 1        | 0.47%   |
| 7      | 1        | 0.47%   |
| 6      | 1        | 0.47%   |
| 5      | 1        | 0.47%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 159      | 77.18%  |
| Yes       | 47       | 22.82%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 203      | 98.54%  |
| No        | 3        | 1.46%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 172      | 83.09%  |
| Yes       | 35       | 16.91%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 183      | 87.98%  |
| Yes       | 25       | 12.02%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Italy   | 206      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Milan                 | 36       | 14.46%  |
| Rome                  | 23       | 9.24%   |
| Trieste               | 5        | 2.01%   |
| Bologna               | 5        | 2.01%   |
| Turin                 | 4        | 1.61%   |
| Naples                | 4        | 1.61%   |
| Monza                 | 4        | 1.61%   |
| Arezzo                | 4        | 1.61%   |
| Momo                  | 3        | 1.2%    |
| Genoa                 | 3        | 1.2%    |
| Bari                  | 3        | 1.2%    |
| Verona                | 2        | 0.8%    |
| Venice                | 2        | 0.8%    |
| Turrivalignani        | 2        | 0.8%    |
| Taviano               | 2        | 0.8%    |
| Silea                 | 2        | 0.8%    |
| San Giustino Valdarno | 2        | 0.8%    |
| San Giuliano Terme    | 2        | 0.8%    |
| Rosignano Marittimo   | 2        | 0.8%    |
| Rho                   | 2        | 0.8%    |
| Reggio Emilia         | 2        | 0.8%    |
| Reggio Calabria       | 2        | 0.8%    |
| Ponte San Pietro      | 2        | 0.8%    |
| Palermo               | 2        | 0.8%    |
| Oulx                  | 2        | 0.8%    |
| Modena                | 2        | 0.8%    |
| Milano                | 2        | 0.8%    |
| Lucca                 | 2        | 0.8%    |
| Lecco                 | 2        | 0.8%    |
| Florence              | 2        | 0.8%    |
| Ferrara               | 2        | 0.8%    |
| Desio                 | 2        | 0.8%    |
| Castelfranco Emilia   | 2        | 0.8%    |
| Besana in Brianza     | 2        | 0.8%    |
| Bergamo               | 2        | 0.8%    |
| Ancona                | 2        | 0.8%    |
| Vogogna               | 1        | 0.4%    |
| Viterbo               | 1        | 0.4%    |
| Villa Bartolomea      | 1        | 0.4%    |
| Vanzago               | 1        | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 32       | 40     | 13.17%  |
| WDC                 | 28       | 54     | 11.52%  |
| Seagate             | 26       | 44     | 10.7%   |
| Kingston            | 23       | 30     | 9.47%   |
| Crucial             | 21       | 37     | 8.64%   |
| Toshiba             | 16       | 34     | 6.58%   |
| Transcend           | 12       | 22     | 4.94%   |
| NVMe                | 8        | 8      | 3.29%   |
| SanDisk             | 7        | 8      | 2.88%   |
| China               | 7        | 17     | 2.88%   |
| Maxtor              | 4        | 4      | 1.65%   |
| Innodisk            | 4        | 6      | 1.65%   |
| Hoodisk             | 4        | 6      | 1.65%   |
| Emtec               | 4        | 7      | 1.65%   |
| Silicon Motion      | 3        | 4      | 1.23%   |
| OCZ                 | 3        | 3      | 1.23%   |
| Hitachi             | 3        | 3      | 1.23%   |
| SPCC                | 2        | 2      | 0.82%   |
| Protectli           | 2        | 2      | 0.82%   |
| PNY                 | 2        | 6      | 0.82%   |
| Phison              | 2        | 2      | 0.82%   |
| Pccooler            | 2        | 4      | 0.82%   |
| Micron Technology   | 2        | 2      | 0.82%   |
| LITEON              | 2        | 3      | 0.82%   |
| Intel               | 2        | 3      | 0.82%   |
| HGST                | 2        | 2      | 0.82%   |
| FORESEE             | 2        | 2      | 0.82%   |
| Dogfish             | 2        | 2      | 0.82%   |
| Corsair             | 2        | 2      | 0.82%   |
| BAITITON            | 2        | 2      | 0.82%   |
| A-DATA Technology   | 2        | 3      | 0.82%   |
| VICKTER             | 1        | 1      | 0.41%   |
| Verbatim            | 1        | 1      | 0.41%   |
| T-FORCE             | 1        | 1      | 0.41%   |
| SK hynix            | 1        | 1      | 0.41%   |
| S3+                 | 1        | 1      | 0.41%   |
| Patriot             | 1        | 1      | 0.41%   |
| KingSpec            | 1        | 2      | 0.41%   |
| Indilinx            | 1        | 1      | 0.41%   |
| Fanxiang            | 1        | 2      | 0.41%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Crucial CT240BX500SSD1 240GB    | 6        | 2.31%   |
| NVMe Samsung SSD 980 1TB        | 4        | 1.54%   |
| Kingston SA400S37120G 120GB     | 4        | 1.54%   |
| Crucial CT120BX500SSD1 120GB    | 4        | 1.54%   |
| Transcend TS128GMSA230S 128GB   | 3        | 1.15%   |
| Samsung SSD 870 EVO 250GB       | 3        | 1.15%   |
| Samsung SSD 860 EVO 250GB       | 3        | 1.15%   |
| Samsung SSD 850 EVO 250GB       | 3        | 1.15%   |
| Kingston SEDC500M480G 480GB     | 3        | 1.15%   |
| Emtec X150 120GB                | 3        | 1.15%   |
| Crucial CT500MX500SSD1 500GB    | 3        | 1.15%   |
| Crucial CT250MX500SSD1 250GB    | 3        | 1.15%   |
| WDC WD5000AAKS-22V1A0 500GB     | 2        | 0.77%   |
| Transcend TS64GMSA370 64GB      | 2        | 0.77%   |
| Transcend TS16GMSA370 16GB      | 2        | 0.77%   |
| Toshiba Q300 240GB              | 2        | 0.77%   |
| Toshiba HDWG440 4TB             | 2        | 0.77%   |
| Toshiba HDWD110 1TB             | 2        | 0.77%   |
| Toshiba DT01ACA050 500GB        | 2        | 0.77%   |
| Seagate ST500DM002-1BD142 500GB | 2        | 0.77%   |
| Seagate ST320LT007-9ZV142 320GB | 2        | 0.77%   |
| Seagate ST1000DM010-2EP102 1TB  | 2        | 0.77%   |
| Seagate ST1000DM003-1ER162 1TB  | 2        | 0.77%   |
| Seagate ST1000DM003-1CH162 1TB  | 2        | 0.77%   |
| SanDisk SDSSDP128G 128GB        | 2        | 0.77%   |
| Samsung SSD 990 PRO 1TB         | 2        | 0.77%   |
| Samsung HM321HI 320GB           | 2        | 0.77%   |
| Phison SATA SSD 16GB            | 2        | 0.77%   |
| Pccooler MSATA 128G             | 2        | 0.77%   |
| OCZ VERTEX3 120GB               | 2        | 0.77%   |
| NVMe Samsung SSD 990 2TB        | 2        | 0.77%   |
| Maxtor 6V080E0 80GB             | 2        | 0.77%   |
| Kingston SV300S37A120G 120GB    | 2        | 0.77%   |
| Kingston SUV500240G 240GB       | 2        | 0.77%   |
| Innodisk DEMSR- 16GB mSATA 3ME3 | 2        | 0.77%   |
| Hoodisk SSD 256GB               | 2        | 0.77%   |
| FORESEE 64GB SSD                | 2        | 0.77%   |
| Crucial CT500P2SSD8 500GB       | 2        | 0.77%   |
| BAITITON BT58SSD08M 128GB       | 2        | 0.77%   |
| WDC WDS250G2B0A-00SM50 250GB    | 1        | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 26       | 44     | 33.33%  |
| WDC                 | 24       | 49     | 30.77%  |
| Toshiba             | 14       | 27     | 17.95%  |
| Samsung Electronics | 4        | 4      | 5.13%   |
| Maxtor              | 4        | 4      | 5.13%   |
| Hitachi             | 3        | 3      | 3.85%   |
| HGST                | 2        | 2      | 2.56%   |
| NVMe                | 1        | 1      | 1.28%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 23       | 28     | 15.44%  |
| Kingston            | 19       | 25     | 12.75%  |
| Crucial             | 19       | 31     | 12.75%  |
| Transcend           | 12       | 22     | 8.05%   |
| SanDisk             | 7        | 8      | 4.7%    |
| NVMe                | 7        | 7      | 4.7%    |
| China               | 7        | 17     | 4.7%    |
| WDC                 | 4        | 4      | 2.68%   |
| Innodisk            | 4        | 6      | 2.68%   |
| Hoodisk             | 4        | 6      | 2.68%   |
| Emtec               | 4        | 7      | 2.68%   |
| OCZ                 | 3        | 3      | 2.01%   |
| Toshiba             | 2        | 7      | 1.34%   |
| SPCC                | 2        | 2      | 1.34%   |
| Protectli           | 2        | 2      | 1.34%   |
| PNY                 | 2        | 6      | 1.34%   |
| Phison              | 2        | 2      | 1.34%   |
| Pccooler            | 2        | 4      | 1.34%   |
| Micron Technology   | 2        | 2      | 1.34%   |
| LITEON              | 2        | 3      | 1.34%   |
| Intel               | 2        | 3      | 1.34%   |
| FORESEE             | 2        | 2      | 1.34%   |
| Dogfish             | 2        | 2      | 1.34%   |
| Corsair             | 2        | 2      | 1.34%   |
| BAITITON            | 2        | 2      | 1.34%   |
| A-DATA Technology   | 2        | 3      | 1.34%   |
| VICKTER             | 1        | 1      | 0.67%   |
| Verbatim            | 1        | 1      | 0.67%   |
| T-FORCE             | 1        | 1      | 0.67%   |
| SK hynix            | 1        | 1      | 0.67%   |
| S3+                 | 1        | 1      | 0.67%   |
| Patriot             | 1        | 1      | 0.67%   |
| KingSpec            | 1        | 2      | 0.67%   |
| Indilinx            | 1        | 1      | 0.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 128      | 215    | 62.44%  |
| HDD  | 59       | 134    | 28.78%  |
| NVMe | 18       | 27     | 8.78%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 168      | 349    | 90.32%  |
| NVMe | 18       | 27     | 9.68%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 143      | 265    | 72.96%  |
| 0.51-1.0   | 31       | 41     | 15.82%  |
| 1.01-2.0   | 11       | 15     | 5.61%   |
| 3.01-4.0   | 7        | 15     | 3.57%   |
| 4.01-10.0  | 3        | 10     | 1.53%   |
| 2.01-3.0   | 1        | 3      | 0.51%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 78       | 36.11%  |
| 1-20           | 42       | 19.44%  |
| 251-500        | 39       | 18.06%  |
| 51-100         | 19       | 8.8%    |
| 501-1000       | 16       | 7.41%   |
| 21-50          | 15       | 6.94%   |
| More than 3000 | 4        | 1.85%   |
| 1001-2000      | 2        | 0.93%   |
| Unknown        | 1        | 0.46%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 192      | 89.72%  |
| 21-50          | 11       | 5.14%   |
| 51-100         | 4        | 1.87%   |
| 101-250        | 2        | 0.93%   |
| 501-1000       | 2        | 0.93%   |
| More than 3000 | 1        | 0.47%   |
| 1001-2000      | 1        | 0.47%   |
| Unknown        | 1        | 0.47%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                   | Desktops | Drives | Percent |
|-----------------------------------------|----------|--------|---------|
| WDC WD5000AAKS-22V1A0 500GB             | 2        | 2      | 6.25%   |
| Seagate ST320LT007-9ZV142 320GB         | 2        | 2      | 6.25%   |
| OCZ VERTEX3 120GB                       | 2        | 2      | 6.25%   |
| WDC WD800JD-75MSA3 80GB                 | 1        | 1      | 3.13%   |
| WDC WD5000AAKS-00E4A0 500GB             | 1        | 1      | 3.13%   |
| WDC WD20EVDS-63T3B0 2TB                 | 1        | 1      | 3.13%   |
| WDC WD2002FYPS-01U1B1 2TB               | 1        | 1      | 3.13%   |
| WDC WD10EZEX-60M2NA0 1TB                | 1        | 1      | 3.13%   |
| WDC WD1000DHTZ-04N21V1 1TB              | 1        | 2      | 3.13%   |
| Transcend TS128GMSA230S 128GB           | 1        | 2      | 3.13%   |
| SK hynix SC313 HFS256G32TNF-N3A0A 256GB | 1        | 1      | 3.13%   |
| Seagate ST9500325AS 500GB               | 1        | 1      | 3.13%   |
| Seagate ST500LM021-1KJ152 500GB         | 1        | 1      | 3.13%   |
| Seagate ST500DM002-1BD142 500GB         | 1        | 7      | 3.13%   |
| Seagate ST4000LM024-2AN17V 4TB          | 1        | 1      | 3.13%   |
| Seagate ST31500341AS 1.5TB              | 1        | 1      | 3.13%   |
| Seagate ST31000524AS 1TB                | 1        | 1      | 3.13%   |
| Samsung Electronics HM501II 500GB       | 1        | 1      | 3.13%   |
| Samsung Electronics HM321HI 320GB       | 1        | 1      | 3.13%   |
| Maxtor 6V080E0 80GB                     | 1        | 1      | 3.13%   |
| Maxtor 6E040L0 40GB                     | 1        | 1      | 3.13%   |
| LITEON CV8-8E128-HP 128GB               | 1        | 2      | 3.13%   |
| Kingston SV300S37A120G 120GB            | 1        | 1      | 3.13%   |
| HGST HTS725050A7E630 500GB              | 1        | 1      | 3.13%   |
| HGST HTS541075A9E680 752GB              | 1        | 1      | 3.13%   |
| Corsair Force GS 180GB                  | 1        | 1      | 3.13%   |
| China SH00R120GB                        | 1        | 1      | 3.13%   |
| BAITITON BT58SSD08M 128GB               | 1        | 1      | 3.13%   |
| A-DATA Technology SX300 128GB           | 1        | 1      | 3.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 9      | 25%     |
| Seagate             | 8        | 14     | 25%     |
| Samsung Electronics | 2        | 2      | 6.25%   |
| OCZ                 | 2        | 2      | 6.25%   |
| Maxtor              | 2        | 2      | 6.25%   |
| HGST                | 2        | 2      | 6.25%   |
| Transcend           | 1        | 2      | 3.13%   |
| SK hynix            | 1        | 1      | 3.13%   |
| LITEON              | 1        | 2      | 3.13%   |
| Kingston            | 1        | 1      | 3.13%   |
| Corsair             | 1        | 1      | 3.13%   |
| China               | 1        | 1      | 3.13%   |
| BAITITON            | 1        | 1      | 3.13%   |
| A-DATA Technology   | 1        | 1      | 3.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 9      | 36.36%  |
| Seagate             | 8        | 14     | 36.36%  |
| Samsung Electronics | 2        | 2      | 9.09%   |
| Maxtor              | 2        | 2      | 9.09%   |
| HGST                | 2        | 2      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 20       | 29     | 68.97%  |
| SSD  | 9        | 12     | 31.03%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Crucial CT500P3SSD8 500GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Crucial | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 151      | 309    | 77.04%  |
| Malfunc  | 29       | 41     | 14.8%   |
| Detected | 15       | 25     | 7.65%   |
| Failed   | 1        | 1      | 0.51%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 150      | 58.14%  |
| AMD                              | 48       | 18.6%   |
| Samsung Electronics              | 13       | 5.04%   |
| ASMedia Technology               | 6        | 2.33%   |
| Marvell Technology Group         | 5        | 1.94%   |
| Phison Electronics               | 4        | 1.55%   |
| Micron/Crucial Technology        | 4        | 1.55%   |
| MAXIO Technology (Hangzhou)      | 4        | 1.55%   |
| Kingston Technology Company      | 4        | 1.55%   |
| Silicon Motion                   | 3        | 1.16%   |
| VIA Technologies                 | 2        | 0.78%   |
| Broadcom / LSI                   | 2        | 0.78%   |
| ULi Electronics                  | 1        | 0.39%   |
| TenaFe                           | 1        | 0.39%   |
| Silicon Integrated Systems [SiS] | 1        | 0.39%   |
| Silicon Image                    | 1        | 0.39%   |
| Shenzhen Longsys Electronics     | 1        | 0.39%   |
| SanDisk                          | 1        | 0.39%   |
| Realtek Semiconductor            | 1        | 0.39%   |
| KIOXIA                           | 1        | 0.39%   |
| JMicron Technology               | 1        | 0.39%   |
| Integrated Technology Express    | 1        | 0.39%   |
| Hosin Global Electronics         | 1        | 0.39%   |
| Adaptec                          | 1        | 0.39%   |
| Unknown                          | 1        | 0.39%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 25       | 8.68%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 13       | 4.51%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 13       | 4.51%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 13       | 4.51%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 9        | 3.13%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 8        | 2.78%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 7        | 2.43%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 7        | 2.43%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 7        | 2.43%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 7        | 2.43%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 6        | 2.08%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 6        | 2.08%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 6        | 2.08%   |
| Intel Elkhart Lake SATA AHCI                                                     | 5        | 1.74%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                    | 5        | 1.74%   |
| AMD 600 Series Chipset SATA Controller                                           | 5        | 1.74%   |
| AMD 500 Series Chipset SATA Controller                                           | 5        | 1.74%   |
| AMD 400 Series Chipset SATA Controller                                           | 5        | 1.74%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                      | 4        | 1.39%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 4        | 1.39%   |
| Intel SATA Controller [RAID mode]                                                | 4        | 1.39%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 4        | 1.39%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4        | 1.39%   |
| Intel Alder Lake-P SATA AHCI Controller                                          | 4        | 1.39%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 4        | 1.39%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 4        | 1.39%   |
| AMD FCH SATA Controller [IDE mode]                                               | 4        | 1.39%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 3        | 1.04%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3        | 1.04%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 3        | 1.04%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                         | 3        | 1.04%   |
| Intel Alder Lake-N SATA AHCI Controller                                          | 3        | 1.04%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 3        | 1.04%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 3        | 1.04%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3        | 1.04%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 3        | 1.04%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 3        | 1.04%   |
| VIA VT6415 PATA IDE Host Controller                                              | 2        | 0.69%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                 | 2        | 0.69%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 2        | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 171      | 68.13%  |
| NVMe | 39       | 15.54%  |
| IDE  | 29       | 11.55%  |
| RAID | 8        | 3.19%   |
| SCSI | 3        | 1.2%    |
| SAS  | 1        | 0.4%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Intel           | 155      | 74.88%  |
| AMD             | 48       | 23.19%  |
| SUNW,UltraAX-i2 | 1        | 0.48%   |
| Arm             | 1        | 0.48%   |
| 11th            | 1        | 0.48%   |
| Unknown         | 1        | 0.48%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD GX-412TC SOC                                | 10       | 4.81%   |
| Intel Celeron J4125 CPU @ 2.00GHz               | 8        | 3.85%   |
| Intel Celeron N5105 @ 2.00GHz                   | 7        | 3.37%   |
| Intel Celeron CPU J1900 @ 1.99GHz               | 6        | 2.88%   |
| Intel N100                                      | 5        | 2.4%    |
| Intel Celeron J6412 @ 2.00GHz                   | 4        | 1.92%   |
| Intel Pentium Gold 8505                         | 3        | 1.44%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 3        | 1.44%   |
| Intel Core i5-3470S CPU @ 2.90GHz               | 3        | 1.44%   |
| Intel Core i3-10100F CPU @ 3.60GHz              | 3        | 1.44%   |
| Intel Celeron CPU J3455 @ 1.50GHz               | 3        | 1.44%   |
| AMD Phenom II X4 965 Processor                  | 3        | 1.44%   |
| AMD GX-415GA SOC with Radeon HD Graphics        | 3        | 1.44%   |
| Intel Pentium Silver J5040 CPU @ 2.00GHz        | 2        | 0.96%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz          | 2        | 0.96%   |
| Intel Pentium CPU G3220 @ 3.00GHz               | 2        | 0.96%   |
| Intel Core i7-7700 CPU @ 3.60GHz                | 2        | 0.96%   |
| Intel Core i5-6500 CPU @ 3.20GHz                | 2        | 0.96%   |
| Intel Core i3-4170 CPU @ 3.70GHz                | 2        | 0.96%   |
| Intel Core i3-4160 CPU @ 3.60GHz                | 2        | 0.96%   |
| Intel Celeron CPU N3450 @ 1.10GHz               | 2        | 0.96%   |
| Intel Celeron CPU J3355 @ 2.00GHz               | 2        | 0.96%   |
| Intel Celeron CPU J3160 @ 1.60GHz               | 2        | 0.96%   |
| Intel Atom CPU D525 @ 1.80GHz                   | 2        | 0.96%   |
| AMD Ryzen 9 7950X 16-Core Processor             | 2        | 0.96%   |
| AMD Ryzen 9 5950X 16-Core Processor             | 2        | 0.96%   |
| AMD Ryzen 5 5600G with Radeon Graphics          | 2        | 0.96%   |
| AMD Ryzen 5 2600 Six-Core Processor             | 2        | 0.96%   |
| AMD GX-420CA SOC with Radeon HD Graphics        | 2        | 0.96%   |
| SUNW,UltraAX-i2 (SUNW,UltraSPARC-IIe @ 500 MHz) | 1        | 0.48%   |
| Intel Xeon E-2236 CPU @ 3.40GHz                 | 1        | 0.48%   |
| Intel Xeon CPU X5650 @ 2.67GHz                  | 1        | 0.48%   |
| Intel Xeon CPU X3470 @ 2.93GHz                  | 1        | 0.48%   |
| Intel Xeon CPU W3680 @ 3.33GHz                  | 1        | 0.48%   |
| Intel Xeon CPU W3520 @ 2.67GHz                  | 1        | 0.48%   |
| Intel Xeon CPU E5440 @ 2.83GHz                  | 1        | 0.48%   |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz             | 1        | 0.48%   |
| Intel Xeon CPU E5-2650L v2 @ 1.70GHz            | 1        | 0.48%   |
| Intel Xeon CPU E5-2640 v4 @ 2.40GHz             | 1        | 0.48%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz             | 1        | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Celeron           | 47       | 22.6%   |
| Intel Core i5           | 24       | 11.54%  |
| Intel Xeon              | 17       | 8.17%   |
| AMD GX                  | 17       | 8.17%   |
| Intel Core i3           | 16       | 7.69%   |
| Other                   | 12       | 5.77%   |
| Intel Core i7           | 12       | 5.77%   |
| AMD Ryzen 5             | 8        | 3.85%   |
| Intel Pentium           | 7        | 3.37%   |
| Intel Atom              | 7        | 3.37%   |
| AMD Ryzen 7             | 7        | 3.37%   |
| AMD Ryzen 9             | 6        | 2.88%   |
| Intel Pentium Gold      | 3        | 1.44%   |
| Intel Pentium Dual-Core | 3        | 1.44%   |
| Intel Pentium Dual      | 3        | 1.44%   |
| Intel Core 2 Duo        | 3        | 1.44%   |
| AMD Phenom II X4        | 3        | 1.44%   |
| Intel Pentium Silver    | 2        | 0.96%   |
| Intel Core 2 Quad       | 2        | 0.96%   |
| Intel Pentium 4         | 1        | 0.48%   |
| Intel Core 2 Extreme    | 1        | 0.48%   |
| AMD Ryzen 3             | 1        | 0.48%   |
| AMD G                   | 1        | 0.48%   |
| AMD FX                  | 1        | 0.48%   |
| AMD E2                  | 1        | 0.48%   |
| AMD Athlon II X4        | 1        | 0.48%   |
| AMD Athlon 64 X2        | 1        | 0.48%   |
| AMD A4                  | 1        | 0.48%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 109      | 52.15%  |
| 2       | 45       | 21.53%  |
| 16      | 11       | 5.26%   |
| Unknown | 11       | 5.26%   |
| 12      | 8        | 3.83%   |
| 8       | 7        | 3.35%   |
| 6       | 7        | 3.35%   |
| 32      | 3        | 1.44%   |
| 1       | 3        | 1.44%   |
| 10      | 2        | 0.96%   |
| 3       | 2        | 0.96%   |
| 24      | 1        | 0.48%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 199      | 96.6%   |
| Unknown | 5        | 2.43%   |
| 2       | 2        | 0.97%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 144      | 68.9%   |
| 2       | 54       | 25.84%  |
| Unknown | 11       | 5.26%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Unknown       | 33       | 15.87%  |
| Haswell       | 16       | 7.69%   |
| KabyLake      | 15       | 7.21%   |
| Goldmont plus | 13       | 6.25%   |
| SandyBridge   | 12       | 5.77%   |
| Puma          | 12       | 5.77%   |
| IvyBridge     | 12       | 5.77%   |
| Silvermont    | 11       | 5.29%   |
| Zen 3         | 9        | 4.33%   |
| Penryn        | 9        | 4.33%   |
| Skylake       | 8        | 3.85%   |
| Goldmont      | 7        | 3.37%   |
| Bonnell       | 7        | 3.37%   |
| CometLake     | 6        | 2.88%   |
| Jaguar        | 5        | 2.4%    |
| Zen 2         | 4        | 1.92%   |
| K10           | 4        | 1.92%   |
| Core          | 4        | 1.92%   |
| Zen+          | 3        | 1.44%   |
| Westmere      | 3        | 1.44%   |
| Nehalem       | 3        | 1.44%   |
| Broadwell     | 3        | 1.44%   |
| K10 Llano     | 2        | 0.96%   |
| Zen           | 1        | 0.48%   |
| TigerLake     | 1        | 0.48%   |
| Piledriver    | 1        | 0.48%   |
| NetBurst      | 1        | 0.48%   |
| K8 Hammer     | 1        | 0.48%   |
| IceLake       | 1        | 0.48%   |
| Bobcat        | 1        | 0.48%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 118      | 60.51%  |
| AMD                              | 46       | 23.59%  |
| Nvidia                           | 25       | 12.82%  |
| Matrox Electronics Systems       | 3        | 1.54%   |
| ASPEED Technology                | 2        | 1.03%   |
| Silicon Integrated Systems [SiS] | 1        | 0.51%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel GeminiLake [UHD Graphics 600]                                                      | 11       | 5.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8        | 4%      |
| Intel JasperLake [UHD Graphics]                                                          | 8        | 4%      |
| Intel HD Graphics 500                                                                    | 7        | 3.5%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7        | 3.5%    |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 7        | 3.5%    |
| Intel Alder Lake-N [UHD Graphics]                                                        | 6        | 3%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6        | 3%      |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5        | 2.5%    |
| Intel Elkhart Lake [UHD Graphics Gen11 16EU]                                             | 5        | 2.5%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 5        | 2.5%    |
| Intel HD Graphics 620                                                                    | 4        | 2%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4        | 2%      |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4        | 2%      |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 4        | 2%      |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4        | 2%      |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4        | 2%      |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4        | 2%      |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 3        | 1.5%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 3        | 1.5%    |
| Intel HD Graphics 630                                                                    | 3        | 1.5%    |
| Intel HD Graphics 530                                                                    | 3        | 1.5%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3        | 1.5%    |
| Intel Alder Lake-UP3 GT1 [UHD Graphics]                                                  | 3        | 1.5%    |
| AMD Raphael                                                                              | 3        | 1.5%    |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                               | 3        | 1.5%    |
| AMD Kabini [Radeon HD 8330E]                                                             | 3        | 1.5%    |
| Nvidia GT218 [GeForce 210]                                                               | 2        | 1%      |
| Nvidia GK208B [GeForce GT 710]                                                           | 2        | 1%      |
| Nvidia GF119 [GeForce GT 520]                                                            | 2        | 1%      |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 2        | 1%      |
| Intel HD Graphics 610                                                                    | 2        | 1%      |
| Intel Haswell-ULT Integrated Graphics Controller [HD Graphics]                           | 2        | 1%      |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2        | 1%      |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 1%      |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 2        | 1%      |
| ASPEED Technology ASPEED Graphics Family                                                 | 2        | 1%      |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2        | 1%      |
| AMD Kabini [Radeon HD 8400E]                                                             | 2        | 1%      |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 2        | 1%      |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 112      | 53.85%  |
| 1 x AMD        | 40       | 19.23%  |
| 1 x Nvidia     | 21       | 10.1%   |
| Other          | 17       | 8.17%   |
| 2 x Intel      | 5        | 2.4%    |
| 2 x AMD        | 3        | 1.44%   |
| 1 x Matrox     | 3        | 1.44%   |
| AMD + Nvidia   | 3        | 1.44%   |
| 1 x ASPEED     | 2        | 0.96%   |
| 1 x SiS        | 1        | 0.48%   |
| Intel + Nvidia | 1        | 0.48%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 172      | 82.69%  |
| Unknown     | 19       | 9.13%   |
| Proprietary | 17       | 8.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 176      | 84.62%  |
| 1.01-2.0   | 7        | 3.37%   |
| 3.01-4.0   | 6        | 2.88%   |
| 0.01-0.5   | 6        | 2.88%   |
| 0.51-1.0   | 5        | 2.4%    |
| 5.01-6.0   | 4        | 1.92%   |
| 7.01-8.0   | 3        | 1.44%   |
| 8.01-16.0  | 1        | 0.48%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Philips              | 19       | 31.15%  |
| Samsung Electronics  | 11       | 18.03%  |
| Hewlett-Packard      | 7        | 11.48%  |
| Dell                 | 4        | 6.56%   |
| Acer                 | 4        | 6.56%   |
| Goldstar             | 3        | 4.92%   |
| Iiyama               | 2        | 3.28%   |
| Ancor Communications | 2        | 3.28%   |
| Sony                 | 1        | 1.64%   |
| Packard Bell         | 1        | 1.64%   |
| Orion                | 1        | 1.64%   |
| MSI                  | 1        | 1.64%   |
| Mi                   | 1        | 1.64%   |
| LG Electronics       | 1        | 1.64%   |
| Eizo                 | 1        | 1.64%   |
| ASUSTek Computer     | 1        | 1.64%   |
| Apple                | 1        | 1.64%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                 | 15       | 24.59%  |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                      | 3        | 4.92%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch     | 2        | 3.28%   |
| Hewlett-Packard 32 Display HPN351A 1920x1080 700x390mm 31.5-inch      | 2        | 3.28%   |
| Hewlett-Packard 27w HPN3494 1920x1080 600x340mm 27.2-inch             | 2        | 3.28%   |
| Sony TV SNY5D01 1360x768                                              | 1        | 1.64%   |
| Samsung Electronics T24D390 SAM0B6E 1920x1080 520x290mm 23.4-inch     | 1        | 1.64%   |
| Samsung Electronics SyncMaster SAM05B0 1920x1080                      | 1        | 1.64%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 530x300mm 24.0-inch     | 1        | 1.64%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch     | 1        | 1.64%   |
| Samsung Electronics LCD Monitor SAM4A75 1024x768 300x230mm 14.9-inch  | 1        | 1.64%   |
| Samsung Electronics LCD Monitor B2430L 1920x1080                      | 1        | 1.64%   |
| Philips PHL 328E9Q PHLC180 1920x1080 700x390mm 31.5-inch              | 1        | 1.64%   |
| Philips PHL 278B1 PHL0949 3840x2160 600x340mm 27.2-inch               | 1        | 1.64%   |
| Philips 22PFL3404D PHLD05D 1920x1080 640x360mm 28.9-inch              | 1        | 1.64%   |
| Philips 170S PHL082B 1280x1024 340x270mm 17.1-inch                    | 1        | 1.64%   |
| Packard Bell Viseo 193 Ws PKB008C 1440x900 410x260mm 19.1-inch        | 1        | 1.64%   |
| Orion LCD Monitor ORN1207 1920x1080                                   | 1        | 1.64%   |
| MSI G272QPF MSI3CD3 2560x1440 600x340mm 27.2-inch                     | 1        | 1.64%   |
| Mi 27 NFGL XMIB004 1920x1080 600x330mm 27.0-inch                      | 1        | 1.64%   |
| LG Electronics LCD Monitor E2360 1920x1080                            | 1        | 1.64%   |
| Iiyama PLE2403WS IVM5604 1920x1200 520x330mm 24.2-inch                | 1        | 1.64%   |
| Iiyama PL2792Q IVM6630 2560x1440 600x340mm 27.2-inch                  | 1        | 1.64%   |
| Hewlett-Packard 27o HPN342C 1920x1080 600x340mm 27.2-inch             | 1        | 1.64%   |
| Hewlett-Packard 27f HPN354A 1920x1080 600x340mm 27.2-inch             | 1        | 1.64%   |
| Hewlett-Packard 22cw HWP3183 1920x1080 480x270mm 21.7-inch            | 1        | 1.64%   |
| Goldstar W2261 GSM56CF 1920x1080 530x300mm 24.0-inch                  | 1        | 1.64%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 580x240mm 24.7-inch           | 1        | 1.64%   |
| Goldstar 2D FHD LG TV GSM59C4 1920x1080 510x290mm 23.1-inch           | 1        | 1.64%   |
| Eizo LCD Monitor S1901 1280x1024                                      | 1        | 1.64%   |
| Dell U4021QW DEL4206 2560x1080 930x390mm 39.7-inch                    | 1        | 1.64%   |
| Dell S2309W DELA041 1920x1080 510x290mm 23.1-inch                     | 1        | 1.64%   |
| Dell P2419H DELD0D9 1920x1080 530x300mm 24.0-inch                     | 1        | 1.64%   |
| Dell E198FP DELA028 1280x1024 380x300mm 19.1-inch                     | 1        | 1.64%   |
| ASUSTek Computer VA24E AUS24D1 1920x1080 530x300mm 24.0-inch          | 1        | 1.64%   |
| Apple Cinema HD APP9223 1920x1200 490x310mm 22.8-inch                 | 1        | 1.64%   |
| Ancor Communications VH226 ACI22F2 1920x1080 480x270mm 21.7-inch      | 1        | 1.64%   |
| Ancor Communications ASUS MX239 ACI23C2 1920x1080 530x310mm 24.2-inch | 1        | 1.64%   |
| Acer X203H ACR0097 1600x900 440x250mm 19.9-inch                       | 1        | 1.64%   |
| Acer RT240Y ACR0539 1920x1080 530x300mm 24.0-inch                     | 1        | 1.64%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 41       | 70.69%  |
| 1280x1024 (SXGA)  | 4        | 6.9%    |
| 3840x2160 (4K)    | 3        | 5.17%   |
| 2560x1440 (QHD)   | 2        | 3.45%   |
| 2560x1080         | 2        | 3.45%   |
| 1920x1200 (WUXGA) | 2        | 3.45%   |
| 1600x900 (HD+)    | 1        | 1.72%   |
| 1440x900 (WXGA+)  | 1        | 1.72%   |
| 1360x768          | 1        | 1.72%   |
| 1024x768 (XGA)    | 1        | 1.72%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 18       | 29.51%  |
| 27      | 11       | 18.03%  |
| Unknown | 9        | 14.75%  |
| 24      | 7        | 11.48%  |
| 19      | 4        | 6.56%   |
| 31      | 3        | 4.92%   |
| 23      | 3        | 4.92%   |
| 39      | 1        | 1.64%   |
| 34      | 1        | 1.64%   |
| 28      | 1        | 1.64%   |
| 22      | 1        | 1.64%   |
| 17      | 1        | 1.64%   |
| 14      | 1        | 1.64%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 20       | 33.9%   |
| 501-600     | 18       | 30.51%  |
| Unknown     | 9        | 15.25%  |
| 601-700     | 6        | 10.17%  |
| 351-400     | 2        | 3.39%   |
| 701-800     | 1        | 1.69%   |
| 301-350     | 1        | 1.69%   |
| 201-300     | 1        | 1.69%   |
| 901-1000    | 1        | 1.69%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 45       | 78.95%  |
| 5/4     | 3        | 5.26%   |
| 16/10   | 3        | 5.26%   |
| Unknown | 3        | 5.26%   |
| 21/9    | 2        | 3.51%   |
| 4/3     | 1        | 1.75%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 25       | 42.37%  |
| 301-350        | 11       | 18.64%  |
| Unknown        | 9        | 15.25%  |
| 351-500        | 5        | 8.47%   |
| 151-200        | 4        | 6.78%   |
| 251-300        | 2        | 3.39%   |
| 141-150        | 1        | 1.69%   |
| 101-110        | 1        | 1.69%   |
| 501-1000       | 1        | 1.69%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 27       | 45.76%  |
| 101-120 | 20       | 33.9%   |
| Unknown | 9        | 15.25%  |
| 121-160 | 2        | 3.39%   |
| 161-240 | 1        | 1.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 144      | 69.23%  |
| 1     | 62       | 29.81%  |
| 2     | 2        | 0.96%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 137      | 50.55%  |
| Realtek Semiconductor  | 96       | 35.42%  |
| Broadcom               | 11       | 4.06%   |
| Qualcomm Atheros       | 9        | 3.32%   |
| MediaTek               | 3        | 1.11%   |
| Ralink                 | 2        | 0.74%   |
| Davicom Semiconductor  | 2        | 0.74%   |
| D-Link System          | 2        | 0.74%   |
| T & A Mobile Phones    | 1        | 0.37%   |
| Sitecom Europe         | 1        | 0.37%   |
| Ralink Technology      | 1        | 0.37%   |
| National Semiconductor | 1        | 0.37%   |
| Mellanox Technologies  | 1        | 0.37%   |
| IMC Networks           | 1        | 0.37%   |
| Google                 | 1        | 0.37%   |
| Digital Equipment      | 1        | 0.37%   |
| Aquantia               | 1        | 0.37%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 81       | 25.88%  |
| Intel I211 Gigabit Network Connection                                         | 28       | 8.95%   |
| Intel Ethernet Controller I226-V                                              | 20       | 6.39%   |
| Intel I210 Gigabit Network Connection                                         | 11       | 3.51%   |
| Intel Ethernet Controller I225-V                                              | 10       | 3.19%   |
| Intel 82574L Gigabit Network Connection                                       | 10       | 3.19%   |
| Realtek RTL8125 2.5GbE Controller                                             | 7        | 2.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 7        | 2.24%   |
| Intel 82583V Gigabit Network Connection                                       | 6        | 1.92%   |
| Intel Ethernet Connection I217-LM                                             | 5        | 1.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 4        | 1.28%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 4        | 1.28%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4        | 1.28%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 4        | 1.28%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 3        | 0.96%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 3        | 0.96%   |
| Intel Wireless 3165                                                           | 3        | 0.96%   |
| Intel I350 Gigabit Network Connection                                         | 3        | 0.96%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 3        | 0.96%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3        | 0.96%   |
| Intel 82580 Gigabit Network Connection                                        | 3        | 0.96%   |
| Intel 82579V Gigabit Network Connection                                       | 3        | 0.96%   |
| Intel 82576 Gigabit Network Connection                                        | 3        | 0.96%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 3        | 0.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2        | 0.64%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 2        | 0.64%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 2        | 0.64%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 2        | 0.64%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 0.64%   |
| Intel Ethernet Connection (2) I219-V                                          | 2        | 0.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 2        | 0.64%   |
| Intel DH8900CC Null Device                                                    | 2        | 0.64%   |
| Intel 82575EB Gigabit Network Connection                                      | 2        | 0.64%   |
| Davicom DM9102 Fast Ethernet Controller                                       | 2        | 0.64%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                       | 2        | 0.64%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 2        | 0.64%   |
| T & A Mobile Phones ALCATEL RNDIS Interface                                   | 1        | 0.32%   |
| Sitecom Europe 802.11n WLAN Adapter                                           | 1        | 0.32%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.32%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.32%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 13       | 35.14%  |
| Qualcomm Atheros      | 9        | 24.32%  |
| Realtek Semiconductor | 7        | 18.92%  |
| Ralink                | 2        | 5.41%   |
| MediaTek              | 2        | 5.41%   |
| Sitecom Europe        | 1        | 2.7%    |
| Ralink Technology     | 1        | 2.7%    |
| IMC Networks          | 1        | 2.7%    |
| Broadcom              | 1        | 2.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 4        | 9.76%   |
| Intel Wireless 3165                                                                   | 3        | 7.32%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 2        | 4.88%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 2        | 4.88%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 2        | 4.88%   |
| Intel Tiger Lake PCH CNVi WiFi                                                        | 2        | 4.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 2        | 4.88%   |
| Sitecom Europe 802.11n WLAN Adapter                                                   | 1        | 2.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 1        | 2.44%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                              | 1        | 2.44%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 1        | 2.44%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 1        | 2.44%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1        | 2.44%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1        | 2.44%   |
| Realtek Bluetooth Adapter                                                             | 1        | 2.44%   |
| Ralink MT7601U Wireless Adapter                                                       | 1        | 2.44%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                | 1        | 2.44%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 1        | 2.44%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter                       | 1        | 2.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 1        | 2.44%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1        | 2.44%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                         | 1        | 2.44%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                               | 1        | 2.44%   |
| Intel Wi-Fi 6 AX200                                                                   | 1        | 2.44%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                               | 1        | 2.44%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                         | 1        | 2.44%   |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 1        | 2.44%   |
| Intel CNVi: Wi-Fi                                                                     | 1        | 2.44%   |
| Intel Centrino Advanced-N 6235                                                        | 1        | 2.44%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                                  | 1        | 2.44%   |
| Broadcom BCM43228 802.11a/b/g/n                                                       | 1        | 2.44%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 129      | 53.53%  |
| Realtek Semiconductor  | 93       | 38.59%  |
| Broadcom               | 10       | 4.15%   |
| Davicom Semiconductor  | 2        | 0.83%   |
| D-Link System          | 2        | 0.83%   |
| T & A Mobile Phones    | 1        | 0.41%   |
| National Semiconductor | 1        | 0.41%   |
| MediaTek               | 1        | 0.41%   |
| Digital Equipment      | 1        | 0.41%   |
| Aquantia               | 1        | 0.41%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 81       | 30.22%  |
| Intel I211 Gigabit Network Connection                                         | 28       | 10.45%  |
| Intel Ethernet Controller I226-V                                              | 20       | 7.46%   |
| Intel I210 Gigabit Network Connection                                         | 11       | 4.1%    |
| Intel Ethernet Controller I225-V                                              | 10       | 3.73%   |
| Intel 82574L Gigabit Network Connection                                       | 10       | 3.73%   |
| Realtek RTL8125 2.5GbE Controller                                             | 7        | 2.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 7        | 2.61%   |
| Intel 82583V Gigabit Network Connection                                       | 6        | 2.24%   |
| Intel Ethernet Connection I217-LM                                             | 5        | 1.87%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 4        | 1.49%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4        | 1.49%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 4        | 1.49%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 3        | 1.12%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 3        | 1.12%   |
| Intel I350 Gigabit Network Connection                                         | 3        | 1.12%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 3        | 1.12%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3        | 1.12%   |
| Intel 82580 Gigabit Network Connection                                        | 3        | 1.12%   |
| Intel 82579V Gigabit Network Connection                                       | 3        | 1.12%   |
| Intel 82576 Gigabit Network Connection                                        | 3        | 1.12%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 3        | 1.12%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 0.75%   |
| Intel Ethernet Connection (2) I219-V                                          | 2        | 0.75%   |
| Intel 82575EB Gigabit Network Connection                                      | 2        | 0.75%   |
| Davicom DM9102 Fast Ethernet Controller                                       | 2        | 0.75%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                       | 2        | 0.75%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 2        | 0.75%   |
| T & A Mobile Phones ALCATEL RNDIS Interface                                   | 1        | 0.37%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.37%   |
| Realtek Killer E3000 2.5GbE Controller                                        | 1        | 0.37%   |
| National DP83815 (MacPhyter) Ethernet Controller                              | 1        | 0.37%   |
| MediaTek USB Ethernet-RNDIS                                                   | 1        | 0.37%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 1        | 0.37%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 1        | 0.37%   |
| Intel Ethernet Controller I226-LM                                             | 1        | 0.37%   |
| Intel Ethernet Controller I225-LM                                             | 1        | 0.37%   |
| Intel Ethernet Connection I217-V                                              | 1        | 0.37%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1        | 0.37%   |
| Intel Ethernet Connection (5) I219-LM                                         | 1        | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 203      | 83.88%  |
| WiFi     | 35       | 14.46%  |
| Unknown  | 4        | 1.65%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 199      | 96.14%  |
| WiFi     | 8        | 3.86%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 62       | 29.67%  |
| 2     | 39       | 18.66%  |
| 4     | 35       | 16.75%  |
| 3     | 27       | 12.92%  |
| 5     | 17       | 8.13%   |
| 6     | 15       | 7.18%   |
| 7     | 5        | 2.39%   |
| 10    | 2        | 0.96%   |
| 9     | 2        | 0.96%   |
| 8     | 2        | 0.96%   |
| 0     | 2        | 0.96%   |
| 12    | 1        | 0.48%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 202      | 98.06%  |
| Yes  | 4        | 1.94%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 12       | 48%     |
| Cambridge Silicon Radio    | 4        | 16%     |
| Realtek Semiconductor      | 3        | 12%     |
| MediaTek                   | 2        | 8%      |
| Integrated System Solution | 2        | 8%      |
| Belkin Components          | 1        | 4%      |
| Apple                      | 1        | 4%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4        | 16%     |
| Intel AX201 Bluetooth                               | 3        | 12%     |
| Realtek Bluetooth Adapter                           | 2        | 8%      |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 8%      |
| Intel Bluetooth wireless interface                  | 2        | 8%      |
| Intel AX200 Bluetooth                               | 2        | 8%      |
| Integrated System Solution Bluetooth Device         | 2        | 8%      |
| Realtek Bluetooth 4.2 Adapter                       | 1        | 4%      |
| MediaTek Wireless_Device                            | 1        | 4%      |
| MediaTek RZ608 Bluetooth Adapter                    | 1        | 4%      |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 4%      |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 4%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 4%      |
| Belkin Components F8T001v2 Bluetooth                | 1        | 4%      |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1        | 4%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 127      | 58.8%   |
| AMD                              | 51       | 23.61%  |
| Nvidia                           | 23       | 10.65%  |
| C-Media Electronics              | 5        | 2.31%   |
| Samson Technologies              | 2        | 0.93%   |
| Logitech                         | 2        | 0.93%   |
| KTMicro                          | 2        | 0.93%   |
| Silicon Integrated Systems [SiS] | 1        | 0.46%   |
| Plantronics                      | 1        | 0.46%   |
| Creative Labs                    | 1        | 0.46%   |
| Bose                             | 1        | 0.46%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 12       | 4.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 11       | 4.26%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 11       | 4.26%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11       | 4.26%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 11       | 4.26%   |
| Intel Jasper Lake HD Audio                                                                        | 8        | 3.1%    |
| AMD FCH Azalia Controller                                                                         | 8        | 3.1%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7        | 2.71%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 7        | 2.71%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 7        | 2.71%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 7        | 2.71%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7        | 2.71%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 7        | 2.71%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                                           | 6        | 2.33%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6        | 2.33%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6        | 2.33%   |
| Intel Elkhart Lake High Density Audio bus interface                                               | 5        | 1.94%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5        | 1.94%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 5        | 1.94%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 4        | 1.55%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 4        | 1.55%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4        | 1.55%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4        | 1.55%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4        | 1.55%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 4        | 1.55%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 4        | 1.55%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 4        | 1.55%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 4        | 1.55%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 3        | 1.16%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3        | 1.16%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 3        | 1.16%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 3        | 1.16%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3        | 1.16%   |
| Samson Technologies GoMic compact condenser mic                                                   | 2        | 0.78%   |
| Nvidia High Definition Audio Controller                                                           | 2        | 0.78%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2        | 0.78%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 2        | 0.78%   |
| KTMicro KT USB Audio                                                                              | 2        | 0.78%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2        | 0.78%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2        | 0.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Samsung Electronics          | 40       | 19.9%   |
| Kingston                     | 29       | 14.43%  |
| Unknown                      | 27       | 13.43%  |
| Crucial                      | 23       | 11.44%  |
| SK hynix                     | 17       | 8.46%   |
| Micron Technology            | 8        | 3.98%   |
| Transcend                    | 7        | 3.48%   |
| Corsair                      | 7        | 3.48%   |
| Unknown (ABCD)               | 6        | 2.99%   |
| Unknown                      | 6        | 2.99%   |
| Nanya Technology             | 5        | 2.49%   |
| Ramaxel Technology           | 4        | 1.99%   |
| Elpida                       | 4        | 1.99%   |
| A-DATA Technology            | 3        | 1.49%   |
| Unknown (AB)                 | 2        | 1%      |
| G.Skill                      | 2        | 1%      |
| Unknown (89F8)               | 1        | 0.5%    |
| Unknown (0x0DD5)             | 1        | 0.5%    |
| SK_Hynix                     | 1        | 0.5%    |
| Patriot Memory (PDP Systems) | 1        | 0.5%    |
| KomputerBay                  | 1        | 0.5%    |
| Intersil                     | 1        | 0.5%    |
| Heoriady                     | 1        | 0.5%    |
| 2C0C0843D7349CA2             | 1        | 0.5%    |
| 2C0C0843D7349C9D             | 1        | 0.5%    |
| 2C080815D82F5C7B             | 1        | 0.5%    |
| 2C0108214C359D20             | 1        | 0.5%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                    | 6        | 2.71%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2133MT/s | 6        | 2.71%   |
| Unknown                                                        | 6        | 2.71%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 3        | 1.36%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 3        | 1.36%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                    | 2        | 0.9%    |
| Unknown RAM Module 1GB DIMM SDRAM                              | 2        | 0.9%    |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                       | 2        | 0.9%    |
| Transcend RAM TS512MLH72V1H 4GB DIMM DDR4 2133MT/s             | 2        | 0.9%    |
| Transcend RAM Module 4GB SODIMM DDR3 1600MT/s                  | 2        | 0.9%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 2        | 0.9%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 2        | 0.9%    |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s           | 2        | 0.9%    |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s                      | 2        | 0.9%    |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s            | 2        | 0.9%    |
| Samsung RAM M471A1K43CB1-CWE 8GB SODIMM DDR4 3200MT/s          | 2        | 0.9%    |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s        | 2        | 0.9%    |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s            | 2        | 0.9%    |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s        | 2        | 0.9%    |
| Ramaxel RAM RMR5030MN68F9F1600 4GB DIMM DDR3 1600MT/s          | 2        | 0.9%    |
| Kingston RAM ACR256X64D3U1333C9 2GB DIMM DDR3 1333MT/s         | 2        | 0.9%    |
| Kingston RAM 99P5700-017.A00G 16GB SODIMM DDR4 2667MT/s        | 2        | 0.9%    |
| Crucial RAM CT8G4DFRA32A.M4FF 8GB DIMM DDR4 3200MT/s           | 2        | 0.9%    |
| Crucial RAM CT16G56C46S5.M8G1 16GB SODIMM DDR5 5600MT/s        | 2        | 0.9%    |
| Crucial RAM CT16G4SFS832A.C8FF 16GB SODIMM DDR4 3200MT/s       | 2        | 0.9%    |
| Crucial RAM CT16G4SFD824A.M16FE 16GB SODIMM DDR4 2400MT/s      | 2        | 0.9%    |
| Corsair RAM CML16GX3M4A1600C9 4GB DIMM DDR3 1600MT/s           | 2        | 0.9%    |
| Unknown RAM Module 8GB DIMM DDR3 1866MT/s                      | 1        | 0.45%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 1        | 0.45%   |
| Unknown RAM Module 4GB SODIMM DDR3 800MT/s                     | 1        | 0.45%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 1        | 0.45%   |
| Unknown RAM Module 4GB 1600MT/s                                | 1        | 0.45%   |
| Unknown RAM Module 4096MB DIMM DDR3 1067MT/s                   | 1        | 0.45%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                        | 1        | 0.45%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                     | 1        | 0.45%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 1        | 0.45%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 1        | 0.45%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                      | 1        | 0.45%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                       | 1        | 0.45%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 1        | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 77       | 43.75%  |
| DDR4    | 58       | 32.95%  |
| DDR2    | 15       | 8.52%   |
| LPDDR4  | 9        | 5.11%   |
| DDR5    | 9        | 5.11%   |
| Unknown | 6        | 3.41%   |
| SDRAM   | 2        | 1.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 100      | 57.14%  |
| SODIMM       | 70       | 40%     |
| Row Of Chips | 3        | 1.71%   |
| FB-DIMM      | 1        | 0.57%   |
| Unknown      | 1        | 0.57%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 65       | 34.76%  |
| 8192  | 59       | 31.55%  |
| 2048  | 29       | 15.51%  |
| 16384 | 25       | 13.37%  |
| 1024  | 7        | 3.74%   |
| 32768 | 2        | 1.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 46       | 24.47%  |
| 1333    | 30       | 15.96%  |
| 2400    | 25       | 13.3%   |
| 3200    | 20       | 10.64%  |
| 800     | 12       | 6.38%   |
| 2133    | 11       | 5.85%   |
| 2667    | 10       | 5.32%   |
| 4800    | 6        | 3.19%   |
| 667     | 5        | 2.66%   |
| 1067    | 4        | 2.13%   |
| 5600    | 3        | 1.6%    |
| 2933    | 3        | 1.6%    |
| Unknown | 3        | 1.6%    |
| 1066    | 2        | 1.06%   |
| 5200    | 1        | 0.53%   |
| 3600    | 1        | 0.53%   |
| 2666    | 1        | 0.53%   |
| 1896    | 1        | 0.53%   |
| 1867    | 1        | 0.53%   |
| 1866    | 1        | 0.53%   |
| 1334    | 1        | 0.53%   |
| 1200    | 1        | 0.53%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 1        | 50%     |
| Apple               | 1        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Samsung ML-1640 Series Laser Printer | 1        | 50%     |
| Apple Gamesir-G3v 1.00               | 1        | 50%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Seiko Epson | 1        | 50%     |
| Canon       | 1        | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1        | 50%     |
| Canon CanoScan N650U/N656U                    | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 3        | 30%     |
| Trust                         | 2        | 20%     |
| Genesys Logic                 | 2        | 20%     |
| Sunplus Innovation Technology | 1        | 10%     |
| Microdia                      | 1        | 10%     |
| KYE Systems (Mouse Systems)   | 1        | 10%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                            | Desktops | Percent |
|--------------------------------------------------|----------|---------|
| Trust Trust QHD Webcam                           | 2        | 20%     |
| Genesys Logic Digital Microscope                 | 2        | 20%     |
| Sunplus Aukey-PC-LM1E Camera                     | 1        | 10%     |
| Microdia ASUS USB 2.0 Webcam                     | 1        | 10%     |
| Logitech Webcam C310                             | 1        | 10%     |
| Logitech Webcam C270                             | 1        | 10%     |
| Logitech C505 HD Webcam                          | 1        | 10%     |
| KYE Systems (Mouse Systems) AUKEY PC-LM1E Camera | 1        | 10%     |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

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
| 1     | 111      | 52.86%  |
| 0     | 77       | 36.67%  |
| 2     | 12       | 5.71%   |
| 3     | 8        | 3.81%   |
| 4     | 2        | 0.95%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 112      | 75.17%  |
| Net/wireless             | 11       | 7.38%   |
| Firewire controller      | 10       | 6.71%   |
| Bluetooth                | 5        | 3.36%   |
| Network                  | 3        | 2.01%   |
| Graphics card            | 3        | 2.01%   |
| Card reader              | 3        | 2.01%   |
| Dvb card                 | 2        | 1.34%   |

