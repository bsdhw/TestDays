OpenBSD - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------

A project to collect tested hardware configurations for OpenBSD.

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

Total: 447

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Panasonic     | CFSX4-1                     | [86abd76c4e](https://bsd-hardware.info/?probe=86abd76c4e) | Sep 27, 2023 |
| GPD           | G1619-04                    | [30ad9b72b5](https://bsd-hardware.info/?probe=30ad9b72b5) | Sep 23, 2023 |
| Dell          | Latitude E7470              | [11cf3b211c](https://bsd-hardware.info/?probe=11cf3b211c) | Sep 22, 2023 |
| Panasonic     | CFSX4-1                     | [398d7a6f26](https://bsd-hardware.info/?probe=398d7a6f26) | Sep 20, 2023 |
| Dell          | XPS 9320                    | [d80b3d5a54](https://bsd-hardware.info/?probe=d80b3d5a54) | Sep 14, 2023 |
| Dell          | Latitude E6420              | [b90b748742](https://bsd-hardware.info/?probe=b90b748742) | Sep 14, 2023 |
| Lenovo        | ThinkPad X140e 20BMS03E0... | [54b04ea958](https://bsd-hardware.info/?probe=54b04ea958) | Sep 12, 2023 |
| Panasonic     | CFSX4-1                     | [8f54654916](https://bsd-hardware.info/?probe=8f54654916) | Sep 01, 2023 |
| Dell          | Latitude 7280               | [c858f191cf](https://bsd-hardware.info/?probe=c858f191cf) | Aug 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [c8e95f3772](https://bsd-hardware.info/?probe=c8e95f3772) | Aug 26, 2023 |
| Getac         | V110G2                      | [884803a6bd](https://bsd-hardware.info/?probe=884803a6bd) | Aug 25, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [27cf2b3e46](https://bsd-hardware.info/?probe=27cf2b3e46) | Aug 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [9beb5f6126](https://bsd-hardware.info/?probe=9beb5f6126) | Aug 17, 2023 |
| Fujitsu Si... | LIFEBOOK P1610              | [bb055a94f0](https://bsd-hardware.info/?probe=bb055a94f0) | Aug 12, 2023 |
| Apple         | MacBookAir4,2               | [b1c97a3a9d](https://bsd-hardware.info/?probe=b1c97a3a9d) | Aug 09, 2023 |
| Apple         | MacBookAir4,2               | [4fdd124b61](https://bsd-hardware.info/?probe=4fdd124b61) | Aug 07, 2023 |
| Lenovo        | ThinkPad T410 2522NP6       | [194b8efa98](https://bsd-hardware.info/?probe=194b8efa98) | Jul 25, 2023 |
| Panasonic     | CFSX4-1                     | [461ad23cc9](https://bsd-hardware.info/?probe=461ad23cc9) | Jul 24, 2023 |
| Lenovo        | B590 20208                  | [ce1aade2c0](https://bsd-hardware.info/?probe=ce1aade2c0) | Jul 24, 2023 |
| Panasonic     | CFSX4-1                     | [1ac1ddd084](https://bsd-hardware.info/?probe=1ac1ddd084) | Jul 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [173fe60308](https://bsd-hardware.info/?probe=173fe60308) | Jul 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [26e44ab6e6](https://bsd-hardware.info/?probe=26e44ab6e6) | Jul 23, 2023 |
| ASUSTek       | 900                         | [2e55f5d4cc](https://bsd-hardware.info/?probe=2e55f5d4cc) | Jul 20, 2023 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | [386a80104d](https://bsd-hardware.info/?probe=386a80104d) | Jul 19, 2023 |
| IBM           | ThinkPad T43 1871F1G        | [d6fbc6ebfb](https://bsd-hardware.info/?probe=d6fbc6ebfb) | Jul 18, 2023 |
| Lenovo        | B590 20208                  | [f734b93999](https://bsd-hardware.info/?probe=f734b93999) | Jul 16, 2023 |
| Sony          | VPCX115KX                   | [9dab449a23](https://bsd-hardware.info/?probe=9dab449a23) | Jul 15, 2023 |
| Tactus        | GeoBook 140                 | [4b7383c876](https://bsd-hardware.info/?probe=4b7383c876) | Jul 11, 2023 |
| Panasonic     | CFSX4-1                     | [ff83a965d2](https://bsd-hardware.info/?probe=ff83a965d2) | Jun 15, 2023 |
| Lenovo        | ThinkPad T430 2344BZU       | [01df487b47](https://bsd-hardware.info/?probe=01df487b47) | Jun 14, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [9f18b1b304](https://bsd-hardware.info/?probe=9f18b1b304) | Jun 06, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [85c18dbbb5](https://bsd-hardware.info/?probe=85c18dbbb5) | Jun 06, 2023 |
| Toshiba       | NB250                       | [62c572e895](https://bsd-hardware.info/?probe=62c572e895) | May 27, 2023 |
| Tactus        | GeoFlex 110                 | [df93ad7e83](https://bsd-hardware.info/?probe=df93ad7e83) | May 27, 2023 |
| Lenovo        | ThinkPad X140e 20BMS03E0... | [580c52399f](https://bsd-hardware.info/?probe=580c52399f) | May 25, 2023 |
| Lenovo        | ThinkPad X140e 20BMS03E0... | [84e3ac62d5](https://bsd-hardware.info/?probe=84e3ac62d5) | May 23, 2023 |
| Unknown       | Apple MacBook Pro (13-in... | [5e25a49c65](https://bsd-hardware.info/?probe=5e25a49c65) | May 20, 2023 |
| Lenovo        | ThinkPad X201 3323BBG       | [7b529b0888](https://bsd-hardware.info/?probe=7b529b0888) | May 17, 2023 |
| Lenovo        | ThinkPad T61 7659AS5        | [7732b2cfa7](https://bsd-hardware.info/?probe=7732b2cfa7) | May 15, 2023 |
| Lenovo        | ThinkPad T61 7659AS5        | [b6071c549a](https://bsd-hardware.info/?probe=b6071c549a) | May 15, 2023 |
| Lenovo        | ThinkPad T410 2537N24       | [6cd0f02045](https://bsd-hardware.info/?probe=6cd0f02045) | May 08, 2023 |
| Matsushita... | CF-48V4KNDQM                | [79f10d24d6](https://bsd-hardware.info/?probe=79f10d24d6) | May 07, 2023 |
| ASUSTek       | 1000HE                      | [36214f8bed](https://bsd-hardware.info/?probe=36214f8bed) | May 07, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [d2bd7a8764](https://bsd-hardware.info/?probe=d2bd7a8764) | May 07, 2023 |
| Lenovo        | ThinkPad T500 205663G       | [d706da9400](https://bsd-hardware.info/?probe=d706da9400) | May 06, 2023 |
| Lenovo        | ThinkPad T480s 20L8A00KC... | [44ddee0eec](https://bsd-hardware.info/?probe=44ddee0eec) | May 06, 2023 |
| Matsushita... | CF-51RCVDNLM                | [105a885451](https://bsd-hardware.info/?probe=105a885451) | May 05, 2023 |
| Lenovo        | ThinkPad T420s 41742BU      | [161fe49de4](https://bsd-hardware.info/?probe=161fe49de4) | May 05, 2023 |
| Lenovo        | ThinkPad X230 2325T4T       | [00303b7a59](https://bsd-hardware.info/?probe=00303b7a59) | May 05, 2023 |
| Lenovo        | ThinkPad X220 429043U       | [bb714a4350](https://bsd-hardware.info/?probe=bb714a4350) | May 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [28e76d5531](https://bsd-hardware.info/?probe=28e76d5531) | May 04, 2023 |
| Lenovo        | ThinkPad T430 2347GZU       | [8c3f486dbc](https://bsd-hardware.info/?probe=8c3f486dbc) | May 03, 2023 |
| Panasonic     | CF-52PFPBSFQ                | [e2c3df29b5](https://bsd-hardware.info/?probe=e2c3df29b5) | May 03, 2023 |
| Panasonic     | CF-53AAGHYDM                | [c7daf17edb](https://bsd-hardware.info/?probe=c7daf17edb) | May 02, 2023 |
| Lenovo        | ThinkPad X260 20F5S2GM00    | [c4af168c4a](https://bsd-hardware.info/?probe=c4af168c4a) | May 01, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [cf504f51df](https://bsd-hardware.info/?probe=cf504f51df) | May 01, 2023 |
| Fujitsu       | LIFEBOOK E752               | [44ea9fb6ae](https://bsd-hardware.info/?probe=44ea9fb6ae) | Apr 30, 2023 |
| HP            | Pavilion Notebook           | [247810c987](https://bsd-hardware.info/?probe=247810c987) | Apr 24, 2023 |
| HP            | Pavilion Notebook           | [243a9c2f22](https://bsd-hardware.info/?probe=243a9c2f22) | Apr 22, 2023 |
| Lenovo        | G570 20079                  | [0ebba481d1](https://bsd-hardware.info/?probe=0ebba481d1) | Apr 14, 2023 |
| Lenovo        | ThinkPad T440s 20ARA07PL... | [04ddab3620](https://bsd-hardware.info/?probe=04ddab3620) | Apr 14, 2023 |
| Lenovo        | ThinkPad X230 23257EP       | [e94085cd2d](https://bsd-hardware.info/?probe=e94085cd2d) | Apr 12, 2023 |
| Fujitsu       | LIFEBOOK U810               | [3073cd605c](https://bsd-hardware.info/?probe=3073cd605c) | Apr 06, 2023 |
| Fujitsu       | LIFEBOOK U810               | [c7718b4aa3](https://bsd-hardware.info/?probe=c7718b4aa3) | Apr 03, 2023 |
| Apple         | MacBookPro12,1              | [640aad419a](https://bsd-hardware.info/?probe=640aad419a) | Apr 02, 2023 |
| Lenovo        | ThinkPad T450s 20BW001KL... | [4f6a7e2739](https://bsd-hardware.info/?probe=4f6a7e2739) | Apr 02, 2023 |
| Lenovo        | ThinkPad T410 2518A37       | [f5537face6](https://bsd-hardware.info/?probe=f5537face6) | Mar 27, 2023 |
| Dell          | G5 5587                     | [9b7714cbab](https://bsd-hardware.info/?probe=9b7714cbab) | Mar 24, 2023 |
| Dell          | G5 5587                     | [c118e0665f](https://bsd-hardware.info/?probe=c118e0665f) | Mar 24, 2023 |
| Lenovo        | ThinkPad T410 2518A37       | [42fffdf3f2](https://bsd-hardware.info/?probe=42fffdf3f2) | Mar 23, 2023 |
| Intel         | S1200RP_SE                  | [5ae9400f0b](https://bsd-hardware.info/?probe=5ae9400f0b) | Mar 17, 2023 |
| OEGStone      | W54_55SU1,SUW               | [7a2b28c47f](https://bsd-hardware.info/?probe=7a2b28c47f) | Mar 17, 2023 |
| Acer          | Nitro AN515-55              | [e023282dcd](https://bsd-hardware.info/?probe=e023282dcd) | Mar 13, 2023 |
| HP            | EliteBook 2530p             | [e70d97f7d6](https://bsd-hardware.info/?probe=e70d97f7d6) | Mar 09, 2023 |
| HP            | 240 G6 Notebook PC          | [d872652e25](https://bsd-hardware.info/?probe=d872652e25) | Feb 28, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [aef791947c](https://bsd-hardware.info/?probe=aef791947c) | Feb 23, 2023 |
| Apple         | MacBookPro11,1              | [673f6c0a01](https://bsd-hardware.info/?probe=673f6c0a01) | Feb 17, 2023 |
| Apple         | MacBookAir6,1               | [96fa5325d1](https://bsd-hardware.info/?probe=96fa5325d1) | Feb 11, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [4d69517a13](https://bsd-hardware.info/?probe=4d69517a13) | Feb 07, 2023 |
| Panasonic     | CF-30KAPAXAM                | [baa7612257](https://bsd-hardware.info/?probe=baa7612257) | Feb 07, 2023 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | [bccdd2f331](https://bsd-hardware.info/?probe=bccdd2f331) | Jan 30, 2023 |
| Google        | Kefka                       | [83771661c6](https://bsd-hardware.info/?probe=83771661c6) | Jan 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [1d040b684b](https://bsd-hardware.info/?probe=1d040b684b) | Jan 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [dcdf55f06e](https://bsd-hardware.info/?probe=dcdf55f06e) | Jan 17, 2023 |
| Apple         | MacBookAir7,2               | [d8007634f3](https://bsd-hardware.info/?probe=d8007634f3) | Jan 17, 2023 |
| HP            | ProBook 455 G7              | [600f7f4f4f](https://bsd-hardware.info/?probe=600f7f4f4f) | Jan 16, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [ced6c29193](https://bsd-hardware.info/?probe=ced6c29193) | Jan 14, 2023 |
| HP            | Presario V2000 (EZ621UA#... | [847af5b70f](https://bsd-hardware.info/?probe=847af5b70f) | Jan 14, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | [82e9263905](https://bsd-hardware.info/?probe=82e9263905) | Jan 11, 2023 |
| Lenovo        | G50-80 80E5                 | [549b75038e](https://bsd-hardware.info/?probe=549b75038e) | Jan 08, 2023 |
| Lenovo        | G50-80 80E5                 | [5e81493c8d](https://bsd-hardware.info/?probe=5e81493c8d) | Jan 08, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [4014cc42ed](https://bsd-hardware.info/?probe=4014cc42ed) | Jan 08, 2023 |
| Notebook      | NS5x_NS7xPU                 | [7dc1fdfadb](https://bsd-hardware.info/?probe=7dc1fdfadb) | Jan 02, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | [3b0ef08599](https://bsd-hardware.info/?probe=3b0ef08599) | Jan 01, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | [c791e3e3fd](https://bsd-hardware.info/?probe=c791e3e3fd) | Dec 30, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B9450FA_... | [d5fa6c651c](https://bsd-hardware.info/?probe=d5fa6c651c) | Dec 30, 2022 |
| Star Labs     | Lite                        | [9ad15636dd](https://bsd-hardware.info/?probe=9ad15636dd) | Dec 25, 2022 |
| Tactus        | GeoFlex 110                 | [955c355b47](https://bsd-hardware.info/?probe=955c355b47) | Dec 23, 2022 |
| Toshiba       | Satellite BE96-F299         | [ca475dd1d0](https://bsd-hardware.info/?probe=ca475dd1d0) | Dec 23, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [b38d32b139](https://bsd-hardware.info/?probe=b38d32b139) | Dec 23, 2022 |
| Lenovo        | ThinkPad T480 20L6S13100    | [67daa912fa](https://bsd-hardware.info/?probe=67daa912fa) | Dec 23, 2022 |
| Lenovo        | ThinkPad T60 1951A47        | [e254601f07](https://bsd-hardware.info/?probe=e254601f07) | Dec 21, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [af2a9d1a42](https://bsd-hardware.info/?probe=af2a9d1a42) | Dec 20, 2022 |
| Lenovo        | ThinkPad X200 Tablet 744... | [ea686f63f5](https://bsd-hardware.info/?probe=ea686f63f5) | Dec 19, 2022 |
| Framework     | Laptop                      | [9dcd3592db](https://bsd-hardware.info/?probe=9dcd3592db) | Dec 19, 2022 |
| HP            | ProBook 430 G7              | [0e2278affa](https://bsd-hardware.info/?probe=0e2278affa) | Dec 14, 2022 |
| Panasonic     | CF-54-1                     | [0c5820ea0d](https://bsd-hardware.info/?probe=0c5820ea0d) | Dec 01, 2022 |
| Dell          | Vostro 3501                 | [61f8a35700](https://bsd-hardware.info/?probe=61f8a35700) | Nov 25, 2022 |
| Lenovo        | ThinkPad X230 2325T4T       | [f0cc17c7eb](https://bsd-hardware.info/?probe=f0cc17c7eb) | Nov 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [4044f32351](https://bsd-hardware.info/?probe=4044f32351) | Nov 12, 2022 |
| Lenovo        | ThinkPad X260 20F5S2GM00    | [b8874a6df3](https://bsd-hardware.info/?probe=b8874a6df3) | Nov 10, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [e8aea441aa](https://bsd-hardware.info/?probe=e8aea441aa) | Nov 06, 2022 |
| Lenovo        | ThinkPad X220 429043U       | [e5716f886a](https://bsd-hardware.info/?probe=e5716f886a) | Oct 30, 2022 |
| Lenovo        | ThinkPad T420s 41742BU      | [34f0a2bc03](https://bsd-hardware.info/?probe=34f0a2bc03) | Oct 30, 2022 |
| Fujitsu       | LIFEBOOK E752               | [e3c5057898](https://bsd-hardware.info/?probe=e3c5057898) | Oct 29, 2022 |
| Panasonic     | CF-53AAGHYDM                | [f2fafaa9e3](https://bsd-hardware.info/?probe=f2fafaa9e3) | Oct 27, 2022 |
| Matsushita... | CF-48V4KNDQM                | [d96fbc17b5](https://bsd-hardware.info/?probe=d96fbc17b5) | Oct 27, 2022 |
| Panasonic     | CF-52PFPBSFQ                | [088e0245af](https://bsd-hardware.info/?probe=088e0245af) | Oct 27, 2022 |
| Matsushita... | CF-51RCVDNLM                | [6e8067d4d8](https://bsd-hardware.info/?probe=6e8067d4d8) | Oct 26, 2022 |
| Lenovo        | ThinkPad T420s 4174DL7      | [82d774e711](https://bsd-hardware.info/?probe=82d774e711) | Oct 26, 2022 |
| Lenovo        | ThinkPad T410 2537N24       | [b7a4ee06a6](https://bsd-hardware.info/?probe=b7a4ee06a6) | Oct 26, 2022 |
| Fujitsu       | LIFEBOOK E752               | [06e6c07e90](https://bsd-hardware.info/?probe=06e6c07e90) | Oct 25, 2022 |
| Lenovo        | ThinkPad T430 2347GZU       | [f2236f17ee](https://bsd-hardware.info/?probe=f2236f17ee) | Oct 25, 2022 |
| ASUSTek       | 1000HE                      | [c4bbcf9537](https://bsd-hardware.info/?probe=c4bbcf9537) | Oct 24, 2022 |
| ASUSTek       | K53TA                       | [521283b723](https://bsd-hardware.info/?probe=521283b723) | Oct 22, 2022 |
| Alienware     | m15                         | [3304a767ba](https://bsd-hardware.info/?probe=3304a767ba) | Oct 22, 2022 |
| Dell          | Latitude E6420              | [07b078fdef](https://bsd-hardware.info/?probe=07b078fdef) | Oct 04, 2022 |
| Lenovo        | ThinkPad T410 2518C3U       | [627206d154](https://bsd-hardware.info/?probe=627206d154) | Oct 04, 2022 |
| Tactus        | GeoFlex 110                 | [0b93b5f915](https://bsd-hardware.info/?probe=0b93b5f915) | Sep 28, 2022 |
| Toshiba       | Satellite BE96-F299         | [15b93c9f4b](https://bsd-hardware.info/?probe=15b93c9f4b) | Sep 21, 2022 |
| Toshiba       | Satellite BE96-F299         | [9beae1547d](https://bsd-hardware.info/?probe=9beae1547d) | Sep 21, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [7576399c3c](https://bsd-hardware.info/?probe=7576399c3c) | Aug 20, 2022 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | [2e7d570822](https://bsd-hardware.info/?probe=2e7d570822) | Aug 20, 2022 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | [7afa139f4f](https://bsd-hardware.info/?probe=7afa139f4f) | Aug 20, 2022 |
| Alienware     | m15 R4                      | [769c5c43f3](https://bsd-hardware.info/?probe=769c5c43f3) | Aug 13, 2022 |
| HUAWEI        | BOM-WXX9                    | [4ba15a31d9](https://bsd-hardware.info/?probe=4ba15a31d9) | Aug 10, 2022 |
| Dell          | XPS 13 9360                 | [1d342196fb](https://bsd-hardware.info/?probe=1d342196fb) | Aug 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X545... | [bf5cea4ab5](https://bsd-hardware.info/?probe=bf5cea4ab5) | Jul 30, 2022 |
| Lenovo        | ThinkPad X200 7458NP9       | [4192abf903](https://bsd-hardware.info/?probe=4192abf903) | Jul 20, 2022 |
| ASUSTek       | X751LB                      | [5c2ef28301](https://bsd-hardware.info/?probe=5c2ef28301) | Jul 12, 2022 |
| Acer          | Nitro AN515-55              | [f98a69101e](https://bsd-hardware.info/?probe=f98a69101e) | Jul 08, 2022 |
| Lenovo        | IdeaPad S12 20021,2959      | [c1bf998d6a](https://bsd-hardware.info/?probe=c1bf998d6a) | Jul 07, 2022 |
| Dell          | Inspiron 5515               | [dca437b993](https://bsd-hardware.info/?probe=dca437b993) | Jul 01, 2022 |
| ASUSTek       | K53TA                       | [6ce39c5e61](https://bsd-hardware.info/?probe=6ce39c5e61) | Jun 27, 2022 |
| HP            | EliteBook 8440p             | [25d5a77b59](https://bsd-hardware.info/?probe=25d5a77b59) | Jun 17, 2022 |
| Lenovo        | ThinkPad L530 24812TG       | [5b66684c4a](https://bsd-hardware.info/?probe=5b66684c4a) | Jun 05, 2022 |
| Lenovo        | ThinkPad Yoga 260 20FES1... | [73ab89b8f0](https://bsd-hardware.info/?probe=73ab89b8f0) | Jun 05, 2022 |
| Lenovo        | ThinkPad Yoga 260 20FES1... | [637f87f44e](https://bsd-hardware.info/?probe=637f87f44e) | Jun 05, 2022 |
| Apple         | MacBookPro5,3               | [3b03bdf595](https://bsd-hardware.info/?probe=3b03bdf595) | May 29, 2022 |
| Lenovo        | ThinkPad X250 20CLS4WV08    | [0419c52079](https://bsd-hardware.info/?probe=0419c52079) | May 11, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [64600e1c24](https://bsd-hardware.info/?probe=64600e1c24) | May 11, 2022 |
| TUXEDO        | Aura 15 Gen1                | [49d1cd3009](https://bsd-hardware.info/?probe=49d1cd3009) | May 10, 2022 |
| Fujitsu       | LIFEBOOK E752               | [3e60a82218](https://bsd-hardware.info/?probe=3e60a82218) | May 06, 2022 |
| ASUSTek       | 1000HE                      | [a6393754b4](https://bsd-hardware.info/?probe=a6393754b4) | May 05, 2022 |
| Matsushita... | CF-48V4KNDQM                | [774cab5326](https://bsd-hardware.info/?probe=774cab5326) | May 03, 2022 |
| Matsushita... | CF-51RCVDNLM                | [4b1abdd507](https://bsd-hardware.info/?probe=4b1abdd507) | May 03, 2022 |
| Lenovo        | ThinkPad T410 2537N24       | [2884106c6b](https://bsd-hardware.info/?probe=2884106c6b) | May 03, 2022 |
| Lenovo        | ThinkPad T430 2347GZU       | [00ba6ca9f8](https://bsd-hardware.info/?probe=00ba6ca9f8) | May 03, 2022 |
| Lenovo        | ThinkPad T420s 41742BU      | [6b77fe651f](https://bsd-hardware.info/?probe=6b77fe651f) | May 03, 2022 |
| Lenovo        | ThinkPad X220 429043U       | [f3c30a6190](https://bsd-hardware.info/?probe=f3c30a6190) | May 02, 2022 |
| Panasonic     | CF-53AAGHYDM                | [abd8754907](https://bsd-hardware.info/?probe=abd8754907) | May 01, 2022 |
| Panasonic     | CF-52PFPBSFQ                | [1ce63e2214](https://bsd-hardware.info/?probe=1ce63e2214) | Apr 29, 2022 |
| MSI           | Modern 14 B11MOL            | [9a61443be9](https://bsd-hardware.info/?probe=9a61443be9) | Apr 25, 2022 |
| DEXP          | NAVIS P100                  | [a9c8814bf8](https://bsd-hardware.info/?probe=a9c8814bf8) | Apr 22, 2022 |
| Lenovo        | ThinkPad X121e 3053A52      | [68d0bf2a99](https://bsd-hardware.info/?probe=68d0bf2a99) | Apr 22, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [b4a6761ab3](https://bsd-hardware.info/?probe=b4a6761ab3) | Apr 21, 2022 |
| Lenovo        | ThinkPad X220 4291QT1       | [f7aa3576ae](https://bsd-hardware.info/?probe=f7aa3576ae) | Apr 13, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [0e836941e0](https://bsd-hardware.info/?probe=0e836941e0) | Apr 11, 2022 |
| Apple         | MacBook5,1                  | [41d62dde7d](https://bsd-hardware.info/?probe=41d62dde7d) | Apr 10, 2022 |
| Apple         | MacBook5,1                  | [c5f7b5499a](https://bsd-hardware.info/?probe=c5f7b5499a) | Apr 10, 2022 |
| Lenovo        | ThinkPad X260 20F5S08Q00    | [1d1db3eab4](https://bsd-hardware.info/?probe=1d1db3eab4) | Apr 03, 2022 |
| IBM           | 2658MNG                     | [e3a5a587fa](https://bsd-hardware.info/?probe=e3a5a587fa) | Mar 28, 2022 |
| Lenovo        | ThinkPad X200 745969G       | [086a58a68f](https://bsd-hardware.info/?probe=086a58a68f) | Mar 24, 2022 |
| Lenovo        | ThinkPad X200 745969G       | [e973d1e806](https://bsd-hardware.info/?probe=e973d1e806) | Mar 18, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [ed0add65a3](https://bsd-hardware.info/?probe=ed0add65a3) | Mar 14, 2022 |
| HP            | EliteBook 2530p             | [e5c8017afb](https://bsd-hardware.info/?probe=e5c8017afb) | Mar 12, 2022 |
| Lenovo        | Yoga 330-11IGM 81A6         | [621ae0501b](https://bsd-hardware.info/?probe=621ae0501b) | Mar 10, 2022 |
| Lenovo        | Flex 2-15 20405             | [3b77055bd4](https://bsd-hardware.info/?probe=3b77055bd4) | Mar 07, 2022 |
| Dell          | Vostro 3550                 | [4bc5573cf5](https://bsd-hardware.info/?probe=4bc5573cf5) | Mar 02, 2022 |
| Lenovo        | ThinkPad X200 745969G       | [a4341268d0](https://bsd-hardware.info/?probe=a4341268d0) | Feb 23, 2022 |
| Dell          | Vostro 3550                 | [11bed21472](https://bsd-hardware.info/?probe=11bed21472) | Feb 21, 2022 |
| Acer          | Aspire A114-33              | [62f4e0a060](https://bsd-hardware.info/?probe=62f4e0a060) | Feb 21, 2022 |
| Acer          | Aspire A514-52              | [60f9683fb1](https://bsd-hardware.info/?probe=60f9683fb1) | Feb 21, 2022 |
| Lenovo        | ThinkPad X250 20CLS59400    | [92333ad60b](https://bsd-hardware.info/?probe=92333ad60b) | Feb 17, 2022 |
| Lenovo        | Flex 2-15 20405             | [1e8904f4fc](https://bsd-hardware.info/?probe=1e8904f4fc) | Feb 15, 2022 |
| Lenovo        | Flex 2-15 20405             | [b77b926f9b](https://bsd-hardware.info/?probe=b77b926f9b) | Feb 13, 2022 |
| Lenovo        | ThinkPad X240 20AMS2QD0C    | [ae597455a4](https://bsd-hardware.info/?probe=ae597455a4) | Feb 13, 2022 |
| Lenovo        | ThinkPad X200 745969G       | [c024d383e7](https://bsd-hardware.info/?probe=c024d383e7) | Feb 13, 2022 |
| Lenovo        | ThinkPad X200 745969G       | [f107f7c1b1](https://bsd-hardware.info/?probe=f107f7c1b1) | Feb 06, 2022 |
| Lenovo        | ThinkPad X200 745969G       | [f8476c0ea7](https://bsd-hardware.info/?probe=f8476c0ea7) | Feb 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [2d65265b52](https://bsd-hardware.info/?probe=2d65265b52) | Jan 29, 2022 |
| Apple         | MacBookPro9,2               | [208819a667](https://bsd-hardware.info/?probe=208819a667) | Jan 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [c36023a724](https://bsd-hardware.info/?probe=c36023a724) | Jan 17, 2022 |
| HP            | EliteBook 2530p             | [42eb986a58](https://bsd-hardware.info/?probe=42eb986a58) | Jan 11, 2022 |
| Lenovo        | V130-15IGM 81HL             | [e0e7b21668](https://bsd-hardware.info/?probe=e0e7b21668) | Jan 09, 2022 |
| Framework     | Laptop                      | [324f0fdebc](https://bsd-hardware.info/?probe=324f0fdebc) | Jan 05, 2022 |
| Framework     | Laptop                      | [ba81f48282](https://bsd-hardware.info/?probe=ba81f48282) | Jan 05, 2022 |
| Dell          | Latitude 3400               | [41bf32aff1](https://bsd-hardware.info/?probe=41bf32aff1) | Jan 02, 2022 |
| Lenovo        | ThinkPad T480 20L5S1S000    | [0925acabe4](https://bsd-hardware.info/?probe=0925acabe4) | Dec 31, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [4bb84a33fa](https://bsd-hardware.info/?probe=4bb84a33fa) | Dec 26, 2021 |
| Casper        | EXCALIBUR G900              | [539cf08655](https://bsd-hardware.info/?probe=539cf08655) | Dec 24, 2021 |
| Samsung       | 530XBB                      | [fe0adb59d8](https://bsd-hardware.info/?probe=fe0adb59d8) | Dec 20, 2021 |
| Samsung       | R720                        | [620195d4aa](https://bsd-hardware.info/?probe=620195d4aa) | Dec 20, 2021 |
| HP            | Compaq 15                   | [1e8b1ce39b](https://bsd-hardware.info/?probe=1e8b1ce39b) | Dec 20, 2021 |
| Intel         | SharkBay Platform           | [383d1e31c9](https://bsd-hardware.info/?probe=383d1e31c9) | Dec 14, 2021 |
| Lenovo        | ThinkPad Edge E430 3254A... | [0215354bfc](https://bsd-hardware.info/?probe=0215354bfc) | Dec 13, 2021 |
| Lenovo        | ThinkPad T420s 41742BU      | [a86326d049](https://bsd-hardware.info/?probe=a86326d049) | Dec 11, 2021 |
| Dell          | G15 5510                    | [2da7a07664](https://bsd-hardware.info/?probe=2da7a07664) | Dec 07, 2021 |
| Lenovo        | ThinkPad X61 7675H7U        | [545cbe065d](https://bsd-hardware.info/?probe=545cbe065d) | Dec 06, 2021 |
| Dell          | G15 5510                    | [8846b3fd69](https://bsd-hardware.info/?probe=8846b3fd69) | Nov 27, 2021 |
| Dell          | Vostro 3500                 | [923a99fade](https://bsd-hardware.info/?probe=923a99fade) | Nov 27, 2021 |
| Lenovo        | ThinkPad X220 429043U       | [339779baad](https://bsd-hardware.info/?probe=339779baad) | Nov 26, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [8b178d13c7](https://bsd-hardware.info/?probe=8b178d13c7) | Nov 22, 2021 |
| Alienware     | m15                         | [20afd3904b](https://bsd-hardware.info/?probe=20afd3904b) | Nov 21, 2021 |
| Dell          | Vostro 3500                 | [63443924f3](https://bsd-hardware.info/?probe=63443924f3) | Nov 19, 2021 |
| Acer          | AO722                       | [98b88ae138](https://bsd-hardware.info/?probe=98b88ae138) | Nov 15, 2021 |
| Lenovo        | ThinkPad T420 4236MBG       | [0391bf9ea4](https://bsd-hardware.info/?probe=0391bf9ea4) | Nov 14, 2021 |
| Dell          | Vostro 3500                 | [34d905d6f3](https://bsd-hardware.info/?probe=34d905d6f3) | Nov 11, 2021 |
| Google        | Grunt                       | [aa07a1dd40](https://bsd-hardware.info/?probe=aa07a1dd40) | Nov 05, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [cdccf02902](https://bsd-hardware.info/?probe=cdccf02902) | Nov 04, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [2471e3f337](https://bsd-hardware.info/?probe=2471e3f337) | Nov 04, 2021 |
| Google        | Grunt                       | [c87e033731](https://bsd-hardware.info/?probe=c87e033731) | Nov 01, 2021 |
| Panasonic     | CF-53AAGHYDM                | [721ef0235c](https://bsd-hardware.info/?probe=721ef0235c) | Oct 30, 2021 |
| Matsushita... | CF-48V4KNDQM                | [9e254ab443](https://bsd-hardware.info/?probe=9e254ab443) | Oct 23, 2021 |
| ASUSTek       | 1000HE                      | [1d5e3e5bc3](https://bsd-hardware.info/?probe=1d5e3e5bc3) | Oct 22, 2021 |
| Lenovo        | ThinkPad T430 2347GZU       | [3337c00433](https://bsd-hardware.info/?probe=3337c00433) | Oct 22, 2021 |
| Matsushita... | CF-51RCVDNLM                | [b20953f2f4](https://bsd-hardware.info/?probe=b20953f2f4) | Oct 18, 2021 |
| Panasonic     | CF-52PFPBSFQ                | [bbdfde368b](https://bsd-hardware.info/?probe=bbdfde368b) | Oct 18, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | [b4ba704356](https://bsd-hardware.info/?probe=b4ba704356) | Oct 17, 2021 |
| Google        | Grunt                       | [e6d4421a4d](https://bsd-hardware.info/?probe=e6d4421a4d) | Oct 16, 2021 |
| Lenovo        | ThinkPad T410 2537N24       | [1a5bae2227](https://bsd-hardware.info/?probe=1a5bae2227) | Oct 15, 2021 |
| Google        | Grunt                       | [ee9b2d7ad3](https://bsd-hardware.info/?probe=ee9b2d7ad3) | Oct 15, 2021 |
| Dell          | Inspiron 5570               | [9eab523504](https://bsd-hardware.info/?probe=9eab523504) | Oct 14, 2021 |
| Google        | Grunt                       | [e76c73d9a3](https://bsd-hardware.info/?probe=e76c73d9a3) | Oct 11, 2021 |
| ASUSTek       | X555LB                      | [e3443d9f27](https://bsd-hardware.info/?probe=e3443d9f27) | Oct 02, 2021 |
| IBM           | ThinkPad H 1846AQG          | [5e5c7247ca](https://bsd-hardware.info/?probe=5e5c7247ca) | Oct 01, 2021 |
| ASUSTek       | UX305FA                     | [decf219ff2](https://bsd-hardware.info/?probe=decf219ff2) | Sep 30, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [d9762d6c2d](https://bsd-hardware.info/?probe=d9762d6c2d) | Sep 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [0d00ce5de9](https://bsd-hardware.info/?probe=0d00ce5de9) | Sep 22, 2021 |
| Dell          | XPS 13 7390 2-in-1          | [577e0ed7fe](https://bsd-hardware.info/?probe=577e0ed7fe) | Sep 13, 2021 |
| HP            | 250 G5 Notebook PC          | [6e50039406](https://bsd-hardware.info/?probe=6e50039406) | Sep 09, 2021 |
| Apple         | MacBookPro6,2               | [4632683b4b](https://bsd-hardware.info/?probe=4632683b4b) | Sep 08, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | [4cc349d29a](https://bsd-hardware.info/?probe=4cc349d29a) | Sep 08, 2021 |
| Lenovo        | ThinkPad X250 20CM0046US    | [1ed50b75f1](https://bsd-hardware.info/?probe=1ed50b75f1) | Sep 08, 2021 |
| Sony          | VGN-P698E                   | [c8274e858d](https://bsd-hardware.info/?probe=c8274e858d) | Aug 30, 2021 |
| Lenovo        | FLEX 3-1120 80LX            | [2f1a1a42b8](https://bsd-hardware.info/?probe=2f1a1a42b8) | Aug 29, 2021 |
| Lenovo        | ThinkPad P73 20QRS00200     | [dfc86a0368](https://bsd-hardware.info/?probe=dfc86a0368) | Aug 29, 2021 |
| Acer          | Aspire ES1-132              | [43c82b1b16](https://bsd-hardware.info/?probe=43c82b1b16) | Aug 22, 2021 |
| IBM           | ThinkPad T42 2374K46        | [d93b6d68fa](https://bsd-hardware.info/?probe=d93b6d68fa) | Aug 18, 2021 |
| Lenovo        | IdeaPad 1 11IGL05 81VT      | [f7725f06df](https://bsd-hardware.info/?probe=f7725f06df) | Aug 18, 2021 |
| Lenovo        | Yoga 6 13ARE05 82FN         | [6f7976c329](https://bsd-hardware.info/?probe=6f7976c329) | Aug 16, 2021 |
| Standard      | TF                          | [c7995f2022](https://bsd-hardware.info/?probe=c7995f2022) | Aug 12, 2021 |
| HP            | Notebook                    | [a3c3297cd2](https://bsd-hardware.info/?probe=a3c3297cd2) | Aug 08, 2021 |
| HP            | Notebook                    | [0c316107a4](https://bsd-hardware.info/?probe=0c316107a4) | Aug 08, 2021 |
| Lenovo        | ThinkPad T430 2349U2B       | [90d85e011f](https://bsd-hardware.info/?probe=90d85e011f) | Jul 31, 2021 |
| Lenovo        | Yoga 330-11IGM 81A6         | [5404f763dd](https://bsd-hardware.info/?probe=5404f763dd) | Jul 26, 2021 |
| Lenovo        | ThinkPad T400 2767WSB       | [36ce1d1e00](https://bsd-hardware.info/?probe=36ce1d1e00) | Jul 24, 2021 |
| MSI           | MS-1613                     | [795e61c1a3](https://bsd-hardware.info/?probe=795e61c1a3) | Jul 21, 2021 |
| Lenovo        | ThinkPad X270 20HNA006ID    | [6fc7c972a5](https://bsd-hardware.info/?probe=6fc7c972a5) | Jul 19, 2021 |
| Lenovo        | ThinkPad T420 4236MBG       | [5b43300a93](https://bsd-hardware.info/?probe=5b43300a93) | Jul 13, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | [740c5182d3](https://bsd-hardware.info/?probe=740c5182d3) | Jul 11, 2021 |
| Lenovo        | ThinkPad X230 232578G       | [a8c497b58b](https://bsd-hardware.info/?probe=a8c497b58b) | Jul 09, 2021 |
| HP            | Pavilion dm1                | [a863347147](https://bsd-hardware.info/?probe=a863347147) | Jul 03, 2021 |
| Lenovo        | Yoga 330-11IGM 81A6         | [72e208aa92](https://bsd-hardware.info/?probe=72e208aa92) | Jul 02, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [443817737d](https://bsd-hardware.info/?probe=443817737d) | Jun 24, 2021 |
| Unknown       | Unknown                     | [f37bf77853](https://bsd-hardware.info/?probe=f37bf77853) | Jun 20, 2021 |
| Lenovo        | ThinkPad X250 20CLS7WY04    | [b60f4a19ee](https://bsd-hardware.info/?probe=b60f4a19ee) | Jun 06, 2021 |
| Lenovo        | ThinkPad T430 23511A6       | [89fb2aa493](https://bsd-hardware.info/?probe=89fb2aa493) | Jun 05, 2021 |
| Lenovo        | ThinkPad T400 6475K43       | [1b3e80e2e9](https://bsd-hardware.info/?probe=1b3e80e2e9) | Jun 03, 2021 |
| Lenovo        | IdeaPad S210 Touch 20257    | [392df069bd](https://bsd-hardware.info/?probe=392df069bd) | Jun 02, 2021 |
| Apple         | PowerBook5,2                | [8cc0aab53c](https://bsd-hardware.info/?probe=8cc0aab53c) | May 31, 2021 |
| HP            | 530 Notebook PC(KP477AA#... | [9c7b85c190](https://bsd-hardware.info/?probe=9c7b85c190) | May 30, 2021 |
| Unknown       | Unknown                     | [b296fb35e2](https://bsd-hardware.info/?probe=b296fb35e2) | May 19, 2021 |
| Unknown       | Unknown                     | [750e01de05](https://bsd-hardware.info/?probe=750e01de05) | May 19, 2021 |
| Panasonic     | CF-53AAGHYDM                | [ef5e9ec095](https://bsd-hardware.info/?probe=ef5e9ec095) | May 18, 2021 |
| Panasonic     | CF-52PFPBSFQ                | [65f5931910](https://bsd-hardware.info/?probe=65f5931910) | May 18, 2021 |
| Lenovo        | ThinkPad T430 2347GZU       | [1e9f399d73](https://bsd-hardware.info/?probe=1e9f399d73) | May 17, 2021 |
| Lenovo        | ThinkPad T410 2537N24       | [109f3afa21](https://bsd-hardware.info/?probe=109f3afa21) | May 17, 2021 |
| ASUSTek       | 1000HE                      | [f92f43bc54](https://bsd-hardware.info/?probe=f92f43bc54) | May 17, 2021 |
| Matsushita... | CF-51RCVDNLM                | [33bc82e701](https://bsd-hardware.info/?probe=33bc82e701) | May 17, 2021 |
| Matsushita... | CF-48V4KNDQM                | [bf76401b74](https://bsd-hardware.info/?probe=bf76401b74) | May 17, 2021 |
| ASUSTek       | UX430UNR                    | [bfe7ec0975](https://bsd-hardware.info/?probe=bfe7ec0975) | May 03, 2021 |
| Acer          | AO531h                      | [614326a3d3](https://bsd-hardware.info/?probe=614326a3d3) | May 03, 2021 |
| Acer          | AO531h                      | [9de7465352](https://bsd-hardware.info/?probe=9de7465352) | May 03, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [6e8891f184](https://bsd-hardware.info/?probe=6e8891f184) | Apr 24, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [7ec73fe36d](https://bsd-hardware.info/?probe=7ec73fe36d) | Apr 23, 2021 |
| Lenovo        | ThinkPad X201 Tablet 298... | [4faceaf6e5](https://bsd-hardware.info/?probe=4faceaf6e5) | Apr 17, 2021 |
| ASUSTek       | UX430UNR                    | [f31eda4c16](https://bsd-hardware.info/?probe=f31eda4c16) | Apr 16, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [403a237513](https://bsd-hardware.info/?probe=403a237513) | Apr 14, 2021 |
| Lenovo        | ThinkPad X250 20CLS1LC13    | [dcf202ea95](https://bsd-hardware.info/?probe=dcf202ea95) | Apr 10, 2021 |
| Lenovo        | ThinkPad X250 20CLS1LC13    | [ee371f3e8f](https://bsd-hardware.info/?probe=ee371f3e8f) | Apr 08, 2021 |
| Lenovo        | ThinkPad Edge 05796AU       | [4a094815c0](https://bsd-hardware.info/?probe=4a094815c0) | Mar 24, 2021 |
| Lenovo        | ThinkPad X220 4291ON5       | [8d81204137](https://bsd-hardware.info/?probe=8d81204137) | Mar 22, 2021 |
| Lenovo        | ThinkPad X220 4291EM4       | [9d393db103](https://bsd-hardware.info/?probe=9d393db103) | Mar 20, 2021 |
| Dell          | Latitude E7270              | [5ba79f9aa5](https://bsd-hardware.info/?probe=5ba79f9aa5) | Mar 19, 2021 |
| Dell          | Inspiron 15-3567            | [b35adf782c](https://bsd-hardware.info/?probe=b35adf782c) | Mar 17, 2021 |
| Lenovo        | ThinkPad X280 20KESA000B    | [e2b586d597](https://bsd-hardware.info/?probe=e2b586d597) | Mar 17, 2021 |
| ASUSTek       | X510UA                      | [440f1ef3ec](https://bsd-hardware.info/?probe=440f1ef3ec) | Mar 14, 2021 |
| Apple         | MacBookAir6,2               | [52584aaa97](https://bsd-hardware.info/?probe=52584aaa97) | Mar 14, 2021 |
| Apple         | MacBookAir6,2               | [fb136a79e7](https://bsd-hardware.info/?probe=fb136a79e7) | Mar 13, 2021 |
| Panasonic     | CF-30KTP48NL                | [119b4875e9](https://bsd-hardware.info/?probe=119b4875e9) | Mar 12, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1HL0... | [954c65dbcf](https://bsd-hardware.info/?probe=954c65dbcf) | Mar 11, 2021 |
| HP            | ProBook 450 G2              | [9f4a3cd83d](https://bsd-hardware.info/?probe=9f4a3cd83d) | Mar 08, 2021 |
| Lenovo        | ThinkPad T400 6475P1G       | [6a0907b5e8](https://bsd-hardware.info/?probe=6a0907b5e8) | Mar 06, 2021 |
| ASUSTek       | X510UA                      | [f22eeba366](https://bsd-hardware.info/?probe=f22eeba366) | Mar 04, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [7d1ff5416d](https://bsd-hardware.info/?probe=7d1ff5416d) | Mar 01, 2021 |
| Acer          | Spin SP111-32N              | [9f44af71aa](https://bsd-hardware.info/?probe=9f44af71aa) | Feb 28, 2021 |
| Dell          | Inspiron 1000               | [70604dcbfa](https://bsd-hardware.info/?probe=70604dcbfa) | Feb 28, 2021 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | [fb890afc86](https://bsd-hardware.info/?probe=fb890afc86) | Feb 28, 2021 |
| Apple         | MacBook5,1                  | [41ea02c8bc](https://bsd-hardware.info/?probe=41ea02c8bc) | Feb 21, 2021 |
| Acer          | AOA150                      | [91e5ec60b9](https://bsd-hardware.info/?probe=91e5ec60b9) | Feb 21, 2021 |
| IBM           | ThinkPad T42 2374K46        | [311f93ab37](https://bsd-hardware.info/?probe=311f93ab37) | Feb 20, 2021 |
| ASUSTek       | X102BA                      | [529baeb345](https://bsd-hardware.info/?probe=529baeb345) | Feb 20, 2021 |
| ASUSTek       | X102BA                      | [65f1904b56](https://bsd-hardware.info/?probe=65f1904b56) | Feb 20, 2021 |
| Dell          | XPS 13 9360                 | [c2dded2160](https://bsd-hardware.info/?probe=c2dded2160) | Feb 19, 2021 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | [4f646f53e9](https://bsd-hardware.info/?probe=4f646f53e9) | Feb 14, 2021 |
| Dell          | Inspiron 1000               | [104175ae13](https://bsd-hardware.info/?probe=104175ae13) | Feb 13, 2021 |
| Sony          | VPCX115KX                   | [fef3d94e6c](https://bsd-hardware.info/?probe=fef3d94e6c) | Feb 12, 2021 |
| Acer          | Extensa 5635Z               | [3b4a7e7fc2](https://bsd-hardware.info/?probe=3b4a7e7fc2) | Feb 10, 2021 |
| Sony          | VPCF12C5E                   | [df8c1de8a5](https://bsd-hardware.info/?probe=df8c1de8a5) | Feb 07, 2021 |
| IBM           | ThinkPad T42 2373K9G        | [a12c3a0b21](https://bsd-hardware.info/?probe=a12c3a0b21) | Feb 01, 2021 |
| Lenovo        | ThinkPad T61 7661AU5        | [23e498234e](https://bsd-hardware.info/?probe=23e498234e) | Jan 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [5f469ceeb9](https://bsd-hardware.info/?probe=5f469ceeb9) | Jan 20, 2021 |
| Dell          | XPS 15 7590                 | [6cd195aa69](https://bsd-hardware.info/?probe=6cd195aa69) | Jan 05, 2021 |
| Dell          | XPS 15 7590                 | [50ca36db01](https://bsd-hardware.info/?probe=50ca36db01) | Jan 05, 2021 |
| ASUSTek       | X101CH                      | [112792b300](https://bsd-hardware.info/?probe=112792b300) | Jan 02, 2021 |
| ASUSTek       | X101CH                      | [8b571cc947](https://bsd-hardware.info/?probe=8b571cc947) | Jan 02, 2021 |
| ASUSTek       | X102BA                      | [893b9111c6](https://bsd-hardware.info/?probe=893b9111c6) | Dec 27, 2020 |
| HP            | 240 G1                      | [3ee90471d0](https://bsd-hardware.info/?probe=3ee90471d0) | Dec 26, 2020 |
| Apple         | PowerBook5,8                | [96f550a537](https://bsd-hardware.info/?probe=96f550a537) | Dec 24, 2020 |
| Lenovo        | ThinkPad T400 6475K43       | [30500a25d3](https://bsd-hardware.info/?probe=30500a25d3) | Dec 18, 2020 |
| HP            | OMEN Laptop 15-en0xxx       | [d019e14245](https://bsd-hardware.info/?probe=d019e14245) | Dec 18, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [7e80ced15e](https://bsd-hardware.info/?probe=7e80ced15e) | Dec 16, 2020 |
| Unknown       | Spring Peak                 | [b61f5c268a](https://bsd-hardware.info/?probe=b61f5c268a) | Dec 15, 2020 |
| Lenovo        | IdeaPad L340-15API 81LW     | [3a78e7dc1a](https://bsd-hardware.info/?probe=3a78e7dc1a) | Dec 11, 2020 |
| Dell          | Latitude 3300               | [108a030875](https://bsd-hardware.info/?probe=108a030875) | Dec 07, 2020 |
| Fujitsu       | LIFEBOOK P1610              | [e8ee627d6e](https://bsd-hardware.info/?probe=e8ee627d6e) | Dec 07, 2020 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | [2544123f79](https://bsd-hardware.info/?probe=2544123f79) | Dec 06, 2020 |
| Lenovo        | ThinkPad T410 2537NB5       | [d6a3aa6f8d](https://bsd-hardware.info/?probe=d6a3aa6f8d) | Dec 06, 2020 |
| Lenovo        | ThinkPad X201 3680FAG       | [1ba69078df](https://bsd-hardware.info/?probe=1ba69078df) | Dec 06, 2020 |
| Lenovo        | ThinkPad W520 42763JU       | [5c50582307](https://bsd-hardware.info/?probe=5c50582307) | Nov 30, 2020 |
| Lenovo        | Yoga 720-13IKB 81C3         | [467a6fc001](https://bsd-hardware.info/?probe=467a6fc001) | Nov 26, 2020 |
| Lenovo        | Unknown                     | [1cf65625a7](https://bsd-hardware.info/?probe=1cf65625a7) | Nov 24, 2020 |
| HP            | Setzer                      | [da7914cdd5](https://bsd-hardware.info/?probe=da7914cdd5) | Nov 22, 2020 |
| Lenovo        | ThinkPad T450 20BVA020AU    | [5d8bce59e8](https://bsd-hardware.info/?probe=5d8bce59e8) | Nov 16, 2020 |
| Lenovo        | ThinkPad T60 87445BU        | [bfd9130d4b](https://bsd-hardware.info/?probe=bfd9130d4b) | Nov 10, 2020 |
| Lenovo        | ThinkPad T490 20N3S8PB00    | [6a0f910601](https://bsd-hardware.info/?probe=6a0f910601) | Nov 10, 2020 |
| Lenovo        | ThinkPad T490 20N3S8PB00    | [6dca4cdd18](https://bsd-hardware.info/?probe=6dca4cdd18) | Nov 10, 2020 |
| Lenovo        | ThinkPad T450s 20BWS2XS0... | [0b04a395a7](https://bsd-hardware.info/?probe=0b04a395a7) | Nov 10, 2020 |
| Lenovo        | ThinkPad T460 20FN003LGE    | [1b7b105e5c](https://bsd-hardware.info/?probe=1b7b105e5c) | Nov 08, 2020 |
| IBM           | ThinkPad T42 2373K9G        | [e041100bb6](https://bsd-hardware.info/?probe=e041100bb6) | Nov 08, 2020 |
| Lenovo        | Yoga 720-13IKB 81C3         | [bdc2de68ce](https://bsd-hardware.info/?probe=bdc2de68ce) | Nov 05, 2020 |
| Lenovo        | Yoga 720-13IKB 81C3         | [8cfb32120b](https://bsd-hardware.info/?probe=8cfb32120b) | Nov 05, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [ebd246c141](https://bsd-hardware.info/?probe=ebd246c141) | Nov 04, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [f2e085e11a](https://bsd-hardware.info/?probe=f2e085e11a) | Nov 04, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [9b6b24708e](https://bsd-hardware.info/?probe=9b6b24708e) | Nov 03, 2020 |
| Dell          | Precision M4800             | [ca6d4c4bb7](https://bsd-hardware.info/?probe=ca6d4c4bb7) | Nov 03, 2020 |
| Dell          | Precision M4800             | [c6a7b68c75](https://bsd-hardware.info/?probe=c6a7b68c75) | Nov 03, 2020 |
| Lenovo        | ThinkPad T500 2087A16       | [334eacfe16](https://bsd-hardware.info/?probe=334eacfe16) | Nov 03, 2020 |
| Lenovo        | ThinkPad W530 2436CTO       | [ded161fe2e](https://bsd-hardware.info/?probe=ded161fe2e) | Oct 31, 2020 |
| Lenovo        | ThinkPad W530 2436CTO       | [e108d4a375](https://bsd-hardware.info/?probe=e108d4a375) | Oct 31, 2020 |
| Acer          | Extensa 2540                | [26670a4ae9](https://bsd-hardware.info/?probe=26670a4ae9) | Oct 30, 2020 |
| Lenovo        | ThinkPad T450 20BV0005US    | [603e66300a](https://bsd-hardware.info/?probe=603e66300a) | Oct 27, 2020 |
| Lenovo        | ThinkPad T500 2087A16       | [cf8228f878](https://bsd-hardware.info/?probe=cf8228f878) | Oct 25, 2020 |
| Lenovo        | Unknown                     | [7bab490506](https://bsd-hardware.info/?probe=7bab490506) | Oct 23, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [03602ed2c0](https://bsd-hardware.info/?probe=03602ed2c0) | Oct 23, 2020 |
| Lenovo        | Unknown                     | [c659708e94](https://bsd-hardware.info/?probe=c659708e94) | Oct 23, 2020 |
| IBM           | ThinkPad X41 2525F8G        | [c58f946d2a](https://bsd-hardware.info/?probe=c58f946d2a) | Oct 22, 2020 |
| Dell          | Precision 3510              | [85a55ab7c3](https://bsd-hardware.info/?probe=85a55ab7c3) | Oct 22, 2020 |
| Lenovo        | ThinkPad E485 20KUCTO1WW    | [f4aa59ba56](https://bsd-hardware.info/?probe=f4aa59ba56) | Oct 22, 2020 |
| Lenovo        | ThinkPad X230 2325AJ9       | [176044b6b8](https://bsd-hardware.info/?probe=176044b6b8) | Oct 21, 2020 |
| Lenovo        | ThinkPad S5-S540 20B3001... | [7e6cb69989](https://bsd-hardware.info/?probe=7e6cb69989) | Oct 21, 2020 |
| Dell          | Latitude C400               | [1dcc5e7972](https://bsd-hardware.info/?probe=1dcc5e7972) | Oct 21, 2020 |
| Dell          | Latitude C400               | [8330d23bd7](https://bsd-hardware.info/?probe=8330d23bd7) | Oct 21, 2020 |
| Lenovo        | ThinkPad X60s 17033JM       | [67e701adb7](https://bsd-hardware.info/?probe=67e701adb7) | Oct 21, 2020 |
| Lenovo        | ThinkPad W540 20BG001KUK    | [1b1327ac93](https://bsd-hardware.info/?probe=1b1327ac93) | Oct 21, 2020 |
| Lenovo        | ThinkPad X230 2325R74       | [82398321f6](https://bsd-hardware.info/?probe=82398321f6) | Oct 21, 2020 |
| Lenovo        | ThinkPad X230 2325R74       | [1cc3cc20e8](https://bsd-hardware.info/?probe=1cc3cc20e8) | Oct 21, 2020 |
| Lenovo        | ThinkPad T430 2347GZU       | [f287de215c](https://bsd-hardware.info/?probe=f287de215c) | Oct 20, 2020 |
| Lenovo        | ThinkPad X230 2325Y36       | [b2e65dd4c5](https://bsd-hardware.info/?probe=b2e65dd4c5) | Oct 20, 2020 |
| Lenovo        | ThinkPad Edge E531 68852... | [e6b45d36e5](https://bsd-hardware.info/?probe=e6b45d36e5) | Oct 20, 2020 |
| Apple         | MacBookAir7,2               | [901c82d31e](https://bsd-hardware.info/?probe=901c82d31e) | Oct 20, 2020 |
| Lenovo        | ThinkPad X250 20CLS4WV08    | [2808d1dd6a](https://bsd-hardware.info/?probe=2808d1dd6a) | Oct 20, 2020 |
| Lenovo        | ThinkPad T410 2537N24       | [f846609c80](https://bsd-hardware.info/?probe=f846609c80) | Oct 20, 2020 |
| Lenovo        | ThinkPad X240 20AL00DKRT    | [623801416c](https://bsd-hardware.info/?probe=623801416c) | Oct 20, 2020 |
| Panasonic     | CF-52PFPBSFQ                | [feb1da0406](https://bsd-hardware.info/?probe=feb1da0406) | Oct 20, 2020 |
| Matsushita... | CF-51RCVDNLM                | [efece2abf7](https://bsd-hardware.info/?probe=efece2abf7) | Oct 20, 2020 |
| ASUSTek       | K53SV                       | [e776458c9e](https://bsd-hardware.info/?probe=e776458c9e) | Oct 19, 2020 |
| Lenovo        | ThinkPad T560 20FJS0CE00    | [be16cb1839](https://bsd-hardware.info/?probe=be16cb1839) | Oct 19, 2020 |
| Lenovo        | ThinkPad X240 20AMS2QD0C    | [fdc7310ca7](https://bsd-hardware.info/?probe=fdc7310ca7) | Oct 19, 2020 |
| ASUSTek       | 1000HE                      | [621df26e0c](https://bsd-hardware.info/?probe=621df26e0c) | Oct 19, 2020 |
| Acer          | Aspire 5251                 | [da9ebcf25e](https://bsd-hardware.info/?probe=da9ebcf25e) | Oct 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [857f9809b7](https://bsd-hardware.info/?probe=857f9809b7) | Oct 19, 2020 |
| Lenovo        | ThinkPad X270 20HNA004CD    | [79160b17c4](https://bsd-hardware.info/?probe=79160b17c4) | Oct 19, 2020 |
| ASUSTek       | X102BA                      | [47e04c9378](https://bsd-hardware.info/?probe=47e04c9378) | Oct 19, 2020 |
| Lenovo        | G50-80 80E5                 | [e06605a92b](https://bsd-hardware.info/?probe=e06605a92b) | Oct 19, 2020 |
| Panasonic     | CF-C1BT02EGE                | [8a80fb614e](https://bsd-hardware.info/?probe=8a80fb614e) | Oct 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [bee732e516](https://bsd-hardware.info/?probe=bee732e516) | Oct 19, 2020 |
| Apple         | PowerBook6,7                | [7ac5f5530a](https://bsd-hardware.info/?probe=7ac5f5530a) | Oct 19, 2020 |
| Alienware     | m15                         | [8f8cf7d956](https://bsd-hardware.info/?probe=8f8cf7d956) | Oct 19, 2020 |
| Lenovo        | ThinkPad T480 20L6S4GR02    | [6c2d8a57ea](https://bsd-hardware.info/?probe=6c2d8a57ea) | Oct 19, 2020 |
| Unknown       | Unknown                     | [fd77b4658f](https://bsd-hardware.info/?probe=fd77b4658f) | Oct 19, 2020 |
| Apple         | MacBookAir6,2               | [9f80fdafb0](https://bsd-hardware.info/?probe=9f80fdafb0) | Oct 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X545... | [017b41dfd7](https://bsd-hardware.info/?probe=017b41dfd7) | Oct 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [4f54c8f399](https://bsd-hardware.info/?probe=4f54c8f399) | Oct 19, 2020 |
| HP            | OmniBook PC                 | [0e0656d228](https://bsd-hardware.info/?probe=0e0656d228) | Oct 19, 2020 |
| HP            | OmniBook PC                 | [60e72f1c10](https://bsd-hardware.info/?probe=60e72f1c10) | Oct 19, 2020 |
| Lenovo        | ThinkPad T460 20FMS1BC01    | [bf6d6d155b](https://bsd-hardware.info/?probe=bf6d6d155b) | Oct 19, 2020 |
| Lenovo        | 3000 N100 0768B9G           | [c44a86f589](https://bsd-hardware.info/?probe=c44a86f589) | Oct 19, 2020 |
| ASUSTek       | G551JW                      | [594e6f28fb](https://bsd-hardware.info/?probe=594e6f28fb) | Oct 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [ee1f866775](https://bsd-hardware.info/?probe=ee1f866775) | Oct 13, 2020 |
| Lenovo        | ThinkPad X395 20NL000HGE    | [fbf90aaf0d](https://bsd-hardware.info/?probe=fbf90aaf0d) | Sep 11, 2020 |
| Lenovo        | ThinkPad X395 20NL000HGE    | [e06815d9dc](https://bsd-hardware.info/?probe=e06815d9dc) | Sep 11, 2020 |
| Lenovo        | ThinkPad X230 2325Y36       | [1f28f1c311](https://bsd-hardware.info/?probe=1f28f1c311) | Aug 30, 2020 |
| Lenovo        | ThinkPad X230 2325Y36       | [11a0bbb73f](https://bsd-hardware.info/?probe=11a0bbb73f) | Aug 30, 2020 |
| Lenovo        | ThinkPad P40 Yoga 20GQ00... | [ac92b69122](https://bsd-hardware.info/?probe=ac92b69122) | Aug 20, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [3032cd9409](https://bsd-hardware.info/?probe=3032cd9409) | Aug 20, 2020 |
| HP            | Laptop 15-dw0xxx            | [547b36ea62](https://bsd-hardware.info/?probe=547b36ea62) | Aug 19, 2020 |
| HCL Infosy... | Calistoga & ICH7M Chipse... | [6adc98922d](https://bsd-hardware.info/?probe=6adc98922d) | Aug 19, 2020 |
| IBM           | ThinkPad T42 2373K9G        | [fa35e7ec26](https://bsd-hardware.info/?probe=fa35e7ec26) | Aug 11, 2020 |
| HP            | ZBook 15 G4                 | [a8953b4964](https://bsd-hardware.info/?probe=a8953b4964) | Aug 03, 2020 |
| HP            | ZBook 15 G4                 | [a97053c5d4](https://bsd-hardware.info/?probe=a97053c5d4) | Aug 03, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [20f3e760eb](https://bsd-hardware.info/?probe=20f3e760eb) | Aug 03, 2020 |
| Lenovo        | ThinkPad W540 20BG001KUK    | [f3e2acbb66](https://bsd-hardware.info/?probe=f3e2acbb66) | Jul 31, 2020 |
| Lenovo        | ThinkPad W540 20BG001KUK    | [7ae8c247e9](https://bsd-hardware.info/?probe=7ae8c247e9) | Jul 31, 2020 |
| Lenovo        | ThinkPad T60 87445BU        | [37a42caa92](https://bsd-hardware.info/?probe=37a42caa92) | Jul 30, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [ac13b0591f](https://bsd-hardware.info/?probe=ac13b0591f) | Jul 27, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [dfef5fdcbf](https://bsd-hardware.info/?probe=dfef5fdcbf) | Jun 10, 2020 |
| Toshiba       | Satellite L775D             | [bb218a14a6](https://bsd-hardware.info/?probe=bb218a14a6) | Jun 03, 2020 |
| Toshiba       | Satellite L775D             | [f0ec90217a](https://bsd-hardware.info/?probe=f0ec90217a) | Jun 03, 2020 |
| Lenovo        | ThinkPad X220 4291C35       | [f22c83f68b](https://bsd-hardware.info/?probe=f22c83f68b) | May 31, 2020 |
| Panasonic     | CF-19ADUAX1M                | [cefc742c62](https://bsd-hardware.info/?probe=cefc742c62) | May 29, 2020 |
| Fujitsu       | LIFEBOOK A357               | [b02640458b](https://bsd-hardware.info/?probe=b02640458b) | May 26, 2020 |
| Lenovo        | ThinkPad X230 2324A57       | [6ea713bf51](https://bsd-hardware.info/?probe=6ea713bf51) | May 25, 2020 |
| Lenovo        | ThinkPad X230 2324A57       | [7b67911c5a](https://bsd-hardware.info/?probe=7b67911c5a) | May 25, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [b4ca8bbc46](https://bsd-hardware.info/?probe=b4ca8bbc46) | May 25, 2020 |
| Lenovo        | ThinkPad T420 4180B39       | [916596bfa8](https://bsd-hardware.info/?probe=916596bfa8) | May 25, 2020 |
| IBM           | ThinkPad X41 2525FAG        | [1e849f86cf](https://bsd-hardware.info/?probe=1e849f86cf) | May 25, 2020 |
| Lenovo        | ThinkPad T440 20B7S1C600    | [a4a62cb85e](https://bsd-hardware.info/?probe=a4a62cb85e) | May 24, 2020 |
| Lenovo        | ThinkPad T440s 20AR003VM... | [3f72b76851](https://bsd-hardware.info/?probe=3f72b76851) | May 23, 2020 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | [fa71e5839a](https://bsd-hardware.info/?probe=fa71e5839a) | May 23, 2020 |
| Lenovo        | ThinkPad X260 20F5S1H800    | [85567202a8](https://bsd-hardware.info/?probe=85567202a8) | May 23, 2020 |
| Lenovo        | ThinkPad T440p 20AN00DEU... | [9ff1537692](https://bsd-hardware.info/?probe=9ff1537692) | May 23, 2020 |
| Lenovo        | G570 20079                  | [8212868b9f](https://bsd-hardware.info/?probe=8212868b9f) | May 19, 2020 |
| Lenovo        | G570 20079                  | [bdd93164cf](https://bsd-hardware.info/?probe=bdd93164cf) | May 17, 2020 |
| ASUSTek       | A3L                         | [0c73038abc](https://bsd-hardware.info/?probe=0c73038abc) | May 06, 2020 |
| ASUSTek       | A3L                         | [ff5b6e3024](https://bsd-hardware.info/?probe=ff5b6e3024) | May 06, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| OpenBSD 6.8 | 91        | 24.73%  |
| OpenBSD 7.2 | 56        | 15.22%  |
| OpenBSD 6.9 | 55        | 14.95%  |
| OpenBSD 7.0 | 50        | 13.59%  |
| OpenBSD 7.3 | 49        | 13.32%  |
| OpenBSD 7.1 | 41        | 11.14%  |
| OpenBSD 6.7 | 23        | 6.25%   |
| OpenBSD 6.6 | 2         | 0.54%   |
| OpenBSD 7.4 | 1         | 0.27%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| OpenBSD | 293       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| amd64  | 259       | 88.4%   |
| i386   | 30        | 10.24%  |
| macppc | 3         | 1.02%   |
| arm64  | 1         | 0.34%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| fvwm         | 182       | 58.33%  |
| helloDesktop | 93        | 29.81%  |
| GNOME        | 11        | 3.53%   |
| Console      | 11        | 3.53%   |
| XFCE         | 7         | 2.24%   |
| MATE         | 3         | 0.96%   |
| Mutter       | 2         | 0.64%   |
| Openbox      | 1         | 0.32%   |
| iwm          | 1         | 0.32%   |
| i3           | 1         | 0.32%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 274       | 92.88%  |
| Console | 21        | 7.12%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 259       | 86.62%  |
| SLiM    | 24        | 8.03%   |
| GDM     | 16        | 5.35%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 223       | 73.84%  |
| en_US   | 35        | 11.59%  |
| C       | 11        | 3.64%   |
| ru_RU   | 7         | 2.32%   |
| fr_FR   | 5         | 1.66%   |
| en_GB   | 5         | 1.66%   |
| zh_TW   | 2         | 0.66%   |
| ja_JP   | 2         | 0.66%   |
| es_ES   | 2         | 0.66%   |
| es_CO   | 2         | 0.66%   |
| en_EN   | 2         | 0.66%   |
| zh_CN   | 1         | 0.33%   |
| pl_PL   | 1         | 0.33%   |
| fr_CA   | 1         | 0.33%   |
| en_CA   | 1         | 0.33%   |
| en_AU   | 1         | 0.33%   |
| de_DE   | 1         | 0.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 173       | 58.25%  |
| BIOS | 124       | 41.75%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Ffs  | 293       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 160       | 53.69%  |
| MBR     | 134       | 44.97%  |
| Unknown | 4         | 1.34%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 138       | 47.1%   |
| Hewlett-Packard                | 23        | 7.85%   |
| Dell                           | 23        | 7.85%   |
| ASUSTek Computer               | 18        | 6.14%   |
| Apple                          | 16        | 5.46%   |
| Acer                           | 12        | 4.1%    |
| Panasonic                      | 7         | 2.39%   |
| IBM                            | 7         | 2.39%   |
| Fujitsu                        | 5         | 1.71%   |
| TUXEDO                         | 4         | 1.37%   |
| Unknown                        | 4         | 1.37%   |
| Toshiba                        | 3         | 1.02%   |
| Sony                           | 3         | 1.02%   |
| Samsung Electronics            | 3         | 1.02%   |
| Framework                      | 3         | 1.02%   |
| Tactus                         | 2         | 0.68%   |
| MSI                            | 2         | 0.68%   |
| Matsushita Electric Industrial | 2         | 0.68%   |
| Intel                          | 2         | 0.68%   |
| Google                         | 2         | 0.68%   |
| Alienware                      | 2         | 0.68%   |
| Star Labs                      | 1         | 0.34%   |
| Standard                       | 1         | 0.34%   |
| OEGStone                       | 1         | 0.34%   |
| Notebook                       | 1         | 0.34%   |
| HUAWEI                         | 1         | 0.34%   |
| HCL Infosystems Limited        | 1         | 0.34%   |
| GPD                            | 1         | 0.34%   |
| Getac                          | 1         | 0.34%   |
| Fujitsu Siemens                | 1         | 0.34%   |
| DEXP                           | 1         | 0.34%   |
| Clevo                          | 1         | 0.34%   |
| Casper                         | 1         | 0.34%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad X200 745969G                | 6         | 2.05%   |
| Unknown                                     | 5         | 1.71%   |
| TUXEDO Pulse 15 Gen1                        | 2         | 0.68%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BSCTO1WW    | 2         | 0.68%   |
| HP ZBook 15 G4                              | 2         | 0.68%   |
| Fujitsu LIFEBOOK E752                       | 2         | 0.68%   |
| Framework Laptop                            | 2         | 0.68%   |
| Dell XPS 13 9360                            | 2         | 0.68%   |
| ASUS X102BA                                 | 2         | 0.68%   |
| Apple MacBookAir7,2                         | 2         | 0.68%   |
| Apple MacBookAir6,2                         | 2         | 0.68%   |
| Apple MacBook5,1                            | 2         | 0.68%   |
| Acer Nitro AN515-55                         | 2         | 0.68%   |
| TUXEDO InfinityBook Pro 14 Gen6             | 1         | 0.34%   |
| TUXEDO Aura 15 Gen1                         | 1         | 0.34%   |
| Toshiba Satellite L775D                     | 1         | 0.34%   |
| Toshiba Satellite BE96-F299                 | 1         | 0.34%   |
| Toshiba NB250                               | 1         | 0.34%   |
| Tactus GeoFlex 110                          | 1         | 0.34%   |
| Tactus GeoBook 140                          | 1         | 0.34%   |
| Star Labs Lite                              | 1         | 0.34%   |
| Standard TF                                 | 1         | 0.34%   |
| Sony VPCX115KX                              | 1         | 0.34%   |
| Sony VPCF12C5E                              | 1         | 0.34%   |
| Sony VGN-P698E                              | 1         | 0.34%   |
| Samsung R720                                | 1         | 0.34%   |
| Samsung 530XBB                              | 1         | 0.34%   |
| Samsung 3570R/370R/470R/450R/510R/4450RV    | 1         | 0.34%   |
| Panasonic CFSX4-1                           | 1         | 0.34%   |
| Panasonic CF-C1BT02EGE                      | 1         | 0.34%   |
| Panasonic CF-54-1                           | 1         | 0.34%   |
| Panasonic CF-53AAGHYDM                      | 1         | 0.34%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 0.34%   |
| Panasonic CF-30KTP48NL                      | 1         | 0.34%   |
| Panasonic CF-19ADUAX1M                      | 1         | 0.34%   |
| OEGStone W54_55SU1,SUW                      | 1         | 0.34%   |
| Notebook NS5x_NS7xPU                        | 1         | 0.34%   |
| MSI MS-1613                                 | 1         | 0.34%   |
| MSI Modern 14 B11MOL                        | 1         | 0.34%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 0.34%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 122       | 41.64%  |
| Dell Latitude       | 7         | 2.39%   |
| IBM ThinkPad        | 6         | 2.05%   |
| Lenovo IdeaPad      | 5         | 1.71%   |
| HP Pavilion         | 5         | 1.71%   |
| Fujitsu LIFEBOOK    | 5         | 1.71%   |
| Dell XPS            | 5         | 1.71%   |
| Unknown             | 5         | 1.71%   |
| Dell Inspiron       | 4         | 1.37%   |
| ASUS VivoBook       | 4         | 1.37%   |
| Acer Aspire         | 4         | 1.37%   |
| Lenovo Yoga         | 3         | 1.02%   |
| HP ProBook          | 3         | 1.02%   |
| Framework Laptop    | 3         | 1.02%   |
| Dell Vostro         | 3         | 1.02%   |
| Apple MacBookAir6   | 3         | 1.02%   |
| TUXEDO Pulse        | 2         | 0.68%   |
| Toshiba Satellite   | 2         | 0.68%   |
| Lenovo Flex         | 2         | 0.68%   |
| HP ZBook            | 2         | 0.68%   |
| HP EliteBook        | 2         | 0.68%   |
| HP 240              | 2         | 0.68%   |
| Dell Precision      | 2         | 0.68%   |
| ASUS X102BA         | 2         | 0.68%   |
| Apple PowerBook5    | 2         | 0.68%   |
| Apple MacBookAir7   | 2         | 0.68%   |
| Apple MacBook5      | 2         | 0.68%   |
| Alienware m15       | 2         | 0.68%   |
| Acer Nitro          | 2         | 0.68%   |
| Acer Extensa        | 2         | 0.68%   |
| TUXEDO InfinityBook | 1         | 0.34%   |
| TUXEDO Aura         | 1         | 0.34%   |
| Toshiba NB250       | 1         | 0.34%   |
| Tactus GeoFlex      | 1         | 0.34%   |
| Tactus GeoBook      | 1         | 0.34%   |
| Star Labs Lite      | 1         | 0.34%   |
| Standard TF         | 1         | 0.34%   |
| Sony VPCX115KX      | 1         | 0.34%   |
| Sony VPCF12C5E      | 1         | 0.34%   |
| Sony VGN-P698E      | 1         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 31        | 10.58%  |
| 2019    | 26        | 8.87%   |
| 2015    | 24        | 8.19%   |
| 2021    | 23        | 7.85%   |
| 2011    | 22        | 7.51%   |
| 2018    | 20        | 6.83%   |
| 2009    | 19        | 6.48%   |
| 2013    | 17        | 5.8%    |
| 2012    | 16        | 5.46%   |
| 2022    | 15        | 5.12%   |
| 2010    | 15        | 5.12%   |
| 2017    | 11        | 3.75%   |
| 2006    | 11        | 3.75%   |
| 2016    | 10        | 3.41%   |
| 2007    | 7         | 2.39%   |
| Unknown | 7         | 2.39%   |
| 2014    | 5         | 1.71%   |
| 2008    | 5         | 1.71%   |
| 2023    | 3         | 1.02%   |
| 2004    | 2         | 0.68%   |
| 2003    | 2         | 0.68%   |
| 2005    | 1         | 0.34%   |
| 2002    | 1         | 0.34%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 293       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 285       | 97.27%  |
| Yes  | 8         | 2.73%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 99        | 33.56%  |
| 4.01-8.0    | 56        | 18.98%  |
| 16.01-24.0  | 48        | 16.27%  |
| 3.01-4.0    | 28        | 9.49%   |
| 32.01-64.0  | 17        | 5.76%   |
| 2.01-3.0    | 16        | 5.42%   |
| 1.01-2.0    | 12        | 4.07%   |
| 0.51-1.0    | 11        | 3.73%   |
| 64.01-256.0 | 3         | 1.02%   |
| 0.01-0.5    | 3         | 1.02%   |
| 24.01-32.0  | 2         | 0.68%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 252       | 85.42%  |
| 0        | 19        | 6.44%   |
| 0.51-1.0 | 16        | 5.42%   |
| 1.01-2.0 | 5         | 1.69%   |
| Unknown  | 3         | 1.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 152       | 50%     |
| 2      | 113       | 37.17%  |
| 3      | 24        | 7.89%   |
| 0      | 8         | 2.63%   |
| 4      | 7         | 2.3%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 292       | 99.32%  |
| Yes       | 2         | 0.68%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 244       | 83.28%  |
| No        | 49        | 16.72%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 283       | 96.59%  |
| No        | 10        | 3.41%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 184       | 61.95%  |
| No        | 113       | 38.05%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 58        | 19.59%  |
| Germany      | 34        | 11.49%  |
| Russia       | 29        | 9.8%    |
| France       | 21        | 7.09%   |
| Canada       | 19        | 6.42%   |
| Poland       | 13        | 4.39%   |
| UK           | 12        | 4.05%   |
| Netherlands  | 8         | 2.7%    |
| Sweden       | 7         | 2.36%   |
| Spain        | 7         | 2.36%   |
| Brazil       | 7         | 2.36%   |
| Australia    | 6         | 2.03%   |
| Norway       | 5         | 1.69%   |
| Ukraine      | 4         | 1.35%   |
| Latvia       | 4         | 1.35%   |
| Italy        | 4         | 1.35%   |
| Colombia     | 4         | 1.35%   |
| Uruguay      | 3         | 1.01%   |
| Switzerland  | 3         | 1.01%   |
| Portugal     | 3         | 1.01%   |
| Philippines  | 3         | 1.01%   |
| Japan        | 3         | 1.01%   |
| India        | 3         | 1.01%   |
| Czechia      | 3         | 1.01%   |
| Turkey       | 2         | 0.68%   |
| Taiwan       | 2         | 0.68%   |
| Slovakia     | 2         | 0.68%   |
| Mexico       | 2         | 0.68%   |
| Malaysia     | 2         | 0.68%   |
| Indonesia    | 2         | 0.68%   |
| Finland      | 2         | 0.68%   |
| Croatia      | 2         | 0.68%   |
| China        | 2         | 0.68%   |
| Vietnam      | 1         | 0.34%   |
| Slovenia     | 1         | 0.34%   |
| Saudi Arabia | 1         | 0.34%   |
| Romania      | 1         | 0.34%   |
| Montserrat   | 1         | 0.34%   |
| Honduras     | 1         | 0.34%   |
| Egypt        | 1         | 0.34%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Montreal           | 16        | 4.86%   |
| Saint-Laurent      | 14        | 4.26%   |
| St Petersburg      | 8         | 2.43%   |
| Paris              | 6         | 1.82%   |
| Vladivostok        | 5         | 1.52%   |
| QuГ©bec          | 5         | 1.52%   |
| Moscow             | 5         | 1.52%   |
| Gdansk             | 5         | 1.52%   |
| Amsterdam          | 5         | 1.52%   |
| Sun Prairie        | 4         | 1.22%   |
| Riga               | 4         | 1.22%   |
| Berlin             | 4         | 1.22%   |
| Zurich             | 3         | 0.91%   |
| Yekaterinburg      | 3         | 0.91%   |
| Portland           | 3         | 0.91%   |
| Oslo               | 3         | 0.91%   |
| Montevideo         | 3         | 0.91%   |
| Lübeck            | 3         | 0.91%   |
| Krakow             | 3         | 0.91%   |
| Frankfurt am Main  | 3         | 0.91%   |
| Fayetteville       | 3         | 0.91%   |
| Brooklyn           | 3         | 0.91%   |
| Blumenau           | 3         | 0.91%   |
| Sydney             | 2         | 0.61%   |
| Sao Paulo          | 2         | 0.61%   |
| Quezon City        | 2         | 0.61%   |
| Puebla City        | 2         | 0.61%   |
| Prague             | 2         | 0.61%   |
| Plymouth           | 2         | 0.61%   |
| Pine Mountain Club | 2         | 0.61%   |
| Papillion          | 2         | 0.61%   |
| Navalcarnero       | 2         | 0.61%   |
| Montería          | 2         | 0.61%   |
| Madrid             | 2         | 0.61%   |
| Mâcon             | 2         | 0.61%   |
| Los Angeles        | 2         | 0.61%   |
| Lafayette          | 2         | 0.61%   |
| Henan              | 2         | 0.61%   |
| Gummersbach        | 2         | 0.61%   |
| Gettysburg         | 2         | 0.61%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| NVMe                | 82        | 110    | 24.33%  |
| Samsung Electronics | 46        | 59     | 13.65%  |
| WDC                 | 33        | 62     | 9.79%   |
| SanDisk             | 19        | 22     | 5.64%   |
| Toshiba             | 18        | 25     | 5.34%   |
| Seagate             | 18        | 24     | 5.34%   |
| Kingston            | 13        | 15     | 3.86%   |
| Crucial             | 12        | 12     | 3.56%   |
| Hitachi             | 10        | 14     | 2.97%   |
| Apple               | 9         | 9      | 2.67%   |
| PNY                 | 7         | 8      | 2.08%   |
| Intel               | 7         | 7      | 2.08%   |
| HGST                | 6         | 8      | 1.78%   |
| Transcend           | 4         | 4      | 1.19%   |
| SK hynix            | 4         | 4      | 1.19%   |
| Apacer              | 4         | 6      | 1.19%   |
| Intenso             | 3         | 3      | 0.89%   |
| Team                | 2         | 2      | 0.59%   |
| SPCC                | 2         | 2      | 0.59%   |
| Plextor             | 2         | 2      | 0.59%   |
| Netac               | 2         | 2      | 0.59%   |
| Innostor            | 2         | 2      | 0.59%   |
| Generic             | 2         | 2      | 0.59%   |
| Fujitsu             | 2         | 2      | 0.59%   |
| A-DATA Technology   | 2         | 6      | 0.59%   |
| Zheino              | 1         | 2      | 0.3%    |
| Verbatim            | 1         | 1      | 0.3%    |
| USB                 | 1         | 1      | 0.3%    |
| Union Memory        | 1         | 1      | 0.3%    |
| UFD 2.0             | 1         | 1      | 0.3%    |
| Star Drive          | 1         | 1      | 0.3%    |
| SMI                 | 1         | 1      | 0.3%    |
| SATA3 60            | 1         | 1      | 0.3%    |
| Patriot             | 1         | 1      | 0.3%    |
| OWC                 | 1         | 1      | 0.3%    |
| OPENBSD             | 1         | 1      | 0.3%    |
| MidasForce          | 1         | 1      | 0.3%    |
| Micron Technology   | 1         | 1      | 0.3%    |
| LITEONIT            | 1         | 1      | 0.3%    |
| LITEON              | 1         | 1      | 0.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| NVMe WDC PC SN730 SDB 512GB         | 9         | 2.57%   |
| Seagate ST1000LM035-1RK172 1TB      | 6         | 1.71%   |
| Samsung HM321HI 320GB               | 6         | 1.71%   |
| NVMe Samsung SSD 980 500GB          | 6         | 1.71%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 5         | 1.43%   |
| Samsung SSD 850 EVO 500GB           | 5         | 1.43%   |
| NVMe SAMSUNG MZVLW256 256GB         | 4         | 1.14%   |
| NVMe SAMSUNG MZVLB256 256GB         | 4         | 1.14%   |
| Kingston SA400S37240G 240GB         | 4         | 1.14%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 3         | 0.86%   |
| Samsung SSD 860 EVO 1TB             | 3         | 0.86%   |
| Samsung SSD 850 EVO 250GB           | 3         | 0.86%   |
| NVMe Samsung SSD 970 250GB          | 3         | 0.86%   |
| Kingston SA400S37480G 480GB         | 3         | 0.86%   |
| Apple SSD SM0128G 121GB             | 3         | 0.86%   |
| Apple SSD SD0128F 121GB             | 3         | 0.86%   |
| WDC WDS240G2G0A-00JH30 240GB        | 2         | 0.57%   |
| WDC WD10JPLX-00MBPT0 1TB            | 2         | 0.57%   |
| Toshiba MK8025GAS 80GB              | 2         | 0.57%   |
| Toshiba MK2556GSY 250GB             | 2         | 0.57%   |
| SK hynix SC311 SATA 256GB           | 2         | 0.57%   |
| Seagate ST9320423AS 320GB           | 2         | 0.57%   |
| Seagate ST500LT012-9WS142 500GB     | 2         | 0.57%   |
| SanDisk X400 M.2 2280 512GB         | 2         | 0.57%   |
| SanDisk SSD U110 16GB               | 2         | 0.57%   |
| SanDisk SSD PLUS 120GB              | 2         | 0.57%   |
| SanDisk Extreme SSD 500GB           | 2         | 0.57%   |
| SanDisk Cruzer Blade 64GB           | 2         | 0.57%   |
| Samsung SSD 850 PRO 256GB           | 2         | 0.57%   |
| Samsung SSD 840 EVO 120GB           | 2         | 0.57%   |
| Samsung MZ7TD256HAFV-000L7 256GB    | 2         | 0.57%   |
| Samsung MZ7PC128HAFU-000L1 128GB    | 2         | 0.57%   |
| PNY CS900 1TB SSD                   | 2         | 0.57%   |
| PNY CS900 120GB SSD                 | 2         | 0.57%   |
| NVMe WDC PC SN720 SDA 512GB         | 2         | 0.57%   |
| NVMe WDC PC SN530 SDB 256GB         | 2         | 0.57%   |
| NVMe SKHynix_HFS512GD 512GB         | 2         | 0.57%   |
| NVMe Samsung SSD 960 500GB          | 2         | 0.57%   |
| NVMe SAMSUNG MZVLB1T0 1TB           | 2         | 0.57%   |
| NVMe PM9A1 Samsu 1TB                | 2         | 0.57%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| NVMe                | 58        | 75     | 37.66%  |
| WDC                 | 26        | 54     | 16.88%  |
| Seagate             | 18        | 24     | 11.69%  |
| Toshiba             | 14        | 21     | 9.09%   |
| Hitachi             | 10        | 14     | 6.49%   |
| Samsung Electronics | 8         | 10     | 5.19%   |
| HGST                | 6         | 8      | 3.9%    |
| Generic             | 2         | 2      | 1.3%    |
| Fujitsu             | 2         | 2      | 1.3%    |
| Verbatim            | 1         | 1      | 0.65%   |
| USB                 | 1         | 1      | 0.65%   |
| UFD 2.0             | 1         | 1      | 0.65%   |
| SMI                 | 1         | 1      | 0.65%   |
| OPENBSD             | 1         | 1      | 0.65%   |
| Lexar               | 1         | 1      | 0.65%   |
| LDLC F6+            | 1         | 1      | 0.65%   |
| JetFlash            | 1         | 1      | 0.65%   |
| General             | 1         | 1      | 0.65%   |
| Apple               | 1         | 1      | 0.65%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 38        | 49     | 21.11%  |
| NVMe                | 21        | 24     | 11.67%  |
| SanDisk             | 19        | 22     | 10.56%  |
| Kingston            | 13        | 15     | 7.22%   |
| Crucial             | 12        | 12     | 6.67%   |
| Apple               | 8         | 8      | 4.44%   |
| WDC                 | 7         | 8      | 3.89%   |
| PNY                 | 7         | 8      | 3.89%   |
| Intel               | 7         | 7      | 3.89%   |
| Transcend           | 4         | 4      | 2.22%   |
| Toshiba             | 4         | 4      | 2.22%   |
| SK hynix            | 4         | 4      | 2.22%   |
| Apacer              | 4         | 6      | 2.22%   |
| Intenso             | 3         | 3      | 1.67%   |
| Team                | 2         | 2      | 1.11%   |
| SPCC                | 2         | 2      | 1.11%   |
| Plextor             | 2         | 2      | 1.11%   |
| Netac               | 2         | 2      | 1.11%   |
| Innostor            | 2         | 2      | 1.11%   |
| A-DATA Technology   | 2         | 6      | 1.11%   |
| Zheino              | 1         | 2      | 0.56%   |
| Union Memory        | 1         | 1      | 0.56%   |
| Star Drive          | 1         | 1      | 0.56%   |
| SATA3 60            | 1         | 1      | 0.56%   |
| Patriot             | 1         | 1      | 0.56%   |
| OWC                 | 1         | 1      | 0.56%   |
| MidasForce          | 1         | 1      | 0.56%   |
| Micron Technology   | 1         | 1      | 0.56%   |
| LITEONIT            | 1         | 1      | 0.56%   |
| LITEON              | 1         | 1      | 0.56%   |
| Leven               | 1         | 1      | 0.56%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.56%   |
| KingSpec            | 1         | 1      | 0.56%   |
| Hewlett-Packard     | 1         | 1      | 0.56%   |
| Gigabyte Technology | 1         | 1      | 0.56%   |
| Dogfish             | 1         | 1      | 0.56%   |
| ASUSTek Computer    | 1         | 2      | 0.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 163       | 209    | 51.75%  |
| HDD  | 143       | 220    | 45.4%   |
| NVMe | 9         | 11     | 2.86%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 276       | 429    | 96.84%  |
| NVMe | 9         | 11     | 3.16%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Notebooks | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 209       | 295    | 68.52%  |
| 0.51-1.0        | 77        | 104    | 25.25%  |
| 1.01-2.0        | 15        | 26     | 4.92%   |
| More than 100.0 | 2         | 2      | 0.66%   |
| 4.01-10.0       | 1         | 1      | 0.33%   |
| 0               | 1         | 1      | 0.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 115       | 37.46%  |
| 251-500    | 89        | 28.99%  |
| 51-100     | 35        | 11.4%   |
| 21-50      | 27        | 8.79%   |
| 1-20       | 17        | 5.54%   |
| 501-1000   | 15        | 4.89%   |
| 1001-2000  | 9         | 2.93%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 211       | 68.95%  |
| 21-50    | 35        | 11.44%  |
| 51-100   | 25        | 8.17%   |
| 101-250  | 23        | 7.52%   |
| 251-500  | 9         | 2.94%   |
| 501-1000 | 3         | 0.98%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST9320423AS 320GB         | 2         | 2      | 7.41%   |
| Intel SSDSC2KF256H6L 256GB        | 2         | 2      | 7.41%   |
| WDC WD2500BEVS-22UST0 250GB       | 1         | 1      | 3.7%    |
| WDC WD1600BEVT-22ZCT0 160GB       | 1         | 1      | 3.7%    |
| Toshiba MQ01ACF032 320GB          | 1         | 3      | 3.7%    |
| Toshiba MK6475GSX 640GB           | 1         | 2      | 3.7%    |
| Toshiba MK6006GAH 64GB            | 1         | 1      | 3.7%    |
| Toshiba MK1629GSGF 160GB          | 1         | 3      | 3.7%    |
| Seagate ST9500420AS 500GB         | 1         | 2      | 3.7%    |
| Seagate ST500LT012-9WS142 500GB   | 1         | 1      | 3.7%    |
| SanDisk SD7UB3Q256G1001 256GB     | 1         | 2      | 3.7%    |
| Samsung Electronics HM500JI 500GB | 1         | 2      | 3.7%    |
| Kingston SMSM151S3128GD 128GB     | 1         | 1      | 3.7%    |
| KingSpec KSD-PA25.6-032MS 32GB    | 1         | 1      | 3.7%    |
| Intel SSDSC2BW480H6 480GB         | 1         | 1      | 3.7%    |
| Intel SSDSA2M080G2GC 80GB         | 1         | 1      | 3.7%    |
| Hitachi HTS722010K9SA00 100GB     | 1         | 1      | 3.7%    |
| Hitachi HTS541060G9SA00 64GB      | 1         | 1      | 3.7%    |
| Hitachi HTC426060G9AT00 64GB      | 1         | 1      | 3.7%    |
| Hitachi DK23AA-12 12GB            | 1         | 1      | 3.7%    |
| HGST HTS545050A7E660 500GB        | 1         | 2      | 3.7%    |
| HGST HTE725032A7E630 320GB        | 1         | 1      | 3.7%    |
| Apple SSD SD0128F 121GB           | 1         | 1      | 3.7%    |
| A-DATA Technology SP550 480GB     | 1         | 5      | 3.7%    |
| A-DATA Technology SP550 240GB     | 1         | 1      | 3.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 4         | 9      | 14.81%  |
| Seagate             | 4         | 5      | 14.81%  |
| Intel               | 4         | 4      | 14.81%  |
| Hitachi             | 4         | 4      | 14.81%  |
| WDC                 | 2         | 2      | 7.41%   |
| HGST                | 2         | 3      | 7.41%   |
| A-DATA Technology   | 2         | 6      | 7.41%   |
| SanDisk             | 1         | 2      | 3.7%    |
| Samsung Electronics | 1         | 2      | 3.7%    |
| Kingston            | 1         | 1      | 3.7%    |
| KingSpec            | 1         | 1      | 3.7%    |
| Apple               | 1         | 1      | 3.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 4         | 9      | 23.53%  |
| Seagate             | 4         | 5      | 23.53%  |
| Hitachi             | 4         | 4      | 23.53%  |
| WDC                 | 2         | 2      | 11.76%  |
| HGST                | 2         | 3      | 11.76%  |
| Samsung Electronics | 1         | 2      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 17        | 25     | 62.96%  |
| SSD  | 10        | 15     | 37.04%  |

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

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 193       | 279    | 62.66%  |
| Detected | 88        | 121    | 28.57%  |
| Malfunc  | 27        | 40     | 8.77%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 202       | 63.32%  |
| Samsung Electronics              | 33        | 10.34%  |
| AMD                              | 22        | 6.9%    |
| SanDisk                          | 21        | 6.58%   |
| SK hynix                         | 6         | 1.88%   |
| Kingston Technology Company      | 6         | 1.88%   |
| Phison Electronics               | 4         | 1.25%   |
| Marvell Technology Group         | 4         | 1.25%   |
| KIOXIA                           | 4         | 1.25%   |
| Nvidia                           | 3         | 0.94%   |
| Lenovo                           | 3         | 0.94%   |
| ADATA Technology                 | 3         | 0.94%   |
| Micron/Crucial Technology        | 2         | 0.63%   |
| Micron Technology                | 2         | 0.63%   |
| Union Memory (Shenzhen)          | 1         | 0.31%   |
| Toshiba                          | 1         | 0.31%   |
| Silicon Integrated Systems [SiS] | 1         | 0.31%   |
| Biwin Storage Technology         | 1         | 0.31%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 24        | 7.1%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 23        | 6.8%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 20        | 5.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 18        | 5.33%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 17        | 5.03%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 16        | 4.73%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 10        | 2.96%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 10        | 2.96%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 10        | 2.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 9         | 2.66%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 9         | 2.66%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 8         | 2.37%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 8         | 2.37%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 7         | 2.07%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 7         | 2.07%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6         | 1.78%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 1.48%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 5         | 1.48%   |
| Intel 82801FBM (ICH6M) SATA Controller                                         | 5         | 1.48%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 4         | 1.18%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 1.18%   |
| Intel 82801CAM IDE U100 Controller                                             | 4         | 1.18%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4         | 1.18%   |
| Samsung NVMe SSD Controller 980                                                | 3         | 0.89%   |
| Phison PS5013 E13 NVMe Controller                                              | 3         | 0.89%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 3         | 0.89%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 3         | 0.89%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 3         | 0.89%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 0.89%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 3         | 0.89%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 0.59%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 0.59%   |
| SanDisk PC SN520 NVMe SSD                                                      | 2         | 0.59%   |
| Nvidia MCP79 AHCI Controller                                                   | 2         | 0.59%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 2         | 0.59%   |
| Lenovo LENSE20256GMSP34MEAT2TA                                                 | 2         | 0.59%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 2         | 0.59%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                     | 2         | 0.59%   |
| Intel SSD 660P Series                                                          | 2         | 0.59%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 201       | 61.66%  |
| NVMe | 80        | 24.54%  |
| IDE  | 44        | 13.5%   |
| RAID | 1         | 0.31%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 251       | 85.67%  |
| AMD     | 37        | 12.63%  |
| PowerPC | 2         | 0.68%   |
| Unknown | 2         | 0.68%   |
| 11th    | 1         | 0.34%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz                            | 13        | 4.35%   |
| Intel Core i5-6300U CPU @ 2.40GHz                            | 11        | 3.68%   |
| Intel Core i5-3320M CPU @ 2.60GHz                            | 11        | 3.68%   |
| Intel Core i5-5300U CPU @ 2.30GHz                            | 8         | 2.68%   |
| Intel Core i5-8250U CPU @ 1.60GHz                            | 6         | 2.01%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz                         | 6         | 2.01%   |
| Intel Core i7-7500U CPU @ 2.70GHz                            | 5         | 1.67%   |
| Intel Core i5-5200U CPU @ 2.20GHz                            | 5         | 1.67%   |
| Intel Core i7-8565U CPU @ 1.80GHz                            | 4         | 1.34%   |
| Intel Core i5-8265U CPU @ 1.60GHz                            | 4         | 1.34%   |
| Intel Core i5 CPU M 520 @ 2.40GHz                            | 4         | 1.34%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz                         | 4         | 1.34%   |
| AMD Ryzen 7 4800H with Radeon Graphics                       | 4         | 1.34%   |
| Intel Core i7-8650U CPU @ 1.90GHz                            | 3         | 1%      |
| Intel Core i7-8550U CPU @ 1.80GHz                            | 3         | 1%      |
| Intel Core i7-6600U CPU @ 2.60GHz                            | 3         | 1%      |
| Intel Core i7-5600U CPU @ 2.60GHz                            | 3         | 1%      |
| Intel Core i7-3520M CPU @ 2.90GHz                            | 3         | 1%      |
| Intel Core i7-10510U CPU @ 1.80GHz                           | 3         | 1%      |
| Intel Core i5-4300U CPU @ 1.90GHz                            | 3         | 1%      |
| Intel Core i5-2540M CPU @ 2.60GHz                            | 3         | 1%      |
| Intel Core i5-10210U CPU @ 1.60GHz                           | 3         | 1%      |
| Intel Core i3-6006U CPU @ 2.00GHz                            | 3         | 1%      |
| Intel Celeron N4020 CPU @ 1.10GHz                            | 3         | 1%      |
| Intel Atom CPU N270 @ 1.60GHz ("GenuineIntel" 686-class)     | 3         | 1%      |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz                      | 3         | 1%      |
| AMD Ryzen 7 4700U with Radeon Graphics                       | 3         | 1%      |
| PowerPC 7447A (Revision 0x105)                               | 2         | 0.67%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz                         | 2         | 0.67%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz                     | 2         | 0.67%   |
| Intel Pentium M processor 1.70GHz ("GenuineIntel" 686-class) | 2         | 0.67%   |
| Intel Pentium M processor                                    | 2         | 0.67%   |
| Intel Core i7-8750H CPU @ 2.20GHz                            | 2         | 0.67%   |
| Intel Core i7-5500U CPU @ 2.40GHz                            | 2         | 0.67%   |
| Intel Core i5-6200U CPU @ 2.30GHz                            | 2         | 0.67%   |
| Intel Core i5-4260U CPU @ 1.40GHz                            | 2         | 0.67%   |
| Intel Core i5-4210M CPU @ 2.60GHz                            | 2         | 0.67%   |
| Intel Core i5-4200U CPU @ 1.60GHz                            | 2         | 0.67%   |
| Intel Core i5-3230M CPU @ 2.60GHz                            | 2         | 0.67%   |
| Intel Core i5 CPU M 560 @ 2.67GHz                            | 2         | 0.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 101       | 34.35%  |
| Intel Core i7           | 46        | 15.65%  |
| Intel Core 2 Duo        | 22        | 7.48%   |
| Other                   | 18        | 6.12%   |
| Intel Core i3           | 16        | 5.44%   |
| Intel Celeron           | 12        | 4.08%   |
| AMD Ryzen 7             | 10        | 3.4%    |
| Intel Atom              | 8         | 2.72%   |
| AMD Ryzen 5             | 7         | 2.38%   |
| Intel Pentium M         | 6         | 2.04%   |
| Intel Pentium Silver    | 4         | 1.36%   |
| Intel Genuine           | 4         | 1.36%   |
| AMD Ryzen 7 PRO         | 4         | 1.36%   |
| Intel Xeon              | 3         | 1.02%   |
| Intel Core Duo          | 3         | 1.02%   |
| AMD A4                  | 3         | 1.02%   |
| Intel Core i9           | 2         | 0.68%   |
| Intel Core 2            | 2         | 0.68%   |
| Intel Celeron M         | 2         | 0.68%   |
| AMD Ryzen 5 PRO         | 2         | 0.68%   |
| AMD Ryzen 3             | 2         | 0.68%   |
| AMD E1                  | 2         | 0.68%   |
| AMD A6                  | 2         | 0.68%   |
| Intel Pentium Dual-Core | 1         | 0.34%   |
| Intel Pentium 4         | 1         | 0.34%   |
| Intel Pentium           | 1         | 0.34%   |
| Intel Mobile Pentium 4  | 1         | 0.34%   |
| Intel Mobile Celeron    | 1         | 0.34%   |
| Intel Core Solo         | 1         | 0.34%   |
| Intel Core m3           | 1         | 0.34%   |
| Intel Core M            | 1         | 0.34%   |
| AMD V120                | 1         | 0.34%   |
| AMD Turion 64 Mobile    | 1         | 0.34%   |
| AMD E                   | 1         | 0.34%   |
| AMD C-50                | 1         | 0.34%   |
| AMD Athlon II Neo       | 1         | 0.34%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 139       | 47.44%  |
| 4       | 60        | 20.48%  |
| Unknown | 41        | 13.99%  |
| 1       | 20        | 6.83%   |
| 8       | 12        | 4.1%    |
| 16      | 10        | 3.41%   |
| 12      | 6         | 2.05%   |
| 6       | 5         | 1.71%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 242       | 81.48%  |
| Unknown | 55        | 18.52%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 179       | 61.09%  |
| Unknown | 59        | 20.14%  |
| 1       | 55        | 18.77%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 44        | 14.92%  |
| Broadwell     | 24        | 8.14%   |
| IvyBridge     | 22        | 7.46%   |
| SandyBridge   | 21        | 7.12%   |
| Penryn        | 21        | 7.12%   |
| Skylake       | 20        | 6.78%   |
| Haswell       | 20        | 6.78%   |
| P6            | 18        | 6.1%    |
| Unknown       | 15        | 5.08%   |
| Zen 2         | 13        | 4.41%   |
| Westmere      | 12        | 4.07%   |
| Goldmont plus | 9         | 3.05%   |
| Bonnell       | 8         | 2.71%   |
| TigerLake     | 6         | 2.03%   |
| Silvermont    | 4         | 1.36%   |
| Jaguar        | 4         | 1.36%   |
| Core          | 4         | 1.36%   |
| CometLake     | 4         | 1.36%   |
| Zen+          | 3         | 1.02%   |
| Zen 3         | 3         | 1.02%   |
| Zen           | 3         | 1.02%   |
| NetBurst      | 3         | 1.02%   |
| Goldmont      | 3         | 1.02%   |
| K10 Llano     | 2         | 0.68%   |
| K10           | 2         | 0.68%   |
| IceLake       | 2         | 0.68%   |
| Bobcat        | 2         | 0.68%   |
| Nehalem       | 1         | 0.34%   |
| K8 Hammer     | 1         | 0.34%   |
| Excavator     | 1         | 0.34%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 234       | 71.34%  |
| AMD                              | 57        | 17.38%  |
| Nvidia                           | 35        | 10.67%  |
| Silicon Integrated Systems [SiS] | 1         | 0.3%    |
| Matrox Electronics Systems       | 1         | 0.3%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 22        | 6.34%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 22        | 6.34%   |
| Intel HD Graphics 5500                                                        | 20        | 5.76%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 19        | 5.48%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 16        | 4.61%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 14        | 4.03%   |
| Intel UHD Graphics 620                                                        | 13        | 3.75%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 13        | 3.75%   |
| AMD Renoir                                                                    | 13        | 3.75%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 9         | 2.59%   |
| Intel Core Processor Integrated Graphics Controller                           | 9         | 2.59%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 8         | 2.31%   |
| Intel HD Graphics 620                                                         | 8         | 2.31%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 7         | 2.02%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 7         | 2.02%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 6         | 1.73%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 6         | 1.73%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 5         | 1.44%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                     | 4         | 1.15%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 4         | 1.15%   |
| Nvidia GT218M [NVS 3100M]                                                     | 3         | 0.86%   |
| Nvidia C79 [GeForce 9400M]                                                    | 3         | 0.86%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 3         | 0.86%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 3         | 0.86%   |
| Intel GeminiLake [UHD Graphics 605]                                           | 3         | 0.86%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 3         | 0.86%   |
| Intel Alder Lake-P Integrated Graphics Controller                             | 3         | 0.86%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 3         | 0.86%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 3         | 0.86%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 3         | 0.86%   |
| AMD Barcelo                                                                   | 3         | 0.86%   |
| Nvidia TU117M                                                                 | 2         | 0.58%   |
| Nvidia GT216M [GeForce GT 330M]                                               | 2         | 0.58%   |
| Nvidia GP108M [GeForce MX150]                                                 | 2         | 0.58%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 2         | 0.58%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                         | 2         | 0.58%   |
| Nvidia GM108M [GeForce 940M]                                                  | 2         | 0.58%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 2         | 0.58%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                           | 2         | 0.58%   |
| Intel HD Graphics P630                                                        | 2         | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 167       | 56.8%   |
| 1 x AMD        | 44        | 14.97%  |
| 2 x Intel      | 36        | 12.24%  |
| Intel + Nvidia | 24        | 8.16%   |
| 1 x Nvidia     | 7         | 2.38%   |
| Intel + AMD    | 7         | 2.38%   |
| AMD + Nvidia   | 3         | 1.02%   |
| Other          | 2         | 0.68%   |
| 2 x Nvidia     | 1         | 0.34%   |
| 2 x AMD        | 1         | 0.34%   |
| 1 x SiS        | 1         | 0.34%   |
| AMD + Matrox   | 1         | 0.34%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Notebooks | Percent |
|---------|-----------|---------|
| Free    | 279       | 95.22%  |
| Unknown | 14        | 4.78%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 293       | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 45        | 21.43%  |
| LG Display              | 40        | 19.05%  |
| BOE                     | 33        | 15.71%  |
| Chimei Innolux          | 21        | 10%     |
| Lenovo                  | 19        | 9.05%   |
| Apple                   | 10        | 4.76%   |
| Samsung Electronics     | 9         | 4.29%   |
| Sharp                   | 3         | 1.43%   |
| PANDA                   | 3         | 1.43%   |
| Dell                    | 3         | 1.43%   |
| Chi Mei Optoelectronics | 3         | 1.43%   |
| InfoVision              | 2         | 0.95%   |
| IBM                     | 2         | 0.95%   |
| Goldstar                | 2         | 0.95%   |
| CSO                     | 2         | 0.95%   |
| BenQ                    | 2         | 0.95%   |
| TRU                     | 1         | 0.48%   |
| Quanta Display          | 1         | 0.48%   |
| Philips                 | 1         | 0.48%   |
| LTM                     | 1         | 0.48%   |
| LG Philips              | 1         | 0.48%   |
| JDI                     | 1         | 0.48%   |
| Iiyama                  | 1         | 0.48%   |
| HannStar                | 1         | 0.48%   |
| Gigabyte Technology     | 1         | 0.48%   |
| Ancor Communications    | 1         | 0.48%   |
| Acer                    | 1         | 0.48%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch                  | 6         | 2.86%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 6         | 2.86%   |
| LG Display LCD Monitor LGD058B 2560x1440 310x170mm 13.9-inch             | 4         | 1.9%    |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch              | 3         | 1.43%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch                  | 3         | 1.43%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch            | 3         | 1.43%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch     | 2         | 0.95%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch             | 2         | 0.95%   |
| LG Display LCD Monitor LGD057E 1920x1080 340x190mm 15.3-inch             | 2         | 0.95%   |
| LG Display LCD Monitor LGD045E 1366x768 310x170mm 13.9-inch              | 2         | 0.95%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch             | 2         | 0.95%   |
| LG Display LCD Monitor LGD0418 2560x1440 310x170mm 13.9-inch             | 2         | 0.95%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 2         | 0.95%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch                 | 2         | 0.95%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch                  | 2         | 0.95%   |
| Lenovo LCD Monitor LEN4033 1440x900 300x190mm 14.0-inch                  | 2         | 0.95%   |
| IBM LCD Monitor IBM2887 1680x1050 330x210mm 15.4-inch                    | 2         | 0.95%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch          | 2         | 0.95%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 310x170mm 13.9-inch          | 2         | 0.95%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 280x160mm 12.7-inch         | 2         | 0.95%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch          | 2         | 0.95%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 2         | 0.95%   |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                    | 2         | 0.95%   |
| BOE LCD Monitor BOE0900 1920x1080 340x190mm 15.3-inch                    | 2         | 0.95%   |
| BOE LCD Monitor BOE07C8 3840x2160 310x170mm 13.9-inch                    | 2         | 0.95%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 310x170mm 13.9-inch           | 2         | 0.95%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 310x170mm 13.9-inch           | 2         | 0.95%   |
| AU Optronics LCD Monitor AUO34ED 1920x1080 340x190mm 15.3-inch           | 2         | 0.95%   |
| AU Optronics LCD Monitor AUO2336 2560x1440 310x170mm 13.9-inch           | 2         | 0.95%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch           | 2         | 0.95%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 340x190mm 15.3-inch            | 2         | 0.95%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch            | 2         | 0.95%   |
| Apple Color LCD APP9CDF 1440x900 290x180mm 13.4-inch                     | 2         | 0.95%   |
| TRU LCD Monitor TRU235C 1366x768 260x140mm 11.6-inch                     | 1         | 0.48%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 340x190mm 15.3-inch                  | 1         | 0.48%   |
| Sharp LCD Monitor SHP14BA 1920x1080 340x190mm 15.3-inch                  | 1         | 0.48%   |
| Sharp LCD Monitor SHP1449 1920x1080 290x170mm 13.2-inch                  | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x170mm 13.9-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 310x170mm 13.9-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch     | 1         | 0.48%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 72        | 34.78%  |
| 1366x768 (WXGA)    | 64        | 30.92%  |
| 1280x800 (WXGA)    | 17        | 8.21%   |
| 2560x1440 (QHD)    | 10        | 4.83%   |
| 1600x900 (HD+)     | 9         | 4.35%   |
| 1440x900 (WXGA+)   | 8         | 3.86%   |
| 3840x2160 (4K)     | 4         | 1.93%   |
| 1680x1050 (WSXGA+) | 4         | 1.93%   |
| 1920x1200 (WUXGA)  | 3         | 1.45%   |
| 2256x1504          | 2         | 0.97%   |
| 720x1280           | 1         | 0.48%   |
| 3840x2400          | 1         | 0.48%   |
| 3456x2160          | 1         | 0.48%   |
| 3440x1440          | 1         | 0.48%   |
| 3200x1800 (QHD+)   | 1         | 0.48%   |
| 2880x1800          | 1         | 0.48%   |
| 2560x1600          | 1         | 0.48%   |
| 1440x960           | 1         | 0.48%   |
| 1360x768           | 1         | 0.48%   |
| 1280x854           | 1         | 0.48%   |
| 1280x768           | 1         | 0.48%   |
| 1280x1024 (SXGA)   | 1         | 0.48%   |
| 1024x768 (XGA)     | 1         | 0.48%   |
| 1024x600           | 1         | 0.48%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 70        | 33.33%  |
| 15     | 59        | 28.1%   |
| 12     | 34        | 16.19%  |
| 11     | 15        | 7.14%   |
| 14     | 11        | 5.24%   |
| 24     | 4         | 1.9%    |
| 23     | 3         | 1.43%   |
| 18     | 2         | 0.95%   |
| 17     | 2         | 0.95%   |
| 10     | 2         | 0.95%   |
| 40     | 1         | 0.48%   |
| 34     | 1         | 0.48%   |
| 28     | 1         | 0.48%   |
| 27     | 1         | 0.48%   |
| 26     | 1         | 0.48%   |
| 19     | 1         | 0.48%   |
| 9      | 1         | 0.48%   |
| 6      | 1         | 0.48%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 112       | 53.33%  |
| 201-300     | 79        | 37.62%  |
| 501-600     | 8         | 3.81%   |
| 401-500     | 3         | 1.43%   |
| 351-400     | 3         | 1.43%   |
| 101-200     | 2         | 0.95%   |
| 801-900     | 1         | 0.48%   |
| 701-800     | 1         | 0.48%   |
| 601-700     | 1         | 0.48%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 159       | 78.71%  |
| 16/10 | 32        | 15.84%  |
| 3/2   | 8         | 3.96%   |
| 5/4   | 1         | 0.5%    |
| 4/3   | 1         | 0.5%    |
| 21/9  | 1         | 0.5%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 72        | 34.29%  |
| 91-100         | 47        | 22.38%  |
| 61-70          | 34        | 16.19%  |
| 51-60          | 15        | 7.14%   |
| 101-110        | 12        | 5.71%   |
| 71-80          | 9         | 4.29%   |
| 201-250        | 6         | 2.86%   |
| 351-500        | 2         | 0.95%   |
| 41-50          | 2         | 0.95%   |
| 1-40           | 2         | 0.95%   |
| 301-350        | 2         | 0.95%   |
| 141-150        | 2         | 0.95%   |
| 121-130        | 2         | 0.95%   |
| 251-300        | 1         | 0.48%   |
| 151-200        | 1         | 0.48%   |
| 501-1000       | 1         | 0.48%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 116       | 55.5%   |
| 101-120       | 42        | 20.1%   |
| 161-240       | 26        | 12.44%  |
| 51-100        | 17        | 8.13%   |
| More than 240 | 8         | 3.83%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 252       | 85.14%  |
| 0     | 29        | 9.8%    |
| 2     | 15        | 5.07%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 221       | 50.8%   |
| Realtek Semiconductor             | 95        | 21.84%  |
| Qualcomm Atheros                  | 38        | 8.74%   |
| Broadcom                          | 24        | 5.52%   |
| Marvell Technology Group          | 8         | 1.84%   |
| Ericsson Business Mobile Networks | 6         | 1.38%   |
| Sierra Wireless                   | 5         | 1.15%   |
| Edimax Technology                 | 5         | 1.15%   |
| TP-Link                           | 4         | 0.92%   |
| Ralink Technology                 | 3         | 0.69%   |
| Qualcomm Atheros Communications   | 3         | 0.69%   |
| Nvidia                            | 3         | 0.69%   |
| Apple                             | 3         | 0.69%   |
| MediaTek                          | 2         | 0.46%   |
| ASUSTek Computer                  | 2         | 0.46%   |
| Xiaomi                            | 1         | 0.23%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.23%   |
| Samsung Electronics               | 1         | 0.23%   |
| Ralink                            | 1         | 0.23%   |
| Micro Star International          | 1         | 0.23%   |
| Hewlett-Packard                   | 1         | 0.23%   |
| Google                            | 1         | 0.23%   |
| Fibocom                           | 1         | 0.23%   |
| Dell                              | 1         | 0.23%   |
| D-Link System                     | 1         | 0.23%   |
| D-Link                            | 1         | 0.23%   |
| AMD                               | 1         | 0.23%   |
| 3Com                              | 1         | 0.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 66        | 11.22%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 27        | 4.59%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 25        | 4.25%   |
| Intel Wireless 8265 / 8275                                                  | 20        | 3.4%    |
| Intel Wireless 7265                                                         | 20        | 3.4%    |
| Intel Wireless 7260                                                         | 17        | 2.89%   |
| Intel Wi-Fi 6 AX200                                                         | 17        | 2.89%   |
| Intel Wireless 8260                                                         | 15        | 2.55%   |
| Intel 82567LM Gigabit Network Connection                                    | 15        | 2.55%   |
| Intel Ethernet Connection I219-LM                                           | 13        | 2.21%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 12        | 2.04%   |
| Intel Ethernet Connection (3) I218-LM                                       | 12        | 2.04%   |
| Intel 82577LM Gigabit Network Connection                                    | 10        | 1.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 9         | 1.53%   |
| Intel Ultimate N WiFi Link 5300                                             | 8         | 1.36%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 8         | 1.36%   |
| Intel Wi-Fi 6 AX201                                                         | 7         | 1.19%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 6         | 1.02%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 6         | 1.02%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 6         | 1.02%   |
| Intel Ethernet Connection (4) I219-V                                        | 6         | 1.02%   |
| Intel Ethernet Connection (4) I219-LM                                       | 6         | 1.02%   |
| Intel Centrino Advanced-N 6200                                              | 6         | 1.02%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                          | 6         | 1.02%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 5         | 0.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                           | 5         | 0.85%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                    | 5         | 0.85%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                       | 4         | 0.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 4         | 0.68%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                  | 4         | 0.68%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                     | 4         | 0.68%   |
| Intel Wireless-AC 9260                                                      | 4         | 0.68%   |
| Intel Wireless 3165                                                         | 4         | 0.68%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                      | 4         | 0.68%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                     | 4         | 0.68%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                   | 4         | 0.68%   |
| Intel Ethernet Connection I218-LM                                           | 4         | 0.68%   |
| Intel Ethernet Connection (6) I219-V                                        | 4         | 0.68%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III | 4         | 0.68%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]              | 4         | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 206       | 65.4%   |
| Qualcomm Atheros                | 33        | 10.48%  |
| Realtek Semiconductor           | 28        | 8.89%   |
| Broadcom                        | 20        | 6.35%   |
| Edimax Technology               | 5         | 1.59%   |
| TP-Link                         | 4         | 1.27%   |
| Sierra Wireless                 | 4         | 1.27%   |
| Ralink Technology               | 3         | 0.95%   |
| Qualcomm Atheros Communications | 3         | 0.95%   |
| MediaTek                        | 2         | 0.63%   |
| ASUSTek Computer                | 2         | 0.63%   |
| Ralink                          | 1         | 0.32%   |
| Micro Star International        | 1         | 0.32%   |
| Dell                            | 1         | 0.32%   |
| D-Link System                   | 1         | 0.32%   |
| D-Link                          | 1         | 0.32%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 25        | 7.81%   |
| Intel Wireless 8265 / 8275                                              | 20        | 6.25%   |
| Intel Wireless 7265                                                     | 20        | 6.25%   |
| Intel Wireless 7260                                                     | 17        | 5.31%   |
| Intel Wi-Fi 6 AX200                                                     | 17        | 5.31%   |
| Intel Wireless 8260                                                     | 15        | 4.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 9         | 2.81%   |
| Intel Ultimate N WiFi Link 5300                                         | 8         | 2.5%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 8         | 2.5%    |
| Intel Wi-Fi 6 AX201                                                     | 7         | 2.19%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.88%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 6         | 1.88%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 1.88%   |
| Intel Centrino Advanced-N 6200                                          | 6         | 1.88%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 6         | 1.88%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 5         | 1.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 1.56%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 1.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 1.25%   |
| Intel Wireless-AC 9260                                                  | 4         | 1.25%   |
| Intel Wireless 3165                                                     | 4         | 1.25%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 4         | 1.25%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 4         | 1.25%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection               | 4         | 1.25%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 4         | 1.25%   |
| Sierra Wireless EM7455                                                  | 3         | 0.94%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 3         | 0.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 0.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 0.94%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 3         | 0.94%   |
| Intel Wireless 3160                                                     | 3         | 0.94%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 0.94%   |
| Intel Centrino Wireless-N 2230                                          | 3         | 0.94%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 3         | 0.94%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 2         | 0.63%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.63%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 2         | 0.63%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 2         | 0.63%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 126       | 51.01%  |
| Realtek Semiconductor            | 84        | 34.01%  |
| Qualcomm Atheros                 | 11        | 4.45%   |
| Marvell Technology Group         | 8         | 3.24%   |
| Broadcom                         | 8         | 3.24%   |
| Nvidia                           | 3         | 1.21%   |
| Apple                            | 2         | 0.81%   |
| Xiaomi                           | 1         | 0.4%    |
| Silicon Integrated Systems [SiS] | 1         | 0.4%    |
| Samsung Electronics              | 1         | 0.4%    |
| Google                           | 1         | 0.4%    |
| 3Com                             | 1         | 0.4%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 66        | 26.72%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 27        | 10.93%  |
| Intel 82567LM Gigabit Network Connection                          | 15        | 6.07%   |
| Intel Ethernet Connection I219-LM                                 | 13        | 5.26%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 4.86%   |
| Intel Ethernet Connection (3) I218-LM                             | 12        | 4.86%   |
| Intel 82577LM Gigabit Network Connection                          | 10        | 4.05%   |
| Intel Ethernet Connection (4) I219-V                              | 6         | 2.43%   |
| Intel Ethernet Connection (4) I219-LM                             | 6         | 2.43%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4         | 1.62%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4         | 1.62%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 4         | 1.62%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 1.62%   |
| Intel Ethernet Connection (6) I219-V                              | 4         | 1.62%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 4         | 1.62%   |
| Nvidia MCP79 Ethernet                                             | 3         | 1.21%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 3         | 1.21%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.21%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.21%   |
| Intel Ethernet Connection (10) I219-V                             | 3         | 1.21%   |
| Intel 82573L Gigabit Ethernet Controller                          | 3         | 1.21%   |
| Intel 82566MM Gigabit Network Connection                          | 3         | 1.21%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.81%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 0.81%   |
| Intel Ethernet Connection I218-V                                  | 2         | 0.81%   |
| Intel Ethernet Connection (3) I218-V                              | 2         | 0.81%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 2         | 0.81%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                   | 2         | 0.81%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.4%    |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1         | 0.4%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.4%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.4%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.4%    |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 0.4%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.4%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.4%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.4%    |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller               | 1         | 0.4%    |
| Intel I210 Gigabit Network Connection                             | 1         | 0.4%    |
| Intel Ethernet Connection I219-V                                  | 1         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 284       | 51.64%  |
| Ethernet | 245       | 44.55%  |
| Modem    | 12        | 2.18%   |
| Unknown  | 9         | 1.64%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 211       | 71.04%  |
| Ethernet | 86        | 28.96%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 230       | 78.5%   |
| 1     | 57        | 19.45%  |
| 3     | 4         | 1.37%   |
| 0     | 2         | 0.68%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 291       | 99.32%  |
| Yes  | 2         | 0.68%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 105       | 56.45%  |
| Broadcom                        | 29        | 15.59%  |
| Apple                           | 13        | 6.99%   |
| IMC Networks                    | 8         | 4.3%    |
| Realtek Semiconductor           | 7         | 3.76%   |
| Alps Electric                   | 7         | 3.76%   |
| Foxconn / Hon Hai               | 6         | 3.23%   |
| Qualcomm Atheros Communications | 3         | 1.61%   |
| Taiyo Yuden                     | 2         | 1.08%   |
| Skylight Digital                | 1         | 0.54%   |
| Ralink                          | 1         | 0.54%   |
| Lite-On Technology              | 1         | 0.54%   |
| Hewlett-Packard                 | 1         | 0.54%   |
| Creative Technology             | 1         | 0.54%   |
| ASUSTek Computer                | 1         | 0.54%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 55        | 29.57%  |
| Intel AX201 Bluetooth                                                               | 14        | 7.53%   |
| Intel AX200 Bluetooth                                                               | 14        | 7.53%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 9         | 4.84%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 9         | 4.84%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 9         | 4.84%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 6         | 3.23%   |
| Apple Broadcom Built-in Bluetooth                                                   | 6         | 3.23%   |
| Apple Bluetooth Host Controller                                                     | 6         | 3.23%   |
| Alps Electric UGTZ4 Bluetooth                                                       | 5         | 2.69%   |
| Realtek Bluetooth Adapter                                                           | 4         | 2.15%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 2.15%   |
| Intel AX210 Bluetooth                                                               | 4         | 2.15%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)                                             | 2         | 1.08%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 1.08%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 1.08%   |
| IMC Networks Realtek Bluetooth Adapter                                              | 2         | 1.08%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                                         | 2         | 1.08%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS                                    | 2         | 1.08%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011]                              | 2         | 1.08%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device                            | 2         | 1.08%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 2         | 1.08%   |
| Skylight Digital Realtek Bluetooth Adapter                                          | 1         | 0.54%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 1         | 0.54%   |
| Realtek Bluetooth 4.2 Adapter                                                       | 1         | 0.54%   |
| Realtek Bluetooth 4.0 Adapter                                                       | 1         | 0.54%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.54%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                                              | 1         | 0.54%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE                                 | 1         | 0.54%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.54%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 0.54%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.54%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.54%   |
| Foxconn / Hon Hai RZ616 Bluetooth Adapter                                           | 1         | 0.54%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 1         | 0.54%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.54%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 1         | 0.54%   |
| Creative Creative Bluetooth Audio W2                                                | 1         | 0.54%   |
| Broadcom BCM43142A0 Bluetooth Module                                                | 1         | 0.54%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.54%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 245       | 80.33%  |
| AMD                              | 39        | 12.79%  |
| Nvidia                           | 16        | 5.25%   |
| Silicon Integrated Systems [SiS] | 1         | 0.33%   |
| Logitech                         | 1         | 0.33%   |
| Generalplus Technology           | 1         | 0.33%   |
| ESS Technology                   | 1         | 0.33%   |
| C-Media Electronics              | 1         | 0.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 41        | 10.79%  |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 24        | 6.32%   |
| Intel Broadwell-U Audio Controller                                                                | 24        | 6.32%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 24        | 6.32%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 24        | 6.32%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 20        | 5.26%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 17        | 4.47%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 16        | 4.21%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 16        | 4.21%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 13        | 3.42%   |
| Intel 8 Series HD Audio Controller                                                                | 13        | 3.42%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 13        | 3.42%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 9         | 2.37%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 8         | 2.11%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 7         | 1.84%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 7         | 1.84%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 1.58%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 1.58%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 1.58%   |
| AMD FCH Azalia Controller                                                                         | 6         | 1.58%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 1.32%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 1.05%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 4         | 1.05%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 1.05%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 1.05%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 0.79%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.79%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 0.79%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 0.79%   |
| Intel 82801CA/CAM AC'97 Audio Controller                                                          | 3         | 0.79%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 0.53%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.53%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 0.53%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 2         | 0.53%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 0.53%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.53%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.53%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.53%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 0.53%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 2         | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 16        | 28.57%  |
| Unknown             | 12        | 21.43%  |
| SK hynix            | 8         | 14.29%  |
| Micron Technology   | 5         | 8.93%   |
| Crucial             | 4         | 7.14%   |
| Kingston            | 3         | 5.36%   |
| Elpida              | 3         | 5.36%   |
| Unknown             | 3         | 5.36%   |
| Ramaxel Technology  | 1         | 1.79%   |
| A-DATA Technology   | 1         | 1.79%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s   | 4         | 6.45%   |
| Unknown                                                 | 3         | 4.84%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s             | 2         | 3.23%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 2         | 3.23%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s   | 2         | 3.23%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM 1067MT/s        | 2         | 3.23%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s   | 2         | 3.23%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s   | 2         | 3.23%   |
| Crucial RAM CT8G3S1339M 8GB SODIMM DDR3 1333MT/s        | 2         | 3.23%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s | 2         | 3.23%   |
| Unknown RAM Module 512MB SODIMM SDRAM                   | 1         | 1.61%   |
| Unknown RAM Module 512MB SODIMM DDR                     | 1         | 1.61%   |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s             | 1         | 1.61%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s              | 1         | 1.61%   |
| Unknown RAM Module 256MB SODIMM DRAM                    | 1         | 1.61%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s          | 1         | 1.61%   |
| Unknown RAM Module 2048MB SODIMM DDR2                   | 1         | 1.61%   |
| Unknown RAM Module 1GB SODIMM DDR2                      | 1         | 1.61%   |
| Unknown RAM Module 1GB SODIMM DDR                       | 1         | 1.61%   |
| Unknown RAM Module 128MB SODIMM DRAM                    | 1         | 1.61%   |
| Unknown RAM Module 1024MB SODIMM DDR                    | 1         | 1.61%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 1         | 1.61%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 1         | 1.61%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s  | 1         | 1.61%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s | 1         | 1.61%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB SODIMM LPDDR3 1867MT/s  | 1         | 1.61%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB Chip LPDDR3 1867MT/s    | 1         | 1.61%   |
| SK hynix RAM 484D543332355336 2GB SODIMM DDR3 1333MT/s  | 1         | 1.61%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM 1067MT/s        | 1         | 1.61%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s   | 1         | 1.61%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s   | 1         | 1.61%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s   | 1         | 1.61%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s  | 1         | 1.61%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s   | 1         | 1.61%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s   | 1         | 1.61%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s | 1         | 1.61%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s   | 1         | 1.61%   |
| Micron RAM 8JSF12864HZ-1G1F1 1GB SODIMM DDR3 800MT/s    | 1         | 1.61%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s   | 1         | 1.61%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s   | 1         | 1.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 28        | 57.14%  |
| DDR4   | 8         | 16.33%  |
| DDR2   | 6         | 12.24%  |
| SDRAM  | 2         | 4.08%   |
| DRAM   | 2         | 4.08%   |
| DDR    | 2         | 4.08%   |
| LPDDR3 | 1         | 2.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 49        | 98%     |
| Chip   | 1         | 2%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 18        | 31.03%  |
| 8192  | 13        | 22.41%  |
| 2048  | 13        | 22.41%  |
| 1024  | 6         | 10.34%  |
| 16384 | 4         | 6.9%    |
| 512   | 2         | 3.45%   |
| 256   | 1         | 1.72%   |
| 128   | 1         | 1.72%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 15        | 27.27%  |
| Unknown | 8         | 14.55%  |
| 1334    | 7         | 12.73%  |
| 1333    | 7         | 12.73%  |
| 3200    | 4         | 7.27%   |
| 1067    | 4         | 7.27%   |
| 2667    | 3         | 5.45%   |
| 2133    | 1         | 1.82%   |
| 1867    | 1         | 1.82%   |
| 800     | 1         | 1.82%   |
| 667     | 1         | 1.82%   |
| 533     | 1         | 1.82%   |
| 400     | 1         | 1.82%   |
| 266     | 1         | 1.82%   |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 63        | 34.05%  |
| Bison Electronics                      | 25        | 13.51%  |
| IMC Networks                           | 19        | 10.27%  |
| Realtek Semiconductor                  | 13        | 7.03%   |
| Lite-On Technology                     | 12        | 6.49%   |
| Microdia                               | 9         | 4.86%   |
| Lenovo                                 | 6         | 3.24%   |
| Sunplus Innovation Technology          | 4         | 2.16%   |
| Quanta                                 | 4         | 2.16%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 2.16%   |
| Syntek                                 | 3         | 1.62%   |
| Suyin                                  | 3         | 1.62%   |
| Ricoh                                  | 3         | 1.62%   |
| Alcor Micro                            | 3         | 1.62%   |
| Tripath Technology                     | 2         | 1.08%   |
| Silicon Motion                         | 2         | 1.08%   |
| Luxvisions Innotech Limited            | 2         | 1.08%   |
| Apple                                  | 2         | 1.08%   |
| SunplusIT                              | 1         | 0.54%   |
| Logitech                               | 1         | 0.54%   |
| Jiangxi Shinetech Optical              | 1         | 0.54%   |
| Genesys Logic                          | 1         | 0.54%   |
| Denron                                 | 1         | 0.54%   |
| ALi                                    | 1         | 0.54%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 25        | 13.3%   |
| Lite-On Integrated Camera                                                  | 11        | 5.85%   |
| Bison Integrated Camera                                                    | 11        | 5.85%   |
| IMC Networks Integrated Camera                                             | 9         | 4.79%   |
| Chicony Integrated Camera [ThinkPad]                                       | 6         | 3.19%   |
| Chicony Lenovo Integrated Camera (0.3MP)                                   | 5         | 2.66%   |
| Realtek Integrated_Webcam_HD                                               | 4         | 2.13%   |
| Microdia Integrated_Webcam_HD                                              | 4         | 2.13%   |
| Bison SunplusIT Integrated Camera                                          | 4         | 2.13%   |
| Lenovo Integrated Webcam [R5U877]                                          | 3         | 1.6%    |
| Lenovo Integrated Webcam                                                   | 3         | 1.6%    |
| Chicony Integrated IR Camera                                               | 3         | 1.6%    |
| Chicony Integrated Camera (1280x720@30)                                    | 3         | 1.6%    |
| Tripath USB Camera                                                         | 2         | 1.06%   |
| Syntek Lenovo EasyCamera                                                   | 2         | 1.06%   |
| Realtek USB 2.0 Webcam                                                     | 2         | 1.06%   |
| IMC Networks Realtek DMFT RGB                                              | 2         | 1.06%   |
| Chicony VGA Webcam                                                         | 2         | 1.06%   |
| Chicony ThinkPad T490 Webcam                                               | 2         | 1.06%   |
| Chicony thinkpad t430s camera                                              | 2         | 1.06%   |
| Chicony Sonix ST50220 USB Video Camera                                     | 2         | 1.06%   |
| Chicony FJ Camera                                                          | 2         | 1.06%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 2         | 1.06%   |
| Bison Lenovo Integrated Webcam                                             | 2         | 1.06%   |
| Bison Lenovo EasyCamera                                                    | 2         | 1.06%   |
| Bison EasyCamera                                                           | 2         | 1.06%   |
| Syntek EasyCamera                                                          | 1         | 0.53%   |
| Suyin Asus Integrated Webcam                                               | 1         | 0.53%   |
| Suyin Acer/Lenovo Webcam [CN0316]                                          | 1         | 0.53%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)                | 1         | 0.53%   |
| SunplusIT USB camera                                                       | 1         | 0.53%   |
| Sunplus Integrated_Webcam_FHD                                              | 1         | 0.53%   |
| Sunplus Integrated HD Webcam                                               | 1         | 0.53%   |
| Sunplus HP TrueVision HD Camera                                            | 1         | 0.53%   |
| Sunplus Dell E5570 integrated webcam                                       | 1         | 0.53%   |
| Silicon Motion Realtek USB 2.0 PC Camera                                   | 1         | 0.53%   |
| Silicon Motion Realtek DMFT RGB                                            | 1         | 0.53%   |
| Ricoh Sony Visual Communication Camera                                     | 1         | 0.53%   |
| Ricoh Laptop_Integrated_Webcam_FHD                                         | 1         | 0.53%   |
| Ricoh Integrated Webcam                                                    | 1         | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 22        | 30.56%  |
| Synaptics                  | 14        | 19.44%  |
| Upek                       | 11        | 15.28%  |
| AuthenTec                  | 10        | 13.89%  |
| STMicroelectronics         | 7         | 9.72%   |
| Shenzhen Goodix Technology | 4         | 5.56%   |
| Elan Microelectronics      | 2         | 2.78%   |
| Samsung Electronics        | 1         | 1.39%   |
| LighTuning Technology      | 1         | 1.39%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor             | 14        | 19.44%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 11        | 15.28%  |
| STMicroelectronics Fingerprint Reader                    | 7         | 9.72%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 5         | 6.94%   |
| AuthenTec AES2810                                        | 5         | 6.94%   |
| AuthenTec AES2501 Fingerprint Sensor                     | 4         | 5.56%   |
| Validity Sensors Synaptics WBDI                          | 3         | 4.17%   |
| Synaptics WBDI                                           | 3         | 4.17%   |
| Shenzhen Goodix Fingerprint Reader                       | 3         | 4.17%   |
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
| LighTuning ES603 Swipe Fingerprint Sensor                | 1         | 1.39%   |
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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 155       | 51.84%  |
| 2     | 74        | 24.75%  |
| 0     | 32        | 10.7%   |
| 3     | 20        | 6.69%   |
| 4     | 9         | 3.01%   |
| 5     | 5         | 1.67%   |
| 6     | 2         | 0.67%   |
| 8     | 1         | 0.33%   |
| 7     | 1         | 0.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 203       | 49.15%  |
| Graphics card            | 73        | 17.68%  |
| Net/wireless             | 50        | 12.11%  |
| Firewire controller      | 30        | 7.26%   |
| Sound                    | 14        | 3.39%   |
| Network                  | 11        | 2.66%   |
| Storage/ata              | 9         | 2.18%   |
| Modem                    | 9         | 2.18%   |
| Net/ethernet             | 4         | 0.97%   |
| Storage                  | 3         | 0.73%   |
| Card reader              | 3         | 0.73%   |
| Storage/ide              | 2         | 0.48%   |
| Storage/nvme             | 1         | 0.24%   |
| Bluetooth                | 1         | 0.24%   |

