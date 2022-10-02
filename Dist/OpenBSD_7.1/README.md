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

Total: 89

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
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
| amd64 | 71        | 85.54%  |
| i386  | 6         | 7.23%   |
| arm64 | 5         | 6.02%   |
| armv7 | 1         | 1.2%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 67        | 80.72%  |
| XFCE         | 8         | 9.64%   |
| fvwm         | 5         | 6.02%   |
| MATE         | 1         | 1.2%    |
| GNOME        | 1         | 1.2%    |
| Console      | 1         | 1.2%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 64        | 77.11%  |
| Console | 19        | 22.89%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 83        | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 70        | 84.34%  |
| ru_RU   | 9         | 10.84%  |
| pl_PL   | 1         | 1.2%    |
| en_US   | 1         | 1.2%    |
| en_GB   | 1         | 1.2%    |
| C       | 1         | 1.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 45        | 54.22%  |
| BIOS | 38        | 45.78%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ffs  | 83        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| MBR  | 46        | 55.42%  |
| GPT  | 37        | 44.58%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 20        | 24.1%   |
| ASUSTek Computer               | 15        | 18.07%  |
| Unknown                        | 6         | 7.23%   |
| MSI                            | 5         | 6.02%   |
| Dell                           | 5         | 6.02%   |
| Gigabyte Technology            | 4         | 4.82%   |
| Intel                          | 3         | 3.61%   |
| TUXEDO                         | 2         | 2.41%   |
| Panasonic                      | 2         | 2.41%   |
| Matsushita Electric Industrial | 2         | 2.41%   |
| Fujitsu                        | 2         | 2.41%   |
| Biostar                        | 2         | 2.41%   |
| Apple                          | 2         | 2.41%   |
| Acer                           | 2         | 2.41%   |
| Toshiba                        | 1         | 1.2%    |
| Tactus                         | 1         | 1.2%    |
| Sony                           | 1         | 1.2%    |
| Samsung Electronics            | 1         | 1.2%    |
| PC Engines                     | 1         | 1.2%    |
| KOHJINSHA                      | 1         | 1.2%    |
| Hewlett-Packard                | 1         | 1.2%    |
| DEXP                           | 1         | 1.2%    |
| CncTion                        | 1         | 1.2%    |
| ASRock                         | 1         | 1.2%    |
| Alienware                      | 1         | 1.2%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 6         | 7.23%   |
| Lenovo ThinkPad X200 745969G                | 3         | 3.61%   |
| ASUS PRIME H410M-A                          | 2         | 2.41%   |
| TUXEDO Pulse 15 Gen1                        | 1         | 1.2%    |
| TUXEDO Aura 15 Gen1                         | 1         | 1.2%    |
| Toshiba Satellite BE96-F299                 | 1         | 1.2%    |
| Tactus GeoFlex 110                          | 1         | 1.2%    |
| Sony VPCL22Z1R                              | 1         | 1.2%    |
| Samsung DP700A3D/DM700A3D/DB701A3D/DP700A7D | 1         | 1.2%    |
| PC Engines APU2                             | 1         | 1.2%    |
| Panasonic CF-53AAGHYDM                      | 1         | 1.2%    |
| Panasonic CF-52PFPBSFQ                      | 1         | 1.2%    |
| MSI MS-7C82                                 | 1         | 1.2%    |
| MSI MS-7C37                                 | 1         | 1.2%    |
| MSI MS-7C02                                 | 1         | 1.2%    |
| MSI MS-6788                                 | 1         | 1.2%    |
| MSI Modern 14 B11MOL                        | 1         | 1.2%    |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 1.2%    |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 1.2%    |
| Lenovo Yoga 330-11IGM 81A6                  | 1         | 1.2%    |
| Lenovo ThinkPad Yoga 260 20FES1K81V         | 1         | 1.2%    |
| Lenovo ThinkPad X270 W10DG 20K5S5MD0F       | 1         | 1.2%    |
| Lenovo ThinkPad X260 20F5S10W0H             | 1         | 1.2%    |
| Lenovo ThinkPad X250 20CLS4WV08             | 1         | 1.2%    |
| Lenovo ThinkPad X240 20ALA0AHRT             | 1         | 1.2%    |
| Lenovo ThinkPad X220 429043U                | 1         | 1.2%    |
| Lenovo ThinkPad X200 7458NP9                | 1         | 1.2%    |
| Lenovo ThinkPad X121e 3053A52               | 1         | 1.2%    |
| Lenovo ThinkPad T530 24292VG                | 1         | 1.2%    |
| Lenovo ThinkPad T430 2347GZU                | 1         | 1.2%    |
| Lenovo ThinkPad T420s 41742BU               | 1         | 1.2%    |
| Lenovo ThinkPad T410 2537N24                | 1         | 1.2%    |
| Lenovo ThinkPad L530 24812TG                | 1         | 1.2%    |
| Lenovo ThinkPad E14 Gen 2 20T6003BRT        | 1         | 1.2%    |
| Lenovo ThinkCentre M93p 10AAS25M00          | 1         | 1.2%    |
| Lenovo IdeaPad S12 20021,2959               | 1         | 1.2%    |
| KOHJINSHA SH series                         | 1         | 1.2%    |
| Intel Q3XXG4-P                              | 1         | 1.2%    |
| Intel NUC5PPYB                              | 1         | 1.2%    |
| Intel DH67BL                                | 1         | 1.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad                             | 17        | 20.48%  |
| ASUS PRIME                                  | 6         | 7.23%   |
| Unknown                                     | 6         | 7.23%   |
| TUXEDO Pulse                                | 1         | 1.2%    |
| TUXEDO Aura                                 | 1         | 1.2%    |
| Toshiba Satellite                           | 1         | 1.2%    |
| Tactus GeoFlex                              | 1         | 1.2%    |
| Sony VPCL22Z1R                              | 1         | 1.2%    |
| Samsung DP700A3D                            | 1         | 1.2%    |
| PC Engines APU2                             | 1         | 1.2%    |
| Panasonic CF-53AAGHYDM                      | 1         | 1.2%    |
| Panasonic CF-52PFPBSFQ                      | 1         | 1.2%    |
| MSI MS-7C82                                 | 1         | 1.2%    |
| MSI MS-7C37                                 | 1         | 1.2%    |
| MSI MS-7C02                                 | 1         | 1.2%    |
| MSI MS-6788                                 | 1         | 1.2%    |
| MSI Modern                                  | 1         | 1.2%    |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 1.2%    |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 1.2%    |
| Lenovo Yoga                                 | 1         | 1.2%    |
| Lenovo ThinkCentre                          | 1         | 1.2%    |
| Lenovo IdeaPad                              | 1         | 1.2%    |
| KOHJINSHA SH                                | 1         | 1.2%    |
| Intel Q3XXG4-P                              | 1         | 1.2%    |
| Intel NUC5PPYB                              | 1         | 1.2%    |
| Intel DH67BL                                | 1         | 1.2%    |
| HP Pavilion                                 | 1         | 1.2%    |
| Gigabyte H87-HD3                            | 1         | 1.2%    |
| Gigabyte H81M-S2PV                          | 1         | 1.2%    |
| Gigabyte H81M-S1                            | 1         | 1.2%    |
| Gigabyte G41MT-S2                           | 1         | 1.2%    |
| Fujitsu PRIMERGY                            | 1         | 1.2%    |
| Fujitsu LIFEBOOK                            | 1         | 1.2%    |
| DEXP NAVIS                                  | 1         | 1.2%    |
| Dell XPS                                    | 1         | 1.2%    |
| Dell Vostro                                 | 1         | 1.2%    |
| Dell OptiPlex                               | 1         | 1.2%    |
| Dell Inspiron                               | 1         | 1.2%    |
| Dell G5                                     | 1         | 1.2%    |
| CncTion N5105-4L                            | 1         | 1.2%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 11        | 13.25%  |
| 2020    | 8         | 9.64%   |
| 2009    | 8         | 9.64%   |
| Unknown | 8         | 9.64%   |
| 2018    | 7         | 8.43%   |
| 2011    | 7         | 8.43%   |
| 2010    | 7         | 8.43%   |
| 2019    | 5         | 6.02%   |
| 2022    | 4         | 4.82%   |
| 2012    | 4         | 4.82%   |
| 2016    | 3         | 3.61%   |
| 2015    | 3         | 3.61%   |
| 2014    | 3         | 3.61%   |
| 2013    | 2         | 2.41%   |
| 2007    | 1         | 1.2%    |
| 2006    | 1         | 1.2%    |
| 2002    | 1         | 1.2%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Desktop    | 42        | 50.6%   |
| Notebook   | 39        | 46.99%  |
| Mini pc    | 1         | 1.2%    |
| All in one | 1         | 1.2%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 82        | 98.8%   |
| Yes  | 1         | 1.2%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 27        | 32.53%  |
| 4.01-8.0    | 21        | 25.3%   |
| 16.01-24.0  | 12        | 14.46%  |
| 3.01-4.0    | 7         | 8.43%   |
| 2.01-3.0    | 6         | 7.23%   |
| 0.51-1.0    | 3         | 3.61%   |
| 32.01-64.0  | 2         | 2.41%   |
| 64.01-256.0 | 2         | 2.41%   |
| 1.01-2.0    | 2         | 2.41%   |
| 24.01-32.0  | 1         | 1.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 74        | 89.16%  |
| 0        | 4         | 4.82%   |
| 0.51-1.0 | 3         | 3.61%   |
| 4.01-8.0 | 1         | 1.2%    |
| 3.01-4.0 | 1         | 1.2%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 43        | 51.81%  |
| 2      | 21        | 25.3%   |
| 3      | 8         | 9.64%   |
| 4      | 7         | 8.43%   |
| 8      | 1         | 1.2%    |
| 6      | 1         | 1.2%    |
| 5      | 1         | 1.2%    |
| 0      | 1         | 1.2%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 82        | 98.8%   |
| Yes       | 1         | 1.2%    |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 69        | 83.13%  |
| No        | 14        | 16.87%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 49        | 59.04%  |
| No        | 34        | 40.96%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 48        | 57.83%  |
| Yes       | 35        | 42.17%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Russia      | 17        | 20.48%  |
| Canada      | 12        | 14.46%  |
| Italy       | 7         | 8.43%   |
| Poland      | 6         | 7.23%   |
| Germany     | 6         | 7.23%   |
| USA         | 5         | 6.02%   |
| Netherlands | 5         | 6.02%   |
| UK          | 4         | 4.82%   |
| Spain       | 4         | 4.82%   |
| France      | 3         | 3.61%   |
| India       | 2         | 2.41%   |
| Egypt       | 2         | 2.41%   |
| Austria     | 2         | 2.41%   |
| Slovakia    | 1         | 1.2%    |
| Philippines | 1         | 1.2%    |
| Norway      | 1         | 1.2%    |
| Montserrat  | 1         | 1.2%    |
| Lithuania   | 1         | 1.2%    |
| Czechia     | 1         | 1.2%    |
| Chile       | 1         | 1.2%    |
| Argentina   | 1         | 1.2%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Montreal            | 10        | 12.05%  |
| Vladivostok         | 6         | 7.23%   |
| Poortugaal          | 4         | 4.82%   |
| Milan               | 4         | 4.82%   |
| Gdansk              | 3         | 3.61%   |
| Vienna              | 2         | 2.41%   |
| Ozersk              | 2         | 2.41%   |
| Wolverhampton       | 1         | 1.2%    |
| West Valley City    | 1         | 1.2%    |
| Valdivia            | 1         | 1.2%    |
| Tanta               | 1         | 1.2%    |
| Tambov              | 1         | 1.2%    |
| Sutton              | 1         | 1.2%    |
| Starogard Gdański  | 1         | 1.2%    |
| St. Albert          | 1         | 1.2%    |
| St Petersburg       | 1         | 1.2%    |
| Springboro          | 1         | 1.2%    |
| Sarnia              | 1         | 1.2%    |
| Reutov              | 1         | 1.2%    |
| Quezon City         | 1         | 1.2%    |
| Pozzuolo Martesana  | 1         | 1.2%    |
| Plymouth            | 1         | 1.2%    |
| Paderborn           | 1         | 1.2%    |
| Oslo                | 1         | 1.2%    |
| Orenburg            | 1         | 1.2%    |
| Oakland             | 1         | 1.2%    |
| Nuremberg           | 1         | 1.2%    |
| Newcastle upon Tyne | 1         | 1.2%    |
| Mumbai              | 1         | 1.2%    |
| Moscow              | 1         | 1.2%    |
| Memmingen           | 1         | 1.2%    |
| Madrid              | 1         | 1.2%    |
| Mâcon              | 1         | 1.2%    |
| Ludwigsburg         | 1         | 1.2%    |
| Lublin              | 1         | 1.2%    |
| Lübeck             | 1         | 1.2%    |
| Lodz                | 1         | 1.2%    |
| Krasnodar           | 1         | 1.2%    |
| Kolomna             | 1         | 1.2%    |
| Gianico             | 1         | 1.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 18        | 19     | 16.07%  |
| NVMe                | 18        | 21     | 16.07%  |
| Seagate             | 14        | 18     | 12.5%   |
| Samsung Electronics | 13        | 18     | 11.61%  |
| Toshiba             | 5         | 9      | 4.46%   |
| Hitachi             | 5         | 6      | 4.46%   |
| Kingston            | 4         | 4      | 3.57%   |
| SanDisk             | 3         | 3      | 2.68%   |
| Innostor            | 3         | 3      | 2.68%   |
| HGST                | 3         | 3      | 2.68%   |
| Crucial             | 3         | 3      | 2.68%   |
| OPENBSD             | 2         | 2      | 1.79%   |
| Corsair             | 2         | 2      | 1.79%   |
| Apacer              | 2         | 2      | 1.79%   |
| A-DATA Technology   | 2         | 2      | 1.79%   |
| XPG                 | 1         | 1      | 0.89%   |
| USB                 | 1         | 1      | 0.89%   |
| StoreJet            | 1         | 1      | 0.89%   |
| SPCC                | 1         | 1      | 0.89%   |
| PNY                 | 1         | 1      | 0.89%   |
| OWC                 | 1         | 1      | 0.89%   |
| OCZ                 | 1         | 1      | 0.89%   |
| LSI                 | 1         | 1      | 0.89%   |
| LDLC F6+            | 1         | 1      | 0.89%   |
| KingSpec            | 1         | 1      | 0.89%   |
| Intel               | 1         | 1      | 0.89%   |
| Hoodisk             | 1         | 1      | 0.89%   |
| GOODRAM             | 1         | 1      | 0.89%   |
| Generic             | 1         | 1      | 0.89%   |
| AMD                 | 1         | 1      | 0.89%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| NVMe Samsung SSD 980 1TB        | 4         | 3.45%   |
| Samsung HM321HI 320GB           | 3         | 2.59%   |
| Innostor SSD 15GB               | 3         | 2.59%   |
| Toshiba HDWG440 4TB             | 2         | 1.72%   |
| Seagate ST1000DM010-2EP102 1TB  | 2         | 1.72%   |
| OPENBSD SR RAID 1 752GB         | 2         | 1.72%   |
| NVMe WDC PC SN530 SDB 256GB     | 2         | 1.72%   |
| Apacer AS340 240GB              | 2         | 1.72%   |
| XPG SX950U 240GB                | 1         | 0.86%   |
| WDC WD800JD-60LSA5 80GB         | 1         | 0.86%   |
| WDC WD7500BPKX-00HPJT0 752GB    | 1         | 0.86%   |
| WDC WD7500BPKT-75PK4T0 752GB    | 1         | 0.86%   |
| WDC WD7500BPKT-00PK4T0 752GB    | 1         | 0.86%   |
| WDC WD6400AARS-00Y5B1 640GB     | 1         | 0.86%   |
| WDC WD6400AAKS-22A7B0 640GB     | 1         | 0.86%   |
| WDC WD5003AZEX-00K1GA0 500GB    | 1         | 0.86%   |
| WDC WD5003ABYX-01WERA2 500GB    | 1         | 0.86%   |
| WDC WD5000LPLX-00ZNTT0 500GB    | 1         | 0.86%   |
| WDC WD5000AZLX-00K2TA0 500GB    | 1         | 0.86%   |
| WDC WD5000AAKX-60U6AA0 500GB    | 1         | 0.86%   |
| WDC WD40EFZX-68AWUN0 4TB        | 1         | 0.86%   |
| WDC WD3200BEVE-00A0HT0 320GB    | 1         | 0.86%   |
| WDC WD20PURX-64P6ZY0 2TB        | 1         | 0.86%   |
| WDC WD1600BEVT-22ZCT0 160GB     | 1         | 0.86%   |
| WDC WD10JPVT-75A1YT0 1TB        | 1         | 0.86%   |
| WDC WD10JPLX-00MBPT0 1TB        | 1         | 0.86%   |
| WDC WD10EZEX-00MFCA0 1TB        | 1         | 0.86%   |
| USB SanDisk 3.2Gen1 64GB        | 1         | 0.86%   |
| Toshiba MK6475GSX 640GB         | 1         | 0.86%   |
| Toshiba MG06ACA800E 8TB         | 1         | 0.86%   |
| Toshiba DT01ACA050 500GB        | 1         | 0.86%   |
| StoreJet Transcend 120GB        | 1         | 0.86%   |
| SPCC Solid State Disk 256GB     | 1         | 0.86%   |
| Seagate ST9500420AS 500GB       | 1         | 0.86%   |
| Seagate ST9160821A 160GB        | 1         | 0.86%   |
| Seagate ST500DM002-1BD142 500GB | 1         | 0.86%   |
| Seagate ST380815AS 80GB         | 1         | 0.86%   |
| Seagate ST3750640NS 752GB       | 1         | 0.86%   |
| Seagate ST3250318AS 250GB       | 1         | 0.86%   |
| Seagate ST3250310AS 250GB       | 1         | 0.86%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 18        | 19     | 26.47%  |
| Seagate             | 14        | 18     | 20.59%  |
| NVMe                | 10        | 11     | 14.71%  |
| Samsung Electronics | 6         | 6      | 8.82%   |
| Toshiba             | 5         | 9      | 7.35%   |
| Hitachi             | 5         | 6      | 7.35%   |
| HGST                | 3         | 3      | 4.41%   |
| OPENBSD             | 2         | 2      | 2.94%   |
| USB                 | 1         | 1      | 1.47%   |
| StoreJet            | 1         | 1      | 1.47%   |
| LSI                 | 1         | 1      | 1.47%   |
| LDLC F6+            | 1         | 1      | 1.47%   |
| Generic             | 1         | 1      | 1.47%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 12     | 17.07%  |
| NVMe                | 5         | 6      | 12.2%   |
| Kingston            | 4         | 4      | 9.76%   |
| SanDisk             | 3         | 3      | 7.32%   |
| Innostor            | 3         | 3      | 7.32%   |
| Crucial             | 3         | 3      | 7.32%   |
| Corsair             | 2         | 2      | 4.88%   |
| Apacer              | 2         | 2      | 4.88%   |
| A-DATA Technology   | 2         | 2      | 4.88%   |
| XPG                 | 1         | 1      | 2.44%   |
| SPCC                | 1         | 1      | 2.44%   |
| PNY                 | 1         | 1      | 2.44%   |
| OWC                 | 1         | 1      | 2.44%   |
| OCZ                 | 1         | 1      | 2.44%   |
| KingSpec            | 1         | 1      | 2.44%   |
| Intel               | 1         | 1      | 2.44%   |
| Hoodisk             | 1         | 1      | 2.44%   |
| GOODRAM             | 1         | 1      | 2.44%   |
| AMD                 | 1         | 1      | 2.44%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 49        | 79     | 56.98%  |
| SSD  | 34        | 47     | 39.53%  |
| NVMe | 3         | 4      | 3.49%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 74        | 126    | 96.1%   |
| NVMe | 3         | 4      | 3.9%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 54        | 71     | 59.34%  |
| 0.51-1.0   | 29        | 35     | 31.87%  |
| 1.01-2.0   | 4         | 11     | 4.4%    |
| 3.01-4.0   | 3         | 6      | 3.3%    |
| 4.01-10.0  | 1         | 3      | 1.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 24        | 28.92%  |
| 251-500        | 22        | 26.51%  |
| 21-50          | 16        | 19.28%  |
| 51-100         | 8         | 9.64%   |
| 1-20           | 7         | 8.43%   |
| 501-1000       | 4         | 4.82%   |
| More than 3000 | 2         | 2.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 70        | 84.34%  |
| 51-100    | 5         | 6.02%   |
| 21-50     | 4         | 4.82%   |
| 101-250   | 2         | 2.41%   |
| 251-500   | 1         | 1.2%    |
| 2001-3000 | 1         | 1.2%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| XPG SX950U 240GB                  | 1         | 1      | 6.25%   |
| WDC WD6400AAKS-22A7B0 640GB       | 1         | 1      | 6.25%   |
| WDC WD5000AAKX-60U6AA0 500GB      | 1         | 1      | 6.25%   |
| Toshiba MK6475GSX 640GB           | 1         | 1      | 6.25%   |
| Seagate ST9500420AS 500GB         | 1         | 1      | 6.25%   |
| Seagate ST500DM002-1BD142 500GB   | 1         | 1      | 6.25%   |
| Seagate ST380815AS 80GB           | 1         | 1      | 6.25%   |
| Seagate ST3750640NS 752GB         | 1         | 2      | 6.25%   |
| Seagate ST3160212SCE 160GB        | 1         | 1      | 6.25%   |
| Seagate ST250DM000-1BD141 250GB   | 1         | 1      | 6.25%   |
| Seagate ST2000DM006-2DM164 2TB    | 1         | 1      | 6.25%   |
| SanDisk SD7UB3Q256G1001 256GB     | 1         | 1      | 6.25%   |
| Samsung Electronics HD753LJ 752GB | 1         | 1      | 6.25%   |
| Samsung Electronics HD161HJ 160GB | 1         | 1      | 6.25%   |
| OCZ VERTEX3 120GB                 | 1         | 1      | 6.25%   |
| A-DATA Technology SP550 480GB     | 1         | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 8      | 40%     |
| WDC                 | 2         | 2      | 13.33%  |
| Samsung Electronics | 2         | 2      | 13.33%  |
| XPG                 | 1         | 1      | 6.67%   |
| Toshiba             | 1         | 1      | 6.67%   |
| SanDisk             | 1         | 1      | 6.67%   |
| OCZ                 | 1         | 1      | 6.67%   |
| A-DATA Technology   | 1         | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 8      | 54.55%  |
| WDC                 | 2         | 2      | 18.18%  |
| Samsung Electronics | 2         | 2      | 18.18%  |
| Toshiba             | 1         | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 13     | 73.33%  |
| SSD  | 4         | 4      | 26.67%  |

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
| Works    | 57        | 86     | 61.29%  |
| Detected | 21        | 26     | 22.58%  |
| Malfunc  | 14        | 17     | 15.05%  |
| Failed   | 1         | 1      | 1.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 54        | 58.7%   |
| AMD                          | 15        | 16.3%   |
| Samsung Electronics          | 6         | 6.52%   |
| SanDisk                      | 4         | 4.35%   |
| KIOXIA                       | 2         | 2.17%   |
| VIA Technologies             | 1         | 1.09%   |
| Toshiba                      | 1         | 1.09%   |
| SK hynix                     | 1         | 1.09%   |
| Shenzhen Longsys Electronics | 1         | 1.09%   |
| Nvidia                       | 1         | 1.09%   |
| Marvell Technology Group     | 1         | 1.09%   |
| Lenovo                       | 1         | 1.09%   |
| Kingston Technology Company  | 1         | 1.09%   |
| Broadcom / LSI               | 1         | 1.09%   |
| ASMedia Technology           | 1         | 1.09%   |
| ADATA Technology             | 1         | 1.09%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 6         | 5.88%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 6         | 5.88%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 4.9%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 5         | 4.9%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 5         | 4.9%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 3.92%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 3.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 3.92%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 2.94%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 2.94%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 3         | 2.94%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3         | 2.94%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3         | 2.94%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 1.96%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2         | 1.96%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 2         | 1.96%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 1.96%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2         | 1.96%   |
| AMD 500 Series Chipset SATA Controller                                         | 2         | 1.96%   |
| AMD 400 Series Chipset SATA Controller                                         | 2         | 1.96%   |
| VIA VT6415 PATA IDE Host Controller                                            | 1         | 0.98%   |
| Toshiba BG3 NVMe SSD Controller                                                | 1         | 0.98%   |
| SK hynix PC300 NVMe Solid State Drive 256GB                                    | 1         | 0.98%   |
| Shenzhen Longsys unknown                                                       | 1         | 0.98%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1         | 0.98%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 0.98%   |
| SanDisk unknown                                                                | 1         | 0.98%   |
| SanDisk PC SN530                                                               | 1         | 0.98%   |
| SanDisk PC SN520 NVMe SSD                                                      | 1         | 0.98%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1         | 0.98%   |
| Samsung NVMe SSD Controller 980                                                | 1         | 0.98%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 0.98%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller               | 1         | 0.98%   |
| Lenovo unknown                                                                 | 1         | 0.98%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 1         | 0.98%   |
| KIOXIA NVMe SSD                                                                | 1         | 0.98%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 1         | 0.98%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 0.98%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1         | 0.98%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 1         | 0.98%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 61        | 64.89%  |
| NVMe | 18        | 19.15%  |
| IDE  | 14        | 14.89%  |
| RAID | 1         | 1.06%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 59        | 71.08%  |
| AMD    | 17        | 20.48%  |
| ARM    | 6         | 7.23%   |
| 11th   | 1         | 1.2%    |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz                         | 4         | 4.82%   |
| ARM Cortex-A72 r0p3                                       | 4         | 4.82%   |
| Intel Core i5-6300U CPU @ 2.40GHz                         | 3         | 3.61%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz                      | 3         | 3.61%   |
| Intel Core i5-4570 CPU @ 3.20GHz                          | 2         | 2.41%   |
| Intel Core i5 CPU M 520 @ 2.40GHz                         | 2         | 2.41%   |
| Intel Core i3-10100F CPU @ 3.60GHz                        | 2         | 2.41%   |
| Intel Core i3-10100 CPU @ 3.60GHz                         | 2         | 2.41%   |
| AMD Ryzen 7 4700U with Radeon Graphics                    | 2         | 2.41%   |
| Intel Xeon CPU X5690 @ 3.47GHz                            | 1         | 1.2%    |
| Intel Xeon CPU E5520 @ 2.27GHz                            | 1         | 1.2%    |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz                       | 1         | 1.2%    |
| Intel Pentium Silver N6000 @ 1.10GHz                      | 1         | 1.2%    |
| Intel Pentium Silver N5000 CPU @ 1.10GHz                  | 1         | 1.2%    |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz               | 1         | 1.2%    |
| Intel Pentium CPU N3700 @ 1.60GHz                         | 1         | 1.2%    |
| Intel Pentium 4 Mobile CPU 1.60GHz                        | 1         | 1.2%    |
| Intel Pentium 4 CPU 2.40GHz ("GenuineIntel" 686-class)    | 1         | 1.2%    |
| Intel Genuine processor 600MHz ("GenuineIntel" 686-class) | 1         | 1.2%    |
| Intel Genuine CPU T2300 @ 1.66GHz                         | 1         | 1.2%    |
| Intel Core i9-10980HK CPU @ 2.40GHz                       | 1         | 1.2%    |
| Intel Core i7-9700K CPU @ 3.60GHz                         | 1         | 1.2%    |
| Intel Core i7-7500U CPU @ 2.70GHz                         | 1         | 1.2%    |
| Intel Core i7-6700 CPU @ 3.40GHz                          | 1         | 1.2%    |
| Intel Core i7-5500U CPU @ 2.40GHz                         | 1         | 1.2%    |
| Intel Core i7-4790 CPU @ 3.60GHz                          | 1         | 1.2%    |
| Intel Core i7-3610QM CPU @ 2.30GHz                        | 1         | 1.2%    |
| Intel Core i7-3520M CPU @ 2.90GHz                         | 1         | 1.2%    |
| Intel Core i7-2670QM CPU @ 2.20GHz                        | 1         | 1.2%    |
| Intel Core i5-8250U CPU @ 1.60GHz                         | 1         | 1.2%    |
| Intel Core i5-5300U CPU @ 2.30GHz                         | 1         | 1.2%    |
| Intel Core i5-4570T CPU @ 2.90GHz                         | 1         | 1.2%    |
| Intel Core i5-3470T CPU @ 2.90GHz                         | 1         | 1.2%    |
| Intel Core i5-3320M CPU @ 2.60GHz                         | 1         | 1.2%    |
| Intel Core i5-3210M CPU @ 2.50GHz                         | 1         | 1.2%    |
| Intel Core i5-10400F CPU @ 2.90GHz                        | 1         | 1.2%    |
| Intel Core i5-10300H CPU @ 2.50GHz                        | 1         | 1.2%    |
| Intel Core i3-5010U CPU @ 2.10GHz                         | 1         | 1.2%    |
| Intel Core i3-4010U CPU @ 1.70GHz                         | 1         | 1.2%    |
| Intel Core i3-3225 CPU @ 3.30GHz                          | 1         | 1.2%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 19        | 22.89%  |
| Intel Core i7           | 8         | 9.64%   |
| Intel Core i3           | 8         | 9.64%   |
| ARM Cortex              | 6         | 7.23%   |
| Intel Core 2 Duo        | 5         | 6.02%   |
| Intel Celeron           | 4         | 4.82%   |
| AMD Ryzen 7             | 4         | 4.82%   |
| Intel Xeon              | 3         | 3.61%   |
| AMD Ryzen 5             | 3         | 3.61%   |
| Other                   | 2         | 2.41%   |
| Intel Pentium Silver    | 2         | 2.41%   |
| Intel Pentium 4         | 2         | 2.41%   |
| Intel Genuine           | 2         | 2.41%   |
| Intel Atom              | 2         | 2.41%   |
| Intel Pentium Dual-Core | 1         | 1.2%    |
| Intel Pentium           | 1         | 1.2%    |
| Intel Core i9           | 1         | 1.2%    |
| Intel Core 2 Quad       | 1         | 1.2%    |
| AMD Ryzen 9             | 1         | 1.2%    |
| AMD Ryzen 3             | 1         | 1.2%    |
| AMD Phenom II X4        | 1         | 1.2%    |
| AMD GX                  | 1         | 1.2%    |
| AMD E                   | 1         | 1.2%    |
| AMD Athlon II X4        | 1         | 1.2%    |
| AMD Athlon II X2        | 1         | 1.2%    |
| AMD Athlon              | 1         | 1.2%    |
| AMD A6                  | 1         | 1.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 26        | 31.33%  |
| 4       | 23        | 27.71%  |
| Unknown | 20        | 24.1%   |
| 8       | 5         | 6.02%   |
| 12      | 3         | 3.61%   |
| 1       | 3         | 3.61%   |
| 32      | 1         | 1.2%    |
| 16      | 1         | 1.2%    |
| 6       | 1         | 1.2%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 61        | 73.49%  |
| Unknown | 20        | 24.1%   |
| 2       | 2         | 2.41%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 34        | 40.96%  |
| 1       | 26        | 31.33%  |
| Unknown | 23        | 27.71%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 12        | 14.46%  |
| Penryn        | 7         | 8.43%   |
| IvyBridge     | 7         | 8.43%   |
| Haswell       | 6         | 7.23%   |
| CometLake     | 6         | 7.23%   |
| Skylake       | 5         | 6.02%   |
| SandyBridge   | 5         | 6.02%   |
| Zen 2         | 4         | 4.82%   |
| K10           | 4         | 4.82%   |
| Westmere      | 3         | 3.61%   |
| KabyLake      | 3         | 3.61%   |
| Broadwell     | 3         | 3.61%   |
| Zen 3         | 2         | 2.41%   |
| P6            | 2         | 2.41%   |
| NetBurst      | 2         | 2.41%   |
| Goldmont plus | 2         | 2.41%   |
| Bonnell       | 2         | 2.41%   |
| Zen+          | 1         | 1.2%    |
| Zen           | 1         | 1.2%    |
| Silvermont    | 1         | 1.2%    |
| Puma          | 1         | 1.2%    |
| Nehalem       | 1         | 1.2%    |
| K10 Llano     | 1         | 1.2%    |
| Goldmont      | 1         | 1.2%    |
| Bobcat        | 1         | 1.2%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 44        | 54.32%  |
| AMD                        | 26        | 32.1%   |
| Nvidia                     | 9         | 11.11%  |
| Matrox Electronics Systems | 1         | 1.23%   |
| ASPEED Technology          | 1         | 1.23%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4         | 4.6%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 4.6%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 4.6%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 4.6%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 4.6%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 3.45%   |
| Intel HD Graphics 5500                                                                   | 3         | 3.45%   |
| AMD Renoir                                                                               | 3         | 3.45%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 3         | 3.45%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 2.3%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 2.3%    |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 2.3%    |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 2.3%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 2.3%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 2.3%    |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 2         | 2.3%    |
| AMD RS880 [Radeon HD 4200]                                                               | 2         | 2.3%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 2         | 2.3%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2         | 2.3%    |
| Nvidia TU117M                                                                            | 1         | 1.15%   |
| Nvidia NV28 [GeForce4 Ti 4200 AGP 8x]                                                    | 1         | 1.15%   |
| Nvidia GM108M [GeForce 940M]                                                             | 1         | 1.15%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 1.15%   |
| Nvidia GF108M [NVS 5400M]                                                                | 1         | 1.15%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 1         | 1.15%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 1         | 1.15%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 1.15%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 1         | 1.15%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 1.15%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 1         | 1.15%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.15%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 1.15%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1         | 1.15%   |
| Intel HD Graphics 620                                                                    | 1         | 1.15%   |
| Intel HD Graphics 530                                                                    | 1         | 1.15%   |
| Intel HD Graphics 500                                                                    | 1         | 1.15%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 1.15%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 1.15%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.15%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 31        | 37.35%  |
| 1 x AMD        | 23        | 27.71%  |
| 2 x Intel      | 8         | 9.64%   |
| Other          | 7         | 8.43%   |
| 1 x Nvidia     | 5         | 6.02%   |
| Intel + Nvidia | 3         | 3.61%   |
| Intel + AMD    | 2         | 2.41%   |
| 2 x Nvidia     | 1         | 1.2%    |
| 2 x AMD        | 1         | 1.2%    |
| 1 x Matrox     | 1         | 1.2%    |
| 1 x ASPEED     | 1         | 1.2%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 70        | 84.34%  |
| Unknown | 13        | 15.66%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 83        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Philips                 | 7         | 14%     |
| Samsung Electronics     | 5         | 10%     |
| LG Display              | 5         | 10%     |
| Lenovo                  | 5         | 10%     |
| BOE                     | 4         | 8%      |
| Dell                    | 3         | 6%      |
| Chimei Innolux          | 3         | 6%      |
| AU Optronics            | 3         | 6%      |
| ViewSonic               | 2         | 4%      |
| MSI                     | 2         | 4%      |
| Chi Mei Optoelectronics | 2         | 4%      |
| TRU                     | 1         | 2%      |
| PANDA                   | 1         | 2%      |
| InfoVision              | 1         | 2%      |
| Hewlett-Packard         | 1         | 2%      |
| Goldstar                | 1         | 2%      |
| BenQ                    | 1         | 2%      |
| AOC                     | 1         | 2%      |
| Ancor Communications    | 1         | 2%      |
| Acer                    | 1         | 2%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                    | 6         | 12%     |
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch                  | 3         | 6%      |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch              | 2         | 4%      |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 2         | 4%      |
| ViewSonic LCD Monitor VSCD22B 1920x1080 520x290mm 23.4-inch              | 1         | 2%      |
| ViewSonic LCD Monitor VSCC42B 1920x1080 480x270mm 21.7-inch              | 1         | 2%      |
| TRU LCD Monitor TRU235C 1366x768 260x140mm 11.6-inch                     | 1         | 2%      |
| Samsung Electronics SyncMaster SAM03CF 1280x1024 340x270mm 17.1-inch     | 1         | 2%      |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch     | 1         | 2%      |
| Samsung Electronics LCD Monitor SEC304C 1366x768 350x200mm 15.9-inch     | 1         | 2%      |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch   | 1         | 2%      |
| Samsung Electronics DM700A-D SEM0324 1920x1080 520x290mm 23.4-inch       | 1         | 2%      |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                  | 1         | 2%      |
| PANDA LM133LF1L01 NCP13FB 1920x1080 290x170mm 13.2-inch                  | 1         | 2%      |
| MSI MP242 MSI30A1 1920x1080 530x300mm 24.0-inch                          | 1         | 2%      |
| MSI MAG241C MSI3EA2 1920x1080 520x290mm 23.4-inch                        | 1         | 2%      |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch             | 1         | 2%      |
| LG Display LCD Monitor LGD0215 1920x1080 350x190mm 15.7-inch             | 1         | 2%      |
| LG Display LCD Monitor LGD01AB 1280x800 260x160mm 12.0-inch              | 1         | 2%      |
| Lenovo LEN S24e-10 LEN61CA 1920x1080 530x300mm 24.0-inch                 | 1         | 2%      |
| Lenovo LCD Monitor LEN4011 1280x800 260x170mm 12.2-inch                  | 1         | 2%      |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch              | 1         | 2%      |
| Hewlett-Packard x23LED HWP2912 1920x1080 510x290mm 23.1-inch             | 1         | 2%      |
| Goldstar L1752T GSM4434 1280x1024 340x270mm 17.1-inch                    | 1         | 2%      |
| Dell LCD Monitor DELF003 1440x900 410x260mm 19.1-inch                    | 1         | 2%      |
| Dell E1916H DELF064 1366x768 410x230mm 18.5-inch                         | 1         | 2%      |
| Dell 2001FP DELA007 1600x1200 410x310mm 20.2-inch                        | 1         | 2%      |
| Chimei Innolux LCD Monitor CMN1734 1600x900 380x210mm 17.1-inch          | 1         | 2%      |
| Chimei Innolux LCD Monitor CMN15D7 1920x1080 340x190mm 15.3-inch         | 1         | 2%      |
| Chimei Innolux LCD Monitor CMN152E 1920x1080 340x190mm 15.3-inch         | 1         | 2%      |
| BOE LCD Monitor BOE0900 1920x1080 340x190mm 15.3-inch                    | 1         | 2%      |
| BOE LCD Monitor BOE08D7 1920x1080 310x170mm 13.9-inch                    | 1         | 2%      |
| BOE LCD Monitor BOE07A5 1366x768 340x190mm 15.3-inch                     | 1         | 2%      |
| BOE LCD Monitor BOE075A 1366x768 310x170mm 13.9-inch                     | 1         | 2%      |
| BenQ G2255 BNQ78B7 1920x1080 480x270mm 21.7-inch                         | 1         | 2%      |
| AU Optronics LCD Monitor AUODF87 1920x1080 340x190mm 15.3-inch           | 1         | 2%      |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch            | 1         | 2%      |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 1         | 2%      |
| AOC 2269WM AOC2269 1920x1080 480x270mm 21.7-inch                         | 1         | 2%      |
| Ancor Communications ASUS VW199 ACI19ED 1440x900 410x260mm 19.1-inch     | 1         | 2%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 22        | 45.83%  |
| 1366x768 (WXGA)  | 12        | 25%     |
| 1280x800 (WXGA)  | 5         | 10.42%  |
| 1600x900 (HD+)   | 2         | 4.17%   |
| 1440x900 (WXGA+) | 2         | 4.17%   |
| 1280x1024 (SXGA) | 2         | 4.17%   |
| 3840x2160 (4K)   | 1         | 2.08%   |
| 3440x1440        | 1         | 2.08%   |
| 1600x1200        | 1         | 2.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 9         | 18.37%  |
| 12     | 9         | 18.37%  |
| 21     | 8         | 16.33%  |
| 13     | 5         | 10.2%   |
| 23     | 4         | 8.16%   |
| 24     | 3         | 6.12%   |
| 17     | 3         | 6.12%   |
| 19     | 2         | 4.08%   |
| 11     | 2         | 4.08%   |
| 54     | 1         | 2.04%   |
| 34     | 1         | 2.04%   |
| 20     | 1         | 2.04%   |
| 18     | 1         | 2.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 15        | 30.61%  |
| 401-500     | 12        | 24.49%  |
| 201-300     | 12        | 24.49%  |
| 501-600     | 7         | 14.29%  |
| 701-800     | 1         | 2.04%   |
| 351-400     | 1         | 2.04%   |
| 1001-1500   | 1         | 2.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 37        | 77.08%  |
| 16/10 | 6         | 12.5%   |
| 5/4   | 2         | 4.17%   |
| 4/3   | 1         | 2.08%   |
| 3/2   | 1         | 2.08%   |
| 21/9  | 1         | 2.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 14        | 29.17%  |
| 61-70          | 9         | 18.75%  |
| 91-100         | 5         | 10.42%  |
| 81-90          | 4         | 8.33%   |
| 101-110        | 4         | 8.33%   |
| 151-200        | 3         | 6.25%   |
| 141-150        | 3         | 6.25%   |
| 51-60          | 2         | 4.17%   |
| More than 1000 | 1         | 2.08%   |
| 71-80          | 1         | 2.08%   |
| 351-500        | 1         | 2.08%   |
| 121-130        | 1         | 2.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 19        | 39.58%  |
| 51-100  | 16        | 33.33%  |
| 101-120 | 12        | 25%     |
| 161-240 | 1         | 2.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 57        | 68.67%  |
| 0     | 24        | 28.92%  |
| 3     | 1         | 1.2%    |
| 2     | 1         | 1.2%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 43        | 41.75%  |
| Realtek Semiconductor             | 37        | 35.92%  |
| Qualcomm Atheros                  | 7         | 6.8%    |
| Qualcomm Atheros Communications   | 3         | 2.91%   |
| Ericsson Business Mobile Networks | 3         | 2.91%   |
| Broadcom                          | 3         | 2.91%   |
| Sierra Wireless                   | 1         | 0.97%   |
| Qcom                              | 1         | 0.97%   |
| Nvidia                            | 1         | 0.97%   |
| Marvell Technology Group          | 1         | 0.97%   |
| Dell                              | 1         | 0.97%   |
| AVM                               | 1         | 0.97%   |
| ASUSTek Computer                  | 1         | 0.97%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 27        | 20.45%  |
| Intel Wi-Fi 6 AX200                                                         | 6         | 4.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 6         | 4.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 6         | 4.55%   |
| Intel Ultimate N WiFi Link 5300                                             | 4         | 3.03%   |
| Intel 82567LM Gigabit Network Connection                                    | 4         | 3.03%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 3         | 2.27%   |
| Qualcomm Atheros AR9271 802.11n                                             | 3         | 2.27%   |
| Intel Wireless 8260                                                         | 3         | 2.27%   |
| Intel I210 Gigabit Network Connection                                       | 3         | 2.27%   |
| Intel Ethernet Connection I219-LM                                           | 3         | 2.27%   |
| Intel 82574L Gigabit Network Connection                                     | 3         | 2.27%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 2         | 1.52%   |
| Realtek RTL8125 2.5GbE Controller                                           | 2         | 1.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                       | 2         | 1.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 2         | 1.52%   |
| Intel Wireless 7265                                                         | 2         | 1.52%   |
| Intel I211 Gigabit Network Connection                                       | 2         | 1.52%   |
| Intel Centrino Advanced-N 6200                                              | 2         | 1.52%   |
| Intel 82577LM Gigabit Network Connection                                    | 2         | 1.52%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III | 2         | 1.52%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                      | 2         | 1.52%   |
| Sierra Wireless EM7455                                                      | 1         | 0.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 1         | 0.76%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                             | 1         | 0.76%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                             | 1         | 0.76%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                            | 1         | 0.76%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                            | 1         | 0.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 1         | 0.76%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                            | 1         | 0.76%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 1         | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                               | 1         | 0.76%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                               | 1         | 0.76%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet              | 1         | 0.76%   |
| Qcom RT73 USB Wireless LAN Card                                             | 1         | 0.76%   |
| Nvidia MCP79 Ethernet                                                       | 1         | 0.76%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                     | 1         | 0.76%   |
| Intel Wireless 7260                                                         | 1         | 0.76%   |
| Intel Wireless 3165                                                         | 1         | 0.76%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                      | 1         | 0.76%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 33        | 62.26%  |
| Realtek Semiconductor           | 5         | 9.43%   |
| Qualcomm Atheros                | 5         | 9.43%   |
| Qualcomm Atheros Communications | 3         | 5.66%   |
| Broadcom                        | 3         | 5.66%   |
| Sierra Wireless                 | 1         | 1.89%   |
| Qcom                            | 1         | 1.89%   |
| Dell                            | 1         | 1.89%   |
| ASUSTek Computer                | 1         | 1.89%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 6         | 11.32%  |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 6         | 11.32%  |
| Intel Ultimate N WiFi Link 5300                                | 4         | 7.55%   |
| Qualcomm Atheros AR9271 802.11n                                | 3         | 5.66%   |
| Intel Wireless 8260                                            | 3         | 5.66%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 3.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 3.77%   |
| Intel Wireless 7265                                            | 2         | 3.77%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 3.77%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 2         | 3.77%   |
| Sierra Wireless EM7455                                         | 1         | 1.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.89%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 1.89%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1         | 1.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 1.89%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 1.89%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 1.89%   |
| Qcom RT73 USB Wireless LAN Card                                | 1         | 1.89%   |
| Intel Wireless 7260                                            | 1         | 1.89%   |
| Intel Wireless 3165                                            | 1         | 1.89%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1         | 1.89%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 1         | 1.89%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 1.89%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 1.89%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 1.89%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 1.89%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 1.89%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 1         | 1.89%   |
| Dell Dell Wireless 5550 HSPA+ Mini-Card Network Adapter        | 1         | 1.89%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 1         | 1.89%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                            | 1         | 1.89%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 36        | 50.7%   |
| Intel                    | 29        | 40.85%  |
| Qualcomm Atheros         | 3         | 4.23%   |
| Nvidia                   | 1         | 1.41%   |
| Marvell Technology Group | 1         | 1.41%   |
| Broadcom                 | 1         | 1.41%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 27        | 36.49%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6         | 8.11%   |
| Intel 82567LM Gigabit Network Connection                                      | 4         | 5.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 3         | 4.05%   |
| Intel I210 Gigabit Network Connection                                         | 3         | 4.05%   |
| Intel Ethernet Connection I219-LM                                             | 3         | 4.05%   |
| Intel 82574L Gigabit Network Connection                                       | 3         | 4.05%   |
| Realtek RTL8125 2.5GbE Controller                                             | 2         | 2.7%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2         | 2.7%    |
| Intel I211 Gigabit Network Connection                                         | 2         | 2.7%    |
| Intel 82577LM Gigabit Network Connection                                      | 2         | 2.7%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                              | 1         | 1.35%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 1         | 1.35%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1         | 1.35%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                 | 1         | 1.35%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1         | 1.35%   |
| Nvidia MCP79 Ethernet                                                         | 1         | 1.35%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 1         | 1.35%   |
| Intel I225-K2                                                                 | 1         | 1.35%   |
| Intel Ethernet Controller I225-V                                              | 1         | 1.35%   |
| Intel Ethernet Connection I218-LM                                             | 1         | 1.35%   |
| Intel Ethernet Connection I217-LM                                             | 1         | 1.35%   |
| Intel Ethernet Connection (3) I218-LM                                         | 1         | 1.35%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1         | 1.35%   |
| Intel 82579V Gigabit Network Connection                                       | 1         | 1.35%   |
| Intel 82575EB Gigabit Network Connection                                      | 1         | 1.35%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 1.35%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                           | 1         | 1.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 69        | 56.1%   |
| WiFi     | 49        | 39.84%  |
| Unknown  | 4         | 3.25%   |
| Modem    | 1         | 0.81%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 37        | 50%     |
| Ethernet | 37        | 50%     |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 41        | 49.4%   |
| 1     | 28        | 33.73%  |
| 0     | 7         | 8.43%   |
| 3     | 4         | 4.82%   |
| 4     | 2         | 2.41%   |
| 5     | 1         | 1.2%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 82        | 98.8%   |
| Yes  | 1         | 1.2%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 18        | 51.43%  |
| Broadcom                        | 7         | 20%     |
| Foxconn / Hon Hai               | 2         | 5.71%   |
| Apple                           | 2         | 5.71%   |
| Alps Electric                   | 2         | 5.71%   |
| Realtek Semiconductor           | 1         | 2.86%   |
| Qualcomm Atheros Communications | 1         | 2.86%   |
| IMC Networks                    | 1         | 2.86%   |
| ASUSTek Computer                | 1         | 2.86%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 7         | 20%     |
| Intel AX200 Bluetooth                                       | 4         | 11.43%  |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 3         | 8.57%   |
| Intel AX201 Bluetooth                                       | 2         | 5.71%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 5.71%   |
| Alps Electric UGTZ4 Bluetooth                               | 2         | 5.71%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 2.86%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 2.86%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 2.86%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 2.86%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 1         | 2.86%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 1         | 2.86%   |
| Intel AX210 Bluetooth                                       | 1         | 2.86%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 2.86%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 2.86%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device    | 1         | 2.86%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 1         | 2.86%   |
| Broadcom BCM2046 Bluetooth Device                           | 1         | 2.86%   |
| ASUS Broadcom Bluetooth 2.1                                 | 1         | 2.86%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1         | 2.86%   |
| Apple Bluetooth Host Controller                             | 1         | 2.86%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 55        | 62.5%   |
| AMD                 | 25        | 28.41%  |
| Nvidia              | 6         | 6.82%   |
| Creative Labs       | 1         | 1.14%   |
| C-Media Electronics | 1         | 1.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 5.45%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 5.45%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 5.45%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 5.45%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 5         | 4.55%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 4.55%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5         | 4.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 3.64%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 4         | 3.64%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 3.64%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4         | 3.64%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 3.64%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 2.73%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 2.73%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 2.73%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 1.82%   |
| Intel Jasper Lake HD Audio                                                                        | 2         | 1.82%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.82%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 1.82%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 1.82%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 2         | 1.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.82%   |
| AMD Navi 10 HDMI Audio                                                                            | 2         | 1.82%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 1.82%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.91%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.91%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.91%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 0.91%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 0.91%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 0.91%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.91%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 0.91%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.91%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1         | 0.91%   |
| Intel 82801CA/CAM AC'97 Audio Controller                                                          | 1         | 0.91%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 0.91%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.91%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                                                | 1         | 0.91%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                                     | 1         | 0.91%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 0.91%   |

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
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 1067MT/s  | 1         | 5.88%   |
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
| Chicony Electronics                    | 11        | 40.74%  |
| Acer                                   | 4         | 14.81%  |
| Ricoh                                  | 2         | 7.41%   |
| Realtek Semiconductor                  | 2         | 7.41%   |
| Tripath Technology                     | 1         | 3.7%    |
| Sunplus Innovation Technology          | 1         | 3.7%    |
| Silicon Motion                         | 1         | 3.7%    |
| Quanta                                 | 1         | 3.7%    |
| Lite-On Technology                     | 1         | 3.7%    |
| Denron                                 | 1         | 3.7%    |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.7%    |
| Alcor Micro                            | 1         | 3.7%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 4         | 14.81%  |
| Chicony Integrated Camera [ThinkPad]                                       | 2         | 7.41%   |
| Tripath PC Camera                                                          | 1         | 3.7%    |
| Sunplus Integrated_Webcam_HD                                               | 1         | 3.7%    |
| Silicon Motion WebCam SC-10IRQ12340N                                       | 1         | 3.7%    |
| Ricoh USB2.0 Camera                                                        | 1         | 3.7%    |
| Ricoh Integrated Webcam                                                    | 1         | 3.7%    |
| Realtek USB Camera                                                         | 1         | 3.7%    |
| Realtek Integrated_Webcam_HD                                               | 1         | 3.7%    |
| Quanta VGA WebCam                                                          | 1         | 3.7%    |
| Lite-On Integrated Camera                                                  | 1         | 3.7%    |
| Denron Corp., 2M Front Camera                                              | 1         | 3.7%    |
| Chicony Lenovo Integrated Camera UVC                                       | 1         | 3.7%    |
| Chicony Lenovo Integrated Camera (0.3MP)                                   | 1         | 3.7%    |
| Chicony HD Webcam                                                          | 1         | 3.7%    |
| Chicony FJ Camera                                                          | 1         | 3.7%    |
| Chicony 2.0M UVC Webcam / CNF7129                                          | 1         | 3.7%    |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 3.7%    |
| Alcor Micro ASUS USB2.0 WebCam                                             | 1         | 3.7%    |
| Acer Integrated Camera                                                     | 1         | 3.7%    |
| Acer HD Webcam                                                             | 1         | 3.7%    |
| Acer EasyCamera                                                            | 1         | 3.7%    |
| Acer BisonCam, NB Pro                                                      | 1         | 3.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 4         | 57.14%  |
| Upek             | 2         | 28.57%  |
| AuthenTec        | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 28.57%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 14.29%  |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 14.29%  |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 14.29%  |
| Validity Sensors Synaptics WBDI                        | 1         | 14.29%  |
| AuthenTec AuthenTec Inc. AES2660                       | 1         | 14.29%  |

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
| 1     | 38        | 45.78%  |
| 0     | 23        | 27.71%  |
| 2     | 15        | 18.07%  |
| 3     | 5         | 6.02%   |
| 5     | 1         | 1.2%    |
| 4     | 1         | 1.2%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 47        | 53.41%  |
| Graphics card            | 16        | 18.18%  |
| Firewire controller      | 9         | 10.23%  |
| Net/wireless             | 8         | 9.09%   |
| Sound                    | 3         | 3.41%   |
| Network                  | 2         | 2.27%   |
| Storage/ide              | 1         | 1.14%   |
| Storage/ata              | 1         | 1.14%   |
| Storage                  | 1         | 1.14%   |

