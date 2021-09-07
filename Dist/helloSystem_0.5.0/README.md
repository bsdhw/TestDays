helloSystem 0.5.0 - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for helloSystem 0.5.0 (Beta test).

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

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 205       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 203       | 99.02%  |
| KDE5         | 1         | 0.49%   |
| GNOME        | 1         | 0.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 205       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| SLiM | 205       | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 203       | 98.54%  |
| it_IT | 1         | 0.49%   |
| es_ES | 1         | 0.49%   |
| es_AR | 1         | 0.49%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 167       | 81.46%  |
| BIOS | 38        | 18.54%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 205       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 205       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 40        | 19.51%  |
| Dell                | 28        | 13.66%  |
| Lenovo              | 27        | 13.17%  |
| Hewlett-Packard     | 24        | 11.71%  |
| Gigabyte Technology | 10        | 4.88%   |
| ASRock              | 9         | 4.39%   |
| Apple               | 8         | 3.9%    |
| MSI                 | 7         | 3.41%   |
| Toshiba             | 6         | 2.93%   |
| Intel               | 6         | 2.93%   |
| Biostar             | 4         | 1.95%   |
| Acer                | 4         | 1.95%   |
| Samsung Electronics | 3         | 1.46%   |
| Foxconn             | 3         | 1.46%   |
| Pegatron            | 2         | 0.98%   |
| Gateway             | 2         | 0.98%   |
| Fujitsu             | 2         | 0.98%   |
| WYSE                | 1         | 0.49%   |
| TUXEDO              | 1         | 0.49%   |
| Sony                | 1         | 0.49%   |
| Shuttle             | 1         | 0.49%   |
| Protectli           | 1         | 0.49%   |
| PCPartner           | 1         | 0.49%   |
| Packard Bell        | 1         | 0.49%   |
| NEC Computers       | 1         | 0.49%   |
| MouseComputer       | 1         | 0.49%   |
| Microsoft           | 1         | 0.49%   |
| Medion              | 1         | 0.49%   |
| LG Electronics      | 1         | 0.49%   |
| Huanan              | 1         | 0.49%   |
| HC                  | 1         | 0.49%   |
| Hampoo              | 1         | 0.49%   |
| EVGA                | 1         | 0.49%   |
| eMachines           | 1         | 0.49%   |
| Alienware           | 1         | 0.49%   |
| Acidanthera         | 1         | 0.49%   |
| Unknown             | 1         | 0.49%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Dell Inspiron 15-3567                       | 3         | 1.46%   |
| Gateway NE56R                               | 2         | 0.98%   |
| Dell Inspiron 7520                          | 2         | 0.98%   |
| ASUS All Series                             | 2         | 0.98%   |
| ASRock B450M Pro4                           | 2         | 0.98%   |
| Apple MacBookPro9,2                         | 2         | 0.98%   |
| WYSE Z CLASS                                | 1         | 0.49%   |
| TUXEDO Aura 15 Gen1                         | 1         | 0.49%   |
| Toshiba Satellite Pro U400                  | 1         | 0.49%   |
| Toshiba Satellite L855                      | 1         | 0.49%   |
| Toshiba Satellite L500                      | 1         | 0.49%   |
| Toshiba Satellite C640                      | 1         | 0.49%   |
| Toshiba PORTEGE Z10t-A                      | 1         | 0.49%   |
| Toshiba PORTEGE R930                        | 1         | 0.49%   |
| Sony VPCEJ1E1E                              | 1         | 0.49%   |
| Shuttle NC10U                               | 1         | 0.49%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 1         | 0.49%   |
| Samsung Galaxy Book 12                      | 1         | 0.49%   |
| Samsung 530U3C/530U4C/532U3C                | 1         | 0.49%   |
| Protectli FW2B                              | 1         | 0.49%   |
| Pegatron SAISHIAT2                          | 1         | 0.49%   |
| Pegatron IPM41-D3                           | 1         | 0.49%   |
| PCPartner DREAMSYS                          | 1         | 0.49%   |
| Packard Bell EasyNote MH36                  | 1         | 0.49%   |
| NEC Computers PC-VK17HBBCD                  | 1         | 0.49%   |
| MSI WC791AA-UUW HPE-119sc                   | 1         | 0.49%   |
| MSI MS-7C37                                 | 1         | 0.49%   |
| MSI MS-7B86                                 | 1         | 0.49%   |
| MSI MS-7B84                                 | 1         | 0.49%   |
| MSI MS-7A15                                 | 1         | 0.49%   |
| MSI MS-7982                                 | 1         | 0.49%   |
| MSI GF65 Thin 10SDR                         | 1         | 0.49%   |
| MouseComputer W331AU                        | 1         | 0.49%   |
| Microsoft Surface Go                        | 1         | 0.49%   |
| Medion H61H2-LM3                            | 1         | 0.49%   |
| LG 14Z980-G.BH51P1                          | 1         | 0.49%   |
| Lenovo ZIUS6                                | 1         | 0.49%   |
| Lenovo ThinkPad X260 20F5S82N00             | 1         | 0.49%   |
| Lenovo ThinkPad X250 20CLS4JH00             | 1         | 0.49%   |
| Lenovo ThinkPad X240 20AMS39F0K             | 1         | 0.49%   |
| Lenovo ThinkPad X230 2330A48                | 1         | 0.49%   |
| Lenovo ThinkPad X230 2325WWB                | 1         | 0.49%   |
| Lenovo ThinkPad X230 23255Y4                | 1         | 0.49%   |
| Lenovo ThinkPad X200 7458VP4                | 1         | 0.49%   |
| Lenovo ThinkPad T490 20RYS06R00             | 1         | 0.49%   |
| Lenovo ThinkPad T470p 20J6A012CD            | 1         | 0.49%   |
| Lenovo ThinkPad T440s 20ARS1B704            | 1         | 0.49%   |
| Lenovo ThinkPad T420 4236FJ1                | 1         | 0.49%   |
| Lenovo ThinkPad L450 20DTCTO1WW             | 1         | 0.49%   |
| Lenovo ThinkPad Edge E530 62724FU           | 1         | 0.49%   |
| Lenovo ThinkPad E420 1141A83                | 1         | 0.49%   |
| Lenovo ThinkCentre M91p 7033DE6             | 1         | 0.49%   |
| Lenovo ThinkCentre M91p 7033D54             | 1         | 0.49%   |
| Lenovo ThinkCentre M83 10AHS35Q00           | 1         | 0.49%   |
| Lenovo Legion Y530-15ICH 81FV               | 1         | 0.49%   |
| Lenovo IdeaPad S145-15IWL 81S9              | 1         | 0.49%   |
| Lenovo IdeaPad 110S-11IBR 80WG              | 1         | 0.49%   |
| Lenovo IdeaCentre AIO 700-22ISH F0BF000WGE  | 1         | 0.49%   |
| Lenovo G550 2958                            | 1         | 0.49%   |
| Lenovo G500 20236                           | 1         | 0.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 14        | 6.83%   |
| Dell Latitude              | 8         | 3.9%    |
| Dell Inspiron              | 7         | 3.41%   |
| HP Pavilion                | 6         | 2.93%   |
| Dell OptiPlex              | 5         | 2.44%   |
| ASUS PRIME                 | 5         | 2.44%   |
| Toshiba Satellite          | 4         | 1.95%   |
| Dell Precision             | 4         | 1.95%   |
| Acer Aspire                | 4         | 1.95%   |
| Lenovo ThinkCentre         | 3         | 1.46%   |
| Toshiba PORTEGE            | 2         | 0.98%   |
| Lenovo IdeaPad             | 2         | 0.98%   |
| HP ProBook                 | 2         | 0.98%   |
| HP EliteBook               | 2         | 0.98%   |
| HP Compaq                  | 2         | 0.98%   |
| Gateway NE56R              | 2         | 0.98%   |
| Dell Vostro                | 2         | 0.98%   |
| ASUS VivoBook              | 2         | 0.98%   |
| ASUS ROG                   | 2         | 0.98%   |
| ASUS P8Z77-V               | 2         | 0.98%   |
| ASUS M5A78L-M              | 2         | 0.98%   |
| ASUS All                   | 2         | 0.98%   |
| ASRock B450M               | 2         | 0.98%   |
| Apple MacBookPro9          | 2         | 0.98%   |
| WYSE Z                     | 1         | 0.49%   |
| TUXEDO Aura                | 1         | 0.49%   |
| Sony VPCEJ1E1E             | 1         | 0.49%   |
| Shuttle NC10U              | 1         | 0.49%   |
| Samsung RV411              | 1         | 0.49%   |
| Samsung Galaxy             | 1         | 0.49%   |
| Samsung 530U3C             | 1         | 0.49%   |
| Protectli FW2B             | 1         | 0.49%   |
| Pegatron SAISHIAT2         | 1         | 0.49%   |
| Pegatron IPM41-D3          | 1         | 0.49%   |
| PCPartner DREAMSYS         | 1         | 0.49%   |
| Packard Bell EasyNote      | 1         | 0.49%   |
| NEC Computers PC-VK17HBBCD | 1         | 0.49%   |
| MSI WC791AA-UUW            | 1         | 0.49%   |
| MSI MS-7C37                | 1         | 0.49%   |
| MSI MS-7B86                | 1         | 0.49%   |
| MSI MS-7B84                | 1         | 0.49%   |
| MSI MS-7A15                | 1         | 0.49%   |
| MSI MS-7982                | 1         | 0.49%   |
| MSI GF65                   | 1         | 0.49%   |
| MouseComputer W331AU       | 1         | 0.49%   |
| Microsoft Surface          | 1         | 0.49%   |
| Medion H61H2-LM3           | 1         | 0.49%   |
| LG 14Z980-G.BH51P1         | 1         | 0.49%   |
| Lenovo ZIUS6               | 1         | 0.49%   |
| Lenovo Legion              | 1         | 0.49%   |
| Lenovo IdeaCentre          | 1         | 0.49%   |
| Lenovo G550                | 1         | 0.49%   |
| Lenovo G500                | 1         | 0.49%   |
| Lenovo G470                | 1         | 0.49%   |
| Lenovo B41-80              | 1         | 0.49%   |
| Lenovo 70F8S01J00          | 1         | 0.49%   |
| Intel X79                  | 1         | 0.49%   |
| Intel NUC7i7BNHXG          | 1         | 0.49%   |
| Intel NUC5i3RYH            | 1         | 0.49%   |
| Intel DN2820FYK            | 1         | 0.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 35        | 17.07%  |
| 2019 | 30        | 14.63%  |
| 2013 | 23        | 11.22%  |
| 2018 | 18        | 8.78%   |
| 2012 | 18        | 8.78%   |
| 2021 | 12        | 5.85%   |
| 2011 | 12        | 5.85%   |
| 2015 | 11        | 5.37%   |
| 2014 | 11        | 5.37%   |
| 2010 | 11        | 5.37%   |
| 2009 | 8         | 3.9%    |
| 2017 | 6         | 2.93%   |
| 2016 | 6         | 2.93%   |
| 2008 | 4         | 1.95%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 98        | 47.8%   |
| Notebook    | 95        | 46.34%  |
| All in one  | 4         | 1.95%   |
| Mini pc     | 3         | 1.46%   |
| Tablet      | 2         | 0.98%   |
| Server      | 2         | 0.98%   |
| Convertible | 1         | 0.49%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 204       | 99.51%  |
| Yes  | 1         | 0.49%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 76        | 37.07%  |
| 8.01-16.0   | 70        | 34.15%  |
| 16.01-24.0  | 45        | 21.95%  |
| 32.01-64.0  | 9         | 4.39%   |
| 24.01-32.0  | 3         | 1.46%   |
| 2.01-3.0    | 1         | 0.49%   |
| 64.01-256.0 | 1         | 0.49%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 128       | 62.14%  |
| 0.51-1.0  | 58        | 28.16%  |
| 1.01-2.0  | 15        | 7.28%   |
| 2.01-3.0  | 3         | 1.46%   |
| 4.01-8.0  | 1         | 0.49%   |
| 8.01-16.0 | 1         | 0.49%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 129       | 62.32%  |
| 2      | 42        | 20.29%  |
| 0      | 13        | 6.28%   |
| 3      | 12        | 5.8%    |
| 4      | 6         | 2.9%    |
| 6      | 3         | 1.45%   |
| 8      | 1         | 0.48%   |
| 5      | 1         | 0.48%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 115       | 56.1%   |
| Yes       | 90        | 43.9%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 188       | 91.71%  |
| No        | 17        | 8.29%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 136       | 66.02%  |
| No        | 70        | 33.98%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 110       | 53.66%  |
| Yes       | 95        | 46.34%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 36        | 17.48%  |
| Germany            | 16        | 7.77%   |
| Brazil             | 13        | 6.31%   |
| UK                 | 12        | 5.83%   |
| China              | 9         | 4.37%   |
| Canada             | 9         | 4.37%   |
| Russia             | 8         | 3.88%   |
| Spain              | 7         | 3.4%    |
| Netherlands        | 7         | 3.4%    |
| Italy              | 7         | 3.4%    |
| Australia          | 7         | 3.4%    |
| Ukraine            | 6         | 2.91%   |
| Sweden             | 5         | 2.43%   |
| Poland             | 4         | 1.94%   |
| Mexico             | 4         | 1.94%   |
| India              | 4         | 1.94%   |
| Taiwan             | 3         | 1.46%   |
| South Korea        | 3         | 1.46%   |
| Indonesia          | 3         | 1.46%   |
| France             | 3         | 1.46%   |
| Argentina          | 3         | 1.46%   |
| Slovakia           | 2         | 0.97%   |
| Portugal           | 2         | 0.97%   |
| Lithuania          | 2         | 0.97%   |
| Hungary            | 2         | 0.97%   |
| Greece             | 2         | 0.97%   |
| Finland            | 2         | 0.97%   |
| Belarus            | 2         | 0.97%   |
| Venezuela          | 1         | 0.49%   |
| Uruguay            | 1         | 0.49%   |
| Turkey             | 1         | 0.49%   |
| Switzerland        | 1         | 0.49%   |
| South Africa       | 1         | 0.49%   |
| Puerto Rico        | 1         | 0.49%   |
| Peru               | 1         | 0.49%   |
| Oman               | 1         | 0.49%   |
| Norway             | 1         | 0.49%   |
| New Zealand        | 1         | 0.49%   |
| Morocco            | 1         | 0.49%   |
| Malaysia           | 1         | 0.49%   |
| Latvia             | 1         | 0.49%   |
| Japan              | 1         | 0.49%   |
| Guatemala          | 1         | 0.49%   |
| Egypt              | 1         | 0.49%   |
| Dominican Republic | 1         | 0.49%   |
| Cyprus             | 1         | 0.49%   |
| Croatia            | 1         | 0.49%   |
| Chile              | 1         | 0.49%   |
| Bulgaria           | 1         | 0.49%   |
| Belgium            | 1         | 0.49%   |
| Austria            | 1         | 0.49%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Brisbane           | 3         | 1.44%   |
| São Paulo         | 2         | 0.96%   |
| New York           | 2         | 0.96%   |
| Mar del Plata      | 2         | 0.96%   |
| Jakarta            | 2         | 0.96%   |
| Dnipropetrovsk     | 2         | 0.96%   |
| Curitiba           | 2         | 0.96%   |
| Chicago            | 2         | 0.96%   |
| Calgary            | 2         | 0.96%   |
| Berlin             | 2         | 0.96%   |
| Athens             | 2         | 0.96%   |
| Aberdeen           | 2         | 0.96%   |
| Šiauliai          | 1         | 0.48%   |
| Zurich             | 1         | 0.48%   |
| Zhongshan          | 1         | 0.48%   |
| Zhengzhou          | 1         | 0.48%   |
| Zagreb             | 1         | 0.48%   |
| York               | 1         | 0.48%   |
| Yekaterinburg      | 1         | 0.48%   |
| Wuhan              | 1         | 0.48%   |
| Wroclaw            | 1         | 0.48%   |
| Winnipeg           | 1         | 0.48%   |
| Washington         | 1         | 0.48%   |
| Warmond            | 1         | 0.48%   |
| Wandur             | 1         | 0.48%   |
| Vladivostok        | 1         | 0.48%   |
| Vitória           | 1         | 0.48%   |
| Villeurbanne       | 1         | 0.48%   |
| Vigonovo           | 1         | 0.48%   |
| Vienna             | 1         | 0.48%   |
| V?�ster??s         | 1         | 0.48%   |
| Vawkavysk          | 1         | 0.48%   |
| Vancouver          | 1         | 0.48%   |
| Utrecht            | 1         | 0.48%   |
| Ufa                | 1         | 0.48%   |
| Tula de Allende    | 1         | 0.48%   |
| Treviso            | 1         | 0.48%   |
| Toronto            | 1         | 0.48%   |
| The Bronx          | 1         | 0.48%   |
| Tettnang Castle    | 1         | 0.48%   |
| Tangara            | 1         | 0.48%   |
| Tampere            | 1         | 0.48%   |
| Taichung           | 1         | 0.48%   |
| Taganrog           | 1         | 0.48%   |
| Sydney             | 1         | 0.48%   |
| Suzhou             | 1         | 0.48%   |
| Surabaya           | 1         | 0.48%   |
| Sungai Buloh       | 1         | 0.48%   |
| St Petersburg      | 1         | 0.48%   |
| Solarino           | 1         | 0.48%   |
| Sofia              | 1         | 0.48%   |
| Simpsonville       | 1         | 0.48%   |
| Shibakoen          | 1         | 0.48%   |
| Sherwood Park      | 1         | 0.48%   |
| Sheffield          | 1         | 0.48%   |
| Shasta             | 1         | 0.48%   |
| Sevastopol         | 1         | 0.48%   |
| Seoul              | 1         | 0.48%   |
| S??o Paulo         | 1         | 0.48%   |
| Santo Domingo Este | 1         | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 47        | 55     | 17.6%   |
| Seagate             | 44        | 62     | 16.48%  |
| Samsung Electronics | 42        | 57     | 15.73%  |
| Toshiba             | 19        | 19     | 7.12%   |
| SanDisk             | 13        | 14     | 4.87%   |
| Hitachi             | 13        | 15     | 4.87%   |
| Crucial             | 12        | 12     | 4.49%   |
| Kingston            | 11        | 12     | 4.12%   |
| Intel               | 9         | 9      | 3.37%   |
| A-DATA Technology   | 8         | 13     | 3%      |
| HGST                | 6         | 6      | 2.25%   |
| Apple               | 6         | 6      | 2.25%   |
| SPCC                | 4         | 5      | 1.5%    |
| PNY                 | 3         | 10     | 1.12%   |
| Hewlett-Packard     | 3         | 4      | 1.12%   |
| Fujitsu             | 3         | 4      | 1.12%   |
| Transcend           | 2         | 3      | 0.75%   |
| Silicon Motion      | 2         | 2      | 0.75%   |
| OCZ                 | 2         | 2      | 0.75%   |
| LITEON              | 2         | 2      | 0.75%   |
| KingSpec            | 2         | 2      | 0.75%   |
| Apacer              | 2         | 2      | 0.75%   |
| SMART               | 1         | 1      | 0.37%   |
| SK Hynix            | 1         | 1      | 0.37%   |
| Phison              | 1         | 1      | 0.37%   |
| Patriot             | 1         | 1      | 0.37%   |
| ORICO               | 1         | 2      | 0.37%   |
| MyDigitalSSD        | 1         | 1      | 0.37%   |
| Micron Technology   | 1         | 1      | 0.37%   |
| LSI                 | 1         | 1      | 0.37%   |
| LITEONIT            | 1         | 1      | 0.37%   |
| Lenovo              | 1         | 1      | 0.37%   |
| HPE                 | 1         | 1      | 0.37%   |
| CLOVER              | 1         | 1      | 0.37%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB           | 5         | 1.71%   |
| A-DATA SU650 120GB                  | 4         | 1.37%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 3         | 1.02%   |
| Seagate ST500DM002-1BD142 500GB     | 3         | 1.02%   |
| Seagate ST3250410AS 250GB           | 3         | 1.02%   |
| Seagate ST1000LM035-1RK172 1TB      | 3         | 1.02%   |
| Samsung SSD 860 EVO 250GB           | 3         | 1.02%   |
| Samsung SSD 860 EVO 1TB             | 3         | 1.02%   |
| WDC WD20EARS-00MVWB0 2TB            | 2         | 0.68%   |
| WDC WD10EZEX-08WN4A0 1TB            | 2         | 0.68%   |
| Seagate ST9500325AS 500GB           | 2         | 0.68%   |
| Seagate ST380815AS 80GB             | 2         | 0.68%   |
| Seagate ST3250318AS 250GB           | 2         | 0.68%   |
| Seagate ST31000528AS 1TB            | 2         | 0.68%   |
| Seagate ST1000DM003-1ER162 1TB      | 2         | 0.68%   |
| SanDisk SDSSDP128G 128GB            | 2         | 0.68%   |
| SanDisk SDSSDA240G 240GB            | 2         | 0.68%   |
| Samsung SSD 970 EVO Plus 250GB      | 2         | 0.68%   |
| Samsung SSD 860 EVO 500GB           | 2         | 0.68%   |
| Samsung SSD 840 EVO 250GB           | 2         | 0.68%   |
| Samsung HN-M101MBB 1TB              | 2         | 0.68%   |
| Kingston SA400S37240G 240GB         | 2         | 0.68%   |
| Intel SSDSC2KW256G8 256GB           | 2         | 0.68%   |
| Intel SSDPEKNW512G8 512GB           | 2         | 0.68%   |
| Hitachi HTS727550A9E364 500GB       | 2         | 0.68%   |
| HGST HTS725050A7E630 500GB          | 2         | 0.68%   |
| HGST HTS545032A7E380 320GB          | 2         | 0.68%   |
| Crucial CT1000MX500SSD1 1TB         | 2         | 0.68%   |
| Apple HDD HTS545050A7E362 500GB     | 2         | 0.68%   |
| A-DATA SX8200PNP 256GB              | 2         | 0.68%   |
| WDC WDS500G3X0C-00SJG0 500GB        | 1         | 0.34%   |
| WDC WDS500G2B0A-00SM50 500GB        | 1         | 0.34%   |
| WDC WDS250G3X0C-00SJG0 250GB        | 1         | 0.34%   |
| WDC WDS250G1B0A-00H9H0 250GB        | 1         | 0.34%   |
| WDC WDS240G2G0A-00JH30 240GB        | 1         | 0.34%   |
| WDC WDS100T2B0A-00SM50 1TB          | 1         | 0.34%   |
| WDC WDBNCE2500PNC 250GB             | 1         | 0.34%   |
| WDC WD800JD-55MUA1 80GB             | 1         | 0.34%   |
| WDC WD800BEVS-00RST0 80GB           | 1         | 0.34%   |
| WDC WD7500BPVX-60JC3T0 752GB        | 1         | 0.34%   |
| WDC WD7500BPKX-00HPJT0 752GB        | 1         | 0.34%   |
| WDC WD6400AAKS-22A7B0 640GB         | 1         | 0.34%   |
| WDC WD5002ABYS-02B1B0 500GB         | 1         | 0.34%   |
| WDC WD5000LPVX-60V0TT0 500GB        | 1         | 0.34%   |
| WDC WD5000LPVX-00V0TT0 500GB        | 1         | 0.34%   |
| WDC WD5000BEVT-22ZAT0 500GB         | 1         | 0.34%   |
| WDC WD5000AZRX-00L4HB0 500GB        | 1         | 0.34%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 1         | 0.34%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 1         | 0.34%   |
| WDC WD5000AAKS-00A7B2 500GB         | 1         | 0.34%   |
| WDC WD40EFRX-68WT0N0 4TB            | 1         | 0.34%   |
| WDC WD400BD-75LRA0 40GB             | 1         | 0.34%   |
| WDC WD4004FZWX-00GBGB0 4TB          | 1         | 0.34%   |
| WDC WD3200BEVT-60ZCT1 320GB         | 1         | 0.34%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 1         | 0.34%   |
| WDC WD3200BEVT-00A0RT0 233GB        | 1         | 0.34%   |
| WDC WD3200BEKT-75PVMT1 320GB        | 1         | 0.34%   |
| WDC WD3200BEKT-60PVMT0 320GB        | 1         | 0.34%   |
| WDC WD3200AAJS-00L7A0 320GB         | 1         | 0.34%   |
| WDC WD3003FZEX-00Z4SA0 3TB          | 1         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 44        | 62     | 32.84%  |
| WDC                 | 39        | 46     | 29.1%   |
| Hitachi             | 13        | 15     | 9.7%    |
| Toshiba             | 12        | 12     | 8.96%   |
| Samsung Electronics | 11        | 13     | 8.21%   |
| HGST                | 6         | 6      | 4.48%   |
| Fujitsu             | 3         | 4      | 2.24%   |
| Apple               | 3         | 3      | 2.24%   |
| LSI                 | 1         | 1      | 0.75%   |
| Hewlett-Packard     | 1         | 1      | 0.75%   |
| CLOVER              | 1         | 1      | 0.75%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 26        | 33     | 24.3%   |
| SanDisk             | 13        | 14     | 12.15%  |
| Kingston            | 10        | 10     | 9.35%   |
| Crucial             | 10        | 10     | 9.35%   |
| Intel               | 6         | 6      | 5.61%   |
| WDC                 | 5         | 5      | 4.67%   |
| A-DATA Technology   | 5         | 6      | 4.67%   |
| Toshiba             | 4         | 4      | 3.74%   |
| SPCC                | 4         | 5      | 3.74%   |
| PNY                 | 3         | 8      | 2.8%    |
| Transcend           | 2         | 3      | 1.87%   |
| OCZ                 | 2         | 2      | 1.87%   |
| LITEON              | 2         | 2      | 1.87%   |
| KingSpec            | 2         | 2      | 1.87%   |
| Apple               | 2         | 2      | 1.87%   |
| Apacer              | 2         | 2      | 1.87%   |
| SMART               | 1         | 1      | 0.93%   |
| Patriot             | 1         | 1      | 0.93%   |
| ORICO               | 1         | 2      | 0.93%   |
| MyDigitalSSD        | 1         | 1      | 0.93%   |
| Micron Technology   | 1         | 1      | 0.93%   |
| LITEONIT            | 1         | 1      | 0.93%   |
| Lenovo              | 1         | 1      | 0.93%   |
| HPE                 | 1         | 1      | 0.93%   |
| Hewlett-Packard     | 1         | 2      | 0.93%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 115       | 164    | 47.52%  |
| SSD  | 94        | 125    | 38.84%  |
| NVMe | 33        | 40     | 13.64%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 181       | 289    | 84.58%  |
| NVMe | 33        | 40     | 15.42%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 148       | 203    | 68.52%  |
| 0.51-1.0   | 48        | 58     | 22.22%  |
| 1.01-2.0   | 12        | 15     | 5.56%   |
| 3.01-4.0   | 4         | 5      | 1.85%   |
| 2.01-3.0   | 2         | 5      | 0.93%   |
| 4.01-10.0  | 2         | 3      | 0.93%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 132       | 63.46%  |
| 101-250    | 27        | 12.98%  |
| 251-500    | 21        | 10.1%   |
| 501-1000   | 16        | 7.69%   |
| 51-100     | 6         | 2.88%   |
| 21-50      | 4         | 1.92%   |
| 1001-2000  | 2         | 0.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 205       | 100%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Seagate ST3250410AS 250GB                | 3         | 3      | 5%      |
| Seagate ST380815AS 80GB                  | 2         | 2      | 3.33%   |
| HGST HTS545032A7E380 320GB               | 2         | 2      | 3.33%   |
| Apple HDD HTS545050A7E362 500GB          | 2         | 2      | 3.33%   |
| WDC WD800JD-55MUA1 80GB                  | 1         | 1      | 1.67%   |
| WDC WD6400AAKS-22A7B0 640GB              | 1         | 1      | 1.67%   |
| WDC WD5000LPVX-60V0TT0 500GB             | 1         | 1      | 1.67%   |
| WDC WD5000AAKX-60U6AA0 500GB             | 1         | 1      | 1.67%   |
| WDC WD5000AAKX-00ERMA0 500GB             | 1         | 1      | 1.67%   |
| WDC WD40EFRX-68WT0N0 4TB                 | 1         | 1      | 1.67%   |
| WDC WD3200BEVT-22ZCT0 320GB              | 1         | 1      | 1.67%   |
| WDC WD3200BEVT-00A0RT0 233GB             | 1         | 1      | 1.67%   |
| WDC WD3200AAJS-00L7A0 320GB              | 1         | 1      | 1.67%   |
| WDC WD2500AAKX-083CA1 250GB              | 1         | 1      | 1.67%   |
| WDC WD20EARS-00MVWB0 2TB                 | 1         | 1      | 1.67%   |
| WDC WD1600AAJS-00WAA0 160GB              | 1         | 1      | 1.67%   |
| WDC WD10EARS-00Y5B1 1TB                  | 1         | 1      | 1.67%   |
| Toshiba THNSNK128GCS8 SATA 128GB         | 1         | 1      | 1.67%   |
| Toshiba MQ01ABD075 752GB                 | 1         | 1      | 1.67%   |
| Toshiba MQ01ABD032 320GB                 | 1         | 1      | 1.67%   |
| Toshiba MK3276GSX 320GB                  | 1         | 1      | 1.67%   |
| Toshiba MK3265GSXN 320GB                 | 1         | 1      | 1.67%   |
| Toshiba MK3261GSYN 320GB                 | 1         | 1      | 1.67%   |
| Seagate ST9500325AS 500GB                | 1         | 1      | 1.67%   |
| Seagate ST9320423AS 320GB                | 1         | 1      | 1.67%   |
| Seagate ST9160412AS 160GB                | 1         | 1      | 1.67%   |
| Seagate ST500LM012 HN-M500MBB 500GB      | 1         | 1      | 1.67%   |
| Seagate ST3500413AS 500GB                | 1         | 1      | 1.67%   |
| Seagate ST3250318AS 250GB                | 1         | 1      | 1.67%   |
| Seagate ST320LT012-9WS14C 320GB          | 1         | 2      | 1.67%   |
| Seagate ST31000528AS 1TB                 | 1         | 1      | 1.67%   |
| Seagate ST31000333AS 1TB                 | 1         | 1      | 1.67%   |
| Seagate ST1000LM049-2GH172 1TB           | 1         | 1      | 1.67%   |
| Seagate ST1000LM035-1RK172 1TB           | 1         | 1      | 1.67%   |
| Samsung Electronics SSD 840 Series 500GB | 1         | 1      | 1.67%   |
| Samsung Electronics SP2004C 200GB        | 1         | 1      | 1.67%   |
| Samsung Electronics HD642JJ 640GB        | 1         | 1      | 1.67%   |
| Samsung Electronics HD321KJ 320GB        | 1         | 1      | 1.67%   |
| Samsung Electronics HD161HJ 160GB        | 1         | 1      | 1.67%   |
| Kingston RBU-SNS8350DES3128GP 128GB      | 1         | 1      | 1.67%   |
| Hitachi HTS727550A9E364 500GB            | 1         | 1      | 1.67%   |
| Hitachi HTS723232A7A364 320GB            | 1         | 1      | 1.67%   |
| Hitachi HTS545050B9A300 500GB            | 1         | 1      | 1.67%   |
| Hitachi HTS545050A7E380 500GB            | 1         | 1      | 1.67%   |
| Hitachi HTS545032B9A300 320GB            | 1         | 1      | 1.67%   |
| Hitachi HTS545025B9SA02 250GB            | 1         | 1      | 1.67%   |
| Hitachi HDS721050CLA362 500GB            | 1         | 1      | 1.67%   |
| Hitachi HDP725025GLA380 250GB            | 1         | 1      | 1.67%   |
| HGST HTS725050A7E630 500GB               | 1         | 1      | 1.67%   |
| HGST HTS721010A9E630 1TB                 | 1         | 1      | 1.67%   |
| Hewlett-Packard SSD S700 1TB             | 1         | 1      | 1.67%   |
| Fujitsu MHZ2250BH G1 250GB               | 1         | 1      | 1.67%   |
| Fujitsu MHW2160BH 160GB                  | 1         | 1      | 1.67%   |
| Crucial CT525MX300SSD1 528GB             | 1         | 1      | 1.67%   |
| Apple HDD HTS541010A9E662 1TB            | 1         | 1      | 1.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 17     | 25.42%  |
| WDC                 | 13        | 13     | 22.03%  |
| Hitachi             | 8         | 8      | 13.56%  |
| Toshiba             | 6         | 6      | 10.17%  |
| Samsung Electronics | 5         | 5      | 8.47%   |
| HGST                | 4         | 4      | 6.78%   |
| Apple               | 3         | 3      | 5.08%   |
| Fujitsu             | 2         | 2      | 3.39%   |
| Kingston            | 1         | 1      | 1.69%   |
| Hewlett-Packard     | 1         | 1      | 1.69%   |
| Crucial             | 1         | 1      | 1.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 17     | 27.78%  |
| WDC                 | 13        | 13     | 24.07%  |
| Hitachi             | 8         | 8      | 14.81%  |
| Toshiba             | 5         | 5      | 9.26%   |
| Samsung Electronics | 4         | 4      | 7.41%   |
| HGST                | 4         | 4      | 7.41%   |
| Apple               | 3         | 3      | 5.56%   |
| Fujitsu             | 2         | 2      | 3.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 50        | 56     | 90.91%  |
| SSD  | 5         | 5      | 9.09%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart_bsd/drive_failed.svg)


