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

Total: 74

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
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
| amd64 | 59        | 83.1%   |
| i386  | 6         | 8.45%   |
| arm64 | 5         | 7.04%   |
| armv7 | 1         | 1.41%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 56        | 78.87%  |
| XFCE         | 7         | 9.86%   |
| fvwm         | 5         | 7.04%   |
| MATE         | 1         | 1.41%   |
| GNOME        | 1         | 1.41%   |
| Console      | 1         | 1.41%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 55        | 77.46%  |
| Console | 16        | 22.54%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 71        | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 59        | 83.1%   |
| ru_RU   | 9         | 12.68%  |
| en_US   | 1         | 1.41%   |
| en_GB   | 1         | 1.41%   |
| C       | 1         | 1.41%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 37        | 52.11%  |
| BIOS | 34        | 47.89%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ffs  | 71        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| MBR  | 41        | 57.75%  |
| GPT  | 30        | 42.25%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 18        | 25.35%  |
| ASUSTek Computer               | 13        | 18.31%  |
| Unknown                        | 6         | 8.45%   |
| MSI                            | 5         | 7.04%   |
| Dell                           | 4         | 5.63%   |
| Intel                          | 3         | 4.23%   |
| Gigabyte Technology            | 3         | 4.23%   |
| TUXEDO                         | 2         | 2.82%   |
| Panasonic                      | 2         | 2.82%   |
| Matsushita Electric Industrial | 2         | 2.82%   |
| Apple                          | 2         | 2.82%   |
| Acer                           | 2         | 2.82%   |
| Sony                           | 1         | 1.41%   |
| Samsung Electronics            | 1         | 1.41%   |
| PC Engines                     | 1         | 1.41%   |
| KOHJINSHA                      | 1         | 1.41%   |
| Hewlett-Packard                | 1         | 1.41%   |
| Fujitsu                        | 1         | 1.41%   |
| DEXP                           | 1         | 1.41%   |
| Biostar                        | 1         | 1.41%   |
| ASRock                         | 1         | 1.41%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 6         | 8.45%   |
| Lenovo ThinkPad X200 745969G                | 3         | 4.23%   |
| ASUS PRIME H410M-A                          | 2         | 2.82%   |
| TUXEDO Pulse 15 Gen1                        | 1         | 1.41%   |
| TUXEDO Aura 15 Gen1                         | 1         | 1.41%   |
| Sony VPCL22Z1R                              | 1         | 1.41%   |
| Samsung DP700A3D/DM700A3D/DB701A3D/DP700A7D | 1         | 1.41%   |
| PC Engines APU2                             | 1         | 1.41%   |
| Panasonic CF-53AAGHYDM                      | 1         | 1.41%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 1.41%   |
| MSI MS-7C82                                 | 1         | 1.41%   |
| MSI MS-7C37                                 | 1         | 1.41%   |
| MSI MS-7C02                                 | 1         | 1.41%   |
| MSI MS-6788                                 | 1         | 1.41%   |
| MSI Modern 14 B11MOL                        | 1         | 1.41%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 1.41%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 1.41%   |
| Lenovo Yoga 330-11IGM 81A6                  | 1         | 1.41%   |
| Lenovo ThinkPad Yoga 260 20FES1K81V         | 1         | 1.41%   |
| Lenovo ThinkPad X250 20CLS4WV08             | 1         | 1.41%   |
| Lenovo ThinkPad X240 20ALA0AHRT             | 1         | 1.41%   |
| Lenovo ThinkPad X220 429043U                | 1         | 1.41%   |
| Lenovo ThinkPad X200 7458NP9                | 1         | 1.41%   |
| Lenovo ThinkPad X121e 3053A52               | 1         | 1.41%   |
| Lenovo ThinkPad T530 24292VG                | 1         | 1.41%   |
| Lenovo ThinkPad T430 2347GZU                | 1         | 1.41%   |
| Lenovo ThinkPad T420s 41742BU               | 1         | 1.41%   |
| Lenovo ThinkPad T410 2537N24                | 1         | 1.41%   |
| Lenovo ThinkPad L530 24812TG                | 1         | 1.41%   |
| Lenovo ThinkPad E14 Gen 2 20T6003BRT        | 1         | 1.41%   |
| Lenovo ThinkCentre M93p 10AAS25M00          | 1         | 1.41%   |
| Lenovo IdeaPad S12 20021,2959               | 1         | 1.41%   |
| KOHJINSHA SH series                         | 1         | 1.41%   |
| Intel Q3XXG4-P                              | 1         | 1.41%   |
| Intel NUC5PPYB                              | 1         | 1.41%   |
| Intel DH67BL                                | 1         | 1.41%   |
| HP Pavilion Laptop 15-cs0xxx                | 1         | 1.41%   |
| Gigabyte H87-HD3                            | 1         | 1.41%   |
| Gigabyte H81M-S2PV                          | 1         | 1.41%   |
| Gigabyte G41MT-S2                           | 1         | 1.41%   |
| Fujitsu LIFEBOOK E752                       | 1         | 1.41%   |
| DEXP NAVIS P100                             | 1         | 1.41%   |
| Dell Vostro 3550                            | 1         | 1.41%   |
| Dell OptiPlex 580                           | 1         | 1.41%   |
| Dell Inspiron 5515                          | 1         | 1.41%   |
| Dell G5 5090                                | 1         | 1.41%   |
| Biostar G31-M7 TE                           | 1         | 1.41%   |
| ASUS Z170-K                                 | 1         | 1.41%   |
| ASUS X751LB                                 | 1         | 1.41%   |
| ASUS TUF Gaming B550-PLUS                   | 1         | 1.41%   |
| ASUS PRIME X470-PRO                         | 1         | 1.41%   |
| ASUS PRIME H410M-E                          | 1         | 1.41%   |
| ASUS PRIME B550M-K                          | 1         | 1.41%   |
| ASUS P10S-I Series                          | 1         | 1.41%   |
| ASUS M4A88TD-V EVO/USB3                     | 1         | 1.41%   |
| ASUS M4A785TD-M EVO                         | 1         | 1.41%   |
| ASUS K53TA                                  | 1         | 1.41%   |
| ASUS 1000HE                                 | 1         | 1.41%   |
| ASRock A320M-DVS R4.0                       | 1         | 1.41%   |
| Apple MacPro4,1                             | 1         | 1.41%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad                             | 15        | 21.13%  |
| Unknown                                     | 6         | 8.45%   |
| ASUS PRIME                                  | 5         | 7.04%   |
| TUXEDO Pulse                                | 1         | 1.41%   |
| TUXEDO Aura                                 | 1         | 1.41%   |
| Sony VPCL22Z1R                              | 1         | 1.41%   |
| Samsung DP700A3D                            | 1         | 1.41%   |
| PC Engines APU2                             | 1         | 1.41%   |
| Panasonic CF-53AAGHYDM                      | 1         | 1.41%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 1.41%   |
| MSI MS-7C82                                 | 1         | 1.41%   |
| MSI MS-7C37                                 | 1         | 1.41%   |
| MSI MS-7C02                                 | 1         | 1.41%   |
| MSI MS-6788                                 | 1         | 1.41%   |
| MSI Modern                                  | 1         | 1.41%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 1.41%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 1.41%   |
| Lenovo Yoga                                 | 1         | 1.41%   |
| Lenovo ThinkCentre                          | 1         | 1.41%   |
| Lenovo IdeaPad                              | 1         | 1.41%   |
| KOHJINSHA SH                                | 1         | 1.41%   |
| Intel Q3XXG4-P                              | 1         | 1.41%   |
| Intel NUC5PPYB                              | 1         | 1.41%   |
| Intel DH67BL                                | 1         | 1.41%   |
| HP Pavilion                                 | 1         | 1.41%   |
| Gigabyte H87-HD3                            | 1         | 1.41%   |
| Gigabyte H81M-S2PV                          | 1         | 1.41%   |
| Gigabyte G41MT-S2                           | 1         | 1.41%   |
| Fujitsu LIFEBOOK                            | 1         | 1.41%   |
| DEXP NAVIS                                  | 1         | 1.41%   |
| Dell Vostro                                 | 1         | 1.41%   |
| Dell OptiPlex                               | 1         | 1.41%   |
| Dell Inspiron                               | 1         | 1.41%   |
| Dell G5                                     | 1         | 1.41%   |
| Biostar G31-M7                              | 1         | 1.41%   |
| ASUS Z170-K                                 | 1         | 1.41%   |
| ASUS X751LB                                 | 1         | 1.41%   |
| ASUS TUF                                    | 1         | 1.41%   |
| ASUS P10S-I                                 | 1         | 1.41%   |
| ASUS M4A88TD-V                              | 1         | 1.41%   |
| ASUS M4A785TD-M                             | 1         | 1.41%   |
| ASUS K53TA                                  | 1         | 1.41%   |
| ASUS 1000HE                                 | 1         | 1.41%   |
| ASRock A320M-DVS                            | 1         | 1.41%   |
| Apple MacPro4                               | 1         | 1.41%   |
| Apple MacBookPro5                           | 1         | 1.41%   |
| Acer Nitro                                  | 1         | 1.41%   |
| Acer Aspire                                 | 1         | 1.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 8         | 11.27%  |
| 2009    | 8         | 11.27%  |
| Unknown | 8         | 11.27%  |
| 2020    | 7         | 9.86%   |
| 2018    | 6         | 8.45%   |
| 2011    | 6         | 8.45%   |
| 2010    | 6         | 8.45%   |
| 2019    | 4         | 5.63%   |
| 2022    | 3         | 4.23%   |
| 2015    | 3         | 4.23%   |
| 2012    | 3         | 4.23%   |
| 2016    | 2         | 2.82%   |
| 2014    | 2         | 2.82%   |
| 2013    | 2         | 2.82%   |
| 2007    | 1         | 1.41%   |
| 2006    | 1         | 1.41%   |
| 2002    | 1         | 1.41%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Desktop    | 36        | 50.7%   |
| Notebook   | 33        | 46.48%  |
| Mini pc    | 1         | 1.41%   |
| All in one | 1         | 1.41%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 70        | 98.59%  |
| Yes  | 1         | 1.41%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 20        | 28.17%  |
| 8.01-16.0   | 20        | 28.17%  |
| 16.01-24.0  | 11        | 15.49%  |
| 3.01-4.0    | 6         | 8.45%   |
| 2.01-3.0    | 6         | 8.45%   |
| 0.51-1.0    | 3         | 4.23%   |
| 1.01-2.0    | 2         | 2.82%   |
| 32.01-64.0  | 1         | 1.41%   |
| 24.01-32.0  | 1         | 1.41%   |
| 64.01-256.0 | 1         | 1.41%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 64        | 90.14%  |
| 0        | 4         | 5.63%   |
| 0.51-1.0 | 2         | 2.82%   |
| 4.01-8.0 | 1         | 1.41%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 37        | 52.11%  |
| 2      | 18        | 25.35%  |
| 4      | 7         | 9.86%   |
| 3      | 6         | 8.45%   |
| 8      | 1         | 1.41%   |
| 6      | 1         | 1.41%   |
| 5      | 1         | 1.41%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 71        | 100%    |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 59        | 83.1%   |
| No        | 12        | 16.9%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 60.56%  |
| No        | 28        | 39.44%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 40        | 56.34%  |
| Yes       | 31        | 43.66%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Russia      | 17        | 23.94%  |
| Canada      | 11        | 15.49%  |
| Italy       | 7         | 9.86%   |
| USA         | 5         | 7.04%   |
| Netherlands | 5         | 7.04%   |
| UK          | 4         | 5.63%   |
| Poland      | 4         | 5.63%   |
| Germany     | 3         | 4.23%   |
| France      | 3         | 4.23%   |
| India       | 2         | 2.82%   |
| Austria     | 2         | 2.82%   |
| Spain       | 1         | 1.41%   |
| Philippines | 1         | 1.41%   |
| Norway      | 1         | 1.41%   |
| Lithuania   | 1         | 1.41%   |
| Egypt       | 1         | 1.41%   |
| Czechia     | 1         | 1.41%   |
| Chile       | 1         | 1.41%   |
| Argentina   | 1         | 1.41%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Montreal            | 10        | 14.08%  |
| Vladivostok         | 6         | 8.45%   |
| Poortugaal          | 4         | 5.63%   |
| Milan               | 4         | 5.63%   |
| Gdansk              | 3         | 4.23%   |
| Vienna              | 2         | 2.82%   |
| Ozersk              | 2         | 2.82%   |
| Wolverhampton       | 1         | 1.41%   |
| West Valley City    | 1         | 1.41%   |
| Valdivia            | 1         | 1.41%   |
| Tambov              | 1         | 1.41%   |
| Sutton              | 1         | 1.41%   |
| Starogard Gdański  | 1         | 1.41%   |
| St. Albert          | 1         | 1.41%   |
| St Petersburg       | 1         | 1.41%   |
| Springboro          | 1         | 1.41%   |
| Reutov              | 1         | 1.41%   |
| Quezon City         | 1         | 1.41%   |
| Pozzuolo Martesana  | 1         | 1.41%   |
| Oslo                | 1         | 1.41%   |
| Orenburg            | 1         | 1.41%   |
| Oakland             | 1         | 1.41%   |
| Nuremberg           | 1         | 1.41%   |
| Newcastle upon Tyne | 1         | 1.41%   |
| Mumbai              | 1         | 1.41%   |
| Moscow              | 1         | 1.41%   |
| Memmingen           | 1         | 1.41%   |
| Mâcon              | 1         | 1.41%   |
| Krasnodar           | 1         | 1.41%   |
| Kolomna             | 1         | 1.41%   |
| Gianico             | 1         | 1.41%   |
| Ermont              | 1         | 1.41%   |
| Edinburgh           | 1         | 1.41%   |
| Delhi               | 1         | 1.41%   |
| Concesio            | 1         | 1.41%   |
| Columbus            | 1         | 1.41%   |
| Cherepovets         | 1         | 1.41%   |
| Chelyabinsk         | 1         | 1.41%   |
| Český Těšín    | 1         | 1.41%   |
| Cairo               | 1         | 1.41%   |
| Buenos Aires        | 1         | 1.41%   |
| Brooklyn            | 1         | 1.41%   |
| Biot                | 1         | 1.41%   |
| Amsterdam           | 1         | 1.41%   |
| Alytus              | 1         | 1.41%   |
| Alcorisa            | 1         | 1.41%   |
| Aidlingen           | 1         | 1.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 17        | 18     | 17.35%  |
| NVMe                | 14        | 16     | 14.29%  |
| Samsung Electronics | 13        | 18     | 13.27%  |
| Seagate             | 12        | 16     | 12.24%  |
| Hitachi             | 5         | 6      | 5.1%    |
| Toshiba             | 4         | 8      | 4.08%   |
| SanDisk             | 3         | 3      | 3.06%   |
| Kingston            | 3         | 3      | 3.06%   |
| Innostor            | 3         | 3      | 3.06%   |
| HGST                | 3         | 3      | 3.06%   |
| Crucial             | 3         | 3      | 3.06%   |
| OPENBSD             | 2         | 2      | 2.04%   |
| Corsair             | 2         | 2      | 2.04%   |
| XPG                 | 1         | 1      | 1.02%   |
| USB                 | 1         | 1      | 1.02%   |
| StoreJet            | 1         | 1      | 1.02%   |
| PNY                 | 1         | 1      | 1.02%   |
| OWC                 | 1         | 1      | 1.02%   |
| OCZ                 | 1         | 1      | 1.02%   |
| LDLC F6+            | 1         | 1      | 1.02%   |
| KingSpec            | 1         | 1      | 1.02%   |
| Intel               | 1         | 1      | 1.02%   |
| Hoodisk             | 1         | 1      | 1.02%   |
| Generic             | 1         | 1      | 1.02%   |
| Apacer              | 1         | 1      | 1.02%   |
| AMD                 | 1         | 1      | 1.02%   |
| A-DATA Technology   | 1         | 1      | 1.02%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| NVMe Samsung SSD 980 1TB           | 4         | 3.92%   |
| Samsung HM321HI 320GB              | 3         | 2.94%   |
| Innostor SSD 15GB                  | 3         | 2.94%   |
| Toshiba HDWG440 4TB                | 2         | 1.96%   |
| Seagate ST1000DM010-2EP102 1TB     | 2         | 1.96%   |
| OPENBSD SR RAID 1 752GB            | 2         | 1.96%   |
| NVMe WDC PC SN530 SDB 256GB        | 2         | 1.96%   |
| XPG SX950U 240GB                   | 1         | 0.98%   |
| WDC WD800JD-60LSA5 80GB            | 1         | 0.98%   |
| WDC WD7500BPKX-00HPJT0 752GB       | 1         | 0.98%   |
| WDC WD7500BPKT-75PK4T0 752GB       | 1         | 0.98%   |
| WDC WD7500BPKT-00PK4T0 752GB       | 1         | 0.98%   |
| WDC WD6400AARS-00Y5B1 640GB        | 1         | 0.98%   |
| WDC WD5003AZEX-00K1GA0 500GB       | 1         | 0.98%   |
| WDC WD5003ABYX-01WERA2 500GB       | 1         | 0.98%   |
| WDC WD5000LPLX-00ZNTT0 500GB       | 1         | 0.98%   |
| WDC WD5000AZLX-00K2TA0 500GB       | 1         | 0.98%   |
| WDC WD5000AAKX-60U6AA0 500GB       | 1         | 0.98%   |
| WDC WD40EFZX-68AWUN0 4TB           | 1         | 0.98%   |
| WDC WD3200BEVE-00A0HT0 320GB       | 1         | 0.98%   |
| WDC WD20PURX-64P6ZY0 2TB           | 1         | 0.98%   |
| WDC WD1600BEVT-22ZCT0 160GB        | 1         | 0.98%   |
| WDC WD10JPVT-75A1YT0 1TB           | 1         | 0.98%   |
| WDC WD10JPLX-00MBPT0 1TB           | 1         | 0.98%   |
| WDC WD10EZEX-00MFCA0 1TB           | 1         | 0.98%   |
| USB SanDisk 3.2Gen1 64GB           | 1         | 0.98%   |
| Toshiba MG06ACA800E 8TB            | 1         | 0.98%   |
| Toshiba DT01ACA050 500GB           | 1         | 0.98%   |
| StoreJet Transcend 120GB           | 1         | 0.98%   |
| Seagate ST9500420AS 500GB          | 1         | 0.98%   |
| Seagate ST9160821A 160GB           | 1         | 0.98%   |
| Seagate ST380815AS 80GB            | 1         | 0.98%   |
| Seagate ST3750640NS 752GB          | 1         | 0.98%   |
| Seagate ST3250318AS 250GB          | 1         | 0.98%   |
| Seagate ST3250310AS 250GB          | 1         | 0.98%   |
| Seagate ST3160212SCE 160GB         | 1         | 0.98%   |
| Seagate ST250DM000-1BD141 250GB    | 1         | 0.98%   |
| Seagate ST2000DM006-2DM164 2TB     | 1         | 0.98%   |
| Seagate ST1000VX000-1CU162 1TB     | 1         | 0.98%   |
| Seagate ST1000LM049-2GH172 1TB     | 1         | 0.98%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 0.98%   |
| Seagate Expansion 320GB            | 1         | 0.98%   |
| SanDisk SD7UB3Q256G1001 256GB      | 1         | 0.98%   |
| SanDisk Extreme Pro 128GB          | 1         | 0.98%   |
| SanDisk Extreme 55AE 500GB         | 1         | 0.98%   |
| Samsung SSD 870 QVO 2TB            | 1         | 0.98%   |
| Samsung SSD 860 EVO 500GB          | 1         | 0.98%   |
| Samsung SSD 860 EVO 250GB          | 1         | 0.98%   |
| Samsung SSD 850 EVO 500GB          | 1         | 0.98%   |
| Samsung Portable SSD T3 250GB      | 1         | 0.98%   |
| Samsung MZNLN512HMJP-000L7 512GB   | 1         | 0.98%   |
| Samsung MZ7PC128HAFU-000L1 128GB   | 1         | 0.98%   |
| Samsung HD753LJ 752GB              | 1         | 0.98%   |
| Samsung HD161HJ 160GB              | 1         | 0.98%   |
| Samsung Flash Drive FIT 32GB       | 1         | 0.98%   |
| PNY CS900 120GB SSD                | 1         | 0.98%   |
| OWC Mercury Electra 6G SSD         | 1         | 0.98%   |
| OCZ VERTEX3 120GB                  | 1         | 0.98%   |
| NVMe WDS100T3X0C-00SJ 1TB          | 1         | 0.98%   |
| NVMe WDC WDS500G2B0C- 500GB        | 1         | 0.98%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 17        | 18     | 27.87%  |
| Seagate             | 12        | 16     | 19.67%  |
| NVMe                | 8         | 9      | 13.11%  |
| Samsung Electronics | 6         | 6      | 9.84%   |
| Hitachi             | 5         | 6      | 8.2%    |
| Toshiba             | 4         | 8      | 6.56%   |
| HGST                | 3         | 3      | 4.92%   |
| OPENBSD             | 2         | 2      | 3.28%   |
| USB                 | 1         | 1      | 1.64%   |
| StoreJet            | 1         | 1      | 1.64%   |
| LDLC F6+            | 1         | 1      | 1.64%   |
| Generic             | 1         | 1      | 1.64%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 12     | 19.44%  |
| NVMe                | 5         | 6      | 13.89%  |
| SanDisk             | 3         | 3      | 8.33%   |
| Kingston            | 3         | 3      | 8.33%   |
| Innostor            | 3         | 3      | 8.33%   |
| Crucial             | 3         | 3      | 8.33%   |
| Corsair             | 2         | 2      | 5.56%   |
| XPG                 | 1         | 1      | 2.78%   |
| PNY                 | 1         | 1      | 2.78%   |
| OWC                 | 1         | 1      | 2.78%   |
| OCZ                 | 1         | 1      | 2.78%   |
| KingSpec            | 1         | 1      | 2.78%   |
| Intel               | 1         | 1      | 2.78%   |
| Hoodisk             | 1         | 1      | 2.78%   |
| Apacer              | 1         | 1      | 2.78%   |
| AMD                 | 1         | 1      | 2.78%   |
| A-DATA Technology   | 1         | 1      | 2.78%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 43        | 72     | 58.11%  |
| SSD  | 30        | 42     | 40.54%  |
| NVMe | 1         | 1      | 1.35%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 65        | 114    | 98.48%  |
| NVMe | 1         | 1      | 1.52%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 47        | 62     | 57.32%  |
| 0.51-1.0   | 27        | 32     | 32.93%  |
| 1.01-2.0   | 4         | 11     | 4.88%   |
| 3.01-4.0   | 3         | 6      | 3.66%   |
| 4.01-10.0  | 1         | 3      | 1.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 18        | 25.35%  |
| 101-250        | 17        | 23.94%  |
| 21-50          | 16        | 22.54%  |
| 51-100         | 8         | 11.27%  |
| 1-20           | 7         | 9.86%   |
| 501-1000       | 3         | 4.23%   |
| More than 3000 | 2         | 2.82%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 62        | 87.32%  |
| 51-100    | 3         | 4.23%   |
| 21-50     | 2         | 2.82%   |
| 101-250   | 2         | 2.82%   |
| 251-500   | 1         | 1.41%   |
| 2001-3000 | 1         | 1.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| XPG SX950U 240GB                  | 1         | 1      | 7.69%   |
| WDC WD5000AAKX-60U6AA0 500GB      | 1         | 1      | 7.69%   |
| Seagate ST9500420AS 500GB         | 1         | 1      | 7.69%   |
| Seagate ST380815AS 80GB           | 1         | 1      | 7.69%   |
| Seagate ST3750640NS 752GB         | 1         | 2      | 7.69%   |
| Seagate ST3160212SCE 160GB        | 1         | 1      | 7.69%   |
| Seagate ST250DM000-1BD141 250GB   | 1         | 1      | 7.69%   |
| Seagate ST2000DM006-2DM164 2TB    | 1         | 1      | 7.69%   |
| SanDisk SD7UB3Q256G1001 256GB     | 1         | 1      | 7.69%   |
| Samsung Electronics HD753LJ 752GB | 1         | 1      | 7.69%   |
| Samsung Electronics HD161HJ 160GB | 1         | 1      | 7.69%   |
| OCZ VERTEX3 120GB                 | 1         | 1      | 7.69%   |
| A-DATA Technology SP550 480GB     | 1         | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 7      | 41.67%  |
| Samsung Electronics | 2         | 2      | 16.67%  |
| XPG                 | 1         | 1      | 8.33%   |
| WDC                 | 1         | 1      | 8.33%   |
| SanDisk             | 1         | 1      | 8.33%   |
| OCZ                 | 1         | 1      | 8.33%   |
| A-DATA Technology   | 1         | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 7      | 62.5%   |
| Samsung Electronics | 2         | 2      | 25%     |
| WDC                 | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 10     | 66.67%  |
| SSD  | 4         | 4      | 33.33%  |

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
| Works    | 52        | 80     | 65%     |
| Detected | 16        | 20     | 20%     |
| Malfunc  | 11        | 14     | 13.75%  |
| Failed   | 1         | 1      | 1.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 46        | 58.97%  |
| AMD                         | 14        | 17.95%  |
| Samsung Electronics         | 5         | 6.41%   |
| SanDisk                     | 4         | 5.13%   |
| KIOXIA                      | 2         | 2.56%   |
| VIA Technologies            | 1         | 1.28%   |
| Toshiba                     | 1         | 1.28%   |
| Nvidia                      | 1         | 1.28%   |
| Marvell Technology Group    | 1         | 1.28%   |
| Kingston Technology Company | 1         | 1.28%   |
| ASMedia Technology          | 1         | 1.28%   |
| ADATA Technology            | 1         | 1.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                                  | Computers | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 6         | 6.98%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 5         | 5.81%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 4         | 4.65%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 4         | 4.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 4         | 4.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 4         | 4.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 3         | 3.49%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 3         | 3.49%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 3         | 3.49%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 3         | 3.49%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 3         | 3.49%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 2         | 2.33%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 2         | 2.33%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 2         | 2.33%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 2         | 2.33%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 2         | 2.33%   |
| AMD 500 Series Chipset SATA Controller                                                 | 2         | 2.33%   |
| AMD 400 Series Chipset SATA Controller                                                 | 2         | 2.33%   |
| VIA VT6415 PATA IDE Host Controller                                                    | 1         | 1.16%   |
| Toshiba BG3 NVMe SSD Controller                                                        | 1         | 1.16%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 1         | 1.16%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 1         | 1.16%   |
| SanDisk unknown                                                                        | 1         | 1.16%   |
| SanDisk PC SN530                                                                       | 1         | 1.16%   |
| SanDisk PC SN520 NVMe SSD                                                              | 1         | 1.16%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 1         | 1.16%   |
| Samsung NVMe SSD Controller 980                                                        | 1         | 1.16%   |
| Nvidia MCP79 AHCI Controller                                                           | 1         | 1.16%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                       | 1         | 1.16%   |
| KIOXIA NVMe SSD Controller BG4                                                         | 1         | 1.16%   |
| KIOXIA NVMe SSD                                                                        | 1         | 1.16%   |
| Kingston Company OM3PDP3 NVMe SSD                                                      | 1         | 1.16%   |
| Intel Jasper Lake SATA AHCI Controller                                                 | 1         | 1.16%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 1         | 1.16%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 1         | 1.16%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                             | 1         | 1.16%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                      | 1         | 1.16%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 1         | 1.16%   |
| Intel 82801EB (ICH5) SATA Controller                                                   | 1         | 1.16%   |
| Intel 82801CAM IDE U100 Controller                                                     | 1         | 1.16%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 1         | 1.16%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]           | 1         | 1.16%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.16%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller          | 1         | 1.16%   |
| ASMedia ASM1062 Serial ATA Controller                                                  | 1         | 1.16%   |
| AMD FCH SATA Controller D                                                              | 1         | 1.16%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                            | 1         | 1.16%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 53        | 67.09%  |
| NVMe | 14        | 17.72%  |
| IDE  | 12        | 15.19%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 48        | 67.61%  |
| AMD    | 16        | 22.54%  |
| ARM    | 6         | 8.45%   |
| 11th   | 1         | 1.41%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz                         | 4         | 5.63%   |
| ARM Cortex-A72 r0p3                                       | 4         | 5.63%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz                      | 3         | 4.23%   |
| Intel Core i5 CPU M 520 @ 2.40GHz                         | 2         | 2.82%   |
| Intel Core i3-10100F CPU @ 3.60GHz                        | 2         | 2.82%   |
| AMD Ryzen 7 4700U with Radeon Graphics                    | 2         | 2.82%   |
| Intel Xeon CPU E5520 @ 2.27GHz                            | 1         | 1.41%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz                       | 1         | 1.41%   |
| Intel Pentium Silver N6000 @ 1.10GHz                      | 1         | 1.41%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz                  | 1         | 1.41%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz               | 1         | 1.41%   |
| Intel Pentium CPU N3700 @ 1.60GHz                         | 1         | 1.41%   |
| Intel Pentium 4 Mobile CPU 1.60GHz                        | 1         | 1.41%   |
| Intel Pentium 4 CPU 2.40GHz ("GenuineIntel" 686-class)    | 1         | 1.41%   |
| Intel Genuine processor 600MHz ("GenuineIntel" 686-class) | 1         | 1.41%   |
| Intel Genuine CPU T2300 @ 1.66GHz                         | 1         | 1.41%   |
| Intel Core i7-9700K CPU @ 3.60GHz                         | 1         | 1.41%   |
| Intel Core i7-6700 CPU @ 3.40GHz                          | 1         | 1.41%   |
| Intel Core i7-5500U CPU @ 2.40GHz                         | 1         | 1.41%   |
| Intel Core i7-4790 CPU @ 3.60GHz                          | 1         | 1.41%   |
| Intel Core i7-3610QM CPU @ 2.30GHz                        | 1         | 1.41%   |
| Intel Core i7-3520M CPU @ 2.90GHz                         | 1         | 1.41%   |
| Intel Core i7-2670QM CPU @ 2.20GHz                        | 1         | 1.41%   |
| Intel Core i5-8250U CPU @ 1.60GHz                         | 1         | 1.41%   |
| Intel Core i5-6300U CPU @ 2.40GHz                         | 1         | 1.41%   |
| Intel Core i5-5300U CPU @ 2.30GHz                         | 1         | 1.41%   |
| Intel Core i5-4570T CPU @ 2.90GHz                         | 1         | 1.41%   |
| Intel Core i5-3470T CPU @ 2.90GHz                         | 1         | 1.41%   |
| Intel Core i5-3320M CPU @ 2.60GHz                         | 1         | 1.41%   |
| Intel Core i5-3210M CPU @ 2.50GHz                         | 1         | 1.41%   |
| Intel Core i5-10400F CPU @ 2.90GHz                        | 1         | 1.41%   |
| Intel Core i5-10300H CPU @ 2.50GHz                        | 1         | 1.41%   |
| Intel Core i3-5010U CPU @ 2.10GHz                         | 1         | 1.41%   |
| Intel Core i3-4010U CPU @ 1.70GHz                         | 1         | 1.41%   |
| Intel Core i3-3225 CPU @ 3.30GHz                          | 1         | 1.41%   |
| Intel Core i3-10100 CPU @ 3.60GHz                         | 1         | 1.41%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz                     | 1         | 1.41%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz                      | 1         | 1.41%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz                      | 1         | 1.41%   |
| Intel Celeron CPU N3350 @ 1.10GHz                         | 1         | 1.41%   |
| Intel Celeron CPU G1820 @ 2.70GHz                         | 1         | 1.41%   |
| Intel Atom CPU N280 @ 1.66GHz                             | 1         | 1.41%   |
| Intel Atom CPU N270 @ 1.60GHz ("GenuineIntel" 686-class)  | 1         | 1.41%   |
| ARM Cortex-A7 r0p4                                        | 1         | 1.41%   |
| ARM Cortex-A53 r0p4                                       | 1         | 1.41%   |
| AMD Ryzen 9 5950X 16-Core Processor                       | 1         | 1.41%   |
| AMD Ryzen 7 5800X 8-Core Processor                        | 1         | 1.41%   |
| AMD Ryzen 7 4800H with Radeon Graphics                    | 1         | 1.41%   |
| AMD Ryzen 5 5600X 6-Core Processor                        | 1         | 1.41%   |
| AMD Ryzen 5 5500U with Radeon Graphics                    | 1         | 1.41%   |
| AMD Ryzen 5 3600 6-Core Processor                         | 1         | 1.41%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics               | 1         | 1.41%   |
| AMD Phenom II X4 965 Processor                            | 1         | 1.41%   |
| AMD GX-412TC SOC                                          | 1         | 1.41%   |
| AMD E-300 APU with Radeon HD Graphics                     | 1         | 1.41%   |
| AMD Athlon II X4 640 Processor                            | 1         | 1.41%   |
| AMD Athlon II X2 B26 Processor                            | 1         | 1.41%   |
| AMD Athlon 3000G with Radeon Vega Graphics                | 1         | 1.41%   |
| AMD A6-3400M APU with Radeon HD Graphics                  | 1         | 1.41%   |
| 11th Gen Intel Core i5-1135G7 @ 2.40GHz                   | 1         | 1.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 15        | 21.13%  |
| Intel Core i7           | 7         | 9.86%   |
| Intel Core i3           | 6         | 8.45%   |
| ARM Cortex              | 6         | 8.45%   |
| Intel Core 2 Duo        | 5         | 7.04%   |
| AMD Ryzen 7             | 4         | 5.63%   |
| AMD Ryzen 5             | 3         | 4.23%   |
| Intel Xeon              | 2         | 2.82%   |
| Intel Pentium Silver    | 2         | 2.82%   |
| Intel Pentium 4         | 2         | 2.82%   |
| Intel Genuine           | 2         | 2.82%   |
| Intel Celeron           | 2         | 2.82%   |
| Intel Atom              | 2         | 2.82%   |
| Other                   | 1         | 1.41%   |
| Intel Pentium Dual-Core | 1         | 1.41%   |
| Intel Pentium           | 1         | 1.41%   |
| Intel Core 2 Quad       | 1         | 1.41%   |
| AMD Ryzen 9             | 1         | 1.41%   |
| AMD Ryzen 3             | 1         | 1.41%   |
| AMD Phenom II X4        | 1         | 1.41%   |
| AMD GX                  | 1         | 1.41%   |
| AMD E                   | 1         | 1.41%   |
| AMD Athlon II X4        | 1         | 1.41%   |
| AMD Athlon II X2        | 1         | 1.41%   |
| AMD Athlon              | 1         | 1.41%   |
| AMD A6                  | 1         | 1.41%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 21        | 29.58%  |
| Unknown | 20        | 28.17%  |
| 4       | 19        | 26.76%  |
| 8       | 4         | 5.63%   |
| 1       | 3         | 4.23%   |
| 12      | 2         | 2.82%   |
| 32      | 1         | 1.41%   |
| 16      | 1         | 1.41%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 50        | 70.42%  |
| Unknown | 20        | 28.17%  |
| 2       | 1         | 1.41%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 27        | 38.03%  |
| Unknown | 23        | 32.39%  |
| 1       | 21        | 29.58%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 11        | 15.49%  |
| Penryn        | 7         | 9.86%   |
| IvyBridge     | 6         | 8.45%   |
| SandyBridge   | 5         | 7.04%   |
| Zen 2         | 4         | 5.63%   |
| Haswell       | 4         | 5.63%   |
| CometLake     | 4         | 5.63%   |
| Skylake       | 3         | 4.23%   |
| K10           | 3         | 4.23%   |
| Broadwell     | 3         | 4.23%   |
| Zen 3         | 2         | 2.82%   |
| Westmere      | 2         | 2.82%   |
| P6            | 2         | 2.82%   |
| NetBurst      | 2         | 2.82%   |
| KabyLake      | 2         | 2.82%   |
| Bonnell       | 2         | 2.82%   |
| Zen+          | 1         | 1.41%   |
| Zen           | 1         | 1.41%   |
| Silvermont    | 1         | 1.41%   |
| Puma          | 1         | 1.41%   |
| Nehalem       | 1         | 1.41%   |
| K10 Llano     | 1         | 1.41%   |
| Goldmont plus | 1         | 1.41%   |
| Goldmont      | 1         | 1.41%   |
| Bobcat        | 1         | 1.41%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 35        | 51.47%  |
| AMD               | 24        | 35.29%  |
| Nvidia            | 8         | 11.76%  |
| ASPEED Technology | 1         | 1.47%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 5.41%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 5.41%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 5.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 4.05%   |
| Intel HD Graphics 5500                                                                   | 3         | 4.05%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 4.05%   |
| AMD Renoir                                                                               | 3         | 4.05%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 3         | 4.05%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 2.7%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 2.7%    |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 2.7%    |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 2         | 2.7%    |
| AMD RS880 [Radeon HD 4200]                                                               | 2         | 2.7%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 2         | 2.7%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2         | 2.7%    |
| Nvidia TU117M                                                                            | 1         | 1.35%   |
| Nvidia NV28 [GeForce4 Ti 4200 AGP 8x]                                                    | 1         | 1.35%   |
| Nvidia GM108M [GeForce 940M]                                                             | 1         | 1.35%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 1.35%   |
| Nvidia GF108M [NVS 5400M]                                                                | 1         | 1.35%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 1         | 1.35%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 1.35%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 1         | 1.35%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 1.35%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.35%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 1.35%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 1.35%   |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 1.35%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1         | 1.35%   |
| Intel HD Graphics 530                                                                    | 1         | 1.35%   |
| Intel HD Graphics 500                                                                    | 1         | 1.35%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 1.35%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 1.35%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1         | 1.35%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.35%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 1         | 1.35%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 1.35%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 1.35%   |
| AMD Sumo [Radeon HD 6520G]                                                               | 1         | 1.35%   |
| AMD RV770 [Radeon HD 4850]                                                               | 1         | 1.35%   |
| AMD RV710/M92 [Mobility Radeon HD 4350/4550]                                             | 1         | 1.35%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                                      | 1         | 1.35%   |
| AMD RS880 [Radeon HD 4250]                                                               | 1         | 1.35%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 1.35%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 1.35%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 1         | 1.35%   |
| AMD Lucienne                                                                             | 1         | 1.35%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 23        | 32.39%  |
| 1 x AMD        | 21        | 29.58%  |
| 2 x Intel      | 8         | 11.27%  |
| Other          | 7         | 9.86%   |
| 1 x Nvidia     | 5         | 7.04%   |
| Intel + Nvidia | 2         | 2.82%   |
| Intel + AMD    | 2         | 2.82%   |
| 2 x Nvidia     | 1         | 1.41%   |
| 2 x AMD        | 1         | 1.41%   |
| 1 x ASPEED     | 1         | 1.41%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 58        | 81.69%  |
| Unknown | 13        | 18.31%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 71        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Philips                 | 6         | 14.29%  |
| Samsung Electronics     | 5         | 11.9%   |
| Lenovo                  | 5         | 11.9%   |
| LG Display              | 4         | 9.52%   |
| BOE                     | 4         | 9.52%   |
| Chimei Innolux          | 3         | 7.14%   |
| AU Optronics            | 3         | 7.14%   |
| ViewSonic               | 2         | 4.76%   |
| Dell                    | 2         | 4.76%   |
| Chi Mei Optoelectronics | 2         | 4.76%   |
| PANDA                   | 1         | 2.38%   |
| MSI                     | 1         | 2.38%   |
| InfoVision              | 1         | 2.38%   |
| Goldstar                | 1         | 2.38%   |
| Ancor Communications    | 1         | 2.38%   |
| Acer                    | 1         | 2.38%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                    | 6         | 14.29%  |
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch                  | 3         | 7.14%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 2         | 4.76%   |
| ViewSonic LCD Monitor VSCD22B 1920x1080 520x290mm 23.4-inch              | 1         | 2.38%   |
| ViewSonic LCD Monitor VSCC42B 1920x1080 480x270mm 21.7-inch              | 1         | 2.38%   |
| Samsung Electronics SyncMaster SAM03CF 1280x1024 340x270mm 17.1-inch     | 1         | 2.38%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch     | 1         | 2.38%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 350x200mm 15.9-inch     | 1         | 2.38%   |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch   | 1         | 2.38%   |
| Samsung Electronics DM700A-D SEM0324 1920x1080 520x290mm 23.4-inch       | 1         | 2.38%   |
| PANDA LM133LF1L01 NCP13FB 1920x1080 290x170mm 13.2-inch                  | 1         | 2.38%   |
| MSI MAG241C MSI3EA2 1920x1080 520x290mm 23.4-inch                        | 1         | 2.38%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch             | 1         | 2.38%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch              | 1         | 2.38%   |
| LG Display LCD Monitor LGD0215 1920x1080 350x190mm 15.7-inch             | 1         | 2.38%   |
| LG Display LCD Monitor LGD01AB 1280x800 260x160mm 12.0-inch              | 1         | 2.38%   |
| Lenovo LEN S24e-10 LEN61CA 1920x1080 530x300mm 24.0-inch                 | 1         | 2.38%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x170mm 12.2-inch                  | 1         | 2.38%   |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch              | 1         | 2.38%   |
| Goldstar L1752T GSM4434 1280x1024 340x270mm 17.1-inch                    | 1         | 2.38%   |
| Dell E1916H DELF064 1366x768 410x230mm 18.5-inch                         | 1         | 2.38%   |
| Dell 2001FP DELA007 1600x1200 410x310mm 20.2-inch                        | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 380x210mm 17.1-inch          | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN15D7 1920x1080 340x190mm 15.3-inch         | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN152E 1920x1080 340x190mm 15.3-inch         | 1         | 2.38%   |
| BOE LCD Monitor BOE0900 1920x1080 340x190mm 15.3-inch                    | 1         | 2.38%   |
| BOE LCD Monitor BOE08D7 1920x1080 310x170mm 13.9-inch                    | 1         | 2.38%   |
| BOE LCD Monitor BOE07A5 1366x768 340x190mm 15.3-inch                     | 1         | 2.38%   |
| BOE LCD Monitor BOE075A 1366x768 310x170mm 13.9-inch                     | 1         | 2.38%   |
| AU Optronics LCD Monitor AUODF87 1920x1080 340x190mm 15.3-inch           | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch            | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 1         | 2.38%   |
| Ancor Communications ASUS VW199 ACI19ED 1440x900 410x260mm 19.1-inch     | 1         | 2.38%   |
| Acer XZ342CK ACR078B 3440x1440 800x330mm 34.1-inch                       | 1         | 2.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 19        | 45.24%  |
| 1366x768 (WXGA)  | 10        | 23.81%  |
| 1280x800 (WXGA)  | 5         | 11.9%   |
| 1600x900 (HD+)   | 2         | 4.76%   |
| 1280x1024 (SXGA) | 2         | 4.76%   |
| 3840x2160 (4K)   | 1         | 2.38%   |
| 3440x1440        | 1         | 2.38%   |
| 1600x1200        | 1         | 2.38%   |
| 1440x900 (WXGA+) | 1         | 2.38%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 9         | 21.43%  |
| 12     | 8         | 19.05%  |
| 21     | 7         | 16.67%  |
| 13     | 5         | 11.9%   |
| 23     | 3         | 7.14%   |
| 17     | 3         | 7.14%   |
| 54     | 1         | 2.38%   |
| 34     | 1         | 2.38%   |
| 24     | 1         | 2.38%   |
| 20     | 1         | 2.38%   |
| 19     | 1         | 2.38%   |
| 18     | 1         | 2.38%   |
| 11     | 1         | 2.38%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 15        | 35.71%  |
| 401-500     | 10        | 23.81%  |
| 201-300     | 10        | 23.81%  |
| 501-600     | 4         | 9.52%   |
| 701-800     | 1         | 2.38%   |
| 351-400     | 1         | 2.38%   |
| 1001-1500   | 1         | 2.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 32        | 76.19%  |
| 16/10 | 5         | 11.9%   |
| 5/4   | 2         | 4.76%   |
| 4/3   | 1         | 2.38%   |
| 3/2   | 1         | 2.38%   |
| 21/9  | 1         | 2.38%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 11        | 26.19%  |
| 61-70          | 8         | 19.05%  |
| 91-100         | 5         | 11.9%   |
| 81-90          | 4         | 9.52%   |
| 101-110        | 4         | 9.52%   |
| 141-150        | 3         | 7.14%   |
| 151-200        | 2         | 4.76%   |
| More than 1000 | 1         | 2.38%   |
| 71-80          | 1         | 2.38%   |
| 51-60          | 1         | 2.38%   |
| 351-500        | 1         | 2.38%   |
| 121-130        | 1         | 2.38%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 17        | 41.46%  |
| 51-100  | 12        | 29.27%  |
| 101-120 | 11        | 26.83%  |
| 161-240 | 1         | 2.44%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 50        | 70.42%  |
| 0     | 20        | 28.17%  |
| 2     | 1         | 1.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 36        | 40.45%  |
| Realtek Semiconductor             | 32        | 35.96%  |
| Qualcomm Atheros                  | 7         | 7.87%   |
| Qualcomm Atheros Communications   | 3         | 3.37%   |
| Ericsson Business Mobile Networks | 3         | 3.37%   |
| Broadcom                          | 3         | 3.37%   |
| Qcom                              | 1         | 1.12%   |
| Nvidia                            | 1         | 1.12%   |
| Marvell Technology Group          | 1         | 1.12%   |
| Dell                              | 1         | 1.12%   |
| AVM                               | 1         | 1.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 23        | 20.54%  |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 6         | 5.36%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6         | 5.36%   |
| Intel Wi-Fi 6 AX200                                                           | 4         | 3.57%   |
| Intel Ultimate N WiFi Link 5300                                               | 4         | 3.57%   |
| Intel 82567LM Gigabit Network Connection                                      | 4         | 3.57%   |
| Qualcomm Atheros AR9271 802.11n                                               | 3         | 2.68%   |
| Intel 82574L Gigabit Network Connection                                       | 3         | 2.68%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 2         | 1.79%   |
| Realtek RTL8125 2.5GbE Controller                                             | 2         | 1.79%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2         | 1.79%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2         | 1.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 2         | 1.79%   |
| Intel I211 Gigabit Network Connection                                         | 2         | 1.79%   |
| Intel I210 Gigabit Network Connection                                         | 2         | 1.79%   |
| Intel Centrino Advanced-N 6200                                                | 2         | 1.79%   |
| Intel 82577LM Gigabit Network Connection                                      | 2         | 1.79%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III   | 2         | 1.79%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                        | 2         | 1.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.89%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 1         | 0.89%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                              | 1         | 0.89%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 1         | 0.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1         | 0.89%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1         | 0.89%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 0.89%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1         | 0.89%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                 | 1         | 0.89%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1         | 0.89%   |
| Qcom RT73 USB Wireless LAN Card                                               | 1         | 0.89%   |
| Nvidia MCP79 Ethernet                                                         | 1         | 0.89%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 1         | 0.89%   |
| Intel Wireless 8260                                                           | 1         | 0.89%   |
| Intel Wireless 7265                                                           | 1         | 0.89%   |
| Intel Wireless 7260                                                           | 1         | 0.89%   |
| Intel Wireless 3165                                                           | 1         | 0.89%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 1         | 0.89%   |
| Intel Wi-Fi 6 AX201 160MHz                                                    | 1         | 0.89%   |
| Intel Wi-Fi 6 AX201                                                           | 1         | 0.89%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 1         | 0.89%   |
| Intel Ethernet Connection I219-LM                                             | 1         | 0.89%   |
| Intel Ethernet Connection I218-LM                                             | 1         | 0.89%   |
| Intel Ethernet Connection I217-LM                                             | 1         | 0.89%   |
| Intel Ethernet Connection (3) I218-LM                                         | 1         | 0.89%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 0.89%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 1         | 0.89%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 1         | 0.89%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                 | 1         | 0.89%   |
| Intel Centrino Advanced-N 6235                                                | 1         | 0.89%   |
| Intel 82579V Gigabit Network Connection                                       | 1         | 0.89%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 0.89%   |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module            | 1         | 0.89%   |
| Dell Dell Wireless 5550 HSPA+ Mini-Card Network Adapter                       | 1         | 0.89%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                           | 1         | 0.89%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 1         | 0.89%   |
| AVM A1 ISDN [Fritz]                                                           | 1         | 0.89%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 28        | 62.22%  |
| Qualcomm Atheros                | 5         | 11.11%  |
| Realtek Semiconductor           | 4         | 8.89%   |
| Qualcomm Atheros Communications | 3         | 6.67%   |
| Broadcom                        | 3         | 6.67%   |
| Qcom                            | 1         | 2.22%   |
| Dell                            | 1         | 2.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 6         | 13.33%  |
| Intel Wi-Fi 6 AX200                                            | 4         | 8.89%   |
| Intel Ultimate N WiFi Link 5300                                | 4         | 8.89%   |
| Qualcomm Atheros AR9271 802.11n                                | 3         | 6.67%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 4.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 4.44%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 4.44%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 2         | 4.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.22%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1         | 2.22%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 2.22%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 2.22%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 2.22%   |
| Qcom RT73 USB Wireless LAN Card                                | 1         | 2.22%   |
| Intel Wireless 8260                                            | 1         | 2.22%   |
| Intel Wireless 7265                                            | 1         | 2.22%   |
| Intel Wireless 7260                                            | 1         | 2.22%   |
| Intel Wireless 3165                                            | 1         | 2.22%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1         | 2.22%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 1         | 2.22%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 2.22%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 2.22%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 2.22%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 2.22%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 2.22%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 1         | 2.22%   |
| Dell Dell Wireless 5550 HSPA+ Mini-Card Network Adapter        | 1         | 2.22%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 1         | 2.22%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 31        | 50.82%  |
| Intel                    | 24        | 39.34%  |
| Qualcomm Atheros         | 3         | 4.92%   |
| Nvidia                   | 1         | 1.64%   |
| Marvell Technology Group | 1         | 1.64%   |
| Broadcom                 | 1         | 1.64%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 23        | 37.1%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6         | 9.68%   |
| Intel 82567LM Gigabit Network Connection                                      | 4         | 6.45%   |
| Intel 82574L Gigabit Network Connection                                       | 3         | 4.84%   |
| Realtek RTL8125 2.5GbE Controller                                             | 2         | 3.23%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2         | 3.23%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2         | 3.23%   |
| Intel I211 Gigabit Network Connection                                         | 2         | 3.23%   |
| Intel I210 Gigabit Network Connection                                         | 2         | 3.23%   |
| Intel 82577LM Gigabit Network Connection                                      | 2         | 3.23%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                              | 1         | 1.61%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 1         | 1.61%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1         | 1.61%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                 | 1         | 1.61%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1         | 1.61%   |
| Nvidia MCP79 Ethernet                                                         | 1         | 1.61%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 1         | 1.61%   |
| Intel Ethernet Connection I219-LM                                             | 1         | 1.61%   |
| Intel Ethernet Connection I218-LM                                             | 1         | 1.61%   |
| Intel Ethernet Connection I217-LM                                             | 1         | 1.61%   |
| Intel Ethernet Connection (3) I218-LM                                         | 1         | 1.61%   |
| Intel 82579V Gigabit Network Connection                                       | 1         | 1.61%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 1.61%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                           | 1         | 1.61%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 59        | 55.14%  |
| WiFi     | 43        | 40.19%  |
| Unknown  | 4         | 3.74%   |
| Modem    | 1         | 0.93%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 32        | 50.79%  |
| Ethernet | 31        | 49.21%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 37        | 52.11%  |
| 1     | 22        | 30.99%  |
| 0     | 7         | 9.86%   |
| 3     | 4         | 5.63%   |
| 4     | 1         | 1.41%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 70        | 98.59%  |
| Yes  | 1         | 1.41%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 14        | 45.16%  |
| Broadcom                        | 7         | 22.58%  |
| Foxconn / Hon Hai               | 2         | 6.45%   |
| Apple                           | 2         | 6.45%   |
| Alps Electric                   | 2         | 6.45%   |
| Realtek Semiconductor           | 1         | 3.23%   |
| Qualcomm Atheros Communications | 1         | 3.23%   |
| IMC Networks                    | 1         | 3.23%   |
| ASUSTek Computer                | 1         | 3.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 4         | 12.9%   |
| Intel AX200 Bluetooth                                       | 3         | 9.68%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 3         | 9.68%   |
| Intel AX201 Bluetooth                                       | 2         | 6.45%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 6.45%   |
| Alps Electric UGTZ4 Bluetooth                               | 2         | 6.45%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 3.23%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 3.23%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 3.23%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 3.23%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 1         | 3.23%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 1         | 3.23%   |
| Intel AX210 Bluetooth                                       | 1         | 3.23%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 3.23%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 3.23%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device    | 1         | 3.23%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 1         | 3.23%   |
| Broadcom BCM2046 Bluetooth Device                           | 1         | 3.23%   |
| ASUS Broadcom Bluetooth 2.1                                 | 1         | 3.23%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1         | 3.23%   |
| Apple Bluetooth Host Controller                             | 1         | 3.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 45        | 60%     |
| AMD                 | 23        | 30.67%  |
| Nvidia              | 5         | 6.67%   |
| Creative Labs       | 1         | 1.33%   |
| C-Media Electronics | 1         | 1.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 6.32%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 6.32%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 6.32%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 5.26%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 4.21%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4         | 4.21%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 4.21%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 4.21%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 3.16%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 3.16%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 3         | 3.16%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 3.16%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 3.16%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 3.16%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 2.11%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 2         | 2.11%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 2.11%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 2         | 2.11%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 2.11%   |
| AMD Navi 10 HDMI Audio                                                                            | 2         | 2.11%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 2.11%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 1.05%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 1.05%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 1.05%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 1.05%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 1.05%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 1.05%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.05%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.05%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.05%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.05%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.05%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1         | 1.05%   |
| Intel 82801CA/CAM AC'97 Audio Controller                                                          | 1         | 1.05%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 1.05%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.05%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                                                | 1         | 1.05%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                                     | 1         | 1.05%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 1.05%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 1.05%   |
| AMD RV770 HDMI Audio [Radeon HD 4850/4870]                                                        | 1         | 1.05%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 1.05%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 1         | 1.05%   |
| AMD FCH Azalia Controller                                                                         | 1         | 1.05%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 1         | 1.05%   |

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
| Chicony Electronics                    | 10        | 43.48%  |
| Acer                                   | 4         | 17.39%  |
| Ricoh                                  | 2         | 8.7%    |
| Sunplus Innovation Technology          | 1         | 4.35%   |
| Silicon Motion                         | 1         | 4.35%   |
| Realtek Semiconductor                  | 1         | 4.35%   |
| Quanta                                 | 1         | 4.35%   |
| Denron                                 | 1         | 4.35%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 4.35%   |
| Alcor Micro                            | 1         | 4.35%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 3         | 13.04%  |
| Chicony Integrated Camera [ThinkPad]                                       | 2         | 8.7%    |
| Sunplus Integrated_Webcam_HD                                               | 1         | 4.35%   |
| Silicon Motion WebCam SC-10IRQ12340N                                       | 1         | 4.35%   |
| Ricoh USB2.0 Camera                                                        | 1         | 4.35%   |
| Ricoh Integrated Webcam                                                    | 1         | 4.35%   |
| Realtek USB Camera                                                         | 1         | 4.35%   |
| Quanta VGA WebCam                                                          | 1         | 4.35%   |
| Denron Corp., 2M Front Camera                                              | 1         | 4.35%   |
| Chicony Lenovo Integrated Camera UVC                                       | 1         | 4.35%   |
| Chicony Lenovo Integrated Camera (0.3MP)                                   | 1         | 4.35%   |
| Chicony HD Webcam                                                          | 1         | 4.35%   |
| Chicony FJ Camera                                                          | 1         | 4.35%   |
| Chicony 2.0M UVC Webcam / CNF7129                                          | 1         | 4.35%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 4.35%   |
| Alcor Micro ASUS USB2.0 WebCam                                             | 1         | 4.35%   |
| Acer Integrated Camera                                                     | 1         | 4.35%   |
| Acer HD Webcam                                                             | 1         | 4.35%   |
| Acer EasyCamera                                                            | 1         | 4.35%   |
| Acer BisonCam, NB Pro                                                      | 1         | 4.35%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 3         | 50%     |
| Upek             | 2         | 33.33%  |
| AuthenTec        | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 33.33%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 16.67%  |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 16.67%  |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 16.67%  |
| AuthenTec AuthenTec Inc. AES2660                       | 1         | 16.67%  |

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
| 1     | 30        | 42.25%  |
| 0     | 22        | 30.99%  |
| 2     | 13        | 18.31%  |
| 3     | 4         | 5.63%   |
| 5     | 1         | 1.41%   |
| 4     | 1         | 1.41%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 37        | 49.33%  |
| Graphics card            | 15        | 20%     |
| Firewire controller      | 9         | 12%     |
| Net/wireless             | 8         | 10.67%  |
| Sound                    | 2         | 2.67%   |
| Network                  | 2         | 2.67%   |
| Storage/ata              | 1         | 1.33%   |
| Storage                  | 1         | 1.33%   |

