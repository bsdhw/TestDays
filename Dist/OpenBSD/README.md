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

Total: 906

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| HP            | ProBook 455 G7              | Notebook    | [11764c4c5e](https://bsd-hardware.info/?probe=11764c4c5e) | Dec 20, 2023 |
| Apple         | PowerBook3,5                | Notebook    | [53313e58d8](https://bsd-hardware.info/?probe=53313e58d8) | Dec 20, 2023 |
| Toshiba       | Portable PC                 | Notebook    | [bee6ea8f18](https://bsd-hardware.info/?probe=bee6ea8f18) | Dec 15, 2023 |
| Lenovo        | ThinkPad P70 20ESS1L600     | Notebook    | [2e3870f2ee](https://bsd-hardware.info/?probe=2e3870f2ee) | Dec 07, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [3784a39a41](https://bsd-hardware.info/?probe=3784a39a41) | Dec 06, 2023 |
| HP            | Pavilion g7                 | Notebook    | [4c1bc19902](https://bsd-hardware.info/?probe=4c1bc19902) | Dec 03, 2023 |
| Star Labs     | LabTop                      | Notebook    | [e8dcf01d78](https://bsd-hardware.info/?probe=e8dcf01d78) | Dec 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [2a34bc9613](https://bsd-hardware.info/?probe=2a34bc9613) | Nov 28, 2023 |
| AZW           | SER                         | Desktop     | [48a259ae28](https://bsd-hardware.info/?probe=48a259ae28) | Nov 28, 2023 |
| Apple         | MacBookAir4,1               | Notebook    | [4661b8933c](https://bsd-hardware.info/?probe=4661b8933c) | Nov 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [9762745c92](https://bsd-hardware.info/?probe=9762745c92) | Nov 23, 2023 |
| Lenovo        | ThinkCentre M90n-1 11AHS... | Desktop     | [eca5b59407](https://bsd-hardware.info/?probe=eca5b59407) | Nov 23, 2023 |
| Lenovo        | ThinkCentre M720s 10SUSB... | Desktop     | [a44a9f3526](https://bsd-hardware.info/?probe=a44a9f3526) | Nov 23, 2023 |
| Lenovo        | ThinkPad X260 20F5S2GM00    | Notebook    | [b5be73085a](https://bsd-hardware.info/?probe=b5be73085a) | Nov 23, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [0d706d98b4](https://bsd-hardware.info/?probe=0d706d98b4) | Nov 23, 2023 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [1da7551908](https://bsd-hardware.info/?probe=1da7551908) | Nov 23, 2023 |
| Dell          | Latitude 7490               | Notebook    | [e860d3dbcf](https://bsd-hardware.info/?probe=e860d3dbcf) | Nov 23, 2023 |
| HP            | Compaq CQ45                 | Desktop     | [4f3c176253](https://bsd-hardware.info/?probe=4f3c176253) | Nov 14, 2023 |
| Unknown       | Raspberry Pi                | Soc         | [de988c2e66](https://bsd-hardware.info/?probe=de988c2e66) | Nov 14, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [f0f418db58](https://bsd-hardware.info/?probe=f0f418db58) | Nov 11, 2023 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [ee95b41634](https://bsd-hardware.info/?probe=ee95b41634) | Nov 10, 2023 |
| Panasonic     | CF-54-1                     | Notebook    | [c530bdbd88](https://bsd-hardware.info/?probe=c530bdbd88) | Nov 10, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [700d52c2dd](https://bsd-hardware.info/?probe=700d52c2dd) | Nov 07, 2023 |
| Unknown       | Raspberry Pi                | Soc         | [e2a506d1b7](https://bsd-hardware.info/?probe=e2a506d1b7) | Nov 07, 2023 |
| Apple         | MacPro4,1                   | Desktop     | [5960492992](https://bsd-hardware.info/?probe=5960492992) | Nov 07, 2023 |
| Intel         | DCP847SKE                   | Desktop     | [3b5b83d95f](https://bsd-hardware.info/?probe=3b5b83d95f) | Oct 30, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [32b7f19d78](https://bsd-hardware.info/?probe=32b7f19d78) | Oct 30, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [522298f90a](https://bsd-hardware.info/?probe=522298f90a) | Oct 29, 2023 |
| ASUSTek       | MINIPC PN53-G               | Desktop     | [57d8823b4b](https://bsd-hardware.info/?probe=57d8823b4b) | Oct 28, 2023 |
| IBM           | ThinkPad R51 2889W11        | Notebook    | [26d2e55032](https://bsd-hardware.info/?probe=26d2e55032) | Oct 28, 2023 |
| Dell          | PowerEdge T110 II           | Desktop     | [f93395bc11](https://bsd-hardware.info/?probe=f93395bc11) | Oct 28, 2023 |
| Sun           | SUNW,SPARC-Enterprise-T5... | Desktop     | [50457ff825](https://bsd-hardware.info/?probe=50457ff825) | Oct 27, 2023 |
| Panasonic     | CF-C2CEAZXCM                | Notebook    | [a871fb0596](https://bsd-hardware.info/?probe=a871fb0596) | Oct 27, 2023 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [310fcb9763](https://bsd-hardware.info/?probe=310fcb9763) | Oct 26, 2023 |
| MECHREVO      | Unknown                     | Desktop     | [2dac22205c](https://bsd-hardware.info/?probe=2dac22205c) | Oct 23, 2023 |
| Panasonic     | CF-52PFPBSFQ                | Notebook    | [4a97ab307a](https://bsd-hardware.info/?probe=4a97ab307a) | Oct 22, 2023 |
| Lenovo        | ThinkPad T430 2347GZU       | Notebook    | [88ae89f787](https://bsd-hardware.info/?probe=88ae89f787) | Oct 22, 2023 |
| Panasonic     | CF-53AAGHYDM                | Notebook    | [6f29731875](https://bsd-hardware.info/?probe=6f29731875) | Oct 22, 2023 |
| ASUSTek       | 1000HE                      | Notebook    | [249959fd2c](https://bsd-hardware.info/?probe=249959fd2c) | Oct 21, 2023 |
| Matsushita... | CF-51RCVDNLM                | Notebook    | [ec5aff8b6b](https://bsd-hardware.info/?probe=ec5aff8b6b) | Oct 21, 2023 |
| Matsushita... | CF-48V4KNDQM                | Notebook    | [625f272fcd](https://bsd-hardware.info/?probe=625f272fcd) | Oct 21, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | Notebook    | [e4b35a3ff6](https://bsd-hardware.info/?probe=e4b35a3ff6) | Oct 21, 2023 |
| Lenovo        | ThinkPad T410 2537N24       | Notebook    | [fd75aab1c6](https://bsd-hardware.info/?probe=fd75aab1c6) | Oct 20, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [d3ad63aa13](https://bsd-hardware.info/?probe=d3ad63aa13) | Oct 19, 2023 |
| IBM           | ThinkPad R51 2889W11        | Notebook    | [45836fafc3](https://bsd-hardware.info/?probe=45836fafc3) | Oct 12, 2023 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [d5676f7895](https://bsd-hardware.info/?probe=d5676f7895) | Oct 10, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [b192196423](https://bsd-hardware.info/?probe=b192196423) | Oct 08, 2023 |
| Dell          | Vostro 3700                 | Notebook    | [8262e3923f](https://bsd-hardware.info/?probe=8262e3923f) | Oct 08, 2023 |
| PC Engines    | APU                         | Desktop     | [ca9bc2faa7](https://bsd-hardware.info/?probe=ca9bc2faa7) | Sep 29, 2023 |
| PC Engines    | APU                         | Desktop     | [067872c1f5](https://bsd-hardware.info/?probe=067872c1f5) | Sep 29, 2023 |
| ASUSTek       | PRIME A520M-A II            | Desktop     | [29bcb3ca3e](https://bsd-hardware.info/?probe=29bcb3ca3e) | Sep 29, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [86abd76c4e](https://bsd-hardware.info/?probe=86abd76c4e) | Sep 27, 2023 |
| GPD           | G1619-04                    | Notebook    | [30ad9b72b5](https://bsd-hardware.info/?probe=30ad9b72b5) | Sep 23, 2023 |
| Dell          | Latitude E7470              | Notebook    | [11cf3b211c](https://bsd-hardware.info/?probe=11cf3b211c) | Sep 22, 2023 |
| Apple         | MacPro4,1                   | Desktop     | [c368087050](https://bsd-hardware.info/?probe=c368087050) | Sep 20, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [398d7a6f26](https://bsd-hardware.info/?probe=398d7a6f26) | Sep 20, 2023 |
| Dell          | XPS 9320                    | Notebook    | [d80b3d5a54](https://bsd-hardware.info/?probe=d80b3d5a54) | Sep 14, 2023 |
| Dell          | Latitude E6420              | Notebook    | [b90b748742](https://bsd-hardware.info/?probe=b90b748742) | Sep 14, 2023 |
| Huanan        | X99-F8D PLUS V1.3           | Desktop     | [53d31a28bf](https://bsd-hardware.info/?probe=53d31a28bf) | Sep 14, 2023 |
| Lenovo        | ThinkPad X140e 20BMS03E0... | Notebook    | [54b04ea958](https://bsd-hardware.info/?probe=54b04ea958) | Sep 12, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS (W... | Desktop     | [89a601d720](https://bsd-hardware.info/?probe=89a601d720) | Sep 12, 2023 |
| Supermicro    | X8DTH-i/6/iF/6F             | Desktop     | [df114e1b94](https://bsd-hardware.info/?probe=df114e1b94) | Sep 09, 2023 |
| Apple         | PowerMac3,6                 | Desktop     | [36daf7ce75](https://bsd-hardware.info/?probe=36daf7ce75) | Sep 09, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [8f54654916](https://bsd-hardware.info/?probe=8f54654916) | Sep 01, 2023 |
| VIA Techno... | VT8623-8235                 | Desktop     | [3274cd095e](https://bsd-hardware.info/?probe=3274cd095e) | Aug 31, 2023 |
| MSI           | MS-7125                     | Desktop     | [3dfb767d80](https://bsd-hardware.info/?probe=3dfb767d80) | Aug 30, 2023 |
| Dell          | Latitude 7280               | Notebook    | [c858f191cf](https://bsd-hardware.info/?probe=c858f191cf) | Aug 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [c8e95f3772](https://bsd-hardware.info/?probe=c8e95f3772) | Aug 26, 2023 |
| Getac         | V110G2                      | Notebook    | [884803a6bd](https://bsd-hardware.info/?probe=884803a6bd) | Aug 25, 2023 |
| ASUSTek       | P5M2-R                      | Desktop     | [73135bf26d](https://bsd-hardware.info/?probe=73135bf26d) | Aug 25, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [27cf2b3e46](https://bsd-hardware.info/?probe=27cf2b3e46) | Aug 19, 2023 |
| MSI           | MS-7721                     | Desktop     | [a577019634](https://bsd-hardware.info/?probe=a577019634) | Aug 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [9beb5f6126](https://bsd-hardware.info/?probe=9beb5f6126) | Aug 17, 2023 |
| Fujitsu Si... | LIFEBOOK P1610              | Notebook    | [bb055a94f0](https://bsd-hardware.info/?probe=bb055a94f0) | Aug 12, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [63c10b6ae5](https://bsd-hardware.info/?probe=63c10b6ae5) | Aug 11, 2023 |
| Apple         | MacBookAir4,2               | Notebook    | [b1c97a3a9d](https://bsd-hardware.info/?probe=b1c97a3a9d) | Aug 09, 2023 |
| MSI           | MS-7623                     | Desktop     | [189fb4d7cc](https://bsd-hardware.info/?probe=189fb4d7cc) | Aug 08, 2023 |
| Apple         | MacBookAir4,2               | Notebook    | [4fdd124b61](https://bsd-hardware.info/?probe=4fdd124b61) | Aug 07, 2023 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [e74d459c5a](https://bsd-hardware.info/?probe=e74d459c5a) | Jul 28, 2023 |
| Lenovo        | ThinkPad T410 2522NP6       | Notebook    | [194b8efa98](https://bsd-hardware.info/?probe=194b8efa98) | Jul 25, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [d4a26f9214](https://bsd-hardware.info/?probe=d4a26f9214) | Jul 24, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [461ad23cc9](https://bsd-hardware.info/?probe=461ad23cc9) | Jul 24, 2023 |
| Lenovo        | B590 20208                  | Notebook    | [ce1aade2c0](https://bsd-hardware.info/?probe=ce1aade2c0) | Jul 24, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [1ac1ddd084](https://bsd-hardware.info/?probe=1ac1ddd084) | Jul 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [173fe60308](https://bsd-hardware.info/?probe=173fe60308) | Jul 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [26e44ab6e6](https://bsd-hardware.info/?probe=26e44ab6e6) | Jul 23, 2023 |
| ASUSTek       | 900                         | Notebook    | [2e55f5d4cc](https://bsd-hardware.info/?probe=2e55f5d4cc) | Jul 20, 2023 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | Notebook    | [386a80104d](https://bsd-hardware.info/?probe=386a80104d) | Jul 19, 2023 |
| IBM           | ThinkPad T43 1871F1G        | Notebook    | [d6fbc6ebfb](https://bsd-hardware.info/?probe=d6fbc6ebfb) | Jul 18, 2023 |
| Lenovo        | B590 20208                  | Notebook    | [f734b93999](https://bsd-hardware.info/?probe=f734b93999) | Jul 16, 2023 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [57f449130a](https://bsd-hardware.info/?probe=57f449130a) | Jul 16, 2023 |
| Sony          | VPCX115KX                   | Notebook    | [9dab449a23](https://bsd-hardware.info/?probe=9dab449a23) | Jul 15, 2023 |
| Tactus        | GeoBook 140                 | Notebook    | [4b7383c876](https://bsd-hardware.info/?probe=4b7383c876) | Jul 11, 2023 |
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
| Lenovo        | ThinkPad T440p 20AWS1HL0... | Notebook    | [954c65dbcf](https://bsd-hardware.info/?probe=954c65dbcf) | Mar 11, 2021 |
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
| Gigabyte      | J3455N-D3H                  | Desktop     | [576771182b](https://bsd-hardware.info/?probe=576771182b) | May 25, 2020 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [05e8154b2c](https://bsd-hardware.info/?probe=05e8154b2c) | May 25, 2020 |
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

![OS](./All/images/pie_chart_bsd/os_name.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OpenBSD 6.8 | 208       | 27.77%  |
| OpenBSD 7.2 | 95        | 12.68%  |
| OpenBSD 7.1 | 93        | 12.42%  |
| OpenBSD 6.9 | 90        | 12.02%  |
| OpenBSD 7.0 | 89        | 11.88%  |
| OpenBSD 7.3 | 82        | 10.95%  |
| OpenBSD 6.7 | 50        | 6.68%   |
| OpenBSD 7.4 | 39        | 5.21%   |
| OpenBSD 6.6 | 3         | 0.4%    |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| OpenBSD | 612       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| amd64   | 524       | 85.48%  |
| i386    | 51        | 8.32%   |
| arm64   | 22        | 3.59%   |
| macppc  | 8         | 1.31%   |
| sparc64 | 4         | 0.65%   |
| octeon  | 2         | 0.33%   |
| armv7   | 2         | 0.33%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| fvwm          | 274       | 42.28%  |
| helloDesktop  | 205       | 31.64%  |
| Console       | 116       | 17.9%   |
| XFCE          | 27        | 4.17%   |
| GNOME         | 14        | 2.16%   |
| MATE          | 3         | 0.46%   |
| i3            | 3         | 0.46%   |
| Mutter        | 2         | 0.31%   |
| Openbox       | 1         | 0.15%   |
| Lumina        | 1         | 0.15%   |
| iwm           | 1         | 0.15%   |
| Enlightenment | 1         | 0.15%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 448       | 72.26%  |
| Console | 172       | 27.74%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 568       | 91.47%  |
| SLiM    | 31        | 4.99%   |
| GDM     | 22        | 3.54%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 497       | 79.52%  |
| en_US      | 53        | 8.48%   |
| ru_RU      | 23        | 3.68%   |
| C          | 16        | 2.56%   |
| fr_FR      | 8         | 1.28%   |
| en_GB      | 5         | 0.8%    |
| de_DE      | 4         | 0.64%   |
| es_CO      | 3         | 0.48%   |
| zh_TW      | 2         | 0.32%   |
| pl_PL      | 2         | 0.32%   |
| ja_JP      | 2         | 0.32%   |
| es_ES      | 2         | 0.32%   |
| en_EN      | 2         | 0.32%   |
| en_AU      | 2         | 0.32%   |
| zh_CN      | 1         | 0.16%   |
| ISO8859-15 | 1         | 0.16%   |
| fr_CA      | 1         | 0.16%   |
| en_CA      | 1         | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 311       | 50.08%  |
| BIOS | 310       | 49.92%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ffs  | 612       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 339       | 54.77%  |
| GPT     | 276       | 44.59%  |
| Unknown | 4         | 0.65%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 157       | 25.65%  |
| ASUSTek Computer               | 58        | 9.48%   |
| Dell                           | 47        | 7.68%   |
| Hewlett-Packard                | 42        | 6.86%   |
| PC Engines                     | 34        | 5.56%   |
| Unknown                        | 31        | 5.07%   |
| Apple                          | 30        | 4.9%    |
| Gigabyte Technology            | 24        | 3.92%   |
| MSI                            | 21        | 3.43%   |
| ASRock                         | 16        | 2.61%   |
| Intel                          | 15        | 2.45%   |
| Acer                           | 14        | 2.29%   |
| Supermicro                     | 10        | 1.63%   |
| IBM                            | 10        | 1.63%   |
| Panasonic                      | 8         | 1.31%   |
| Raspberry Pi Foundation        | 6         | 0.98%   |
| Fujitsu                        | 6         | 0.98%   |
| Sony                           | 5         | 0.82%   |
| TUXEDO                         | 4         | 0.65%   |
| Toshiba                        | 4         | 0.65%   |
| Sun                            | 4         | 0.65%   |
| Samsung Electronics            | 4         | 0.65%   |
| Soekris Engineering            | 3         | 0.49%   |
| Microsoft                      | 3         | 0.49%   |
| Framework                      | 3         | 0.49%   |
| Alienware                      | 3         | 0.49%   |
| VIA Technologies               | 2         | 0.33%   |
| Tactus                         | 2         | 0.33%   |
| Star Labs                      | 2         | 0.33%   |
| Shuttle                        | 2         | 0.33%   |
| Pegatron                       | 2         | 0.33%   |
| Matsushita Electric Industrial | 2         | 0.33%   |
| Google                         | 2         | 0.33%   |
| Clevo                          | 2         | 0.33%   |
| Biostar                        | 2         | 0.33%   |
| AZW                            | 2         | 0.33%   |
| ZOTAC                          | 1         | 0.16%   |
| Yanling                        | 1         | 0.16%   |
| WYSE                           | 1         | 0.16%   |
| Wistron                        | 1         | 0.16%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 36        | 5.88%   |
| PC Engines APU2                          | 15        | 2.45%   |
| PC Engines apu4                          | 9         | 1.47%   |
| Lenovo ThinkPad X200 745969G             | 6         | 0.98%   |
| PC Engines apu1                          | 5         | 0.82%   |
| Dell PowerEdge R620                      | 5         | 0.82%   |
| ASUS All Series                          | 4         | 0.65%   |
| Supermicro Super Server                  | 3         | 0.49%   |
| RPi Raspberry Pi 400                     | 3         | 0.49%   |
| RPi Raspberry Pi 4 Model B               | 3         | 0.49%   |
| PC Engines APU3                          | 3         | 0.49%   |
| ASUS PRIME H410M-A                       | 3         | 0.49%   |
| Apple MacBookAir7,2                      | 3         | 0.49%   |
| TUXEDO Pulse 15 Gen1                     | 2         | 0.33%   |
| Soekris Engineering net6501              | 2         | 0.33%   |
| PC Engines APU                           | 2         | 0.33%   |
| MSI MS-7A34                              | 2         | 0.33%   |
| Microsoft Surface Pro 7                  | 2         | 0.33%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BSCTO1WW | 2         | 0.33%   |
| HP ZBook 15 G4                           | 2         | 0.33%   |
| HP ProLiant DL360 Gen9                   | 2         | 0.33%   |
| Gigabyte M68MT-S2P                       | 2         | 0.33%   |
| Fujitsu LIFEBOOK E752                    | 2         | 0.33%   |
| Framework Laptop                         | 2         | 0.33%   |
| Dell XPS 13 9360                         | 2         | 0.33%   |
| ASUS X102BA                              | 2         | 0.33%   |
| ASUS PRIME X370-PRO                      | 2         | 0.33%   |
| ASUS PRIME B650-PLUS                     | 2         | 0.33%   |
| Apple PowerMac3,6                        | 2         | 0.33%   |
| Apple MacPro4,1                          | 2         | 0.33%   |
| Apple MacBookAir6,2                      | 2         | 0.33%   |
| Apple MacBook5,1                         | 2         | 0.33%   |
| Acer Nitro AN515-55                      | 2         | 0.33%   |
| ZOTAC XXXXXX                             | 1         | 0.16%   |
| Yanling YL-KBR6L                         | 1         | 0.16%   |
| WYSE D CLASS                             | 1         | 0.16%   |
| Wistron ProLiant ML110 G6                | 1         | 0.16%   |
| VIA VT8623-8235                          | 1         | 0.16%   |
| VIA VT82C597                             | 1         | 0.16%   |
| TUXEDO InfinityBook Pro 14 Gen6          | 1         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Lenovo ThinkPad             | 128       | 20.92%  |
| Unknown                     | 36        | 5.88%   |
| ASUS PRIME                  | 16        | 2.61%   |
| PC Engines APU2             | 15        | 2.45%   |
| Dell PowerEdge              | 11        | 1.8%    |
| PC Engines apu4             | 9         | 1.47%   |
| Lenovo ThinkCentre          | 9         | 1.47%   |
| Dell OptiPlex               | 8         | 1.31%   |
| Dell Latitude               | 8         | 1.31%   |
| IBM ThinkPad                | 7         | 1.14%   |
| HP Pavilion                 | 7         | 1.14%   |
| RPi Raspberry               | 6         | 0.98%   |
| Lenovo IdeaPad              | 6         | 0.98%   |
| PC Engines apu1             | 5         | 0.82%   |
| HP ProLiant                 | 5         | 0.82%   |
| HP Compaq                   | 5         | 0.82%   |
| Fujitsu LIFEBOOK            | 5         | 0.82%   |
| Dell XPS                    | 5         | 0.82%   |
| Acer Aspire                 | 5         | 0.82%   |
| Sun SUNW                    | 4         | 0.65%   |
| Dell Vostro                 | 4         | 0.65%   |
| Dell Precision              | 4         | 0.65%   |
| Dell Inspiron               | 4         | 0.65%   |
| ASUS VivoBook               | 4         | 0.65%   |
| ASUS All                    | 4         | 0.65%   |
| Supermicro Super            | 3         | 0.49%   |
| PC Engines APU3             | 3         | 0.49%   |
| Microsoft Surface           | 3         | 0.49%   |
| Lenovo Yoga                 | 3         | 0.49%   |
| HP ProBook                  | 3         | 0.49%   |
| Framework Laptop            | 3         | 0.49%   |
| ASUS ROG                    | 3         | 0.49%   |
| Apple MacBookAir7           | 3         | 0.49%   |
| Apple MacBookAir6           | 3         | 0.49%   |
| TUXEDO Pulse                | 2         | 0.33%   |
| Toshiba Satellite           | 2         | 0.33%   |
| Soekris Engineering net6501 | 2         | 0.33%   |
| PC Engines APU              | 2         | 0.33%   |
| MSI MS-7A34                 | 2         | 0.33%   |
| Lenovo FLEX                 | 2         | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 60        | 9.8%    |
| 2019    | 56        | 9.15%   |
| 2018    | 52        | 8.5%    |
| 2021    | 42        | 6.86%   |
| Unknown | 40        | 6.54%   |
| 2015    | 33        | 5.39%   |
| 2016    | 32        | 5.23%   |
| 2013    | 32        | 5.23%   |
| 2011    | 32        | 5.23%   |
| 2010    | 29        | 4.74%   |
| 2012    | 28        | 4.58%   |
| 2014    | 27        | 4.41%   |
| 2022    | 26        | 4.25%   |
| 2009    | 26        | 4.25%   |
| 2017    | 24        | 3.92%   |
| 2023    | 17        | 2.78%   |
| 2007    | 16        | 2.61%   |
| 2006    | 14        | 2.29%   |
| 2008    | 13        | 2.12%   |
| 2005    | 4         | 0.65%   |
| 2004    | 4         | 0.65%   |
| 2003    | 3         | 0.49%   |
| 2002    | 1         | 0.16%   |
| 2001    | 1         | 0.16%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 305       | 49.84%  |
| Desktop        | 284       | 46.41%  |
| Mini pc        | 7         | 1.14%   |
| Server         | 6         | 0.98%   |
| All in one     | 4         | 0.65%   |
| Tablet         | 3         | 0.49%   |
| System on chip | 2         | 0.33%   |
| Convertible    | 1         | 0.16%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 568       | 92.81%  |
| Yes  | 44        | 7.19%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 167       | 26.85%  |
| 4.01-8.0        | 129       | 20.74%  |
| 16.01-24.0      | 96        | 15.43%  |
| 3.01-4.0        | 56        | 9%      |
| 32.01-64.0      | 43        | 6.91%   |
| 2.01-3.0        | 33        | 5.31%   |
| 1.01-2.0        | 27        | 4.34%   |
| 0.51-1.0        | 22        | 3.54%   |
| 64.01-256.0     | 20        | 3.22%   |
| 0.01-0.5        | 14        | 2.25%   |
| 24.01-32.0      | 12        | 1.93%   |
| More than 256.0 | 3         | 0.48%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 490       | 79.42%  |
| 0.51-1.0   | 51        | 8.27%   |
| 0          | 42        | 6.81%   |
| 1.01-2.0   | 15        | 2.43%   |
| 4.01-8.0   | 7         | 1.13%   |
| Unknown    | 7         | 1.13%   |
| 3.01-4.0   | 2         | 0.32%   |
| 8.01-16.0  | 2         | 0.32%   |
| 16.01-24.0 | 1         | 0.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 325       | 50.78%  |
| 2      | 195       | 30.47%  |
| 3      | 62        | 9.69%   |
| 4      | 28        | 4.38%   |
| 0      | 14        | 2.19%   |
| 5      | 5         | 0.78%   |
| 6      | 4         | 0.63%   |
| 10     | 2         | 0.31%   |
| 7      | 2         | 0.31%   |
| 14     | 1         | 0.16%   |
| 12     | 1         | 0.16%   |
| 8      | 1         | 0.16%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 608       | 99.18%  |
| Yes       | 5         | 0.82%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 524       | 85.62%  |
| No        | 88        | 14.38%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 376       | 61.34%  |
| No        | 237       | 38.66%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 373       | 60.45%  |
| Yes       | 244       | 39.55%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 106       | 17.21%  |
| Russia       | 84        | 13.64%  |
| Germany      | 71        | 11.53%  |
| France       | 40        | 6.49%   |
| Canada       | 29        | 4.71%   |
| UK           | 25        | 4.06%   |
| Poland       | 25        | 4.06%   |
| Netherlands  | 23        | 3.73%   |
| Italy        | 23        | 3.73%   |
| Spain        | 17        | 2.76%   |
| Sweden       | 16        | 2.6%    |
| Switzerland  | 14        | 2.27%   |
| Ukraine      | 11        | 1.79%   |
| Australia    | 11        | 1.79%   |
| Brazil       | 10        | 1.62%   |
| Norway       | 8         | 1.3%    |
| Austria      | 8         | 1.3%    |
| Taiwan       | 7         | 1.14%   |
| Romania      | 5         | 0.81%   |
| Mexico       | 5         | 0.81%   |
| Latvia       | 5         | 0.81%   |
| Colombia     | 5         | 0.81%   |
| Japan        | 4         | 0.65%   |
| India        | 4         | 0.65%   |
| Czechia      | 4         | 0.65%   |
| Uruguay      | 3         | 0.49%   |
| Portugal     | 3         | 0.49%   |
| Philippines  | 3         | 0.49%   |
| Finland      | 3         | 0.49%   |
| Cyprus       | 3         | 0.49%   |
| Croatia      | 3         | 0.49%   |
| China        | 3         | 0.49%   |
| Bulgaria     | 3         | 0.49%   |
| Turkey       | 2         | 0.32%   |
| Slovakia     | 2         | 0.32%   |
| Saudi Arabia | 2         | 0.32%   |
| Malaysia     | 2         | 0.32%   |
| Indonesia    | 2         | 0.32%   |
| Egypt        | 2         | 0.32%   |
| Denmark      | 2         | 0.32%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| St Petersburg     | 21        | 3.15%   |
| Moscow            | 20        | 3%      |
| Montreal          | 18        | 2.7%    |
| Saint-Laurent     | 15        | 2.25%   |
| Amsterdam         | 14        | 2.1%    |
| Berlin            | 13        | 1.95%   |
| Paris             | 12        | 1.8%    |
| Vladivostok       | 11        | 1.65%   |
| Milan             | 9         | 1.35%   |
| Gdansk            | 8         | 1.2%    |
| Zurich            | 6         | 0.9%    |
| Vienna            | 6         | 0.9%    |
| New Taipei        | 6         | 0.9%    |
| Sydney            | 5         | 0.75%   |
| Sun Prairie       | 5         | 0.75%   |
| Riga              | 5         | 0.75%   |
| QuГ©bec         | 5         | 0.75%   |
| Puebla City       | 5         | 0.75%   |
| Brooklyn          | 5         | 0.75%   |
| Blumenau          | 5         | 0.75%   |
| Poortugaal        | 4         | 0.6%    |
| Oslo              | 4         | 0.6%    |
| Nuremberg         | 4         | 0.6%    |
| Miedziana Gora    | 4         | 0.6%    |
| Malmo             | 4         | 0.6%    |
| Ibiza Town        | 4         | 0.6%    |
| Gummersbach       | 4         | 0.6%    |
| Frankfurt am Main | 4         | 0.6%    |
| Yekaterinburg     | 3         | 0.45%   |
| Wroclaw           | 3         | 0.45%   |
| Wittersham        | 3         | 0.45%   |
| Syeverodonets'k   | 3         | 0.45%   |
| Sofia             | 3         | 0.45%   |
| Portland          | 3         | 0.45%   |
| New York          | 3         | 0.45%   |
| Montevideo        | 3         | 0.45%   |
| Mâcon            | 3         | 0.45%   |
| Lübeck           | 3         | 0.45%   |
| Los Angeles       | 3         | 0.45%   |
| London            | 3         | 0.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| NVMe                | 135       | 188    | 17.13%  |
| Samsung Electronics | 91        | 159    | 11.55%  |
| WDC                 | 83        | 145    | 10.53%  |
| Seagate             | 75        | 128    | 9.52%   |
| Kingston            | 41        | 54     | 5.2%    |
| SanDisk             | 34        | 41     | 4.31%   |
| Toshiba             | 32        | 49     | 4.06%   |
| Crucial             | 31        | 42     | 3.93%   |
| Hitachi             | 24        | 40     | 3.05%   |
| Intel               | 22        | 27     | 2.79%   |
| OPENBSD             | 16        | 27     | 2.03%   |
| HGST                | 15        | 26     | 1.9%    |
| Phison              | 14        | 16     | 1.78%   |
| Apple               | 14        | 14     | 1.78%   |
| Transcend           | 10        | 17     | 1.27%   |
| PNY                 | 9         | 12     | 1.14%   |
| A-DATA Technology   | 8         | 14     | 1.02%   |
| SK hynix            | 7         | 7      | 0.89%   |
| Dell                | 7         | 12     | 0.89%   |
| Apacer              | 6         | 8      | 0.76%   |
| USB                 | 5         | 5      | 0.63%   |
| Hewlett-Packard     | 5         | 10     | 0.63%   |
| Fujitsu             | 5         | 5      | 0.63%   |
| SPCC                | 4         | 4      | 0.51%   |
| Generic             | 4         | 4      | 0.51%   |
| Patriot             | 3         | 3      | 0.38%   |
| OCZ                 | 3         | 3      | 0.38%   |
| Netac               | 3         | 3      | 0.38%   |
| Micron Technology   | 3         | 3      | 0.38%   |
| LSI                 | 3         | 7      | 0.38%   |
| Lexar               | 3         | 3      | 0.38%   |
| KingSpec            | 3         | 3      | 0.38%   |
| Intenso             | 3         | 3      | 0.38%   |
| Innostor            | 3         | 3      | 0.38%   |
| Corsair             | 3         | 3      | 0.38%   |
| China               | 3         | 3      | 0.38%   |
| Team                | 2         | 2      | 0.25%   |
| StoreJet            | 2         | 2      | 0.25%   |
| Plextor             | 2         | 2      | 0.25%   |
| Multiple            | 2         | 2      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| OPENBSD SR RAID 1 2TB               | 13        | 1.53%   |
| NVMe Samsung SSD 980 1TB            | 13        | 1.53%   |
| Phison SATA SSD 16GB                | 11        | 1.29%   |
| NVMe WDC PC SN730 SDB 512GB         | 9         | 1.06%   |
| NVMe Samsung SSD 970 250GB          | 9         | 1.06%   |
| Seagate ST1000LM035-1RK172 1TB      | 8         | 0.94%   |
| Samsung HM321HI 320GB               | 6         | 0.71%   |
| Kingston SA400S37240G 240GB         | 6         | 0.71%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 5         | 0.59%   |
| USB SanDisk 3.2Gen1 16GB            | 5         | 0.59%   |
| Samsung SSD 860 EVO 250GB           | 5         | 0.59%   |
| Samsung SSD 850 EVO 500GB           | 5         | 0.59%   |
| NVMe SAMSUNG MZVLB256 256GB         | 5         | 0.59%   |
| Kingston SA400S37480G 480GB         | 5         | 0.59%   |
| Intel SSDSC2BW480H6 480GB           | 5         | 0.59%   |
| Crucial CT1000MX500SSD1 1TB         | 5         | 0.59%   |
| Toshiba MQ04ABF100 1TB              | 4         | 0.47%   |
| Seagate ST1000DM010-2EP102 1TB      | 4         | 0.47%   |
| SanDisk Ultra Fit 128GB             | 4         | 0.47%   |
| SanDisk Cruzer Blade 64GB           | 4         | 0.47%   |
| Samsung SSD 860 EVO mSATA 500GB     | 4         | 0.47%   |
| Samsung SSD 860 EVO 500GB           | 4         | 0.47%   |
| Samsung SSD 860 EVO 1TB             | 4         | 0.47%   |
| Samsung SSD 850 EVO 250GB           | 4         | 0.47%   |
| Samsung SSD 850 EVO 1TB             | 4         | 0.47%   |
| NVMe Samsung SSD 960 500GB          | 4         | 0.47%   |
| NVMe SAMSUNG MZVLW256 256GB         | 4         | 0.47%   |
| Kingston SUV500MS240G 240GB         | 4         | 0.47%   |
| Dell PERC H710 282GB                | 4         | 0.47%   |
| Crucial CT240BX500SSD1 240GB        | 4         | 0.47%   |
| Apple SSD SM0128G 121GB             | 4         | 0.47%   |
| WDC WD6400AARS-00Y5B1 640GB         | 3         | 0.35%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 3         | 0.35%   |
| Seagate ST3250318AS 250GB           | 3         | 0.35%   |
| Seagate ST250DM000-1BD141 250GB     | 3         | 0.35%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 3         | 0.35%   |
| SanDisk SSD PLUS 120GB              | 3         | 0.35%   |
| Samsung SSD 860 EVO M.2 1TB         | 3         | 0.35%   |
| Samsung SSD 840 EVO 250GB           | 3         | 0.35%   |
| Samsung SSD 840 EVO 120GB           | 3         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                             | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| NVMe                               | 87        | 120    | 21.91%  |
| Seagate                            | 75        | 128    | 18.89%  |
| WDC                                | 73        | 134    | 18.39%  |
| Toshiba                            | 28        | 45     | 7.05%   |
| Hitachi                            | 24        | 40     | 6.05%   |
| Samsung Electronics                | 20        | 30     | 5.04%   |
| OPENBSD                            | 16        | 27     | 4.03%   |
| HGST                               | 15        | 26     | 3.78%   |
| Dell                               | 7         | 12     | 1.76%   |
| USB                                | 5         | 5      | 1.26%   |
| Fujitsu                            | 5         | 5      | 1.26%   |
| Generic                            | 4         | 4      | 1.01%   |
| Apple                              | 4         | 4      | 1.01%   |
| Hewlett-Packard                    | 3         | 7      | 0.76%   |
| StoreJet                           | 2         | 2      | 0.5%    |
| Multiple                           | 2         | 2      | 0.5%    |
| Maxtor                             | 2         | 3      | 0.5%    |
| LSI                                | 2         | 5      | 0.5%    |
| Lexar                              | 2         | 2      | 0.5%    |
| JetFlash                           | 2         | 2      | 0.5%    |
| General                            | 2         | 2      | 0.5%    |
| ASMT                               | 2         | 2      | 0.5%    |
| Verbatim                           | 1         | 1      | 0.25%   |
| UFD 2.0                            | 1         | 1      | 0.25%   |
| SSDPR-CX                           | 1         | 1      | 0.25%   |
| SMI                                | 1         | 1      | 0.25%   |
| SABRENT                            | 1         | 1      | 0.25%   |
| Product:              USB DISK 3.0 | 1         | 1      | 0.25%   |
| Product:              USB DISK 2.0 | 1         | 1      | 0.25%   |
| Product:                           | 1         | 1      | 0.25%   |
| Memorex                            | 1         | 1      | 0.25%   |
| MaxDigital                         | 1         | 1      | 0.25%   |
| LSILOGIC                           | 1         | 1      | 0.25%   |
| LDLC F6+                           | 1         | 1      | 0.25%   |
| IBM-ESXS                           | 1         | 1      | 0.25%   |
| IBM                                | 1         | 1      | 0.25%   |
| China                              | 1         | 1      | 0.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 72        | 129    | 18.51%  |
| NVMe                | 45        | 54     | 11.57%  |
| Kingston            | 41        | 54     | 10.54%  |
| SanDisk             | 34        | 41     | 8.74%   |
| Crucial             | 31        | 42     | 7.97%   |
| Intel               | 22        | 27     | 5.66%   |
| Phison              | 14        | 16     | 3.6%    |
| WDC                 | 10        | 11     | 2.57%   |
| Transcend           | 10        | 17     | 2.57%   |
| Apple               | 10        | 10     | 2.57%   |
| PNY                 | 9         | 12     | 2.31%   |
| A-DATA Technology   | 8         | 14     | 2.06%   |
| SK hynix            | 7         | 7      | 1.8%    |
| Apacer              | 6         | 8      | 1.54%   |
| Toshiba             | 4         | 4      | 1.03%   |
| SPCC                | 4         | 4      | 1.03%   |
| Patriot             | 3         | 3      | 0.77%   |
| OCZ                 | 3         | 3      | 0.77%   |
| Netac               | 3         | 3      | 0.77%   |
| Micron Technology   | 3         | 3      | 0.77%   |
| KingSpec            | 3         | 3      | 0.77%   |
| Intenso             | 3         | 3      | 0.77%   |
| Innostor            | 3         | 3      | 0.77%   |
| Corsair             | 3         | 3      | 0.77%   |
| Team                | 2         | 2      | 0.51%   |
| Plextor             | 2         | 2      | 0.51%   |
| LITEONIT            | 2         | 2      | 0.51%   |
| Hoodisk             | 2         | 3      | 0.51%   |
| Hewlett-Packard     | 2         | 3      | 0.51%   |
| China               | 2         | 2      | 0.51%   |
| AMD                 | 2         | 2      | 0.51%   |
| Zheino              | 1         | 2      | 0.26%   |
| XPG                 | 1         | 1      | 0.26%   |
| Union Memory        | 1         | 1      | 0.26%   |
| UDinfo              | 1         | 1      | 0.26%   |
| Star Drive          | 1         | 1      | 0.26%   |
| SATA3 60            | 1         | 1      | 0.26%   |
| Qumo                | 1         | 1      | 0.26%   |
| OWC                 | 1         | 1      | 0.26%   |
| MidasForce          | 1         | 1      | 0.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 341       | 518    | 50.22%  |
| HDD  | 326       | 622    | 48.01%  |
| NVMe | 12        | 14     | 1.77%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 574       | 1140   | 97.95%  |
| NVMe | 12        | 14     | 2.05%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 451       | 695    | 64.89%  |
| 0.51-1.0        | 159       | 238    | 22.88%  |
| 1.01-2.0        | 53        | 149    | 7.63%   |
| 3.01-4.0        | 14        | 22     | 2.01%   |
| 4.01-10.0       | 11        | 27     | 1.58%   |
| More than 100.0 | 3         | 3      | 0.43%   |
| 2.01-3.0        | 3         | 5      | 0.43%   |
| 0               | 1         | 1      | 0.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 216       | 33.7%   |
| 251-500        | 179       | 27.93%  |
| 51-100         | 69        | 10.76%  |
| 21-50          | 55        | 8.58%   |
| 1-20           | 50        | 7.8%    |
| 501-1000       | 34        | 5.3%    |
| 1001-2000      | 20        | 3.12%   |
| More than 3000 | 14        | 2.18%   |
| 2001-3000      | 4         | 0.62%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 453       | 70.02%  |
| 21-50          | 66        | 10.2%   |
| 101-250        | 45        | 6.96%   |
| 51-100         | 43        | 6.65%   |
| 251-500        | 17        | 2.63%   |
| 501-1000       | 11        | 1.7%    |
| 1001-2000      | 7         | 1.08%   |
| More than 3000 | 4         | 0.62%   |
| 2001-3000      | 1         | 0.15%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| Intel SSDSC2BW480H6 480GB        | 5         | 5      | 5.88%   |
| Toshiba MQ04ABF100 1TB           | 2         | 2      | 2.35%   |
| Seagate ST9320423AS 320GB        | 2         | 2      | 2.35%   |
| OCZ VERTEX3 120GB                | 2         | 2      | 2.35%   |
| Kingston SMS200S330G 32GB        | 2         | 4      | 2.35%   |
| Intel SSDSC2KF256H6L 256GB       | 2         | 2      | 2.35%   |
| HGST HTS541010A7E630 1TB         | 2         | 4      | 2.35%   |
| A-DATA Technology SP550 240GB    | 2         | 2      | 2.35%   |
| XPG SX950U 240GB                 | 1         | 1      | 1.18%   |
| WDC WD7500AACS-00ZJB0 752GB      | 1         | 1      | 1.18%   |
| WDC WD6400AAKS-22A7B0 640GB      | 1         | 1      | 1.18%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 1         | 2      | 1.18%   |
| WDC WD2500BEVS-22UST0 250GB      | 1         | 1      | 1.18%   |
| WDC WD1600BEVT-22ZCT0 160GB      | 1         | 1      | 1.18%   |
| WDC WD1600BEVE-00UYT0 160GB      | 1         | 1      | 1.18%   |
| WDC WD15EARS-00Z5B1 1.5TB        | 1         | 1      | 1.18%   |
| WDC WD10SPZX-24Z10 1TB           | 1         | 1      | 1.18%   |
| WDC WD10EADS-00M2B0 1TB          | 1         | 1      | 1.18%   |
| Transcend 3E128-TS2-550B01 100GB | 1         | 4      | 1.18%   |
| Toshiba MQ01ACF032 320GB         | 1         | 3      | 1.18%   |
| Toshiba MK6475GSX 640GB          | 1         | 2      | 1.18%   |
| Toshiba MK6006GAH 64GB           | 1         | 1      | 1.18%   |
| Toshiba MK5065GSX 500GB          | 1         | 1      | 1.18%   |
| Toshiba MK1629GSGF 160GB         | 1         | 3      | 1.18%   |
| Toshiba DT01ACA100 1TB           | 1         | 1      | 1.18%   |
| Seagate ST9500420AS 500GB        | 1         | 2      | 1.18%   |
| Seagate ST9500325AS 500GB        | 1         | 1      | 1.18%   |
| Seagate ST9160310AS 160GB        | 1         | 2      | 1.18%   |
| Seagate ST500LT012-9WS142 500GB  | 1         | 1      | 1.18%   |
| Seagate ST500DM002-1BD142 500GB  | 1         | 1      | 1.18%   |
| Seagate ST380815AS 80GB          | 1         | 1      | 1.18%   |
| Seagate ST3750640NS 752GB        | 1         | 6      | 1.18%   |
| Seagate ST3500418AS 500GB        | 1         | 1      | 1.18%   |
| Seagate ST3320418AS 320GB        | 1         | 1      | 1.18%   |
| Seagate ST3160212SCE 160GB       | 1         | 1      | 1.18%   |
| Seagate ST3120211AS 120GB        | 1         | 1      | 1.18%   |
| Seagate ST250DM000-1BD141 250GB  | 1         | 3      | 1.18%   |
| Seagate ST2000DM006-2DM164 2TB   | 1         | 1      | 1.18%   |
| Seagate ST1000DM003-1CH162 1TB   | 1         | 1      | 1.18%   |
| SanDisk SSD PLUS 240GB           | 1         | 1      | 1.18%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 25     | 18.07%  |
| Intel               | 10        | 10     | 12.05%  |
| WDC                 | 8         | 10     | 9.64%   |
| Toshiba             | 8         | 13     | 9.64%   |
| Samsung Electronics | 7         | 11     | 8.43%   |
| Hitachi             | 7         | 8      | 8.43%   |
| HGST                | 6         | 9      | 7.23%   |
| Kingston            | 5         | 7      | 6.02%   |
| A-DATA Technology   | 4         | 10     | 4.82%   |
| SanDisk             | 2         | 3      | 2.41%   |
| OCZ                 | 2         | 2      | 2.41%   |
| KingSpec            | 2         | 2      | 2.41%   |
| XPG                 | 1         | 1      | 1.2%    |
| Transcend           | 1         | 4      | 1.2%    |
| Micron Technology   | 1         | 1      | 1.2%    |
| Hewlett-Packard     | 1         | 1      | 1.2%    |
| GLOWAY              | 1         | 1      | 1.2%    |
| Corsair             | 1         | 1      | 1.2%    |
| Apple               | 1         | 1      | 1.2%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 25     | 30%     |
| WDC                 | 8         | 10     | 16%     |
| Toshiba             | 8         | 13     | 16%     |
| Hitachi             | 7         | 8      | 14%     |
| HGST                | 6         | 9      | 12%     |
| Samsung Electronics | 5         | 8      | 10%     |
| Hewlett-Packard     | 1         | 1      | 2%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 50        | 74     | 60.24%  |
| SSD  | 33        | 46     | 39.76%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart_bsd/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD6400AARS-00Y5B1 640GB     | 1         | 2      | 50%     |
| Samsung Electronics HD204UI 2TB | 1         | 2      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 2      | 50%     |
| Samsung Electronics | 1         | 2      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 410       | 735    | 60.38%  |
| Detected | 185       | 295    | 27.25%  |
| Malfunc  | 82        | 120    | 12.08%  |
| Failed   | 2         | 4      | 0.29%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 370       | 54.41%  |
| AMD                              | 114       | 16.76%  |
| Samsung Electronics              | 60        | 8.82%   |
| SanDisk                          | 29        | 4.26%   |
| Broadcom / LSI                   | 15        | 2.21%   |
| Nvidia                           | 9         | 1.32%   |
| Phison Electronics               | 8         | 1.18%   |
| KIOXIA                           | 8         | 1.18%   |
| Marvell Technology Group         | 7         | 1.03%   |
| Kingston Technology Company      | 7         | 1.03%   |
| SK hynix                         | 6         | 0.88%   |
| VIA Technologies                 | 5         | 0.74%   |
| Micron/Crucial Technology        | 5         | 0.74%   |
| ASMedia Technology               | 5         | 0.74%   |
| ADATA Technology                 | 5         | 0.74%   |
| Shenzhen Longsys Electronics     | 3         | 0.44%   |
| Lenovo                           | 3         | 0.44%   |
| Hewlett-Packard                  | 3         | 0.44%   |
| ULi Electronics                  | 2         | 0.29%   |
| Toshiba                          | 2         | 0.29%   |
| Silicon Motion                   | 2         | 0.29%   |
| Micron Technology                | 2         | 0.29%   |
| Union Memory (Shenzhen)          | 1         | 0.15%   |
| Solid State Storage Technology   | 1         | 0.15%   |
| Silicon Integrated Systems [SiS] | 1         | 0.15%   |
| Silicon Image                    | 1         | 0.15%   |
| Seagate Technology               | 1         | 0.15%   |
| HighPoint Technologies           | 1         | 0.15%   |
| Dell                             | 1         | 0.15%   |
| Biwin Storage Technology         | 1         | 0.15%   |
| Artop Electronic                 | 1         | 0.15%   |
| Unknown                          | 1         | 0.15%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 61        | 8.01%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 32        | 4.2%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 30        | 3.94%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 23        | 3.02%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 23        | 3.02%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 23        | 3.02%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 21        | 2.76%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 20        | 2.62%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 19        | 2.49%   |
| AMD FCH SATA Controller [IDE mode]                                             | 18        | 2.36%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 17        | 2.23%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 14        | 1.84%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 14        | 1.84%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 12        | 1.57%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 12        | 1.57%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 12        | 1.57%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 11        | 1.44%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 9         | 1.18%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 9         | 1.18%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 9         | 1.18%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 9         | 1.18%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 9         | 1.18%   |
| AMD 500 Series Chipset SATA Controller                                         | 9         | 1.18%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 8         | 1.05%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 8         | 1.05%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 8         | 1.05%   |
| AMD 400 Series Chipset SATA Controller                                         | 8         | 1.05%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 7         | 0.92%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 7         | 0.92%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 6         | 0.79%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 6         | 0.79%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 6         | 0.79%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 6         | 0.79%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 5         | 0.66%   |
| Nvidia MCP61 SATA Controller                                                   | 5         | 0.66%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 5         | 0.66%   |
| Intel Comet Lake SATA AHCI Controller                                          | 5         | 0.66%   |
| Intel 82801FBM (ICH6M) SATA Controller                                         | 5         | 0.66%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                 | 5         | 0.66%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 5         | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 429       | 61.55%  |
| NVMe | 133       | 19.08%  |
| IDE  | 109       | 15.64%  |
| RAID | 16        | 2.3%    |
| SAS  | 5         | 0.72%   |
| SCSI | 5         | 0.72%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 431       | 70.42%  |
| AMD     | 141       | 23.04%  |
| ARM     | 23        | 3.76%   |
| Unknown | 11        | 1.8%    |
| PowerPC | 4         | 0.65%   |
| VIA     | 1         | 0.16%   |
| 11th    | 1         | 0.16%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| AMD GX-412TC SOC                                         | 27        | 4.35%   |
| Intel Core i5-2520M CPU @ 2.50GHz                        | 13        | 2.1%    |
| ARM Cortex-A72 r0p3                                      | 13        | 2.1%    |
| Intel Core i5-6300U CPU @ 2.40GHz                        | 11        | 1.77%   |
| Intel Core i5-3320M CPU @ 2.60GHz                        | 11        | 1.77%   |
|                                                          | 11        | 1.77%   |
| Intel Core i5-5300U CPU @ 2.30GHz                        | 8         | 1.29%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz                     | 7         | 1.13%   |
| ARM Cortex-A53 r0p4                                      | 7         | 1.13%   |
| AMD G-T40E Processor                                     | 7         | 1.13%   |
| Intel Core i5-8250U CPU @ 1.60GHz                        | 6         | 0.97%   |
| Intel Core i7-8550U CPU @ 1.80GHz                        | 5         | 0.81%   |
| Intel Core i7-7500U CPU @ 2.70GHz                        | 5         | 0.81%   |
| Intel Core i5-5200U CPU @ 2.20GHz                        | 5         | 0.81%   |
| Intel Atom CPU N270 @ 1.60GHz ("GenuineIntel" 686-class) | 5         | 0.81%   |
| Intel Core i7-8565U CPU @ 1.80GHz                        | 4         | 0.65%   |
| Intel Core i5-8265U CPU @ 1.60GHz                        | 4         | 0.65%   |
| Intel Core i5-4570 CPU @ 3.20GHz                         | 4         | 0.65%   |
| Intel Core i5-4300U CPU @ 1.90GHz                        | 4         | 0.65%   |
| Intel Core i5 CPU M 520 @ 2.40GHz                        | 4         | 0.65%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz                     | 4         | 0.65%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz                  | 4         | 0.65%   |
| AMD Ryzen 7 5800X 8-Core Processor                       | 4         | 0.65%   |
| AMD Ryzen 7 4800H with Radeon Graphics                   | 4         | 0.65%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz                      | 3         | 0.48%   |
| Intel Pentium M processor                                | 3         | 0.48%   |
| Intel Core i7-8750H CPU @ 2.20GHz                        | 3         | 0.48%   |
| Intel Core i7-8650U CPU @ 1.90GHz                        | 3         | 0.48%   |
| Intel Core i7-6600U CPU @ 2.60GHz                        | 3         | 0.48%   |
| Intel Core i7-5600U CPU @ 2.60GHz                        | 3         | 0.48%   |
| Intel Core i7-3520M CPU @ 2.90GHz                        | 3         | 0.48%   |
| Intel Core i7-10510U CPU @ 1.80GHz                       | 3         | 0.48%   |
| Intel Core i5-4260U CPU @ 1.40GHz                        | 3         | 0.48%   |
| Intel Core i5-2540M CPU @ 2.60GHz                        | 3         | 0.48%   |
| Intel Core i5-10210U CPU @ 1.60GHz                       | 3         | 0.48%   |
| Intel Core i3-6006U CPU @ 2.00GHz                        | 3         | 0.48%   |
| Intel Celeron N4020 CPU @ 1.10GHz                        | 3         | 0.48%   |
| Intel Celeron CPU J1900 @ 1.99GHz                        | 3         | 0.48%   |
| AMD Ryzen 7 4700U with Radeon Graphics                   | 3         | 0.48%   |
| AMD Ryzen 5 3600 6-Core Processor                        | 3         | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 135       | 22.02%  |
| Intel Core i7           | 68        | 11.09%  |
| Intel Xeon              | 40        | 6.53%   |
| Other                   | 38        | 6.2%    |
| Intel Celeron           | 33        | 5.38%   |
| Intel Core i3           | 32        | 5.22%   |
| AMD GX                  | 28        | 4.57%   |
| AMD Ryzen 7             | 27        | 4.4%    |
| Intel Core 2 Duo        | 26        | 4.24%   |
| ARM Cortex              | 23        | 3.75%   |
| Intel Atom              | 15        | 2.45%   |
| AMD Ryzen 5             | 15        | 2.45%   |
| AMD G                   | 8         | 1.31%   |
| Intel Pentium M         | 7         | 1.14%   |
| Intel Genuine           | 7         | 1.14%   |
| Intel Pentium 4         | 6         | 0.98%   |
| Intel Pentium           | 6         | 0.98%   |
| Intel Core 2            | 6         | 0.98%   |
| AMD Ryzen 9             | 6         | 0.98%   |
| Intel Pentium Dual-Core | 5         | 0.82%   |
| AMD Ryzen 7 PRO         | 5         | 0.82%   |
| AMD Ryzen 3             | 5         | 0.82%   |
| AMD A4                  | 5         | 0.82%   |
| Intel Pentium Silver    | 4         | 0.65%   |
| Intel Core i9           | 3         | 0.49%   |
| Intel Core Duo          | 3         | 0.49%   |
| Intel Core 2 Quad       | 3         | 0.49%   |
| AMD E2                  | 3         | 0.49%   |
| AMD E1                  | 3         | 0.49%   |
| AMD A6                  | 3         | 0.49%   |
| Intel Xeon Gold         | 2         | 0.33%   |
| Intel Core m3           | 2         | 0.33%   |
| Intel Celeron M         | 2         | 0.33%   |
| AMD Ryzen 5 PRO         | 2         | 0.33%   |
| AMD Phenom II X4        | 2         | 0.33%   |
| AMD Geode Integrated    | 2         | 0.33%   |
| AMD E                   | 2         | 0.33%   |
| AMD Athlon II X3        | 2         | 0.33%   |
| AMD Athlon II X2        | 2         | 0.33%   |
| AMD Athlon 64 X2        | 2         | 0.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 197       | 32.14%  |
| 4       | 169       | 27.57%  |
| Unknown | 108       | 17.62%  |
| 1       | 42        | 6.85%   |
| 16      | 24        | 3.92%   |
| 8       | 24        | 3.92%   |
| 6       | 22        | 3.59%   |
| 12      | 17        | 2.77%   |
| 32      | 3         | 0.49%   |
| 36      | 2         | 0.33%   |
| 24      | 2         | 0.33%   |
| 3       | 2         | 0.33%   |
| 14      | 1         | 0.16%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 474       | 76.7%   |
| Unknown | 132       | 21.36%  |
| 2       | 12        | 1.94%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 266       | 43.46%  |
| 1       | 203       | 33.17%  |
| Unknown | 143       | 23.37%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 70        | 11.4%   |
| Unknown       | 69        | 11.24%  |
| Haswell       | 43        | 7%      |
| SandyBridge   | 37        | 6.03%   |
| IvyBridge     | 35        | 5.7%    |
| Broadwell     | 33        | 5.37%   |
| Penryn        | 30        | 4.89%   |
| Skylake       | 28        | 4.56%   |
| Puma          | 28        | 4.56%   |
| Zen 2         | 24        | 3.91%   |
| P6            | 21        | 3.42%   |
| Westmere      | 20        | 3.26%   |
| Core          | 15        | 2.44%   |
| Bonnell       | 15        | 2.44%   |
| Silvermont    | 14        | 2.28%   |
| K10           | 13        | 2.12%   |
| Bobcat        | 13        | 2.12%   |
| Zen 3         | 11        | 1.79%   |
| Goldmont plus | 11        | 1.79%   |
| NetBurst      | 10        | 1.63%   |
| CometLake     | 9         | 1.47%   |
| Zen           | 8         | 1.3%    |
| TigerLake     | 8         | 1.3%    |
| Zen+          | 7         | 1.14%   |
| Goldmont      | 7         | 1.14%   |
| Nehalem       | 6         | 0.98%   |
| Jaguar        | 6         | 0.98%   |
| Piledriver    | 4         | 0.65%   |
| K8 Hammer     | 4         | 0.65%   |
| K10 Llano     | 4         | 0.65%   |
| IceLake       | 4         | 0.65%   |
| Geode         | 3         | 0.49%   |
| Excavator     | 2         | 0.33%   |
| Steamroller   | 1         | 0.16%   |
| K6            | 1         | 0.16%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 342       | 57.58%  |
| AMD                                          | 155       | 26.09%  |
| Nvidia                                       | 66        | 11.11%  |
| Matrox Electronics Systems                   | 18        | 3.03%   |
| ASPEED Technology                            | 9         | 1.52%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.17%   |
| VIA Technologies                             | 1         | 0.17%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.17%   |
| 3DLabs                                       | 1         | 0.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 30        | 4.83%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 25        | 4.03%   |
| Intel HD Graphics 5500                                                                   | 22        | 3.54%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 19        | 3.06%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 18        | 2.9%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 17        | 2.74%   |
| Intel UHD Graphics 620                                                                   | 16        | 2.58%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 16        | 2.58%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 15        | 2.42%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 11        | 1.77%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 11        | 1.77%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 10        | 1.61%   |
| Intel HD Graphics 620                                                                    | 10        | 1.61%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 1.45%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 1.45%   |
| Intel Core Processor Integrated Graphics Controller                                      | 9         | 1.45%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 9         | 1.45%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8         | 1.29%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 8         | 1.29%   |
| Matrox Electronics Systems G200eR2                                                       | 7         | 1.13%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 7         | 1.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 1.13%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 1.13%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 0.97%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 6         | 0.97%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 6         | 0.97%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 5         | 0.81%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 0.81%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 5         | 0.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 4         | 0.64%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 4         | 0.64%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 4         | 0.64%   |
| Intel HD Graphics 6000                                                                   | 4         | 0.64%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4         | 0.64%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 0.64%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 4         | 0.64%   |
| AMD ES1000                                                                               | 4         | 0.64%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 4         | 0.64%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.48%   |
| Nvidia GT218M [NVS 3100M]                                                                | 3         | 0.48%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 260       | 42.21%  |
| 1 x AMD        | 133       | 21.59%  |
| Other          | 67        | 10.88%  |
| 2 x Intel      | 44        | 7.14%   |
| 1 x Nvidia     | 31        | 5.03%   |
| Intel + Nvidia | 28        | 4.55%   |
| 1 x Matrox     | 16        | 2.6%    |
| Intel + AMD    | 11        | 1.79%   |
| 1 x ASPEED     | 9         | 1.46%   |
| AMD + Nvidia   | 6         | 0.97%   |
| 2 x AMD        | 4         | 0.65%   |
| AMD + Matrox   | 2         | 0.32%   |
| 2 x Nvidia     | 1         | 0.16%   |
| 1 x XGI        | 1         | 0.16%   |
| 1 x VIA        | 1         | 0.16%   |
| 1 x SiS        | 1         | 0.16%   |
| 1 x 3DLabs     | 1         | 0.16%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 509       | 82.9%   |
| Unknown | 105       | 17.1%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 612       | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 48        | 13.52%  |
| LG Display              | 46        | 12.96%  |
| BOE                     | 34        | 9.58%   |
| Samsung Electronics     | 29        | 8.17%   |
| Lenovo                  | 23        | 6.48%   |
| Chimei Innolux          | 23        | 6.48%   |
| Philips                 | 22        | 6.2%    |
| Dell                    | 17        | 4.79%   |
| Apple                   | 14        | 3.94%   |
| Goldstar                | 13        | 3.66%   |
| Ancor Communications    | 9         | 2.54%   |
| BenQ                    | 7         | 1.97%   |
| Iiyama                  | 6         | 1.69%   |
| ASUSTek Computer        | 6         | 1.69%   |
| Acer                    | 6         | 1.69%   |
| ViewSonic               | 5         | 1.41%   |
| AOC                     | 5         | 1.41%   |
| Sharp                   | 4         | 1.13%   |
| NEC Computers           | 4         | 1.13%   |
| Hewlett-Packard         | 4         | 1.13%   |
| PANDA                   | 3         | 0.85%   |
| InfoVision              | 3         | 0.85%   |
| Chi Mei Optoelectronics | 3         | 0.85%   |
| MSI                     | 2         | 0.56%   |
| IBM                     | 2         | 0.56%   |
| Eizo                    | 2         | 0.56%   |
| CSO                     | 2         | 0.56%   |
| Vizio                   | 1         | 0.28%   |
| TRU                     | 1         | 0.28%   |
| SHI                     | 1         | 0.28%   |
| Sceptre Tech            | 1         | 0.28%   |
| Quanta Display          | 1         | 0.28%   |
| Panasonic               | 1         | 0.28%   |
| Medion                  | 1         | 0.28%   |
| LTM                     | 1         | 0.28%   |
| LG Philips              | 1         | 0.28%   |
| JDI                     | 1         | 0.28%   |
| HannStar                | 1         | 0.28%   |
| Gigabyte Technology     | 1         | 0.28%   |
| DSC                     | 1         | 0.28%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                    | 12        | 3.35%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 7         | 1.96%   |
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch                  | 6         | 1.68%   |
| LG Display LCD Monitor LGD058B 2560x1440 310x170mm 13.9-inch             | 4         | 1.12%   |
| Samsung Electronics SyncMaster SAM03CF 1280x1024 340x270mm 17.1-inch     | 3         | 0.84%   |
| Philips 170S PHL0839 1280x1024 340x270mm 17.1-inch                       | 3         | 0.84%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch              | 3         | 0.84%   |
| Lenovo LCD Monitor LEN4033 1440x900 300x190mm 14.0-inch                  | 3         | 0.84%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch                  | 3         | 0.84%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch            | 3         | 0.84%   |
| Ancor Communications ASUS VW199 ACI19ED 1440x900 410x260mm 19.1-inch     | 3         | 0.84%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch     | 2         | 0.56%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch             | 2         | 0.56%   |
| LG Display LCD Monitor LGD057E 1920x1080 340x190mm 15.3-inch             | 2         | 0.56%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x170mm 12.2-inch             | 2         | 0.56%   |
| LG Display LCD Monitor LGD045E 1366x768 310x170mm 13.9-inch              | 2         | 0.56%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch             | 2         | 0.56%   |
| LG Display LCD Monitor LGD0418 2560x1440 310x170mm 13.9-inch             | 2         | 0.56%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 2         | 0.56%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch                 | 2         | 0.56%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch                  | 2         | 0.56%   |
| Iiyama PL2779QQ IVM6641 3840x2160 600x330mm 27.0-inch                    | 2         | 0.56%   |
| Iiyama PL2474H IVM6137 1920x1080 520x290mm 23.4-inch                     | 2         | 0.56%   |
| IBM LCD Monitor IBM2887 1680x1050 330x210mm 15.4-inch                    | 2         | 0.56%   |
| Hewlett-Packard LA2405 HWP284B 1920x1200 520x320mm 24.0-inch             | 2         | 0.56%   |
| Eizo EV2450 ENC2530 1920x1080 530x300mm 24.0-inch                        | 2         | 0.56%   |
| Dell UP2715K DEL40B6 848x480 600x340mm 27.2-inch                         | 2         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch          | 2         | 0.56%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 310x170mm 13.9-inch          | 2         | 0.56%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 280x160mm 12.7-inch         | 2         | 0.56%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch          | 2         | 0.56%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 2         | 0.56%   |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                    | 2         | 0.56%   |
| BOE LCD Monitor BOE0900 1920x1080 340x190mm 15.3-inch                    | 2         | 0.56%   |
| BOE LCD Monitor BOE07C8 3840x2160 310x170mm 13.9-inch                    | 2         | 0.56%   |
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                       | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 310x170mm 13.9-inch           | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 310x170mm 13.9-inch           | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO34ED 1920x1080 340x190mm 15.3-inch           | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO2336 2560x1440 310x170mm 13.9-inch           | 2         | 0.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 130       | 37.36%  |
| 1366x768 (WXGA)    | 72        | 20.69%  |
| 1280x1024 (SXGA)   | 19        | 5.46%   |
| 1280x800 (WXGA)    | 18        | 5.17%   |
| 1440x900 (WXGA+)   | 17        | 4.89%   |
| 2560x1440 (QHD)    | 16        | 4.6%    |
| 3840x2160 (4K)     | 15        | 4.31%   |
| 1600x900 (HD+)     | 12        | 3.45%   |
| 1920x1200 (WUXGA)  | 9         | 2.59%   |
| 3440x1440          | 7         | 2.01%   |
| 1680x1050 (WSXGA+) | 5         | 1.44%   |
| 3840x1080          | 3         | 0.86%   |
| 2736x1824          | 2         | 0.57%   |
| 2256x1504          | 2         | 0.57%   |
| 1600x1200          | 2         | 0.57%   |
| 1360x768           | 2         | 0.57%   |
| 1280x854           | 2         | 0.57%   |
| 1024x768 (XGA)     | 2         | 0.57%   |
| 720x1280           | 1         | 0.29%   |
| 3840x2400          | 1         | 0.29%   |
| 3456x2160          | 1         | 0.29%   |
| 3200x1800 (QHD+)   | 1         | 0.29%   |
| 2880x1800          | 1         | 0.29%   |
| 2560x1600          | 1         | 0.29%   |
| 2560x1080          | 1         | 0.29%   |
| 2200x1650          | 1         | 0.29%   |
| 1920x1280          | 1         | 0.29%   |
| 1440x960           | 1         | 0.29%   |
| 1400x1050          | 1         | 0.29%   |
| 1280x768           | 1         | 0.29%   |
| 1024x600           | 1         | 0.29%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 77        | 21.94%  |
| 15      | 62        | 17.66%  |
| 12      | 39        | 11.11%  |
| 24      | 27        | 7.69%   |
| 21      | 20        | 5.7%    |
| 23      | 17        | 4.84%   |
| 17      | 16        | 4.56%   |
| 11      | 16        | 4.56%   |
| 19      | 15        | 4.27%   |
| 14      | 14        | 3.99%   |
| 27      | 12        | 3.42%   |
| 34      | 7         | 1.99%   |
| 31      | 5         | 1.42%   |
| 18      | 5         | 1.42%   |
| 10      | 3         | 0.85%   |
| 54      | 2         | 0.57%   |
| 49      | 2         | 0.57%   |
| 9       | 2         | 0.57%   |
| 48      | 1         | 0.28%   |
| 40      | 1         | 0.28%   |
| 35      | 1         | 0.28%   |
| 28      | 1         | 0.28%   |
| 26      | 1         | 0.28%   |
| 22      | 1         | 0.28%   |
| 20      | 1         | 0.28%   |
| 16      | 1         | 0.28%   |
| 6       | 1         | 0.28%   |
| Unknown | 1         | 0.28%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 131       | 37.32%  |
| 201-300     | 93        | 26.5%   |
| 501-600     | 55        | 15.67%  |
| 401-500     | 35        | 9.97%   |
| 351-400     | 12        | 3.42%   |
| 701-800     | 7         | 1.99%   |
| 601-700     | 7         | 1.99%   |
| 1001-1500   | 5         | 1.42%   |
| 101-200     | 3         | 0.85%   |
| 801-900     | 2         | 0.57%   |
| Unknown     | 1         | 0.28%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 244       | 71.55%  |
| 16/10 | 49        | 14.37%  |
| 5/4   | 19        | 5.57%   |
| 3/2   | 12        | 3.52%   |
| 21/9  | 8         | 2.35%   |
| 4/3   | 6         | 1.76%   |
| 32/9  | 3         | 0.88%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 78        | 22.41%  |
| 201-250        | 51        | 14.66%  |
| 91-100         | 50        | 14.37%  |
| 61-70          | 39        | 11.21%  |
| 151-200        | 18        | 5.17%   |
| 51-60          | 17        | 4.89%   |
| 141-150        | 16        | 4.6%    |
| 351-500        | 14        | 4.02%   |
| 101-110        | 14        | 4.02%   |
| 301-350        | 13        | 3.74%   |
| 71-80          | 11        | 3.16%   |
| 251-300        | 10        | 2.87%   |
| 121-130        | 5         | 1.44%   |
| 501-1000       | 4         | 1.15%   |
| 41-50          | 3         | 0.86%   |
| More than 1000 | 2         | 0.57%   |
| 1-40           | 2         | 0.57%   |
| Unknown        | 1         | 0.29%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 132       | 37.82%  |
| 51-100        | 90        | 25.79%  |
| 101-120       | 75        | 21.49%  |
| 161-240       | 35        | 10.03%  |
| More than 240 | 12        | 3.44%   |
| 1-50          | 4         | 1.15%   |
| Unknown       | 1         | 0.29%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 399       | 64.35%  |
| 0     | 197       | 31.77%  |
| 2     | 22        | 3.55%   |
| 3     | 2         | 0.32%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 371       | 46.03%  |
| Realtek Semiconductor             | 220       | 27.3%   |
| Qualcomm Atheros                  | 57        | 7.07%   |
| Broadcom                          | 53        | 6.58%   |
| Qualcomm Atheros Communications   | 10        | 1.24%   |
| TP-Link                           | 8         | 0.99%   |
| Marvell Technology Group          | 8         | 0.99%   |
| Apple                             | 8         | 0.99%   |
| Ericsson Business Mobile Networks | 7         | 0.87%   |
| Edimax Technology                 | 6         | 0.74%   |
| Sierra Wireless                   | 5         | 0.62%   |
| MediaTek                          | 5         | 0.62%   |
| VIA Technologies                  | 4         | 0.5%    |
| U-Blox                            | 4         | 0.5%    |
| Ralink                            | 4         | 0.5%    |
| Ralink Technology                 | 3         | 0.37%   |
| Nvidia                            | 3         | 0.37%   |
| D-Link System                     | 3         | 0.37%   |
| 3Com                              | 3         | 0.37%   |
| Oracle/SUN                        | 2         | 0.25%   |
| ASUSTek Computer                  | 2         | 0.25%   |
| Xiaomi                            | 1         | 0.12%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.12%   |
| Samsung Electronics               | 1         | 0.12%   |
| Qcom                              | 1         | 0.12%   |
| National Semiconductor            | 1         | 0.12%   |
| Microsoft                         | 1         | 0.12%   |
| Micro Star International          | 1         | 0.12%   |
| LG Electronics                    | 1         | 0.12%   |
| Huawei Technologies               | 1         | 0.12%   |
| Hewlett-Packard                   | 1         | 0.12%   |
| Google                            | 1         | 0.12%   |
| Fibocom                           | 1         | 0.12%   |
| Emulex                            | 1         | 0.12%   |
| Dell                              | 1         | 0.12%   |
| Davicom Semiconductor             | 1         | 0.12%   |
| D-Link                            | 1         | 0.12%   |
| AVM                               | 1         | 0.12%   |
| Aquantia                          | 1         | 0.12%   |
| AMD                               | 1         | 0.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 159       | 15.62%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 32        | 3.14%   |
| Intel I211 Gigabit Network Connection                                   | 27        | 2.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 27        | 2.65%   |
| Intel Wi-Fi 6 AX200                                                     | 25        | 2.46%   |
| Intel Wireless 8265 / 8275                                              | 24        | 2.36%   |
| Intel I210 Gigabit Network Connection                                   | 23        | 2.26%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 22        | 2.16%   |
| Intel Wireless 7265                                                     | 21        | 2.06%   |
| Intel Wireless 7260                                                     | 20        | 1.96%   |
| Intel Wireless 8260                                                     | 17        | 1.67%   |
| Intel 82567LM Gigabit Network Connection                                | 16        | 1.57%   |
| Intel Ethernet Connection I219-LM                                       | 14        | 1.38%   |
| Intel 82574L Gigabit Network Connection                                 | 13        | 1.28%   |
| Intel Ethernet Connection (3) I218-LM                                   | 12        | 1.18%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 11        | 1.08%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 11        | 1.08%   |
| Realtek RTL8125 2.5GbE Controller                                       | 10        | 0.98%   |
| Intel I350 Gigabit Network Connection                                   | 10        | 0.98%   |
| Intel Ethernet Connection I217-LM                                       | 10        | 0.98%   |
| Intel 82577LM Gigabit Network Connection                                | 10        | 0.98%   |
| Intel Wi-Fi 6 AX201                                                     | 9         | 0.88%   |
| Intel Ultimate N WiFi Link 5300                                         | 9         | 0.88%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter            | 9         | 0.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 0.79%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 8         | 0.79%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 7         | 0.69%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 7         | 0.69%   |
| Qualcomm Atheros AR9271 802.11n                                         | 7         | 0.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 0.69%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 7         | 0.69%   |
| Intel Ethernet Connection (4) I219-V                                    | 7         | 0.69%   |
| Intel Ethernet Connection (4) I219-LM                                   | 7         | 0.69%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 6         | 0.59%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 0.59%   |
| Intel Ethernet Connection I218-LM                                       | 6         | 0.59%   |
| Intel Centrino Advanced-N 6200                                          | 6         | 0.59%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 6         | 0.59%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                         | 6         | 0.59%   |
| Intel Wireless 3165                                                     | 5         | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 246       | 59.42%  |
| Qualcomm Atheros                | 49        | 11.84%  |
| Realtek Semiconductor           | 43        | 10.39%  |
| Broadcom                        | 28        | 6.76%   |
| Qualcomm Atheros Communications | 10        | 2.42%   |
| TP-Link                         | 8         | 1.93%   |
| Edimax Technology               | 6         | 1.45%   |
| MediaTek                        | 5         | 1.21%   |
| Sierra Wireless                 | 4         | 0.97%   |
| Ralink                          | 4         | 0.97%   |
| Ralink Technology               | 3         | 0.72%   |
| D-Link System                   | 2         | 0.48%   |
| ASUSTek Computer                | 2         | 0.48%   |
| Qcom                            | 1         | 0.24%   |
| Micro Star International        | 1         | 0.24%   |
| Dell                            | 1         | 0.24%   |
| D-Link                          | 1         | 0.24%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 27        | 6.43%   |
| Intel Wi-Fi 6 AX200                                                     | 25        | 5.95%   |
| Intel Wireless 8265 / 8275                                              | 24        | 5.71%   |
| Intel Wireless 7265                                                     | 21        | 5%      |
| Intel Wireless 7260                                                     | 20        | 4.76%   |
| Intel Wireless 8260                                                     | 17        | 4.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 11        | 2.62%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 11        | 2.62%   |
| Intel Wi-Fi 6 AX201                                                     | 9         | 2.14%   |
| Intel Ultimate N WiFi Link 5300                                         | 9         | 2.14%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter            | 9         | 2.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 1.9%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 7         | 1.67%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 7         | 1.67%   |
| Qualcomm Atheros AR9271 802.11n                                         | 7         | 1.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 1.67%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 7         | 1.67%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 6         | 1.43%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 1.43%   |
| Intel Centrino Advanced-N 6200                                          | 6         | 1.43%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 6         | 1.43%   |
| Intel Wireless 3165                                                     | 5         | 1.19%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 1.19%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 0.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 0.95%   |
| Intel Wireless-AC 9260                                                  | 4         | 0.95%   |
| Intel Wireless 3160                                                     | 4         | 0.95%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 4         | 0.95%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection               | 4         | 0.95%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 0.95%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 0.95%   |
| Intel Centrino Wireless-N 2230                                          | 4         | 0.95%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 4         | 0.95%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 4         | 0.95%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 4         | 0.95%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 3         | 0.71%   |
| Sierra Wireless EM7455                                                  | 3         | 0.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 0.71%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 3         | 0.71%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 3         | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 255       | 47.05%  |
| Realtek Semiconductor            | 204       | 37.64%  |
| Broadcom                         | 32        | 5.9%    |
| Qualcomm Atheros                 | 14        | 2.58%   |
| Marvell Technology Group         | 8         | 1.48%   |
| Apple                            | 6         | 1.11%   |
| VIA Technologies                 | 4         | 0.74%   |
| Nvidia                           | 3         | 0.55%   |
| 3Com                             | 3         | 0.55%   |
| Oracle/SUN                       | 2         | 0.37%   |
| Xiaomi                           | 1         | 0.18%   |
| Silicon Integrated Systems [SiS] | 1         | 0.18%   |
| Samsung Electronics              | 1         | 0.18%   |
| National Semiconductor           | 1         | 0.18%   |
| Microsoft                        | 1         | 0.18%   |
| Google                           | 1         | 0.18%   |
| Emulex                           | 1         | 0.18%   |
| Davicom Semiconductor            | 1         | 0.18%   |
| D-Link System                    | 1         | 0.18%   |
| Aquantia                         | 1         | 0.18%   |
| Accton Technology                | 1         | 0.18%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 159       | 28.09%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 32        | 5.65%   |
| Intel I211 Gigabit Network Connection                             | 27        | 4.77%   |
| Intel I210 Gigabit Network Connection                             | 23        | 4.06%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 22        | 3.89%   |
| Intel 82567LM Gigabit Network Connection                          | 16        | 2.83%   |
| Intel Ethernet Connection I219-LM                                 | 14        | 2.47%   |
| Intel 82574L Gigabit Network Connection                           | 13        | 2.3%    |
| Intel Ethernet Connection (3) I218-LM                             | 12        | 2.12%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10        | 1.77%   |
| Intel I350 Gigabit Network Connection                             | 10        | 1.77%   |
| Intel Ethernet Connection I217-LM                                 | 10        | 1.77%   |
| Intel 82577LM Gigabit Network Connection                          | 10        | 1.77%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 8         | 1.41%   |
| Intel Ethernet Connection (4) I219-V                              | 7         | 1.24%   |
| Intel Ethernet Connection (4) I219-LM                             | 7         | 1.24%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 1.06%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                   | 6         | 1.06%   |
| Intel Ethernet Connection (6) I219-V                              | 5         | 0.88%   |
| Intel Ethernet Connection (2) I219-LM                             | 5         | 0.88%   |
| Intel 82573L Gigabit Ethernet Controller                          | 5         | 0.88%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4         | 0.71%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 4         | 0.71%   |
| Intel Ethernet Controller I225-V                                  | 4         | 0.71%   |
| Intel Ethernet Connection (7) I219-LM                             | 4         | 0.71%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 0.71%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 4         | 0.71%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 0.53%   |
| Nvidia MCP79 Ethernet                                             | 3         | 0.53%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 3         | 0.53%   |
| Intel Ethernet Connection (3) I218-V                              | 3         | 0.53%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.53%   |
| Intel Ethernet Connection (10) I219-V                             | 3         | 0.53%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 3         | 0.53%   |
| Intel 82566MM Gigabit Network Connection                          | 3         | 0.53%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 3         | 0.53%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 3         | 0.53%   |
| VIA VT6105M [Rhine-III]                                           | 2         | 0.35%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2         | 0.35%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 525       | 56.15%  |
| WiFi     | 378       | 40.43%  |
| Modem    | 19        | 2.03%   |
| Unknown  | 13        | 1.39%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 288       | 52.94%  |
| WiFi     | 256       | 47.06%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 317       | 51.71%  |
| 1     | 181       | 29.53%  |
| 3     | 41        | 6.69%   |
| 4     | 31        | 5.06%   |
| 0     | 31        | 5.06%   |
| 5     | 4         | 0.65%   |
| 8     | 3         | 0.49%   |
| 7     | 2         | 0.33%   |
| 6     | 2         | 0.33%   |
| 12    | 1         | 0.16%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 609       | 99.35%  |
| Yes  | 4         | 0.65%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 136       | 55.06%  |
| Broadcom                        | 31        | 12.55%  |
| Apple                           | 22        | 8.91%   |
| IMC Networks                    | 11        | 4.45%   |
| Realtek Semiconductor           | 10        | 4.05%   |
| Foxconn / Hon Hai               | 9         | 3.64%   |
| Qualcomm Atheros Communications | 7         | 2.83%   |
| Alps Electric                   | 7         | 2.83%   |
| Cambridge Silicon Radio         | 4         | 1.62%   |
| Taiyo Yuden                     | 2         | 0.81%   |
| Hewlett-Packard                 | 2         | 0.81%   |
| ASUSTek Computer                | 2         | 0.81%   |
| Skylight Digital                | 1         | 0.4%    |
| Ralink                          | 1         | 0.4%    |
| Lite-On Technology              | 1         | 0.4%    |
| Creative Technology             | 1         | 0.4%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 66        | 26.72%  |
| Intel AX200 Bluetooth                                    | 22        | 8.91%   |
| Intel AX201 Bluetooth                                    | 17        | 6.88%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 12        | 4.86%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]               | 9         | 3.64%   |
| Broadcom BCM2045B (BDC-2.1)                              | 9         | 3.64%   |
| Apple Broadcom Built-in Bluetooth                        | 9         | 3.64%   |
| Apple Bluetooth Host Controller                          | 8         | 3.24%   |
| Realtek Bluetooth Adapter                                | 7         | 2.83%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 6         | 2.43%   |
| Intel AX210 Bluetooth                                    | 6         | 2.43%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]       | 6         | 2.43%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                     | 5         | 2.02%   |
| Alps Electric UGTZ4 Bluetooth                            | 5         | 2.02%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                    | 4         | 1.62%   |
| Intel Wireless-AC 3168 Bluetooth                         | 4         | 1.62%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 4         | 1.62%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip     | 3         | 1.21%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)                  | 2         | 0.81%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 2         | 0.81%   |
| IMC Networks Realtek Bluetooth Adapter                   | 2         | 0.81%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1              | 2         | 0.81%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS         | 2         | 0.81%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011]   | 2         | 0.81%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]            | 2         | 0.81%   |
| Foxconn / Hon Hai RZ616 Bluetooth Adapter                | 2         | 0.81%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device | 2         | 0.81%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 2         | 0.81%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]         | 2         | 0.81%   |
| Alps Electric BCM2046 Bluetooth Device                   | 2         | 0.81%   |
| Skylight Digital Realtek Bluetooth Adapter               | 1         | 0.4%    |
| Realtek  Bluetooth 4.2 Adapter                           | 1         | 0.4%    |
| Realtek Bluetooth 4.2 Adapter                            | 1         | 0.4%    |
| Realtek Bluetooth 4.0 Adapter                            | 1         | 0.4%    |
| Ralink RT3290 Bluetooth                                  | 1         | 0.4%    |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                   | 1         | 0.4%    |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE      | 1         | 0.4%    |
| Qualcomm Atheros Bluetooth                               | 1         | 0.4%    |
| Lite-On Atheros AR3012 Bluetooth                         | 1         | 0.4%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter         | 1         | 0.4%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 373       | 65.1%   |
| AMD                                          | 127       | 22.16%  |
| Nvidia                                       | 39        | 6.81%   |
| C-Media Electronics                          | 9         | 1.57%   |
| VIA Technologies                             | 4         | 0.7%    |
| Logitech                                     | 3         | 0.52%   |
| ULi Electronics                              | 2         | 0.35%   |
| JMTek                                        | 2         | 0.35%   |
| Generalplus Technology                       | 2         | 0.35%   |
| ESS Technology                               | 2         | 0.35%   |
| Creative Labs                                | 2         | 0.35%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.17%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.17%   |
| Texas Instruments                            | 1         | 0.17%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.17%   |
| Lenovo                                       | 1         | 0.17%   |
| Elgato Systems                               | 1         | 0.17%   |
| Dell                                         | 1         | 0.17%   |
| Blue Microphones                             | 1         | 0.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                   | 50        | 7.01%   |
| AMD Family 17h/19h HD Audio Controller                                            | 36        | 5.05%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 34        | 4.77%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 30        | 4.21%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 28        | 3.93%   |
| Intel Broadwell-U Audio Controller                                                | 28        | 3.93%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 27        | 3.79%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 23        | 3.23%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 21        | 2.95%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 18        | 2.52%   |
| AMD Starship/Matisse HD Audio Controller                                          | 17        | 2.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 16        | 2.24%   |
| Intel Haswell-ULT HD Audio Controller                                             | 16        | 2.24%   |
| Intel 8 Series HD Audio Controller                                                | 16        | 2.24%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 16        | 2.24%   |
| AMD FCH Azalia Controller                                                         | 15        | 2.1%    |
| Intel Cannon Lake PCH cAVS                                                        | 14        | 1.96%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 14        | 1.96%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 11        | 1.54%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 10        | 1.4%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 9         | 1.26%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 9         | 1.26%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 9         | 1.26%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 8         | 1.12%   |
| AMD Kabini HDMI/DP Audio                                                          | 8         | 1.12%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 7         | 0.98%   |
| AMD Navi 10 HDMI Audio                                                            | 7         | 0.98%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 7         | 0.98%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 6         | 0.84%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 6         | 0.84%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 6         | 0.84%   |
| AMD Rembrandt Radeon High Definition Audio Controller                             | 6         | 0.84%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 6         | 0.84%   |
| Intel Comet Lake PCH-V cAVS                                                       | 5         | 0.7%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                 | 5         | 0.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 5         | 0.7%    |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                      | 5         | 0.7%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 5         | 0.7%    |
| Nvidia MCP61 High Definition Audio                                                | 4         | 0.56%   |
| Nvidia High Definition Audio Controller                                           | 4         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 24        | 25.26%  |
| Samsung Electronics | 22        | 23.16%  |
| SK hynix            | 11        | 11.58%  |
| Kingston            | 8         | 8.42%   |
| Unknown             | 7         | 7.37%   |
| Micron Technology   | 5         | 5.26%   |
| Elpida              | 4         | 4.21%   |
| Crucial             | 4         | 4.21%   |
| Transcend           | 2         | 2.11%   |
| Ramaxel Technology  | 2         | 2.11%   |
| Corsair             | 2         | 2.11%   |
| A-DATA Technology   | 2         | 2.11%   |
| Nanya Technology    | 1         | 1.05%   |
| Hewlett-Packard     | 1         | 1.05%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Unknown                                                 | 7         | 6.6%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s   | 5         | 4.72%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s             | 3         | 2.83%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s       | 3         | 2.83%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s          | 2         | 1.89%   |
| Unknown RAM Module 1GB SODIMM DDR                       | 2         | 1.89%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 2         | 1.89%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s   | 2         | 1.89%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s   | 2         | 1.89%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s   | 2         | 1.89%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s   | 2         | 1.89%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s   | 2         | 1.89%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s   | 2         | 1.89%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 2400MT/s     | 2         | 1.89%   |
| Crucial RAM CT8G3S1339M 8GB SODIMM DDR3 1333MT/s        | 2         | 1.89%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s | 2         | 1.89%   |
| Unknown RAM Module 512MB SODIMM SDRAM                   | 1         | 0.94%   |
| Unknown RAM Module 512MB SODIMM DDR                     | 1         | 0.94%   |
| Unknown RAM Module 512MB DIMM SDRAM                     | 1         | 0.94%   |
| Unknown RAM Module 512MB DIMM DDR 400MT/s               | 1         | 0.94%   |
| Unknown RAM Module 512MB DIMM 400MT/s                   | 1         | 0.94%   |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s             | 1         | 0.94%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s              | 1         | 0.94%   |
| Unknown RAM Module 2GB DIMM DDR3 1332MT/s               | 1         | 0.94%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                | 1         | 0.94%   |
| Unknown RAM Module 256MB SODIMM DRAM                    | 1         | 0.94%   |
| Unknown RAM Module 256MB DIMM 333MT/s                   | 1         | 0.94%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s          | 1         | 0.94%   |
| Unknown RAM Module 2048MB SODIMM DDR2                   | 1         | 0.94%   |
| Unknown RAM Module 2048MB DIMM DDR2 266MT/s             | 1         | 0.94%   |
| Unknown RAM Module 1GB SODIMM DDR2                      | 1         | 0.94%   |
| Unknown RAM Module 1GB DIMM 400MT/s                     | 1         | 0.94%   |
| Unknown RAM Module 128MB SODIMM DRAM                    | 1         | 0.94%   |
| Unknown RAM Module 1024MB SODIMM DDR                    | 1         | 0.94%   |
| Unknown RAM Module 1024MB DIMM DDR                      | 1         | 0.94%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                  | 1         | 0.94%   |
| Transcend RAM TS1GSK64W6H 8GB DIMM DDR3 1600MT/s        | 1         | 0.94%   |
| Transcend RAM TS128MLQ64V6J 1GB DIMM DDR2 667MT/s       | 1         | 0.94%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s   | 1         | 0.94%   |
| SK hynix RAM HYMP112U64CP8-Y5 1GB DIMM DDR2 667MT/s     | 1         | 0.94%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 37        | 45.12%  |
| DDR4    | 17        | 20.73%  |
| DDR2    | 11        | 13.41%  |
| DDR     | 5         | 6.1%    |
| SDRAM   | 4         | 4.88%   |
| Unknown | 4         | 4.88%   |
| DRAM    | 2         | 2.44%   |
| LPDDR3  | 1         | 1.22%   |
| DDR5    | 1         | 1.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 59        | 71.08%  |
| DIMM   | 23        | 27.71%  |
| Chip   | 1         | 1.2%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 26        | 27.37%  |
| 8192  | 20        | 21.05%  |
| 2048  | 18        | 18.95%  |
| 1024  | 13        | 13.68%  |
| 512   | 6         | 6.32%   |
| 16384 | 5         | 5.26%   |
| 32768 | 4         | 4.21%   |
| 256   | 2         | 2.11%   |
| 128   | 1         | 1.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 20        | 22.47%  |
| Unknown | 13        | 14.61%  |
| 1333    | 10        | 11.24%  |
| 1334    | 7         | 7.87%   |
| 2400    | 6         | 6.74%   |
| 3200    | 4         | 4.49%   |
| 1067    | 4         | 4.49%   |
| 800     | 4         | 4.49%   |
| 667     | 4         | 4.49%   |
| 2667    | 3         | 3.37%   |
| 400     | 3         | 3.37%   |
| 2133    | 2         | 2.25%   |
| 266     | 2         | 2.25%   |
| 4800    | 1         | 1.12%   |
| 3000    | 1         | 1.12%   |
| 2666    | 1         | 1.12%   |
| 1867    | 1         | 1.12%   |
| 1332    | 1         | 1.12%   |
| 533     | 1         | 1.12%   |
| 333     | 1         | 1.12%   |

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
| Chicony Electronics                    | 67        | 32.21%  |
| Bison Electronics                      | 26        | 12.5%   |
| IMC Networks                           | 19        | 9.13%   |
| Realtek Semiconductor                  | 14        | 6.73%   |
| Microdia                               | 12        | 5.77%   |
| Lite-On Technology                     | 12        | 5.77%   |
| Lenovo                                 | 6         | 2.88%   |
| Apple                                  | 6         | 2.88%   |
| Sunplus Innovation Technology          | 5         | 2.4%    |
| Logitech                               | 5         | 2.4%    |
| Cheng Uei Precision Industry (Foxlink) | 5         | 2.4%    |
| Ricoh                                  | 4         | 1.92%   |
| Quanta                                 | 4         | 1.92%   |
| Syntek                                 | 3         | 1.44%   |
| Suyin                                  | 3         | 1.44%   |
| Silicon Motion                         | 3         | 1.44%   |
| Alcor Micro                            | 3         | 1.44%   |
| Tripath Technology                     | 2         | 0.96%   |
| Luxvisions Innotech Limited            | 2         | 0.96%   |
| Z-Star Microelectronics                | 1         | 0.48%   |
| SunplusIT                              | 1         | 0.48%   |
| Jiangxi Shinetech Optical              | 1         | 0.48%   |
| Genesys Logic                          | 1         | 0.48%   |
| Generalplus Technology                 | 1         | 0.48%   |
| Denron                                 | 1         | 0.48%   |
| ALi                                    | 1         | 0.48%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 27        | 12.8%   |
| Lite-On Integrated Camera                                                  | 11        | 5.21%   |
| Bison Integrated Camera                                                    | 11        | 5.21%   |
| IMC Networks Integrated Camera                                             | 9         | 4.27%   |
| Chicony Integrated Camera [ThinkPad]                                       | 7         | 3.32%   |
| Chicony Lenovo Integrated Camera (0.3MP)                                   | 5         | 2.37%   |
| Realtek Integrated_Webcam_HD                                               | 4         | 1.9%    |
| Microdia Integrated_Webcam_HD                                              | 4         | 1.9%    |
| Bison SunplusIT Integrated Camera                                          | 4         | 1.9%    |
| Lenovo Integrated Webcam [R5U877]                                          | 3         | 1.42%   |
| Lenovo Integrated Webcam                                                   | 3         | 1.42%   |
| Chicony Integrated IR Camera                                               | 3         | 1.42%   |
| Chicony Integrated Camera (1280x720@30)                                    | 3         | 1.42%   |
| Tripath USB Camera                                                         | 2         | 0.95%   |
| Syntek Lenovo EasyCamera                                                   | 2         | 0.95%   |
| Realtek USB 2.0 Webcam                                                     | 2         | 0.95%   |
| Realtek Integrated Webcam HD                                               | 2         | 0.95%   |
| Microdia USB 2.0 Camera                                                    | 2         | 0.95%   |
| Microdia Integrated Webcam                                                 | 2         | 0.95%   |
| IMC Networks Realtek DMFT RGB                                              | 2         | 0.95%   |
| Chicony VGA Webcam                                                         | 2         | 0.95%   |
| Chicony ThinkPad T490 Webcam                                               | 2         | 0.95%   |
| Chicony thinkpad t430s camera                                              | 2         | 0.95%   |
| Chicony Sonix ST50220 USB Video Camera                                     | 2         | 0.95%   |
| Chicony FJ Camera                                                          | 2         | 0.95%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 2         | 0.95%   |
| Bison USB HD Webcam                                                        | 2         | 0.95%   |
| Bison Lenovo Integrated Webcam                                             | 2         | 0.95%   |
| Bison Lenovo EasyCamera                                                    | 2         | 0.95%   |
| Bison EasyCamera                                                           | 2         | 0.95%   |
| Apple FaceTime HD Camera (Built-in)                                        | 2         | 0.95%   |
| Apple FaceTime HD Camera                                                   | 2         | 0.95%   |
| Apple FaceTime Camera                                                      | 2         | 0.95%   |
| Z-Star Integrated Camera                                                   | 1         | 0.47%   |
| Syntek EasyCamera                                                          | 1         | 0.47%   |
| Suyin Asus Integrated Webcam                                               | 1         | 0.47%   |
| Suyin Acer/Lenovo Webcam [CN0316]                                          | 1         | 0.47%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)                | 1         | 0.47%   |
| SunplusIT USB camera                                                       | 1         | 0.47%   |
| Sunplus Integrated_Webcam_FHD                                              | 1         | 0.47%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 24        | 30.38%  |
| Synaptics                  | 14        | 17.72%  |
| Upek                       | 12        | 15.19%  |
| AuthenTec                  | 11        | 13.92%  |
| STMicroelectronics         | 9         | 11.39%  |
| Shenzhen Goodix Technology | 5         | 6.33%   |
| Elan Microelectronics      | 2         | 2.53%   |
| Samsung Electronics        | 1         | 1.27%   |
| LighTuning Technology      | 1         | 1.27%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor             | 15        | 18.99%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 12        | 15.19%  |
| STMicroelectronics Fingerprint Reader                    | 9         | 11.39%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 5         | 6.33%   |
| AuthenTec AES2810                                        | 5         | 6.33%   |
| AuthenTec AES2501 Fingerprint Sensor                     | 5         | 6.33%   |
| Shenzhen Goodix Fingerprint Reader                       | 4         | 5.06%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor        | 3         | 3.8%    |
| Validity Sensors Synaptics WBDI                          | 3         | 3.8%    |
| Synaptics WBDI                                           | 3         | 3.8%    |
| Validity Sensors VFS5011 Fingerprint Reader              | 2         | 2.53%   |
| Synaptics Metallica MIS Touch Fingerprint Reader         | 2         | 2.53%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 2.53%   |
| Elan Fingerprint Sensor                                  | 2         | 2.53%   |
| Validity Sensors VFS451 Fingerprint Reader               | 1         | 1.27%   |
| Synaptics UWP WBDI Device                                | 1         | 1.27%   |
| Synaptics Metallica MOH Touch Fingerprint Reader         | 1         | 1.27%   |
| Shenzhen Goodix Fingerprint Reader SGX                   | 1         | 1.27%   |
| Samsung CanvasBio Fingerprint Reader                     | 1         | 1.27%   |
| LighTuning ES603 Swipe Fingerprint Sensor                | 1         | 1.27%   |
| AuthenTec AES2660                                        | 1         | 1.27%   |

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
| 1     | 256       | 41.16%  |
| 0     | 180       | 28.94%  |
| 2     | 129       | 20.74%  |
| 3     | 29        | 4.66%   |
| 4     | 14        | 2.25%   |
| 5     | 7         | 1.13%   |
| 7     | 3         | 0.48%   |
| 6     | 3         | 0.48%   |
| 8     | 1         | 0.16%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 319       | 47.97%  |
| Graphics card            | 115       | 17.29%  |
| Net/wireless             | 75        | 11.28%  |
| Firewire controller      | 56        | 8.42%   |
| Sound                    | 24        | 3.61%   |
| Storage/ata              | 21        | 3.16%   |
| Net/ethernet             | 16        | 2.41%   |
| Network                  | 13        | 1.95%   |
| Modem                    | 10        | 1.5%    |
| Storage                  | 6         | 0.9%    |
| Storage/ide              | 4         | 0.6%    |
| Card reader              | 3         | 0.45%   |
| Storage/raid             | 1         | 0.15%   |
| Storage/nvme             | 1         | 0.15%   |
| Bluetooth                | 1         | 0.15%   |