| Model                      | Computers | Drives | Percent |
|----------------------------|-----------|--------|---------|
| HPE MK000480GWUGF 480GB    | 1         | 1      | 50%     |
| HGST HTS725050A7E630 500GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| HPE    | 1         | 1      | 50%     |
| HGST   | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 156       | 255    | 71.23%  |
| Malfunc  | 55        | 61     | 25.11%  |
| Detected | 6         | 11     | 2.74%   |
| Failed   | 2         | 2      | 0.91%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 167       | 67.07%  |
| AMD                         | 31        | 12.45%  |
| Samsung Electronics         | 12        | 4.82%   |
| Sandisk                     | 4         | 1.61%   |
| Broadcom / LSI              | 4         | 1.61%   |
| ASMedia Technology          | 4         | 1.61%   |
| Silicon Motion              | 3         | 1.2%    |
| VIA Technologies            | 2         | 0.8%    |
| Toshiba                     | 2         | 0.8%    |
| Phison Electronics          | 2         | 0.8%    |
| Nvidia                      | 2         | 0.8%    |
| Micron/Crucial Technology   | 2         | 0.8%    |
| Kingston Technology Company | 2         | 0.8%    |
| JMicron Technology          | 2         | 0.8%    |
| ADATA Technology            | 2         | 0.8%    |
| Adaptec                     | 2         | 0.8%    |
| SK Hynix                    | 1         | 0.4%    |
| Silicon Image               | 1         | 0.4%    |
| Realtek Semiconductor       | 1         | 0.4%    |
| Marvell Technology Group    | 1         | 0.4%    |
| KIOXIA                      | 1         | 0.4%    |
| Hewlett-Packard             | 1         | 0.4%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 20        | 6.92%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 17        | 5.88%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 13        | 4.5%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 11        | 3.81%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 10        | 3.46%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 9         | 3.11%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 7         | 2.42%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 7         | 2.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 7         | 2.42%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 7         | 2.42%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 6         | 2.08%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 6         | 2.08%   |
| AMD 400 Series Chipset SATA Controller                                                  | 6         | 2.08%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 5         | 1.73%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5         | 1.73%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5         | 1.73%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5         | 1.73%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 5         | 1.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 4         | 1.38%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4         | 1.38%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3         | 1.04%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3         | 1.04%   |
| Intel SSD 660P Series                                                                   | 3         | 1.04%   |
| Intel SATA Controller [RAID mode]                                                       | 3         | 1.04%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3         | 1.04%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 3         | 1.04%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 3         | 1.04%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 3         | 1.04%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3         | 1.04%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3         | 1.04%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 3         | 1.04%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 3         | 1.04%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 3         | 1.04%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3         | 1.04%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 2         | 0.69%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 2         | 0.69%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2         | 0.69%   |
| Nvidia MCP61 SATA Controller                                                            | 2         | 0.69%   |
| Nvidia MCP61 IDE                                                                        | 2         | 0.69%   |
| Kingston Company A2000 NVMe SSD                                                         | 2         | 0.69%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2         | 0.69%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 2         | 0.69%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 2         | 0.69%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 2         | 0.69%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 2         | 0.69%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2         | 0.69%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 2         | 0.69%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 2         | 0.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 0.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 0.69%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2         | 0.69%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 2         | 0.69%   |
| AMD FCH SATA Controller D                                                               | 2         | 0.69%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 2         | 0.69%   |
| Adaptec AIC-7850T/7856T [AVA-2902/4/6 / AHA-2910]                                       | 2         | 0.69%   |
| Unknown                                                                                 | 2         | 0.69%   |
| Toshiba unknown                                                                         | 1         | 0.35%   |
| Toshiba BG3 NVMe SSD Controller                                                         | 1         | 0.35%   |
| SK Hynix NVMe SSD Controller                                                            | 1         | 0.35%   |
| Silicon Image SiI 3512 [SATALink/SATARaid] Serial ATA Controller                        | 1         | 0.35%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 164       | 64.57%  |
| IDE  | 35        | 13.78%  |
| NVMe | 33        | 12.99%  |
| RAID | 17        | 6.69%   |
| SCSI | 3         | 1.18%   |
| SAS  | 2         | 0.79%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 171       | 83.41%  |
| AMD    | 34        | 16.59%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Xeon                                  | 5         | 2.44%   |
| Intel CPU Version                           | 5         | 2.44%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 4         | 1.95%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 4         | 1.95%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 3         | 1.46%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 3         | 1.46%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3         | 1.46%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 3         | 1.46%   |
| Intel Core i7-4510U CPU @ 2.00GHz           | 2         | 0.98%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 2         | 0.98%   |
| Intel Core i7 CPU M 620 @ 2.67GHz           | 2         | 0.98%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 0.98%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 2         | 0.98%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 0.98%   |
| Intel Core i5-3340M CPU @ 2.70GHz           | 2         | 0.98%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 0.98%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 0.98%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 2         | 0.98%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 2         | 0.98%   |
| Intel Core i3-2370M CPU @ 2.40GHz           | 2         | 0.98%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 2         | 0.98%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 2         | 0.98%   |
| Intel Core 2 Duo                            | 2         | 0.98%   |
| Intel Celeron CPU N3450 @ 1.10GHz           | 2         | 0.98%   |
| Intel Celeron CPU G3930 @ 2.90GHz           | 2         | 0.98%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 2         | 0.98%   |
| Intel Xeon CPU X3470                        | 1         | 0.49%   |
| Intel Xeon CPU W3550 @ 3.07GHz              | 1         | 0.49%   |
| Intel Xeon CPU E5530 @ 2.40GHz              | 1         | 0.49%   |
| Intel Xeon CPU E5-2630L 0 @ 2.00GHz         | 1         | 0.49%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz         | 1         | 0.49%   |
| Intel Xeon CPU E5-1603 @ 2.80GHz            | 1         | 0.49%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz         | 1         | 0.49%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz         | 1         | 0.49%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 1         | 0.49%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1         | 0.49%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 1         | 0.49%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1         | 0.49%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 1         | 0.49%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 1         | 0.49%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1         | 0.49%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1         | 0.49%   |
| Intel Pentium CPU G3460 @ 3.50GHz           | 1         | 0.49%   |
| Intel Pentium CPU G3420 @ 3.20GHz           | 1         | 0.49%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1         | 0.49%   |
| Intel Pentium CPU B940 @ 2.00GHz            | 1         | 0.49%   |
| Intel Pentium CPU 4415Y @ 1.60GHz           | 1         | 0.49%   |
| Intel Pentium 4 CPU 3.60GHz                 | 1         | 0.49%   |
| Intel Genuine CPU 0000 @ 2.10GHz            | 1         | 0.49%   |
| Intel Genuine CPU                           | 1         | 0.49%   |
| Intel Core i9-7920X CPU @ 2.90GHz           | 1         | 0.49%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 1         | 0.49%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1         | 0.49%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1         | 0.49%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 0.49%   |
| Intel Core i7-7567U CPU @ 3.50GHz           | 1         | 0.49%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.49%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 1         | 0.49%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 0.49%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 55        | 26.83%  |
| Intel Core i3           | 31        | 15.12%  |
| Intel Core i7           | 26        | 12.68%  |
| Intel Celeron           | 15        | 7.32%   |
| Intel Xeon              | 13        | 6.34%   |
| Intel Pentium           | 8         | 3.9%    |
| Intel Core 2 Duo        | 8         | 3.9%    |
| AMD Ryzen 5             | 6         | 2.93%   |
| Other                   | 5         | 2.44%   |
| AMD FX                  | 5         | 2.44%   |
| Intel Pentium Dual-Core | 4         | 1.95%   |
| AMD Ryzen 3             | 4         | 1.95%   |
| AMD Ryzen 7             | 3         | 1.46%   |
| Intel Genuine           | 2         | 0.98%   |
| AMD Ryzen 9             | 2         | 0.98%   |
| AMD Phenom II X4        | 2         | 0.98%   |
| AMD Athlon II X4        | 2         | 0.98%   |
| AMD A6                  | 2         | 0.98%   |
| AMD A10                 | 2         | 0.98%   |
| Intel Pentium Gold      | 1         | 0.49%   |
| Intel Pentium 4         | 1         | 0.49%   |
| Intel Core i9           | 1         | 0.49%   |
| Intel Core 2 Solo       | 1         | 0.49%   |
| AMD Phenom II X6        | 1         | 0.49%   |
| AMD G                   | 1         | 0.49%   |
| AMD E1                  | 1         | 0.49%   |
| AMD Athlon II X2        | 1         | 0.49%   |
| AMD Athlon II           | 1         | 0.49%   |
| AMD Athlon              | 1         | 0.49%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 104       | 50.73%  |
| 4       | 61        | 29.76%  |
| 6       | 15        | 7.32%   |
| 8       | 11        | 5.37%   |
| Unknown | 6         | 2.93%   |
| 12      | 3         | 1.46%   |
| 24      | 2         | 0.98%   |
| 16      | 2         | 0.98%   |
| 1       | 1         | 0.49%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 200       | 97.56%  |
| 2      | 5         | 2.44%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 103       | 50.24%  |
| 1       | 95        | 46.34%  |
| Unknown | 7         | 3.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 30        | 14.63%  |
| IvyBridge     | 25        | 12.2%   |
| SandyBridge   | 24        | 11.71%  |
| Haswell       | 20        | 9.76%   |
| Penryn        | 17        | 8.29%   |
| Skylake       | 16        | 7.8%    |
| Westmere      | 9         | 4.39%   |
| Broadwell     | 8         | 3.9%    |
| Zen 2         | 6         | 2.93%   |
| Piledriver    | 6         | 2.93%   |
| K10           | 6         | 2.93%   |
| Zen+          | 5         | 2.44%   |
| Zen           | 5         | 2.44%   |
| Silvermont    | 5         | 2.44%   |
| CometLake     | 5         | 2.44%   |
| Nehalem       | 4         | 1.95%   |
| Core          | 4         | 1.95%   |
| Jaguar        | 2         | 0.98%   |
| Goldmont      | 2         | 0.98%   |
| Bulldozer     | 2         | 0.98%   |
| NetBurst      | 1         | 0.49%   |
| K10 Llano     | 1         | 0.49%   |
| Goldmont plus | 1         | 0.49%   |
| Bobcat        | 1         | 0.49%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 116       | 50.88%  |
| Nvidia                     | 70        | 30.7%   |
| AMD                        | 41        | 17.98%  |
| Matrox Electronics Systems | 1         | 0.44%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 16        | 7.02%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 15        | 6.58%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 10        | 4.39%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 3.51%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 3.07%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 6         | 2.63%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 6         | 2.63%   |
| Intel HD Graphics 5500                                                                   | 5         | 2.19%   |
| Intel HD Graphics 530                                                                    | 5         | 2.19%   |
| AMD Picasso                                                                              | 5         | 2.19%   |
| Nvidia GT218 [GeForce 210]                                                               | 4         | 1.75%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 1.75%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 1.75%   |
| Intel HD Graphics 620                                                                    | 4         | 1.75%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.75%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 1.75%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 1.32%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 3         | 1.32%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3         | 1.32%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.32%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 2         | 0.88%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 0.88%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 2         | 0.88%   |
| Nvidia GM206 [GeForce GTX 950]                                                           | 2         | 0.88%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 2         | 0.88%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.88%   |
| Nvidia G92 [GeForce GTS 250]                                                             | 2         | 0.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 0.88%   |
| Intel HD Graphics 630                                                                    | 2         | 0.88%   |
| Intel HD Graphics 500                                                                    | 2         | 0.88%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 2         | 0.88%   |
| AMD RS780L [Radeon 3000]                                                                 | 2         | 0.88%   |
| AMD Chelsea LP [Radeon HD 7730M]                                                         | 2         | 0.88%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.44%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 1         | 0.44%   |
| Nvidia TU116 [GeForce GTX 1650]                                                          | 1         | 0.44%   |
| Nvidia NV43 [GeForce 6600]                                                               | 1         | 0.44%   |
| Nvidia GT216M [NVS 5100M]                                                                | 1         | 0.44%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.44%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 0.44%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1         | 0.44%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.44%   |
| Nvidia GM108M [GeForce 930M]                                                             | 1         | 0.44%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.44%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.44%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1         | 0.44%   |
| Nvidia GK208 [GeForce GT 630 Rev. 2]                                                     | 1         | 0.44%   |
| Nvidia GK107M [GeForce GTX 660M]                                                         | 1         | 0.44%   |
| Nvidia GK107 [GeForce GT 740]                                                            | 1         | 0.44%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 1         | 0.44%   |
| Nvidia GK106M [GeForce GTX 770M]                                                         | 1         | 0.44%   |
| Nvidia GK106GL [Quadro K4000]                                                            | 1         | 0.44%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1         | 0.44%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 1         | 0.44%   |
| Nvidia GF119M [GeForce 610M]                                                             | 1         | 0.44%   |
| Nvidia GF119M [GeForce 410M]                                                             | 1         | 0.44%   |
| Nvidia GF119 [NVS 315]                                                                   | 1         | 0.44%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 1         | 0.44%   |
| Nvidia GF108 [GeForce GT 530]                                                            | 1         | 0.44%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 86        | 41.75%  |
| 1 x Nvidia     | 55        | 26.7%   |
| 1 x AMD        | 32        | 15.53%  |
| Intel + Nvidia | 13        | 6.31%   |
| 2 x Intel      | 9         | 4.37%   |
| Intel + AMD    | 8         | 3.88%   |
| AMD + Nvidia   | 2         | 0.97%   |
| 1 x Matrox     | 1         | 0.49%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 148       | 72.2%   |
| Proprietary | 32        | 15.61%  |
| Unknown     | 25        | 12.2%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 148       | 72.2%   |
| 1.01-2.0   | 21        | 10.24%  |
| 0.51-1.0   | 11        | 5.37%   |
| 0.01-0.5   | 10        | 4.88%   |
| 3.01-4.0   | 8         | 3.9%    |
| 7.01-8.0   | 3         | 1.46%   |
| 5.01-6.0   | 2         | 0.98%   |
| 2.01-3.0   | 2         | 0.98%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 29        | 18.35%  |
| LG Display              | 23        | 14.56%  |
| AU Optronics            | 13        | 8.23%   |
| Chimei Innolux          | 12        | 7.59%   |
| Goldstar                | 11        | 6.96%   |
| Dell                    | 9         | 5.7%    |
| Hewlett-Packard         | 6         | 3.8%    |
| BOE                     | 5         | 3.16%   |
| AOC                     | 5         | 3.16%   |
| Chi Mei Optoelectronics | 4         | 2.53%   |
| Acer                    | 4         | 2.53%   |
| ViewSonic               | 3         | 1.9%    |
| Lenovo                  | 3         | 1.9%    |
| InfoVision              | 3         | 1.9%    |
| Iiyama                  | 3         | 1.9%    |
| BenQ                    | 3         | 1.9%    |
| Ancor Communications    | 3         | 1.9%    |
| Sony                    | 2         | 1.27%   |
| Apple                   | 2         | 1.27%   |
| Vizio                   | 1         | 0.63%   |
| Toshiba                 | 1         | 0.63%   |
| Sun                     | 1         | 0.63%   |
| Sharp                   | 1         | 0.63%   |
| RS                      | 1         | 0.63%   |
| Philips                 | 1         | 0.63%   |
| NEC Computers           | 1         | 0.63%   |
| Medion                  | 1         | 0.63%   |
| LG Philips              | 1         | 0.63%   |
| LED                     | 1         | 0.63%   |
| Insignia                | 1         | 0.63%   |
| Gateway                 | 1         | 0.63%   |
| Fujitsu Siemens         | 1         | 0.63%   |
| CVT                     | 1         | 0.63%   |
| CAN                     | 1         | 0.63%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch          | 3         | 1.9%    |
| LG Display LCD Monitor LGD0532 1920x1080 340x190mm 15.3-inch           | 2         | 1.27%   |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch            | 2         | 1.27%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch              | 2         | 1.27%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 310x170mm 13.9-inch       | 2         | 1.27%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 340x190mm 15.3-inch          | 2         | 1.27%   |
| Vizio D32f-F1 VIZ1027 1920x1080 700x390mm 31.5-inch                    | 1         | 0.63%   |
| ViewSonic VX1940w VSC6A20 1680x1050 410x260mm 19.1-inch                | 1         | 0.63%   |
| ViewSonic LCD Monitor VSCD824 1920x1080 520x290mm 23.4-inch            | 1         | 0.63%   |
| ViewSonic LCD Monitor VSC8724 1440x900 410x260mm 19.1-inch             | 1         | 0.63%   |
| Toshiba TV TSB0108 1360x768 480x270mm 21.7-inch                        | 1         | 0.63%   |
| Sun X7202A SUN0595 1280x1024 380x300mm 19.1-inch                       | 1         | 0.63%   |
| Sony TV SNYC901 1920x1080                                              | 1         | 0.63%   |
| Sony SDM-HS95P SNY2500 1280x1024 380x300mm 19.1-inch                   | 1         | 0.63%   |
| Sharp LQ100P1JX51 SHP14A6 1800x1200 210x140mm 9.9-inch                 | 1         | 0.63%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 700x390mm 31.5-inch      | 1         | 0.63%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 610x350mm 27.7-inch      | 1         | 0.63%   |
| Samsung Electronics T24D390 SAM0B6E 1920x1080 520x290mm 23.4-inch      | 1         | 0.63%   |
| Samsung Electronics T22C300 SAM0AB3 1920x1080 480x270mm 21.7-inch      | 1         | 0.63%   |
| Samsung Electronics SyncMaster SAM0600 1600x900 440x250mm 19.9-inch    | 1         | 0.63%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 470x300mm 22.0-inch   | 1         | 0.63%   |
| Samsung Electronics SyncMaster SAM03E0 1440x900 410x260mm 19.1-inch    | 1         | 0.63%   |
| Samsung Electronics SyncMaster SAM03D7 1680x1050 470x300mm 22.0-inch   | 1         | 0.63%   |
| Samsung Electronics SyncMaster SAM0320 1680x1050 470x300mm 22.0-inch   | 1         | 0.63%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 490x320mm 23.0-inch   | 1         | 0.63%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 430x270mm 20.0-inch   | 1         | 0.63%   |
| Samsung Electronics SE790C SAM0C62 2560x1080 700x310mm 30.1-inch       | 1         | 0.63%   |
| Samsung Electronics S27D590 SAM0B49 1920x1080 600x340mm 27.2-inch      | 1         | 0.63%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 530x300mm 24.0-inch      | 1         | 0.63%   |
| Samsung Electronics S24C350 SAM0A3A 1920x1080 530x300mm 24.0-inch      | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 330x210mm 15.4-inch   | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC354C 1366x768 350x200mm 15.9-inch   | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch   | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 340x190mm 15.3-inch   | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SDC4253 1366x768 260x150mm 11.8-inch   | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SDC324D 1366x768 310x170mm 13.9-inch   | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SDC324A 1366x768 290x170mm 13.2-inch   | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SAM4A75 1024x768 300x230mm 14.9-inch   | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SAM0F9F 3840x2160 1420x800mm 64.2-inch | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SAM0D3B 3840x2160 890x500mm 40.2-inch  | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SAM0AC6 1920x1080 700x390mm 31.5-inch  | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 480x270mm 21.7-inch  | 1         | 0.63%   |
| Samsung Electronics LC24RG50 SAM0F91 1920x1080 530x300mm 24.0-inch     | 1         | 0.63%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 520x290mm 23.4-inch      | 1         | 0.63%   |
| RS LE2262 BTC2262 1680x1050 470x290mm 21.7-inch                        | 1         | 0.63%   |
| Philips LCD Monitor PHLC0B1 1920x1080 480x270mm 21.7-inch              | 1         | 0.63%   |
| NEC Computers EA244UHD NEC2B1D 3840x2160 530x300mm 24.0-inch           | 1         | 0.63%   |
| Medion MD21281 MED3947 1366x768 410x230mm 18.5-inch                    | 1         | 0.63%   |
| LG Philips LCD Monitor LPL3B01 1280x800 330x210mm 15.4-inch            | 1         | 0.63%   |
| LG Display LCD Monitor LGD11F9 1280x800 290x180mm 13.4-inch            | 1         | 0.63%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch           | 1         | 0.63%   |
| LG Display LCD Monitor LGD05B1 1920x1080 310x170mm 13.9-inch           | 1         | 0.63%   |
| LG Display LCD Monitor LGD0545 3200x1800 290x170mm 13.2-inch           | 1         | 0.63%   |
| LG Display LCD Monitor LGD053F 1920x1080 340x190mm 15.3-inch           | 1         | 0.63%   |
| LG Display LCD Monitor LGD0527 1366x768 310x170mm 13.9-inch            | 1         | 0.63%   |
| LG Display LCD Monitor LGD0525 1366x768 340x190mm 15.3-inch            | 1         | 0.63%   |
| LG Display LCD Monitor LGD045C 1366x768 350x190mm 15.7-inch            | 1         | 0.63%   |
| LG Display LCD Monitor LGD0459 1920x1080 380x210mm 17.1-inch           | 1         | 0.63%   |
| LG Display LCD Monitor LGD0446 1920x1080 310x170mm 13.9-inch           | 1         | 0.63%   |
| LG Display LCD Monitor LGD03A3 1366x768 280x160mm 12.7-inch            | 1         | 0.63%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 52        | 33.33%  |
| 1366x768 (WXGA)    | 45        | 28.85%  |
| 1680x1050 (WSXGA+) | 11        | 7.05%   |
| 3840x2160 (4K)     | 10        | 6.41%   |
| 1280x1024 (SXGA)   | 7         | 4.49%   |
| 1440x900 (WXGA+)   | 6         | 3.85%   |
| 2560x1440 (QHD)    | 5         | 3.21%   |
| 1600x900 (HD+)     | 5         | 3.21%   |
| 1280x800 (WXGA)    | 5         | 3.21%   |
| 2560x1080          | 3         | 1.92%   |
| 3440x1440          | 2         | 1.28%   |
| 3200x1800 (QHD+)   | 1         | 0.64%   |
| 2048x1152          | 1         | 0.64%   |
| 1800x1200          | 1         | 0.64%   |
| 1360x768           | 1         | 0.64%   |
| 1024x768 (XGA)     | 1         | 0.64%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 30        | 19.11%  |
| 13      | 25        | 15.92%  |
| 19      | 14        | 8.92%   |
| 21      | 13        | 8.28%   |
| 24      | 9         | 5.73%   |
| 23      | 9         | 5.73%   |
| 27      | 8         | 5.1%    |
| 31      | 7         | 4.46%   |
| 12      | 7         | 4.46%   |
| 18      | 6         | 3.82%   |
| 17      | 6         | 3.82%   |
| 22      | 4         | 2.55%   |
| 11      | 4         | 2.55%   |
| 20      | 3         | 1.91%   |
| 34      | 2         | 1.27%   |
| 64      | 1         | 0.64%   |
| 54      | 1         | 0.64%   |
| 40      | 1         | 0.64%   |
| 39      | 1         | 0.64%   |
| 30      | 1         | 0.64%   |
| 28      | 1         | 0.64%   |
| 16      | 1         | 0.64%   |
| 14      | 1         | 0.64%   |
| 9       | 1         | 0.64%   |
| Unknown | 1         | 0.64%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 49        | 31.21%  |
| 401-500     | 36        | 22.93%  |
| 501-600     | 23        | 14.65%  |
| 201-300     | 20        | 12.74%  |
| 601-700     | 11        | 7.01%   |
| 351-400     | 11        | 7.01%   |
| 801-900     | 2         | 1.27%   |
| 701-800     | 2         | 1.27%   |
| 1001-1500   | 2         | 1.27%   |
| Unknown     | 1         | 0.64%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 117       | 76.47%  |
| 16/10 | 22        | 14.38%  |
| 5/4   | 6         | 3.92%   |
| 21/9  | 5         | 3.27%   |
| 3/2   | 2         | 1.31%   |
| 4/3   | 1         | 0.65%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 33        | 21.15%  |
| 91-100         | 23        | 14.74%  |
| 81-90          | 22        | 14.1%   |
| 151-200        | 17        | 10.9%   |
| 351-500        | 9         | 5.77%   |
| 301-350        | 9         | 5.77%   |
| 101-110        | 8         | 5.13%   |
| 61-70          | 7         | 4.49%   |
| 141-150        | 7         | 4.49%   |
| 121-130        | 5         | 3.21%   |
| 51-60          | 4         | 2.56%   |
| 71-80          | 3         | 1.92%   |
| More than 1000 | 2         | 1.28%   |
| 251-300        | 2         | 1.28%   |
| 501-1000       | 2         | 1.28%   |
| 41-50          | 1         | 0.64%   |
| 111-120        | 1         | 0.64%   |
| Unknown        | 1         | 0.64%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 62        | 40.26%  |
| 101-120       | 49        | 31.82%  |
| 121-160       | 35        | 22.73%  |
| 161-240       | 6         | 3.9%    |
| More than 240 | 1         | 0.65%   |
| Unknown       | 1         | 0.65%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 145       | 70.73%  |
| 0     | 51        | 24.88%  |
| 2     | 9         | 4.39%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 107       | 37.41%  |
| Intel                             | 90        | 31.47%  |
| Qualcomm Atheros                  | 37        | 12.94%  |
| Broadcom                          | 26        | 9.09%   |
| Ralink                            | 7         | 2.45%   |
| Ralink Technology                 | 3         | 1.05%   |
| Marvell Technology Group          | 3         | 1.05%   |
| D-Link                            | 2         | 0.7%    |
| TP-Link                           | 1         | 0.35%   |
| Toshiba                           | 1         | 0.35%   |
| Sierra Wireless                   | 1         | 0.35%   |
| Qualcomm Atheros Communications   | 1         | 0.35%   |
| Mellanox Technologies             | 1         | 0.35%   |
| Hewlett-Packard                   | 1         | 0.35%   |
| Ericsson Business Mobile Networks | 1         | 0.35%   |
| D-Link System                     | 1         | 0.35%   |
| ASUSTek Computer                  | 1         | 0.35%   |
| AboCom Systems                    | 1         | 0.35%   |
| 3Com                              | 1         | 0.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller     | 86        | 25.07%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                 | 16        | 4.66%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                 | 12        | 3.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                      | 9         | 2.62%   |
| Intel Wireless 7260                                                   | 8         | 2.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter            | 7         | 2.04%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                   | 6         | 1.75%   |
| Intel Wireless 7265                                                   | 6         | 1.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)        | 5         | 1.46%   |
| Intel Wireless 8265 / 8275                                            | 5         | 1.46%   |
| Intel Wireless 8260                                                   | 5         | 1.46%   |
| Intel WiFi Link 5100                                                  | 4         | 1.17%   |
| Intel Ethernet Connection (7) I219-V                                  | 4         | 1.17%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                       | 4         | 1.17%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                     | 4         | 1.17%   |
| Intel Wireless 3165                                                   | 3         | 0.87%   |
| Intel Wi-Fi 6 AX200                                                   | 3         | 0.87%   |
| Intel I211 Gigabit Network Connection                                 | 3         | 0.87%   |
| Intel Ethernet Connection I218-LM                                     | 3         | 0.87%   |
| Intel Ethernet Connection I217-LM                                     | 3         | 0.87%   |
| Intel Centrino Wireless-N 2230                                        | 3         | 0.87%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                          | 3         | 0.87%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                              | 3         | 0.87%   |
| Intel 82579V Gigabit Network Connection                               | 3         | 0.87%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                     | 3         | 0.87%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                      | 3         | 0.87%   |
| Broadcom BCM4331 802.11a/b/g/n                                        | 3         | 0.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter              | 2         | 0.58%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter              | 2         | 0.58%   |
| Realtek RTL8188EE Wireless Network Adapter                            | 2         | 0.58%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                            | 2         | 0.58%   |
| Ralink RT5370 Wireless Adapter                                        | 2         | 0.58%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                | 2         | 0.58%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                             | 2         | 0.58%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter            | 2         | 0.58%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter            | 2         | 0.58%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)        | 2         | 0.58%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)        | 2         | 0.58%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                              | 2         | 0.58%   |
| Intel Ultimate N WiFi Link 5300                                       | 2         | 0.58%   |
| Intel Ethernet Connection I219-LM                                     | 2         | 0.58%   |
| Intel Ethernet Connection I218-V                                      | 2         | 0.58%   |
| Intel Ethernet Connection (3) I218-V                                  | 2         | 0.58%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                          | 2         | 0.58%   |
| Intel Centrino Advanced-N 6235                                        | 2         | 0.58%   |
| Intel Centrino Advanced-N 6200                                        | 2         | 0.58%   |
| Intel Cannon Lake PCH CNVi WiFi                                       | 2         | 0.58%   |
| Intel 82577LM Gigabit Network Connection                              | 2         | 0.58%   |
| Intel 82567LM Gigabit Network Connection                              | 2         | 0.58%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                     | 2         | 0.58%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                       | 2         | 0.58%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                    | 2         | 0.58%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                    | 2         | 0.58%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]            | 1         | 0.29%   |
| Toshiba Ericsson H5321gw for TOSHIBA Mobile Broadband Network Adapter | 1         | 0.29%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                         | 1         | 0.29%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter              | 1         | 0.29%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                       | 1         | 0.29%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                | 1         | 0.29%   |
| Realtek RTL8191SEvB Wireless LAN Controller                           | 1         | 0.29%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 63        | 43.15%  |
| Qualcomm Atheros                | 33        | 22.6%   |
| Realtek Semiconductor           | 19        | 13.01%  |
| Broadcom                        | 13        | 8.9%    |
| Ralink                          | 7         | 4.79%   |
| Ralink Technology               | 3         | 2.05%   |
| D-Link                          | 2         | 1.37%   |
| TP-Link                         | 1         | 0.68%   |
| Sierra Wireless                 | 1         | 0.68%   |
| Qualcomm Atheros Communications | 1         | 0.68%   |
| D-Link System                   | 1         | 0.68%   |
| ASUSTek Computer                | 1         | 0.68%   |
| AboCom Systems                  | 1         | 0.68%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 9         | 6.16%   |
| Intel Wireless 7260                                                                   | 8         | 5.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 7         | 4.79%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 6         | 4.11%   |
| Intel Wireless 7265                                                                   | 6         | 4.11%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 5         | 3.42%   |
| Intel Wireless 8265 / 8275                                                            | 5         | 3.42%   |
| Intel Wireless 8260                                                                   | 5         | 3.42%   |
| Intel WiFi Link 5100                                                                  | 4         | 2.74%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 4         | 2.74%   |
| Intel Wireless 3165                                                                   | 3         | 2.05%   |
| Intel Wi-Fi 6 AX200                                                                   | 3         | 2.05%   |
| Intel Centrino Wireless-N 2230                                                        | 3         | 2.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 3         | 2.05%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 3         | 2.05%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 3         | 2.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 2         | 1.37%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                              | 2         | 1.37%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 2         | 1.37%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 2         | 1.37%   |
| Ralink RT5370 Wireless Adapter                                                        | 2         | 1.37%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                | 2         | 1.37%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                             | 2         | 1.37%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 2         | 1.37%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 2         | 1.37%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 2         | 1.37%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 2         | 1.37%   |
| Intel Ultimate N WiFi Link 5300                                                       | 2         | 1.37%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                          | 2         | 1.37%   |
| Intel Centrino Advanced-N 6235                                                        | 2         | 1.37%   |
| Intel Centrino Advanced-N 6200                                                        | 2         | 1.37%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 2         | 1.37%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                    | 2         | 1.37%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                    | 2         | 1.37%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                            | 1         | 0.68%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                                         | 1         | 0.68%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.68%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 1         | 0.68%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                | 1         | 0.68%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                           | 1         | 0.68%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                | 1         | 0.68%   |
| Ralink MT7601U Wireless Adapter                                                       | 1         | 0.68%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                           | 1         | 0.68%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                                             | 1         | 0.68%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 1         | 0.68%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 1         | 0.68%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 1         | 0.68%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 0.68%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.68%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn]                | 1         | 0.68%   |
| Intel Wireless-AC 9260                                                                | 1         | 0.68%   |
| Intel Wireless 3160                                                                   | 1         | 0.68%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                               | 1         | 0.68%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 0.68%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 1         | 0.68%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 1         | 0.68%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]            | 1         | 0.68%   |
| D-Link DWA-171 AC600 DB Wireless Adapter(rev.A1) [Realtek RTL8811AU]                  | 1         | 0.68%   |
| D-Link DWA-125 Wireless N 150 Adapter(rev.B1) [Ralink RT5370]                         | 1         | 0.68%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                           | 1         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 102       | 53.97%  |
| Intel                    | 54        | 28.57%  |
| Broadcom                 | 20        | 10.58%  |
| Qualcomm Atheros         | 10        | 5.29%   |
| Marvell Technology Group | 3         | 1.59%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 86        | 44.79%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 16        | 8.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 6.25%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 2.08%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 4         | 2.08%   |
| Intel I211 Gigabit Network Connection                             | 3         | 1.56%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.56%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.56%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 1.56%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 1.56%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 3         | 1.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 1.04%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.04%   |
| Intel Ethernet Connection I218-V                                  | 2         | 1.04%   |
| Intel Ethernet Connection (3) I218-V                              | 2         | 1.04%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.04%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 1.04%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 1.04%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 1.04%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.52%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.52%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 0.52%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.52%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.52%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.52%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.52%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.52%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.52%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 0.52%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 0.52%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.52%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.52%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.52%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.52%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 0.52%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.52%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.52%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 0.52%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.52%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 0.52%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 0.52%   |
| Intel 82583V Gigabit Network Connection                           | 1         | 0.52%   |
| Intel 82578DM Gigabit Network Connection                          | 1         | 0.52%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 0.52%   |
| Intel 82567LF Gigabit Network Connection                          | 1         | 0.52%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1         | 0.52%   |
| Intel 82562V-2 10/100 Network Connection                          | 1         | 0.52%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1         | 0.52%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                    | 1         | 0.52%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1         | 0.52%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1         | 0.52%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1         | 0.52%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 0.52%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 188       | 57.32%  |
| WiFi     | 135       | 41.16%  |
| Modem    | 3         | 0.91%   |
| Unknown  | 2         | 0.61%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 187       | 61.92%  |
| WiFi     | 111       | 36.75%  |
| Modem    | 2         | 0.66%   |
| Unknown  | 2         | 0.66%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 115       | 55.83%  |
| 1     | 87        | 42.23%  |
| 3     | 3         | 1.46%   |
| 0     | 1         | 0.49%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 196       | 94.69%  |
| Yes  | 11        | 5.31%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 44        | 45.36%  |
| Qualcomm Atheros Communications | 9         | 9.28%   |
| Cambridge Silicon Radio         | 8         | 8.25%   |
| Apple                           | 8         | 8.25%   |
| Broadcom                        | 7         | 7.22%   |
| Realtek Semiconductor           | 5         | 5.15%   |
| IMC Networks                    | 4         | 4.12%   |
| ASUSTek Computer                | 3         | 3.09%   |
| Ralink                          | 2         | 2.06%   |
| Dell                            | 2         | 2.06%   |
| Lite-On Technology              | 1         | 1.03%   |
| Integrated System Solution      | 1         | 1.03%   |
| Hewlett-Packard                 | 1         | 1.03%   |
| Foxconn / Hon Hai               | 1         | 1.03%   |
| Edimax Technology               | 1         | 1.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 28        | 28.87%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 8         | 8.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 5         | 5.15%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 5         | 5.15%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 4         | 4.12%   |
| Intel AX200 Bluetooth                                       | 3         | 3.09%   |
| Ralink RT3290 Bluetooth                                     | 2         | 2.06%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 2         | 2.06%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 2.06%   |
| Intel AX201 Bluetooth                                       | 2         | 2.06%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 2         | 2.06%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 2.06%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 2         | 2.06%   |
| Realtek RTL8821A Bluetooth                                  | 1         | 1.03%   |
| Realtek  Bluetooth Adapter                                  | 1         | 1.03%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 1.03%   |
| Realtek  Bluetooth 4.0 + High Speed Chip                    | 1         | 1.03%   |
| Realtek CSR Bluetooth Chip                                  | 1         | 1.03%   |
| Qualcomm Atheros  QCA9565 Bluetooth 4.0 + HS Adapter        | 1         | 1.03%   |
| Qualcomm Atheros  QCA61x4 Bluetooth 4.1                     | 1         | 1.03%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 1.03%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 1.03%   |
| Qualcomm Atheros Atheros AR9462 Bluetooth 3.0 + HS Adapter  | 1         | 1.03%   |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS                 | 1         | 1.03%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 1.03%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 1.03%   |
| Integrated System Solution Bluetooth Device                 | 1         | 1.03%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0                 | 1         | 1.03%   |
| IMC Networks Broadcom BCM20702 Bluetooth 4.0 +HS USB Device | 1         | 1.03%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 1.03%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 1.03%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter     | 1         | 1.03%   |
| Dell DW375 Bluetooth Module                                 | 1         | 1.03%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 1         | 1.03%   |
| Broadcom Bluetooth Device                                   | 1         | 1.03%   |
| Broadcom Bluetooth 2.0+eDR dongle                           | 1         | 1.03%   |
| Broadcom BCM43142A0 Bluetooth 4.0                           | 1         | 1.03%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 1         | 1.03%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                        | 1         | 1.03%   |
| ASUS Realtek Bluetooth 4.0 + High Speed Chip                | 1         | 1.03%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1         | 1.03%   |
| Apple Bluetooth USB Host Controller                         | 1         | 1.03%   |
| Apple Bluetooth Host Controller                             | 1         | 1.03%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 169       | 61.45%  |
| Nvidia                      | 50        | 18.18%  |
| AMD                         | 45        | 16.36%  |
| Texas Instruments           | 2         | 0.73%   |
| Creative Technology         | 2         | 0.73%   |
| XMOS                        | 1         | 0.36%   |
| Steinberg Soft-und Hardware | 1         | 0.36%   |
| SteelSeries ApS             | 1         | 0.36%   |
| Realtek Semiconductor       | 1         | 0.36%   |
| Logitech                    | 1         | 0.36%   |
| Creative Labs               | 1         | 0.36%   |
| C-Media Electronics         | 1         | 0.36%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 26        | 8.2%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 20        | 6.31%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 14        | 4.42%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 12        | 3.79%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 11        | 3.47%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 3.47%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 11        | 3.47%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 10        | 3.15%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 2.52%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8         | 2.52%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 7         | 2.21%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 2.21%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 2.21%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 2.21%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 7         | 2.21%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 6         | 1.89%   |
| Intel 200 Series PCH HD Audio                                                                     | 6         | 1.89%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 5         | 1.58%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 5         | 1.58%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 1.58%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 5         | 1.58%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 5         | 1.58%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 1.58%   |
| AMD FCH Azalia Controller                                                                         | 5         | 1.58%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 4         | 1.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.26%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 1.26%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.26%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 1.26%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 4         | 1.26%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 4         | 1.26%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.95%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.95%   |
| Intel Comet Lake PCH-V Smart Sound Technology Audio Controller                                    | 3         | 0.95%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 0.95%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 3         | 0.95%   |
| Nvidia MCP61 High Definition Audio                                                                | 2         | 0.63%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.63%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 0.63%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.63%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 2         | 0.63%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 2         | 0.63%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.63%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 2         | 0.63%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 0.63%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 0.63%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 2         | 0.63%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 0.63%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.63%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 0.63%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 2         | 0.63%   |
| XMOS Cyberdrive Audio Driver                                                                      | 1         | 0.32%   |
| Texas Instruments SMSL Q5 AMP                                                                     | 1         | 0.32%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.32%   |
| Steinberg Soft-und Hardware MI4                                                                   | 1         | 0.32%   |
| SteelSeries ApS Arctis 7 wireless adapter                                                         | 1         | 0.32%   |
| Realtek Semiconductor Realtek Audio USB Realtek Audio USB Microphone                              | 1         | 0.32%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.32%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.32%   |
| Logitech HD Webcam C910                                                                           | 1         | 0.32%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Samsung Electronics        | 42        | 16.8%   |
| SK Hynix                   | 34        | 13.6%   |
| Kingston                   | 32        | 12.8%   |
| Unknown                    | 28        | 11.2%   |
| Micron Technology          | 25        | 10%     |
| Crucial                    | 22        | 8.8%    |
| Elpida                     | 13        | 5.2%    |
| Nanya Technology           | 6         | 2.4%    |
| G.Skill                    | 6         | 2.4%    |
| Corsair                    | 6         | 2.4%    |
| Ramaxel Technology         | 5         | 2%      |
| Smart                      | 4         | 1.6%    |
| Apacer                     | 3         | 1.2%    |
| A-DATA Technology          | 3         | 1.2%    |
| Teikon                     | 2         | 0.8%    |
| Team                       | 2         | 0.8%    |
| PNY                        | 2         | 0.8%    |
| High Bridge                | 2         | 0.8%    |
| Avant                      | 2         | 0.8%    |
| AMD                        | 2         | 0.8%    |
| Unknown (ABCD)             | 1         | 0.4%    |
| Unknown (7F7F7F94FFFFFFFF) | 1         | 0.4%    |
| Unknown (09A4)             | 1         | 0.4%    |
| Transcend                  | 1         | 0.4%    |
| Toshiba                    | 1         | 0.4%    |
| Smart Brazil               | 1         | 0.4%    |
| SHARETRONIC                | 1         | 0.4%    |
| Patriot                    | 1         | 0.4%    |
| Goldkey                    | 1         | 0.4%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                              | Computers | Percent |
|--------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s             | 4         | 1.48%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s              | 3         | 1.11%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1333MT/s              | 3         | 1.11%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s              | 3         | 1.11%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                        | 2         | 0.74%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                        | 2         | 0.74%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                               | 2         | 0.74%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                               | 2         | 0.74%   |
| SK Hynix RAM Module 2GB SODIMM DDR3 1600MT/s                       | 2         | 0.74%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s             | 2         | 0.74%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s              | 2         | 0.74%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s              | 2         | 0.74%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s              | 2         | 0.74%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s             | 2         | 0.74%   |
| Samsung RAM K3QF4F40BM-AGCF 4GB Row Of Chips LPDDR3 1867MT/s       | 2         | 0.74%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s              | 2         | 0.74%   |
| Micron RAM 8JTF25664AZ-1G6M1 2GB DIMM DDR3 1600MT/s                | 2         | 0.74%   |
| Micron RAM 4ATF51264HZ-2G3E1 4GB SODIMM DDR4 2400MT/s              | 2         | 0.74%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s              | 2         | 0.74%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3200MT/s               | 2         | 0.74%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 2667MT/s                  | 2         | 0.74%   |
| G.Skill RAM F4-2666C19-8GNT 8GB DIMM DDR4 2666MT/s                 | 2         | 0.74%   |
| Unknown RAM TMKS8G68ALFBCH-266 8192MB SODIMM DDR4 2400MT/s         | 1         | 0.37%   |
| Unknown RAM R9P5316-007.A02LF 2GB DIMM 533MT/s                     | 1         | 0.37%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                        | 1         | 0.37%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                          | 1         | 0.37%   |
| Unknown RAM Module 8GB DIMM DDR3 1866MT/s                          | 1         | 0.37%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                               | 1         | 0.37%   |
| Unknown RAM Module 4GB SODIMM DDR3                                 | 1         | 0.37%   |
| Unknown RAM Module 4GB DIMM DDR3 1866MT/s                          | 1         | 0.37%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                          | 1         | 0.37%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                           | 1         | 0.37%   |
| Unknown RAM Module 4GB DIMM 667MT/s                                | 1         | 0.37%   |
| Unknown RAM Module 4096MB DIMM DDR2                                | 1         | 0.37%   |
| Unknown RAM Module 2GB FB-DIMM DDR2 667MT/s                        | 1         | 0.37%   |
| Unknown RAM Module 2GB DIMM SDRAM                                  | 1         | 0.37%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                           | 1         | 0.37%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                           | 1         | 0.37%   |
| Unknown RAM Module 2GB DIMM 1600MT/s                               | 1         | 0.37%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                           | 1         | 0.37%   |
| Unknown RAM Module 2048MB SODIMM 667MT/s                           | 1         | 0.37%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s                       | 1         | 0.37%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                        | 1         | 0.37%   |
| Unknown RAM Module 2048MB DIMM DDR2                                | 1         | 0.37%   |
| Unknown RAM Module 1GB DIMM 1333MT/s                               | 1         | 0.37%   |
| Unknown RAM Module 1024MB DIMM SDRAM 667MT/s                       | 1         | 0.37%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s     | 1         | 0.37%   |
| Unknown (7F7F7F94FFFFFFFF) RAM 996593PCGH 2048MB DIMM DDR2 800MT/s | 1         | 0.37%   |
| Unknown (09A4) RAM 08S2400CL170H 8192MB DIMM DDR4 2133MT/s         | 1         | 0.37%   |
| Transcend RAM JM1600KSH-8G 8192MB SODIMM DDR3 1333MT/s             | 1         | 0.37%   |
| Toshiba RAM 8HTF12864HDY-800G1 2048MB SODIMM 800MT/s               | 1         | 0.37%   |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 800MT/s                | 1         | 0.37%   |
| Teikon RAM TMT451S6BFR8A-PBSC 4096MB SODIMM DDR3 1600MT/s          | 1         | 0.37%   |
| Teikon RAM TML251S6EFR8A-PBHC 4096MB SODIMM DDR3 1600MT/s          | 1         | 0.37%   |
| Team RAM TEAMGROUP-UD4-3000 4GB DIMM DDR4 2400MT/s                 | 1         | 0.37%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2667MT/s                 | 1         | 0.37%   |
| Smart RAM SH564568FH8NWPHSFR 2GB SODIMM DDR3 1333MT/s              | 1         | 0.37%   |
| Smart RAM SH564128FJ8NZRNSDR 4GB SODIMM DDR3 1600MT/s              | 1         | 0.37%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4096MB SODIMM DDR4 2400MT/s    | 1         | 0.37%   |
| SK Hynix RAM Module 2GB DDR3 1600MT/s                              | 1         | 0.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 108       | 52.68%  |
| DDR4    | 64        | 31.22%  |
| DDR2    | 12        | 5.85%   |
| Unknown | 12        | 5.85%   |
| LPDDR3  | 4         | 1.95%   |
| SDRAM   | 3         | 1.46%   |
| LPDDR4  | 1         | 0.49%   |
| DDR     | 1         | 0.49%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 102       | 49.76%  |
| DIMM         | 93        | 45.37%  |
| Row Of Chips | 5         | 2.44%   |
| FB-DIMM      | 2         | 0.98%   |
| Chip         | 2         | 0.98%   |
| Unknown      | 1         | 0.49%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 96        | 40%     |
| 2048  | 64        | 26.67%  |
| 8192  | 59        | 24.58%  |
| 16384 | 14        | 5.83%   |
| 1024  | 5         | 2.08%   |
| 32768 | 2         | 0.83%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 66        | 28.82%  |
| 1333    | 44        | 19.21%  |
| 2400    | 27        | 11.79%  |
| 2667    | 18        | 7.86%   |
| 2133    | 17        | 7.42%   |
| 800     | 11        | 4.8%    |
| 667     | 9         | 3.93%   |
| 3200    | 5         | 2.18%   |
| 2666    | 5         | 2.18%   |
| 1867    | 5         | 2.18%   |
| 1334    | 5         | 2.18%   |
| 1067    | 3         | 1.31%   |
| Unknown | 3         | 1.31%   |
| 1866    | 2         | 0.87%   |
| 1066    | 2         | 0.87%   |
| 533     | 2         | 0.87%   |
| 2933    | 1         | 0.44%   |
| 1800    | 1         | 0.44%   |
| 1777    | 1         | 0.44%   |
| 1400    | 1         | 0.44%   |
| 975     | 1         | 0.44%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart_bsd/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 4         | 57.14%  |
| Lexmark International | 2         | 28.57%  |
| Seiko Epson           | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart_bsd/printer_model.svg)


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

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 17        | 22.67%  |
| Realtek Semiconductor                  | 10        | 13.33%  |
| Microdia                               | 7         | 9.33%   |
| Sunplus Innovation Technology          | 6         | 8%      |
| Apple                                  | 4         | 5.33%   |
| Acer                                   | 4         | 5.33%   |
| Suyin                                  | 3         | 4%      |
| IMC Networks                           | 3         | 4%      |
| Syntek                                 | 2         | 2.67%   |
| Silicon Motion                         | 2         | 2.67%   |
| Logitech                               | 2         | 2.67%   |
| Lite-On Technology                     | 2         | 2.67%   |
| Importek                               | 2         | 2.67%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.67%   |
| Alcor Micro                            | 2         | 2.67%   |
| Ricoh                                  | 1         | 1.33%   |
| Quanta                                 | 1         | 1.33%   |
| Intel                                  | 1         | 1.33%   |
| Holitech                               | 1         | 1.33%   |
| Hewlett-Packard                        | 1         | 1.33%   |
| Generalplus Technology                 | 1         | 1.33%   |
| A4Tech                                 | 1         | 1.33%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                              | 4         | 5.26%   |
| Apple FaceTime HD camera                                  | 4         | 5.26%   |
| Realtek Realtek USB2.0 PC Camera                          | 3         | 3.95%   |
| Chicony integrated camera                                 | 3         | 3.95%   |
| Chicony HP HD Webcam [Fixed]                              | 3         | 3.95%   |
| Sunplus Integrated_Webcam_HD                              | 2         | 2.63%   |
| Sunplus Asus Webcam                                       | 2         | 2.63%   |
| Realtek Integrated Webcam                                 | 2         | 2.63%   |
| Microdia Laptop_Integrated_Webcam_HD                      | 2         | 2.63%   |
| Microdia Integrated Webcam                                | 2         | 2.63%   |
| Logitech Webcam C270                                      | 2         | 2.63%   |
| IMC Networks USB2.0 HD UVC WebCam                         | 2         | 2.63%   |
| Chicony Integrated Camera [ThinkPad]                      | 2         | 2.63%   |
| Syntek Lenovo EasyCamera                                  | 1         | 1.32%   |
| Syntek EasyCamera                                         | 1         | 1.32%   |
| Suyin USB 2.0 Camera                                      | 1         | 1.32%   |
| Suyin Sony Visual Communication Camera                    | 1         | 1.32%   |
| Suyin HP Integrated Webcam                                | 1         | 1.32%   |
| Sunplus Integrated Camera                                 | 1         | 1.32%   |
| Sunplus Dell E5570 integrated webcam                      | 1         | 1.32%   |
| Silicon Motion WebCam SCX Series                          | 1         | 1.32%   |
| Silicon Motion Realtek USB2.0 PC Camera                   | 1         | 1.32%   |
| Ricoh Integrated Camera                                   | 1         | 1.32%   |
| Realtek LG Camera                                         | 1         | 1.32%   |
| Quanta HP Webcam                                          | 1         | 1.32%   |
| Microdia Laptop_Integrated_Webcam_FHD                     | 1         | 1.32%   |
| Microdia HP Webcam                                        | 1         | 1.32%   |
| Microdia ASUS USB2.0 Webcam                               | 1         | 1.32%   |
| Lite-On Integrated Camera                                 | 1         | 1.32%   |
| Lite-On HP IR Camera                                      | 1         | 1.32%   |
| Intel Intel(R) RealSense(TM) 3D Camera (Front F200)       | 1         | 1.32%   |
| Importek TOSHIBA Web Camera - HD                          | 1         | 1.32%   |
| Importek TOSHIBA Web Camera                               | 1         | 1.32%   |
| IMC Networks EasyCamera                                   | 1         | 1.32%   |
| Holitech USB2.0 HD UVC WebCam                             | 1         | 1.32%   |
| HP Premium Starter Webcam                                 | 1         | 1.32%   |
| Generalplus GENERAL WEBCAM                                | 1         | 1.32%   |
| Chicony UVC 1.00 device HD UVC WebCam                     | 1         | 1.32%   |
| Chicony USB2.0 VGA UVC WebCam                             | 1         | 1.32%   |
| Chicony TOSHIBA Web Camera - HD                           | 1         | 1.32%   |
| Chicony TOSHIBA Web Camera - 3M                           | 1         | 1.32%   |
| Chicony Lenovo EasyCamera                                 | 1         | 1.32%   |
| Chicony HP Webcam [2 MP Macro]                            | 1         | 1.32%   |
| Chicony HP HD Camera                                      | 1         | 1.32%   |
| Chicony HD WebCam                                         | 1         | 1.32%   |
| Chicony Chicony USB2.0 Camera                             | 1         | 1.32%   |
| Chicony 1.3M Webcam                                       | 1         | 1.32%   |
| Cheng Uei Precision Industry (Foxlink) Webcam             | 1         | 1.32%   |
| Cheng Uei Precision Industry (Foxlink) Realtek DMFT - RGB | 1         | 1.32%   |
| Alcor Micro USB 2.0 Camera                                | 1         | 1.32%   |
| Alcor Micro Acer Integrated Webcam                        | 1         | 1.32%   |
| Acer Lenovo Integrated Webcam                             | 1         | 1.32%   |
| Acer Lenovo EasyCamera                                    | 1         | 1.32%   |
| Acer Integrated Camera                                    | 1         | 1.32%   |
| Acer HD Webcam                                            | 1         | 1.32%   |
| A4Tech A4tech FHD 1080P PC Camera                         | 1         | 1.32%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 7         | 77.78%  |
| Broadcom         | 1         | 11.11%  |
| AuthenTec        | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                                  | 3         | 33.33%  |
| Validity Sensors VFS495 Fingerprint Reader                                   | 1         | 11.11%  |
| Validity Sensors VFS451 Fingerprint Reader                                   | 1         | 11.11%  |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 1         | 11.11%  |
| Validity Sensors Synaptics WBDI                                              | 1         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 11.11%  |
| AuthenTec AES2810                                                            | 1         | 11.11%  |

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
| 1     | 79        | 37.98%  |
| 2     | 51        | 24.52%  |
| 0     | 46        | 22.12%  |
| 3     | 25        | 12.02%  |
| 4     | 7         | 3.37%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 137       | 50.74%  |
| Card reader              | 52        | 19.26%  |
| Net/wireless             | 32        | 11.85%  |
| Bluetooth                | 21        | 7.78%   |
| Firewire controller      | 11        | 4.07%   |
| Fingerprint reader       | 9         | 3.33%   |
| Sound                    | 4         | 1.48%   |
| Storage                  | 2         | 0.74%   |
| Storage/raid             | 1         | 0.37%   |
| Dvb card                 | 1         | 0.37%   |

