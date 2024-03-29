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

Total: 102

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| HP            | EliteBook 2530p             | Notebook    | [e70d97f7d6](https://bsd-hardware.info/?probe=e70d97f7d6) | Mar 09, 2023 |
| Dell          | OptiPlex 3040               | Desktop     | [07abf8e8b2](https://bsd-hardware.info/?probe=07abf8e8b2) | Jan 14, 2023 |
| MSI           | MS-7922                     | Desktop     | [95dbf4f7a8](https://bsd-hardware.info/?probe=95dbf4f7a8) | Dec 19, 2022 |
| Acer          | Aspire XC-105               | Desktop     | [250b12c3f2](https://bsd-hardware.info/?probe=250b12c3f2) | Dec 05, 2022 |
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
| Intel         | NUC5PPYB H76558-102         | Mini pc     | [d9a4a9745d](https://bsd-hardware.info/?probe=d9a4a9745d) | Jul 28, 2022 |
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

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 80        | 86.02%  |
| i386  | 7         | 7.53%   |
| arm64 | 5         | 5.38%   |
| armv7 | 1         | 1.08%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 76        | 81.72%  |
| XFCE         | 9         | 9.68%   |
| fvwm         | 5         | 5.38%   |
| MATE         | 1         | 1.08%   |
| GNOME        | 1         | 1.08%   |
| Console      | 1         | 1.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 72        | 77.42%  |
| Console | 21        | 22.58%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 93        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 77        | 81.91%  |
| ru_RU   | 9         | 9.57%   |
| fr_FR   | 3         | 3.19%   |
| en_US   | 2         | 2.13%   |
| pl_PL   | 1         | 1.06%   |
| en_GB   | 1         | 1.06%   |
| C       | 1         | 1.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 49        | 52.69%  |
| BIOS | 44        | 47.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ffs  | 93        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| MBR  | 53        | 56.99%  |
| GPT  | 40        | 43.01%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 22        | 23.66%  |
| ASUSTek Computer               | 15        | 16.13%  |
| MSI                            | 6         | 6.45%   |
| Unknown                        | 6         | 6.45%   |
| Dell                           | 5         | 5.38%   |
| Hewlett-Packard                | 4         | 4.3%    |
| Gigabyte Technology            | 4         | 4.3%    |
| Intel                          | 3         | 3.23%   |
| Acer                           | 3         | 3.23%   |
| TUXEDO                         | 2         | 2.15%   |
| Panasonic                      | 2         | 2.15%   |
| Matsushita Electric Industrial | 2         | 2.15%   |
| Fujitsu                        | 2         | 2.15%   |
| Biostar                        | 2         | 2.15%   |
| ASRock                         | 2         | 2.15%   |
| Apple                          | 2         | 2.15%   |
| Toshiba                        | 1         | 1.08%   |
| Tactus                         | 1         | 1.08%   |
| Sony                           | 1         | 1.08%   |
| Soekris Engineering            | 1         | 1.08%   |
| Samsung Electronics            | 1         | 1.08%   |
| PC Engines                     | 1         | 1.08%   |
| KOHJINSHA                      | 1         | 1.08%   |
| DEXP                           | 1         | 1.08%   |
| CncTion                        | 1         | 1.08%   |
| Clevo                          | 1         | 1.08%   |
| Alienware                      | 1         | 1.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 6         | 6.45%   |
| Lenovo ThinkPad X200 745969G                | 3         | 3.23%   |
| ASUS PRIME H410M-A                          | 2         | 2.15%   |
| TUXEDO Pulse 15 Gen1                        | 1         | 1.08%   |
| TUXEDO Aura 15 Gen1                         | 1         | 1.08%   |
| Toshiba Satellite BE96-F299                 | 1         | 1.08%   |
| Tactus GeoFlex 110                          | 1         | 1.08%   |
| Sony VPCL22Z1R                              | 1         | 1.08%   |
| Soekris Engineering net6501                 | 1         | 1.08%   |
| Samsung DP700A3D/DM700A3D/DB701A3D/DP700A7D | 1         | 1.08%   |
| PC Engines APU2                             | 1         | 1.08%   |
| Panasonic CF-53AAGHYDM                      | 1         | 1.08%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 1.08%   |
| MSI MS-7C82                                 | 1         | 1.08%   |
| MSI MS-7C37                                 | 1         | 1.08%   |
| MSI MS-7C02                                 | 1         | 1.08%   |
| MSI MS-7922                                 | 1         | 1.08%   |
| MSI MS-6788                                 | 1         | 1.08%   |
| MSI Modern 14 B11MOL                        | 1         | 1.08%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 1.08%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 1.08%   |
| Lenovo Yoga 330-11IGM 81A6                  | 1         | 1.08%   |
| Lenovo ThinkPad Yoga 260 20FES1K81V         | 1         | 1.08%   |
| Lenovo ThinkPad X270 W10DG 20K5S5MD0F       | 1         | 1.08%   |
| Lenovo ThinkPad X260 20F5S10W0H             | 1         | 1.08%   |
| Lenovo ThinkPad X250 20CLS4WV08             | 1         | 1.08%   |
| Lenovo ThinkPad X240 20ALA0AHRT             | 1         | 1.08%   |
| Lenovo ThinkPad X220 429043U                | 1         | 1.08%   |
| Lenovo ThinkPad X200 7458NP9                | 1         | 1.08%   |
| Lenovo ThinkPad X121e 3053A52               | 1         | 1.08%   |
| Lenovo ThinkPad T60 2613CTO                 | 1         | 1.08%   |
| Lenovo ThinkPad T530 24292VG                | 1         | 1.08%   |
| Lenovo ThinkPad T430 2347GZU                | 1         | 1.08%   |
| Lenovo ThinkPad T420s 4174DL7               | 1         | 1.08%   |
| Lenovo ThinkPad T420s 41742BU               | 1         | 1.08%   |
| Lenovo ThinkPad T410 2537N24                | 1         | 1.08%   |
| Lenovo ThinkPad L530 24812TG                | 1         | 1.08%   |
| Lenovo ThinkPad E14 Gen 2 20T6003BRT        | 1         | 1.08%   |
| Lenovo ThinkCentre M93p 10AAS25M00          | 1         | 1.08%   |
| Lenovo IdeaPad S12 20021,2959               | 1         | 1.08%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad                             | 19        | 20.43%  |
| ASUS PRIME                                  | 6         | 6.45%   |
| Unknown                                     | 6         | 6.45%   |
| Acer Aspire                                 | 2         | 2.15%   |
| TUXEDO Pulse                                | 1         | 1.08%   |
| TUXEDO Aura                                 | 1         | 1.08%   |
| Toshiba Satellite                           | 1         | 1.08%   |
| Tactus GeoFlex                              | 1         | 1.08%   |
| Sony VPCL22Z1R                              | 1         | 1.08%   |
| Soekris Engineering net6501                 | 1         | 1.08%   |
| Samsung DP700A3D                            | 1         | 1.08%   |
| PC Engines APU2                             | 1         | 1.08%   |
| Panasonic CF-53AAGHYDM                      | 1         | 1.08%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 1.08%   |
| MSI MS-7C82                                 | 1         | 1.08%   |
| MSI MS-7C37                                 | 1         | 1.08%   |
| MSI MS-7C02                                 | 1         | 1.08%   |
| MSI MS-7922                                 | 1         | 1.08%   |
| MSI MS-6788                                 | 1         | 1.08%   |
| MSI Modern                                  | 1         | 1.08%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 1.08%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 1.08%   |
| Lenovo Yoga                                 | 1         | 1.08%   |
| Lenovo ThinkCentre                          | 1         | 1.08%   |
| Lenovo IdeaPad                              | 1         | 1.08%   |
| KOHJINSHA SH                                | 1         | 1.08%   |
| Intel Q3XXG4-P                              | 1         | 1.08%   |
| Intel NUC5PPYB                              | 1         | 1.08%   |
| Intel DH67BL                                | 1         | 1.08%   |
| HP Pavilion                                 | 1         | 1.08%   |
| HP EliteBook                                | 1         | 1.08%   |
| HP Compaq                                   | 1         | 1.08%   |
| HP 260                                      | 1         | 1.08%   |
| Gigabyte H87-HD3                            | 1         | 1.08%   |
| Gigabyte H81M-S2PV                          | 1         | 1.08%   |
| Gigabyte H81M-S1                            | 1         | 1.08%   |
| Gigabyte G41MT-S2                           | 1         | 1.08%   |
| Fujitsu PRIMERGY                            | 1         | 1.08%   |
| Fujitsu LIFEBOOK                            | 1         | 1.08%   |
| DEXP NAVIS                                  | 1         | 1.08%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 11        | 11.83%  |
| 2018    | 9         | 9.68%   |
| 2009    | 9         | 9.68%   |
| Unknown | 9         | 9.68%   |
| 2011    | 8         | 8.6%    |
| 2010    | 8         | 8.6%    |
| 2020    | 7         | 7.53%   |
| 2022    | 5         | 5.38%   |
| 2019    | 5         | 5.38%   |
| 2012    | 5         | 5.38%   |
| 2014    | 4         | 4.3%    |
| 2016    | 3         | 3.23%   |
| 2015    | 3         | 3.23%   |
| 2013    | 3         | 3.23%   |
| 2007    | 2         | 2.15%   |
| 2006    | 1         | 1.08%   |
| 2002    | 1         | 1.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Desktop    | 50        | 53.76%  |
| Notebook   | 41        | 44.09%  |
| Mini pc    | 1         | 1.08%   |
| All in one | 1         | 1.08%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 91        | 97.85%  |
| Yes  | 2         | 2.15%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 30        | 32.26%  |
| 4.01-8.0    | 21        | 22.58%  |
| 16.01-24.0  | 13        | 13.98%  |
| 3.01-4.0    | 10        | 10.75%  |
| 2.01-3.0    | 6         | 6.45%   |
| 1.01-2.0    | 4         | 4.3%    |
| 0.51-1.0    | 4         | 4.3%    |
| 32.01-64.0  | 2         | 2.15%   |
| 64.01-256.0 | 2         | 2.15%   |
| 24.01-32.0  | 1         | 1.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 83        | 89.25%  |
| 0        | 5         | 5.38%   |
| 0.51-1.0 | 3         | 3.23%   |
| 4.01-8.0 | 1         | 1.08%   |
| 3.01-4.0 | 1         | 1.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 50        | 53.76%  |
| 2      | 23        | 24.73%  |
| 3      | 9         | 9.68%   |
| 4      | 7         | 7.53%   |
| 8      | 1         | 1.08%   |
| 6      | 1         | 1.08%   |
| 5      | 1         | 1.08%   |
| 0      | 1         | 1.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 92        | 98.92%  |
| Yes       | 1         | 1.08%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 79        | 84.95%  |
| No        | 14        | 15.05%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 55        | 59.14%  |
| No        | 38        | 40.86%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 53        | 56.99%  |
| Yes       | 40        | 43.01%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Russia      | 17        | 18.09%  |
| Canada      | 13        | 13.83%  |
| Italy       | 9         | 9.57%   |
| France      | 8         | 8.51%   |
| USA         | 6         | 6.38%   |
| Poland      | 6         | 6.38%   |
| Netherlands | 6         | 6.38%   |
| Germany     | 6         | 6.38%   |
| UK          | 4         | 4.26%   |
| Spain       | 4         | 4.26%   |
| India       | 2         | 2.13%   |
| Egypt       | 2         | 2.13%   |
| Austria     | 2         | 2.13%   |
| Ukraine     | 1         | 1.06%   |
| Slovakia    | 1         | 1.06%   |
| Philippines | 1         | 1.06%   |
| Norway      | 1         | 1.06%   |
| Montserrat  | 1         | 1.06%   |
| Lithuania   | 1         | 1.06%   |
| Czechia     | 1         | 1.06%   |
| Chile       | 1         | 1.06%   |
| Argentina   | 1         | 1.06%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Montreal            | 10        | 10.64%  |
| Vladivostok         | 6         | 6.38%   |
| Poortugaal          | 4         | 4.26%   |
| Milan               | 4         | 4.26%   |
| Gdansk              | 3         | 3.19%   |
| Vienna              | 2         | 2.13%   |
| Paris               | 2         | 2.13%   |
| Ozersk              | 2         | 2.13%   |
| Anglet              | 2         | 2.13%   |
| Amsterdam           | 2         | 2.13%   |
| Wolverhampton       | 1         | 1.06%   |
| West Valley City    | 1         | 1.06%   |
| Valdivia            | 1         | 1.06%   |
| Tanta               | 1         | 1.06%   |
| Tambov              | 1         | 1.06%   |
| Sutton              | 1         | 1.06%   |
| Starogard Gdański  | 1         | 1.06%   |
| St. Albert          | 1         | 1.06%   |
| St Petersburg       | 1         | 1.06%   |
| Springboro          | 1         | 1.06%   |
| Sarnia              | 1         | 1.06%   |
| Rome                | 1         | 1.06%   |
| Reutov              | 1         | 1.06%   |
| Quezon City         | 1         | 1.06%   |
| Pozzuolo Martesana  | 1         | 1.06%   |
| Plymouth            | 1         | 1.06%   |
| Paderborn           | 1         | 1.06%   |
| Ottawa              | 1         | 1.06%   |
| Oslo                | 1         | 1.06%   |
| Orenburg            | 1         | 1.06%   |
| Odessa              | 1         | 1.06%   |
| Oakland             | 1         | 1.06%   |
| Nuremberg           | 1         | 1.06%   |
| Newcastle upon Tyne | 1         | 1.06%   |
| Mumbai              | 1         | 1.06%   |
| Moscow              | 1         | 1.06%   |
| Memphis             | 1         | 1.06%   |
| Memmingen           | 1         | 1.06%   |
| Madrid              | 1         | 1.06%   |
| Mâcon              | 1         | 1.06%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 19        | 21     | 15.32%  |
| NVMe                | 19        | 22     | 15.32%  |
| Samsung Electronics | 15        | 20     | 12.1%   |
| Seagate             | 14        | 18     | 11.29%  |
| Toshiba             | 7         | 11     | 5.65%   |
| Kingston            | 5         | 5      | 4.03%   |
| Hitachi             | 5         | 7      | 4.03%   |
| HGST                | 4         | 4      | 3.23%   |
| SanDisk             | 3         | 3      | 2.42%   |
| OPENBSD             | 3         | 3      | 2.42%   |
| Innostor            | 3         | 3      | 2.42%   |
| Crucial             | 3         | 3      | 2.42%   |
| Corsair             | 3         | 3      | 2.42%   |
| OCZ                 | 2         | 2      | 1.61%   |
| Apacer              | 2         | 2      | 1.61%   |
| A-DATA Technology   | 2         | 2      | 1.61%   |
| XPG                 | 1         | 1      | 0.81%   |
| USB                 | 1         | 1      | 0.81%   |
| StoreJet            | 1         | 1      | 0.81%   |
| SPCC                | 1         | 1      | 0.81%   |
| PNY                 | 1         | 1      | 0.81%   |
| OWC                 | 1         | 1      | 0.81%   |
| LSI                 | 1         | 1      | 0.81%   |
| LDLC F6+            | 1         | 1      | 0.81%   |
| KingSpec            | 1         | 1      | 0.81%   |
| Intel               | 1         | 1      | 0.81%   |
| Hoodisk             | 1         | 1      | 0.81%   |
| GOODRAM             | 1         | 1      | 0.81%   |
| Generic             | 1         | 1      | 0.81%   |
| Fujitsu             | 1         | 1      | 0.81%   |
| AMD                 | 1         | 1      | 0.81%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| NVMe Samsung SSD 980 500GB     | 4         | 3.13%   |
| Samsung HM321HI 320GB          | 3         | 2.34%   |
| OPENBSD SR RAID 1 1TB          | 3         | 2.34%   |
| Innostor SSD 15GB              | 3         | 2.34%   |
| Toshiba HDWG440 4TB            | 2         | 1.56%   |
| Seagate ST1000DM010-2EP102 1TB | 2         | 1.56%   |
| Samsung SSD 860 EVO 500GB      | 2         | 1.56%   |
| OCZ VERTEX3 120GB              | 2         | 1.56%   |
| NVMe WDC PC SN530 SDB 256GB    | 2         | 1.56%   |
| Apacer AS340 240GB             | 2         | 1.56%   |
| XPG SX950U 240GB               | 1         | 0.78%   |
| WDC WD800JD-60LSA5 80GB        | 1         | 0.78%   |
| WDC WD7500BPKX-00HPJT0 752GB   | 1         | 0.78%   |
| WDC WD7500BPKT-75PK4T0 752GB   | 1         | 0.78%   |
| WDC WD7500BPKT-00PK4T0 752GB   | 1         | 0.78%   |
| WDC WD6400AARS-00Y5B1 640GB    | 1         | 0.78%   |
| WDC WD6400AAKS-22A7B0 640GB    | 1         | 0.78%   |
| WDC WD5003AZEX-00K1GA0 500GB   | 1         | 0.78%   |
| WDC WD5003ABYX-01WERA2 500GB   | 1         | 0.78%   |
| WDC WD5000LPLX-00ZNTT0 500GB   | 1         | 0.78%   |
| WDC WD5000AZLX-00K2TA0 500GB   | 1         | 0.78%   |
| WDC WD5000AAKX-60U6AA0 500GB   | 1         | 0.78%   |
| WDC WD40EZAZ-19SF3B0 4TB       | 1         | 0.78%   |
| WDC WD40EFZX-68AWUN0 4TB       | 1         | 0.78%   |
| WDC WD3200BEVE-00A0HT0 320GB   | 1         | 0.78%   |
| WDC WD20PURX-64P6ZY0 2TB       | 1         | 0.78%   |
| WDC WD1600BEVT-22ZCT0 160GB    | 1         | 0.78%   |
| WDC WD10JPVT-75A1YT0 1TB       | 1         | 0.78%   |
| WDC WD10JPLX-00MBPT0 1TB       | 1         | 0.78%   |
| WDC WD10EZEX-00MFCA0 1TB       | 1         | 0.78%   |
| USB SanDisk 3.2Gen1 16GB       | 1         | 0.78%   |
| Toshiba MK6475GSX 640GB        | 1         | 0.78%   |
| Toshiba MK5065GSX 500GB        | 1         | 0.78%   |
| Toshiba MK1629GSGF 160GB       | 1         | 0.78%   |
| Toshiba MG06ACA800E 8TB        | 1         | 0.78%   |
| Toshiba DT01ACA050 500GB       | 1         | 0.78%   |
| StoreJet Transcend 120GB       | 1         | 0.78%   |
| SPCC Solid State Disk 256GB    | 1         | 0.78%   |
| Seagate ST9500420AS 500GB      | 1         | 0.78%   |
| Seagate ST9160821A 160GB       | 1         | 0.78%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 19        | 21     | 25.33%  |
| Seagate             | 14        | 18     | 18.67%  |
| NVMe                | 10        | 11     | 13.33%  |
| Toshiba             | 7         | 11     | 9.33%   |
| Samsung Electronics | 7         | 7      | 9.33%   |
| Hitachi             | 5         | 7      | 6.67%   |
| HGST                | 4         | 4      | 5.33%   |
| OPENBSD             | 3         | 3      | 4%      |
| USB                 | 1         | 1      | 1.33%   |
| StoreJet            | 1         | 1      | 1.33%   |
| LSI                 | 1         | 1      | 1.33%   |
| LDLC F6+            | 1         | 1      | 1.33%   |
| Generic             | 1         | 1      | 1.33%   |
| Fujitsu             | 1         | 1      | 1.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 13     | 17.39%  |
| NVMe                | 6         | 7      | 13.04%  |
| Kingston            | 5         | 5      | 10.87%  |
| SanDisk             | 3         | 3      | 6.52%   |
| Innostor            | 3         | 3      | 6.52%   |
| Crucial             | 3         | 3      | 6.52%   |
| Corsair             | 3         | 3      | 6.52%   |
| OCZ                 | 2         | 2      | 4.35%   |
| Apacer              | 2         | 2      | 4.35%   |
| A-DATA Technology   | 2         | 2      | 4.35%   |
| XPG                 | 1         | 1      | 2.17%   |
| SPCC                | 1         | 1      | 2.17%   |
| PNY                 | 1         | 1      | 2.17%   |
| OWC                 | 1         | 1      | 2.17%   |
| KingSpec            | 1         | 1      | 2.17%   |
| Intel               | 1         | 1      | 2.17%   |
| Hoodisk             | 1         | 1      | 2.17%   |
| GOODRAM             | 1         | 1      | 2.17%   |
| AMD                 | 1         | 1      | 2.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 55        | 88     | 56.7%   |
| SSD  | 39        | 52     | 40.21%  |
| NVMe | 3         | 4      | 3.09%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 84        | 140    | 96.55%  |
| NVMe | 3         | 4      | 3.45%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 67        | 83     | 63.81%  |
| 0.51-1.0   | 27        | 33     | 25.71%  |
| 3.01-4.0   | 5         | 9      | 4.76%   |
| 1.01-2.0   | 5         | 12     | 4.76%   |
| 4.01-10.0  | 1         | 3      | 0.95%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 27        | 29.03%  |
| 251-500        | 25        | 26.88%  |
| 21-50          | 17        | 18.28%  |
| 1-20           | 8         | 8.6%    |
| 51-100         | 8         | 8.6%    |
| 501-1000       | 5         | 5.38%   |
| More than 3000 | 3         | 3.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 78        | 83.87%  |
| 51-100    | 5         | 5.38%   |
| 21-50     | 4         | 4.3%    |
| 101-250   | 3         | 3.23%   |
| 251-500   | 1         | 1.08%   |
| 2001-3000 | 1         | 1.08%   |
| 1001-2000 | 1         | 1.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| OCZ VERTEX3 120GB                 | 2         | 2      | 9.52%   |
| XPG SX950U 240GB                  | 1         | 1      | 4.76%   |
| WDC WD6400AAKS-22A7B0 640GB       | 1         | 1      | 4.76%   |
| WDC WD5000AAKX-60U6AA0 500GB      | 1         | 1      | 4.76%   |
| Toshiba MK6475GSX 640GB           | 1         | 1      | 4.76%   |
| Toshiba MK5065GSX 500GB           | 1         | 1      | 4.76%   |
| Toshiba MK1629GSGF 160GB          | 1         | 1      | 4.76%   |
| Seagate ST9500420AS 500GB         | 1         | 1      | 4.76%   |
| Seagate ST500DM002-1BD142 500GB   | 1         | 1      | 4.76%   |
| Seagate ST380815AS 80GB           | 1         | 1      | 4.76%   |
| Seagate ST3750640NS 752GB         | 1         | 2      | 4.76%   |
| Seagate ST3160212SCE 160GB        | 1         | 1      | 4.76%   |
| Seagate ST250DM000-1BD141 250GB   | 1         | 1      | 4.76%   |
| Seagate ST2000DM006-2DM164 2TB    | 1         | 1      | 4.76%   |
| SanDisk SD7UB3Q256G1001 256GB     | 1         | 1      | 4.76%   |
| Samsung Electronics HD753LJ 752GB | 1         | 1      | 4.76%   |
| Samsung Electronics HD161HJ 160GB | 1         | 1      | 4.76%   |
| HGST HTS721010A9E630 1TB          | 1         | 1      | 4.76%   |
| Corsair Force LS SSD 120GB        | 1         | 1      | 4.76%   |
| A-DATA Technology SP550 480GB     | 1         | 1      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 8      | 30%     |
| Toshiba             | 3         | 3      | 15%     |
| WDC                 | 2         | 2      | 10%     |
| Samsung Electronics | 2         | 2      | 10%     |
| OCZ                 | 2         | 2      | 10%     |
| XPG                 | 1         | 1      | 5%      |
| SanDisk             | 1         | 1      | 5%      |
| HGST                | 1         | 1      | 5%      |
| Corsair             | 1         | 1      | 5%      |
| A-DATA Technology   | 1         | 1      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 8      | 42.86%  |
| Toshiba             | 3         | 3      | 21.43%  |
| WDC                 | 2         | 2      | 14.29%  |
| Samsung Electronics | 2         | 2      | 14.29%  |
| HGST                | 1         | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 16     | 70%     |
| SSD  | 6         | 6      | 30%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                       | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC WD6400AARS-00Y5B1 640GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 61        | 92     | 58.1%   |
| Detected | 24        | 29     | 22.86%  |
| Malfunc  | 19        | 22     | 18.1%   |
| Failed   | 1         | 1      | 0.95%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 63        | 61.17%  |
| AMD                          | 16        | 15.53%  |
| Samsung Electronics          | 6         | 5.83%   |
| SanDisk                      | 4         | 3.88%   |
| KIOXIA                       | 2         | 1.94%   |
| VIA Technologies             | 1         | 0.97%   |
| Toshiba                      | 1         | 0.97%   |
| SK hynix                     | 1         | 0.97%   |
| Shenzhen Longsys Electronics | 1         | 0.97%   |
| Nvidia                       | 1         | 0.97%   |
| Micron/Crucial Technology    | 1         | 0.97%   |
| Marvell Technology Group     | 1         | 0.97%   |
| Lenovo                       | 1         | 0.97%   |
| Kingston Technology Company  | 1         | 0.97%   |
| Broadcom / LSI               | 1         | 0.97%   |
| ASMedia Technology           | 1         | 0.97%   |
| ADATA Technology             | 1         | 0.97%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                  | Computers | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 6         | 5.13%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 6         | 5.13%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 5         | 4.27%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 5         | 4.27%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 5         | 4.27%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 5         | 4.27%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 5         | 4.27%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 4         | 3.42%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 4         | 3.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 4         | 3.42%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 3         | 2.56%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 3         | 2.56%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 3         | 2.56%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 3         | 2.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 2         | 1.71%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 2         | 1.71%   |
| Intel Jasper Lake SATA AHCI Controller                                                 | 2         | 1.71%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 2         | 1.71%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 2         | 1.71%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 2         | 1.71%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 2         | 1.71%   |
| AMD 500 Series Chipset SATA Controller                                                 | 2         | 1.71%   |
| AMD 400 Series Chipset SATA Controller                                                 | 2         | 1.71%   |
| VIA VT6415 PATA IDE Host Controller                                                    | 1         | 0.85%   |
| Toshiba BG3 NVMe SSD Controller                                                        | 1         | 0.85%   |
| SK hynix PC300 NVMe Solid State Drive 256GB                                            | 1         | 0.85%   |
| Shenzhen Longsys unknown                                                               | 1         | 0.85%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 1         | 0.85%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 1         | 0.85%   |
| SanDisk unknown                                                                        | 1         | 0.85%   |
| SanDisk PC SN520 NVMe SSD                                                              | 1         | 0.85%   |
| SanDisk NVMe Controller                                                                | 1         | 0.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 1         | 0.85%   |
| Samsung NVMe SSD Controller 980                                                        | 1         | 0.85%   |
| Nvidia MCP79 AHCI Controller                                                           | 1         | 0.85%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                        | 1         | 0.85%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                       | 1         | 0.85%   |
| Lenovo unknown                                                                         | 1         | 0.85%   |
| KIOXIA NVMe SSD Controller BG4                                                         | 1         | 0.85%   |
| KIOXIA NVMe SSD                                                                        | 1         | 0.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 69        | 63.89%  |
| NVMe | 19        | 17.59%  |
| IDE  | 19        | 17.59%  |
| RAID | 1         | 0.93%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 68        | 73.12%  |
| AMD    | 18        | 19.35%  |
| ARM    | 6         | 6.45%   |
| 11th   | 1         | 1.08%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz                         | 5         | 5.38%   |
| ARM Cortex-A72 r0p3                                       | 4         | 4.3%    |
| Intel Core i5-6300U CPU @ 2.40GHz                         | 3         | 3.23%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz                      | 3         | 3.23%   |
| Intel Core i5-4570 CPU @ 3.20GHz                          | 2         | 2.15%   |
| Intel Core i5 CPU M 520 @ 2.40GHz                         | 2         | 2.15%   |
| Intel Core i3-10100F CPU @ 3.60GHz                        | 2         | 2.15%   |
| Intel Core i3-10100 CPU @ 3.60GHz                         | 2         | 2.15%   |
| AMD Ryzen 7 4700U with Radeon Graphics                    | 2         | 2.15%   |
| Intel Xeon CPU X5690 @ 3.47GHz                            | 1         | 1.08%   |
| Intel Xeon CPU E5520 @ 2.27GHz                            | 1         | 1.08%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz                       | 1         | 1.08%   |
| Intel Pentium Silver N6000 @ 1.10GHz                      | 1         | 1.08%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz                  | 1         | 1.08%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz               | 1         | 1.08%   |
| Intel Pentium CPU N3700 @ 1.60GHz                         | 1         | 1.08%   |
| Intel Pentium 4 Mobile CPU 1.60GHz                        | 1         | 1.08%   |
| Intel Pentium 4 CPU 2.40GHz ("GenuineIntel" 686-class)    | 1         | 1.08%   |
| Intel Genuine processor 600MHz ("GenuineIntel" 686-class) | 1         | 1.08%   |
| Intel Genuine CPU T2300 @ 1.66GHz                         | 1         | 1.08%   |
| Intel Genuine CPU @ 1.00GHz ("GenuineIntel" 686-class)    | 1         | 1.08%   |
| Intel Core i9-10980HK CPU @ 2.40GHz                       | 1         | 1.08%   |
| Intel Core i7-9700K CPU @ 3.60GHz                         | 1         | 1.08%   |
| Intel Core i7-7500U CPU @ 2.70GHz                         | 1         | 1.08%   |
| Intel Core i7-6700 CPU @ 3.40GHz                          | 1         | 1.08%   |
| Intel Core i7-5500U CPU @ 2.40GHz                         | 1         | 1.08%   |
| Intel Core i7-4790 CPU @ 3.60GHz                          | 1         | 1.08%   |
| Intel Core i7-3610QM CPU @ 2.30GHz                        | 1         | 1.08%   |
| Intel Core i7-3520M CPU @ 2.90GHz                         | 1         | 1.08%   |
| Intel Core i7-2670QM CPU @ 2.20GHz                        | 1         | 1.08%   |
| Intel Core i5-8250U CPU @ 1.60GHz                         | 1         | 1.08%   |
| Intel Core i5-5300U CPU @ 2.30GHz                         | 1         | 1.08%   |
| Intel Core i5-4690K CPU @ 3.50GHz                         | 1         | 1.08%   |
| Intel Core i5-4570T CPU @ 2.90GHz                         | 1         | 1.08%   |
| Intel Core i5-3470T CPU @ 2.90GHz                         | 1         | 1.08%   |
| Intel Core i5-3320M CPU @ 2.60GHz                         | 1         | 1.08%   |
| Intel Core i5-3210M CPU @ 2.50GHz                         | 1         | 1.08%   |
| Intel Core i5-10400F CPU @ 2.90GHz                        | 1         | 1.08%   |
| Intel Core i5-10300H CPU @ 2.50GHz                        | 1         | 1.08%   |
| Intel Core i3-7130U CPU @ 2.70GHz                         | 1         | 1.08%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 21        | 22.58%  |
| Intel Core i3           | 9         | 9.68%   |
| Intel Core i7           | 8         | 8.6%    |
| Intel Core 2 Duo        | 7         | 7.53%   |
| ARM Cortex              | 6         | 6.45%   |
| Intel Celeron           | 5         | 5.38%   |
| AMD Ryzen 7             | 4         | 4.3%    |
| Intel Xeon              | 3         | 3.23%   |
| Intel Genuine           | 3         | 3.23%   |
| AMD Ryzen 5             | 3         | 3.23%   |
| Other                   | 2         | 2.15%   |
| Intel Pentium Silver    | 2         | 2.15%   |
| Intel Pentium 4         | 2         | 2.15%   |
| Intel Core 2            | 2         | 2.15%   |
| Intel Atom              | 2         | 2.15%   |
| Intel Pentium Dual-Core | 1         | 1.08%   |
| Intel Pentium           | 1         | 1.08%   |
| Intel Core i9           | 1         | 1.08%   |
| Intel Core 2 Quad       | 1         | 1.08%   |
| AMD Ryzen 9             | 1         | 1.08%   |
| AMD Ryzen 3             | 1         | 1.08%   |
| AMD Phenom II X4        | 1         | 1.08%   |
| AMD GX                  | 1         | 1.08%   |
| AMD E                   | 1         | 1.08%   |
| AMD Athlon II X4        | 1         | 1.08%   |
| AMD Athlon II X2        | 1         | 1.08%   |
| AMD Athlon              | 1         | 1.08%   |
| AMD A6                  | 1         | 1.08%   |
| AMD A4                  | 1         | 1.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 28        | 30.11%  |
| 4       | 26        | 27.96%  |
| Unknown | 25        | 26.88%  |
| 8       | 5         | 5.38%   |
| 12      | 3         | 3.23%   |
| 1       | 3         | 3.23%   |
| 32      | 1         | 1.08%   |
| 16      | 1         | 1.08%   |
| 6       | 1         | 1.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 66        | 70.97%  |
| Unknown | 25        | 26.88%  |
| 2       | 2         | 2.15%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 36        | 38.71%  |
| 1       | 29        | 31.18%  |
| Unknown | 28        | 30.11%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 12        | 12.9%   |
| Penryn        | 9         | 9.68%   |
| IvyBridge     | 7         | 7.53%   |
| Haswell       | 7         | 7.53%   |
| SandyBridge   | 6         | 6.45%   |
| CometLake     | 6         | 6.45%   |
| Skylake       | 5         | 5.38%   |
| Zen 2         | 4         | 4.3%    |
| KabyLake      | 4         | 4.3%    |
| K10           | 4         | 4.3%    |
| Westmere      | 3         | 3.23%   |
| Broadwell     | 3         | 3.23%   |
| Bonnell       | 3         | 3.23%   |
| Zen 3         | 2         | 2.15%   |
| Silvermont    | 2         | 2.15%   |
| P6            | 2         | 2.15%   |
| NetBurst      | 2         | 2.15%   |
| Goldmont plus | 2         | 2.15%   |
| Core          | 2         | 2.15%   |
| Zen+          | 1         | 1.08%   |
| Zen           | 1         | 1.08%   |
| Puma          | 1         | 1.08%   |
| Nehalem       | 1         | 1.08%   |
| K10 Llano     | 1         | 1.08%   |
| Jaguar        | 1         | 1.08%   |
| Goldmont      | 1         | 1.08%   |
| Bobcat        | 1         | 1.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 49        | 54.44%  |
| AMD                        | 30        | 33.33%  |
| Nvidia                     | 9         | 10%     |
| Matrox Electronics Systems | 1         | 1.11%   |
| ASPEED Technology          | 1         | 1.11%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 6.25%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 5.21%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4         | 4.17%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 4.17%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 4.17%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 3.13%   |
| Intel HD Graphics 5500                                                                   | 3         | 3.13%   |
| AMD Renoir                                                                               | 3         | 3.13%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 3         | 3.13%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 2.08%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 2.08%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 2.08%   |
| Intel HD Graphics 620                                                                    | 2         | 2.08%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 2.08%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 2.08%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 2.08%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 2         | 2.08%   |
| AMD RS880 [Radeon HD 4200]                                                               | 2         | 2.08%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 2         | 2.08%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2         | 2.08%   |
| Nvidia TU117M                                                                            | 1         | 1.04%   |
| Nvidia NV28 [GeForce4 Ti 4200 AGP 8x]                                                    | 1         | 1.04%   |
| Nvidia GM108M [GeForce 940M]                                                             | 1         | 1.04%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 1.04%   |
| Nvidia GF108M [NVS 5400M]                                                                | 1         | 1.04%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 1         | 1.04%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 1         | 1.04%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 1.04%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 1         | 1.04%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 1.04%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 1         | 1.04%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.04%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 1.04%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1         | 1.04%   |
| Intel HD Graphics 530                                                                    | 1         | 1.04%   |
| Intel HD Graphics 500                                                                    | 1         | 1.04%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 1.04%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 1.04%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.04%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 34        | 36.56%  |
| 1 x AMD        | 27        | 29.03%  |
| 2 x Intel      | 10        | 10.75%  |
| Other          | 8         | 8.6%    |
| 1 x Nvidia     | 5         | 5.38%   |
| Intel + Nvidia | 3         | 3.23%   |
| Intel + AMD    | 2         | 2.15%   |
| 2 x Nvidia     | 1         | 1.08%   |
| 2 x AMD        | 1         | 1.08%   |
| 1 x Matrox     | 1         | 1.08%   |
| 1 x ASPEED     | 1         | 1.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 79        | 84.95%  |
| Unknown | 14        | 15.05%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 93        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Philips                 | 8         | 14.04%  |
| Samsung Electronics     | 6         | 10.53%  |
| Lenovo                  | 6         | 10.53%  |
| LG Display              | 5         | 8.77%   |
| BOE                     | 4         | 7.02%   |
| AU Optronics            | 4         | 7.02%   |
| Dell                    | 3         | 5.26%   |
| Chimei Innolux          | 3         | 5.26%   |
| Acer                    | 3         | 5.26%   |
| ViewSonic               | 2         | 3.51%   |
| MSI                     | 2         | 3.51%   |
| Chi Mei Optoelectronics | 2         | 3.51%   |
| TRU                     | 1         | 1.75%   |
| PANDA                   | 1         | 1.75%   |
| InfoVision              | 1         | 1.75%   |
| Hewlett-Packard         | 1         | 1.75%   |
| Goldstar                | 1         | 1.75%   |
| BenQ                    | 1         | 1.75%   |
| Apple                   | 1         | 1.75%   |
| AOC                     | 1         | 1.75%   |
| Ancor Communications    | 1         | 1.75%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                    | 7         | 12.28%  |
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch                  | 3         | 5.26%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch              | 2         | 3.51%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 2         | 3.51%   |
| Acer V223HQ ACR0070 1920x1080 470x270mm 21.3-inch                        | 2         | 3.51%   |
| ViewSonic LCD Monitor VSCD22B 1920x1080 520x290mm 23.4-inch              | 1         | 1.75%   |
| ViewSonic LCD Monitor VSCC42B 1920x1080 480x270mm 21.7-inch              | 1         | 1.75%   |
| TRU LCD Monitor TRU235C 1366x768 260x140mm 11.6-inch                     | 1         | 1.75%   |
| Samsung Electronics SyncMaster SAM03CF 1280x1024 340x270mm 17.1-inch     | 1         | 1.75%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 530x300mm 24.0-inch        | 1         | 1.75%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch     | 1         | 1.75%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 310x170mm 13.9-inch     | 1         | 1.75%   |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch   | 1         | 1.75%   |
| Samsung Electronics DM700A-D SEM0324 1920x1080 520x290mm 23.4-inch       | 1         | 1.75%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                  | 1         | 1.75%   |
| PANDA LM133LF1L01 NCP13FB 1920x1080 290x170mm 13.2-inch                  | 1         | 1.75%   |
| MSI MP242 MSI30A1 1920x1080 530x300mm 24.0-inch                          | 1         | 1.75%   |
| MSI MAG241C MSI3EA2 1920x1080 520x290mm 23.4-inch                        | 1         | 1.75%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch             | 1         | 1.75%   |
| LG Display LCD Monitor LGD0215 1920x1080 350x190mm 15.7-inch             | 1         | 1.75%   |
| LG Display LCD Monitor LGD01AB 1280x800 260x160mm 12.0-inch              | 1         | 1.75%   |
| Lenovo LEN S24e-10 LEN61CA 1920x1080 530x300mm 24.0-inch                 | 1         | 1.75%   |
| Lenovo LCD Monitor LEN4022 1400x1050 290x210mm 14.1-inch                 | 1         | 1.75%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch                  | 1         | 1.75%   |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch              | 1         | 1.75%   |
| Hewlett-Packard x23LED HWP2912 1920x1080 510x290mm 23.1-inch             | 1         | 1.75%   |
| Goldstar L1752T GSM4434 1280x1024 340x270mm 17.1-inch                    | 1         | 1.75%   |
| Dell LCD Monitor DELF003 1440x900 410x260mm 19.1-inch                    | 1         | 1.75%   |
| Dell E1916H DELF064 1366x768 410x230mm 18.5-inch                         | 1         | 1.75%   |
| Dell 2001FP DELA007 1600x1200 410x310mm 20.2-inch                        | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 380x210mm 17.1-inch          | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN15D7 1920x1080 340x190mm 15.3-inch         | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN152E 1920x1080 340x190mm 15.3-inch         | 1         | 1.75%   |
| BOE LCD Monitor BOE0900 1920x1080 340x190mm 15.3-inch                    | 1         | 1.75%   |
| BOE LCD Monitor BOE08D7 1920x1080 310x170mm 13.9-inch                    | 1         | 1.75%   |
| BOE LCD Monitor BOE07A5 1366x768 340x190mm 15.3-inch                     | 1         | 1.75%   |
| BOE LCD Monitor BOE075A 1366x768 310x170mm 13.9-inch                     | 1         | 1.75%   |
| BenQ G2255 BNQ78B7 1920x1080 480x270mm 21.7-inch                         | 1         | 1.75%   |
| AU Optronics LCD Monitor AUODF87 1920x1080 340x190mm 15.3-inch           | 1         | 1.75%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch            | 1         | 1.75%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 26        | 47.27%  |
| 1366x768 (WXGA)  | 12        | 21.82%  |
| 1280x800 (WXGA)  | 6         | 10.91%  |
| 1600x900 (HD+)   | 3         | 5.45%   |
| 1440x900 (WXGA+) | 2         | 3.64%   |
| 1280x1024 (SXGA) | 2         | 3.64%   |
| 3840x2160 (4K)   | 1         | 1.82%   |
| 3440x1440        | 1         | 1.82%   |
| 1600x1200        | 1         | 1.82%   |
| 1400x1050        | 1         | 1.82%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 21     | 11        | 19.64%  |
| 15     | 9         | 16.07%  |
| 12     | 9         | 16.07%  |
| 13     | 7         | 12.5%   |
| 24     | 4         | 7.14%   |
| 23     | 4         | 7.14%   |
| 17     | 3         | 5.36%   |
| 19     | 2         | 3.57%   |
| 11     | 2         | 3.57%   |
| 54     | 1         | 1.79%   |
| 34     | 1         | 1.79%   |
| 20     | 1         | 1.79%   |
| 18     | 1         | 1.79%   |
| 14     | 1         | 1.79%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 16        | 28.57%  |
| 401-500     | 15        | 26.79%  |
| 201-300     | 14        | 25%     |
| 501-600     | 8         | 14.29%  |
| 701-800     | 1         | 1.79%   |
| 351-400     | 1         | 1.79%   |
| 1001-1500   | 1         | 1.79%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 42        | 76.36%  |
| 16/10 | 7         | 12.73%  |
| 5/4   | 2         | 3.64%   |
| 4/3   | 2         | 3.64%   |
| 3/2   | 1         | 1.82%   |
| 21/9  | 1         | 1.82%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 16        | 29.09%  |
| 61-70          | 9         | 16.36%  |
| 81-90          | 6         | 10.91%  |
| 91-100         | 6         | 10.91%  |
| 151-200        | 5         | 9.09%   |
| 101-110        | 4         | 7.27%   |
| 141-150        | 3         | 5.45%   |
| 51-60          | 2         | 3.64%   |
| More than 1000 | 1         | 1.82%   |
| 71-80          | 1         | 1.82%   |
| 351-500        | 1         | 1.82%   |
| 121-130        | 1         | 1.82%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 21        | 38.18%  |
| 51-100  | 17        | 30.91%  |
| 101-120 | 16        | 29.09%  |
| 161-240 | 1         | 1.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 65        | 69.89%  |
| 0     | 26        | 27.96%  |
| 3     | 1         | 1.08%   |
| 2     | 1         | 1.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 49        | 42.24%  |
| Realtek Semiconductor             | 42        | 36.21%  |
| Qualcomm Atheros                  | 7         | 6.03%   |
| Broadcom                          | 4         | 3.45%   |
| Qualcomm Atheros Communications   | 3         | 2.59%   |
| Ericsson Business Mobile Networks | 3         | 2.59%   |
| Sierra Wireless                   | 1         | 0.86%   |
| Qcom                              | 1         | 0.86%   |
| Nvidia                            | 1         | 0.86%   |
| Marvell Technology Group          | 1         | 0.86%   |
| Hewlett-Packard                   | 1         | 0.86%   |
| Dell                              | 1         | 0.86%   |
| AVM                               | 1         | 0.86%   |
| ASUSTek Computer                  | 1         | 0.86%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 32        | 21.33%  |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 7         | 4.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 7         | 4.67%   |
| Intel Wi-Fi 6 AX200                                                         | 6         | 4%      |
| Intel 82567LM Gigabit Network Connection                                    | 5         | 3.33%   |
| Intel Ultimate N WiFi Link 5300                                             | 4         | 2.67%   |
| Intel 82574L Gigabit Network Connection                                     | 4         | 2.67%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 3         | 2%      |
| Qualcomm Atheros AR9271 802.11n                                             | 3         | 2%      |
| Intel Wireless 8260                                                         | 3         | 2%      |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 3         | 2%      |
| Intel I210 Gigabit Network Connection                                       | 3         | 2%      |
| Intel Ethernet Connection I219-LM                                           | 3         | 2%      |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 2         | 1.33%   |
| Realtek RTL8125 2.5GbE Controller                                           | 2         | 1.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                       | 2         | 1.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 2         | 1.33%   |
| Intel Wireless 7265                                                         | 2         | 1.33%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                      | 2         | 1.33%   |
| Intel I211 Gigabit Network Connection                                       | 2         | 1.33%   |
| Intel Centrino Advanced-N 6200                                              | 2         | 1.33%   |
| Intel 82577LM Gigabit Network Connection                                    | 2         | 1.33%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III | 2         | 1.33%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                      | 2         | 1.33%   |
| Sierra Wireless EM7455                                                      | 1         | 0.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 1         | 0.67%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                             | 1         | 0.67%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                             | 1         | 0.67%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                 | 1         | 0.67%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                            | 1         | 0.67%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                            | 1         | 0.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 1         | 0.67%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                            | 1         | 0.67%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 1         | 0.67%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                               | 1         | 0.67%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                               | 1         | 0.67%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet              | 1         | 0.67%   |
| Qcom RT73 USB Wireless LAN Card                                             | 1         | 0.67%   |
| Nvidia MCP79 Ethernet                                                       | 1         | 0.67%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                     | 1         | 0.67%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 38        | 64.41%  |
| Realtek Semiconductor           | 6         | 10.17%  |
| Qualcomm Atheros                | 5         | 8.47%   |
| Qualcomm Atheros Communications | 3         | 5.08%   |
| Broadcom                        | 3         | 5.08%   |
| Sierra Wireless                 | 1         | 1.69%   |
| Qcom                            | 1         | 1.69%   |
| Dell                            | 1         | 1.69%   |
| ASUSTek Computer                | 1         | 1.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 7         | 11.86%  |
| Intel Wi-Fi 6 AX200                                            | 6         | 10.17%  |
| Intel Ultimate N WiFi Link 5300                                | 4         | 6.78%   |
| Qualcomm Atheros AR9271 802.11n                                | 3         | 5.08%   |
| Intel Wireless 8260                                            | 3         | 5.08%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 3         | 5.08%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 3.39%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 3.39%   |
| Intel Wireless 7265                                            | 2         | 3.39%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 3.39%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 3.39%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 2         | 3.39%   |
| Sierra Wireless EM7455                                         | 1         | 1.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.69%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 1.69%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1         | 1.69%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 1.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 1.69%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 1.69%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 1.69%   |
| Qcom RT73 USB Wireless LAN Card                                | 1         | 1.69%   |
| Intel Wireless 7260                                            | 1         | 1.69%   |
| Intel Wireless 3165                                            | 1         | 1.69%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 1         | 1.69%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 1.69%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 1.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 1.69%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 1.69%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 1.69%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 1         | 1.69%   |
| Dell Wireless 5550 HSPA+ Mini-Card Network Adapter             | 1         | 1.69%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 1         | 1.69%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                            | 1         | 1.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 41        | 50.62%  |
| Intel                    | 33        | 40.74%  |
| Qualcomm Atheros         | 3         | 3.7%    |
| Broadcom                 | 2         | 2.47%   |
| Nvidia                   | 1         | 1.23%   |
| Marvell Technology Group | 1         | 1.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 32        | 37.65%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 7         | 8.24%   |
| Intel 82567LM Gigabit Network Connection                                      | 5         | 5.88%   |
| Intel 82574L Gigabit Network Connection                                       | 4         | 4.71%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 3         | 3.53%   |
| Intel I210 Gigabit Network Connection                                         | 3         | 3.53%   |
| Intel Ethernet Connection I219-LM                                             | 3         | 3.53%   |
| Realtek RTL8125 2.5GbE Controller                                             | 2         | 2.35%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2         | 2.35%   |
| Intel I211 Gigabit Network Connection                                         | 2         | 2.35%   |
| Intel 82577LM Gigabit Network Connection                                      | 2         | 2.35%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                              | 1         | 1.18%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 1         | 1.18%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1         | 1.18%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                 | 1         | 1.18%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1         | 1.18%   |
| Nvidia MCP79 Ethernet                                                         | 1         | 1.18%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 1         | 1.18%   |
| Intel Platform Controller Hub EG20T Gigabit Ethernet Controller               | 1         | 1.18%   |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller                           | 1         | 1.18%   |
| Intel Ethernet Controller I225-V                                              | 1         | 1.18%   |
| Intel Ethernet Connection I218-LM                                             | 1         | 1.18%   |
| Intel Ethernet Connection I217-LM                                             | 1         | 1.18%   |
| Intel Ethernet Connection (3) I218-LM                                         | 1         | 1.18%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1         | 1.18%   |
| Intel 82579V Gigabit Network Connection                                       | 1         | 1.18%   |
| Intel 82575EB Gigabit Network Connection                                      | 1         | 1.18%   |
| Intel 82573L Gigabit Ethernet Controller                                      | 1         | 1.18%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 1.18%   |
| Broadcom NetXtreme BCM5753M Gigabit Ethernet PCI Express                      | 1         | 1.18%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                           | 1         | 1.18%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 79        | 56.43%  |
| WiFi     | 55        | 39.29%  |
| Unknown  | 4         | 2.86%   |
| Modem    | 2         | 1.43%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 42        | 50.6%   |
| WiFi     | 41        | 49.4%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 46        | 49.46%  |
| 1     | 31        | 33.33%  |
| 0     | 7         | 7.53%   |
| 3     | 5         | 5.38%   |
| 5     | 2         | 2.15%   |
| 4     | 2         | 2.15%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 92        | 98.92%  |
| Yes  | 1         | 1.08%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 18        | 45%     |
| Broadcom                        | 9         | 22.5%   |
| Hewlett-Packard                 | 2         | 5%      |
| Foxconn / Hon Hai               | 2         | 5%      |
| Apple                           | 2         | 5%      |
| Alps Electric                   | 2         | 5%      |
| Realtek Semiconductor           | 1         | 2.5%    |
| Qualcomm Atheros Communications | 1         | 2.5%    |
| IMC Networks                    | 1         | 2.5%    |
| Cambridge Silicon Radio         | 1         | 2.5%    |
| ASUSTek Computer                | 1         | 2.5%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 7         | 17.5%   |
| Intel AX200 Bluetooth                                       | 4         | 10%     |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 3         | 7.5%    |
| Broadcom BCM2045B (BDC-2.1)                                 | 3         | 7.5%    |
| Intel AX201 Bluetooth                                       | 2         | 5%      |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 2         | 5%      |
| Alps Electric UGTZ4 Bluetooth                               | 2         | 5%      |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 2.5%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 2.5%    |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 2.5%    |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 2.5%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 1         | 2.5%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 1         | 2.5%    |
| Intel AX210 Bluetooth                                       | 1         | 2.5%    |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 2.5%    |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 2.5%    |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device    | 1         | 2.5%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1         | 2.5%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 1         | 2.5%    |
| Broadcom BCM2046 Bluetooth Device                           | 1         | 2.5%    |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 1         | 2.5%    |
| ASUS Broadcom Bluetooth 2.1                                 | 1         | 2.5%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1         | 2.5%    |
| Apple Bluetooth Host Controller                             | 1         | 2.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 63        | 64.29%  |
| AMD                 | 27        | 27.55%  |
| Nvidia              | 6         | 6.12%   |
| Creative Labs       | 1         | 1.02%   |
| C-Media Electronics | 1         | 1.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 6.61%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7         | 5.79%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 6         | 4.96%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 4.96%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 4.96%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 4.96%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 4.13%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5         | 4.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 3.31%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 4         | 3.31%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4         | 3.31%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 3.31%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 2.48%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 2.48%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 2.48%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 1.65%   |
| Intel Jasper Lake HD Audio                                                                        | 2         | 1.65%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.65%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 1.65%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 1.65%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 2         | 1.65%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.65%   |
| AMD Navi 10 HDMI Audio                                                                            | 2         | 1.65%   |
| AMD FCH Azalia Controller                                                                         | 2         | 1.65%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 1.65%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.83%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.83%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.83%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 0.83%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 0.83%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 0.83%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.83%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 0.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.83%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.83%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 1         | 0.83%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1         | 0.83%   |
| Intel 82801CA/CAM AC'97 Audio Controller                                                          | 1         | 0.83%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 0.83%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.83%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


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

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


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

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind  | Computers | Percent |
|-------|-----------|---------|
| DDR3  | 10        | 71.43%  |
| SDRAM | 2         | 14.29%  |
| DDR4  | 1         | 7.14%   |
| DDR2  | 1         | 7.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 12        | 85.71%  |
| DIMM   | 2         | 14.29%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


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

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


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

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 13        | 44.83%  |
| Bison Electronics                      | 4         | 13.79%  |
| Ricoh                                  | 2         | 6.9%    |
| Realtek Semiconductor                  | 2         | 6.9%    |
| Tripath Technology                     | 1         | 3.45%   |
| Sunplus Innovation Technology          | 1         | 3.45%   |
| Silicon Motion                         | 1         | 3.45%   |
| Quanta                                 | 1         | 3.45%   |
| Lite-On Technology                     | 1         | 3.45%   |
| Denron                                 | 1         | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.45%   |
| Alcor Micro                            | 1         | 3.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony integrated camera                                                  | 5         | 17.24%  |
| Chicony Integrated Camera [ThinkPad]                                       | 2         | 6.9%    |
| Tripath PC Camera                                                          | 1         | 3.45%   |
| Sunplus Integrated HD Webcam                                               | 1         | 3.45%   |
| Silicon Motion WebCam SC-10IRQ12340N                                       | 1         | 3.45%   |
| Ricoh USB2.0 Camera                                                        | 1         | 3.45%   |
| Ricoh Integrated Webcam                                                    | 1         | 3.45%   |
| Realtek USB Camera                                                         | 1         | 3.45%   |
| Realtek Integrated_Webcam_HD                                               | 1         | 3.45%   |
| Quanta VGA WebCam                                                          | 1         | 3.45%   |
| Lite-On Integrated Camera                                                  | 1         | 3.45%   |
| Denron Corp., 2M Front Camera                                              | 1         | 3.45%   |
| Chicony Lenovo Integrated Camera UVC                                       | 1         | 3.45%   |
| Chicony Lenovo Integrated Camera (0.3MP)                                   | 1         | 3.45%   |
| Chicony Integrated IR Camera                                               | 1         | 3.45%   |
| Chicony HP Webcam [2 MP]                                                   | 1         | 3.45%   |
| Chicony FJ Camera                                                          | 1         | 3.45%   |
| Chicony 2.0M UVC Webcam / CNF7129                                          | 1         | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 3.45%   |
| Bison Integrated Camera                                                    | 1         | 3.45%   |
| Bison HD Webcam                                                            | 1         | 3.45%   |
| Bison EasyCamera                                                           | 1         | 3.45%   |
| Bison BisonCam, NB Pro                                                     | 1         | 3.45%   |
| Alcor Micro ASUS USB2.0 WebCam                                             | 1         | 3.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Validity Sensors   | 4         | 33.33%  |
| Upek               | 4         | 33.33%  |
| AuthenTec          | 3         | 25%     |
| STMicroelectronics | 1         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 4         | 33.33%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 8.33%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 8.33%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 8.33%   |
| Validity Sensors Synaptics WBDI                        | 1         | 8.33%   |
| STMicroelectronics Fingerprint Reader                  | 1         | 8.33%   |
| AuthenTec AES2810                                      | 1         | 8.33%   |
| AuthenTec AES2660                                      | 1         | 8.33%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 8.33%   |

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
| 1     | 43        | 46.24%  |
| 0     | 25        | 26.88%  |
| 2     | 16        | 17.2%   |
| 3     | 7         | 7.53%   |
| 5     | 1         | 1.08%   |
| 4     | 1         | 1.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 52        | 51.49%  |
| Graphics card            | 18        | 17.82%  |
| Firewire controller      | 11        | 10.89%  |
| Net/wireless             | 10        | 9.9%    |
| Sound                    | 3         | 2.97%   |
| Storage                  | 2         | 1.98%   |
| Network                  | 2         | 1.98%   |
| Storage/ide              | 1         | 0.99%   |
| Storage/ata              | 1         | 0.99%   |
| Net/ethernet             | 1         | 0.99%   |

