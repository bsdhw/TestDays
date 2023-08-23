FreeBSD 14.0-CURRENT - Tested Hardware & Statistics
---------------------------------------------------

A project to collect tested hardware configurations for FreeBSD 14.0-CURRENT.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/FreeBSD_14.0-CURRENT/Desktop/README.md) and [notebooks](/Dist/FreeBSD_14.0-CURRENT/Notebook/README.md).

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

Total: 248

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Supermicro    | X10DRI-TB                   | Server      | [d4e7a4dde7](https://bsd-hardware.info/?probe=d4e7a4dde7) | Aug 06, 2023 |
| Dell          | Inspiron 14-3467            | Notebook    | [5db7e9b7a1](https://bsd-hardware.info/?probe=5db7e9b7a1) | Aug 05, 2023 |
| ASUSTek       | ROG Strix G513QC_G513QC     | Notebook    | [b90e62e27d](https://bsd-hardware.info/?probe=b90e62e27d) | Aug 04, 2023 |
| AZW           | SER                         | Mini pc     | [287fdf7e70](https://bsd-hardware.info/?probe=287fdf7e70) | Jul 30, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [2619fadb11](https://bsd-hardware.info/?probe=2619fadb11) | Jul 29, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [9f4f71236e](https://bsd-hardware.info/?probe=9f4f71236e) | Jul 21, 2023 |
| ASRock        | Z690 PG Riptide             | Desktop     | [813e46e924](https://bsd-hardware.info/?probe=813e46e924) | Jul 10, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [44b85aad5e](https://bsd-hardware.info/?probe=44b85aad5e) | Jul 07, 2023 |
| ASRock        | Z690 PG Riptide             | Desktop     | [364cf5800b](https://bsd-hardware.info/?probe=364cf5800b) | Jul 06, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [03c29939fc](https://bsd-hardware.info/?probe=03c29939fc) | Jun 28, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [748ae83ba1](https://bsd-hardware.info/?probe=748ae83ba1) | Jun 27, 2023 |
| HP            | EliteBook 850 G5            | Notebook    | [4bae8cd192](https://bsd-hardware.info/?probe=4bae8cd192) | Jun 27, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [e7dfbf94d0](https://bsd-hardware.info/?probe=e7dfbf94d0) | Jun 25, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [53bbc07cc8](https://bsd-hardware.info/?probe=53bbc07cc8) | Jun 17, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [705c750691](https://bsd-hardware.info/?probe=705c750691) | Jun 17, 2023 |
| AZW           | SER                         | Mini pc     | [278b419d40](https://bsd-hardware.info/?probe=278b419d40) | Jun 17, 2023 |
| Dell          | 053CWD A00                  | Desktop     | [7a5418ac7e](https://bsd-hardware.info/?probe=7a5418ac7e) | Jun 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [6b4f214b72](https://bsd-hardware.info/?probe=6b4f214b72) | Jun 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [615e7cbf52](https://bsd-hardware.info/?probe=615e7cbf52) | Jun 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [8357f0f72e](https://bsd-hardware.info/?probe=8357f0f72e) | Jun 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [f41e1f2b83](https://bsd-hardware.info/?probe=f41e1f2b83) | Jun 14, 2023 |
| Lenovo        | IdeaPad Slim 9 14ITL5 82... | Notebook    | [03e1e6d302](https://bsd-hardware.info/?probe=03e1e6d302) | Jun 05, 2023 |
| Dell          | G5 5505                     | Notebook    | [5a3c1f19a0](https://bsd-hardware.info/?probe=5a3c1f19a0) | Jun 03, 2023 |
| Dell          | G5 5505                     | Notebook    | [1b10aecc38](https://bsd-hardware.info/?probe=1b10aecc38) | Jun 02, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [22572f1df6](https://bsd-hardware.info/?probe=22572f1df6) | Jun 01, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | Notebook    | [8cc6299ba9](https://bsd-hardware.info/?probe=8cc6299ba9) | May 31, 2023 |
| Gigabyte      | H170-D3HP-CF                | Desktop     | [d5fdf2ff2c](https://bsd-hardware.info/?probe=d5fdf2ff2c) | May 28, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [65376d6b42](https://bsd-hardware.info/?probe=65376d6b42) | May 27, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [a1a68c0f7d](https://bsd-hardware.info/?probe=a1a68c0f7d) | May 24, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [70d54595c2](https://bsd-hardware.info/?probe=70d54595c2) | May 19, 2023 |
| Valve         | Jupiter                     | Notebook    | [7be0869603](https://bsd-hardware.info/?probe=7be0869603) | May 19, 2023 |
| Valve         | Jupiter                     | Notebook    | [ef56a2bd17](https://bsd-hardware.info/?probe=ef56a2bd17) | May 19, 2023 |
| Dell          | Inspiron 3581               | Notebook    | [25c403ca33](https://bsd-hardware.info/?probe=25c403ca33) | May 15, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [e252dc5ff2](https://bsd-hardware.info/?probe=e252dc5ff2) | May 15, 2023 |
| Dell          | Inspiron 3581               | Notebook    | [8d445a3fb3](https://bsd-hardware.info/?probe=8d445a3fb3) | May 14, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [526906c806](https://bsd-hardware.info/?probe=526906c806) | May 14, 2023 |
| Alienware     | 17 R4                       | Notebook    | [df734c8e64](https://bsd-hardware.info/?probe=df734c8e64) | May 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [990b3eb510](https://bsd-hardware.info/?probe=990b3eb510) | May 12, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [dcea67b6a6](https://bsd-hardware.info/?probe=dcea67b6a6) | May 08, 2023 |
| AZW           | SER                         | Mini pc     | [d3d9ba6f52](https://bsd-hardware.info/?probe=d3d9ba6f52) | Apr 30, 2023 |
| Intel         | NUC11PHBi7 M26151-402       | Mini pc     | [596ddff446](https://bsd-hardware.info/?probe=596ddff446) | Apr 22, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [6e82f69c4c](https://bsd-hardware.info/?probe=6e82f69c4c) | Apr 20, 2023 |
| F-Plus Mob... | FLAPTOP r                   | Notebook    | [3d7bf4205b](https://bsd-hardware.info/?probe=3d7bf4205b) | Apr 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [c801b9e5af](https://bsd-hardware.info/?probe=c801b9e5af) | Apr 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [9b2420726f](https://bsd-hardware.info/?probe=9b2420726f) | Apr 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [414cbf5935](https://bsd-hardware.info/?probe=414cbf5935) | Apr 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [6b79c64c73](https://bsd-hardware.info/?probe=6b79c64c73) | Apr 03, 2023 |
| SolidRun      | CEX7 Platform               | Desktop     | [8e2e4d6686](https://bsd-hardware.info/?probe=8e2e4d6686) | Mar 31, 2023 |
| ASRockRack    | EPYCD8-2T                   | Desktop     | [75f414997a](https://bsd-hardware.info/?probe=75f414997a) | Mar 31, 2023 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [c83b0dda87](https://bsd-hardware.info/?probe=c83b0dda87) | Mar 18, 2023 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [9ac4738956](https://bsd-hardware.info/?probe=9ac4738956) | Mar 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [6d9c564a33](https://bsd-hardware.info/?probe=6d9c564a33) | Mar 17, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | Notebook    | [44a8bf8fbc](https://bsd-hardware.info/?probe=44a8bf8fbc) | Mar 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [278a2a11cd](https://bsd-hardware.info/?probe=278a2a11cd) | Mar 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [ef85735453](https://bsd-hardware.info/?probe=ef85735453) | Mar 09, 2023 |
| Samsung       | 750XEE                      | Notebook    | [47d2204f58](https://bsd-hardware.info/?probe=47d2204f58) | Mar 08, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [f9db95d778](https://bsd-hardware.info/?probe=f9db95d778) | Mar 03, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [1a4897cb53](https://bsd-hardware.info/?probe=1a4897cb53) | Feb 26, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [1e548fa114](https://bsd-hardware.info/?probe=1e548fa114) | Feb 24, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [e55635df08](https://bsd-hardware.info/?probe=e55635df08) | Feb 23, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [1ba2a827d9](https://bsd-hardware.info/?probe=1ba2a827d9) | Feb 18, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [dd083df1a2](https://bsd-hardware.info/?probe=dd083df1a2) | Feb 16, 2023 |
| ASUSTek       | PRIME H410M-K               | Desktop     | [d2edba8775](https://bsd-hardware.info/?probe=d2edba8775) | Feb 11, 2023 |
| F-Plus Mob... | FLAPTOP r                   | Notebook    | [165d435f30](https://bsd-hardware.info/?probe=165d435f30) | Jan 31, 2023 |
| F-Plus Mob... | FLAPTOP r                   | Notebook    | [448f9265f2](https://bsd-hardware.info/?probe=448f9265f2) | Jan 27, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [87e25e2abd](https://bsd-hardware.info/?probe=87e25e2abd) | Jan 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [3afbfc6cea](https://bsd-hardware.info/?probe=3afbfc6cea) | Jan 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [e13627df1a](https://bsd-hardware.info/?probe=e13627df1a) | Jan 20, 2023 |
| Dell          | Precision 5540              | Notebook    | [683769b797](https://bsd-hardware.info/?probe=683769b797) | Jan 19, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [3126dc27f1](https://bsd-hardware.info/?probe=3126dc27f1) | Jan 12, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [17f5e2e3d2](https://bsd-hardware.info/?probe=17f5e2e3d2) | Jan 04, 2023 |
| Timi          | Redmi Book Pro 14 2022      | Notebook    | [ce5e882952](https://bsd-hardware.info/?probe=ce5e882952) | Dec 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [d702dfcde2](https://bsd-hardware.info/?probe=d702dfcde2) | Dec 23, 2022 |
| ASRock        | 4X4-4000 Series             | Desktop     | [009ef73bd1](https://bsd-hardware.info/?probe=009ef73bd1) | Dec 20, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [7cf06451fd](https://bsd-hardware.info/?probe=7cf06451fd) | Dec 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [7c644cc639](https://bsd-hardware.info/?probe=7c644cc639) | Dec 15, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [64c92d49d9](https://bsd-hardware.info/?probe=64c92d49d9) | Dec 12, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [6d10b2a0b4](https://bsd-hardware.info/?probe=6d10b2a0b4) | Dec 11, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [3ad7cec298](https://bsd-hardware.info/?probe=3ad7cec298) | Nov 26, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [436a2d30f6](https://bsd-hardware.info/?probe=436a2d30f6) | Nov 16, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [15657b37e2](https://bsd-hardware.info/?probe=15657b37e2) | Nov 15, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [f4a8c42773](https://bsd-hardware.info/?probe=f4a8c42773) | Nov 15, 2022 |
| Dell          | Latitude E7240              | Notebook    | [ea99621380](https://bsd-hardware.info/?probe=ea99621380) | Nov 12, 2022 |
| Google        | Akemi                       | Notebook    | [2d8e99f0c2](https://bsd-hardware.info/?probe=2d8e99f0c2) | Nov 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [20ff21d751](https://bsd-hardware.info/?probe=20ff21d751) | Oct 18, 2022 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [d89559e5c2](https://bsd-hardware.info/?probe=d89559e5c2) | Oct 03, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [dbda136daa](https://bsd-hardware.info/?probe=dbda136daa) | Sep 24, 2022 |
| System76      | Gazelle                     | Notebook    | [6d5d4f5021](https://bsd-hardware.info/?probe=6d5d4f5021) | Sep 24, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [98dff45d54](https://bsd-hardware.info/?probe=98dff45d54) | Sep 09, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [7c6751649b](https://bsd-hardware.info/?probe=7c6751649b) | Sep 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [4e58d828cc](https://bsd-hardware.info/?probe=4e58d828cc) | Sep 01, 2022 |
| Dell          | 0VG93V A00                  | Desktop     | [8de9fa2319](https://bsd-hardware.info/?probe=8de9fa2319) | Aug 18, 2022 |
| Intel         | S2600WTTR G92187-372        | Server      | [ce1988c8ff](https://bsd-hardware.info/?probe=ce1988c8ff) | Aug 18, 2022 |
| Unknown       | Unknown                     | Desktop     | [3208aefb72](https://bsd-hardware.info/?probe=3208aefb72) | Aug 17, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [978f01c546](https://bsd-hardware.info/?probe=978f01c546) | Jul 16, 2022 |
| Lenovo        | ThinkPad T495 20NJ0010PB    | Notebook    | [078888676a](https://bsd-hardware.info/?probe=078888676a) | Jul 13, 2022 |
| Apple         | MacBookAir5,2               | Notebook    | [894b6f82cf](https://bsd-hardware.info/?probe=894b6f82cf) | Jul 13, 2022 |
| Toshiba       | Satellite L305D             | Notebook    | [ed950787b0](https://bsd-hardware.info/?probe=ed950787b0) | Jul 10, 2022 |
| Intel         | NUC11PHBi7 M26151-402       | Mini pc     | [7c34be7c2e](https://bsd-hardware.info/?probe=7c34be7c2e) | Jul 06, 2022 |
| Dell          | Latitude 5521               | Notebook    | [2c9d24a69e](https://bsd-hardware.info/?probe=2c9d24a69e) | Jun 19, 2022 |
| Dell          | Latitude 5410               | Notebook    | [3334ff3727](https://bsd-hardware.info/?probe=3334ff3727) | Jun 06, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [1067f6ab27](https://bsd-hardware.info/?probe=1067f6ab27) | Jun 03, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [3dc5a6f7d2](https://bsd-hardware.info/?probe=3dc5a6f7d2) | May 24, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [c6944afe69](https://bsd-hardware.info/?probe=c6944afe69) | May 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [f3ab857e43](https://bsd-hardware.info/?probe=f3ab857e43) | May 13, 2022 |
| Intel         | NUC11PHBi7 M26151-402       | Mini pc     | [3a3729e497](https://bsd-hardware.info/?probe=3a3729e497) | May 12, 2022 |
| Intel         | NUC11PHBi7 M26151-402       | Mini pc     | [46b11e5051](https://bsd-hardware.info/?probe=46b11e5051) | May 12, 2022 |
| Lenovo        | ThinkPad T495s 20QKS1812... | Notebook    | [89db84f7ec](https://bsd-hardware.info/?probe=89db84f7ec) | May 10, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [224614e9ab](https://bsd-hardware.info/?probe=224614e9ab) | May 10, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [76eef59920](https://bsd-hardware.info/?probe=76eef59920) | May 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [015bf0fea4](https://bsd-hardware.info/?probe=015bf0fea4) | May 06, 2022 |
| Framework     | Laptop                      | Notebook    | [5d6cb039ea](https://bsd-hardware.info/?probe=5d6cb039ea) | Apr 25, 2022 |
| Dell          | 0FKD45 A03                  | Server      | [dde6af4613](https://bsd-hardware.info/?probe=dde6af4613) | Apr 19, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [ee73e0cddb](https://bsd-hardware.info/?probe=ee73e0cddb) | Apr 07, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [0c73871c49](https://bsd-hardware.info/?probe=0c73871c49) | Apr 04, 2022 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [1868573e9a](https://bsd-hardware.info/?probe=1868573e9a) | Apr 02, 2022 |
| Lenovo        | ThinkPad X260 20F5A28AUK    | Notebook    | [f53c625efd](https://bsd-hardware.info/?probe=f53c625efd) | Mar 30, 2022 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | Notebook    | [859a429ad0](https://bsd-hardware.info/?probe=859a429ad0) | Mar 24, 2022 |
| Dell          | 0DNFFW A00                  | All in one  | [30432daccb](https://bsd-hardware.info/?probe=30432daccb) | Mar 23, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [6858ad2b12](https://bsd-hardware.info/?probe=6858ad2b12) | Mar 22, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [7e1e137c8f](https://bsd-hardware.info/?probe=7e1e137c8f) | Mar 20, 2022 |
| Acer          | Aspire A114-33              | Notebook    | [6e7384f4cc](https://bsd-hardware.info/?probe=6e7384f4cc) | Mar 15, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [e04a1b354c](https://bsd-hardware.info/?probe=e04a1b354c) | Mar 11, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [ac59621182](https://bsd-hardware.info/?probe=ac59621182) | Mar 10, 2022 |
| Framework     | Laptop                      | Notebook    | [1f58e0594f](https://bsd-hardware.info/?probe=1f58e0594f) | Mar 01, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [64ccf1e6a0](https://bsd-hardware.info/?probe=64ccf1e6a0) | Feb 18, 2022 |
| HP            | 83E1                        | Desktop     | [d8e995126f](https://bsd-hardware.info/?probe=d8e995126f) | Feb 10, 2022 |
| Notebook      | NS50_70MU                   | Notebook    | [3b3ff8b95d](https://bsd-hardware.info/?probe=3b3ff8b95d) | Feb 05, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [840c7f2142](https://bsd-hardware.info/?probe=840c7f2142) | Feb 05, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [e660899158](https://bsd-hardware.info/?probe=e660899158) | Feb 03, 2022 |
| Dell          | G3 3500                     | Notebook    | [536a7a1b38](https://bsd-hardware.info/?probe=536a7a1b38) | Jan 31, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [f47789d894](https://bsd-hardware.info/?probe=f47789d894) | Jan 29, 2022 |
| MSI           | GE76 Raider 10UG            | Notebook    | [b48b628936](https://bsd-hardware.info/?probe=b48b628936) | Jan 27, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [61406080a7](https://bsd-hardware.info/?probe=61406080a7) | Jan 18, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [825d20fcf7](https://bsd-hardware.info/?probe=825d20fcf7) | Jan 14, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b953d9d2e6](https://bsd-hardware.info/?probe=b953d9d2e6) | Jan 13, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20T20... | Notebook    | [6836fc60f6](https://bsd-hardware.info/?probe=6836fc60f6) | Jan 09, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [2cc4698cbc](https://bsd-hardware.info/?probe=2cc4698cbc) | Jan 09, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [2481037b2a](https://bsd-hardware.info/?probe=2481037b2a) | Jan 09, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [6c208c85a5](https://bsd-hardware.info/?probe=6c208c85a5) | Jan 06, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [7ea8daae8d](https://bsd-hardware.info/?probe=7ea8daae8d) | Jan 05, 2022 |
| ASUSTek       | TUF GAMING B550-PLUS        | Desktop     | [ea4719600a](https://bsd-hardware.info/?probe=ea4719600a) | Jan 05, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [1bbb37d4c6](https://bsd-hardware.info/?probe=1bbb37d4c6) | Jan 03, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [e67007df20](https://bsd-hardware.info/?probe=e67007df20) | Jan 01, 2022 |
| friendlyel... | nanopi-m4                   | Desktop     | [bb29e50061](https://bsd-hardware.info/?probe=bb29e50061) | Dec 27, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [42b4bcbcc2](https://bsd-hardware.info/?probe=42b4bcbcc2) | Dec 27, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [695d7201d4](https://bsd-hardware.info/?probe=695d7201d4) | Dec 27, 2021 |
| khadas        | edge-v                      | Desktop     | [42c428aac0](https://bsd-hardware.info/?probe=42c428aac0) | Dec 26, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [b872e9b044](https://bsd-hardware.info/?probe=b872e9b044) | Dec 18, 2021 |
| HP            | ProBook 440 G6              | Notebook    | [7a8a66430a](https://bsd-hardware.info/?probe=7a8a66430a) | Dec 13, 2021 |
| HP            | ProBook 440 G6              | Notebook    | [f3c014b120](https://bsd-hardware.info/?probe=f3c014b120) | Dec 12, 2021 |
| Unknown       | Unknown                     | Desktop     | [b726a1b3e3](https://bsd-hardware.info/?probe=b726a1b3e3) | Dec 11, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [9a8d19aa04](https://bsd-hardware.info/?probe=9a8d19aa04) | Dec 11, 2021 |
| Unknown       | Unknown                     | Desktop     | [7633cb9296](https://bsd-hardware.info/?probe=7633cb9296) | Dec 11, 2021 |
| ASUSTek       | 1215B                       | Notebook    | [6dbcac684f](https://bsd-hardware.info/?probe=6dbcac684f) | Dec 04, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [822a2481bb](https://bsd-hardware.info/?probe=822a2481bb) | Nov 17, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [83480615f6](https://bsd-hardware.info/?probe=83480615f6) | Nov 04, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [e54d79065e](https://bsd-hardware.info/?probe=e54d79065e) | Nov 02, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [a71d3392eb](https://bsd-hardware.info/?probe=a71d3392eb) | Nov 02, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0PM0... | Notebook    | [7a61d90a55](https://bsd-hardware.info/?probe=7a61d90a55) | Oct 28, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [70422b437f](https://bsd-hardware.info/?probe=70422b437f) | Oct 27, 2021 |
| Beckhoff A... | CX51x0 G3                   | Desktop     | [6db720018b](https://bsd-hardware.info/?probe=6db720018b) | Oct 25, 2021 |
| Beckhoff A... | CX20x3 G1                   | Desktop     | [a49fbd5ce3](https://bsd-hardware.info/?probe=a49fbd5ce3) | Oct 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [d910c79d75](https://bsd-hardware.info/?probe=d910c79d75) | Oct 24, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [9f66ee1b41](https://bsd-hardware.info/?probe=9f66ee1b41) | Oct 18, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [86613b04d3](https://bsd-hardware.info/?probe=86613b04d3) | Oct 17, 2021 |
| Valve         | Jupiter                     | Notebook    | [e5aca4b7d0](https://bsd-hardware.info/?probe=e5aca4b7d0) | Oct 02, 2021 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [1aa5ced5a0](https://bsd-hardware.info/?probe=1aa5ced5a0) | Sep 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [0b73df29bf](https://bsd-hardware.info/?probe=0b73df29bf) | Sep 15, 2021 |
| Lenovo        | ThinkPad X395 20NL000GPG    | Notebook    | [d7812a2905](https://bsd-hardware.info/?probe=d7812a2905) | Sep 10, 2021 |
| Lenovo        | ThinkPad X395 20NL000GPG    | Notebook    | [cdde22fb04](https://bsd-hardware.info/?probe=cdde22fb04) | Sep 10, 2021 |
| Gigabyte      | X399 DESIGNARE EX-CF        | Desktop     | [a78cc6a11b](https://bsd-hardware.info/?probe=a78cc6a11b) | Sep 04, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [fae9e84f60](https://bsd-hardware.info/?probe=fae9e84f60) | Aug 27, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [76f004bd26](https://bsd-hardware.info/?probe=76f004bd26) | Aug 26, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [71092e78e2](https://bsd-hardware.info/?probe=71092e78e2) | Aug 17, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [6e97c9a59e](https://bsd-hardware.info/?probe=6e97c9a59e) | Aug 14, 2021 |
| Lenovo        | Unknown                     | Notebook    | [e16ce5e864](https://bsd-hardware.info/?probe=e16ce5e864) | Aug 08, 2021 |
| HP            | ZBook 17 G2                 | Notebook    | [f2d911563a](https://bsd-hardware.info/?probe=f2d911563a) | Aug 07, 2021 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [6d5e1a13d0](https://bsd-hardware.info/?probe=6d5e1a13d0) | Aug 07, 2021 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | Notebook    | [bf56b2a81a](https://bsd-hardware.info/?probe=bf56b2a81a) | Aug 05, 2021 |
| HP            | ZBook 17 G2                 | Notebook    | [2faf8af7be](https://bsd-hardware.info/?probe=2faf8af7be) | Jul 30, 2021 |
| HP            | ZBook 17 G2                 | Notebook    | [c7fb9e9dee](https://bsd-hardware.info/?probe=c7fb9e9dee) | Jul 27, 2021 |
| HP            | ZBook 17 G2                 | Notebook    | [50c349b7b5](https://bsd-hardware.info/?probe=50c349b7b5) | Jul 27, 2021 |
| HP            | ZBook 17 G2                 | Notebook    | [6149ab50a8](https://bsd-hardware.info/?probe=6149ab50a8) | Jul 24, 2021 |
| Dell          | G5 5505                     | Notebook    | [9933a09c4f](https://bsd-hardware.info/?probe=9933a09c4f) | Jul 24, 2021 |
| HP            | ZBook 17 G2                 | Notebook    | [1ef99f31dd](https://bsd-hardware.info/?probe=1ef99f31dd) | Jul 23, 2021 |
| Avell High... | A62 LIV                     | Notebook    | [5983302b1d](https://bsd-hardware.info/?probe=5983302b1d) | Jul 21, 2021 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | Notebook    | [b0da42c20d](https://bsd-hardware.info/?probe=b0da42c20d) | Jul 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [9c9d4cc782](https://bsd-hardware.info/?probe=9c9d4cc782) | Jul 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [3d5e512e18](https://bsd-hardware.info/?probe=3d5e512e18) | Jul 18, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [63dc88528c](https://bsd-hardware.info/?probe=63dc88528c) | Jul 17, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [7138e2a9e7](https://bsd-hardware.info/?probe=7138e2a9e7) | Jul 17, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [b73eb50747](https://bsd-hardware.info/?probe=b73eb50747) | Jul 16, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [462fc329a9](https://bsd-hardware.info/?probe=462fc329a9) | Jul 16, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [d2866f01b5](https://bsd-hardware.info/?probe=d2866f01b5) | Jul 16, 2021 |
| Unknown       | Unknown                     | Desktop     | [4a3836de00](https://bsd-hardware.info/?probe=4a3836de00) | Jul 08, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [cc24e867fc](https://bsd-hardware.info/?probe=cc24e867fc) | Jun 19, 2021 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | Notebook    | [3d50ba4d85](https://bsd-hardware.info/?probe=3d50ba4d85) | Jun 13, 2021 |
| Dell          | G5 5505                     | Notebook    | [97319295ee](https://bsd-hardware.info/?probe=97319295ee) | Jun 13, 2021 |
| Dell          | Vostro 5490                 | Notebook    | [cf3508718c](https://bsd-hardware.info/?probe=cf3508718c) | Jun 11, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [4ac6c9b3eb](https://bsd-hardware.info/?probe=4ac6c9b3eb) | Jun 08, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [8fc867cfae](https://bsd-hardware.info/?probe=8fc867cfae) | Jun 06, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [edebe87739](https://bsd-hardware.info/?probe=edebe87739) | Jun 04, 2021 |
| Intel         | S2600WTTR G92187-372        | Server      | [289d61b1b2](https://bsd-hardware.info/?probe=289d61b1b2) | Jun 04, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [52ba4e835f](https://bsd-hardware.info/?probe=52ba4e835f) | Jun 03, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [4e4f164625](https://bsd-hardware.info/?probe=4e4f164625) | May 29, 2021 |
| Unknown       | Unknown                     | Soc         | [d96ade87e5](https://bsd-hardware.info/?probe=d96ade87e5) | May 29, 2021 |
| Lenovo        | ThinkPad X270 20HM004JBR    | Notebook    | [88c27e65d7](https://bsd-hardware.info/?probe=88c27e65d7) | May 23, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [62b9ea2794](https://bsd-hardware.info/?probe=62b9ea2794) | May 14, 2021 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [b3acafeb1a](https://bsd-hardware.info/?probe=b3acafeb1a) | May 09, 2021 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [86cec3b874](https://bsd-hardware.info/?probe=86cec3b874) | May 09, 2021 |
| Dell          | G5 5505                     | Notebook    | [ba74d8eee0](https://bsd-hardware.info/?probe=ba74d8eee0) | May 08, 2021 |
| Dell          | G5 5505                     | Notebook    | [23ae99e489](https://bsd-hardware.info/?probe=23ae99e489) | May 08, 2021 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | Notebook    | [2be8cf963c](https://bsd-hardware.info/?probe=2be8cf963c) | May 02, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [c2d56fc369](https://bsd-hardware.info/?probe=c2d56fc369) | Apr 29, 2021 |
| pine64        | pinebook-pro-rk3399         | Desktop     | [79713a2668](https://bsd-hardware.info/?probe=79713a2668) | Apr 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [4993ad0feb](https://bsd-hardware.info/?probe=4993ad0feb) | Apr 25, 2021 |
| HUAWEI        | HN-WX9X                     | Notebook    | [d776625073](https://bsd-hardware.info/?probe=d776625073) | Apr 11, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [325186171a](https://bsd-hardware.info/?probe=325186171a) | Apr 02, 2021 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [342e914968](https://bsd-hardware.info/?probe=342e914968) | Mar 29, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [ed80dc9019](https://bsd-hardware.info/?probe=ed80dc9019) | Mar 27, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [dd877e6c6c](https://bsd-hardware.info/?probe=dd877e6c6c) | Mar 27, 2021 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [cc3151bc6f](https://bsd-hardware.info/?probe=cc3151bc6f) | Mar 17, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [e3f20f8770](https://bsd-hardware.info/?probe=e3f20f8770) | Mar 17, 2021 |
| Lenovo        | ThinkPad X395 20NL001SMX    | Notebook    | [cd016e96ee](https://bsd-hardware.info/?probe=cd016e96ee) | Mar 17, 2021 |
| MSI           | B450 GAMING PLUS            | Desktop     | [547fd655f0](https://bsd-hardware.info/?probe=547fd655f0) | Mar 13, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [9fed35d792](https://bsd-hardware.info/?probe=9fed35d792) | Mar 10, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [1fcde7c0e1](https://bsd-hardware.info/?probe=1fcde7c0e1) | Mar 09, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [29936dd1c0](https://bsd-hardware.info/?probe=29936dd1c0) | Feb 25, 2021 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | Notebook    | [aacafb6ace](https://bsd-hardware.info/?probe=aacafb6ace) | Feb 24, 2021 |
| Unknown       | Unknown                     | Desktop     | [74b11992d7](https://bsd-hardware.info/?probe=74b11992d7) | Feb 20, 2021 |
| Raspberry ... | rpi                         | Desktop     | [92ee9b3619](https://bsd-hardware.info/?probe=92ee9b3619) | Feb 18, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [a601b10377](https://bsd-hardware.info/?probe=a601b10377) | Feb 16, 2021 |
| A-DATA Tec... | XENIA159GENI72060           | Notebook    | [be88e8f865](https://bsd-hardware.info/?probe=be88e8f865) | Feb 15, 2021 |
| Lenovo        | ThinkPad T495s 20QKS1812... | Notebook    | [0e5e228d18](https://bsd-hardware.info/?probe=0e5e228d18) | Feb 13, 2021 |
| Lenovo        | ThinkPad T495s 20QKS1812... | Notebook    | [2d93a6bebc](https://bsd-hardware.info/?probe=2d93a6bebc) | Feb 13, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [ba7f82b343](https://bsd-hardware.info/?probe=ba7f82b343) | Feb 12, 2021 |
| Matsushita... | CF-T2BW1AXR                 | Notebook    | [f6ec2858a5](https://bsd-hardware.info/?probe=f6ec2858a5) | Feb 10, 2021 |
| pine64        | pinebook-pro-rk3399         | Desktop     | [5a55b22f44](https://bsd-hardware.info/?probe=5a55b22f44) | Feb 09, 2021 |
| Dell          | 0D9JG3 A00                  | Desktop     | [65dd4083c5](https://bsd-hardware.info/?probe=65dd4083c5) | Feb 09, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [72137c63f8](https://bsd-hardware.info/?probe=72137c63f8) | Feb 09, 2021 |
| pine64        | pinebook-pro-rk3399         | Desktop     | [97e72f0066](https://bsd-hardware.info/?probe=97e72f0066) | Feb 06, 2021 |
| Dell          | Latitude E5430 vPro         | Notebook    | [bee421a110](https://bsd-hardware.info/?probe=bee421a110) | Feb 06, 2021 |
| Dell          | Latitude E5430 vPro         | Notebook    | [e8157ac6a3](https://bsd-hardware.info/?probe=e8157ac6a3) | Feb 06, 2021 |
| Lenovo        | ThinkPad T430 2349H2G       | Notebook    | [229db16a93](https://bsd-hardware.info/?probe=229db16a93) | Feb 05, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [46c938b853](https://bsd-hardware.info/?probe=46c938b853) | Feb 01, 2021 |
| Matsushita... | CF-T2BW1AXR                 | Notebook    | [c16cd20c42](https://bsd-hardware.info/?probe=c16cd20c42) | Jan 25, 2021 |
| pine64        | pinebook-pro-rk3399         | Desktop     | [2338de9efc](https://bsd-hardware.info/?probe=2338de9efc) | Jan 24, 2021 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 122       | 81.33%  |
| arm64 | 24        | 16%     |
| arm   | 2         | 1.33%   |
| riscv | 1         | 0.67%   |
| i386  | 1         | 0.67%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 45        | 28.66%  |
| KDE5          | 39        | 24.84%  |
| XFCE          | 19        | 12.1%   |
| MATE          | 9         | 5.73%   |
| i3            | 8         | 5.1%    |
| GNOME         | 8         | 5.1%    |
| TWM           | 7         | 4.46%   |
| Openbox       | 3         | 1.91%   |
| LXQt          | 3         | 1.91%   |
| Cinnamon      | 3         | 1.91%   |
| LXDE          | 2         | 1.27%   |
| Lumina        | 2         | 1.27%   |
| Xfwm4         | 1         | 0.64%   |
| sway          | 1         | 0.64%   |
| spectrwm      | 1         | 0.64%   |
| Picom         | 1         | 0.64%   |
| GNUstep       | 1         | 0.64%   |
| Fluxbox       | 1         | 0.64%   |
| Enlightenment | 1         | 0.64%   |
| ctwm          | 1         | 0.64%   |
| Budgie        | 1         | 0.64%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 104       | 67.53%  |
| Console | 46        | 29.87%  |
| Wayland | 4         | 2.6%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 75        | 48.39%  |
| SDDM    | 36        | 23.23%  |
| SLiM    | 16        | 10.32%  |
| GDM     | 12        | 7.74%   |
| XDM     | 9         | 5.81%   |
| LightDM | 5         | 3.23%   |
| Ly      | 2         | 1.29%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang             | Computers | Percent |
|------------------|-----------|---------|
| C                | 96        | 63.16%  |
| en_US            | 23        | 15.13%  |
| Unknown          | 9         | 5.92%   |
| de_DE            | 5         | 3.29%   |
| uk_UA            | 3         | 1.97%   |
| ru_RU            | 3         | 1.97%   |
| zh_CN            | 2         | 1.32%   |
| pl_PL            | 2         | 1.32%   |
| fr_FR            | 2         | 1.32%   |
| en_GB            | 2         | 1.32%   |
| sv_SE            | 1         | 0.66%   |
| pt_PT            | 1         | 0.66%   |
| it_IT.ISO8859-15 | 1         | 0.66%   |
| en_CA            | 1         | 0.66%   |
| de_CH            | 1         | 0.66%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 135       | 90%     |
| BIOS | 15        | 10%     |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 106       | 70.2%   |
| Ufs  | 44        | 29.14%  |
| Nfs  | 1         | 0.66%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 141       | 94%     |
| MBR  | 9         | 6%      |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 29        | 19.33%  |
| Unknown                        | 21        | 14%     |
| ASUSTek Computer               | 17        | 11.33%  |
| Dell                           | 16        | 10.67%  |
| Hewlett-Packard                | 11        | 7.33%   |
| Gigabyte Technology            | 9         | 6%      |
| ASRock                         | 7         | 4.67%   |
| MSI                            | 6         | 4%      |
| Raspberry Pi Foundation        | 4         | 2.67%   |
| Apple                          | 3         | 2%      |
| Valve                          | 2         | 1.33%   |
| Intel                          | 2         | 1.33%   |
| Framework                      | 2         | 1.33%   |
| F-Plus Mobile                  | 2         | 1.33%   |
| Beckhoff Automation            | 2         | 1.33%   |
| Timi                           | 1         | 0.67%   |
| System76                       | 1         | 0.67%   |
| Supermicro                     | 1         | 0.67%   |
| SolidRun                       | 1         | 0.67%   |
| Samsung Electronics            | 1         | 0.67%   |
| pine64                         | 1         | 0.67%   |
| Notebook                       | 1         | 0.67%   |
| Matsushita Electric Industrial | 1         | 0.67%   |
| khadas                         | 1         | 0.67%   |
| HUAWEI                         | 1         | 0.67%   |
| Google                         | 1         | 0.67%   |
| friendlyelec                   | 1         | 0.67%   |
| AZW                            | 1         | 0.67%   |
| Avell High Performance         | 1         | 0.67%   |
| ASRockRack                     | 1         | 0.67%   |
| Alienware                      | 1         | 0.67%   |
| A-DATA Technology              | 1         | 0.67%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 22        | 14.67%  |
| RPi Raspberry Pi                            | 3         | 2%      |
| HP EliteBook 8570p                          | 3         | 2%      |
| Valve Jupiter                               | 2         | 1.33%   |
| Framework Laptop                            | 2         | 1.33%   |
| F-Plus Mobile FLAPTOP r                     | 2         | 1.33%   |
| ASRock X570 Phantom Gaming 4                | 2         | 1.33%   |
| Timi Redmi Book Pro 14 2022                 | 1         | 0.67%   |
| System76 Gazelle                            | 1         | 0.67%   |
| Supermicro X10DRi                           | 1         | 0.67%   |
| SolidRun CEX7 Platform                      | 1         | 0.67%   |
| Samsung 750XEE                              | 1         | 0.67%   |
| RPi rpi                                     | 1         | 0.67%   |
| pine64 pinebook-pro-rk3399                  | 1         | 0.67%   |
| Notebook NS50_70MU                          | 1         | 0.67%   |
| MSI MS-7C79                                 | 1         | 0.67%   |
| MSI MS-7C75                                 | 1         | 0.67%   |
| MSI MS-7B89                                 | 1         | 0.67%   |
| MSI MS-7B86                                 | 1         | 0.67%   |
| MSI GE76 Raider 10UG                        | 1         | 0.67%   |
| MSI Bravo 15 A4DDR                          | 1         | 0.67%   |
| Matsushita Electric Industrial CF-T2BW1AXR  | 1         | 0.67%   |
| Lenovo XiaoXinPro-13ARE 2020 82DM           | 1         | 0.67%   |
| Lenovo ThinkPad X395 20NL001SMX             | 1         | 0.67%   |
| Lenovo ThinkPad X395 20NL000GPG             | 1         | 0.67%   |
| Lenovo ThinkPad X270 20HM004JBR             | 1         | 0.67%   |
| Lenovo ThinkPad X260 20F5A28AUK             | 1         | 0.67%   |
| Lenovo ThinkPad X13 Gen 1 20T2003PRT        | 1         | 0.67%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TLA055CD | 1         | 0.67%   |
| Lenovo ThinkPad X1 Extreme 20MF000BUS       | 1         | 0.67%   |
| Lenovo ThinkPad X1 Carbon 6th 20KHCTO1WW    | 1         | 0.67%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS1QC00    | 1         | 0.67%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS0BT00    | 1         | 0.67%   |
| Lenovo ThinkPad T495s 20QKS1812F            | 1         | 0.67%   |
| Lenovo ThinkPad T495 20NJ0010PB             | 1         | 0.67%   |
| Lenovo ThinkPad T470p 20J7S0PM00            | 1         | 0.67%   |
| Lenovo ThinkPad T430 2349H2G                | 1         | 0.67%   |
| Lenovo ThinkPad T15p Gen 3 21DA000QUS       | 1         | 0.67%   |
| Lenovo ThinkPad T14s Gen 2i 20WM00B7MX      | 1         | 0.67%   |
| Lenovo ThinkPad T14s Gen 1 20UH0019PB       | 1         | 0.67%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 22        | 14.67%  |
| Lenovo ThinkPad                            | 21        | 14%     |
| ASUS PRIME                                 | 7         | 4.67%   |
| HP EliteBook                               | 5         | 3.33%   |
| HP ProBook                                 | 4         | 2.67%   |
| Dell Latitude                              | 4         | 2.67%   |
| ASUS ROG                                   | 4         | 2.67%   |
| RPi Raspberry                              | 3         | 2%      |
| Lenovo IdeaPad                             | 3         | 2%      |
| Dell OptiPlex                              | 3         | 2%      |
| Dell Inspiron                              | 3         | 2%      |
| Valve Jupiter                              | 2         | 1.33%   |
| Lenovo Legion                              | 2         | 1.33%   |
| Gigabyte X570                              | 2         | 1.33%   |
| Gigabyte B450M                             | 2         | 1.33%   |
| Framework Laptop                           | 2         | 1.33%   |
| F-Plus Mobile FLAPTOP                      | 2         | 1.33%   |
| Dell Vostro                                | 2         | 1.33%   |
| ASRock X570                                | 2         | 1.33%   |
| Timi Redmi                                 | 1         | 0.67%   |
| System76 Gazelle                           | 1         | 0.67%   |
| Supermicro X10DRi                          | 1         | 0.67%   |
| SolidRun CEX7                              | 1         | 0.67%   |
| Samsung 750XEE                             | 1         | 0.67%   |
| RPi rpi                                    | 1         | 0.67%   |
| pine64 pinebook-pro-rk3399                 | 1         | 0.67%   |
| Notebook NS50                              | 1         | 0.67%   |
| MSI MS-7C79                                | 1         | 0.67%   |
| MSI MS-7C75                                | 1         | 0.67%   |
| MSI MS-7B89                                | 1         | 0.67%   |
| MSI MS-7B86                                | 1         | 0.67%   |
| MSI GE76                                   | 1         | 0.67%   |
| MSI Bravo                                  | 1         | 0.67%   |
| Matsushita Electric Industrial CF-T2BW1AXR | 1         | 0.67%   |
| Lenovo XiaoXinPro-13ARE                    | 1         | 0.67%   |
| Lenovo ThinkBook                           | 1         | 0.67%   |
| khadas edge-v                              | 1         | 0.67%   |
| Intel S2600WTTR                            | 1         | 0.67%   |
| Intel NUC11PHi7                            | 1         | 0.67%   |
| HUAWEI HN-WX9X                             | 1         | 0.67%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 33        | 22%     |
| 2020    | 30        | 20%     |
| Unknown | 20        | 13.33%  |
| 2022    | 18        | 12%     |
| 2019    | 16        | 10.67%  |
| 2018    | 9         | 6%      |
| 2023    | 6         | 4%      |
| 2017    | 5         | 3.33%   |
| 2013    | 4         | 2.67%   |
| 2015    | 3         | 2%      |
| 2016    | 2         | 1.33%   |
| 2014    | 1         | 0.67%   |
| 2012    | 1         | 0.67%   |
| 2011    | 1         | 0.67%   |
| 2003    | 1         | 0.67%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 75        | 50%     |
| Desktop        | 61        | 40.67%  |
| System on chip | 7         | 4.67%   |
| Mini pc        | 3         | 2%      |
| Server         | 3         | 2%      |
| All in one     | 1         | 0.67%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 148       | 98.67%  |
| Yes  | 2         | 1.33%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 53        | 34.87%  |
| 8.01-16.0       | 26        | 17.11%  |
| 32.01-64.0      | 25        | 16.45%  |
| 64.01-256.0     | 23        | 15.13%  |
| 4.01-8.0        | 9         | 5.92%   |
| 3.01-4.0        | 8         | 5.26%   |
| 0.51-1.0        | 4         | 2.63%   |
| More than 256.0 | 1         | 0.66%   |
| 24.01-32.0      | 1         | 0.66%   |
| 1.01-2.0        | 1         | 0.66%   |
| 0.01-0.5        | 1         | 0.66%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.51-1.0    | 45        | 29.41%  |
| 1.01-2.0    | 44        | 28.76%  |
| 0.01-0.5    | 31        | 20.26%  |
| 2.01-3.0    | 16        | 10.46%  |
| 3.01-4.0    | 7         | 4.58%   |
| 4.01-8.0    | 2         | 1.31%   |
| 24.01-32.0  | 2         | 1.31%   |
| 0           | 2         | 1.31%   |
| 32.01-64.0  | 1         | 0.65%   |
| 64.01-256.0 | 1         | 0.65%   |
| 16.01-24.0  | 1         | 0.65%   |
| 8.01-16.0   | 1         | 0.65%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 74        | 46.84%  |
| 2      | 35        | 22.15%  |
| 0      | 23        | 14.56%  |
| 3      | 12        | 7.59%   |
| 6      | 5         | 3.16%   |
| 4      | 5         | 3.16%   |
| 5      | 2         | 1.27%   |
| 15     | 1         | 0.63%   |
| 7      | 1         | 0.63%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 132       | 86.84%  |
| Yes       | 20        | 13.16%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 115       | 76.67%  |
| No        | 35        | 23.33%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 98        | 65.33%  |
| No        | 52        | 34.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 77        | 50.66%  |
| No        | 75        | 49.34%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 26        | 17.33%  |
| Russia       | 24        | 16%     |
| Germany      | 15        | 10%     |
| UK           | 14        | 9.33%   |
| Poland       | 9         | 6%      |
| Brazil       | 7         | 4.67%   |
| Ukraine      | 5         | 3.33%   |
| China        | 5         | 3.33%   |
| Canada       | 5         | 3.33%   |
| Japan        | 4         | 2.67%   |
| Austria      | 4         | 2.67%   |
| Portugal     | 3         | 2%      |
| France       | 3         | 2%      |
| Turkey       | 2         | 1.33%   |
| Switzerland  | 2         | 1.33%   |
| Sweden       | 2         | 1.33%   |
| Romania      | 2         | 1.33%   |
| Netherlands  | 2         | 1.33%   |
| Denmark      | 2         | 1.33%   |
| Taiwan       | 1         | 0.67%   |
| Spain        | 1         | 0.67%   |
| Singapore    | 1         | 0.67%   |
| Saudi Arabia | 1         | 0.67%   |
| Peru         | 1         | 0.67%   |
| Jordan       | 1         | 0.67%   |
| Jamaica      | 1         | 0.67%   |
| Italy        | 1         | 0.67%   |
| India        | 1         | 0.67%   |
| Czechia      | 1         | 0.67%   |
| Croatia      | 1         | 0.67%   |
| Colombia     | 1         | 0.67%   |
| Belarus      | 1         | 0.67%   |
| Bangladesh   | 1         | 0.67%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Moscow                      | 9         | 5.39%   |
| Krasnodar                   | 7         | 4.19%   |
| St Petersburg               | 5         | 2.99%   |
| Brighton                    | 5         | 2.99%   |
| Seattle                     | 4         | 2.4%    |
| Vienna                      | 3         | 1.8%    |
| London                      | 3         | 1.8%    |
| Kyiv                        | 3         | 1.8%    |
| ЕЊta-ku                   | 2         | 1.2%    |
| Zurich                      | 2         | 1.2%    |
| Warsaw                      | 2         | 1.2%    |
| Vancouver                   | 2         | 1.2%    |
| Shoreham-by-Sea             | 2         | 1.2%    |
| Rio de Janeiro              | 2         | 1.2%    |
| Rietberg                    | 2         | 1.2%    |
| Northeim                    | 2         | 1.2%    |
| Istanbul                    | 2         | 1.2%    |
| Graz                        | 2         | 1.2%    |
| Fuchu                       | 2         | 1.2%    |
| Fremont                     | 2         | 1.2%    |
| Egham                       | 2         | 1.2%    |
| Choroszcz                   | 2         | 1.2%    |
| Chicago                     | 2         | 1.2%    |
| Cambridge                   | 2         | 1.2%    |
| Berlin                      | 2         | 1.2%    |
| Albuquerque                 | 2         | 1.2%    |
| Zaporizhzhya                | 1         | 0.6%    |
| Wuhan                       | 1         | 0.6%    |
| Woodburn                    | 1         | 0.6%    |
| Wieliczka                   | 1         | 0.6%    |
| Washington                  | 1         | 0.6%    |
| Voznesensk                  | 1         | 0.6%    |
| Vila Real de Santo António | 1         | 0.6%    |
| Tynda                       | 1         | 0.6%    |
| Trosa                       | 1         | 0.6%    |
| Toronto                     | 1         | 0.6%    |
| Thrissur                    | 1         | 0.6%    |
| Teaneck                     | 1         | 0.6%    |
| Taipei                      | 1         | 0.6%    |
| Stuttgart                   | 1         | 0.6%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 41        | 61     | 21.47%  |
| WDC                 | 31        | 50     | 16.23%  |
| Toshiba             | 17        | 30     | 8.9%    |
| Seagate             | 16        | 34     | 8.38%   |
| Crucial             | 13        | 25     | 6.81%   |
| Kingston            | 10        | 13     | 5.24%   |
| HGST                | 9         | 32     | 4.71%   |
| Intel               | 8         | 11     | 4.19%   |
| Micron Technology   | 6         | 9      | 3.14%   |
| KIOXIA              | 6         | 6      | 3.14%   |
| A-DATA Technology   | 6         | 6      | 3.14%   |
| SK hynix            | 5         | 5      | 2.62%   |
| FORESEE             | 3         | 3      | 1.57%   |
| Apple               | 3         | 3      | 1.57%   |
| SSSTC               | 2         | 2      | 1.05%   |
| SPCC                | 2         | 2      | 1.05%   |
| UMIS                | 1         | 1      | 0.52%   |
| Solid State Storage | 1         | 1      | 0.52%   |
| Silicon Motion      | 1         | 1      | 0.52%   |
| SanDisk             | 1         | 2      | 0.52%   |
| PNY                 | 1         | 1      | 0.52%   |
| Phison              | 1         | 2      | 0.52%   |
| Mushkin             | 1         | 1      | 0.52%   |
| LSI                 | 1         | 4      | 0.52%   |
| LITEON              | 1         | 1      | 0.52%   |
| Hitachi             | 1         | 2      | 0.52%   |
| GOODRAM             | 1         | 1      | 0.52%   |
| Fujitsu             | 1         | 2      | 0.52%   |
| Apacer              | 1         | 1      | 0.52%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB             | 7         | 3.33%   |
| Toshiba MQ04ABF100 1TB               | 4         | 1.9%    |
| HGST HTS725050A7E630 500GB           | 4         | 1.9%    |
| HGST HTS721010A9E630 1TB             | 4         | 1.9%    |
| WDC WDS100T3X0C-00SJG0 1TB           | 3         | 1.43%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 3         | 1.43%   |
| Samsung SSD 980 PRO 1TB              | 3         | 1.43%   |
| Samsung SSD 970 EVO Plus 1TB         | 3         | 1.43%   |
| Samsung SSD 870 EVO 1TB              | 3         | 1.43%   |
| Samsung SSD 860 EVO 250GB            | 3         | 1.43%   |
| Samsung HM251JX 250GB                | 3         | 1.43%   |
| WDC WDS100T1X0E-00AFY0 1TB           | 2         | 0.95%   |
| WDC WD30EFRX-68EUZN0 3TB             | 2         | 0.95%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB   | 2         | 0.95%   |
| WDC PC SN730 NVMe 1024GB             | 2         | 0.95%   |
| Seagate ST1000LM049-2GH172 1TB       | 2         | 0.95%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 0.95%   |
| Samsung SSD 980 1TB                  | 2         | 0.95%   |
| Samsung SSD 970 EVO Plus 500GB       | 2         | 0.95%   |
| Samsung SSD 870 QVO 1TB              | 2         | 0.95%   |
| Samsung SSD 850 EVO 250GB            | 2         | 0.95%   |
| Samsung MZVLB512HBJQ-000L7 512GB     | 2         | 0.95%   |
| Samsung MZVLB1T0HBLR-000L2 1TB       | 2         | 0.95%   |
| KIOXIA KBG40ZNS512G NVMe 512GB       | 2         | 0.95%   |
| KIOXIA KBG40ZNS256G NVMe 256GB       | 2         | 0.95%   |
| Kingston SA400S37240G 240GB          | 2         | 0.95%   |
| Kingston SA2000M81000G 1TB           | 2         | 0.95%   |
| FORESEE XP1000F001T 1TB              | 2         | 0.95%   |
| Crucial CT750MX300SSD1 752GB         | 2         | 0.95%   |
| Crucial CT500P2SSD8 500GB            | 2         | 0.95%   |
| Apple SSD SM256E 256GB               | 2         | 0.95%   |
| WDC WDS500G1X0E-00AFY0 500GB         | 1         | 0.48%   |
| WDC WDS250G2B0C-00PXH0 250GB         | 1         | 0.48%   |
| WDC WDS100T2B0A-00SM50 1TB           | 1         | 0.48%   |
| WDC WD60EFRX-68TGBN1 6TB             | 1         | 0.48%   |
| WDC WD5002ABYS-18B1B0 500GB          | 1         | 0.48%   |
| WDC WD40EZRZ-75GXCB0 4TB             | 1         | 0.48%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 1         | 0.48%   |
| WDC WD20EFRX-68AX9N0 2TB             | 1         | 0.48%   |
| WDC WD2003FZEX-00SRLA0 2TB           | 1         | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 34     | 25.81%  |
| Toshiba             | 15        | 27     | 24.19%  |
| WDC                 | 14        | 20     | 22.58%  |
| HGST                | 9         | 32     | 14.52%  |
| Samsung Electronics | 5         | 9      | 8.06%   |
| LSI                 | 1         | 4      | 1.61%   |
| Hitachi             | 1         | 2      | 1.61%   |
| Fujitsu             | 1         | 2      | 1.61%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 14        | 19     | 29.17%  |
| Crucial             | 8         | 15     | 16.67%  |
| Kingston            | 6         | 8      | 12.5%   |
| Intel               | 4         | 7      | 8.33%   |
| A-DATA Technology   | 4         | 4      | 8.33%   |
| Apple               | 3         | 3      | 6.25%   |
| Micron Technology   | 2         | 3      | 4.17%   |
| WDC                 | 1         | 2      | 2.08%   |
| SPCC                | 1         | 1      | 2.08%   |
| SK hynix            | 1         | 1      | 2.08%   |
| SanDisk             | 1         | 2      | 2.08%   |
| LITEON              | 1         | 1      | 2.08%   |
| GOODRAM             | 1         | 1      | 2.08%   |
| Apacer              | 1         | 1      | 2.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 78        | 114    | 46.15%  |
| SSD  | 46        | 68     | 27.22%  |
| HDD  | 45        | 130    | 26.63%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 78        | 114    | 50.65%  |
| SATA | 76        | 198    | 49.35%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 45        | 82     | 45%     |
| 0.51-1.0   | 30        | 59     | 30%     |
| 1.01-2.0   | 10        | 16     | 10%     |
| 4.01-10.0  | 6         | 26     | 6%      |
| 3.01-4.0   | 3         | 4      | 3%      |
| 2.01-3.0   | 3         | 4      | 3%      |
| 10.01-20.0 | 2         | 3      | 2%      |
| 20.01-50.0 | 1         | 4      | 1%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 40        | 25.48%  |
| 251-500        | 38        | 24.2%   |
| 501-1000       | 26        | 16.56%  |
| 21-50          | 14        | 8.92%   |
| 1-20           | 13        | 8.28%   |
| 51-100         | 12        | 7.64%   |
| 1001-2000      | 7         | 4.46%   |
| 2001-3000      | 4         | 2.55%   |
| More than 3000 | 3         | 1.91%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 101       | 63.92%  |
| 21-50          | 37        | 23.42%  |
| 101-250        | 8         | 5.06%   |
| 251-500        | 3         | 1.9%    |
| 501-1000       | 3         | 1.9%    |
| 1001-2000      | 2         | 1.27%   |
| 51-100         | 2         | 1.27%   |
| More than 3000 | 1         | 0.63%   |
| 0              | 1         | 0.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                      | Computers | Drives | Percent |
|--------------------------------------------|-----------|--------|---------|
| HGST HTS725050A7E630 500GB                 | 4         | 7      | 20%     |
| Samsung Electronics SSD 870 EVO 1TB        | 3         | 5      | 15%     |
| WDC WD60EFRX-68TGBN1 6TB                   | 1         | 3      | 5%      |
| WDC WD5002ABYS-18B1B0 500GB                | 1         | 1      | 5%      |
| WDC WD10SPZX-60Z10T0 1TB                   | 1         | 1      | 5%      |
| Seagate ST1000DM003-1CH162 1TB             | 1         | 1      | 5%      |
| Samsung Electronics SSD PM851 mSATA 256GB  | 1         | 1      | 5%      |
| Samsung Electronics HM251JX 250GB          | 1         | 1      | 5%      |
| Samsung Electronics HD154UI 1.5TB          | 1         | 2      | 5%      |
| Micron Technology P300-MTFDDAC200SAL 200GB | 1         | 2      | 5%      |
| Kingston SHPM2280P2H-240G                  | 1         | 1      | 5%      |
| Kingston SA400S37120G 120GB                | 1         | 1      | 5%      |
| Hitachi HUA722020ALA331 2TB                | 1         | 2      | 5%      |
| HGST HTS721010A9E630 1TB                   | 1         | 17     | 5%      |
| Fujitsu MHS2040AT D 40GB                   | 1         | 2      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 9      | 31.58%  |
| HGST                | 4         | 24     | 21.05%  |
| WDC                 | 3         | 5      | 15.79%  |
| Kingston            | 2         | 2      | 10.53%  |
| Seagate             | 1         | 1      | 5.26%   |
| Micron Technology   | 1         | 2      | 5.26%   |
| Hitachi             | 1         | 2      | 5.26%   |
| Fujitsu             | 1         | 2      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 4         | 24     | 33.33%  |
| WDC                 | 3         | 5      | 25%     |
| Samsung Electronics | 2         | 3      | 16.67%  |
| Seagate             | 1         | 1      | 8.33%   |
| Hitachi             | 1         | 2      | 8.33%   |
| Fujitsu             | 1         | 2      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 37     | 64.71%  |
| SSD  | 6         | 10     | 35.29%  |

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
| Works    | 122       | 255    | 85.31%  |
| Malfunc  | 16        | 47     | 11.19%  |
| Detected | 5         | 10     | 3.5%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 60        | 30.15%  |
| AMD                                     | 35        | 17.59%  |
| Samsung Electronics                     | 28        | 14.07%  |
| SanDisk                                 | 19        | 9.55%   |
| Silicon Motion                          | 8         | 4.02%   |
| Kingston Technology Company             | 6         | 3.02%   |
| SK hynix                                | 5         | 2.51%   |
| Micron/Crucial Technology               | 5         | 2.51%   |
| Micron Technology                       | 5         | 2.51%   |
| KIOXIA                                  | 5         | 2.51%   |
| Toshiba                                 | 4         | 2.01%   |
| Solid State Storage Technology          | 3         | 1.51%   |
| Broadcom / LSI                          | 3         | 1.51%   |
| Shenzhen Longsys Electronics            | 2         | 1.01%   |
| Phison Electronics                      | 2         | 1.01%   |
| Marvell Technology Group                | 2         | 1.01%   |
| ASMedia Technology                      | 2         | 1.01%   |
| ADATA Technology                        | 2         | 1.01%   |
| Shenzhen Unionmemory Information System | 1         | 0.5%    |
| MAXIO Technology (Hangzhou)             | 1         | 0.5%    |
| Chelsio Communications                  | 1         | 0.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 26        | 11.98%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 18        | 8.29%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 11        | 5.07%   |
| Intel Comet Lake SATA AHCI Controller                                          | 9         | 4.15%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 8         | 3.69%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 3.23%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 7         | 3.23%   |
| AMD 400 Series Chipset SATA Controller                                         | 7         | 3.23%   |
| Samsung NVMe SSD Controller 980                                                | 6         | 2.76%   |
| AMD 500 Series Chipset SATA Controller                                         | 5         | 2.3%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 1.84%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 4         | 1.84%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 4         | 1.84%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                 | 3         | 1.38%   |
| SK hynix BC511 NVMe SSD                                                        | 3         | 1.38%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 3         | 1.38%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 3         | 1.38%   |
| Kingston Company A2000 NVMe SSD                                                | 3         | 1.38%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 1.38%   |
| Toshiba XG6 NVMe SSD Controller                                                | 2         | 0.92%   |
| Shenzhen Longsys Lexar NM620 NVME SSD (DRAM-less)                              | 2         | 0.92%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 0.92%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 0.92%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 0.92%   |
| Phison E12 NVMe Controller                                                     | 2         | 0.92%   |
| Micron 2300 NVMe SSD [Santana]                                                 | 2         | 0.92%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 2         | 0.92%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 2         | 0.92%   |
| Intel SSD 660P Series                                                          | 2         | 0.92%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 0.92%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 0.92%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 0.92%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 2         | 0.92%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 0.92%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 0.92%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 2         | 0.92%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 2         | 0.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 0.92%   |
| Toshiba XG5 NVMe SSD Controller                                                | 1         | 0.46%   |
| Toshiba XG4 NVMe SSD Controller                                                | 1         | 0.46%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 93        | 48.95%  |
| SATA | 85        | 44.74%  |
| RAID | 5         | 2.63%   |
| IDE  | 4         | 2.11%   |
| SAS  | 2         | 1.05%   |
| SCSI | 1         | 0.53%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 73        | 48.03%  |
| AMD      | 51        | 33.55%  |
| ARM      | 18        | 11.84%  |
| Unknown  | 8         | 5.26%   |
| Research | 1         | 0.66%   |
| NXP      | 1         | 0.66%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| ARM Cortex-A55 r2p0                             | 9         | 5.92%   |
|                                                 | 8         | 5.26%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 6         | 3.95%   |
| Intel Core i5-10210U CPU @ 1.60GHz              | 5         | 3.29%   |
| Intel Core i7-3520M CPU @ 2.90GHz               | 4         | 2.63%   |
| ARM Cortex-A72 r0p3                             | 4         | 2.63%   |
| AMD Ryzen 5 5600G with Radeon Graphics          | 4         | 2.63%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 3         | 1.97%   |
| Intel Core i5-10400 CPU @ 2.90GHz               | 3         | 1.97%   |
| Intel Core i5-10300H CPU @ 2.50GHz              | 3         | 1.97%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 2         | 1.32%   |
| Intel Core i7-7600U CPU @ 2.80GHz               | 2         | 1.32%   |
| Intel Core i5-10500T CPU @ 2.30GHz              | 2         | 1.32%   |
| ARM Cortex-A72 r0p2                             | 2         | 1.32%   |
| ARM Cortex-A53 r0p4                             | 2         | 1.32%   |
| AMD Ryzen 9 7950X 16-Core Processor             | 2         | 1.32%   |
| AMD Ryzen 9 5950X 16-Core Processor             | 2         | 1.32%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 2         | 1.32%   |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx | 2         | 1.32%   |
| AMD Ryzen 7 5825U with Radeon Graphics          | 2         | 1.32%   |
| AMD Ryzen 7 4800U with Radeon Graphics          | 2         | 1.32%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 2         | 1.32%   |
| AMD Ryzen 7 4700U with Radeon Graphics          | 2         | 1.32%   |
| AMD Ryzen 7 2700X Eight-Core Processor          | 2         | 1.32%   |
| AMD Ryzen 5 PRO 3500U w/ Radeon Vega Mobile Gfx | 2         | 1.32%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 2         | 1.32%   |
| AMD Custom APU 0405                             | 2         | 1.32%   |
| Research Morello SoC r0p0                       | 1         | 0.66%   |
| NXP Cortex-A72                                  | 1         | 0.66%   |
| Intel Xeon W-10885M CPU @ 2.40GHz               | 1         | 0.66%   |
| Intel Xeon E-2334 CPU @ 3.40GHz                 | 1         | 0.66%   |
| Intel Xeon CPU E5-2697A v4 @ 2.60GHz            | 1         | 0.66%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz             | 1         | 0.66%   |
| Intel Pentium M processor 1000MHz               | 1         | 0.66%   |
| Intel Core i7-9850H CPU @ 2.60GHz               | 1         | 0.66%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 1         | 0.66%   |
| Intel Core i7-8700 CPU @ 3.20GHz                | 1         | 0.66%   |
| Intel Core i7-8650U CPU @ 1.90GHz               | 1         | 0.66%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 0.66%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 1         | 0.66%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 32        | 21.19%  |
| Other                  | 27        | 17.88%  |
| Intel Core i5          | 19        | 12.58%  |
| ARM Cortex             | 17        | 11.26%  |
| AMD Ryzen 7            | 14        | 9.27%   |
| AMD Ryzen 5            | 13        | 8.61%   |
| AMD Ryzen 9            | 9         | 5.96%   |
| Intel Xeon             | 4         | 2.65%   |
| AMD Ryzen 7 PRO        | 3         | 1.99%   |
| AMD Ryzen 5 PRO        | 3         | 1.99%   |
| Intel Pentium M        | 1         | 0.66%   |
| Intel Core i3          | 1         | 0.66%   |
| Intel Atom             | 1         | 0.66%   |
| AMD Ryzen Threadripper | 1         | 0.66%   |
| AMD Ryzen Embedded     | 1         | 0.66%   |
| AMD Ryzen 3            | 1         | 0.66%   |
| AMD FX                 | 1         | 0.66%   |
| AMD EPYC               | 1         | 0.66%   |
| AMD E                  | 1         | 0.66%   |
| AMD Athlon             | 1         | 0.66%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 32        | 21.19%  |
| Unknown | 27        | 17.88%  |
| 8       | 20        | 13.25%  |
| 2       | 18        | 11.92%  |
| 16      | 16        | 10.6%   |
| 6       | 15        | 9.93%   |
| 12      | 11        | 7.28%   |
| 32      | 6         | 3.97%   |
| 24      | 3         | 1.99%   |
| 64      | 1         | 0.66%   |
| 10      | 1         | 0.66%   |
| 1       | 1         | 0.66%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 128       | 84.77%  |
| Unknown | 22        | 14.57%  |
| 2       | 1         | 0.66%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 70        | 46.36%  |
| 1       | 53        | 35.1%   |
| Unknown | 28        | 18.54%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 43        | 28.48%  |
| KabyLake   | 21        | 13.91%  |
| CometLake  | 15        | 9.93%   |
| Zen 2      | 13        | 8.61%   |
| Zen 3      | 12        | 7.95%   |
| Zen+       | 11        | 7.28%   |
| IvyBridge  | 9         | 5.96%   |
| TigerLake  | 8         | 5.3%    |
| Zen        | 5         | 3.31%   |
| Broadwell  | 4         | 2.65%   |
| Haswell    | 3         | 1.99%   |
| Skylake    | 2         | 1.32%   |
| Silvermont | 1         | 0.66%   |
| Piledriver | 1         | 0.66%   |
| P6         | 1         | 0.66%   |
| IceLake    | 1         | 0.66%   |
| Bobcat     | 1         | 0.66%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 60        | 38.46%  |
| AMD                        | 50        | 32.05%  |
| Nvidia                     | 42        | 26.92%  |
| Matrox Electronics Systems | 2         | 1.28%   |
| ASPEED Technology          | 2         | 1.28%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                           | 10        | 6.29%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                            | 8         | 5.03%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series] | 7         | 4.4%    |
| Intel CometLake-U GT2 [UHD Graphics]                                 | 6         | 3.77%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]         | 6         | 3.77%   |
| Intel CometLake-H GT2 [UHD Graphics]                                 | 5         | 3.14%   |
| Intel 3rd Gen Core processor Graphics Controller                     | 5         | 3.14%   |
| Nvidia TU117M                                                        | 4         | 2.52%   |
| Intel HD Graphics 620                                                | 4         | 2.52%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                             | 4         | 2.52%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                            | 4         | 2.52%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                             | 3         | 1.89%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]     | 3         | 1.89%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                           | 2         | 1.26%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                           | 2         | 1.26%   |
| Nvidia GP108M [GeForce MX230]                                        | 2         | 1.26%   |
| Nvidia GP108 [GeForce GT 1030]                                       | 2         | 1.26%   |
| Nvidia GK208B [GeForce GT 710]                                       | 2         | 1.26%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                              | 2         | 1.26%   |
| Intel UHD Graphics 620                                               | 2         | 1.26%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                 | 2         | 1.26%   |
| Intel HD Graphics 630                                                | 2         | 1.26%   |
| Intel Alder Lake-P Integrated Graphics Controller                    | 2         | 1.26%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller          | 2         | 1.26%   |
| ASPEED Technology ASPEED Graphics Family                             | 2         | 1.26%   |
| AMD VanGogh [AMD Custom GPU 0405]                                    | 2         | 1.26%   |
| AMD Rembrandt [Radeon 680M]                                          | 2         | 1.26%   |
| AMD Raphael                                                          | 2         | 1.26%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]        | 2         | 1.26%   |
| AMD Lucienne                                                         | 2         | 1.26%   |
| AMD Barcelo                                                          | 2         | 1.26%   |
| Nvidia TU117M [GeForce MX450]                                        | 1         | 0.63%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                | 1         | 0.63%   |
| Nvidia TU117 [GeForce GTX 1650]                                      | 1         | 0.63%   |
| Nvidia TU116 [GeForce GTX 1660]                                      | 1         | 0.63%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                              | 1         | 0.63%   |
| Nvidia TU104GLM [Quadro RTX 5000 Mobile / Max-Q]                     | 1         | 0.63%   |
| Nvidia GT218 [GeForce 210]                                           | 1         | 0.63%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                           | 1         | 0.63%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                              | 1         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x AMD                  | 40        | 26.32%  |
| 1 x Intel                | 34        | 22.37%  |
| Other                    | 26        | 17.11%  |
| Intel + Nvidia           | 22        | 14.47%  |
| 1 x Nvidia               | 17        | 11.18%  |
| 2 x AMD                  | 3         | 1.97%   |
| AMD + Nvidia             | 3         | 1.97%   |
| 1 x Matrox               | 2         | 1.32%   |
| Intel + AMD              | 2         | 1.32%   |
| 1 x ASPEED               | 2         | 1.32%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.66%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 97        | 64.67%  |
| Proprietary | 27        | 18%     |
| Unknown     | 26        | 17.33%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 109       | 71.24%  |
| 1.01-2.0   | 11        | 7.19%   |
| 0.01-0.5   | 8         | 5.23%   |
| 0.51-1.0   | 7         | 4.58%   |
| 3.01-4.0   | 6         | 3.92%   |
| 7.01-8.0   | 5         | 3.27%   |
| 5.01-6.0   | 3         | 1.96%   |
| 8.01-16.0  | 3         | 1.96%   |
| 2.01-3.0   | 1         | 0.65%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| BOE                 | 15        | 15.15%  |
| AU Optronics        | 13        | 13.13%  |
| LG Display          | 10        | 10.1%   |
| Dell                | 7         | 7.07%   |
| Goldstar            | 6         | 6.06%   |
| Hewlett-Packard     | 5         | 5.05%   |
| Chimei Innolux      | 5         | 5.05%   |
| Philips             | 4         | 4.04%   |
| Samsung Electronics | 3         | 3.03%   |
| LG Electronics      | 3         | 3.03%   |
| BenQ                | 3         | 3.03%   |
| Sony                | 2         | 2.02%   |
| Sharp               | 2         | 2.02%   |
| RTK                 | 2         | 2.02%   |
| Lenovo              | 2         | 2.02%   |
| InfoVision          | 2         | 2.02%   |
| HKC                 | 2         | 2.02%   |
| Apple               | 2         | 2.02%   |
| ViewSonic           | 1         | 1.01%   |
| SDC                 | 1         | 1.01%   |
| PANDA               | 1         | 1.01%   |
| LGD                 | 1         | 1.01%   |
| Iiyama              | 1         | 1.01%   |
| Idek Iiyama         | 1         | 1.01%   |
| HJW                 | 1         | 1.01%   |
| Eizo                | 1         | 1.01%   |
| CSO                 | 1         | 1.01%   |
| AOC                 | 1         | 1.01%   |
| Unknown             | 1         | 1.01%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0258 1600x900 350x190mm 15.7-inch            | 3         | 2.97%   |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                  | 3         | 2.97%   |
| RTK WCS Display RTK1A1B 1920x1080 344x195mm 15.6-inch                  | 2         | 1.98%   |
| Philips 271P4 PHL08C3 1920x1080 600x340mm 27.2-inch                    | 2         | 1.98%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch           | 2         | 1.98%   |
| ViewSonic VG2439 Series VSCD22B 1920x1080 520x290mm 23.4-inch          | 1         | 0.99%   |
| Sony TV SNY4B03 1920x1080 930x520mm 41.9-inch                          | 1         | 0.99%   |
| Sony TV  *30 SNY05D1 3840x2160 1660x930mm 74.9-inch                    | 1         | 0.99%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 380x210mm 17.1-inch                | 1         | 0.99%   |
| Sharp LCD Monitor SHP14B9 3840x2160 340x190mm 15.3-inch                | 1         | 0.99%   |
| SDC LCD Monitor 3520x1080                                              | 1         | 0.99%   |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                       | 1         | 0.99%   |
| Samsung Electronics LCD Monitor SDC3754 1600x900 380x210mm 17.1-inch   | 1         | 0.99%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1020x570mm 46.0-inch | 1         | 0.99%   |
| Philips PHL 273V7 PHLC156 1920x1080 600x340mm 27.2-inch                | 1         | 0.99%   |
| Philips LCD Monitor 271P4 3520x1080                                    | 1         | 0.99%   |
| Philips LCD Monitor 271P4                                              | 1         | 0.99%   |
| PANDA LCD Monitor NCP004F 1920x1080 310x170mm 13.9-inch                | 1         | 0.99%   |
| LGD LCD Monitor 1920x1080                                              | 1         | 0.99%   |
| LG Electronics LCD Monitor LX20D 1600x1200                             | 1         | 0.99%   |
| LG Electronics LCD Monitor LG Ultra HD 11520x2160                      | 1         | 0.99%   |
| LG Electronics LCD Monitor LG Ultra HD                                 | 1         | 0.99%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                        | 1         | 0.99%   |
| LG Display LCD Monitor LGD062E 1920x1080 340x190mm 15.3-inch           | 1         | 0.99%   |
| LG Display LCD Monitor LGD060A 1920x1080 290x170mm 13.2-inch           | 1         | 0.99%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch           | 1         | 0.99%   |
| LG Display LCD Monitor LGD05F1 1920x1080 310x170mm 13.9-inch           | 1         | 0.99%   |
| LG Display LCD Monitor LGD033E 1366x768 310x170mm 13.9-inch            | 1         | 0.99%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                  | 1         | 0.99%   |
| Lenovo LEN P44w-10 LEN61D5 3840x1200 1050x330mm 43.3-inch              | 1         | 0.99%   |
| InfoVision LCD Monitor IVO8544 1920x1080 290x170mm 13.2-inch           | 1         | 0.99%   |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch           | 1         | 0.99%   |
| Iiyama PL2474H IVM6146 1920x1080 520x290mm 23.4-inch                   | 1         | 0.99%   |
| Idek Iiyama LCD Monitor PL2792UH 3840x2160                             | 1         | 0.99%   |
| HKC LCD Monitor HKC3D05 1920x1080 340x190mm 15.3-inch                  | 1         | 0.99%   |
| HKC 27E6QC HKC274F 2560x1440 600x330mm 27.0-inch                       | 1         | 0.99%   |
| HJW HDMI TO USB HJW0001 1920x1080 700x390mm 31.5-inch                  | 1         | 0.99%   |
| Hewlett-Packard LCD Monitor LA2306 3520x1080                           | 1         | 0.99%   |
| Hewlett-Packard LA2405x HWP301F 1920x1200 520x320mm 24.0-inch          | 1         | 0.99%   |
| Hewlett-Packard LA2306 HWP2949 1920x1080 510x290mm 23.1-inch           | 1         | 0.99%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 54        | 54.55%  |
| 3840x2160 (4K)    | 10        | 10.1%   |
| 2560x1440 (QHD)   | 7         | 7.07%   |
| 1600x900 (HD+)    | 6         | 6.06%   |
| 1920x1200 (WUXGA) | 5         | 5.05%   |
| 2256x1504         | 3         | 3.03%   |
| 1366x768 (WXGA)   | 3         | 3.03%   |
| 2560x1600         | 2         | 2.02%   |
| Unknown           | 2         | 2.02%   |
| 4480x1440         | 1         | 1.01%   |
| 3840x1200         | 1         | 1.01%   |
| 3520x1080         | 1         | 1.01%   |
| 2560x1080         | 1         | 1.01%   |
| 2160x1440         | 1         | 1.01%   |
| 1600x1200         | 1         | 1.01%   |
| 11520x2160        | 1         | 1.01%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 26        | 26.8%   |
| 15      | 21        | 21.65%  |
| Unknown | 11        | 11.34%  |
| 27      | 10        | 10.31%  |
| 24      | 7         | 7.22%   |
| 23      | 6         | 6.19%   |
| 17      | 3         | 3.09%   |
| 12      | 3         | 3.09%   |
| 32      | 2         | 2.06%   |
| 74      | 1         | 1.03%   |
| 46      | 1         | 1.03%   |
| 43      | 1         | 1.03%   |
| 41      | 1         | 1.03%   |
| 34      | 1         | 1.03%   |
| 31      | 1         | 1.03%   |
| 22      | 1         | 1.03%   |
| 21      | 1         | 1.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 37        | 38.54%  |
| 501-600     | 21        | 21.88%  |
| 201-300     | 13        | 13.54%  |
| Unknown     | 11        | 11.46%  |
| 701-800     | 3         | 3.13%   |
| 351-400     | 3         | 3.13%   |
| 601-700     | 2         | 2.08%   |
| 401-500     | 2         | 2.08%   |
| 1001-1500   | 2         | 2.08%   |
| 1501-2000   | 1         | 1.04%   |
| 901-1000    | 1         | 1.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 67        | 74.44%  |
| Unknown | 10        | 11.11%  |
| 16/10   | 8         | 8.89%   |
| 3/2     | 3         | 3.33%   |
| 3.18    | 1         | 1.11%   |
| 21/9    | 1         | 1.11%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 21        | 21.65%  |
| 91-100         | 16        | 16.49%  |
| Unknown        | 11        | 11.34%  |
| 301-350        | 10        | 10.31%  |
| 201-250        | 10        | 10.31%  |
| 71-80          | 5         | 5.15%   |
| 251-300        | 5         | 5.15%   |
| 101-110        | 5         | 5.15%   |
| 351-500        | 4         | 4.12%   |
| 61-70          | 3         | 3.09%   |
| 121-130        | 3         | 3.09%   |
| 501-1000       | 3         | 3.09%   |
| More than 1000 | 1         | 1.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 32        | 33.68%  |
| 51-100        | 24        | 25.26%  |
| 161-240       | 14        | 14.74%  |
| Unknown       | 11        | 11.58%  |
| 101-120       | 9         | 9.47%   |
| More than 240 | 4         | 4.21%   |
| 1-50          | 1         | 1.05%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 80        | 51.61%  |
| 0     | 63        | 40.65%  |
| 2     | 11        | 7.1%    |
| 3     | 1         | 0.65%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 94        | 43.12%  |
| Realtek Semiconductor           | 72        | 33.03%  |
| Qualcomm Atheros                | 8         | 3.67%   |
| TP-Link                         | 7         | 3.21%   |
| Broadcom                        | 6         | 2.75%   |
| Ralink Technology               | 4         | 1.83%   |
| Hewlett-Packard                 | 4         | 1.83%   |
| Mellanox Technologies           | 3         | 1.38%   |
| MediaTek                        | 3         | 1.38%   |
| D-Link System                   | 3         | 1.38%   |
| Edimax Technology               | 2         | 0.92%   |
| Xiaomi                          | 1         | 0.46%   |
| Ralink                          | 1         | 0.46%   |
| Qualcomm Atheros Communications | 1         | 0.46%   |
| Lenovo                          | 1         | 0.46%   |
| Huawei Technologies             | 1         | 0.46%   |
| Google                          | 1         | 0.46%   |
| Emulex                          | 1         | 0.46%   |
| Chelsio Communications          | 1         | 0.46%   |
| BUFFALO                         | 1         | 0.46%   |
| ASUSTek Computer                | 1         | 0.46%   |
| Arduino SA                      | 1         | 0.46%   |
| Aquantia                        | 1         | 0.46%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 48        | 18.11%  |
| Realtek RTL8125 2.5GbE Controller                                          | 14        | 5.28%   |
| Intel Wi-Fi 6 AX200                                                        | 14        | 5.28%   |
| Intel Wireless-AC 9260                                                     | 7         | 2.64%   |
| Intel I211 Gigabit Network Connection                                      | 7         | 2.64%   |
| Intel Comet Lake PCH CNVi WiFi                                             | 7         | 2.64%   |
| Intel Wireless 8265 / 8275                                                 | 6         | 2.26%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                     | 6         | 2.26%   |
| Intel Wi-Fi 6 AX201                                                        | 6         | 2.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                          | 6         | 2.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 6         | 2.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 6         | 2.26%   |
| Intel Ethernet Controller I225-V                                           | 5         | 1.89%   |
| Intel 82574L Gigabit Network Connection                                    | 5         | 1.89%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 4         | 1.51%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 4         | 1.51%   |
| Intel Wireless 7265                                                        | 4         | 1.51%   |
| Intel I210 Gigabit Network Connection                                      | 4         | 1.51%   |
| HP hs2350 HSPA+ Mobile Broadband Module Network Adapter                    | 4         | 1.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 3         | 1.13%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 3         | 1.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 3         | 1.13%   |
| Intel Ethernet Connection (4) I219-LM                                      | 3         | 1.13%   |
| Intel Ethernet Connection (14) I219-LM                                     | 3         | 1.13%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 3         | 1.13%   |
| Ralink MT7601U Wireless Adapter                                            | 2         | 0.75%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 2         | 0.75%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter              | 2         | 0.75%   |
| Intel Wireless 7260                                                        | 2         | 0.75%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                              | 2         | 0.75%   |
| Intel Ethernet Connection (11) I219-LM                                     | 2         | 0.75%   |
| Intel Ethernet Connection (10) I219-V                                      | 2         | 0.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 2         | 0.75%   |
| Intel Alder Lake-P PCH CNVi WiFi                                           | 2         | 0.75%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                       | 1         | 0.38%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                | 1         | 0.38%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                     | 1         | 0.38%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]        | 1         | 0.38%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                         | 1         | 0.38%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                | 1         | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 74        | 61.67%  |
| Realtek Semiconductor           | 11        | 9.17%   |
| TP-Link                         | 7         | 5.83%   |
| Qualcomm Atheros                | 7         | 5.83%   |
| Broadcom                        | 5         | 4.17%   |
| Ralink Technology               | 4         | 3.33%   |
| MediaTek                        | 3         | 2.5%    |
| D-Link System                   | 3         | 2.5%    |
| Edimax Technology               | 2         | 1.67%   |
| Ralink                          | 1         | 0.83%   |
| Qualcomm Atheros Communications | 1         | 0.83%   |
| BUFFALO                         | 1         | 0.83%   |
| ASUSTek Computer                | 1         | 0.83%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                           | 14        | 11.67%  |
| Intel Wireless-AC 9260                                                        | 7         | 5.83%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 7         | 5.83%   |
| Intel Wireless 8265 / 8275                                                    | 6         | 5%      |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 6         | 5%      |
| Intel Wi-Fi 6 AX201                                                           | 6         | 5%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 6         | 5%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 6         | 5%      |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 4         | 3.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 4         | 3.33%   |
| Intel Wireless 7265                                                           | 4         | 3.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 3         | 2.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 3         | 2.5%    |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]    | 3         | 2.5%    |
| Ralink MT7601U Wireless Adapter                                               | 2         | 1.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 2         | 1.67%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                 | 2         | 1.67%   |
| Intel Wireless 7260                                                           | 2         | 1.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2         | 1.67%   |
| Intel Alder Lake-P PCH CNVi WiFi                                              | 2         | 1.67%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1         | 0.83%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1         | 0.83%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]           | 1         | 0.83%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1         | 0.83%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                      | 1         | 0.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.83%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                        | 1         | 0.83%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 0.83%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1         | 0.83%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 1         | 0.83%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 1         | 0.83%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1         | 0.83%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 0.83%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                 | 1         | 0.83%   |
| Intel Wireless 8260                                                           | 1         | 0.83%   |
| Intel Wi-Fi 6 AX201 160MHz                                                    | 1         | 0.83%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 1         | 0.83%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 0.83%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 0.83%   |
| Intel Centrino Advanced-N 6235                                                | 1         | 0.83%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Realtek Semiconductor  | 64        | 50%     |
| Intel                  | 53        | 41.41%  |
| Qualcomm Atheros       | 2         | 1.56%   |
| Broadcom               | 2         | 1.56%   |
| Xiaomi                 | 1         | 0.78%   |
| Lenovo                 | 1         | 0.78%   |
| Huawei Technologies    | 1         | 0.78%   |
| Google                 | 1         | 0.78%   |
| Emulex                 | 1         | 0.78%   |
| Chelsio Communications | 1         | 0.78%   |
| Aquantia               | 1         | 0.78%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 48        | 35.82%  |
| Realtek RTL8125 2.5GbE Controller                                             | 13        | 9.7%    |
| Intel I211 Gigabit Network Connection                                         | 7         | 5.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6         | 4.48%   |
| Intel Ethernet Controller I225-V                                              | 5         | 3.73%   |
| Intel 82574L Gigabit Network Connection                                       | 5         | 3.73%   |
| Intel I210 Gigabit Network Connection                                         | 4         | 2.99%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 3         | 2.24%   |
| Intel Ethernet Connection (4) I219-LM                                         | 3         | 2.24%   |
| Intel Ethernet Connection (14) I219-LM                                        | 3         | 2.24%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 2         | 1.49%   |
| Intel Ethernet Connection (11) I219-LM                                        | 2         | 1.49%   |
| Intel Ethernet Connection (10) I219-V                                         | 2         | 1.49%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                          | 1         | 0.75%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 0.75%   |
| Realtek Killer E3000 2.5GbE Controller                                        | 1         | 0.75%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1         | 0.75%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1         | 0.75%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                              | 1         | 0.75%   |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller                           | 1         | 0.75%   |
| Intel I350 Gigabit Network Connection                                         | 1         | 0.75%   |
| Intel Ethernet Controller X550                                                | 1         | 0.75%   |
| Intel Ethernet Controller I225-LM                                             | 1         | 0.75%   |
| Intel Ethernet Connection I219-LM                                             | 1         | 0.75%   |
| Intel Ethernet Connection I218-LM                                             | 1         | 0.75%   |
| Intel Ethernet Connection I217-LM                                             | 1         | 0.75%   |
| Intel Ethernet Connection (7) I219-V                                          | 1         | 0.75%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1         | 0.75%   |
| Intel Ethernet Connection (5) I219-V                                          | 1         | 0.75%   |
| Intel Ethernet Connection (4) I219-V                                          | 1         | 0.75%   |
| Intel Ethernet Connection (3) I218-LM                                         | 1         | 0.75%   |
| Intel Ethernet Connection (2) I219-V                                          | 1         | 0.75%   |
| Intel Ethernet Connection (16) I219-LM                                        | 1         | 0.75%   |
| Intel Ethernet Connection (13) I219-V                                         | 1         | 0.75%   |
| Intel Ethernet Connection (11) I219-V                                         | 1         | 0.75%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1         | 0.75%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 0.75%   |
| Huawei USB Device                                                             | 1         | 0.75%   |
| Google Nexus/Pixel Device (charging + debug)                                  | 1         | 0.75%   |
| Emulex OneConnect 10Gb NIC (be3)                                              | 1         | 0.75%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 116       | 51.33%  |
| WiFi     | 99        | 43.81%  |
| Modem    | 6         | 2.65%   |
| Unknown  | 5         | 2.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 95        | 62.5%   |
| WiFi     | 54        | 35.53%  |
| Modem    | 3         | 1.97%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 79        | 52.67%  |
| 1     | 40        | 26.67%  |
| 0     | 17        | 11.33%  |
| 3     | 9         | 6%      |
| 4     | 3         | 2%      |
| 10    | 1         | 0.67%   |
| 7     | 1         | 0.67%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 131       | 83.97%  |
| Yes  | 25        | 16.03%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 58        | 73.42%  |
| IMC Networks                    | 5         | 6.33%   |
| Apple                           | 4         | 5.06%   |
| Broadcom                        | 3         | 3.8%    |
| Realtek Semiconductor           | 2         | 2.53%   |
| Qualcomm Atheros Communications | 2         | 2.53%   |
| Skylight Digital                | 1         | 1.27%   |
| Ralink                          | 1         | 1.27%   |
| Opticis                         | 1         | 1.27%   |
| Foxconn / Hon Hai               | 1         | 1.27%   |
| Cambridge Silicon Radio         | 1         | 1.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 18        | 22.78%  |
| Intel AX200 Bluetooth                               | 13        | 16.46%  |
| Intel Bluetooth wireless interface                  | 10        | 12.66%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 6         | 7.59%   |
| Intel AX210 Bluetooth                               | 5         | 6.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 5.06%   |
| IMC Networks Realtek Bluetooth Adapter              | 3         | 3.8%    |
| Apple Bluetooth Host Controller                     | 3         | 3.8%    |
| Realtek Bluetooth Adapter                           | 2         | 2.53%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 2.53%   |
| Skylight Digital Realtek Bluetooth Adapter          | 1         | 1.27%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.27%   |
| Opticis Realtek Bluetooth Adapter                   | 1         | 1.27%   |
| Intel Wireless Bluetooth                            | 1         | 1.27%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.27%   |
| IMC Networks MediaTek Bluetooth Adapter             | 1         | 1.27%   |
| IMC Networks Bluetooth module                       | 1         | 1.27%   |
| Foxconn / Hon Hai RZ616 Bluetooth Adapter           | 1         | 1.27%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.27%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.27%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.27%   |
| Broadcom BCM2035 Bluetooth dongle                   | 1         | 1.27%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 1.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 69        | 37.91%  |
| AMD                     | 56        | 30.77%  |
| Nvidia                  | 33        | 18.13%  |
| C-Media Electronics     | 4         | 2.2%    |
| Lenovo                  | 3         | 1.65%   |
| Logitech                | 2         | 1.1%    |
| Generalplus Technology  | 2         | 1.1%    |
| CMX Systems             | 2         | 1.1%    |
| Yamaha                  | 1         | 0.55%   |
| Texas Instruments       | 1         | 0.55%   |
| SteelSeries ApS         | 1         | 0.55%   |
| RODE Microphones        | 1         | 0.55%   |
| JMTek                   | 1         | 0.55%   |
| GN Netcom               | 1         | 0.55%   |
| Creative Labs           | 1         | 0.55%   |
| Blue Microphones        | 1         | 0.55%   |
| AudioQuest              | 1         | 0.55%   |
| ASUSTek Computer        | 1         | 0.55%   |
| AKAI  Professional M.I. | 1         | 0.55%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                  | 32        | 14.22%  |
| AMD Renoir Radeon High Definition Audio Controller                      | 18        | 8%      |
| Intel Comet Lake PCH cAVS                                               | 11        | 4.89%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                     | 10        | 4.44%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller     | 9         | 4%      |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller             | 8         | 3.56%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller          | 7         | 3.11%   |
| Intel Sunrise Point-LP HD Audio                                         | 7         | 3.11%   |
| Intel Comet Lake PCH-LP cAVS                                            | 6         | 2.67%   |
| Intel Cannon Lake PCH cAVS                                              | 6         | 2.67%   |
| AMD Starship/Matisse HD Audio Controller                                | 6         | 2.67%   |
| AMD Rembrandt Radeon High Definition Audio Controller                   | 6         | 2.67%   |
| Nvidia GP107GL High Definition Audio Controller                         | 5         | 2.22%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                     | 5         | 2.22%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                 | 4         | 1.78%   |
| Nvidia TU116 High Definition Audio Controller                           | 3         | 1.33%   |
| Intel Tiger Lake-H HD Audio Controller                                  | 3         | 1.33%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]               | 3         | 1.33%   |
| Nvidia GP108 High Definition Audio Controller                           | 2         | 0.89%   |
| Nvidia GK208 HDMI/DP Audio Controller                                   | 2         | 0.89%   |
| Nvidia GK107 HDMI Audio Controller                                      | 2         | 0.89%   |
| Nvidia GA104 High Definition Audio Controller                           | 2         | 0.89%   |
| Intel Wildcat Point-LP High Definition Audio Controller                 | 2         | 0.89%   |
| Intel Comet Lake PCH-V cAVS                                             | 2         | 0.89%   |
| Intel CM238 HD Audio Controller                                         | 2         | 0.89%   |
| Intel Broadwell-U Audio Controller                                      | 2         | 0.89%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                 | 2         | 0.89%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller     | 2         | 0.89%   |
| Generalplus Technology USB Audio Device                                 | 2         | 0.89%   |
| CMX Systems USB PnP Audio Device                                        | 2         | 0.89%   |
| AMD SBx00 Azalia (Intel HDA)                                            | 2         | 0.89%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 2         | 0.89%   |
| AMD Navi 10 HDMI Audio                                                  | 2         | 0.89%   |
| Unknown                                                                 | 2         | 0.89%   |
| Yamaha Steinberg UR12                                                   | 1         | 0.44%   |
| Texas Instruments PCM2706 stereo audio DAC                              | 1         | 0.44%   |
| SteelSeries ApS SteelSeries Siberia 350                                 | 1         | 0.44%   |
| RODE Microphones RODE AI-1                                              | 1         | 0.44%   |
| Nvidia TU106 High Definition Audio Controller                           | 1         | 0.44%   |
| Nvidia TU104 HD Audio Controller                                        | 1         | 0.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 31        | 21.53%  |
| SK hynix                     | 20        | 13.89%  |
| Micron Technology            | 19        | 13.19%  |
| Kingston                     | 18        | 12.5%   |
| Crucial                      | 12        | 8.33%   |
| Corsair                      | 6         | 4.17%   |
| Unknown                      | 5         | 3.47%   |
| Unknown                      | 5         | 3.47%   |
| G.Skill                      | 4         | 2.78%   |
| Smart                        | 3         | 2.08%   |
| Ramaxel Technology           | 3         | 2.08%   |
| Team                         | 2         | 1.39%   |
| Goodram                      | 2         | 1.39%   |
| A-DATA Technology            | 2         | 1.39%   |
| Unknown (000000000C01)       | 1         | 0.69%   |
| Transcend                    | 1         | 0.69%   |
| PNY                          | 1         | 0.69%   |
| Patriot Memory (PDP Systems) | 1         | 0.69%   |
| Neo Forza                    | 1         | 0.69%   |
| KLEVV                        | 1         | 0.69%   |
| Golden Empire                | 1         | 0.69%   |
| Gold Key                     | 1         | 0.69%   |
| Elpida                       | 1         | 0.69%   |
| Apacer                       | 1         | 0.69%   |
| 0B45000080CE                 | 1         | 0.69%   |
| 06F100000C01                 | 1         | 0.69%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown                                                        | 5         | 3.33%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s          | 4         | 2.67%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s         | 3         | 2%      |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 2         | 1.33%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s         | 2         | 1.33%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s        | 2         | 1.33%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s          | 2         | 1.33%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s          | 2         | 1.33%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s           | 2         | 1.33%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s           | 2         | 1.33%   |
| Crucial RAM BL32G32C16S4B.M16FB1 32GB SODIMM DDR4 2667MT/s     | 2         | 1.33%   |
| Corsair RAM CMK32GX4M2D3200C16 16GB DIMM DDR4 3200MT/s         | 2         | 1.33%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 1         | 0.67%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                    | 1         | 0.67%   |
| Unknown RAM Module 1GB SODIMM DDR                              | 1         | 0.67%   |
| Unknown RAM 3000 C16 Series 4096MB DIMM DDR4 2933MT/s          | 1         | 0.67%   |
| Unknown RAM 2G-08-10-12-1333 2GB DIMM DDR3 1333MT/s            | 1         | 0.67%   |
| Unknown (000000000C01) RAM Module 32GB DIMM DDR4 3200MT/s      | 1         | 0.67%   |
| Transcend RAM JM2666HLE-32G 32GB DIMM DDR4 2666MT/s            | 1         | 0.67%   |
| Team RAM TEAMGROUP-UD4-4133 8GB DIMM DDR4 4133MT/s             | 1         | 0.67%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s           | 1         | 0.67%   |
| Smart RAM SF4641G8CK8IWGKSEG 8GB SODIMM DDR4 2133MT/s          | 1         | 0.67%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s          | 1         | 0.67%   |
| Smart RAM Module 8GB DIMM DDR4 2667MT/s                        | 1         | 0.67%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1867MT/s                   | 1         | 0.67%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                   | 1         | 0.67%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s         | 1         | 0.67%   |
| SK hynix RAM HMAA4GU6CJR8N-XN 32GB DIMM DDR4 3200MT/s          | 1         | 0.67%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s         | 1         | 0.67%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s        | 1         | 0.67%   |
| SK hynix RAM HMA82GR7JJR8N-VK 16GB DIMM DDR4 2667MT/s          | 1         | 0.67%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 1         | 0.67%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s         | 1         | 0.67%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 1         | 0.67%   |
| SK hynix RAM HCNNNCRMBLPR-NEE 2GB Row Of Chips LPDDR4 4267MT/s | 1         | 0.67%   |
| Samsung RAM Module 4GB SODIMM DDR4 3200MT/s                    | 1         | 0.67%   |
| Samsung RAM M474A4G43AB1-CVF 32GB SODIMM DDR4 2933MT/s         | 1         | 0.67%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s          | 1         | 0.67%   |
| Samsung RAM M471B5674-M0-YK0 4GB Chip DDR3 1600MT/s            | 1         | 0.67%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 1         | 0.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 96        | 76.8%   |
| DDR3   | 16        | 12.8%   |
| DDR5   | 4         | 3.2%    |
| LPDDR5 | 3         | 2.4%    |
| LPDDR4 | 3         | 2.4%    |
| LPDDR3 | 2         | 1.6%    |
| DDR    | 1         | 0.8%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 77        | 61.6%   |
| DIMM         | 39        | 31.2%   |
| Row Of Chips | 8         | 6.4%    |
| Chip         | 1         | 0.8%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 45        | 34.62%  |
| 16384 | 42        | 32.31%  |
| 32768 | 20        | 15.38%  |
| 4096  | 17        | 13.08%  |
| 2048  | 5         | 3.85%   |
| 1024  | 1         | 0.77%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 46        | 34.85%  |
| 2667    | 25        | 18.94%  |
| 2400    | 14        | 10.61%  |
| 1600    | 8         | 6.06%   |
| 2133    | 6         | 4.55%   |
| 1867    | 6         | 4.55%   |
| 2666    | 5         | 3.79%   |
| 4800    | 3         | 2.27%   |
| 4267    | 3         | 2.27%   |
| 2933    | 3         | 2.27%   |
| 4266    | 2         | 1.52%   |
| 3600    | 2         | 1.52%   |
| 1333    | 2         | 1.52%   |
| 6400    | 1         | 0.76%   |
| 5200    | 1         | 0.76%   |
| 4133    | 1         | 0.76%   |
| 3000    | 1         | 0.76%   |
| 1866    | 1         | 0.76%   |
| 1334    | 1         | 0.76%   |
| Unknown | 1         | 0.76%   |

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
| Chicony Electronics                    | 17        | 20.73%  |
| IMC Networks                           | 12        | 14.63%  |
| Microdia                               | 9         | 10.98%  |
| Logitech                               | 9         | 10.98%  |
| Realtek Semiconductor                  | 8         | 9.76%   |
| Lite-On Technology                     | 5         | 6.1%    |
| Bison Electronics                      | 5         | 6.1%    |
| Sunplus Innovation Technology          | 4         | 4.88%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.66%   |
| Syntek                                 | 2         | 2.44%   |
| Shenzhen Kingcome Optoelectronic       | 2         | 2.44%   |
| Apple                                  | 2         | 2.44%   |
| Trust                                  | 1         | 1.22%   |
| Luxvisions Innotech Limited            | 1         | 1.22%   |
| GEMBIRD                                | 1         | 1.22%   |
| Aveo Technology                        | 1         | 1.22%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                         | 9         | 10.84%  |
| Chicony Integrated Camera                              | 8         | 9.64%   |
| Logitech Webcam C270                                   | 3         | 3.61%   |
| Lite-On Integrated Camera                              | 3         | 3.61%   |
| Chicony Integrated HP HD Webcam                        | 3         | 3.61%   |
| Bison Integrated Camera                                | 3         | 3.61%   |
| Sunplus Integrated_Webcam_HD                           | 2         | 2.41%   |
| Realtek USB 2.0 Webcam                                 | 2         | 2.41%   |
| Realtek Laptop Camera                                  | 2         | 2.41%   |
| Microdia USB Camera                                    | 2         | 2.41%   |
| Microdia Integrated Webcam                             | 2         | 2.41%   |
| Microdia HP Integrated Webcam                          | 2         | 2.41%   |
| Logitech C920 PRO HD Webcam                            | 2         | 2.41%   |
| Lite-On HP HD Camera                                   | 2         | 2.41%   |
| IMC Networks Realtek PC Camera                         | 2         | 2.41%   |
| Chicony ThinkPad T490 Webcam                           | 2         | 2.41%   |
| Bison HD Webcam                                        | 2         | 2.41%   |
| Apple FaceTime HD Camera (Built-in)                    | 2         | 2.41%   |
| Trust Canyon CNS-CWC6 Webcam                           | 1         | 1.2%    |
| Syntek Lenovo EasyCamera                               | 1         | 1.2%    |
| Syntek Integrated Camera                               | 1         | 1.2%    |
| Sunplus SPCA2650 AV Camera                             | 1         | 1.2%    |
| Sunplus Integrated_Webcam_FHD                          | 1         | 1.2%    |
| Shenzhen Kingcome Optoelectronic XiaoMi USB 2.0 Webcam | 1         | 1.2%    |
| Shenzhen Kingcome Optoelectronic 720p HD Camera        | 1         | 1.2%    |
| Realtek USB 2.0 PC Camera                              | 1         | 1.2%    |
| Realtek Integrated_Webcam_HD                           | 1         | 1.2%    |
| Realtek Integrated Webcam                              | 1         | 1.2%    |
| Realtek Composite Webcam                               | 1         | 1.2%    |
| Microdia USB 2.0 Camera                                | 1         | 1.2%    |
| Microdia Integrated_Webcam_FHD                         | 1         | 1.2%    |
| Microdia Dell Integrated HD Webcam                     | 1         | 1.2%    |
| Luxvisions Innotech Limited HP HD Camera               | 1         | 1.2%    |
| Logitech Webcam C170                                   | 1         | 1.2%    |
| Logitech HD Pro Webcam C920                            | 1         | 1.2%    |
| Logitech C505 HD Webcam                                | 1         | 1.2%    |
| Logitech BRIO Ultra HD Webcam                          | 1         | 1.2%    |
| IMC Networks EasyCamera                                | 1         | 1.2%    |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]      | 1         | 1.2%    |
| Chicony USB2.0 0.3M UVC WebCam                         | 1         | 1.2%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 11        | 40.74%  |
| Validity Sensors           | 5         | 18.52%  |
| Shenzhen Goodix Technology | 5         | 18.52%  |
| FocalTech Systems          | 4         | 14.81%  |
| Elan Microelectronics      | 1         | 3.7%    |
| AuthenTec                  | 1         | 3.7%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 7         | 25.93%  |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 14.81%  |
| FocalTech Systems Fingerprint Reader                                       | 3         | 11.11%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 7.41%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 7.41%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 7.41%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 7.41%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.7%    |
| Shenzhen Goodix Fingerprint Reader SGX                                     | 1         | 3.7%    |
| FocalTech Systems FocalTech Fingerprint Device                             | 1         | 3.7%    |
| Elan Fingerprint Sensor                                                    | 1         | 3.7%    |
| AuthenTec AES2810                                                          | 1         | 3.7%    |

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
| 0     | 45        | 28.3%   |
| 2     | 41        | 25.79%  |
| 1     | 33        | 20.75%  |
| 4     | 18        | 11.32%  |
| 3     | 17        | 10.69%  |
| 5     | 4         | 2.52%   |
| 9     | 1         | 0.63%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 80        | 37.04%  |
| Bluetooth                | 43        | 19.91%  |
| Net/wireless             | 34        | 15.74%  |
| Fingerprint reader       | 26        | 12.04%  |
| Card reader              | 13        | 6.02%   |
| Net/ethernet             | 6         | 2.78%   |
| Sound                    | 5         | 2.31%   |
| Network                  | 4         | 1.85%   |
| Firewire controller      | 3         | 1.39%   |
| Storage/raid             | 1         | 0.46%   |
| Modem                    | 1         | 0.46%   |

