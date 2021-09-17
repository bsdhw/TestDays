helloSystem 0.5.0 - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for helloSystem 0.5.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/helloSystem_0.5.0/Desktop/README.md) and [notebooks](/Dist/helloSystem_0.5.0/Notebook/README.md).

Full-feature report is available here: https://bsd-hardware.info/?view=trends&rel=hellosystem-0.5.0

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T61 64607EU        | Notebook    | [34e48b691d](https://bsd-hardware.info/?probe=34e48b691d) | Sep 17, 2021 |
| HP            | G42                         | Notebook    | [738ccd1adf](https://bsd-hardware.info/?probe=738ccd1adf) | Sep 15, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [7979c87340](https://bsd-hardware.info/?probe=7979c87340) | Sep 14, 2021 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [bc2a287495](https://bsd-hardware.info/?probe=bc2a287495) | Sep 13, 2021 |
| HP            | 87D6 SMVB                   | Desktop     | [61fc69edfe](https://bsd-hardware.info/?probe=61fc69edfe) | Sep 13, 2021 |
| ASUSTek       | P8H77-I                     | Desktop     | [1feb22dc52](https://bsd-hardware.info/?probe=1feb22dc52) | Sep 12, 2021 |
| Sapphire      | EDGE-FT1M1 E450 1AOVU044    | Desktop     | [85ed325446](https://bsd-hardware.info/?probe=85ed325446) | Sep 11, 2021 |
| ASRock        | B460M Pro4                  | Desktop     | [cfc7818691](https://bsd-hardware.info/?probe=cfc7818691) | Sep 10, 2021 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [08b4825275](https://bsd-hardware.info/?probe=08b4825275) | Sep 09, 2021 |
| ASRock        | B550M Pro4                  | Desktop     | [dc582ea4d3](https://bsd-hardware.info/?probe=dc582ea4d3) | Sep 09, 2021 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [c729f82f4c](https://bsd-hardware.info/?probe=c729f82f4c) | Sep 08, 2021 |
| Packard Be... | imedia S2110A               | Desktop     | [d62a38660c](https://bsd-hardware.info/?probe=d62a38660c) | Sep 08, 2021 |
| Lenovo        | Board                       | Desktop     | [685abcc739](https://bsd-hardware.info/?probe=685abcc739) | Sep 07, 2021 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | Notebook    | [62f9376847](https://bsd-hardware.info/?probe=62f9376847) | Sep 04, 2021 |
| Medion        | H61H2-LM3                   | Desktop     | [7a42009a08](https://bsd-hardware.info/?probe=7a42009a08) | Sep 02, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [9e13729a12](https://bsd-hardware.info/?probe=9e13729a12) | Sep 02, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [6eada6e49e](https://bsd-hardware.info/?probe=6eada6e49e) | Aug 28, 2021 |
| Itautec       | Infoway w7530               | Notebook    | [fe69db32c8](https://bsd-hardware.info/?probe=fe69db32c8) | Aug 27, 2021 |
| HP            | 0A60h                       | Desktop     | [0f28538e3d](https://bsd-hardware.info/?probe=0f28538e3d) | Aug 25, 2021 |
| HP            | 1589                        | Desktop     | [4d51cc9c4b](https://bsd-hardware.info/?probe=4d51cc9c4b) | Aug 24, 2021 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [da3e8986a3](https://bsd-hardware.info/?probe=da3e8986a3) | Aug 22, 2021 |
| HP            | Pavilion dv6                | Notebook    | [8054d6310f](https://bsd-hardware.info/?probe=8054d6310f) | Aug 19, 2021 |
| EVGA          | X299 MICRO                  | Desktop     | [d04b55d1f6](https://bsd-hardware.info/?probe=d04b55d1f6) | Aug 19, 2021 |
| MSI           | GF65 Thin 10SDR             | Notebook    | [7e5ebc9c82](https://bsd-hardware.info/?probe=7e5ebc9c82) | Aug 18, 2021 |
| ASRock        | Z390 Pro4                   | Desktop     | [aca402061b](https://bsd-hardware.info/?probe=aca402061b) | Aug 18, 2021 |
| Toshiba       | Satellite L855              | Notebook    | [116ce6af18](https://bsd-hardware.info/?probe=116ce6af18) | Aug 18, 2021 |
| Intel         | NUC5i3RYB K23918-501        | Mini pc     | [75f3efc215](https://bsd-hardware.info/?probe=75f3efc215) | Aug 18, 2021 |
| Foxconn       | 2ADA                        | Desktop     | [e96976b2cc](https://bsd-hardware.info/?probe=e96976b2cc) | Aug 18, 2021 |
| HC            | HCAR357-MI V1.0             | Desktop     | [3293b7bad9](https://bsd-hardware.info/?probe=3293b7bad9) | Aug 17, 2021 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [bd4b0f0700](https://bsd-hardware.info/?probe=bd4b0f0700) | Aug 17, 2021 |
| Gigabyte      | HA65M-D2H-B3                | Desktop     | [fc9b50bb85](https://bsd-hardware.info/?probe=fc9b50bb85) | Aug 16, 2021 |
| ASUSTek       | X55CR                       | Notebook    | [c7c812c2c9](https://bsd-hardware.info/?probe=c7c812c2c9) | Aug 15, 2021 |
| Lenovo        | SKYBAY SDK0J40700 WIN 32... | All in one  | [37e51c01a1](https://bsd-hardware.info/?probe=37e51c01a1) | Aug 15, 2021 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [7b20265c8e](https://bsd-hardware.info/?probe=7b20265c8e) | Aug 14, 2021 |
| HP            | 250 G4                      | Notebook    | [24e8c3de59](https://bsd-hardware.info/?probe=24e8c3de59) | Aug 13, 2021 |
| HP            | 625                         | Notebook    | [606d75e6a1](https://bsd-hardware.info/?probe=606d75e6a1) | Aug 11, 2021 |
| HP            | 250 G4                      | Notebook    | [43a7b112ba](https://bsd-hardware.info/?probe=43a7b112ba) | Aug 11, 2021 |
| Lenovo        | ThinkPad X230 2330A48       | Notebook    | [791c826f7d](https://bsd-hardware.info/?probe=791c826f7d) | Aug 11, 2021 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [1c88ce5779](https://bsd-hardware.info/?probe=1c88ce5779) | Aug 10, 2021 |
| HP            | Pavilion 11                 | Notebook    | [5300a49632](https://bsd-hardware.info/?probe=5300a49632) | Aug 10, 2021 |
| Pegatron      | IPPCR-SS                    | Desktop     | [8a7fc2689b](https://bsd-hardware.info/?probe=8a7fc2689b) | Aug 09, 2021 |
| Gigabyte      | A75M-DS2                    | Desktop     | [2010fe5fab](https://bsd-hardware.info/?probe=2010fe5fab) | Aug 09, 2021 |
| Dell          | G3 3579                     | Notebook    | [91c803fdf2](https://bsd-hardware.info/?probe=91c803fdf2) | Aug 09, 2021 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [df393cc673](https://bsd-hardware.info/?probe=df393cc673) | Aug 08, 2021 |
| Intel         | D54250WYK H13922-304        | Desktop     | [45c86d174e](https://bsd-hardware.info/?probe=45c86d174e) | Aug 08, 2021 |
| NEC Comput... | PC-VK17HBBCD                | Notebook    | [1e23da04c0](https://bsd-hardware.info/?probe=1e23da04c0) | Aug 08, 2021 |
| ASUSTek       | M5A78L LE                   | Desktop     | [7a1d31be72](https://bsd-hardware.info/?probe=7a1d31be72) | Aug 07, 2021 |
| ASUSTek       | H81M-A                      | Desktop     | [bb65c30be3](https://bsd-hardware.info/?probe=bb65c30be3) | Aug 07, 2021 |
| ASUSTek       | H81M-A                      | Desktop     | [9e0c8e8024](https://bsd-hardware.info/?probe=9e0c8e8024) | Aug 07, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [9073f1975d](https://bsd-hardware.info/?probe=9073f1975d) | Aug 07, 2021 |
| ASUSTek       | K55VD                       | Notebook    | [6896c37580](https://bsd-hardware.info/?probe=6896c37580) | Aug 06, 2021 |
| ASUSTek       | Crosshair V Formula         | Desktop     | [90c27497d9](https://bsd-hardware.info/?probe=90c27497d9) | Aug 05, 2021 |
| Apple         | MacBookPro3,1               | Notebook    | [3566222830](https://bsd-hardware.info/?probe=3566222830) | Aug 04, 2021 |
| PCPartner     | MILANO-P Rev.00             | Desktop     | [526390c559](https://bsd-hardware.info/?probe=526390c559) | Aug 04, 2021 |
| PCPartner     | MILANO-P Rev.00             | Desktop     | [071eac9b1b](https://bsd-hardware.info/?probe=071eac9b1b) | Aug 04, 2021 |
| Acidanther... | Mac-7BA5B2D9E42DDD94 iMa... | All in one  | [4055806819](https://bsd-hardware.info/?probe=4055806819) | Aug 04, 2021 |
| Biostar       | A770E3                      | Desktop     | [4d0ac19b8e](https://bsd-hardware.info/?probe=4d0ac19b8e) | Aug 03, 2021 |
| Lenovo        | ThinkPad X250 20CLS4JH00    | Notebook    | [89a74889ae](https://bsd-hardware.info/?probe=89a74889ae) | Aug 02, 2021 |
| Dell          | 0RY007                      | Desktop     | [c67ccf8bc6](https://bsd-hardware.info/?probe=c67ccf8bc6) | Aug 01, 2021 |
| Sony          | VPCEJ1E1E                   | Notebook    | [c471fb3f82](https://bsd-hardware.info/?probe=c471fb3f82) | Aug 01, 2021 |
| PCPartner     | MILANO-P Rev.00             | Desktop     | [ef40df391b](https://bsd-hardware.info/?probe=ef40df391b) | Aug 01, 2021 |
| Gigabyte      | H110-D3A-CF                 | Desktop     | [7923f57fbe](https://bsd-hardware.info/?probe=7923f57fbe) | Aug 01, 2021 |
| ASUSTek       | A58M-A/USB3                 | Desktop     | [9ffd4220e8](https://bsd-hardware.info/?probe=9ffd4220e8) | Aug 01, 2021 |
| Lenovo        | G550 2958                   | Notebook    | [86880c29cf](https://bsd-hardware.info/?probe=86880c29cf) | Jul 31, 2021 |
| Lenovo        | G550 2958                   | Notebook    | [4fe522eaf3](https://bsd-hardware.info/?probe=4fe522eaf3) | Jul 31, 2021 |
| HP            | 15                          | Notebook    | [c2da1dd654](https://bsd-hardware.info/?probe=c2da1dd654) | Jul 30, 2021 |
| Microsoft     | Surface Go                  | Tablet      | [1dfbc72509](https://bsd-hardware.info/?probe=1dfbc72509) | Jul 30, 2021 |
| Biostar       | N68S3+                      | Desktop     | [528c9d6eab](https://bsd-hardware.info/?probe=528c9d6eab) | Jul 26, 2021 |
| Apple         | MacBookPro6,2               | Notebook    | [7f25ab7c67](https://bsd-hardware.info/?probe=7f25ab7c67) | Jul 26, 2021 |
| Gigabyte      | PH67A-D3-B3                 | Desktop     | [73dff53f04](https://bsd-hardware.info/?probe=73dff53f04) | Jul 23, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [d15eff8bcc](https://bsd-hardware.info/?probe=d15eff8bcc) | Jul 21, 2021 |
| HP            | Stream 11 Pro G4 EE         | Notebook    | [bd2bf6b0a0](https://bsd-hardware.info/?probe=bd2bf6b0a0) | Jul 20, 2021 |
| Gigabyte      | H110-D3A-CF                 | Desktop     | [58e49f458e](https://bsd-hardware.info/?probe=58e49f458e) | Jul 19, 2021 |
| PCPartner     | MILANO-P Rev.00             | Desktop     | [f20ac8df75](https://bsd-hardware.info/?probe=f20ac8df75) | Jul 19, 2021 |
| MSI           | IONA                        | Desktop     | [bb2c6b383b](https://bsd-hardware.info/?probe=bb2c6b383b) | Jul 17, 2021 |
| ASRock        | N68C-GS FX                  | Desktop     | [012356047f](https://bsd-hardware.info/?probe=012356047f) | Jul 17, 2021 |
| ASRock        | N68C-GS FX                  | Desktop     | [e1f439def9](https://bsd-hardware.info/?probe=e1f439def9) | Jul 17, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [20fc88018b](https://bsd-hardware.info/?probe=20fc88018b) | Jul 16, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [6cca4dee6f](https://bsd-hardware.info/?probe=6cca4dee6f) | Jul 15, 2021 |
| HP            | ProLiant DL380 G5           | Server      | [7dfaec9b01](https://bsd-hardware.info/?probe=7dfaec9b01) | Jul 13, 2021 |
| HP            | 0AE8h C                     | Desktop     | [23df6b2e94](https://bsd-hardware.info/?probe=23df6b2e94) | Jul 12, 2021 |
| Intel         | NUC5i3RYB K23918-501        | Mini pc     | [4bd9c0bbb8](https://bsd-hardware.info/?probe=4bd9c0bbb8) | Jul 11, 2021 |
| Alienware     | 17                          | Notebook    | [aff2be63cd](https://bsd-hardware.info/?probe=aff2be63cd) | Jul 10, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [40624b04c0](https://bsd-hardware.info/?probe=40624b04c0) | Jul 08, 2021 |
| Dell          | 0GXM1W A02                  | Desktop     | [269edf2dcf](https://bsd-hardware.info/?probe=269edf2dcf) | Jul 06, 2021 |
| MouseCompu... | W331AU                      | Notebook    | [f9a4733911](https://bsd-hardware.info/?probe=f9a4733911) | Jul 06, 2021 |
| Intel         | NUC7i7BNB J31145-306        | Mini pc     | [631f69c3f6](https://bsd-hardware.info/?probe=631f69c3f6) | Jul 06, 2021 |
| MouseCompu... | W331AU                      | Notebook    | [4adfeaa072](https://bsd-hardware.info/?probe=4adfeaa072) | Jul 06, 2021 |
| ASRock        | B450M-HDV                   | Desktop     | [dca41aa10a](https://bsd-hardware.info/?probe=dca41aa10a) | Jul 05, 2021 |
| ASRock        | X99 Taichi                  | Desktop     | [149d7abd05](https://bsd-hardware.info/?probe=149d7abd05) | Jul 04, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [4060cdec72](https://bsd-hardware.info/?probe=4060cdec72) | Jul 04, 2021 |
| ASRock        | Z390 Pro4                   | Desktop     | [dc4eb674ea](https://bsd-hardware.info/?probe=dc4eb674ea) | Jul 03, 2021 |
| Shuttle       | NC10U                       | Desktop     | [5d2d20dd04](https://bsd-hardware.info/?probe=5d2d20dd04) | Jul 02, 2021 |
| HP            | ProBook 4440s               | Notebook    | [4aac49bc1e](https://bsd-hardware.info/?probe=4aac49bc1e) | Jul 01, 2021 |
| Fujitsu       | D2863 S26361-D2863-A10 W... | Server      | [8cebf32782](https://bsd-hardware.info/?probe=8cebf32782) | Jun 30, 2021 |
| Lenovo        | ThinkPad X200 7458VP4       | Notebook    | [42100d8ea1](https://bsd-hardware.info/?probe=42100d8ea1) | Jun 30, 2021 |
| Protectli     | FW2B Ver                    | Desktop     | [7b6f704247](https://bsd-hardware.info/?probe=7b6f704247) | Jun 30, 2021 |
| HP            | Pavilion 17                 | Notebook    | [9929e0c39b](https://bsd-hardware.info/?probe=9929e0c39b) | Jun 30, 2021 |
| HP            | 0B4Ch D                     | Desktop     | [b56bd19073](https://bsd-hardware.info/?probe=b56bd19073) | Jun 30, 2021 |
| Biostar       | B450MH                      | Desktop     | [167f09a25c](https://bsd-hardware.info/?probe=167f09a25c) | Jun 29, 2021 |
| Dell          | Latitude E6410              | Notebook    | [8c904d84e0](https://bsd-hardware.info/?probe=8c904d84e0) | Jun 28, 2021 |
| Huanan        | X99-8M-F V1.2               | Desktop     | [6477b9ef24](https://bsd-hardware.info/?probe=6477b9ef24) | Jun 28, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [6e96d4c26f](https://bsd-hardware.info/?probe=6e96d4c26f) | Jun 28, 2021 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [f0e80b0788](https://bsd-hardware.info/?probe=f0e80b0788) | Jun 28, 2021 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [f3b0bb0930](https://bsd-hardware.info/?probe=f3b0bb0930) | Jun 28, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [7ae63d4c6c](https://bsd-hardware.info/?probe=7ae63d4c6c) | Jun 27, 2021 |
| Lenovo        | ThinkPad L450 20DTCTO1WW    | Notebook    | [aba7b76575](https://bsd-hardware.info/?probe=aba7b76575) | Jun 27, 2021 |
| ASUSTek       | PRIME H410M-D               | Desktop     | [8ea103b783](https://bsd-hardware.info/?probe=8ea103b783) | Jun 26, 2021 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [1697ebb0a5](https://bsd-hardware.info/?probe=1697ebb0a5) | Jun 25, 2021 |
| Dell          | 0P03DX A03                  | Desktop     | [b2f0c90d79](https://bsd-hardware.info/?probe=b2f0c90d79) | Jun 24, 2021 |
| Acer          | Aspire 5750                 | Notebook    | [d59f20f88a](https://bsd-hardware.info/?probe=d59f20f88a) | Jun 22, 2021 |
| ASUSTek       | P7H55                       | Desktop     | [c33ec074f8](https://bsd-hardware.info/?probe=c33ec074f8) | Jun 22, 2021 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [616c7043bd](https://bsd-hardware.info/?probe=616c7043bd) | Jun 22, 2021 |
| Dell          | Precision 7710              | Notebook    | [33653d0c28](https://bsd-hardware.info/?probe=33653d0c28) | Jun 22, 2021 |
| Lenovo        | ThinkPad X230 2325WWB       | Notebook    | [786669cc9c](https://bsd-hardware.info/?probe=786669cc9c) | Jun 21, 2021 |
| ASUSTek       | CP5141                      | Desktop     | [73c62835c1](https://bsd-hardware.info/?probe=73c62835c1) | Jun 21, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | Notebook    | [46dca136f6](https://bsd-hardware.info/?probe=46dca136f6) | Jun 21, 2021 |
| Lenovo        | ThinkPad T470p 20J6A012C... | Notebook    | [d5e4c49986](https://bsd-hardware.info/?probe=d5e4c49986) | Jun 21, 2021 |
| Acer          | Aspire 5750                 | Notebook    | [cc6dc71d37](https://bsd-hardware.info/?probe=cc6dc71d37) | Jun 21, 2021 |
| Foxconn       | 2ABF                        | Desktop     | [d30b2629eb](https://bsd-hardware.info/?probe=d30b2629eb) | Jun 21, 2021 |
| Intel         | DH67CL AAG10212-206         | Desktop     | [f2367a4249](https://bsd-hardware.info/?probe=f2367a4249) | Jun 21, 2021 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [a326fd4061](https://bsd-hardware.info/?probe=a326fd4061) | Jun 20, 2021 |
| Dell          | 0PGKWF A01                  | Desktop     | [9f09d62462](https://bsd-hardware.info/?probe=9f09d62462) | Jun 20, 2021 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [45b842180e](https://bsd-hardware.info/?probe=45b842180e) | Jun 20, 2021 |
| Toshiba       | PORTEGE Z10t-A              | Notebook    | [cb7cbd17d0](https://bsd-hardware.info/?probe=cb7cbd17d0) | Jun 20, 2021 |
| Gateway       | NE56R                       | Notebook    | [cc65e24aea](https://bsd-hardware.info/?probe=cc65e24aea) | Jun 20, 2021 |
| ASUSTek       | ROG STRIX H370-I GAMING     | Desktop     | [d2dd261a2a](https://bsd-hardware.info/?probe=d2dd261a2a) | Jun 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [0fe1337b93](https://bsd-hardware.info/?probe=0fe1337b93) | Jun 19, 2021 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [edcbaf755f](https://bsd-hardware.info/?probe=edcbaf755f) | Jun 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [902b4298d4](https://bsd-hardware.info/?probe=902b4298d4) | Jun 19, 2021 |
| WYSE          | Z CLASS                     | Notebook    | [571fdbf390](https://bsd-hardware.info/?probe=571fdbf390) | Jun 19, 2021 |
| Dell          | 0XPDFK A01                  | Desktop     | [631dbb841b](https://bsd-hardware.info/?probe=631dbb841b) | Jun 19, 2021 |
| Dell          | Latitude E5420              | Notebook    | [1ed3ff35f6](https://bsd-hardware.info/?probe=1ed3ff35f6) | Jun 19, 2021 |
| Lenovo        | ThinkServer RS140           | Desktop     | [0f5d669e9f](https://bsd-hardware.info/?probe=0f5d669e9f) | Jun 18, 2021 |
| Lenovo        | ThinkServer RS140           | Desktop     | [63ba615299](https://bsd-hardware.info/?probe=63ba615299) | Jun 18, 2021 |
| Gigabyte      | AX370-Gaming-CF             | Desktop     | [d77be09267](https://bsd-hardware.info/?probe=d77be09267) | Jun 18, 2021 |
| Dell          | 0XPDFK A01                  | Desktop     | [7a1c26edeb](https://bsd-hardware.info/?probe=7a1c26edeb) | Jun 18, 2021 |
| Dell          | Vostro 3560                 | Notebook    | [ce9d5f9a46](https://bsd-hardware.info/?probe=ce9d5f9a46) | Jun 18, 2021 |
| Lenovo        | ThinkPad Edge E530 62724... | Notebook    | [78abd376db](https://bsd-hardware.info/?probe=78abd376db) | Jun 18, 2021 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [0cb30b464d](https://bsd-hardware.info/?probe=0cb30b464d) | Jun 17, 2021 |
| Lenovo        | ThinkPad T420 4236FJ1       | Notebook    | [808f58228e](https://bsd-hardware.info/?probe=808f58228e) | Jun 17, 2021 |
| HP            | 3397                        | Desktop     | [3dd97c60ca](https://bsd-hardware.info/?probe=3dd97c60ca) | Jun 16, 2021 |
| Lenovo        | Board                       | Desktop     | [c981ffdff7](https://bsd-hardware.info/?probe=c981ffdff7) | Jun 15, 2021 |
| Toshiba       | PORTEGE R930                | Notebook    | [db520e9382](https://bsd-hardware.info/?probe=db520e9382) | Jun 15, 2021 |
| Toshiba       | Satellite C640              | Notebook    | [ec0d93d08c](https://bsd-hardware.info/?probe=ec0d93d08c) | Jun 15, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | Notebook    | [9ae8146589](https://bsd-hardware.info/?probe=9ae8146589) | Jun 15, 2021 |
| Dell          | Latitude 5400               | Notebook    | [1bb6c1f63f](https://bsd-hardware.info/?probe=1bb6c1f63f) | Jun 15, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [5f9b56c8ae](https://bsd-hardware.info/?probe=5f9b56c8ae) | Jun 15, 2021 |
| ASUSTek       | M4A78LT-M                   | Desktop     | [0c8d6cd661](https://bsd-hardware.info/?probe=0c8d6cd661) | Jun 14, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [fea57181b5](https://bsd-hardware.info/?probe=fea57181b5) | Jun 14, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [53049dff12](https://bsd-hardware.info/?probe=53049dff12) | Jun 14, 2021 |
| ASRock        | G31M-VS2                    | Desktop     | [f2f5b95f4b](https://bsd-hardware.info/?probe=f2f5b95f4b) | Jun 14, 2021 |
| Intel         | X79 V2.72A                  | Desktop     | [88173bcf06](https://bsd-hardware.info/?probe=88173bcf06) | Jun 14, 2021 |
| HP            | OMEN by HP Laptop           | Notebook    | [abc94e9198](https://bsd-hardware.info/?probe=abc94e9198) | Jun 13, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [eeb4489d2f](https://bsd-hardware.info/?probe=eeb4489d2f) | Jun 13, 2021 |
| Gigabyte      | H470M DS3H                  | Desktop     | [7c37a0319b](https://bsd-hardware.info/?probe=7c37a0319b) | Jun 13, 2021 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [8bb0d23eb4](https://bsd-hardware.info/?probe=8bb0d23eb4) | Jun 13, 2021 |
| HP            | 255 G2                      | Notebook    | [31177d9e0f](https://bsd-hardware.info/?probe=31177d9e0f) | Jun 13, 2021 |
| Lenovo        | ThinkPad T430 2349GCU       | Notebook    | [ca15c7d742](https://bsd-hardware.info/?probe=ca15c7d742) | Jun 13, 2021 |
| Gateway       | NE56R                       | Notebook    | [932f5d03f3](https://bsd-hardware.info/?probe=932f5d03f3) | Jun 13, 2021 |
| Dell          | Latitude E4300              | Notebook    | [7855973957](https://bsd-hardware.info/?probe=7855973957) | Jun 12, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [d239ee4916](https://bsd-hardware.info/?probe=d239ee4916) | Jun 12, 2021 |
| Lenovo        | ThinkPad X240 20AMS39F0K    | Notebook    | [65564434a9](https://bsd-hardware.info/?probe=65564434a9) | Jun 12, 2021 |
| ASUSTek       | UX330UAK                    | Notebook    | [430c90b88d](https://bsd-hardware.info/?probe=430c90b88d) | Jun 12, 2021 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [1759329ae3](https://bsd-hardware.info/?probe=1759329ae3) | Apr 12, 2021 |
| Dell          | 0RW199                      | Desktop     | [e78392bc4c](https://bsd-hardware.info/?probe=e78392bc4c) | Apr 02, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [62376c16a4](https://bsd-hardware.info/?probe=62376c16a4) | Mar 31, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | Notebook    | [b644ed3914](https://bsd-hardware.info/?probe=b644ed3914) | Mar 31, 2021 |
| Medion        | H61H2-LM3                   | Desktop     | [6483c8390f](https://bsd-hardware.info/?probe=6483c8390f) | Mar 31, 2021 |
| Pegatron      | IPM41-D3                    | Desktop     | [687047b3d2](https://bsd-hardware.info/?probe=687047b3d2) | Mar 30, 2021 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [ac585b4e0d](https://bsd-hardware.info/?probe=ac585b4e0d) | Mar 30, 2021 |
| Dell          | Vostro 14-3468              | Notebook    | [219133fc53](https://bsd-hardware.info/?probe=219133fc53) | Mar 30, 2021 |
| Dell          | Vostro 14-3468              | Notebook    | [2c61fcee12](https://bsd-hardware.info/?probe=2c61fcee12) | Mar 30, 2021 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [d3742d3898](https://bsd-hardware.info/?probe=d3742d3898) | Mar 29, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | Notebook    | [a5b9f5e79d](https://bsd-hardware.info/?probe=a5b9f5e79d) | Mar 27, 2021 |
| Lenovo        | ThinkPad X230 23255Y4       | Notebook    | [ab871769f0](https://bsd-hardware.info/?probe=ab871769f0) | Mar 27, 2021 |
| Toshiba       | Satellite L500              | Notebook    | [e07fd4edd9](https://bsd-hardware.info/?probe=e07fd4edd9) | Mar 25, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [42ecf97502](https://bsd-hardware.info/?probe=42ecf97502) | Mar 25, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [88e98e18a5](https://bsd-hardware.info/?probe=88e98e18a5) | Mar 25, 2021 |
| HP            | 18E7                        | Desktop     | [0e835b61ff](https://bsd-hardware.info/?probe=0e835b61ff) | Mar 24, 2021 |
| ASUSTek       | G75VW                       | Notebook    | [9b84d1e7e6](https://bsd-hardware.info/?probe=9b84d1e7e6) | Mar 24, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [78a7c7b8cb](https://bsd-hardware.info/?probe=78a7c7b8cb) | Mar 23, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | Notebook    | [d856b5bf95](https://bsd-hardware.info/?probe=d856b5bf95) | Mar 23, 2021 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [10c79ea427](https://bsd-hardware.info/?probe=10c79ea427) | Mar 22, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [5ae508dfa8](https://bsd-hardware.info/?probe=5ae508dfa8) | Mar 19, 2021 |
| Lenovo        | ThinkPad X260 20F5S82N00    | Notebook    | [aa3deadedd](https://bsd-hardware.info/?probe=aa3deadedd) | Mar 19, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [599d3e84d7](https://bsd-hardware.info/?probe=599d3e84d7) | Mar 16, 2021 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [8964a02114](https://bsd-hardware.info/?probe=8964a02114) | Mar 15, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [0a3b290f9f](https://bsd-hardware.info/?probe=0a3b290f9f) | Mar 15, 2021 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [860b1cd65b](https://bsd-hardware.info/?probe=860b1cd65b) | Mar 15, 2021 |
| Packard Be... | EasyNote MH36               | Notebook    | [2a98cae4e8](https://bsd-hardware.info/?probe=2a98cae4e8) | Mar 13, 2021 |
| Fujitsu       | LIFEBOOK A555               | Notebook    | [bcb99d0f09](https://bsd-hardware.info/?probe=bcb99d0f09) | Mar 13, 2021 |
| Fujitsu       | LIFEBOOK A555               | Notebook    | [ee894449af](https://bsd-hardware.info/?probe=ee894449af) | Mar 13, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [0054ef2511](https://bsd-hardware.info/?probe=0054ef2511) | Mar 13, 2021 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [80e7c230d7](https://bsd-hardware.info/?probe=80e7c230d7) | Mar 12, 2021 |
| Dell          | 0W2PJY A01                  | Desktop     | [f162510a27](https://bsd-hardware.info/?probe=f162510a27) | Mar 12, 2021 |
| Dell          | Inspiron 3543               | Notebook    | [525eeec663](https://bsd-hardware.info/?probe=525eeec663) | Mar 12, 2021 |
| MSI           | B150M PRO-VDH               | Desktop     | [bc75a3ab13](https://bsd-hardware.info/?probe=bc75a3ab13) | Mar 11, 2021 |
| Acer          | Aspire 4810T                | Notebook    | [14af887195](https://bsd-hardware.info/?probe=14af887195) | Mar 11, 2021 |
| Lenovo        | B41-80 80LG                 | Notebook    | [d598cc6240](https://bsd-hardware.info/?probe=d598cc6240) | Mar 11, 2021 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [cf00023cef](https://bsd-hardware.info/?probe=cf00023cef) | Mar 11, 2021 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [9a7f08f8c1](https://bsd-hardware.info/?probe=9a7f08f8c1) | Mar 11, 2021 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [d9661207d7](https://bsd-hardware.info/?probe=d9661207d7) | Mar 11, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [e9ca160a2d](https://bsd-hardware.info/?probe=e9ca160a2d) | Mar 11, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [47d17e6983](https://bsd-hardware.info/?probe=47d17e6983) | Mar 10, 2021 |
| Dell          | 0JP3NX A01                  | Desktop     | [fc94b8c422](https://bsd-hardware.info/?probe=fc94b8c422) | Mar 09, 2021 |
| Toshiba       | Satellite Pro U400          | Notebook    | [71fd81df30](https://bsd-hardware.info/?probe=71fd81df30) | Mar 07, 2021 |
| ASUSTek       | X556UA                      | Notebook    | [57018edd10](https://bsd-hardware.info/?probe=57018edd10) | Mar 07, 2021 |
| Dell          | Latitude E6500              | Notebook    | [d25dacc162](https://bsd-hardware.info/?probe=d25dacc162) | Mar 07, 2021 |
| ASUSTek       | P8Z77-V                     | Desktop     | [88ee81b089](https://bsd-hardware.info/?probe=88ee81b089) | Mar 06, 2021 |
| Dell          | Latitude E5570              | Notebook    | [12eae7a62e](https://bsd-hardware.info/?probe=12eae7a62e) | Mar 05, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [de98cd5952](https://bsd-hardware.info/?probe=de98cd5952) | Mar 04, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [03c5808adf](https://bsd-hardware.info/?probe=03c5808adf) | Mar 04, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [d129752b43](https://bsd-hardware.info/?probe=d129752b43) | Mar 04, 2021 |
| Dell          | 0W2PJY A01                  | Desktop     | [d8c2f0b19f](https://bsd-hardware.info/?probe=d8c2f0b19f) | Mar 04, 2021 |
| Foxconn       | 2ADA                        | Desktop     | [10d02d0982](https://bsd-hardware.info/?probe=10d02d0982) | Mar 03, 2021 |
| Acer          | Aspire 8730                 | Notebook    | [33e7d80b63](https://bsd-hardware.info/?probe=33e7d80b63) | Mar 01, 2021 |
| Hampoo        | B3W6_NA123C Reserved        | Notebook    | [bc138c0580](https://bsd-hardware.info/?probe=bc138c0580) | Feb 27, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [5211d36066](https://bsd-hardware.info/?probe=5211d36066) | Feb 25, 2021 |
| Lenovo        | ThinkPad T470p 20J6A012C... | Notebook    | [cbaa19611e](https://bsd-hardware.info/?probe=cbaa19611e) | Feb 24, 2021 |
| Dell          | XPS 13 9333                 | Notebook    | [7c78b3d42a](https://bsd-hardware.info/?probe=7c78b3d42a) | Feb 24, 2021 |
| ASUSTek       | P8Z77-V LX2                 | Desktop     | [0aeea0fec9](https://bsd-hardware.info/?probe=0aeea0fec9) | Feb 23, 2021 |
| ASUSTek       | P5Q                         | Desktop     | [22fa0d8178](https://bsd-hardware.info/?probe=22fa0d8178) | Feb 23, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [467a915fc7](https://bsd-hardware.info/?probe=467a915fc7) | Feb 23, 2021 |
| LG Electro... | 14Z980-G.BH51P1             | Notebook    | [d8ee6bc4e3](https://bsd-hardware.info/?probe=d8ee6bc4e3) | Feb 22, 2021 |
| Dell          | Latitude E7240              | Notebook    | [e42e579971](https://bsd-hardware.info/?probe=e42e579971) | Feb 22, 2021 |
| Lenovo        | G470 20078                  | Notebook    | [b8e35aacdb](https://bsd-hardware.info/?probe=b8e35aacdb) | Feb 22, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [a7d9aeda81](https://bsd-hardware.info/?probe=a7d9aeda81) | Feb 22, 2021 |
| Biostar       | B365MHC                     | Desktop     | [adb029c65f](https://bsd-hardware.info/?probe=adb029c65f) | Feb 22, 2021 |
| Dell          | 0RW199                      | Desktop     | [e0ecb4caa7](https://bsd-hardware.info/?probe=e0ecb4caa7) | Feb 21, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [78d9a31074](https://bsd-hardware.info/?probe=78d9a31074) | Feb 21, 2021 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [c9a8d5ade5](https://bsd-hardware.info/?probe=c9a8d5ade5) | Feb 21, 2021 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [a471763f19](https://bsd-hardware.info/?probe=a471763f19) | Feb 20, 2021 |
| Lenovo        | ThinkPad E420 1141A83       | Notebook    | [aa98e655f3](https://bsd-hardware.info/?probe=aa98e655f3) | Feb 20, 2021 |
| Lenovo        | ThinkPad E420 1141A83       | Notebook    | [9731048099](https://bsd-hardware.info/?probe=9731048099) | Feb 20, 2021 |
| Lenovo        | ThinkPad E420 1141A83       | Notebook    | [03d4d9a468](https://bsd-hardware.info/?probe=03d4d9a468) | Feb 20, 2021 |
| Lenovo        | ThinkPad E420 1141A83       | Notebook    | [a48872901d](https://bsd-hardware.info/?probe=a48872901d) | Feb 20, 2021 |
| ASUSTek       | PRIME H270-PLUS             | Desktop     | [0b5194e68e](https://bsd-hardware.info/?probe=0b5194e68e) | Feb 19, 2021 |
| HP            | ProBook 440 G2              | Notebook    | [63038d613f](https://bsd-hardware.info/?probe=63038d613f) | Feb 19, 2021 |
| Lenovo        | ZIUS6                       | Notebook    | [1c239bac92](https://bsd-hardware.info/?probe=1c239bac92) | Feb 18, 2021 |
| Samsung       | Galaxy Book 12              | Tablet      | [91c76db748](https://bsd-hardware.info/?probe=91c76db748) | Feb 18, 2021 |
| Samsung       | Galaxy Book 12              | Tablet      | [5f73061749](https://bsd-hardware.info/?probe=5f73061749) | Feb 18, 2021 |
| Unknown       | Unknown                     | Desktop     | [22af66ce96](https://bsd-hardware.info/?probe=22af66ce96) | Feb 18, 2021 |
| Dell          | 0GM819                      | Desktop     | [836d0f9057](https://bsd-hardware.info/?probe=836d0f9057) | Feb 17, 2021 |
| Lenovo        | ThinkPad T490 20RYS06R00    | Notebook    | [12c985b708](https://bsd-hardware.info/?probe=12c985b708) | Feb 17, 2021 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [e601d28f5e](https://bsd-hardware.info/?probe=e601d28f5e) | Feb 17, 2021 |
| HP            | Pavilion Laptop 14-ce2xx... | Notebook    | [c355a6280b](https://bsd-hardware.info/?probe=c355a6280b) | Feb 17, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [b087324f05](https://bsd-hardware.info/?probe=b087324f05) | Feb 17, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [d03a5bbea5](https://bsd-hardware.info/?probe=d03a5bbea5) | Feb 17, 2021 |
| HP            | OMEN by HP Laptop           | Notebook    | [bb8beb97be](https://bsd-hardware.info/?probe=bb8beb97be) | Feb 17, 2021 |
| Pegatron      | IPM41-D3                    | Desktop     | [6e5c330c9c](https://bsd-hardware.info/?probe=6e5c330c9c) | Feb 16, 2021 |
| ASUSTek       | VM62                        | Desktop     | [4d02a33fec](https://bsd-hardware.info/?probe=4d02a33fec) | Feb 16, 2021 |
| ASUSTek       | P5B SE                      | Desktop     | [425210021c](https://bsd-hardware.info/?probe=425210021c) | Feb 16, 2021 |
| HP            | 8768 A                      | Desktop     | [f2be4b7b65](https://bsd-hardware.info/?probe=f2be4b7b65) | Feb 16, 2021 |
| eMachines     | eME732ZG                    | Notebook    | [d0c0433452](https://bsd-hardware.info/?probe=d0c0433452) | Feb 16, 2021 |
| ASUSTek       | X555LD                      | Notebook    | [74d43ccd10](https://bsd-hardware.info/?probe=74d43ccd10) | Feb 16, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [0d35b2f5d8](https://bsd-hardware.info/?probe=0d35b2f5d8) | Feb 15, 2021 |
| Intel         | DN2820FYK H24582-201        | Desktop     | [be56203e79](https://bsd-hardware.info/?probe=be56203e79) | Feb 15, 2021 |
| ASUSTek       | EX-B85M-V                   | Desktop     | [54c319f2c0](https://bsd-hardware.info/?probe=54c319f2c0) | Feb 15, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [ef29c46355](https://bsd-hardware.info/?probe=ef29c46355) | Feb 15, 2021 |
| ASRock        | B550M Pro4                  | Desktop     | [61a5641019](https://bsd-hardware.info/?probe=61a5641019) | Feb 14, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [f8bdec0105](https://bsd-hardware.info/?probe=f8bdec0105) | Feb 14, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [8082fefc2e](https://bsd-hardware.info/?probe=8082fefc2e) | Feb 14, 2021 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [565ceb36f0](https://bsd-hardware.info/?probe=565ceb36f0) | Feb 14, 2021 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 216       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 214       | 99.07%  |
| KDE5         | 1         | 0.46%   |
| GNOME        | 1         | 0.46%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 216       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| SLiM | 216       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 214       | 98.62%  |
| it_IT | 1         | 0.46%   |
| es_ES | 1         | 0.46%   |
| es_AR | 1         | 0.46%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 176       | 81.48%  |
| BIOS | 40        | 18.52%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 216       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 216       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 41        | 18.98%  |
| Lenovo              | 30        | 13.89%  |
| Dell                | 28        | 12.96%  |
| Hewlett-Packard     | 26        | 12.04%  |
| Gigabyte Technology | 11        | 5.09%   |
| ASRock              | 11        | 5.09%   |
| Apple               | 8         | 3.7%    |
| MSI                 | 7         | 3.24%   |
| Toshiba             | 6         | 2.78%   |
| Intel               | 6         | 2.78%   |
| Biostar             | 4         | 1.85%   |
| Acer                | 4         | 1.85%   |
| Samsung Electronics | 3         | 1.39%   |
| Foxconn             | 3         | 1.39%   |
| Pegatron            | 2         | 0.93%   |
| Packard Bell        | 2         | 0.93%   |
| Gateway             | 2         | 0.93%   |
| Fujitsu             | 2         | 0.93%   |
| WYSE                | 1         | 0.46%   |
| TUXEDO              | 1         | 0.46%   |
| Sony                | 1         | 0.46%   |
| Shuttle             | 1         | 0.46%   |
| Sapphire            | 1         | 0.46%   |
| Protectli           | 1         | 0.46%   |
| PCPartner           | 1         | 0.46%   |
| NEC Computers       | 1         | 0.46%   |
| MouseComputer       | 1         | 0.46%   |
| Microsoft           | 1         | 0.46%   |
| Medion              | 1         | 0.46%   |
| LG Electronics      | 1         | 0.46%   |
| Huanan              | 1         | 0.46%   |
| HC                  | 1         | 0.46%   |
| Hampoo              | 1         | 0.46%   |
| EVGA                | 1         | 0.46%   |
| eMachines           | 1         | 0.46%   |
| Alienware           | 1         | 0.46%   |
| Acidanthera         | 1         | 0.46%   |
| Unknown             | 1         | 0.46%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Dell Inspiron 15-3567                       | 3         | 1.39%   |
| Gateway NE56R                               | 2         | 0.93%   |
| Dell Inspiron 7520                          | 2         | 0.93%   |
| ASUS All Series                             | 2         | 0.93%   |
| ASRock B550M Pro4                           | 2         | 0.93%   |
| ASRock B450M Pro4                           | 2         | 0.93%   |
| Apple MacBookPro9,2                         | 2         | 0.93%   |
| WYSE Z CLASS                                | 1         | 0.46%   |
| TUXEDO Aura 15 Gen1                         | 1         | 0.46%   |
| Toshiba Satellite Pro U400                  | 1         | 0.46%   |
| Toshiba Satellite L855                      | 1         | 0.46%   |
| Toshiba Satellite L500                      | 1         | 0.46%   |
| Toshiba Satellite C640                      | 1         | 0.46%   |
| Toshiba PORTEGE Z10t-A                      | 1         | 0.46%   |
| Toshiba PORTEGE R930                        | 1         | 0.46%   |
| Sony VPCEJ1E1E                              | 1         | 0.46%   |
| Shuttle NC10U                               | 1         | 0.46%   |
| Sapphire EDGE-FT1M1 E450 1AOVU044           | 1         | 0.46%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 1         | 0.46%   |
| Samsung Galaxy Book 12                      | 1         | 0.46%   |
| Samsung 530U3C/530U4C/532U3C                | 1         | 0.46%   |
| Protectli FW2B                              | 1         | 0.46%   |
| Pegatron SAISHIAT2                          | 1         | 0.46%   |
| Pegatron IPM41-D3                           | 1         | 0.46%   |
| PCPartner DREAMSYS                          | 1         | 0.46%   |
| Packard Bell imedia S2110                   | 1         | 0.46%   |
| Packard Bell EasyNote MH36                  | 1         | 0.46%   |
| NEC Computers PC-VK17HBBCD                  | 1         | 0.46%   |
| MSI WC791AA-UUW HPE-119sc                   | 1         | 0.46%   |
| MSI MS-7C37                                 | 1         | 0.46%   |
| MSI MS-7B86                                 | 1         | 0.46%   |
| MSI MS-7B84                                 | 1         | 0.46%   |
| MSI MS-7A15                                 | 1         | 0.46%   |
| MSI MS-7982                                 | 1         | 0.46%   |
| MSI GF65 Thin 10SDR                         | 1         | 0.46%   |
| MouseComputer W331AU                        | 1         | 0.46%   |
| Microsoft Surface Go                        | 1         | 0.46%   |
| Medion H61H2-LM3                            | 1         | 0.46%   |
| LG 14Z980-G.BH51P1                          | 1         | 0.46%   |
| Lenovo ZIUS6                                | 1         | 0.46%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS          | 1         | 0.46%   |
| Lenovo ThinkPad X260 20F5S82N00             | 1         | 0.46%   |
| Lenovo ThinkPad X250 20CLS4JH00             | 1         | 0.46%   |
| Lenovo ThinkPad X240 20AMS39F0K             | 1         | 0.46%   |
| Lenovo ThinkPad X230 2330A48                | 1         | 0.46%   |
| Lenovo ThinkPad X230 2325WWB                | 1         | 0.46%   |
| Lenovo ThinkPad X230 23255Y4                | 1         | 0.46%   |
| Lenovo ThinkPad X200 7458VP4                | 1         | 0.46%   |
| Lenovo ThinkPad T61 64607EU                 | 1         | 0.46%   |
| Lenovo ThinkPad T490 20RYS06R00             | 1         | 0.46%   |
| Lenovo ThinkPad T470p 20J6A012CD            | 1         | 0.46%   |
| Lenovo ThinkPad T440s 20ARS1B704            | 1         | 0.46%   |
| Lenovo ThinkPad T420 4236FJ1                | 1         | 0.46%   |
| Lenovo ThinkPad L450 20DTCTO1WW             | 1         | 0.46%   |
| Lenovo ThinkPad Edge E530 62724FU           | 1         | 0.46%   |
| Lenovo ThinkPad E420 1141A83                | 1         | 0.46%   |
| Lenovo ThinkCentre M91p 7033DE6             | 1         | 0.46%   |
| Lenovo ThinkCentre M91p 7033D54             | 1         | 0.46%   |
| Lenovo ThinkCentre M83 10AHS35Q00           | 1         | 0.46%   |
| Lenovo ThinkCentre M720s 10SUS4WT00         | 1         | 0.46%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 15        | 6.94%   |
| Dell Latitude              | 8         | 3.7%    |
| Dell Inspiron              | 7         | 3.24%   |
| HP Pavilion                | 6         | 2.78%   |
| Dell OptiPlex              | 5         | 2.31%   |
| ASUS PRIME                 | 5         | 2.31%   |
| Toshiba Satellite          | 4         | 1.85%   |
| Lenovo ThinkCentre         | 4         | 1.85%   |
| Dell Precision             | 4         | 1.85%   |
| Acer Aspire                | 4         | 1.85%   |
| Toshiba PORTEGE            | 2         | 0.93%   |
| Lenovo IdeaPad             | 2         | 0.93%   |
| HP ProBook                 | 2         | 0.93%   |
| HP EliteBook               | 2         | 0.93%   |
| HP Compaq                  | 2         | 0.93%   |
| Gateway NE56R              | 2         | 0.93%   |
| Dell Vostro                | 2         | 0.93%   |
| ASUS VivoBook              | 2         | 0.93%   |
| ASUS ROG                   | 2         | 0.93%   |
| ASUS P8Z77-V               | 2         | 0.93%   |
| ASUS M5A78L-M              | 2         | 0.93%   |
| ASUS All                   | 2         | 0.93%   |
| ASRock B550M               | 2         | 0.93%   |
| ASRock B450M               | 2         | 0.93%   |
| Apple MacBookPro9          | 2         | 0.93%   |
| WYSE Z                     | 1         | 0.46%   |
| TUXEDO Aura                | 1         | 0.46%   |
| Sony VPCEJ1E1E             | 1         | 0.46%   |
| Shuttle NC10U              | 1         | 0.46%   |
| Sapphire EDGE-FT1M1        | 1         | 0.46%   |
| Samsung RV411              | 1         | 0.46%   |
| Samsung Galaxy             | 1         | 0.46%   |
| Samsung 530U3C             | 1         | 0.46%   |
| Protectli FW2B             | 1         | 0.46%   |
| Pegatron SAISHIAT2         | 1         | 0.46%   |
| Pegatron IPM41-D3          | 1         | 0.46%   |
| PCPartner DREAMSYS         | 1         | 0.46%   |
| Packard Bell imedia        | 1         | 0.46%   |
| Packard Bell EasyNote      | 1         | 0.46%   |
| NEC Computers PC-VK17HBBCD | 1         | 0.46%   |
| MSI WC791AA-UUW            | 1         | 0.46%   |
| MSI MS-7C37                | 1         | 0.46%   |
| MSI MS-7B86                | 1         | 0.46%   |
| MSI MS-7B84                | 1         | 0.46%   |
| MSI MS-7A15                | 1         | 0.46%   |
| MSI MS-7982                | 1         | 0.46%   |
| MSI GF65                   | 1         | 0.46%   |
| MouseComputer W331AU       | 1         | 0.46%   |
| Microsoft Surface          | 1         | 0.46%   |
| Medion H61H2-LM3           | 1         | 0.46%   |
| LG 14Z980-G.BH51P1         | 1         | 0.46%   |
| Lenovo ZIUS6               | 1         | 0.46%   |
| Lenovo Yoga                | 1         | 0.46%   |
| Lenovo Legion              | 1         | 0.46%   |
| Lenovo IdeaCentre          | 1         | 0.46%   |
| Lenovo G550                | 1         | 0.46%   |
| Lenovo G500                | 1         | 0.46%   |
| Lenovo G470                | 1         | 0.46%   |
| Lenovo B41-80              | 1         | 0.46%   |
| Lenovo 70F8S01J00          | 1         | 0.46%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 35        | 16.2%   |
| 2019 | 31        | 14.35%  |
| 2013 | 23        | 10.65%  |
| 2012 | 19        | 8.8%    |
| 2018 | 18        | 8.33%   |
| 2021 | 16        | 7.41%   |
| 2011 | 15        | 6.94%   |
| 2014 | 12        | 5.56%   |
| 2015 | 11        | 5.09%   |
| 2010 | 11        | 5.09%   |
| 2009 | 8         | 3.7%    |
| 2017 | 7         | 3.24%   |
| 2016 | 6         | 2.78%   |
| 2008 | 4         | 1.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 106       | 49.07%  |
| Notebook    | 98        | 45.37%  |
| All in one  | 4         | 1.85%   |
| Mini pc     | 3         | 1.39%   |
| Tablet      | 2         | 0.93%   |
| Server      | 2         | 0.93%   |
| Convertible | 1         | 0.46%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 215       | 99.54%  |
| Yes  | 1         | 0.46%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 79        | 36.57%  |
| 8.01-16.0   | 73        | 33.8%   |
| 16.01-24.0  | 48        | 22.22%  |
| 32.01-64.0  | 10        | 4.63%   |
| 24.01-32.0  | 3         | 1.39%   |
| 64.01-256.0 | 2         | 0.93%   |
| 2.01-3.0    | 1         | 0.46%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 132       | 60.83%  |
| 0.51-1.0  | 61        | 28.11%  |
| 1.01-2.0  | 18        | 8.29%   |
| 2.01-3.0  | 4         | 1.84%   |
| 4.01-8.0  | 1         | 0.46%   |
| 8.01-16.0 | 1         | 0.46%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 134       | 61.19%  |
| 2      | 45        | 20.55%  |
| 0      | 14        | 6.39%   |
| 3      | 13        | 5.94%   |
| 4      | 7         | 3.2%    |
| 6      | 3         | 1.37%   |
| 10     | 1         | 0.46%   |
| 8      | 1         | 0.46%   |
| 5      | 1         | 0.46%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 122       | 56.48%  |
| Yes       | 94        | 43.52%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 198       | 91.67%  |
| No        | 18        | 8.33%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 142       | 65.44%  |
| No        | 75        | 34.56%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 118       | 54.63%  |
| Yes       | 98        | 45.37%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 40        | 18.43%  |
| Germany            | 16        | 7.37%   |
| Brazil             | 13        | 5.99%   |
| UK                 | 12        | 5.53%   |
| Canada             | 10        | 4.61%   |
| China              | 9         | 4.15%   |
| Russia             | 8         | 3.69%   |
| Netherlands        | 8         | 3.69%   |
| Italy              | 8         | 3.69%   |
| Spain              | 7         | 3.23%   |
| Australia          | 7         | 3.23%   |
| Ukraine            | 6         | 2.76%   |
| Sweden             | 5         | 2.3%    |
| France             | 5         | 2.3%    |
| Poland             | 4         | 1.84%   |
| Mexico             | 4         | 1.84%   |
| India              | 4         | 1.84%   |
| Taiwan             | 3         | 1.38%   |
| South Korea        | 3         | 1.38%   |
| Indonesia          | 3         | 1.38%   |
| Argentina          | 3         | 1.38%   |
| Switzerland        | 2         | 0.92%   |
| Slovakia           | 2         | 0.92%   |
| Portugal           | 2         | 0.92%   |
| Lithuania          | 2         | 0.92%   |
| Hungary            | 2         | 0.92%   |
| Greece             | 2         | 0.92%   |
| Finland            | 2         | 0.92%   |
| Belarus            | 2         | 0.92%   |
| Venezuela          | 1         | 0.46%   |
| Uruguay            | 1         | 0.46%   |
| Turkey             | 1         | 0.46%   |
| South Africa       | 1         | 0.46%   |
| Puerto Rico        | 1         | 0.46%   |
| Peru               | 1         | 0.46%   |
| Oman               | 1         | 0.46%   |
| Norway             | 1         | 0.46%   |
| New Zealand        | 1         | 0.46%   |
| Morocco            | 1         | 0.46%   |
| Malaysia           | 1         | 0.46%   |
| Latvia             | 1         | 0.46%   |
| Japan              | 1         | 0.46%   |
| Guatemala          | 1         | 0.46%   |
| Eswatini           | 1         | 0.46%   |
| Egypt              | 1         | 0.46%   |
| Dominican Republic | 1         | 0.46%   |
| Cyprus             | 1         | 0.46%   |
| Croatia            | 1         | 0.46%   |
| Chile              | 1         | 0.46%   |
| Bulgaria           | 1         | 0.46%   |
| Belgium            | 1         | 0.46%   |
| Austria            | 1         | 0.46%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City            | Computers | Percent |
|-----------------|-----------|---------|
| Brisbane        | 3         | 1.36%   |
| Zurich          | 2         | 0.91%   |
| São Paulo      | 2         | 0.91%   |
| New York        | 2         | 0.91%   |
| Mar del Plata   | 2         | 0.91%   |
| Jakarta         | 2         | 0.91%   |
| Dnipropetrovsk  | 2         | 0.91%   |
| Curitiba        | 2         | 0.91%   |
| Chicago         | 2         | 0.91%   |
| Calgary         | 2         | 0.91%   |
| Berlin          | 2         | 0.91%   |
| Athens          | 2         | 0.91%   |
| Aberdeen        | 2         | 0.91%   |
| Šiauliai       | 1         | 0.45%   |
| Zhongshan       | 1         | 0.45%   |
| Zhengzhou       | 1         | 0.45%   |
| Zagreb          | 1         | 0.45%   |
| York            | 1         | 0.45%   |
| Yekaterinburg   | 1         | 0.45%   |
| Wuhan           | 1         | 0.45%   |
| Wroclaw         | 1         | 0.45%   |
| Winnipeg        | 1         | 0.45%   |
| Washington      | 1         | 0.45%   |
| Warmond         | 1         | 0.45%   |
| Wandur          | 1         | 0.45%   |
| Vladivostok     | 1         | 0.45%   |
| Vitória        | 1         | 0.45%   |
| Villeurbanne    | 1         | 0.45%   |
| Vigonovo        | 1         | 0.45%   |
| Vienna          | 1         | 0.45%   |
| V?�ster??s      | 1         | 0.45%   |
| Vawkavysk       | 1         | 0.45%   |
| Vancouver       | 1         | 0.45%   |
| Utrecht         | 1         | 0.45%   |
| Ufa             | 1         | 0.45%   |
| Tula de Allende | 1         | 0.45%   |
| Treviso         | 1         | 0.45%   |
| Traverse City   | 1         | 0.45%   |
| Toronto         | 1         | 0.45%   |
| The Bronx       | 1         | 0.45%   |
| Tettnang Castle | 1         | 0.45%   |
| Tangara         | 1         | 0.45%   |
| Tampere         | 1         | 0.45%   |
| Taichung        | 1         | 0.45%   |
| Taganrog        | 1         | 0.45%   |
| Sydney          | 1         | 0.45%   |
| Suzhou          | 1         | 0.45%   |
| Surabaya        | 1         | 0.45%   |
| Sungai Buloh    | 1         | 0.45%   |
| St Petersburg   | 1         | 0.45%   |
| Solarino        | 1         | 0.45%   |
| Sofia           | 1         | 0.45%   |
| Simpsonville    | 1         | 0.45%   |
| Shibakoen       | 1         | 0.45%   |
| Sherwood Park   | 1         | 0.45%   |
| Sheffield       | 1         | 0.45%   |
| Shasta          | 1         | 0.45%   |
| Sevastopol      | 1         | 0.45%   |
| Seoul           | 1         | 0.45%   |
| S??o Paulo      | 1         | 0.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 51        | 67     | 17.96%  |
| Seagate             | 46        | 66     | 16.2%   |
| Samsung Electronics | 44        | 59     | 15.49%  |
| Toshiba             | 20        | 20     | 7.04%   |
| Crucial             | 14        | 15     | 4.93%   |
| SanDisk             | 13        | 14     | 4.58%   |
| Hitachi             | 13        | 15     | 4.58%   |
| Kingston            | 12        | 13     | 4.23%   |
| Intel               | 10        | 10     | 3.52%   |
| A-DATA Technology   | 8         | 13     | 2.82%   |
| HGST                | 7         | 7      | 2.46%   |
| Apple               | 7         | 7      | 2.46%   |
| SPCC                | 4         | 5      | 1.41%   |
| SK Hynix            | 3         | 3      | 1.06%   |
| PNY                 | 3         | 10     | 1.06%   |
| Hewlett-Packard     | 3         | 4      | 1.06%   |
| Fujitsu             | 3         | 4      | 1.06%   |
| Transcend           | 2         | 3      | 0.7%    |
| Silicon Motion      | 2         | 2      | 0.7%    |
| OCZ                 | 2         | 2      | 0.7%    |
| LITEON              | 2         | 2      | 0.7%    |
| KingSpec            | 2         | 2      | 0.7%    |
| Apacer              | 2         | 2      | 0.7%    |
| SMART               | 1         | 1      | 0.35%   |
| Phison              | 1         | 1      | 0.35%   |
| Patriot             | 1         | 1      | 0.35%   |
| ORICO               | 1         | 2      | 0.35%   |
| MyDigitalSSD        | 1         | 1      | 0.35%   |
| Micron Technology   | 1         | 1      | 0.35%   |
| LSI                 | 1         | 1      | 0.35%   |
| LITEONIT            | 1         | 1      | 0.35%   |
| Lenovo              | 1         | 1      | 0.35%   |
| HPE                 | 1         | 1      | 0.35%   |
| CLOVER              | 1         | 1      | 0.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB           | 6         | 1.92%   |
| A-DATA SU650 120GB                  | 4         | 1.28%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 3         | 0.96%   |
| Seagate ST500DM002-1BD142 500GB     | 3         | 0.96%   |
| Seagate ST3250410AS 250GB           | 3         | 0.96%   |
| Seagate ST1000LM035-1RK172 1TB      | 3         | 0.96%   |
| Seagate ST1000DM003-1ER162 1TB      | 3         | 0.96%   |
| Samsung SSD 860 EVO 250GB           | 3         | 0.96%   |
| Samsung SSD 860 EVO 1TB             | 3         | 0.96%   |
| WDC WD20EARS-00MVWB0 2TB            | 2         | 0.64%   |
| WDC WD10EZEX-08WN4A0 1TB            | 2         | 0.64%   |
| Seagate ST9500325AS 500GB           | 2         | 0.64%   |
| Seagate ST380815AS 80GB             | 2         | 0.64%   |
| Seagate ST3250318AS 250GB           | 2         | 0.64%   |
| Seagate ST31000528AS 1TB            | 2         | 0.64%   |
| SanDisk SDSSDP128G 128GB            | 2         | 0.64%   |
| SanDisk SDSSDA240G 240GB            | 2         | 0.64%   |
| Samsung SSD 970 EVO Plus 250GB      | 2         | 0.64%   |
| Samsung SSD 860 EVO 500GB           | 2         | 0.64%   |
| Samsung SSD 840 EVO 250GB           | 2         | 0.64%   |
| Samsung HN-M101MBB 1TB              | 2         | 0.64%   |
| Kingston SA400S37240G 240GB         | 2         | 0.64%   |
| Kingston SA400S37120G 120GB         | 2         | 0.64%   |
| Intel SSDSC2KW256G8 256GB           | 2         | 0.64%   |
| Intel SSDPEKNW512G8 512GB           | 2         | 0.64%   |
| Hitachi HTS727550A9E364 500GB       | 2         | 0.64%   |
| HGST HTS725050A7E630 500GB          | 2         | 0.64%   |
| HGST HTS545032A7E380 320GB          | 2         | 0.64%   |
| Crucial CT1000P1SSD8 1TB            | 2         | 0.64%   |
| Crucial CT1000MX500SSD1 1TB         | 2         | 0.64%   |
| Apple HDD HTS545050A7E362 500GB     | 2         | 0.64%   |
| A-DATA SX8200PNP 256GB              | 2         | 0.64%   |
| WDC WDS500G3X0C-00SJG0 500GB        | 1         | 0.32%   |
| WDC WDS500G2B0A-00SM50 500GB        | 1         | 0.32%   |
| WDC WDS250G3X0C-00SJG0 250GB        | 1         | 0.32%   |
| WDC WDS250G1B0A-00H9H0 250GB        | 1         | 0.32%   |
| WDC WDS240G2G0A-00JH30 240GB        | 1         | 0.32%   |
| WDC WDS100T2B0A-00SM50 1TB          | 1         | 0.32%   |
| WDC WDBNCE2500PNC 250GB             | 1         | 0.32%   |
| WDC WD800JD-55MUA1 80GB             | 1         | 0.32%   |
| WDC WD800BEVS-00RST0 80GB           | 1         | 0.32%   |
| WDC WD7500BPVX-60JC3T0 752GB        | 1         | 0.32%   |
| WDC WD7500BPKX-00HPJT0 752GB        | 1         | 0.32%   |
| WDC WD6400AAKS-22A7B0 640GB         | 1         | 0.32%   |
| WDC WD5002ABYS-02B1B0 500GB         | 1         | 0.32%   |
| WDC WD5000LPVX-60V0TT0 500GB        | 1         | 0.32%   |
| WDC WD5000LPVX-00V0TT0 500GB        | 1         | 0.32%   |
| WDC WD5000BEVT-22ZAT0 500GB         | 1         | 0.32%   |
| WDC WD5000AZRX-00L4HB0 500GB        | 1         | 0.32%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 1         | 0.32%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 1         | 0.32%   |
| WDC WD5000AAKS-00A7B2 500GB         | 1         | 0.32%   |
| WDC WD40EFRX-68WT0N0 4TB            | 1         | 0.32%   |
| WDC WD400BD-75LRA0 40GB             | 1         | 0.32%   |
| WDC WD4004FZWX-00GBGB0 4TB          | 1         | 0.32%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 1         | 0.32%   |
| WDC WD3200BEVT-60ZCT1 320GB         | 1         | 0.32%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 1         | 0.32%   |
| WDC WD3200BEVT-00A0RT0 233GB        | 1         | 0.32%   |
| WDC WD3200BEKT-75PVMT1 320GB        | 1         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 46        | 66     | 32.86%  |
| WDC                 | 42        | 56     | 30%     |
| Hitachi             | 13        | 15     | 9.29%   |
| Toshiba             | 12        | 12     | 8.57%   |
| Samsung Electronics | 11        | 13     | 7.86%   |
| HGST                | 7         | 7      | 5%      |
| Fujitsu             | 3         | 4      | 2.14%   |
| Apple               | 3         | 3      | 2.14%   |
| LSI                 | 1         | 1      | 0.71%   |
| Hewlett-Packard     | 1         | 1      | 0.71%   |
| CLOVER              | 1         | 1      | 0.71%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 28        | 35     | 24.78%  |
| SanDisk             | 13        | 14     | 11.5%   |
| Kingston            | 11        | 11     | 9.73%   |
| Crucial             | 11        | 12     | 9.73%   |
| Intel               | 7         | 7      | 6.19%   |
| WDC                 | 5         | 6      | 4.42%   |
| A-DATA Technology   | 5         | 6      | 4.42%   |
| Toshiba             | 4         | 4      | 3.54%   |
| SPCC                | 4         | 5      | 3.54%   |
| PNY                 | 3         | 8      | 2.65%   |
| Apple               | 3         | 3      | 2.65%   |
| Transcend           | 2         | 3      | 1.77%   |
| OCZ                 | 2         | 2      | 1.77%   |
| LITEON              | 2         | 2      | 1.77%   |
| KingSpec            | 2         | 2      | 1.77%   |
| Apacer              | 2         | 2      | 1.77%   |
| SMART               | 1         | 1      | 0.88%   |
| Patriot             | 1         | 1      | 0.88%   |
| ORICO               | 1         | 2      | 0.88%   |
| MyDigitalSSD        | 1         | 1      | 0.88%   |
| Micron Technology   | 1         | 1      | 0.88%   |
| LITEONIT            | 1         | 1      | 0.88%   |
| Lenovo              | 1         | 1      | 0.88%   |
| HPE                 | 1         | 1      | 0.88%   |
| Hewlett-Packard     | 1         | 2      | 0.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 121       | 179    | 46.72%  |
| SSD  | 100       | 133    | 38.61%  |
| NVMe | 38        | 45     | 14.67%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 190       | 312    | 83.33%  |
| NVMe | 38        | 45     | 16.67%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 156       | 217    | 68.42%  |
| 0.51-1.0   | 51        | 65     | 22.37%  |
| 1.01-2.0   | 13        | 17     | 5.7%    |
| 3.01-4.0   | 4         | 5      | 1.75%   |
| 2.01-3.0   | 2         | 5      | 0.88%   |
| 4.01-10.0  | 2         | 3      | 0.88%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 140       | 63.93%  |
| 101-250    | 29        | 13.24%  |
| 251-500    | 21        | 9.59%   |
| 501-1000   | 16        | 7.31%   |
| 51-100     | 7         | 3.2%    |
| 21-50      | 4         | 1.83%   |
| 1001-2000  | 2         | 0.91%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 216       | 100%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Seagate ST3250410AS 250GB                | 3         | 3      | 4.84%   |
| Seagate ST380815AS 80GB                  | 2         | 2      | 3.23%   |
| HGST HTS545032A7E380 320GB               | 2         | 2      | 3.23%   |
| Apple HDD HTS545050A7E362 500GB          | 2         | 2      | 3.23%   |
| WDC WD800JD-55MUA1 80GB                  | 1         | 1      | 1.61%   |
| WDC WD6400AAKS-22A7B0 640GB              | 1         | 1      | 1.61%   |
| WDC WD5000LPVX-60V0TT0 500GB             | 1         | 1      | 1.61%   |
| WDC WD5000AAKX-60U6AA0 500GB             | 1         | 1      | 1.61%   |
| WDC WD5000AAKX-00ERMA0 500GB             | 1         | 1      | 1.61%   |
| WDC WD40EFRX-68WT0N0 4TB                 | 1         | 1      | 1.61%   |
| WDC WD3200BEVT-22ZCT0 320GB              | 1         | 1      | 1.61%   |
| WDC WD3200BEVT-00A0RT0 233GB             | 1         | 1      | 1.61%   |
| WDC WD3200AAJS-00L7A0 320GB              | 1         | 1      | 1.61%   |
| WDC WD2500AAKX-083CA1 250GB              | 1         | 1      | 1.61%   |
| WDC WD20EARS-00MVWB0 2TB                 | 1         | 1      | 1.61%   |
| WDC WD1600AAJS-00WAA0 160GB              | 1         | 1      | 1.61%   |
| WDC WD10EARS-00Y5B1 1TB                  | 1         | 1      | 1.61%   |
| Toshiba THNSNK128GCS8 SATA 128GB         | 1         | 1      | 1.61%   |
| Toshiba MQ01ABD075 752GB                 | 1         | 1      | 1.61%   |
| Toshiba MQ01ABD032 320GB                 | 1         | 1      | 1.61%   |
| Toshiba MK3276GSX 320GB                  | 1         | 1      | 1.61%   |
| Toshiba MK3265GSXN 320GB                 | 1         | 1      | 1.61%   |
| Toshiba MK3261GSYN 320GB                 | 1         | 1      | 1.61%   |
| Seagate ST9500325AS 500GB                | 1         | 1      | 1.61%   |
| Seagate ST9320423AS 320GB                | 1         | 1      | 1.61%   |
| Seagate ST9160412AS 160GB                | 1         | 1      | 1.61%   |
| Seagate ST500VT000-1DK142 500GB          | 1         | 1      | 1.61%   |
| Seagate ST500LM012 HN-M500MBB 500GB      | 1         | 1      | 1.61%   |
| Seagate ST3500413AS 500GB                | 1         | 1      | 1.61%   |
| Seagate ST3250318AS 250GB                | 1         | 1      | 1.61%   |
| Seagate ST320LT012-9WS14C 320GB          | 1         | 2      | 1.61%   |
| Seagate ST31000528AS 1TB                 | 1         | 1      | 1.61%   |
| Seagate ST31000333AS 1TB                 | 1         | 1      | 1.61%   |
| Seagate ST1000LM049-2GH172 1TB           | 1         | 1      | 1.61%   |
| Seagate ST1000LM035-1RK172 1TB           | 1         | 1      | 1.61%   |
| Samsung Electronics SSD 840 Series 500GB | 1         | 1      | 1.61%   |
| Samsung Electronics SP2004C 200GB        | 1         | 1      | 1.61%   |
| Samsung Electronics HD642JJ 640GB        | 1         | 1      | 1.61%   |
| Samsung Electronics HD321KJ 320GB        | 1         | 1      | 1.61%   |
| Samsung Electronics HD161HJ 160GB        | 1         | 1      | 1.61%   |
| Kingston RBU-SNS8350DES3128GP 128GB      | 1         | 1      | 1.61%   |
| Hitachi HTS727550A9E364 500GB            | 1         | 1      | 1.61%   |
| Hitachi HTS723232A7A364 320GB            | 1         | 1      | 1.61%   |
| Hitachi HTS545050B9A300 500GB            | 1         | 1      | 1.61%   |
| Hitachi HTS545050A7E380 500GB            | 1         | 1      | 1.61%   |
| Hitachi HTS545032B9A300 320GB            | 1         | 1      | 1.61%   |
| Hitachi HTS545025B9SA02 250GB            | 1         | 1      | 1.61%   |
| Hitachi HDS721050CLA362 500GB            | 1         | 1      | 1.61%   |
| Hitachi HDP725025GLA380 250GB            | 1         | 1      | 1.61%   |
| HGST HTS725050A7E630 500GB               | 1         | 1      | 1.61%   |
| HGST HTS721010A9E630 1TB                 | 1         | 1      | 1.61%   |
| HGST HTS541010A9E680 1TB                 | 1         | 1      | 1.61%   |
| Hewlett-Packard SSD S700 1TB             | 1         | 1      | 1.61%   |
| Fujitsu MHZ2250BH G1 250GB               | 1         | 1      | 1.61%   |
| Fujitsu MHW2160BH 160GB                  | 1         | 1      | 1.61%   |
| Crucial CT525MX300SSD1 528GB             | 1         | 2      | 1.61%   |
| Apple HDD HTS541010A9E662 1TB            | 1         | 1      | 1.61%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 18     | 26.23%  |
| WDC                 | 13        | 13     | 21.31%  |
| Hitachi             | 8         | 8      | 13.11%  |
| Toshiba             | 6         | 6      | 9.84%   |
| Samsung Electronics | 5         | 5      | 8.2%    |
| HGST                | 5         | 5      | 8.2%    |
| Apple               | 3         | 3      | 4.92%   |
| Fujitsu             | 2         | 2      | 3.28%   |
| Kingston            | 1         | 1      | 1.64%   |
| Hewlett-Packard     | 1         | 1      | 1.64%   |
| Crucial             | 1         | 2      | 1.64%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 18     | 28.57%  |
| WDC                 | 13        | 13     | 23.21%  |
| Hitachi             | 8         | 8      | 14.29%  |
| Toshiba             | 5         | 5      | 8.93%   |
| HGST                | 5         | 5      | 8.93%   |
| Samsung Electronics | 4         | 4      | 7.14%   |
| Apple               | 3         | 3      | 5.36%   |
| Fujitsu             | 2         | 2      | 3.57%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 52        | 58     | 91.23%  |
| SSD  | 5         | 6      | 8.77%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                      | Computers | Drives | Percent |
|----------------------------|-----------|--------|---------|
| HPE MK000480GWUGF 480GB    | 1         | 1      | 50%     |
| HGST HTS725050A7E630 500GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| HPE    | 1         | 1      | 50%     |
| HGST   | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 165       | 280    | 71.74%  |
| Malfunc  | 57        | 64     | 24.78%  |
| Detected | 6         | 11     | 2.61%   |
| Failed   | 2         | 2      | 0.87%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 172       | 64.42%  |
| AMD                         | 36        | 13.48%  |
| Samsung Electronics         | 12        | 4.49%   |
| ASMedia Technology          | 6         | 2.25%   |
| Sandisk                     | 5         | 1.87%   |
| Broadcom / LSI              | 5         | 1.87%   |
| Toshiba                     | 3         | 1.12%   |
| SK Hynix                    | 3         | 1.12%   |
| Silicon Motion              | 3         | 1.12%   |
| Micron/Crucial Technology   | 3         | 1.12%   |
| VIA Technologies            | 2         | 0.75%   |
| Phison Electronics          | 2         | 0.75%   |
| Nvidia                      | 2         | 0.75%   |
| Kingston Technology Company | 2         | 0.75%   |
| JMicron Technology          | 2         | 0.75%   |
| ADATA Technology            | 2         | 0.75%   |
| Adaptec                     | 2         | 0.75%   |
| Silicon Image               | 1         | 0.37%   |
| Realtek Semiconductor       | 1         | 0.37%   |
| Marvell Technology Group    | 1         | 0.37%   |
| KIOXIA                      | 1         | 0.37%   |
| Hewlett-Packard             | 1         | 0.37%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 20        | 6.45%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 18        | 5.81%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 13        | 4.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 11        | 3.55%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 10        | 3.23%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 9         | 2.9%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 8         | 2.58%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 7         | 2.26%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 7         | 2.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 7         | 2.26%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 7         | 2.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7         | 2.26%   |
| AMD 400 Series Chipset SATA Controller                                                  | 7         | 2.26%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 6         | 1.94%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6         | 1.94%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6         | 1.94%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 5         | 1.61%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5         | 1.61%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5         | 1.61%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 5         | 1.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 4         | 1.29%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3         | 0.97%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3         | 0.97%   |
| Intel SSD 660P Series                                                                   | 3         | 0.97%   |
| Intel SATA Controller [RAID mode]                                                       | 3         | 0.97%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3         | 0.97%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 3         | 0.97%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 3         | 0.97%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 3         | 0.97%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3         | 0.97%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3         | 0.97%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 3         | 0.97%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 3         | 0.97%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 3         | 0.97%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3         | 0.97%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 3         | 0.97%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 2         | 0.65%   |
| Toshiba unknown                                                                         | 2         | 0.65%   |
| SK Hynix NVMe SSD Controller                                                            | 2         | 0.65%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 2         | 0.65%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2         | 0.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2         | 0.65%   |
| Nvidia MCP61 SATA Controller                                                            | 2         | 0.65%   |
| Nvidia MCP61 IDE                                                                        | 2         | 0.65%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 2         | 0.65%   |
| Kingston Company A2000 NVMe SSD                                                         | 2         | 0.65%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2         | 0.65%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 2         | 0.65%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 2         | 0.65%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 2         | 0.65%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 2         | 0.65%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 2         | 0.65%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 2         | 0.65%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2         | 0.65%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 2         | 0.65%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 2         | 0.65%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 0.65%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 0.65%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 2         | 0.65%   |
| AMD FCH SATA Controller D                                                               | 2         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 174       | 63.97%  |
| NVMe | 38        | 13.97%  |
| IDE  | 37        | 13.6%   |
| RAID | 17        | 6.25%   |
| SAS  | 3         | 1.1%    |
| SCSI | 3         | 1.1%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 176       | 81.48%  |
| AMD    | 40        | 18.52%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Xeon                                  | 5         | 2.31%   |
| Intel CPU Version                           | 5         | 2.31%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 4         | 1.85%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 4         | 1.85%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 3         | 1.39%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 3         | 1.39%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3         | 1.39%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 3         | 1.39%   |
| Intel Core i7-4510U CPU @ 2.00GHz           | 2         | 0.93%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 2         | 0.93%   |
| Intel Core i7 CPU M 620 @ 2.67GHz           | 2         | 0.93%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 0.93%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 2         | 0.93%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 0.93%   |
| Intel Core i5-3340M CPU @ 2.70GHz           | 2         | 0.93%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 0.93%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 0.93%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 2         | 0.93%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 2         | 0.93%   |
| Intel Core i3-2370M CPU @ 2.40GHz           | 2         | 0.93%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 2         | 0.93%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 2         | 0.93%   |
| Intel Core 2 Duo                            | 2         | 0.93%   |
| Intel Celeron CPU N3450 @ 1.10GHz           | 2         | 0.93%   |
| Intel Celeron CPU G3930 @ 2.90GHz           | 2         | 0.93%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 2         | 0.93%   |
| Intel Xeon CPU X3470                        | 1         | 0.46%   |
| Intel Xeon CPU W3550 @ 3.07GHz              | 1         | 0.46%   |
| Intel Xeon CPU E5530 @ 2.40GHz              | 1         | 0.46%   |
| Intel Xeon CPU E5-2630L 0 @ 2.00GHz         | 1         | 0.46%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz         | 1         | 0.46%   |
| Intel Xeon CPU E5-1603 @ 2.80GHz            | 1         | 0.46%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz         | 1         | 0.46%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz         | 1         | 0.46%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 1         | 0.46%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1         | 0.46%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 1         | 0.46%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1         | 0.46%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 1         | 0.46%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 1         | 0.46%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1         | 0.46%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1         | 0.46%   |
| Intel Pentium CPU G3460 @ 3.50GHz           | 1         | 0.46%   |
| Intel Pentium CPU G3420 @ 3.20GHz           | 1         | 0.46%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1         | 0.46%   |
| Intel Pentium CPU B940 @ 2.00GHz            | 1         | 0.46%   |
| Intel Pentium CPU 4415Y @ 1.60GHz           | 1         | 0.46%   |
| Intel Pentium 4 CPU 3.60GHz                 | 1         | 0.46%   |
| Intel Genuine CPU 0000 @ 2.10GHz            | 1         | 0.46%   |
| Intel Genuine CPU                           | 1         | 0.46%   |
| Intel Core i9-7920X CPU @ 2.90GHz           | 1         | 0.46%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 1         | 0.46%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1         | 0.46%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1         | 0.46%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 0.46%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1         | 0.46%   |
| Intel Core i7-7567U CPU @ 3.50GHz           | 1         | 0.46%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.46%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 1         | 0.46%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 58        | 26.85%  |
| Intel Core i3           | 31        | 14.35%  |
| Intel Core i7           | 27        | 12.5%   |
| Intel Celeron           | 15        | 6.94%   |
| Intel Xeon              | 13        | 6.02%   |
| Intel Core 2 Duo        | 9         | 4.17%   |
| Intel Pentium           | 8         | 3.7%    |
| AMD Ryzen 5             | 7         | 3.24%   |
| Other                   | 5         | 2.31%   |
| AMD Ryzen 7             | 5         | 2.31%   |
| AMD FX                  | 5         | 2.31%   |
| Intel Pentium Dual-Core | 4         | 1.85%   |
| AMD Ryzen 3             | 4         | 1.85%   |
| Intel Genuine           | 2         | 0.93%   |
| AMD Ryzen 9             | 2         | 0.93%   |
| AMD Phenom II X4        | 2         | 0.93%   |
| AMD E1                  | 2         | 0.93%   |
| AMD Athlon II X4        | 2         | 0.93%   |
| AMD A6                  | 2         | 0.93%   |
| AMD A10                 | 2         | 0.93%   |
| Intel Pentium Gold      | 1         | 0.46%   |
| Intel Pentium 4         | 1         | 0.46%   |
| Intel Core i9           | 1         | 0.46%   |
| Intel Core 2 Solo       | 1         | 0.46%   |
| AMD Phenom II X6        | 1         | 0.46%   |
| AMD Phenom II           | 1         | 0.46%   |
| AMD G                   | 1         | 0.46%   |
| AMD E                   | 1         | 0.46%   |
| AMD Athlon II X2        | 1         | 0.46%   |
| AMD Athlon II           | 1         | 0.46%   |
| AMD Athlon              | 1         | 0.46%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 108       | 50%     |
| 4       | 62        | 28.7%   |
| 6       | 17        | 7.87%   |
| 8       | 11        | 5.09%   |
| Unknown | 7         | 3.24%   |
| 16      | 4         | 1.85%   |
| 12      | 4         | 1.85%   |
| 24      | 2         | 0.93%   |
| 1       | 1         | 0.46%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 211       | 97.69%  |
| 2      | 5         | 2.31%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 106       | 49.07%  |
| 1       | 102       | 47.22%  |
| Unknown | 8         | 3.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 32        | 14.81%  |
| IvyBridge     | 26        | 12.04%  |
| SandyBridge   | 24        | 11.11%  |
| Haswell       | 20        | 9.26%   |
| Penryn        | 17        | 7.87%   |
| Skylake       | 16        | 7.41%   |
| Westmere      | 9         | 4.17%   |
| Broadwell     | 8         | 3.7%    |
| Zen 2         | 7         | 3.24%   |
| K10           | 7         | 3.24%   |
| Piledriver    | 6         | 2.78%   |
| CometLake     | 6         | 2.78%   |
| Zen+          | 5         | 2.31%   |
| Zen           | 5         | 2.31%   |
| Silvermont    | 5         | 2.31%   |
| Core          | 5         | 2.31%   |
| Nehalem       | 4         | 1.85%   |
| Bobcat        | 3         | 1.39%   |
| Zen 3         | 2         | 0.93%   |
| Jaguar        | 2         | 0.93%   |
| Goldmont      | 2         | 0.93%   |
| Bulldozer     | 2         | 0.93%   |
| NetBurst      | 1         | 0.46%   |
| K10 Llano     | 1         | 0.46%   |
| Goldmont plus | 1         | 0.46%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 119       | 49.79%  |
| Nvidia                     | 71        | 29.71%  |
| AMD                        | 48        | 20.08%  |
| Matrox Electronics Systems | 1         | 0.42%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 16        | 6.69%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 15        | 6.28%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 10        | 4.18%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 3.35%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 2.93%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 6         | 2.51%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 6         | 2.51%   |
| Intel HD Graphics 5500                                                                   | 5         | 2.09%   |
| Intel HD Graphics 530                                                                    | 5         | 2.09%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 5         | 2.09%   |
| AMD Picasso                                                                              | 5         | 2.09%   |
| Nvidia GT218 [GeForce 210]                                                               | 4         | 1.67%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 1.67%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 1.67%   |
| Intel HD Graphics 620                                                                    | 4         | 1.67%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.67%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 1.67%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 1.26%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 3         | 1.26%   |
| Intel HD Graphics 630                                                                    | 3         | 1.26%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.26%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 2         | 0.84%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 0.84%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 2         | 0.84%   |
| Nvidia GM206 [GeForce GTX 950]                                                           | 2         | 0.84%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 2         | 0.84%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.84%   |
| Nvidia G92 [GeForce GTS 250]                                                             | 2         | 0.84%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 0.84%   |
| Intel HD Graphics 500                                                                    | 2         | 0.84%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 2         | 0.84%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 2         | 0.84%   |
| AMD RS780L [Radeon 3000]                                                                 | 2         | 0.84%   |
| AMD Renoir                                                                               | 2         | 0.84%   |
| AMD Chelsea LP [Radeon HD 7730M]                                                         | 2         | 0.84%   |
| AMD Cezanne                                                                              | 2         | 0.84%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2         | 0.84%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.42%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 1         | 0.42%   |
| Nvidia TU116 [GeForce GTX 1650]                                                          | 1         | 0.42%   |
| Nvidia NV43 [GeForce 6600]                                                               | 1         | 0.42%   |
| Nvidia GT216M [NVS 5100M]                                                                | 1         | 0.42%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.42%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 0.42%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1         | 0.42%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.42%   |
| Nvidia GM108M [GeForce 930M]                                                             | 1         | 0.42%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.42%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.42%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1         | 0.42%   |
| Nvidia GK208 [GeForce GT 630 Rev. 2]                                                     | 1         | 0.42%   |
| Nvidia GK107M [GeForce GTX 660M]                                                         | 1         | 0.42%   |
| Nvidia GK107 [GeForce GT 740]                                                            | 1         | 0.42%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 1         | 0.42%   |
| Nvidia GK106M [GeForce GTX 770M]                                                         | 1         | 0.42%   |
| Nvidia GK106GL [Quadro K4000]                                                            | 1         | 0.42%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1         | 0.42%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 1         | 0.42%   |
| Nvidia GF119M [GeForce 610M]                                                             | 1         | 0.42%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 89        | 41.01%  |
| 1 x Nvidia     | 56        | 25.81%  |
| 1 x AMD        | 39        | 17.97%  |
| Intel + Nvidia | 13        | 5.99%   |
| 2 x Intel      | 9         | 4.15%   |
| Intel + AMD    | 8         | 3.69%   |
| AMD + Nvidia   | 2         | 0.92%   |
| 1 x Matrox     | 1         | 0.46%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 154       | 71.3%   |
| Proprietary | 32        | 14.81%  |
| Unknown     | 30        | 13.89%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 155       | 71.76%  |
| 1.01-2.0   | 21        | 9.72%   |
| 0.01-0.5   | 13        | 6.02%   |
| 0.51-1.0   | 12        | 5.56%   |
| 3.01-4.0   | 8         | 3.7%    |
| 7.01-8.0   | 3         | 1.39%   |
| 5.01-6.0   | 2         | 0.93%   |
| 2.01-3.0   | 2         | 0.93%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 30        | 18.29%  |
| LG Display              | 23        | 14.02%  |
| AU Optronics            | 14        | 8.54%   |
| Chimei Innolux          | 12        | 7.32%   |
| Goldstar                | 11        | 6.71%   |
| Dell                    | 9         | 5.49%   |
| Hewlett-Packard         | 7         | 4.27%   |
| BOE                     | 5         | 3.05%   |
| AOC                     | 5         | 3.05%   |
| Iiyama                  | 4         | 2.44%   |
| Chi Mei Optoelectronics | 4         | 2.44%   |
| Acer                    | 4         | 2.44%   |
| ViewSonic               | 3         | 1.83%   |
| Lenovo                  | 3         | 1.83%   |
| InfoVision              | 3         | 1.83%   |
| BenQ                    | 3         | 1.83%   |
| Ancor Communications    | 3         | 1.83%   |
| Sony                    | 2         | 1.22%   |
| Apple                   | 2         | 1.22%   |
| Vizio                   | 1         | 0.61%   |
| VIE                     | 1         | 0.61%   |
| Videoseven              | 1         | 0.61%   |
| Toshiba                 | 1         | 0.61%   |
| Sun                     | 1         | 0.61%   |
| Sharp                   | 1         | 0.61%   |
| RS                      | 1         | 0.61%   |
| Philips                 | 1         | 0.61%   |
| NEC Computers           | 1         | 0.61%   |
| Medion                  | 1         | 0.61%   |
| LG Philips              | 1         | 0.61%   |
| LED                     | 1         | 0.61%   |
| Insignia                | 1         | 0.61%   |
| Gateway                 | 1         | 0.61%   |
| Fujitsu Siemens         | 1         | 0.61%   |
| CVT                     | 1         | 0.61%   |
| CAN                     | 1         | 0.61%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch          | 3         | 1.83%   |
| LG Display LCD Monitor LGD0532 1920x1080 340x190mm 15.3-inch           | 2         | 1.22%   |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch            | 2         | 1.22%   |
| Iiyama PLE2407HDS IVM560D 1920x1080 520x300mm 23.6-inch                | 2         | 1.22%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch              | 2         | 1.22%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 310x170mm 13.9-inch       | 2         | 1.22%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 340x190mm 15.3-inch          | 2         | 1.22%   |
| Vizio D32f-F1 VIZ1027 1920x1080 700x390mm 31.5-inch                    | 1         | 0.61%   |
| ViewSonic VX1940w VSC6A20 1680x1050 410x260mm 19.1-inch                | 1         | 0.61%   |
| ViewSonic LCD Monitor VSCD824 1920x1080 520x290mm 23.4-inch            | 1         | 0.61%   |
| ViewSonic LCD Monitor VSC8724 1440x900 410x260mm 19.1-inch             | 1         | 0.61%   |
| VIE A/G2356 VIE2300 1920x1080 500x300mm 23.0-inch                      | 1         | 0.61%   |
| Videoseven WL19A IGM1908 1280x1024 380x300mm 19.1-inch                 | 1         | 0.61%   |
| Toshiba TV TSB0108 1360x768 480x270mm 21.7-inch                        | 1         | 0.61%   |
| Sun X7202A SUN0595 1280x1024 380x300mm 19.1-inch                       | 1         | 0.61%   |
| Sony TV SNYC901 1920x1080                                              | 1         | 0.61%   |
| Sony SDM-HS95P SNY2500 1280x1024 380x300mm 19.1-inch                   | 1         | 0.61%   |
| Sharp LQ100P1JX51 SHP14A6 1800x1200 210x140mm 9.9-inch                 | 1         | 0.61%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 700x390mm 31.5-inch      | 1         | 0.61%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 610x350mm 27.7-inch      | 1         | 0.61%   |
| Samsung Electronics T24D390 SAM0B6E 1920x1080 520x290mm 23.4-inch      | 1         | 0.61%   |
| Samsung Electronics T22C300 SAM0AB3 1920x1080 480x270mm 21.7-inch      | 1         | 0.61%   |
| Samsung Electronics SyncMaster SAM0600 1600x900 440x250mm 19.9-inch    | 1         | 0.61%   |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                       | 1         | 0.61%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 470x300mm 22.0-inch   | 1         | 0.61%   |
| Samsung Electronics SyncMaster SAM03E0 1440x900 410x260mm 19.1-inch    | 1         | 0.61%   |
| Samsung Electronics SyncMaster SAM03D7 1680x1050 470x300mm 22.0-inch   | 1         | 0.61%   |
| Samsung Electronics SyncMaster SAM0320 1680x1050 470x300mm 22.0-inch   | 1         | 0.61%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 490x320mm 23.0-inch   | 1         | 0.61%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 430x270mm 20.0-inch   | 1         | 0.61%   |
| Samsung Electronics SE790C SAM0C62 2560x1080 700x310mm 30.1-inch       | 1         | 0.61%   |
| Samsung Electronics S27D590 SAM0B49 1920x1080 600x340mm 27.2-inch      | 1         | 0.61%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 530x300mm 24.0-inch      | 1         | 0.61%   |
| Samsung Electronics S24C350 SAM0A3A 1920x1080 530x300mm 24.0-inch      | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 330x210mm 15.4-inch   | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC354C 1366x768 350x200mm 15.9-inch   | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch   | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 340x190mm 15.3-inch   | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SDC4253 1366x768 260x150mm 11.8-inch   | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SDC324D 1366x768 310x170mm 13.9-inch   | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SDC324A 1366x768 290x170mm 13.2-inch   | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SAM4A75 1024x768 300x230mm 14.9-inch   | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SAM0F9F 3840x2160 1420x800mm 64.2-inch | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SAM0D3B 3840x2160 890x500mm 40.2-inch  | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SAM0AC6 1920x1080 700x390mm 31.5-inch  | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 480x270mm 21.7-inch  | 1         | 0.61%   |
| Samsung Electronics LC24RG50 SAM0F91 1920x1080 530x300mm 24.0-inch     | 1         | 0.61%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 520x290mm 23.4-inch      | 1         | 0.61%   |
| RS LE2262 BTC2262 1680x1050 470x290mm 21.7-inch                        | 1         | 0.61%   |
| Philips LCD Monitor PHLC0B1 1920x1080 480x270mm 21.7-inch              | 1         | 0.61%   |
| NEC Computers EA244UHD NEC2B1D 3840x2160 530x300mm 24.0-inch           | 1         | 0.61%   |
| Medion MD21281 MED3947 1366x768 410x230mm 18.5-inch                    | 1         | 0.61%   |
| LG Philips LCD Monitor LPL3B01 1280x800 330x210mm 15.4-inch            | 1         | 0.61%   |
| LG Display LCD Monitor LGD11F9 1280x800 290x180mm 13.4-inch            | 1         | 0.61%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch           | 1         | 0.61%   |
| LG Display LCD Monitor LGD05B1 1920x1080 310x170mm 13.9-inch           | 1         | 0.61%   |
| LG Display LCD Monitor LGD0545 3200x1800 290x170mm 13.2-inch           | 1         | 0.61%   |
| LG Display LCD Monitor LGD053F 1920x1080 340x190mm 15.3-inch           | 1         | 0.61%   |
| LG Display LCD Monitor LGD0527 1366x768 310x170mm 13.9-inch            | 1         | 0.61%   |
| LG Display LCD Monitor LGD0525 1366x768 340x190mm 15.3-inch            | 1         | 0.61%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 56        | 34.57%  |
| 1366x768 (WXGA)    | 46        | 28.4%   |
| 1680x1050 (WSXGA+) | 11        | 6.79%   |
| 3840x2160 (4K)     | 10        | 6.17%   |
| 1280x1024 (SXGA)   | 8         | 4.94%   |
| 1440x900 (WXGA+)   | 6         | 3.7%    |
| 2560x1440 (QHD)    | 5         | 3.09%   |
| 1600x900 (HD+)     | 5         | 3.09%   |
| 1280x800 (WXGA)    | 5         | 3.09%   |
| 2560x1080          | 3         | 1.85%   |
| 3440x1440          | 2         | 1.23%   |
| 3200x1800 (QHD+)   | 1         | 0.62%   |
| 2048x1152          | 1         | 0.62%   |
| 1800x1200          | 1         | 0.62%   |
| 1360x768           | 1         | 0.62%   |
| 1024x768 (XGA)     | 1         | 0.62%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 30        | 18.4%   |
| 13      | 26        | 15.95%  |
| 19      | 15        | 9.2%    |
| 21      | 14        | 8.59%   |
| 23      | 11        | 6.75%   |
| 24      | 9         | 5.52%   |
| 27      | 8         | 4.91%   |
| 31      | 7         | 4.29%   |
| 12      | 7         | 4.29%   |
| 18      | 6         | 3.68%   |
| 17      | 6         | 3.68%   |
| 22      | 4         | 2.45%   |
| 11      | 4         | 2.45%   |
| 20      | 3         | 1.84%   |
| 34      | 2         | 1.23%   |
| Unknown | 2         | 1.23%   |
| 64      | 1         | 0.61%   |
| 54      | 1         | 0.61%   |
| 40      | 1         | 0.61%   |
| 39      | 1         | 0.61%   |
| 30      | 1         | 0.61%   |
| 28      | 1         | 0.61%   |
| 16      | 1         | 0.61%   |
| 14      | 1         | 0.61%   |
| 9       | 1         | 0.61%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 50        | 30.67%  |
| 401-500     | 38        | 23.31%  |
| 501-600     | 24        | 14.72%  |
| 201-300     | 20        | 12.27%  |
| 351-400     | 12        | 7.36%   |
| 601-700     | 11        | 6.75%   |
| 801-900     | 2         | 1.23%   |
| 701-800     | 2         | 1.23%   |
| 1001-1500   | 2         | 1.23%   |
| Unknown     | 2         | 1.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 122       | 76.73%  |
| 16/10 | 22        | 13.84%  |
| 5/4   | 7         | 4.4%    |
| 21/9  | 5         | 3.14%   |
| 3/2   | 2         | 1.26%   |
| 4/3   | 1         | 0.63%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 36        | 22.22%  |
| 81-90          | 23        | 14.2%   |
| 91-100         | 23        | 14.2%   |
| 151-200        | 18        | 11.11%  |
| 351-500        | 9         | 5.56%   |
| 301-350        | 9         | 5.56%   |
| 101-110        | 8         | 4.94%   |
| 61-70          | 7         | 4.32%   |
| 141-150        | 7         | 4.32%   |
| 121-130        | 5         | 3.09%   |
| 51-60          | 4         | 2.47%   |
| 71-80          | 3         | 1.85%   |
| More than 1000 | 2         | 1.23%   |
| 251-300        | 2         | 1.23%   |
| 501-1000       | 2         | 1.23%   |
| Unknown        | 2         | 1.23%   |
| 41-50          | 1         | 0.62%   |
| 111-120        | 1         | 0.62%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 65        | 40.63%  |
| 101-120       | 51        | 31.88%  |
| 121-160       | 35        | 21.88%  |
| 161-240       | 6         | 3.75%   |
| Unknown       | 2         | 1.25%   |
| More than 240 | 1         | 0.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 151       | 69.91%  |
| 0     | 56        | 25.93%  |
| 2     | 9         | 4.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 115       | 38.21%  |
| Intel                             | 93        | 30.9%   |
| Qualcomm Atheros                  | 37        | 12.29%  |
| Broadcom                          | 27        | 8.97%   |
| Ralink                            | 7         | 2.33%   |
| Ralink Technology                 | 4         | 1.33%   |
| Marvell Technology Group          | 4         | 1.33%   |
| D-Link                            | 2         | 0.66%   |
| TP-Link                           | 1         | 0.33%   |
| Toshiba                           | 1         | 0.33%   |
| Sierra Wireless                   | 1         | 0.33%   |
| Qualcomm Atheros Communications   | 1         | 0.33%   |
| Mellanox Technologies             | 1         | 0.33%   |
| IMC Networks                      | 1         | 0.33%   |
| Hewlett-Packard                   | 1         | 0.33%   |
| Ericsson Business Mobile Networks | 1         | 0.33%   |
| D-Link System                     | 1         | 0.33%   |
| ASUSTek Computer                  | 1         | 0.33%   |
| AboCom Systems                    | 1         | 0.33%   |
| 3Com                              | 1         | 0.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller     | 91        | 25.28%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                 | 17        | 4.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                 | 12        | 3.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                      | 9         | 2.5%    |
| Intel Wireless 7260                                                   | 8         | 2.22%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter            | 7         | 1.94%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                   | 6         | 1.67%   |
| Intel Wireless 7265                                                   | 6         | 1.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)        | 5         | 1.39%   |
| Intel Wireless 8265 / 8275                                            | 5         | 1.39%   |
| Intel Wireless 8260                                                   | 5         | 1.39%   |
| Intel Ethernet Connection (7) I219-V                                  | 5         | 1.39%   |
| Intel WiFi Link 5100                                                  | 4         | 1.11%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                       | 4         | 1.11%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                     | 4         | 1.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter              | 3         | 0.83%   |
| Intel Wireless 3165                                                   | 3         | 0.83%   |
| Intel Wi-Fi 6 AX200                                                   | 3         | 0.83%   |
| Intel I211 Gigabit Network Connection                                 | 3         | 0.83%   |
| Intel Ethernet Connection I218-LM                                     | 3         | 0.83%   |
| Intel Ethernet Connection I217-LM                                     | 3         | 0.83%   |
| Intel Centrino Wireless-N 2230                                        | 3         | 0.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                          | 3         | 0.83%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                              | 3         | 0.83%   |
| Intel 82579V Gigabit Network Connection                               | 3         | 0.83%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                     | 3         | 0.83%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                      | 3         | 0.83%   |
| Broadcom BCM4331 802.11a/b/g/n                                        | 3         | 0.83%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter              | 2         | 0.56%   |
| Realtek RTL8188EE Wireless Network Adapter                            | 2         | 0.56%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                            | 2         | 0.56%   |
| Ralink RT5370 Wireless Adapter                                        | 2         | 0.56%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                | 2         | 0.56%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                             | 2         | 0.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter            | 2         | 0.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter            | 2         | 0.56%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)        | 2         | 0.56%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)        | 2         | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                              | 2         | 0.56%   |
| Intel Ultimate N WiFi Link 5300                                       | 2         | 0.56%   |
| Intel Ethernet Connection I219-LM                                     | 2         | 0.56%   |
| Intel Ethernet Connection I218-V                                      | 2         | 0.56%   |
| Intel Ethernet Connection (3) I218-V                                  | 2         | 0.56%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                          | 2         | 0.56%   |
| Intel Centrino Advanced-N 6235                                        | 2         | 0.56%   |
| Intel Centrino Advanced-N 6200                                        | 2         | 0.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                       | 2         | 0.56%   |
| Intel 82577LM Gigabit Network Connection                              | 2         | 0.56%   |
| Intel 82567LM Gigabit Network Connection                              | 2         | 0.56%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                     | 2         | 0.56%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                       | 2         | 0.56%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                    | 2         | 0.56%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                    | 2         | 0.56%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                   | 2         | 0.56%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]            | 1         | 0.28%   |
| Toshiba Ericsson H5321gw for TOSHIBA Mobile Broadband Network Adapter | 1         | 0.28%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                         | 1         | 0.28%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter              | 1         | 0.28%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter              | 1         | 0.28%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                       | 1         | 0.28%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 64        | 41.83%  |
| Qualcomm Atheros                | 33        | 21.57%  |
| Realtek Semiconductor           | 22        | 14.38%  |
| Broadcom                        | 14        | 9.15%   |
| Ralink                          | 7         | 4.58%   |
| Ralink Technology               | 4         | 2.61%   |
| D-Link                          | 2         | 1.31%   |
| TP-Link                         | 1         | 0.65%   |
| Sierra Wireless                 | 1         | 0.65%   |
| Qualcomm Atheros Communications | 1         | 0.65%   |
| IMC Networks                    | 1         | 0.65%   |
| D-Link System                   | 1         | 0.65%   |
| ASUSTek Computer                | 1         | 0.65%   |
| AboCom Systems                  | 1         | 0.65%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 9         | 5.88%   |
| Intel Wireless 7260                                                                   | 8         | 5.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 7         | 4.58%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 6         | 3.92%   |
| Intel Wireless 7265                                                                   | 6         | 3.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 5         | 3.27%   |
| Intel Wireless 8265 / 8275                                                            | 5         | 3.27%   |
| Intel Wireless 8260                                                                   | 5         | 3.27%   |
| Intel WiFi Link 5100                                                                  | 4         | 2.61%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 4         | 2.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 3         | 1.96%   |
| Intel Wireless 3165                                                                   | 3         | 1.96%   |
| Intel Wi-Fi 6 AX200                                                                   | 3         | 1.96%   |
| Intel Centrino Wireless-N 2230                                                        | 3         | 1.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 3         | 1.96%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 3         | 1.96%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 3         | 1.96%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                              | 2         | 1.31%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 2         | 1.31%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 2         | 1.31%   |
| Ralink RT5370 Wireless Adapter                                                        | 2         | 1.31%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                | 2         | 1.31%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                             | 2         | 1.31%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 2         | 1.31%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 2         | 1.31%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 2         | 1.31%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 2         | 1.31%   |
| Intel Ultimate N WiFi Link 5300                                                       | 2         | 1.31%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                          | 2         | 1.31%   |
| Intel Centrino Advanced-N 6235                                                        | 2         | 1.31%   |
| Intel Centrino Advanced-N 6200                                                        | 2         | 1.31%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 2         | 1.31%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                    | 2         | 1.31%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                    | 2         | 1.31%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 2         | 1.31%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                            | 1         | 0.65%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                                         | 1         | 0.65%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 1         | 0.65%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.65%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 1         | 0.65%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                | 1         | 0.65%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 1         | 0.65%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                           | 1         | 0.65%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                | 1         | 0.65%   |
| Ralink RT2501/RT2573 Wireless Adapter                                                 | 1         | 0.65%   |
| Ralink MT7601U Wireless Adapter                                                       | 1         | 0.65%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                           | 1         | 0.65%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                                             | 1         | 0.65%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 1         | 0.65%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 1         | 0.65%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 1         | 0.65%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 0.65%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.65%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn]                | 1         | 0.65%   |
| Intel Wireless-AC 9260                                                                | 1         | 0.65%   |
| Intel Wireless 3160                                                                   | 1         | 0.65%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                               | 1         | 0.65%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                         | 1         | 0.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 0.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 1         | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 108       | 54.27%  |
| Intel                    | 57        | 28.64%  |
| Broadcom                 | 20        | 10.05%  |
| Qualcomm Atheros         | 10        | 5.03%   |
| Marvell Technology Group | 4         | 2.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 91        | 45.05%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 17        | 8.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 12        | 5.94%   |
| Intel Ethernet Connection (7) I219-V                                           | 5         | 2.48%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 4         | 1.98%   |
| Intel I211 Gigabit Network Connection                                          | 3         | 1.49%   |
| Intel Ethernet Connection I218-LM                                              | 3         | 1.49%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 1.49%   |
| Intel 82579V Gigabit Network Connection                                        | 3         | 1.49%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 3         | 1.49%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 3         | 1.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 0.99%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 0.99%   |
| Intel Ethernet Connection I218-V                                               | 2         | 0.99%   |
| Intel Ethernet Connection (3) I218-V                                           | 2         | 0.99%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 0.99%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 0.99%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                              | 2         | 0.99%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 0.99%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.5%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                  | 1         | 0.5%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.5%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.5%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.5%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1         | 0.5%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.5%    |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 1         | 0.5%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.5%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 1         | 0.5%    |
| Marvell Group 88E8001 Gigabit Ethernet Controller                              | 1         | 0.5%    |
| Intel Ethernet Connection I219-V                                               | 1         | 0.5%    |
| Intel Ethernet Connection I217-V                                               | 1         | 0.5%    |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.5%    |
| Intel Ethernet Connection (6) I219-LM                                          | 1         | 0.5%    |
| Intel Ethernet Connection (5) I219-V                                           | 1         | 0.5%    |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.5%    |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 0.5%    |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 0.5%    |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 0.5%    |
| Intel Ethernet Connection (2) I218-V                                           | 1         | 0.5%    |
| Intel Ethernet Connection (12) I219-V                                          | 1         | 0.5%    |
| Intel Ethernet Connection (11) I219-V                                          | 1         | 0.5%    |
| Intel 82583V Gigabit Network Connection                                        | 1         | 0.5%    |
| Intel 82578DM Gigabit Network Connection                                       | 1         | 0.5%    |
| Intel 82574L Gigabit Network Connection                                        | 1         | 0.5%    |
| Intel 82567LF Gigabit Network Connection                                       | 1         | 0.5%    |
| Intel 82566MM Gigabit Network Connection                                       | 1         | 0.5%    |
| Intel 82566DM-2 Gigabit Network Connection                                     | 1         | 0.5%    |
| Intel 82562V-2 10/100 Network Connection                                       | 1         | 0.5%    |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                           | 1         | 0.5%    |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                 | 1         | 0.5%    |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                               | 1         | 0.5%    |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                        | 1         | 0.5%    |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                        | 1         | 0.5%    |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 1         | 0.5%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 1         | 0.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 198       | 57.56%  |
| WiFi     | 141       | 40.99%  |
| Modem    | 3         | 0.87%   |
| Unknown  | 2         | 0.58%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 197       | 62.34%  |
| WiFi     | 115       | 36.39%  |
| Modem    | 2         | 0.63%   |
| Unknown  | 2         | 0.63%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 119       | 54.84%  |
| 1     | 94        | 43.32%  |
| 3     | 3         | 1.38%   |
| 0     | 1         | 0.46%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 207       | 94.95%  |
| Yes  | 11        | 5.05%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 44        | 44%     |
| Qualcomm Atheros Communications | 9         | 9%      |
| Cambridge Silicon Radio         | 8         | 8%      |
| Broadcom                        | 8         | 8%      |
| Apple                           | 8         | 8%      |
| Realtek Semiconductor           | 7         | 7%      |
| IMC Networks                    | 4         | 4%      |
| ASUSTek Computer                | 3         | 3%      |
| Ralink                          | 2         | 2%      |
| Dell                            | 2         | 2%      |
| Lite-On Technology              | 1         | 1%      |
| Integrated System Solution      | 1         | 1%      |
| Hewlett-Packard                 | 1         | 1%      |
| Foxconn / Hon Hai               | 1         | 1%      |
| Edimax Technology               | 1         | 1%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 28        | 28%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 8         | 8%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 5         | 5%      |
| Apple Apple Broadcom Built-in Bluetooth                     | 5         | 5%      |
| Intel Centrino Bluetooth Wireless Transceiver               | 4         | 4%      |
| Intel AX200 Bluetooth                                       | 3         | 3%      |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 2%      |
| Ralink RT3290 Bluetooth                                     | 2         | 2%      |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 2         | 2%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 2%      |
| Intel AX201 Bluetooth                                       | 2         | 2%      |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 2         | 2%      |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 2%      |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 2         | 2%      |
| Realtek RTL8821A Bluetooth                                  | 1         | 1%      |
| Realtek  Bluetooth Adapter                                  | 1         | 1%      |
| Realtek  Bluetooth 4.0 + High Speed Chip                    | 1         | 1%      |
| Realtek CSR Bluetooth Chip                                  | 1         | 1%      |
| Realtek Bluetooth Radio                                     | 1         | 1%      |
| Qualcomm Atheros  QCA9565 Bluetooth 4.0 + HS Adapter        | 1         | 1%      |
| Qualcomm Atheros  QCA61x4 Bluetooth 4.1                     | 1         | 1%      |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 1%      |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 1%      |
| Qualcomm Atheros Atheros AR9462 Bluetooth 3.0 + HS Adapter  | 1         | 1%      |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS                 | 1         | 1%      |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 1%      |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 1%      |
| Integrated System Solution Bluetooth Device                 | 1         | 1%      |
| IMC Networks Qualcomm Atheros Bluetooth 4.0                 | 1         | 1%      |
| IMC Networks Broadcom BCM20702 Bluetooth 4.0 +HS USB Device | 1         | 1%      |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 1%      |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 1%      |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter     | 1         | 1%      |
| Dell DW375 Bluetooth Module                                 | 1         | 1%      |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 1         | 1%      |
| Broadcom Bluetooth Device                                   | 1         | 1%      |
| Broadcom Bluetooth 2.0+eDR dongle                           | 1         | 1%      |
| Broadcom BCM43142A0 Bluetooth 4.0                           | 1         | 1%      |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 1         | 1%      |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                        | 1         | 1%      |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 1         | 1%      |
| ASUS Realtek Bluetooth 4.0 + High Speed Chip                | 1         | 1%      |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1         | 1%      |
| Apple Bluetooth USB Host Controller                         | 1         | 1%      |
| Apple Bluetooth Host Controller                             | 1         | 1%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 174       | 60.42%  |
| AMD                         | 52        | 18.06%  |
| Nvidia                      | 50        | 17.36%  |
| Texas Instruments           | 2         | 0.69%   |
| Logitech                    | 2         | 0.69%   |
| Creative Technology         | 2         | 0.69%   |
| XMOS                        | 1         | 0.35%   |
| Steinberg Soft-und Hardware | 1         | 0.35%   |
| SteelSeries ApS             | 1         | 0.35%   |
| Realtek Semiconductor       | 1         | 0.35%   |
| Creative Labs               | 1         | 0.35%   |
| C-Media Electronics         | 1         | 0.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 27        | 8.04%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 20        | 5.95%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 14        | 4.17%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 13        | 3.87%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 12        | 3.57%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 11        | 3.27%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 3.27%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 11        | 3.27%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 10        | 2.98%   |
| Intel Cannon Lake PCH cAVS                                                                        | 9         | 2.68%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8         | 2.38%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 7         | 2.08%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 2.08%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 2.08%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 2.08%   |
| Intel 200 Series PCH HD Audio                                                                     | 7         | 2.08%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 6         | 1.79%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 5         | 1.49%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 5         | 1.49%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 1.49%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 5         | 1.49%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5         | 1.49%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 5         | 1.49%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 1.49%   |
| AMD FCH Azalia Controller                                                                         | 5         | 1.49%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 4         | 1.19%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.19%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 1.19%   |
| Intel Comet Lake PCH-V Smart Sound Technology Audio Controller                                    | 4         | 1.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.19%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 4         | 1.19%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 1.19%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 4         | 1.19%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.89%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.89%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 0.89%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 0.89%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 0.89%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 3         | 0.89%   |
| Nvidia MCP61 High Definition Audio                                                                | 2         | 0.6%    |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.6%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 0.6%    |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.6%    |
| Nvidia GM204 High Definition Audio Controller                                                     | 2         | 0.6%    |
| Nvidia GK106 HDMI Audio Controller                                                                | 2         | 0.6%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.6%    |
| Nvidia GF106 High Definition Audio Controller                                                     | 2         | 0.6%    |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 0.6%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 0.6%    |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 2         | 0.6%    |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 0.6%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.6%    |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 2         | 0.6%    |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 0.6%    |
| XMOS Cyberdrive Audio Driver                                                                      | 1         | 0.3%    |
| Texas Instruments SMSL Q5 AMP                                                                     | 1         | 0.3%    |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.3%    |
| Steinberg Soft-und Hardware MI4                                                                   | 1         | 0.3%    |
| SteelSeries ApS Arctis 7 wireless adapter                                                         | 1         | 0.3%    |
| Realtek Semiconductor Realtek Audio USB Realtek Audio USB Microphone                              | 1         | 0.3%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Samsung Electronics        | 43        | 16.48%  |
| SK Hynix                   | 35        | 13.41%  |
| Kingston                   | 33        | 12.64%  |
| Unknown                    | 30        | 11.49%  |
| Micron Technology          | 25        | 9.58%   |
| Crucial                    | 22        | 8.43%   |
| Elpida                     | 13        | 4.98%   |
| G.Skill                    | 8         | 3.07%   |
| Corsair                    | 8         | 3.07%   |
| Ramaxel Technology         | 6         | 2.3%    |
| Nanya Technology           | 6         | 2.3%    |
| Smart                      | 4         | 1.53%   |
| Apacer                     | 3         | 1.15%   |
| A-DATA Technology          | 3         | 1.15%   |
| Transcend                  | 2         | 0.77%   |
| Teikon                     | 2         | 0.77%   |
| Team                       | 2         | 0.77%   |
| PNY                        | 2         | 0.77%   |
| High Bridge                | 2         | 0.77%   |
| Avant                      | 2         | 0.77%   |
| AMD                        | 2         | 0.77%   |
| Unknown (ABCD)             | 1         | 0.38%   |
| Unknown (7F7F7F94FFFFFFFF) | 1         | 0.38%   |
| Unknown (09A4)             | 1         | 0.38%   |
| Toshiba                    | 1         | 0.38%   |
| Smart Brazil               | 1         | 0.38%   |
| SHARETRONIC                | 1         | 0.38%   |
| Patriot                    | 1         | 0.38%   |
| Goldkey                    | 1         | 0.38%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                              | Computers | Percent |
|--------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s             | 4         | 1.41%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s              | 3         | 1.06%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1333MT/s              | 3         | 1.06%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s              | 3         | 1.06%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                        | 2         | 0.71%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                        | 2         | 0.71%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                               | 2         | 0.71%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                               | 2         | 0.71%   |
| SK Hynix RAM Module 2GB SODIMM DDR3 1600MT/s                       | 2         | 0.71%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s             | 2         | 0.71%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s              | 2         | 0.71%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s              | 2         | 0.71%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s              | 2         | 0.71%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s             | 2         | 0.71%   |
| Samsung RAM K3QF4F40BM-AGCF 4GB Row Of Chips LPDDR3 1867MT/s       | 2         | 0.71%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s              | 2         | 0.71%   |
| Micron RAM 8JTF25664AZ-1G6M1 2GB DIMM DDR3 1600MT/s                | 2         | 0.71%   |
| Micron RAM 4ATF51264HZ-2G3E1 4GB SODIMM DDR4 2400MT/s              | 2         | 0.71%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s              | 2         | 0.71%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3200MT/s               | 2         | 0.71%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 2667MT/s                  | 2         | 0.71%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s                | 2         | 0.71%   |
| G.Skill RAM F4-2666C19-8GNT 8GB DIMM DDR4 2666MT/s                 | 2         | 0.71%   |
| Unknown RAM TMKS8G68ALFBCH-266 8192MB SODIMM DDR4 2400MT/s         | 1         | 0.35%   |
| Unknown RAM R9P5316-007.A02LF 2GB DIMM 533MT/s                     | 1         | 0.35%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                        | 1         | 0.35%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                          | 1         | 0.35%   |
| Unknown RAM Module 8GB DIMM DDR3 1866MT/s                          | 1         | 0.35%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                               | 1         | 0.35%   |
| Unknown RAM Module 4GB SODIMM DDR3                                 | 1         | 0.35%   |
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                         | 1         | 0.35%   |
| Unknown RAM Module 4GB DIMM DDR3 1866MT/s                          | 1         | 0.35%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                          | 1         | 0.35%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                           | 1         | 0.35%   |
| Unknown RAM Module 4GB DIMM 667MT/s                                | 1         | 0.35%   |
| Unknown RAM Module 4096MB DIMM DDR2                                | 1         | 0.35%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                         | 1         | 0.35%   |
| Unknown RAM Module 2GB FB-DIMM DDR2 667MT/s                        | 1         | 0.35%   |
| Unknown RAM Module 2GB DIMM SDRAM                                  | 1         | 0.35%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                           | 1         | 0.35%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                           | 1         | 0.35%   |
| Unknown RAM Module 2GB DIMM 1600MT/s                               | 1         | 0.35%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                           | 1         | 0.35%   |
| Unknown RAM Module 2048MB SODIMM 667MT/s                           | 1         | 0.35%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s                       | 1         | 0.35%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                        | 1         | 0.35%   |
| Unknown RAM Module 2048MB DIMM DDR2                                | 1         | 0.35%   |
| Unknown RAM Module 1GB DIMM 1333MT/s                               | 1         | 0.35%   |
| Unknown RAM Module 1024MB DIMM SDRAM 667MT/s                       | 1         | 0.35%   |
| Unknown RAM 7TE39AA# 8GB DIMM DDR4 2667MT/s                        | 1         | 0.35%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s       | 1         | 0.35%   |
| Unknown (7F7F7F94FFFFFFFF) RAM 996593PCGH 2048MB DIMM DDR2 800MT/s | 1         | 0.35%   |
| Unknown (09A4) RAM 08S2400CL170H 8192MB DIMM DDR4 2133MT/s         | 1         | 0.35%   |
| Transcend RAM JM1600KSH-8G 8192MB SODIMM DDR3 1333MT/s             | 1         | 0.35%   |
| Transcend RAM JM1333KSN-4G 4GB DIMM DDR3 1333MT/s                  | 1         | 0.35%   |
| Toshiba RAM 8HTF12864HDY-800G1 2048MB SODIMM 800MT/s               | 1         | 0.35%   |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 800MT/s                | 1         | 0.35%   |
| Teikon RAM TMT451S6BFR8A-PBSC 4096MB SODIMM DDR3 1600MT/s          | 1         | 0.35%   |
| Teikon RAM TML251S6EFR8A-PBHC 4096MB SODIMM DDR3 1600MT/s          | 1         | 0.35%   |
| Team RAM TEAMGROUP-UD4-3000 4GB DIMM DDR4 2400MT/s                 | 1         | 0.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 112       | 51.85%  |
| DDR4    | 70        | 32.41%  |
| DDR2    | 13        | 6.02%   |
| Unknown | 12        | 5.56%   |
| LPDDR3  | 4         | 1.85%   |
| SDRAM   | 3         | 1.39%   |
| LPDDR4  | 1         | 0.46%   |
| DDR     | 1         | 0.46%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 104       | 48.15%  |
| DIMM         | 101       | 46.76%  |
| Row Of Chips | 6         | 2.78%   |
| FB-DIMM      | 2         | 0.93%   |
| Chip         | 2         | 0.93%   |
| Unknown      | 1         | 0.46%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 101       | 40.08%  |
| 2048  | 65        | 25.79%  |
| 8192  | 63        | 25%     |
| 16384 | 16        | 6.35%   |
| 1024  | 5         | 1.98%   |
| 32768 | 2         | 0.79%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 67        | 27.92%  |
| 1333    | 46        | 19.17%  |
| 2400    | 28        | 11.67%  |
| 2667    | 20        | 8.33%   |
| 2133    | 17        | 7.08%   |
| 800     | 11        | 4.58%   |
| 667     | 10        | 4.17%   |
| 3200    | 7         | 2.92%   |
| 2666    | 5         | 2.08%   |
| 1867    | 5         | 2.08%   |
| 1334    | 5         | 2.08%   |
| 1067    | 3         | 1.25%   |
| 1066    | 3         | 1.25%   |
| Unknown | 3         | 1.25%   |
| 2933    | 2         | 0.83%   |
| 1866    | 2         | 0.83%   |
| 533     | 2         | 0.83%   |
| 1800    | 1         | 0.42%   |
| 1777    | 1         | 0.42%   |
| 1400    | 1         | 0.42%   |
| 975     | 1         | 0.42%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 4         | 57.14%  |
| Lexmark International | 2         | 28.57%  |
| Seiko Epson           | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Seiko Epson USB2.0 Printer (Hi-speed)        | 1         | 12.5%   |
| Lexmark International SINDOH A603_A608 Print | 1         | 12.5%   |
| Lexmark International Lexmark MS710 Print    | 1         | 12.5%   |
| HP LaserJet 2200                             | 1         | 12.5%   |
| HP LaserJet 1200                             | 1         | 12.5%   |
| HP HP LaserJet P2035 HP Print                | 1         | 12.5%   |
| HP DeskJet 5850c                             | 1         | 12.5%   |
| HP Color LaserJet CP1215                     | 1         | 12.5%   |

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
| Chicony Electronics                    | 17        | 22.08%  |
| Realtek Semiconductor                  | 10        | 12.99%  |
| Microdia                               | 7         | 9.09%   |
| Sunplus Innovation Technology          | 6         | 7.79%   |
| Suyin                                  | 4         | 5.19%   |
| IMC Networks                           | 4         | 5.19%   |
| Apple                                  | 4         | 5.19%   |
| Acer                                   | 4         | 5.19%   |
| Syntek                                 | 2         | 2.6%    |
| Silicon Motion                         | 2         | 2.6%    |
| Logitech                               | 2         | 2.6%    |
| Lite-On Technology                     | 2         | 2.6%    |
| Importek                               | 2         | 2.6%    |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.6%    |
| Alcor Micro                            | 2         | 2.6%    |
| Ricoh                                  | 1         | 1.3%    |
| Quanta                                 | 1         | 1.3%    |
| Intel                                  | 1         | 1.3%    |
| Holitech                               | 1         | 1.3%    |
| Hewlett-Packard                        | 1         | 1.3%    |
| Generalplus Technology                 | 1         | 1.3%    |
| A4Tech                                 | 1         | 1.3%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                              | 4         | 5.13%   |
| Apple FaceTime HD camera                                  | 4         | 5.13%   |
| Realtek Realtek USB2.0 PC Camera                          | 3         | 3.85%   |
| Chicony integrated camera                                 | 3         | 3.85%   |
| Chicony HP HD Webcam [Fixed]                              | 3         | 3.85%   |
| Sunplus Integrated_Webcam_HD                              | 2         | 2.56%   |
| Sunplus Asus Webcam                                       | 2         | 2.56%   |
| Realtek Integrated Webcam                                 | 2         | 2.56%   |
| Microdia Laptop_Integrated_Webcam_HD                      | 2         | 2.56%   |
| Microdia Integrated Webcam                                | 2         | 2.56%   |
| Logitech Webcam C270                                      | 2         | 2.56%   |
| IMC Networks USB2.0 HD UVC WebCam                         | 2         | 2.56%   |
| Chicony Integrated Camera [ThinkPad]                      | 2         | 2.56%   |
| Syntek Lenovo EasyCamera                                  | 1         | 1.28%   |
| Syntek EasyCamera                                         | 1         | 1.28%   |
| Suyin USB 2.0 Camera                                      | 1         | 1.28%   |
| Suyin Sony Visual Communication Camera                    | 1         | 1.28%   |
| Suyin HP Webcam-101                                       | 1         | 1.28%   |
| Suyin HP Integrated Webcam                                | 1         | 1.28%   |
| Sunplus Integrated Camera                                 | 1         | 1.28%   |
| Sunplus Dell E5570 integrated webcam                      | 1         | 1.28%   |
| Silicon Motion WebCam SCX Series                          | 1         | 1.28%   |
| Silicon Motion Realtek USB2.0 PC Camera                   | 1         | 1.28%   |
| Ricoh Integrated Camera                                   | 1         | 1.28%   |
| Realtek LG Camera                                         | 1         | 1.28%   |
| Quanta HP Webcam                                          | 1         | 1.28%   |
| Microdia Laptop_Integrated_Webcam_FHD                     | 1         | 1.28%   |
| Microdia HP Webcam                                        | 1         | 1.28%   |
| Microdia ASUS USB2.0 Webcam                               | 1         | 1.28%   |
| Lite-On Integrated Camera                                 | 1         | 1.28%   |
| Lite-On HP IR Camera                                      | 1         | 1.28%   |
| Intel Intel(R) RealSense(TM) 3D Camera (Front F200)       | 1         | 1.28%   |
| Importek TOSHIBA Web Camera - HD                          | 1         | 1.28%   |
| Importek TOSHIBA Web Camera                               | 1         | 1.28%   |
| IMC Networks Integrated Camera                            | 1         | 1.28%   |
| IMC Networks EasyCamera                                   | 1         | 1.28%   |
| Holitech USB2.0 HD UVC WebCam                             | 1         | 1.28%   |
| HP Premium Starter Webcam                                 | 1         | 1.28%   |
| Generalplus GENERAL WEBCAM                                | 1         | 1.28%   |
| Chicony UVC 1.00 device HD UVC WebCam                     | 1         | 1.28%   |
| Chicony USB2.0 VGA UVC WebCam                             | 1         | 1.28%   |
| Chicony TOSHIBA Web Camera - HD                           | 1         | 1.28%   |
| Chicony TOSHIBA Web Camera - 3M                           | 1         | 1.28%   |
| Chicony Lenovo EasyCamera                                 | 1         | 1.28%   |
| Chicony HP Webcam [2 MP Macro]                            | 1         | 1.28%   |
| Chicony HP HD Camera                                      | 1         | 1.28%   |
| Chicony HD WebCam                                         | 1         | 1.28%   |
| Chicony Chicony USB2.0 Camera                             | 1         | 1.28%   |
| Chicony 1.3M Webcam                                       | 1         | 1.28%   |
| Cheng Uei Precision Industry (Foxlink) Webcam             | 1         | 1.28%   |
| Cheng Uei Precision Industry (Foxlink) Realtek DMFT - RGB | 1         | 1.28%   |
| Alcor Micro USB 2.0 Camera                                | 1         | 1.28%   |
| Alcor Micro Acer Integrated Webcam                        | 1         | 1.28%   |
| Acer Lenovo Integrated Webcam                             | 1         | 1.28%   |
| Acer Lenovo EasyCamera                                    | 1         | 1.28%   |
| Acer Integrated Camera                                    | 1         | 1.28%   |
| Acer HD Webcam                                            | 1         | 1.28%   |
| A4Tech A4tech FHD 1080P PC Camera                         | 1         | 1.28%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Validity Sensors   | 7         | 70%     |
| STMicroelectronics | 1         | 10%     |
| Broadcom           | 1         | 10%     |
| AuthenTec          | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                                  | 3         | 30%     |
| Validity Sensors VFS495 Fingerprint Reader                                   | 1         | 10%     |
| Validity Sensors VFS451 Fingerprint Reader                                   | 1         | 10%     |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 1         | 10%     |
| Validity Sensors Synaptics WBDI                                              | 1         | 10%     |
| STMicroelectronics Fingerprint Reader                                        | 1         | 10%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 10%     |
| AuthenTec AES2810                                                            | 1         | 10%     |

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
| 1     | 88        | 40.18%  |
| 2     | 51        | 23.29%  |
| 0     | 48        | 21.92%  |
| 3     | 25        | 11.42%  |
| 4     | 7         | 3.2%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 141       | 50.54%  |
| Card reader              | 52        | 18.64%  |
| Net/wireless             | 36        | 12.9%   |
| Bluetooth                | 21        | 7.53%   |
| Firewire controller      | 11        | 3.94%   |
| Fingerprint reader       | 10        | 3.58%   |
| Sound                    | 4         | 1.43%   |
| Storage                  | 2         | 0.72%   |
| Storage/raid             | 1         | 0.36%   |
| Dvb card                 | 1         | 0.36%   |

