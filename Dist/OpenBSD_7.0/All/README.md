OpenBSD 7.0 - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for OpenBSD 7.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/OpenBSD_7.0/Desktop/README.md) and [notebooks](/Dist/OpenBSD_7.0/Notebook/README.md).

Full-feature report is available here: https://bsd-hardware.info/?view=trends

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
| Unknown       | Hardkernel ODROID-N2        | Desktop     | [42f6e357c9](https://bsd-hardware.info/?probe=42f6e357c9) | Nov 05, 2021 |
| Google        | Grunt                       | Notebook    | [aa07a1dd40](https://bsd-hardware.info/?probe=aa07a1dd40) | Nov 05, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [cdccf02902](https://bsd-hardware.info/?probe=cdccf02902) | Nov 04, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [2471e3f337](https://bsd-hardware.info/?probe=2471e3f337) | Nov 04, 2021 |
| Yanling       | YL-KBR6L                    | Desktop     | [35f1c905eb](https://bsd-hardware.info/?probe=35f1c905eb) | Nov 04, 2021 |
| Google        | Grunt                       | Notebook    | [c87e033731](https://bsd-hardware.info/?probe=c87e033731) | Nov 01, 2021 |
| Panasonic     | CF-53AAGHYDM                | Notebook    | [721ef0235c](https://bsd-hardware.info/?probe=721ef0235c) | Oct 30, 2021 |
| HP            | 0A60h                       | Desktop     | [5c227c5b61](https://bsd-hardware.info/?probe=5c227c5b61) | Oct 27, 2021 |
| Matsushita... | CF-48V4KNDQM                | Notebook    | [9e254ab443](https://bsd-hardware.info/?probe=9e254ab443) | Oct 23, 2021 |
| ASUSTek       | 1000HE                      | Notebook    | [1d5e3e5bc3](https://bsd-hardware.info/?probe=1d5e3e5bc3) | Oct 22, 2021 |
| Google        | Grunt                       | Notebook    | [259f96d9c8](https://bsd-hardware.info/?probe=259f96d9c8) | Oct 22, 2021 |
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
| Supermicro    | X11SCE-F                    | Server      | [5731b09f69](https://bsd-hardware.info/?probe=5731b09f69) | Oct 11, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B      | Desktop     | [49173900e7](https://bsd-hardware.info/?probe=49173900e7) | Oct 04, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B      | Desktop     | [d05a877535](https://bsd-hardware.info/?probe=d05a877535) | Oct 03, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [46672cf89f](https://bsd-hardware.info/?probe=46672cf89f) | Oct 01, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [d9762d6c2d](https://bsd-hardware.info/?probe=d9762d6c2d) | Sep 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [0d00ce5de9](https://bsd-hardware.info/?probe=0d00ce5de9) | Sep 22, 2021 |
| Gigabyte      | BRi3(H)-10110               | Desktop     | [9aa3540749](https://bsd-hardware.info/?probe=9aa3540749) | Sep 09, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | Notebook    | [4cc349d29a](https://bsd-hardware.info/?probe=4cc349d29a) | Sep 08, 2021 |
| Lenovo        | ThinkPad P73 20QRS00200     | Notebook    | [dfc86a0368](https://bsd-hardware.info/?probe=dfc86a0368) | Aug 29, 2021 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 50        | 86.21%  |
| i386  | 4         | 6.9%    |
| arm64 | 3         | 5.17%   |
| armv7 | 1         | 1.72%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| fvwm    | 46        | 77.97%  |
| Console | 10        | 16.95%  |
| XFCE    | 1         | 1.69%   |
| Mutter  | 1         | 1.69%   |
| iwm     | 1         | 1.69%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 46        | 79.31%  |
| Console | 12        | 20.69%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 51        | 86.44%  |
| SLiM    | 5         | 8.47%   |
| GDM     | 3         | 5.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 46        | 77.97%  |
| en_US   | 6         | 10.17%  |
| fr_FR   | 2         | 3.39%   |
| zh_CN   | 1         | 1.69%   |
| ru_RU   | 1         | 1.69%   |
| en_GB   | 1         | 1.69%   |
| de_DE   | 1         | 1.69%   |
| C       | 1         | 1.69%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 37        | 63.79%  |
| BIOS | 21        | 36.21%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ffs  | 58        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 34        | 57.63%  |
| MBR  | 25        | 42.37%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 18        | 31.03%  |
| Gigabyte Technology            | 5         | 8.62%   |
| Dell                           | 4         | 6.9%    |
| Hewlett-Packard                | 3         | 5.17%   |
| Samsung Electronics            | 2         | 3.45%   |
| Raspberry Pi Foundation        | 2         | 3.45%   |
| Panasonic                      | 2         | 3.45%   |
| MSI                            | 2         | 3.45%   |
| Matsushita Electric Industrial | 2         | 3.45%   |
| ASUSTek Computer               | 2         | 3.45%   |
| Unknown                        | 2         | 3.45%   |
| Yanling                        | 1         | 1.72%   |
| WYSE                           | 1         | 1.72%   |
| Supermicro                     | 1         | 1.72%   |
| Protectli                      | 1         | 1.72%   |
| PC Engines                     | 1         | 1.72%   |
| Microsoft                      | 1         | 1.72%   |
| Intel                          | 1         | 1.72%   |
| Google                         | 1         | 1.72%   |
| Framework                      | 1         | 1.72%   |
| Casper                         | 1         | 1.72%   |
| ASRock                         | 1         | 1.72%   |
| Apple                          | 1         | 1.72%   |
| Alienware                      | 1         | 1.72%   |
| Acer                           | 1         | 1.72%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 2         | 3.45%   |
| Yanling YL-KBR6L                            | 1         | 1.72%   |
| WYSE D CLASS                                | 1         | 1.72%   |
| Supermicro X11SCE-F                         | 1         | 1.72%   |
| Samsung R720                                | 1         | 1.72%   |
| Samsung 530XBB                              | 1         | 1.72%   |
| RPi Raspberry Pi 400                        | 1         | 1.72%   |
| RPi Raspberry Pi 4 Model B                  | 1         | 1.72%   |
| Protectli FW6                               | 1         | 1.72%   |
| PC Engines APU2                             | 1         | 1.72%   |
| Panasonic CF-53AAGHYDM                      | 1         | 1.72%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 1.72%   |
| MSI MS-7D54                                 | 1         | 1.72%   |
| MSI MS-7C56                                 | 1         | 1.72%   |
| Microsoft Surface Pro 7                     | 1         | 1.72%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 1.72%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 1.72%   |
| Lenovo V130-15IGM 81HL                      | 1         | 1.72%   |
| Lenovo ThinkPad Yoga 11e 20DAS02S00         | 1         | 1.72%   |
| Lenovo ThinkPad X61 7675H7U                 | 1         | 1.72%   |
| Lenovo ThinkPad X220 429043U                | 1         | 1.72%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW0061MX  | 1         | 1.72%   |
| Lenovo ThinkPad X1 Carbon 5th 20HR0068GE    | 1         | 1.72%   |
| Lenovo ThinkPad T480 20L5S1S000             | 1         | 1.72%   |
| Lenovo ThinkPad T430 2347GZU                | 1         | 1.72%   |
| Lenovo ThinkPad T420s 41742BU               | 1         | 1.72%   |
| Lenovo ThinkPad T420 4236MBG                | 1         | 1.72%   |
| Lenovo ThinkPad T410 2537N24                | 1         | 1.72%   |
| Lenovo ThinkPad P73 20QRS00200              | 1         | 1.72%   |
| Lenovo ThinkPad L14 Gen 1 20U1000VGE        | 1         | 1.72%   |
| Lenovo ThinkPad Edge E430 3254A68           | 1         | 1.72%   |
| Lenovo ThinkPad E490 20N8CTO1WW             | 1         | 1.72%   |
| Lenovo ThinkPad E14 Gen 2 20T6S02Y00        | 1         | 1.72%   |
| Lenovo ThinkCentre M73z 10BB001DRU          | 1         | 1.72%   |
| Lenovo IdeaPad 330-15ARR 81D2               | 1         | 1.72%   |
| Intel SharkBay Platform                     | 1         | 1.72%   |
| HP EliteBook 2530p                          | 1         | 1.72%   |
| HP Compaq dc5700 Microtower                 | 1         | 1.72%   |
| HP Compaq 15                                | 1         | 1.72%   |
| Google Grunt                                | 1         | 1.72%   |
| Gigabyte Z590 VISION G                      | 1         | 1.72%   |
| Gigabyte X470 AORUS ULTRA GAMING            | 1         | 1.72%   |
| Gigabyte H81M-S2PV                          | 1         | 1.72%   |
| Gigabyte BRi3(H)-10110                      | 1         | 1.72%   |
| Gigabyte B450M DS3H                         | 1         | 1.72%   |
| Framework Laptop                            | 1         | 1.72%   |
| Dell Vostro 3500                            | 1         | 1.72%   |
| Dell Latitude 3400                          | 1         | 1.72%   |
| Dell Inspiron 5570                          | 1         | 1.72%   |
| Dell G15 5510                               | 1         | 1.72%   |
| Casper EXCALIBUR G900                       | 1         | 1.72%   |
| ASUS P10S-I Series                          | 1         | 1.72%   |
| ASUS 1000HE                                 | 1         | 1.72%   |
| ASRock X570 Pro4                            | 1         | 1.72%   |
| Apple MacBookPro9,2                         | 1         | 1.72%   |
| Alienware m15                               | 1         | 1.72%   |
| Acer AO722                                  | 1         | 1.72%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad                             | 15        | 25.86%  |
| RPi Raspberry                               | 2         | 3.45%   |
| HP Compaq                                   | 2         | 3.45%   |
| Unknown                                     | 2         | 3.45%   |
| Yanling YL-KBR6L                            | 1         | 1.72%   |
| WYSE D                                      | 1         | 1.72%   |
| Supermicro X11SCE-F                         | 1         | 1.72%   |
| Samsung R720                                | 1         | 1.72%   |
| Samsung 530XBB                              | 1         | 1.72%   |
| Protectli FW6                               | 1         | 1.72%   |
| PC Engines APU2                             | 1         | 1.72%   |
| Panasonic CF-53AAGHYDM                      | 1         | 1.72%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 1.72%   |
| MSI MS-7D54                                 | 1         | 1.72%   |
| MSI MS-7C56                                 | 1         | 1.72%   |
| Microsoft Surface                           | 1         | 1.72%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 1.72%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 1.72%   |
| Lenovo V130-15IGM                           | 1         | 1.72%   |
| Lenovo ThinkCentre                          | 1         | 1.72%   |
| Lenovo IdeaPad                              | 1         | 1.72%   |
| Intel SharkBay                              | 1         | 1.72%   |
| HP EliteBook                                | 1         | 1.72%   |
| Google Grunt                                | 1         | 1.72%   |
| Gigabyte Z590                               | 1         | 1.72%   |
| Gigabyte X470                               | 1         | 1.72%   |
| Gigabyte H81M-S2PV                          | 1         | 1.72%   |
| Gigabyte BRi3(H)-10110                      | 1         | 1.72%   |
| Gigabyte B450M                              | 1         | 1.72%   |
| Framework Laptop                            | 1         | 1.72%   |
| Dell Vostro                                 | 1         | 1.72%   |
| Dell Latitude                               | 1         | 1.72%   |
| Dell Inspiron                               | 1         | 1.72%   |
| Dell G15                                    | 1         | 1.72%   |
| Casper EXCALIBUR                            | 1         | 1.72%   |
| ASUS P10S-I                                 | 1         | 1.72%   |
| ASUS 1000HE                                 | 1         | 1.72%   |
| ASRock X570                                 | 1         | 1.72%   |
| Apple MacBookPro9                           | 1         | 1.72%   |
| Alienware m15                               | 1         | 1.72%   |
| Acer AO722                                  | 1         | 1.72%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 9         | 15.52%  |
| 2020    | 9         | 15.52%  |
| 2019    | 8         | 13.79%  |
| 2011    | 5         | 8.62%   |
| 2018    | 4         | 6.9%    |
| 2015    | 4         | 6.9%    |
| 2010    | 3         | 5.17%   |
| Unknown | 3         | 5.17%   |
| 2014    | 2         | 3.45%   |
| 2009    | 2         | 3.45%   |
| 2006    | 2         | 3.45%   |
| 2022    | 1         | 1.72%   |
| 2017    | 1         | 1.72%   |
| 2016    | 1         | 1.72%   |
| 2013    | 1         | 1.72%   |
| 2012    | 1         | 1.72%   |
| 2007    | 1         | 1.72%   |
| 2002    | 1         | 1.72%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 37        | 63.79%  |
| Desktop  | 19        | 32.76%  |
| Tablet   | 1         | 1.72%   |
| Server   | 1         | 1.72%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 55        | 94.83%  |
| Yes  | 3         | 5.17%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 14        | 24.14%  |
| 16.01-24.0  | 11        | 18.97%  |
| 4.01-8.0    | 10        | 17.24%  |
| 3.01-4.0    | 10        | 17.24%  |
| 32.01-64.0  | 5         | 8.62%   |
| 2.01-3.0    | 3         | 5.17%   |
| 1.01-2.0    | 2         | 3.45%   |
| 64.01-256.0 | 1         | 1.72%   |
| 0.51-1.0    | 1         | 1.72%   |
| 0.01-0.5    | 1         | 1.72%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 49        | 84.48%  |
| 0.51-1.0 | 5         | 8.62%   |
| 0        | 2         | 3.45%   |
| 1.01-2.0 | 1         | 1.72%   |
| Unknown  | 1         | 1.72%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 32        | 54.24%  |
| 2      | 18        | 30.51%  |
| 4      | 4         | 6.78%   |
| 3      | 4         | 6.78%   |
| 6      | 1         | 1.69%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 57        | 98.28%  |
| Yes       | 1         | 1.72%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 48        | 82.76%  |
| No        | 10        | 17.24%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 41        | 70.69%  |
| No        | 17        | 29.31%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 30        | 51.72%  |
| Yes       | 28        | 48.28%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 13        | 22.41%  |
| Canada      | 9         | 15.52%  |
| Germany     | 8         | 13.79%  |
| Russia      | 6         | 10.34%  |
| Sweden      | 5         | 8.62%   |
| Poland      | 4         | 6.9%    |
| France      | 3         | 5.17%   |
| Switzerland | 2         | 3.45%   |
| Vietnam     | 1         | 1.72%   |
| Ukraine     | 1         | 1.72%   |
| UK          | 1         | 1.72%   |
| Finland     | 1         | 1.72%   |
| Czechia     | 1         | 1.72%   |
| Cyprus      | 1         | 1.72%   |
| China       | 1         | 1.72%   |
| Brazil      | 1         | 1.72%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Montreal          | 6         | 9.84%   |
| Saint-Laurent     | 3         | 4.92%   |
| Paris             | 3         | 4.92%   |
| Portland          | 2         | 3.28%   |
| Moscow            | 2         | 3.28%   |
| Miedziana Gora    | 2         | 3.28%   |
| Henan             | 2         | 3.28%   |
| Frankfurt am Main | 2         | 3.28%   |
| Zurich            | 1         | 1.64%   |
| Zhukovskiy        | 1         | 1.64%   |
| Yekaterinburg     | 1         | 1.64%   |
| Wroclaw           | 1         | 1.64%   |
| Wolfsburg         | 1         | 1.64%   |
| Wheaton           | 1         | 1.64%   |
| Weinbohla         | 1         | 1.64%   |
| Warner            | 1         | 1.64%   |
| Voskresensk       | 1         | 1.64%   |
| Syeverodonets'k   | 1         | 1.64%   |
| Stockholm         | 1         | 1.64%   |
| St Petersburg     | 1         | 1.64%   |
| Skellefte??       | 1         | 1.64%   |
| Sinzig            | 1         | 1.64%   |
| Sheboygan         | 1         | 1.64%   |
| Sao Vicente       | 1         | 1.64%   |
| Queens            | 1         | 1.64%   |
| Prague            | 1         | 1.64%   |
| Poplar            | 1         | 1.64%   |
| Pacierzow         | 1         | 1.64%   |
| Omaha             | 1         | 1.64%   |
| Oensingen         | 1         | 1.64%   |
| Nuremberg         | 1         | 1.64%   |
| Munich            | 1         | 1.64%   |
| Mountain View     | 1         | 1.64%   |
| Matfors           | 1         | 1.64%   |
| Lidkoeping        | 1         | 1.64%   |
| Larnaca           | 1         | 1.64%   |
| Kingman           | 1         | 1.64%   |
| Irvine            | 1         | 1.64%   |
| Hohhot            | 1         | 1.64%   |
| Ho Chi Minh City  | 1         | 1.64%   |
| Helsinki          | 1         | 1.64%   |
| Gettysburg        | 1         | 1.64%   |
| Erlangen          | 1         | 1.64%   |
| Dallas            | 1         | 1.64%   |
| Berlin            | 1         | 1.64%   |
| Ames              | 1         | 1.64%   |
| Akarp             | 1         | 1.64%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor                             | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| NVMe                               | 21        | 26     | 26.92%  |
| WDC                                | 12        | 12     | 15.38%  |
| Samsung Electronics                | 8         | 10     | 10.26%  |
| Toshiba                            | 6         | 6      | 7.69%   |
| Kingston                           | 5         | 7      | 6.41%   |
| Seagate                            | 4         | 4      | 5.13%   |
| Hitachi                            | 3         | 3      | 3.85%   |
| SK Hynix                           | 2         | 2      | 2.56%   |
| Intel                              | 2         | 3      | 2.56%   |
| Crucial                            | 2         | 2      | 2.56%   |
| StoreJet                           | 1         | 1      | 1.28%   |
| SanDisk                            | 1         | 1      | 1.28%   |
| Product:              USB DISK 3.0 | 1         | 1      | 1.28%   |
| PLEXTOR                            | 1         | 1      | 1.28%   |
| OPENBSD                            | 1         | 1      | 1.28%   |
| Netac                              | 1         | 1      | 1.28%   |
| Lexar                              | 1         | 1      | 1.28%   |
| HPE                                | 1         | 2      | 1.28%   |
| HGST                               | 1         | 1      | 1.28%   |
| ASMT                               | 1         | 1      | 1.28%   |
| Apple                              | 1         | 1      | 1.28%   |
| Apacer                             | 1         | 1      | 1.28%   |
| A-DATA Technology                  | 1         | 1      | 1.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| NVMe WDC PC SN730 SDB 256GB                          | 3         | 3.75%   |
| Toshiba MK2556GSY 250GB                              | 2         | 2.5%    |
| Samsung Flash Drive FIT 32GB                         | 2         | 2.5%    |
| NVMe Samsung SSD 970 250GB                           | 2         | 2.5%    |
| WDC WDS480G2G0B-00EPW0 480GB                         | 1         | 1.25%   |
| WDC WDS240G2G0B-00EPW0 240GB                         | 1         | 1.25%   |
| WDC WD7500BPKX-00HPJT0 752GB                         | 1         | 1.25%   |
| WDC WD7500BPKT-00PK4T0 752GB                         | 1         | 1.25%   |
| WDC WD6400AARS-00Y5B1 640GB                          | 1         | 1.25%   |
| WDC WD5000LPLX-00ZNTT0 500GB                         | 1         | 1.25%   |
| WDC WD5000LPCX-24VHAT0 500GB                         | 1         | 1.25%   |
| WDC WD3200BEVE-00A0HT0 320GB                         | 1         | 1.25%   |
| WDC WD20PURX-64P6ZY0 2TB                             | 1         | 1.25%   |
| WDC WD10JPLX-00MBPT0 1TB                             | 1         | 1.25%   |
| WDC WD10EADS-00M2B0 1TB                              | 1         | 1.25%   |
| WDC WD101KFBX-68R56N0 10TB                           | 1         | 1.25%   |
| Toshiba TR200 240GB                                  | 1         | 1.25%   |
| Toshiba MQ04ABF100 1TB                               | 1         | 1.25%   |
| Toshiba MK1629GSGF 160GB                             | 1         | 1.25%   |
| Toshiba DT01ACA050 500GB                             | 1         | 1.25%   |
| StoreJet Transcend 1TB                               | 1         | 1.25%   |
| SK Hynix SC311 SATA 256GB                            | 1         | 1.25%   |
| SK Hynix HFS128G32TNF-N3A0A 128GB                    | 1         | 1.25%   |
| Seagate ST9160821A 160GB                             | 1         | 1.25%   |
| Seagate ST3250318AS 250GB                            | 1         | 1.25%   |
| Seagate ST250DM000-1BD141 250GB                      | 1         | 1.25%   |
| Seagate ST1000LM035-1RK172 1TB                       | 1         | 1.25%   |
| SanDisk Ultra 32GB                                   | 1         | 1.25%   |
| Samsung SSD 860 EVO 250GB                            | 1         | 1.25%   |
| Samsung SSD 860 EVO 1TB                              | 1         | 1.25%   |
| Samsung SSD 850 EVO 500GB                            | 1         | 1.25%   |
| Samsung MZ7TE128HMGR-000L1 128GB                     | 1         | 1.25%   |
| Samsung MZ7PC128HAFU-000L1 128GB                     | 1         | 1.25%   |
| Samsung HD501LJ 500GB                                | 1         | 1.25%   |
| Product:              USB DISK 3.0 USB DISK 3.0 64GB | 1         | 1.25%   |
| PLEXTOR PX-128M6S 128GB                              | 1         | 1.25%   |
| OPENBSD SR RAID 1 1TB                                | 1         | 1.25%   |
| NVMe WDS500G3X0C-00SJ 500GB                          | 1         | 1.25%   |
| NVMe WDC WDS100T2B0C- 1TB                            | 1         | 1.25%   |
| NVMe TOSHIBA-RC100 240GB                             | 1         | 1.25%   |
| NVMe Samsung SSD 980 500GB                           | 1         | 1.25%   |
| NVMe SAMSUNG MZVLW1T0 1TB                            | 1         | 1.25%   |
| NVMe SAMSUNG MZVLB256 256GB                          | 1         | 1.25%   |
| NVMe SAMSUNG MZVLB1T0 1TB                            | 1         | 1.25%   |
| NVMe SAMSUNG MZVL21T0 1TB                            | 1         | 1.25%   |
| NVMe SAMSUNG MZ1LB960 960GB                          | 1         | 1.25%   |
| NVMe Sabrent Rocket n 512GB                          | 1         | 1.25%   |
| NVMe PCIe SSD 512GB                                  | 1         | 1.25%   |
| NVMe PC SN530 WD 512GB                               | 1         | 1.25%   |
| NVMe OM3PDP3-AD 256GB                                | 1         | 1.25%   |
| NVMe KXG50ZNV1T02 NVM 1TB                            | 1         | 1.25%   |
| NVMe KIOXIA-EXCERIA S 500GB                          | 1         | 1.25%   |
| NVMe KBG40ZPZ256G TOS 256GB                          | 1         | 1.25%   |
| NVMe INTEL SSDPEKKF51 512GB                          | 1         | 1.25%   |
| NVMe IM2P33F3 AD 256GB                               | 1         | 1.25%   |
| Netac SSD 240GB                                      | 1         | 1.25%   |
| Lexar USB Flash Drive 64GB                           | 1         | 1.25%   |
| Kingston SV300S37A240G 240GB                         | 1         | 1.25%   |
| Kingston SUV500MS480G 480GB                          | 1         | 1.25%   |
| Kingston SUV500MS240G 240GB                          | 1         | 1.25%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                             | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| NVMe                               | 14        | 17     | 30.43%  |
| WDC                                | 10        | 10     | 21.74%  |
| Toshiba                            | 5         | 5      | 10.87%  |
| Seagate                            | 4         | 4      | 8.7%    |
| Samsung Electronics                | 3         | 5      | 6.52%   |
| Hitachi                            | 3         | 3      | 6.52%   |
| StoreJet                           | 1         | 1      | 2.17%   |
| Product:              USB DISK 3.0 | 1         | 1      | 2.17%   |
| OPENBSD                            | 1         | 1      | 2.17%   |
| Lexar                              | 1         | 1      | 2.17%   |
| HGST                               | 1         | 1      | 2.17%   |
| ASMT                               | 1         | 1      | 2.17%   |
| Apple                              | 1         | 1      | 2.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 5      | 16.67%  |
| NVMe                | 5         | 5      | 16.67%  |
| Kingston            | 5         | 7      | 16.67%  |
| WDC                 | 2         | 2      | 6.67%   |
| SK Hynix            | 2         | 2      | 6.67%   |
| Intel               | 2         | 3      | 6.67%   |
| Crucial             | 2         | 2      | 6.67%   |
| Toshiba             | 1         | 1      | 3.33%   |
| SanDisk             | 1         | 1      | 3.33%   |
| PLEXTOR             | 1         | 1      | 3.33%   |
| Netac               | 1         | 1      | 3.33%   |
| HPE                 | 1         | 2      | 3.33%   |
| Apacer              | 1         | 1      | 3.33%   |
| A-DATA Technology   | 1         | 1      | 3.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 35        | 51     | 54.69%  |
| SSD  | 26        | 34     | 40.63%  |
| NVMe | 3         | 4      | 4.69%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 55        | 85     | 94.83%  |
| NVMe | 3         | 4      | 5.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 44        | 59     | 68.75%  |
| 0.51-1.0   | 14        | 16     | 21.88%  |
| 1.01-2.0   | 5         | 9      | 7.81%   |
| 4.01-10.0  | 1         | 1      | 1.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 17        | 28.81%  |
| 251-500        | 14        | 23.73%  |
| 21-50          | 11        | 18.64%  |
| 51-100         | 9         | 15.25%  |
| 501-1000       | 5         | 8.47%   |
| 1-20           | 2         | 3.39%   |
| More than 3000 | 1         | 1.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 43        | 74.14%  |
| 21-50     | 6         | 10.34%  |
| 101-250   | 5         | 8.62%   |
| 51-100    | 2         | 3.45%   |
| 2001-3000 | 1         | 1.72%   |
| 501-1000  | 1         | 1.72%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD10EADS-00M2B0 1TB         | 1         | 1      | 12.5%   |
| Toshiba MQ04ABF100 1TB          | 1         | 1      | 12.5%   |
| Toshiba MK1629GSGF 160GB        | 1         | 1      | 12.5%   |
| Seagate ST250DM000-1BD141 250GB | 1         | 1      | 12.5%   |
| Kingston SMS200S330G 32GB       | 1         | 2      | 12.5%   |
| Intel SSDSA2M080G2GC 80GB       | 1         | 1      | 12.5%   |
| Hitachi HTS722010K9SA00 100GB   | 1         | 1      | 12.5%   |
| A-DATA Technology SP550 480GB   | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Toshiba           | 2         | 2      | 25%     |
| WDC               | 1         | 1      | 12.5%   |
| Seagate           | 1         | 1      | 12.5%   |
| Kingston          | 1         | 2      | 12.5%   |
| Intel             | 1         | 1      | 12.5%   |
| Hitachi           | 1         | 1      | 12.5%   |
| A-DATA Technology | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 2      | 40%     |
| WDC     | 1         | 1      | 20%     |
| Seagate | 1         | 1      | 20%     |
| Hitachi | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 5      | 62.5%   |
| SSD  | 3         | 4      | 37.5%   |

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
| Works    | 38        | 48     | 55.07%  |
| Detected | 22        | 31     | 31.88%  |
| Malfunc  | 8         | 9      | 11.59%  |
| Failed   | 1         | 1      | 1.45%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 36        | 53.73%  |
| AMD                         | 10        | 14.93%  |
| Sandisk                     | 6         | 8.96%   |
| Samsung Electronics         | 6         | 8.96%   |
| Toshiba                     | 2         | 2.99%   |
| Phison Electronics          | 2         | 2.99%   |
| KIOXIA                      | 2         | 2.99%   |
| Kingston Technology Company | 1         | 1.49%   |
| HighPoint Technologies      | 1         | 1.49%   |
| ADATA Technology            | 1         | 1.49%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                  | Computers | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 7         | 9.72%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                             | 4         | 5.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 3         | 4.17%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 3         | 4.17%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 3         | 4.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 3         | 4.17%   |
| Sandisk unknown                                                                        | 2         | 2.78%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 2         | 2.78%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 2         | 2.78%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 2         | 2.78%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 2         | 2.78%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 2         | 2.78%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 2         | 2.78%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                   | 2         | 2.78%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 2         | 2.78%   |
| AMD 400 Series Chipset SATA Controller                                                 | 2         | 2.78%   |
| Toshiba unknown                                                                        | 1         | 1.39%   |
| Toshiba BG3 NVMe SSD Controller                                                        | 1         | 1.39%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 1.39%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 1         | 1.39%   |
| Samsung NVMe SSD Controller 980                                                        | 1         | 1.39%   |
| Phison PS5013 E13 NVMe Controller                                                      | 1         | 1.39%   |
| Phison E12 NVMe Controller                                                             | 1         | 1.39%   |
| KIOXIA unknown                                                                         | 1         | 1.39%   |
| KIOXIA NVMe SSD                                                                        | 1         | 1.39%   |
| Kingston Company OM3PDP3 NVMe SSD                                                      | 1         | 1.39%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 1         | 1.39%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                        | 1         | 1.39%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 1         | 1.39%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 1.39%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 1         | 1.39%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 1         | 1.39%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                             | 1         | 1.39%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 1         | 1.39%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                    | 1         | 1.39%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 1         | 1.39%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                           | 1         | 1.39%   |
| Intel 82801CAM IDE U100 Controller                                                     | 1         | 1.39%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.39%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.39%   |
| HighPoint unknown                                                                      | 1         | 1.39%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                               | 1         | 1.39%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                       | 1         | 1.39%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 1         | 1.39%   |
| ADATA Technology unknown                                                               | 1         | 1.39%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 39        | 58.21%  |
| NVMe | 20        | 29.85%  |
| IDE  | 7         | 10.45%  |
| RAID | 1         | 1.49%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 42        | 72.41%  |
| AMD    | 12        | 20.69%  |
| ARM    | 4         | 6.9%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 5.17%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 3.45%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 3.45%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 3.45%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 3.45%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 3.45%   |
| ARM Cortex-A72 r0p3                           | 2         | 3.45%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 2         | 3.45%   |
| Intel Xeon E-2276G CPU @ 3.80GHz              | 1         | 1.72%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz           | 1         | 1.72%   |
| Intel Pentium 4 Mobile CPU 1.60GHz            | 1         | 1.72%   |
| Intel Genuine CPU T2300 @ 1.66GHz             | 1         | 1.72%   |
| Intel Core i9-9880H CPU @ 2.30GHz             | 1         | 1.72%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 1.72%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 1.72%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 1.72%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.72%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 1         | 1.72%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 1.72%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 1.72%   |
| Intel Core i5-4570S CPU @ 2.90GHz             | 1         | 1.72%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 1.72%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz            | 1         | 1.72%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 1.72%   |
| Intel Core i5-10200H CPU @ 2.40GHz            | 1         | 1.72%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 1         | 1.72%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz          | 1         | 1.72%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz          | 1         | 1.72%   |
| Intel Core 2 Duo CPU L9600 @ 2.13GHz          | 1         | 1.72%   |
| Intel Core 2 CPU 6400 @ 2.13GHz               | 1         | 1.72%   |
| Intel Celeron CPU N2930 @ 1.83GHz             | 1         | 1.72%   |
| Intel Celeron CPU G1820 @ 2.70GHz             | 1         | 1.72%   |
| Intel Celeron CPU 3865U @ 1.80GHz             | 1         | 1.72%   |
| Intel Atom CPU N280 @ 1.66GHz                 | 1         | 1.72%   |
| Intel 11th Gen Core i9-11900K @ 3.50GHz       | 1         | 1.72%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 1         | 1.72%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 1.72%   |
| ARM Cortex-A8 r3p2                            | 1         | 1.72%   |
| ARM Cortex-A53 r0p4                           | 1         | 1.72%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 1         | 1.72%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 1         | 1.72%   |
| AMD Ryzen 7 2700 Eight-Core Processor         | 1         | 1.72%   |
| AMD Ryzen 3 3100 4-Core Processor             | 1         | 1.72%   |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx | 1         | 1.72%   |
| AMD GX-412TC SOC                              | 1         | 1.72%   |
| AMD G-T48E Processor                          | 1         | 1.72%   |
| AMD E1-2100 APU with Radeon HD Graphics       | 1         | 1.72%   |
| AMD C-50 Processor                            | 1         | 1.72%   |
| AMD A4-9120C RADEON R4, 5 COMPUTE CORES 2C+3G | 1         | 1.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 16        | 27.59%  |
| Other            | 5         | 8.62%   |
| Intel Core i7    | 5         | 8.62%   |
| Intel Celeron    | 5         | 8.62%   |
| AMD Ryzen 7      | 5         | 8.62%   |
| ARM Cortex       | 4         | 6.9%    |
| Intel Core 2 Duo | 3         | 5.17%   |
| Intel Xeon       | 2         | 3.45%   |
| AMD Ryzen 3      | 2         | 3.45%   |
| Intel Pentium 4  | 1         | 1.72%   |
| Intel Genuine    | 1         | 1.72%   |
| Intel Core i9    | 1         | 1.72%   |
| Intel Core i3    | 1         | 1.72%   |
| Intel Core 2     | 1         | 1.72%   |
| Intel Atom       | 1         | 1.72%   |
| AMD GX           | 1         | 1.72%   |
| AMD G            | 1         | 1.72%   |
| AMD E1           | 1         | 1.72%   |
| AMD C-50         | 1         | 1.72%   |
| AMD A4           | 1         | 1.72%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 21        | 36.21%  |
| 4       | 16        | 27.59%  |
| Unknown | 11        | 18.97%  |
| 8       | 5         | 8.62%   |
| 16      | 2         | 3.45%   |
| 6       | 2         | 3.45%   |
| 1       | 1         | 1.72%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 48        | 82.76%  |
| Unknown | 9         | 15.52%  |
| 2       | 1         | 1.72%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 28        | 48.28%  |
| 1       | 18        | 31.03%  |
| Unknown | 12        | 20.69%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 12        | 20.69%  |
| Unknown       | 8         | 13.79%  |
| SandyBridge   | 5         | 8.62%   |
| TigerLake     | 3         | 5.17%   |
| Penryn        | 3         | 5.17%   |
| Zen 2         | 2         | 3.45%   |
| Westmere      | 2         | 3.45%   |
| IvyBridge     | 2         | 3.45%   |
| Haswell       | 2         | 3.45%   |
| Goldmont plus | 2         | 3.45%   |
| Bobcat        | 2         | 3.45%   |
| Zen+          | 1         | 1.72%   |
| Zen 3         | 1         | 1.72%   |
| Zen           | 1         | 1.72%   |
| Skylake       | 1         | 1.72%   |
| Silvermont    | 1         | 1.72%   |
| Puma          | 1         | 1.72%   |
| P6            | 1         | 1.72%   |
| NetBurst      | 1         | 1.72%   |
| Jaguar        | 1         | 1.72%   |
| IceLake       | 1         | 1.72%   |
| Excavator     | 1         | 1.72%   |
| Core          | 1         | 1.72%   |
| CometLake     | 1         | 1.72%   |
| Broadwell     | 1         | 1.72%   |
| Bonnell       | 1         | 1.72%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 37        | 64.91%  |
| AMD               | 14        | 24.56%  |
| Nvidia            | 4         | 7.02%   |
| ASPEED Technology | 2         | 3.51%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 5         | 8.33%   |
| Intel UHD Graphics 620                                                        | 3         | 5%      |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 3         | 5%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 2         | 3.33%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 2         | 3.33%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 2         | 3.33%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 2         | 3.33%   |
| Intel Core Processor Integrated Graphics Controller                           | 2         | 3.33%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 2         | 3.33%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 2         | 3.33%   |
| ASPEED Technology ASPEED Graphics Family                                      | 2         | 3.33%   |
| AMD Wrestler [Radeon HD 6250]                                                 | 2         | 3.33%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT / 6800M]                                  | 2         | 3.33%   |
| Nvidia TU104GLM [Quadro RTX 4000 Mobile / Max-Q]                              | 1         | 1.67%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                       | 1         | 1.67%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 1         | 1.67%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 1         | 1.67%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 1         | 1.67%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                     | 1         | 1.67%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 1.67%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 1.67%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 1.67%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 1         | 1.67%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 1         | 1.67%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                          | 1         | 1.67%   |
| Intel Iris Plus Graphics G4 (Ice Lake)                                        | 1         | 1.67%   |
| Intel HD Graphics 620                                                         | 1         | 1.67%   |
| Intel HD Graphics 5500                                                        | 1         | 1.67%   |
| Intel Comet Lake UHD Graphics                                                 | 1         | 1.67%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 1         | 1.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 1         | 1.67%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                              | 1         | 1.67%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                      | 1         | 1.67%   |
| AMD RV730/M96 [Mobility Radeon HD 4650/5165]                                  | 1         | 1.67%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 1         | 1.67%   |
| AMD Renoir                                                                    | 1         | 1.67%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 1         | 1.67%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                                | 1         | 1.67%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                    | 1         | 1.67%   |
| AMD Kabini [Radeon HD 8210]                                                   | 1         | 1.67%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 1         | 1.67%   |
| AMD Cezanne                                                                   | 1         | 1.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 29        | 50%     |
| 1 x AMD        | 13        | 22.41%  |
| Other          | 5         | 8.62%   |
| 2 x Intel      | 4         | 6.9%    |
| Intel + Nvidia | 3         | 5.17%   |
| 1 x ASPEED     | 2         | 3.45%   |
| 1 x Nvidia     | 1         | 1.72%   |
| Intel + AMD    | 1         | 1.72%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 48        | 81.36%  |
| Unknown | 11        | 18.64%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 58        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| BOE                  | 7         | 19.44%  |
| AU Optronics         | 7         | 19.44%  |
| Samsung Electronics  | 5         | 13.89%  |
| LG Display           | 3         | 8.33%   |
| Chimei Innolux       | 3         | 8.33%   |
| Ancor Communications | 2         | 5.56%   |
| PANDA                | 1         | 2.78%   |
| NEC Computers        | 1         | 2.78%   |
| Iiyama               | 1         | 2.78%   |
| Gigabyte Technology  | 1         | 2.78%   |
| Dell                 | 1         | 2.78%   |
| CSO                  | 1         | 2.78%   |
| Apple                | 1         | 2.78%   |
| AOC                  | 1         | 2.78%   |
| Acer                 | 1         | 2.78%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics S24D390 SAM0B65 1920x1080 520x290mm 23.4-inch     | 1         | 2.78%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x170mm 13.9-inch  | 1         | 2.78%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch  | 1         | 2.78%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 310x170mm 13.9-inch  | 1         | 2.78%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch | 1         | 2.78%   |
| PANDA LCD Monitor NCP0004 1920x1080 290x170mm 13.2-inch               | 1         | 2.78%   |
| NEC Computers EX341R NEC2C7A 3440x1440 800x330mm 34.1-inch            | 1         | 2.78%   |
| LG Display LCD Monitor LGD058B 2560x1440 310x170mm 13.9-inch          | 1         | 2.78%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x170mm 12.2-inch          | 1         | 2.78%   |
| LG Display LCD Monitor LGD046D 1920x1080 310x170mm 13.9-inch          | 1         | 2.78%   |
| Iiyama PL3288UH IVM7610 3840x2160 700x390mm 31.5-inch                 | 1         | 2.78%   |
| Gigabyte Technology M28U GBT2800 3840x2160 630x360mm 28.6-inch        | 1         | 2.78%   |
| Dell U3415W DELA0AA 3440x1440 800x330mm 34.1-inch                     | 1         | 2.78%   |
| CSO LCD Monitor CSO1403 3840x2400 300x190mm 14.0-inch                 | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch       | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch      | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch       | 1         | 2.78%   |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                 | 1         | 2.78%   |
| BOE LCD Monitor BOE092A 1920x1080 340x190mm 15.3-inch                 | 1         | 2.78%   |
| BOE LCD Monitor BOE0910 1920x1080 340x190mm 15.3-inch                 | 1         | 2.78%   |
| BOE LCD Monitor BOE082E 1920x1080 310x170mm 13.9-inch                 | 1         | 2.78%   |
| BOE LCD Monitor BOE07A3 1920x1080 340x190mm 15.3-inch                 | 1         | 2.78%   |
| BOE LCD Monitor BOE06A9 1920x1080 340x190mm 15.3-inch                 | 1         | 2.78%   |
| BOE LCD Monitor BOE05E9 1366x768 250x140mm 11.3-inch                  | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO9314 1280x800 260x160mm 12.0-inch         | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO423D 1920x1080 310x170mm 13.9-inch        | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO4199 1920x1080 340x190mm 15.3-inch        | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 310x170mm 13.9-inch        | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO34EB 3840x2160 340x190mm 15.3-inch        | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO325C 1366x768 260x140mm 11.6-inch         | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch         | 1         | 2.78%   |
| Apple Color LCD APP9CC7 1280x800 290x180mm 13.4-inch                  | 1         | 2.78%   |
| AOC 2350 AOC2350 1920x1080 510x290mm 23.1-inch                        | 1         | 2.78%   |
| Ancor Communications VG248 ACI24A5 1920x1080 530x300mm 24.0-inch      | 1         | 2.78%   |
| Ancor Communications ASUS VW199 ACI19ED 1440x900 410x260mm 19.1-inch  | 1         | 2.78%   |
| Acer VG220Q ACR06D8 1920x1080 480x270mm 21.7-inch                     | 1         | 2.78%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 14        | 40%     |
| 1366x768 (WXGA)  | 6         | 17.14%  |
| 3840x2160 (4K)   | 4         | 11.43%  |
| 3440x1440        | 2         | 5.71%   |
| 1600x900 (HD+)   | 2         | 5.71%   |
| 1280x800 (WXGA)  | 2         | 5.71%   |
| 3840x2400        | 1         | 2.86%   |
| 2736x1824        | 1         | 2.86%   |
| 2560x1440 (QHD)  | 1         | 2.86%   |
| 2256x1504        | 1         | 2.86%   |
| 1440x900 (WXGA+) | 1         | 2.86%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 13     | 12        | 34.29%  |
| 15     | 7         | 20%     |
| 12     | 3         | 8.57%   |
| 11     | 3         | 8.57%   |
| 34     | 2         | 5.71%   |
| 31     | 2         | 5.71%   |
| 28     | 1         | 2.86%   |
| 24     | 1         | 2.86%   |
| 23     | 1         | 2.86%   |
| 21     | 1         | 2.86%   |
| 19     | 1         | 2.86%   |
| 14     | 1         | 2.86%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 16        | 45.71%  |
| 201-300     | 10        | 28.57%  |
| 601-700     | 3         | 8.57%   |
| 701-800     | 2         | 5.71%   |
| 501-600     | 2         | 5.71%   |
| 401-500     | 2         | 5.71%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 26        | 76.47%  |
| 16/10 | 4         | 11.76%  |
| 3/2   | 2         | 5.88%   |
| 21/9  | 2         | 5.88%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 12        | 34.29%  |
| 91-100         | 7         | 20%     |
| 351-500        | 5         | 14.29%  |
| 61-70          | 3         | 8.57%   |
| 51-60          | 3         | 8.57%   |
| 201-250        | 3         | 8.57%   |
| 71-80          | 1         | 2.86%   |
| 151-200        | 1         | 2.86%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 20        | 57.14%  |
| 101-120       | 6         | 17.14%  |
| More than 240 | 3         | 8.57%   |
| 161-240       | 3         | 8.57%   |
| 51-100        | 3         | 8.57%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 39        | 66.1%   |
| 0     | 17        | 28.81%  |
| 2     | 3         | 5.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 40        | 53.33%  |
| Realtek Semiconductor             | 18        | 24%     |
| Qualcomm Atheros                  | 7         | 9.33%   |
| TP-Link                           | 2         | 2.67%   |
| Marvell Technology Group          | 2         | 2.67%   |
| Broadcom                          | 2         | 2.67%   |
| Ralink Technology                 | 1         | 1.33%   |
| Ericsson Business Mobile Networks | 1         | 1.33%   |
| D-Link System                     | 1         | 1.33%   |
| D-Link                            | 1         | 1.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                 | 14        | 14.89%  |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                      | 5         | 5.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                             | 5         | 5.32%   |
| Intel Wireless 7260                                                               | 3         | 3.19%   |
| Intel Wi-Fi 6 AX201                                                               | 3         | 3.19%   |
| Intel Wi-Fi 6 AX200                                                               | 3         | 3.19%   |
| Intel I211 Gigabit Network Connection                                             | 3         | 3.19%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                             | 2         | 2.13%   |
| Intel Wireless-AC 9260                                                            | 2         | 2.13%   |
| Intel Wireless 8265 / 8275                                                        | 2         | 2.13%   |
| Intel I210 Gigabit Network Connection                                             | 2         | 2.13%   |
| Intel Ethernet Connection (4) I219-V                                              | 2         | 2.13%   |
| Intel Centrino Wireless-N 2230                                                    | 2         | 2.13%   |
| Intel Centrino Advanced-N 6200                                                    | 2         | 2.13%   |
| Intel 82577LM Gigabit Network Connection                                          | 2         | 2.13%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                       | 1         | 1.06%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                      | 1         | 1.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                          | 1         | 1.06%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                        | 1         | 1.06%   |
| Realtek RTL8125 2.5GbE Controller                                                 | 1         | 1.06%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                             | 1         | 1.06%   |
| Ralink RT5370 Wireless Adapter                                                    | 1         | 1.06%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                        | 1         | 1.06%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                         | 1         | 1.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                  | 1         | 1.06%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                  | 1         | 1.06%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                    | 1         | 1.06%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                        | 1         | 1.06%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                    | 1         | 1.06%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)           | 1         | 1.06%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                           | 1         | 1.06%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                           | 1         | 1.06%   |
| Intel Wireless 3165                                                               | 1         | 1.06%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                            | 1         | 1.06%   |
| Intel Tiger Lake PCH CNVi WiFi                                                    | 1         | 1.06%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                           | 1         | 1.06%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                     | 1         | 1.06%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                             | 1         | 1.06%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                   | 1         | 1.06%   |
| Intel Gemini Lake PCH CNVi WiFi                                                   | 1         | 1.06%   |
| Intel Ethernet Controller I225-V                                                  | 1         | 1.06%   |
| Intel Ethernet Connection I217-V                                                  | 1         | 1.06%   |
| Intel Ethernet Connection (7) I219-LM                                             | 1         | 1.06%   |
| Intel Ethernet Connection (6) I219-V                                              | 1         | 1.06%   |
| Intel Ethernet Connection (10) I219-V                                             | 1         | 1.06%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                   | 1         | 1.06%   |
| Intel Comet Lake PCH CNVi WiFi                                                    | 1         | 1.06%   |
| Intel 82599 10 Gigabit Network Connection                                         | 1         | 1.06%   |
| Intel 82583V Gigabit Network Connection                                           | 1         | 1.06%   |
| Intel 82567LM Gigabit Network Connection                                          | 1         | 1.06%   |
| Intel 82566MM Gigabit Network Connection                                          | 1         | 1.06%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III       | 1         | 1.06%   |
| D-Link System DWA-131 802.11n Wireless N Nano Adapter(rev.A1) [Realtek RTL8192SU] | 1         | 1.06%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]              | 1         | 1.06%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                                 | 1         | 1.06%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                           | 1         | 1.06%   |
| Broadcom BCM4331 802.11a/b/g/n                                                    | 1         | 1.06%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 32        | 71.11%  |
| Qualcomm Atheros      | 5         | 11.11%  |
| TP-Link               | 2         | 4.44%   |
| Realtek Semiconductor | 2         | 4.44%   |
| Ralink Technology     | 1         | 2.22%   |
| D-Link System         | 1         | 2.22%   |
| D-Link                | 1         | 2.22%   |
| Broadcom              | 1         | 2.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                      | 5         | 11.11%  |
| Intel Wireless 7260                                                               | 3         | 6.67%   |
| Intel Wi-Fi 6 AX201                                                               | 3         | 6.67%   |
| Intel Wi-Fi 6 AX200                                                               | 3         | 6.67%   |
| Intel Wireless-AC 9260                                                            | 2         | 4.44%   |
| Intel Wireless 8265 / 8275                                                        | 2         | 4.44%   |
| Intel Centrino Wireless-N 2230                                                    | 2         | 4.44%   |
| Intel Centrino Advanced-N 6200                                                    | 2         | 4.44%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                       | 1         | 2.22%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                      | 1         | 2.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                          | 1         | 2.22%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                        | 1         | 2.22%   |
| Ralink RT5370 Wireless Adapter                                                    | 1         | 2.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                        | 1         | 2.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                  | 1         | 2.22%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                  | 1         | 2.22%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                    | 1         | 2.22%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)           | 1         | 2.22%   |
| Intel Wireless 3165                                                               | 1         | 2.22%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                            | 1         | 2.22%   |
| Intel Tiger Lake PCH CNVi WiFi                                                    | 1         | 2.22%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                           | 1         | 2.22%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                     | 1         | 2.22%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                             | 1         | 2.22%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                   | 1         | 2.22%   |
| Intel Gemini Lake PCH CNVi WiFi                                                   | 1         | 2.22%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                   | 1         | 2.22%   |
| Intel Comet Lake PCH CNVi WiFi                                                    | 1         | 2.22%   |
| D-Link System DWA-131 802.11n Wireless N Nano Adapter(rev.A1) [Realtek RTL8192SU] | 1         | 2.22%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]              | 1         | 2.22%   |
| Broadcom BCM4331 802.11a/b/g/n                                                    | 1         | 2.22%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 23        | 47.92%  |
| Realtek Semiconductor    | 18        | 37.5%   |
| Qualcomm Atheros         | 3         | 6.25%   |
| Marvell Technology Group | 2         | 4.17%   |
| Broadcom                 | 2         | 4.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 14        | 29.17%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 10.42%  |
| Intel I211 Gigabit Network Connection                             | 3         | 6.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 4.17%   |
| Intel I210 Gigabit Network Connection                             | 2         | 4.17%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 4.17%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 4.17%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 2.08%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 2.08%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 2.08%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 2.08%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 2.08%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 2.08%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 2.08%   |
| Intel Ethernet Controller I225-V                                  | 1         | 2.08%   |
| Intel Ethernet Connection I217-V                                  | 1         | 2.08%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 2.08%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 2.08%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 2.08%   |
| Intel 82599 10 Gigabit Network Connection                         | 1         | 2.08%   |
| Intel 82583V Gigabit Network Connection                           | 1         | 2.08%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.08%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 2.08%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 2.08%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1         | 2.08%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 48        | 53.33%  |
| WiFi     | 41        | 45.56%  |
| Unknown  | 1         | 1.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 31        | 55.36%  |
| Ethernet | 25        | 44.64%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 34        | 58.62%  |
| 1     | 17        | 29.31%  |
| 0     | 4         | 6.9%    |
| 7     | 1         | 1.72%   |
| 6     | 1         | 1.72%   |
| 3     | 1         | 1.72%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 58        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 18        | 64.29%  |
| Broadcom                        | 2         | 7.14%   |
| Alps Electric                   | 2         | 7.14%   |
| Realtek Semiconductor           | 1         | 3.57%   |
| Qualcomm Atheros Communications | 1         | 3.57%   |
| Lite-On Technology              | 1         | 3.57%   |
| Cambridge Silicon Radio         | 1         | 3.57%   |
| ASUSTek Computer                | 1         | 3.57%   |
| Apple                           | 1         | 3.57%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 5         | 17.86%  |
| Intel AX201 Bluetooth                               | 4         | 14.29%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 7.14%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 7.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 7.14%   |
| Intel AX200 Bluetooth                               | 2         | 7.14%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 7.14%   |
| Alps Electric UGTZ4 Bluetooth                       | 2         | 7.14%   |
| Realtek  Bluetooth Adapter                          | 1         | 3.57%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE | 1         | 3.57%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 3.57%   |
| Intel AX210 Bluetooth                               | 1         | 3.57%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.57%   |
| ASUS Broadcom Bluetooth 2.1                         | 1         | 3.57%   |
| Apple Apple Broadcom Built-in Bluetooth             | 1         | 3.57%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 39        | 68.42%  |
| AMD                 | 12        | 21.05%  |
| Nvidia              | 3         | 5.26%   |
| C-Media Electronics | 2         | 3.51%   |
| Blue Microphones    | 1         | 1.75%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 4         | 5.88%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 5.88%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 4.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 4.41%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3         | 4.41%   |
| Nvidia unknown                                                             | 2         | 2.94%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 2.94%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 2.94%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 2.94%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 2.94%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 2.94%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 2.94%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 2.94%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 2.94%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 2.94%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 2.94%   |
| C-Media Electronics FX-AUDIO                                               | 2         | 2.94%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 2.94%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 2.94%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 2.94%   |
| AMD Navi 21 HDMI Audio [Radeon RX 6800/6800 XT / 6900 XT]                  | 2         | 2.94%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 2         | 2.94%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 1.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.47%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 1.47%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1.47%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.47%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 1.47%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 1.47%   |
| Intel 82801CA/CAM AC'97 Audio Controller                                   | 1         | 1.47%   |
| Blue Microphones Yeti Stereo Microphone                                    | 1         | 1.47%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1         | 1.47%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 1.47%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1         | 1.47%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.47%   |
| AMD High Definition Audio Controller                                       | 1         | 1.47%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.47%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1         | 1.47%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1         | 1.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7         | 41.18%  |
| Unknown             | 5         | 29.41%  |
| SK Hynix            | 2         | 11.76%  |
| Transcend           | 1         | 5.88%   |
| Kingston            | 1         | 5.88%   |
| Unknown             | 1         | 5.88%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s            | 2         | 10.53%  |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s  | 2         | 10.53%  |
| Unknown RAM Module 512MB SODIMM SDRAM                  | 1         | 5.26%   |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s            | 1         | 5.26%   |
| Unknown RAM Module 1GB SODIMM DDR2                     | 1         | 5.26%   |
| Transcend RAM TS128MLQ64V6J 1GB DIMM DDR2 667MT/s      | 1         | 5.26%   |
| SK Hynix RAM HYMP112U64CP8-Y5 1GB DIMM DDR2 667MT/s    | 1         | 5.26%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s | 1         | 5.26%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s  | 1         | 5.26%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM 1067MT/s       | 1         | 5.26%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s  | 1         | 5.26%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s  | 1         | 5.26%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s  | 1         | 5.26%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s  | 1         | 5.26%   |
| Samsung RAM M3 78T2953CZ3-CE6 1GB DIMM DDR2 667MT/s    | 1         | 5.26%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s  | 1         | 5.26%   |
| Unknown                                                | 1         | 5.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind  | Computers | Percent |
|-------|-----------|---------|
| DDR3  | 9         | 64.29%  |
| SDRAM | 2         | 14.29%  |
| DDR2  | 2         | 14.29%  |
| DDR4  | 1         | 7.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 13        | 92.86%  |
| DIMM   | 1         | 7.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size | Computers | Percent |
|------|-----------|---------|
| 4096 | 7         | 50%     |
| 2048 | 3         | 21.43%  |
| 1024 | 2         | 14.29%  |
| 8192 | 1         | 7.14%   |
| 512  | 1         | 7.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 3         | 21.43%  |
| Unknown | 3         | 21.43%  |
| 1334    | 2         | 14.29%  |
| 1333    | 2         | 14.29%  |
| 1067    | 2         | 14.29%  |
| 3200    | 1         | 7.14%   |
| 667     | 1         | 7.14%   |

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


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 8         | 28.57%  |
| Acer                          | 6         | 21.43%  |
| Microdia                      | 3         | 10.71%  |
| Realtek Semiconductor         | 2         | 7.14%   |
| IMC Networks                  | 2         | 7.14%   |
| Z-Star Microelectronics       | 1         | 3.57%   |
| Sunplus Innovation Technology | 1         | 3.57%   |
| Silicon Motion                | 1         | 3.57%   |
| Luxvisions Innotech Limited   | 1         | 3.57%   |
| Apple                         | 1         | 3.57%   |
| ALi                           | 1         | 3.57%   |
| Alcor Micro                   | 1         | 3.57%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 3         | 10.71%  |
| Acer Integrated Camera                        | 3         | 10.71%  |
| Microdia Integrated_Webcam_HD                 | 2         | 7.14%   |
| IMC Networks Integrated Camera                | 2         | 7.14%   |
| Z-Star Integrated Camera                      | 1         | 3.57%   |
| Sunplus Integrated_Webcam_FHD                 | 1         | 3.57%   |
| Silicon Motion Web Camera                     | 1         | 3.57%   |
| Realtek USB 2 Webcam                          | 1         | 3.57%   |
| Realtek Integrated Webcam                     | 1         | 3.57%   |
| Microdia Ltd., USB  Live camera               | 1         | 3.57%   |
| Luxvisions Innotech Limited Integrated Camera | 1         | 3.57%   |
| Chicony Sonix ST50220 USB Video Camera        | 1         | 3.57%   |
| Chicony Lenovo Integrated Camera (0.3MP)      | 1         | 3.57%   |
| Chicony Integrated Camera (1280x720@30)       | 1         | 3.57%   |
| Chicony HP Webcam [2 MP]                      | 1         | 3.57%   |
| Chicony 2.0M UVC Webcam / CNF7129             | 1         | 3.57%   |
| Apple FaceTime HD Camera                      | 1         | 3.57%   |
| ALi WebCam                                    | 1         | 3.57%   |
| Alcor Micro USB 2.0 Camera                    | 1         | 3.57%   |
| Acer ThinkPad Integrated Camera               | 1         | 3.57%   |
| Acer SunplusIT Integrated Camera              | 1         | 3.57%   |
| Acer EasyCamera                               | 1         | 3.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Upek                       | 2         | 25%     |
| Synaptics                  | 2         | 25%     |
| STMicroelectronics         | 1         | 12.5%   |
| Shenzhen Goodix Technology | 1         | 12.5%   |
| Samsung Electronics        | 1         | 12.5%   |
| AuthenTec                  | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 25%     |
| Synaptics product 0x00be                               | 1         | 12.5%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 12.5%   |
| STMicroelectronics Fingerprint Reader                  | 1         | 12.5%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 12.5%   |
| Samsung Fingerprint Device                             | 1         | 12.5%   |
| AuthenTec AES2810                                      | 1         | 12.5%   |

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
| 1     | 25        | 40.98%  |
| 0     | 15        | 24.59%  |
| 2     | 12        | 19.67%  |
| 4     | 5         | 8.2%    |
| 5     | 2         | 3.28%   |
| 3     | 2         | 3.28%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 35        | 52.24%  |
| Graphics card            | 13        | 19.4%   |
| Net/wireless             | 7         | 10.45%  |
| Firewire controller      | 6         | 8.96%   |
| Sound                    | 3         | 4.48%   |
| Storage/raid             | 1         | 1.49%   |
| Storage/ata              | 1         | 1.49%   |
| Network                  | 1         | 1.49%   |

