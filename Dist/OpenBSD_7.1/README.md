OpenBSD 7.1 - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for OpenBSD 7.1.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/OpenBSD_7.1/Desktop/README.md) and [notebooks](/Dist/OpenBSD_7.1/Notebook/README.md).

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

Total: 98

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T420s 4174DL7      | Notebook    | [82d774e711](https://bsd-hardware.info/?probe=82d774e711) | Oct 26, 2022 |
| ASUSTek       | K53TA                       | Notebook    | [521283b723](https://bsd-hardware.info/?probe=521283b723) | Oct 22, 2022 |
| ASRock        | Q1900M                      | Desktop     | [7d0380e2d0](https://bsd-hardware.info/?probe=7d0380e2d0) | Oct 15, 2022 |
| HP            | 260 G3 DM                   | Desktop     | [3ad5292d71](https://bsd-hardware.info/?probe=3ad5292d71) | Oct 13, 2022 |
| HP            | Compaq nw8440 (RND39ET)     | Desktop     | [55bef385e3](https://bsd-hardware.info/?probe=55bef385e3) | Oct 13, 2022 |
| Clevo         | R130T                       | Desktop     | [6f8a6bf77c](https://bsd-hardware.info/?probe=6f8a6bf77c) | Oct 10, 2022 |
| Soekris En... | net6501                     | Desktop     | [1cb23f6bda](https://bsd-hardware.info/?probe=1cb23f6bda) | Oct 08, 2022 |
| Soekris En... | net6501                     | Desktop     | [03ee772b1f](https://bsd-hardware.info/?probe=03ee772b1f) | Oct 08, 2022 |
| Lenovo        | ThinkPad T60 2613CTO        | Desktop     | [cb649b809c](https://bsd-hardware.info/?probe=cb649b809c) | Oct 04, 2022 |
| Tactus        | GeoFlex 110                 | Notebook    | [0b93b5f915](https://bsd-hardware.info/?probe=0b93b5f915) | Sep 28, 2022 |
| ASUSTek       | All Series                  | Desktop     | [ab3b339cf0](https://bsd-hardware.info/?probe=ab3b339cf0) | Sep 24, 2022 |
| Toshiba       | Satellite BE96-F299         | Notebook    | [15b93c9f4b](https://bsd-hardware.info/?probe=15b93c9f4b) | Sep 21, 2022 |
| Toshiba       | Satellite BE96-F299         | Notebook    | [9beae1547d](https://bsd-hardware.info/?probe=9beae1547d) | Sep 21, 2022 |
| Gigabyte      | H81M-S1                     | Desktop     | [fe9eecb935](https://bsd-hardware.info/?probe=fe9eecb935) | Sep 18, 2022 |
| CncTion       | N5105-4L                    | Desktop     | [2a34dc3fe0](https://bsd-hardware.info/?probe=2a34dc3fe0) | Sep 05, 2022 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [21fed03fa2](https://bsd-hardware.info/?probe=21fed03fa2) | Aug 24, 2022 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [48210e4d2a](https://bsd-hardware.info/?probe=48210e4d2a) | Aug 24, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [7576399c3c](https://bsd-hardware.info/?probe=7576399c3c) | Aug 20, 2022 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | Notebook    | [2e7d570822](https://bsd-hardware.info/?probe=2e7d570822) | Aug 20, 2022 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | Notebook    | [7afa139f4f](https://bsd-hardware.info/?probe=7afa139f4f) | Aug 20, 2022 |
| Fujitsu       | PRIMERGY RX200 S6           | Desktop     | [9267873961](https://bsd-hardware.info/?probe=9267873961) | Aug 13, 2022 |
| Alienware     | m15 R4                      | Notebook    | [769c5c43f3](https://bsd-hardware.info/?probe=769c5c43f3) | Aug 13, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [1d342196fb](https://bsd-hardware.info/?probe=1d342196fb) | Aug 08, 2022 |
| Biostar       | TA880GU3+                   | Desktop     | [8b0c8541b3](https://bsd-hardware.info/?probe=8b0c8541b3) | Aug 06, 2022 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [77f61a8711](https://bsd-hardware.info/?probe=77f61a8711) | Aug 01, 2022 |
| Intel         | NUC5PPYB                    | Mini pc     | [d9a4a9745d](https://bsd-hardware.info/?probe=d9a4a9745d) | Jul 28, 2022 |
| Gigabyte      | H87-HD3                     | Desktop     | [e6a9b0dd8b](https://bsd-hardware.info/?probe=e6a9b0dd8b) | Jul 25, 2022 |
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
| Lenovo        | ThinkPad X200 745969G       | Notebook    | [086a58a68f](https://bsd-hardware.info/?probe=086a58a68f) | Mar 24, 2022 |
| Lenovo        | ThinkCentre M93p 10AAS25... | Desktop     | [32d27b9404](https://bsd-hardware.info/?probe=32d27b9404) | Mar 19, 2022 |
| Lenovo        | ThinkCentre M93p 10AAS25... | Desktop     | [7361628ed9](https://bsd-hardware.info/?probe=7361628ed9) | Mar 19, 2022 |
| Lenovo        | ThinkPad X200 745969G       | Notebook    | [e973d1e806](https://bsd-hardware.info/?probe=e973d1e806) | Mar 18, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [ed0add65a3](https://bsd-hardware.info/?probe=ed0add65a3) | Mar 14, 2022 |
| Lenovo        | Yoga 330-11IGM 81A6         | Notebook    | [621ae0501b](https://bsd-hardware.info/?probe=621ae0501b) | Mar 10, 2022 |
| Unknown       | LeMaker Banana Pi           | Desktop     | [37e7d1912b](https://bsd-hardware.info/?probe=37e7d1912b) | Mar 05, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [4bc5573cf5](https://bsd-hardware.info/?probe=4bc5573cf5) | Mar 02, 2022 |
| Lenovo        | ThinkPad X200 745969G       | Notebook    | [a4341268d0](https://bsd-hardware.info/?probe=a4341268d0) | Feb 23, 2022 |
| Acer          | Aspire A114-33              | Notebook    | [62f4e0a060](https://bsd-hardware.info/?probe=62f4e0a060) | Feb 21, 2022 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 77        | 85.56%  |
| i386  | 7         | 7.78%   |
| arm64 | 5         | 5.56%   |
| armv7 | 1         | 1.11%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 73        | 81.11%  |
| XFCE         | 9         | 10%     |
| fvwm         | 5         | 5.56%   |
| MATE         | 1         | 1.11%   |
| GNOME        | 1         | 1.11%   |
| Console      | 1         | 1.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 70        | 77.78%  |
| Console | 20        | 22.22%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 90        | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 76        | 83.52%  |
| ru_RU   | 9         | 9.89%   |
| fr_FR   | 2         | 2.2%    |
| pl_PL   | 1         | 1.1%    |
| en_US   | 1         | 1.1%    |
| en_GB   | 1         | 1.1%    |
| C       | 1         | 1.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 46        | 51.11%  |
| BIOS | 44        | 48.89%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ffs  | 90        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| MBR  | 52        | 57.78%  |
| GPT  | 38        | 42.22%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 22        | 24.44%  |
| ASUSTek Computer               | 15        | 16.67%  |
| Unknown                        | 6         | 6.67%   |
| MSI                            | 5         | 5.56%   |
| Dell                           | 5         | 5.56%   |
| Gigabyte Technology            | 4         | 4.44%   |
| Intel                          | 3         | 3.33%   |
| Hewlett-Packard                | 3         | 3.33%   |
| TUXEDO                         | 2         | 2.22%   |
| Panasonic                      | 2         | 2.22%   |
| Matsushita Electric Industrial | 2         | 2.22%   |
| Fujitsu                        | 2         | 2.22%   |
| Biostar                        | 2         | 2.22%   |
| ASRock                         | 2         | 2.22%   |
| Apple                          | 2         | 2.22%   |
| Acer                           | 2         | 2.22%   |
| Toshiba                        | 1         | 1.11%   |
| Tactus                         | 1         | 1.11%   |
| Sony                           | 1         | 1.11%   |
| Soekris Engineering            | 1         | 1.11%   |
| Samsung Electronics            | 1         | 1.11%   |
| PC Engines                     | 1         | 1.11%   |
| KOHJINSHA                      | 1         | 1.11%   |
| DEXP                           | 1         | 1.11%   |
| CncTion                        | 1         | 1.11%   |
| Clevo                          | 1         | 1.11%   |
| Alienware                      | 1         | 1.11%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 6         | 6.67%   |
| Lenovo ThinkPad X200 745969G                | 3         | 3.33%   |
| ASUS PRIME H410M-A                          | 2         | 2.22%   |
| TUXEDO Pulse 15 Gen1                        | 1         | 1.11%   |
| TUXEDO Aura 15 Gen1                         | 1         | 1.11%   |
| Toshiba Satellite BE96-F299                 | 1         | 1.11%   |
| Tactus GeoFlex 110                          | 1         | 1.11%   |
| Sony VPCL22Z1R                              | 1         | 1.11%   |
| Soekris Engineering net6501                 | 1         | 1.11%   |
| Samsung DP700A3D/DM700A3D/DB701A3D/DP700A7D | 1         | 1.11%   |
| PC Engines APU2                             | 1         | 1.11%   |
| Panasonic CF-53AAGHYDM                      | 1         | 1.11%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 1.11%   |
| MSI MS-7C82                                 | 1         | 1.11%   |
| MSI MS-7C37                                 | 1         | 1.11%   |
| MSI MS-7C02                                 | 1         | 1.11%   |
| MSI MS-6788                                 | 1         | 1.11%   |
| MSI Modern 14 B11MOL                        | 1         | 1.11%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 1.11%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 1.11%   |
| Lenovo Yoga 330-11IGM 81A6                  | 1         | 1.11%   |
| Lenovo ThinkPad Yoga 260 20FES1K81V         | 1         | 1.11%   |
| Lenovo ThinkPad X270 W10DG 20K5S5MD0F       | 1         | 1.11%   |
| Lenovo ThinkPad X260 20F5S10W0H             | 1         | 1.11%   |
| Lenovo ThinkPad X250 20CLS4WV08             | 1         | 1.11%   |
| Lenovo ThinkPad X240 20ALA0AHRT             | 1         | 1.11%   |
| Lenovo ThinkPad X220 429043U                | 1         | 1.11%   |
| Lenovo ThinkPad X200 7458NP9                | 1         | 1.11%   |
| Lenovo ThinkPad X121e 3053A52               | 1         | 1.11%   |
| Lenovo ThinkPad T60 2613CTO                 | 1         | 1.11%   |
| Lenovo ThinkPad T530 24292VG                | 1         | 1.11%   |
| Lenovo ThinkPad T430 2347GZU                | 1         | 1.11%   |
| Lenovo ThinkPad T420s 4174DL7               | 1         | 1.11%   |
| Lenovo ThinkPad T420s 41742BU               | 1         | 1.11%   |
| Lenovo ThinkPad T410 2537N24                | 1         | 1.11%   |
| Lenovo ThinkPad L530 24812TG                | 1         | 1.11%   |
| Lenovo ThinkPad E14 Gen 2 20T6003BRT        | 1         | 1.11%   |
| Lenovo ThinkCentre M93p 10AAS25M00          | 1         | 1.11%   |
| Lenovo IdeaPad S12 20021,2959               | 1         | 1.11%   |
| KOHJINSHA SH series                         | 1         | 1.11%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad                             | 19        | 21.11%  |
| ASUS PRIME                                  | 6         | 6.67%   |
| Unknown                                     | 6         | 6.67%   |
| TUXEDO Pulse                                | 1         | 1.11%   |
| TUXEDO Aura                                 | 1         | 1.11%   |
| Toshiba Satellite                           | 1         | 1.11%   |
| Tactus GeoFlex                              | 1         | 1.11%   |
| Sony VPCL22Z1R                              | 1         | 1.11%   |
| Soekris Engineering net6501                 | 1         | 1.11%   |
| Samsung DP700A3D                            | 1         | 1.11%   |
| PC Engines APU2                             | 1         | 1.11%   |
| Panasonic CF-53AAGHYDM                      | 1         | 1.11%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 1.11%   |
| MSI MS-7C82                                 | 1         | 1.11%   |
| MSI MS-7C37                                 | 1         | 1.11%   |
| MSI MS-7C02                                 | 1         | 1.11%   |
| MSI MS-6788                                 | 1         | 1.11%   |
| MSI Modern                                  | 1         | 1.11%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 1.11%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 1.11%   |
| Lenovo Yoga                                 | 1         | 1.11%   |
| Lenovo ThinkCentre                          | 1         | 1.11%   |
| Lenovo IdeaPad                              | 1         | 1.11%   |
| KOHJINSHA SH                                | 1         | 1.11%   |
| Intel Q3XXG4-P                              | 1         | 1.11%   |
| Intel NUC5PPYB                              | 1         | 1.11%   |
| Intel DH67BL                                | 1         | 1.11%   |
| HP Pavilion                                 | 1         | 1.11%   |
| HP Compaq                                   | 1         | 1.11%   |
| HP 260                                      | 1         | 1.11%   |
| Gigabyte H87-HD3                            | 1         | 1.11%   |
| Gigabyte H81M-S2PV                          | 1         | 1.11%   |
| Gigabyte H81M-S1                            | 1         | 1.11%   |
| Gigabyte G41MT-S2                           | 1         | 1.11%   |
| Fujitsu PRIMERGY                            | 1         | 1.11%   |
| Fujitsu LIFEBOOK                            | 1         | 1.11%   |
| DEXP NAVIS                                  | 1         | 1.11%   |
| Dell XPS                                    | 1         | 1.11%   |
| Dell Vostro                                 | 1         | 1.11%   |
| Dell OptiPlex                               | 1         | 1.11%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 11        | 12.22%  |
| 2018    | 9         | 10%     |
| 2009    | 9         | 10%     |
| Unknown | 9         | 10%     |
| 2011    | 8         | 8.89%   |
| 2020    | 7         | 7.78%   |
| 2010    | 7         | 7.78%   |
| 2022    | 5         | 5.56%   |
| 2019    | 5         | 5.56%   |
| 2012    | 5         | 5.56%   |
| 2016    | 3         | 3.33%   |
| 2015    | 3         | 3.33%   |
| 2014    | 3         | 3.33%   |
| 2013    | 2         | 2.22%   |
| 2007    | 2         | 2.22%   |
| 2006    | 1         | 1.11%   |
| 2002    | 1         | 1.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Desktop    | 48        | 53.33%  |
| Notebook   | 40        | 44.44%  |
| Mini pc    | 1         | 1.11%   |
| All in one | 1         | 1.11%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 88        | 97.78%  |
| Yes  | 2         | 2.22%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 30        | 33.33%  |
| 4.01-8.0    | 21        | 23.33%  |
| 16.01-24.0  | 12        | 13.33%  |
| 3.01-4.0    | 9         | 10%     |
| 2.01-3.0    | 6         | 6.67%   |
| 0.51-1.0    | 4         | 4.44%   |
| 1.01-2.0    | 3         | 3.33%   |
| 32.01-64.0  | 2         | 2.22%   |
| 64.01-256.0 | 2         | 2.22%   |
| 24.01-32.0  | 1         | 1.11%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 80        | 88.89%  |
| 0        | 5         | 5.56%   |
| 0.51-1.0 | 3         | 3.33%   |
| 4.01-8.0 | 1         | 1.11%   |
| 3.01-4.0 | 1         | 1.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 49        | 54.44%  |
| 2      | 22        | 24.44%  |
| 3      | 8         | 8.89%   |
| 4      | 7         | 7.78%   |
| 8      | 1         | 1.11%   |
| 6      | 1         | 1.11%   |
| 5      | 1         | 1.11%   |
| 0      | 1         | 1.11%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 89        | 98.89%  |
| Yes       | 1         | 1.11%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 76        | 84.44%  |
| No        | 14        | 15.56%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 58.89%  |
| No        | 37        | 41.11%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 51        | 56.67%  |
| Yes       | 39        | 43.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Russia      | 17        | 18.68%  |
| Canada      | 12        | 13.19%  |
| Italy       | 8         | 8.79%   |
| France      | 7         | 7.69%   |
| USA         | 6         | 6.59%   |
| Poland      | 6         | 6.59%   |
| Netherlands | 6         | 6.59%   |
| Germany     | 6         | 6.59%   |
| UK          | 4         | 4.4%    |
| Spain       | 4         | 4.4%    |
| India       | 2         | 2.2%    |
| Egypt       | 2         | 2.2%    |
| Austria     | 2         | 2.2%    |
| Ukraine     | 1         | 1.1%    |
| Slovakia    | 1         | 1.1%    |
| Philippines | 1         | 1.1%    |
| Norway      | 1         | 1.1%    |
| Montserrat  | 1         | 1.1%    |
| Lithuania   | 1         | 1.1%    |
| Czechia     | 1         | 1.1%    |
| Chile       | 1         | 1.1%    |
| Argentina   | 1         | 1.1%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Montreal            | 10        | 10.99%  |
| Vladivostok         | 6         | 6.59%   |
| Poortugaal          | 4         | 4.4%    |
| Milan               | 4         | 4.4%    |
| Gdansk              | 3         | 3.3%    |
| Vienna              | 2         | 2.2%    |
| Paris               | 2         | 2.2%    |
| Ozersk              | 2         | 2.2%    |
| Anglet              | 2         | 2.2%    |
| Amsterdam           | 2         | 2.2%    |
| Wolverhampton       | 1         | 1.1%    |
| West Valley City    | 1         | 1.1%    |
| Valdivia            | 1         | 1.1%    |
| Tanta               | 1         | 1.1%    |
| Tambov              | 1         | 1.1%    |
| Sutton              | 1         | 1.1%    |
| Starogard Gdański  | 1         | 1.1%    |
| St. Albert          | 1         | 1.1%    |
| St Petersburg       | 1         | 1.1%    |
| Springboro          | 1         | 1.1%    |
| Sarnia              | 1         | 1.1%    |
| Reutov              | 1         | 1.1%    |
| Quezon City         | 1         | 1.1%    |
| Pozzuolo Martesana  | 1         | 1.1%    |
| Plymouth            | 1         | 1.1%    |
| Paderborn           | 1         | 1.1%    |
| Oslo                | 1         | 1.1%    |
| Orenburg            | 1         | 1.1%    |
| Odessa              | 1         | 1.1%    |
| Oakland             | 1         | 1.1%    |
| Nuremberg           | 1         | 1.1%    |
| Newcastle upon Tyne | 1         | 1.1%    |
| Mumbai              | 1         | 1.1%    |
| Moscow              | 1         | 1.1%    |
| Memphis             | 1         | 1.1%    |
| Memmingen           | 1         | 1.1%    |
| Madrid              | 1         | 1.1%    |
| Mâcon              | 1         | 1.1%    |
| Ludwigsburg         | 1         | 1.1%    |
| Lublin              | 1         | 1.1%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| NVMe                | 19        | 22     | 15.83%  |
| WDC                 | 18        | 19     | 15%     |
| Seagate             | 14        | 18     | 11.67%  |
| Samsung Electronics | 14        | 19     | 11.67%  |
| Toshiba             | 6         | 10     | 5%      |
| Kingston            | 5         | 5      | 4.17%   |
| Hitachi             | 5         | 7      | 4.17%   |
| HGST                | 4         | 4      | 3.33%   |
| SanDisk             | 3         | 3      | 2.5%    |
| Innostor            | 3         | 3      | 2.5%    |
| Crucial             | 3         | 3      | 2.5%    |
| Corsair             | 3         | 3      | 2.5%    |
| OPENBSD             | 2         | 2      | 1.67%   |
| OCZ                 | 2         | 2      | 1.67%   |
| Apacer              | 2         | 2      | 1.67%   |
| A-DATA Technology   | 2         | 2      | 1.67%   |
| XPG                 | 1         | 1      | 0.83%   |
| USB                 | 1         | 1      | 0.83%   |
| StoreJet            | 1         | 1      | 0.83%   |
| SPCC                | 1         | 1      | 0.83%   |
| PNY                 | 1         | 1      | 0.83%   |
| OWC                 | 1         | 1      | 0.83%   |
| LSI                 | 1         | 1      | 0.83%   |
| LDLC F6+            | 1         | 1      | 0.83%   |
| KingSpec            | 1         | 1      | 0.83%   |
| Intel               | 1         | 1      | 0.83%   |
| Hoodisk             | 1         | 1      | 0.83%   |
| GOODRAM             | 1         | 1      | 0.83%   |
| Generic             | 1         | 1      | 0.83%   |
| Fujitsu             | 1         | 1      | 0.83%   |
| AMD                 | 1         | 1      | 0.83%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| NVMe Samsung SSD 980 1TB        | 4         | 3.23%   |
| Samsung HM321HI 320GB           | 3         | 2.42%   |
| Innostor SSD 15GB               | 3         | 2.42%   |
| Toshiba HDWG440 4TB             | 2         | 1.61%   |
| Seagate ST1000DM010-2EP102 1TB  | 2         | 1.61%   |
| OPENBSD SR RAID 1 752GB         | 2         | 1.61%   |
| OCZ VERTEX3 120GB               | 2         | 1.61%   |
| NVMe WDC PC SN530 SDB 256GB     | 2         | 1.61%   |
| Apacer AS340 240GB              | 2         | 1.61%   |
| XPG SX950U 240GB                | 1         | 0.81%   |
| WDC WD800JD-60LSA5 80GB         | 1         | 0.81%   |
| WDC WD7500BPKX-00HPJT0 752GB    | 1         | 0.81%   |
| WDC WD7500BPKT-75PK4T0 752GB    | 1         | 0.81%   |
| WDC WD7500BPKT-00PK4T0 752GB    | 1         | 0.81%   |
| WDC WD6400AARS-00Y5B1 640GB     | 1         | 0.81%   |
| WDC WD6400AAKS-22A7B0 640GB     | 1         | 0.81%   |
| WDC WD5003AZEX-00K1GA0 500GB    | 1         | 0.81%   |
| WDC WD5003ABYX-01WERA2 500GB    | 1         | 0.81%   |
| WDC WD5000LPLX-00ZNTT0 500GB    | 1         | 0.81%   |
| WDC WD5000AZLX-00K2TA0 500GB    | 1         | 0.81%   |
| WDC WD5000AAKX-60U6AA0 500GB    | 1         | 0.81%   |
| WDC WD40EFZX-68AWUN0 4TB        | 1         | 0.81%   |
| WDC WD3200BEVE-00A0HT0 320GB    | 1         | 0.81%   |
| WDC WD20PURX-64P6ZY0 2TB        | 1         | 0.81%   |
| WDC WD1600BEVT-22ZCT0 160GB     | 1         | 0.81%   |
| WDC WD10JPVT-75A1YT0 1TB        | 1         | 0.81%   |
| WDC WD10JPLX-00MBPT0 1TB        | 1         | 0.81%   |
| WDC WD10EZEX-00MFCA0 1TB        | 1         | 0.81%   |
| USB SanDisk 3.2Gen1 64GB        | 1         | 0.81%   |
| Toshiba MK6475GSX 640GB         | 1         | 0.81%   |
| Toshiba MK5065GSX 500GB         | 1         | 0.81%   |
| Toshiba MG06ACA800E 8TB         | 1         | 0.81%   |
| Toshiba DT01ACA050 500GB        | 1         | 0.81%   |
| StoreJet Transcend 120GB        | 1         | 0.81%   |
| SPCC Solid State Disk 256GB     | 1         | 0.81%   |
| Seagate ST9500420AS 500GB       | 1         | 0.81%   |
| Seagate ST9160821A 160GB        | 1         | 0.81%   |
| Seagate ST500DM002-1BD142 500GB | 1         | 0.81%   |
| Seagate ST380815AS 80GB         | 1         | 0.81%   |
| Seagate ST3750640NS 752GB       | 1         | 0.81%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 18        | 19     | 25%     |
| Seagate             | 14        | 18     | 19.44%  |
| NVMe                | 10        | 11     | 13.89%  |
| Samsung Electronics | 7         | 7      | 9.72%   |
| Toshiba             | 6         | 10     | 8.33%   |
| Hitachi             | 5         | 7      | 6.94%   |
| HGST                | 4         | 4      | 5.56%   |
| OPENBSD             | 2         | 2      | 2.78%   |
| USB                 | 1         | 1      | 1.39%   |
| StoreJet            | 1         | 1      | 1.39%   |
| LSI                 | 1         | 1      | 1.39%   |
| LDLC F6+            | 1         | 1      | 1.39%   |
| Generic             | 1         | 1      | 1.39%   |
| Fujitsu             | 1         | 1      | 1.39%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 12     | 15.56%  |
| NVMe                | 6         | 7      | 13.33%  |
| Kingston            | 5         | 5      | 11.11%  |
| SanDisk             | 3         | 3      | 6.67%   |
| Innostor            | 3         | 3      | 6.67%   |
| Crucial             | 3         | 3      | 6.67%   |
| Corsair             | 3         | 3      | 6.67%   |
| OCZ                 | 2         | 2      | 4.44%   |
| Apacer              | 2         | 2      | 4.44%   |
| A-DATA Technology   | 2         | 2      | 4.44%   |
| XPG                 | 1         | 1      | 2.22%   |
| SPCC                | 1         | 1      | 2.22%   |
| PNY                 | 1         | 1      | 2.22%   |
| OWC                 | 1         | 1      | 2.22%   |
| KingSpec            | 1         | 1      | 2.22%   |
| Intel               | 1         | 1      | 2.22%   |
| Hoodisk             | 1         | 1      | 2.22%   |
| GOODRAM             | 1         | 1      | 2.22%   |
| AMD                 | 1         | 1      | 2.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 53        | 84     | 56.38%  |
| SSD  | 38        | 51     | 40.43%  |
| NVMe | 3         | 4      | 3.19%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 81        | 135    | 96.43%  |
| NVMe | 3         | 4      | 3.57%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 61        | 77     | 61%     |
| 0.51-1.0   | 30        | 37     | 30%     |
| 3.01-4.0   | 4         | 7      | 4%      |
| 1.01-2.0   | 4         | 11     | 4%      |
| 4.01-10.0  | 1         | 3      | 1%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 27        | 30%     |
| 251-500        | 24        | 26.67%  |
| 21-50          | 17        | 18.89%  |
| 51-100         | 8         | 8.89%   |
| 1-20           | 7         | 7.78%   |
| 501-1000       | 5         | 5.56%   |
| More than 3000 | 2         | 2.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 76        | 84.44%  |
| 51-100    | 5         | 5.56%   |
| 21-50     | 4         | 4.44%   |
| 101-250   | 3         | 3.33%   |
| 251-500   | 1         | 1.11%   |
| 2001-3000 | 1         | 1.11%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| OCZ VERTEX3 120GB                 | 2         | 2      | 10%     |
| XPG SX950U 240GB                  | 1         | 1      | 5%      |
| WDC WD6400AAKS-22A7B0 640GB       | 1         | 1      | 5%      |
| WDC WD5000AAKX-60U6AA0 500GB      | 1         | 1      | 5%      |
| Toshiba MK6475GSX 640GB           | 1         | 1      | 5%      |
| Toshiba MK5065GSX 500GB           | 1         | 1      | 5%      |
| Seagate ST9500420AS 500GB         | 1         | 1      | 5%      |
| Seagate ST500DM002-1BD142 500GB   | 1         | 1      | 5%      |
| Seagate ST380815AS 80GB           | 1         | 1      | 5%      |
| Seagate ST3750640NS 752GB         | 1         | 2      | 5%      |
| Seagate ST3160212SCE 160GB        | 1         | 1      | 5%      |
| Seagate ST250DM000-1BD141 250GB   | 1         | 1      | 5%      |
| Seagate ST2000DM006-2DM164 2TB    | 1         | 1      | 5%      |
| SanDisk SD7UB3Q256G1001 256GB     | 1         | 1      | 5%      |
| Samsung Electronics HD753LJ 752GB | 1         | 1      | 5%      |
| Samsung Electronics HD161HJ 160GB | 1         | 1      | 5%      |
| HGST HTS721010A9E630 1TB          | 1         | 1      | 5%      |
| Corsair Force LS SSD 120GB        | 1         | 1      | 5%      |
| A-DATA Technology SP550 480GB     | 1         | 1      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 8      | 31.58%  |
| WDC                 | 2         | 2      | 10.53%  |
| Toshiba             | 2         | 2      | 10.53%  |
| Samsung Electronics | 2         | 2      | 10.53%  |
| OCZ                 | 2         | 2      | 10.53%  |
| XPG                 | 1         | 1      | 5.26%   |
| SanDisk             | 1         | 1      | 5.26%   |
| HGST                | 1         | 1      | 5.26%   |
| Corsair             | 1         | 1      | 5.26%   |
| A-DATA Technology   | 1         | 1      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 8      | 46.15%  |
| WDC                 | 2         | 2      | 15.38%  |
| Toshiba             | 2         | 2      | 15.38%  |
| Samsung Electronics | 2         | 2      | 15.38%  |
| HGST                | 1         | 1      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 15     | 68.42%  |
| SSD  | 6         | 6      | 31.58%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart_bsd/drive_failed.svg)


| Model                       | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC WD6400AARS-00Y5B1 640GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 59        | 89     | 58.42%  |
| Detected | 23        | 28     | 22.77%  |
| Malfunc  | 18        | 21     | 17.82%  |
| Failed   | 1         | 1      | 0.99%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 61        | 61%     |
| AMD                          | 15        | 15%     |
| Samsung Electronics          | 6         | 6%      |
| SanDisk                      | 4         | 4%      |
| KIOXIA                       | 2         | 2%      |
| VIA Technologies             | 1         | 1%      |
| Toshiba                      | 1         | 1%      |
| SK hynix                     | 1         | 1%      |
| Shenzhen Longsys Electronics | 1         | 1%      |
| Nvidia                       | 1         | 1%      |
| Micron/Crucial Technology    | 1         | 1%      |
| Marvell Technology Group     | 1         | 1%      |
| Lenovo                       | 1         | 1%      |
| Kingston Technology Company  | 1         | 1%      |
| Broadcom / LSI               | 1         | 1%      |
| ASMedia Technology           | 1         | 1%      |
| ADATA Technology             | 1         | 1%      |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                                  | Computers | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 6         | 5.31%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 6         | 5.31%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 5         | 4.42%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 5         | 4.42%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 5         | 4.42%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 5         | 4.42%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 4         | 3.54%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 4         | 3.54%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 4         | 3.54%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 4         | 3.54%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 3         | 2.65%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 3         | 2.65%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 3         | 2.65%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 3         | 2.65%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 2         | 1.77%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 2         | 1.77%   |
| Intel Jasper Lake SATA AHCI Controller                                                 | 2         | 1.77%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 2         | 1.77%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 2         | 1.77%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 2         | 1.77%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 2         | 1.77%   |
| AMD 500 Series Chipset SATA Controller                                                 | 2         | 1.77%   |
| AMD 400 Series Chipset SATA Controller                                                 | 2         | 1.77%   |
| VIA VT6415 PATA IDE Host Controller                                                    | 1         | 0.88%   |
| Toshiba BG3 NVMe SSD Controller                                                        | 1         | 0.88%   |
| SK hynix PC300 NVMe Solid State Drive 256GB                                            | 1         | 0.88%   |
| Shenzhen Longsys unknown                                                               | 1         | 0.88%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 1         | 0.88%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 1         | 0.88%   |
| SanDisk unknown                                                                        | 1         | 0.88%   |
| SanDisk PC SN530                                                                       | 1         | 0.88%   |
| SanDisk PC SN520 NVMe SSD                                                              | 1         | 0.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 1         | 0.88%   |
| Samsung NVMe SSD Controller 980                                                        | 1         | 0.88%   |
| Nvidia MCP79 AHCI Controller                                                           | 1         | 0.88%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                        | 1         | 0.88%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                       | 1         | 0.88%   |
| Lenovo unknown                                                                         | 1         | 0.88%   |
| KIOXIA NVMe SSD Controller BG4                                                         | 1         | 0.88%   |
| KIOXIA NVMe SSD                                                                        | 1         | 0.88%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 66        | 63.46%  |
| NVMe | 19        | 18.27%  |
| IDE  | 18        | 17.31%  |
| RAID | 1         | 0.96%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 66        | 73.33%  |
| AMD    | 17        | 18.89%  |
| ARM    | 6         | 6.67%   |
| 11th   | 1         | 1.11%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz                         | 5         | 5.56%   |
| ARM Cortex-A72 r0p3                                       | 4         | 4.44%   |
| Intel Core i5-6300U CPU @ 2.40GHz                         | 3         | 3.33%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz                      | 3         | 3.33%   |
| Intel Core i5-4570 CPU @ 3.20GHz                          | 2         | 2.22%   |
| Intel Core i5 CPU M 520 @ 2.40GHz                         | 2         | 2.22%   |
| Intel Core i3-10100F CPU @ 3.60GHz                        | 2         | 2.22%   |
| Intel Core i3-10100 CPU @ 3.60GHz                         | 2         | 2.22%   |
| AMD Ryzen 7 4700U with Radeon Graphics                    | 2         | 2.22%   |
| Intel Xeon CPU X5690 @ 3.47GHz                            | 1         | 1.11%   |
| Intel Xeon CPU E5520 @ 2.27GHz                            | 1         | 1.11%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz                       | 1         | 1.11%   |
| Intel Pentium Silver N6000 @ 1.10GHz                      | 1         | 1.11%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz                  | 1         | 1.11%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz               | 1         | 1.11%   |
| Intel Pentium CPU N3700 @ 1.60GHz                         | 1         | 1.11%   |
| Intel Pentium 4 Mobile CPU 1.60GHz                        | 1         | 1.11%   |
| Intel Pentium 4 CPU 2.40GHz ("GenuineIntel" 686-class)    | 1         | 1.11%   |
| Intel Genuine processor 600MHz ("GenuineIntel" 686-class) | 1         | 1.11%   |
| Intel Genuine CPU T2300 @ 1.66GHz                         | 1         | 1.11%   |
| Intel Genuine CPU @ 1.00GHz ("GenuineIntel" 686-class)    | 1         | 1.11%   |
| Intel Core i9-10980HK CPU @ 2.40GHz                       | 1         | 1.11%   |
| Intel Core i7-9700K CPU @ 3.60GHz                         | 1         | 1.11%   |
| Intel Core i7-7500U CPU @ 2.70GHz                         | 1         | 1.11%   |
| Intel Core i7-6700 CPU @ 3.40GHz                          | 1         | 1.11%   |
| Intel Core i7-5500U CPU @ 2.40GHz                         | 1         | 1.11%   |
| Intel Core i7-4790 CPU @ 3.60GHz                          | 1         | 1.11%   |
| Intel Core i7-3610QM CPU @ 2.30GHz                        | 1         | 1.11%   |
| Intel Core i7-3520M CPU @ 2.90GHz                         | 1         | 1.11%   |
| Intel Core i7-2670QM CPU @ 2.20GHz                        | 1         | 1.11%   |
| Intel Core i5-8250U CPU @ 1.60GHz                         | 1         | 1.11%   |
| Intel Core i5-5300U CPU @ 2.30GHz                         | 1         | 1.11%   |
| Intel Core i5-4570T CPU @ 2.90GHz                         | 1         | 1.11%   |
| Intel Core i5-3470T CPU @ 2.90GHz                         | 1         | 1.11%   |
| Intel Core i5-3320M CPU @ 2.60GHz                         | 1         | 1.11%   |
| Intel Core i5-3210M CPU @ 2.50GHz                         | 1         | 1.11%   |
| Intel Core i5-10400F CPU @ 2.90GHz                        | 1         | 1.11%   |
| Intel Core i5-10300H CPU @ 2.50GHz                        | 1         | 1.11%   |
| Intel Core i3-7130U CPU @ 2.70GHz                         | 1         | 1.11%   |
| Intel Core i3-5010U CPU @ 2.10GHz                         | 1         | 1.11%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 20        | 22.22%  |
| Intel Core i3           | 9         | 10%     |
| Intel Core i7           | 8         | 8.89%   |
| Intel Core 2 Duo        | 6         | 6.67%   |
| ARM Cortex              | 6         | 6.67%   |
| Intel Celeron           | 5         | 5.56%   |
| AMD Ryzen 7             | 4         | 4.44%   |
| Intel Xeon              | 3         | 3.33%   |
| Intel Genuine           | 3         | 3.33%   |
| AMD Ryzen 5             | 3         | 3.33%   |
| Other                   | 2         | 2.22%   |
| Intel Pentium Silver    | 2         | 2.22%   |
| Intel Pentium 4         | 2         | 2.22%   |
| Intel Core 2            | 2         | 2.22%   |
| Intel Atom              | 2         | 2.22%   |
| Intel Pentium Dual-Core | 1         | 1.11%   |
| Intel Pentium           | 1         | 1.11%   |
| Intel Core i9           | 1         | 1.11%   |
| Intel Core 2 Quad       | 1         | 1.11%   |
| AMD Ryzen 9             | 1         | 1.11%   |
| AMD Ryzen 3             | 1         | 1.11%   |
| AMD Phenom II X4        | 1         | 1.11%   |
| AMD GX                  | 1         | 1.11%   |
| AMD E                   | 1         | 1.11%   |
| AMD Athlon II X4        | 1         | 1.11%   |
| AMD Athlon II X2        | 1         | 1.11%   |
| AMD Athlon              | 1         | 1.11%   |
| AMD A6                  | 1         | 1.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 28        | 31.11%  |
| 4       | 24        | 26.67%  |
| Unknown | 24        | 26.67%  |
| 8       | 5         | 5.56%   |
| 12      | 3         | 3.33%   |
| 1       | 3         | 3.33%   |
| 32      | 1         | 1.11%   |
| 16      | 1         | 1.11%   |
| 6       | 1         | 1.11%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 64        | 71.11%  |
| Unknown | 24        | 26.67%  |
| 2       | 2         | 2.22%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 36        | 40%     |
| 1       | 27        | 30%     |
| Unknown | 27        | 30%     |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 12        | 13.33%  |
| Penryn        | 8         | 8.89%   |
| IvyBridge     | 7         | 7.78%   |
| SandyBridge   | 6         | 6.67%   |
| Haswell       | 6         | 6.67%   |
| CometLake     | 6         | 6.67%   |
| Skylake       | 5         | 5.56%   |
| Zen 2         | 4         | 4.44%   |
| KabyLake      | 4         | 4.44%   |
| K10           | 4         | 4.44%   |
| Westmere      | 3         | 3.33%   |
| Broadwell     | 3         | 3.33%   |
| Bonnell       | 3         | 3.33%   |
| Zen 3         | 2         | 2.22%   |
| Silvermont    | 2         | 2.22%   |
| P6            | 2         | 2.22%   |
| NetBurst      | 2         | 2.22%   |
| Goldmont plus | 2         | 2.22%   |
| Core          | 2         | 2.22%   |
| Zen+          | 1         | 1.11%   |
| Zen           | 1         | 1.11%   |
| Puma          | 1         | 1.11%   |
| Nehalem       | 1         | 1.11%   |
| K10 Llano     | 1         | 1.11%   |
| Goldmont      | 1         | 1.11%   |
| Bobcat        | 1         | 1.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 48        | 55.17%  |
| AMD                        | 28        | 32.18%  |
| Nvidia                     | 9         | 10.34%  |
| Matrox Electronics Systems | 1         | 1.15%   |
| ASPEED Technology          | 1         | 1.15%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 5.38%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 5.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4         | 4.3%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 4.3%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 4.3%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 3.23%   |
| Intel HD Graphics 5500                                                                   | 3         | 3.23%   |
| AMD Renoir                                                                               | 3         | 3.23%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 3         | 3.23%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 2.15%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 2.15%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 2.15%   |
| Intel HD Graphics 620                                                                    | 2         | 2.15%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 2.15%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 2.15%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 2.15%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 2         | 2.15%   |
| AMD RS880 [Radeon HD 4200]                                                               | 2         | 2.15%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 2         | 2.15%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2         | 2.15%   |
| Nvidia TU117M                                                                            | 1         | 1.08%   |
| Nvidia NV28 [GeForce4 Ti 4200 AGP 8x]                                                    | 1         | 1.08%   |
| Nvidia GM108M [GeForce 940M]                                                             | 1         | 1.08%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 1.08%   |
| Nvidia GF108M [NVS 5400M]                                                                | 1         | 1.08%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 1         | 1.08%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 1         | 1.08%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 1.08%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 1         | 1.08%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 1.08%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 1         | 1.08%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.08%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 1.08%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1         | 1.08%   |
| Intel HD Graphics 530                                                                    | 1         | 1.08%   |
| Intel HD Graphics 500                                                                    | 1         | 1.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 1.08%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 1.08%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.08%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 34        | 37.78%  |
| 1 x AMD        | 25        | 27.78%  |
| 2 x Intel      | 9         | 10%     |
| Other          | 8         | 8.89%   |
| 1 x Nvidia     | 5         | 5.56%   |
| Intel + Nvidia | 3         | 3.33%   |
| Intel + AMD    | 2         | 2.22%   |
| 2 x Nvidia     | 1         | 1.11%   |
| 2 x AMD        | 1         | 1.11%   |
| 1 x Matrox     | 1         | 1.11%   |
| 1 x ASPEED     | 1         | 1.11%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 76        | 84.44%  |
| Unknown | 14        | 15.56%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 90        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Philips                 | 8         | 14.29%  |
| Lenovo                  | 6         | 10.71%  |
| Samsung Electronics     | 5         | 8.93%   |
| LG Display              | 5         | 8.93%   |
| BOE                     | 4         | 7.14%   |
| AU Optronics            | 4         | 7.14%   |
| Dell                    | 3         | 5.36%   |
| Chimei Innolux          | 3         | 5.36%   |
| Acer                    | 3         | 5.36%   |
| ViewSonic               | 2         | 3.57%   |
| MSI                     | 2         | 3.57%   |
| Chi Mei Optoelectronics | 2         | 3.57%   |
| TRU                     | 1         | 1.79%   |
| PANDA                   | 1         | 1.79%   |
| InfoVision              | 1         | 1.79%   |
| Hewlett-Packard         | 1         | 1.79%   |
| Goldstar                | 1         | 1.79%   |
| BenQ                    | 1         | 1.79%   |
| Apple                   | 1         | 1.79%   |
| AOC                     | 1         | 1.79%   |
| Ancor Communications    | 1         | 1.79%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                    | 7         | 12.5%   |
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch                  | 3         | 5.36%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch              | 2         | 3.57%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 2         | 3.57%   |
| Acer V223HQ ACR0070 1920x1080 470x270mm 21.3-inch                        | 2         | 3.57%   |
| ViewSonic LCD Monitor VSCD22B 1920x1080 520x290mm 23.4-inch              | 1         | 1.79%   |
| ViewSonic LCD Monitor VSCC42B 1920x1080 480x270mm 21.7-inch              | 1         | 1.79%   |
| TRU LCD Monitor TRU235C 1366x768 260x140mm 11.6-inch                     | 1         | 1.79%   |
| Samsung Electronics SyncMaster SAM03CF 1280x1024 340x270mm 17.1-inch     | 1         | 1.79%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch     | 1         | 1.79%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 310x170mm 13.9-inch     | 1         | 1.79%   |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch   | 1         | 1.79%   |
| Samsung Electronics DM700A-D SEM0324 1920x1080 520x290mm 23.4-inch       | 1         | 1.79%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                  | 1         | 1.79%   |
| PANDA LM133LF1L01 NCP13FB 1920x1080 290x170mm 13.2-inch                  | 1         | 1.79%   |
| MSI MP242 MSI30A1 1920x1080 530x300mm 24.0-inch                          | 1         | 1.79%   |
| MSI MAG241C MSI3EA2 1920x1080 520x290mm 23.4-inch                        | 1         | 1.79%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch             | 1         | 1.79%   |
| LG Display LCD Monitor LGD0215 1920x1080 350x190mm 15.7-inch             | 1         | 1.79%   |
| LG Display LCD Monitor LGD01AB 1280x800 260x160mm 12.0-inch              | 1         | 1.79%   |
| Lenovo LEN S24e-10 LEN61CA 1920x1080 530x300mm 24.0-inch                 | 1         | 1.79%   |
| Lenovo LCD Monitor LEN4022 1400x1050 290x210mm 14.1-inch                 | 1         | 1.79%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x170mm 12.2-inch                  | 1         | 1.79%   |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch              | 1         | 1.79%   |
| Hewlett-Packard x23LED HWP2912 1920x1080 510x290mm 23.1-inch             | 1         | 1.79%   |
| Goldstar L1752T GSM4434 1280x1024 340x270mm 17.1-inch                    | 1         | 1.79%   |
| Dell LCD Monitor DELF003 1440x900 410x260mm 19.1-inch                    | 1         | 1.79%   |
| Dell E1916H DELF064 1366x768 410x230mm 18.5-inch                         | 1         | 1.79%   |
| Dell 2001FP DELA007 1600x1200 410x310mm 20.2-inch                        | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 380x210mm 17.1-inch          | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN15D7 1920x1080 340x190mm 15.3-inch         | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN152E 1920x1080 340x190mm 15.3-inch         | 1         | 1.79%   |
| BOE LCD Monitor BOE0900 1920x1080 340x190mm 15.3-inch                    | 1         | 1.79%   |
| BOE LCD Monitor BOE08D7 1920x1080 310x170mm 13.9-inch                    | 1         | 1.79%   |
| BOE LCD Monitor BOE07A5 1366x768 340x190mm 15.3-inch                     | 1         | 1.79%   |
| BOE LCD Monitor BOE075A 1366x768 310x170mm 13.9-inch                     | 1         | 1.79%   |
| BenQ G2255 BNQ78B7 1920x1080 480x270mm 21.7-inch                         | 1         | 1.79%   |
| AU Optronics LCD Monitor AUODF87 1920x1080 340x190mm 15.3-inch           | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch            | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch            | 1         | 1.79%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 25        | 46.3%   |
| 1366x768 (WXGA)  | 12        | 22.22%  |
| 1280x800 (WXGA)  | 6         | 11.11%  |
| 1600x900 (HD+)   | 3         | 5.56%   |
| 1440x900 (WXGA+) | 2         | 3.7%    |
| 1280x1024 (SXGA) | 2         | 3.7%    |
| 3840x2160 (4K)   | 1         | 1.85%   |
| 3440x1440        | 1         | 1.85%   |
| 1600x1200        | 1         | 1.85%   |
| 1400x1050        | 1         | 1.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 21     | 11        | 20%     |
| 15     | 9         | 16.36%  |
| 12     | 9         | 16.36%  |
| 13     | 7         | 12.73%  |
| 23     | 4         | 7.27%   |
| 24     | 3         | 5.45%   |
| 17     | 3         | 5.45%   |
| 19     | 2         | 3.64%   |
| 11     | 2         | 3.64%   |
| 54     | 1         | 1.82%   |
| 34     | 1         | 1.82%   |
| 20     | 1         | 1.82%   |
| 18     | 1         | 1.82%   |
| 14     | 1         | 1.82%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 16        | 29.09%  |
| 401-500     | 15        | 27.27%  |
| 201-300     | 14        | 25.45%  |
| 501-600     | 7         | 12.73%  |
| 701-800     | 1         | 1.82%   |
| 351-400     | 1         | 1.82%   |
| 1001-1500   | 1         | 1.82%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 41        | 75.93%  |
| 16/10 | 7         | 12.96%  |
| 5/4   | 2         | 3.7%    |
| 4/3   | 2         | 3.7%    |
| 3/2   | 1         | 1.85%   |
| 21/9  | 1         | 1.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 15        | 27.78%  |
| 61-70          | 9         | 16.67%  |
| 81-90          | 6         | 11.11%  |
| 91-100         | 6         | 11.11%  |
| 151-200        | 5         | 9.26%   |
| 101-110        | 4         | 7.41%   |
| 141-150        | 3         | 5.56%   |
| 51-60          | 2         | 3.7%    |
| More than 1000 | 1         | 1.85%   |
| 71-80          | 1         | 1.85%   |
| 351-500        | 1         | 1.85%   |
| 121-130        | 1         | 1.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 21        | 38.89%  |
| 101-120 | 16        | 29.63%  |
| 51-100  | 16        | 29.63%  |
| 161-240 | 1         | 1.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 63        | 70%     |
| 0     | 25        | 27.78%  |
| 3     | 1         | 1.11%   |
| 2     | 1         | 1.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 47        | 42.34%  |
| Realtek Semiconductor             | 40        | 36.04%  |
| Qualcomm Atheros                  | 7         | 6.31%   |
| Broadcom                          | 4         | 3.6%    |
| Qualcomm Atheros Communications   | 3         | 2.7%    |
| Ericsson Business Mobile Networks | 3         | 2.7%    |
| Sierra Wireless                   | 1         | 0.9%    |
| Qcom                              | 1         | 0.9%    |
| Nvidia                            | 1         | 0.9%    |
| Marvell Technology Group          | 1         | 0.9%    |
| Dell                              | 1         | 0.9%    |
| AVM                               | 1         | 0.9%    |
| ASUSTek Computer                  | 1         | 0.9%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 30        | 20.83%  |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 7         | 4.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 7         | 4.86%   |
| Intel Wi-Fi 6 AX200                                                         | 6         | 4.17%   |
| Intel Ultimate N WiFi Link 5300                                             | 4         | 2.78%   |
| Intel 82574L Gigabit Network Connection                                     | 4         | 2.78%   |
| Intel 82567LM Gigabit Network Connection                                    | 4         | 2.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 3         | 2.08%   |
| Qualcomm Atheros AR9271 802.11n                                             | 3         | 2.08%   |
| Intel Wireless 8260                                                         | 3         | 2.08%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 3         | 2.08%   |
| Intel I210 Gigabit Network Connection                                       | 3         | 2.08%   |
| Intel Ethernet Connection I219-LM                                           | 3         | 2.08%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 2         | 1.39%   |
| Realtek RTL8125 2.5GbE Controller                                           | 2         | 1.39%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                       | 2         | 1.39%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 2         | 1.39%   |
| Intel Wireless 7265                                                         | 2         | 1.39%   |
| Intel I211 Gigabit Network Connection                                       | 2         | 1.39%   |
| Intel Centrino Advanced-N 6200                                              | 2         | 1.39%   |
| Intel 82577LM Gigabit Network Connection                                    | 2         | 1.39%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III | 2         | 1.39%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                      | 2         | 1.39%   |
| Sierra Wireless EM7455                                                      | 1         | 0.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 1         | 0.69%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                             | 1         | 0.69%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                             | 1         | 0.69%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                 | 1         | 0.69%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                            | 1         | 0.69%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                            | 1         | 0.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 1         | 0.69%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                            | 1         | 0.69%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 1         | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                               | 1         | 0.69%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                               | 1         | 0.69%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet              | 1         | 0.69%   |
| Qcom RT73 USB Wireless LAN Card                                             | 1         | 0.69%   |
| Nvidia MCP79 Ethernet                                                       | 1         | 0.69%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                     | 1         | 0.69%   |
| Intel Wireless 7260                                                         | 1         | 0.69%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 36        | 63.16%  |
| Realtek Semiconductor           | 6         | 10.53%  |
| Qualcomm Atheros                | 5         | 8.77%   |
| Qualcomm Atheros Communications | 3         | 5.26%   |
| Broadcom                        | 3         | 5.26%   |
| Sierra Wireless                 | 1         | 1.75%   |
| Qcom                            | 1         | 1.75%   |
| Dell                            | 1         | 1.75%   |
| ASUSTek Computer                | 1         | 1.75%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 7         | 12.28%  |
| Intel Wi-Fi 6 AX200                                            | 6         | 10.53%  |
| Intel Ultimate N WiFi Link 5300                                | 4         | 7.02%   |
| Qualcomm Atheros AR9271 802.11n                                | 3         | 5.26%   |
| Intel Wireless 8260                                            | 3         | 5.26%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 3         | 5.26%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 3.51%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 3.51%   |
| Intel Wireless 7265                                            | 2         | 3.51%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 3.51%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 2         | 3.51%   |
| Sierra Wireless EM7455                                         | 1         | 1.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.75%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 1.75%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1         | 1.75%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 1.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 1.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 1.75%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 1.75%   |
| Qcom RT73 USB Wireless LAN Card                                | 1         | 1.75%   |
| Intel Wireless 7260                                            | 1         | 1.75%   |
| Intel Wireless 3165                                            | 1         | 1.75%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1         | 1.75%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 1         | 1.75%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 1.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 1.75%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 1.75%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 1.75%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 1         | 1.75%   |
| Dell Dell Wireless 5550 HSPA+ Mini-Card Network Adapter        | 1         | 1.75%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 1         | 1.75%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                            | 1         | 1.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 39        | 50%     |
| Intel                    | 32        | 41.03%  |
| Qualcomm Atheros         | 3         | 3.85%   |
| Broadcom                 | 2         | 2.56%   |
| Nvidia                   | 1         | 1.28%   |
| Marvell Technology Group | 1         | 1.28%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 30        | 36.59%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 7         | 8.54%   |
| Intel 82574L Gigabit Network Connection                                       | 4         | 4.88%   |
| Intel 82567LM Gigabit Network Connection                                      | 4         | 4.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 3         | 3.66%   |
| Intel I210 Gigabit Network Connection                                         | 3         | 3.66%   |
| Intel Ethernet Connection I219-LM                                             | 3         | 3.66%   |
| Realtek RTL8125 2.5GbE Controller                                             | 2         | 2.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2         | 2.44%   |
| Intel I211 Gigabit Network Connection                                         | 2         | 2.44%   |
| Intel 82577LM Gigabit Network Connection                                      | 2         | 2.44%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                              | 1         | 1.22%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 1         | 1.22%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1         | 1.22%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                 | 1         | 1.22%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1         | 1.22%   |
| Nvidia MCP79 Ethernet                                                         | 1         | 1.22%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 1         | 1.22%   |
| Intel Platform Controller Hub EG20T Gigabit Ethernet Controller               | 1         | 1.22%   |
| Intel I225-K2                                                                 | 1         | 1.22%   |
| Intel Ethernet Controller I225-V                                              | 1         | 1.22%   |
| Intel Ethernet Connection I218-LM                                             | 1         | 1.22%   |
| Intel Ethernet Connection I217-LM                                             | 1         | 1.22%   |
| Intel Ethernet Connection (3) I218-LM                                         | 1         | 1.22%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1         | 1.22%   |
| Intel 82579V Gigabit Network Connection                                       | 1         | 1.22%   |
| Intel 82575EB Gigabit Network Connection                                      | 1         | 1.22%   |
| Intel 82573L Gigabit Ethernet Controller                                      | 1         | 1.22%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 1.22%   |
| Broadcom NetXtreme BCM5753M Gigabit Ethernet PCI Express                      | 1         | 1.22%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                           | 1         | 1.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 76        | 56.72%  |
| WiFi     | 53        | 39.55%  |
| Unknown  | 4         | 2.99%   |
| Modem    | 1         | 0.75%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 40        | 50%     |
| Ethernet | 40        | 50%     |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 45        | 50%     |
| 1     | 30        | 33.33%  |
| 0     | 7         | 7.78%   |
| 3     | 4         | 4.44%   |
| 5     | 2         | 2.22%   |
| 4     | 2         | 2.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 89        | 98.89%  |
| Yes  | 1         | 1.11%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 18        | 46.15%  |
| Broadcom                        | 9         | 23.08%  |
| Foxconn / Hon Hai               | 2         | 5.13%   |
| Apple                           | 2         | 5.13%   |
| Alps Electric                   | 2         | 5.13%   |
| Realtek Semiconductor           | 1         | 2.56%   |
| Qualcomm Atheros Communications | 1         | 2.56%   |
| IMC Networks                    | 1         | 2.56%   |
| Hewlett-Packard                 | 1         | 2.56%   |
| Cambridge Silicon Radio         | 1         | 2.56%   |
| ASUSTek Computer                | 1         | 2.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 7         | 17.95%  |
| Intel AX200 Bluetooth                                       | 4         | 10.26%  |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 3         | 7.69%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 3         | 7.69%   |
| Intel AX201 Bluetooth                                       | 2         | 5.13%   |
| Alps Electric UGTZ4 Bluetooth                               | 2         | 5.13%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 2.56%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 2.56%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 2.56%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 2.56%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 1         | 2.56%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 1         | 2.56%   |
| Intel AX210 Bluetooth                                       | 1         | 2.56%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 2.56%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 2.56%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 2.56%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device    | 1         | 2.56%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1         | 2.56%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 1         | 2.56%   |
| Broadcom BCM2046 Bluetooth Device                           | 1         | 2.56%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 1         | 2.56%   |
| ASUS Broadcom Bluetooth 2.1                                 | 1         | 2.56%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1         | 2.56%   |
| Apple Bluetooth Host Controller                             | 1         | 2.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 61        | 64.89%  |
| AMD                 | 25        | 26.6%   |
| Nvidia              | 6         | 6.38%   |
| Creative Labs       | 1         | 1.06%   |
| C-Media Electronics | 1         | 1.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 6.9%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7         | 6.03%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 6         | 5.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 5.17%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 5.17%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 4.31%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 4.31%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5         | 4.31%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 3.45%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 4         | 3.45%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4         | 3.45%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 3.45%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 2.59%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 2.59%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 2.59%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 1.72%   |
| Intel Jasper Lake HD Audio                                                                        | 2         | 1.72%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.72%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 1.72%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 1.72%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 2         | 1.72%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.72%   |
| AMD Navi 10 HDMI Audio                                                                            | 2         | 1.72%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 1.72%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.86%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.86%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.86%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 0.86%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 0.86%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 0.86%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.86%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 0.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.86%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.86%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1         | 0.86%   |
| Intel 82801CA/CAM AC'97 Audio Controller                                                          | 1         | 0.86%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 0.86%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.86%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                                                | 1         | 0.86%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                                     | 1         | 0.86%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 4         | 25%     |
| Samsung Electronics | 4         | 25%     |
| SK hynix            | 3         | 18.75%  |
| Kingston            | 2         | 12.5%   |
| Corsair             | 1         | 6.25%   |
| A-DATA Technology   | 1         | 6.25%   |
| Unknown             | 1         | 6.25%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s  | 2         | 11.76%  |
| Unknown RAM Module 512MB SODIMM SDRAM                  | 1         | 5.88%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s            | 1         | 5.88%   |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s            | 1         | 5.88%   |
| Unknown RAM Module 1GB SODIMM DDR2                     | 1         | 5.88%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s | 1         | 5.88%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s | 1         | 5.88%   |
| SK hynix RAM 484D543332355336 2GB SODIMM DDR3 1333MT/s | 1         | 5.88%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s  | 1         | 5.88%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM 1067MT/s       | 1         | 5.88%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s  | 1         | 5.88%   |
| Kingston RAM KF3600C18D4/32GX 32GB DIMM DDR4 2400MT/s  | 1         | 5.88%   |
| Kingston RAM 4143523531325836 4GB SODIMM DDR3 1333MT/s | 1         | 5.88%   |
| Corsair RAM CML16GX3M2A1600C9 8GB DIMM DDR3 1600MT/s   | 1         | 5.88%   |
| A-DATA RAM AM1U16BC4P2-B19C 4GB SODIMM DDR3 1600MT/s   | 1         | 5.88%   |
| Unknown                                                | 1         | 5.88%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind  | Computers | Percent |
|-------|-----------|---------|
| DDR3  | 10        | 71.43%  |
| SDRAM | 2         | 14.29%  |
| DDR4  | 1         | 7.14%   |
| DDR2  | 1         | 7.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 12        | 85.71%  |
| DIMM   | 2         | 14.29%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 6         | 40%     |
| 2048  | 5         | 33.33%  |
| 32768 | 1         | 6.67%   |
| 8192  | 1         | 6.67%   |
| 1024  | 1         | 6.67%   |
| 512   | 1         | 6.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 3         | 21.43%  |
| 1333    | 3         | 21.43%  |
| Unknown | 3         | 21.43%  |
| 1334    | 2         | 14.29%  |
| 1067    | 2         | 14.29%  |
| 2400    | 1         | 7.14%   |

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
| Chicony Electronics                    | 12        | 42.86%  |
| Acer                                   | 4         | 14.29%  |
| Ricoh                                  | 2         | 7.14%   |
| Realtek Semiconductor                  | 2         | 7.14%   |
| Tripath Technology                     | 1         | 3.57%   |
| Sunplus Innovation Technology          | 1         | 3.57%   |
| Silicon Motion                         | 1         | 3.57%   |
| Quanta                                 | 1         | 3.57%   |
| Lite-On Technology                     | 1         | 3.57%   |
| Denron                                 | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.57%   |
| Alcor Micro                            | 1         | 3.57%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony integrated camera                                                  | 5         | 17.86%  |
| Chicony Integrated Camera [ThinkPad]                                       | 2         | 7.14%   |
| Tripath PC Camera                                                          | 1         | 3.57%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 3.57%   |
| Silicon Motion WebCam SC-10IRQ12340N                                       | 1         | 3.57%   |
| Ricoh USB2.0 Camera                                                        | 1         | 3.57%   |
| Ricoh Integrated Webcam                                                    | 1         | 3.57%   |
| Realtek USB Camera                                                         | 1         | 3.57%   |
| Realtek Integrated_Webcam_HD                                               | 1         | 3.57%   |
| Quanta VGA WebCam                                                          | 1         | 3.57%   |
| Lite-On Integrated Camera                                                  | 1         | 3.57%   |
| Denron Corp., 2M Front Camera                                              | 1         | 3.57%   |
| Chicony Lenovo Integrated Camera UVC                                       | 1         | 3.57%   |
| Chicony Lenovo Integrated Camera (0.3MP)                                   | 1         | 3.57%   |
| Chicony HD Webcam                                                          | 1         | 3.57%   |
| Chicony FJ Camera                                                          | 1         | 3.57%   |
| Chicony 2.0M UVC Webcam / CNF7129                                          | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 3.57%   |
| Alcor Micro ASUS USB2.0 WebCam                                             | 1         | 3.57%   |
| Acer Integrated Camera                                                     | 1         | 3.57%   |
| Acer HD Webcam                                                             | 1         | 3.57%   |
| Acer EasyCamera                                                            | 1         | 3.57%   |
| Acer BisonCam, NB Pro                                                      | 1         | 3.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Validity Sensors   | 4         | 36.36%  |
| Upek               | 4         | 36.36%  |
| AuthenTec          | 2         | 18.18%  |
| STMicroelectronics | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 4         | 36.36%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 9.09%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 9.09%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 9.09%   |
| Validity Sensors Synaptics WBDI                        | 1         | 9.09%   |
| STMicroelectronics Fingerprint Reader                  | 1         | 9.09%   |
| AuthenTec AuthenTec Inc. AES2660                       | 1         | 9.09%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 9.09%   |

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
| 1     | 41        | 45.56%  |
| 0     | 25        | 27.78%  |
| 2     | 16        | 17.78%  |
| 3     | 6         | 6.67%   |
| 5     | 1         | 1.11%   |
| 4     | 1         | 1.11%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 50        | 52.08%  |
| Graphics card            | 17        | 17.71%  |
| Firewire controller      | 10        | 10.42%  |
| Net/wireless             | 9         | 9.38%   |
| Sound                    | 3         | 3.13%   |
| Storage                  | 2         | 2.08%   |
| Network                  | 2         | 2.08%   |
| Storage/ide              | 1         | 1.04%   |
| Storage/ata              | 1         | 1.04%   |
| Net/ethernet             | 1         | 1.04%   |

