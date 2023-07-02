OpenBSD - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for OpenBSD.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/OpenBSD/Desktop/README.md) and [notebooks](/Dist/OpenBSD/Notebook/README.md).

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

Total: 813

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Sony          | VGC-RB41M                   | Desktop     | [95804a1f40](https://bsd-hardware.info/?probe=95804a1f40) | Jun 28, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS (W... | Desktop     | [4d99bc4b63](https://bsd-hardware.info/?probe=4d99bc4b63) | Jun 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS (W... | Desktop     | [8866724f46](https://bsd-hardware.info/?probe=8866724f46) | Jun 27, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [ff83a965d2](https://bsd-hardware.info/?probe=ff83a965d2) | Jun 15, 2023 |
| Lenovo        | ThinkPad T430 2344BZU       | Notebook    | [01df487b47](https://bsd-hardware.info/?probe=01df487b47) | Jun 14, 2023 |
| Gigabyte      | G41MT-S2                    | Desktop     | [355202536f](https://bsd-hardware.info/?probe=355202536f) | Jun 07, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [9f18b1b304](https://bsd-hardware.info/?probe=9f18b1b304) | Jun 06, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [85c18dbbb5](https://bsd-hardware.info/?probe=85c18dbbb5) | Jun 06, 2023 |
| Toshiba       | NB250                       | Notebook    | [62c572e895](https://bsd-hardware.info/?probe=62c572e895) | May 27, 2023 |
| Tactus        | GeoFlex 110                 | Notebook    | [df93ad7e83](https://bsd-hardware.info/?probe=df93ad7e83) | May 27, 2023 |
| Lenovo        | ThinkPad X140e 20BMS03E0... | Notebook    | [580c52399f](https://bsd-hardware.info/?probe=580c52399f) | May 25, 2023 |
| Lenovo        | ThinkPad X140e 20BMS03E0... | Notebook    | [84e3ac62d5](https://bsd-hardware.info/?probe=84e3ac62d5) | May 23, 2023 |
| Unknown       | Apple MacBook Pro (13-in... | Notebook    | [5e25a49c65](https://bsd-hardware.info/?probe=5e25a49c65) | May 20, 2023 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [4c8047dca3](https://bsd-hardware.info/?probe=4c8047dca3) | May 19, 2023 |
| VIA Techno... | VT82C597                    | Desktop     | [d73db58e48](https://bsd-hardware.info/?probe=d73db58e48) | May 19, 2023 |
| Lenovo        | ThinkPad X201 3323BBG       | Notebook    | [7b529b0888](https://bsd-hardware.info/?probe=7b529b0888) | May 17, 2023 |
| HP            | 0A60h                       | Desktop     | [98e9deff3d](https://bsd-hardware.info/?probe=98e9deff3d) | May 16, 2023 |
| Lenovo        | ThinkPad T61 7659AS5        | Notebook    | [7732b2cfa7](https://bsd-hardware.info/?probe=7732b2cfa7) | May 15, 2023 |
| PC Engines    | APU2                        | Desktop     | [62fef2616b](https://bsd-hardware.info/?probe=62fef2616b) | May 15, 2023 |
| Lenovo        | ThinkPad T61 7659AS5        | Notebook    | [b6071c549a](https://bsd-hardware.info/?probe=b6071c549a) | May 15, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [2ce057e389](https://bsd-hardware.info/?probe=2ce057e389) | May 14, 2023 |
| ASUSTek       | M3A78-EMH HDMI              | Desktop     | [b4bf04ac2f](https://bsd-hardware.info/?probe=b4bf04ac2f) | May 13, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | Desktop     | [fa87f4741a](https://bsd-hardware.info/?probe=fa87f4741a) | May 13, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | Desktop     | [bd81294acc](https://bsd-hardware.info/?probe=bd81294acc) | May 13, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [cace71018f](https://bsd-hardware.info/?probe=cace71018f) | May 11, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [4353bb0195](https://bsd-hardware.info/?probe=4353bb0195) | May 09, 2023 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [be83fbb0f2](https://bsd-hardware.info/?probe=be83fbb0f2) | May 09, 2023 |
| Lenovo        | ThinkPad T410 2537N24       | Notebook    | [6cd0f02045](https://bsd-hardware.info/?probe=6cd0f02045) | May 08, 2023 |
| Matsushita... | CF-48V4KNDQM                | Notebook    | [79f10d24d6](https://bsd-hardware.info/?probe=79f10d24d6) | May 07, 2023 |
| ASUSTek       | 1000HE                      | Notebook    | [36214f8bed](https://bsd-hardware.info/?probe=36214f8bed) | May 07, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [d2bd7a8764](https://bsd-hardware.info/?probe=d2bd7a8764) | May 07, 2023 |
| Lenovo        | ThinkPad T500 205663G       | Notebook    | [d706da9400](https://bsd-hardware.info/?probe=d706da9400) | May 06, 2023 |
| Lenovo        | ThinkPad T480s 20L8A00KC... | Notebook    | [44ddee0eec](https://bsd-hardware.info/?probe=44ddee0eec) | May 06, 2023 |
| Matsushita... | CF-51RCVDNLM                | Notebook    | [105a885451](https://bsd-hardware.info/?probe=105a885451) | May 05, 2023 |
| Lenovo        | ThinkPad T420s 41742BU      | Notebook    | [161fe49de4](https://bsd-hardware.info/?probe=161fe49de4) | May 05, 2023 |
| Lenovo        | ThinkPad X230 2325T4T       | Notebook    | [00303b7a59](https://bsd-hardware.info/?probe=00303b7a59) | May 05, 2023 |
| Lenovo        | ThinkPad X220 429043U       | Notebook    | [bb714a4350](https://bsd-hardware.info/?probe=bb714a4350) | May 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [28e76d5531](https://bsd-hardware.info/?probe=28e76d5531) | May 04, 2023 |
| Lenovo        | ThinkPad T430 2347GZU       | Notebook    | [8c3f486dbc](https://bsd-hardware.info/?probe=8c3f486dbc) | May 03, 2023 |
| Panasonic     | CF-52PFPBSFQ                | Notebook    | [e2c3df29b5](https://bsd-hardware.info/?probe=e2c3df29b5) | May 03, 2023 |
| Panasonic     | CF-53AAGHYDM                | Notebook    | [c7daf17edb](https://bsd-hardware.info/?probe=c7daf17edb) | May 02, 2023 |
| Lenovo        | ThinkPad X260 20F5S2GM00    | Notebook    | [c4af168c4a](https://bsd-hardware.info/?probe=c4af168c4a) | May 01, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [cf504f51df](https://bsd-hardware.info/?probe=cf504f51df) | May 01, 2023 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [44ea9fb6ae](https://bsd-hardware.info/?probe=44ea9fb6ae) | Apr 30, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [247810c987](https://bsd-hardware.info/?probe=247810c987) | Apr 24, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | Desktop     | [827308827b](https://bsd-hardware.info/?probe=827308827b) | Apr 24, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [243a9c2f22](https://bsd-hardware.info/?probe=243a9c2f22) | Apr 22, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [c26c1111c6](https://bsd-hardware.info/?probe=c26c1111c6) | Apr 21, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | Desktop     | [a6141b809a](https://bsd-hardware.info/?probe=a6141b809a) | Apr 21, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [0ebba481d1](https://bsd-hardware.info/?probe=0ebba481d1) | Apr 14, 2023 |
| Lenovo        | ThinkPad T440s 20ARA07PL... | Notebook    | [04ddab3620](https://bsd-hardware.info/?probe=04ddab3620) | Apr 14, 2023 |
| Lenovo        | ThinkPad X230 23257EP       | Notebook    | [e94085cd2d](https://bsd-hardware.info/?probe=e94085cd2d) | Apr 12, 2023 |
| ASUSTek       | P10S-I Series               | Desktop     | [5084c2b77f](https://bsd-hardware.info/?probe=5084c2b77f) | Apr 11, 2023 |
| Apple         | MacPro1,1                   | Desktop     | [6843822d8c](https://bsd-hardware.info/?probe=6843822d8c) | Apr 11, 2023 |
| PC Engines    | APU2                        | Desktop     | [cdcdfe6e0b](https://bsd-hardware.info/?probe=cdcdfe6e0b) | Apr 10, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [a149d0b4b5](https://bsd-hardware.info/?probe=a149d0b4b5) | Apr 10, 2023 |
| HP            | Pavilion g6                 | Desktop     | [eeffda8d57](https://bsd-hardware.info/?probe=eeffda8d57) | Apr 09, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [ffbe23b7d8](https://bsd-hardware.info/?probe=ffbe23b7d8) | Apr 09, 2023 |
| Fujitsu       | LIFEBOOK U810               | Notebook    | [3073cd605c](https://bsd-hardware.info/?probe=3073cd605c) | Apr 06, 2023 |
| Fujitsu       | LIFEBOOK U810               | Notebook    | [c7718b4aa3](https://bsd-hardware.info/?probe=c7718b4aa3) | Apr 03, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [640aad419a](https://bsd-hardware.info/?probe=640aad419a) | Apr 02, 2023 |
| Lenovo        | ThinkPad T450s 20BW001KL... | Notebook    | [4f6a7e2739](https://bsd-hardware.info/?probe=4f6a7e2739) | Apr 02, 2023 |
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
| Elpitech      | ET101-A1                    | Desktop     | [0172697883](https://bsd-hardware.info/?probe=0172697883) | Mar 10, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [e70d97f7d6](https://bsd-hardware.info/?probe=e70d97f7d6) | Mar 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [13ac9d6b7e](https://bsd-hardware.info/?probe=13ac9d6b7e) | Mar 01, 2023 |
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
| Lenovo        | ThinkCentre Edge72 34971... | Desktop     | [9c392dab85](https://bsd-hardware.info/?probe=9c392dab85) | Jan 24, 2023 |
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
| Dell          | OptiPlex 3040               | Desktop     | [07abf8e8b2](https://bsd-hardware.info/?probe=07abf8e8b2) | Jan 14, 2023 |
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
| Raspberry ... | Raspberry Pi 4 Model B      | Desktop     | [888de76acd](https://bsd-hardware.info/?probe=888de76acd) | Dec 28, 2022 |
| Star Labs     | Lite                        | Notebook    | [9ad15636dd](https://bsd-hardware.info/?probe=9ad15636dd) | Dec 25, 2022 |
| Gigabyte      | Z390 AORUS ELITE            | Desktop     | [91b7417b84](https://bsd-hardware.info/?probe=91b7417b84) | Dec 24, 2022 |
| Tactus        | GeoFlex 110                 | Notebook    | [955c355b47](https://bsd-hardware.info/?probe=955c355b47) | Dec 23, 2022 |
| Toshiba       | Satellite BE96-F299         | Notebook    | [ca475dd1d0](https://bsd-hardware.info/?probe=ca475dd1d0) | Dec 23, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [b38d32b139](https://bsd-hardware.info/?probe=b38d32b139) | Dec 23, 2022 |
| Lenovo        | ThinkPad T480 20L6S13100    | Notebook    | [67daa912fa](https://bsd-hardware.info/?probe=67daa912fa) | Dec 23, 2022 |
| Raspberry ... | Raspberry Pi 400            | Desktop     | [ee9cac334f](https://bsd-hardware.info/?probe=ee9cac334f) | Dec 21, 2022 |
| Lenovo        | ThinkPad T60 1951A47        | Notebook    | [e254601f07](https://bsd-hardware.info/?probe=e254601f07) | Dec 21, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [af2a9d1a42](https://bsd-hardware.info/?probe=af2a9d1a42) | Dec 20, 2022 |
| MSI           | MS-7922                     | Desktop     | [95dbf4f7a8](https://bsd-hardware.info/?probe=95dbf4f7a8) | Dec 19, 2022 |
| Unknown       | Pine64 RockPro64 v2.1       | Desktop     | [59525051d3](https://bsd-hardware.info/?probe=59525051d3) | Dec 19, 2022 |
| Lenovo        | ThinkPad X200 Tablet 744... | Notebook    | [ea686f63f5](https://bsd-hardware.info/?probe=ea686f63f5) | Dec 19, 2022 |
| Framework     | Laptop                      | Notebook    | [9dcd3592db](https://bsd-hardware.info/?probe=9dcd3592db) | Dec 19, 2022 |
| Lenovo        | ThinkCentre M93p 10A8S0C... | Desktop     | [11d5b82cdd](https://bsd-hardware.info/?probe=11d5b82cdd) | Dec 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [9b5307f44d](https://bsd-hardware.info/?probe=9b5307f44d) | Dec 15, 2022 |
| HP            | ProBook 430 G7              | Notebook    | [0e2278affa](https://bsd-hardware.info/?probe=0e2278affa) | Dec 14, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [15b2363325](https://bsd-hardware.info/?probe=15b2363325) | Dec 05, 2022 |
| Acer          | Aspire XC-105               | Desktop     | [250b12c3f2](https://bsd-hardware.info/?probe=250b12c3f2) | Dec 05, 2022 |
| Panasonic     | CF-54-1                     | Notebook    | [0c5820ea0d](https://bsd-hardware.info/?probe=0c5820ea0d) | Dec 01, 2022 |
| ASRock        | X570 Pro4                   | Desktop     | [b23f59a068](https://bsd-hardware.info/?probe=b23f59a068) | Nov 27, 2022 |
| ASUSTek       | P11C-X Series               | Desktop     | [6860cd72f8](https://bsd-hardware.info/?probe=6860cd72f8) | Nov 26, 2022 |
| ASUSTek       | P11C-X Series               | Desktop     | [cfdb06e761](https://bsd-hardware.info/?probe=cfdb06e761) | Nov 26, 2022 |
| Dell          | Vostro 3501                 | Notebook    | [61f8a35700](https://bsd-hardware.info/?probe=61f8a35700) | Nov 25, 2022 |
| Unknown       | Unknown                     | Desktop     | [0760ed34c3](https://bsd-hardware.info/?probe=0760ed34c3) | Nov 21, 2022 |
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
| Lenovo        | ThinkPad T420s 4174DL7      | Notebook    | [82d774e711](https://bsd-hardware.info/?probe=82d774e711) | Oct 26, 2022 |
| Lenovo        | ThinkPad T410 2537N24       | Notebook    | [b7a4ee06a6](https://bsd-hardware.info/?probe=b7a4ee06a6) | Oct 26, 2022 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [06e6c07e90](https://bsd-hardware.info/?probe=06e6c07e90) | Oct 25, 2022 |
| PC Engines    | APU2                        | Desktop     | [d52e3d0ce3](https://bsd-hardware.info/?probe=d52e3d0ce3) | Oct 25, 2022 |
| Lenovo        | ThinkPad T430 2347GZU       | Notebook    | [f2236f17ee](https://bsd-hardware.info/?probe=f2236f17ee) | Oct 25, 2022 |
| ASUSTek       | 1000HE                      | Notebook    | [c4bbcf9537](https://bsd-hardware.info/?probe=c4bbcf9537) | Oct 24, 2022 |
| ASUSTek       | K53TA                       | Notebook    | [521283b723](https://bsd-hardware.info/?probe=521283b723) | Oct 22, 2022 |
| Alienware     | m15                         | Notebook    | [3304a767ba](https://bsd-hardware.info/?probe=3304a767ba) | Oct 22, 2022 |
| ASUSTek       | P8Z68-V GEN3                | Desktop     | [d7b32200a5](https://bsd-hardware.info/?probe=d7b32200a5) | Oct 22, 2022 |
| PC Engines    | APU2                        | Desktop     | [cf1abf5e46](https://bsd-hardware.info/?probe=cf1abf5e46) | Oct 21, 2022 |
| Supermicro    | X8DTH-i/6/iF/6F             | Desktop     | [12f7ac40ac](https://bsd-hardware.info/?probe=12f7ac40ac) | Oct 21, 2022 |
| Unknown       | Unknown                     | Desktop     | [d5586487b4](https://bsd-hardware.info/?probe=d5586487b4) | Oct 21, 2022 |
| ASUSTek       | P10S-I Series               | Desktop     | [ceb58e75b8](https://bsd-hardware.info/?probe=ceb58e75b8) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [7ecffc1ca3](https://bsd-hardware.info/?probe=7ecffc1ca3) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [eb6eda641d](https://bsd-hardware.info/?probe=eb6eda641d) | Oct 20, 2022 |
| ASRock        | Q1900M                      | Desktop     | [7d0380e2d0](https://bsd-hardware.info/?probe=7d0380e2d0) | Oct 15, 2022 |
| HP            | 260 G3 DM                   | Desktop     | [3ad5292d71](https://bsd-hardware.info/?probe=3ad5292d71) | Oct 13, 2022 |
| HP            | Compaq nw8440 (RND39ET)     | Desktop     | [55bef385e3](https://bsd-hardware.info/?probe=55bef385e3) | Oct 13, 2022 |
| Clevo         | R130T                       | Desktop     | [6f8a6bf77c](https://bsd-hardware.info/?probe=6f8a6bf77c) | Oct 10, 2022 |
| Soekris En... | net6501                     | Desktop     | [1cb23f6bda](https://bsd-hardware.info/?probe=1cb23f6bda) | Oct 08, 2022 |
| Soekris En... | net6501                     | Desktop     | [03ee772b1f](https://bsd-hardware.info/?probe=03ee772b1f) | Oct 08, 2022 |
| Lenovo        | ThinkPad T60 2613CTO        | Desktop     | [cb649b809c](https://bsd-hardware.info/?probe=cb649b809c) | Oct 04, 2022 |
| Dell          | Latitude E6420              | Notebook    | [07b078fdef](https://bsd-hardware.info/?probe=07b078fdef) | Oct 04, 2022 |
| Lenovo        | ThinkPad T410 2518C3U       | Notebook    | [627206d154](https://bsd-hardware.info/?probe=627206d154) | Oct 04, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Desktop     | [e001150f93](https://bsd-hardware.info/?probe=e001150f93) | Oct 03, 2022 |
| Tactus        | GeoFlex 110                 | Notebook    | [0b93b5f915](https://bsd-hardware.info/?probe=0b93b5f915) | Sep 28, 2022 |
| ASUSTek       | All Series                  | Desktop     | [ab3b339cf0](https://bsd-hardware.info/?probe=ab3b339cf0) | Sep 24, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [1a89d78fa4](https://bsd-hardware.info/?probe=1a89d78fa4) | Sep 22, 2022 |
| Toshiba       | Satellite BE96-F299         | Notebook    | [15b93c9f4b](https://bsd-hardware.info/?probe=15b93c9f4b) | Sep 21, 2022 |
| Toshiba       | Satellite BE96-F299         | Notebook    | [9beae1547d](https://bsd-hardware.info/?probe=9beae1547d) | Sep 21, 2022 |
| Gigabyte      | H81M-S1                     | Desktop     | [fe9eecb935](https://bsd-hardware.info/?probe=fe9eecb935) | Sep 18, 2022 |
| CncTion       | N5105-4L                    | Desktop     | [2a34dc3fe0](https://bsd-hardware.info/?probe=2a34dc3fe0) | Sep 05, 2022 |
| Dell          | PowerEdge R620              | Desktop     | [66db9eb745](https://bsd-hardware.info/?probe=66db9eb745) | Aug 25, 2022 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [21fed03fa2](https://bsd-hardware.info/?probe=21fed03fa2) | Aug 24, 2022 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [48210e4d2a](https://bsd-hardware.info/?probe=48210e4d2a) | Aug 24, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [7576399c3c](https://bsd-hardware.info/?probe=7576399c3c) | Aug 20, 2022 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | Notebook    | [2e7d570822](https://bsd-hardware.info/?probe=2e7d570822) | Aug 20, 2022 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | Notebook    | [7afa139f4f](https://bsd-hardware.info/?probe=7afa139f4f) | Aug 20, 2022 |
| Fujitsu       | PRIMERGY RX200 S6           | Desktop     | [9267873961](https://bsd-hardware.info/?probe=9267873961) | Aug 13, 2022 |
| Alienware     | m15 R4                      | Notebook    | [769c5c43f3](https://bsd-hardware.info/?probe=769c5c43f3) | Aug 13, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [4ba15a31d9](https://bsd-hardware.info/?probe=4ba15a31d9) | Aug 10, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [1d342196fb](https://bsd-hardware.info/?probe=1d342196fb) | Aug 08, 2022 |
| Biostar       | TA880GU3+                   | Desktop     | [8b0c8541b3](https://bsd-hardware.info/?probe=8b0c8541b3) | Aug 06, 2022 |
| Intel         | NUC5PPYB H76558-102         | Mini pc     | [9124f0eb45](https://bsd-hardware.info/?probe=9124f0eb45) | Aug 05, 2022 |
| ASUSTek       | P5QL-ASUS-SE                | Desktop     | [f2836f4a6c](https://bsd-hardware.info/?probe=f2836f4a6c) | Aug 01, 2022 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [77f61a8711](https://bsd-hardware.info/?probe=77f61a8711) | Aug 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X545... | Notebook    | [bf5cea4ab5](https://bsd-hardware.info/?probe=bf5cea4ab5) | Jul 30, 2022 |
| Intel         | NUC5PPYB H76558-102         | Mini pc     | [d9a4a9745d](https://bsd-hardware.info/?probe=d9a4a9745d) | Jul 28, 2022 |
| Gigabyte      | H87-HD3                     | Desktop     | [e6a9b0dd8b](https://bsd-hardware.info/?probe=e6a9b0dd8b) | Jul 25, 2022 |
| Dell          | 0G7W4R A00                  | Server      | [4aa8b5487a](https://bsd-hardware.info/?probe=4aa8b5487a) | Jul 20, 2022 |
| Lenovo        | ThinkPad X200 7458NP9       | Notebook    | [4192abf903](https://bsd-hardware.info/?probe=4192abf903) | Jul 20, 2022 |
| ASUSTek       | M4A785TD-M EVO              | Desktop     | [def87ec245](https://bsd-hardware.info/?probe=def87ec245) | Jul 18, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [7b6faf5301](https://bsd-hardware.info/?probe=7b6faf5301) | Jul 14, 2022 |
| ASUSTek       | X751LB                      | Notebook    | [5c2ef28301](https://bsd-hardware.info/?probe=5c2ef28301) | Jul 12, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [ba243fa7c4](https://bsd-hardware.info/?probe=ba243fa7c4) | Jul 09, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [f98a69101e](https://bsd-hardware.info/?probe=f98a69101e) | Jul 08, 2022 |
| Lenovo        | IdeaPad S12 20021,2959      | Notebook    | [c1bf998d6a](https://bsd-hardware.info/?probe=c1bf998d6a) | Jul 07, 2022 |
| Dell          | OptiPlex 580                | Desktop     | [620888d077](https://bsd-hardware.info/?probe=620888d077) | Jul 02, 2022 |
| Dell          | Inspiron 5515               | Notebook    | [dca437b993](https://bsd-hardware.info/?probe=dca437b993) | Jul 01, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [77acc9f5cf](https://bsd-hardware.info/?probe=77acc9f5cf) | Jul 01, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [ffa0086c70](https://bsd-hardware.info/?probe=ffa0086c70) | Jul 01, 2022 |
| Gigabyte      | G41MT-S2                    | Desktop     | [0563158740](https://bsd-hardware.info/?probe=0563158740) | Jun 28, 2022 |
| ASUSTek       | K53TA                       | Notebook    | [6ce39c5e61](https://bsd-hardware.info/?probe=6ce39c5e61) | Jun 27, 2022 |
| MSI           | MS-7C02                     | Desktop     | [65265eea62](https://bsd-hardware.info/?probe=65265eea62) | Jun 20, 2022 |
| Lenovo        | ThinkPad T530 24292VG       | Desktop     | [6f744019ce](https://bsd-hardware.info/?probe=6f744019ce) | Jun 19, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [25d5a77b59](https://bsd-hardware.info/?probe=25d5a77b59) | Jun 17, 2022 |
| Apple         | MacPro4,1                   | Desktop     | [65380f3847](https://bsd-hardware.info/?probe=65380f3847) | Jun 06, 2022 |
| Lenovo        | ThinkPad L530 24812TG       | Notebook    | [5b66684c4a](https://bsd-hardware.info/?probe=5b66684c4a) | Jun 05, 2022 |
| Lenovo        | ThinkPad Yoga 260 20FES1... | Notebook    | [73ab89b8f0](https://bsd-hardware.info/?probe=73ab89b8f0) | Jun 05, 2022 |
| Lenovo        | ThinkPad Yoga 260 20FES1... | Notebook    | [637f87f44e](https://bsd-hardware.info/?probe=637f87f44e) | Jun 05, 2022 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [8099e7abaf](https://bsd-hardware.info/?probe=8099e7abaf) | Jun 03, 2022 |
| MSI           | MS-6788                     | Desktop     | [f750cb83e3](https://bsd-hardware.info/?probe=f750cb83e3) | May 31, 2022 |
| Apple         | MacBookPro5,3               | Notebook    | [3b03bdf595](https://bsd-hardware.info/?probe=3b03bdf595) | May 29, 2022 |
| Unknown       | Raspberry Pi 4 Model B R... | Desktop     | [ade09344b8](https://bsd-hardware.info/?probe=ade09344b8) | May 26, 2022 |
| Unknown       | Raspberry Pi 4 Model B R... | Desktop     | [cc37ea1b7d](https://bsd-hardware.info/?probe=cc37ea1b7d) | May 26, 2022 |
| Unknown       | Raspberry Pi 4 Model B R... | Desktop     | [abacee12a9](https://bsd-hardware.info/?probe=abacee12a9) | May 26, 2022 |
| Unknown       | Raspberry Pi 3 Model B P... | Desktop     | [21fa41e4c1](https://bsd-hardware.info/?probe=21fa41e4c1) | May 26, 2022 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [1937e77b97](https://bsd-hardware.info/?probe=1937e77b97) | May 22, 2022 |
| Biostar       | G31-M7 TE                   | Desktop     | [5c7af4b143](https://bsd-hardware.info/?probe=5c7af4b143) | May 21, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [ce5ddde5ad](https://bsd-hardware.info/?probe=ce5ddde5ad) | May 18, 2022 |
| MSI           | MS-7C82                     | Desktop     | [2ad883afec](https://bsd-hardware.info/?probe=2ad883afec) | May 15, 2022 |
| Lenovo        | ThinkPad X250 20CLS4WV08    | Notebook    | [0419c52079](https://bsd-hardware.info/?probe=0419c52079) | May 11, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [9f6b4f114d](https://bsd-hardware.info/?probe=9f6b4f114d) | May 11, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [64600e1c24](https://bsd-hardware.info/?probe=64600e1c24) | May 11, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [49d1cd3009](https://bsd-hardware.info/?probe=49d1cd3009) | May 10, 2022 |
| Unknown       | Raspberry Pi 4 Model B R... | Desktop     | [154799d7fa](https://bsd-hardware.info/?probe=154799d7fa) | May 08, 2022 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [3e60a82218](https://bsd-hardware.info/?probe=3e60a82218) | May 06, 2022 |
| ASUSTek       | 1000HE                      | Notebook    | [a6393754b4](https://bsd-hardware.info/?probe=a6393754b4) | May 05, 2022 |
| Matsushita... | CF-48V4KNDQM                | Notebook    | [774cab5326](https://bsd-hardware.info/?probe=774cab5326) | May 03, 2022 |
| Matsushita... | CF-51RCVDNLM                | Notebook    | [4b1abdd507](https://bsd-hardware.info/?probe=4b1abdd507) | May 03, 2022 |
| Lenovo        | ThinkPad T410 2537N24       | Notebook    | [2884106c6b](https://bsd-hardware.info/?probe=2884106c6b) | May 03, 2022 |
| Lenovo        | ThinkPad T430 2347GZU       | Notebook    | [00ba6ca9f8](https://bsd-hardware.info/?probe=00ba6ca9f8) | May 03, 2022 |
| Intel         | Q3XXG4-P                    | Desktop     | [ed04988a23](https://bsd-hardware.info/?probe=ed04988a23) | May 03, 2022 |
| Lenovo        | ThinkPad T420s 41742BU      | Notebook    | [6b77fe651f](https://bsd-hardware.info/?probe=6b77fe651f) | May 03, 2022 |
| Lenovo        | ThinkPad X220 429043U       | Notebook    | [f3c30a6190](https://bsd-hardware.info/?probe=f3c30a6190) | May 02, 2022 |
| Panasonic     | CF-53AAGHYDM                | Notebook    | [abd8754907](https://bsd-hardware.info/?probe=abd8754907) | May 01, 2022 |
| Panasonic     | CF-52PFPBSFQ                | Notebook    | [1ce63e2214](https://bsd-hardware.info/?probe=1ce63e2214) | Apr 29, 2022 |
| MSI           | MS-7C37                     | Desktop     | [aaab7cf22a](https://bsd-hardware.info/?probe=aaab7cf22a) | Apr 28, 2022 |
| MSI           | Modern 14 B11MOL            | Notebook    | [9a61443be9](https://bsd-hardware.info/?probe=9a61443be9) | Apr 25, 2022 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [12cc40cc60](https://bsd-hardware.info/?probe=12cc40cc60) | Apr 23, 2022 |
| PC Engines    | APU2                        | Desktop     | [04a6549c99](https://bsd-hardware.info/?probe=04a6549c99) | Apr 23, 2022 |
| Apple         | PowerMac10,1                | Desktop     | [e054e605fa](https://bsd-hardware.info/?probe=e054e605fa) | Apr 23, 2022 |
| Intel         | DH67BL                      | Desktop     | [3c3c9e12da](https://bsd-hardware.info/?probe=3c3c9e12da) | Apr 22, 2022 |
| KOHJINSHA     | SH series                   | Desktop     | [3136a0ca03](https://bsd-hardware.info/?probe=3136a0ca03) | Apr 22, 2022 |
| Lenovo        | ThinkPad X240 20ALA0AHRT    | Desktop     | [062a08c811](https://bsd-hardware.info/?probe=062a08c811) | Apr 22, 2022 |
| DEXP          | NAVIS P100                  | Notebook    | [a9c8814bf8](https://bsd-hardware.info/?probe=a9c8814bf8) | Apr 22, 2022 |
| Sony          | VPCL22Z1R                   | Desktop     | [f199d57905](https://bsd-hardware.info/?probe=f199d57905) | Apr 22, 2022 |
| Lenovo        | ThinkPad X121e 3053A52      | Notebook    | [68d0bf2a99](https://bsd-hardware.info/?probe=68d0bf2a99) | Apr 22, 2022 |
| Samsung       | DP700A3D-X01RU SEC_SW_RE... | All in one  | [22febd212f](https://bsd-hardware.info/?probe=22febd212f) | Apr 22, 2022 |
| ASUSTek       | Z170-K                      | Desktop     | [b16705bbbd](https://bsd-hardware.info/?probe=b16705bbbd) | Apr 22, 2022 |
| ASUSTek       | P10S-I Series               | Desktop     | [aca13dba36](https://bsd-hardware.info/?probe=aca13dba36) | Apr 22, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [b4a6761ab3](https://bsd-hardware.info/?probe=b4a6761ab3) | Apr 21, 2022 |
| Dell          | G5 5090                     | Desktop     | [8b24170852](https://bsd-hardware.info/?probe=8b24170852) | Apr 17, 2022 |
| Lenovo        | ThinkPad X220 4291QT1       | Notebook    | [f7aa3576ae](https://bsd-hardware.info/?probe=f7aa3576ae) | Apr 13, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [0e836941e0](https://bsd-hardware.info/?probe=0e836941e0) | Apr 11, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [41d62dde7d](https://bsd-hardware.info/?probe=41d62dde7d) | Apr 10, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [c5f7b5499a](https://bsd-hardware.info/?probe=c5f7b5499a) | Apr 10, 2022 |
| PC Engines    | apu4                        | Desktop     | [62df504364](https://bsd-hardware.info/?probe=62df504364) | Apr 09, 2022 |
| Unknown       | Raspberry Pi 3 Model B R... | Desktop     | [040f37113c](https://bsd-hardware.info/?probe=040f37113c) | Apr 06, 2022 |
| Lenovo        | ThinkPad X260 20F5S08Q00    | Notebook    | [1d1db3eab4](https://bsd-hardware.info/?probe=1d1db3eab4) | Apr 03, 2022 |
| Intel         | DCP847SKE                   | Desktop     | [a79e298be3](https://bsd-hardware.info/?probe=a79e298be3) | Apr 03, 2022 |
| IBM           | 2658MNG                     | Notebook    | [e3a5a587fa](https://bsd-hardware.info/?probe=e3a5a587fa) | Mar 28, 2022 |
| Lenovo        | ThinkPad X200 745969G       | Notebook    | [086a58a68f](https://bsd-hardware.info/?probe=086a58a68f) | Mar 24, 2022 |
| Lenovo        | ThinkCentre M93p 10AAS25... | Desktop     | [32d27b9404](https://bsd-hardware.info/?probe=32d27b9404) | Mar 19, 2022 |
| Lenovo        | ThinkCentre M93p 10AAS25... | Desktop     | [7361628ed9](https://bsd-hardware.info/?probe=7361628ed9) | Mar 19, 2022 |
| Lenovo        | ThinkPad X200 745969G       | Notebook    | [e973d1e806](https://bsd-hardware.info/?probe=e973d1e806) | Mar 18, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [ed0add65a3](https://bsd-hardware.info/?probe=ed0add65a3) | Mar 14, 2022 |
| HP            | EliteBook 2530p             | Notebook    | [e5c8017afb](https://bsd-hardware.info/?probe=e5c8017afb) | Mar 12, 2022 |
| Lenovo        | Yoga 330-11IGM 81A6         | Notebook    | [621ae0501b](https://bsd-hardware.info/?probe=621ae0501b) | Mar 10, 2022 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [3b77055bd4](https://bsd-hardware.info/?probe=3b77055bd4) | Mar 07, 2022 |
| Unknown       | LeMaker Banana Pi           | Desktop     | [37e7d1912b](https://bsd-hardware.info/?probe=37e7d1912b) | Mar 05, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [4bc5573cf5](https://bsd-hardware.info/?probe=4bc5573cf5) | Mar 02, 2022 |
| Intel         | D945GSEJT                   | Desktop     | [bf6a38dfcb](https://bsd-hardware.info/?probe=bf6a38dfcb) | Feb 26, 2022 |
| Dell          | OptiPlex 755                | Desktop     | [9ddfe010c4](https://bsd-hardware.info/?probe=9ddfe010c4) | Feb 24, 2022 |
| Lenovo        | ThinkPad X200 745969G       | Notebook    | [a4341268d0](https://bsd-hardware.info/?probe=a4341268d0) | Feb 23, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [11bed21472](https://bsd-hardware.info/?probe=11bed21472) | Feb 21, 2022 |
| Acer          | Aspire A114-33              | Notebook    | [62f4e0a060](https://bsd-hardware.info/?probe=62f4e0a060) | Feb 21, 2022 |
| Acer          | Aspire A514-52              | Notebook    | [60f9683fb1](https://bsd-hardware.info/?probe=60f9683fb1) | Feb 21, 2022 |
| Gigabyte      | X58A-UD5                    | Desktop     | [58d57520c1](https://bsd-hardware.info/?probe=58d57520c1) | Feb 20, 2022 |
| Unknown       | Raspberry Pi 4 Model B R... | Desktop     | [04e528ca9f](https://bsd-hardware.info/?probe=04e528ca9f) | Feb 19, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [07546b5925](https://bsd-hardware.info/?probe=07546b5925) | Feb 18, 2022 |
| Lenovo        | ThinkPad X250 20CLS59400    | Notebook    | [92333ad60b](https://bsd-hardware.info/?probe=92333ad60b) | Feb 17, 2022 |
| MSI           | MS-7253                     | Desktop     | [c4e971ea82](https://bsd-hardware.info/?probe=c4e971ea82) | Feb 16, 2022 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [1e8904f4fc](https://bsd-hardware.info/?probe=1e8904f4fc) | Feb 15, 2022 |
| Raspberry ... | Raspberry Pi 400            | Desktop     | [dd56609ceb](https://bsd-hardware.info/?probe=dd56609ceb) | Feb 14, 2022 |
| Lenovo        | ThinkPad T400 2768W3A       | Desktop     | [4691fdb146](https://bsd-hardware.info/?probe=4691fdb146) | Feb 13, 2022 |
| Lenovo        | ThinkPad T400 2768W3A       | Desktop     | [97788dfb1a](https://bsd-hardware.info/?probe=97788dfb1a) | Feb 13, 2022 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [b77b926f9b](https://bsd-hardware.info/?probe=b77b926f9b) | Feb 13, 2022 |
| Lenovo        | ThinkPad X240 20AMS2QD0C    | Notebook    | [ae597455a4](https://bsd-hardware.info/?probe=ae597455a4) | Feb 13, 2022 |
| Lenovo        | ThinkPad X200 745969G       | Notebook    | [c024d383e7](https://bsd-hardware.info/?probe=c024d383e7) | Feb 13, 2022 |
| Unknown       | LeMaker Banana Pi           | Desktop     | [77413a3d9d](https://bsd-hardware.info/?probe=77413a3d9d) | Feb 12, 2022 |
| HP            | t620 Quad Core TC           | Desktop     | [965ced51e6](https://bsd-hardware.info/?probe=965ced51e6) | Feb 12, 2022 |
| MSI           | MS-7C96                     | Desktop     | [c08331ad58](https://bsd-hardware.info/?probe=c08331ad58) | Feb 06, 2022 |
| Lenovo        | ThinkPad X200 745969G       | Notebook    | [f107f7c1b1](https://bsd-hardware.info/?probe=f107f7c1b1) | Feb 06, 2022 |
| Lenovo        | ThinkPad X200 745969G       | Notebook    | [f8476c0ea7](https://bsd-hardware.info/?probe=f8476c0ea7) | Feb 01, 2022 |
| Raspberry ... | Raspberry Pi 400            | Desktop     | [b35265f8f4](https://bsd-hardware.info/?probe=b35265f8f4) | Jan 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [2d65265b52](https://bsd-hardware.info/?probe=2d65265b52) | Jan 29, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [9c73c01062](https://bsd-hardware.info/?probe=9c73c01062) | Jan 28, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [208819a667](https://bsd-hardware.info/?probe=208819a667) | Jan 27, 2022 |
| WYSE          | D CLASS                     | Desktop     | [5f31ae866c](https://bsd-hardware.info/?probe=5f31ae866c) | Jan 24, 2022 |
| ASRock        | X570 Pro4                   | Desktop     | [d77aae8064](https://bsd-hardware.info/?probe=d77aae8064) | Jan 23, 2022 |
| MSI           | MS-7C56                     | Desktop     | [962ac1c7b0](https://bsd-hardware.info/?probe=962ac1c7b0) | Jan 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [c36023a724](https://bsd-hardware.info/?probe=c36023a724) | Jan 17, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [26ccd8e3c5](https://bsd-hardware.info/?probe=26ccd8e3c5) | Jan 16, 2022 |
| HP            | EliteBook 2530p             | Notebook    | [42eb986a58](https://bsd-hardware.info/?probe=42eb986a58) | Jan 11, 2022 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [e0e7b21668](https://bsd-hardware.info/?probe=e0e7b21668) | Jan 09, 2022 |
| Framework     | Laptop                      | Notebook    | [324f0fdebc](https://bsd-hardware.info/?probe=324f0fdebc) | Jan 05, 2022 |
| Framework     | Laptop                      | Notebook    | [ba81f48282](https://bsd-hardware.info/?probe=ba81f48282) | Jan 05, 2022 |
| Dell          | Latitude 3400               | Notebook    | [41bf32aff1](https://bsd-hardware.info/?probe=41bf32aff1) | Jan 02, 2022 |
| Lenovo        | ThinkPad T480 20L5S1S000    | Notebook    | [0925acabe4](https://bsd-hardware.info/?probe=0925acabe4) | Dec 31, 2021 |
| Unknown       | TI AM335x BeagleBone Bla... | Desktop     | [14d6cfb7a4](https://bsd-hardware.info/?probe=14d6cfb7a4) | Dec 27, 2021 |
| Unknown       | TI AM335x BeagleBone Bla... | Desktop     | [ce75fa56bd](https://bsd-hardware.info/?probe=ce75fa56bd) | Dec 27, 2021 |
| Unknown       | TI AM335x BeagleBone Bla... | Desktop     | [612825abe3](https://bsd-hardware.info/?probe=612825abe3) | Dec 27, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING     | Desktop     | [2ee4c7fefe](https://bsd-hardware.info/?probe=2ee4c7fefe) | Dec 27, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [4bb84a33fa](https://bsd-hardware.info/?probe=4bb84a33fa) | Dec 26, 2021 |
| Casper        | EXCALIBUR G900              | Notebook    | [539cf08655](https://bsd-hardware.info/?probe=539cf08655) | Dec 24, 2021 |
| Samsung       | 530XBB                      | Notebook    | [fe0adb59d8](https://bsd-hardware.info/?probe=fe0adb59d8) | Dec 20, 2021 |
| Samsung       | R720                        | Notebook    | [620195d4aa](https://bsd-hardware.info/?probe=620195d4aa) | Dec 20, 2021 |
| HP            | Compaq 15                   | Notebook    | [1e8b1ce39b](https://bsd-hardware.info/?probe=1e8b1ce39b) | Dec 20, 2021 |
| PC Engines    | APU2                        | Desktop     | [d271c4a29f](https://bsd-hardware.info/?probe=d271c4a29f) | Dec 15, 2021 |
| Intel         | SharkBay Platform           | Notebook    | [383d1e31c9](https://bsd-hardware.info/?probe=383d1e31c9) | Dec 14, 2021 |
| Lenovo        | ThinkPad Edge E430 3254A... | Notebook    | [0215354bfc](https://bsd-hardware.info/?probe=0215354bfc) | Dec 13, 2021 |
| Lenovo        | ThinkPad T420s 41742BU      | Notebook    | [a86326d049](https://bsd-hardware.info/?probe=a86326d049) | Dec 11, 2021 |
| Dell          | G15 5510                    | Notebook    | [2da7a07664](https://bsd-hardware.info/?probe=2da7a07664) | Dec 07, 2021 |
| Lenovo        | ThinkPad X61 7675H7U        | Notebook    | [545cbe065d](https://bsd-hardware.info/?probe=545cbe065d) | Dec 06, 2021 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [0d4c532744](https://bsd-hardware.info/?probe=0d4c532744) | Nov 29, 2021 |
| Dell          | G15 5510                    | Notebook    | [8846b3fd69](https://bsd-hardware.info/?probe=8846b3fd69) | Nov 27, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [923a99fade](https://bsd-hardware.info/?probe=923a99fade) | Nov 27, 2021 |
| Lenovo        | ThinkPad X220 429043U       | Notebook    | [339779baad](https://bsd-hardware.info/?probe=339779baad) | Nov 26, 2021 |
| MSI           | MS-7C56                     | Desktop     | [d4e3f14ad4](https://bsd-hardware.info/?probe=d4e3f14ad4) | Nov 23, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [8b178d13c7](https://bsd-hardware.info/?probe=8b178d13c7) | Nov 22, 2021 |
| Alienware     | m15                         | Notebook    | [20afd3904b](https://bsd-hardware.info/?probe=20afd3904b) | Nov 21, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [63443924f3](https://bsd-hardware.info/?probe=63443924f3) | Nov 19, 2021 |
| Acer          | AO722                       | Notebook    | [98b88ae138](https://bsd-hardware.info/?probe=98b88ae138) | Nov 15, 2021 |
| Lenovo        | ThinkPad T420 4236MBG       | Notebook    | [0391bf9ea4](https://bsd-hardware.info/?probe=0391bf9ea4) | Nov 14, 2021 |
| PC Engines    | APU2                        | Desktop     | [15a26da041](https://bsd-hardware.info/?probe=15a26da041) | Nov 14, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [34d905d6f3](https://bsd-hardware.info/?probe=34d905d6f3) | Nov 11, 2021 |
| Apple         | iMac13,1                    | All in one  | [3da0012112](https://bsd-hardware.info/?probe=3da0012112) | Nov 06, 2021 |
| Unknown       | Hardkernel ODROID-N2        | Desktop     | [42f6e357c9](https://bsd-hardware.info/?probe=42f6e357c9) | Nov 05, 2021 |
| Google        | Grunt                       | Notebook    | [aa07a1dd40](https://bsd-hardware.info/?probe=aa07a1dd40) | Nov 05, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [cdccf02902](https://bsd-hardware.info/?probe=cdccf02902) | Nov 04, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [2471e3f337](https://bsd-hardware.info/?probe=2471e3f337) | Nov 04, 2021 |
| Yanling       | YL-KBR6L                    | Desktop     | [35f1c905eb](https://bsd-hardware.info/?probe=35f1c905eb) | Nov 04, 2021 |
| Google        | Grunt                       | Notebook    | [c87e033731](https://bsd-hardware.info/?probe=c87e033731) | Nov 01, 2021 |
| Panasonic     | CF-53AAGHYDM                | Notebook    | [721ef0235c](https://bsd-hardware.info/?probe=721ef0235c) | Oct 30, 2021 |
| HP            | 0A60h                       | Desktop     | [5c227c5b61](https://bsd-hardware.info/?probe=5c227c5b61) | Oct 27, 2021 |
| HP            | ProDesk 600 G1 SFF          | Desktop     | [7f19a8a566](https://bsd-hardware.info/?probe=7f19a8a566) | Oct 26, 2021 |
| Matsushita... | CF-48V4KNDQM                | Notebook    | [9e254ab443](https://bsd-hardware.info/?probe=9e254ab443) | Oct 23, 2021 |
| Supermicro    | X7SBL                       | Desktop     | [f5b4e8e7ab](https://bsd-hardware.info/?probe=f5b4e8e7ab) | Oct 23, 2021 |
| ASUSTek       | 1000HE                      | Notebook    | [1d5e3e5bc3](https://bsd-hardware.info/?probe=1d5e3e5bc3) | Oct 22, 2021 |
| Lenovo        | ThinkPad T430 2347GZU       | Notebook    | [3337c00433](https://bsd-hardware.info/?probe=3337c00433) | Oct 22, 2021 |
| Matsushita... | CF-51RCVDNLM                | Notebook    | [b20953f2f4](https://bsd-hardware.info/?probe=b20953f2f4) | Oct 18, 2021 |
| Panasonic     | CF-52PFPBSFQ                | Notebook    | [bbdfde368b](https://bsd-hardware.info/?probe=bbdfde368b) | Oct 18, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | Notebook    | [b4ba704356](https://bsd-hardware.info/?probe=b4ba704356) | Oct 17, 2021 |
| Google        | Grunt                       | Notebook    | [e6d4421a4d](https://bsd-hardware.info/?probe=e6d4421a4d) | Oct 16, 2021 |
| Lenovo        | SHARKBAY No DPK             | Desktop     | [e762f9146e](https://bsd-hardware.info/?probe=e762f9146e) | Oct 16, 2021 |
| Lenovo        | ThinkPad T410 2537N24       | Notebook    | [1a5bae2227](https://bsd-hardware.info/?probe=1a5bae2227) | Oct 15, 2021 |
| ASUSTek       | P10S-I Series               | Desktop     | [d086bf947a](https://bsd-hardware.info/?probe=d086bf947a) | Oct 15, 2021 |
| Gigabyte      | B450M DS3H                  | Desktop     | [445b53ddba](https://bsd-hardware.info/?probe=445b53ddba) | Oct 15, 2021 |
| Protectli     | FW6                         | Desktop     | [de39c4e316](https://bsd-hardware.info/?probe=de39c4e316) | Oct 15, 2021 |
| Google        | Grunt                       | Notebook    | [ee9b2d7ad3](https://bsd-hardware.info/?probe=ee9b2d7ad3) | Oct 15, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [9eab523504](https://bsd-hardware.info/?probe=9eab523504) | Oct 14, 2021 |
| MSI           | MS-7D54                     | Desktop     | [ac1f6ee8a6](https://bsd-hardware.info/?probe=ac1f6ee8a6) | Oct 13, 2021 |
| Google        | Grunt                       | Notebook    | [e76c73d9a3](https://bsd-hardware.info/?probe=e76c73d9a3) | Oct 11, 2021 |
| Supermicro    | X11SCE-F                    | Server      | [5731b09f69](https://bsd-hardware.info/?probe=5731b09f69) | Oct 11, 2021 |
| Gigabyte      | B450M DS3H                  | Desktop     | [50e4e13ee0](https://bsd-hardware.info/?probe=50e4e13ee0) | Oct 07, 2021 |
| MSI           | MS-7B53                     | Desktop     | [c7104d301e](https://bsd-hardware.info/?probe=c7104d301e) | Oct 05, 2021 |
| Unknown       | Raspberry Pi 4 Model B R... | Desktop     | [49173900e7](https://bsd-hardware.info/?probe=49173900e7) | Oct 04, 2021 |
| Unknown       | Raspberry Pi 4 Model B R... | Desktop     | [d05a877535](https://bsd-hardware.info/?probe=d05a877535) | Oct 03, 2021 |
| ASUSTek       | X555LB                      | Notebook    | [e3443d9f27](https://bsd-hardware.info/?probe=e3443d9f27) | Oct 02, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [46672cf89f](https://bsd-hardware.info/?probe=46672cf89f) | Oct 01, 2021 |
| IBM           | ThinkPad H 1846AQG          | Notebook    | [5e5c7247ca](https://bsd-hardware.info/?probe=5e5c7247ca) | Oct 01, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [838a177f57](https://bsd-hardware.info/?probe=838a177f57) | Sep 30, 2021 |
| ASUSTek       | UX305FA                     | Notebook    | [decf219ff2](https://bsd-hardware.info/?probe=decf219ff2) | Sep 30, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [d9762d6c2d](https://bsd-hardware.info/?probe=d9762d6c2d) | Sep 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [0d00ce5de9](https://bsd-hardware.info/?probe=0d00ce5de9) | Sep 22, 2021 |
| HP            | Pro3500 Series              | Desktop     | [abf3223f32](https://bsd-hardware.info/?probe=abf3223f32) | Sep 19, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [7a800aec88](https://bsd-hardware.info/?probe=7a800aec88) | Sep 15, 2021 |
| Dell          | XPS 13 7390 2-in-1          | Notebook    | [577e0ed7fe](https://bsd-hardware.info/?probe=577e0ed7fe) | Sep 13, 2021 |
| NF541         | Unknown                     | Desktop     | [deb29af749](https://bsd-hardware.info/?probe=deb29af749) | Sep 11, 2021 |
| MSI           | MS-7A34                     | Desktop     | [decfe43121](https://bsd-hardware.info/?probe=decfe43121) | Sep 10, 2021 |
| HP            | 250 G5 Notebook PC          | Notebook    | [6e50039406](https://bsd-hardware.info/?probe=6e50039406) | Sep 09, 2021 |
| PC Engines    | apu4                        | Desktop     | [9557835b54](https://bsd-hardware.info/?probe=9557835b54) | Sep 09, 2021 |
| Gigabyte      | BRi3(H)-10110               | Desktop     | [9aa3540749](https://bsd-hardware.info/?probe=9aa3540749) | Sep 09, 2021 |
| Apple         | MacBookPro6,2               | Notebook    | [4632683b4b](https://bsd-hardware.info/?probe=4632683b4b) | Sep 08, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [f860e13b6b](https://bsd-hardware.info/?probe=f860e13b6b) | Sep 08, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | Notebook    | [4cc349d29a](https://bsd-hardware.info/?probe=4cc349d29a) | Sep 08, 2021 |
| Lenovo        | ThinkPad X250 20CM0046US    | Notebook    | [1ed50b75f1](https://bsd-hardware.info/?probe=1ed50b75f1) | Sep 08, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [1b6bf4666c](https://bsd-hardware.info/?probe=1b6bf4666c) | Sep 05, 2021 |
| Sony          | VGN-P698E                   | Notebook    | [c8274e858d](https://bsd-hardware.info/?probe=c8274e858d) | Aug 30, 2021 |
| Lenovo        | FLEX 3-1120 80LX            | Notebook    | [2f1a1a42b8](https://bsd-hardware.info/?probe=2f1a1a42b8) | Aug 29, 2021 |
| Lenovo        | ThinkPad P73 20QRS00200     | Notebook    | [dfc86a0368](https://bsd-hardware.info/?probe=dfc86a0368) | Aug 29, 2021 |
| Gigabyte      | GA-7VT600                   | Desktop     | [83b86f3e8c](https://bsd-hardware.info/?probe=83b86f3e8c) | Aug 23, 2021 |
| Acer          | Aspire ES1-132              | Notebook    | [43c82b1b16](https://bsd-hardware.info/?probe=43c82b1b16) | Aug 22, 2021 |
| IBM           | ThinkPad T42 2374K46        | Notebook    | [d93b6d68fa](https://bsd-hardware.info/?probe=d93b6d68fa) | Aug 18, 2021 |
| Lenovo        | IdeaPad 1 11IGL05 81VT      | Notebook    | [f7725f06df](https://bsd-hardware.info/?probe=f7725f06df) | Aug 18, 2021 |
| Lenovo        | Yoga 6 13ARE05 82FN         | Notebook    | [6f7976c329](https://bsd-hardware.info/?probe=6f7976c329) | Aug 16, 2021 |
| Standard      | TF                          | Notebook    | [c7995f2022](https://bsd-hardware.info/?probe=c7995f2022) | Aug 12, 2021 |
| HP            | Notebook                    | Notebook    | [a3c3297cd2](https://bsd-hardware.info/?probe=a3c3297cd2) | Aug 08, 2021 |
| HP            | Notebook                    | Notebook    | [0c316107a4](https://bsd-hardware.info/?probe=0c316107a4) | Aug 08, 2021 |
| Unknown       | FriendlyElec NanoPi R4S     | Desktop     | [ac10928ac3](https://bsd-hardware.info/?probe=ac10928ac3) | Aug 05, 2021 |
| Lenovo        | ThinkPad T430 2349U2B       | Notebook    | [90d85e011f](https://bsd-hardware.info/?probe=90d85e011f) | Jul 31, 2021 |
| Lenovo        | Yoga 330-11IGM 81A6         | Notebook    | [5404f763dd](https://bsd-hardware.info/?probe=5404f763dd) | Jul 26, 2021 |
| Lenovo        | ThinkPad T400 2767WSB       | Notebook    | [36ce1d1e00](https://bsd-hardware.info/?probe=36ce1d1e00) | Jul 24, 2021 |
| Unknown       | Pine64 Rock64               | Desktop     | [0df3f7572c](https://bsd-hardware.info/?probe=0df3f7572c) | Jul 23, 2021 |
| MSI           | MS-1613                     | Notebook    | [795e61c1a3](https://bsd-hardware.info/?probe=795e61c1a3) | Jul 21, 2021 |
| ASUSTek       | B202                        | Desktop     | [9f5f0a4117](https://bsd-hardware.info/?probe=9f5f0a4117) | Jul 21, 2021 |
| Lenovo        | ThinkPad X270 20HNA006ID    | Notebook    | [6fc7c972a5](https://bsd-hardware.info/?probe=6fc7c972a5) | Jul 19, 2021 |
| Lenovo        | ThinkPad T420 4236MBG       | Notebook    | [5b43300a93](https://bsd-hardware.info/?probe=5b43300a93) | Jul 13, 2021 |
| Unknown       | Pine64 Rock64               | Desktop     | [83c18360fc](https://bsd-hardware.info/?probe=83c18360fc) | Jul 12, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [740c5182d3](https://bsd-hardware.info/?probe=740c5182d3) | Jul 11, 2021 |
| HP            | ProLiant DL360e Gen8        | Desktop     | [30eeb098b0](https://bsd-hardware.info/?probe=30eeb098b0) | Jul 10, 2021 |
| HP            | ProLiant DL320 G5           | Desktop     | [3b4ee33976](https://bsd-hardware.info/?probe=3b4ee33976) | Jul 10, 2021 |
| Foxconn       | AT-7000 Series              | Desktop     | [3802fb98b5](https://bsd-hardware.info/?probe=3802fb98b5) | Jul 10, 2021 |
| Lenovo        | ThinkPad X230 232578G       | Notebook    | [a8c497b58b](https://bsd-hardware.info/?probe=a8c497b58b) | Jul 09, 2021 |
| Unknown       | Pine64 Rock64               | Desktop     | [9cffa29c69](https://bsd-hardware.info/?probe=9cffa29c69) | Jul 08, 2021 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [55f46bc85d](https://bsd-hardware.info/?probe=55f46bc85d) | Jul 07, 2021 |
| HP            | Pavilion dm1                | Notebook    | [a863347147](https://bsd-hardware.info/?probe=a863347147) | Jul 03, 2021 |
| Lenovo        | Yoga 330-11IGM 81A6         | Notebook    | [72e208aa92](https://bsd-hardware.info/?probe=72e208aa92) | Jul 02, 2021 |
| Unknown       | Unknown                     | Desktop     | [cfb0e172cb](https://bsd-hardware.info/?probe=cfb0e172cb) | Jun 27, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [443817737d](https://bsd-hardware.info/?probe=443817737d) | Jun 24, 2021 |
| Microsoft     | Surface Pro 7               | Tablet      | [1b8d66e5f0](https://bsd-hardware.info/?probe=1b8d66e5f0) | Jun 22, 2021 |
| Dell          | 0GTK4K A02                  | Desktop     | [bb610333d0](https://bsd-hardware.info/?probe=bb610333d0) | Jun 22, 2021 |
| Unknown       | Unknown                     | Notebook    | [f37bf77853](https://bsd-hardware.info/?probe=f37bf77853) | Jun 20, 2021 |
| ASRock        | X99 WS                      | Desktop     | [201a7417a5](https://bsd-hardware.info/?probe=201a7417a5) | Jun 11, 2021 |
| Supermicro    | X8DTH-i/6/iF/6F             | Desktop     | [1e8ac47693](https://bsd-hardware.info/?probe=1e8ac47693) | Jun 08, 2021 |
| Supermicro    | X8DTH-i/6/iF/6F             | Desktop     | [bd4a74c5e5](https://bsd-hardware.info/?probe=bd4a74c5e5) | Jun 08, 2021 |
| Supermicro    | X10SLH-N6-ST031             | Desktop     | [e54175f99f](https://bsd-hardware.info/?probe=e54175f99f) | Jun 06, 2021 |
| Lenovo        | ThinkPad X250 20CLS7WY04    | Notebook    | [b60f4a19ee](https://bsd-hardware.info/?probe=b60f4a19ee) | Jun 06, 2021 |
| ASRock        | Z68 Extreme4 Gen3           | Desktop     | [58c8cdc060](https://bsd-hardware.info/?probe=58c8cdc060) | Jun 05, 2021 |
| Lenovo        | ThinkPad T430 23511A6       | Notebook    | [89fb2aa493](https://bsd-hardware.info/?probe=89fb2aa493) | Jun 05, 2021 |
| Lenovo        | ThinkPad T400 6475K43       | Notebook    | [1b3e80e2e9](https://bsd-hardware.info/?probe=1b3e80e2e9) | Jun 03, 2021 |
| Supermicro    | Super Server                | Server      | [68579d4660](https://bsd-hardware.info/?probe=68579d4660) | Jun 03, 2021 |
| Lenovo        | IdeaPad S210 Touch 20257    | Notebook    | [392df069bd](https://bsd-hardware.info/?probe=392df069bd) | Jun 02, 2021 |
| Apple         | PowerBook5,2                | Notebook    | [8cc0aab53c](https://bsd-hardware.info/?probe=8cc0aab53c) | May 31, 2021 |
| Shuttle       | DS77U                       | Desktop     | [5d1c78145e](https://bsd-hardware.info/?probe=5d1c78145e) | May 30, 2021 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [ca05acd52f](https://bsd-hardware.info/?probe=ca05acd52f) | May 30, 2021 |
| HP            | 530 Notebook PC(KP477AA#... | Notebook    | [9c7b85c190](https://bsd-hardware.info/?probe=9c7b85c190) | May 30, 2021 |
| ASRock        | X570M Pro4                  | Desktop     | [1d1a5afcfb](https://bsd-hardware.info/?probe=1d1a5afcfb) | May 28, 2021 |
| Alienware     | Aurora Ryzen Edition        | Desktop     | [b9dc8b182c](https://bsd-hardware.info/?probe=b9dc8b182c) | May 28, 2021 |
| Unknown       | Unknown                     | Desktop     | [d098ba539d](https://bsd-hardware.info/?probe=d098ba539d) | May 27, 2021 |
| ASUSTek       | B202                        | Desktop     | [0b66a5fd20](https://bsd-hardware.info/?probe=0b66a5fd20) | May 21, 2021 |
| Unknown       | Unknown                     | Notebook    | [b296fb35e2](https://bsd-hardware.info/?probe=b296fb35e2) | May 19, 2021 |
| Unknown       | Unknown                     | Notebook    | [750e01de05](https://bsd-hardware.info/?probe=750e01de05) | May 19, 2021 |
| Panasonic     | CF-53AAGHYDM                | Notebook    | [ef5e9ec095](https://bsd-hardware.info/?probe=ef5e9ec095) | May 18, 2021 |
| Panasonic     | CF-52PFPBSFQ                | Notebook    | [65f5931910](https://bsd-hardware.info/?probe=65f5931910) | May 18, 2021 |
| Lenovo        | ThinkPad T430 2347GZU       | Notebook    | [1e9f399d73](https://bsd-hardware.info/?probe=1e9f399d73) | May 17, 2021 |
| Lenovo        | ThinkPad T410 2537N24       | Notebook    | [109f3afa21](https://bsd-hardware.info/?probe=109f3afa21) | May 17, 2021 |
| ASUSTek       | 1000HE                      | Notebook    | [f92f43bc54](https://bsd-hardware.info/?probe=f92f43bc54) | May 17, 2021 |
| Matsushita... | CF-51RCVDNLM                | Notebook    | [33bc82e701](https://bsd-hardware.info/?probe=33bc82e701) | May 17, 2021 |
| Matsushita... | CF-48V4KNDQM                | Notebook    | [bf76401b74](https://bsd-hardware.info/?probe=bf76401b74) | May 17, 2021 |
| PC Engines    | APU2                        | Desktop     | [c99a0b0e4d](https://bsd-hardware.info/?probe=c99a0b0e4d) | May 05, 2021 |
| ASRock        | X99 WS                      | Desktop     | [eb20367455](https://bsd-hardware.info/?probe=eb20367455) | May 05, 2021 |
| Supermicro    | X8STi                       | Desktop     | [c615ef1edf](https://bsd-hardware.info/?probe=c615ef1edf) | May 04, 2021 |
| ASUSTek       | UX430UNR                    | Notebook    | [bfe7ec0975](https://bsd-hardware.info/?probe=bfe7ec0975) | May 03, 2021 |
| Lenovo        | ThinkCentre M93p 10AAS25... | Desktop     | [a9bbd07ad9](https://bsd-hardware.info/?probe=a9bbd07ad9) | May 03, 2021 |
| PC Engines    | apu1                        | Desktop     | [7b4678c7ef](https://bsd-hardware.info/?probe=7b4678c7ef) | May 03, 2021 |
| Acer          | AO531h                      | Notebook    | [614326a3d3](https://bsd-hardware.info/?probe=614326a3d3) | May 03, 2021 |
| Acer          | AO531h                      | Notebook    | [9de7465352](https://bsd-hardware.info/?probe=9de7465352) | May 03, 2021 |
| ASUSTek       | P10S-I Series               | Desktop     | [6548ae7d88](https://bsd-hardware.info/?probe=6548ae7d88) | May 01, 2021 |
| PC Engines    | apu1                        | Desktop     | [c5ae3337e7](https://bsd-hardware.info/?probe=c5ae3337e7) | May 01, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [6e8891f184](https://bsd-hardware.info/?probe=6e8891f184) | Apr 24, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [7ec73fe36d](https://bsd-hardware.info/?probe=7ec73fe36d) | Apr 23, 2021 |
| ASUSTek       | All Series                  | Desktop     | [ef6afe88d7](https://bsd-hardware.info/?probe=ef6afe88d7) | Apr 17, 2021 |
| Lenovo        | ThinkPad X201 Tablet 298... | Notebook    | [4faceaf6e5](https://bsd-hardware.info/?probe=4faceaf6e5) | Apr 17, 2021 |
| ASUSTek       | UX430UNR                    | Notebook    | [f31eda4c16](https://bsd-hardware.info/?probe=f31eda4c16) | Apr 16, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [403a237513](https://bsd-hardware.info/?probe=403a237513) | Apr 14, 2021 |
| Lenovo        | ThinkPad X250 20CLS1LC13    | Notebook    | [dcf202ea95](https://bsd-hardware.info/?probe=dcf202ea95) | Apr 10, 2021 |
| Lenovo        | ThinkPad X250 20CLS1LC13    | Notebook    | [ee371f3e8f](https://bsd-hardware.info/?probe=ee371f3e8f) | Apr 08, 2021 |
| ECT           | One Computer AMD A10-785... | Desktop     | [de7e23b3e3](https://bsd-hardware.info/?probe=de7e23b3e3) | Apr 07, 2021 |
| HP            | t630 Thin Client            | Mini pc     | [994a246318](https://bsd-hardware.info/?probe=994a246318) | Apr 06, 2021 |
| Gigabyte      | GB-BXBT-2807                | Desktop     | [25e9765fc0](https://bsd-hardware.info/?probe=25e9765fc0) | Apr 03, 2021 |
| Lenovo        | ThinkPad Edge 05796AU       | Notebook    | [4a094815c0](https://bsd-hardware.info/?probe=4a094815c0) | Mar 24, 2021 |
| ASUSTek       | All Series                  | Desktop     | [c5bc64e4e9](https://bsd-hardware.info/?probe=c5bc64e4e9) | Mar 22, 2021 |
| Lenovo        | ThinkPad X220 4291ON5       | Notebook    | [8d81204137](https://bsd-hardware.info/?probe=8d81204137) | Mar 22, 2021 |
| ASUSTek       | All Series                  | Desktop     | [700ff7d378](https://bsd-hardware.info/?probe=700ff7d378) | Mar 22, 2021 |
| Lenovo        | ThinkPad X220 4291EM4       | Notebook    | [9d393db103](https://bsd-hardware.info/?probe=9d393db103) | Mar 20, 2021 |
| Dell          | Latitude E7270              | Notebook    | [5ba79f9aa5](https://bsd-hardware.info/?probe=5ba79f9aa5) | Mar 19, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [b35adf782c](https://bsd-hardware.info/?probe=b35adf782c) | Mar 17, 2021 |
| HP            | ProLiant DL360 Gen9         | Desktop     | [b283b34881](https://bsd-hardware.info/?probe=b283b34881) | Mar 17, 2021 |
| Supermicro    | Super Server                | Server      | [ec1e532ea9](https://bsd-hardware.info/?probe=ec1e532ea9) | Mar 17, 2021 |
| Lenovo        | ThinkPad X280 20KESA000B    | Notebook    | [e2b586d597](https://bsd-hardware.info/?probe=e2b586d597) | Mar 17, 2021 |
| HP            | ProLiant DL360 Gen9         | Desktop     | [bf440e72a1](https://bsd-hardware.info/?probe=bf440e72a1) | Mar 17, 2021 |
| HP            | EliteDesk 800 G5 SFF        | Desktop     | [aaf9bc1c12](https://bsd-hardware.info/?probe=aaf9bc1c12) | Mar 17, 2021 |
| ASUSTek       | X510UA                      | Notebook    | [440f1ef3ec](https://bsd-hardware.info/?probe=440f1ef3ec) | Mar 14, 2021 |
| Apple         | MacBookAir6,2               | Notebook    | [52584aaa97](https://bsd-hardware.info/?probe=52584aaa97) | Mar 14, 2021 |
| Apple         | iMac12,1                    | All in one  | [17466db7fd](https://bsd-hardware.info/?probe=17466db7fd) | Mar 14, 2021 |
| Apple         | MacBookAir6,2               | Notebook    | [fb136a79e7](https://bsd-hardware.info/?probe=fb136a79e7) | Mar 13, 2021 |
| Panasonic     | CF-30KTP48NL                | Notebook    | [119b4875e9](https://bsd-hardware.info/?probe=119b4875e9) | Mar 12, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1HL0... | Desktop     | [954c65dbcf](https://bsd-hardware.info/?probe=954c65dbcf) | Mar 11, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [9f4a3cd83d](https://bsd-hardware.info/?probe=9f4a3cd83d) | Mar 08, 2021 |
| ASUSTek       | All Series                  | Desktop     | [b4aec46644](https://bsd-hardware.info/?probe=b4aec46644) | Mar 07, 2021 |
| ASUSTek       | All Series                  | Desktop     | [f7b1921594](https://bsd-hardware.info/?probe=f7b1921594) | Mar 07, 2021 |
| Lenovo        | ThinkPad T400 6475P1G       | Notebook    | [6a0907b5e8](https://bsd-hardware.info/?probe=6a0907b5e8) | Mar 06, 2021 |
| ASUSTek       | X510UA                      | Notebook    | [f22eeba366](https://bsd-hardware.info/?probe=f22eeba366) | Mar 04, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [7d1ff5416d](https://bsd-hardware.info/?probe=7d1ff5416d) | Mar 01, 2021 |
| Acer          | Spin SP111-32N              | Notebook    | [9f44af71aa](https://bsd-hardware.info/?probe=9f44af71aa) | Feb 28, 2021 |
| Dell          | Inspiron 1000               | Notebook    | [70604dcbfa](https://bsd-hardware.info/?probe=70604dcbfa) | Feb 28, 2021 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | Notebook    | [fb890afc86](https://bsd-hardware.info/?probe=fb890afc86) | Feb 28, 2021 |
| ASRock        | G31M-VS2                    | Desktop     | [6c7150dc1b](https://bsd-hardware.info/?probe=6c7150dc1b) | Feb 24, 2021 |
| ASRock        | J4205-ITX                   | Desktop     | [c8e0b22858](https://bsd-hardware.info/?probe=c8e0b22858) | Feb 23, 2021 |
| Apple         | MacBook5,1                  | Notebook    | [41ea02c8bc](https://bsd-hardware.info/?probe=41ea02c8bc) | Feb 21, 2021 |
| Acer          | AOA150                      | Notebook    | [91e5ec60b9](https://bsd-hardware.info/?probe=91e5ec60b9) | Feb 21, 2021 |
| IBM           | ThinkPad T42 2374K46        | Notebook    | [311f93ab37](https://bsd-hardware.info/?probe=311f93ab37) | Feb 20, 2021 |
| ASUSTek       | X102BA                      | Notebook    | [529baeb345](https://bsd-hardware.info/?probe=529baeb345) | Feb 20, 2021 |
| ASUSTek       | X102BA                      | Notebook    | [65f1904b56](https://bsd-hardware.info/?probe=65f1904b56) | Feb 20, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [c2dded2160](https://bsd-hardware.info/?probe=c2dded2160) | Feb 19, 2021 |
| PC Engines    | apu4                        | Desktop     | [b30884fc0e](https://bsd-hardware.info/?probe=b30884fc0e) | Feb 18, 2021 |
| PC Engines    | APU3                        | Desktop     | [449967354c](https://bsd-hardware.info/?probe=449967354c) | Feb 18, 2021 |
| PC Engines    | APU2                        | Desktop     | [b911e3bec2](https://bsd-hardware.info/?probe=b911e3bec2) | Feb 18, 2021 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | Notebook    | [4f646f53e9](https://bsd-hardware.info/?probe=4f646f53e9) | Feb 14, 2021 |
| Shuttle       | DS77U                       | Desktop     | [2d0bd0e99a](https://bsd-hardware.info/?probe=2d0bd0e99a) | Feb 14, 2021 |
| Dell          | Inspiron 1000               | Notebook    | [104175ae13](https://bsd-hardware.info/?probe=104175ae13) | Feb 13, 2021 |
| Sony          | VPCX115KX                   | Notebook    | [fef3d94e6c](https://bsd-hardware.info/?probe=fef3d94e6c) | Feb 12, 2021 |
| Acer          | Extensa 5635Z               | Notebook    | [3b4a7e7fc2](https://bsd-hardware.info/?probe=3b4a7e7fc2) | Feb 10, 2021 |
| Sony          | VPCF12C5E                   | Notebook    | [df8c1de8a5](https://bsd-hardware.info/?probe=df8c1de8a5) | Feb 07, 2021 |
| Gigabyte      | Z68A-D3H-B3                 | Desktop     | [e1c3b89d0d](https://bsd-hardware.info/?probe=e1c3b89d0d) | Feb 06, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [b35f7a5610](https://bsd-hardware.info/?probe=b35f7a5610) | Feb 05, 2021 |
| Microsoft     | Surface Go 2                | Tablet      | [69c8123ec6](https://bsd-hardware.info/?probe=69c8123ec6) | Feb 01, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [828a9df369](https://bsd-hardware.info/?probe=828a9df369) | Feb 01, 2021 |
| IBM           | ThinkPad T42 2373K9G        | Notebook    | [a12c3a0b21](https://bsd-hardware.info/?probe=a12c3a0b21) | Feb 01, 2021 |
| Lenovo        | ThinkCentre M93p 10A8S0C... | Desktop     | [c8af335c01](https://bsd-hardware.info/?probe=c8af335c01) | Jan 29, 2021 |
| Lenovo        | ThinkPad T61 7661AU5        | Notebook    | [23e498234e](https://bsd-hardware.info/?probe=23e498234e) | Jan 28, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B      | Desktop     | [8c953bac3f](https://bsd-hardware.info/?probe=8c953bac3f) | Jan 25, 2021 |
| ASUSTek       | All Series                  | Desktop     | [7ebe6eee38](https://bsd-hardware.info/?probe=7ebe6eee38) | Jan 25, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [2a81a1bd1f](https://bsd-hardware.info/?probe=2a81a1bd1f) | Jan 24, 2021 |
| Sun           | SUNW,Sun-Blade-1500         | Desktop     | [647618a0ca](https://bsd-hardware.info/?probe=647618a0ca) | Jan 22, 2021 |
| PC Engines    | apu1                        | Desktop     | [a5d18dcbbc](https://bsd-hardware.info/?probe=a5d18dcbbc) | Jan 21, 2021 |
| PC Engines    | apu1                        | Desktop     | [70918da1e7](https://bsd-hardware.info/?probe=70918da1e7) | Jan 21, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [5f469ceeb9](https://bsd-hardware.info/?probe=5f469ceeb9) | Jan 20, 2021 |
| Sun           | SUNW,Sun-Blade-100          | Desktop     | [299c76eb85](https://bsd-hardware.info/?probe=299c76eb85) | Jan 18, 2021 |
| Lenovo        | ThinkCentre M93p 10A8S0C... | Desktop     | [36ef631bfe](https://bsd-hardware.info/?probe=36ef631bfe) | Jan 05, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [6cd195aa69](https://bsd-hardware.info/?probe=6cd195aa69) | Jan 05, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [50ca36db01](https://bsd-hardware.info/?probe=50ca36db01) | Jan 05, 2021 |
| ASUSTek       | X101CH                      | Notebook    | [112792b300](https://bsd-hardware.info/?probe=112792b300) | Jan 02, 2021 |
| ASUSTek       | X101CH                      | Notebook    | [8b571cc947](https://bsd-hardware.info/?probe=8b571cc947) | Jan 02, 2021 |
| ASUSTek       | X102BA                      | Notebook    | [893b9111c6](https://bsd-hardware.info/?probe=893b9111c6) | Dec 27, 2020 |
| HP            | 240 G1                      | Notebook    | [3ee90471d0](https://bsd-hardware.info/?probe=3ee90471d0) | Dec 26, 2020 |
| Apple         | PowerBook5,8                | Notebook    | [96f550a537](https://bsd-hardware.info/?probe=96f550a537) | Dec 24, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [f0b9687ab8](https://bsd-hardware.info/?probe=f0b9687ab8) | Dec 22, 2020 |
| Lenovo        | ThinkPad T400 6475K43       | Notebook    | [30500a25d3](https://bsd-hardware.info/?probe=30500a25d3) | Dec 18, 2020 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [d019e14245](https://bsd-hardware.info/?probe=d019e14245) | Dec 18, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [7e80ced15e](https://bsd-hardware.info/?probe=7e80ced15e) | Dec 16, 2020 |
| Unknown       | ODYSSEY-X86J4105            | Desktop     | [17749e13c8](https://bsd-hardware.info/?probe=17749e13c8) | Dec 16, 2020 |
| Unknown       | Spring Peak                 | Notebook    | [b61f5c268a](https://bsd-hardware.info/?probe=b61f5c268a) | Dec 15, 2020 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [d13e0a1749](https://bsd-hardware.info/?probe=d13e0a1749) | Dec 15, 2020 |
| Supermicro    | X11DDW-L                    | Desktop     | [57a5022e27](https://bsd-hardware.info/?probe=57a5022e27) | Dec 14, 2020 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [3a78e7dc1a](https://bsd-hardware.info/?probe=3a78e7dc1a) | Dec 11, 2020 |
| Dell          | Latitude 3300               | Notebook    | [108a030875](https://bsd-hardware.info/?probe=108a030875) | Dec 07, 2020 |
| Fujitsu       | LIFEBOOK P1610              | Notebook    | [e8ee627d6e](https://bsd-hardware.info/?probe=e8ee627d6e) | Dec 07, 2020 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | Notebook    | [2544123f79](https://bsd-hardware.info/?probe=2544123f79) | Dec 06, 2020 |
| Lenovo        | ThinkPad T410 2537NB5       | Notebook    | [d6a3aa6f8d](https://bsd-hardware.info/?probe=d6a3aa6f8d) | Dec 06, 2020 |
| Lenovo        | ThinkPad X201 3680FAG       | Notebook    | [1ba69078df](https://bsd-hardware.info/?probe=1ba69078df) | Dec 06, 2020 |
| ASUSTek       | P4P800-VM                   | Desktop     | [4fe4c14195](https://bsd-hardware.info/?probe=4fe4c14195) | Dec 05, 2020 |
| Apple         | Xserve3,1                   | Desktop     | [7329a7650d](https://bsd-hardware.info/?probe=7329a7650d) | Dec 05, 2020 |
| Gigabyte      | Unknown                     | Desktop     | [8a9ae48d42](https://bsd-hardware.info/?probe=8a9ae48d42) | Dec 01, 2020 |
| Lenovo        | ThinkPad W520 42763JU       | Notebook    | [5c50582307](https://bsd-hardware.info/?probe=5c50582307) | Nov 30, 2020 |
| HP            | Compaq dc7800 Small Form... | Desktop     | [2b49eb75dc](https://bsd-hardware.info/?probe=2b49eb75dc) | Nov 27, 2020 |
| HP            | Compaq dc7800 Small Form... | Desktop     | [3fe6528682](https://bsd-hardware.info/?probe=3fe6528682) | Nov 27, 2020 |
| Dell          | OptiPlex GX1 500M+          | Desktop     | [deb0d463ab](https://bsd-hardware.info/?probe=deb0d463ab) | Nov 27, 2020 |
| Dell          | OptiPlex GX1 500M+          | Desktop     | [5186eb9e52](https://bsd-hardware.info/?probe=5186eb9e52) | Nov 26, 2020 |
| Lenovo        | Yoga 720-13IKB 81C3         | Notebook    | [467a6fc001](https://bsd-hardware.info/?probe=467a6fc001) | Nov 26, 2020 |
| Lenovo        | Unknown                     | Notebook    | [1cf65625a7](https://bsd-hardware.info/?probe=1cf65625a7) | Nov 24, 2020 |
| HP            | Setzer                      | Notebook    | [da7914cdd5](https://bsd-hardware.info/?probe=da7914cdd5) | Nov 22, 2020 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [9cf79cf54b](https://bsd-hardware.info/?probe=9cf79cf54b) | Nov 22, 2020 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [cab036429d](https://bsd-hardware.info/?probe=cab036429d) | Nov 22, 2020 |
| Unknown       | cavium,ubnt_e300            | Desktop     | [b8524b5002](https://bsd-hardware.info/?probe=b8524b5002) | Nov 20, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B      | Desktop     | [c030400069](https://bsd-hardware.info/?probe=c030400069) | Nov 19, 2020 |
| ASRock        | IMB-191                     | Desktop     | [76991234cd](https://bsd-hardware.info/?probe=76991234cd) | Nov 18, 2020 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [c03bc18b3a](https://bsd-hardware.info/?probe=c03bc18b3a) | Nov 18, 2020 |
| MSI           | MS-B09012                   | Desktop     | [7ba791108f](https://bsd-hardware.info/?probe=7ba791108f) | Nov 18, 2020 |
| PC Engines    | APU2                        | Desktop     | [b4f5d7d344](https://bsd-hardware.info/?probe=b4f5d7d344) | Nov 16, 2020 |
| Supermicro    | X8DTH-i/6/iF/6F             | Desktop     | [778cb9f428](https://bsd-hardware.info/?probe=778cb9f428) | Nov 16, 2020 |
| Lenovo        | ThinkPad T450 20BVA020AU    | Notebook    | [5d8bce59e8](https://bsd-hardware.info/?probe=5d8bce59e8) | Nov 16, 2020 |
| Gigabyte      | GB-BXBT-2807                | Desktop     | [c11b475d28](https://bsd-hardware.info/?probe=c11b475d28) | Nov 13, 2020 |
| Lenovo        | ThinkPad T60 87445BU        | Notebook    | [bfd9130d4b](https://bsd-hardware.info/?probe=bfd9130d4b) | Nov 10, 2020 |
| Lenovo        | ThinkCentre M92p 3212AD2    | Desktop     | [579528e284](https://bsd-hardware.info/?probe=579528e284) | Nov 10, 2020 |
| Lenovo        | ThinkPad T490 20N3S8PB00    | Notebook    | [6a0f910601](https://bsd-hardware.info/?probe=6a0f910601) | Nov 10, 2020 |
| Lenovo        | ThinkPad T490 20N3S8PB00    | Notebook    | [6dca4cdd18](https://bsd-hardware.info/?probe=6dca4cdd18) | Nov 10, 2020 |
| Lenovo        | ThinkPad T450s 20BWS2XS0... | Notebook    | [0b04a395a7](https://bsd-hardware.info/?probe=0b04a395a7) | Nov 10, 2020 |
| Gigabyte      | M61SME-S2L                  | Desktop     | [d8809eb5e7](https://bsd-hardware.info/?probe=d8809eb5e7) | Nov 09, 2020 |
| Gigabyte      | M61SME-S2L                  | Desktop     | [e5f658c70a](https://bsd-hardware.info/?probe=e5f658c70a) | Nov 09, 2020 |
| Pegatron      | SKLD4-P1                    | Desktop     | [ea548b4c71](https://bsd-hardware.info/?probe=ea548b4c71) | Nov 08, 2020 |
| Lenovo        | ThinkPad T460 20FN003LGE    | Notebook    | [1b7b105e5c](https://bsd-hardware.info/?probe=1b7b105e5c) | Nov 08, 2020 |
| IBM           | ThinkPad T42 2373K9G        | Notebook    | [e041100bb6](https://bsd-hardware.info/?probe=e041100bb6) | Nov 08, 2020 |
| Soekris En... | net5501                     | Desktop     | [bd9930a18a](https://bsd-hardware.info/?probe=bd9930a18a) | Nov 06, 2020 |
| Soekris En... | net6501                     | Desktop     | [fdf124653b](https://bsd-hardware.info/?probe=fdf124653b) | Nov 06, 2020 |
| Lenovo        | Yoga 720-13IKB 81C3         | Notebook    | [bdc2de68ce](https://bsd-hardware.info/?probe=bdc2de68ce) | Nov 05, 2020 |
| Lenovo        | Yoga 720-13IKB 81C3         | Notebook    | [8cfb32120b](https://bsd-hardware.info/?probe=8cfb32120b) | Nov 05, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [ebd246c141](https://bsd-hardware.info/?probe=ebd246c141) | Nov 04, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [f2e085e11a](https://bsd-hardware.info/?probe=f2e085e11a) | Nov 04, 2020 |
| MSI           | MS-7A34                     | Desktop     | [8c87d6b643](https://bsd-hardware.info/?probe=8c87d6b643) | Nov 03, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [9b6b24708e](https://bsd-hardware.info/?probe=9b6b24708e) | Nov 03, 2020 |
| Dell          | Precision M4800             | Notebook    | [ca6d4c4bb7](https://bsd-hardware.info/?probe=ca6d4c4bb7) | Nov 03, 2020 |
| Dell          | Precision M4800             | Notebook    | [c6a7b68c75](https://bsd-hardware.info/?probe=c6a7b68c75) | Nov 03, 2020 |
| Lenovo        | ThinkPad T500 2087A16       | Notebook    | [334eacfe16](https://bsd-hardware.info/?probe=334eacfe16) | Nov 03, 2020 |
| Lenovo        | ThinkPad W530 2436CTO       | Notebook    | [ded161fe2e](https://bsd-hardware.info/?probe=ded161fe2e) | Oct 31, 2020 |
| Lenovo        | ThinkPad W530 2436CTO       | Notebook    | [e108d4a375](https://bsd-hardware.info/?probe=e108d4a375) | Oct 31, 2020 |
| PC Engines    | APU2                        | Desktop     | [e0361ddbad](https://bsd-hardware.info/?probe=e0361ddbad) | Oct 31, 2020 |
| Intel         | NUC7i5BNH                   | Mini pc     | [ea59613cff](https://bsd-hardware.info/?probe=ea59613cff) | Oct 31, 2020 |
| ASUSTek       | B75M-A                      | Desktop     | [43ece33e8c](https://bsd-hardware.info/?probe=43ece33e8c) | Oct 31, 2020 |
| Intel         | D945GCLF2                   | Desktop     | [58678b0643](https://bsd-hardware.info/?probe=58678b0643) | Oct 30, 2020 |
| Intel         | D945GCLF2                   | Desktop     | [3354fb903b](https://bsd-hardware.info/?probe=3354fb903b) | Oct 30, 2020 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [973b62551f](https://bsd-hardware.info/?probe=973b62551f) | Oct 30, 2020 |
| eMachines     | EL1200                      | Desktop     | [ae59908738](https://bsd-hardware.info/?probe=ae59908738) | Oct 30, 2020 |
| Acer          | Veriton M6610G              | Desktop     | [7dd00aa8b1](https://bsd-hardware.info/?probe=7dd00aa8b1) | Oct 30, 2020 |
| eMachines     | EL1200                      | Desktop     | [5bc54351be](https://bsd-hardware.info/?probe=5bc54351be) | Oct 30, 2020 |
| ECS           | BSWI-D2                     | Desktop     | [c5b07f5c31](https://bsd-hardware.info/?probe=c5b07f5c31) | Oct 30, 2020 |
| Acer          | Extensa 2540                | Notebook    | [26670a4ae9](https://bsd-hardware.info/?probe=26670a4ae9) | Oct 30, 2020 |
| ASRock        | N3160-NUC IPC               | Desktop     | [8d13af2f0b](https://bsd-hardware.info/?probe=8d13af2f0b) | Oct 28, 2020 |
| ASRock        | N3160-NUC IPC               | Desktop     | [8714fe0665](https://bsd-hardware.info/?probe=8714fe0665) | Oct 28, 2020 |
| ASUSTek       | PRIME B250M-C               | Desktop     | [4594c1084c](https://bsd-hardware.info/?probe=4594c1084c) | Oct 28, 2020 |
| Shuttle       | DS77U                       | Desktop     | [c70e526574](https://bsd-hardware.info/?probe=c70e526574) | Oct 27, 2020 |
| Intel         | NUC5CPYB                    | Mini pc     | [1ec5c12f0b](https://bsd-hardware.info/?probe=1ec5c12f0b) | Oct 27, 2020 |
| Lenovo        | ThinkPad T450 20BV0005US    | Notebook    | [603e66300a](https://bsd-hardware.info/?probe=603e66300a) | Oct 27, 2020 |
| PC Engines    | APU2                        | Desktop     | [ce4c41d466](https://bsd-hardware.info/?probe=ce4c41d466) | Oct 26, 2020 |
| Dell          | PowerEdge R230              | Desktop     | [1422e9737b](https://bsd-hardware.info/?probe=1422e9737b) | Oct 26, 2020 |
| Supermicro    | X8STi                       | Desktop     | [1b64902781](https://bsd-hardware.info/?probe=1b64902781) | Oct 26, 2020 |
| HP            | 120-1136                    | Desktop     | [12f3eb0227](https://bsd-hardware.info/?probe=12f3eb0227) | Oct 25, 2020 |
| Lenovo        | ThinkPad T500 2087A16       | Notebook    | [cf8228f878](https://bsd-hardware.info/?probe=cf8228f878) | Oct 25, 2020 |
| HP            | ProLiant MicroServer        | Desktop     | [04b6ad9952](https://bsd-hardware.info/?probe=04b6ad9952) | Oct 25, 2020 |
| Supermicro    | X11SSW-F                    | Desktop     | [ca07d7ef48](https://bsd-hardware.info/?probe=ca07d7ef48) | Oct 25, 2020 |
| Gigabyte      | X58A-UD5                    | Desktop     | [6e642641e5](https://bsd-hardware.info/?probe=6e642641e5) | Oct 25, 2020 |
| AZW           | Z83 II                      | Desktop     | [9416876f20](https://bsd-hardware.info/?probe=9416876f20) | Oct 24, 2020 |
| AZW           | Z83 II                      | Desktop     | [19b1b4d85d](https://bsd-hardware.info/?probe=19b1b4d85d) | Oct 24, 2020 |
| Dell          | Precision WorkStation T7... | Desktop     | [c01ce9ec81](https://bsd-hardware.info/?probe=c01ce9ec81) | Oct 24, 2020 |
| Lenovo        | Unknown                     | Notebook    | [7bab490506](https://bsd-hardware.info/?probe=7bab490506) | Oct 23, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [03602ed2c0](https://bsd-hardware.info/?probe=03602ed2c0) | Oct 23, 2020 |
| Lenovo        | Unknown                     | Notebook    | [c659708e94](https://bsd-hardware.info/?probe=c659708e94) | Oct 23, 2020 |
| IBM           | ThinkPad X41 2525F8G        | Notebook    | [c58f946d2a](https://bsd-hardware.info/?probe=c58f946d2a) | Oct 22, 2020 |
| PC Engines    | APU2                        | Desktop     | [5cee7fa636](https://bsd-hardware.info/?probe=5cee7fa636) | Oct 22, 2020 |
| MSI           | MS-7345                     | Desktop     | [96cc99accc](https://bsd-hardware.info/?probe=96cc99accc) | Oct 22, 2020 |
| Dell          | Precision 3510              | Notebook    | [85a55ab7c3](https://bsd-hardware.info/?probe=85a55ab7c3) | Oct 22, 2020 |
| MSI           | MS-7816                     | Desktop     | [337e5b8e0c](https://bsd-hardware.info/?probe=337e5b8e0c) | Oct 22, 2020 |
| Lenovo        | ThinkPad E485 20KUCTO1WW    | Notebook    | [f4aa59ba56](https://bsd-hardware.info/?probe=f4aa59ba56) | Oct 22, 2020 |
| ASRock        | DN2800MT                    | Desktop     | [b475aa2ead](https://bsd-hardware.info/?probe=b475aa2ead) | Oct 21, 2020 |
| Intel         | D2500HN                     | Desktop     | [6dbc4dfa33](https://bsd-hardware.info/?probe=6dbc4dfa33) | Oct 21, 2020 |
| Intel         | CRESCENTBAY                 | Desktop     | [42d114559b](https://bsd-hardware.info/?probe=42d114559b) | Oct 21, 2020 |
| PC Engines    | APU2                        | Desktop     | [d1ca549fe7](https://bsd-hardware.info/?probe=d1ca549fe7) | Oct 21, 2020 |
| Lenovo        | ThinkPad X230 2325AJ9       | Notebook    | [176044b6b8](https://bsd-hardware.info/?probe=176044b6b8) | Oct 21, 2020 |
| Lenovo        | ThinkPad S5-S540 20B3001... | Notebook    | [7e6cb69989](https://bsd-hardware.info/?probe=7e6cb69989) | Oct 21, 2020 |
| Dell          | Latitude C400               | Notebook    | [1dcc5e7972](https://bsd-hardware.info/?probe=1dcc5e7972) | Oct 21, 2020 |
| Dell          | Latitude C400               | Notebook    | [8330d23bd7](https://bsd-hardware.info/?probe=8330d23bd7) | Oct 21, 2020 |
| ZOTAC         | XXXXXX                      | Desktop     | [0f8960bdd3](https://bsd-hardware.info/?probe=0f8960bdd3) | Oct 21, 2020 |
| Lenovo        | ThinkPad X60s 17033JM       | Notebook    | [67e701adb7](https://bsd-hardware.info/?probe=67e701adb7) | Oct 21, 2020 |
| Lenovo        | ThinkPad W540 20BG001KUK    | Notebook    | [1b1327ac93](https://bsd-hardware.info/?probe=1b1327ac93) | Oct 21, 2020 |
| IBM           | Board                       | Desktop     | [11b0b7012f](https://bsd-hardware.info/?probe=11b0b7012f) | Oct 21, 2020 |
| IBM           | Board                       | Desktop     | [a92c08a920](https://bsd-hardware.info/?probe=a92c08a920) | Oct 21, 2020 |
| IBM           | Board                       | Desktop     | [80d5f15a63](https://bsd-hardware.info/?probe=80d5f15a63) | Oct 21, 2020 |
| Lenovo        | ThinkPad X230 2325R74       | Notebook    | [82398321f6](https://bsd-hardware.info/?probe=82398321f6) | Oct 21, 2020 |
| Lenovo        | ThinkPad X230 2325R74       | Notebook    | [1cc3cc20e8](https://bsd-hardware.info/?probe=1cc3cc20e8) | Oct 21, 2020 |
| Gigabyte      | GA-MA770T-UD3P              | Desktop     | [2cb76e5886](https://bsd-hardware.info/?probe=2cb76e5886) | Oct 21, 2020 |
| Lenovo        | ThinkPad T430 2347GZU       | Notebook    | [f287de215c](https://bsd-hardware.info/?probe=f287de215c) | Oct 20, 2020 |
| PC Engines    | APU2                        | Desktop     | [e6ee8a14d5](https://bsd-hardware.info/?probe=e6ee8a14d5) | Oct 20, 2020 |
| ASUSTek       | Z170-K                      | Desktop     | [19cb3ccc34](https://bsd-hardware.info/?probe=19cb3ccc34) | Oct 20, 2020 |
| Lenovo        | ThinkPad X230 2325Y36       | Notebook    | [b2e65dd4c5](https://bsd-hardware.info/?probe=b2e65dd4c5) | Oct 20, 2020 |
| Intel         | S3000AH                     | Desktop     | [f5b858601a](https://bsd-hardware.info/?probe=f5b858601a) | Oct 20, 2020 |
| Lenovo        | ThinkPad Edge E531 68852... | Notebook    | [e6b45d36e5](https://bsd-hardware.info/?probe=e6b45d36e5) | Oct 20, 2020 |
| Apple         | MacBookAir7,2               | Notebook    | [901c82d31e](https://bsd-hardware.info/?probe=901c82d31e) | Oct 20, 2020 |
| Intel         | D2500HN                     | Desktop     | [4b432dcb3d](https://bsd-hardware.info/?probe=4b432dcb3d) | Oct 20, 2020 |
| PC Engines    | APU2                        | Desktop     | [b95ef9962d](https://bsd-hardware.info/?probe=b95ef9962d) | Oct 20, 2020 |
| PC Engines    | APU2                        | Desktop     | [aecf376503](https://bsd-hardware.info/?probe=aecf376503) | Oct 20, 2020 |
| Lenovo        | ThinkPad X250 20CLS4WV08    | Notebook    | [2808d1dd6a](https://bsd-hardware.info/?probe=2808d1dd6a) | Oct 20, 2020 |
| Unknown       | Unknown                     | Desktop     | [bedb4a4b37](https://bsd-hardware.info/?probe=bedb4a4b37) | Oct 20, 2020 |
| Lenovo        | ThinkPad T410 2537N24       | Notebook    | [f846609c80](https://bsd-hardware.info/?probe=f846609c80) | Oct 20, 2020 |
| Unknown       | Unknown                     | Desktop     | [a28ef1d2b8](https://bsd-hardware.info/?probe=a28ef1d2b8) | Oct 20, 2020 |
| Lenovo        | ThinkPad X240 20AL00DKRT    | Notebook    | [623801416c](https://bsd-hardware.info/?probe=623801416c) | Oct 20, 2020 |
| Panasonic     | CF-52PFPBSFQ                | Notebook    | [feb1da0406](https://bsd-hardware.info/?probe=feb1da0406) | Oct 20, 2020 |
| PC Engines    | apu1                        | Desktop     | [c77b06b3eb](https://bsd-hardware.info/?probe=c77b06b3eb) | Oct 20, 2020 |
| Intel         | NUC5i3RYB                   | Mini pc     | [3d03473ea9](https://bsd-hardware.info/?probe=3d03473ea9) | Oct 20, 2020 |
| Matsushita... | CF-51RCVDNLM                | Notebook    | [efece2abf7](https://bsd-hardware.info/?probe=efece2abf7) | Oct 20, 2020 |
| Apple         | Macmini7,1                  | Mini pc     | [5caa1e1c7b](https://bsd-hardware.info/?probe=5caa1e1c7b) | Oct 19, 2020 |
| Dell          | PowerEdge R620              | Desktop     | [7671a495d1](https://bsd-hardware.info/?probe=7671a495d1) | Oct 19, 2020 |
| Dell          | PowerEdge R620              | Desktop     | [c1a2bc7a51](https://bsd-hardware.info/?probe=c1a2bc7a51) | Oct 19, 2020 |
| Dell          | PowerEdge R620              | Desktop     | [c1c5ee566c](https://bsd-hardware.info/?probe=c1c5ee566c) | Oct 19, 2020 |
| Dell          | PowerEdge R620              | Desktop     | [af87ddbbaa](https://bsd-hardware.info/?probe=af87ddbbaa) | Oct 19, 2020 |
| ASUSTek       | P10S-I Series               | Desktop     | [1a0e9f0100](https://bsd-hardware.info/?probe=1a0e9f0100) | Oct 19, 2020 |
| ASUSTek       | K53SV                       | Notebook    | [e776458c9e](https://bsd-hardware.info/?probe=e776458c9e) | Oct 19, 2020 |
| Lenovo        | ThinkPad T560 20FJS0CE00    | Notebook    | [be16cb1839](https://bsd-hardware.info/?probe=be16cb1839) | Oct 19, 2020 |
| Lenovo        | ThinkPad X240 20AMS2QD0C    | Notebook    | [fdc7310ca7](https://bsd-hardware.info/?probe=fdc7310ca7) | Oct 19, 2020 |
| Unknown       | Unknown                     | Desktop     | [a3db8641e6](https://bsd-hardware.info/?probe=a3db8641e6) | Oct 19, 2020 |
| ASUSTek       | 1000HE                      | Notebook    | [621df26e0c](https://bsd-hardware.info/?probe=621df26e0c) | Oct 19, 2020 |
| PC Engines    | apu4                        | Desktop     | [e4cd6d0b48](https://bsd-hardware.info/?probe=e4cd6d0b48) | Oct 19, 2020 |
| PC Engines    | APU                         | Desktop     | [0cf4f6a5f9](https://bsd-hardware.info/?probe=0cf4f6a5f9) | Oct 19, 2020 |
| Lenovo        | SHARKBAY WIN                | Desktop     | [53feb1fec6](https://bsd-hardware.info/?probe=53feb1fec6) | Oct 19, 2020 |
| ASRock        | IMB-191                     | Desktop     | [4ac9e9cf2a](https://bsd-hardware.info/?probe=4ac9e9cf2a) | Oct 19, 2020 |
| PC Engines    | APU2                        | Desktop     | [064e7167a0](https://bsd-hardware.info/?probe=064e7167a0) | Oct 19, 2020 |
| Dell          | OptiPlex 3060               | Desktop     | [13992dbb10](https://bsd-hardware.info/?probe=13992dbb10) | Oct 19, 2020 |
| PC Engines    | APU2                        | Desktop     | [a5b1c3a559](https://bsd-hardware.info/?probe=a5b1c3a559) | Oct 19, 2020 |
| Acer          | Aspire 5251                 | Notebook    | [da9ebcf25e](https://bsd-hardware.info/?probe=da9ebcf25e) | Oct 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [857f9809b7](https://bsd-hardware.info/?probe=857f9809b7) | Oct 19, 2020 |
| Dell          | PowerEdge T320              | Desktop     | [75c395f941](https://bsd-hardware.info/?probe=75c395f941) | Oct 19, 2020 |
| Dell          | PowerEdge 1950              | Desktop     | [3cfcdfce6d](https://bsd-hardware.info/?probe=3cfcdfce6d) | Oct 19, 2020 |
| Dell          | PowerEdge 1950              | Desktop     | [0865193e7e](https://bsd-hardware.info/?probe=0865193e7e) | Oct 19, 2020 |
| Dell          | PowerEdge R610              | Desktop     | [2ea539bbd3](https://bsd-hardware.info/?probe=2ea539bbd3) | Oct 19, 2020 |
| Dell          | OptiPlex 7020               | Desktop     | [293e6af35e](https://bsd-hardware.info/?probe=293e6af35e) | Oct 19, 2020 |
| Lenovo        | ThinkPad X270 20HNA004CD    | Notebook    | [79160b17c4](https://bsd-hardware.info/?probe=79160b17c4) | Oct 19, 2020 |
| PC Engines    | APU2                        | Desktop     | [2ab3051cb8](https://bsd-hardware.info/?probe=2ab3051cb8) | Oct 19, 2020 |
| PC Engines    | apu4                        | Desktop     | [f0116986e0](https://bsd-hardware.info/?probe=f0116986e0) | Oct 19, 2020 |
| IBM           | Board                       | Desktop     | [af2f64a7a8](https://bsd-hardware.info/?probe=af2f64a7a8) | Oct 19, 2020 |
| ASUSTek       | X102BA                      | Notebook    | [47e04c9378](https://bsd-hardware.info/?probe=47e04c9378) | Oct 19, 2020 |
| Lenovo        | G50-80 80E5                 | Notebook    | [e06605a92b](https://bsd-hardware.info/?probe=e06605a92b) | Oct 19, 2020 |
| Panasonic     | CF-C1BT02EGE                | Notebook    | [8a80fb614e](https://bsd-hardware.info/?probe=8a80fb614e) | Oct 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [bee732e516](https://bsd-hardware.info/?probe=bee732e516) | Oct 19, 2020 |
| Apple         | PowerBook6,7                | Notebook    | [7ac5f5530a](https://bsd-hardware.info/?probe=7ac5f5530a) | Oct 19, 2020 |
| Foxconn       | AT-7000 Series              | Desktop     | [dc7b96e637](https://bsd-hardware.info/?probe=dc7b96e637) | Oct 19, 2020 |
| Foxconn       | AT-7000 Series              | Desktop     | [0184fcedcf](https://bsd-hardware.info/?probe=0184fcedcf) | Oct 19, 2020 |
| Alienware     | m15                         | Notebook    | [8f8cf7d956](https://bsd-hardware.info/?probe=8f8cf7d956) | Oct 19, 2020 |
| Lenovo        | ThinkPad T480 20L6S4GR02    | Notebook    | [6c2d8a57ea](https://bsd-hardware.info/?probe=6c2d8a57ea) | Oct 19, 2020 |
| ASUSTek       | PRIME X570-P                | Desktop     | [b33e2a5177](https://bsd-hardware.info/?probe=b33e2a5177) | Oct 19, 2020 |
| PC Engines    | apu1                        | Desktop     | [576f4db9e1](https://bsd-hardware.info/?probe=576f4db9e1) | Oct 19, 2020 |
| PC Engines    | APU2                        | Desktop     | [e4030e5ee2](https://bsd-hardware.info/?probe=e4030e5ee2) | Oct 19, 2020 |
| PC Engines    | APU2                        | Desktop     | [ca0480a30d](https://bsd-hardware.info/?probe=ca0480a30d) | Oct 19, 2020 |
| Bluechip C... | bluechip BUSINESSline Wo... | Desktop     | [6dc86d6a5b](https://bsd-hardware.info/?probe=6dc86d6a5b) | Oct 19, 2020 |
| Unknown       | Unknown                     | Notebook    | [fd77b4658f](https://bsd-hardware.info/?probe=fd77b4658f) | Oct 19, 2020 |
| Apple         | MacBookAir6,2               | Notebook    | [9f80fdafb0](https://bsd-hardware.info/?probe=9f80fdafb0) | Oct 19, 2020 |
| Unknown       | Unknown                     | Desktop     | [e36fc2b2b2](https://bsd-hardware.info/?probe=e36fc2b2b2) | Oct 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X545... | Notebook    | [017b41dfd7](https://bsd-hardware.info/?probe=017b41dfd7) | Oct 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [4f54c8f399](https://bsd-hardware.info/?probe=4f54c8f399) | Oct 19, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [027fbd78f5](https://bsd-hardware.info/?probe=027fbd78f5) | Oct 19, 2020 |
| HP            | OmniBook PC                 | Notebook    | [0e0656d228](https://bsd-hardware.info/?probe=0e0656d228) | Oct 19, 2020 |
| HP            | OmniBook PC                 | Notebook    | [60e72f1c10](https://bsd-hardware.info/?probe=60e72f1c10) | Oct 19, 2020 |
| Lenovo        | ThinkPad T460 20FMS1BC01    | Notebook    | [bf6d6d155b](https://bsd-hardware.info/?probe=bf6d6d155b) | Oct 19, 2020 |
| Lenovo        | 3000 N100 0768B9G           | Notebook    | [c44a86f589](https://bsd-hardware.info/?probe=c44a86f589) | Oct 19, 2020 |
| ASRock        | A75M-ITX                    | Desktop     | [dff827c2ae](https://bsd-hardware.info/?probe=dff827c2ae) | Oct 19, 2020 |
| PC Engines    | apu1                        | Desktop     | [8aade944d5](https://bsd-hardware.info/?probe=8aade944d5) | Oct 19, 2020 |
| ASUSTek       | G551JW                      | Notebook    | [594e6f28fb](https://bsd-hardware.info/?probe=594e6f28fb) | Oct 19, 2020 |
| PC Engines    | apu4                        | Desktop     | [ee8a1317f9](https://bsd-hardware.info/?probe=ee8a1317f9) | Oct 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [ee1f866775](https://bsd-hardware.info/?probe=ee1f866775) | Oct 13, 2020 |
| Lenovo        | ThinkPad X395 20NL000HGE    | Notebook    | [fbf90aaf0d](https://bsd-hardware.info/?probe=fbf90aaf0d) | Sep 11, 2020 |
| Lenovo        | ThinkPad X395 20NL000HGE    | Notebook    | [e06815d9dc](https://bsd-hardware.info/?probe=e06815d9dc) | Sep 11, 2020 |
| Lenovo        | ThinkPad X230 2325Y36       | Notebook    | [1f28f1c311](https://bsd-hardware.info/?probe=1f28f1c311) | Aug 30, 2020 |
| Lenovo        | ThinkPad X230 2325Y36       | Notebook    | [11a0bbb73f](https://bsd-hardware.info/?probe=11a0bbb73f) | Aug 30, 2020 |
| Protectli     | FW6                         | Desktop     | [1454991c98](https://bsd-hardware.info/?probe=1454991c98) | Aug 27, 2020 |
| PC Engines    | apu4                        | Desktop     | [8f4ed98a45](https://bsd-hardware.info/?probe=8f4ed98a45) | Aug 21, 2020 |
| Lenovo        | ThinkPad P40 Yoga 20GQ00... | Notebook    | [ac92b69122](https://bsd-hardware.info/?probe=ac92b69122) | Aug 20, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [3032cd9409](https://bsd-hardware.info/?probe=3032cd9409) | Aug 20, 2020 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [547b36ea62](https://bsd-hardware.info/?probe=547b36ea62) | Aug 19, 2020 |
| HCL Infosy... | Calistoga & ICH7M Chipse... | Notebook    | [6adc98922d](https://bsd-hardware.info/?probe=6adc98922d) | Aug 19, 2020 |
| Gigabyte      | X58A-UD5                    | Desktop     | [63a429ad0e](https://bsd-hardware.info/?probe=63a429ad0e) | Aug 16, 2020 |
| Dell          | OptiPlex 745                | Desktop     | [6de04c2c9c](https://bsd-hardware.info/?probe=6de04c2c9c) | Aug 14, 2020 |
| IBM           | ThinkPad T42 2373K9G        | Notebook    | [fa35e7ec26](https://bsd-hardware.info/?probe=fa35e7ec26) | Aug 11, 2020 |
| PC Engines    | apu4                        | Desktop     | [f0f8a22656](https://bsd-hardware.info/?probe=f0f8a22656) | Aug 05, 2020 |
| Intel         | ChiefRiver                  | Desktop     | [022d2761b9](https://bsd-hardware.info/?probe=022d2761b9) | Aug 03, 2020 |
| PC Engines    | APU3                        | Desktop     | [1eaf8a1484](https://bsd-hardware.info/?probe=1eaf8a1484) | Aug 03, 2020 |
| PC Engines    | APU3                        | Desktop     | [4980462667](https://bsd-hardware.info/?probe=4980462667) | Aug 03, 2020 |
| PC Engines    | APU3                        | Desktop     | [975e23e09d](https://bsd-hardware.info/?probe=975e23e09d) | Aug 03, 2020 |
| HP            | ZBook 15 G4                 | Notebook    | [a8953b4964](https://bsd-hardware.info/?probe=a8953b4964) | Aug 03, 2020 |
| HP            | ZBook 15 G4                 | Notebook    | [a97053c5d4](https://bsd-hardware.info/?probe=a97053c5d4) | Aug 03, 2020 |
| Shuttle       | DS437                       | Desktop     | [aa350b6b92](https://bsd-hardware.info/?probe=aa350b6b92) | Aug 03, 2020 |
| PC Engines    | APU2                        | Desktop     | [fe5c2f4838](https://bsd-hardware.info/?probe=fe5c2f4838) | Aug 03, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [20f3e760eb](https://bsd-hardware.info/?probe=20f3e760eb) | Aug 03, 2020 |
| Lenovo        | ThinkPad W540 20BG001KUK    | Notebook    | [f3e2acbb66](https://bsd-hardware.info/?probe=f3e2acbb66) | Jul 31, 2020 |
| Lenovo        | ThinkPad W540 20BG001KUK    | Notebook    | [7ae8c247e9](https://bsd-hardware.info/?probe=7ae8c247e9) | Jul 31, 2020 |
| Lenovo        | ThinkPad T60 87445BU        | Notebook    | [37a42caa92](https://bsd-hardware.info/?probe=37a42caa92) | Jul 30, 2020 |
| Lenovo        | ThinkCentre M92p 3212AD2    | Desktop     | [ca76cc5467](https://bsd-hardware.info/?probe=ca76cc5467) | Jul 30, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [ac13b0591f](https://bsd-hardware.info/?probe=ac13b0591f) | Jul 27, 2020 |
| ASRock        | E350M1                      | Desktop     | [08eec78cdf](https://bsd-hardware.info/?probe=08eec78cdf) | Jul 25, 2020 |
| Pegatron      | 2A73                        | Desktop     | [05dea28605](https://bsd-hardware.info/?probe=05dea28605) | Jul 21, 2020 |
| PC Engines    | apu4                        | Desktop     | [52c611855b](https://bsd-hardware.info/?probe=52c611855b) | Jul 12, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [c1f2cdf7a8](https://bsd-hardware.info/?probe=c1f2cdf7a8) | Jul 03, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [b79f3127ee](https://bsd-hardware.info/?probe=b79f3127ee) | Jul 03, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [dfef5fdcbf](https://bsd-hardware.info/?probe=dfef5fdcbf) | Jun 10, 2020 |
| ASUSTek       | All Series                  | Desktop     | [e4f1a19012](https://bsd-hardware.info/?probe=e4f1a19012) | Jun 05, 2020 |
| Toshiba       | Satellite L775D             | Notebook    | [bb218a14a6](https://bsd-hardware.info/?probe=bb218a14a6) | Jun 03, 2020 |
| Toshiba       | Satellite L775D             | Notebook    | [f0ec90217a](https://bsd-hardware.info/?probe=f0ec90217a) | Jun 03, 2020 |
| Unknown       | Unknown                     | Desktop     | [4e3b87cc6c](https://bsd-hardware.info/?probe=4e3b87cc6c) | Jun 01, 2020 |
| Lenovo        | ThinkPad X220 4291C35       | Notebook    | [f22c83f68b](https://bsd-hardware.info/?probe=f22c83f68b) | May 31, 2020 |
| Panasonic     | CF-19ADUAX1M                | Notebook    | [cefc742c62](https://bsd-hardware.info/?probe=cefc742c62) | May 29, 2020 |
| Sony UK       | Raspberry Pi 4 Model B      | Desktop     | [483af3998c](https://bsd-hardware.info/?probe=483af3998c) | May 28, 2020 |
| Unknown       | Unknown                     | Desktop     | [80a1eda96f](https://bsd-hardware.info/?probe=80a1eda96f) | May 28, 2020 |
| Dell          | PowerEdge T320              | Desktop     | [eec750b5c5](https://bsd-hardware.info/?probe=eec750b5c5) | May 28, 2020 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [08534174df](https://bsd-hardware.info/?probe=08534174df) | May 27, 2020 |
| Unknown       | TI AM335x BeagleBone Bla... | Desktop     | [8e0f831fd8](https://bsd-hardware.info/?probe=8e0f831fd8) | May 27, 2020 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [03ea0992c4](https://bsd-hardware.info/?probe=03ea0992c4) | May 27, 2020 |
| IBM           | Board                       | Desktop     | [1bcc2b8e0b](https://bsd-hardware.info/?probe=1bcc2b8e0b) | May 27, 2020 |
| Unknown       | TI AM335x BeagleBone Bla... | Desktop     | [74b9526162](https://bsd-hardware.info/?probe=74b9526162) | May 27, 2020 |
| Fujitsu       | LIFEBOOK A357               | Notebook    | [b02640458b](https://bsd-hardware.info/?probe=b02640458b) | May 26, 2020 |
| Lenovo        | ThinkPad X230 2324A57       | Notebook    | [6ea713bf51](https://bsd-hardware.info/?probe=6ea713bf51) | May 25, 2020 |
| Lenovo        | ThinkPad X230 2324A57       | Notebook    | [7b67911c5a](https://bsd-hardware.info/?probe=7b67911c5a) | May 25, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [b4ca8bbc46](https://bsd-hardware.info/?probe=b4ca8bbc46) | May 25, 2020 |
| Gigabyte      | Unknown                     | Desktop     | [576771182b](https://bsd-hardware.info/?probe=576771182b) | May 25, 2020 |
| Gigabyte      | Unknown                     | Desktop     | [05e8154b2c](https://bsd-hardware.info/?probe=05e8154b2c) | May 25, 2020 |
| Lenovo        | ThinkPad T420 4180B39       | Notebook    | [916596bfa8](https://bsd-hardware.info/?probe=916596bfa8) | May 25, 2020 |
| IBM           | ThinkPad X41 2525FAG        | Notebook    | [1e849f86cf](https://bsd-hardware.info/?probe=1e849f86cf) | May 25, 2020 |
| ASUSTek       | P4P800-VM                   | Desktop     | [8b9481baf2](https://bsd-hardware.info/?probe=8b9481baf2) | May 25, 2020 |
| ASUSTek       | P4P800-VM                   | Desktop     | [33c4579f99](https://bsd-hardware.info/?probe=33c4579f99) | May 25, 2020 |
| Lenovo        | ThinkPad T440 20B7S1C600    | Notebook    | [a4a62cb85e](https://bsd-hardware.info/?probe=a4a62cb85e) | May 24, 2020 |
| Lenovo        | ThinkPad T440s 20AR003VM... | Notebook    | [3f72b76851](https://bsd-hardware.info/?probe=3f72b76851) | May 23, 2020 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | Notebook    | [fa71e5839a](https://bsd-hardware.info/?probe=fa71e5839a) | May 23, 2020 |
| Lenovo        | ThinkPad X260 20F5S1H800    | Notebook    | [85567202a8](https://bsd-hardware.info/?probe=85567202a8) | May 23, 2020 |
| Lenovo        | ThinkPad T440p 20AN00DEU... | Notebook    | [9ff1537692](https://bsd-hardware.info/?probe=9ff1537692) | May 23, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [8212868b9f](https://bsd-hardware.info/?probe=8212868b9f) | May 19, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [bdd93164cf](https://bsd-hardware.info/?probe=bdd93164cf) | May 17, 2020 |
| ASUSTek       | A3L                         | Notebook    | [0c73038abc](https://bsd-hardware.info/?probe=0c73038abc) | May 06, 2020 |
| ASUSTek       | A3L                         | Notebook    | [ff5b6e3024](https://bsd-hardware.info/?probe=ff5b6e3024) | May 06, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenBSD/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OpenBSD 6.8 | 208       | 30.91%  |
| OpenBSD 7.2 | 95        | 14.12%  |
| OpenBSD 7.1 | 93        | 13.82%  |
| OpenBSD 6.9 | 89        | 13.22%  |
| OpenBSD 7.0 | 88        | 13.08%  |
| OpenBSD 6.7 | 50        | 7.43%   |
| OpenBSD 7.3 | 47        | 6.98%   |
| OpenBSD 6.6 | 3         | 0.45%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| OpenBSD | 559       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| amd64   | 481       | 85.89%  |
| i386    | 46        | 8.21%   |
| arm64   | 20        | 3.57%   |
| macppc  | 6         | 1.07%   |
| sparc64 | 3         | 0.54%   |
| octeon  | 2         | 0.36%   |
| armv7   | 2         | 0.36%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| fvwm          | 273       | 46.04%  |
| helloDesktop  | 161       | 27.15%  |
| Console       | 116       | 19.56%  |
| XFCE          | 21        | 3.54%   |
| GNOME         | 10        | 1.69%   |
| MATE          | 3         | 0.51%   |
| i3            | 3         | 0.51%   |
| Mutter        | 2         | 0.34%   |
| Openbox       | 1         | 0.17%   |
| Lumina        | 1         | 0.17%   |
| iwm           | 1         | 0.17%   |
| Enlightenment | 1         | 0.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 402       | 71.15%  |
| Console | 163       | 28.85%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 515       | 90.67%  |
| SLiM    | 31        | 5.46%   |
| GDM     | 22        | 3.87%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 454       | 79.51%  |
| en_US      | 47        | 8.23%   |
| ru_RU      | 23        | 4.03%   |
| C          | 15        | 2.63%   |
| fr_FR      | 7         | 1.23%   |
| en_GB      | 5         | 0.88%   |
| de_DE      | 4         | 0.7%    |
| pl_PL      | 2         | 0.35%   |
| ja_JP      | 2         | 0.35%   |
| es_ES      | 2         | 0.35%   |
| es_CO      | 2         | 0.35%   |
| en_AU      | 2         | 0.35%   |
| zh_TW      | 1         | 0.18%   |
| zh_CN      | 1         | 0.18%   |
| ISO8859-15 | 1         | 0.18%   |
| fr_CA      | 1         | 0.18%   |
| en_EN      | 1         | 0.18%   |
| en_CA      | 1         | 0.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 285       | 50.35%  |
| EFI  | 281       | 49.65%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ffs  | 559       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 313       | 55.5%   |
| GPT     | 247       | 43.79%  |
| Unknown | 4         | 0.71%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 150       | 26.83%  |
| ASUSTek Computer               | 51        | 9.12%   |
| Dell                           | 41        | 7.33%   |
| Hewlett-Packard                | 38        | 6.8%    |
| PC Engines                     | 33        | 5.9%    |
| Unknown                        | 28        | 5.01%   |
| Gigabyte Technology            | 24        | 4.29%   |
| Apple                          | 24        | 4.29%   |
| MSI                            | 17        | 3.04%   |
| ASRock                         | 16        | 2.86%   |
| Intel                          | 15        | 2.68%   |
| Acer                           | 14        | 2.5%    |
| Supermicro                     | 10        | 1.79%   |
| IBM                            | 8         | 1.43%   |
| Panasonic                      | 7         | 1.25%   |
| Raspberry Pi Foundation        | 6         | 1.07%   |
| Fujitsu                        | 6         | 1.07%   |
| Sony                           | 5         | 0.89%   |
| TUXEDO                         | 4         | 0.72%   |
| Samsung Electronics            | 4         | 0.72%   |
| Toshiba                        | 3         | 0.54%   |
| Sun                            | 3         | 0.54%   |
| Soekris Engineering            | 3         | 0.54%   |
| Microsoft                      | 3         | 0.54%   |
| Framework                      | 3         | 0.54%   |
| Alienware                      | 3         | 0.54%   |
| Shuttle                        | 2         | 0.36%   |
| Pegatron                       | 2         | 0.36%   |
| Matsushita Electric Industrial | 2         | 0.36%   |
| Google                         | 2         | 0.36%   |
| Clevo                          | 2         | 0.36%   |
| Biostar                        | 2         | 0.36%   |
| ZOTAC                          | 1         | 0.18%   |
| Yanling                        | 1         | 0.18%   |
| WYSE                           | 1         | 0.18%   |
| VIA Technologies               | 1         | 0.18%   |
| Unknown                        | 1         | 0.18%   |
| Tactus                         | 1         | 0.18%   |
| Star Labs                      | 1         | 0.18%   |
| Standard                       | 1         | 0.18%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 33        | 5.9%    |
| PC Engines APU2                          | 15        | 2.68%   |
| PC Engines apu4                          | 9         | 1.61%   |
| Lenovo ThinkPad X200 745969G             | 6         | 1.07%   |
| PC Engines apu1                          | 5         | 0.89%   |
| Dell PowerEdge R620                      | 5         | 0.89%   |
| ASUS All Series                          | 4         | 0.72%   |
| Supermicro Super Server                  | 3         | 0.54%   |
| RPi Raspberry Pi 400                     | 3         | 0.54%   |
| RPi Raspberry Pi 4 Model B               | 3         | 0.54%   |
| PC Engines APU3                          | 3         | 0.54%   |
| ASUS PRIME H410M-A                       | 3         | 0.54%   |
| TUXEDO Pulse 15 Gen1                     | 2         | 0.36%   |
| Soekris Engineering net6501              | 2         | 0.36%   |
| MSI MS-7A34                              | 2         | 0.36%   |
| Microsoft Surface Pro 7                  | 2         | 0.36%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BSCTO1WW | 2         | 0.36%   |
| HP ZBook 15 G4                           | 2         | 0.36%   |
| Gigabyte M68MT-S2P                       | 2         | 0.36%   |
| Fujitsu LIFEBOOK E752                    | 2         | 0.36%   |
| Framework Laptop                         | 2         | 0.36%   |
| Dell XPS 13 9360                         | 2         | 0.36%   |
| ASUS X102BA                              | 2         | 0.36%   |
| ASUS PRIME X370-PRO                      | 2         | 0.36%   |
| Apple MacBookAir7,2                      | 2         | 0.36%   |
| Apple MacBookAir6,2                      | 2         | 0.36%   |
| Apple MacBook5,1                         | 2         | 0.36%   |
| Acer Nitro AN515-55                      | 2         | 0.36%   |
| ZOTAC XXXXXX                             | 1         | 0.18%   |
| Yanling YL-KBR6L                         | 1         | 0.18%   |
| WYSE D CLASS                             | 1         | 0.18%   |
| VIA VT82C597                             | 1         | 0.18%   |
| TUXEDO InfinityBook Pro 14 Gen6          | 1         | 0.18%   |
| TUXEDO Aura 15 Gen1                      | 1         | 0.18%   |
| Toshiba Satellite L775D                  | 1         | 0.18%   |
| Toshiba Satellite BE96-F299              | 1         | 0.18%   |
| Toshiba NB250                            | 1         | 0.18%   |
| Tactus GeoFlex 110                       | 1         | 0.18%   |
| Supermicro X8STi                         | 1         | 0.18%   |
| Supermicro X8DTH-i/6/iF/6F               | 1         | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Lenovo ThinkPad             | 124       | 22.18%  |
| Unknown                     | 33        | 5.9%    |
| PC Engines APU2             | 15        | 2.68%   |
| ASUS PRIME                  | 14        | 2.5%    |
| Dell PowerEdge              | 10        | 1.79%   |
| PC Engines apu4             | 9         | 1.61%   |
| Dell OptiPlex               | 8         | 1.43%   |
| Lenovo ThinkCentre          | 7         | 1.25%   |
| RPi Raspberry               | 6         | 1.07%   |
| Lenovo IdeaPad              | 6         | 1.07%   |
| PC Engines apu1             | 5         | 0.89%   |
| IBM ThinkPad                | 5         | 0.89%   |
| HP Pavilion                 | 5         | 0.89%   |
| Fujitsu LIFEBOOK            | 5         | 0.89%   |
| Dell Latitude               | 5         | 0.89%   |
| Acer Aspire                 | 5         | 0.89%   |
| HP ProLiant                 | 4         | 0.72%   |
| HP Compaq                   | 4         | 0.72%   |
| Dell XPS                    | 4         | 0.72%   |
| Dell Precision              | 4         | 0.72%   |
| Dell Inspiron               | 4         | 0.72%   |
| ASUS All                    | 4         | 0.72%   |
| Supermicro Super            | 3         | 0.54%   |
| Sun SUNW                    | 3         | 0.54%   |
| PC Engines APU3             | 3         | 0.54%   |
| Microsoft Surface           | 3         | 0.54%   |
| Lenovo Yoga                 | 3         | 0.54%   |
| HP ProBook                  | 3         | 0.54%   |
| Framework Laptop            | 3         | 0.54%   |
| Dell Vostro                 | 3         | 0.54%   |
| ASUS VivoBook               | 3         | 0.54%   |
| ASUS ROG                    | 3         | 0.54%   |
| Apple MacBookAir6           | 3         | 0.54%   |
| TUXEDO Pulse                | 2         | 0.36%   |
| Toshiba Satellite           | 2         | 0.36%   |
| Soekris Engineering net6501 | 2         | 0.36%   |
| MSI MS-7A34                 | 2         | 0.36%   |
| Lenovo Flex                 | 2         | 0.36%   |
| HP ZBook                    | 2         | 0.36%   |
| HP EliteBook                | 2         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 56        | 10.02%  |
| 2019    | 55        | 9.84%   |
| 2018    | 51        | 9.12%   |
| 2021    | 39        | 6.98%   |
| Unknown | 37        | 6.62%   |
| 2015    | 33        | 5.9%    |
| 2016    | 31        | 5.55%   |
| 2011    | 31        | 5.55%   |
| 2013    | 28        | 5.01%   |
| 2012    | 27        | 4.83%   |
| 2010    | 25        | 4.47%   |
| 2022    | 24        | 4.29%   |
| 2017    | 23        | 4.11%   |
| 2009    | 23        | 4.11%   |
| 2014    | 22        | 3.94%   |
| 2007    | 14        | 2.5%    |
| 2008    | 13        | 2.33%   |
| 2006    | 11        | 1.97%   |
| 2023    | 5         | 0.89%   |
| 2005    | 3         | 0.54%   |
| 2004    | 3         | 0.54%   |
| 2003    | 3         | 0.54%   |
| 2002    | 1         | 0.18%   |
| 2001    | 1         | 0.18%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 277       | 49.55%  |
| Desktop     | 262       | 46.87%  |
| Mini pc     | 7         | 1.25%   |
| Server      | 5         | 0.89%   |
| All in one  | 4         | 0.72%   |
| Tablet      | 3         | 0.54%   |
| Convertible | 1         | 0.18%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 516       | 92.31%  |
| Yes  | 43        | 7.69%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 152       | 26.81%  |
| 4.01-8.0        | 116       | 20.46%  |
| 16.01-24.0      | 87        | 15.34%  |
| 3.01-4.0        | 54        | 9.52%   |
| 32.01-64.0      | 40        | 7.05%   |
| 2.01-3.0        | 29        | 5.11%   |
| 1.01-2.0        | 27        | 4.76%   |
| 0.51-1.0        | 19        | 3.35%   |
| 64.01-256.0     | 18        | 3.17%   |
| 0.01-0.5        | 12        | 2.12%   |
| 24.01-32.0      | 10        | 1.76%   |
| More than 256.0 | 3         | 0.53%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 448       | 79.43%  |
| 0.51-1.0   | 46        | 8.16%   |
| 0          | 38        | 6.74%   |
| 1.01-2.0   | 15        | 2.66%   |
| Unknown    | 7         | 1.24%   |
| 4.01-8.0   | 5         | 0.89%   |
| 3.01-4.0   | 2         | 0.35%   |
| 8.01-16.0  | 2         | 0.35%   |
| 16.01-24.0 | 1         | 0.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 290       | 49.83%  |
| 2      | 177       | 30.41%  |
| 3      | 60        | 10.31%  |
| 4      | 27        | 4.64%   |
| 0      | 12        | 2.06%   |
| 5      | 5         | 0.86%   |
| 6      | 4         | 0.69%   |
| 10     | 2         | 0.34%   |
| 7      | 2         | 0.34%   |
| 14     | 1         | 0.17%   |
| 12     | 1         | 0.17%   |
| 8      | 1         | 0.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 555       | 99.11%  |
| Yes       | 5         | 0.89%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 482       | 86.23%  |
| No        | 77        | 13.77%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 345       | 61.61%  |
| No        | 215       | 38.39%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 340       | 60.5%   |
| Yes       | 222       | 39.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 100       | 17.76%  |
| Russia       | 68        | 12.08%  |
| Germany      | 68        | 12.08%  |
| France       | 38        | 6.75%   |
| Canada       | 25        | 4.44%   |
| UK           | 24        | 4.26%   |
| Netherlands  | 23        | 4.09%   |
| Poland       | 22        | 3.91%   |
| Italy        | 19        | 3.37%   |
| Sweden       | 16        | 2.84%   |
| Spain        | 15        | 2.66%   |
| Switzerland  | 13        | 2.31%   |
| Ukraine      | 10        | 1.78%   |
| Brazil       | 9         | 1.6%    |
| Australia    | 9         | 1.6%    |
| Norway       | 8         | 1.42%   |
| Austria      | 8         | 1.42%   |
| Taiwan       | 6         | 1.07%   |
| Mexico       | 5         | 0.89%   |
| Romania      | 4         | 0.71%   |
| Latvia       | 4         | 0.71%   |
| Japan        | 4         | 0.71%   |
| India        | 4         | 0.71%   |
| Czechia      | 4         | 0.71%   |
| Uruguay      | 3         | 0.53%   |
| Portugal     | 3         | 0.53%   |
| Philippines  | 3         | 0.53%   |
| Finland      | 3         | 0.53%   |
| Cyprus       | 3         | 0.53%   |
| Croatia      | 3         | 0.53%   |
| Colombia     | 3         | 0.53%   |
| Bulgaria     | 3         | 0.53%   |
| Turkey       | 2         | 0.36%   |
| Slovakia     | 2         | 0.36%   |
| Saudi Arabia | 2         | 0.36%   |
| Malaysia     | 2         | 0.36%   |
| Indonesia    | 2         | 0.36%   |
| Egypt        | 2         | 0.36%   |
| Denmark      | 2         | 0.36%   |
| Argentina    | 2         | 0.36%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 19        | 3.13%   |
| Montreal          | 16        | 2.64%   |
| Saint-Laurent     | 14        | 2.31%   |
| Amsterdam         | 14        | 2.31%   |
| Berlin            | 13        | 2.14%   |
| Paris             | 12        | 1.98%   |
| Vladivostok       | 11        | 1.81%   |
| St Petersburg     | 9         | 1.48%   |
| Gdansk            | 7         | 1.15%   |
| Zurich            | 6         | 0.99%   |
| Vienna            | 6         | 0.99%   |
| New Taipei        | 6         | 0.99%   |
| Sydney            | 5         | 0.82%   |
| QuГ©bec         | 5         | 0.82%   |
| Puebla City       | 5         | 0.82%   |
| Milan             | 5         | 0.82%   |
| Brooklyn          | 5         | 0.82%   |
| Blumenau          | 5         | 0.82%   |
| Sun Prairie       | 4         | 0.66%   |
| Riga              | 4         | 0.66%   |
| Poortugaal        | 4         | 0.66%   |
| Oslo              | 4         | 0.66%   |
| Nuremberg         | 4         | 0.66%   |
| Miedziana Gora    | 4         | 0.66%   |
| Malmo             | 4         | 0.66%   |
| Ibiza Town        | 4         | 0.66%   |
| Gummersbach       | 4         | 0.66%   |
| Frankfurt am Main | 4         | 0.66%   |
| Yekaterinburg     | 3         | 0.49%   |
| Wittersham        | 3         | 0.49%   |
| Syeverodonets'k   | 3         | 0.49%   |
| Sofia             | 3         | 0.49%   |
| Portland          | 3         | 0.49%   |
| Montevideo        | 3         | 0.49%   |
| Los Angeles       | 3         | 0.49%   |
| London            | 3         | 0.49%   |
| Lausanne          | 3         | 0.49%   |
| Larnaca           | 3         | 0.49%   |
| Lafayette         | 3         | 0.49%   |
| Krakow            | 3         | 0.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| NVMe                | 122       | 168    | 16.78%  |
| Samsung Electronics | 86        | 144    | 11.83%  |
| WDC                 | 80        | 134    | 11%     |
| Seagate             | 72        | 121    | 9.9%    |
| Kingston            | 38        | 50     | 5.23%   |
| SanDisk             | 30        | 37     | 4.13%   |
| Toshiba             | 29        | 45     | 3.99%   |
| Crucial             | 29        | 40     | 3.99%   |
| Hitachi             | 24        | 38     | 3.3%    |
| OPENBSD             | 16        | 26     | 2.2%    |
| Intel               | 16        | 21     | 2.2%    |
| Phison              | 14        | 16     | 1.93%   |
| HGST                | 14        | 25     | 1.93%   |
| Apple               | 11        | 11     | 1.51%   |
| Transcend           | 10        | 17     | 1.38%   |
| PNY                 | 8         | 9      | 1.1%    |
| A-DATA Technology   | 8         | 13     | 1.1%    |
| SK hynix            | 7         | 7      | 0.96%   |
| Dell                | 7         | 12     | 0.96%   |
| Apacer              | 6         | 7      | 0.83%   |
| USB                 | 5         | 5      | 0.69%   |
| SPCC                | 4         | 4      | 0.55%   |
| Hewlett-Packard     | 4         | 9      | 0.55%   |
| Generic             | 4         | 4      | 0.55%   |
| Patriot             | 3         | 3      | 0.41%   |
| OCZ                 | 3         | 3      | 0.41%   |
| LSI                 | 3         | 6      | 0.41%   |
| KingSpec            | 3         | 3      | 0.41%   |
| Innostor            | 3         | 3      | 0.41%   |
| Corsair             | 3         | 3      | 0.41%   |
| Team                | 2         | 2      | 0.28%   |
| StoreJet            | 2         | 2      | 0.28%   |
| Plextor             | 2         | 2      | 0.28%   |
| Netac               | 2         | 2      | 0.28%   |
| Multiple            | 2         | 2      | 0.28%   |
| Micron Technology   | 2         | 2      | 0.28%   |
| Maxtor              | 2         | 3      | 0.28%   |
| LITEONIT            | 2         | 2      | 0.28%   |
| Lexar               | 2         | 2      | 0.28%   |
| Intenso             | 2         | 2      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| OPENBSD SR RAID 1 2TB               | 13        | 1.66%   |
| NVMe Samsung SSD 980 500GB          | 13        | 1.66%   |
| Phison SATA SSD 16GB                | 11        | 1.4%    |
| NVMe Samsung SSD 970 250GB          | 9         | 1.15%   |
| Seagate ST1000LM035-1RK172 1TB      | 8         | 1.02%   |
| NVMe WDC PC SN730 SDB 256GB         | 8         | 1.02%   |
| Samsung HM321HI 320GB               | 6         | 0.76%   |
| Kingston SA400S37240G 240GB         | 6         | 0.76%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 5         | 0.64%   |
| USB SanDisk 3.2Gen1 16GB            | 5         | 0.64%   |
| Samsung SSD 850 EVO 500GB           | 5         | 0.64%   |
| NVMe SAMSUNG MZVLB256 256GB         | 5         | 0.64%   |
| Crucial CT1000MX500SSD1 1TB         | 5         | 0.64%   |
| Toshiba MQ04ABF100 1TB              | 4         | 0.51%   |
| Seagate ST1000DM010-2EP102 1TB      | 4         | 0.51%   |
| SanDisk Ultra Fit 128GB             | 4         | 0.51%   |
| SanDisk Cruzer Blade 64GB           | 4         | 0.51%   |
| Samsung SSD 860 EVO mSATA 500GB     | 4         | 0.51%   |
| Samsung SSD 860 EVO 500GB           | 4         | 0.51%   |
| Samsung SSD 860 EVO 250GB           | 4         | 0.51%   |
| Samsung SSD 860 EVO 1TB             | 4         | 0.51%   |
| Samsung SSD 850 EVO 250GB           | 4         | 0.51%   |
| Samsung SSD 850 EVO 1TB             | 4         | 0.51%   |
| NVMe Samsung SSD 960 500GB          | 4         | 0.51%   |
| NVMe SAMSUNG MZVLW256 256GB         | 4         | 0.51%   |
| Kingston SUV500MS240G 240GB         | 4         | 0.51%   |
| Dell PERC H710 282GB                | 4         | 0.51%   |
| WDC WD6400AARS-00Y5B1 640GB         | 3         | 0.38%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 3         | 0.38%   |
| Seagate ST3250318AS 250GB           | 3         | 0.38%   |
| Seagate ST250DM000-1BD141 250GB     | 3         | 0.38%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 3         | 0.38%   |
| SanDisk SSD PLUS 120GB              | 3         | 0.38%   |
| Samsung SSD 860 EVO M.2 1TB         | 3         | 0.38%   |
| Samsung SSD 840 EVO 120GB           | 3         | 0.38%   |
| Samsung Flash Drive FIT 32GB        | 3         | 0.38%   |
| PNY CS900 120GB SSD                 | 3         | 0.38%   |
| Kingston SEDC500M480G 480GB         | 3         | 0.38%   |
| Kingston SA400S37480G 480GB         | 3         | 0.38%   |
| Innostor SSD 15GB                   | 3         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                             | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| NVMe                               | 80        | 109    | 21.39%  |
| Seagate                            | 72        | 121    | 19.25%  |
| WDC                                | 70        | 123    | 18.72%  |
| Toshiba                            | 26        | 42     | 6.95%   |
| Hitachi                            | 24        | 38     | 6.42%   |
| Samsung Electronics                | 19        | 29     | 5.08%   |
| OPENBSD                            | 16        | 26     | 4.28%   |
| HGST                               | 14        | 25     | 3.74%   |
| Dell                               | 7         | 12     | 1.87%   |
| USB                                | 5         | 5      | 1.34%   |
| Generic                            | 4         | 4      | 1.07%   |
| Apple                              | 4         | 4      | 1.07%   |
| StoreJet                           | 2         | 2      | 0.53%   |
| Multiple                           | 2         | 2      | 0.53%   |
| Maxtor                             | 2         | 3      | 0.53%   |
| LSI                                | 2         | 4      | 0.53%   |
| Lexar                              | 2         | 2      | 0.53%   |
| Hewlett-Packard                    | 2         | 6      | 0.53%   |
| General                            | 2         | 2      | 0.53%   |
| Fujitsu                            | 2         | 2      | 0.53%   |
| ASMT                               | 2         | 2      | 0.53%   |
| Verbatim                           | 1         | 1      | 0.27%   |
| UFD 2.0                            | 1         | 1      | 0.27%   |
| SSDPR-CX                           | 1         | 1      | 0.27%   |
| SMI                                | 1         | 1      | 0.27%   |
| SABRENT                            | 1         | 1      | 0.27%   |
| Product:              USB DISK 3.0 | 1         | 1      | 0.27%   |
| Product:              USB DISK 2.0 | 1         | 1      | 0.27%   |
| Product:                           | 1         | 1      | 0.27%   |
| Memorex                            | 1         | 1      | 0.27%   |
| MaxDigital                         | 1         | 1      | 0.27%   |
| LDLC F6+                           | 1         | 1      | 0.27%   |
| JetFlash                           | 1         | 1      | 0.27%   |
| IBM-ESXS                           | 1         | 1      | 0.27%   |
| IBM                                | 1         | 1      | 0.27%   |
| China                              | 1         | 1      | 0.27%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 68        | 115    | 19.37%  |
| NVMe                | 39        | 47     | 11.11%  |
| Kingston            | 38        | 50     | 10.83%  |
| SanDisk             | 30        | 37     | 8.55%   |
| Crucial             | 29        | 40     | 8.26%   |
| Intel               | 16        | 21     | 4.56%   |
| Phison              | 14        | 16     | 3.99%   |
| WDC                 | 10        | 11     | 2.85%   |
| Transcend           | 10        | 17     | 2.85%   |
| PNY                 | 8         | 9      | 2.28%   |
| A-DATA Technology   | 8         | 13     | 2.28%   |
| SK hynix            | 7         | 7      | 1.99%   |
| Apple               | 7         | 7      | 1.99%   |
| Apacer              | 6         | 7      | 1.71%   |
| SPCC                | 4         | 4      | 1.14%   |
| Toshiba             | 3         | 3      | 0.85%   |
| Patriot             | 3         | 3      | 0.85%   |
| OCZ                 | 3         | 3      | 0.85%   |
| KingSpec            | 3         | 3      | 0.85%   |
| Innostor            | 3         | 3      | 0.85%   |
| Corsair             | 3         | 3      | 0.85%   |
| Team                | 2         | 2      | 0.57%   |
| Plextor             | 2         | 2      | 0.57%   |
| Netac               | 2         | 2      | 0.57%   |
| Micron Technology   | 2         | 2      | 0.57%   |
| LITEONIT            | 2         | 2      | 0.57%   |
| Intenso             | 2         | 2      | 0.57%   |
| Hoodisk             | 2         | 3      | 0.57%   |
| Hewlett-Packard     | 2         | 3      | 0.57%   |
| Zheino              | 1         | 2      | 0.28%   |
| XPG                 | 1         | 1      | 0.28%   |
| Union Memory        | 1         | 1      | 0.28%   |
| UDinfo              | 1         | 1      | 0.28%   |
| Star Drive          | 1         | 1      | 0.28%   |
| SATA3 60            | 1         | 1      | 0.28%   |
| Qumo                | 1         | 1      | 0.28%   |
| OWC                 | 1         | 1      | 0.28%   |
| MidasForce          | 1         | 1      | 0.28%   |
| MEMXPRO             | 1         | 1      | 0.28%   |
| LSI                 | 1         | 2      | 0.28%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 305       | 463    | 49.19%  |
| HDD  | 305       | 578    | 49.19%  |
| NVMe | 10        | 12     | 1.61%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 523       | 1041   | 98.12%  |
| NVMe | 10        | 12     | 1.88%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 428       | 655    | 66.88%  |
| 0.51-1.0        | 132       | 191    | 20.63%  |
| 1.01-2.0        | 48        | 138    | 7.5%    |
| 3.01-4.0        | 14        | 22     | 2.19%   |
| 4.01-10.0       | 11        | 26     | 1.72%   |
| More than 100.0 | 3         | 3      | 0.47%   |
| 2.01-3.0        | 3         | 5      | 0.47%   |
| 0               | 1         | 1      | 0.16%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 198       | 34.08%  |
| 251-500        | 154       | 26.51%  |
| 51-100         | 67        | 11.53%  |
| 21-50          | 49        | 8.43%   |
| 1-20           | 44        | 7.57%   |
| 501-1000       | 31        | 5.34%   |
| 1001-2000      | 20        | 3.44%   |
| More than 3000 | 14        | 2.41%   |
| 2001-3000      | 4         | 0.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 404       | 69.18%  |
| 21-50          | 60        | 10.27%  |
| 101-250        | 42        | 7.19%   |
| 51-100         | 41        | 7.02%   |
| 251-500        | 16        | 2.74%   |
| 501-1000       | 9         | 1.54%   |
| 1001-2000      | 7         | 1.2%    |
| More than 3000 | 4         | 0.68%   |
| 2001-3000      | 1         | 0.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Toshiba MQ04ABF100 1TB                | 2         | 2      | 2.63%   |
| Seagate ST9320423AS 320GB             | 2         | 2      | 2.63%   |
| OCZ VERTEX3 120GB                     | 2         | 2      | 2.63%   |
| Kingston SMS200S330G 32GB             | 2         | 4      | 2.63%   |
| Intel SSDSC2KF256H6L 256GB            | 2         | 2      | 2.63%   |
| HGST HTS541010A7E630 1TB              | 2         | 4      | 2.63%   |
| A-DATA Technology SP550 240GB         | 2         | 2      | 2.63%   |
| XPG SX950U 240GB                      | 1         | 1      | 1.32%   |
| WDC WD7500AACS-00ZJB0 752GB           | 1         | 1      | 1.32%   |
| WDC WD6400AAKS-22A7B0 640GB           | 1         | 1      | 1.32%   |
| WDC WD5000AAKX-60U6AA0 500GB          | 1         | 1      | 1.32%   |
| WDC WD2500BEVS-22UST0 250GB           | 1         | 1      | 1.32%   |
| WDC WD1600BEVT-22ZCT0 160GB           | 1         | 1      | 1.32%   |
| WDC WD1600BEVE-00UYT0 160GB           | 1         | 1      | 1.32%   |
| WDC WD15EARS-00Z5B1 1.5TB             | 1         | 1      | 1.32%   |
| WDC WD10SPZX-24Z10 1TB                | 1         | 1      | 1.32%   |
| WDC WD10EADS-00M2B0 1TB               | 1         | 1      | 1.32%   |
| Transcend 3E128-TS2-550B01 100GB      | 1         | 4      | 1.32%   |
| Toshiba MQ01ACF032 320GB              | 1         | 3      | 1.32%   |
| Toshiba MK6475GSX 640GB               | 1         | 2      | 1.32%   |
| Toshiba MK6006GAH 64GB                | 1         | 1      | 1.32%   |
| Toshiba MK5065GSX 500GB               | 1         | 1      | 1.32%   |
| Toshiba MK1629GSGF 160GB              | 1         | 3      | 1.32%   |
| Toshiba DT01ACA100 1TB                | 1         | 1      | 1.32%   |
| Seagate ST9500420AS 500GB             | 1         | 2      | 1.32%   |
| Seagate ST9500325AS 500GB             | 1         | 1      | 1.32%   |
| Seagate ST9160310AS 160GB             | 1         | 2      | 1.32%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1      | 1.32%   |
| Seagate ST500DM002-1BD142 500GB       | 1         | 1      | 1.32%   |
| Seagate ST380815AS 80GB               | 1         | 1      | 1.32%   |
| Seagate ST3750640NS 752GB             | 1         | 6      | 1.32%   |
| Seagate ST3500418AS 500GB             | 1         | 1      | 1.32%   |
| Seagate ST3320418AS 320GB             | 1         | 1      | 1.32%   |
| Seagate ST3160212SCE 160GB            | 1         | 1      | 1.32%   |
| Seagate ST3120211AS 120GB             | 1         | 1      | 1.32%   |
| Seagate ST250DM000-1BD141 250GB       | 1         | 2      | 1.32%   |
| Seagate ST2000DM006-2DM164 2TB        | 1         | 1      | 1.32%   |
| Seagate ST1000DM003-1CH162 1TB        | 1         | 1      | 1.32%   |
| SanDisk SD7UB3Q256G1001 256GB         | 1         | 2      | 1.32%   |
| Samsung Electronics SSD 870 EVO 500GB | 1         | 1      | 1.32%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 24     | 20.27%  |
| WDC                 | 8         | 9      | 10.81%  |
| Toshiba             | 8         | 13     | 10.81%  |
| Samsung Electronics | 7         | 10     | 9.46%   |
| Hitachi             | 7         | 8      | 9.46%   |
| Kingston            | 5         | 7      | 6.76%   |
| Intel               | 5         | 5      | 6.76%   |
| HGST                | 5         | 8      | 6.76%   |
| A-DATA Technology   | 4         | 9      | 5.41%   |
| OCZ                 | 2         | 2      | 2.7%    |
| KingSpec            | 2         | 2      | 2.7%    |
| XPG                 | 1         | 1      | 1.35%   |
| Transcend           | 1         | 4      | 1.35%   |
| SanDisk             | 1         | 2      | 1.35%   |
| GLOWAY              | 1         | 1      | 1.35%   |
| Corsair             | 1         | 1      | 1.35%   |
| Apple               | 1         | 1      | 1.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 24     | 31.25%  |
| WDC                 | 8         | 9      | 16.67%  |
| Toshiba             | 8         | 13     | 16.67%  |
| Hitachi             | 7         | 8      | 14.58%  |
| Samsung Electronics | 5         | 8      | 10.42%  |
| HGST                | 5         | 8      | 10.42%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 48        | 70     | 64.86%  |
| SSD  | 26        | 37     | 35.14%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD6400AARS-00Y5B1 640GB     | 1         | 2      | 50%     |
| Samsung Electronics HD204UI 2TB | 1         | 2      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 2      | 50%     |
| Samsung Electronics | 1         | 2      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 379       | 675    | 60.93%  |
| Detected | 168       | 267    | 27.01%  |
| Malfunc  | 73        | 107    | 11.74%  |
| Failed   | 2         | 4      | 0.32%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 339       | 54.24%  |
| AMD                              | 108       | 17.28%  |
| Samsung Electronics              | 55        | 8.8%    |
| Sandisk                          | 28        | 4.48%   |
| Broadcom / LSI                   | 14        | 2.24%   |
| Nvidia                           | 8         | 1.28%   |
| KIOXIA                           | 8         | 1.28%   |
| Phison Electronics               | 7         | 1.12%   |
| Marvell Technology Group         | 7         | 1.12%   |
| SK hynix                         | 6         | 0.96%   |
| Kingston Technology Company      | 6         | 0.96%   |
| ADATA Technology                 | 5         | 0.8%    |
| VIA Technologies                 | 4         | 0.64%   |
| Micron/Crucial Technology        | 4         | 0.64%   |
| ASMedia Technology               | 4         | 0.64%   |
| Lenovo                           | 3         | 0.48%   |
| ULi Electronics                  | 2         | 0.32%   |
| Toshiba                          | 2         | 0.32%   |
| Silicon Motion                   | 2         | 0.32%   |
| Micron Technology                | 2         | 0.32%   |
| Hewlett-Packard                  | 2         | 0.32%   |
| Union Memory (Shenzhen)          | 1         | 0.16%   |
| Solid State Storage Technology   | 1         | 0.16%   |
| Silicon Integrated Systems [SiS] | 1         | 0.16%   |
| Silicon Image                    | 1         | 0.16%   |
| Shenzhen Longsys Electronics     | 1         | 0.16%   |
| Seagate Technology               | 1         | 0.16%   |
| HighPoint Technologies           | 1         | 0.16%   |
| Dell                             | 1         | 0.16%   |
| Artop Electronic                 | 1         | 0.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 57        | 8.14%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 28        | 4%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 28        | 4%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 23        | 3.29%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 22        | 3.14%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 19        | 2.71%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 19        | 2.71%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 18        | 2.57%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 18        | 2.57%   |
| AMD FCH SATA Controller [IDE mode]                                             | 18        | 2.57%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 17        | 2.43%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 13        | 1.86%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 13        | 1.86%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 12        | 1.71%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 11        | 1.57%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 10        | 1.43%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 9         | 1.29%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 9         | 1.29%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 8         | 1.14%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 8         | 1.14%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 8         | 1.14%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 8         | 1.14%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 8         | 1.14%   |
| AMD 500 Series Chipset SATA Controller                                         | 8         | 1.14%   |
| AMD 400 Series Chipset SATA Controller                                         | 8         | 1.14%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 7         | 1%      |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 7         | 1%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 7         | 1%      |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 6         | 0.86%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 6         | 0.86%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 6         | 0.86%   |
| Samsung NVMe SSD Controller 980                                                | 5         | 0.71%   |
| Nvidia MCP61 SATA Controller                                                   | 5         | 0.71%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 5         | 0.71%   |
| Intel Comet Lake SATA AHCI Controller                                          | 5         | 0.71%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 0.71%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                 | 5         | 0.71%   |
| Samsung SM951 AHCI                                                             | 4         | 0.57%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 4         | 0.57%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]           | 4         | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 390       | 60.84%  |
| NVMe | 121       | 18.88%  |
| IDE  | 106       | 16.54%  |
| RAID | 15        | 2.34%   |
| SAS  | 5         | 0.78%   |
| SCSI | 4         | 0.62%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 396       | 70.84%  |
| AMD     | 129       | 23.08%  |
| ARM     | 21        | 3.76%   |
| Unknown | 8         | 1.43%   |
| PowerPC | 4         | 0.72%   |
| 11th    | 1         | 0.18%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| AMD GX-412TC SOC                                         | 27        | 4.77%   |
| Intel Core i5-2520M CPU @ 2.50GHz                        | 13        | 2.3%    |
| ARM Cortex-A72 r0p3                                      | 12        | 2.12%   |
| Intel Core i5-3320M CPU @ 2.60GHz                        | 11        | 1.94%   |
| Intel Core i5-6300U CPU @ 2.40GHz                        | 10        | 1.77%   |
| Intel Core i5-5300U CPU @ 2.30GHz                        | 8         | 1.41%   |
|                                                          | 8         | 1.41%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz                     | 7         | 1.24%   |
| Intel Core i5-8250U CPU @ 1.60GHz                        | 6         | 1.06%   |
| ARM Cortex-A53 r0p4                                      | 6         | 1.06%   |
| AMD G-T40E Processor                                     | 6         | 1.06%   |
| Intel Core i7-7500U CPU @ 2.70GHz                        | 5         | 0.88%   |
| Intel Atom CPU N270 @ 1.60GHz ("GenuineIntel" 686-class) | 5         | 0.88%   |
| Intel Core i7-8565U CPU @ 1.80GHz                        | 4         | 0.71%   |
| Intel Core i7-8550U CPU @ 1.80GHz                        | 4         | 0.71%   |
| Intel Core i5-5200U CPU @ 2.20GHz                        | 4         | 0.71%   |
| Intel Core i5-4570 CPU @ 3.20GHz                         | 4         | 0.71%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz                     | 4         | 0.71%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz                  | 4         | 0.71%   |
| AMD Ryzen 7 5800X 8-Core Processor                       | 4         | 0.71%   |
| AMD Ryzen 7 4800H with Radeon Graphics                   | 4         | 0.71%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz                      | 3         | 0.53%   |
| Intel Core i7-8750H CPU @ 2.20GHz                        | 3         | 0.53%   |
| Intel Core i7-8650U CPU @ 1.90GHz                        | 3         | 0.53%   |
| Intel Core i7-5600U CPU @ 2.60GHz                        | 3         | 0.53%   |
| Intel Core i7-3520M CPU @ 2.90GHz                        | 3         | 0.53%   |
| Intel Core i7-10510U CPU @ 1.80GHz                       | 3         | 0.53%   |
| Intel Core i5-8265U CPU @ 1.60GHz                        | 3         | 0.53%   |
| Intel Core i5-4300U CPU @ 1.90GHz                        | 3         | 0.53%   |
| Intel Core i5-4260U CPU @ 1.40GHz                        | 3         | 0.53%   |
| Intel Core i5-2540M CPU @ 2.60GHz                        | 3         | 0.53%   |
| Intel Core i5-10210U CPU @ 1.60GHz                       | 3         | 0.53%   |
| Intel Core i5 CPU M 520 @ 2.40GHz                        | 3         | 0.53%   |
| Intel Core i3-6006U CPU @ 2.00GHz                        | 3         | 0.53%   |
| Intel Celeron CPU J1900 @ 1.99GHz                        | 3         | 0.53%   |
| AMD Ryzen 7 4700U with Radeon Graphics                   | 3         | 0.53%   |
| AMD Ryzen 5 3600 6-Core Processor                        | 3         | 0.53%   |
| PowerPC 7447A (Revision 0x105)                           | 2         | 0.35%   |
| Intel Xeon CPU E5520 @ 2.27GHz                           | 2         | 0.35%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz                       | 2         | 0.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 125       | 22.32%  |
| Intel Core i7           | 64        | 11.43%  |
| Intel Xeon              | 35        | 6.25%   |
| Other                   | 31        | 5.54%   |
| Intel Celeron           | 31        | 5.54%   |
| Intel Core i3           | 29        | 5.18%   |
| AMD GX                  | 28        | 5%      |
| Intel Core 2 Duo        | 26        | 4.64%   |
| AMD Ryzen 7             | 24        | 4.29%   |
| ARM Cortex              | 21        | 3.75%   |
| Intel Atom              | 15        | 2.68%   |
| AMD Ryzen 5             | 13        | 2.32%   |
| AMD G                   | 7         | 1.25%   |
| Intel Pentium 4         | 6         | 1.07%   |
| Intel Genuine           | 6         | 1.07%   |
| Intel Core 2            | 6         | 1.07%   |
| Intel Pentium M         | 5         | 0.89%   |
| Intel Pentium           | 5         | 0.89%   |
| AMD Ryzen 7 PRO         | 5         | 0.89%   |
| AMD Ryzen 3             | 5         | 0.89%   |
| AMD A4                  | 5         | 0.89%   |
| Intel Pentium Silver    | 4         | 0.71%   |
| Intel Pentium Dual-Core | 4         | 0.71%   |
| AMD Ryzen 9             | 4         | 0.71%   |
| Intel Core i9           | 3         | 0.54%   |
| Intel Core Duo          | 3         | 0.54%   |
| AMD E1                  | 3         | 0.54%   |
| AMD A6                  | 3         | 0.54%   |
| Intel Xeon Gold         | 2         | 0.36%   |
| Intel Core m3           | 2         | 0.36%   |
| AMD Ryzen 5 PRO         | 2         | 0.36%   |
| AMD Phenom II X4        | 2         | 0.36%   |
| AMD Geode Integrated    | 2         | 0.36%   |
| AMD E2                  | 2         | 0.36%   |
| AMD E                   | 2         | 0.36%   |
| AMD Athlon II X3        | 2         | 0.36%   |
| AMD Athlon 64 X2        | 2         | 0.36%   |
| AMD Athlon              | 2         | 0.36%   |
| AMD A10                 | 2         | 0.36%   |
| Intel Pentium III       | 1         | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 179       | 31.96%  |
| 4       | 159       | 28.39%  |
| Unknown | 100       | 17.86%  |
| 1       | 36        | 6.43%   |
| 8       | 22        | 3.93%   |
| 6       | 22        | 3.93%   |
| 16      | 20        | 3.57%   |
| 12      | 15        | 2.68%   |
| 32      | 2         | 0.36%   |
| 24      | 2         | 0.36%   |
| 3       | 2         | 0.36%   |
| 36      | 1         | 0.18%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 429       | 76.06%  |
| Unknown | 125       | 22.16%  |
| 2       | 10        | 1.77%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 245       | 43.83%  |
| 1       | 185       | 33.09%  |
| Unknown | 129       | 23.08%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 64        | 11.41%  |
| Unknown       | 57        | 10.16%  |
| Haswell       | 42        | 7.49%   |
| SandyBridge   | 33        | 5.88%   |
| IvyBridge     | 33        | 5.88%   |
| Penryn        | 29        | 5.17%   |
| Broadwell     | 29        | 5.17%   |
| Puma          | 28        | 4.99%   |
| Skylake       | 25        | 4.46%   |
| Zen 2         | 22        | 3.92%   |
| Westmere      | 17        | 3.03%   |
| P6            | 17        | 3.03%   |
| Bonnell       | 15        | 2.67%   |
| Silvermont    | 14        | 2.5%    |
| K10           | 12        | 2.14%   |
| Core          | 12        | 2.14%   |
| Bobcat        | 12        | 2.14%   |
| Zen 3         | 10        | 1.78%   |
| NetBurst      | 10        | 1.78%   |
| Goldmont plus | 10        | 1.78%   |
| CometLake     | 9         | 1.6%    |
| Zen           | 8         | 1.43%   |
| TigerLake     | 8         | 1.43%   |
| Zen+          | 7         | 1.25%   |
| Goldmont      | 7         | 1.25%   |
| Jaguar        | 6         | 1.07%   |
| Nehalem       | 5         | 0.89%   |
| Piledriver    | 4         | 0.71%   |
| IceLake       | 4         | 0.71%   |
| K8 Hammer     | 3         | 0.53%   |
| K10 Llano     | 3         | 0.53%   |
| Geode         | 3         | 0.53%   |
| Excavator     | 2         | 0.36%   |
| K6            | 1         | 0.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 314       | 57.93%  |
| AMD                                          | 143       | 26.38%  |
| Nvidia                                       | 58        | 10.7%   |
| Matrox Electronics Systems                   | 15        | 2.77%   |
| ASPEED Technology                            | 9         | 1.66%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.18%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.18%   |
| 3DLabs                                       | 1         | 0.18%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 26        | 4.6%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 24        | 4.25%   |
| Intel HD Graphics 5500                                                                   | 21        | 3.72%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 18        | 3.19%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 17        | 3.01%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 16        | 2.83%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 15        | 2.65%   |
| Intel UHD Graphics 620                                                                   | 14        | 2.48%   |
| AMD Renoir                                                                               | 13        | 2.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 11        | 1.95%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 11        | 1.95%   |
| Intel HD Graphics 620                                                                    | 10        | 1.77%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 1.59%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 9         | 1.59%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 9         | 1.59%   |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 1.42%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 8         | 1.42%   |
| Matrox Electronics Systems G200eR2                                                       | 7         | 1.24%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 1.24%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 7         | 1.24%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 1.24%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 1.24%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 1.24%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 1.06%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 6         | 1.06%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 6         | 1.06%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 5         | 0.88%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 4         | 0.71%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 0.71%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 0.71%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 4         | 0.71%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 4         | 0.71%   |
| Nvidia GT218M [NVS 3100M]                                                                | 3         | 0.53%   |
| Nvidia C79 [GeForce 9400M]                                                               | 3         | 0.53%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.53%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 0.53%   |
| Intel JasperLake [UHD Graphics]                                                          | 3         | 0.53%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 3         | 0.53%   |
| Intel HD Graphics 610                                                                    | 3         | 0.53%   |
| Intel HD Graphics 6000                                                                   | 3         | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 238       | 42.27%  |
| 1 x AMD        | 123       | 21.85%  |
| Other          | 63        | 11.19%  |
| 2 x Intel      | 40        | 7.1%    |
| 1 x Nvidia     | 26        | 4.62%   |
| Intel + Nvidia | 26        | 4.62%   |
| 1 x Matrox     | 13        | 2.31%   |
| Intel + AMD    | 11        | 1.95%   |
| 1 x ASPEED     | 9         | 1.6%    |
| AMD + Nvidia   | 5         | 0.89%   |
| 2 x AMD        | 3         | 0.53%   |
| AMD + Matrox   | 2         | 0.36%   |
| 2 x Nvidia     | 1         | 0.18%   |
| 1 x XGI        | 1         | 0.18%   |
| 1 x SiS        | 1         | 0.18%   |
| 1 x 3DLabs     | 1         | 0.18%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 462       | 82.5%   |
| Unknown | 98        | 17.5%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 559       | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 44        | 13.54%  |
| LG Display              | 43        | 13.23%  |
| BOE                     | 33        | 10.15%  |
| Samsung Electronics     | 26        | 8%      |
| Lenovo                  | 23        | 7.08%   |
| Chimei Innolux          | 22        | 6.77%   |
| Philips                 | 17        | 5.23%   |
| Dell                    | 17        | 5.23%   |
| Goldstar                | 13        | 4%      |
| Apple                   | 9         | 2.77%   |
| Ancor Communications    | 9         | 2.77%   |
| Iiyama                  | 6         | 1.85%   |
| BenQ                    | 6         | 1.85%   |
| Acer                    | 6         | 1.85%   |
| ViewSonic               | 4         | 1.23%   |
| NEC Computers           | 4         | 1.23%   |
| Hewlett-Packard         | 4         | 1.23%   |
| ASUSTek Computer        | 4         | 1.23%   |
| AOC                     | 4         | 1.23%   |
| Sharp                   | 3         | 0.92%   |
| PANDA                   | 3         | 0.92%   |
| InfoVision              | 3         | 0.92%   |
| Chi Mei Optoelectronics | 3         | 0.92%   |
| MSI                     | 2         | 0.62%   |
| IBM                     | 2         | 0.62%   |
| Eizo                    | 2         | 0.62%   |
| CSO                     | 2         | 0.62%   |
| Vizio                   | 1         | 0.31%   |
| TRU                     | 1         | 0.31%   |
| SHI                     | 1         | 0.31%   |
| Sceptre Tech            | 1         | 0.31%   |
| Quanta Display          | 1         | 0.31%   |
| Medion                  | 1         | 0.31%   |
| LTM                     | 1         | 0.31%   |
| LG Philips              | 1         | 0.31%   |
| HannStar                | 1         | 0.31%   |
| Gigabyte Technology     | 1         | 0.31%   |
| DSC                     | 1         | 0.31%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                    | 10        | 3.05%   |
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch                  | 6         | 1.83%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 6         | 1.83%   |
| LG Display LCD Monitor LGD058B 2560x1440 310x170mm 13.9-inch             | 4         | 1.22%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch              | 3         | 0.91%   |
| Lenovo LCD Monitor LEN4033 1440x900 300x190mm 14.0-inch                  | 3         | 0.91%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch                  | 3         | 0.91%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch            | 3         | 0.91%   |
| Ancor Communications ASUS VW199 ACI19ED 1440x900 410x260mm 19.1-inch     | 3         | 0.91%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch     | 2         | 0.61%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch             | 2         | 0.61%   |
| LG Display LCD Monitor LGD057E 1920x1080 340x190mm 15.3-inch             | 2         | 0.61%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x170mm 12.2-inch             | 2         | 0.61%   |
| LG Display LCD Monitor LGD045E 1366x768 310x170mm 13.9-inch              | 2         | 0.61%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch             | 2         | 0.61%   |
| LG Display LCD Monitor LGD0418 2560x1440 310x170mm 13.9-inch             | 2         | 0.61%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 2         | 0.61%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch                 | 2         | 0.61%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch                  | 2         | 0.61%   |
| Iiyama PL2779QQ IVM6641 3840x2160 600x330mm 27.0-inch                    | 2         | 0.61%   |
| Iiyama PL2474H IVM6137 1920x1080 520x290mm 23.4-inch                     | 2         | 0.61%   |
| IBM LCD Monitor IBM2887 1680x1050 330x210mm 15.4-inch                    | 2         | 0.61%   |
| Hewlett-Packard LA2405 HWP284B 1920x1200 520x320mm 24.0-inch             | 2         | 0.61%   |
| Eizo EV2450 ENC2530 1920x1080 530x300mm 24.0-inch                        | 2         | 0.61%   |
| Dell UP2715K DEL40B6 848x480 600x340mm 27.2-inch                         | 2         | 0.61%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch          | 2         | 0.61%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 310x170mm 13.9-inch          | 2         | 0.61%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 280x160mm 12.7-inch         | 2         | 0.61%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch          | 2         | 0.61%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 2         | 0.61%   |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                    | 2         | 0.61%   |
| BOE LCD Monitor BOE0900 1920x1080 340x190mm 15.3-inch                    | 2         | 0.61%   |
| BOE LCD Monitor BOE07C8 3840x2160 310x170mm 13.9-inch                    | 2         | 0.61%   |
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                       | 2         | 0.61%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 310x170mm 13.9-inch           | 2         | 0.61%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 310x170mm 13.9-inch           | 2         | 0.61%   |
| AU Optronics LCD Monitor AUO34ED 1920x1080 340x190mm 15.3-inch           | 2         | 0.61%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch           | 2         | 0.61%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 340x190mm 15.3-inch            | 2         | 0.61%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch            | 2         | 0.61%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 121       | 38.05%  |
| 1366x768 (WXGA)    | 66        | 20.75%  |
| 1280x800 (WXGA)    | 18        | 5.66%   |
| 2560x1440 (QHD)    | 15        | 4.72%   |
| 1440x900 (WXGA+)   | 15        | 4.72%   |
| 3840x2160 (4K)     | 14        | 4.4%    |
| 1280x1024 (SXGA)   | 14        | 4.4%    |
| 1600x900 (HD+)     | 11        | 3.46%   |
| 1920x1200 (WUXGA)  | 9         | 2.83%   |
| 3440x1440          | 7         | 2.2%    |
| 1680x1050 (WSXGA+) | 5         | 1.57%   |
| 2736x1824          | 2         | 0.63%   |
| 2256x1504          | 2         | 0.63%   |
| 1600x1200          | 2         | 0.63%   |
| 1360x768           | 2         | 0.63%   |
| 1024x768 (XGA)     | 2         | 0.63%   |
| 720x1280           | 1         | 0.31%   |
| 3840x2400          | 1         | 0.31%   |
| 3840x1080          | 1         | 0.31%   |
| 3200x1800 (QHD+)   | 1         | 0.31%   |
| 2880x1800          | 1         | 0.31%   |
| 2560x1080          | 1         | 0.31%   |
| 2200x1650          | 1         | 0.31%   |
| 1920x1280          | 1         | 0.31%   |
| 1440x960           | 1         | 0.31%   |
| 1400x1050          | 1         | 0.31%   |
| 1280x854           | 1         | 0.31%   |
| 1280x768           | 1         | 0.31%   |
| 1024x600           | 1         | 0.31%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 68        | 21.18%  |
| 15      | 60        | 18.69%  |
| 12      | 37        | 11.53%  |
| 24      | 25        | 7.79%   |
| 21      | 18        | 5.61%   |
| 23      | 17        | 5.3%    |
| 19      | 15        | 4.67%   |
| 14      | 14        | 4.36%   |
| 11      | 14        | 4.36%   |
| 27      | 11        | 3.43%   |
| 17      | 9         | 2.8%    |
| 34      | 7         | 2.18%   |
| 31      | 5         | 1.56%   |
| 18      | 5         | 1.56%   |
| 10      | 3         | 0.93%   |
| 54      | 2         | 0.62%   |
| 9       | 2         | 0.62%   |
| 49      | 1         | 0.31%   |
| 35      | 1         | 0.31%   |
| 28      | 1         | 0.31%   |
| 26      | 1         | 0.31%   |
| 22      | 1         | 0.31%   |
| 20      | 1         | 0.31%   |
| 16      | 1         | 0.31%   |
| 6       | 1         | 0.31%   |
| Unknown | 1         | 0.31%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 119       | 37.07%  |
| 201-300     | 85        | 26.48%  |
| 501-600     | 52        | 16.2%   |
| 401-500     | 33        | 10.28%  |
| 351-400     | 10        | 3.12%   |
| 701-800     | 7         | 2.18%   |
| 601-700     | 7         | 2.18%   |
| 101-200     | 3         | 0.93%   |
| 1001-1500   | 3         | 0.93%   |
| 801-900     | 1         | 0.31%   |
| Unknown     | 1         | 0.31%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 225       | 72.35%  |
| 16/10 | 46        | 14.79%  |
| 5/4   | 14        | 4.5%    |
| 3/2   | 11        | 3.54%   |
| 21/9  | 8         | 2.57%   |
| 4/3   | 6         | 1.93%   |
| 32/9  | 1         | 0.32%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 70        | 22.01%  |
| 91-100         | 49        | 15.41%  |
| 201-250        | 47        | 14.78%  |
| 61-70          | 37        | 11.64%  |
| 151-200        | 18        | 5.66%   |
| 51-60          | 15        | 4.72%   |
| 351-500        | 14        | 4.4%    |
| 101-110        | 13        | 4.09%   |
| 301-350        | 12        | 3.77%   |
| 141-150        | 11        | 3.46%   |
| 71-80          | 10        | 3.14%   |
| 251-300        | 10        | 3.14%   |
| 41-50          | 3         | 0.94%   |
| 121-130        | 3         | 0.94%   |
| More than 1000 | 2         | 0.63%   |
| 1-40           | 2         | 0.63%   |
| 501-1000       | 1         | 0.31%   |
| Unknown        | 1         | 0.31%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 123       | 38.56%  |
| 51-100        | 79        | 24.76%  |
| 101-120       | 69        | 21.63%  |
| 161-240       | 33        | 10.34%  |
| More than 240 | 10        | 3.13%   |
| 1-50          | 4         | 1.25%   |
| Unknown       | 1         | 0.31%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 360       | 63.6%   |
| 0     | 183       | 32.33%  |
| 2     | 21        | 3.71%   |
| 3     | 2         | 0.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 348       | 46.84%  |
| Realtek Semiconductor             | 200       | 26.92%  |
| Qualcomm Atheros                  | 53        | 7.13%   |
| Broadcom                          | 45        | 6.06%   |
| Qualcomm Atheros Communications   | 10        | 1.35%   |
| TP-Link                           | 7         | 0.94%   |
| Marvell Technology Group          | 7         | 0.94%   |
| Ericsson Business Mobile Networks | 7         | 0.94%   |
| Edimax Technology                 | 6         | 0.81%   |
| Apple                             | 6         | 0.81%   |
| Sierra Wireless                   | 5         | 0.67%   |
| U-Blox                            | 4         | 0.54%   |
| Ralink                            | 4         | 0.54%   |
| MediaTek                          | 4         | 0.54%   |
| VIA Technologies                  | 3         | 0.4%    |
| Ralink Technology                 | 3         | 0.4%    |
| Nvidia                            | 3         | 0.4%    |
| 3Com                              | 3         | 0.4%    |
| Oracle/SUN                        | 2         | 0.27%   |
| D-Link System                     | 2         | 0.27%   |
| Xiaomi                            | 1         | 0.13%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.13%   |
| Samsung Electronics               | 1         | 0.13%   |
| Qcom                              | 1         | 0.13%   |
| National Semiconductor            | 1         | 0.13%   |
| Microsoft                         | 1         | 0.13%   |
| Micro Star International          | 1         | 0.13%   |
| LG Electronics                    | 1         | 0.13%   |
| Huawei Technologies               | 1         | 0.13%   |
| Hewlett-Packard                   | 1         | 0.13%   |
| Google                            | 1         | 0.13%   |
| Fibocom                           | 1         | 0.13%   |
| Emulex                            | 1         | 0.13%   |
| Dell                              | 1         | 0.13%   |
| Davicom Semiconductor             | 1         | 0.13%   |
| D-Link                            | 1         | 0.13%   |
| AVM                               | 1         | 0.13%   |
| ASUSTek Computer                  | 1         | 0.13%   |
| Aquantia                          | 1         | 0.13%   |
| AMD                               | 1         | 0.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 150       | 15.97%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 31        | 3.3%    |
| Intel I211 Gigabit Network Connection                                   | 27        | 2.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 26        | 2.77%   |
| Intel Wi-Fi 6 AX200                                                     | 24        | 2.56%   |
| Intel I210 Gigabit Network Connection                                   | 23        | 2.45%   |
| Intel Wireless 8265 / 8275                                              | 21        | 2.24%   |
| Intel Wireless 7265                                                     | 20        | 2.13%   |
| Intel Wireless 7260                                                     | 19        | 2.02%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 18        | 1.92%   |
| Intel 82567LM Gigabit Network Connection                                | 16        | 1.7%    |
| Intel Wireless 8260                                                     | 15        | 1.6%    |
| Intel Ethernet Connection I219-LM                                       | 13        | 1.38%   |
| Intel 82574L Gigabit Network Connection                                 | 12        | 1.28%   |
| Intel Ethernet Connection (3) I218-LM                                   | 11        | 1.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 10        | 1.06%   |
| Intel I350 Gigabit Network Connection                                   | 10        | 1.06%   |
| Intel Ethernet Connection I217-LM                                       | 10        | 1.06%   |
| Intel Wi-Fi 6 AX201                                                     | 9         | 0.96%   |
| Intel Ultimate N WiFi Link 5300                                         | 9         | 0.96%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 9         | 0.96%   |
| Intel 82577LM Gigabit Network Connection                                | 9         | 0.96%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 8         | 0.85%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 8         | 0.85%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 7         | 0.75%   |
| Qualcomm Atheros AR9271 802.11n                                         | 7         | 0.75%   |
| Intel Ethernet Connection (4) I219-V                                    | 7         | 0.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 0.64%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 6         | 0.64%   |
| Realtek RTL8125 2.5GbE Controller                                       | 6         | 0.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 0.64%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 6         | 0.64%   |
| Intel Centrino Advanced-N 6200                                          | 6         | 0.64%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 0.53%   |
| Intel Wireless 3165                                                     | 5         | 0.53%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 5         | 0.53%   |
| Intel Ethernet Connection I218-LM                                       | 5         | 0.53%   |
| Intel Ethernet Connection (4) I219-LM                                   | 5         | 0.53%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 0.53%   |
| Intel 82573L Gigabit Ethernet Controller                                | 5         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 226       | 59.47%  |
| Qualcomm Atheros                | 46        | 12.11%  |
| Realtek Semiconductor           | 38        | 10%     |
| Broadcom                        | 25        | 6.58%   |
| Qualcomm Atheros Communications | 10        | 2.63%   |
| TP-Link                         | 7         | 1.84%   |
| Edimax Technology               | 6         | 1.58%   |
| Sierra Wireless                 | 4         | 1.05%   |
| Ralink                          | 4         | 1.05%   |
| MediaTek                        | 4         | 1.05%   |
| Ralink Technology               | 3         | 0.79%   |
| D-Link System                   | 2         | 0.53%   |
| Qcom                            | 1         | 0.26%   |
| Micro Star International        | 1         | 0.26%   |
| Dell                            | 1         | 0.26%   |
| D-Link                          | 1         | 0.26%   |
| ASUSTek Computer                | 1         | 0.26%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 26        | 6.74%   |
| Intel Wi-Fi 6 AX200                                                     | 24        | 6.22%   |
| Intel Wireless 8265 / 8275                                              | 21        | 5.44%   |
| Intel Wireless 7265                                                     | 20        | 5.18%   |
| Intel Wireless 7260                                                     | 19        | 4.92%   |
| Intel Wireless 8260                                                     | 15        | 3.89%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 10        | 2.59%   |
| Intel Wi-Fi 6 AX201                                                     | 9         | 2.33%   |
| Intel Ultimate N WiFi Link 5300                                         | 9         | 2.33%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 9         | 2.33%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 8         | 2.07%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 7         | 1.81%   |
| Qualcomm Atheros AR9271 802.11n                                         | 7         | 1.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 6         | 1.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 1.55%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 6         | 1.55%   |
| Intel Centrino Advanced-N 6200                                          | 6         | 1.55%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 1.3%    |
| Intel Wireless 3165                                                     | 5         | 1.3%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 5         | 1.3%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 1.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 1.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 1.04%   |
| Intel Wireless-AC 9260                                                  | 4         | 1.04%   |
| Intel Wireless 3160                                                     | 4         | 1.04%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 4         | 1.04%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 1.04%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 1.04%   |
| Intel Centrino Wireless-N 2230                                          | 4         | 1.04%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 1.04%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 4         | 1.04%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 4         | 1.04%   |
| Sierra Wireless EM7455                                                  | 3         | 0.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 0.78%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 3         | 0.78%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 3         | 0.78%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 3         | 0.78%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection               | 3         | 0.78%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 241       | 48.2%   |
| Realtek Semiconductor            | 187       | 37.4%   |
| Broadcom                         | 27        | 5.4%    |
| Qualcomm Atheros                 | 12        | 2.4%    |
| Marvell Technology Group         | 7         | 1.4%    |
| Apple                            | 5         | 1%      |
| VIA Technologies                 | 3         | 0.6%    |
| Nvidia                           | 3         | 0.6%    |
| 3Com                             | 3         | 0.6%    |
| Oracle/SUN                       | 2         | 0.4%    |
| Xiaomi                           | 1         | 0.2%    |
| Silicon Integrated Systems [SiS] | 1         | 0.2%    |
| Samsung Electronics              | 1         | 0.2%    |
| National Semiconductor           | 1         | 0.2%    |
| Microsoft                        | 1         | 0.2%    |
| Google                           | 1         | 0.2%    |
| Emulex                           | 1         | 0.2%    |
| Davicom Semiconductor            | 1         | 0.2%    |
| Aquantia                         | 1         | 0.2%    |
| Accton Technology                | 1         | 0.2%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 150       | 28.63%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 31        | 5.92%   |
| Intel I211 Gigabit Network Connection                             | 27        | 5.15%   |
| Intel I210 Gigabit Network Connection                             | 23        | 4.39%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 18        | 3.44%   |
| Intel 82567LM Gigabit Network Connection                          | 16        | 3.05%   |
| Intel Ethernet Connection I219-LM                                 | 13        | 2.48%   |
| Intel 82574L Gigabit Network Connection                           | 12        | 2.29%   |
| Intel Ethernet Connection (3) I218-LM                             | 11        | 2.1%    |
| Intel I350 Gigabit Network Connection                             | 10        | 1.91%   |
| Intel Ethernet Connection I217-LM                                 | 10        | 1.91%   |
| Intel 82577LM Gigabit Network Connection                          | 9         | 1.72%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 8         | 1.53%   |
| Intel Ethernet Connection (4) I219-V                              | 7         | 1.34%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 1.15%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 0.95%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 0.95%   |
| Intel 82573L Gigabit Ethernet Controller                          | 5         | 0.95%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                   | 5         | 0.95%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4         | 0.76%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 4         | 0.76%   |
| Intel Ethernet Controller I225-V                                  | 4         | 0.76%   |
| Intel Ethernet Connection (7) I219-LM                             | 4         | 0.76%   |
| Intel Ethernet Connection (6) I219-V                              | 4         | 0.76%   |
| Intel Ethernet Connection (2) I219-LM                             | 4         | 0.76%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 0.76%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 0.57%   |
| Nvidia MCP79 Ethernet                                             | 3         | 0.57%   |
| Intel Ethernet Connection (3) I218-V                              | 3         | 0.57%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.57%   |
| Intel Ethernet Connection (10) I219-V                             | 3         | 0.57%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 3         | 0.57%   |
| Intel 82566MM Gigabit Network Connection                          | 3         | 0.57%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 3         | 0.57%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 3         | 0.57%   |
| VIA VT6105M [Rhine-III]                                           | 2         | 0.38%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2         | 0.38%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 0.38%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 0.38%   |
| Intel Platform Controller Hub EG20T Gigabit Ethernet Controller   | 2         | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 483       | 56.23%  |
| WiFi     | 347       | 40.4%   |
| Modem    | 17        | 1.98%   |
| Unknown  | 12        | 1.4%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 261       | 52.41%  |
| WiFi     | 237       | 47.59%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 292       | 52.14%  |
| 1     | 159       | 28.39%  |
| 3     | 39        | 6.96%   |
| 4     | 29        | 5.18%   |
| 0     | 29        | 5.18%   |
| 5     | 4         | 0.71%   |
| 8     | 3         | 0.54%   |
| 7     | 2         | 0.36%   |
| 6     | 2         | 0.36%   |
| 12    | 1         | 0.18%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 557       | 99.64%  |
| Yes  | 2         | 0.36%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 125       | 55.56%  |
| Broadcom                        | 31        | 13.78%  |
| Apple                           | 18        | 8%      |
| IMC Networks                    | 9         | 4%      |
| Realtek Semiconductor           | 8         | 3.56%   |
| Foxconn / Hon Hai               | 8         | 3.56%   |
| Alps Electric                   | 7         | 3.11%   |
| Qualcomm Atheros Communications | 6         | 2.67%   |
| Cambridge Silicon Radio         | 4         | 1.78%   |
| Hewlett-Packard                 | 2         | 0.89%   |
| ASUSTek Computer                | 2         | 0.89%   |
| Taiyo Yuden                     | 1         | 0.44%   |
| Skylight Digital                | 1         | 0.44%   |
| Ralink                          | 1         | 0.44%   |
| Lite-On Technology              | 1         | 0.44%   |
| Creative Technology             | 1         | 0.44%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 61        | 27.11%  |
| Intel AX200 Bluetooth                                       | 21        | 9.33%   |
| Intel AX201 Bluetooth                                       | 17        | 7.56%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 9         | 4%      |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 9         | 4%      |
| Broadcom BCM2045B (BDC-2.1)                                 | 9         | 4%      |
| Apple Broadcom Built-in Bluetooth                           | 8         | 3.56%   |
| Apple Bluetooth Host Controller                             | 8         | 3.56%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 6         | 2.67%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 6         | 2.67%   |
| Realtek Bluetooth Adapter                                   | 5         | 2.22%   |
| Alps Electric UGTZ4 Bluetooth                               | 5         | 2.22%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 4         | 1.78%   |
| Intel Wireless-AC 3168 Bluetooth                            | 4         | 1.78%   |
| Intel AX210 Bluetooth                                       | 4         | 1.78%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 4         | 1.78%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 2         | 0.89%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip        | 2         | 0.89%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 2         | 0.89%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 2         | 0.89%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011]      | 2         | 0.89%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 2         | 0.89%   |
| Foxconn / Hon Hai RZ616 Bluetooth Adapter                   | 2         | 0.89%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device    | 2         | 0.89%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 2         | 0.89%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 2         | 0.89%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 2         | 0.89%   |
| Alps Electric BCM2046 Bluetooth Device                      | 2         | 0.89%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)                     | 1         | 0.44%   |
| Skylight Digital Realtek Bluetooth Adapter                  | 1         | 0.44%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 0.44%   |
| Realtek Bluetooth 4.2 Adapter                               | 1         | 0.44%   |
| Realtek Bluetooth 4.0 Adapter                               | 1         | 0.44%   |
| Ralink RT3290 Bluetooth                                     | 1         | 0.44%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 1         | 0.44%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 0.44%   |
| Lite-On Atheros AR3012 Bluetooth                            | 1         | 0.44%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 1         | 0.44%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 0.44%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 0.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 343       | 65.21%  |
| AMD                                  | 117       | 22.24%  |
| Nvidia                               | 35        | 6.65%   |
| C-Media Electronics                  | 8         | 1.52%   |
| VIA Technologies                     | 3         | 0.57%   |
| Logitech                             | 3         | 0.57%   |
| ULi Electronics                      | 2         | 0.38%   |
| JMTek                                | 2         | 0.38%   |
| Generalplus Technology               | 2         | 0.38%   |
| ESS Technology                       | 2         | 0.38%   |
| Creative Labs                        | 2         | 0.38%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.19%   |
| Texas Instruments                    | 1         | 0.19%   |
| Silicon Integrated Systems [SiS]     | 1         | 0.19%   |
| Lenovo                               | 1         | 0.19%   |
| Elgato Systems                       | 1         | 0.19%   |
| Dell                                 | 1         | 0.19%   |
| Blue Microphones                     | 1         | 0.19%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                   | 46        | 7.04%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 32        | 4.9%    |
| AMD Family 17h/19h HD Audio Controller                                            | 29        | 4.44%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 27        | 4.13%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 26        | 3.98%   |
| Intel Broadwell-U Audio Controller                                                | 26        | 3.98%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 24        | 3.68%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 23        | 3.52%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 18        | 2.76%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 18        | 2.76%   |
| AMD Starship/Matisse HD Audio Controller                                          | 17        | 2.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 16        | 2.45%   |
| Intel Haswell-ULT HD Audio Controller                                             | 15        | 2.3%    |
| Intel 8 Series HD Audio Controller                                                | 15        | 2.3%    |
| AMD SBx00 Azalia (Intel HDA)                                                      | 15        | 2.3%    |
| AMD FCH Azalia Controller                                                         | 13        | 1.99%   |
| Intel Cannon Lake PCH cAVS                                                        | 12        | 1.84%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 12        | 1.84%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 11        | 1.68%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 9         | 1.38%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 9         | 1.38%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 9         | 1.38%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 8         | 1.23%   |
| AMD Kabini HDMI/DP Audio                                                          | 8         | 1.23%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 7         | 1.07%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 7         | 1.07%   |
| AMD Navi 10 HDMI Audio                                                            | 7         | 1.07%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 7         | 1.07%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 6         | 0.92%   |
| Intel Comet Lake PCH-V cAVS                                                       | 5         | 0.77%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                 | 5         | 0.77%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 5         | 0.77%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 5         | 0.77%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 5         | 0.77%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 5         | 0.77%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                      | 5         | 0.77%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 5         | 0.77%   |
| Nvidia MCP61 High Definition Audio                                                | 4         | 0.61%   |
| Nvidia High Definition Audio Controller                                           | 4         | 0.61%   |
| Nvidia GP106 High Definition Audio Controller                                     | 4         | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 20        | 26.67%  |
| Samsung Electronics | 16        | 21.33%  |
| SK hynix            | 10        | 13.33%  |
| Kingston            | 8         | 10.67%  |
| Micron Technology   | 5         | 6.67%   |
| Elpida              | 4         | 5.33%   |
| Crucial             | 3         | 4%      |
| Transcend           | 2         | 2.67%   |
| Ramaxel Technology  | 2         | 2.67%   |
| Corsair             | 2         | 2.67%   |
| Nanya Technology    | 1         | 1.33%   |
| A-DATA Technology   | 1         | 1.33%   |
| Unknown             | 1         | 1.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s             | 3         | 3.57%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s   | 3         | 3.57%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s       | 3         | 3.57%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s          | 2         | 2.38%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 2         | 2.38%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s   | 2         | 2.38%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s   | 2         | 2.38%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 2400MT/s     | 2         | 2.38%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s | 2         | 2.38%   |
| Unknown RAM Module 512MB SODIMM SDRAM                   | 1         | 1.19%   |
| Unknown RAM Module 512MB SODIMM DDR                     | 1         | 1.19%   |
| Unknown RAM Module 512MB DIMM SDRAM                     | 1         | 1.19%   |
| Unknown RAM Module 512MB DIMM DDR 400MT/s               | 1         | 1.19%   |
| Unknown RAM Module 512MB DIMM 400MT/s                   | 1         | 1.19%   |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s             | 1         | 1.19%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s              | 1         | 1.19%   |
| Unknown RAM Module 256MB SODIMM DRAM                    | 1         | 1.19%   |
| Unknown RAM Module 256MB DIMM 333MT/s                   | 1         | 1.19%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s          | 1         | 1.19%   |
| Unknown RAM Module 2048MB SODIMM DDR2                   | 1         | 1.19%   |
| Unknown RAM Module 2048MB DIMM DDR2 266MT/s             | 1         | 1.19%   |
| Unknown RAM Module 1GB SODIMM DDR2                      | 1         | 1.19%   |
| Unknown RAM Module 1GB DIMM 400MT/s                     | 1         | 1.19%   |
| Unknown RAM Module 128MB SODIMM DRAM                    | 1         | 1.19%   |
| Unknown RAM Module 1024MB SODIMM DDR                    | 1         | 1.19%   |
| Unknown RAM Module 1024MB DIMM DDR                      | 1         | 1.19%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                  | 1         | 1.19%   |
| Transcend RAM TS1GSK64W6H 8GB DIMM DDR3 1600MT/s        | 1         | 1.19%   |
| Transcend RAM TS128MLQ64V6J 1GB DIMM DDR2 667MT/s       | 1         | 1.19%   |
| SK hynix RAM HYMP112U64CP8-Y5 1GB DIMM DDR2 667MT/s     | 1         | 1.19%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 1         | 1.19%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 1         | 1.19%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s  | 1         | 1.19%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s | 1         | 1.19%   |
| SK hynix RAM HMA81GR7AFR8N-VK 8GB DIMM DDR4 2666MT/s    | 1         | 1.19%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB SODIMM LPDDR3 1867MT/s  | 1         | 1.19%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB Chip LPDDR3 1867MT/s    | 1         | 1.19%   |
| SK hynix RAM 484D543332355336 2GB SODIMM DDR3 1333MT/s  | 1         | 1.19%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s   | 1         | 1.19%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 1067MT/s   | 1         | 1.19%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 34        | 51.52%  |
| DDR4    | 13        | 19.7%   |
| DDR2    | 7         | 10.61%  |
| SDRAM   | 3         | 4.55%   |
| DDR     | 3         | 4.55%   |
| DRAM    | 2         | 3.03%   |
| Unknown | 2         | 3.03%   |
| LPDDR3  | 1         | 1.52%   |
| DDR5    | 1         | 1.52%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 50        | 74.63%  |
| DIMM   | 16        | 23.88%  |
| Chip   | 1         | 1.49%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 24        | 32%     |
| 8192  | 16        | 21.33%  |
| 2048  | 12        | 16%     |
| 1024  | 9         | 12%     |
| 512   | 5         | 6.67%   |
| 16384 | 4         | 5.33%   |
| 32768 | 2         | 2.67%   |
| 256   | 2         | 2.67%   |
| 128   | 1         | 1.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 18        | 25.71%  |
| Unknown | 9         | 12.86%  |
| 1333    | 8         | 11.43%  |
| 1334    | 5         | 7.14%   |
| 3200    | 4         | 5.71%   |
| 2400    | 4         | 5.71%   |
| 1067    | 4         | 5.71%   |
| 800     | 4         | 5.71%   |
| 2667    | 3         | 4.29%   |
| 667     | 2         | 2.86%   |
| 400     | 2         | 2.86%   |
| 4800    | 1         | 1.43%   |
| 2666    | 1         | 1.43%   |
| 2133    | 1         | 1.43%   |
| 1867    | 1         | 1.43%   |
| 533     | 1         | 1.43%   |
| 333     | 1         | 1.43%   |
| 266     | 1         | 1.43%   |

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

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 65        | 34.57%  |
| Bison Electronics                      | 24        | 12.77%  |
| IMC Networks                           | 18        | 9.57%   |
| Realtek Semiconductor                  | 12        | 6.38%   |
| Microdia                               | 11        | 5.85%   |
| Lite-On Technology                     | 11        | 5.85%   |
| Logitech                               | 5         | 2.66%   |
| Lenovo                                 | 5         | 2.66%   |
| Sunplus Innovation Technology          | 4         | 2.13%   |
| Ricoh                                  | 4         | 2.13%   |
| Quanta                                 | 4         | 2.13%   |
| Apple                                  | 4         | 2.13%   |
| Syntek                                 | 3         | 1.6%    |
| Suyin                                  | 3         | 1.6%    |
| Silicon Motion                         | 3         | 1.6%    |
| Cheng Uei Precision Industry (Foxlink) | 3         | 1.6%    |
| Alcor Micro                            | 3         | 1.6%    |
| Luxvisions Innotech Limited            | 2         | 1.06%   |
| Z-Star Microelectronics                | 1         | 0.53%   |
| Tripath Technology                     | 1         | 0.53%   |
| Denron                                 | 1         | 0.53%   |
| ALi                                    | 1         | 0.53%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 26        | 13.61%  |
| Lite-On Integrated Camera                                                  | 11        | 5.76%   |
| Bison Integrated Camera                                                    | 11        | 5.76%   |
| IMC Networks Integrated Camera                                             | 8         | 4.19%   |
| Chicony Integrated Camera [ThinkPad]                                       | 7         | 3.66%   |
| Chicony Lenovo Integrated Camera (0.3MP)                                   | 5         | 2.62%   |
| Realtek Integrated_Webcam_HD                                               | 4         | 2.09%   |
| Microdia Integrated_Webcam_HD                                              | 4         | 2.09%   |
| Bison SunplusIT Integrated Camera                                          | 4         | 2.09%   |
| Lenovo Integrated Webcam                                                   | 3         | 1.57%   |
| Chicony Integrated IR Camera                                               | 3         | 1.57%   |
| Chicony Integrated Camera (1280x720@30)                                    | 3         | 1.57%   |
| Syntek Lenovo EasyCamera                                                   | 2         | 1.05%   |
| Realtek USB 2.0 Webcam                                                     | 2         | 1.05%   |
| Lenovo Integrated Webcam [R5U877]                                          | 2         | 1.05%   |
| IMC Networks Realtek DMFT RGB                                              | 2         | 1.05%   |
| Chicony VGA Webcam                                                         | 2         | 1.05%   |
| Chicony ThinkPad T490 Webcam                                               | 2         | 1.05%   |
| Chicony thinkpad t430s camera                                              | 2         | 1.05%   |
| Chicony Sonix ST50220 USB Video Camera                                     | 2         | 1.05%   |
| Chicony FJ Camera                                                          | 2         | 1.05%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 2         | 1.05%   |
| Bison Lenovo EasyCamera                                                    | 2         | 1.05%   |
| Bison EasyCamera                                                           | 2         | 1.05%   |
| Apple FaceTime HD Camera (Built-in)                                        | 2         | 1.05%   |
| Apple FaceTime HD Camera                                                   | 2         | 1.05%   |
| Z-Star Integrated Camera                                                   | 1         | 0.52%   |
| Tripath PC Camera                                                          | 1         | 0.52%   |
| Syntek EasyCamera                                                          | 1         | 0.52%   |
| Suyin Asus Integrated Webcam                                               | 1         | 0.52%   |
| Suyin Acer/Lenovo Webcam [CN0316]                                          | 1         | 0.52%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)                | 1         | 0.52%   |
| Sunplus Integrated_Webcam_FHD                                              | 1         | 0.52%   |
| Sunplus Integrated HD Webcam                                               | 1         | 0.52%   |
| Sunplus HP TrueVision HD Camera                                            | 1         | 0.52%   |
| Sunplus Dell E5570 integrated webcam                                       | 1         | 0.52%   |
| Silicon Motion WebCam SC-10IRQ12340N                                       | 1         | 0.52%   |
| Silicon Motion Realtek USB 2.0 PC Camera                                   | 1         | 0.52%   |
| Silicon Motion Realtek DMFT RGB                                            | 1         | 0.52%   |
| Ricoh USB2.0 Camera                                                        | 1         | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 23        | 31.94%  |
| Synaptics                  | 13        | 18.06%  |
| Upek                       | 11        | 15.28%  |
| AuthenTec                  | 10        | 13.89%  |
| STMicroelectronics         | 7         | 9.72%   |
| Shenzhen Goodix Technology | 5         | 6.94%   |
| Elan Microelectronics      | 2         | 2.78%   |
| Samsung Electronics        | 1         | 1.39%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor             | 15        | 20.83%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 11        | 15.28%  |
| STMicroelectronics Fingerprint Reader                    | 7         | 9.72%   |
| AuthenTec AES2810                                        | 5         | 6.94%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 4         | 5.56%   |
| Shenzhen Goodix Fingerprint Reader                       | 4         | 5.56%   |
| AuthenTec AES2501 Fingerprint Sensor                     | 4         | 5.56%   |
| Validity Sensors Synaptics WBDI                          | 3         | 4.17%   |
| Synaptics WBDI                                           | 3         | 4.17%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor        | 2         | 2.78%   |
| Validity Sensors VFS5011 Fingerprint Reader              | 2         | 2.78%   |
| Synaptics Metallica MIS Touch Fingerprint Reader         | 2         | 2.78%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 2.78%   |
| Elan Fingerprint Sensor                                  | 2         | 2.78%   |
| Validity Sensors VFS451 Fingerprint Reader               | 1         | 1.39%   |
| Synaptics UWP WBDI Device                                | 1         | 1.39%   |
| Synaptics Metallica MOH Touch Fingerprint Reader         | 1         | 1.39%   |
| Shenzhen Goodix Fingerprint Reader SGX                   | 1         | 1.39%   |
| Samsung CanvasBio Fingerprint Reader                     | 1         | 1.39%   |
| AuthenTec AES2660                                        | 1         | 1.39%   |

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
| 1     | 236       | 41.48%  |
| 0     | 164       | 28.82%  |
| 2     | 117       | 20.56%  |
| 3     | 26        | 4.57%   |
| 4     | 13        | 2.28%   |
| 5     | 6         | 1.05%   |
| 7     | 3         | 0.53%   |
| 6     | 3         | 0.53%   |
| 8     | 1         | 0.18%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 296       | 48.93%  |
| Graphics card            | 105       | 17.36%  |
| Net/wireless             | 66        | 10.91%  |
| Firewire controller      | 49        | 8.1%    |
| Sound                    | 22        | 3.64%   |
| Storage/ata              | 19        | 3.14%   |
| Net/ethernet             | 15        | 2.48%   |
| Network                  | 11        | 1.82%   |
| Modem                    | 8         | 1.32%   |
| Storage                  | 5         | 0.83%   |
| Storage/ide              | 4         | 0.66%   |
| Card reader              | 2         | 0.33%   |
| Storage/raid             | 1         | 0.17%   |
| Storage/nvme             | 1         | 0.17%   |
| Bluetooth                | 1         | 0.17%   |

