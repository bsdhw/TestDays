BSD in Australia - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for BSD in Australia.

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

Total: 86

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Dell          | Latitude E5520              | [e8415a5758](https://bsd-hardware.info/?probe=e8415a5758) | Jan 05, 2025 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [b659f5f797](https://bsd-hardware.info/?probe=b659f5f797) | Dec 03, 2024 |
| HP            | EliteBook 840 G5            | [1abb405f84](https://bsd-hardware.info/?probe=1abb405f84) | Nov 24, 2024 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | [b16a33c476](https://bsd-hardware.info/?probe=b16a33c476) | Nov 17, 2024 |
| Lenovo        | ThinkPad T490 20N2S0QE00    | [4ea2230818](https://bsd-hardware.info/?probe=4ea2230818) | Oct 15, 2024 |
| Lenovo        | ThinkPad T490 20N2S0QE00    | [b7f189a238](https://bsd-hardware.info/?probe=b7f189a238) | Oct 14, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | [869d37ac5e](https://bsd-hardware.info/?probe=869d37ac5e) | Oct 04, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [9aea4f42bc](https://bsd-hardware.info/?probe=9aea4f42bc) | Sep 18, 2024 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [91106574a4](https://bsd-hardware.info/?probe=91106574a4) | Aug 24, 2024 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [14634a95c5](https://bsd-hardware.info/?probe=14634a95c5) | Jul 29, 2024 |
| ASUSTek       | U50Vg                       | [02c8f9cdf5](https://bsd-hardware.info/?probe=02c8f9cdf5) | Jul 06, 2024 |
| Google        | Ultima                      | [732adeb5e4](https://bsd-hardware.info/?probe=732adeb5e4) | Feb 15, 2024 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [6a78256797](https://bsd-hardware.info/?probe=6a78256797) | Feb 04, 2024 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [2c33e6e9e7](https://bsd-hardware.info/?probe=2c33e6e9e7) | Nov 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [ed79ea60c4](https://bsd-hardware.info/?probe=ed79ea60c4) | Nov 13, 2023 |
| Dell          | XPS 13 9360                 | [c7d016caa9](https://bsd-hardware.info/?probe=c7d016caa9) | Nov 04, 2023 |
| Dell          | G16 7630                    | [deb5f3bd32](https://bsd-hardware.info/?probe=deb5f3bd32) | Oct 21, 2023 |
| Unknown       | Unknown                     | [9c6c7f9d6b](https://bsd-hardware.info/?probe=9c6c7f9d6b) | Oct 10, 2023 |
| Dell          | G16 7630                    | [4e39a5ebdf](https://bsd-hardware.info/?probe=4e39a5ebdf) | Sep 21, 2023 |
| Lenovo        | ThinkPad L390 20NRS00Q00    | [b9885ea126](https://bsd-hardware.info/?probe=b9885ea126) | Sep 17, 2023 |
| Lenovo        | ThinkPad T480s 20L7S24F0... | [bb7eb8b380](https://bsd-hardware.info/?probe=bb7eb8b380) | Sep 15, 2023 |
| HP            | Pavilion dv5                | [b7dad77d0d](https://bsd-hardware.info/?probe=b7dad77d0d) | Sep 14, 2023 |
| ReachingTe... | DreamQuest Pro 2022         | [2e6af170b9](https://bsd-hardware.info/?probe=2e6af170b9) | Sep 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [0ebdda5146](https://bsd-hardware.info/?probe=0ebdda5146) | Aug 31, 2023 |
| Dell          | G5 5590                     | [2e496efada](https://bsd-hardware.info/?probe=2e496efada) | Aug 26, 2023 |
| Dell          | G5 5590                     | [fd4f457391](https://bsd-hardware.info/?probe=fd4f457391) | Aug 26, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [60dac781b2](https://bsd-hardware.info/?probe=60dac781b2) | Jul 24, 2023 |
| Lenovo        | ThinkPad T440s 20ARS1BK0... | [01f4886e09](https://bsd-hardware.info/?probe=01f4886e09) | Jul 21, 2023 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | [4274ca291e](https://bsd-hardware.info/?probe=4274ca291e) | Jul 08, 2023 |
| Dell          | XPS 13 9360                 | [648c09752f](https://bsd-hardware.info/?probe=648c09752f) | Jun 27, 2023 |
| HP            | Compaq 6830s                | [1a06917a0f](https://bsd-hardware.info/?probe=1a06917a0f) | Jun 14, 2023 |
| Timi          | TM1701                      | [1dd768a721](https://bsd-hardware.info/?probe=1dd768a721) | May 25, 2023 |
| Intel Clie... | LAPBC510                    | [68b1300903](https://bsd-hardware.info/?probe=68b1300903) | Apr 22, 2023 |
| Unknown       | Unknown                     | [ee06e14aa2](https://bsd-hardware.info/?probe=ee06e14aa2) | Mar 29, 2023 |
| Acer          | Nitro AN515-55              | [e023282dcd](https://bsd-hardware.info/?probe=e023282dcd) | Mar 13, 2023 |
| ASUSTek       | G74Sx                       | [6b7cf8fcac](https://bsd-hardware.info/?probe=6b7cf8fcac) | Mar 13, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [4d69517a13](https://bsd-hardware.info/?probe=4d69517a13) | Feb 07, 2023 |
| Lenovo        | ThinkPad X131e 33672K5      | [4cc4d44e43](https://bsd-hardware.info/?probe=4cc4d44e43) | Aug 15, 2022 |
| Dell          | G5 5590                     | [86bac52410](https://bsd-hardware.info/?probe=86bac52410) | May 29, 2022 |
| HP            | ZBook 14                    | [a646255b51](https://bsd-hardware.info/?probe=a646255b51) | May 02, 2022 |
| Lenovo        | ThinkPad T470 20HES0ES1F    | [f1f0676663](https://bsd-hardware.info/?probe=f1f0676663) | Apr 28, 2022 |
| HP            | Notebook                    | [eea4cff90b](https://bsd-hardware.info/?probe=eea4cff90b) | Apr 27, 2022 |
| HP            | Notebook                    | [eaff4f0fbf](https://bsd-hardware.info/?probe=eaff4f0fbf) | Apr 19, 2022 |
| HP            | Notebook                    | [6a112cfe6c](https://bsd-hardware.info/?probe=6a112cfe6c) | Apr 11, 2022 |
| HP            | Notebook                    | [a31dd5f48d](https://bsd-hardware.info/?probe=a31dd5f48d) | Apr 11, 2022 |
| Dell          | G5 5590                     | [0871c1269b](https://bsd-hardware.info/?probe=0871c1269b) | Mar 07, 2022 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [51b0a953b5](https://bsd-hardware.info/?probe=51b0a953b5) | Feb 22, 2022 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [85441a65a9](https://bsd-hardware.info/?probe=85441a65a9) | Feb 21, 2022 |
| Dell          | Latitude E7450              | [8a3867f171](https://bsd-hardware.info/?probe=8a3867f171) | Feb 03, 2022 |
| Toshiba       | Satellite L50-A             | [94b87158aa](https://bsd-hardware.info/?probe=94b87158aa) | Jan 21, 2022 |
| Apple         | MacBookPro5,5               | [53b106bbb6](https://bsd-hardware.info/?probe=53b106bbb6) | Jan 16, 2022 |
| HP            | Laptop 15s-du1xxx           | [8ebeac18ca](https://bsd-hardware.info/?probe=8ebeac18ca) | Nov 19, 2021 |
| Lenovo        | ThinkPad Mini10 3507A31     | [ced0819a8e](https://bsd-hardware.info/?probe=ced0819a8e) | Oct 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | [2494d9d2db](https://bsd-hardware.info/?probe=2494d9d2db) | Sep 26, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | [28bbeb8b2e](https://bsd-hardware.info/?probe=28bbeb8b2e) | Sep 26, 2021 |
| Lenovo        | G40-70 20369                | [ef8eafa662](https://bsd-hardware.info/?probe=ef8eafa662) | Sep 18, 2021 |
| Intel         | SandyBridge Platform        | [f0aaf635c3](https://bsd-hardware.info/?probe=f0aaf635c3) | Sep 02, 2021 |
| Toshiba       | PORTEGE Z10t-A              | [cb7cbd17d0](https://bsd-hardware.info/?probe=cb7cbd17d0) | Jun 20, 2021 |
| Apple         | MacBookPro11,3              | [1c9feef8e7](https://bsd-hardware.info/?probe=1c9feef8e7) | May 03, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [821c81e652](https://bsd-hardware.info/?probe=821c81e652) | Apr 09, 2021 |
| ASUSTek       | TP500LNG                    | [6501322932](https://bsd-hardware.info/?probe=6501322932) | Apr 06, 2021 |
| Dell          | G5 5590                     | [18863bc535](https://bsd-hardware.info/?probe=18863bc535) | Apr 05, 2021 |
| HP            | ProBook 430 G3              | [32dfd5e52a](https://bsd-hardware.info/?probe=32dfd5e52a) | Mar 22, 2021 |
| Unknown       | Unknown                     | [70304f9c5d](https://bsd-hardware.info/?probe=70304f9c5d) | Mar 11, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [950cf51db1](https://bsd-hardware.info/?probe=950cf51db1) | Feb 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [a2833c6695](https://bsd-hardware.info/?probe=a2833c6695) | Feb 08, 2021 |
| Lenovo        | ThinkPad E420 1141CTO       | [a201c5f713](https://bsd-hardware.info/?probe=a201c5f713) | Feb 08, 2021 |
| Lenovo        | ThinkPad E420 1141CTO       | [d0a5d1cb86](https://bsd-hardware.info/?probe=d0a5d1cb86) | Feb 08, 2021 |
| Lenovo        | ThinkPad E420 1141CTO       | [a51cf81e58](https://bsd-hardware.info/?probe=a51cf81e58) | Feb 06, 2021 |
| Toshiba       | KIRA                        | [1ee77fde0b](https://bsd-hardware.info/?probe=1ee77fde0b) | Jan 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [de7d8622aa](https://bsd-hardware.info/?probe=de7d8622aa) | Dec 18, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [7f6ebffad8](https://bsd-hardware.info/?probe=7f6ebffad8) | Dec 18, 2020 |
| Lenovo        | ThinkPad T460p 20FXCTO1W... | [ddc907ccf4](https://bsd-hardware.info/?probe=ddc907ccf4) | Dec 17, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [1414d7ae80](https://bsd-hardware.info/?probe=1414d7ae80) | Dec 16, 2020 |
| ASUSTek       | K72F                        | [321cd9d139](https://bsd-hardware.info/?probe=321cd9d139) | Dec 08, 2020 |
| ASUSTek       | K72F                        | [b36ff0b052](https://bsd-hardware.info/?probe=b36ff0b052) | Dec 08, 2020 |
| HP            | Setzer                      | [da7914cdd5](https://bsd-hardware.info/?probe=da7914cdd5) | Nov 22, 2020 |
| Lenovo        | ThinkPad T450 20BVA020AU    | [5d8bce59e8](https://bsd-hardware.info/?probe=5d8bce59e8) | Nov 16, 2020 |
| Lenovo        | ThinkPad X230 2320JXM       | [cdbf62a168](https://bsd-hardware.info/?probe=cdbf62a168) | Oct 29, 2020 |
| Lenovo        | ThinkPad X60s 17033JM       | [67e701adb7](https://bsd-hardware.info/?probe=67e701adb7) | Oct 21, 2020 |
| Acer          | Peppy                       | [d68bd5cbb5](https://bsd-hardware.info/?probe=d68bd5cbb5) | Oct 02, 2020 |
| Acer          | Peppy                       | [26058cddbf](https://bsd-hardware.info/?probe=26058cddbf) | Oct 02, 2020 |
| Apple         | MacBookAir5,1               | [6cced6fcf0](https://bsd-hardware.info/?probe=6cced6fcf0) | Sep 23, 2020 |
| Lenovo        | ThinkPad T460p 20FXCTO1W... | [b62876dd94](https://bsd-hardware.info/?probe=b62876dd94) | Aug 04, 2020 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | [e4d2dcda5b](https://bsd-hardware.info/?probe=e4d2dcda5b) | Jul 31, 2020 |
| Lenovo        | ThinkPad X220 4291C35       | [f22c83f68b](https://bsd-hardware.info/?probe=f22c83f68b) | May 31, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| helloSystem 0.8.1   | 4         | 5.48%   |
| FreeBSD 13.0        | 4         | 5.48%   |
| OpenBSD 6.8         | 3         | 4.11%   |
| helloSystem 0.4.0   | 3         | 4.11%   |
| FreeBSD 14.1        | 3         | 4.11%   |
| FreeBSD 13.2        | 3         | 4.11%   |
| OPNsense 22.1.6     | 2         | 2.74%   |
| OPNsense 21.1.3     | 2         | 2.74%   |
| OpenBSD 7.2         | 2         | 2.74%   |
| helloSystem 0.6.0   | 2         | 2.74%   |
| FreeBSD 14.0-BETA2  | 2         | 2.74%   |
| FreeBSD 14.0        | 2         | 2.74%   |
| FreeBSD 12.2        | 2         | 2.74%   |
| FreeBSD 12.1-p10    | 2         | 2.74%   |
| FreeBSD 12.1        | 2         | 2.74%   |
| OPNsense 24.7.9     | 1         | 1.37%   |
| OPNsense 24.1.9     | 1         | 1.37%   |
| OPNsense 23.7.3     | 1         | 1.37%   |
| OPNsense 23.1.4     | 1         | 1.37%   |
| OPNsense 22.1.1     | 1         | 1.37%   |
| OPNsense 21.7.1     | 1         | 1.37%   |
| OPNsense 21.7       | 1         | 1.37%   |
| OpenBSD 6.7         | 1         | 1.37%   |
| NomadBSD 81e34fc3   | 1         | 1.37%   |
| NomadBSD 20231013   | 1         | 1.37%   |
| NomadBSD 1.4        | 1         | 1.37%   |
| helloSystem 0.9.0   | 1         | 1.37%   |
| helloSystem 0.5.0   | 1         | 1.37%   |
| GhostBSD 24.07.3    | 1         | 1.37%   |
| FuguIta 7.1         | 1         | 1.37%   |
| FreeBSD 14.1-p6     | 1         | 1.37%   |
| FreeBSD 14.1-p5     | 1         | 1.37%   |
| FreeBSD 14.1-p3     | 1         | 1.37%   |
| FreeBSD 14.0-RC2    | 1         | 1.37%   |
| FreeBSD 14.0-p4     | 1         | 1.37%   |
| FreeBSD 14.0-BETA1  | 1         | 1.37%   |
| FreeBSD 14.0-ALPHA3 | 1         | 1.37%   |
| FreeBSD 13.2-STABLE | 1         | 1.37%   |
| FreeBSD 13.2-p4     | 1         | 1.37%   |
| FreeBSD 13.2-p3     | 1         | 1.37%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 33        | 50%     |
| OPNsense    | 11        | 16.67%  |
| helloSystem | 11        | 16.67%  |
| OpenBSD     | 6         | 9.09%   |
| NomadBSD    | 3         | 4.55%   |
| GhostBSD    | 1         | 1.52%   |
| FuguIta     | 1         | 1.52%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 65        | 98.48%  |
| i386  | 1         | 1.52%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Console      | 19        | 27.54%  |
| helloDesktop | 14        | 20.29%  |
| XFCE         | 6         | 8.7%    |
| KDE5         | 5         | 7.25%   |
| GNOME        | 4         | 5.8%    |
| fvwm         | 4         | 5.8%    |
| TWM          | 3         | 4.35%   |
| Openbox      | 3         | 4.35%   |
| i3           | 3         | 4.35%   |
| MATE         | 2         | 2.9%    |
| Fluxbox      | 2         | 2.9%    |
| wlroots      | 1         | 1.45%   |
| sway         | 1         | 1.45%   |
| Budgie       | 1         | 1.45%   |
| AwesomeWM    | 1         | 1.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 44        | 65.67%  |
| Console | 16        | 23.88%  |
| Wayland | 7         | 10.45%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 36        | 53.73%  |
| SLiM    | 12        | 17.91%  |
| SDDM    | 10        | 14.93%  |
| LightDM | 4         | 5.97%   |
| GDM     | 2         | 2.99%   |
| XDM     | 1         | 1.49%   |
| PCDM    | 1         | 1.49%   |
| Ly      | 1         | 1.49%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| Unknown         | 28        | 40.58%  |
| C               | 18        | 26.09%  |
| en_US           | 14        | 20.29%  |
| en_AU           | 7         | 10.14%  |
| en_AU.US-ASCII  | 1         | 1.45%   |
| en_AU.ISO8859-1 | 1         | 1.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 56        | 84.85%  |
| BIOS | 10        | 15.15%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 37        | 56.06%  |
| Ufs    | 18        | 27.27%  |
| Ffs    | 7         | 10.61%  |
| Cd9660 | 4         | 6.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 59        | 89.39%  |
| MBR  | 7         | 10.61%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo               | 29        | 43.94%  |
| Hewlett-Packard      | 8         | 12.12%  |
| Dell                 | 7         | 10.61%  |
| ASUSTek Computer     | 4         | 6.06%   |
| Toshiba              | 3         | 4.55%   |
| Apple                | 3         | 4.55%   |
| Unknown              | 3         | 4.55%   |
| Acer                 | 2         | 3.03%   |
| Timi                 | 1         | 1.52%   |
| Samsung Electronics  | 1         | 1.52%   |
| ReachingTech         | 1         | 1.52%   |
| Intel Client Systems | 1         | 1.52%   |
| Intel                | 1         | 1.52%   |
| Google               | 1         | 1.52%   |
| Framework            | 1         | 1.52%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                                                                     | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                                  | 3         | 4.55%   |
| Dell XPS 13 9360                                                                         | 2         | 3.03%   |
| Dell G5 5590                                                                             | 2         | 3.03%   |
| Toshiba Satellite L50-A                                                                  | 1         | 1.52%   |
| Toshiba PORTEGE Z10t-A                                                                   | 1         | 1.52%   |
| Toshiba KIRA                                                                             | 1         | 1.52%   |
| Timi TM1701                                                                              | 1         | 1.52%   |
| Samsung 350V5C/350V5X/350V4C/350V4X/351V5C/351V5X/351V4C/351V4X/3540VC/3540VX/3440VC/344 | 1         | 1.52%   |
| ReachingTech DreamQuest Pro 2022                                                         | 1         | 1.52%   |
| Lenovo ThinkPad X60s 17033JM                                                             | 1         | 1.52%   |
| Lenovo ThinkPad X230 2320JXM                                                             | 1         | 1.52%   |
| Lenovo ThinkPad X220 4291C35                                                             | 1         | 1.52%   |
| Lenovo ThinkPad X1C 5th W10DG 20K3A03CAU                                                 | 1         | 1.52%   |
| Lenovo ThinkPad X131e 33672K5                                                            | 1         | 1.52%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XXS2XW00                                               | 1         | 1.52%   |
| Lenovo ThinkPad X1 Carbon Gen 10 21CBCTO1WW                                              | 1         | 1.52%   |
| Lenovo ThinkPad X1 Carbon 7th 20R1CTO1WW                                                 | 1         | 1.52%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS02100                                                 | 1         | 1.52%   |
| Lenovo ThinkPad X1 Carbon 4th 20FC0019AU                                                 | 1         | 1.52%   |
| Lenovo ThinkPad X1 Carbon 4th 20FB006FAU                                                 | 1         | 1.52%   |
| Lenovo ThinkPad X1 Carbon 4th 20FB001XAU                                                 | 1         | 1.52%   |
| Lenovo ThinkPad X1 Carbon 3443CTO                                                        | 1         | 1.52%   |
| Lenovo ThinkPad T490 20N2S0QE00                                                          | 1         | 1.52%   |
| Lenovo ThinkPad T480s 20L7S24F00                                                         | 1         | 1.52%   |
| Lenovo ThinkPad T470 W10DG 20JM000BUS                                                    | 1         | 1.52%   |
| Lenovo ThinkPad T470 20HES0ES1F                                                          | 1         | 1.52%   |
| Lenovo ThinkPad T460p 20FXCTO1WW                                                         | 1         | 1.52%   |
| Lenovo ThinkPad T450 20BVA020AU                                                          | 1         | 1.52%   |
| Lenovo ThinkPad T440s 20ARS1BK08                                                         | 1         | 1.52%   |
| Lenovo ThinkPad Mini10 3507A31                                                           | 1         | 1.52%   |
| Lenovo ThinkPad L390 20NRS00Q00                                                          | 1         | 1.52%   |
| Lenovo ThinkPad E595 20NFCTO1WW                                                          | 1         | 1.52%   |
| Lenovo ThinkPad E420 1141CTO                                                             | 1         | 1.52%   |
| Lenovo ThinkPad E16 Gen 1 21JT001HAU                                                     | 1         | 1.52%   |
| Lenovo IdeaPad Gaming 3 15IMH05 81Y4                                                     | 1         | 1.52%   |
| Lenovo IdeaPad 5 15ALC05 82LN                                                            | 1         | 1.52%   |
| Lenovo IdeaPad 320-15AST 80XV                                                            | 1         | 1.52%   |
| Lenovo G40-70 20369                                                                      | 1         | 1.52%   |
| Intel SandyBridge Platform                                                               | 1         | 1.52%   |
| Intel Client Systems LAPBC510                                                            | 1         | 1.52%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Lenovo ThinkPad               | 25        | 37.88%  |
| Lenovo IdeaPad                | 3         | 4.55%   |
| Unknown                       | 3         | 4.55%   |
| Dell XPS                      | 2         | 3.03%   |
| Dell Latitude                 | 2         | 3.03%   |
| Dell G5                       | 2         | 3.03%   |
| Toshiba Satellite             | 1         | 1.52%   |
| Toshiba PORTEGE               | 1         | 1.52%   |
| Toshiba KIRA                  | 1         | 1.52%   |
| Timi TM1701                   | 1         | 1.52%   |
| Samsung 350V5C                | 1         | 1.52%   |
| ReachingTech DreamQuest       | 1         | 1.52%   |
| Lenovo G40-70                 | 1         | 1.52%   |
| Intel SandyBridge             | 1         | 1.52%   |
| Intel Client Systems LAPBC510 | 1         | 1.52%   |
| HP ZBook                      | 1         | 1.52%   |
| HP Setzer                     | 1         | 1.52%   |
| HP ProBook                    | 1         | 1.52%   |
| HP Pavilion                   | 1         | 1.52%   |
| HP Notebook                   | 1         | 1.52%   |
| HP Laptop                     | 1         | 1.52%   |
| HP EliteBook                  | 1         | 1.52%   |
| HP Compaq                     | 1         | 1.52%   |
| Google Ultima                 | 1         | 1.52%   |
| Framework Laptop              | 1         | 1.52%   |
| Dell G16                      | 1         | 1.52%   |
| ASUS U50Vg                    | 1         | 1.52%   |
| ASUS TP500LNG                 | 1         | 1.52%   |
| ASUS K72F                     | 1         | 1.52%   |
| ASUS G74Sx                    | 1         | 1.52%   |
| Apple MacBookPro5             | 1         | 1.52%   |
| Apple MacBookPro11            | 1         | 1.52%   |
| Apple MacBookAir5             | 1         | 1.52%   |
| Acer Peppy                    | 1         | 1.52%   |
| Acer Nitro                    | 1         | 1.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 7         | 10.61%  |
| 2017 | 6         | 9.09%   |
| 2015 | 6         | 9.09%   |
| 2023 | 5         | 7.58%   |
| 2018 | 5         | 7.58%   |
| 2022 | 4         | 6.06%   |
| 2021 | 4         | 6.06%   |
| 2019 | 4         | 6.06%   |
| 2014 | 4         | 6.06%   |
| 2013 | 4         | 6.06%   |
| 2012 | 4         | 6.06%   |
| 2016 | 3         | 4.55%   |
| 2009 | 3         | 4.55%   |
| 2011 | 2         | 3.03%   |
| 2010 | 2         | 3.03%   |
| 2024 | 1         | 1.52%   |
| 2008 | 1         | 1.52%   |
| 2007 | 1         | 1.52%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 66        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 63        | 95.45%  |
| Yes  | 3         | 4.55%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 26        | 39.39%  |
| 16.01-24.0  | 23        | 34.85%  |
| 4.01-8.0    | 9         | 13.64%  |
| 32.01-64.0  | 3         | 4.55%   |
| 1.01-2.0    | 2         | 3.03%   |
| 3.01-4.0    | 1         | 1.52%   |
| 2.01-3.0    | 1         | 1.52%   |
| 64.01-256.0 | 1         | 1.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.51-1.0 | 28        | 41.79%  |
| 0.01-0.5 | 27        | 40.3%   |
| 1.01-2.0 | 6         | 8.96%   |
| 2.01-3.0 | 3         | 4.48%   |
| 4.01-8.0 | 2         | 2.99%   |
| 0        | 1         | 1.49%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 48        | 72.73%  |
| 0      | 13        | 19.7%   |
| 2      | 4         | 6.06%   |
| 3      | 1         | 1.52%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 54        | 81.82%  |
| Yes       | 12        | 18.18%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 80.3%   |
| No        | 13        | 19.7%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 62        | 93.94%  |
| No        | 4         | 6.06%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 49        | 73.13%  |
| No        | 18        | 26.87%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Australia | 66        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City         | Notebooks | Percent |
|--------------|-----------|---------|
| Sydney       | 22        | 32.84%  |
| Melbourne    | 11        | 16.42%  |
| Brisbane     | 10        | 14.93%  |
| Perth        | 6         | 8.96%   |
| Adelaide     | 5         | 7.46%   |
| Canberra     | 4         | 5.97%   |
| Warrnambool  | 1         | 1.49%   |
| South Yarra  | 1         | 1.49%   |
| Ryde         | 1         | 1.49%   |
| Kellyville   | 1         | 1.49%   |
| Gold Coast   | 1         | 1.49%   |
| East Malvern | 1         | 1.49%   |
| Darlinghurst | 1         | 1.49%   |
| Burwood      | 1         | 1.49%   |
| Adelaide CBD | 1         | 1.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 15     | 27.27%  |
| Toshiba             | 6         | 7      | 10.91%  |
| Seagate             | 5         | 6      | 9.09%   |
| Intel               | 5         | 5      | 9.09%   |
| Crucial             | 4         | 5      | 7.27%   |
| WDC                 | 3         | 3      | 5.45%   |
| SK hynix            | 2         | 4      | 3.64%   |
| SanDisk             | 2         | 3      | 3.64%   |
| NVMe                | 2         | 3      | 3.64%   |
| Kingston            | 2         | 2      | 3.64%   |
| Silicon Motion      | 1         | 1      | 1.82%   |
| Lenovo              | 1         | 1      | 1.82%   |
| Jetflash            | 1         | 1      | 1.82%   |
| Hitachi             | 1         | 1      | 1.82%   |
| HGST                | 1         | 1      | 1.82%   |
| Fujitsu             | 1         | 1      | 1.82%   |
| FORESEE             | 1         | 1      | 1.82%   |
| Dogfish             | 1         | 1      | 1.82%   |
| Apple               | 1         | 1      | 1.82%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Toshiba THNSF5256GPUK 256GB          | 2         | 3.57%   |
| Samsung SSD 840 EVO 250GB            | 2         | 3.57%   |
| Crucial CT1000BX500SSD1 1TB          | 2         | 3.57%   |
| WDC WD3200BEVT-00SCST0 320GB         | 1         | 1.79%   |
| WDC WD2500BEVS-22UST0 250GB          | 1         | 1.79%   |
| WDC WD10JPVX-60JC3T0 1TB             | 1         | 1.79%   |
| Toshiba THNSNF256GMCS 256GB          | 1         | 1.79%   |
| Toshiba THNSF5256GCJ7 256GB          | 1         | 1.79%   |
| Toshiba MQ01ABF050 500GB             | 1         | 1.79%   |
| Toshiba MQ01ABD100 1TB               | 1         | 1.79%   |
| SK hynix PC401 NVMe 512GB            | 1         | 1.79%   |
| SK hynix BC501 NVMe 512GB            | 1         | 1.79%   |
| Silicon Motion Aura Pro X2 960GB     | 1         | 1.79%   |
| Seagate ST9750420AS 752GB            | 1         | 1.79%   |
| Seagate ST9500325AS 500GB            | 1         | 1.79%   |
| Seagate ST9250315ASG 250GB           | 1         | 1.79%   |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 1         | 1.79%   |
| Seagate ST1000LM035-1RK172 1TB       | 1         | 1.79%   |
| SanDisk SD8TN8U256G1001 256GB        | 1         | 1.79%   |
| SanDisk SD5SG2128G1052E 128GB        | 1         | 1.79%   |
| Samsung SSD PM871 mSATA 256GB        | 1         | 1.79%   |
| Samsung SSD 980 1TB                  | 1         | 1.79%   |
| Samsung SSD 860 EVO 500GB            | 1         | 1.79%   |
| Samsung PM961 NVMe 256GB             | 1         | 1.79%   |
| Samsung MZVLB512HBJQ-000H1 512GB     | 1         | 1.79%   |
| Samsung MZVLB256HAHQ-000L7 256GB     | 1         | 1.79%   |
| Samsung MZVLB256HAHQ-00000 256GB     | 1         | 1.79%   |
| Samsung MZVL2512HCJQ-00BL7 512GB     | 1         | 1.79%   |
| Samsung MZVL2512HCJQ-00B00 512GB     | 1         | 1.79%   |
| Samsung MZNLN256HCHP-000L7 256GB     | 1         | 1.79%   |
| Samsung MZMTE128HMGR-00000 128GB     | 1         | 1.79%   |
| Samsung MZALQ512HBLU-00BL2 512GB     | 1         | 1.79%   |
| Samsung MZ7PC128HAFU-000L1 128GB     | 1         | 1.79%   |
| NVMe WD_BLACK SN850X 1TB             | 1         | 1.79%   |
| NVMe WD Blue SN570 2T                | 1         | 1.79%   |
| NVMe CT2000P3SSD8 2TB                | 1         | 1.79%   |
| Lenovo LENSE30256GMSP34MEAT3TA 256GB | 1         | 1.79%   |
| Kingston SV300S37A120G 120GB         | 1         | 1.79%   |
| Kingston SNS4151S316G 16GB           | 1         | 1.79%   |
| Jetflash Transcend 8G                | 1         | 1.79%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 5         | 6      | 31.25%  |
| WDC      | 3         | 3      | 18.75%  |
| Toshiba  | 2         | 2      | 12.5%   |
| NVMe     | 2         | 2      | 12.5%   |
| Jetflash | 1         | 1      | 6.25%   |
| Hitachi  | 1         | 1      | 6.25%   |
| HGST     | 1         | 1      | 6.25%   |
| Fujitsu  | 1         | 1      | 6.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 7      | 29.17%  |
| Intel               | 4         | 4      | 16.67%  |
| Crucial             | 4         | 5      | 16.67%  |
| SanDisk             | 2         | 3      | 8.33%   |
| Kingston            | 2         | 2      | 8.33%   |
| Toshiba             | 1         | 1      | 4.17%   |
| NVMe                | 1         | 1      | 4.17%   |
| FORESEE             | 1         | 1      | 4.17%   |
| Dogfish             | 1         | 1      | 4.17%   |
| Apple               | 1         | 1      | 4.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 23        | 26     | 41.82%  |
| NVMe | 16        | 19     | 29.09%  |
| HDD  | 16        | 17     | 29.09%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 37        | 43     | 69.81%  |
| NVMe | 16        | 19     | 30.19%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 29        | 32     | 76.32%  |
| 0.51-1.0   | 7         | 8      | 18.42%  |
| 1.01-2.0   | 2         | 3      | 5.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 23        | 34.85%  |
| 251-500    | 18        | 27.27%  |
| 1-20       | 14        | 21.21%  |
| 501-1000   | 5         | 7.58%   |
| 51-100     | 5         | 7.58%   |
| 21-50      | 1         | 1.52%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 57        | 83.82%  |
| 21-50   | 5         | 7.35%   |
| 51-100  | 3         | 4.41%   |
| 101-250 | 2         | 2.94%   |
| 251-500 | 1         | 1.47%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST2000LM003 HN-M201RAD 2TB | 1         | 1      | 16.67%  |
| Kingston SNS4151S316G 16GB         | 1         | 1      | 16.67%  |
| Intel SSDSC2BF180A4L 180GB         | 1         | 1      | 16.67%  |
| Hitachi HTS542525K9A300 250GB      | 1         | 1      | 16.67%  |
| HGST HTS725050A7E630 500GB         | 1         | 1      | 16.67%  |
| Apple SSD SM256E 256GB             | 1         | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 1         | 1      | 16.67%  |
| Kingston | 1         | 1      | 16.67%  |
| Intel    | 1         | 1      | 16.67%  |
| Hitachi  | 1         | 1      | 16.67%  |
| HGST     | 1         | 1      | 16.67%  |
| Apple    | 1         | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 33.33%  |
| Hitachi | 1         | 1      | 33.33%  |
| HGST    | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 3         | 3      | 50%     |
| HDD  | 3         | 3      | 50%     |

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
| Works    | 46        | 53     | 85.19%  |
| Malfunc  | 6         | 6      | 11.11%  |
| Detected | 2         | 3      | 3.7%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 39        | 54.17%  |
| Samsung Electronics       | 10        | 13.89%  |
| SanDisk                   | 7         | 9.72%   |
| Toshiba                   | 4         | 5.56%   |
| AMD                       | 4         | 5.56%   |
| SK hynix                  | 2         | 2.78%   |
| Micron Technology         | 2         | 2.78%   |
| Silicon Motion            | 1         | 1.39%   |
| Nvidia                    | 1         | 1.39%   |
| Micron/Crucial Technology | 1         | 1.39%   |
| Lenovo                    | 1         | 1.39%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 9.59%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 6         | 8.22%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 6.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 6.85%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 4         | 5.48%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 4.11%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 4.11%   |
| Toshiba XG4 NVMe SSD Controller                                                | 2         | 2.74%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 2         | 2.74%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 2.74%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 2         | 2.74%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 2         | 2.74%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 2.74%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 2.74%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 2.74%   |
| Toshiba XG5 NVMe SSD Controller                                                | 1         | 1.37%   |
| Toshiba XG3 NVMe SSD Controller                                                | 1         | 1.37%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 1         | 1.37%   |
| SK hynix BC511 NVMe SSD                                                        | 1         | 1.37%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 1.37%   |
| Sandisk WD PC SN540 / Green SN350 NVMe SSD 1 TB (DRAM-less)                    | 1         | 1.37%   |
| Sandisk WD Blue SN570 NVMe SSD 2TB                                             | 1         | 1.37%   |
| Sandisk WD Black SN850X NVMe SSD                                               | 1         | 1.37%   |
| Sandisk PC SN740 NVMe SSD (DRAM-less)                                          | 1         | 1.37%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 1         | 1.37%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 1.37%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 1.37%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1         | 1.37%   |
| Lenovo LENSE30256GMSP34MEAT3TA                                                 | 1         | 1.37%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 1         | 1.37%   |
| Intel SSD 660P Series                                                          | 1         | 1.37%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 1.37%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 1         | 1.37%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.37%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 1         | 1.37%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1         | 1.37%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.37%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1         | 1.37%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.37%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 40        | 55.56%  |
| NVMe | 28        | 38.89%  |
| RAID | 3         | 4.17%   |
| IDE  | 1         | 1.39%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 60        | 90.91%  |
| AMD    | 6         | 9.09%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz                             | 3         | 4.55%   |
| Intel Core i7-9750H CPU @ 2.60GHz                             | 2         | 3.03%   |
| Intel Core i7-8550U CPU @ 1.80GHz                             | 2         | 3.03%   |
| Intel Core i7-4510U CPU @ 2.00GHz                             | 2         | 3.03%   |
| Intel Core i7-3667U CPU @ 2.00GHz                             | 2         | 3.03%   |
| Intel Core i7-10750H CPU @ 2.60GHz                            | 2         | 3.03%   |
| Intel Core i7-10510U CPU @ 1.80GHz                            | 2         | 3.03%   |
| Intel Core i5-7200U CPU @ 2.50GHz                             | 2         | 3.03%   |
| Intel Core i5-6300U CPU @ 2.40GHz                             | 2         | 3.03%   |
| Intel Core i5-5300U CPU @ 2.30GHz                             | 2         | 3.03%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz                          | 2         | 3.03%   |
| AMD Ryzen 5 5500U with Radeon Graphics                        | 2         | 3.03%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GH                            | 1         | 1.52%   |
| Intel CPU Version                                             | 1         | 1.52%   |
| Intel Core i7-8565U CPU @ 1.80GHz                             | 1         | 1.52%   |
| Intel Core i7-7500U CPU @ 2.70GHz                             | 1         | 1.52%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz                            | 1         | 1.52%   |
| Intel Core i7-6600U CPU @ 2.60GHz                             | 1         | 1.52%   |
| Intel Core i7-6500U CPU @ 2.50GHz                             | 1         | 1.52%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz                            | 1         | 1.52%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz                            | 1         | 1.52%   |
| Intel Core i7-4600U CPU @ 2.10GHz                             | 1         | 1.52%   |
| Intel Core i7-3537U CPU @ 2.00GHz                             | 1         | 1.52%   |
| Intel Core i7-2670QM CPU @ 2.20GHz                            | 1         | 1.52%   |
| Intel Core i5-8265U CPU @ 1.60GHz                             | 1         | 1.52%   |
| Intel Core i5-8250U CPU @ 1.60GHz                             | 1         | 1.52%   |
| Intel Core i5-7300U CPU @ 2.60GHz                             | 1         | 1.52%   |
| Intel Core i5-6200U CPU @ 2.30GHz                             | 1         | 1.52%   |
| Intel Core i5-4300U CPU @ 1.90GHz                             | 1         | 1.52%   |
| Intel Core i5-4210Y CPU @ 1.50GHz                             | 1         | 1.52%   |
| Intel Core i5-3380M CPU @ 2.90GHz                             | 1         | 1.52%   |
| Intel Core i5-3210M CPU @ 2.50GHz                             | 1         | 1.52%   |
| Intel Core i5-2520M CPU @ 2.50GH                              | 1         | 1.52%   |
| Intel Core i5 CPU M 480 @ 2.67GH                              | 1         | 1.52%   |
| Intel Core i3-6100U CPU @ 2.30GHz                             | 1         | 1.52%   |
| Intel Core Duo CPU L2400 @ 1.66GHz ("GenuineIntel" 686-class) | 1         | 1.52%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz                          | 1         | 1.52%   |
| Intel Core 2 Duo CPU T5870 @ 2.00GHz                          | 1         | 1.52%   |
| Intel Celeron N5105 @ 2.00GHz                                 | 1         | 1.52%   |
| Intel Celeron CPU N3150 @ 1.60GHz                             | 1         | 1.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 22        | 33.33%  |
| Intel Core i5    | 19        | 28.79%  |
| Other            | 7         | 10.61%  |
| Intel Celeron    | 6         | 9.09%   |
| Intel Core 2 Duo | 4         | 6.06%   |
| AMD Ryzen 5      | 3         | 4.55%   |
| Intel Xeon       | 1         | 1.52%   |
| Intel Core i3    | 1         | 1.52%   |
| Intel Core Duo   | 1         | 1.52%   |
| AMD Ryzen 7      | 1         | 1.52%   |
| AMD A6           | 1         | 1.52%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 33        | 50%     |
| 4       | 18        | 27.27%  |
| 6       | 4         | 6.06%   |
| Unknown | 4         | 6.06%   |
| 12      | 2         | 3.03%   |
| 8       | 2         | 3.03%   |
| 16      | 1         | 1.52%   |
| 10      | 1         | 1.52%   |
| 1       | 1         | 1.52%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 64        | 96.97%  |
| 2       | 1         | 1.52%   |
| Unknown | 1         | 1.52%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 49        | 74.24%  |
| 1       | 13        | 19.7%   |
| Unknown | 4         | 6.06%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 13        | 19.7%   |
| IvyBridge   | 8         | 12.12%  |
| Haswell     | 8         | 12.12%  |
| Skylake     | 7         | 10.61%  |
| Unknown     | 6         | 9.09%   |
| SandyBridge | 5         | 7.58%   |
| Penryn      | 3         | 4.55%   |
| TigerLake   | 2         | 3.03%   |
| Silvermont  | 2         | 3.03%   |
| CometLake   | 2         | 3.03%   |
| Broadwell   | 2         | 3.03%   |
| Zen+        | 1         | 1.52%   |
| Zen 3       | 1         | 1.52%   |
| Westmere    | 1         | 1.52%   |
| Puma        | 1         | 1.52%   |
| P6          | 1         | 1.52%   |
| Excavator   | 1         | 1.52%   |
| Core        | 1         | 1.52%   |
| Bonnell     | 1         | 1.52%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor         | Notebooks | Percent |
|----------------|-----------|---------|
| Intel          | 53        | 67.09%  |
| Nvidia         | 15        | 18.99%  |
| AMD            | 10        | 12.66%  |
| Silicon Motion | 1         | 1.27%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 8.64%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 7.41%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 6.17%   |
| Intel HD Graphics 620                                                                    | 4         | 4.94%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 4.94%   |
| Intel UHD Graphics 620                                                                   | 3         | 3.7%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 2.47%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 2.47%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 2.47%   |
| Intel HD Graphics 5500                                                                   | 2         | 2.47%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 2.47%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 2.47%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 2.47%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 2.47%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 2         | 2.47%   |
| AMD Lucienne                                                                             | 2         | 2.47%   |
| Silicon Motion SM712 LynxEM+                                                             | 1         | 1.23%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 1.23%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 1.23%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 1.23%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 1.23%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 1.23%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 1.23%   |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                                              | 1         | 1.23%   |
| Nvidia GF116M [GeForce GT 560M]                                                          | 1         | 1.23%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 1.23%   |
| Nvidia G98M [GeForce G 105M]                                                             | 1         | 1.23%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 1.23%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 1.23%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                                          | 1         | 1.23%   |
| Intel Raptor Lake-S UHD Graphics                                                         | 1         | 1.23%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.23%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 1.23%   |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 1.23%   |
| Intel HD Graphics 530                                                                    | 1         | 1.23%   |
| Intel Haswell-ULT Integrated Graphics Controller [HD Graphics]                           | 1         | 1.23%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.23%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 1.23%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.23%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 1         | 1.23%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 38        | 57.58%  |
| Intel + Nvidia     | 10        | 15.15%  |
| 1 x AMD            | 6         | 9.09%   |
| 1 x Nvidia         | 5         | 7.58%   |
| Intel + AMD        | 3         | 4.55%   |
| 2 x Intel          | 2         | 3.03%   |
| 2 x AMD            | 1         | 1.52%   |
| 1 x Silicon Motion | 1         | 1.52%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 61        | 91.04%  |
| Proprietary | 4         | 5.97%   |
| Unknown     | 2         | 2.99%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 60        | 90.91%  |
| 0.01-0.5   | 3         | 4.55%   |
| 1.01-2.0   | 2         | 3.03%   |
| 7.01-8.0   | 1         | 1.52%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 9         | 26.47%  |
| LG Display           | 5         | 14.71%  |
| BOE                  | 5         | 14.71%  |
| Sharp                | 3         | 8.82%   |
| Samsung Electronics  | 2         | 5.88%   |
| Chimei Innolux       | 2         | 5.88%   |
| Panasonic            | 1         | 2.94%   |
| LG Philips           | 1         | 2.94%   |
| Lenovo               | 1         | 2.94%   |
| Dell                 | 1         | 2.94%   |
| CTO                  | 1         | 2.94%   |
| CSO                  | 1         | 2.94%   |
| Ancor Communications | 1         | 2.94%   |
| Unknown              | 1         | 2.94%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP1449 1920x1080 290x170mm 13.2-inch              | 2         | 5.88%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 340x190mm 15.3-inch       | 2         | 5.88%   |
| Sharp LQ133T1JX03 SHP140F 2560x1440 290x170mm 13.2-inch              | 1         | 2.94%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch | 1         | 2.94%   |
| Samsung Electronics LCD Monitor SDC4445 1366x768 340x190mm 15.3-inch | 1         | 2.94%   |
| Panasonic LCD Monitor MEI96A2 3840x2160 380x210mm 17.1-inch          | 1         | 2.94%   |
| LG Philips LP154WX4-TLCB LPL3101 1280x800 330x210mm 15.4-inch        | 1         | 2.94%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch         | 1         | 2.94%   |
| LG Display LCD Monitor LGD04A9 1920x1080 310x170mm 13.9-inch         | 1         | 2.94%   |
| LG Display LCD Monitor LGD049A 2560x1440 310x170mm 13.9-inch         | 1         | 2.94%   |
| LG Display LCD Monitor LGD046D 1920x1080 310x170mm 13.9-inch         | 1         | 2.94%   |
| LG Display LCD Monitor LGD01DD 1600x900 380x210mm 17.1-inch          | 1         | 2.94%   |
| Lenovo LCD Monitor LEN40C1 1280x720 220x130mm 10.1-inch              | 1         | 2.94%   |
| Dell P2314H DEL4098 1920x1080 510x290mm 23.1-inch                    | 1         | 2.94%   |
| CTO LCD Monitor CTO1412 1920x1200 300x190mm 14.0-inch                | 1         | 2.94%   |
| CSO LCD Monitor CSO1630 1920x1200 350x220mm 16.3-inch                | 1         | 2.94%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch      | 1         | 2.94%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch      | 1         | 2.94%   |
| BOE LCD Monitor BOE08E2 1920x1080 340x190mm 15.3-inch                | 1         | 2.94%   |
| BOE LCD Monitor BOE07C9 1920x1080 300x170mm 13.6-inch                | 1         | 2.94%   |
| BOE LCD Monitor BOE0747 1920x1080 350x200mm 15.9-inch                | 1         | 2.94%   |
| BOE LCD Monitor BOE06FF 1920x1080 340x190mm 15.3-inch                | 1         | 2.94%   |
| BOE LCD Monitor BOE05F0 1366x768 310x170mm 13.9-inch                 | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO315D 1920x1080 260x140mm 11.6-inch       | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch        | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 310x170mm 13.9-inch       | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 340x190mm 15.3-inch        | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO235C 1366x768 260x140mm 11.6-inch        | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch        | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO103D 1920x1080 310x170mm 13.9-inch       | 1         | 2.94%   |
| Ancor Communications VG248 ACI24A4 1920x1080 530x300mm 24.0-inch     | 1         | 2.94%   |
| Unknown                                                              | 1         | 2.94%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 15        | 45.45%  |
| 1366x768 (WXGA)   | 9         | 27.27%  |
| 2560x1440 (QHD)   | 2         | 6.06%   |
| 1920x1200 (WUXGA) | 2         | 6.06%   |
| 3840x2160 (4K)    | 1         | 3.03%   |
| 2560x1600         | 1         | 3.03%   |
| 1600x900 (HD+)    | 1         | 3.03%   |
| 1280x800 (WXGA)   | 1         | 3.03%   |
| 1280x720 (HD)     | 1         | 3.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 11        | 32.35%  |
| 15      | 9         | 26.47%  |
| 11      | 4         | 11.76%  |
| 17      | 2         | 5.88%   |
| 12      | 2         | 5.88%   |
| 24      | 1         | 2.94%   |
| 23      | 1         | 2.94%   |
| 16      | 1         | 2.94%   |
| 14      | 1         | 2.94%   |
| 10      | 1         | 2.94%   |
| Unknown | 1         | 2.94%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 17        | 50%     |
| 201-300     | 12        | 35.29%  |
| 501-600     | 2         | 5.88%   |
| 351-400     | 2         | 5.88%   |
| Unknown     | 1         | 2.94%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 29        | 87.88%  |
| 16/10   | 3         | 9.09%   |
| Unknown | 1         | 3.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 8         | 23.53%  |
| 91-100         | 6         | 17.65%  |
| 71-80          | 4         | 11.76%  |
| 51-60          | 4         | 11.76%  |
| 101-110        | 3         | 8.82%   |
| 61-70          | 2         | 5.88%   |
| 201-250        | 2         | 5.88%   |
| 121-130        | 2         | 5.88%   |
| 41-50          | 1         | 2.94%   |
| 111-120        | 1         | 2.94%   |
| Unknown        | 1         | 2.94%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 17        | 50%     |
| 161-240       | 7         | 20.59%  |
| 101-120       | 4         | 11.76%  |
| 51-100        | 4         | 11.76%  |
| More than 240 | 1         | 2.94%   |
| Unknown       | 1         | 2.94%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 38        | 56.72%  |
| 0     | 28        | 41.79%  |
| 2     | 1         | 1.49%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 49        | 48.04%  |
| Realtek Semiconductor             | 23        | 22.55%  |
| Qualcomm Atheros                  | 9         | 8.82%   |
| Broadcom                          | 6         | 5.88%   |
| TP-Link                           | 2         | 1.96%   |
| MediaTek                          | 2         | 1.96%   |
| Lenovo                            | 2         | 1.96%   |
| Ericsson Business Mobile Networks | 2         | 1.96%   |
| Sierra Wireless                   | 1         | 0.98%   |
| Samsung Electronics               | 1         | 0.98%   |
| Nvidia                            | 1         | 0.98%   |
| NetGear                           | 1         | 0.98%   |
| Microsoft                         | 1         | 0.98%   |
| Marvell Technology Group          | 1         | 0.98%   |
| Google                            | 1         | 0.98%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 15        | 11.36%  |
| Intel Wireless 8260                                                    | 8         | 6.06%   |
| Intel Wireless 8265 / 8275                                             | 5         | 3.79%   |
| Intel Wireless 7265                                                    | 5         | 3.79%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 4         | 3.03%   |
| Intel Wireless 7260                                                    | 3         | 2.27%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                | 3         | 2.27%   |
| Intel Ethernet Connection I219-LM                                      | 3         | 2.27%   |
| Intel Ethernet Connection (4) I219-V                                   | 3         | 2.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 2.27%   |
| Intel 82574L Gigabit Network Connection                                | 3         | 2.27%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 2         | 1.52%   |
| Realtek USB 2.5GbE Controller                                          | 2         | 1.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2         | 1.52%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                       | 2         | 1.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 2         | 1.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 2         | 1.52%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 2         | 1.52%   |
| Lenovo USB-C Dock Ethernet                                             | 2         | 1.52%   |
| Intel Wi-Fi 6 AX201                                                    | 2         | 1.52%   |
| Intel Ethernet Connection I219-V                                       | 2         | 1.52%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 1.52%   |
| Intel Ethernet Connection (6) I219-V                                   | 2         | 1.52%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 1.52%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 2         | 1.52%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 2         | 1.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 2         | 1.52%   |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module     | 2         | 1.52%   |
| Broadcom BCM43224 802.11a/b/g/n                                        | 2         | 1.52%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 1         | 0.76%   |
| Sierra Wireless EM7455                                                 | 1         | 0.76%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 0.76%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 1         | 0.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 1         | 0.76%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                | 1         | 0.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1         | 0.76%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 0.76%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 0.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 1         | 0.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 1         | 0.76%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 45        | 67.16%  |
| Qualcomm Atheros      | 8         | 11.94%  |
| Broadcom              | 5         | 7.46%   |
| Realtek Semiconductor | 3         | 4.48%   |
| TP-Link               | 2         | 2.99%   |
| MediaTek              | 2         | 2.99%   |
| Sierra Wireless       | 1         | 1.49%   |
| NetGear               | 1         | 1.49%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                            | 8         | 11.59%  |
| Intel Wireless 8265 / 8275                                     | 5         | 7.25%   |
| Intel Wireless 7265                                            | 5         | 7.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 5.8%    |
| Intel Wireless 7260                                            | 3         | 4.35%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 3         | 4.35%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 2         | 2.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 2.9%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 2.9%    |
| Intel Wi-Fi 6 AX201                                            | 2         | 2.9%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 2.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 2.9%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 2.9%    |
| Broadcom BCM43224 802.11a/b/g/n                                | 2         | 2.9%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 1.45%   |
| Sierra Wireless EM7455                                         | 1         | 1.45%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 1.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.45%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1         | 1.45%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 1.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 1.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 1.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 1.45%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 1.45%   |
| NetGear WNA1000M 802.11bgn [Realtek RTL8188CUS]                | 1         | 1.45%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 1         | 1.45%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 1.45%   |
| Intel Wireless 3165                                            | 1         | 1.45%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 1         | 1.45%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 1         | 1.45%   |
| Intel Raptor Lake-S PCH CNVi WiFi                              | 1         | 1.45%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 1.45%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 1.45%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 1         | 1.45%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 1.45%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 1         | 1.45%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 1         | 1.45%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 1         | 1.45%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 1         | 1.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 24        | 42.11%  |
| Realtek Semiconductor    | 22        | 38.6%   |
| Qualcomm Atheros         | 3         | 5.26%   |
| Lenovo                   | 2         | 3.51%   |
| Broadcom                 | 2         | 3.51%   |
| Samsung Electronics      | 1         | 1.75%   |
| Nvidia                   | 1         | 1.75%   |
| Microsoft                | 1         | 1.75%   |
| Marvell Technology Group | 1         | 1.75%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 15        | 25%     |
| Intel Ethernet Connection I219-LM                                      | 3         | 5%      |
| Intel Ethernet Connection (4) I219-V                                   | 3         | 5%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 5%      |
| Intel 82574L Gigabit Network Connection                                | 3         | 5%      |
| Realtek USB 2.5GbE Controller                                          | 2         | 3.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2         | 3.33%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                       | 2         | 3.33%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 2         | 3.33%   |
| Lenovo USB-C Dock Ethernet                                             | 2         | 3.33%   |
| Intel Ethernet Connection I219-V                                       | 2         | 3.33%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 3.33%   |
| Intel Ethernet Connection (6) I219-V                                   | 2         | 3.33%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 3.33%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 1.67%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 1.67%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 1.67%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 1.67%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 1.67%   |
| Microsoft RTL8153B GigE [Surface Ethernet Adapter]                     | 1         | 1.67%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                | 1         | 1.67%   |
| Intel Ethernet Connection I218-V                                       | 1         | 1.67%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 1.67%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 1.67%   |
| Intel Ethernet Connection (10) I219-V                                  | 1         | 1.67%   |
| Intel Ethernet 10G 2P X520 Adapter                                     | 1         | 1.67%   |
| Intel 82573L Gigabit Ethernet Controller                               | 1         | 1.67%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                      | 1         | 1.67%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 1         | 1.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 62        | 52.54%  |
| Ethernet | 53        | 44.92%  |
| Modem    | 2         | 1.69%   |
| Unknown  | 1         | 0.85%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 38        | 50%     |
| Ethernet | 37        | 48.68%  |
| Modem    | 1         | 1.32%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 45        | 68.18%  |
| 1     | 17        | 25.76%  |
| 3     | 2         | 3.03%   |
| 6     | 1         | 1.52%   |
| 4     | 1         | 1.52%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 60        | 89.55%  |
| Yes  | 7         | 10.45%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 32        | 65.31%  |
| Qualcomm Atheros Communications | 4         | 8.16%   |
| Broadcom                        | 3         | 6.12%   |
| Apple                           | 3         | 6.12%   |
| Realtek Semiconductor           | 2         | 4.08%   |
| Hewlett-Packard                 | 2         | 4.08%   |
| Foxconn / Hon Hai               | 2         | 4.08%   |
| IMC Networks                    | 1         | 2.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                     | 19        | 38.78%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)         | 5         | 10.2%   |
| Intel AX201 Bluetooth                                  | 5         | 10.2%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                 | 2         | 4.08%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]          | 2         | 4.08%   |
| Apple Bluetooth Host Controller                        | 2         | 4.08%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                | 1         | 2.04%   |
| Realtek  Bluetooth 4.2 Adapter                         | 1         | 2.04%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                 | 1         | 2.04%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                  | 1         | 2.04%   |
| Intel Wireless-AC 9260 Bluetooth Adapter               | 1         | 2.04%   |
| Intel AX211 Bluetooth                                  | 1         | 2.04%   |
| Intel AX210 Bluetooth                                  | 1         | 2.04%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011] | 1         | 2.04%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter           | 1         | 2.04%   |
| Foxconn / Hon Hai Bluetooth USB Module                 | 1         | 2.04%   |
| Broadcom Bluetooth 4.0                                 | 1         | 2.04%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]             | 1         | 2.04%   |
| Broadcom BCM2045B (BDC-2.1)                            | 1         | 2.04%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                   | 1         | 2.04%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 57        | 76%     |
| Nvidia                                       | 8         | 10.67%  |
| AMD                                          | 7         | 9.33%   |
| Lenovo                                       | 2         | 2.67%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 1.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 12        | 13.48%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 7         | 7.87%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 6.74%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 5.62%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5         | 5.62%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 4         | 4.49%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 3.37%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 3.37%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 2.25%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                                         | 2         | 2.25%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 2.25%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 2.25%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 2.25%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 2.25%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 2.25%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 2.25%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 2.25%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 2.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 2.25%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 2.25%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 2.25%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 1         | 1.12%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 1.12%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 1.12%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 1.12%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 1.12%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 1.12%   |
| Nvidia AD107 High Definition Audio Controller                                                     | 1         | 1.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.12%   |
| Intel Raptor Lake High Definition Audio Controller                                                | 1         | 1.12%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 1.12%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 1.12%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.12%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 1.12%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 1.12%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 1.12%   |
| AMD High Definition Audio Controller                                                              | 1         | 1.12%   |
| AMD FCH Azalia Controller                                                                         | 1         | 1.12%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 1.12%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 28        | 41.18%  |
| SK hynix            | 13        | 19.12%  |
| Micron Technology   | 9         | 13.24%  |
| Kingston            | 4         | 5.88%   |
| Unknown             | 3         | 4.41%   |
| Crucial             | 3         | 4.41%   |
| Team                | 2         | 2.94%   |
| Unifosa             | 1         | 1.47%   |
| Transcend           | 1         | 1.47%   |
| Silicon Power       | 1         | 1.47%   |
| Corsair             | 1         | 1.47%   |
| ASint Technology    | 1         | 1.47%   |
| Unknown             | 1         | 1.47%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s            | 3         | 4.11%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s             | 2         | 2.74%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 2.74%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 2.74%   |
| Unknown RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 1.37%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 1         | 1.37%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                       | 1         | 1.37%   |
| Unifosa RAM HU6E4403EP0200 4GB SODIMM DDR3 1333MT/s              | 1         | 1.37%   |
| Transcend RAM JM667QSU-2G 2GB SODIMM DDR2 667MT/s                | 1         | 1.37%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 1         | 1.37%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1067MT/s                     | 1         | 1.37%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 1         | 1.37%   |
| SK hynix RAM Module 2GB DDR3 1600MT/s                            | 1         | 1.37%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 1         | 1.37%   |
| SK hynix RAM HMT851S6AMR6A-PB 4GB Chip DDR3 1600MT/s             | 1         | 1.37%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.37%   |
| SK hynix RAM HMCG66AEBSA095N 8GB SODIMM DDR5 4800MT/s            | 1         | 1.37%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.37%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.37%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB SODIMM LPDDR3 1867MT/s           | 1         | 1.37%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB Chip LPDDR3 1867MT/s             | 1         | 1.37%   |
| Silicon Power RAM DBST4GN568S 4GB SODIMM DDR3 1333MT/s           | 1         | 1.37%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 2133MT/s              | 1         | 1.37%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 1.37%   |
| Samsung RAM Module 2GB SODIMM DDR3 1067MT/s                      | 1         | 1.37%   |
| Samsung RAM Module 2GB SODIMM 667MT/s                            | 1         | 1.37%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s            | 1         | 1.37%   |
| Samsung RAM M471B5273DH0-CK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.37%   |
| Samsung RAM M471B5174BM0-YH9 4GB Chip DDR3 1333MT/s              | 1         | 1.37%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.37%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.37%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.37%   |
| Samsung RAM M471B5173BH0-CK0 4GB DDR3 1333MT/s                   | 1         | 1.37%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.37%   |
| Samsung RAM M471B1G73CB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.37%   |
| Samsung RAM M471B1G73BH0-CK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.37%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 1.37%   |
| Samsung RAM M471A2K43BB1-CPB 16384MB Chip DDR4 2133MT/s          | 1         | 1.37%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 1.37%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 23        | 39.66%  |
| DDR4    | 17        | 29.31%  |
| LPDDR3  | 9         | 15.52%  |
| LPDDR4  | 3         | 5.17%   |
| DDR2    | 3         | 5.17%   |
| LPDDR5  | 1         | 1.72%   |
| DDR5    | 1         | 1.72%   |
| Unknown | 1         | 1.72%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 43        | 69.35%  |
| Row Of Chips | 10        | 16.13%  |
| Chip         | 6         | 9.68%   |
| Unknown      | 3         | 4.84%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 24        | 38.1%   |
| 4096  | 20        | 31.75%  |
| 2048  | 10        | 15.87%  |
| 16384 | 7         | 11.11%  |
| 32768 | 2         | 3.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 17        | 26.98%  |
| 2667  | 7         | 11.11%  |
| 1867  | 7         | 11.11%  |
| 1333  | 6         | 9.52%   |
| 3200  | 5         | 7.94%   |
| 2133  | 5         | 7.94%   |
| 2400  | 4         | 6.35%   |
| 800   | 3         | 4.76%   |
| 4267  | 2         | 3.17%   |
| 667   | 2         | 3.17%   |
| 6400  | 1         | 1.59%   |
| 4800  | 1         | 1.59%   |
| 3733  | 1         | 1.59%   |
| 1334  | 1         | 1.59%   |
| 1067  | 1         | 1.59%   |

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
| Chicony Electronics                    | 17        | 37.78%  |
| Bison Electronics                      | 6         | 13.33%  |
| IMC Networks                           | 5         | 11.11%  |
| Microdia                               | 4         | 8.89%   |
| Sunplus Innovation Technology          | 3         | 6.67%   |
| Suyin                                  | 2         | 4.44%   |
| Realtek Semiconductor                  | 2         | 4.44%   |
| Z-Star Microelectronics                | 1         | 2.22%   |
| Syntek                                 | 1         | 2.22%   |
| Quanta                                 | 1         | 2.22%   |
| Luxvisions Innotech Limited            | 1         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.22%   |
| Apple                                  | 1         | 2.22%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                    | 10        | 21.74%  |
| Microdia Integrated_Webcam_HD                                | 3         | 6.52%   |
| Bison Integrated Camera                                      | 3         | 6.52%   |
| IMC Networks Integrated Webcam                               | 2         | 4.35%   |
| IMC Networks EasyCamera                                      | 2         | 4.35%   |
| Chicony Integrated Camera (1280x720@30)                      | 2         | 4.35%   |
| Z-Star WebCam SC-03FFL11739P                                 | 1         | 2.17%   |
| Syntek Integrated Camera                                     | 1         | 2.17%   |
| Suyin Lenovo Integrated Webcam                               | 1         | 2.17%   |
| Suyin HP webcam [dv6-1190en]                                 | 1         | 2.17%   |
| Sunplus Laptop_Integrated_Webcam_FHD                         | 1         | 2.17%   |
| Sunplus Laptop Integrated Webcam HD                          | 1         | 2.17%   |
| Sunplus HD WebCam                                            | 1         | 2.17%   |
| Realtek Integrated_Webcam_HD                                 | 1         | 2.17%   |
| Realtek Integrated Camera                                    | 1         | 2.17%   |
| Quanta HP Universal Camera                                   | 1         | 2.17%   |
| Microdia Integrated Webcam HD                                | 1         | 2.17%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera          | 1         | 2.17%   |
| IMC Networks SunplusIT Integrated Camera                     | 1         | 2.17%   |
| Chicony USB2.0 VGA UVC WebCam                                | 1         | 2.17%   |
| Chicony TOSHIBA Web Camera - HD                              | 1         | 2.17%   |
| Chicony TOSHIBA Web Camera - 3M                              | 1         | 2.17%   |
| Chicony Lenovo Integrated Camera (0.3MP)                     | 1         | 2.17%   |
| Chicony Lenovo Integrated Camera                             | 1         | 2.17%   |
| Chicony EasyCamera                                           | 1         | 2.17%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 1         | 2.17%   |
| Bison SunplusIT Integrated Camera                            | 1         | 2.17%   |
| Bison Lenovo Integrated Webcam                               | 1         | 2.17%   |
| Bison Lenovo EasyCamera                                      | 1         | 2.17%   |
| Apple FaceTime HD Camera (Built-in)                          | 1         | 2.17%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 12        | 66.67%  |
| Synaptics                  | 2         | 11.11%  |
| Elan Microelectronics      | 2         | 11.11%  |
| Upek                       | 1         | 5.56%   |
| Shenzhen Goodix Technology | 1         | 5.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 4         | 22.22%  |
| Validity Sensors Synaptics WBDI                        | 4         | 22.22%  |
| Validity Sensors VFS7552 Touch Fingerprint Sensor      | 2         | 11.11%  |
| Elan Fingerprint Sensor                                | 2         | 11.11%  |
| Validity Sensors VFS101 Fingerprint Reader             | 1         | 5.56%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 5.56%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 5.56%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 5.56%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 5.56%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 5.56%   |

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
| 1     | 24        | 34.78%  |
| 3     | 21        | 30.43%  |
| 2     | 17        | 24.64%  |
| 0     | 4         | 5.8%    |
| 6     | 1         | 1.45%   |
| 5     | 1         | 1.45%   |
| 4     | 1         | 1.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 50        | 40.98%  |
| Bluetooth                | 23        | 18.85%  |
| Fingerprint reader       | 15        | 12.3%   |
| Card reader              | 11        | 9.02%   |
| Net/wireless             | 10        | 8.2%    |
| Net/ethernet             | 3         | 2.46%   |
| Graphics card            | 3         | 2.46%   |
| Firewire controller      | 3         | 2.46%   |
| Sound                    | 2         | 1.64%   |
| Storage                  | 1         | 0.82%   |
| Network                  | 1         | 0.82%   |

