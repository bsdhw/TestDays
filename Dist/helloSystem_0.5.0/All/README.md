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
| HP            | ProBook 470 G4              | Notebook    | [5f026ff3a2](https://bsd-hardware.info/?probe=5f026ff3a2) | Oct 17, 2021 |
| HP            | ProBook 470 G4              | Notebook    | [40c180238f](https://bsd-hardware.info/?probe=40c180238f) | Oct 17, 2021 |
| Lenovo        | G500s 20245                 | Notebook    | [e6141c9ab3](https://bsd-hardware.info/?probe=e6141c9ab3) | Oct 16, 2021 |
| Lenovo        | ThinkPad X230 23254G7       | Notebook    | [06c6a282ca](https://bsd-hardware.info/?probe=06c6a282ca) | Oct 16, 2021 |
| HP            | Pavilion dv3                | Notebook    | [7f0b7f520f](https://bsd-hardware.info/?probe=7f0b7f520f) | Oct 14, 2021 |
| ASUSTek       | F2A85-M                     | Desktop     | [b4e3f33e5c](https://bsd-hardware.info/?probe=b4e3f33e5c) | Oct 14, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [b3b31d25b0](https://bsd-hardware.info/?probe=b3b31d25b0) | Oct 13, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [5a7c1871b1](https://bsd-hardware.info/?probe=5a7c1871b1) | Oct 11, 2021 |
| Acer          | Aspire TC-780               | Desktop     | [77101a00b3](https://bsd-hardware.info/?probe=77101a00b3) | Oct 11, 2021 |
| ASUSTek       | D940MX                      | Desktop     | [4e798f3ef0](https://bsd-hardware.info/?probe=4e798f3ef0) | Oct 10, 2021 |
| HP            | ProBook 470 G4              | Notebook    | [a9c135bf27](https://bsd-hardware.info/?probe=a9c135bf27) | Oct 10, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [fc1eda0998](https://bsd-hardware.info/?probe=fc1eda0998) | Oct 08, 2021 |
| Toshiba       | dynabook Satellite B453/... | Notebook    | [e621531452](https://bsd-hardware.info/?probe=e621531452) | Oct 05, 2021 |
| ASUSTek       | X441BA                      | Notebook    | [2fcb818b78](https://bsd-hardware.info/?probe=2fcb818b78) | Oct 04, 2021 |
| Dell          | 0D90HM A00                  | All in one  | [d21f14c779](https://bsd-hardware.info/?probe=d21f14c779) | Oct 02, 2021 |
| Lenovo        | ThinkPad T490s 20NYS3TU0... | Notebook    | [d377309110](https://bsd-hardware.info/?probe=d377309110) | Oct 02, 2021 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [efdfee9023](https://bsd-hardware.info/?probe=efdfee9023) | Oct 01, 2021 |
| Lenovo        | ThinkPad X230 2325O76       | Notebook    | [b8729e39e1](https://bsd-hardware.info/?probe=b8729e39e1) | Sep 29, 2021 |
| Toshiba       | Satellite P300              | Notebook    | [13e4aa7026](https://bsd-hardware.info/?probe=13e4aa7026) | Sep 29, 2021 |
| Lenovo        | ThinkPad L520 78594KM       | Notebook    | [7905093412](https://bsd-hardware.info/?probe=7905093412) | Sep 26, 2021 |
| HP            | 87D6 SMVB                   | Desktop     | [90d91bc113](https://bsd-hardware.info/?probe=90d91bc113) | Sep 26, 2021 |
| Gigabyte      | H61M-D2P-B3                 | Desktop     | [c6da80d54b](https://bsd-hardware.info/?probe=c6da80d54b) | Sep 25, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [f336d13e01](https://bsd-hardware.info/?probe=f336d13e01) | Sep 24, 2021 |
| Gigabyte      | H61M-D2P-B3                 | Desktop     | [6ed62a3798](https://bsd-hardware.info/?probe=6ed62a3798) | Sep 23, 2021 |
| Lenovo        | ThinkPad T410 2537E82       | Notebook    | [4ccdde7b89](https://bsd-hardware.info/?probe=4ccdde7b89) | Sep 20, 2021 |
| Foxconn       | A88GMX FAB                  | Desktop     | [b46845b69f](https://bsd-hardware.info/?probe=b46845b69f) | Sep 19, 2021 |
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
| amd64 | 234       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 232       | 99.15%  |
| KDE5         | 1         | 0.43%   |
| GNOME        | 1         | 0.43%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 234       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| SLiM | 234       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 232       | 98.72%  |
| it_IT | 1         | 0.43%   |
| es_ES | 1         | 0.43%   |
| es_AR | 1         | 0.43%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 188       | 80.34%  |
| BIOS | 46        | 19.66%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 234       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 234       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 45        | 19.23%  |
| Lenovo              | 38        | 16.24%  |
| Dell                | 29        | 12.39%  |
| Hewlett-Packard     | 28        | 11.97%  |
| Gigabyte Technology | 11        | 4.7%    |
| ASRock              | 11        | 4.7%    |
| Toshiba             | 8         | 3.42%   |
| Apple               | 8         | 3.42%   |
| MSI                 | 7         | 2.99%   |
| Intel               | 6         | 2.56%   |
| Acer                | 5         | 2.14%   |
| Foxconn             | 4         | 1.71%   |
| Biostar             | 4         | 1.71%   |
| Samsung Electronics | 3         | 1.28%   |
| Pegatron            | 2         | 0.85%   |
| Packard Bell        | 2         | 0.85%   |
| Gateway             | 2         | 0.85%   |
| Fujitsu             | 2         | 0.85%   |
| WYSE                | 1         | 0.43%   |
| TUXEDO              | 1         | 0.43%   |
| Sony                | 1         | 0.43%   |
| Shuttle             | 1         | 0.43%   |
| Protectli           | 1         | 0.43%   |
| PCPartner           | 1         | 0.43%   |
| NEC Computers       | 1         | 0.43%   |
| MouseComputer       | 1         | 0.43%   |
| Microsoft           | 1         | 0.43%   |
| Medion              | 1         | 0.43%   |
| LG Electronics      | 1         | 0.43%   |
| Huanan              | 1         | 0.43%   |
| HC                  | 1         | 0.43%   |
| Hampoo              | 1         | 0.43%   |
| EVGA                | 1         | 0.43%   |
| eMachines           | 1         | 0.43%   |
| Alienware           | 1         | 0.43%   |
| Acidanthera         | 1         | 0.43%   |
| Unknown             | 1         | 0.43%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Dell Inspiron 15-3567                       | 3         | 1.28%   |
| Gateway NE56R                               | 2         | 0.85%   |
| Dell Inspiron 7520                          | 2         | 0.85%   |
| ASUS All Series                             | 2         | 0.85%   |
| ASRock B550M Pro4                           | 2         | 0.85%   |
| ASRock B450M Pro4                           | 2         | 0.85%   |
| Apple MacBookPro9,2                         | 2         | 0.85%   |
| WYSE Z CLASS                                | 1         | 0.43%   |
| TUXEDO Aura 15 Gen1                         | 1         | 0.43%   |
| Toshiba Satellite Pro U400                  | 1         | 0.43%   |
| Toshiba Satellite P300                      | 1         | 0.43%   |
| Toshiba Satellite L855                      | 1         | 0.43%   |
| Toshiba Satellite L500                      | 1         | 0.43%   |
| Toshiba Satellite C640                      | 1         | 0.43%   |
| Toshiba PORTEGE Z10t-A                      | 1         | 0.43%   |
| Toshiba PORTEGE R930                        | 1         | 0.43%   |
| Toshiba dynabook Satellite B453/L           | 1         | 0.43%   |
| Sony VPCEJ1E1E                              | 1         | 0.43%   |
| Shuttle NC10U                               | 1         | 0.43%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 1         | 0.43%   |
| Samsung Galaxy Book 12                      | 1         | 0.43%   |
| Samsung 530U3C/530U4C/532U3C                | 1         | 0.43%   |
| Protectli FW2B                              | 1         | 0.43%   |
| Pegatron SAISHIAT2                          | 1         | 0.43%   |
| Pegatron IPM41-D3                           | 1         | 0.43%   |
| PCPartner DREAMSYS                          | 1         | 0.43%   |
| Packard Bell imedia S2110                   | 1         | 0.43%   |
| Packard Bell EasyNote MH36                  | 1         | 0.43%   |
| NEC Computers PC-VK17HBBCD                  | 1         | 0.43%   |
| MSI WC791AA-UUW HPE-119sc                   | 1         | 0.43%   |
| MSI MS-7C37                                 | 1         | 0.43%   |
| MSI MS-7B86                                 | 1         | 0.43%   |
| MSI MS-7B84                                 | 1         | 0.43%   |
| MSI MS-7A15                                 | 1         | 0.43%   |
| MSI MS-7982                                 | 1         | 0.43%   |
| MSI GF65 Thin 10SDR                         | 1         | 0.43%   |
| MouseComputer W331AU                        | 1         | 0.43%   |
| Microsoft Surface Go                        | 1         | 0.43%   |
| Medion H61H2-LM3                            | 1         | 0.43%   |
| LG 14Z980-G.BH51P1                          | 1         | 0.43%   |
| Lenovo ZIUS6                                | 1         | 0.43%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS          | 1         | 0.43%   |
| Lenovo ThinkPad X260 20F5S82N00             | 1         | 0.43%   |
| Lenovo ThinkPad X250 20CLS4JH00             | 1         | 0.43%   |
| Lenovo ThinkPad X240 20AMS39F0K             | 1         | 0.43%   |
| Lenovo ThinkPad X230 Tablet 343522U         | 1         | 0.43%   |
| Lenovo ThinkPad X230 2330A48                | 1         | 0.43%   |
| Lenovo ThinkPad X230 2325WWB                | 1         | 0.43%   |
| Lenovo ThinkPad X230 2325O76                | 1         | 0.43%   |
| Lenovo ThinkPad X230 23255Y4                | 1         | 0.43%   |
| Lenovo ThinkPad X230 23254G7                | 1         | 0.43%   |
| Lenovo ThinkPad X200 7458VP4                | 1         | 0.43%   |
| Lenovo ThinkPad T61 64607EU                 | 1         | 0.43%   |
| Lenovo ThinkPad T490s 20NYS3TU00            | 1         | 0.43%   |
| Lenovo ThinkPad T490 20RYS06R00             | 1         | 0.43%   |
| Lenovo ThinkPad T470p 20J6A012CD            | 1         | 0.43%   |
| Lenovo ThinkPad T440s 20ARS1B704            | 1         | 0.43%   |
| Lenovo ThinkPad T420 4236FJ1                | 1         | 0.43%   |
| Lenovo ThinkPad T410 2537E82                | 1         | 0.43%   |
| Lenovo ThinkPad T14s Gen 1 20T1S0Q200       | 1         | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 22        | 9.4%    |
| Dell Latitude              | 8         | 3.42%   |
| Dell Inspiron              | 8         | 3.42%   |
| HP Pavilion                | 7         | 2.99%   |
| Toshiba Satellite          | 5         | 2.14%   |
| Dell OptiPlex              | 5         | 2.14%   |
| ASUS PRIME                 | 5         | 2.14%   |
| Acer Aspire                | 5         | 2.14%   |
| Lenovo ThinkCentre         | 4         | 1.71%   |
| Dell Precision             | 4         | 1.71%   |
| HP ProBook                 | 3         | 1.28%   |
| ASUS M5A78L-M              | 3         | 1.28%   |
| Toshiba PORTEGE            | 2         | 0.85%   |
| Lenovo IdeaPad             | 2         | 0.85%   |
| HP EliteBook               | 2         | 0.85%   |
| HP Compaq                  | 2         | 0.85%   |
| Gateway NE56R              | 2         | 0.85%   |
| Dell Vostro                | 2         | 0.85%   |
| ASUS VivoBook              | 2         | 0.85%   |
| ASUS ROG                   | 2         | 0.85%   |
| ASUS P8Z77-V               | 2         | 0.85%   |
| ASUS All                   | 2         | 0.85%   |
| ASRock B550M               | 2         | 0.85%   |
| ASRock B450M               | 2         | 0.85%   |
| Apple MacBookPro9          | 2         | 0.85%   |
| WYSE Z                     | 1         | 0.43%   |
| TUXEDO Aura                | 1         | 0.43%   |
| Toshiba dynabook           | 1         | 0.43%   |
| Sony VPCEJ1E1E             | 1         | 0.43%   |
| Shuttle NC10U              | 1         | 0.43%   |
| Samsung RV411              | 1         | 0.43%   |
| Samsung Galaxy             | 1         | 0.43%   |
| Samsung 530U3C             | 1         | 0.43%   |
| Protectli FW2B             | 1         | 0.43%   |
| Pegatron SAISHIAT2         | 1         | 0.43%   |
| Pegatron IPM41-D3          | 1         | 0.43%   |
| PCPartner DREAMSYS         | 1         | 0.43%   |
| Packard Bell imedia        | 1         | 0.43%   |
| Packard Bell EasyNote      | 1         | 0.43%   |
| NEC Computers PC-VK17HBBCD | 1         | 0.43%   |
| MSI WC791AA-UUW            | 1         | 0.43%   |
| MSI MS-7C37                | 1         | 0.43%   |
| MSI MS-7B86                | 1         | 0.43%   |
| MSI MS-7B84                | 1         | 0.43%   |
| MSI MS-7A15                | 1         | 0.43%   |
| MSI MS-7982                | 1         | 0.43%   |
| MSI GF65                   | 1         | 0.43%   |
| MouseComputer W331AU       | 1         | 0.43%   |
| Microsoft Surface          | 1         | 0.43%   |
| Medion H61H2-LM3           | 1         | 0.43%   |
| LG 14Z980-G.BH51P1         | 1         | 0.43%   |
| Lenovo ZIUS6               | 1         | 0.43%   |
| Lenovo Yoga                | 1         | 0.43%   |
| Lenovo Legion              | 1         | 0.43%   |
| Lenovo IdeaCentre          | 1         | 0.43%   |
| Lenovo G550                | 1         | 0.43%   |
| Lenovo G500s               | 1         | 0.43%   |
| Lenovo G500                | 1         | 0.43%   |
| Lenovo G470                | 1         | 0.43%   |
| Lenovo B41-80              | 1         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 38        | 16.24%  |
| 2019 | 34        | 14.53%  |
| 2013 | 28        | 11.97%  |
| 2018 | 19        | 8.12%   |
| 2012 | 19        | 8.12%   |
| 2021 | 18        | 7.69%   |
| 2011 | 15        | 6.41%   |
| 2014 | 13        | 5.56%   |
| 2010 | 12        | 5.13%   |
| 2015 | 11        | 4.7%    |
| 2009 | 10        | 4.27%   |
| 2016 | 7         | 2.99%   |
| 2017 | 6         | 2.56%   |
| 2008 | 4         | 1.71%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 111       | 47.44%  |
| Desktop     | 110       | 47.01%  |
| All in one  | 5         | 2.14%   |
| Mini pc     | 3         | 1.28%   |
| Tablet      | 2         | 0.85%   |
| Server      | 2         | 0.85%   |
| Convertible | 1         | 0.43%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 233       | 99.57%  |
| Yes  | 1         | 0.43%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 86        | 36.75%  |
| 8.01-16.0   | 81        | 34.62%  |
| 16.01-24.0  | 51        | 21.79%  |
| 32.01-64.0  | 10        | 4.27%   |
| 24.01-32.0  | 3         | 1.28%   |
| 64.01-256.0 | 2         | 0.85%   |
| 2.01-3.0    | 1         | 0.43%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 145       | 61.7%   |
| 0.51-1.0  | 65        | 27.66%  |
| 1.01-2.0  | 19        | 8.09%   |
| 2.01-3.0  | 4         | 1.7%    |
| 4.01-8.0  | 1         | 0.43%   |
| 8.01-16.0 | 1         | 0.43%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 147       | 62.03%  |
| 2      | 47        | 19.83%  |
| 0      | 15        | 6.33%   |
| 3      | 14        | 5.91%   |
| 4      | 7         | 2.95%   |
| 6      | 3         | 1.27%   |
| 5      | 2         | 0.84%   |
| 10     | 1         | 0.42%   |
| 8      | 1         | 0.42%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 130       | 55.56%  |
| Yes       | 104       | 44.44%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 216       | 92.31%  |
| No        | 18        | 7.69%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 156       | 66.38%  |
| No        | 79        | 33.62%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 127       | 54.04%  |
| Yes       | 108       | 45.96%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 41        | 17.45%  |
| Germany            | 18        | 7.66%   |
| Brazil             | 13        | 5.53%   |
| UK                 | 12        | 5.11%   |
| Canada             | 11        | 4.68%   |
| Russia             | 9         | 3.83%   |
| China              | 9         | 3.83%   |
| Spain              | 8         | 3.4%    |
| Italy              | 8         | 3.4%    |
| Netherlands        | 7         | 2.98%   |
| Australia          | 7         | 2.98%   |
| Ukraine            | 6         | 2.55%   |
| Sweden             | 5         | 2.13%   |
| Poland             | 5         | 2.13%   |
| India              | 5         | 2.13%   |
| France             | 5         | 2.13%   |
| Mexico             | 4         | 1.7%    |
| Indonesia          | 4         | 1.7%    |
| Taiwan             | 3         | 1.28%   |
| Switzerland        | 3         | 1.28%   |
| South Korea        | 3         | 1.28%   |
| Portugal           | 3         | 1.28%   |
| Lithuania          | 3         | 1.28%   |
| Argentina          | 3         | 1.28%   |
| Slovakia           | 2         | 0.85%   |
| Peru               | 2         | 0.85%   |
| New Zealand        | 2         | 0.85%   |
| Japan              | 2         | 0.85%   |
| Hungary            | 2         | 0.85%   |
| Greece             | 2         | 0.85%   |
| Finland            | 2         | 0.85%   |
| Belarus            | 2         | 0.85%   |
| Venezuela          | 1         | 0.43%   |
| Uruguay            | 1         | 0.43%   |
| Turkey             | 1         | 0.43%   |
| Thailand           | 1         | 0.43%   |
| South Africa       | 1         | 0.43%   |
| Puerto Rico        | 1         | 0.43%   |
| Oman               | 1         | 0.43%   |
| Norway             | 1         | 0.43%   |
| Morocco            | 1         | 0.43%   |
| Montenegro         | 1         | 0.43%   |
| Malta              | 1         | 0.43%   |
| Malaysia           | 1         | 0.43%   |
| Latvia             | 1         | 0.43%   |
| Guatemala          | 1         | 0.43%   |
| Eswatini           | 1         | 0.43%   |
| Egypt              | 1         | 0.43%   |
| Ecuador            | 1         | 0.43%   |
| Dominican Republic | 1         | 0.43%   |
| Cyprus             | 1         | 0.43%   |
| Croatia            | 1         | 0.43%   |
| Chile              | 1         | 0.43%   |
| Bulgaria           | 1         | 0.43%   |
| Belgium            | 1         | 0.43%   |
| Austria            | 1         | 0.43%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City            | Computers | Percent |
|-----------------|-----------|---------|
| Brisbane        | 3         | 1.26%   |
| Zurich          | 2         | 0.84%   |
| Wroclaw         | 2         | 0.84%   |
| São Paulo      | 2         | 0.84%   |
| Surabaya        | 2         | 0.84%   |
| New York        | 2         | 0.84%   |
| Mumbai          | 2         | 0.84%   |
| Mar del Plata   | 2         | 0.84%   |
| Jakarta         | 2         | 0.84%   |
| Dnipropetrovsk  | 2         | 0.84%   |
| Curitiba        | 2         | 0.84%   |
| Chicago         | 2         | 0.84%   |
| Calgary         | 2         | 0.84%   |
| Berlin          | 2         | 0.84%   |
| Athens          | 2         | 0.84%   |
| Aberdeen        | 2         | 0.84%   |
| Šiauliai       | 1         | 0.42%   |
| Zhongshan       | 1         | 0.42%   |
| Zhengzhou       | 1         | 0.42%   |
| Zagreb          | 1         | 0.42%   |
| York            | 1         | 0.42%   |
| Yekaterinburg   | 1         | 0.42%   |
| Yarang          | 1         | 0.42%   |
| Wuhan           | 1         | 0.42%   |
| Winnipeg        | 1         | 0.42%   |
| Washington      | 1         | 0.42%   |
| Warmond         | 1         | 0.42%   |
| Wandur          | 1         | 0.42%   |
| Vladivostok     | 1         | 0.42%   |
| Vitória        | 1         | 0.42%   |
| Vilnius         | 1         | 0.42%   |
| Villeurbanne    | 1         | 0.42%   |
| Vigonovo        | 1         | 0.42%   |
| Vienna          | 1         | 0.42%   |
| V?�ster??s      | 1         | 0.42%   |
| Vawkavysk       | 1         | 0.42%   |
| Vancouver       | 1         | 0.42%   |
| Utrecht         | 1         | 0.42%   |
| Ufa             | 1         | 0.42%   |
| Tula de Allende | 1         | 0.42%   |
| Trujillo        | 1         | 0.42%   |
| Treviso         | 1         | 0.42%   |
| Traverse City   | 1         | 0.42%   |
| Toronto         | 1         | 0.42%   |
| The Bronx       | 1         | 0.42%   |
| Tettnang Castle | 1         | 0.42%   |
| Tangara         | 1         | 0.42%   |
| Tampere         | 1         | 0.42%   |
| Taichung        | 1         | 0.42%   |
| Taganrog        | 1         | 0.42%   |
| Sydney          | 1         | 0.42%   |
| Suzhou          | 1         | 0.42%   |
| Sungai Buloh    | 1         | 0.42%   |
| St Petersburg   | 1         | 0.42%   |
| Solarino        | 1         | 0.42%   |
| Sofia           | 1         | 0.42%   |
| Simpsonville    | 1         | 0.42%   |
| Shibakoen       | 1         | 0.42%   |
| Sherwood Park   | 1         | 0.42%   |
| Sheffield       | 1         | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 57        | 76     | 18.51%  |
| Seagate             | 50        | 70     | 16.23%  |
| Samsung Electronics | 48        | 64     | 15.58%  |
| Toshiba             | 21        | 22     | 6.82%   |
| Crucial             | 16        | 18     | 5.19%   |
| Kingston            | 14        | 16     | 4.55%   |
| SanDisk             | 13        | 14     | 4.22%   |
| Hitachi             | 13        | 15     | 4.22%   |
| Intel               | 11        | 11     | 3.57%   |
| A-DATA Technology   | 9         | 14     | 2.92%   |
| HGST                | 7         | 7      | 2.27%   |
| Apple               | 7         | 7      | 2.27%   |
| SPCC                | 4         | 5      | 1.3%    |
| Hewlett-Packard     | 4         | 5      | 1.3%    |
| SK Hynix            | 3         | 3      | 0.97%   |
| PNY                 | 3         | 11     | 0.97%   |
| Fujitsu             | 3         | 4      | 0.97%   |
| Transcend           | 2         | 3      | 0.65%   |
| Silicon Motion      | 2         | 2      | 0.65%   |
| Patriot             | 2         | 2      | 0.65%   |
| OCZ                 | 2         | 2      | 0.65%   |
| LITEON              | 2         | 2      | 0.65%   |
| KingSpec            | 2         | 2      | 0.65%   |
| Apacer              | 2         | 2      | 0.65%   |
| SMART               | 1         | 1      | 0.32%   |
| Phison              | 1         | 1      | 0.32%   |
| ORICO               | 1         | 2      | 0.32%   |
| MyDigitalSSD        | 1         | 1      | 0.32%   |
| Micron Technology   | 1         | 1      | 0.32%   |
| LSI                 | 1         | 1      | 0.32%   |
| LITEONIT            | 1         | 1      | 0.32%   |
| Lenovo              | 1         | 1      | 0.32%   |
| HPE                 | 1         | 1      | 0.32%   |
| EMTEC               | 1         | 1      | 0.32%   |
| CLOVER              | 1         | 1      | 0.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB           | 6         | 1.78%   |
| A-DATA SU650 120GB                  | 5         | 1.48%   |
| Seagate ST1000LM035-1RK172 1TB      | 4         | 1.18%   |
| Seagate ST9500325AS 500GB           | 3         | 0.89%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 3         | 0.89%   |
| Seagate ST500DM002-1BD142 500GB     | 3         | 0.89%   |
| Seagate ST3250410AS 250GB           | 3         | 0.89%   |
| Seagate ST1000DM003-1ER162 1TB      | 3         | 0.89%   |
| Samsung SSD 860 EVO 250GB           | 3         | 0.89%   |
| Samsung SSD 860 EVO 1TB             | 3         | 0.89%   |
| Kingston SA400S37240G 240GB         | 3         | 0.89%   |
| Kingston SA400S37120G 120GB         | 3         | 0.89%   |
| WDC WD20EARS-00MVWB0 2TB            | 2         | 0.59%   |
| WDC WD10EZEX-08WN4A0 1TB            | 2         | 0.59%   |
| Seagate ST380815AS 80GB             | 2         | 0.59%   |
| Seagate ST3250318AS 250GB           | 2         | 0.59%   |
| Seagate ST31000528AS 1TB            | 2         | 0.59%   |
| Seagate ST1000LM049-2GH172 1TB      | 2         | 0.59%   |
| SanDisk SDSSDP128G 128GB            | 2         | 0.59%   |
| SanDisk SDSSDA240G 240GB            | 2         | 0.59%   |
| Samsung SSD 970 EVO Plus 250GB      | 2         | 0.59%   |
| Samsung SSD 860 EVO 500GB           | 2         | 0.59%   |
| Samsung SSD 840 EVO 250GB           | 2         | 0.59%   |
| Samsung HN-M101MBB 1TB              | 2         | 0.59%   |
| Intel SSDSC2KW256G8 256GB           | 2         | 0.59%   |
| Intel SSDPEKNW512G8 512GB           | 2         | 0.59%   |
| Hitachi HTS727550A9E364 500GB       | 2         | 0.59%   |
| HGST HTS725050A7E630 500GB          | 2         | 0.59%   |
| HGST HTS545032A7E380 320GB          | 2         | 0.59%   |
| Crucial CT525MX300SSD1 528GB        | 2         | 0.59%   |
| Crucial CT1000P1SSD8 1TB            | 2         | 0.59%   |
| Crucial CT1000MX500SSD1 1TB         | 2         | 0.59%   |
| Apple HDD HTS545050A7E362 500GB     | 2         | 0.59%   |
| A-DATA SX8200PNP 256GB              | 2         | 0.59%   |
| WDC WDS500G3X0C-00SJG0 500GB        | 1         | 0.3%    |
| WDC WDS500G2B0A-00SM50 500GB        | 1         | 0.3%    |
| WDC WDS250G3X0C-00SJG0 250GB        | 1         | 0.3%    |
| WDC WDS250G1B0A-00H9H0 250GB        | 1         | 0.3%    |
| WDC WDS240G2G0A-00JH30 240GB        | 1         | 0.3%    |
| WDC WDS120G2G0A-00JH30 120GB        | 1         | 0.3%    |
| WDC WDS120G1G0A-00SS50 120GB        | 1         | 0.3%    |
| WDC WDS100T2B0A-00SM50 1TB          | 1         | 0.3%    |
| WDC WDBNCE2500PNC 250GB             | 1         | 0.3%    |
| WDC WD80EZAZ-11TDBA0 8TB            | 1         | 0.3%    |
| WDC WD800JD-55MUA1 80GB             | 1         | 0.3%    |
| WDC WD800BEVS-00RST0 80GB           | 1         | 0.3%    |
| WDC WD7500BPVX-60JC3T0 752GB        | 1         | 0.3%    |
| WDC WD7500BPKX-00HPJT0 752GB        | 1         | 0.3%    |
| WDC WD6400AAKS-22A7B0 640GB         | 1         | 0.3%    |
| WDC WD5002ABYS-02B1B0 500GB         | 1         | 0.3%    |
| WDC WD5000LPVX-60V0TT0 500GB        | 1         | 0.3%    |
| WDC WD5000LPVX-00V0TT0 500GB        | 1         | 0.3%    |
| WDC WD5000BEVT-22ZAT0 500GB         | 1         | 0.3%    |
| WDC WD5000AZRX-00L4HB0 500GB        | 1         | 0.3%    |
| WDC WD5000ABYS-01TNA0 500GB         | 1         | 0.3%    |
| WDC WD5000AAKX-60U6AA0 500GB        | 1         | 0.3%    |
| WDC WD5000AAKX-083CA1 500GB         | 1         | 0.3%    |
| WDC WD5000AAKX-00ERMA0 500GB        | 1         | 0.3%    |
| WDC WD5000AAKS-00A7B2 500GB         | 1         | 0.3%    |
| WDC WD40EFRX-68WT0N0 4TB            | 1         | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 50        | 70     | 33.11%  |
| WDC                 | 46        | 63     | 30.46%  |
| Toshiba             | 13        | 13     | 8.61%   |
| Samsung Electronics | 13        | 15     | 8.61%   |
| Hitachi             | 13        | 15     | 8.61%   |
| HGST                | 7         | 7      | 4.64%   |
| Fujitsu             | 3         | 4      | 1.99%   |
| Apple               | 3         | 3      | 1.99%   |
| LSI                 | 1         | 1      | 0.66%   |
| Hewlett-Packard     | 1         | 1      | 0.66%   |
| CLOVER              | 1         | 1      | 0.66%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 29        | 37     | 23.58%  |
| SanDisk             | 13        | 14     | 10.57%  |
| Kingston            | 13        | 14     | 10.57%  |
| Crucial             | 13        | 15     | 10.57%  |
| WDC                 | 7         | 8      | 5.69%   |
| Intel               | 7         | 7      | 5.69%   |
| A-DATA Technology   | 6         | 7      | 4.88%   |
| Toshiba             | 4         | 5      | 3.25%   |
| SPCC                | 4         | 5      | 3.25%   |
| PNY                 | 3         | 9      | 2.44%   |
| Apple               | 3         | 3      | 2.44%   |
| Transcend           | 2         | 3      | 1.63%   |
| Patriot             | 2         | 2      | 1.63%   |
| OCZ                 | 2         | 2      | 1.63%   |
| LITEON              | 2         | 2      | 1.63%   |
| KingSpec            | 2         | 2      | 1.63%   |
| Apacer              | 2         | 2      | 1.63%   |
| SMART               | 1         | 1      | 0.81%   |
| ORICO               | 1         | 2      | 0.81%   |
| MyDigitalSSD        | 1         | 1      | 0.81%   |
| Micron Technology   | 1         | 1      | 0.81%   |
| LITEONIT            | 1         | 1      | 0.81%   |
| Lenovo              | 1         | 1      | 0.81%   |
| HPE                 | 1         | 1      | 0.81%   |
| Hewlett-Packard     | 1         | 2      | 0.81%   |
| EMTEC               | 1         | 1      | 0.81%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 131       | 193    | 46.79%  |
| SSD  | 109       | 148    | 38.93%  |
| NVMe | 40        | 48     | 14.29%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 206       | 341    | 83.74%  |
| NVMe | 40        | 48     | 16.26%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 167       | 237    | 67.89%  |
| 0.51-1.0   | 57        | 72     | 23.17%  |
| 1.01-2.0   | 12        | 16     | 4.88%   |
| 3.01-4.0   | 4         | 5      | 1.63%   |
| 2.01-3.0   | 3         | 6      | 1.22%   |
| 4.01-10.0  | 3         | 5      | 1.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 150       | 63.29%  |
| 101-250    | 34        | 14.35%  |
| 251-500    | 22        | 9.28%   |
| 501-1000   | 18        | 7.59%   |
| 51-100     | 7         | 2.95%   |
| 21-50      | 4         | 1.69%   |
| 1001-2000  | 2         | 0.84%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 234       | 100%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Seagate ST3250410AS 250GB                | 3         | 3      | 4.41%   |
| Seagate ST9500325AS 500GB                | 2         | 2      | 2.94%   |
| Seagate ST380815AS 80GB                  | 2         | 2      | 2.94%   |
| Seagate ST1000LM035-1RK172 1TB           | 2         | 2      | 2.94%   |
| HGST HTS545032A7E380 320GB               | 2         | 2      | 2.94%   |
| Crucial CT525MX300SSD1 528GB             | 2         | 3      | 2.94%   |
| Apple HDD HTS545050A7E362 500GB          | 2         | 2      | 2.94%   |
| WDC WD800JD-55MUA1 80GB                  | 1         | 1      | 1.47%   |
| WDC WD6400AAKS-22A7B0 640GB              | 1         | 1      | 1.47%   |
| WDC WD5000LPVX-60V0TT0 500GB             | 1         | 1      | 1.47%   |
| WDC WD5000AAKX-60U6AA0 500GB             | 1         | 1      | 1.47%   |
| WDC WD5000AAKX-00ERMA0 500GB             | 1         | 1      | 1.47%   |
| WDC WD40EFRX-68WT0N0 4TB                 | 1         | 1      | 1.47%   |
| WDC WD3200BEVT-22ZCT0 320GB              | 1         | 1      | 1.47%   |
| WDC WD3200BEVT-00A0RT0 233GB             | 1         | 1      | 1.47%   |
| WDC WD3200AAJS-00L7A0 320GB              | 1         | 1      | 1.47%   |
| WDC WD30EZRX-22D8PB0 3TB                 | 1         | 1      | 1.47%   |
| WDC WD2500AAKX-083CA1 250GB              | 1         | 1      | 1.47%   |
| WDC WD20EARS-00MVWB0 2TB                 | 1         | 1      | 1.47%   |
| WDC WD1600AAJS-60WAA0 160GB              | 1         | 1      | 1.47%   |
| WDC WD1600AAJS-00WAA0 160GB              | 1         | 1      | 1.47%   |
| WDC WD10EARS-00Y5B1 1TB                  | 1         | 1      | 1.47%   |
| Toshiba THNSNK128GCS8 SATA 128GB         | 1         | 1      | 1.47%   |
| Toshiba MQ01ABD075 752GB                 | 1         | 1      | 1.47%   |
| Toshiba MQ01ABD032 320GB                 | 1         | 1      | 1.47%   |
| Toshiba MK3276GSX 320GB                  | 1         | 1      | 1.47%   |
| Toshiba MK3265GSXN 320GB                 | 1         | 1      | 1.47%   |
| Toshiba MK3261GSYN 320GB                 | 1         | 1      | 1.47%   |
| Seagate ST9320423AS 320GB                | 1         | 1      | 1.47%   |
| Seagate ST9160412AS 160GB                | 1         | 1      | 1.47%   |
| Seagate ST500VT000-1DK142 500GB          | 1         | 1      | 1.47%   |
| Seagate ST500LM012 HN-M500MBB 500GB      | 1         | 1      | 1.47%   |
| Seagate ST3500413AS 500GB                | 1         | 1      | 1.47%   |
| Seagate ST3250318AS 250GB                | 1         | 1      | 1.47%   |
| Seagate ST320LT012-9WS14C 320GB          | 1         | 2      | 1.47%   |
| Seagate ST31000528AS 1TB                 | 1         | 1      | 1.47%   |
| Seagate ST31000333AS 1TB                 | 1         | 1      | 1.47%   |
| Seagate ST1000LM049-2GH172 1TB           | 1         | 1      | 1.47%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 1         | 1      | 1.47%   |
| Samsung Electronics SSD 840 Series 500GB | 1         | 1      | 1.47%   |
| Samsung Electronics SP2004C 200GB        | 1         | 1      | 1.47%   |
| Samsung Electronics HD642JJ 640GB        | 1         | 1      | 1.47%   |
| Samsung Electronics HD321KJ 320GB        | 1         | 1      | 1.47%   |
| Samsung Electronics HD161HJ 160GB        | 1         | 1      | 1.47%   |
| Kingston RBU-SNS8350DES3128GP 128GB      | 1         | 1      | 1.47%   |
| Hitachi HTS727550A9E364 500GB            | 1         | 1      | 1.47%   |
| Hitachi HTS723232A7A364 320GB            | 1         | 1      | 1.47%   |
| Hitachi HTS545050B9A300 500GB            | 1         | 1      | 1.47%   |
| Hitachi HTS545050A7E380 500GB            | 1         | 1      | 1.47%   |
| Hitachi HTS545032B9A300 320GB            | 1         | 1      | 1.47%   |
| Hitachi HTS545025B9SA02 250GB            | 1         | 1      | 1.47%   |
| Hitachi HDS721050CLA362 500GB            | 1         | 1      | 1.47%   |
| Hitachi HDP725025GLA380 250GB            | 1         | 1      | 1.47%   |
| HGST HTS725050A7E630 500GB               | 1         | 1      | 1.47%   |
| HGST HTS721010A9E630 1TB                 | 1         | 1      | 1.47%   |
| HGST HTS541010A9E680 1TB                 | 1         | 1      | 1.47%   |
| Hewlett-Packard SSD S700 1TB             | 1         | 1      | 1.47%   |
| Fujitsu MHZ2250BH G1 250GB               | 1         | 1      | 1.47%   |
| Fujitsu MHW2160BH 160GB                  | 1         | 1      | 1.47%   |
| Apple HDD HTS541010A9E662 1TB            | 1         | 1      | 1.47%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 21     | 28.36%  |
| WDC                 | 15        | 15     | 22.39%  |
| Hitachi             | 8         | 8      | 11.94%  |
| Toshiba             | 6         | 6      | 8.96%   |
| Samsung Electronics | 5         | 5      | 7.46%   |
| HGST                | 5         | 5      | 7.46%   |
| Apple               | 3         | 3      | 4.48%   |
| Fujitsu             | 2         | 2      | 2.99%   |
| Crucial             | 2         | 3      | 2.99%   |
| Kingston            | 1         | 1      | 1.49%   |
| Hewlett-Packard     | 1         | 1      | 1.49%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 21     | 31.15%  |
| WDC                 | 15        | 15     | 24.59%  |
| Hitachi             | 8         | 8      | 13.11%  |
| Toshiba             | 5         | 5      | 8.2%    |
| HGST                | 5         | 5      | 8.2%    |
| Samsung Electronics | 4         | 4      | 6.56%   |
| Apple               | 3         | 3      | 4.92%   |
| Fujitsu             | 2         | 2      | 3.28%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 57        | 63     | 90.48%  |
| SSD  | 6         | 7      | 9.52%   |

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
| Works    | 176       | 304    | 70.97%  |
| Malfunc  | 63        | 70     | 25.4%   |
| Detected | 7         | 13     | 2.82%   |
| Failed   | 2         | 2      | 0.81%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 187       | 65.16%  |
| AMD                         | 39        | 13.59%  |
| Samsung Electronics         | 13        | 4.53%   |
| ASMedia Technology          | 6         | 2.09%   |
| Sandisk                     | 5         | 1.74%   |
| Broadcom / LSI              | 5         | 1.74%   |
| Silicon Motion              | 4         | 1.39%   |
| Toshiba                     | 3         | 1.05%   |
| SK Hynix                    | 3         | 1.05%   |
| Micron/Crucial Technology   | 3         | 1.05%   |
| VIA Technologies            | 2         | 0.7%    |
| Phison Electronics          | 2         | 0.7%    |
| Nvidia                      | 2         | 0.7%    |
| Kingston Technology Company | 2         | 0.7%    |
| JMicron Technology          | 2         | 0.7%    |
| ADATA Technology            | 2         | 0.7%    |
| Adaptec                     | 2         | 0.7%    |
| Silicon Image               | 1         | 0.35%   |
| Realtek Semiconductor       | 1         | 0.35%   |
| Marvell Technology Group    | 1         | 0.35%   |
| KIOXIA                      | 1         | 0.35%   |
| Hewlett-Packard             | 1         | 0.35%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 25        | 7.51%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 20        | 6.01%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 15        | 4.5%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 11        | 3.3%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 10        | 3%      |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 10        | 3%      |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 10        | 3%      |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 9         | 2.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 8         | 2.4%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 8         | 2.4%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 7         | 2.1%    |
| AMD 400 Series Chipset SATA Controller                                                  | 7         | 2.1%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6         | 1.8%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 6         | 1.8%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6         | 1.8%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6         | 1.8%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 6         | 1.8%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5         | 1.5%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5         | 1.5%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 5         | 1.5%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 4         | 1.2%    |
| Intel SATA Controller [RAID mode]                                                       | 4         | 1.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 4         | 1.2%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4         | 1.2%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3         | 0.9%    |
| Intel SSD 660P Series                                                                   | 3         | 0.9%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3         | 0.9%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 3         | 0.9%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 3         | 0.9%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 3         | 0.9%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3         | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3         | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3         | 0.9%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 3         | 0.9%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 3         | 0.9%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 3         | 0.9%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3         | 0.9%    |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 3         | 0.9%    |
| VIA VT6415 PATA IDE Host Controller                                                     | 2         | 0.6%    |
| Toshiba unknown                                                                         | 2         | 0.6%    |
| SK Hynix Gold P31 SSD                                                                   | 2         | 0.6%    |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 2         | 0.6%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2         | 0.6%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2         | 0.6%    |
| Nvidia MCP61 SATA Controller                                                            | 2         | 0.6%    |
| Nvidia MCP61 IDE                                                                        | 2         | 0.6%    |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 2         | 0.6%    |
| Kingston Company A2000 NVMe SSD                                                         | 2         | 0.6%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 2         | 0.6%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 2         | 0.6%    |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 2         | 0.6%    |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 2         | 0.6%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 2         | 0.6%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 2         | 0.6%    |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 2         | 0.6%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2         | 0.6%    |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 2         | 0.6%    |
| Intel 631xESB/632xESB IDE Controller                                                    | 2         | 0.6%    |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 2         | 0.6%    |
| AMD FCH SATA Controller D                                                               | 2         | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 189       | 64.51%  |
| NVMe | 40        | 13.65%  |
| IDE  | 40        | 13.65%  |
| RAID | 18        | 6.14%   |
| SAS  | 3         | 1.02%   |
| SCSI | 3         | 1.02%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 191       | 81.62%  |
| AMD    | 43        | 18.38%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel CPU Version                           | 6         | 2.56%   |
| Intel Xeon                                  | 5         | 2.14%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 5         | 2.14%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 4         | 1.71%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 4         | 1.71%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 3         | 1.28%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 3         | 1.28%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3         | 1.28%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 3         | 1.28%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 2         | 0.85%   |
| Intel Core i7-4510U CPU @ 2.00GHz           | 2         | 0.85%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 2         | 0.85%   |
| Intel Core i7 CPU M 620 @ 2.67GHz           | 2         | 0.85%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 0.85%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 2         | 0.85%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 0.85%   |
| Intel Core i5-3340M CPU @ 2.70GHz           | 2         | 0.85%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 0.85%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 2         | 0.85%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 2         | 0.85%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 2         | 0.85%   |
| Intel Core i3-2370M CPU @ 2.40GHz           | 2         | 0.85%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 2         | 0.85%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 2         | 0.85%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz        | 2         | 0.85%   |
| Intel Core 2 Duo                            | 2         | 0.85%   |
| Intel Celeron CPU N3450 @ 1.10GHz           | 2         | 0.85%   |
| Intel Celeron CPU G3930 @ 2.90GHz           | 2         | 0.85%   |
| Intel Celeron CPU 1005M @ 1.90GHz           | 2         | 0.85%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 2         | 0.85%   |
| AMD A10-5700 APU with Radeon HD Graphics    | 2         | 0.85%   |
| Intel Xeon CPU X3470                        | 1         | 0.43%   |
| Intel Xeon CPU W3550 @ 3.07GHz              | 1         | 0.43%   |
| Intel Xeon CPU E5530 @ 2.40GHz              | 1         | 0.43%   |
| Intel Xeon CPU E5-2630L 0 @ 2.00GHz         | 1         | 0.43%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz         | 1         | 0.43%   |
| Intel Xeon CPU E5-1603 @ 2.80GHz            | 1         | 0.43%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz         | 1         | 0.43%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz         | 1         | 0.43%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 1         | 0.43%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1         | 0.43%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 1         | 0.43%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1         | 0.43%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 1         | 0.43%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 1         | 0.43%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1         | 0.43%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1         | 0.43%   |
| Intel Pentium CPU G3460 @ 3.50GHz           | 1         | 0.43%   |
| Intel Pentium CPU G3420 @ 3.20GHz           | 1         | 0.43%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1         | 0.43%   |
| Intel Pentium CPU B940 @ 2.00GHz            | 1         | 0.43%   |
| Intel Pentium CPU 4415Y @ 1.60GHz           | 1         | 0.43%   |
| Intel Pentium 4 CPU 3.60GHz                 | 1         | 0.43%   |
| Intel Genuine CPU 0000 @ 2.10GHz            | 1         | 0.43%   |
| Intel Genuine CPU                           | 1         | 0.43%   |
| Intel Core i9-7920X CPU @ 2.90GHz           | 1         | 0.43%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1         | 0.43%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 1         | 0.43%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1         | 0.43%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1         | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 64        | 27.35%  |
| Intel Core i3           | 33        | 14.1%   |
| Intel Core i7           | 31        | 13.25%  |
| Intel Celeron           | 16        | 6.84%   |
| Intel Xeon              | 13        | 5.56%   |
| Intel Core 2 Duo        | 10        | 4.27%   |
| Intel Pentium           | 8         | 3.42%   |
| AMD Ryzen 5             | 7         | 2.99%   |
| Other                   | 6         | 2.56%   |
| AMD Ryzen 7             | 5         | 2.14%   |
| AMD FX                  | 5         | 2.14%   |
| Intel Pentium Dual-Core | 4         | 1.71%   |
| AMD Ryzen 3             | 4         | 1.71%   |
| AMD A6                  | 3         | 1.28%   |
| AMD A10                 | 3         | 1.28%   |
| Intel Genuine           | 2         | 0.85%   |
| AMD Ryzen 9             | 2         | 0.85%   |
| AMD Phenom II X4        | 2         | 0.85%   |
| AMD E1                  | 2         | 0.85%   |
| AMD Athlon II X4        | 2         | 0.85%   |
| Intel Pentium Gold      | 1         | 0.43%   |
| Intel Pentium 4         | 1         | 0.43%   |
| Intel Core i9           | 1         | 0.43%   |
| Intel Core 2 Solo       | 1         | 0.43%   |
| AMD Sempron             | 1         | 0.43%   |
| AMD Phenom II X6        | 1         | 0.43%   |
| AMD Phenom II           | 1         | 0.43%   |
| AMD G                   | 1         | 0.43%   |
| AMD Athlon II X3        | 1         | 0.43%   |
| AMD Athlon II X2        | 1         | 0.43%   |
| AMD Athlon II           | 1         | 0.43%   |
| AMD Athlon              | 1         | 0.43%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 118       | 50.43%  |
| 4       | 66        | 28.21%  |
| 6       | 17        | 7.26%   |
| 8       | 12        | 5.13%   |
| Unknown | 8         | 3.42%   |
| 16      | 4         | 1.71%   |
| 12      | 4         | 1.71%   |
| 24      | 2         | 0.85%   |
| 1       | 2         | 0.85%   |
| 3       | 1         | 0.43%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 229       | 97.86%  |
| 2      | 5         | 2.14%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 116       | 49.57%  |
| 1       | 109       | 46.58%  |
| Unknown | 9         | 3.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 36        | 15.38%  |
| IvyBridge     | 31        | 13.25%  |
| SandyBridge   | 26        | 11.11%  |
| Haswell       | 20        | 8.55%   |
| Penryn        | 19        | 8.12%   |
| Skylake       | 17        | 7.26%   |
| Westmere      | 10        | 4.27%   |
| K10           | 9         | 3.85%   |
| Broadwell     | 8         | 3.42%   |
| Zen 2         | 7         | 2.99%   |
| Piledriver    | 7         | 2.99%   |
| CometLake     | 6         | 2.56%   |
| Zen+          | 5         | 2.14%   |
| Zen           | 5         | 2.14%   |
| Silvermont    | 5         | 2.14%   |
| Core          | 5         | 2.14%   |
| Nehalem       | 4         | 1.71%   |
| Zen 3         | 2         | 0.85%   |
| Jaguar        | 2         | 0.85%   |
| Goldmont      | 2         | 0.85%   |
| Bulldozer     | 2         | 0.85%   |
| Bobcat        | 2         | 0.85%   |
| NetBurst      | 1         | 0.43%   |
| K10 Llano     | 1         | 0.43%   |
| Goldmont plus | 1         | 0.43%   |
| Excavator     | 1         | 0.43%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 133       | 51.15%  |
| Nvidia                     | 75        | 28.85%  |
| AMD                        | 51        | 19.62%  |
| Matrox Electronics Systems | 1         | 0.38%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 20        | 7.69%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 18        | 6.92%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 10        | 3.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 9         | 3.46%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 3.08%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 6         | 2.31%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 6         | 2.31%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 1.92%   |
| Intel HD Graphics 620                                                                    | 5         | 1.92%   |
| Intel HD Graphics 5500                                                                   | 5         | 1.92%   |
| Intel HD Graphics 530                                                                    | 5         | 1.92%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 1.92%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 5         | 1.92%   |
| AMD Picasso                                                                              | 5         | 1.92%   |
| Nvidia GT218 [GeForce 210]                                                               | 4         | 1.54%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 1.54%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.54%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 1.54%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 1.15%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 3         | 1.15%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 1.15%   |
| Intel HD Graphics 630                                                                    | 3         | 1.15%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.15%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 2         | 0.77%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 0.77%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 2         | 0.77%   |
| Nvidia GM206 [GeForce GTX 950]                                                           | 2         | 0.77%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 2         | 0.77%   |
| Nvidia G92 [GeForce GTS 250]                                                             | 2         | 0.77%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 0.77%   |
| Intel HD Graphics 500                                                                    | 2         | 0.77%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.77%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 2         | 0.77%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 2         | 0.77%   |
| AMD RS780L [Radeon 3000]                                                                 | 2         | 0.77%   |
| AMD Renoir                                                                               | 2         | 0.77%   |
| AMD Chelsea LP [Radeon HD 7730M]                                                         | 2         | 0.77%   |
| AMD Cezanne                                                                              | 2         | 0.77%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2         | 0.77%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.38%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 1         | 0.38%   |
| Nvidia TU116 [GeForce GTX 1650]                                                          | 1         | 0.38%   |
| Nvidia TU104GL [Quadro RTX 4000]                                                         | 1         | 0.38%   |
| Nvidia NV43 [GeForce 6600]                                                               | 1         | 0.38%   |
| Nvidia GT216M [NVS 5100M]                                                                | 1         | 0.38%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.38%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 0.38%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1         | 0.38%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.38%   |
| Nvidia GM108M [GeForce 930M]                                                             | 1         | 0.38%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 0.38%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.38%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.38%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1         | 0.38%   |
| Nvidia GK208 [GeForce GT 630 Rev. 2]                                                     | 1         | 0.38%   |
| Nvidia GK107M [GeForce GTX 660M]                                                         | 1         | 0.38%   |
| Nvidia GK107 [GeForce GT 740]                                                            | 1         | 0.38%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 1         | 0.38%   |
| Nvidia GK106M [GeForce GTX 770M]                                                         | 1         | 0.38%   |
| Nvidia GK106GL [Quadro K4000]                                                            | 1         | 0.38%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 99        | 42.13%  |
| 1 x Nvidia     | 57        | 24.26%  |
| 1 x AMD        | 42        | 17.87%  |
| Intel + Nvidia | 16        | 6.81%   |
| 2 x Intel      | 10        | 4.26%   |
| Intel + AMD    | 8         | 3.4%    |
| AMD + Nvidia   | 2         | 0.85%   |
| 1 x Matrox     | 1         | 0.43%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 169       | 71.91%  |
| Proprietary | 35        | 14.89%  |
| Unknown     | 31        | 13.19%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 169       | 71.91%  |
| 1.01-2.0   | 21        | 8.94%   |
| 0.51-1.0   | 14        | 5.96%   |
| 0.01-0.5   | 14        | 5.96%   |
| 3.01-4.0   | 8         | 3.4%    |
| 7.01-8.0   | 4         | 1.7%    |
| 5.01-6.0   | 3         | 1.28%   |
| 2.01-3.0   | 2         | 0.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 32        | 17.78%  |
| LG Display              | 24        | 13.33%  |
| AU Optronics            | 18        | 10%     |
| Goldstar                | 13        | 7.22%   |
| Chimei Innolux          | 13        | 7.22%   |
| Dell                    | 10        | 5.56%   |
| Hewlett-Packard         | 8         | 4.44%   |
| Chi Mei Optoelectronics | 5         | 2.78%   |
| BOE                     | 5         | 2.78%   |
| AOC                     | 5         | 2.78%   |
| Acer                    | 5         | 2.78%   |
| Lenovo                  | 4         | 2.22%   |
| BenQ                    | 4         | 2.22%   |
| ViewSonic               | 3         | 1.67%   |
| InfoVision              | 3         | 1.67%   |
| Iiyama                  | 3         | 1.67%   |
| Ancor Communications    | 3         | 1.67%   |
| Sony                    | 2         | 1.11%   |
| Apple                   | 2         | 1.11%   |
| Vizio                   | 1         | 0.56%   |
| VIE                     | 1         | 0.56%   |
| Videoseven              | 1         | 0.56%   |
| Toshiba                 | 1         | 0.56%   |
| Sun                     | 1         | 0.56%   |
| Sharp                   | 1         | 0.56%   |
| RS                      | 1         | 0.56%   |
| Philips                 | 1         | 0.56%   |
| NEC Computers           | 1         | 0.56%   |
| Medion                  | 1         | 0.56%   |
| LG Philips              | 1         | 0.56%   |
| LED                     | 1         | 0.56%   |
| Insignia                | 1         | 0.56%   |
| Gateway                 | 1         | 0.56%   |
| Fujitsu Siemens         | 1         | 0.56%   |
| CVT                     | 1         | 0.56%   |
| CAN                     | 1         | 0.56%   |
| ASUSTek Computer        | 1         | 0.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch          | 3         | 1.67%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch   | 2         | 1.11%   |
| LG Display LCD Monitor LGD0532 1920x1080 340x190mm 15.3-inch           | 2         | 1.11%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch            | 2         | 1.11%   |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch            | 2         | 1.11%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch              | 2         | 1.11%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 310x170mm 13.9-inch       | 2         | 1.11%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 340x190mm 15.3-inch          | 2         | 1.11%   |
| Vizio D32f-F1 VIZ1027 1920x1080 700x390mm 31.5-inch                    | 1         | 0.56%   |
| ViewSonic VX1940w VSC6A20 1680x1050 410x260mm 19.1-inch                | 1         | 0.56%   |
| ViewSonic LCD Monitor VSCD824 1920x1080 520x290mm 23.4-inch            | 1         | 0.56%   |
| ViewSonic LCD Monitor VSC8724 1440x900 410x260mm 19.1-inch             | 1         | 0.56%   |
| VIE A/G2356 VIE2300 1920x1080 500x300mm 23.0-inch                      | 1         | 0.56%   |
| Videoseven WL19A IGM1908 1280x1024 380x300mm 19.1-inch                 | 1         | 0.56%   |
| Toshiba TV TSB0108 1360x768 480x270mm 21.7-inch                        | 1         | 0.56%   |
| Sun X7202A SUN0595 1280x1024 380x300mm 19.1-inch                       | 1         | 0.56%   |
| Sony TV SNYC901 1920x1080                                              | 1         | 0.56%   |
| Sony SDM-HS95P SNY2500 1280x1024 380x300mm 19.1-inch                   | 1         | 0.56%   |
| Sharp LQ100P1JX51 SHP14A6 1800x1200 210x140mm 9.9-inch                 | 1         | 0.56%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 700x390mm 31.5-inch      | 1         | 0.56%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 610x350mm 27.7-inch      | 1         | 0.56%   |
| Samsung Electronics T24D390 SAM0B6E 1920x1080 520x290mm 23.4-inch      | 1         | 0.56%   |
| Samsung Electronics T22C300 SAM0AB3 1920x1080 480x270mm 21.7-inch      | 1         | 0.56%   |
| Samsung Electronics SyncMaster SAM0600 1600x900 440x250mm 19.9-inch    | 1         | 0.56%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 470x300mm 22.0-inch   | 1         | 0.56%   |
| Samsung Electronics SyncMaster SAM03E0 1440x900 410x260mm 19.1-inch    | 1         | 0.56%   |
| Samsung Electronics SyncMaster SAM03D7 1680x1050 470x300mm 22.0-inch   | 1         | 0.56%   |
| Samsung Electronics SyncMaster SAM0320 1680x1050 470x300mm 22.0-inch   | 1         | 0.56%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 490x320mm 23.0-inch   | 1         | 0.56%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 430x270mm 20.0-inch   | 1         | 0.56%   |
| Samsung Electronics SE790C SAM0C62 2560x1080 700x310mm 30.1-inch       | 1         | 0.56%   |
| Samsung Electronics SA300/SA350 SAM078A 1366x768 410x230mm 18.5-inch   | 1         | 0.56%   |
| Samsung Electronics S27D590 SAM0B49 1920x1080 600x340mm 27.2-inch      | 1         | 0.56%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 530x300mm 24.0-inch      | 1         | 0.56%   |
| Samsung Electronics S24C350 SAM0A3A 1920x1080 530x300mm 24.0-inch      | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 330x210mm 15.4-inch   | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 370x230mm 17.2-inch   | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC354C 1366x768 350x200mm 15.9-inch   | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 340x190mm 15.3-inch   | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC4253 1366x768 260x150mm 11.8-inch   | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC324D 1366x768 310x170mm 13.9-inch   | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC324A 1366x768 290x170mm 13.2-inch   | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SAM4A75 1024x768 300x230mm 14.9-inch   | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SAM0F9F 3840x2160 1420x800mm 64.2-inch | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SAM0D3B 3840x2160 890x500mm 40.2-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SAM0AC6 1920x1080 700x390mm 31.5-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 480x270mm 21.7-inch  | 1         | 0.56%   |
| Samsung Electronics LC24RG50 SAM0F91 1920x1080 530x300mm 24.0-inch     | 1         | 0.56%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 520x290mm 23.4-inch      | 1         | 0.56%   |
| RS LE2262 BTC2262 1680x1050 470x290mm 21.7-inch                        | 1         | 0.56%   |
| Philips LCD Monitor PHLC0B1 1920x1080 480x270mm 21.7-inch              | 1         | 0.56%   |
| NEC Computers EA244UHD NEC2B1D 3840x2160 530x300mm 24.0-inch           | 1         | 0.56%   |
| Medion MD21281 MED3947 1366x768 410x230mm 18.5-inch                    | 1         | 0.56%   |
| LG Philips LCD Monitor LPL3B01 1280x800 330x210mm 15.4-inch            | 1         | 0.56%   |
| LG Display LCD Monitor LGD11F9 1280x800 290x180mm 13.4-inch            | 1         | 0.56%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch           | 1         | 0.56%   |
| LG Display LCD Monitor LGD05B1 1920x1080 310x170mm 13.9-inch           | 1         | 0.56%   |
| LG Display LCD Monitor LGD0545 3200x1800 290x170mm 13.2-inch           | 1         | 0.56%   |
| LG Display LCD Monitor LGD053F 1920x1080 340x190mm 15.3-inch           | 1         | 0.56%   |
| LG Display LCD Monitor LGD0527 1366x768 310x170mm 13.9-inch            | 1         | 0.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 60        | 33.71%  |
| 1366x768 (WXGA)    | 53        | 29.78%  |
| 3840x2160 (4K)     | 11        | 6.18%   |
| 1680x1050 (WSXGA+) | 11        | 6.18%   |
| 1280x1024 (SXGA)   | 9         | 5.06%   |
| 1440x900 (WXGA+)   | 7         | 3.93%   |
| 1600x900 (HD+)     | 6         | 3.37%   |
| 1280x800 (WXGA)    | 6         | 3.37%   |
| 2560x1440 (QHD)    | 5         | 2.81%   |
| 2560x1080          | 3         | 1.69%   |
| 3440x1440          | 2         | 1.12%   |
| 3200x1800 (QHD+)   | 1         | 0.56%   |
| 2048x1152          | 1         | 0.56%   |
| 1800x1200          | 1         | 0.56%   |
| 1360x768           | 1         | 0.56%   |
| 1024x768 (XGA)     | 1         | 0.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 32        | 17.88%  |
| 13      | 28        | 15.64%  |
| 21      | 16        | 8.94%   |
| 19      | 15        | 8.38%   |
| 23      | 11        | 6.15%   |
| 27      | 10        | 5.59%   |
| 24      | 10        | 5.59%   |
| 12      | 10        | 5.59%   |
| 17      | 9         | 5.03%   |
| 31      | 7         | 3.91%   |
| 18      | 7         | 3.91%   |
| 22      | 4         | 2.23%   |
| 11      | 4         | 2.23%   |
| 20      | 3         | 1.68%   |
| 34      | 2         | 1.12%   |
| 14      | 2         | 1.12%   |
| 64      | 1         | 0.56%   |
| 54      | 1         | 0.56%   |
| 40      | 1         | 0.56%   |
| 39      | 1         | 0.56%   |
| 30      | 1         | 0.56%   |
| 28      | 1         | 0.56%   |
| 16      | 1         | 0.56%   |
| 9       | 1         | 0.56%   |
| Unknown | 1         | 0.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 54        | 30.17%  |
| 401-500     | 41        | 22.91%  |
| 501-600     | 27        | 15.08%  |
| 201-300     | 25        | 13.97%  |
| 351-400     | 14        | 7.82%   |
| 601-700     | 11        | 6.15%   |
| 801-900     | 2         | 1.12%   |
| 701-800     | 2         | 1.12%   |
| 1001-1500   | 2         | 1.12%   |
| Unknown     | 1         | 0.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 135       | 77.14%  |
| 16/10 | 24        | 13.71%  |
| 5/4   | 8         | 4.57%   |
| 21/9  | 5         | 2.86%   |
| 3/2   | 2         | 1.14%   |
| 4/3   | 1         | 0.57%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 39        | 22.03%  |
| 81-90          | 25        | 14.12%  |
| 91-100         | 25        | 14.12%  |
| 151-200        | 18        | 10.17%  |
| 301-350        | 11        | 6.21%   |
| 61-70          | 10        | 5.65%   |
| 351-500        | 9         | 5.08%   |
| 141-150        | 8         | 4.52%   |
| 101-110        | 8         | 4.52%   |
| 121-130        | 6         | 3.39%   |
| 71-80          | 4         | 2.26%   |
| 51-60          | 4         | 2.26%   |
| More than 1000 | 2         | 1.13%   |
| 251-300        | 2         | 1.13%   |
| 501-1000       | 2         | 1.13%   |
| 41-50          | 1         | 0.56%   |
| 131-140        | 1         | 0.56%   |
| 111-120        | 1         | 0.56%   |
| Unknown        | 1         | 0.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 69        | 39.43%  |
| 101-120       | 57        | 32.57%  |
| 121-160       | 40        | 22.86%  |
| 161-240       | 7         | 4%      |
| More than 240 | 1         | 0.57%   |
| Unknown       | 1         | 0.57%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 166       | 70.64%  |
| 0     | 59        | 25.11%  |
| 2     | 10        | 4.26%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 123       | 37.61%  |
| Intel                             | 107       | 32.72%  |
| Qualcomm Atheros                  | 40        | 12.23%  |
| Broadcom                          | 28        | 8.56%   |
| Ralink                            | 7         | 2.14%   |
| Ralink Technology                 | 4         | 1.22%   |
| Marvell Technology Group          | 4         | 1.22%   |
| D-Link                            | 2         | 0.61%   |
| VIA Technologies                  | 1         | 0.31%   |
| TP-Link                           | 1         | 0.31%   |
| Toshiba                           | 1         | 0.31%   |
| Sierra Wireless                   | 1         | 0.31%   |
| Qualcomm Atheros Communications   | 1         | 0.31%   |
| Mellanox Technologies             | 1         | 0.31%   |
| Hewlett-Packard                   | 1         | 0.31%   |
| Ericsson Business Mobile Networks | 1         | 0.31%   |
| D-Link System                     | 1         | 0.31%   |
| ASUSTek Computer                  | 1         | 0.31%   |
| AboCom Systems                    | 1         | 0.31%   |
| 3Com                              | 1         | 0.31%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 97        | 24.68%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 19        | 4.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 15        | 3.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 9         | 2.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 8         | 2.04%   |
| Intel Wireless 7260                                               | 8         | 2.04%   |
| Intel Wireless 7265                                               | 7         | 1.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 7         | 1.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 6         | 1.53%   |
| Intel Ethernet Connection (7) I219-V                              | 6         | 1.53%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 1.27%   |
| Intel Wireless 8265 / 8275                                        | 5         | 1.27%   |
| Intel Wireless 8260                                               | 5         | 1.27%   |
| Intel WiFi Link 5100                                              | 5         | 1.27%   |
| Intel Wi-Fi 6 AX200                                               | 4         | 1.02%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 1.02%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 1.02%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 1.02%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 4         | 1.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.76%   |
| Intel Wireless 3165                                               | 3         | 0.76%   |
| Intel I211 Gigabit Network Connection                             | 3         | 0.76%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.76%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.76%   |
| Intel Centrino Wireless-N 2230                                    | 3         | 0.76%   |
| Intel Centrino Advanced-N 6200                                    | 3         | 0.76%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.76%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 0.76%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 3         | 0.76%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 3         | 0.76%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.51%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.51%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.51%   |
| Ralink RT5370 Wireless Adapter                                    | 2         | 0.51%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter            | 2         | 0.51%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 0.51%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.51%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.51%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 2         | 0.51%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2         | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.51%   |
| Intel Wireless 3160                                               | 2         | 0.51%   |
| Intel Ultimate N WiFi Link 5300                                   | 2         | 0.51%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.51%   |
| Intel Ethernet Connection I218-V                                  | 2         | 0.51%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.51%   |
| Intel Ethernet Connection (3) I218-V                              | 2         | 0.51%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.51%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 0.51%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 2         | 0.51%   |
| Intel Centrino Advanced-N 6235                                    | 2         | 0.51%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 0.51%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 0.51%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 0.51%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 0.51%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 2         | 0.51%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 2         | 0.51%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 0.51%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1         | 0.25%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 77        | 46.11%  |
| Qualcomm Atheros                | 34        | 20.36%  |
| Realtek Semiconductor           | 22        | 13.17%  |
| Broadcom                        | 15        | 8.98%   |
| Ralink                          | 7         | 4.19%   |
| Ralink Technology               | 4         | 2.4%    |
| D-Link                          | 2         | 1.2%    |
| TP-Link                         | 1         | 0.6%    |
| Sierra Wireless                 | 1         | 0.6%    |
| Qualcomm Atheros Communications | 1         | 0.6%    |
| D-Link System                   | 1         | 0.6%    |
| ASUSTek Computer                | 1         | 0.6%    |
| AboCom Systems                  | 1         | 0.6%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 9         | 5.39%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 8         | 4.79%   |
| Intel Wireless 7260                                                                   | 8         | 4.79%   |
| Intel Wireless 7265                                                                   | 7         | 4.19%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 7         | 4.19%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 6         | 3.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 5         | 2.99%   |
| Intel Wireless 8265 / 8275                                                            | 5         | 2.99%   |
| Intel Wireless 8260                                                                   | 5         | 2.99%   |
| Intel WiFi Link 5100                                                                  | 5         | 2.99%   |
| Intel Wi-Fi 6 AX200                                                                   | 4         | 2.4%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 4         | 2.4%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 4         | 2.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 3         | 1.8%    |
| Intel Wireless 3165                                                                   | 3         | 1.8%    |
| Intel Centrino Wireless-N 2230                                                        | 3         | 1.8%    |
| Intel Centrino Advanced-N 6200                                                        | 3         | 1.8%    |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 3         | 1.8%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                              | 2         | 1.2%    |
| Realtek RTL8188EE Wireless Network Adapter                                            | 2         | 1.2%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 2         | 1.2%    |
| Ralink RT5370 Wireless Adapter                                                        | 2         | 1.2%    |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                | 2         | 1.2%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                             | 2         | 1.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 2         | 1.2%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 2         | 1.2%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 2         | 1.2%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 2         | 1.2%    |
| Intel Wireless 3160                                                                   | 2         | 1.2%    |
| Intel Ultimate N WiFi Link 5300                                                       | 2         | 1.2%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 2         | 1.2%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 2         | 1.2%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                          | 2         | 1.2%    |
| Intel Centrino Advanced-N 6235                                                        | 2         | 1.2%    |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 2         | 1.2%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                    | 2         | 1.2%    |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                    | 2         | 1.2%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 2         | 1.2%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                            | 1         | 0.6%    |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                                         | 1         | 0.6%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 1         | 0.6%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.6%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 1         | 0.6%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                | 1         | 0.6%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 1         | 0.6%    |
| Realtek RTL8191SEvB Wireless LAN Controller                                           | 1         | 0.6%    |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                | 1         | 0.6%    |
| Ralink RT2501/RT2573 Wireless Adapter                                                 | 1         | 0.6%    |
| Ralink MT7601U Wireless Adapter                                                       | 1         | 0.6%    |
| Ralink RT5392 PCIe Wireless Network Adapter                                           | 1         | 0.6%    |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                                             | 1         | 0.6%    |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 1         | 0.6%    |
| Qualcomm Atheros AR9271 802.11n                                                       | 1         | 0.6%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 1         | 0.6%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 0.6%    |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.6%    |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn]                | 1         | 0.6%    |
| Intel Wireless-AC 9260                                                                | 1         | 0.6%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                               | 1         | 0.6%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                         | 1         | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 116       | 53.21%  |
| Intel                    | 65        | 29.82%  |
| Broadcom                 | 20        | 9.17%   |
| Qualcomm Atheros         | 12        | 5.5%    |
| Marvell Technology Group | 4         | 1.83%   |
| VIA Technologies         | 1         | 0.46%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 97        | 43.89%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 19        | 8.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 15        | 6.79%   |
| Intel Ethernet Connection (7) I219-V                              | 6         | 2.71%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 1.81%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 4         | 1.81%   |
| Intel I211 Gigabit Network Connection                             | 3         | 1.36%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.36%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.36%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.36%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 1.36%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 3         | 1.36%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.9%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.9%    |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.9%    |
| Intel Ethernet Connection I218-V                                  | 2         | 0.9%    |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.9%    |
| Intel Ethernet Connection (3) I218-V                              | 2         | 0.9%    |
| Intel 82567LM Gigabit Network Connection                          | 2         | 0.9%    |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 0.9%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 0.9%    |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1         | 0.45%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.45%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.45%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 0.45%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.45%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.45%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.45%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.45%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.45%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.45%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.45%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 0.45%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 0.45%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 0.45%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.45%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.45%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.45%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 0.45%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.45%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.45%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 0.45%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.45%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 0.45%   |
| Intel Ethernet Connection (12) I219-V                             | 1         | 0.45%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 0.45%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 0.45%   |
| Intel 82583V Gigabit Network Connection                           | 1         | 0.45%   |
| Intel 82578DM Gigabit Network Connection                          | 1         | 0.45%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 0.45%   |
| Intel 82567LF Gigabit Network Connection                          | 1         | 0.45%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 0.45%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1         | 0.45%   |
| Intel 82562V-2 10/100 Network Connection                          | 1         | 0.45%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1         | 0.45%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                    | 1         | 0.45%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1         | 0.45%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1         | 0.45%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1         | 0.45%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 0.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 216       | 57.45%  |
| WiFi     | 155       | 41.22%  |
| Modem    | 3         | 0.8%    |
| Unknown  | 2         | 0.53%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 214       | 61.85%  |
| WiFi     | 128       | 36.99%  |
| Modem    | 2         | 0.58%   |
| Unknown  | 2         | 0.58%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 135       | 57.45%  |
| 1     | 96        | 40.85%  |
| 3     | 3         | 1.28%   |
| 0     | 1         | 0.43%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 224       | 94.92%  |
| Yes  | 12        | 5.08%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 49        | 44.55%  |
| Broadcom                        | 11        | 10%     |
| Qualcomm Atheros Communications | 9         | 8.18%   |
| Cambridge Silicon Radio         | 9         | 8.18%   |
| Apple                           | 8         | 7.27%   |
| Realtek Semiconductor           | 7         | 6.36%   |
| IMC Networks                    | 4         | 3.64%   |
| ASUSTek Computer                | 3         | 2.73%   |
| Ralink                          | 2         | 1.82%   |
| Lite-On Technology              | 2         | 1.82%   |
| Dell                            | 2         | 1.82%   |
| Integrated System Solution      | 1         | 0.91%   |
| Hewlett-Packard                 | 1         | 0.91%   |
| Foxconn / Hon Hai               | 1         | 0.91%   |
| Edimax Technology               | 1         | 0.91%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 30        | 27.27%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 9         | 8.18%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 5         | 4.55%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 5         | 4.55%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 4         | 3.64%   |
| Intel AX200 Bluetooth                                       | 4         | 3.64%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 4         | 3.64%   |
| Intel AX201 Bluetooth                                       | 3         | 2.73%   |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 1.82%   |
| Ralink RT3290 Bluetooth                                     | 2         | 1.82%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 2         | 1.82%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 1.82%   |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS                 | 2         | 1.82%   |
| Intel Wireless-AC 3168 Bluetooth                            | 2         | 1.82%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 2         | 1.82%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 2         | 1.82%   |
| Realtek RTL8821A Bluetooth                                  | 1         | 0.91%   |
| Realtek  Bluetooth Adapter                                  | 1         | 0.91%   |
| Realtek  Bluetooth 4.0 + High Speed Chip                    | 1         | 0.91%   |
| Realtek CSR Bluetooth Chip                                  | 1         | 0.91%   |
| Realtek Bluetooth Radio                                     | 1         | 0.91%   |
| Qualcomm Atheros  QCA9565 Bluetooth 4.0 + HS Adapter        | 1         | 0.91%   |
| Qualcomm Atheros  QCA61x4 Bluetooth 4.1                     | 1         | 0.91%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 0.91%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 0.91%   |
| Qualcomm Atheros Atheros AR9462 Bluetooth 3.0 + HS Adapter  | 1         | 0.91%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 0.91%   |
| Integrated System Solution Bluetooth Device                 | 1         | 0.91%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0                 | 1         | 0.91%   |
| IMC Networks Broadcom BCM20702 Bluetooth 4.0 +HS USB Device | 1         | 0.91%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 0.91%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 0.91%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter     | 1         | 0.91%   |
| Dell DW375 Bluetooth Module                                 | 1         | 0.91%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 1         | 0.91%   |
| Broadcom Bluetooth Device                                   | 1         | 0.91%   |
| Broadcom Bluetooth 2.0+eDR dongle                           | 1         | 0.91%   |
| Broadcom BCM43142A0 Bluetooth 4.0                           | 1         | 0.91%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 1         | 0.91%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                        | 1         | 0.91%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 1         | 0.91%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 1         | 0.91%   |
| ASUS Realtek Bluetooth 4.0 + High Speed Chip                | 1         | 0.91%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1         | 0.91%   |
| Apple Bluetooth USB Host Controller                         | 1         | 0.91%   |
| Apple Bluetooth Host Controller                             | 1         | 0.91%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 189       | 60.97%  |
| AMD                         | 56        | 18.06%  |
| Nvidia                      | 52        | 16.77%  |
| Texas Instruments           | 2         | 0.65%   |
| Creative Technology         | 2         | 0.65%   |
| C-Media Electronics         | 2         | 0.65%   |
| XMOS                        | 1         | 0.32%   |
| Steinberg Soft-und Hardware | 1         | 0.32%   |
| SteelSeries ApS             | 1         | 0.32%   |
| Realtek Semiconductor       | 1         | 0.32%   |
| Logitech                    | 1         | 0.32%   |
| Ensoniq                     | 1         | 0.32%   |
| Creative Labs               | 1         | 0.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 32        | 8.89%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 22        | 6.11%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 16        | 4.44%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 14        | 3.89%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 14        | 3.89%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 12        | 3.33%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 11        | 3.06%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 3.06%   |
| Intel Cannon Lake PCH cAVS                                                                        | 10        | 2.78%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 10        | 2.78%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 9         | 2.5%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 7         | 1.94%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 1.94%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 1.94%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 1.94%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 6         | 1.67%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 6         | 1.67%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 1.67%   |
| Intel 200 Series PCH HD Audio                                                                     | 6         | 1.67%   |
| AMD FCH Azalia Controller                                                                         | 6         | 1.67%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 5         | 1.39%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 5         | 1.39%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5         | 1.39%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 5         | 1.39%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 1.39%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 4         | 1.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.11%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 1.11%   |
| Intel Comet Lake PCH-V Smart Sound Technology Audio Controller                                    | 4         | 1.11%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.11%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 4         | 1.11%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 1.11%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 4         | 1.11%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.83%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.83%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 0.83%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3         | 0.83%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 0.83%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 0.83%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 3         | 0.83%   |
| Nvidia MCP61 High Definition Audio                                                                | 2         | 0.56%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.56%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 0.56%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.56%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 2         | 0.56%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 2         | 0.56%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.56%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 2         | 0.56%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.56%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 0.56%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 0.56%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 2         | 0.56%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.56%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 2         | 0.56%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 0.56%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 0.56%   |
| XMOS Cyberdrive Audio Driver                                                                      | 1         | 0.28%   |
| Texas Instruments SMSL Q5 AMP                                                                     | 1         | 0.28%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.28%   |
| Steinberg Soft-und Hardware MI4                                                                   | 1         | 0.28%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Samsung Electronics        | 49        | 17.25%  |
| SK Hynix                   | 39        | 13.73%  |
| Kingston                   | 37        | 13.03%  |
| Unknown                    | 35        | 12.32%  |
| Micron Technology          | 28        | 9.86%   |
| Crucial                    | 22        | 7.75%   |
| Elpida                     | 13        | 4.58%   |
| G.Skill                    | 8         | 2.82%   |
| Corsair                    | 7         | 2.46%   |
| Ramaxel Technology         | 6         | 2.11%   |
| Nanya Technology           | 6         | 2.11%   |
| Smart                      | 4         | 1.41%   |
| A-DATA Technology          | 4         | 1.41%   |
| Apacer                     | 3         | 1.06%   |
| Teikon                     | 2         | 0.7%    |
| Team                       | 2         | 0.7%    |
| PNY                        | 2         | 0.7%    |
| High Bridge                | 2         | 0.7%    |
| Avant                      | 2         | 0.7%    |
| AMD                        | 2         | 0.7%    |
| Unknown (ABCD)             | 1         | 0.35%   |
| Unknown (7F7F7F94FFFFFFFF) | 1         | 0.35%   |
| Unknown (09A4)             | 1         | 0.35%   |
| Transcend                  | 1         | 0.35%   |
| Toshiba                    | 1         | 0.35%   |
| Smart Brazil               | 1         | 0.35%   |
| SHARETRONIC                | 1         | 0.35%   |
| Patriot                    | 1         | 0.35%   |
| Goldkey                    | 1         | 0.35%   |
| Axiom                      | 1         | 0.35%   |
| Unknown                    | 1         | 0.35%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                              | Computers | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB DIMM 1333MT/s                               | 4         | 1.3%    |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s             | 4         | 1.3%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s              | 4         | 1.3%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                               | 3         | 0.98%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s              | 3         | 0.98%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s             | 3         | 0.98%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s              | 3         | 0.98%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1333MT/s              | 3         | 0.98%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s              | 3         | 0.98%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s              | 3         | 0.98%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                        | 2         | 0.65%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                        | 2         | 0.65%   |
| SK Hynix RAM Module 2GB SODIMM DDR3 1600MT/s                       | 2         | 0.65%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s             | 2         | 0.65%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s              | 2         | 0.65%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s             | 2         | 0.65%   |
| Samsung RAM K3QF4F40BM-AGCF 4GB Row Of Chips LPDDR3 1867MT/s       | 2         | 0.65%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s              | 2         | 0.65%   |
| Micron RAM 8JTF25664AZ-1G6M1 2GB DIMM DDR3 1600MT/s                | 2         | 0.65%   |
| Micron RAM 4ATF51264HZ-2G3E1 4GB SODIMM DDR4 2400MT/s              | 2         | 0.65%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s              | 2         | 0.65%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s             | 2         | 0.65%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3200MT/s               | 2         | 0.65%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 2667MT/s                  | 2         | 0.65%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s                | 2         | 0.65%   |
| G.Skill RAM F4-2666C19-8GNT 8GB DIMM DDR4 2666MT/s                 | 2         | 0.65%   |
| Unknown RAM TMKS8G68ALFBCH-266 8192MB SODIMM DDR4 2400MT/s         | 1         | 0.33%   |
| Unknown RAM R9P5316-007.A02LF 2GB DIMM 533MT/s                     | 1         | 0.33%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                        | 1         | 0.33%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                          | 1         | 0.33%   |
| Unknown RAM Module 8GB DIMM DDR3 1866MT/s                          | 1         | 0.33%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                               | 1         | 0.33%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                        | 1         | 0.33%   |
| Unknown RAM Module 4GB SODIMM DDR3                                 | 1         | 0.33%   |
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                         | 1         | 0.33%   |
| Unknown RAM Module 4GB DIMM DDR3 1866MT/s                          | 1         | 0.33%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                          | 1         | 0.33%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                           | 1         | 0.33%   |
| Unknown RAM Module 4GB DIMM 667MT/s                                | 1         | 0.33%   |
| Unknown RAM Module 4096MB DIMM DDR2                                | 1         | 0.33%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                         | 1         | 0.33%   |
| Unknown RAM Module 2GB FB-DIMM DDR2 667MT/s                        | 1         | 0.33%   |
| Unknown RAM Module 2GB DIMM SDRAM                                  | 1         | 0.33%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                          | 1         | 0.33%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                           | 1         | 0.33%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                           | 1         | 0.33%   |
| Unknown RAM Module 2GB DIMM 533MT/s                                | 1         | 0.33%   |
| Unknown RAM Module 2GB DIMM 1600MT/s                               | 1         | 0.33%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                           | 1         | 0.33%   |
| Unknown RAM Module 2048MB SODIMM 667MT/s                           | 1         | 0.33%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s                       | 1         | 0.33%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                        | 1         | 0.33%   |
| Unknown RAM Module 2048MB DIMM DDR2                                | 1         | 0.33%   |
| Unknown RAM Module 1GB DIMM 1333MT/s                               | 1         | 0.33%   |
| Unknown RAM Module 1024MB DIMM SDRAM 667MT/s                       | 1         | 0.33%   |
| Unknown RAM 7TE39AA# 8GB DIMM DDR4 2667MT/s                        | 1         | 0.33%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s       | 1         | 0.33%   |
| Unknown (7F7F7F94FFFFFFFF) RAM 996593PCGH 2048MB DIMM DDR2 800MT/s | 1         | 0.33%   |
| Unknown (09A4) RAM 08S2400CL170H 8192MB DIMM DDR4 2133MT/s         | 1         | 0.33%   |
| Transcend RAM JM1600KSH-8G 8192MB SODIMM DDR3 1333MT/s             | 1         | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 120       | 51.28%  |
| DDR4    | 75        | 32.05%  |
| Unknown | 16        | 6.84%   |
| DDR2    | 14        | 5.98%   |
| LPDDR3  | 4         | 1.71%   |
| SDRAM   | 3         | 1.28%   |
| LPDDR4  | 1         | 0.43%   |
| DDR     | 1         | 0.43%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 119       | 50.85%  |
| DIMM         | 104       | 44.44%  |
| Row Of Chips | 6         | 2.56%   |
| FB-DIMM      | 2         | 0.85%   |
| Chip         | 2         | 0.85%   |
| Unknown      | 1         | 0.43%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 109       | 40.07%  |
| 2048  | 72        | 26.47%  |
| 8192  | 66        | 24.26%  |
| 16384 | 17        | 6.25%   |
| 1024  | 5         | 1.84%   |
| 32768 | 3         | 1.1%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 72        | 27.69%  |
| 1333    | 49        | 18.85%  |
| 2400    | 28        | 10.77%  |
| 2667    | 23        | 8.85%   |
| 2133    | 18        | 6.92%   |
| 800     | 13        | 5%      |
| 667     | 10        | 3.85%   |
| 1334    | 9         | 3.46%   |
| 3200    | 8         | 3.08%   |
| 2666    | 5         | 1.92%   |
| 1867    | 5         | 1.92%   |
| 1067    | 3         | 1.15%   |
| 1066    | 3         | 1.15%   |
| 533     | 3         | 1.15%   |
| Unknown | 3         | 1.15%   |
| 2933    | 2         | 0.77%   |
| 1866    | 2         | 0.77%   |
| 1800    | 1         | 0.38%   |
| 1777    | 1         | 0.38%   |
| 1400    | 1         | 0.38%   |
| 975     | 1         | 0.38%   |

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
| Chicony Electronics                    | 21        | 22.83%  |
| Realtek Semiconductor                  | 11        | 11.96%  |
| Microdia                               | 7         | 7.61%   |
| Sunplus Innovation Technology          | 6         | 6.52%   |
| IMC Networks                           | 6         | 6.52%   |
| Acer                                   | 6         | 6.52%   |
| Suyin                                  | 5         | 5.43%   |
| Apple                                  | 4         | 4.35%   |
| Syntek                                 | 3         | 3.26%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.26%   |
| Silicon Motion                         | 2         | 2.17%   |
| Logitech                               | 2         | 2.17%   |
| Lite-On Technology                     | 2         | 2.17%   |
| Importek                               | 2         | 2.17%   |
| Alcor Micro                            | 2         | 2.17%   |
| Ricoh                                  | 1         | 1.09%   |
| Quanta                                 | 1         | 1.09%   |
| Lenovo                                 | 1         | 1.09%   |
| Intel                                  | 1         | 1.09%   |
| Holitech                               | 1         | 1.09%   |
| Hewlett-Packard                        | 1         | 1.09%   |
| HD WEBCAM                              | 1         | 1.09%   |
| Generalplus Technology                 | 1         | 1.09%   |
| GEMBIRD                                | 1         | 1.09%   |
| A4Tech                                 | 1         | 1.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                               | 5         | 5.38%   |
| Chicony Integrated Camera                                  | 5         | 5.38%   |
| Realtek Realtek USB2.0 PC Camera                           | 3         | 3.23%   |
| Chicony Integrated Camera [ThinkPad]                       | 3         | 3.23%   |
| Chicony HP HD Webcam [Fixed]                               | 3         | 3.23%   |
| Apple FaceTime HD Camera                                   | 3         | 3.23%   |
| Syntek Lenovo EasyCamera                                   | 2         | 2.15%   |
| Sunplus Integrated_Webcam_HD                               | 2         | 2.15%   |
| Sunplus Asus Webcam                                        | 2         | 2.15%   |
| Realtek Integrated Webcam                                  | 2         | 2.15%   |
| Microdia Laptop_Integrated_Webcam_HD                       | 2         | 2.15%   |
| Microdia Integrated Webcam                                 | 2         | 2.15%   |
| Logitech Webcam C270                                       | 2         | 2.15%   |
| IMC Networks USB2.0 HD UVC WebCam                          | 2         | 2.15%   |
| IMC Networks Integrated Camera                             | 2         | 2.15%   |
| Acer Integrated Camera                                     | 2         | 2.15%   |
| Syntek EasyCamera                                          | 1         | 1.08%   |
| Suyin USB 2.0 Camera                                       | 1         | 1.08%   |
| Suyin Sony Visual Communication Camera                     | 1         | 1.08%   |
| Suyin HP Webcam-101                                        | 1         | 1.08%   |
| Suyin HP Integrated Webcam                                 | 1         | 1.08%   |
| Suyin Acer/Lenovo Webcam [CN0316]                          | 1         | 1.08%   |
| Sunplus Integrated Camera                                  | 1         | 1.08%   |
| Sunplus Dell E5570 integrated webcam                       | 1         | 1.08%   |
| Silicon Motion WebCam SCX Series                           | 1         | 1.08%   |
| Silicon Motion Realtek USB2.0 PC Camera                    | 1         | 1.08%   |
| Ricoh Integrated Camera                                    | 1         | 1.08%   |
| Realtek LG Camera                                          | 1         | 1.08%   |
| Quanta HP Webcam                                           | 1         | 1.08%   |
| Microdia Laptop_Integrated_Webcam_FHD                      | 1         | 1.08%   |
| Microdia HP Webcam                                         | 1         | 1.08%   |
| Microdia ASUS USB2.0 Webcam                                | 1         | 1.08%   |
| Lite-On Integrated Camera                                  | 1         | 1.08%   |
| Lite-On HP IR Camera                                       | 1         | 1.08%   |
| Lenovo Integrated Webcam [R5U877]                          | 1         | 1.08%   |
| Intel Intel(R) RealSense(TM) 3D Camera (Front F200)        | 1         | 1.08%   |
| Importek TOSHIBA Web Camera - HD                           | 1         | 1.08%   |
| Importek TOSHIBA Web Camera                                | 1         | 1.08%   |
| IMC Networks USB2.0 VGA UVC WebCam                         | 1         | 1.08%   |
| IMC Networks EasyCamera                                    | 1         | 1.08%   |
| Holitech USB2.0 HD UVC WebCam                              | 1         | 1.08%   |
| HP Premium Starter Webcam                                  | 1         | 1.08%   |
| HD WEBCAM HD WEBCAM                                        | 1         | 1.08%   |
| Generalplus GENERAL WEBCAM                                 | 1         | 1.08%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]          | 1         | 1.08%   |
| Chicony UVC 1.00 device HD UVC WebCam                      | 1         | 1.08%   |
| Chicony USB2.0 VGA UVC WebCam                              | 1         | 1.08%   |
| Chicony USB 2.0 Camera                                     | 1         | 1.08%   |
| Chicony TOSHIBA Web Camera - HD                            | 1         | 1.08%   |
| Chicony TOSHIBA Web Camera - 3M                            | 1         | 1.08%   |
| Chicony Lenovo EasyCamera                                  | 1         | 1.08%   |
| Chicony HP Webcam [2 MP Macro]                             | 1         | 1.08%   |
| Chicony HP HD Camera                                       | 1         | 1.08%   |
| Chicony HD WebCam                                          | 1         | 1.08%   |
| Chicony Chicony USB2.0 Camera                              | 1         | 1.08%   |
| Chicony 1.3M Webcam                                        | 1         | 1.08%   |
| Cheng Uei Precision Industry (Foxlink) Webcam              | 1         | 1.08%   |
| Cheng Uei Precision Industry (Foxlink) Realtek DMFT - RGB  | 1         | 1.08%   |
| Cheng Uei Precision Industry (Foxlink) HP Universal Camera | 1         | 1.08%   |
| Apple FaceTime HD Camera (Built-in)                        | 1         | 1.08%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Validity Sensors   | 8         | 66.67%  |
| Synaptics          | 1         | 8.33%   |
| STMicroelectronics | 1         | 8.33%   |
| Broadcom           | 1         | 8.33%   |
| AuthenTec          | 1         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                                  | 3         | 25%     |
| Validity Sensors VFS495 Fingerprint Reader                                   | 2         | 16.67%  |
| Validity Sensors VFS451 Fingerprint Reader                                   | 1         | 8.33%   |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 1         | 8.33%   |
| Validity Sensors Synaptics WBDI                                              | 1         | 8.33%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 1         | 8.33%   |
| STMicroelectronics Fingerprint Reader                                        | 1         | 8.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 8.33%   |
| AuthenTec AES2810                                                            | 1         | 8.33%   |

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
| 1     | 95        | 40.08%  |
| 2     | 56        | 23.63%  |
| 0     | 52        | 21.94%  |
| 3     | 26        | 10.97%  |
| 4     | 7         | 2.95%   |
| 6     | 1         | 0.42%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 154       | 50.66%  |
| Card reader              | 57        | 18.75%  |
| Net/wireless             | 37        | 12.17%  |
| Bluetooth                | 22        | 7.24%   |
| Firewire controller      | 12        | 3.95%   |
| Fingerprint reader       | 12        | 3.95%   |
| Sound                    | 5         | 1.64%   |
| Storage                  | 3         | 0.99%   |
| Storage/raid             | 1         | 0.33%   |
| Dvb card                 | 1         | 0.33%   |

