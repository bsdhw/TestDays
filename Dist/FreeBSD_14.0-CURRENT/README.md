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

Total: 227

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
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
| amd64 | 115       | 81.56%  |
| arm64 | 22        | 15.6%   |
| arm   | 2         | 1.42%   |
| riscv | 1         | 0.71%   |
| i386  | 1         | 0.71%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 39        | 26.35%  |
| KDE5          | 37        | 25%     |
| XFCE          | 19        | 12.84%  |
| MATE          | 9         | 6.08%   |
| GNOME         | 8         | 5.41%   |
| TWM           | 7         | 4.73%   |
| i3            | 7         | 4.73%   |
| Openbox       | 3         | 2.03%   |
| LXQt          | 3         | 2.03%   |
| Cinnamon      | 3         | 2.03%   |
| LXDE          | 2         | 1.35%   |
| Lumina        | 2         | 1.35%   |
| Xfwm4         | 1         | 0.68%   |
| sway          | 1         | 0.68%   |
| spectrwm      | 1         | 0.68%   |
| Picom         | 1         | 0.68%   |
| GNUstep       | 1         | 0.68%   |
| Fluxbox       | 1         | 0.68%   |
| Enlightenment | 1         | 0.68%   |
| ctwm          | 1         | 0.68%   |
| Budgie        | 1         | 0.68%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 101       | 69.66%  |
| Console | 40        | 27.59%  |
| Wayland | 4         | 2.76%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 68        | 46.58%  |
| SDDM    | 34        | 23.29%  |
| SLiM    | 16        | 10.96%  |
| GDM     | 12        | 8.22%   |
| XDM     | 9         | 6.16%   |
| LightDM | 5         | 3.42%   |
| Ly      | 2         | 1.37%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang             | Computers | Percent |
|------------------|-----------|---------|
| C                | 90        | 62.94%  |
| en_US            | 22        | 15.38%  |
| Unknown          | 8         | 5.59%   |
| de_DE            | 5         | 3.5%    |
| uk_UA            | 3         | 2.1%    |
| ru_RU            | 3         | 2.1%    |
| zh_CN            | 2         | 1.4%    |
| fr_FR            | 2         | 1.4%    |
| en_GB            | 2         | 1.4%    |
| sv_SE            | 1         | 0.7%    |
| pt_PT            | 1         | 0.7%    |
| pl_PL            | 1         | 0.7%    |
| it_IT.ISO8859-15 | 1         | 0.7%    |
| en_CA            | 1         | 0.7%    |
| de_CH            | 1         | 0.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 126       | 89.36%  |
| BIOS | 15        | 10.64%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 101       | 71.63%  |
| Ufs  | 39        | 27.66%  |
| Nfs  | 1         | 0.71%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 132       | 93.62%  |
| MBR  | 9         | 6.38%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 29        | 20.57%  |
| Unknown                        | 19        | 13.48%  |
| ASUSTek Computer               | 16        | 11.35%  |
| Dell                           | 14        | 9.93%   |
| Hewlett-Packard                | 10        | 7.09%   |
| Gigabyte Technology            | 9         | 6.38%   |
| MSI                            | 6         | 4.26%   |
| ASRock                         | 5         | 3.55%   |
| Raspberry Pi Foundation        | 4         | 2.84%   |
| Apple                          | 3         | 2.13%   |
| Valve                          | 2         | 1.42%   |
| Intel                          | 2         | 1.42%   |
| Framework                      | 2         | 1.42%   |
| F-Plus Mobile                  | 2         | 1.42%   |
| Beckhoff Automation            | 2         | 1.42%   |
| Timi                           | 1         | 0.71%   |
| System76                       | 1         | 0.71%   |
| SolidRun                       | 1         | 0.71%   |
| Samsung Electronics            | 1         | 0.71%   |
| pine64                         | 1         | 0.71%   |
| Notebook                       | 1         | 0.71%   |
| Matsushita Electric Industrial | 1         | 0.71%   |
| khadas                         | 1         | 0.71%   |
| HUAWEI                         | 1         | 0.71%   |
| Google                         | 1         | 0.71%   |
| friendlyelec                   | 1         | 0.71%   |
| AZW                            | 1         | 0.71%   |
| Avell High Performance         | 1         | 0.71%   |
| ASRockRack                     | 1         | 0.71%   |
| Alienware                      | 1         | 0.71%   |
| A-DATA Technology              | 1         | 0.71%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 20        | 14.18%  |
| RPi Raspberry Pi                            | 3         | 2.13%   |
| HP EliteBook 8570p                          | 3         | 2.13%   |
| Valve Jupiter                               | 2         | 1.42%   |
| Framework Laptop                            | 2         | 1.42%   |
| F-Plus Mobile FLAPTOP r                     | 2         | 1.42%   |
| Timi Redmi Book Pro 14 2022                 | 1         | 0.71%   |
| System76 Gazelle                            | 1         | 0.71%   |
| SolidRun CEX7 Platform                      | 1         | 0.71%   |
| Samsung 750XEE                              | 1         | 0.71%   |
| RPi rpi                                     | 1         | 0.71%   |
| pine64 pinebook-pro-rk3399                  | 1         | 0.71%   |
| Notebook NS50_70MU                          | 1         | 0.71%   |
| MSI MS-7C79                                 | 1         | 0.71%   |
| MSI MS-7C75                                 | 1         | 0.71%   |
| MSI MS-7B89                                 | 1         | 0.71%   |
| MSI MS-7B86                                 | 1         | 0.71%   |
| MSI GE76 Raider 10UG                        | 1         | 0.71%   |
| MSI Bravo 15 A4DDR                          | 1         | 0.71%   |
| Matsushita Electric Industrial CF-T2BW1AXR  | 1         | 0.71%   |
| Lenovo XiaoXinPro-13ARE 2020 82DM           | 1         | 0.71%   |
| Lenovo ThinkPad X395 20NL001SMX             | 1         | 0.71%   |
| Lenovo ThinkPad X395 20NL000GPG             | 1         | 0.71%   |
| Lenovo ThinkPad X270 20HM004JBR             | 1         | 0.71%   |
| Lenovo ThinkPad X260 20F5A28AUK             | 1         | 0.71%   |
| Lenovo ThinkPad X13 Gen 1 20T2003PRT        | 1         | 0.71%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TLA055CD | 1         | 0.71%   |
| Lenovo ThinkPad X1 Extreme 20MF000BUS       | 1         | 0.71%   |
| Lenovo ThinkPad X1 Carbon 6th 20KHCTO1WW    | 1         | 0.71%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS1QC00    | 1         | 0.71%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS0BT00    | 1         | 0.71%   |
| Lenovo ThinkPad T495s 20QKS1812F            | 1         | 0.71%   |
| Lenovo ThinkPad T495 20NJ0010PB             | 1         | 0.71%   |
| Lenovo ThinkPad T470p 20J7S0PM00            | 1         | 0.71%   |
| Lenovo ThinkPad T430 2349H2G                | 1         | 0.71%   |
| Lenovo ThinkPad T15p Gen 3 21DA000QUS       | 1         | 0.71%   |
| Lenovo ThinkPad T14s Gen 2i 20WM00B7MX      | 1         | 0.71%   |
| Lenovo ThinkPad T14s Gen 1 20UH0019PB       | 1         | 0.71%   |
| Lenovo ThinkPad P15 Gen 1 20ST005VRT        | 1         | 0.71%   |
| Lenovo ThinkPad P14s Gen 1 20Y1CTO1WW       | 1         | 0.71%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo ThinkPad                            | 21        | 14.89%  |
| Unknown                                    | 20        | 14.18%  |
| ASUS PRIME                                 | 7         | 4.96%   |
| HP ProBook                                 | 4         | 2.84%   |
| HP EliteBook                               | 4         | 2.84%   |
| Dell Latitude                              | 4         | 2.84%   |
| RPi Raspberry                              | 3         | 2.13%   |
| Lenovo IdeaPad                             | 3         | 2.13%   |
| Dell OptiPlex                              | 3         | 2.13%   |
| ASUS ROG                                   | 3         | 2.13%   |
| Valve Jupiter                              | 2         | 1.42%   |
| Lenovo Legion                              | 2         | 1.42%   |
| Gigabyte X570                              | 2         | 1.42%   |
| Gigabyte B450M                             | 2         | 1.42%   |
| Framework Laptop                           | 2         | 1.42%   |
| F-Plus Mobile FLAPTOP                      | 2         | 1.42%   |
| Dell Inspiron                              | 2         | 1.42%   |
| Timi Redmi                                 | 1         | 0.71%   |
| System76 Gazelle                           | 1         | 0.71%   |
| SolidRun CEX7                              | 1         | 0.71%   |
| Samsung 750XEE                             | 1         | 0.71%   |
| RPi rpi                                    | 1         | 0.71%   |
| pine64 pinebook-pro-rk3399                 | 1         | 0.71%   |
| Notebook NS50                              | 1         | 0.71%   |
| MSI MS-7C79                                | 1         | 0.71%   |
| MSI MS-7C75                                | 1         | 0.71%   |
| MSI MS-7B89                                | 1         | 0.71%   |
| MSI MS-7B86                                | 1         | 0.71%   |
| MSI GE76                                   | 1         | 0.71%   |
| MSI Bravo                                  | 1         | 0.71%   |
| Matsushita Electric Industrial CF-T2BW1AXR | 1         | 0.71%   |
| Lenovo XiaoXinPro-13ARE                    | 1         | 0.71%   |
| Lenovo ThinkBook                           | 1         | 0.71%   |
| khadas edge-v                              | 1         | 0.71%   |
| Intel S2600WTTR                            | 1         | 0.71%   |
| Intel NUC11PHi7                            | 1         | 0.71%   |
| HUAWEI HN-WX9X                             | 1         | 0.71%   |
| HP ZBook                                   | 1         | 0.71%   |
| HP EliteDesk                               | 1         | 0.71%   |
| Google Akemi                               | 1         | 0.71%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 33        | 23.4%   |
| 2020    | 30        | 21.28%  |
| Unknown | 18        | 12.77%  |
| 2022    | 16        | 11.35%  |
| 2019    | 15        | 10.64%  |
| 2018    | 7         | 4.96%   |
| 2017    | 5         | 3.55%   |
| 2023    | 4         | 2.84%   |
| 2013    | 4         | 2.84%   |
| 2015    | 3         | 2.13%   |
| 2016    | 2         | 1.42%   |
| 2014    | 1         | 0.71%   |
| 2012    | 1         | 0.71%   |
| 2011    | 1         | 0.71%   |
| 2003    | 1         | 0.71%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 72        | 51.06%  |
| Desktop        | 56        | 39.72%  |
| System on chip | 7         | 4.96%   |
| Mini pc        | 3         | 2.13%   |
| Server         | 2         | 1.42%   |
| All in one     | 1         | 0.71%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 139       | 98.58%  |
| Yes  | 2         | 1.42%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 51        | 35.66%  |
| 8.01-16.0       | 25        | 17.48%  |
| 32.01-64.0      | 23        | 16.08%  |
| 64.01-256.0     | 21        | 14.69%  |
| 4.01-8.0        | 9         | 6.29%   |
| 3.01-4.0        | 8         | 5.59%   |
| 0.51-1.0        | 2         | 1.4%    |
| More than 256.0 | 1         | 0.7%    |
| 24.01-32.0      | 1         | 0.7%    |
| 1.01-2.0        | 1         | 0.7%    |
| 0.01-0.5        | 1         | 0.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.51-1.0    | 43        | 29.86%  |
| 1.01-2.0    | 42        | 29.17%  |
| 0.01-0.5    | 28        | 19.44%  |
| 2.01-3.0    | 15        | 10.42%  |
| 3.01-4.0    | 6         | 4.17%   |
| 4.01-8.0    | 2         | 1.39%   |
| 24.01-32.0  | 2         | 1.39%   |
| 0           | 2         | 1.39%   |
| 32.01-64.0  | 1         | 0.69%   |
| 64.01-256.0 | 1         | 0.69%   |
| 16.01-24.0  | 1         | 0.69%   |
| 8.01-16.0   | 1         | 0.69%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 69        | 46.62%  |
| 2      | 35        | 23.65%  |
| 0      | 21        | 14.19%  |
| 3      | 10        | 6.76%   |
| 6      | 5         | 3.38%   |
| 4      | 5         | 3.38%   |
| 15     | 1         | 0.68%   |
| 7      | 1         | 0.68%   |
| 5      | 1         | 0.68%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 124       | 86.71%  |
| Yes       | 19        | 13.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 108       | 76.6%   |
| No        | 33        | 23.4%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 95        | 67.38%  |
| No        | 46        | 32.62%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 52.11%  |
| No        | 68        | 47.89%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 24        | 17.02%  |
| Russia       | 23        | 16.31%  |
| Germany      | 15        | 10.64%  |
| UK           | 13        | 9.22%   |
| Poland       | 7         | 4.96%   |
| Brazil       | 6         | 4.26%   |
| Ukraine      | 5         | 3.55%   |
| Japan        | 4         | 2.84%   |
| China        | 4         | 2.84%   |
| Canada       | 4         | 2.84%   |
| Austria      | 4         | 2.84%   |
| Portugal     | 3         | 2.13%   |
| France       | 3         | 2.13%   |
| Turkey       | 2         | 1.42%   |
| Switzerland  | 2         | 1.42%   |
| Sweden       | 2         | 1.42%   |
| Romania      | 2         | 1.42%   |
| Netherlands  | 2         | 1.42%   |
| Denmark      | 2         | 1.42%   |
| Taiwan       | 1         | 0.71%   |
| Spain        | 1         | 0.71%   |
| Singapore    | 1         | 0.71%   |
| Saudi Arabia | 1         | 0.71%   |
| Peru         | 1         | 0.71%   |
| Jordan       | 1         | 0.71%   |
| Jamaica      | 1         | 0.71%   |
| Italy        | 1         | 0.71%   |
| India        | 1         | 0.71%   |
| Czechia      | 1         | 0.71%   |
| Croatia      | 1         | 0.71%   |
| Colombia     | 1         | 0.71%   |
| Belarus      | 1         | 0.71%   |
| Bangladesh   | 1         | 0.71%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Moscow                      | 9         | 5.7%    |
| Krasnodar                   | 7         | 4.43%   |
| Brighton                    | 5         | 3.16%   |
| St Petersburg               | 4         | 2.53%   |
| Seattle                     | 4         | 2.53%   |
| Vienna                      | 3         | 1.9%    |
| London                      | 3         | 1.9%    |
| Kyiv                        | 3         | 1.9%    |
| ЕЊta-ku                   | 2         | 1.27%   |
| Zurich                      | 2         | 1.27%   |
| Warsaw                      | 2         | 1.27%   |
| Vancouver                   | 2         | 1.27%   |
| Shoreham-by-Sea             | 2         | 1.27%   |
| Rio de Janeiro              | 2         | 1.27%   |
| Rietberg                    | 2         | 1.27%   |
| Northeim                    | 2         | 1.27%   |
| Istanbul                    | 2         | 1.27%   |
| Graz                        | 2         | 1.27%   |
| Fuchu                       | 2         | 1.27%   |
| Fremont                     | 2         | 1.27%   |
| Egham                       | 2         | 1.27%   |
| Chicago                     | 2         | 1.27%   |
| Cambridge                   | 2         | 1.27%   |
| Berlin                      | 2         | 1.27%   |
| Albuquerque                 | 2         | 1.27%   |
| Zaporizhzhya                | 1         | 0.63%   |
| Wuhan                       | 1         | 0.63%   |
| Woodburn                    | 1         | 0.63%   |
| Wieliczka                   | 1         | 0.63%   |
| Washington                  | 1         | 0.63%   |
| Voznesensk                  | 1         | 0.63%   |
| Vila Real de Santo António | 1         | 0.63%   |
| Tynda                       | 1         | 0.63%   |
| Trosa                       | 1         | 0.63%   |
| Toronto                     | 1         | 0.63%   |
| Thrissur                    | 1         | 0.63%   |
| Teaneck                     | 1         | 0.63%   |
| Taipei                      | 1         | 0.63%   |
| Stuttgart                   | 1         | 0.63%   |
| Stolberg                    | 1         | 0.63%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 40        | 60     | 22.35%  |
| WDC                 | 30        | 49     | 16.76%  |
| Toshiba             | 16        | 29     | 8.94%   |
| Seagate             | 14        | 30     | 7.82%   |
| Crucial             | 13        | 23     | 7.26%   |
| Kingston            | 8         | 11     | 4.47%   |
| HGST                | 8         | 29     | 4.47%   |
| Intel               | 7         | 10     | 3.91%   |
| KIOXIA              | 6         | 6      | 3.35%   |
| A-DATA Technology   | 6         | 6      | 3.35%   |
| SK hynix            | 5         | 5      | 2.79%   |
| Micron Technology   | 5         | 6      | 2.79%   |
| FORESEE             | 3         | 3      | 1.68%   |
| Apple               | 3         | 3      | 1.68%   |
| SSSTC               | 2         | 2      | 1.12%   |
| UMIS                | 1         | 1      | 0.56%   |
| SPCC                | 1         | 1      | 0.56%   |
| Solid State Storage | 1         | 1      | 0.56%   |
| Silicon Motion      | 1         | 1      | 0.56%   |
| SanDisk             | 1         | 2      | 0.56%   |
| PNY                 | 1         | 1      | 0.56%   |
| Mushkin             | 1         | 1      | 0.56%   |
| LSI                 | 1         | 4      | 0.56%   |
| LITEON              | 1         | 1      | 0.56%   |
| Hitachi             | 1         | 2      | 0.56%   |
| GOODRAM             | 1         | 1      | 0.56%   |
| Fujitsu             | 1         | 2      | 0.56%   |
| Apacer              | 1         | 1      | 0.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB             | 6         | 3.03%   |
| Toshiba MQ04ABF100 1TB               | 4         | 2.02%   |
| HGST HTS725050A7E630 500GB           | 4         | 2.02%   |
| HGST HTS721010A9E630 1TB             | 4         | 2.02%   |
| WDC WDS100T3X0C-00SJG0 1TB           | 3         | 1.52%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 3         | 1.52%   |
| Samsung SSD 980 PRO 1TB              | 3         | 1.52%   |
| Samsung SSD 970 EVO Plus 1TB         | 3         | 1.52%   |
| Samsung SSD 870 EVO 1TB              | 3         | 1.52%   |
| Samsung SSD 860 EVO 250GB            | 3         | 1.52%   |
| Samsung HM251JX 250GB                | 3         | 1.52%   |
| WDC WDS100T1X0E-00AFY0 1TB           | 2         | 1.01%   |
| WDC WD30EFRX-68EUZN0 3TB             | 2         | 1.01%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB   | 2         | 1.01%   |
| WDC PC SN730 NVMe 1024GB             | 2         | 1.01%   |
| Seagate ST1000LM049-2GH172 1TB       | 2         | 1.01%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 1.01%   |
| Samsung SSD 980 1TB                  | 2         | 1.01%   |
| Samsung SSD 970 EVO Plus 500GB       | 2         | 1.01%   |
| Samsung SSD 850 EVO 250GB            | 2         | 1.01%   |
| Samsung MZVLB512HBJQ-000L7 512GB     | 2         | 1.01%   |
| Samsung MZVLB1T0HBLR-000L2 1TB       | 2         | 1.01%   |
| KIOXIA KBG40ZNS512G NVMe 512GB       | 2         | 1.01%   |
| KIOXIA KBG40ZNS256G NVMe 256GB       | 2         | 1.01%   |
| Kingston SA2000M81000G 1TB           | 2         | 1.01%   |
| FORESEE XP1000F001T 1TB              | 2         | 1.01%   |
| Crucial CT750MX300SSD1 752GB         | 2         | 1.01%   |
| Crucial CT500P2SSD8 500GB            | 2         | 1.01%   |
| Apple SSD SM256E 256GB               | 2         | 1.01%   |
| WDC WDS500G1X0E-00AFY0 500GB         | 1         | 0.51%   |
| WDC WDS250G2B0C-00PXH0 250GB         | 1         | 0.51%   |
| WDC WDS100T2B0A-00SM50 1TB           | 1         | 0.51%   |
| WDC WD60EFRX-68TGBN1 6TB             | 1         | 0.51%   |
| WDC WD5002ABYS-18B1B0 500GB          | 1         | 0.51%   |
| WDC WD40EZRZ-75GXCB0 4TB             | 1         | 0.51%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 1         | 0.51%   |
| WDC WD20EFRX-68AX9N0 2TB             | 1         | 0.51%   |
| WDC WD120EFAX-68UNTN0 12TB           | 1         | 0.51%   |
| WDC WD10SPZX-60Z10T0 1TB             | 1         | 0.51%   |
| WDC WD10SPZX-21Z10T0 1TB             | 1         | 0.51%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 14        | 26     | 24.56%  |
| Seagate             | 14        | 30     | 24.56%  |
| WDC                 | 13        | 19     | 22.81%  |
| HGST                | 8         | 29     | 14.04%  |
| Samsung Electronics | 5         | 9      | 8.77%   |
| LSI                 | 1         | 4      | 1.75%   |
| Hitachi             | 1         | 2      | 1.75%   |
| Fujitsu             | 1         | 2      | 1.75%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 18     | 30.95%  |
| Crucial             | 8         | 13     | 19.05%  |
| Kingston            | 4         | 6      | 9.52%   |
| A-DATA Technology   | 4         | 4      | 9.52%   |
| Intel               | 3         | 6      | 7.14%   |
| Apple               | 3         | 3      | 7.14%   |
| WDC                 | 1         | 2      | 2.38%   |
| SK hynix            | 1         | 1      | 2.38%   |
| SanDisk             | 1         | 2      | 2.38%   |
| Micron Technology   | 1         | 1      | 2.38%   |
| LITEON              | 1         | 1      | 2.38%   |
| GOODRAM             | 1         | 1      | 2.38%   |
| Apacer              | 1         | 1      | 2.38%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 77        | 111    | 48.43%  |
| SSD  | 41        | 59     | 25.79%  |
| HDD  | 41        | 121    | 25.79%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 77        | 111    | 52.74%  |
| SATA | 69        | 180    | 47.26%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 40        | 75     | 43.96%  |
| 0.51-1.0   | 29        | 55     | 31.87%  |
| 1.01-2.0   | 8         | 11     | 8.79%   |
| 4.01-10.0  | 5         | 24     | 5.49%   |
| 3.01-4.0   | 3         | 4      | 3.3%    |
| 2.01-3.0   | 3         | 4      | 3.3%    |
| 10.01-20.0 | 2         | 3      | 2.2%    |
| 20.01-50.0 | 1         | 4      | 1.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 38        | 25.68%  |
| 251-500        | 36        | 24.32%  |
| 501-1000       | 25        | 16.89%  |
| 21-50          | 12        | 8.11%   |
| 1-20           | 12        | 8.11%   |
| 51-100         | 11        | 7.43%   |
| 1001-2000      | 7         | 4.73%   |
| 2001-3000      | 4         | 2.7%    |
| More than 3000 | 3         | 2.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 93        | 62.84%  |
| 21-50          | 36        | 24.32%  |
| 101-250        | 8         | 5.41%   |
| 251-500        | 3         | 2.03%   |
| 1001-2000      | 2         | 1.35%   |
| 501-1000       | 2         | 1.35%   |
| 51-100         | 2         | 1.35%   |
| More than 3000 | 1         | 0.68%   |
| 0              | 1         | 0.68%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                     | Computers | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| HGST HTS725050A7E630 500GB                | 4         | 7      | 21.05%  |
| Samsung Electronics SSD 870 EVO 1TB       | 3         | 5      | 15.79%  |
| WDC WD60EFRX-68TGBN1 6TB                  | 1         | 3      | 5.26%   |
| WDC WD5002ABYS-18B1B0 500GB               | 1         | 1      | 5.26%   |
| WDC WD10SPZX-60Z10T0 1TB                  | 1         | 1      | 5.26%   |
| Seagate ST1000DM003-1CH162 1TB            | 1         | 1      | 5.26%   |
| Samsung Electronics SSD PM851 mSATA 256GB | 1         | 1      | 5.26%   |
| Samsung Electronics HM251JX 250GB         | 1         | 1      | 5.26%   |
| Samsung Electronics HD154UI 1.5TB         | 1         | 2      | 5.26%   |
| Kingston SHPM2280P2H-240G                 | 1         | 1      | 5.26%   |
| Kingston SA400S37120G 120GB               | 1         | 1      | 5.26%   |
| Hitachi HUA722020ALA331 2TB               | 1         | 2      | 5.26%   |
| HGST HTS721010A9E630 1TB                  | 1         | 16     | 5.26%   |
| Fujitsu MHS2040AT D 40GB                  | 1         | 2      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 9      | 33.33%  |
| HGST                | 4         | 23     | 22.22%  |
| WDC                 | 3         | 5      | 16.67%  |
| Kingston            | 2         | 2      | 11.11%  |
| Seagate             | 1         | 1      | 5.56%   |
| Hitachi             | 1         | 2      | 5.56%   |
| Fujitsu             | 1         | 2      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 4         | 23     | 33.33%  |
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
| HDD  | 11        | 36     | 68.75%  |
| SSD  | 5         | 8      | 31.25%  |

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
| Works    | 115       | 237    | 85.19%  |
| Malfunc  | 15        | 44     | 11.11%  |
| Detected | 5         | 10     | 3.7%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 55        | 29.41%  |
| AMD                                     | 34        | 18.18%  |
| Samsung Electronics                     | 28        | 14.97%  |
| SanDisk                                 | 19        | 10.16%  |
| Silicon Motion                          | 8         | 4.28%   |
| Kingston Technology Company             | 6         | 3.21%   |
| Micron/Crucial Technology               | 5         | 2.67%   |
| Micron Technology                       | 5         | 2.67%   |
| KIOXIA                                  | 5         | 2.67%   |
| SK hynix                                | 4         | 2.14%   |
| Toshiba                                 | 3         | 1.6%    |
| Solid State Storage Technology          | 3         | 1.6%    |
| Shenzhen Longsys Electronics            | 2         | 1.07%   |
| Marvell Technology Group                | 2         | 1.07%   |
| Broadcom / LSI                          | 2         | 1.07%   |
| ASMedia Technology                      | 2         | 1.07%   |
| ADATA Technology                        | 2         | 1.07%   |
| Shenzhen Unionmemory Information System | 1         | 0.53%   |
| Phison Electronics                      | 1         | 0.53%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 25        | 12.2%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 18        | 8.78%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 11        | 5.37%   |
| Intel Comet Lake SATA AHCI Controller                                          | 9         | 4.39%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 8         | 3.9%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 3.41%   |
| AMD 400 Series Chipset SATA Controller                                         | 7         | 3.41%   |
| Samsung NVMe SSD Controller 980                                                | 6         | 2.93%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 6         | 2.93%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 6         | 2.93%   |
| Unknown                                                                        | 6         | 2.93%   |
| AMD 500 Series Chipset SATA Controller                                         | 5         | 2.44%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 1.95%   |
| Micron NVMe Storage Controller                                                 | 4         | 1.95%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 4         | 1.95%   |
| Solid State Storage CL1                                                        | 3         | 1.46%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 3         | 1.46%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 3         | 1.46%   |
| Kingston Company A2000 NVMe SSD                                                | 3         | 1.46%   |
| Toshiba XG6 NVMe SSD Controller                                                | 2         | 0.98%   |
| SK hynix BC511                                                                 | 2         | 0.98%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 0.98%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 0.98%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 0.98%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 0.98%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 2         | 0.98%   |
| Intel SSD 660P Series                                                          | 2         | 0.98%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 0.98%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 0.98%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 0.98%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 0.98%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 0.98%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 2         | 0.98%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 2         | 0.98%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 0.98%   |
| Toshiba XG4 NVMe SSD Controller                                                | 1         | 0.49%   |
| SK hynix Platinum P41 NVMe Solid State Drive 2TB                               | 1         | 0.49%   |
| SK hynix PC300 NVMe Solid State Drive 512GB                                    | 1         | 0.49%   |
| SanDisk NVMe Controller                                                        | 1         | 0.49%   |
| Samsung SM951 AHCI                                                             | 1         | 0.49%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 89        | 49.72%  |
| SATA | 80        | 44.69%  |
| RAID | 5         | 2.79%   |
| IDE  | 4         | 2.23%   |
| SAS  | 1         | 0.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 68        | 47.55%  |
| AMD      | 49        | 34.27%  |
| ARM      | 16        | 11.19%  |
| Unknown  | 8         | 5.59%   |
| Research | 1         | 0.7%    |
| NXP      | 1         | 0.7%    |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
|                                                 | 8         | 5.59%   |
| ARM Cortex-A55 r2p0                             | 7         | 4.9%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 6         | 4.2%    |
| Intel Core i5-10210U CPU @ 1.60GHz              | 5         | 3.5%    |
| Intel Core i7-3520M CPU @ 2.90GHz               | 4         | 2.8%    |
| ARM Cortex-A72 r0p3                             | 4         | 2.8%    |
| AMD Ryzen 5 5600G with Radeon Graphics          | 4         | 2.8%    |
| Intel Core i7-10750H CPU @ 2.60GHz              | 3         | 2.1%    |
| Intel Core i5-10300H CPU @ 2.50GHz              | 3         | 2.1%    |
| Intel Core i7-8750H CPU @ 2.20GHz               | 2         | 1.4%    |
| Intel Core i7-7600U CPU @ 2.80GHz               | 2         | 1.4%    |
| Intel Core i5-10500T CPU @ 2.30GHz              | 2         | 1.4%    |
| Intel Core i5-10400 CPU @ 2.90GHz               | 2         | 1.4%    |
| ARM Cortex-A72 r0p2                             | 2         | 1.4%    |
| ARM Cortex-A53 r0p4                             | 2         | 1.4%    |
| AMD Ryzen 9 7950X 16-Core Processor             | 2         | 1.4%    |
| AMD Ryzen 9 5950X 16-Core Processor             | 2         | 1.4%    |
| AMD Ryzen 9 3900X 12-Core Processor             | 2         | 1.4%    |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx | 2         | 1.4%    |
| AMD Ryzen 7 5825U with Radeon Graphics          | 2         | 1.4%    |
| AMD Ryzen 7 4800U with Radeon Graphics          | 2         | 1.4%    |
| AMD Ryzen 7 4800H with Radeon Graphics          | 2         | 1.4%    |
| AMD Ryzen 7 4700U with Radeon Graphics          | 2         | 1.4%    |
| AMD Ryzen 5 PRO 3500U w/ Radeon Vega Mobile Gfx | 2         | 1.4%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 2         | 1.4%    |
| AMD Custom APU 0405                             | 2         | 1.4%    |
| Research Morello SoC r0p0                       | 1         | 0.7%    |
| NXP Cortex-A72                                  | 1         | 0.7%    |
| Intel Xeon W-10885M CPU @ 2.40GHz               | 1         | 0.7%    |
| Intel Xeon E-2334 CPU @ 3.40GHz                 | 1         | 0.7%    |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz             | 1         | 0.7%    |
| Intel Pentium M processor 1000MHz               | 1         | 0.7%    |
| Intel Core i7-9850H CPU @ 2.60GHz               | 1         | 0.7%    |
| Intel Core i7-9750H CPU @ 2.60GHz               | 1         | 0.7%    |
| Intel Core i7-8700 CPU @ 3.20GHz                | 1         | 0.7%    |
| Intel Core i7-8650U CPU @ 1.90GHz               | 1         | 0.7%    |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 0.7%    |
| Intel Core i7-7820HK CPU @ 2.90GHz              | 1         | 0.7%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 0.7%    |
| Intel Core i7-6700 CPU @ 3.40GHz                | 1         | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 31        | 21.83%  |
| Other                  | 26        | 18.31%  |
| Intel Core i5          | 17        | 11.97%  |
| ARM Cortex             | 15        | 10.56%  |
| AMD Ryzen 7            | 13        | 9.15%   |
| AMD Ryzen 5            | 13        | 9.15%   |
| AMD Ryzen 9            | 8         | 5.63%   |
| Intel Xeon             | 3         | 2.11%   |
| AMD Ryzen 7 PRO        | 3         | 2.11%   |
| AMD Ryzen 5 PRO        | 3         | 2.11%   |
| Intel Pentium M        | 1         | 0.7%    |
| Intel Core i3          | 1         | 0.7%    |
| Intel Atom             | 1         | 0.7%    |
| AMD Ryzen Threadripper | 1         | 0.7%    |
| AMD Ryzen Embedded     | 1         | 0.7%    |
| AMD Ryzen 3            | 1         | 0.7%    |
| AMD FX                 | 1         | 0.7%    |
| AMD EPYC               | 1         | 0.7%    |
| AMD E                  | 1         | 0.7%    |
| AMD Athlon             | 1         | 0.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 30        | 21.13%  |
| Unknown | 25        | 17.61%  |
| 8       | 20        | 14.08%  |
| 2       | 17        | 11.97%  |
| 6       | 14        | 9.86%   |
| 16      | 13        | 9.15%   |
| 12      | 11        | 7.75%   |
| 32      | 6         | 4.23%   |
| 24      | 3         | 2.11%   |
| 64      | 1         | 0.7%    |
| 10      | 1         | 0.7%    |
| 1       | 1         | 0.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 121       | 85.21%  |
| Unknown | 20        | 14.08%  |
| 2       | 1         | 0.7%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 65        | 45.77%  |
| 1       | 51        | 35.92%  |
| Unknown | 26        | 18.31%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 40        | 28.17%  |
| KabyLake   | 19        | 13.38%  |
| CometLake  | 14        | 9.86%   |
| Zen 2      | 13        | 9.15%   |
| Zen 3      | 11        | 7.75%   |
| Zen+       | 10        | 7.04%   |
| IvyBridge  | 9         | 6.34%   |
| TigerLake  | 8         | 5.63%   |
| Zen        | 5         | 3.52%   |
| Haswell    | 3         | 2.11%   |
| Broadwell  | 3         | 2.11%   |
| Skylake    | 2         | 1.41%   |
| Silvermont | 1         | 0.7%    |
| Piledriver | 1         | 0.7%    |
| P6         | 1         | 0.7%    |
| IceLake    | 1         | 0.7%    |
| Bobcat     | 1         | 0.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 56        | 38.1%   |
| AMD                        | 47        | 31.97%  |
| Nvidia                     | 41        | 27.89%  |
| Matrox Electronics Systems | 2         | 1.36%   |
| ASPEED Technology          | 1         | 0.68%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                           | 10        | 6.67%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                            | 8         | 5.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series] | 7         | 4.67%   |
| Intel CometLake-U GT2 [UHD Graphics]                                 | 6         | 4%      |
| Intel CometLake-H GT2 [UHD Graphics]                                 | 5         | 3.33%   |
| Intel 3rd Gen Core processor Graphics Controller                     | 5         | 3.33%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]         | 5         | 3.33%   |
| Nvidia TU117M                                                        | 4         | 2.67%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                            | 4         | 2.67%   |
| Intel HD Graphics 620                                                | 3         | 2%      |
| Intel CometLake-S GT2 [UHD Graphics 630]                             | 3         | 2%      |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                             | 3         | 2%      |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]     | 3         | 2%      |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                           | 2         | 1.33%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                           | 2         | 1.33%   |
| Nvidia GP108M [GeForce MX230]                                        | 2         | 1.33%   |
| Nvidia GP108 [GeForce GT 1030]                                       | 2         | 1.33%   |
| Nvidia GK208B [GeForce GT 710]                                       | 2         | 1.33%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                 | 2         | 1.33%   |
| Intel HD Graphics 630                                                | 2         | 1.33%   |
| Intel Alder Lake-P Integrated Graphics Controller                    | 2         | 1.33%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller          | 2         | 1.33%   |
| AMD VanGogh [AMD Custom GPU 0405]                                    | 2         | 1.33%   |
| AMD Rembrandt [Radeon 680M]                                          | 2         | 1.33%   |
| AMD Raphael                                                          | 2         | 1.33%   |
| AMD Lucienne                                                         | 2         | 1.33%   |
| AMD Barcelo                                                          | 2         | 1.33%   |
| Nvidia TU117M [GeForce MX450]                                        | 1         | 0.67%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                | 1         | 0.67%   |
| Nvidia TU117 [GeForce GTX 1650]                                      | 1         | 0.67%   |
| Nvidia TU116 [GeForce GTX 1660]                                      | 1         | 0.67%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                              | 1         | 0.67%   |
| Nvidia TU104GLM [Quadro RTX 5000 Mobile / Max-Q]                     | 1         | 0.67%   |
| Nvidia GT218 [GeForce 210]                                           | 1         | 0.67%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                           | 1         | 0.67%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                              | 1         | 0.67%   |
| Nvidia GP107GL [Quadro P620]                                         | 1         | 0.67%   |
| Nvidia GP107 [GeForce GTX 1050]                                      | 1         | 0.67%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                   | 1         | 0.67%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                  | 1         | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x AMD                  | 39        | 27.27%  |
| 1 x Intel                | 31        | 21.68%  |
| Other                    | 24        | 16.78%  |
| Intel + Nvidia           | 22        | 15.38%  |
| 1 x Nvidia               | 17        | 11.89%  |
| 2 x AMD                  | 3         | 2.1%    |
| 1 x Matrox               | 2         | 1.4%    |
| AMD + Nvidia             | 2         | 1.4%    |
| Intel + AMD + 1 x Nvidia | 1         | 0.7%    |
| Intel + AMD              | 1         | 0.7%    |
| 1 x ASPEED               | 1         | 0.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 90        | 63.83%  |
| Proprietary | 27        | 19.15%  |
| Unknown     | 24        | 17.02%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 100       | 69.44%  |
| 1.01-2.0   | 11        | 7.64%   |
| 0.51-1.0   | 8         | 5.56%   |
| 0.01-0.5   | 8         | 5.56%   |
| 3.01-4.0   | 6         | 4.17%   |
| 7.01-8.0   | 5         | 3.47%   |
| 5.01-6.0   | 3         | 2.08%   |
| 8.01-16.0  | 2         | 1.39%   |
| 2.01-3.0   | 1         | 0.69%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| BOE                 | 15        | 15.79%  |
| AU Optronics        | 12        | 12.63%  |
| LG Display          | 10        | 10.53%  |
| Dell                | 7         | 7.37%   |
| Hewlett-Packard     | 5         | 5.26%   |
| Goldstar            | 5         | 5.26%   |
| Chimei Innolux      | 5         | 5.26%   |
| Philips             | 4         | 4.21%   |
| Samsung Electronics | 3         | 3.16%   |
| LG Electronics      | 3         | 3.16%   |
| Sony                | 2         | 2.11%   |
| Sharp               | 2         | 2.11%   |
| RTK                 | 2         | 2.11%   |
| Lenovo              | 2         | 2.11%   |
| InfoVision          | 2         | 2.11%   |
| BenQ                | 2         | 2.11%   |
| Apple               | 2         | 2.11%   |
| ViewSonic           | 1         | 1.05%   |
| SDC                 | 1         | 1.05%   |
| PANDA               | 1         | 1.05%   |
| LGD                 | 1         | 1.05%   |
| Iiyama              | 1         | 1.05%   |
| Idek Iiyama         | 1         | 1.05%   |
| HKC                 | 1         | 1.05%   |
| HJW                 | 1         | 1.05%   |
| Eizo                | 1         | 1.05%   |
| CSO                 | 1         | 1.05%   |
| AOC                 | 1         | 1.05%   |
| Unknown             | 1         | 1.05%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0258 1600x900 350x190mm 15.7-inch            | 3         | 3.09%   |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                  | 3         | 3.09%   |
| RTK WCS Display RTK1A1B 1920x1080 344x195mm 15.6-inch                  | 2         | 2.06%   |
| Philips 271P4 PHL08C3 1920x1080 600x340mm 27.2-inch                    | 2         | 2.06%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch           | 2         | 2.06%   |
| ViewSonic VG2439 Series VSCD22B 1920x1080 520x290mm 23.4-inch          | 1         | 1.03%   |
| Sony TV SNY4B03 1920x1080 930x520mm 41.9-inch                          | 1         | 1.03%   |
| Sony TV  *30 SNY05D1 3840x2160 1660x930mm 74.9-inch                    | 1         | 1.03%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 380x210mm 17.1-inch                | 1         | 1.03%   |
| Sharp LCD Monitor SHP14B9 3840x2160 340x190mm 15.3-inch                | 1         | 1.03%   |
| SDC LCD Monitor 3520x1080                                              | 1         | 1.03%   |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                       | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SDC3754 1600x900 380x210mm 17.1-inch   | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1020x570mm 46.0-inch | 1         | 1.03%   |
| Philips PHL 273V7 PHLC156 1920x1080 600x340mm 27.2-inch                | 1         | 1.03%   |
| Philips LCD Monitor 271P4 3520x1080                                    | 1         | 1.03%   |
| Philips LCD Monitor 271P4                                              | 1         | 1.03%   |
| PANDA LCD Monitor NCP004F 1920x1080 310x170mm 13.9-inch                | 1         | 1.03%   |
| LGD LCD Monitor 1920x1080                                              | 1         | 1.03%   |
| LG Electronics LCD Monitor LX20D 1600x1200                             | 1         | 1.03%   |
| LG Electronics LCD Monitor LG Ultra HD 11520x2160                      | 1         | 1.03%   |
| LG Electronics LCD Monitor LG Ultra HD                                 | 1         | 1.03%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                        | 1         | 1.03%   |
| LG Display LCD Monitor LGD062E 1920x1080 340x190mm 15.3-inch           | 1         | 1.03%   |
| LG Display LCD Monitor LGD060A 1920x1080 290x170mm 13.2-inch           | 1         | 1.03%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch           | 1         | 1.03%   |
| LG Display LCD Monitor LGD05F1 1920x1080 310x170mm 13.9-inch           | 1         | 1.03%   |
| LG Display LCD Monitor LGD033E 1366x768 310x170mm 13.9-inch            | 1         | 1.03%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                  | 1         | 1.03%   |
| Lenovo LEN P44w-10 LEN61D5 3840x1200 1050x330mm 43.3-inch              | 1         | 1.03%   |
| InfoVision LCD Monitor IVO8544 1920x1080 290x170mm 13.2-inch           | 1         | 1.03%   |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch           | 1         | 1.03%   |
| Iiyama PL2474H IVM6146 1920x1080 520x290mm 23.4-inch                   | 1         | 1.03%   |
| Idek Iiyama LCD Monitor PL2792UH 3840x2160                             | 1         | 1.03%   |
| HKC LCD Monitor HKC3D05 1920x1080 340x190mm 15.3-inch                  | 1         | 1.03%   |
| HJW HDMI TO USB HJW0001 1920x1080 700x390mm 31.5-inch                  | 1         | 1.03%   |
| Hewlett-Packard LCD Monitor LA2306 3520x1080                           | 1         | 1.03%   |
| Hewlett-Packard LA2405x HWP301F 1920x1200 520x320mm 24.0-inch          | 1         | 1.03%   |
| Hewlett-Packard LA2306 HWP2949 1920x1080 510x290mm 23.1-inch           | 1         | 1.03%   |
| Hewlett-Packard E242 HWP326E 1920x1200 520x320mm 24.0-inch             | 1         | 1.03%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 53        | 55.79%  |
| 3840x2160 (4K)    | 10        | 10.53%  |
| 1600x900 (HD+)    | 6         | 6.32%   |
| 2560x1440 (QHD)   | 5         | 5.26%   |
| 1920x1200 (WUXGA) | 5         | 5.26%   |
| 2256x1504         | 3         | 3.16%   |
| 1366x768 (WXGA)   | 3         | 3.16%   |
| 2560x1600         | 2         | 2.11%   |
| Unknown           | 2         | 2.11%   |
| 4480x1440         | 1         | 1.05%   |
| 3840x1200         | 1         | 1.05%   |
| 3520x1080         | 1         | 1.05%   |
| 2160x1440         | 1         | 1.05%   |
| 1600x1200         | 1         | 1.05%   |
| 11520x2160        | 1         | 1.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 26        | 27.96%  |
| 15      | 20        | 21.51%  |
| Unknown | 11        | 11.83%  |
| 27      | 9         | 9.68%   |
| 24      | 7         | 7.53%   |
| 23      | 6         | 6.45%   |
| 17      | 3         | 3.23%   |
| 12      | 3         | 3.23%   |
| 74      | 1         | 1.08%   |
| 46      | 1         | 1.08%   |
| 43      | 1         | 1.08%   |
| 41      | 1         | 1.08%   |
| 32      | 1         | 1.08%   |
| 31      | 1         | 1.08%   |
| 22      | 1         | 1.08%   |
| 21      | 1         | 1.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 36        | 39.13%  |
| 501-600     | 20        | 21.74%  |
| 201-300     | 13        | 14.13%  |
| Unknown     | 11        | 11.96%  |
| 351-400     | 3         | 3.26%   |
| 601-700     | 2         | 2.17%   |
| 401-500     | 2         | 2.17%   |
| 1001-1500   | 2         | 2.17%   |
| 701-800     | 1         | 1.09%   |
| 1501-2000   | 1         | 1.09%   |
| 901-1000    | 1         | 1.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 64        | 74.42%  |
| Unknown | 10        | 11.63%  |
| 16/10   | 8         | 9.3%    |
| 3/2     | 3         | 3.49%   |
| 3.18    | 1         | 1.16%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 21        | 22.58%  |
| 91-100         | 15        | 16.13%  |
| Unknown        | 11        | 11.83%  |
| 201-250        | 10        | 10.75%  |
| 301-350        | 9         | 9.68%   |
| 71-80          | 5         | 5.38%   |
| 251-300        | 5         | 5.38%   |
| 101-110        | 5         | 5.38%   |
| 61-70          | 3         | 3.23%   |
| 121-130        | 3         | 3.23%   |
| 501-1000       | 3         | 3.23%   |
| 351-500        | 2         | 2.15%   |
| More than 1000 | 1         | 1.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 31        | 34.07%  |
| 51-100        | 22        | 24.18%  |
| 161-240       | 14        | 15.38%  |
| Unknown       | 11        | 12.09%  |
| 101-120       | 8         | 8.79%   |
| More than 240 | 4         | 4.4%    |
| 1-50          | 1         | 1.1%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 77        | 52.74%  |
| 0     | 57        | 39.04%  |
| 2     | 11        | 7.53%   |
| 3     | 1         | 0.68%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 90        | 43.9%   |
| Realtek Semiconductor           | 68        | 33.17%  |
| TP-Link                         | 7         | 3.41%   |
| Qualcomm Atheros                | 7         | 3.41%   |
| Broadcom                        | 6         | 2.93%   |
| Ralink Technology               | 4         | 1.95%   |
| Hewlett-Packard                 | 4         | 1.95%   |
| D-Link System                   | 3         | 1.46%   |
| Mellanox Technologies           | 2         | 0.98%   |
| MediaTek                        | 2         | 0.98%   |
| Edimax Technology               | 2         | 0.98%   |
| Xiaomi                          | 1         | 0.49%   |
| Qualcomm Atheros Communications | 1         | 0.49%   |
| Lenovo                          | 1         | 0.49%   |
| Huawei Technologies             | 1         | 0.49%   |
| Google                          | 1         | 0.49%   |
| Emulex                          | 1         | 0.49%   |
| BUFFALO                         | 1         | 0.49%   |
| ASUSTek Computer                | 1         | 0.49%   |
| Arduino SA                      | 1         | 0.49%   |
| Aquantia                        | 1         | 0.49%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 46        | 18.47%  |
| Realtek RTL8125 2.5GbE Controller                                          | 14        | 5.62%   |
| Intel Wi-Fi 6 AX200                                                        | 14        | 5.62%   |
| Intel Wireless-AC 9260                                                     | 7         | 2.81%   |
| Intel Comet Lake PCH CNVi WiFi                                             | 7         | 2.81%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                     | 6         | 2.41%   |
| Intel Wi-Fi 6 AX201                                                        | 6         | 2.41%   |
| Intel I211 Gigabit Network Connection                                      | 6         | 2.41%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                          | 6         | 2.41%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 6         | 2.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 6         | 2.41%   |
| Intel Wireless 8265 / 8275                                                 | 5         | 2.01%   |
| Intel Ethernet Controller I225-V                                           | 5         | 2.01%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 4         | 1.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 4         | 1.61%   |
| Intel Wireless 7265                                                        | 4         | 1.61%   |
| Intel I210 Gigabit Network Connection                                      | 4         | 1.61%   |
| Intel 82574L Gigabit Network Connection                                    | 4         | 1.61%   |
| HP hs2350 HSPA+ Mobile Broadband Module Network Adapter                    | 4         | 1.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 3         | 1.2%    |
| Intel Ethernet Connection (4) I219-LM                                      | 3         | 1.2%    |
| Intel Ethernet Connection (14) I219-LM                                     | 3         | 1.2%    |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 3         | 1.2%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 2         | 0.8%    |
| Ralink MT7601U Wireless Adapter                                            | 2         | 0.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 2         | 0.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 2         | 0.8%    |
| Intel Wireless 7260                                                        | 2         | 0.8%    |
| Intel Ethernet Connection (11) I219-LM                                     | 2         | 0.8%    |
| Intel Ethernet Connection (10) I219-V                                      | 2         | 0.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                            | 2         | 0.8%    |
| Intel Alder Lake-P PCH CNVi WiFi                                           | 2         | 0.8%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                       | 1         | 0.4%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                | 1         | 0.4%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                                     | 1         | 0.4%    |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]        | 1         | 0.4%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                | 1         | 0.4%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                   | 1         | 0.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 0.4%    |
| Realtek RTL8188SU 802.11n WLAN Adapter                                     | 1         | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 73        | 63.48%  |
| Realtek Semiconductor           | 10        | 8.7%    |
| TP-Link                         | 7         | 6.09%   |
| Qualcomm Atheros                | 6         | 5.22%   |
| Broadcom                        | 5         | 4.35%   |
| Ralink Technology               | 4         | 3.48%   |
| D-Link System                   | 3         | 2.61%   |
| MediaTek                        | 2         | 1.74%   |
| Edimax Technology               | 2         | 1.74%   |
| Qualcomm Atheros Communications | 1         | 0.87%   |
| BUFFALO                         | 1         | 0.87%   |
| ASUSTek Computer                | 1         | 0.87%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                           | 14        | 12.17%  |
| Intel Wireless-AC 9260                                                        | 7         | 6.09%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 7         | 6.09%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 6         | 5.22%   |
| Intel Wi-Fi 6 AX201                                                           | 6         | 5.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 6         | 5.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 6         | 5.22%   |
| Intel Wireless 8265 / 8275                                                    | 5         | 4.35%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 4         | 3.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 4         | 3.48%   |
| Intel Wireless 7265                                                           | 4         | 3.48%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 3         | 2.61%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]    | 3         | 2.61%   |
| Ralink MT7601U Wireless Adapter                                               | 2         | 1.74%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 1.74%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 2         | 1.74%   |
| Intel Wireless 7260                                                           | 2         | 1.74%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2         | 1.74%   |
| Intel Alder Lake-P PCH CNVi WiFi                                              | 2         | 1.74%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1         | 0.87%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1         | 0.87%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]           | 1         | 0.87%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                      | 1         | 0.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.87%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                        | 1         | 0.87%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 0.87%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1         | 0.87%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 1         | 0.87%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1         | 0.87%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 0.87%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                 | 1         | 0.87%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                 | 1         | 0.87%   |
| Intel Wireless 8260                                                           | 1         | 0.87%   |
| Intel Wi-Fi 6 AX201 160MHz                                                    | 1         | 0.87%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 1         | 0.87%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 0.87%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 0.87%   |
| Intel Centrino Advanced-N 6235                                                | 1         | 0.87%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                | 1         | 0.87%   |
| Edimax EW-7711MAC 802.11ac Wireless Adapter                                   | 1         | 0.87%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 60        | 50.42%  |
| Intel                 | 49        | 41.18%  |
| Qualcomm Atheros      | 2         | 1.68%   |
| Broadcom              | 2         | 1.68%   |
| Xiaomi                | 1         | 0.84%   |
| Lenovo                | 1         | 0.84%   |
| Huawei Technologies   | 1         | 0.84%   |
| Google                | 1         | 0.84%   |
| Emulex                | 1         | 0.84%   |
| Aquantia              | 1         | 0.84%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 46        | 37.1%   |
| Realtek RTL8125 2.5GbE Controller                                             | 13        | 10.48%  |
| Intel I211 Gigabit Network Connection                                         | 6         | 4.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6         | 4.84%   |
| Intel Ethernet Controller I225-V                                              | 5         | 4.03%   |
| Intel I210 Gigabit Network Connection                                         | 4         | 3.23%   |
| Intel 82574L Gigabit Network Connection                                       | 4         | 3.23%   |
| Intel Ethernet Connection (4) I219-LM                                         | 3         | 2.42%   |
| Intel Ethernet Connection (14) I219-LM                                        | 3         | 2.42%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2         | 1.61%   |
| Intel Ethernet Connection (11) I219-LM                                        | 2         | 1.61%   |
| Intel Ethernet Connection (10) I219-V                                         | 2         | 1.61%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                          | 1         | 0.81%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 0.81%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1         | 0.81%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1         | 0.81%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                              | 1         | 0.81%   |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller                           | 1         | 0.81%   |
| Intel I350 Gigabit Network Connection                                         | 1         | 0.81%   |
| Intel Ethernet Controller X550                                                | 1         | 0.81%   |
| Intel Ethernet Controller I225-LM                                             | 1         | 0.81%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 1         | 0.81%   |
| Intel Ethernet Connection I219-LM                                             | 1         | 0.81%   |
| Intel Ethernet Connection I218-LM                                             | 1         | 0.81%   |
| Intel Ethernet Connection I217-LM                                             | 1         | 0.81%   |
| Intel Ethernet Connection (7) I219-V                                          | 1         | 0.81%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1         | 0.81%   |
| Intel Ethernet Connection (5) I219-V                                          | 1         | 0.81%   |
| Intel Ethernet Connection (3) I218-LM                                         | 1         | 0.81%   |
| Intel Ethernet Connection (2) I219-V                                          | 1         | 0.81%   |
| Intel Ethernet Connection (16) I219-LM                                        | 1         | 0.81%   |
| Intel Ethernet Connection (13) I219-V                                         | 1         | 0.81%   |
| Intel Ethernet Connection (11) I219-V                                         | 1         | 0.81%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 0.81%   |
| Huawei USB Device                                                             | 1         | 0.81%   |
| Google Nexus/Pixel Device (charging + debug)                                  | 1         | 0.81%   |
| Emulex OneConnect 10Gb NIC (be3)                                              | 1         | 0.81%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                             | 1         | 0.81%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 1         | 0.81%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 1         | 0.81%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 109       | 50.7%   |
| WiFi     | 96        | 44.65%  |
| Modem    | 6         | 2.79%   |
| Unknown  | 4         | 1.86%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 89        | 60.96%  |
| WiFi     | 54        | 36.99%  |
| Modem    | 3         | 2.05%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 75        | 53.19%  |
| 1     | 38        | 26.95%  |
| 0     | 15        | 10.64%  |
| 3     | 9         | 6.38%   |
| 4     | 3         | 2.13%   |
| 7     | 1         | 0.71%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 123       | 83.67%  |
| Yes  | 24        | 16.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 57        | 75%     |
| IMC Networks                    | 4         | 5.26%   |
| Apple                           | 4         | 5.26%   |
| Broadcom                        | 3         | 3.95%   |
| Realtek Semiconductor           | 2         | 2.63%   |
| Qualcomm Atheros Communications | 2         | 2.63%   |
| Skylight Digital                | 1         | 1.32%   |
| Opticis                         | 1         | 1.32%   |
| Foxconn / Hon Hai               | 1         | 1.32%   |
| Cambridge Silicon Radio         | 1         | 1.32%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 18        | 23.68%  |
| Intel AX200 Bluetooth                               | 13        | 17.11%  |
| Intel Bluetooth wireless interface                  | 9         | 11.84%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 6         | 7.89%   |
| Intel AX210 Bluetooth                               | 5         | 6.58%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 5.26%   |
| IMC Networks Realtek Bluetooth Adapter              | 3         | 3.95%   |
| Apple Bluetooth Host Controller                     | 3         | 3.95%   |
| Realtek Bluetooth Adapter                           | 2         | 2.63%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 2.63%   |
| Skylight Digital Realtek Bluetooth Adapter          | 1         | 1.32%   |
| Opticis Realtek Bluetooth Adapter                   | 1         | 1.32%   |
| Intel Wireless Bluetooth                            | 1         | 1.32%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.32%   |
| IMC Networks Bluetooth module                       | 1         | 1.32%   |
| Foxconn / Hon Hai RZ616 Bluetooth Adapter           | 1         | 1.32%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.32%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.32%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.32%   |
| Broadcom BCM2035 Bluetooth dongle                   | 1         | 1.32%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 1.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 65        | 37.36%  |
| AMD                     | 54        | 31.03%  |
| Nvidia                  | 32        | 18.39%  |
| C-Media Electronics     | 4         | 2.3%    |
| Lenovo                  | 3         | 1.72%   |
| Logitech                | 2         | 1.15%   |
| CMX Systems             | 2         | 1.15%   |
| Yamaha                  | 1         | 0.57%   |
| Texas Instruments       | 1         | 0.57%   |
| SteelSeries ApS         | 1         | 0.57%   |
| RODE Microphones        | 1         | 0.57%   |
| JMTek                   | 1         | 0.57%   |
| GN Netcom               | 1         | 0.57%   |
| Generalplus Technology  | 1         | 0.57%   |
| Creative Labs           | 1         | 0.57%   |
| Blue Microphones        | 1         | 0.57%   |
| AudioQuest              | 1         | 0.57%   |
| ASUSTek Computer        | 1         | 0.57%   |
| AKAI  Professional M.I. | 1         | 0.57%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                  | 31        | 14.42%  |
| AMD Renoir Radeon High Definition Audio Controller                      | 17        | 7.91%   |
| Intel Comet Lake PCH cAVS                                               | 11        | 5.12%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                     | 10        | 4.65%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller     | 9         | 4.19%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller             | 8         | 3.72%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller          | 7         | 3.26%   |
| Intel Comet Lake PCH-LP cAVS                                            | 6         | 2.79%   |
| Intel Cannon Lake PCH cAVS                                              | 6         | 2.79%   |
| AMD Starship/Matisse HD Audio Controller                                | 6         | 2.79%   |
| AMD Rembrandt Radeon High Definition Audio Controller                   | 6         | 2.79%   |
| Nvidia GP107GL High Definition Audio Controller                         | 5         | 2.33%   |
| Intel Sunrise Point-LP HD Audio                                         | 5         | 2.33%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                     | 4         | 1.86%   |
| Nvidia TU116 High Definition Audio Controller                           | 3         | 1.4%    |
| Intel Tiger Lake-H HD Audio Controller                                  | 3         | 1.4%    |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]               | 3         | 1.4%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                 | 3         | 1.4%    |
| Nvidia GP108 High Definition Audio Controller                           | 2         | 0.93%   |
| Nvidia GK208 HDMI/DP Audio Controller                                   | 2         | 0.93%   |
| Nvidia GK107 HDMI Audio Controller                                      | 2         | 0.93%   |
| Nvidia GA104 High Definition Audio Controller                           | 2         | 0.93%   |
| Intel Wildcat Point-LP High Definition Audio Controller                 | 2         | 0.93%   |
| Intel CM238 HD Audio Controller                                         | 2         | 0.93%   |
| Intel Broadwell-U Audio Controller                                      | 2         | 0.93%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                 | 2         | 0.93%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller     | 2         | 0.93%   |
| CMX Systems USB PnP Audio Device                                        | 2         | 0.93%   |
| AMD SBx00 Azalia (Intel HDA)                                            | 2         | 0.93%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 2         | 0.93%   |
| AMD Navi 10 HDMI Audio                                                  | 2         | 0.93%   |
| Yamaha Steinberg UR12                                                   | 1         | 0.47%   |
| Texas Instruments PCM2706 stereo audio DAC                              | 1         | 0.47%   |
| SteelSeries ApS SteelSeries Siberia 350                                 | 1         | 0.47%   |
| RODE Microphones RODE AI-1                                              | 1         | 0.47%   |
| Nvidia TU106 High Definition Audio Controller                           | 1         | 0.47%   |
| Nvidia TU104 HD Audio Controller                                        | 1         | 0.47%   |
| Nvidia High Definition Audio Controller                                 | 1         | 0.47%   |
| Nvidia GP106 High Definition Audio Controller                           | 1         | 0.47%   |
| Nvidia GP104 High Definition Audio Controller                           | 1         | 0.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 30        | 22.39%  |
| SK hynix               | 19        | 14.18%  |
| Micron Technology      | 17        | 12.69%  |
| Kingston               | 15        | 11.19%  |
| Crucial                | 12        | 8.96%   |
| Corsair                | 6         | 4.48%   |
| Unknown                | 5         | 3.73%   |
| Unknown                | 5         | 3.73%   |
| Smart                  | 3         | 2.24%   |
| Ramaxel Technology     | 3         | 2.24%   |
| G.Skill                | 3         | 2.24%   |
| Team                   | 2         | 1.49%   |
| Goodram                | 2         | 1.49%   |
| A-DATA Technology      | 2         | 1.49%   |
| Unknown (000000000C01) | 1         | 0.75%   |
| Transcend              | 1         | 0.75%   |
| PNY                    | 1         | 0.75%   |
| Neo Forza              | 1         | 0.75%   |
| KLEVV                  | 1         | 0.75%   |
| Golden Empire          | 1         | 0.75%   |
| Gold Key               | 1         | 0.75%   |
| Elpida                 | 1         | 0.75%   |
| 0B45000080CE           | 1         | 0.75%   |
| 06F100000C01           | 1         | 0.75%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown                                                        | 5         | 3.57%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s          | 4         | 2.86%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 2         | 1.43%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s         | 2         | 1.43%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s         | 2         | 1.43%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s        | 2         | 1.43%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s          | 2         | 1.43%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s          | 2         | 1.43%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s           | 2         | 1.43%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s           | 2         | 1.43%   |
| Crucial RAM BL32G32C16S4B.M16FB1 32GB SODIMM DDR4 2667MT/s     | 2         | 1.43%   |
| Corsair RAM CMK32GX4M2D3200C16 16GB DIMM DDR4 3200MT/s         | 2         | 1.43%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 1         | 0.71%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                    | 1         | 0.71%   |
| Unknown RAM Module 1GB SODIMM DDR                              | 1         | 0.71%   |
| Unknown RAM 3000 C16 Series 4096MB DIMM DDR4 2933MT/s          | 1         | 0.71%   |
| Unknown RAM 2G-08-10-12-1333 2GB DIMM DDR3 1333MT/s            | 1         | 0.71%   |
| Unknown (000000000C01) RAM Module 32GB DIMM DDR4 3200MT/s      | 1         | 0.71%   |
| Transcend RAM JM2666HLE-32G 32GB DIMM DDR4 2666MT/s            | 1         | 0.71%   |
| Team RAM TEAMGROUP-UD4-4133 8GB DIMM DDR4 4133MT/s             | 1         | 0.71%   |
| Team RAM TEAMGROUP-SD4-3200 32GB SODIMM DDR4 3200MT/s          | 1         | 0.71%   |
| Smart RAM SF4641G8CK8IWGKSEG 8GB SODIMM DDR4 2133MT/s          | 1         | 0.71%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s          | 1         | 0.71%   |
| Smart RAM Module 8GB DIMM DDR4 2667MT/s                        | 1         | 0.71%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1867MT/s                   | 1         | 0.71%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                   | 1         | 0.71%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s         | 1         | 0.71%   |
| SK hynix RAM HMAA4GU6CJR8N-XN 32GB DIMM DDR4 3200MT/s          | 1         | 0.71%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s         | 1         | 0.71%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s        | 1         | 0.71%   |
| SK hynix RAM HMA82GR7JJR8N-VK 16GB DIMM DDR4 2667MT/s          | 1         | 0.71%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 1         | 0.71%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s         | 1         | 0.71%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 1         | 0.71%   |
| SK hynix RAM HCNNNCRMBLPR-NEE 2GB Row Of Chips LPDDR4 4267MT/s | 1         | 0.71%   |
| Samsung RAM Module 4GB SODIMM DDR4 3200MT/s                    | 1         | 0.71%   |
| Samsung RAM M474A4G43AB1-CVF 32GB SODIMM DDR4 2933MT/s         | 1         | 0.71%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s          | 1         | 0.71%   |
| Samsung RAM M471B5674-M0-YK0 4GB Chip DDR3 1600MT/s            | 1         | 0.71%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 1         | 0.71%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 89        | 75.42%  |
| DDR3   | 16        | 13.56%  |
| DDR5   | 4         | 3.39%   |
| LPDDR5 | 3         | 2.54%   |
| LPDDR4 | 3         | 2.54%   |
| LPDDR3 | 2         | 1.69%   |
| DDR    | 1         | 0.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 74        | 62.71%  |
| DIMM         | 35        | 29.66%  |
| Row Of Chips | 8         | 6.78%   |
| Chip         | 1         | 0.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 43        | 35.25%  |
| 16384 | 39        | 31.97%  |
| 32768 | 18        | 14.75%  |
| 4096  | 16        | 13.11%  |
| 2048  | 5         | 4.1%    |
| 1024  | 1         | 0.82%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 43        | 34.68%  |
| 2667    | 25        | 20.16%  |
| 2400    | 10        | 8.06%   |
| 1600    | 8         | 6.45%   |
| 1867    | 6         | 4.84%   |
| 2666    | 5         | 4.03%   |
| 2133    | 5         | 4.03%   |
| 4800    | 3         | 2.42%   |
| 4267    | 3         | 2.42%   |
| 2933    | 3         | 2.42%   |
| 4266    | 2         | 1.61%   |
| 3600    | 2         | 1.61%   |
| 1333    | 2         | 1.61%   |
| 6400    | 1         | 0.81%   |
| 5200    | 1         | 0.81%   |
| 4133    | 1         | 0.81%   |
| 3000    | 1         | 0.81%   |
| 1866    | 1         | 0.81%   |
| 1334    | 1         | 0.81%   |
| Unknown | 1         | 0.81%   |

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
| Chicony Electronics                    | 16        | 20%     |
| IMC Networks                           | 12        | 15%     |
| Microdia                               | 9         | 11.25%  |
| Logitech                               | 9         | 11.25%  |
| Realtek Semiconductor                  | 7         | 8.75%   |
| Lite-On Technology                     | 5         | 6.25%   |
| Bison Electronics                      | 5         | 6.25%   |
| Sunplus Innovation Technology          | 4         | 5%      |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.75%   |
| Syntek                                 | 2         | 2.5%    |
| Shenzhen Kingcome Optoelectronic       | 2         | 2.5%    |
| Apple                                  | 2         | 2.5%    |
| Trust                                  | 1         | 1.25%   |
| Luxvisions Innotech Limited            | 1         | 1.25%   |
| GEMBIRD                                | 1         | 1.25%   |
| Aveo Technology                        | 1         | 1.25%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                         | 9         | 11.11%  |
| Chicony Integrated Camera                              | 8         | 9.88%   |
| Logitech Webcam C270                                   | 3         | 3.7%    |
| Lite-On Integrated Camera                              | 3         | 3.7%    |
| Chicony Integrated HP HD Webcam                        | 3         | 3.7%    |
| Bison Integrated Camera                                | 3         | 3.7%    |
| Sunplus Integrated_Webcam_HD                           | 2         | 2.47%   |
| Realtek USB 2.0 Webcam                                 | 2         | 2.47%   |
| Realtek Laptop Camera                                  | 2         | 2.47%   |
| Microdia USB Camera                                    | 2         | 2.47%   |
| Microdia Integrated Webcam                             | 2         | 2.47%   |
| Microdia HP Integrated Webcam                          | 2         | 2.47%   |
| Logitech C920 PRO HD Webcam                            | 2         | 2.47%   |
| Lite-On HP HD Camera                                   | 2         | 2.47%   |
| IMC Networks Realtek PC Camera                         | 2         | 2.47%   |
| Chicony ThinkPad T490 Webcam                           | 2         | 2.47%   |
| Bison HD Webcam                                        | 2         | 2.47%   |
| Apple FaceTime HD Camera (Built-in)                    | 2         | 2.47%   |
| Trust Canyon CNS-CWC6 Webcam                           | 1         | 1.23%   |
| Syntek Lenovo EasyCamera                               | 1         | 1.23%   |
| Syntek Integrated Camera                               | 1         | 1.23%   |
| Sunplus SPCA2650 AV Camera                             | 1         | 1.23%   |
| Sunplus Integrated_Webcam_FHD                          | 1         | 1.23%   |
| Shenzhen Kingcome Optoelectronic XiaoMi USB 2.0 Webcam | 1         | 1.23%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera        | 1         | 1.23%   |
| Realtek USB 2.0 PC Camera                              | 1         | 1.23%   |
| Realtek Integrated_Webcam_HD                           | 1         | 1.23%   |
| Realtek Composite Webcam                               | 1         | 1.23%   |
| Microdia USB 2.0 Camera                                | 1         | 1.23%   |
| Microdia Integrated_Webcam_FHD                         | 1         | 1.23%   |
| Microdia Dell Integrated HD Webcam                     | 1         | 1.23%   |
| Luxvisions Innotech Limited HP HD Camera               | 1         | 1.23%   |
| Logitech Webcam C170                                   | 1         | 1.23%   |
| Logitech HD Pro Webcam C920                            | 1         | 1.23%   |
| Logitech C505 HD Webcam                                | 1         | 1.23%   |
| Logitech BRIO Ultra HD Webcam                          | 1         | 1.23%   |
| IMC Networks EasyCamera                                | 1         | 1.23%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]      | 1         | 1.23%   |
| Chicony USB2.0 0.3M UVC WebCam                         | 1         | 1.23%   |
| Chicony Integrated IR Camera                           | 1         | 1.23%   |

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
| 0     | 42        | 28.19%  |
| 2     | 37        | 24.83%  |
| 1     | 31        | 20.81%  |
| 4     | 18        | 12.08%  |
| 3     | 16        | 10.74%  |
| 5     | 4         | 2.68%   |
| 9     | 1         | 0.67%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 75        | 36.41%  |
| Bluetooth                | 41        | 19.9%   |
| Net/wireless             | 32        | 15.53%  |
| Fingerprint reader       | 26        | 12.62%  |
| Card reader              | 12        | 5.83%   |
| Net/ethernet             | 6         | 2.91%   |
| Sound                    | 5         | 2.43%   |
| Network                  | 4         | 1.94%   |
| Firewire controller      | 3         | 1.46%   |
| Storage/raid             | 1         | 0.49%   |
| Modem                    | 1         | 0.49%   |

