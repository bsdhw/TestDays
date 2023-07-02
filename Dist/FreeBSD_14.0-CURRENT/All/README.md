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

Total: 239

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
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

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 118       | 80.82%  |
| arm64 | 24        | 16.44%  |
| arm   | 2         | 1.37%   |
| riscv | 1         | 0.68%   |
| i386  | 1         | 0.68%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 41        | 26.8%   |
| KDE5          | 39        | 25.49%  |
| XFCE          | 19        | 12.42%  |
| MATE          | 9         | 5.88%   |
| i3            | 8         | 5.23%   |
| GNOME         | 8         | 5.23%   |
| TWM           | 7         | 4.58%   |
| Openbox       | 3         | 1.96%   |
| LXQt          | 3         | 1.96%   |
| Cinnamon      | 3         | 1.96%   |
| LXDE          | 2         | 1.31%   |
| Lumina        | 2         | 1.31%   |
| Xfwm4         | 1         | 0.65%   |
| sway          | 1         | 0.65%   |
| spectrwm      | 1         | 0.65%   |
| Picom         | 1         | 0.65%   |
| GNUstep       | 1         | 0.65%   |
| Fluxbox       | 1         | 0.65%   |
| Enlightenment | 1         | 0.65%   |
| ctwm          | 1         | 0.65%   |
| Budgie        | 1         | 0.65%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 104       | 69.33%  |
| Console | 42        | 28%     |
| Wayland | 4         | 2.67%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 71        | 47.02%  |
| SDDM    | 36        | 23.84%  |
| SLiM    | 16        | 10.6%   |
| GDM     | 12        | 7.95%   |
| XDM     | 9         | 5.96%   |
| LightDM | 5         | 3.31%   |
| Ly      | 2         | 1.32%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Computers | Percent |
|------------------|-----------|---------|
| C                | 93        | 62.84%  |
| en_US            | 22        | 14.86%  |
| Unknown          | 9         | 6.08%   |
| de_DE            | 5         | 3.38%   |
| uk_UA            | 3         | 2.03%   |
| ru_RU            | 3         | 2.03%   |
| zh_CN            | 2         | 1.35%   |
| pl_PL            | 2         | 1.35%   |
| fr_FR            | 2         | 1.35%   |
| en_GB            | 2         | 1.35%   |
| sv_SE            | 1         | 0.68%   |
| pt_PT            | 1         | 0.68%   |
| it_IT.ISO8859-15 | 1         | 0.68%   |
| en_CA            | 1         | 0.68%   |
| de_CH            | 1         | 0.68%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 131       | 89.73%  |
| BIOS | 15        | 10.27%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 103       | 70.07%  |
| Ufs  | 43        | 29.25%  |
| Nfs  | 1         | 0.68%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 137       | 93.84%  |
| MBR  | 9         | 6.16%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 29        | 19.86%  |
| Unknown                        | 21        | 14.38%  |
| ASUSTek Computer               | 16        | 10.96%  |
| Dell                           | 15        | 10.27%  |
| Hewlett-Packard                | 11        | 7.53%   |
| Gigabyte Technology            | 9         | 6.16%   |
| MSI                            | 6         | 4.11%   |
| ASRock                         | 6         | 4.11%   |
| Raspberry Pi Foundation        | 4         | 2.74%   |
| Apple                          | 3         | 2.05%   |
| Valve                          | 2         | 1.37%   |
| Intel                          | 2         | 1.37%   |
| Framework                      | 2         | 1.37%   |
| F-Plus Mobile                  | 2         | 1.37%   |
| Beckhoff Automation            | 2         | 1.37%   |
| Timi                           | 1         | 0.68%   |
| System76                       | 1         | 0.68%   |
| SolidRun                       | 1         | 0.68%   |
| Samsung Electronics            | 1         | 0.68%   |
| pine64                         | 1         | 0.68%   |
| Notebook                       | 1         | 0.68%   |
| Matsushita Electric Industrial | 1         | 0.68%   |
| khadas                         | 1         | 0.68%   |
| HUAWEI                         | 1         | 0.68%   |
| Google                         | 1         | 0.68%   |
| friendlyelec                   | 1         | 0.68%   |
| AZW                            | 1         | 0.68%   |
| Avell High Performance         | 1         | 0.68%   |
| ASRockRack                     | 1         | 0.68%   |
| Alienware                      | 1         | 0.68%   |
| A-DATA Technology              | 1         | 0.68%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 22        | 15.07%  |
| RPi Raspberry Pi                            | 3         | 2.05%   |
| HP EliteBook 8570p                          | 3         | 2.05%   |
| Valve Jupiter                               | 2         | 1.37%   |
| Framework Laptop                            | 2         | 1.37%   |
| F-Plus Mobile FLAPTOP r                     | 2         | 1.37%   |
| ASRock X570 Phantom Gaming 4                | 2         | 1.37%   |
| Timi Redmi Book Pro 14 2022                 | 1         | 0.68%   |
| System76 Gazelle                            | 1         | 0.68%   |
| SolidRun CEX7 Platform                      | 1         | 0.68%   |
| Samsung 750XEE                              | 1         | 0.68%   |
| RPi rpi                                     | 1         | 0.68%   |
| pine64 pinebook-pro-rk3399                  | 1         | 0.68%   |
| Notebook NS50_70MU                          | 1         | 0.68%   |
| MSI MS-7C79                                 | 1         | 0.68%   |
| MSI MS-7C75                                 | 1         | 0.68%   |
| MSI MS-7B89                                 | 1         | 0.68%   |
| MSI MS-7B86                                 | 1         | 0.68%   |
| MSI GE76 Raider 10UG                        | 1         | 0.68%   |
| MSI Bravo 15 A4DDR                          | 1         | 0.68%   |
| Matsushita Electric Industrial CF-T2BW1AXR  | 1         | 0.68%   |
| Lenovo XiaoXinPro-13ARE 2020 82DM           | 1         | 0.68%   |
| Lenovo ThinkPad X395 20NL001SMX             | 1         | 0.68%   |
| Lenovo ThinkPad X395 20NL000GPG             | 1         | 0.68%   |
| Lenovo ThinkPad X270 20HM004JBR             | 1         | 0.68%   |
| Lenovo ThinkPad X260 20F5A28AUK             | 1         | 0.68%   |
| Lenovo ThinkPad X13 Gen 1 20T2003PRT        | 1         | 0.68%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TLA055CD | 1         | 0.68%   |
| Lenovo ThinkPad X1 Extreme 20MF000BUS       | 1         | 0.68%   |
| Lenovo ThinkPad X1 Carbon 6th 20KHCTO1WW    | 1         | 0.68%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS1QC00    | 1         | 0.68%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS0BT00    | 1         | 0.68%   |
| Lenovo ThinkPad T495s 20QKS1812F            | 1         | 0.68%   |
| Lenovo ThinkPad T495 20NJ0010PB             | 1         | 0.68%   |
| Lenovo ThinkPad T470p 20J7S0PM00            | 1         | 0.68%   |
| Lenovo ThinkPad T430 2349H2G                | 1         | 0.68%   |
| Lenovo ThinkPad T15p Gen 3 21DA000QUS       | 1         | 0.68%   |
| Lenovo ThinkPad T14s Gen 2i 20WM00B7MX      | 1         | 0.68%   |
| Lenovo ThinkPad T14s Gen 1 20UH0019PB       | 1         | 0.68%   |
| Lenovo ThinkPad P15 Gen 1 20ST005VRT        | 1         | 0.68%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 22        | 15.07%  |
| Lenovo ThinkPad                            | 21        | 14.38%  |
| ASUS PRIME                                 | 7         | 4.79%   |
| HP EliteBook                               | 5         | 3.42%   |
| HP ProBook                                 | 4         | 2.74%   |
| Dell Latitude                              | 4         | 2.74%   |
| RPi Raspberry                              | 3         | 2.05%   |
| Lenovo IdeaPad                             | 3         | 2.05%   |
| Dell OptiPlex                              | 3         | 2.05%   |
| ASUS ROG                                   | 3         | 2.05%   |
| Valve Jupiter                              | 2         | 1.37%   |
| Lenovo Legion                              | 2         | 1.37%   |
| Gigabyte X570                              | 2         | 1.37%   |
| Gigabyte B450M                             | 2         | 1.37%   |
| Framework Laptop                           | 2         | 1.37%   |
| F-Plus Mobile FLAPTOP                      | 2         | 1.37%   |
| Dell Vostro                                | 2         | 1.37%   |
| Dell Inspiron                              | 2         | 1.37%   |
| ASRock X570                                | 2         | 1.37%   |
| Timi Redmi                                 | 1         | 0.68%   |
| System76 Gazelle                           | 1         | 0.68%   |
| SolidRun CEX7                              | 1         | 0.68%   |
| Samsung 750XEE                             | 1         | 0.68%   |
| RPi rpi                                    | 1         | 0.68%   |
| pine64 pinebook-pro-rk3399                 | 1         | 0.68%   |
| Notebook NS50                              | 1         | 0.68%   |
| MSI MS-7C79                                | 1         | 0.68%   |
| MSI MS-7C75                                | 1         | 0.68%   |
| MSI MS-7B89                                | 1         | 0.68%   |
| MSI MS-7B86                                | 1         | 0.68%   |
| MSI GE76                                   | 1         | 0.68%   |
| MSI Bravo                                  | 1         | 0.68%   |
| Matsushita Electric Industrial CF-T2BW1AXR | 1         | 0.68%   |
| Lenovo XiaoXinPro-13ARE                    | 1         | 0.68%   |
| Lenovo ThinkBook                           | 1         | 0.68%   |
| khadas edge-v                              | 1         | 0.68%   |
| Intel S2600WTTR                            | 1         | 0.68%   |
| Intel NUC11PHi7                            | 1         | 0.68%   |
| HUAWEI HN-WX9X                             | 1         | 0.68%   |
| HP ZBook                                   | 1         | 0.68%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 33        | 22.6%   |
| 2020    | 30        | 20.55%  |
| Unknown | 20        | 13.7%   |
| 2022    | 17        | 11.64%  |
| 2019    | 15        | 10.27%  |
| 2018    | 8         | 5.48%   |
| 2023    | 5         | 3.42%   |
| 2017    | 5         | 3.42%   |
| 2013    | 4         | 2.74%   |
| 2015    | 3         | 2.05%   |
| 2016    | 2         | 1.37%   |
| 2014    | 1         | 0.68%   |
| 2012    | 1         | 0.68%   |
| 2011    | 1         | 0.68%   |
| 2003    | 1         | 0.68%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 73        | 50%     |
| Desktop        | 60        | 41.1%   |
| System on chip | 7         | 4.79%   |
| Mini pc        | 3         | 2.05%   |
| Server         | 2         | 1.37%   |
| All in one     | 1         | 0.68%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 144       | 98.63%  |
| Yes  | 2         | 1.37%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 53        | 35.81%  |
| 8.01-16.0       | 25        | 16.89%  |
| 32.01-64.0      | 23        | 15.54%  |
| 64.01-256.0     | 22        | 14.86%  |
| 4.01-8.0        | 9         | 6.08%   |
| 3.01-4.0        | 8         | 5.41%   |
| 0.51-1.0        | 4         | 2.7%    |
| More than 256.0 | 1         | 0.68%   |
| 24.01-32.0      | 1         | 0.68%   |
| 1.01-2.0        | 1         | 0.68%   |
| 0.01-0.5        | 1         | 0.68%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.51-1.0    | 45        | 30.2%   |
| 1.01-2.0    | 42        | 28.19%  |
| 0.01-0.5    | 30        | 20.13%  |
| 2.01-3.0    | 16        | 10.74%  |
| 3.01-4.0    | 6         | 4.03%   |
| 4.01-8.0    | 2         | 1.34%   |
| 24.01-32.0  | 2         | 1.34%   |
| 0           | 2         | 1.34%   |
| 32.01-64.0  | 1         | 0.67%   |
| 64.01-256.0 | 1         | 0.67%   |
| 16.01-24.0  | 1         | 0.67%   |
| 8.01-16.0   | 1         | 0.67%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 71        | 46.41%  |
| 2      | 35        | 22.88%  |
| 0      | 23        | 15.03%  |
| 3      | 10        | 6.54%   |
| 6      | 5         | 3.27%   |
| 4      | 5         | 3.27%   |
| 5      | 2         | 1.31%   |
| 15     | 1         | 0.65%   |
| 7      | 1         | 0.65%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 128       | 86.49%  |
| Yes       | 20        | 13.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 111       | 76.03%  |
| No        | 35        | 23.97%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 96        | 65.75%  |
| No        | 50        | 34.25%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 76        | 51.35%  |
| No        | 72        | 48.65%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 25        | 17.12%  |
| Russia       | 23        | 15.75%  |
| Germany      | 15        | 10.27%  |
| UK           | 14        | 9.59%   |
| Poland       | 9         | 6.16%   |
| Brazil       | 7         | 4.79%   |
| Ukraine      | 5         | 3.42%   |
| Japan        | 4         | 2.74%   |
| China        | 4         | 2.74%   |
| Canada       | 4         | 2.74%   |
| Austria      | 4         | 2.74%   |
| Portugal     | 3         | 2.05%   |
| France       | 3         | 2.05%   |
| Turkey       | 2         | 1.37%   |
| Switzerland  | 2         | 1.37%   |
| Sweden       | 2         | 1.37%   |
| Romania      | 2         | 1.37%   |
| Netherlands  | 2         | 1.37%   |
| Denmark      | 2         | 1.37%   |
| Taiwan       | 1         | 0.68%   |
| Spain        | 1         | 0.68%   |
| Singapore    | 1         | 0.68%   |
| Saudi Arabia | 1         | 0.68%   |
| Peru         | 1         | 0.68%   |
| Jordan       | 1         | 0.68%   |
| Jamaica      | 1         | 0.68%   |
| Italy        | 1         | 0.68%   |
| India        | 1         | 0.68%   |
| Czechia      | 1         | 0.68%   |
| Croatia      | 1         | 0.68%   |
| Colombia     | 1         | 0.68%   |
| Belarus      | 1         | 0.68%   |
| Bangladesh   | 1         | 0.68%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Moscow                      | 9         | 5.52%   |
| Krasnodar                   | 7         | 4.29%   |
| Brighton                    | 5         | 3.07%   |
| St Petersburg               | 4         | 2.45%   |
| Seattle                     | 4         | 2.45%   |
| Vienna                      | 3         | 1.84%   |
| London                      | 3         | 1.84%   |
| Kyiv                        | 3         | 1.84%   |
| ЕЊta-ku                   | 2         | 1.23%   |
| Zurich                      | 2         | 1.23%   |
| Warsaw                      | 2         | 1.23%   |
| Vancouver                   | 2         | 1.23%   |
| Shoreham-by-Sea             | 2         | 1.23%   |
| Rio de Janeiro              | 2         | 1.23%   |
| Rietberg                    | 2         | 1.23%   |
| Northeim                    | 2         | 1.23%   |
| Istanbul                    | 2         | 1.23%   |
| Graz                        | 2         | 1.23%   |
| Fuchu                       | 2         | 1.23%   |
| Fremont                     | 2         | 1.23%   |
| Egham                       | 2         | 1.23%   |
| Choroszcz                   | 2         | 1.23%   |
| Chicago                     | 2         | 1.23%   |
| Cambridge                   | 2         | 1.23%   |
| Berlin                      | 2         | 1.23%   |
| Albuquerque                 | 2         | 1.23%   |
| Zaporizhzhya                | 1         | 0.61%   |
| Wuhan                       | 1         | 0.61%   |
| Woodburn                    | 1         | 0.61%   |
| Wieliczka                   | 1         | 0.61%   |
| Washington                  | 1         | 0.61%   |
| Voznesensk                  | 1         | 0.61%   |
| Vila Real de Santo António | 1         | 0.61%   |
| Tynda                       | 1         | 0.61%   |
| Trosa                       | 1         | 0.61%   |
| Toronto                     | 1         | 0.61%   |
| Thrissur                    | 1         | 0.61%   |
| Teaneck                     | 1         | 0.61%   |
| Taipei                      | 1         | 0.61%   |
| Stuttgart                   | 1         | 0.61%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 40        | 60     | 21.62%  |
| WDC                 | 31        | 50     | 16.76%  |
| Toshiba             | 17        | 30     | 9.19%   |
| Seagate             | 15        | 32     | 8.11%   |
| Crucial             | 13        | 24     | 7.03%   |
| Kingston            | 9         | 12     | 4.86%   |
| HGST                | 8         | 29     | 4.32%   |
| Intel               | 7         | 10     | 3.78%   |
| KIOXIA              | 6         | 6      | 3.24%   |
| A-DATA Technology   | 6         | 6      | 3.24%   |
| SK hynix            | 5         | 5      | 2.7%    |
| Micron Technology   | 5         | 7      | 2.7%    |
| FORESEE             | 3         | 3      | 1.62%   |
| Apple               | 3         | 3      | 1.62%   |
| SSSTC               | 2         | 2      | 1.08%   |
| SPCC                | 2         | 2      | 1.08%   |
| UMIS                | 1         | 1      | 0.54%   |
| Solid State Storage | 1         | 1      | 0.54%   |
| Silicon Motion      | 1         | 1      | 0.54%   |
| SanDisk             | 1         | 2      | 0.54%   |
| PNY                 | 1         | 1      | 0.54%   |
| Phison              | 1         | 2      | 0.54%   |
| Mushkin             | 1         | 1      | 0.54%   |
| LSI                 | 1         | 4      | 0.54%   |
| LITEON              | 1         | 1      | 0.54%   |
| Hitachi             | 1         | 2      | 0.54%   |
| GOODRAM             | 1         | 1      | 0.54%   |
| Fujitsu             | 1         | 2      | 0.54%   |
| Apacer              | 1         | 1      | 0.54%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB             | 7         | 3.43%   |
| Toshiba MQ04ABF100 1TB               | 4         | 1.96%   |
| HGST HTS725050A7E630 500GB           | 4         | 1.96%   |
| HGST HTS721010A9E630 1TB             | 4         | 1.96%   |
| WDC WDS100T3X0C-00SJG0 1TB           | 3         | 1.47%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 3         | 1.47%   |
| Samsung SSD 980 PRO 1TB              | 3         | 1.47%   |
| Samsung SSD 970 EVO Plus 1TB         | 3         | 1.47%   |
| Samsung SSD 870 EVO 1TB              | 3         | 1.47%   |
| Samsung SSD 860 EVO 250GB            | 3         | 1.47%   |
| Samsung HM251JX 250GB                | 3         | 1.47%   |
| WDC WDS100T1X0E-00AFY0 1TB           | 2         | 0.98%   |
| WDC WD30EFRX-68EUZN0 3TB             | 2         | 0.98%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB   | 2         | 0.98%   |
| WDC PC SN730 NVMe 1024GB             | 2         | 0.98%   |
| Seagate ST1000LM049-2GH172 1TB       | 2         | 0.98%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 0.98%   |
| Samsung SSD 980 1TB                  | 2         | 0.98%   |
| Samsung SSD 970 EVO Plus 500GB       | 2         | 0.98%   |
| Samsung SSD 850 EVO 250GB            | 2         | 0.98%   |
| Samsung MZVLB512HBJQ-000L7 512GB     | 2         | 0.98%   |
| Samsung MZVLB1T0HBLR-000L2 1TB       | 2         | 0.98%   |
| KIOXIA KBG40ZNS512G NVMe 512GB       | 2         | 0.98%   |
| KIOXIA KBG40ZNS256G NVMe 256GB       | 2         | 0.98%   |
| Kingston SA2000M81000G 1TB           | 2         | 0.98%   |
| FORESEE XP1000F001T 1TB              | 2         | 0.98%   |
| Crucial CT750MX300SSD1 752GB         | 2         | 0.98%   |
| Crucial CT500P2SSD8 500GB            | 2         | 0.98%   |
| Apple SSD SM256E 256GB               | 2         | 0.98%   |
| WDC WDS500G1X0E-00AFY0 500GB         | 1         | 0.49%   |
| WDC WDS250G2B0C-00PXH0 250GB         | 1         | 0.49%   |
| WDC WDS100T2B0A-00SM50 1TB           | 1         | 0.49%   |
| WDC WD60EFRX-68TGBN1 6TB             | 1         | 0.49%   |
| WDC WD5002ABYS-18B1B0 500GB          | 1         | 0.49%   |
| WDC WD40EZRZ-75GXCB0 4TB             | 1         | 0.49%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 1         | 0.49%   |
| WDC WD20EFRX-68AX9N0 2TB             | 1         | 0.49%   |
| WDC WD2003FZEX-00SRLA0 2TB           | 1         | 0.49%   |
| WDC WD120EFAX-68UNTN0 12TB           | 1         | 0.49%   |
| WDC WD10SPZX-60Z10T0 1TB             | 1         | 0.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 15        | 27     | 25%     |
| Seagate             | 15        | 32     | 25%     |
| WDC                 | 14        | 20     | 23.33%  |
| HGST                | 8         | 29     | 13.33%  |
| Samsung Electronics | 5         | 9      | 8.33%   |
| LSI                 | 1         | 4      | 1.67%   |
| Hitachi             | 1         | 2      | 1.67%   |
| Fujitsu             | 1         | 2      | 1.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 18     | 29.55%  |
| Crucial             | 8         | 14     | 18.18%  |
| Kingston            | 5         | 7      | 11.36%  |
| A-DATA Technology   | 4         | 4      | 9.09%   |
| Intel               | 3         | 6      | 6.82%   |
| Apple               | 3         | 3      | 6.82%   |
| WDC                 | 1         | 2      | 2.27%   |
| SPCC                | 1         | 1      | 2.27%   |
| SK hynix            | 1         | 1      | 2.27%   |
| SanDisk             | 1         | 2      | 2.27%   |
| Micron Technology   | 1         | 1      | 2.27%   |
| LITEON              | 1         | 1      | 2.27%   |
| GOODRAM             | 1         | 1      | 2.27%   |
| Apacer              | 1         | 1      | 2.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 78        | 114    | 47.56%  |
| SSD  | 43        | 62     | 26.22%  |
| HDD  | 43        | 125    | 26.22%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 78        | 114    | 52%     |
| SATA | 72        | 187    | 48%     |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 43        | 78     | 45.26%  |
| 0.51-1.0   | 29        | 56     | 30.53%  |
| 1.01-2.0   | 9         | 14     | 9.47%   |
| 4.01-10.0  | 5         | 24     | 5.26%   |
| 3.01-4.0   | 3         | 4      | 3.16%   |
| 2.01-3.0   | 3         | 4      | 3.16%   |
| 10.01-20.0 | 2         | 3      | 2.11%   |
| 20.01-50.0 | 1         | 4      | 1.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 40        | 26.14%  |
| 251-500        | 37        | 24.18%  |
| 501-1000       | 25        | 16.34%  |
| 21-50          | 14        | 9.15%   |
| 1-20           | 12        | 7.84%   |
| 51-100         | 11        | 7.19%   |
| 1001-2000      | 7         | 4.58%   |
| 2001-3000      | 4         | 2.61%   |
| More than 3000 | 3         | 1.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 97        | 62.99%  |
| 21-50          | 37        | 24.03%  |
| 101-250        | 8         | 5.19%   |
| 251-500        | 3         | 1.95%   |
| 501-1000       | 3         | 1.95%   |
| 1001-2000      | 2         | 1.3%    |
| 51-100         | 2         | 1.3%    |
| More than 3000 | 1         | 0.65%   |
| 0              | 1         | 0.65%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


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

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


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

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


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

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


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

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 118       | 247    | 85.51%  |
| Malfunc  | 15        | 44     | 10.87%  |
| Detected | 5         | 10     | 3.62%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 56        | 29.17%  |
| AMD                                     | 35        | 18.23%  |
| Samsung Electronics                     | 28        | 14.58%  |
| SanDisk                                 | 19        | 9.9%    |
| Silicon Motion                          | 8         | 4.17%   |
| Kingston Technology Company             | 6         | 3.13%   |
| SK hynix                                | 5         | 2.6%    |
| Micron/Crucial Technology               | 5         | 2.6%    |
| Micron Technology                       | 5         | 2.6%    |
| KIOXIA                                  | 5         | 2.6%    |
| Toshiba                                 | 4         | 2.08%   |
| Solid State Storage Technology          | 3         | 1.56%   |
| Shenzhen Longsys Electronics            | 2         | 1.04%   |
| Phison Electronics                      | 2         | 1.04%   |
| Marvell Technology Group                | 2         | 1.04%   |
| Broadcom / LSI                          | 2         | 1.04%   |
| ASMedia Technology                      | 2         | 1.04%   |
| ADATA Technology                        | 2         | 1.04%   |
| Shenzhen Unionmemory Information System | 1         | 0.52%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 26        | 12.38%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 18        | 8.57%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 11        | 5.24%   |
| Intel Comet Lake SATA AHCI Controller                                          | 9         | 4.29%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 8         | 3.81%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 3.33%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 7         | 3.33%   |
| AMD 400 Series Chipset SATA Controller                                         | 7         | 3.33%   |
| Samsung NVMe SSD Controller 980                                                | 6         | 2.86%   |
| Unknown                                                                        | 6         | 2.86%   |
| AMD 500 Series Chipset SATA Controller                                         | 5         | 2.38%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 1.9%    |
| KIOXIA NVMe SSD Controller BG4                                                 | 4         | 1.9%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 4         | 1.9%    |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                 | 3         | 1.43%   |
| SK hynix BC511 NVMe SSD                                                        | 3         | 1.43%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 3         | 1.43%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 3         | 1.43%   |
| Micron NVMe Storage Controller                                                 | 3         | 1.43%   |
| Kingston Company A2000 NVMe SSD                                                | 3         | 1.43%   |
| Toshiba XG6 NVMe SSD Controller                                                | 2         | 0.95%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 0.95%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 0.95%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 0.95%   |
| Phison E12 NVMe Controller                                                     | 2         | 0.95%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 2         | 0.95%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 0.95%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 2         | 0.95%   |
| Intel SSD 660P Series                                                          | 2         | 0.95%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 0.95%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 0.95%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 0.95%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 0.95%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 0.95%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 2         | 0.95%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 2         | 0.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 0.95%   |
| Toshiba XG5 NVMe SSD Controller                                                | 1         | 0.48%   |
| Toshiba XG4 NVMe SSD Controller                                                | 1         | 0.48%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 1         | 0.48%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 92        | 50%     |
| SATA | 82        | 44.57%  |
| RAID | 5         | 2.72%   |
| IDE  | 4         | 2.17%   |
| SAS  | 1         | 0.54%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 70        | 47.3%   |
| AMD      | 50        | 33.78%  |
| ARM      | 18        | 12.16%  |
| Unknown  | 8         | 5.41%   |
| Research | 1         | 0.68%   |
| NXP      | 1         | 0.68%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| ARM Cortex-A55 r2p0                             | 9         | 6.08%   |
|                                                 | 8         | 5.41%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 6         | 4.05%   |
| Intel Core i5-10210U CPU @ 1.60GHz              | 5         | 3.38%   |
| Intel Core i7-3520M CPU @ 2.90GHz               | 4         | 2.7%    |
| ARM Cortex-A72 r0p3                             | 4         | 2.7%    |
| AMD Ryzen 5 5600G with Radeon Graphics          | 4         | 2.7%    |
| Intel Core i7-10750H CPU @ 2.60GHz              | 3         | 2.03%   |
| Intel Core i5-10400 CPU @ 2.90GHz               | 3         | 2.03%   |
| Intel Core i5-10300H CPU @ 2.50GHz              | 3         | 2.03%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 2         | 1.35%   |
| Intel Core i7-7600U CPU @ 2.80GHz               | 2         | 1.35%   |
| Intel Core i5-10500T CPU @ 2.30GHz              | 2         | 1.35%   |
| ARM Cortex-A72 r0p2                             | 2         | 1.35%   |
| ARM Cortex-A53 r0p4                             | 2         | 1.35%   |
| AMD Ryzen 9 7950X 16-Core Processor             | 2         | 1.35%   |
| AMD Ryzen 9 5950X 16-Core Processor             | 2         | 1.35%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 2         | 1.35%   |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx | 2         | 1.35%   |
| AMD Ryzen 7 5825U with Radeon Graphics          | 2         | 1.35%   |
| AMD Ryzen 7 4800U with Radeon Graphics          | 2         | 1.35%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 2         | 1.35%   |
| AMD Ryzen 7 4700U with Radeon Graphics          | 2         | 1.35%   |
| AMD Ryzen 7 2700X Eight-Core Processor          | 2         | 1.35%   |
| AMD Ryzen 5 PRO 3500U w/ Radeon Vega Mobile Gfx | 2         | 1.35%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 2         | 1.35%   |
| AMD Custom APU 0405                             | 2         | 1.35%   |
| Research Morello SoC r0p0                       | 1         | 0.68%   |
| NXP Cortex-A72                                  | 1         | 0.68%   |
| Intel Xeon W-10885M CPU @ 2.40GHz               | 1         | 0.68%   |
| Intel Xeon E-2334 CPU @ 3.40GHz                 | 1         | 0.68%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz             | 1         | 0.68%   |
| Intel Pentium M processor 1000MHz               | 1         | 0.68%   |
| Intel Core i7-9850H CPU @ 2.60GHz               | 1         | 0.68%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 1         | 0.68%   |
| Intel Core i7-8700 CPU @ 3.20GHz                | 1         | 0.68%   |
| Intel Core i7-8650U CPU @ 1.90GHz               | 1         | 0.68%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 0.68%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 1         | 0.68%   |
| Intel Core i7-7820HK CPU @ 2.90GHz              | 1         | 0.68%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 32        | 21.77%  |
| Other                  | 26        | 17.69%  |
| Intel Core i5          | 18        | 12.24%  |
| ARM Cortex             | 17        | 11.56%  |
| AMD Ryzen 7            | 14        | 9.52%   |
| AMD Ryzen 5            | 13        | 8.84%   |
| AMD Ryzen 9            | 8         | 5.44%   |
| Intel Xeon             | 3         | 2.04%   |
| AMD Ryzen 7 PRO        | 3         | 2.04%   |
| AMD Ryzen 5 PRO        | 3         | 2.04%   |
| Intel Pentium M        | 1         | 0.68%   |
| Intel Core i3          | 1         | 0.68%   |
| Intel Atom             | 1         | 0.68%   |
| AMD Ryzen Threadripper | 1         | 0.68%   |
| AMD Ryzen Embedded     | 1         | 0.68%   |
| AMD Ryzen 3            | 1         | 0.68%   |
| AMD FX                 | 1         | 0.68%   |
| AMD EPYC               | 1         | 0.68%   |
| AMD E                  | 1         | 0.68%   |
| AMD Athlon             | 1         | 0.68%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 31        | 21.09%  |
| Unknown | 27        | 18.37%  |
| 8       | 20        | 13.61%  |
| 2       | 17        | 11.56%  |
| 6       | 15        | 10.2%   |
| 16      | 14        | 9.52%   |
| 12      | 11        | 7.48%   |
| 32      | 6         | 4.08%   |
| 24      | 3         | 2.04%   |
| 64      | 1         | 0.68%   |
| 10      | 1         | 0.68%   |
| 1       | 1         | 0.68%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 124       | 84.35%  |
| Unknown | 22        | 14.97%  |
| 2       | 1         | 0.68%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 67        | 45.58%  |
| 1       | 52        | 35.37%  |
| Unknown | 28        | 19.05%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 42        | 28.57%  |
| KabyLake   | 20        | 13.61%  |
| CometLake  | 15        | 10.2%   |
| Zen 2      | 13        | 8.84%   |
| Zen+       | 11        | 7.48%   |
| Zen 3      | 11        | 7.48%   |
| IvyBridge  | 9         | 6.12%   |
| TigerLake  | 8         | 5.44%   |
| Zen        | 5         | 3.4%    |
| Haswell    | 3         | 2.04%   |
| Broadwell  | 3         | 2.04%   |
| Skylake    | 2         | 1.36%   |
| Silvermont | 1         | 0.68%   |
| Piledriver | 1         | 0.68%   |
| P6         | 1         | 0.68%   |
| IceLake    | 1         | 0.68%   |
| Bobcat     | 1         | 0.68%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 58        | 38.67%  |
| AMD                        | 48        | 32%     |
| Nvidia                     | 41        | 27.33%  |
| Matrox Electronics Systems | 2         | 1.33%   |
| ASPEED Technology          | 1         | 0.67%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                           | 10        | 6.54%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                            | 8         | 5.23%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series] | 7         | 4.58%   |
| Intel CometLake-U GT2 [UHD Graphics]                                 | 6         | 3.92%   |
| Intel CometLake-H GT2 [UHD Graphics]                                 | 5         | 3.27%   |
| Intel 3rd Gen Core processor Graphics Controller                     | 5         | 3.27%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]         | 5         | 3.27%   |
| Nvidia TU117M                                                        | 4         | 2.61%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                             | 4         | 2.61%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                            | 4         | 2.61%   |
| Intel HD Graphics 620                                                | 3         | 1.96%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                             | 3         | 1.96%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]     | 3         | 1.96%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                           | 2         | 1.31%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                           | 2         | 1.31%   |
| Nvidia GP108M [GeForce MX230]                                        | 2         | 1.31%   |
| Nvidia GP108 [GeForce GT 1030]                                       | 2         | 1.31%   |
| Nvidia GK208B [GeForce GT 710]                                       | 2         | 1.31%   |
| Intel UHD Graphics 620                                               | 2         | 1.31%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                 | 2         | 1.31%   |
| Intel HD Graphics 630                                                | 2         | 1.31%   |
| Intel Alder Lake-P Integrated Graphics Controller                    | 2         | 1.31%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller          | 2         | 1.31%   |
| AMD VanGogh [AMD Custom GPU 0405]                                    | 2         | 1.31%   |
| AMD Rembrandt [Radeon 680M]                                          | 2         | 1.31%   |
| AMD Raphael                                                          | 2         | 1.31%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]        | 2         | 1.31%   |
| AMD Lucienne                                                         | 2         | 1.31%   |
| AMD Barcelo                                                          | 2         | 1.31%   |
| Nvidia TU117M [GeForce MX450]                                        | 1         | 0.65%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                | 1         | 0.65%   |
| Nvidia TU117 [GeForce GTX 1650]                                      | 1         | 0.65%   |
| Nvidia TU116 [GeForce GTX 1660]                                      | 1         | 0.65%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                              | 1         | 0.65%   |
| Nvidia TU104GLM [Quadro RTX 5000 Mobile / Max-Q]                     | 1         | 0.65%   |
| Nvidia GT218 [GeForce 210]                                           | 1         | 0.65%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                           | 1         | 0.65%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                              | 1         | 0.65%   |
| Nvidia GP107GL [Quadro P620]                                         | 1         | 0.65%   |
| Nvidia GP107 [GeForce GTX 1050]                                      | 1         | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x AMD                  | 40        | 27.03%  |
| 1 x Intel                | 33        | 22.3%   |
| Other                    | 26        | 17.57%  |
| Intel + Nvidia           | 22        | 14.86%  |
| 1 x Nvidia               | 17        | 11.49%  |
| 2 x AMD                  | 3         | 2.03%   |
| 1 x Matrox               | 2         | 1.35%   |
| AMD + Nvidia             | 2         | 1.35%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.68%   |
| Intel + AMD              | 1         | 0.68%   |
| 1 x ASPEED               | 1         | 0.68%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 93        | 63.7%   |
| Proprietary | 27        | 18.49%  |
| Unknown     | 26        | 17.81%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 104       | 69.8%   |
| 1.01-2.0   | 11        | 7.38%   |
| 0.51-1.0   | 8         | 5.37%   |
| 0.01-0.5   | 8         | 5.37%   |
| 3.01-4.0   | 6         | 4.03%   |
| 7.01-8.0   | 5         | 3.36%   |
| 5.01-6.0   | 3         | 2.01%   |
| 8.01-16.0  | 3         | 2.01%   |
| 2.01-3.0   | 1         | 0.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


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

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


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

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


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

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


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

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


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

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


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

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


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

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


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

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 80        | 52.98%  |
| 0     | 59        | 39.07%  |
| 2     | 11        | 7.28%   |
| 3     | 1         | 0.66%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 92        | 44.02%  |
| Realtek Semiconductor           | 69        | 33.01%  |
| TP-Link                         | 7         | 3.35%   |
| Qualcomm Atheros                | 7         | 3.35%   |
| Broadcom                        | 6         | 2.87%   |
| Ralink Technology               | 4         | 1.91%   |
| Hewlett-Packard                 | 4         | 1.91%   |
| D-Link System                   | 3         | 1.44%   |
| Mellanox Technologies           | 2         | 0.96%   |
| MediaTek                        | 2         | 0.96%   |
| Edimax Technology               | 2         | 0.96%   |
| Xiaomi                          | 1         | 0.48%   |
| Ralink                          | 1         | 0.48%   |
| Qualcomm Atheros Communications | 1         | 0.48%   |
| Lenovo                          | 1         | 0.48%   |
| Huawei Technologies             | 1         | 0.48%   |
| Google                          | 1         | 0.48%   |
| Emulex                          | 1         | 0.48%   |
| BUFFALO                         | 1         | 0.48%   |
| ASUSTek Computer                | 1         | 0.48%   |
| Arduino SA                      | 1         | 0.48%   |
| Aquantia                        | 1         | 0.48%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 47        | 18.5%   |
| Realtek RTL8125 2.5GbE Controller                                          | 14        | 5.51%   |
| Intel Wi-Fi 6 AX200                                                        | 14        | 5.51%   |
| Intel Wireless-AC 9260                                                     | 7         | 2.76%   |
| Intel I211 Gigabit Network Connection                                      | 7         | 2.76%   |
| Intel Comet Lake PCH CNVi WiFi                                             | 7         | 2.76%   |
| Intel Wireless 8265 / 8275                                                 | 6         | 2.36%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                     | 6         | 2.36%   |
| Intel Wi-Fi 6 AX201                                                        | 6         | 2.36%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                          | 6         | 2.36%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 6         | 2.36%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 6         | 2.36%   |
| Intel Ethernet Controller I225-V                                           | 5         | 1.97%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 4         | 1.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 4         | 1.57%   |
| Intel Wireless 7265                                                        | 4         | 1.57%   |
| Intel I210 Gigabit Network Connection                                      | 4         | 1.57%   |
| Intel 82574L Gigabit Network Connection                                    | 4         | 1.57%   |
| HP hs2350 HSPA+ Mobile Broadband Module Network Adapter                    | 4         | 1.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 3         | 1.18%   |
| Intel Ethernet Connection (4) I219-LM                                      | 3         | 1.18%   |
| Intel Ethernet Connection (14) I219-LM                                     | 3         | 1.18%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 3         | 1.18%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 2         | 0.79%   |
| Ralink MT7601U Wireless Adapter                                            | 2         | 0.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 2         | 0.79%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 2         | 0.79%   |
| Intel Wireless 7260                                                        | 2         | 0.79%   |
| Intel Ethernet Connection (11) I219-LM                                     | 2         | 0.79%   |
| Intel Ethernet Connection (10) I219-V                                      | 2         | 0.79%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 2         | 0.79%   |
| Intel Alder Lake-P PCH CNVi WiFi                                           | 2         | 0.79%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                       | 1         | 0.39%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                | 1         | 0.39%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                     | 1         | 0.39%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]        | 1         | 0.39%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                | 1         | 0.39%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                   | 1         | 0.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 0.39%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                     | 1         | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 74        | 63.25%  |
| Realtek Semiconductor           | 10        | 8.55%   |
| TP-Link                         | 7         | 5.98%   |
| Qualcomm Atheros                | 6         | 5.13%   |
| Broadcom                        | 5         | 4.27%   |
| Ralink Technology               | 4         | 3.42%   |
| D-Link System                   | 3         | 2.56%   |
| MediaTek                        | 2         | 1.71%   |
| Edimax Technology               | 2         | 1.71%   |
| Ralink                          | 1         | 0.85%   |
| Qualcomm Atheros Communications | 1         | 0.85%   |
| BUFFALO                         | 1         | 0.85%   |
| ASUSTek Computer                | 1         | 0.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                           | 14        | 11.97%  |
| Intel Wireless-AC 9260                                                        | 7         | 5.98%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 7         | 5.98%   |
| Intel Wireless 8265 / 8275                                                    | 6         | 5.13%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 6         | 5.13%   |
| Intel Wi-Fi 6 AX201                                                           | 6         | 5.13%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 6         | 5.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 6         | 5.13%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 4         | 3.42%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 4         | 3.42%   |
| Intel Wireless 7265                                                           | 4         | 3.42%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 3         | 2.56%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]    | 3         | 2.56%   |
| Ralink MT7601U Wireless Adapter                                               | 2         | 1.71%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 1.71%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 2         | 1.71%   |
| Intel Wireless 7260                                                           | 2         | 1.71%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2         | 1.71%   |
| Intel Alder Lake-P PCH CNVi WiFi                                              | 2         | 1.71%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1         | 0.85%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1         | 0.85%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]           | 1         | 0.85%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                      | 1         | 0.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.85%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                        | 1         | 0.85%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 0.85%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1         | 0.85%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 1         | 0.85%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 1         | 0.85%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1         | 0.85%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 0.85%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                 | 1         | 0.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                 | 1         | 0.85%   |
| Intel Wireless 8260                                                           | 1         | 0.85%   |
| Intel Wi-Fi 6 AX201 160MHz                                                    | 1         | 0.85%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 1         | 0.85%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 0.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 0.85%   |
| Intel Centrino Advanced-N 6235                                                | 1         | 0.85%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                | 1         | 0.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 61        | 50%     |
| Intel                 | 51        | 41.8%   |
| Qualcomm Atheros      | 2         | 1.64%   |
| Broadcom              | 2         | 1.64%   |
| Xiaomi                | 1         | 0.82%   |
| Lenovo                | 1         | 0.82%   |
| Huawei Technologies   | 1         | 0.82%   |
| Google                | 1         | 0.82%   |
| Emulex                | 1         | 0.82%   |
| Aquantia              | 1         | 0.82%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 47        | 37.01%  |
| Realtek RTL8125 2.5GbE Controller                                             | 13        | 10.24%  |
| Intel I211 Gigabit Network Connection                                         | 7         | 5.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6         | 4.72%   |
| Intel Ethernet Controller I225-V                                              | 5         | 3.94%   |
| Intel I210 Gigabit Network Connection                                         | 4         | 3.15%   |
| Intel 82574L Gigabit Network Connection                                       | 4         | 3.15%   |
| Intel Ethernet Connection (4) I219-LM                                         | 3         | 2.36%   |
| Intel Ethernet Connection (14) I219-LM                                        | 3         | 2.36%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2         | 1.57%   |
| Intel Ethernet Connection (11) I219-LM                                        | 2         | 1.57%   |
| Intel Ethernet Connection (10) I219-V                                         | 2         | 1.57%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                          | 1         | 0.79%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 0.79%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1         | 0.79%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1         | 0.79%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                              | 1         | 0.79%   |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller                           | 1         | 0.79%   |
| Intel I350 Gigabit Network Connection                                         | 1         | 0.79%   |
| Intel Ethernet Controller X550                                                | 1         | 0.79%   |
| Intel Ethernet Controller I225-LM                                             | 1         | 0.79%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 1         | 0.79%   |
| Intel Ethernet Connection I219-LM                                             | 1         | 0.79%   |
| Intel Ethernet Connection I218-LM                                             | 1         | 0.79%   |
| Intel Ethernet Connection I217-LM                                             | 1         | 0.79%   |
| Intel Ethernet Connection (7) I219-V                                          | 1         | 0.79%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1         | 0.79%   |
| Intel Ethernet Connection (5) I219-V                                          | 1         | 0.79%   |
| Intel Ethernet Connection (4) I219-V                                          | 1         | 0.79%   |
| Intel Ethernet Connection (3) I218-LM                                         | 1         | 0.79%   |
| Intel Ethernet Connection (2) I219-V                                          | 1         | 0.79%   |
| Intel Ethernet Connection (16) I219-LM                                        | 1         | 0.79%   |
| Intel Ethernet Connection (13) I219-V                                         | 1         | 0.79%   |
| Intel Ethernet Connection (11) I219-V                                         | 1         | 0.79%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 0.79%   |
| Huawei USB Device                                                             | 1         | 0.79%   |
| Google Nexus/Pixel Device (charging + debug)                                  | 1         | 0.79%   |
| Emulex OneConnect 10Gb NIC (be3)                                              | 1         | 0.79%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                             | 1         | 0.79%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 1         | 0.79%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 112       | 51.14%  |
| WiFi     | 97        | 44.29%  |
| Modem    | 6         | 2.74%   |
| Unknown  | 4         | 1.83%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 92        | 61.74%  |
| WiFi     | 54        | 36.24%  |
| Modem    | 3         | 2.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 76        | 52.05%  |
| 1     | 40        | 27.4%   |
| 0     | 17        | 11.64%  |
| 3     | 9         | 6.16%   |
| 4     | 3         | 2.05%   |
| 7     | 1         | 0.68%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 128       | 84.21%  |
| Yes  | 24        | 15.79%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 58        | 74.36%  |
| IMC Networks                    | 4         | 5.13%   |
| Apple                           | 4         | 5.13%   |
| Broadcom                        | 3         | 3.85%   |
| Realtek Semiconductor           | 2         | 2.56%   |
| Qualcomm Atheros Communications | 2         | 2.56%   |
| Skylight Digital                | 1         | 1.28%   |
| Ralink                          | 1         | 1.28%   |
| Opticis                         | 1         | 1.28%   |
| Foxconn / Hon Hai               | 1         | 1.28%   |
| Cambridge Silicon Radio         | 1         | 1.28%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 18        | 23.08%  |
| Intel AX200 Bluetooth                               | 13        | 16.67%  |
| Intel Bluetooth wireless interface                  | 10        | 12.82%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 6         | 7.69%   |
| Intel AX210 Bluetooth                               | 5         | 6.41%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 5.13%   |
| IMC Networks Realtek Bluetooth Adapter              | 3         | 3.85%   |
| Apple Bluetooth Host Controller                     | 3         | 3.85%   |
| Realtek Bluetooth Adapter                           | 2         | 2.56%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 2.56%   |
| Skylight Digital Realtek Bluetooth Adapter          | 1         | 1.28%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.28%   |
| Opticis Realtek Bluetooth Adapter                   | 1         | 1.28%   |
| Intel Wireless Bluetooth                            | 1         | 1.28%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.28%   |
| IMC Networks Bluetooth module                       | 1         | 1.28%   |
| Foxconn / Hon Hai RZ616 Bluetooth Adapter           | 1         | 1.28%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.28%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.28%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.28%   |
| Broadcom BCM2035 Bluetooth dongle                   | 1         | 1.28%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 1.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 67        | 37.85%  |
| AMD                     | 55        | 31.07%  |
| Nvidia                  | 32        | 18.08%  |
| C-Media Electronics     | 4         | 2.26%   |
| Lenovo                  | 3         | 1.69%   |
| Logitech                | 2         | 1.13%   |
| CMX Systems             | 2         | 1.13%   |
| Yamaha                  | 1         | 0.56%   |
| Texas Instruments       | 1         | 0.56%   |
| SteelSeries ApS         | 1         | 0.56%   |
| RODE Microphones        | 1         | 0.56%   |
| JMTek                   | 1         | 0.56%   |
| GN Netcom               | 1         | 0.56%   |
| Generalplus Technology  | 1         | 0.56%   |
| Creative Labs           | 1         | 0.56%   |
| Blue Microphones        | 1         | 0.56%   |
| AudioQuest              | 1         | 0.56%   |
| ASUSTek Computer        | 1         | 0.56%   |
| AKAI  Professional M.I. | 1         | 0.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                  | 31        | 14.16%  |
| AMD Renoir Radeon High Definition Audio Controller                      | 17        | 7.76%   |
| Intel Comet Lake PCH cAVS                                               | 11        | 5.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                     | 10        | 4.57%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller     | 9         | 4.11%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller             | 8         | 3.65%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller          | 7         | 3.2%    |
| Intel Sunrise Point-LP HD Audio                                         | 6         | 2.74%   |
| Intel Comet Lake PCH-LP cAVS                                            | 6         | 2.74%   |
| Intel Cannon Lake PCH cAVS                                              | 6         | 2.74%   |
| AMD Starship/Matisse HD Audio Controller                                | 6         | 2.74%   |
| AMD Rembrandt Radeon High Definition Audio Controller                   | 6         | 2.74%   |
| Nvidia GP107GL High Definition Audio Controller                         | 5         | 2.28%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                     | 5         | 2.28%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                 | 4         | 1.83%   |
| Nvidia TU116 High Definition Audio Controller                           | 3         | 1.37%   |
| Intel Tiger Lake-H HD Audio Controller                                  | 3         | 1.37%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]               | 3         | 1.37%   |
| Nvidia GP108 High Definition Audio Controller                           | 2         | 0.91%   |
| Nvidia GK208 HDMI/DP Audio Controller                                   | 2         | 0.91%   |
| Nvidia GK107 HDMI Audio Controller                                      | 2         | 0.91%   |
| Nvidia GA104 High Definition Audio Controller                           | 2         | 0.91%   |
| Intel Wildcat Point-LP High Definition Audio Controller                 | 2         | 0.91%   |
| Intel Comet Lake PCH-V cAVS                                             | 2         | 0.91%   |
| Intel CM238 HD Audio Controller                                         | 2         | 0.91%   |
| Intel Broadwell-U Audio Controller                                      | 2         | 0.91%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                 | 2         | 0.91%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller     | 2         | 0.91%   |
| CMX Systems USB PnP Audio Device                                        | 2         | 0.91%   |
| AMD SBx00 Azalia (Intel HDA)                                            | 2         | 0.91%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 2         | 0.91%   |
| AMD Navi 10 HDMI Audio                                                  | 2         | 0.91%   |
| Yamaha Steinberg UR12                                                   | 1         | 0.46%   |
| Texas Instruments PCM2706 stereo audio DAC                              | 1         | 0.46%   |
| SteelSeries ApS SteelSeries Siberia 350                                 | 1         | 0.46%   |
| RODE Microphones RODE AI-1                                              | 1         | 0.46%   |
| Nvidia TU106 High Definition Audio Controller                           | 1         | 0.46%   |
| Nvidia TU104 HD Audio Controller                                        | 1         | 0.46%   |
| Nvidia High Definition Audio Controller                                 | 1         | 0.46%   |
| Nvidia GP106 High Definition Audio Controller                           | 1         | 0.46%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 30        | 21.9%   |
| SK hynix               | 19        | 13.87%  |
| Micron Technology      | 18        | 13.14%  |
| Kingston               | 16        | 11.68%  |
| Crucial                | 12        | 8.76%   |
| Corsair                | 6         | 4.38%   |
| Unknown                | 5         | 3.65%   |
| Unknown                | 5         | 3.65%   |
| G.Skill                | 4         | 2.92%   |
| Smart                  | 3         | 2.19%   |
| Ramaxel Technology     | 3         | 2.19%   |
| Team                   | 2         | 1.46%   |
| Goodram                | 2         | 1.46%   |
| A-DATA Technology      | 2         | 1.46%   |
| Unknown (000000000C01) | 1         | 0.73%   |
| Transcend              | 1         | 0.73%   |
| PNY                    | 1         | 0.73%   |
| Neo Forza              | 1         | 0.73%   |
| KLEVV                  | 1         | 0.73%   |
| Golden Empire          | 1         | 0.73%   |
| Gold Key               | 1         | 0.73%   |
| Elpida                 | 1         | 0.73%   |
| 0B45000080CE           | 1         | 0.73%   |
| 06F100000C01           | 1         | 0.73%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown                                                        | 5         | 3.5%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s          | 4         | 2.8%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 2         | 1.4%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s         | 2         | 1.4%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s         | 2         | 1.4%    |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s        | 2         | 1.4%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s          | 2         | 1.4%    |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s          | 2         | 1.4%    |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s           | 2         | 1.4%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s           | 2         | 1.4%    |
| Crucial RAM BL32G32C16S4B.M16FB1 32GB SODIMM DDR4 2667MT/s     | 2         | 1.4%    |
| Corsair RAM CMK32GX4M2D3200C16 16GB DIMM DDR4 3200MT/s         | 2         | 1.4%    |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 1         | 0.7%    |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                    | 1         | 0.7%    |
| Unknown RAM Module 1GB SODIMM DDR                              | 1         | 0.7%    |
| Unknown RAM 3000 C16 Series 4096MB DIMM DDR4 2933MT/s          | 1         | 0.7%    |
| Unknown RAM 2G-08-10-12-1333 2GB DIMM DDR3 1333MT/s            | 1         | 0.7%    |
| Unknown (000000000C01) RAM Module 32GB DIMM DDR4 3200MT/s      | 1         | 0.7%    |
| Transcend RAM JM2666HLE-32G 32GB DIMM DDR4 2666MT/s            | 1         | 0.7%    |
| Team RAM TEAMGROUP-UD4-4133 8GB DIMM DDR4 4133MT/s             | 1         | 0.7%    |
| Team RAM TEAMGROUP-SD4-3200 32GB SODIMM DDR4 3200MT/s          | 1         | 0.7%    |
| Smart RAM SF4641G8CK8IWGKSEG 8GB SODIMM DDR4 2133MT/s          | 1         | 0.7%    |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s          | 1         | 0.7%    |
| Smart RAM Module 8GB DIMM DDR4 2667MT/s                        | 1         | 0.7%    |
| SK hynix RAM Module 4GB SODIMM DDR3 1867MT/s                   | 1         | 0.7%    |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                   | 1         | 0.7%    |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s         | 1         | 0.7%    |
| SK hynix RAM HMAA4GU6CJR8N-XN 32GB DIMM DDR4 3200MT/s          | 1         | 0.7%    |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s         | 1         | 0.7%    |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s        | 1         | 0.7%    |
| SK hynix RAM HMA82GR7JJR8N-VK 16GB DIMM DDR4 2667MT/s          | 1         | 0.7%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 1         | 0.7%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s         | 1         | 0.7%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 1         | 0.7%    |
| SK hynix RAM HCNNNCRMBLPR-NEE 2GB Row Of Chips LPDDR4 4267MT/s | 1         | 0.7%    |
| Samsung RAM Module 4GB SODIMM DDR4 3200MT/s                    | 1         | 0.7%    |
| Samsung RAM M474A4G43AB1-CVF 32GB SODIMM DDR4 2933MT/s         | 1         | 0.7%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s          | 1         | 0.7%    |
| Samsung RAM M471B5674-M0-YK0 4GB Chip DDR3 1600MT/s            | 1         | 0.7%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 1         | 0.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 92        | 76.03%  |
| DDR3   | 16        | 13.22%  |
| DDR5   | 4         | 3.31%   |
| LPDDR5 | 3         | 2.48%   |
| LPDDR4 | 3         | 2.48%   |
| LPDDR3 | 2         | 1.65%   |
| DDR    | 1         | 0.83%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 75        | 61.98%  |
| DIMM         | 37        | 30.58%  |
| Row Of Chips | 8         | 6.61%   |
| Chip         | 1         | 0.83%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 44        | 35.2%   |
| 16384 | 40        | 32%     |
| 32768 | 19        | 15.2%   |
| 4096  | 16        | 12.8%   |
| 2048  | 5         | 4%      |
| 1024  | 1         | 0.8%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 44        | 34.65%  |
| 2667    | 25        | 19.69%  |
| 2400    | 12        | 9.45%   |
| 1600    | 8         | 6.3%    |
| 1867    | 6         | 4.72%   |
| 2666    | 5         | 3.94%   |
| 2133    | 5         | 3.94%   |
| 4800    | 3         | 2.36%   |
| 4267    | 3         | 2.36%   |
| 2933    | 3         | 2.36%   |
| 4266    | 2         | 1.57%   |
| 3600    | 2         | 1.57%   |
| 1333    | 2         | 1.57%   |
| 6400    | 1         | 0.79%   |
| 5200    | 1         | 0.79%   |
| 4133    | 1         | 0.79%   |
| 3000    | 1         | 0.79%   |
| 1866    | 1         | 0.79%   |
| 1334    | 1         | 0.79%   |
| Unknown | 1         | 0.79%   |

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
| Chicony Electronics                    | 17        | 20.99%  |
| IMC Networks                           | 12        | 14.81%  |
| Microdia                               | 9         | 11.11%  |
| Logitech                               | 9         | 11.11%  |
| Realtek Semiconductor                  | 7         | 8.64%   |
| Lite-On Technology                     | 5         | 6.17%   |
| Bison Electronics                      | 5         | 6.17%   |
| Sunplus Innovation Technology          | 4         | 4.94%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.7%    |
| Syntek                                 | 2         | 2.47%   |
| Shenzhen Kingcome Optoelectronic       | 2         | 2.47%   |
| Apple                                  | 2         | 2.47%   |
| Trust                                  | 1         | 1.23%   |
| Luxvisions Innotech Limited            | 1         | 1.23%   |
| GEMBIRD                                | 1         | 1.23%   |
| Aveo Technology                        | 1         | 1.23%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                         | 9         | 10.98%  |
| Chicony Integrated Camera                              | 8         | 9.76%   |
| Logitech Webcam C270                                   | 3         | 3.66%   |
| Lite-On Integrated Camera                              | 3         | 3.66%   |
| Chicony Integrated HP HD Webcam                        | 3         | 3.66%   |
| Bison Integrated Camera                                | 3         | 3.66%   |
| Sunplus Integrated_Webcam_HD                           | 2         | 2.44%   |
| Realtek USB 2.0 Webcam                                 | 2         | 2.44%   |
| Realtek Laptop Camera                                  | 2         | 2.44%   |
| Microdia USB Camera                                    | 2         | 2.44%   |
| Microdia Integrated Webcam                             | 2         | 2.44%   |
| Microdia HP Integrated Webcam                          | 2         | 2.44%   |
| Logitech C920 PRO HD Webcam                            | 2         | 2.44%   |
| Lite-On HP HD Camera                                   | 2         | 2.44%   |
| IMC Networks Realtek PC Camera                         | 2         | 2.44%   |
| Chicony ThinkPad T490 Webcam                           | 2         | 2.44%   |
| Bison HD Webcam                                        | 2         | 2.44%   |
| Apple FaceTime HD Camera (Built-in)                    | 2         | 2.44%   |
| Trust Canyon CNS-CWC6 Webcam                           | 1         | 1.22%   |
| Syntek Lenovo EasyCamera                               | 1         | 1.22%   |
| Syntek Integrated Camera                               | 1         | 1.22%   |
| Sunplus SPCA2650 AV Camera                             | 1         | 1.22%   |
| Sunplus Integrated_Webcam_FHD                          | 1         | 1.22%   |
| Shenzhen Kingcome Optoelectronic XiaoMi USB 2.0 Webcam | 1         | 1.22%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera        | 1         | 1.22%   |
| Realtek USB 2.0 PC Camera                              | 1         | 1.22%   |
| Realtek Integrated_Webcam_HD                           | 1         | 1.22%   |
| Realtek Composite Webcam                               | 1         | 1.22%   |
| Microdia USB 2.0 Camera                                | 1         | 1.22%   |
| Microdia Integrated_Webcam_FHD                         | 1         | 1.22%   |
| Microdia Dell Integrated HD Webcam                     | 1         | 1.22%   |
| Luxvisions Innotech Limited HP HD Camera               | 1         | 1.22%   |
| Logitech Webcam C170                                   | 1         | 1.22%   |
| Logitech HD Pro Webcam C920                            | 1         | 1.22%   |
| Logitech C505 HD Webcam                                | 1         | 1.22%   |
| Logitech BRIO Ultra HD Webcam                          | 1         | 1.22%   |
| IMC Networks EasyCamera                                | 1         | 1.22%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]      | 1         | 1.22%   |
| Chicony USB2.0 0.3M UVC WebCam                         | 1         | 1.22%   |
| Chicony Integrated IR Camera                           | 1         | 1.22%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


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

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


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

![Unsupported Devices](./images/pie_chart_bsd/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 45        | 29.03%  |
| 2     | 39        | 25.16%  |
| 1     | 32        | 20.65%  |
| 4     | 18        | 11.61%  |
| 3     | 16        | 10.32%  |
| 5     | 4         | 2.58%   |
| 9     | 1         | 0.65%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 77        | 36.67%  |
| Bluetooth                | 43        | 20.48%  |
| Net/wireless             | 32        | 15.24%  |
| Fingerprint reader       | 26        | 12.38%  |
| Card reader              | 12        | 5.71%   |
| Net/ethernet             | 6         | 2.86%   |
| Sound                    | 5         | 2.38%   |
| Network                  | 4         | 1.9%    |
| Firewire controller      | 3         | 1.43%   |
| Storage/raid             | 1         | 0.48%   |
| Modem                    | 1         | 0.48%   |

