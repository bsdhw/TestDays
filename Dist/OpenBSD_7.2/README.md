OpenBSD 7.2 - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for OpenBSD 7.2.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/OpenBSD_7.2/Desktop/README.md) and [notebooks](/Dist/OpenBSD_7.2/Notebook/README.md).

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

Total: 114

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Sony          | SVS1312J3EW                 | Notebook    | [3451ac064b](https://bsd-hardware.info/?probe=3451ac064b) | Nov 02, 2024 |
| ASUSTek       | X541UAK                     | Notebook    | [35a1818a41](https://bsd-hardware.info/?probe=35a1818a41) | Aug 11, 2024 |
| HP            | Pavilion g6                 | Desktop     | [eeffda8d57](https://bsd-hardware.info/?probe=eeffda8d57) | Apr 09, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [ffbe23b7d8](https://bsd-hardware.info/?probe=ffbe23b7d8) | Apr 09, 2023 |
| Fujitsu       | LIFEBOOK U810               | Notebook    | [3073cd605c](https://bsd-hardware.info/?probe=3073cd605c) | Apr 06, 2023 |
| Fujitsu       | LIFEBOOK U810               | Notebook    | [c7718b4aa3](https://bsd-hardware.info/?probe=c7718b4aa3) | Apr 03, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [640aad419a](https://bsd-hardware.info/?probe=640aad419a) | Apr 02, 2023 |
| Sun           | SUNW,T5140                  | Desktop     | [a285e4f43a](https://bsd-hardware.info/?probe=a285e4f43a) | Apr 02, 2023 |
| Lenovo        | ThinkPad T410 2518A37       | Notebook    | [f5537face6](https://bsd-hardware.info/?probe=f5537face6) | Mar 27, 2023 |
| Dell          | G5 5587                     | Notebook    | [9b7714cbab](https://bsd-hardware.info/?probe=9b7714cbab) | Mar 24, 2023 |
| Dell          | G5 5587                     | Notebook    | [c118e0665f](https://bsd-hardware.info/?probe=c118e0665f) | Mar 24, 2023 |
| Lenovo        | ThinkPad T410 2518A37       | Notebook    | [42fffdf3f2](https://bsd-hardware.info/?probe=42fffdf3f2) | Mar 23, 2023 |
| Lenovo        | ThinkCentre M910q 10MVCT... | Desktop     | [5459ed9c31](https://bsd-hardware.info/?probe=5459ed9c31) | Mar 22, 2023 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [cbbeb5c41c](https://bsd-hardware.info/?probe=cbbeb5c41c) | Mar 22, 2023 |
| Apple         | iMac18,1                    | All in one  | [c6c12705af](https://bsd-hardware.info/?probe=c6c12705af) | Mar 20, 2023 |
| Intel         | S1200RP_SE                  | Notebook    | [5ae9400f0b](https://bsd-hardware.info/?probe=5ae9400f0b) | Mar 17, 2023 |
| OEGStone      | W54_55SU1,SUW               | Notebook    | [7a2b28c47f](https://bsd-hardware.info/?probe=7a2b28c47f) | Mar 17, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [e023282dcd](https://bsd-hardware.info/?probe=e023282dcd) | Mar 13, 2023 |
| Gigabyte      | B450M K                     | Desktop     | [0d0433284e](https://bsd-hardware.info/?probe=0d0433284e) | Mar 11, 2023 |
| HP            | 240 G6 Notebook PC          | Notebook    | [d872652e25](https://bsd-hardware.info/?probe=d872652e25) | Feb 28, 2023 |
| HP            | Pavilion g6                 | Desktop     | [39a7b609d6](https://bsd-hardware.info/?probe=39a7b609d6) | Feb 27, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | Notebook    | [aef791947c](https://bsd-hardware.info/?probe=aef791947c) | Feb 23, 2023 |
| PC Engines    | apu1                        | Desktop     | [41fe7362c4](https://bsd-hardware.info/?probe=41fe7362c4) | Feb 22, 2023 |
| Apple         | PowerMac3,6                 | Desktop     | [f31181f95c](https://bsd-hardware.info/?probe=f31181f95c) | Feb 20, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [673f6c0a01](https://bsd-hardware.info/?probe=673f6c0a01) | Feb 17, 2023 |
| Dell          | OptiPlex 9020               | Desktop     | [0c8a5f8dfa](https://bsd-hardware.info/?probe=0c8a5f8dfa) | Feb 13, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [96fa5325d1](https://bsd-hardware.info/?probe=96fa5325d1) | Feb 11, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [4d69517a13](https://bsd-hardware.info/?probe=4d69517a13) | Feb 07, 2023 |
| Panasonic     | CF-30KAPAXAM                | Notebook    | [baa7612257](https://bsd-hardware.info/?probe=baa7612257) | Feb 07, 2023 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | Notebook    | [bccdd2f331](https://bsd-hardware.info/?probe=bccdd2f331) | Jan 30, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [4c25e80924](https://bsd-hardware.info/?probe=4c25e80924) | Jan 29, 2023 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [a6b109939f](https://bsd-hardware.info/?probe=a6b109939f) | Jan 28, 2023 |
| Google        | Kefka                       | Notebook    | [83771661c6](https://bsd-hardware.info/?probe=83771661c6) | Jan 27, 2023 |
| Dell          | OptiPlex 3040               | Desktop     | [9c925f4e7f](https://bsd-hardware.info/?probe=9c925f4e7f) | Jan 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [1d040b684b](https://bsd-hardware.info/?probe=1d040b684b) | Jan 21, 2023 |
| ASUSTek       | PRO A520M-C                 | Desktop     | [bebcd1a008](https://bsd-hardware.info/?probe=bebcd1a008) | Jan 20, 2023 |
| Fujitsu       | PRIMERGY RX200 S6           | Desktop     | [4bcc8752f4](https://bsd-hardware.info/?probe=4bcc8752f4) | Jan 20, 2023 |
| Lenovo        | H30-05 90BJ0085SP           | Desktop     | [1424b3641c](https://bsd-hardware.info/?probe=1424b3641c) | Jan 18, 2023 |
| Dell          | PowerEdge R710              | Desktop     | [720e99b25e](https://bsd-hardware.info/?probe=720e99b25e) | Jan 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [dcdf55f06e](https://bsd-hardware.info/?probe=dcdf55f06e) | Jan 17, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [d8007634f3](https://bsd-hardware.info/?probe=d8007634f3) | Jan 17, 2023 |
| HP            | ProBook 455 G7              | Notebook    | [600f7f4f4f](https://bsd-hardware.info/?probe=600f7f4f4f) | Jan 16, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | Notebook    | [ced6c29193](https://bsd-hardware.info/?probe=ced6c29193) | Jan 14, 2023 |
| HP            | Presario V2000 (EZ621UA#... | Notebook    | [847af5b70f](https://bsd-hardware.info/?probe=847af5b70f) | Jan 14, 2023 |
| Gigabyte      | Z390 AORUS ELITE            | Desktop     | [53a5719c6a](https://bsd-hardware.info/?probe=53a5719c6a) | Jan 12, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | Notebook    | [82e9263905](https://bsd-hardware.info/?probe=82e9263905) | Jan 11, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [549b75038e](https://bsd-hardware.info/?probe=549b75038e) | Jan 08, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [5e81493c8d](https://bsd-hardware.info/?probe=5e81493c8d) | Jan 08, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [4014cc42ed](https://bsd-hardware.info/?probe=4014cc42ed) | Jan 08, 2023 |
| Lenovo        | ThinkStation D20 415575G    | Desktop     | [0a15d989e3](https://bsd-hardware.info/?probe=0a15d989e3) | Jan 08, 2023 |
| Supermicro    | Super Server                | Server      | [841407deb7](https://bsd-hardware.info/?probe=841407deb7) | Jan 07, 2023 |
| ASUSTek       | F2A85-M                     | Desktop     | [e25da8b10a](https://bsd-hardware.info/?probe=e25da8b10a) | Jan 06, 2023 |
| PC Engines    | apu4                        | Desktop     | [62e6e7e679](https://bsd-hardware.info/?probe=62e6e7e679) | Jan 03, 2023 |
| Notebook      | NS5x_NS7xPU                 | Notebook    | [7dc1fdfadb](https://bsd-hardware.info/?probe=7dc1fdfadb) | Jan 02, 2023 |
| Gigabyte      | Z390 AORUS ELITE            | Desktop     | [dcf6e2df1a](https://bsd-hardware.info/?probe=dcf6e2df1a) | Jan 02, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | Notebook    | [3b0ef08599](https://bsd-hardware.info/?probe=3b0ef08599) | Jan 01, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | Notebook    | [c791e3e3fd](https://bsd-hardware.info/?probe=c791e3e3fd) | Dec 30, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B9450FA_... | Notebook    | [d5fa6c651c](https://bsd-hardware.info/?probe=d5fa6c651c) | Dec 30, 2022 |
| Star Labs     | Lite                        | Notebook    | [9ad15636dd](https://bsd-hardware.info/?probe=9ad15636dd) | Dec 25, 2022 |
| Gigabyte      | Z390 AORUS ELITE            | Desktop     | [91b7417b84](https://bsd-hardware.info/?probe=91b7417b84) | Dec 24, 2022 |
| Tactus        | GeoFlex 110                 | Notebook    | [955c355b47](https://bsd-hardware.info/?probe=955c355b47) | Dec 23, 2022 |
| Toshiba       | Satellite BE96-F299         | Notebook    | [ca475dd1d0](https://bsd-hardware.info/?probe=ca475dd1d0) | Dec 23, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [b38d32b139](https://bsd-hardware.info/?probe=b38d32b139) | Dec 23, 2022 |
| Lenovo        | ThinkPad T480 20L6S13100    | Notebook    | [67daa912fa](https://bsd-hardware.info/?probe=67daa912fa) | Dec 23, 2022 |
| Raspberry ... | Raspberry Pi 400            | Desktop     | [ee9cac334f](https://bsd-hardware.info/?probe=ee9cac334f) | Dec 21, 2022 |
| Lenovo        | ThinkPad T60 1951A47        | Notebook    | [e254601f07](https://bsd-hardware.info/?probe=e254601f07) | Dec 21, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [af2a9d1a42](https://bsd-hardware.info/?probe=af2a9d1a42) | Dec 20, 2022 |
| Unknown       | Pine64 RockPro64 v2.1       | Desktop     | [59525051d3](https://bsd-hardware.info/?probe=59525051d3) | Dec 19, 2022 |
| Lenovo        | ThinkPad X200 Tablet 744... | Notebook    | [ea686f63f5](https://bsd-hardware.info/?probe=ea686f63f5) | Dec 19, 2022 |
| Framework     | Laptop                      | Notebook    | [9dcd3592db](https://bsd-hardware.info/?probe=9dcd3592db) | Dec 19, 2022 |
| Lenovo        | ThinkCentre M93p 10A8S0C... | Desktop     | [11d5b82cdd](https://bsd-hardware.info/?probe=11d5b82cdd) | Dec 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [9b5307f44d](https://bsd-hardware.info/?probe=9b5307f44d) | Dec 15, 2022 |
| HP            | ProBook 430 G7              | Notebook    | [0e2278affa](https://bsd-hardware.info/?probe=0e2278affa) | Dec 14, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [15b2363325](https://bsd-hardware.info/?probe=15b2363325) | Dec 05, 2022 |
| Panasonic     | CF-54-1                     | Notebook    | [0c5820ea0d](https://bsd-hardware.info/?probe=0c5820ea0d) | Dec 01, 2022 |
| ASRock        | X570 Pro4                   | Desktop     | [b23f59a068](https://bsd-hardware.info/?probe=b23f59a068) | Nov 27, 2022 |
| ASUSTek       | P11C-X Series               | Desktop     | [6860cd72f8](https://bsd-hardware.info/?probe=6860cd72f8) | Nov 26, 2022 |
| ASUSTek       | P11C-X Series               | Desktop     | [cfdb06e761](https://bsd-hardware.info/?probe=cfdb06e761) | Nov 26, 2022 |
| Dell          | Vostro 3501                 | Notebook    | [61f8a35700](https://bsd-hardware.info/?probe=61f8a35700) | Nov 25, 2022 |
| Lenovo        | ThinkPad X230 2325T4T       | Notebook    | [f0cc17c7eb](https://bsd-hardware.info/?probe=f0cc17c7eb) | Nov 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [4044f32351](https://bsd-hardware.info/?probe=4044f32351) | Nov 12, 2022 |
| Lenovo        | ThinkPad X260 20F5S2GM00    | Notebook    | [b8874a6df3](https://bsd-hardware.info/?probe=b8874a6df3) | Nov 10, 2022 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [5dcd51844e](https://bsd-hardware.info/?probe=5dcd51844e) | Nov 09, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [e8aea441aa](https://bsd-hardware.info/?probe=e8aea441aa) | Nov 06, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [95d5580fd7](https://bsd-hardware.info/?probe=95d5580fd7) | Nov 05, 2022 |
| ASUSTek       | Z170-K                      | Desktop     | [907b8c2402](https://bsd-hardware.info/?probe=907b8c2402) | Nov 05, 2022 |
| Lenovo        | ThinkPad X220 429043U       | Notebook    | [e5716f886a](https://bsd-hardware.info/?probe=e5716f886a) | Oct 30, 2022 |
| Lenovo        | ThinkPad T420s 41742BU      | Notebook    | [34f0a2bc03](https://bsd-hardware.info/?probe=34f0a2bc03) | Oct 30, 2022 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [e3c5057898](https://bsd-hardware.info/?probe=e3c5057898) | Oct 29, 2022 |
| Panasonic     | CF-53AAGHYDM                | Notebook    | [f2fafaa9e3](https://bsd-hardware.info/?probe=f2fafaa9e3) | Oct 27, 2022 |
| Matsushita... | CF-48V4KNDQM                | Notebook    | [d96fbc17b5](https://bsd-hardware.info/?probe=d96fbc17b5) | Oct 27, 2022 |
| Panasonic     | CF-52PFPBSFQ                | Notebook    | [088e0245af](https://bsd-hardware.info/?probe=088e0245af) | Oct 27, 2022 |
| Matsushita... | CF-51RCVDNLM                | Notebook    | [6e8067d4d8](https://bsd-hardware.info/?probe=6e8067d4d8) | Oct 26, 2022 |
| Lenovo        | ThinkPad T410 2537N24       | Notebook    | [b7a4ee06a6](https://bsd-hardware.info/?probe=b7a4ee06a6) | Oct 26, 2022 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [06e6c07e90](https://bsd-hardware.info/?probe=06e6c07e90) | Oct 25, 2022 |
| PC Engines    | APU2                        | Desktop     | [d52e3d0ce3](https://bsd-hardware.info/?probe=d52e3d0ce3) | Oct 25, 2022 |
| Lenovo        | ThinkPad T430 2347GZU       | Notebook    | [f2236f17ee](https://bsd-hardware.info/?probe=f2236f17ee) | Oct 25, 2022 |
| ASUSTek       | 1000HE                      | Notebook    | [c4bbcf9537](https://bsd-hardware.info/?probe=c4bbcf9537) | Oct 24, 2022 |
| Alienware     | m15                         | Notebook    | [3304a767ba](https://bsd-hardware.info/?probe=3304a767ba) | Oct 22, 2022 |
| ASUSTek       | P8Z68-V GEN3                | Desktop     | [d7b32200a5](https://bsd-hardware.info/?probe=d7b32200a5) | Oct 22, 2022 |
| PC Engines    | APU2                        | Desktop     | [cf1abf5e46](https://bsd-hardware.info/?probe=cf1abf5e46) | Oct 21, 2022 |
| Supermicro    | X8DTH-i/6/iF/6F             | Desktop     | [12f7ac40ac](https://bsd-hardware.info/?probe=12f7ac40ac) | Oct 21, 2022 |
| Unknown       | Unknown                     | Desktop     | [d5586487b4](https://bsd-hardware.info/?probe=d5586487b4) | Oct 21, 2022 |
| ASUSTek       | P10S-I Series               | Desktop     | [ceb58e75b8](https://bsd-hardware.info/?probe=ceb58e75b8) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [7ecffc1ca3](https://bsd-hardware.info/?probe=7ecffc1ca3) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [eb6eda641d](https://bsd-hardware.info/?probe=eb6eda641d) | Oct 20, 2022 |
| Dell          | Latitude E6420              | Notebook    | [07b078fdef](https://bsd-hardware.info/?probe=07b078fdef) | Oct 04, 2022 |
| Lenovo        | ThinkPad T410 2518C3U       | Notebook    | [627206d154](https://bsd-hardware.info/?probe=627206d154) | Oct 04, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Desktop     | [e001150f93](https://bsd-hardware.info/?probe=e001150f93) | Oct 03, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [1a89d78fa4](https://bsd-hardware.info/?probe=1a89d78fa4) | Sep 22, 2022 |
| Dell          | PowerEdge R620              | Desktop     | [66db9eb745](https://bsd-hardware.info/?probe=66db9eb745) | Aug 25, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [4ba15a31d9](https://bsd-hardware.info/?probe=4ba15a31d9) | Aug 10, 2022 |
| Intel         | NUC5PPYB H76558-102         | Mini pc     | [9124f0eb45](https://bsd-hardware.info/?probe=9124f0eb45) | Aug 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X545... | Notebook    | [bf5cea4ab5](https://bsd-hardware.info/?probe=bf5cea4ab5) | Jul 30, 2022 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| amd64   | 88        | 90.72%  |
| i386    | 5         | 5.15%   |
| arm64   | 2         | 2.06%   |
| sparc64 | 1         | 1.03%   |
| macppc  | 1         | 1.03%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 85        | 87.63%  |
| XFCE         | 6         | 6.19%   |
| GNOME        | 4         | 4.12%   |
| MATE         | 1         | 1.03%   |
| Lumina       | 1         | 1.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 82        | 83.67%  |
| Console | 16        | 16.33%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 97        | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 79        | 81.44%  |
| C          | 4         | 4.12%   |
| en_US      | 3         | 3.09%   |
| ru_RU      | 2         | 2.06%   |
| pl_PL      | 2         | 2.06%   |
| ja_JP      | 2         | 2.06%   |
| fr_FR      | 2         | 2.06%   |
| zh_TW      | 1         | 1.03%   |
| ISO8859-15 | 1         | 1.03%   |
| es_ES      | 1         | 1.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 62        | 63.92%  |
| BIOS | 35        | 36.08%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ffs  | 97        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 54        | 55.67%  |
| MBR  | 43        | 44.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 25        | 25.77%  |
| ASUSTek Computer               | 15        | 15.46%  |
| Dell                           | 7         | 7.22%   |
| Apple                          | 6         | 6.19%   |
| Hewlett-Packard                | 5         | 5.15%   |
| Fujitsu                        | 4         | 4.12%   |
| PC Engines                     | 3         | 3.09%   |
| Panasonic                      | 3         | 3.09%   |
| Unknown                        | 3         | 3.09%   |
| TUXEDO                         | 2         | 2.06%   |
| Supermicro                     | 2         | 2.06%   |
| Matsushita Electric Industrial | 2         | 2.06%   |
| Intel                          | 2         | 2.06%   |
| Gigabyte Technology            | 2         | 2.06%   |
| Framework                      | 2         | 2.06%   |
| ASRock                         | 2         | 2.06%   |
| Toshiba                        | 1         | 1.03%   |
| Tactus                         | 1         | 1.03%   |
| Sun                            | 1         | 1.03%   |
| Star Labs                      | 1         | 1.03%   |
| Sony                           | 1         | 1.03%   |
| Raspberry Pi Foundation        | 1         | 1.03%   |
| OEGStone                       | 1         | 1.03%   |
| Notebook                       | 1         | 1.03%   |
| HUAWEI                         | 1         | 1.03%   |
| Google                         | 1         | 1.03%   |
| Alienware                      | 1         | 1.03%   |
| Acer                           | 1         | 1.03%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 3         | 3.09%   |
| Fujitsu LIFEBOOK E752                       | 2         | 2.06%   |
| TUXEDO Pulse 15 Gen1                        | 1         | 1.03%   |
| TUXEDO InfinityBook Pro 14 Gen6             | 1         | 1.03%   |
| Toshiba Satellite BE96-F299                 | 1         | 1.03%   |
| Tactus GeoFlex 110                          | 1         | 1.03%   |
| Supermicro X8DTH-i/6/iF/6F                  | 1         | 1.03%   |
| Supermicro Super Server                     | 1         | 1.03%   |
| Sun SUNW,T5140                              | 1         | 1.03%   |
| Star Labs Lite                              | 1         | 1.03%   |
| Sony SVS1312J3EW                            | 1         | 1.03%   |
| RPi Raspberry Pi 400                        | 1         | 1.03%   |
| PC Engines apu4                             | 1         | 1.03%   |
| PC Engines APU2                             | 1         | 1.03%   |
| PC Engines apu1                             | 1         | 1.03%   |
| Panasonic CF-54-1                           | 1         | 1.03%   |
| Panasonic CF-53AAGHYDM                      | 1         | 1.03%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 1.03%   |
| OEGStone W54_55SU1,SUW                      | 1         | 1.03%   |
| Notebook NS5x_NS7xPU                        | 1         | 1.03%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 1.03%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 1.03%   |
| Lenovo ThinkStation D20 415575G             | 1         | 1.03%   |
| Lenovo ThinkPad X270 W10DG 20K5S0TT1N       | 1         | 1.03%   |
| Lenovo ThinkPad X260 20F5S2GM00             | 1         | 1.03%   |
| Lenovo ThinkPad X260 20F5S10W0H             | 1         | 1.03%   |
| Lenovo ThinkPad X230 2325T4T                | 1         | 1.03%   |
| Lenovo ThinkPad X220 429043U                | 1         | 1.03%   |
| Lenovo ThinkPad X200 Tablet 744943U         | 1         | 1.03%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW00QGUS  | 1         | 1.03%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS13H00    | 1         | 1.03%   |
| Lenovo ThinkPad T60 1951A47                 | 1         | 1.03%   |
| Lenovo ThinkPad T480 20L6S13100             | 1         | 1.03%   |
| Lenovo ThinkPad T480 20L5CTO1WW             | 1         | 1.03%   |
| Lenovo ThinkPad T430 2347GZU                | 1         | 1.03%   |
| Lenovo ThinkPad T420s 41742BU               | 1         | 1.03%   |
| Lenovo ThinkPad T410 2537N24                | 1         | 1.03%   |
| Lenovo ThinkPad T410 2518C3U                | 1         | 1.03%   |
| Lenovo ThinkPad T410 2518A37                | 1         | 1.03%   |
| Lenovo ThinkPad L14 Gen 3 21C5CTO1WW        | 1         | 1.03%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad                             | 19        | 19.59%  |
| Fujitsu LIFEBOOK                            | 3         | 3.09%   |
| ASUS PRIME                                  | 3         | 3.09%   |
| Unknown                                     | 3         | 3.09%   |
| Lenovo ThinkCentre                          | 2         | 2.06%   |
| HP ProBook                                  | 2         | 2.06%   |
| Framework Laptop                            | 2         | 2.06%   |
| Dell PowerEdge                              | 2         | 2.06%   |
| Dell OptiPlex                               | 2         | 2.06%   |
| ASRock X570                                 | 2         | 2.06%   |
| TUXEDO Pulse                                | 1         | 1.03%   |
| TUXEDO InfinityBook                         | 1         | 1.03%   |
| Toshiba Satellite                           | 1         | 1.03%   |
| Tactus GeoFlex                              | 1         | 1.03%   |
| Supermicro X8DTH-i                          | 1         | 1.03%   |
| Supermicro Super                            | 1         | 1.03%   |
| Sun SUNW                                    | 1         | 1.03%   |
| Star Labs Lite                              | 1         | 1.03%   |
| Sony SVS1312J3EW                            | 1         | 1.03%   |
| RPi Raspberry                               | 1         | 1.03%   |
| PC Engines apu4                             | 1         | 1.03%   |
| PC Engines APU2                             | 1         | 1.03%   |
| PC Engines apu1                             | 1         | 1.03%   |
| Panasonic CF-54-1                           | 1         | 1.03%   |
| Panasonic CF-53AAGHYDM                      | 1         | 1.03%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 1.03%   |
| OEGStone W54                                | 1         | 1.03%   |
| Notebook NS5x                               | 1         | 1.03%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 1.03%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 1.03%   |
| Lenovo ThinkStation                         | 1         | 1.03%   |
| Lenovo IdeaPad                              | 1         | 1.03%   |
| Lenovo H30-05                               | 1         | 1.03%   |
| Lenovo G50-80                               | 1         | 1.03%   |
| Intel S1200RP                               | 1         | 1.03%   |
| Intel NUC5PPYB                              | 1         | 1.03%   |
| HUAWEI BOM-WXX9                             | 1         | 1.03%   |
| HP Presario                                 | 1         | 1.03%   |
| HP Pavilion                                 | 1         | 1.03%   |
| HP 240                                      | 1         | 1.03%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2022    | 18        | 18.56%  |
| 2021    | 15        | 15.46%  |
| 2018    | 8         | 8.25%   |
| 2019    | 7         | 7.22%   |
| 2012    | 7         | 7.22%   |
| 2010    | 6         | 6.19%   |
| 2015    | 5         | 5.15%   |
| 2014    | 4         | 4.12%   |
| 2013    | 4         | 4.12%   |
| 2011    | 4         | 4.12%   |
| 2020    | 3         | 3.09%   |
| 2016    | 3         | 3.09%   |
| 2006    | 3         | 3.09%   |
| Unknown | 3         | 3.09%   |
| 2023    | 2         | 2.06%   |
| 2017    | 2         | 2.06%   |
| 2009    | 1         | 1.03%   |
| 2007    | 1         | 1.03%   |
| 2002    | 1         | 1.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 58        | 59.79%  |
| Desktop    | 36        | 37.11%  |
| Mini pc    | 1         | 1.03%   |
| All in one | 1         | 1.03%   |
| Server     | 1         | 1.03%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 91        | 93.81%  |
| Yes  | 6         | 6.19%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 23        | 23.47%  |
| 16.01-24.0      | 20        | 20.41%  |
| 4.01-8.0        | 16        | 16.33%  |
| 32.01-64.0      | 10        | 10.2%   |
| 3.01-4.0        | 10        | 10.2%   |
| 64.01-256.0     | 8         | 8.16%   |
| 24.01-32.0      | 3         | 3.06%   |
| 2.01-3.0        | 3         | 3.06%   |
| 1.01-2.0        | 2         | 2.04%   |
| 0.51-1.0        | 2         | 2.04%   |
| More than 256.0 | 1         | 1.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 72        | 74.23%  |
| 0.51-1.0  | 13        | 13.4%   |
| 1.01-2.0  | 5         | 5.15%   |
| 0         | 3         | 3.09%   |
| 3.01-4.0  | 2         | 2.06%   |
| 4.01-8.0  | 1         | 1.03%   |
| 8.01-16.0 | 1         | 1.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 54        | 54.55%  |
| 2      | 22        | 22.22%  |
| 3      | 10        | 10.1%   |
| 0      | 5         | 5.05%   |
| 6      | 3         | 3.03%   |
| 4      | 2         | 2.02%   |
| 14     | 1         | 1.01%   |
| 8      | 1         | 1.01%   |
| 5      | 1         | 1.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 94        | 96.91%  |
| Yes       | 3         | 3.09%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 83        | 85.57%  |
| No        | 14        | 14.43%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 66        | 68.04%  |
| No        | 31        | 31.96%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 52        | 53.61%  |
| No        | 45        | 46.39%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| Canada             | 17        | 17.53%  |
| USA                | 14        | 14.43%  |
| Germany            | 10        | 10.31%  |
| Russia             | 9         | 9.28%   |
| France             | 7         | 7.22%   |
| UK                 | 5         | 5.15%   |
| Spain              | 5         | 5.15%   |
| Italy              | 5         | 5.15%   |
| Australia          | 4         | 4.12%   |
| Poland             | 3         | 3.09%   |
| Netherlands        | 3         | 3.09%   |
| Switzerland        | 2         | 2.06%   |
| Mexico             | 2         | 2.06%   |
| Japan              | 2         | 2.06%   |
| Cyprus             | 2         | 2.06%   |
| The Netherlands    | 1         | 1.03%   |
| Taiwan             | 1         | 1.03%   |
| Sweden             | 1         | 1.03%   |
| Slovakia           | 1         | 1.03%   |
| Egypt              | 1         | 1.03%   |
| Dominican Republic | 1         | 1.03%   |
| Brazil             | 1         | 1.03%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Montreal           | 15        | 15.46%  |
| Moscow             | 4         | 4.12%   |
| Paris              | 3         | 3.09%   |
| Lafayette          | 3         | 3.09%   |
| Fayetteville       | 3         | 3.09%   |
| Amsterdam          | 3         | 3.09%   |
| Sydney             | 2         | 2.06%   |
| Reutov             | 2         | 2.06%   |
| Puebla City        | 2         | 2.06%   |
| Nuremberg          | 2         | 2.06%   |
| Navalcarnero       | 2         | 2.06%   |
| Lübeck            | 2         | 2.06%   |
| Larnaca            | 2         | 2.06%   |
| Cambridge          | 2         | 2.06%   |
| Zurich             | 1         | 1.03%   |
| Yokohama           | 1         | 1.03%   |
| Warsaw             | 1         | 1.03%   |
| Vidnoye            | 1         | 1.03%   |
| Verona             | 1         | 1.03%   |
| Varekil            | 1         | 1.03%   |
| Vanzago            | 1         | 1.03%   |
| Tala               | 1         | 1.03%   |
| Sun Prairie        | 1         | 1.03%   |
| Sao Paulo          | 1         | 1.03%   |
| Santo Domingo Este | 1         | 1.03%   |
| Rhoon              | 1         | 1.03%   |
| Remseck am Neckar  | 1         | 1.03%   |
| Plymouth           | 1         | 1.03%   |
| Pine Mountain Club | 1         | 1.03%   |
| Perth              | 1         | 1.03%   |
| Padova             | 1         | 1.03%   |
| Ozersk             | 1         | 1.03%   |
| Osaka              | 1         | 1.03%   |
| New Taipei         | 1         | 1.03%   |
| Monza              | 1         | 1.03%   |
| Marcq-en-Baroeul   | 1         | 1.03%   |
| Mâcon             | 1         | 1.03%   |
| Los Angeles        | 1         | 1.03%   |
| London             | 1         | 1.03%   |
| Lee's Summit       | 1         | 1.03%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| NVMe                | 33        | 41     | 26.19%  |
| WDC                 | 15        | 20     | 11.9%   |
| Samsung Electronics | 12        | 24     | 9.52%   |
| Seagate             | 9         | 19     | 7.14%   |
| Toshiba             | 6         | 12     | 4.76%   |
| OPENBSD             | 6         | 8      | 4.76%   |
| Kingston            | 6         | 7      | 4.76%   |
| Crucial             | 5         | 5      | 3.97%   |
| Apple               | 4         | 4      | 3.17%   |
| SanDisk             | 3         | 3      | 2.38%   |
| Intel               | 3         | 3      | 2.38%   |
| HGST                | 3         | 3      | 2.38%   |
| Hitachi             | 2         | 2      | 1.59%   |
| USB                 | 1         | 1      | 0.79%   |
| Team                | 1         | 1      | 0.79%   |
| Star Drive          | 1         | 1      | 0.79%   |
| SPCC                | 1         | 1      | 0.79%   |
| SK hynix            | 1         | 1      | 0.79%   |
| SATA3 60            | 1         | 1      | 0.79%   |
| PNY                 | 1         | 1      | 0.79%   |
| Patriot             | 1         | 1      | 0.79%   |
| Memorex             | 1         | 1      | 0.79%   |
| LSI                 | 1         | 1      | 0.79%   |
| KingSpec            | 1         | 1      | 0.79%   |
| KingDian            | 1         | 1      | 0.79%   |
| Intenso             | 1         | 1      | 0.79%   |
| IBM-ESXS            | 1         | 1      | 0.79%   |
| General             | 1         | 1      | 0.79%   |
| Dell                | 1         | 2      | 0.79%   |
| China               | 1         | 1      | 0.79%   |
| Apacer              | 1         | 1      | 0.79%   |
| A-DATA Technology   | 1         | 1      | 0.79%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| NVMe Samsung SSD 980 1TB       | 8         | 5.56%   |
| OPENBSD SR RAID 1 128GB        | 4         | 2.78%   |
| Seagate ST1000LM035-1RK172 1TB | 2         | 1.39%   |
| Samsung SSD 860 EVO M.2 1TB    | 2         | 1.39%   |
| Samsung SSD 860 EVO 1TB        | 2         | 1.39%   |
| Kingston SEDC500M480G 480GB    | 2         | 1.39%   |
| Crucial CT1000BX500SSD1 1TB    | 2         | 1.39%   |
| Apple SSD SM0128G 121GB        | 2         | 1.39%   |
| WDC WD7500BPKX-00HPJT0 752GB   | 1         | 0.69%   |
| WDC WD7500BPKT-75PK4T0 752GB   | 1         | 0.69%   |
| WDC WD7500BPKT-00PK4T0 752GB   | 1         | 0.69%   |
| WDC WD7500AACS-00ZJB0 752GB    | 1         | 0.69%   |
| WDC WD5000LPLX-00ZNTT0 500GB   | 1         | 0.69%   |
| WDC WD4003FFBX-68MU3N0 4TB     | 1         | 0.69%   |
| WDC WD3200BEVE-00A0HT0 320GB   | 1         | 0.69%   |
| WDC WD3200AAKX-001CA0 320GB    | 1         | 0.69%   |
| WDC WD2500BEVS-22UST0 250GB    | 1         | 0.69%   |
| WDC WD20PURX-64P6ZY0 2TB       | 1         | 0.69%   |
| WDC WD20EARX-00PASB0 2TB       | 1         | 0.69%   |
| WDC WD15EARS-00Z5B1 1.5TB      | 1         | 0.69%   |
| WDC WD10JPLX-00MBPT0 1TB       | 1         | 0.69%   |
| WDC WD10JPCX-24UE4T0 1TB       | 1         | 0.69%   |
| WDC WD101KFBX-68R56N0 10TB     | 1         | 0.69%   |
| WDC WD My Passport 25E7 2TB    | 1         | 0.69%   |
| WDC WD Elements 2621 2TB       | 1         | 0.69%   |
| WDC WD Elements 25A2 1TB       | 1         | 0.69%   |
| WDC WD Elements 25A1 4TB       | 1         | 0.69%   |
| WDC WD Elements 1078 1TB       | 1         | 0.69%   |
| USB SanDisk 3.2Gen1 64GB       | 1         | 0.69%   |
| Toshiba MQ04ABF100 1TB         | 1         | 0.69%   |
| Toshiba MQ01ACF032 320GB       | 1         | 0.69%   |
| Toshiba MQ01ABD050 500GB       | 1         | 0.69%   |
| Toshiba MK6475GSX 640GB        | 1         | 0.69%   |
| Toshiba MG08ADA800E 8TB        | 1         | 0.69%   |
| Toshiba DT01ACA100 1TB         | 1         | 0.69%   |
| Team TEAML5Lite3D120G 120GB    | 1         | 0.69%   |
| Star Drive SATA SSD 960GB      | 1         | 0.69%   |
| SPCC Solid State Disk 128GB    | 1         | 0.69%   |
| SK hynix SC311 SATA 128GB      | 1         | 0.69%   |
| Seagate ST9160821A 160GB       | 1         | 0.69%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| NVMe                | 22        | 25     | 30.99%  |
| WDC                 | 15        | 20     | 21.13%  |
| Seagate             | 9         | 19     | 12.68%  |
| Toshiba             | 6         | 12     | 8.45%   |
| OPENBSD             | 6         | 8      | 8.45%   |
| HGST                | 3         | 3      | 4.23%   |
| Samsung Electronics | 2         | 3      | 2.82%   |
| Hitachi             | 2         | 2      | 2.82%   |
| USB                 | 1         | 1      | 1.41%   |
| Memorex             | 1         | 1      | 1.41%   |
| LSI                 | 1         | 1      | 1.41%   |
| IBM-ESXS            | 1         | 1      | 1.41%   |
| General             | 1         | 1      | 1.41%   |
| Dell                | 1         | 2      | 1.41%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| NVMe                | 13        | 15     | 22.81%  |
| Samsung Electronics | 10        | 21     | 17.54%  |
| Kingston            | 6         | 7      | 10.53%  |
| Crucial             | 5         | 5      | 8.77%   |
| Apple               | 4         | 4      | 7.02%   |
| SanDisk             | 3         | 3      | 5.26%   |
| Intel               | 3         | 3      | 5.26%   |
| Team                | 1         | 1      | 1.75%   |
| Star Drive          | 1         | 1      | 1.75%   |
| SPCC                | 1         | 1      | 1.75%   |
| SK hynix            | 1         | 1      | 1.75%   |
| SATA3 60            | 1         | 1      | 1.75%   |
| PNY                 | 1         | 1      | 1.75%   |
| Patriot             | 1         | 1      | 1.75%   |
| KingSpec            | 1         | 1      | 1.75%   |
| KingDian            | 1         | 1      | 1.75%   |
| Intenso             | 1         | 1      | 1.75%   |
| China               | 1         | 1      | 1.75%   |
| Apacer              | 1         | 1      | 1.75%   |
| A-DATA Technology   | 1         | 1      | 1.75%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 57        | 99     | 53.77%  |
| SSD  | 48        | 71     | 45.28%  |
| NVMe | 1         | 1      | 0.94%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 88        | 170    | 98.88%  |
| NVMe | 1         | 1      | 1.12%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 54        | 70     | 45.76%  |
| 0.51-1.0   | 43        | 50     | 36.44%  |
| 1.01-2.0   | 12        | 31     | 10.17%  |
| 4.01-10.0  | 5         | 13     | 4.24%   |
| 3.01-4.0   | 4         | 6      | 3.39%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 32        | 32.32%  |
| 101-250        | 25        | 25.25%  |
| 21-50          | 17        | 17.17%  |
| 51-100         | 9         | 9.09%   |
| More than 3000 | 5         | 5.05%   |
| 1001-2000      | 5         | 5.05%   |
| 501-1000       | 5         | 5.05%   |
| 1-20           | 1         | 1.01%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 71        | 71%     |
| 21-50          | 9         | 9%      |
| 51-100         | 9         | 9%      |
| 251-500        | 4         | 4%      |
| 101-250        | 3         | 3%      |
| More than 3000 | 2         | 2%      |
| 2001-3000      | 1         | 1%      |
| 501-1000       | 1         | 1%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD7500AACS-00ZJB0 752GB       | 1         | 1      | 7.14%   |
| WDC WD2500BEVS-22UST0 250GB       | 1         | 1      | 7.14%   |
| WDC WD15EARS-00Z5B1 1.5TB         | 1         | 1      | 7.14%   |
| Toshiba MQ01ACF032 320GB          | 1         | 3      | 7.14%   |
| Toshiba MQ01ABD050 500GB          | 1         | 1      | 7.14%   |
| Toshiba MK6475GSX 640GB           | 1         | 1      | 7.14%   |
| Toshiba DT01ACA100 1TB            | 1         | 1      | 7.14%   |
| Seagate ST3750640NS 752GB         | 1         | 2      | 7.14%   |
| Seagate ST1000LM035-1RK172 1TB    | 1         | 1      | 7.14%   |
| Samsung Electronics HM160HI 160GB | 1         | 2      | 7.14%   |
| Kingston SMS200S330G 32GB         | 1         | 1      | 7.14%   |
| KingSpec P3-512 512GB             | 1         | 1      | 7.14%   |
| HGST HTS541010A7E630 1TB          | 1         | 1      | 7.14%   |
| A-DATA Technology SP550 480GB     | 1         | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 4         | 6      | 30.77%  |
| WDC                 | 2         | 3      | 15.38%  |
| Seagate             | 2         | 3      | 15.38%  |
| Samsung Electronics | 1         | 2      | 7.69%   |
| Kingston            | 1         | 1      | 7.69%   |
| KingSpec            | 1         | 1      | 7.69%   |
| HGST                | 1         | 1      | 7.69%   |
| A-DATA Technology   | 1         | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 4         | 6      | 40%     |
| WDC                 | 2         | 3      | 20%     |
| Seagate             | 2         | 3      | 20%     |
| Samsung Electronics | 1         | 2      | 10%     |
| HGST                | 1         | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 15     | 76.92%  |
| SSD  | 3         | 3      | 23.08%  |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 55        | 92     | 51.4%   |
| Detected | 39        | 61     | 36.45%  |
| Malfunc  | 13        | 18     | 12.15%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 58        | 47.93%  |
| Samsung Electronics       | 18        | 14.88%  |
| AMD                       | 15        | 12.4%   |
| SanDisk                   | 7         | 5.79%   |
| Broadcom / LSI            | 5         | 4.13%   |
| Micron/Crucial Technology | 3         | 2.48%   |
| Marvell Technology Group  | 3         | 2.48%   |
| ADATA Technology          | 3         | 2.48%   |
| Toshiba                   | 2         | 1.65%   |
| Micron Technology         | 2         | 1.65%   |
| SK hynix                  | 1         | 0.83%   |
| Silicon Motion            | 1         | 0.83%   |
| Seagate Technology        | 1         | 0.83%   |
| Phison Electronics        | 1         | 0.83%   |
| KIOXIA                    | 1         | 0.83%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 9         | 7.26%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 8         | 6.45%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6         | 4.84%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 4.84%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 5         | 4.03%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 3.23%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 3         | 2.42%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 2.42%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 2.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 3         | 2.42%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3         | 2.42%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 2         | 1.61%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 2         | 1.61%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 1.61%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 2         | 1.61%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 2         | 1.61%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 1.61%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 1.61%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 1.61%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 1.61%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 2         | 1.61%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 2         | 1.61%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2         | 1.61%   |
| AMD 500 Series Chipset SATA Controller                                         | 2         | 1.61%   |
| Toshiba XG5 NVMe SSD Controller                                                | 1         | 0.81%   |
| Toshiba BG3 x2 NVMe SSD Controller (DRAM-less)                                 | 1         | 0.81%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 0.81%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 1         | 0.81%   |
| Seagate FireCuda 520/IronWolf 525 SSD                                          | 1         | 0.81%   |
| Sandisk WD Blue SN570 NVMe SSD 2TB                                             | 1         | 0.81%   |
| Sandisk WD Black SN850X NVMe SSD                                               | 1         | 0.81%   |
| Sandisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 1         | 0.81%   |
| Sandisk PC SN735 / WD_BLACK SN750 SE NVMe SSD (DRAM-less)                      | 1         | 0.81%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 1         | 0.81%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                             | 1         | 0.81%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1         | 0.81%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1         | 0.81%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 1         | 0.81%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 1         | 0.81%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 1         | 0.81%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 70        | 59.83%  |
| NVMe | 33        | 28.21%  |
| IDE  | 9         | 7.69%   |
| RAID | 2         | 1.71%   |
| SCSI | 2         | 1.71%   |
| SAS  | 1         | 0.85%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 74        | 76.29%  |
| AMD     | 19        | 19.59%  |
| ARM     | 2         | 2.06%   |
| Unknown | 2         | 2.06%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz                         | 4         | 4.12%   |
| Intel Core i5-3320M CPU @ 2.60GHz                         | 3         | 3.09%   |
| Intel Core i5-2520M CPU @ 2.50GHz                         | 3         | 3.09%   |
| Intel Core i5 CPU M 520 @ 2.40GHz                         | 3         | 3.09%   |
| Intel Core i7-8750H CPU @ 2.20GHz                         | 2         | 2.06%   |
| Intel Core i7-10510U CPU @ 1.80GHz                        | 2         | 2.06%   |
| Intel Core i5-4570 CPU @ 3.20GHz                          | 2         | 2.06%   |
| AMD GX-412TC SOC                                          | 2         | 2.06%   |
|                                                           | 2         | 2.06%   |
| Intel Xeon E-2236 CPU @ 3.40GHz                           | 1         | 1.03%   |
| Intel Xeon CPU X5690 @ 3.47GHz                            | 1         | 1.03%   |
| Intel Xeon CPU X5675 @ 3.07GHz                            | 1         | 1.03%   |
| Intel Xeon CPU X5650 @ 2.67GHz                            | 1         | 1.03%   |
| Intel Xeon CPU E5540 @ 2.53GHz                            | 1         | 1.03%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz                        | 1         | 1.03%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz                       | 1         | 1.03%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz                       | 1         | 1.03%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz                       | 1         | 1.03%   |
| Intel Xeon CPU D-1528 @ 1.90GHz                           | 1         | 1.03%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz                  | 1         | 1.03%   |
| Intel Pentium CPU N3700 @ 1.60GHz                         | 1         | 1.03%   |
| Intel Pentium 4 Mobile CPU 1.60GHz                        | 1         | 1.03%   |
| Intel Genuine processor 800MHz ("GenuineIntel" 686-class) | 1         | 1.03%   |
| Intel Genuine CPU T2300 @ 1.66GHz                         | 1         | 1.03%   |
| Intel Core i9-9900K CPU @ 3.60GHz                         | 1         | 1.03%   |
| Intel Core i7-8650U CPU @ 1.90GHz                         | 1         | 1.03%   |
| Intel Core i7-8550U CPU @ 1.80GHz                         | 1         | 1.03%   |
| Intel Core i7-7700T CPU @ 2.90GHz                         | 1         | 1.03%   |
| Intel Core i7-6700 CPU @ 3.40GHz                          | 1         | 1.03%   |
| Intel Core i7-5500U CPU @ 2.40GHz                         | 1         | 1.03%   |
| Intel Core i7-3520M CPU @ 2.90GHz                         | 1         | 1.03%   |
| Intel Core i7-10750H CPU @ 2.60GHz                        | 1         | 1.03%   |
| Intel Core i7-10700 CPU @ 2.90GHz                         | 1         | 1.03%   |
| Intel Core i5-7360U CPU @ 2.30GHz                         | 1         | 1.03%   |
| Intel Core i5-6500T CPU @ 2.50GHz                         | 1         | 1.03%   |
| Intel Core i5-5300U CPU @ 2.30GHz                         | 1         | 1.03%   |
| Intel Core i5-5257U CPU @ 2.70GHz                         | 1         | 1.03%   |
| Intel Core i5-5250U CPU @ 1.60GHz                         | 1         | 1.03%   |
| Intel Core i5-4278U CPU @ 2.60GHz                         | 1         | 1.03%   |
| Intel Core i5-4260U CPU @ 1.40GHz                         | 1         | 1.03%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 29        | 29.9%   |
| Intel Core i7        | 12        | 12.37%  |
| Intel Xeon           | 10        | 10.31%  |
| Other                | 9         | 9.28%   |
| Intel Celeron        | 4         | 4.12%   |
| AMD Ryzen 9          | 4         | 4.12%   |
| AMD Ryzen 7          | 4         | 4.12%   |
| Intel Core i3        | 3         | 3.09%   |
| AMD Ryzen 5          | 3         | 3.09%   |
| Intel Genuine        | 2         | 2.06%   |
| ARM Cortex           | 2         | 2.06%   |
| AMD GX               | 2         | 2.06%   |
| Intel Pentium Silver | 1         | 1.03%   |
| Intel Pentium 4      | 1         | 1.03%   |
| Intel Pentium        | 1         | 1.03%   |
| Intel Core i9        | 1         | 1.03%   |
| Intel Core Duo       | 1         | 1.03%   |
| Intel Core 2 Duo     | 1         | 1.03%   |
| Intel Atom           | 1         | 1.03%   |
| AMD Turion 64 Mobile | 1         | 1.03%   |
| AMD Ryzen 7 PRO      | 1         | 1.03%   |
| AMD G                | 1         | 1.03%   |
| AMD E1               | 1         | 1.03%   |
| AMD A6               | 1         | 1.03%   |
| AMD A10              | 1         | 1.03%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 32        | 32.99%  |
| 4       | 27        | 27.84%  |
| 6       | 10        | 10.31%  |
| Unknown | 9         | 9.28%   |
| 16      | 6         | 6.19%   |
| 12      | 4         | 4.12%   |
| 8       | 3         | 3.09%   |
| 32      | 2         | 2.06%   |
| 24      | 2         | 2.06%   |
| 1       | 2         | 2.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 88        | 90.72%  |
| Unknown | 7         | 7.22%   |
| 2       | 2         | 2.06%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 56        | 57.73%  |
| 1       | 31        | 31.96%  |
| Unknown | 10        | 10.31%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 11        | 11.34%  |
| Unknown       | 10        | 10.31%  |
| Skylake       | 8         | 8.25%   |
| Zen 3         | 7         | 7.22%   |
| Westmere      | 7         | 7.22%   |
| IvyBridge     | 7         | 7.22%   |
| Haswell       | 7         | 7.22%   |
| SandyBridge   | 5         | 5.15%   |
| Broadwell     | 5         | 5.15%   |
| TigerLake     | 4         | 4.12%   |
| Zen 2         | 3         | 3.09%   |
| Puma          | 3         | 3.09%   |
| P6            | 3         | 3.09%   |
| Goldmont plus | 3         | 3.09%   |
| CometLake     | 3         | 3.09%   |
| Silvermont    | 2         | 2.06%   |
| Piledriver    | 2         | 2.06%   |
| Penryn        | 1         | 1.03%   |
| NetBurst      | 1         | 1.03%   |
| Nehalem       | 1         | 1.03%   |
| K8 Hammer     | 1         | 1.03%   |
| IceLake       | 1         | 1.03%   |
| Bonnell       | 1         | 1.03%   |
| Bobcat        | 1         | 1.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 61        | 61.62%  |
| AMD                        | 23        | 23.23%  |
| Nvidia                     | 7         | 7.07%   |
| Matrox Electronics Systems | 5         | 5.05%   |
| ASPEED Technology          | 3         | 3.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 5.77%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 4.81%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 3.85%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 3.85%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 3.85%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 2.88%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 2.88%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 2.88%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 3         | 2.88%   |
| AMD Barcelo                                                                              | 3         | 2.88%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 2         | 1.92%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 2         | 1.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 1.92%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.92%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.92%   |
| Intel HD Graphics 530                                                                    | 2         | 1.92%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 1.92%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.92%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 1.92%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.92%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 2         | 1.92%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 2         | 1.92%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 2         | 1.92%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.96%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.96%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.96%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                                  | 1         | 0.96%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 0.96%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 0.96%   |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 1         | 0.96%   |
| Matrox Electronics Systems G200eR2                                                       | 1         | 0.96%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 0.96%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 0.96%   |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 0.96%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1         | 0.96%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 0.96%   |
| Intel Iris Plus Graphics 640                                                             | 1         | 0.96%   |
| Intel Iris Graphics 6100                                                                 | 1         | 0.96%   |
| Intel HD Graphics 630                                                                    | 1         | 0.96%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 51        | 52.04%  |
| 1 x AMD        | 19        | 19.39%  |
| Other          | 6         | 6.12%   |
| 2 x Intel      | 5         | 5.1%    |
| Intel + Nvidia | 4         | 4.08%   |
| 1 x Matrox     | 3         | 3.06%   |
| 1 x ASPEED     | 3         | 3.06%   |
| 1 x Nvidia     | 2         | 2.04%   |
| AMD + Matrox   | 2         | 2.04%   |
| 2 x AMD        | 1         | 1.02%   |
| Intel + AMD    | 1         | 1.02%   |
| AMD + Nvidia   | 1         | 1.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 86        | 88.66%  |
| Unknown | 11        | 11.34%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 97        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 9         | 15.25%  |
| BOE                  | 8         | 13.56%  |
| LG Display           | 7         | 11.86%  |
| Samsung Electronics  | 6         | 10.17%  |
| Dell                 | 4         | 6.78%   |
| Philips              | 3         | 5.08%   |
| Lenovo               | 3         | 5.08%   |
| Chimei Innolux       | 3         | 5.08%   |
| Ancor Communications | 2         | 3.39%   |
| ViewSonic            | 1         | 1.69%   |
| TRU                  | 1         | 1.69%   |
| Sceptre Tech         | 1         | 1.69%   |
| Quanta Display       | 1         | 1.69%   |
| PANDA                | 1         | 1.69%   |
| MSI                  | 1         | 1.69%   |
| Eizo                 | 1         | 1.69%   |
| DSC                  | 1         | 1.69%   |
| CSO                  | 1         | 1.69%   |
| BenQ                 | 1         | 1.69%   |
| ASUSTek Computer     | 1         | 1.69%   |
| Apple                | 1         | 1.69%   |
| AOC                  | 1         | 1.69%   |
| Acer                 | 1         | 1.69%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                 | 2         | 3.39%   |
| ViewSonic VG2439 Series VSCD22B 1920x1080 520x290mm 23.4-inch         | 1         | 1.69%   |
| TRU LCD Monitor TRU235C 1366x768 260x140mm 11.6-inch                  | 1         | 1.69%   |
| Sceptre Tech Sceptre C35 SPT0DB7 3440x1440 820x350mm 35.1-inch        | 1         | 1.69%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x260mm 19.1-inch   | 1         | 1.69%   |
| Samsung Electronics S24E650 SAM0CC3 1920x1200 520x320mm 24.0-inch     | 1         | 1.69%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch  | 1         | 1.69%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 310x170mm 13.9-inch  | 1         | 1.69%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch  | 1         | 1.69%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch | 1         | 1.69%   |
| Quanta Display LCD Monitor QDS0020 1280x768 310x180mm 14.1-inch       | 1         | 1.69%   |
| Philips PHL 240B9 PHL0966 1920x1200 520x320mm 24.0-inch               | 1         | 1.69%   |
| PANDA LCD Monitor NCP0046 1920x1080 340x190mm 15.3-inch               | 1         | 1.69%   |
| MSI MP242 MSI30A1 1920x1080 530x300mm 24.0-inch                       | 1         | 1.69%   |
| LG Display LCD Monitor LGD062E 1920x1080 340x190mm 15.3-inch          | 1         | 1.69%   |
| LG Display LCD Monitor LGD058B 2560x1440 310x170mm 13.9-inch          | 1         | 1.69%   |
| LG Display LCD Monitor LGD045E 1366x768 310x170mm 13.9-inch           | 1         | 1.69%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch           | 1         | 1.69%   |
| LG Display LCD Monitor LGD02EB 1366x768 310x170mm 13.9-inch           | 1         | 1.69%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch           | 1         | 1.69%   |
| LG Display LCD Monitor LGD0215 1920x1080 350x190mm 15.7-inch          | 1         | 1.69%   |
| Lenovo LCD Monitor LEN40B1 1600x900 350x190mm 15.7-inch               | 1         | 1.69%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch               | 1         | 1.69%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch               | 1         | 1.69%   |
| Eizo EV2450 ENC2531 1920x1080 530x300mm 24.0-inch                     | 1         | 1.69%   |
| DSC LCD Monitor DSC0001 2200x1650 200x150mm 9.8-inch                  | 1         | 1.69%   |
| Dell U2515H DELD06F 2560x1440 550x310mm 24.9-inch                     | 1         | 1.69%   |
| Dell S2721D DELA19A 2560x1440 590x330mm 26.6-inch                     | 1         | 1.69%   |
| Dell P780 DEL510F 1600x1200 330x240mm 16.1-inch                       | 1         | 1.69%   |
| Dell P1917S DELD093 1280x1024 380x300mm 19.1-inch                     | 1         | 1.69%   |
| CSO LCD Monitor CSO1402 2880x1800 300x190mm 14.0-inch                 | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 340x190mm 15.3-inch       | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 310x170mm 13.9-inch      | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 280x160mm 12.7-inch      | 1         | 1.69%   |
| BOE LCD Monitor BOE096F 1920x1080 250x140mm 11.3-inch                 | 1         | 1.69%   |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                 | 1         | 1.69%   |
| BOE LCD Monitor BOE0900 1920x1080 340x190mm 15.3-inch                 | 1         | 1.69%   |
| BOE LCD Monitor BOE08E2 1920x1080 340x190mm 15.3-inch                 | 1         | 1.69%   |
| BOE LCD Monitor BOE08CD 1366x768 340x190mm 15.3-inch                  | 1         | 1.69%   |
| BOE LCD Monitor BOE08A6 1920x1080 290x170mm 13.2-inch                 | 1         | 1.69%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 24        | 40.68%  |
| 1366x768 (WXGA)   | 11        | 18.64%  |
| 2560x1440 (QHD)   | 4         | 6.78%   |
| 1920x1200 (WUXGA) | 3         | 5.08%   |
| 1600x900 (HD+)    | 3         | 5.08%   |
| 1440x900 (WXGA+)  | 3         | 5.08%   |
| 3840x2160 (4K)    | 2         | 3.39%   |
| 1280x800 (WXGA)   | 2         | 3.39%   |
| 3440x1440         | 1         | 1.69%   |
| 2880x1800         | 1         | 1.69%   |
| 2256x1504         | 1         | 1.69%   |
| 2200x1650         | 1         | 1.69%   |
| 1600x1200         | 1         | 1.69%   |
| 1280x768          | 1         | 1.69%   |
| 1280x1024 (SXGA)  | 1         | 1.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 14        | 23.73%  |
| 13     | 12        | 20.34%  |
| 24     | 8         | 13.56%  |
| 12     | 5         | 8.47%   |
| 14     | 4         | 6.78%   |
| 19     | 3         | 5.08%   |
| 11     | 3         | 5.08%   |
| 23     | 2         | 3.39%   |
| 21     | 2         | 3.39%   |
| 35     | 1         | 1.69%   |
| 31     | 1         | 1.69%   |
| 26     | 1         | 1.69%   |
| 18     | 1         | 1.69%   |
| 16     | 1         | 1.69%   |
| 9      | 1         | 1.69%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 24        | 40.68%  |
| 201-300     | 15        | 25.42%  |
| 501-600     | 11        | 18.64%  |
| 401-500     | 4         | 6.78%   |
| 351-400     | 2         | 3.39%   |
| 801-900     | 1         | 1.69%   |
| 601-700     | 1         | 1.69%   |
| 101-200     | 1         | 1.69%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 44        | 75.86%  |
| 16/10 | 8         | 13.79%  |
| 4/3   | 2         | 3.45%   |
| 3/2   | 2         | 3.45%   |
| 5/4   | 1         | 1.72%   |
| 21/9  | 1         | 1.72%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 14        | 24.14%  |
| 91-100         | 11        | 18.97%  |
| 201-250        | 8         | 13.79%  |
| 61-70          | 5         | 8.62%   |
| 251-300        | 4         | 6.9%    |
| 51-60          | 3         | 5.17%   |
| 151-200        | 3         | 5.17%   |
| 101-110        | 3         | 5.17%   |
| 71-80          | 2         | 3.45%   |
| 351-500        | 2         | 3.45%   |
| 41-50          | 1         | 1.72%   |
| 301-350        | 1         | 1.72%   |
| 121-130        | 1         | 1.72%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 22        | 37.93%  |
| 101-120       | 13        | 22.41%  |
| 51-100        | 13        | 22.41%  |
| 161-240       | 7         | 12.07%  |
| More than 240 | 3         | 5.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 77        | 78.57%  |
| 0     | 17        | 17.35%  |
| 2     | 4         | 4.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 65        | 48.51%  |
| Realtek Semiconductor             | 37        | 27.61%  |
| Qualcomm Atheros                  | 8         | 5.97%   |
| Broadcom                          | 8         | 5.97%   |
| MediaTek                          | 3         | 2.24%   |
| Sierra Wireless                   | 2         | 1.49%   |
| Ericsson Business Mobile Networks | 2         | 1.49%   |
| TP-Link                           | 1         | 0.75%   |
| Qualcomm Atheros Communications   | 1         | 0.75%   |
| Oracle/SUN                        | 1         | 0.75%   |
| Marvell Technology Group          | 1         | 0.75%   |
| Edimax Technology                 | 1         | 0.75%   |
| D-Link System                     | 1         | 0.75%   |
| Aquantia                          | 1         | 0.75%   |
| Apple                             | 1         | 0.75%   |
| AMD                               | 1         | 0.75%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 24        | 13.79%  |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 8         | 4.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 7         | 4.02%   |
| Intel Wireless 8260                                                    | 5         | 2.87%   |
| Intel I210 Gigabit Network Connection                                  | 5         | 2.87%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4         | 2.3%    |
| Intel Wi-Fi 6 AX201                                                    | 4         | 2.3%    |
| Intel Ethernet Connection I219-LM                                      | 4         | 2.3%    |
| Intel 82577LM Gigabit Network Connection                               | 4         | 2.3%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3         | 1.72%   |
| Intel Wireless 8265 / 8275                                             | 3         | 1.72%   |
| Intel Wireless 7265                                                    | 3         | 1.72%   |
| Intel Wi-Fi 6 AX200                                                    | 3         | 1.72%   |
| Intel I350 Gigabit Network Connection                                  | 3         | 1.72%   |
| Intel I211 Gigabit Network Connection                                  | 3         | 1.72%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 3         | 1.72%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 2         | 1.15%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 2         | 1.15%   |
| Intel Wireless 7260                                                    | 2         | 1.15%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 2         | 1.15%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 1.15%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 2         | 1.15%   |
| Intel Centrino Advanced-N 6200                                         | 2         | 1.15%   |
| Intel 82579V Gigabit Network Connection                                | 2         | 1.15%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                            | 2         | 1.15%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                    | 1         | 0.57%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 1         | 0.57%   |
| Sierra Wireless EM7455                                                 | 1         | 0.57%   |
| Sierra Wireless EM7305 Modem                                           | 1         | 0.57%   |
| Realtek USB 2.5GbE Controller                                          | 1         | 0.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 1         | 0.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 1         | 0.57%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter               | 1         | 0.57%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 1         | 0.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 1         | 0.57%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                        | 1         | 0.57%   |
| Realtek RTL8191SEvB Wireless LAN Controller                            | 1         | 0.57%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 1         | 0.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1         | 0.57%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                | 1         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 43        | 60.56%  |
| Realtek Semiconductor           | 8         | 11.27%  |
| Qualcomm Atheros                | 6         | 8.45%   |
| Broadcom                        | 6         | 8.45%   |
| MediaTek                        | 3         | 4.23%   |
| TP-Link                         | 1         | 1.41%   |
| Sierra Wireless                 | 1         | 1.41%   |
| Qualcomm Atheros Communications | 1         | 1.41%   |
| Edimax Technology               | 1         | 1.41%   |
| D-Link System                   | 1         | 1.41%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 8         | 10.53%  |
| Intel Wireless 8260                                            | 5         | 6.58%   |
| Intel Wi-Fi 6 AX201                                            | 4         | 5.26%   |
| Intel Wireless 8265 / 8275                                     | 3         | 3.95%   |
| Intel Wireless 7265                                            | 3         | 3.95%   |
| Intel Wi-Fi 6 AX200                                            | 3         | 3.95%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 3         | 3.95%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 2.63%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 2         | 2.63%   |
| Intel Wireless 7260                                            | 2         | 2.63%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 2         | 2.63%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 2.63%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 2.63%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 2         | 2.63%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 1         | 1.32%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 1.32%   |
| Sierra Wireless EM7455                                         | 1         | 1.32%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.32%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.32%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.32%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 1.32%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1         | 1.32%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 1.32%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 1.32%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1         | 1.32%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 1.32%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter        | 1         | 1.32%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 1.32%   |
| Realtek Realtek Bluetooth 4.2 Adapter                          | 1         | 1.32%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 1.32%   |
| Qualcomm Atheros AR9271 802.11n                                | 1         | 1.32%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 1.32%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.32%   |
| Qualcomm Atheros AR5212 802.11abg NIC                          | 1         | 1.32%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 1.32%   |
| Intel Wireless 3160                                            | 1         | 1.32%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 1         | 1.32%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 1.32%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1         | 1.32%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 1         | 1.32%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 42        | 48.84%  |
| Realtek Semiconductor    | 34        | 39.53%  |
| Qualcomm Atheros         | 3         | 3.49%   |
| Broadcom                 | 3         | 3.49%   |
| Oracle/SUN               | 1         | 1.16%   |
| Marvell Technology Group | 1         | 1.16%   |
| Aquantia                 | 1         | 1.16%   |
| Apple                    | 1         | 1.16%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 24        | 25.81%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 7         | 7.53%   |
| Intel I210 Gigabit Network Connection                                         | 5         | 5.38%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 4         | 4.3%    |
| Intel Ethernet Connection I219-LM                                             | 4         | 4.3%    |
| Intel 82577LM Gigabit Network Connection                                      | 4         | 4.3%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 3         | 3.23%   |
| Intel I350 Gigabit Network Connection                                         | 3         | 3.23%   |
| Intel I211 Gigabit Network Connection                                         | 3         | 3.23%   |
| Intel Ethernet Connection I217-LM                                             | 2         | 2.15%   |
| Intel 82579V Gigabit Network Connection                                       | 2         | 2.15%   |
| Realtek USB 2.5GbE Controller                                                 | 1         | 1.08%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 1.08%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 1.08%   |
| Realtek Killer E2600 GbE Controller                                           | 1         | 1.08%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1         | 1.08%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 1         | 1.08%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1         | 1.08%   |
| Oracle/SUN Multithreaded 10-Gigabit Ethernet Network Controller               | 1         | 1.08%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 1         | 1.08%   |
| Intel Ethernet Controller I226-V                                              | 1         | 1.08%   |
| Intel Ethernet Controller I225-V                                              | 1         | 1.08%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                              | 1         | 1.08%   |
| Intel Ethernet Connection (7) I219-V                                          | 1         | 1.08%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1         | 1.08%   |
| Intel Ethernet Connection (4) I219-V                                          | 1         | 1.08%   |
| Intel Ethernet Connection (4) I219-LM                                         | 1         | 1.08%   |
| Intel Ethernet Connection (3) I218-LM                                         | 1         | 1.08%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1         | 1.08%   |
| Intel Ethernet Connection (14) I219-V                                         | 1         | 1.08%   |
| Intel Ethernet Connection (10) I219-V                                         | 1         | 1.08%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1         | 1.08%   |
| Intel 82576 Gigabit Network Connection                                        | 1         | 1.08%   |
| Intel 82575EB Gigabit Network Connection                                      | 1         | 1.08%   |
| Intel 82573L Gigabit Ethernet Controller                                      | 1         | 1.08%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 1.08%   |
| Intel 82567LM Gigabit Network Connection                                      | 1         | 1.08%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 1         | 1.08%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                             | 1         | 1.08%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                       | 1         | 1.08%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 83        | 53.9%   |
| WiFi     | 66        | 42.86%  |
| Unknown  | 3         | 1.95%   |
| Modem    | 2         | 1.3%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 47        | 55.29%  |
| Ethernet | 38        | 44.71%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 55        | 56.7%   |
| 1     | 28        | 28.87%  |
| 4     | 8         | 8.25%   |
| 3     | 3         | 3.09%   |
| 0     | 2         | 2.06%   |
| 5     | 1         | 1.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 96        | 98.97%  |
| Yes  | 1         | 1.03%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 27        | 50.94%  |
| Broadcom                        | 7         | 13.21%  |
| Foxconn / Hon Hai               | 5         | 9.43%   |
| Apple                           | 5         | 9.43%   |
| Realtek Semiconductor           | 2         | 3.77%   |
| Alps Electric                   | 2         | 3.77%   |
| Taiyo Yuden                     | 1         | 1.89%   |
| Skylight Digital                | 1         | 1.89%   |
| Qualcomm Atheros Communications | 1         | 1.89%   |
| IMC Networks                    | 1         | 1.89%   |
| ASUSTek Computer                | 1         | 1.89%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                        | 11        | 20.75%  |
| Intel AX201 Bluetooth                                     | 6         | 11.32%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)            | 3         | 5.66%   |
| Intel AX200 Bluetooth                                     | 3         | 5.66%   |
| Broadcom BCM2045B (BDC-2.1)                               | 3         | 5.66%   |
| Apple Broadcom Built-in Bluetooth                         | 3         | 5.66%   |
| Intel AX210 Bluetooth                                     | 2         | 3.77%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device  | 2         | 3.77%   |
| Apple Bluetooth Host Controller                           | 2         | 3.77%   |
| Alps Electric UGTZ4 Bluetooth                             | 2         | 3.77%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)                   | 1         | 1.89%   |
| Skylight Digital Realtek Bluetooth Adapter                | 1         | 1.89%   |
| Realtek Bluetooth Adapter                                 | 1         | 1.89%   |
| Realtek Bluetooth 4.0 Adapter                             | 1         | 1.89%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                     | 1         | 1.89%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                  | 1         | 1.89%   |
| Intel Centrino Bluetooth Wireless Transceiver             | 1         | 1.89%   |
| IMC Networks Realtek Bluetooth Adapter                    | 1         | 1.89%   |
| Foxconn / Hon Hai RZ616 Bluetooth Adapter                 | 1         | 1.89%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter              | 1         | 1.89%   |
| Foxconn / Hon Hai Bluetooth 5.2 Adapter [MediaTek MT7922] | 1         | 1.89%   |
| Broadcom BCM20702A0 Bluetooth 4.0                         | 1         | 1.89%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                | 1         | 1.89%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]        | 1         | 1.89%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]          | 1         | 1.89%   |
| ASUS Broadcom Bluetooth 2.1                               | 1         | 1.89%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 66        | 64.71%  |
| AMD                                  | 22        | 21.57%  |
| Nvidia                               | 4         | 3.92%   |
| C-Media Electronics                  | 2         | 1.96%   |
| VIA Technologies                     | 1         | 0.98%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.98%   |
| Texas Instruments                    | 1         | 0.98%   |
| Logitech                             | 1         | 0.98%   |
| JMTek                                | 1         | 0.98%   |
| Generalplus Technology               | 1         | 0.98%   |
| Elgato Systems                       | 1         | 0.98%   |
| Dell                                 | 1         | 0.98%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 8         | 6.5%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7         | 5.69%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 4.88%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 6         | 4.88%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 3.25%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 3.25%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 3.25%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 3.25%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 3.25%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 3.25%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 3.25%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4         | 3.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 2.44%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 2.44%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 2.44%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 2.44%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 3         | 2.44%   |
| AMD FCH Azalia Controller                                                                         | 3         | 2.44%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 1.63%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 2         | 1.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.63%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 1.63%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 1.63%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.63%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 1.63%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 2         | 1.63%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller                       | 1         | 0.81%   |
| Thesycon Systemsoftware & Consulting Topping DX3 Pro Audio Control                                | 1         | 0.81%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.81%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.81%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.81%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.81%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 1         | 0.81%   |
| Logitech HD Webcam C910                                                                           | 1         | 0.81%   |
| JMTek USB PnP Audio Device                                                                        | 1         | 0.81%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.81%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 0.81%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.81%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.81%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1         | 0.81%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7         | 33.33%  |
| Unknown             | 4         | 19.05%  |
| SK hynix            | 3         | 14.29%  |
| Kingston            | 3         | 14.29%  |
| Micron Technology   | 1         | 4.76%   |
| Elpida              | 1         | 4.76%   |
| Corsair             | 1         | 4.76%   |
| Unknown             | 1         | 4.76%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s  | 2         | 8%      |
| Unknown RAM Module 512MB SODIMM SDRAM                  | 1         | 4%      |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s            | 1         | 4%      |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s            | 1         | 4%      |
| Unknown RAM Module 1GB SODIMM DDR2                     | 1         | 4%      |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s | 1         | 4%      |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s | 1         | 4%      |
| SK hynix RAM H9CCNNNBJTMLAR 4GB SODIMM LPDDR3 1867MT/s | 1         | 4%      |
| SK hynix RAM H9CCNNNBJTMLAR 4GB Chip LPDDR3 1867MT/s   | 1         | 4%      |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s  | 1         | 4%      |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 1067MT/s  | 1         | 4%      |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s  | 1         | 4%      |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s  | 1         | 4%      |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s  | 1         | 4%      |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s  | 1         | 4%      |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s | 1         | 4%      |
| Kingston RAM KHYXPX-MIE 8GB SODIMM DDR4 2667MT/s       | 1         | 4%      |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 2400MT/s    | 1         | 4%      |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s      | 1         | 4%      |
| Kingston RAM KF3600C18D4/32GX 32GB DIMM DDR4 3000MT/s  | 1         | 4%      |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s  | 1         | 4%      |
| Elpida RAM EBJ21UE8BDS0-AE-F 2GB SODIMM DDR3 1067MT/s  | 1         | 4%      |
| Corsair RAM CMK64GX5M2B5200C40 32GB DIMM DDR5 4800MT/s | 1         | 4%      |
| Unknown                                                | 1         | 4%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR3   | 9         | 45%     |
| DDR4   | 6         | 30%     |
| SDRAM  | 2         | 10%     |
| LPDDR3 | 1         | 5%      |
| DDR5   | 1         | 5%      |
| DDR2   | 1         | 5%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 17        | 80.95%  |
| DIMM   | 3         | 14.29%  |
| Chip   | 1         | 4.76%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 8         | 34.78%  |
| 8192  | 5         | 21.74%  |
| 2048  | 5         | 21.74%  |
| 32768 | 2         | 8.7%    |
| 16384 | 1         | 4.35%   |
| 1024  | 1         | 4.35%   |
| 512   | 1         | 4.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 3         | 14.29%  |
| 1334    | 3         | 14.29%  |
| 1067    | 3         | 14.29%  |
| Unknown | 3         | 14.29%  |
| 1600    | 2         | 9.52%   |
| 1333    | 2         | 9.52%   |
| 4800    | 1         | 4.76%   |
| 3000    | 1         | 4.76%   |
| 2400    | 1         | 4.76%   |
| 2133    | 1         | 4.76%   |
| 1867    | 1         | 4.76%   |

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
| Chicony Electronics                    | 10        | 26.32%  |
| Bison Electronics                      | 6         | 15.79%  |
| Microdia                               | 4         | 10.53%  |
| IMC Networks                           | 4         | 10.53%  |
| Sunplus Innovation Technology          | 2         | 5.26%   |
| Realtek Semiconductor                  | 2         | 5.26%   |
| Lite-On Technology                     | 2         | 5.26%   |
| Lenovo                                 | 2         | 5.26%   |
| Tripath Technology                     | 1         | 2.63%   |
| Ricoh                                  | 1         | 2.63%   |
| Quanta                                 | 1         | 2.63%   |
| Foxconn / Hon Hai                      | 1         | 2.63%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.63%   |
| Apple                                  | 1         | 2.63%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Bison Integrated Camera                                                    | 5         | 12.5%   |
| Chicony Integrated Camera                                                  | 3         | 7.5%    |
| Microdia Integrated_Webcam_HD                                              | 2         | 5%      |
| Lite-On Integrated Camera                                                  | 2         | 5%      |
| Lenovo Integrated Webcam [R5U877]                                          | 2         | 5%      |
| Bison SunplusIT Integrated Camera                                          | 2         | 5%      |
| Tripath USB Camera                                                         | 1         | 2.5%    |
| Sunplus Integrated_Webcam_FHD                                              | 1         | 2.5%    |
| Sunplus HP TrueVision HD Camera                                            | 1         | 2.5%    |
| Ricoh Laptop_Integrated_Webcam_FHD                                         | 1         | 2.5%    |
| Realtek Laptop Camera                                                      | 1         | 2.5%    |
| Realtek Integrated_Webcam_HD                                               | 1         | 2.5%    |
| Quanta HP Universal Camera                                                 | 1         | 2.5%    |
| Microdia USB 2.0 Camera                                                    | 1         | 2.5%    |
| Microdia USB  Live camera                                                  | 1         | 2.5%    |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 1         | 2.5%    |
| IMC Networks Realtek PC Camera                                             | 1         | 2.5%    |
| IMC Networks Realtek DMFT RGB                                              | 1         | 2.5%    |
| IMC Networks Integrated Camera                                             | 1         | 2.5%    |
| Foxconn / Hon Hai USB2.0 Camera                                            | 1         | 2.5%    |
| Chicony Ltd., Chicony USB 2.0 Camera                                       | 1         | 2.5%    |
| Chicony Lenovo Integrated Camera (0.3MP)                                   | 1         | 2.5%    |
| Chicony Integrated IR Camera                                               | 1         | 2.5%    |
| Chicony Integrated Camera [ThinkPad]                                       | 1         | 2.5%    |
| Chicony FJ Camera                                                          | 1         | 2.5%    |
| Chicony Chicony USB2.0 Camera                                              | 1         | 2.5%    |
| Chicony 2.0M UVC Webcam / CNF7129                                          | 1         | 2.5%    |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 2.5%    |
| Bison Lenovo EasyCamera                                                    | 1         | 2.5%    |
| Apple FaceTime HD Camera (Built-in)                                        | 1         | 2.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 4         | 33.33%  |
| AuthenTec                  | 3         | 25%     |
| Validity Sensors           | 2         | 16.67%  |
| Shenzhen Goodix Technology | 2         | 16.67%  |
| Upek                       | 1         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 16.67%  |
| Shenzhen Goodix Fingerprint Reader                       | 2         | 16.67%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor        | 1         | 8.33%   |
| Validity Sensors VFS 5011 fingerprint sensor             | 1         | 8.33%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 1         | 8.33%   |
| Synaptics UWP WBDI Device                                | 1         | 8.33%   |
| Synaptics Metallica MIS Touch Fingerprint Reader         | 1         | 8.33%   |
| AuthenTec AES2810                                        | 1         | 8.33%   |
| AuthenTec AES2660                                        | 1         | 8.33%   |
| AuthenTec AES2501 Fingerprint Sensor                     | 1         | 8.33%   |

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
| 1     | 50        | 51.55%  |
| 2     | 20        | 20.62%  |
| 0     | 18        | 18.56%  |
| 3     | 4         | 4.12%   |
| 4     | 3         | 3.09%   |
| 5     | 2         | 2.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 58        | 50.43%  |
| Graphics card            | 17        | 14.78%  |
| Net/wireless             | 14        | 12.17%  |
| Storage/ata              | 7         | 6.09%   |
| Firewire controller      | 6         | 5.22%   |
| Sound                    | 5         | 4.35%   |
| Network                  | 3         | 2.61%   |
| Storage                  | 2         | 1.74%   |
| Net/ethernet             | 2         | 1.74%   |
| Modem                    | 1         | 0.87%   |

