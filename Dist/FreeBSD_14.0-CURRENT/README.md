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

Total: 209

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
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
| amd64 | 107       | 81.06%  |
| arm64 | 21        | 15.91%  |
| arm   | 2         | 1.52%   |
| riscv | 1         | 0.76%   |
| i386  | 1         | 0.76%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 36        | 26.28%  |
| KDE5          | 34        | 24.82%  |
| XFCE          | 17        | 12.41%  |
| MATE          | 9         | 6.57%   |
| TWM           | 7         | 5.11%   |
| GNOME         | 7         | 5.11%   |
| i3            | 6         | 4.38%   |
| Openbox       | 3         | 2.19%   |
| LXQt          | 3         | 2.19%   |
| Cinnamon      | 3         | 2.19%   |
| LXDE          | 2         | 1.46%   |
| Lumina        | 2         | 1.46%   |
| Xfwm4         | 1         | 0.73%   |
| sway          | 1         | 0.73%   |
| spectrwm      | 1         | 0.73%   |
| Picom         | 1         | 0.73%   |
| GNUstep       | 1         | 0.73%   |
| Fluxbox       | 1         | 0.73%   |
| Enlightenment | 1         | 0.73%   |
| ctwm          | 1         | 0.73%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 94        | 69.12%  |
| Console | 39        | 28.68%  |
| Wayland | 3         | 2.21%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 65        | 48.15%  |
| SDDM    | 31        | 22.96%  |
| SLiM    | 15        | 11.11%  |
| GDM     | 11        | 8.15%   |
| XDM     | 8         | 5.93%   |
| LightDM | 4         | 2.96%   |
| Ly      | 1         | 0.74%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang             | Computers | Percent |
|------------------|-----------|---------|
| C                | 86        | 64.18%  |
| en_US            | 20        | 14.93%  |
| Unknown          | 6         | 4.48%   |
| de_DE            | 5         | 3.73%   |
| uk_UA            | 3         | 2.24%   |
| ru_RU            | 3         | 2.24%   |
| zh_CN            | 2         | 1.49%   |
| en_GB            | 2         | 1.49%   |
| sv_SE            | 1         | 0.75%   |
| pt_PT            | 1         | 0.75%   |
| pl_PL            | 1         | 0.75%   |
| it_IT.ISO8859-15 | 1         | 0.75%   |
| fr_FR            | 1         | 0.75%   |
| en_CA            | 1         | 0.75%   |
| de_CH            | 1         | 0.75%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 120       | 90.91%  |
| BIOS | 12        | 9.09%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 96        | 72.73%  |
| Ufs  | 35        | 26.52%  |
| Nfs  | 1         | 0.76%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 123       | 93.18%  |
| MBR  | 9         | 6.82%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 26        | 19.7%   |
| Unknown                        | 18        | 13.64%  |
| ASUSTek Computer               | 15        | 11.36%  |
| Dell                           | 13        | 9.85%   |
| Hewlett-Packard                | 10        | 7.58%   |
| Gigabyte Technology            | 8         | 6.06%   |
| MSI                            | 6         | 4.55%   |
| ASRock                         | 5         | 3.79%   |
| Raspberry Pi Foundation        | 4         | 3.03%   |
| Apple                          | 3         | 2.27%   |
| Intel                          | 2         | 1.52%   |
| Framework                      | 2         | 1.52%   |
| F-Plus Mobile                  | 2         | 1.52%   |
| Beckhoff Automation            | 2         | 1.52%   |
| Valve                          | 1         | 0.76%   |
| Timi                           | 1         | 0.76%   |
| System76                       | 1         | 0.76%   |
| SolidRun                       | 1         | 0.76%   |
| Samsung Electronics            | 1         | 0.76%   |
| pine64                         | 1         | 0.76%   |
| Notebook                       | 1         | 0.76%   |
| Matsushita Electric Industrial | 1         | 0.76%   |
| khadas                         | 1         | 0.76%   |
| HUAWEI                         | 1         | 0.76%   |
| Google                         | 1         | 0.76%   |
| friendlyelec                   | 1         | 0.76%   |
| AZW                            | 1         | 0.76%   |
| Avell High Performance         | 1         | 0.76%   |
| ASRockRack                     | 1         | 0.76%   |
| A-DATA Technology              | 1         | 0.76%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 19        | 14.39%  |
| RPi Raspberry Pi                            | 3         | 2.27%   |
| HP EliteBook 8570p                          | 3         | 2.27%   |
| Framework Laptop                            | 2         | 1.52%   |
| F-Plus Mobile FLAPTOP r                     | 2         | 1.52%   |
| Valve Jupiter                               | 1         | 0.76%   |
| Timi Redmi Book Pro 14 2022                 | 1         | 0.76%   |
| System76 Gazelle                            | 1         | 0.76%   |
| SolidRun CEX7 Platform                      | 1         | 0.76%   |
| Samsung 750XEE                              | 1         | 0.76%   |
| RPi rpi                                     | 1         | 0.76%   |
| pine64 pinebook-pro-rk3399                  | 1         | 0.76%   |
| Notebook NS50_70MU                          | 1         | 0.76%   |
| MSI MS-7C79                                 | 1         | 0.76%   |
| MSI MS-7C75                                 | 1         | 0.76%   |
| MSI MS-7B89                                 | 1         | 0.76%   |
| MSI MS-7B86                                 | 1         | 0.76%   |
| MSI GE76 Raider 10UG                        | 1         | 0.76%   |
| MSI Bravo 15 A4DDR                          | 1         | 0.76%   |
| Matsushita Electric Industrial CF-T2BW1AXR  | 1         | 0.76%   |
| Lenovo XiaoXinPro-13ARE 2020 82DM           | 1         | 0.76%   |
| Lenovo ThinkPad X395 20NL001SMX             | 1         | 0.76%   |
| Lenovo ThinkPad X395 20NL000GPG             | 1         | 0.76%   |
| Lenovo ThinkPad X270 20HM004JBR             | 1         | 0.76%   |
| Lenovo ThinkPad X260 20F5A28AUK             | 1         | 0.76%   |
| Lenovo ThinkPad X13 Gen 1 20T2003PRT        | 1         | 0.76%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TLA055CD | 1         | 0.76%   |
| Lenovo ThinkPad X1 Extreme 20MF000BUS       | 1         | 0.76%   |
| Lenovo ThinkPad X1 Carbon 6th 20KHCTO1WW    | 1         | 0.76%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS1QC00    | 1         | 0.76%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS0BT00    | 1         | 0.76%   |
| Lenovo ThinkPad T495s 20QKS1812F            | 1         | 0.76%   |
| Lenovo ThinkPad T495 20NJ0010PB             | 1         | 0.76%   |
| Lenovo ThinkPad T470p 20J7S0PM00            | 1         | 0.76%   |
| Lenovo ThinkPad T430 2349H2G                | 1         | 0.76%   |
| Lenovo ThinkPad T14s Gen 2i 20WM00B7MX      | 1         | 0.76%   |
| Lenovo ThinkPad P15 Gen 1 20ST005VRT        | 1         | 0.76%   |
| Lenovo ThinkPad P14s Gen 1 20Y1CTO1WW       | 1         | 0.76%   |
| Lenovo ThinkPad E14 Gen 3 20Y7003SGE        | 1         | 0.76%   |
| Lenovo ThinkPad E14 20RBCTO1WW              | 1         | 0.76%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo ThinkPad                            | 19        | 14.39%  |
| Unknown                                    | 19        | 14.39%  |
| ASUS PRIME                                 | 7         | 5.3%    |
| HP ProBook                                 | 4         | 3.03%   |
| HP EliteBook                               | 4         | 3.03%   |
| Dell Latitude                              | 4         | 3.03%   |
| RPi Raspberry                              | 3         | 2.27%   |
| Dell OptiPlex                              | 3         | 2.27%   |
| Lenovo Legion                              | 2         | 1.52%   |
| Lenovo IdeaPad                             | 2         | 1.52%   |
| Gigabyte X570                              | 2         | 1.52%   |
| Gigabyte B450M                             | 2         | 1.52%   |
| Framework Laptop                           | 2         | 1.52%   |
| F-Plus Mobile FLAPTOP                      | 2         | 1.52%   |
| ASUS ROG                                   | 2         | 1.52%   |
| Valve Jupiter                              | 1         | 0.76%   |
| Timi Redmi                                 | 1         | 0.76%   |
| System76 Gazelle                           | 1         | 0.76%   |
| SolidRun CEX7                              | 1         | 0.76%   |
| Samsung 750XEE                             | 1         | 0.76%   |
| RPi rpi                                    | 1         | 0.76%   |
| pine64 pinebook-pro-rk3399                 | 1         | 0.76%   |
| Notebook NS50                              | 1         | 0.76%   |
| MSI MS-7C79                                | 1         | 0.76%   |
| MSI MS-7C75                                | 1         | 0.76%   |
| MSI MS-7B89                                | 1         | 0.76%   |
| MSI MS-7B86                                | 1         | 0.76%   |
| MSI GE76                                   | 1         | 0.76%   |
| MSI Bravo                                  | 1         | 0.76%   |
| Matsushita Electric Industrial CF-T2BW1AXR | 1         | 0.76%   |
| Lenovo XiaoXinPro-13ARE                    | 1         | 0.76%   |
| Lenovo ThinkBook                           | 1         | 0.76%   |
| khadas edge-v                              | 1         | 0.76%   |
| Intel S2600WTTR                            | 1         | 0.76%   |
| Intel NUC11PHi7                            | 1         | 0.76%   |
| HUAWEI HN-WX9X                             | 1         | 0.76%   |
| HP ZBook                                   | 1         | 0.76%   |
| HP EliteDesk                               | 1         | 0.76%   |
| Google Akemi                               | 1         | 0.76%   |
| Gigabyte X670E                             | 1         | 0.76%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 31        | 23.48%  |
| 2020    | 30        | 22.73%  |
| Unknown | 17        | 12.88%  |
| 2019    | 15        | 11.36%  |
| 2022    | 12        | 9.09%   |
| 2018    | 7         | 5.3%    |
| 2017    | 4         | 3.03%   |
| 2013    | 4         | 3.03%   |
| 2023    | 3         | 2.27%   |
| 2015    | 3         | 2.27%   |
| 2016    | 2         | 1.52%   |
| 2014    | 1         | 0.76%   |
| 2012    | 1         | 0.76%   |
| 2011    | 1         | 0.76%   |
| 2003    | 1         | 0.76%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 66        | 50%     |
| Desktop        | 53        | 40.15%  |
| System on chip | 7         | 5.3%    |
| Mini pc        | 3         | 2.27%   |
| Server         | 2         | 1.52%   |
| All in one     | 1         | 0.76%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 130       | 98.48%  |
| Yes  | 2         | 1.52%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 48        | 35.82%  |
| 8.01-16.0       | 24        | 17.91%  |
| 32.01-64.0      | 21        | 15.67%  |
| 64.01-256.0     | 19        | 14.18%  |
| 4.01-8.0        | 9         | 6.72%   |
| 3.01-4.0        | 7         | 5.22%   |
| 0.51-1.0        | 2         | 1.49%   |
| More than 256.0 | 1         | 0.75%   |
| 24.01-32.0      | 1         | 0.75%   |
| 1.01-2.0        | 1         | 0.75%   |
| 0.01-0.5        | 1         | 0.75%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.51-1.0    | 41        | 30.37%  |
| 1.01-2.0    | 37        | 27.41%  |
| 0.01-0.5    | 27        | 20%     |
| 2.01-3.0    | 14        | 10.37%  |
| 3.01-4.0    | 6         | 4.44%   |
| 4.01-8.0    | 2         | 1.48%   |
| 24.01-32.0  | 2         | 1.48%   |
| 0           | 2         | 1.48%   |
| 32.01-64.0  | 1         | 0.74%   |
| 64.01-256.0 | 1         | 0.74%   |
| 16.01-24.0  | 1         | 0.74%   |
| 8.01-16.0   | 1         | 0.74%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 64        | 46.04%  |
| 2      | 34        | 24.46%  |
| 0      | 20        | 14.39%  |
| 3      | 9         | 6.47%   |
| 6      | 5         | 3.6%    |
| 4      | 4         | 2.88%   |
| 15     | 1         | 0.72%   |
| 7      | 1         | 0.72%   |
| 5      | 1         | 0.72%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 117       | 87.31%  |
| Yes       | 17        | 12.69%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 101       | 76.52%  |
| No        | 31        | 23.48%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 87        | 65.91%  |
| No        | 45        | 34.09%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 68        | 51.13%  |
| No        | 65        | 48.87%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 22        | 16.67%  |
| Russia       | 22        | 16.67%  |
| Germany      | 15        | 11.36%  |
| UK           | 13        | 9.85%   |
| Poland       | 6         | 4.55%   |
| Brazil       | 6         | 4.55%   |
| Ukraine      | 5         | 3.79%   |
| Japan        | 4         | 3.03%   |
| China        | 4         | 3.03%   |
| Austria      | 4         | 3.03%   |
| Portugal     | 3         | 2.27%   |
| Turkey       | 2         | 1.52%   |
| Switzerland  | 2         | 1.52%   |
| Sweden       | 2         | 1.52%   |
| Romania      | 2         | 1.52%   |
| Netherlands  | 2         | 1.52%   |
| France       | 2         | 1.52%   |
| Denmark      | 2         | 1.52%   |
| Canada       | 2         | 1.52%   |
| Taiwan       | 1         | 0.76%   |
| Spain        | 1         | 0.76%   |
| Singapore    | 1         | 0.76%   |
| Saudi Arabia | 1         | 0.76%   |
| Peru         | 1         | 0.76%   |
| Jamaica      | 1         | 0.76%   |
| Italy        | 1         | 0.76%   |
| India        | 1         | 0.76%   |
| Croatia      | 1         | 0.76%   |
| Colombia     | 1         | 0.76%   |
| Belarus      | 1         | 0.76%   |
| Bangladesh   | 1         | 0.76%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Moscow                      | 9         | 6.08%   |
| Krasnodar                   | 6         | 4.05%   |
| Brighton                    | 5         | 3.38%   |
| St Petersburg               | 4         | 2.7%    |
| Vienna                      | 3         | 2.03%   |
| Seattle                     | 3         | 2.03%   |
| London                      | 3         | 2.03%   |
| Kyiv                        | 3         | 2.03%   |
| ЕЊta-ku                   | 2         | 1.35%   |
| Zurich                      | 2         | 1.35%   |
| Vancouver                   | 2         | 1.35%   |
| Shoreham-by-Sea             | 2         | 1.35%   |
| Rio de Janeiro              | 2         | 1.35%   |
| Rietberg                    | 2         | 1.35%   |
| Northeim                    | 2         | 1.35%   |
| Istanbul                    | 2         | 1.35%   |
| Graz                        | 2         | 1.35%   |
| Fuchu                       | 2         | 1.35%   |
| Fremont                     | 2         | 1.35%   |
| Egham                       | 2         | 1.35%   |
| Chicago                     | 2         | 1.35%   |
| Cambridge                   | 2         | 1.35%   |
| Berlin                      | 2         | 1.35%   |
| Albuquerque                 | 2         | 1.35%   |
| Zaporizhzhya                | 1         | 0.68%   |
| Wuhan                       | 1         | 0.68%   |
| Woodburn                    | 1         | 0.68%   |
| Wieliczka                   | 1         | 0.68%   |
| Washington                  | 1         | 0.68%   |
| Warsaw                      | 1         | 0.68%   |
| Voznesensk                  | 1         | 0.68%   |
| Vila Real de Santo António | 1         | 0.68%   |
| Tynda                       | 1         | 0.68%   |
| Trosa                       | 1         | 0.68%   |
| Thrissur                    | 1         | 0.68%   |
| Teaneck                     | 1         | 0.68%   |
| Taipei                      | 1         | 0.68%   |
| Stuttgart                   | 1         | 0.68%   |
| Stolberg                    | 1         | 0.68%   |
| Sollentuna                  | 1         | 0.68%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 35        | 54     | 21.21%  |
| WDC                 | 30        | 49     | 18.18%  |
| Toshiba             | 14        | 26     | 8.48%   |
| Seagate             | 13        | 29     | 7.88%   |
| Crucial             | 12        | 21     | 7.27%   |
| Kingston            | 7         | 10     | 4.24%   |
| HGST                | 7         | 26     | 4.24%   |
| Intel               | 6         | 9      | 3.64%   |
| A-DATA Technology   | 6         | 6      | 3.64%   |
| SK hynix            | 5         | 5      | 3.03%   |
| Micron Technology   | 5         | 6      | 3.03%   |
| KIOXIA              | 5         | 5      | 3.03%   |
| FORESEE             | 3         | 3      | 1.82%   |
| Apple               | 3         | 3      | 1.82%   |
| SSSTC               | 2         | 2      | 1.21%   |
| SPCC                | 1         | 1      | 0.61%   |
| Solid State Storage | 1         | 1      | 0.61%   |
| Silicon Motion      | 1         | 1      | 0.61%   |
| SanDisk             | 1         | 2      | 0.61%   |
| PNY                 | 1         | 1      | 0.61%   |
| Mushkin             | 1         | 1      | 0.61%   |
| LSI                 | 1         | 4      | 0.61%   |
| LITEON              | 1         | 1      | 0.61%   |
| Hitachi             | 1         | 2      | 0.61%   |
| GOODRAM             | 1         | 1      | 0.61%   |
| Fujitsu             | 1         | 2      | 0.61%   |
| Apacer              | 1         | 1      | 0.61%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB             | 6         | 3.26%   |
| HGST HTS725050A7E630 500GB           | 4         | 2.17%   |
| WDC WDS100T3X0C-00SJG0 1TB           | 3         | 1.63%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 3         | 1.63%   |
| Toshiba MQ04ABF100 1TB               | 3         | 1.63%   |
| Samsung SSD 980 PRO 1TB              | 3         | 1.63%   |
| Samsung SSD 970 EVO Plus 1TB         | 3         | 1.63%   |
| Samsung SSD 870 EVO 1TB              | 3         | 1.63%   |
| Samsung SSD 860 EVO 250GB            | 3         | 1.63%   |
| Samsung HM251JX 250GB                | 3         | 1.63%   |
| HGST HTS721010A9E630 1TB             | 3         | 1.63%   |
| WDC WDS100T1X0E-00AFY0 1TB           | 2         | 1.09%   |
| WDC WD30EFRX-68EUZN0 3TB             | 2         | 1.09%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB   | 2         | 1.09%   |
| WDC PC SN730 NVMe 1024GB             | 2         | 1.09%   |
| Seagate ST1000LM049-2GH172 1TB       | 2         | 1.09%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 1.09%   |
| Samsung SSD 850 EVO 250GB            | 2         | 1.09%   |
| Samsung MZVLB512HBJQ-000L7 512GB     | 2         | 1.09%   |
| KIOXIA KBG40ZNS256G NVMe 256GB       | 2         | 1.09%   |
| Kingston SA2000M81000G 1TB           | 2         | 1.09%   |
| FORESEE XP1000F001T 1TB              | 2         | 1.09%   |
| Crucial CT750MX300SSD1 752GB         | 2         | 1.09%   |
| Apple SSD SM256E 256GB               | 2         | 1.09%   |
| WDC WDS500G1X0E-00AFY0 500GB         | 1         | 0.54%   |
| WDC WDS250G2B0C-00PXH0 250GB         | 1         | 0.54%   |
| WDC WDS100T2B0A-00SM50 1TB           | 1         | 0.54%   |
| WDC WD60EFRX-68TGBN1 6TB             | 1         | 0.54%   |
| WDC WD5002ABYS-18B1B0 500GB          | 1         | 0.54%   |
| WDC WD40EZRZ-75GXCB0 4TB             | 1         | 0.54%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 1         | 0.54%   |
| WDC WD20EFRX-68AX9N0 2TB             | 1         | 0.54%   |
| WDC WD120EFAX-68UNTN0 12TB           | 1         | 0.54%   |
| WDC WD10SPZX-60Z10T0 1TB             | 1         | 0.54%   |
| WDC WD10SPZX-21Z10T0 1TB             | 1         | 0.54%   |
| WDC WD10JPVX-00JC3T0 1TB             | 1         | 0.54%   |
| WDC WD10JMVW-11AJGS3 1TB             | 1         | 0.54%   |
| WDC WD10EZEX-60WN4A0 1TB             | 1         | 0.54%   |
| WDC WD10EZEX-21WN4A0 1TB             | 1         | 0.54%   |
| WDC WD10EZEX-00RKKA0 1TB             | 1         | 0.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 13        | 19     | 24.53%  |
| Toshiba             | 13        | 25     | 24.53%  |
| Seagate             | 13        | 29     | 24.53%  |
| HGST                | 7         | 26     | 13.21%  |
| Samsung Electronics | 4         | 7      | 7.55%   |
| LSI                 | 1         | 4      | 1.89%   |
| Hitachi             | 1         | 2      | 1.89%   |
| Fujitsu             | 1         | 2      | 1.89%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 18     | 31.71%  |
| Crucial             | 8         | 13     | 19.51%  |
| A-DATA Technology   | 4         | 4      | 9.76%   |
| Kingston            | 3         | 5      | 7.32%   |
| Intel               | 3         | 6      | 7.32%   |
| Apple               | 3         | 3      | 7.32%   |
| WDC                 | 1         | 2      | 2.44%   |
| SK hynix            | 1         | 1      | 2.44%   |
| SanDisk             | 1         | 2      | 2.44%   |
| Micron Technology   | 1         | 1      | 2.44%   |
| LITEON              | 1         | 1      | 2.44%   |
| GOODRAM             | 1         | 1      | 2.44%   |
| Apacer              | 1         | 1      | 2.44%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 70        | 100    | 47.3%   |
| SSD  | 40        | 58     | 27.03%  |
| HDD  | 38        | 114    | 25.68%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 70        | 100    | 51.47%  |
| SATA | 66        | 172    | 48.53%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 39        | 74     | 44.83%  |
| 0.51-1.0   | 27        | 50     | 31.03%  |
| 1.01-2.0   | 7         | 9      | 8.05%   |
| 4.01-10.0  | 5         | 24     | 5.75%   |
| 3.01-4.0   | 3         | 4      | 3.45%   |
| 2.01-3.0   | 3         | 4      | 3.45%   |
| 10.01-20.0 | 2         | 3      | 2.3%    |
| 20.01-50.0 | 1         | 4      | 1.15%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 36        | 26.09%  |
| 251-500        | 34        | 24.64%  |
| 501-1000       | 22        | 15.94%  |
| 1-20           | 12        | 8.7%    |
| 21-50          | 11        | 7.97%   |
| 51-100         | 10        | 7.25%   |
| 1001-2000      | 6         | 4.35%   |
| 2001-3000      | 4         | 2.9%    |
| More than 3000 | 3         | 2.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 90        | 64.75%  |
| 21-50          | 31        | 22.3%   |
| 101-250        | 8         | 5.76%   |
| 251-500        | 2         | 1.44%   |
| 1001-2000      | 2         | 1.44%   |
| 501-1000       | 2         | 1.44%   |
| 51-100         | 2         | 1.44%   |
| More than 3000 | 1         | 0.72%   |
| 0              | 1         | 0.72%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                     | Computers | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| HGST HTS725050A7E630 500GB                | 4         | 7      | 23.53%  |
| Samsung Electronics SSD 870 EVO 1TB       | 3         | 5      | 17.65%  |
| WDC WD60EFRX-68TGBN1 6TB                  | 1         | 3      | 5.88%   |
| WDC WD5002ABYS-18B1B0 500GB               | 1         | 1      | 5.88%   |
| WDC WD10SPZX-60Z10T0 1TB                  | 1         | 1      | 5.88%   |
| Seagate ST1000DM003-1CH162 1TB            | 1         | 1      | 5.88%   |
| Samsung Electronics SSD PM851 mSATA 256GB | 1         | 1      | 5.88%   |
| Samsung Electronics HM251JX 250GB         | 1         | 1      | 5.88%   |
| Kingston SA400S37120G 120GB               | 1         | 1      | 5.88%   |
| Hitachi HUA722020ALA331 2TB               | 1         | 2      | 5.88%   |
| HGST HTS721010A9E630 1TB                  | 1         | 14     | 5.88%   |
| Fujitsu MHS2040AT D 40GB                  | 1         | 2      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 7      | 31.25%  |
| HGST                | 4         | 21     | 25%     |
| WDC                 | 3         | 5      | 18.75%  |
| Seagate             | 1         | 1      | 6.25%   |
| Kingston            | 1         | 1      | 6.25%   |
| Hitachi             | 1         | 2      | 6.25%   |
| Fujitsu             | 1         | 2      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 4         | 21     | 36.36%  |
| WDC                 | 3         | 5      | 27.27%  |
| Seagate             | 1         | 1      | 9.09%   |
| Samsung Electronics | 1         | 1      | 9.09%   |
| Hitachi             | 1         | 2      | 9.09%   |
| Fujitsu             | 1         | 2      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 32     | 71.43%  |
| SSD  | 4         | 7      | 28.57%  |

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
| Works    | 107       | 223    | 84.92%  |
| Malfunc  | 14        | 39     | 11.11%  |
| Detected | 5         | 10     | 3.97%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 52        | 29.71%  |
| AMD                            | 33        | 18.86%  |
| Samsung Electronics            | 25        | 14.29%  |
| SanDisk                        | 19        | 10.86%  |
| Silicon Motion                 | 8         | 4.57%   |
| Micron Technology              | 5         | 2.86%   |
| Kingston Technology Company    | 5         | 2.86%   |
| SK hynix                       | 4         | 2.29%   |
| Micron/Crucial Technology      | 4         | 2.29%   |
| KIOXIA                         | 4         | 2.29%   |
| Solid State Storage Technology | 3         | 1.71%   |
| Toshiba                        | 2         | 1.14%   |
| Shenzhen Longsys Electronics   | 2         | 1.14%   |
| Marvell Technology Group       | 2         | 1.14%   |
| Broadcom / LSI                 | 2         | 1.14%   |
| ASMedia Technology             | 2         | 1.14%   |
| ADATA Technology               | 2         | 1.14%   |
| Phison Electronics             | 1         | 0.57%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 25        | 13.09%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 16        | 8.38%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 11        | 5.76%   |
| Intel Comet Lake SATA AHCI Controller                                          | 9         | 4.71%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 8         | 4.19%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 3.66%   |
| AMD 400 Series Chipset SATA Controller                                         | 7         | 3.66%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 6         | 3.14%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 6         | 3.14%   |
| Samsung NVMe SSD Controller 980                                                | 5         | 2.62%   |
| AMD 500 Series Chipset SATA Controller                                         | 5         | 2.62%   |
| Unknown                                                                        | 5         | 2.62%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 2.09%   |
| Micron NVMe Storage Controller                                                 | 4         | 2.09%   |
| Solid State Storage CL1                                                        | 3         | 1.57%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 3         | 1.57%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 3         | 1.57%   |
| Kingston Company A2000 NVMe SSD                                                | 3         | 1.57%   |
| Toshiba XG6 NVMe SSD Controller                                                | 2         | 1.05%   |
| SK hynix BC511                                                                 | 2         | 1.05%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 1.05%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 1.05%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 1.05%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2         | 1.05%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 1.05%   |
| Intel SSD 660P Series                                                          | 2         | 1.05%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 1.05%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 1.05%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.05%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 2         | 1.05%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 2         | 1.05%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 1.05%   |
| SK hynix Platinum P41 NVMe Solid State Drive 2TB                               | 1         | 0.52%   |
| SK hynix PC300 NVMe Solid State Drive 512GB                                    | 1         | 0.52%   |
| SanDisk NVMe Controller                                                        | 1         | 0.52%   |
| Samsung SM951 AHCI                                                             | 1         | 0.52%   |
| Phison E12 NVMe Controller                                                     | 1         | 0.52%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 1         | 0.52%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 1         | 0.52%   |
| Micron NVMe Controller                                                         | 1         | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 82        | 48.81%  |
| SATA | 78        | 46.43%  |
| IDE  | 4         | 2.38%   |
| RAID | 3         | 1.79%   |
| SAS  | 1         | 0.6%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 63        | 47.01%  |
| AMD      | 46        | 34.33%  |
| ARM      | 15        | 11.19%  |
| Unknown  | 8         | 5.97%   |
| Research | 1         | 0.75%   |
| NXP      | 1         | 0.75%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
|                                                 | 8         | 5.97%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 6         | 4.48%   |
| ARM Cortex-A55 r2p0                             | 6         | 4.48%   |
| Intel Core i5-10210U CPU @ 1.60GHz              | 5         | 3.73%   |
| Intel Core i7-3520M CPU @ 2.90GHz               | 4         | 2.99%   |
| ARM Cortex-A72 r0p3                             | 4         | 2.99%   |
| AMD Ryzen 5 5600G with Radeon Graphics          | 4         | 2.99%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 3         | 2.24%   |
| Intel Core i5-10300H CPU @ 2.50GHz              | 3         | 2.24%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 2         | 1.49%   |
| Intel Core i7-7600U CPU @ 2.80GHz               | 2         | 1.49%   |
| Intel Core i5-10500T CPU @ 2.30GHz              | 2         | 1.49%   |
| Intel Core i5-10400 CPU @ 2.90GHz               | 2         | 1.49%   |
| ARM Cortex-A72 r0p2                             | 2         | 1.49%   |
| ARM Cortex-A53 r0p4                             | 2         | 1.49%   |
| AMD Ryzen 9 5950X 16-Core Processor             | 2         | 1.49%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 2         | 1.49%   |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx | 2         | 1.49%   |
| AMD Ryzen 7 5825U with Radeon Graphics          | 2         | 1.49%   |
| AMD Ryzen 7 4800U with Radeon Graphics          | 2         | 1.49%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 2         | 1.49%   |
| AMD Ryzen 7 4700U with Radeon Graphics          | 2         | 1.49%   |
| AMD Ryzen 5 PRO 3500U w/ Radeon Vega Mobile Gfx | 2         | 1.49%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 2         | 1.49%   |
| Research Morello SoC r0p0                       | 1         | 0.75%   |
| NXP Cortex-A72                                  | 1         | 0.75%   |
| Intel Xeon W-10885M CPU @ 2.40GHz               | 1         | 0.75%   |
| Intel Xeon E-2334 CPU @ 3.40GHz                 | 1         | 0.75%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz             | 1         | 0.75%   |
| Intel Pentium M processor 1000MHz               | 1         | 0.75%   |
| Intel Core i7-9850H CPU @ 2.60GHz               | 1         | 0.75%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 1         | 0.75%   |
| Intel Core i7-8700 CPU @ 3.20GHz                | 1         | 0.75%   |
| Intel Core i7-8650U CPU @ 1.90GHz               | 1         | 0.75%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 0.75%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 0.75%   |
| Intel Core i7-5600U CPU @ 2.60GHz               | 1         | 0.75%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz              | 1         | 0.75%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz              | 1         | 0.75%   |
| Intel Core i7-4600U CPU @ 2.10GHz               | 1         | 0.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 29        | 21.8%   |
| Other                  | 23        | 17.29%  |
| Intel Core i5          | 17        | 12.78%  |
| ARM Cortex             | 14        | 10.53%  |
| AMD Ryzen 7            | 13        | 9.77%   |
| AMD Ryzen 5            | 13        | 9.77%   |
| AMD Ryzen 9            | 7         | 5.26%   |
| Intel Xeon             | 3         | 2.26%   |
| AMD Ryzen 7 PRO        | 3         | 2.26%   |
| AMD Ryzen 5 PRO        | 2         | 1.5%    |
| Intel Pentium M        | 1         | 0.75%   |
| Intel Atom             | 1         | 0.75%   |
| AMD Ryzen Threadripper | 1         | 0.75%   |
| AMD Ryzen Embedded     | 1         | 0.75%   |
| AMD Ryzen 3            | 1         | 0.75%   |
| AMD FX                 | 1         | 0.75%   |
| AMD EPYC               | 1         | 0.75%   |
| AMD E                  | 1         | 0.75%   |
| AMD Athlon             | 1         | 0.75%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 27        | 20.3%   |
| Unknown | 24        | 18.05%  |
| 8       | 19        | 14.29%  |
| 2       | 16        | 12.03%  |
| 6       | 14        | 10.53%  |
| 16      | 13        | 9.77%   |
| 12      | 10        | 7.52%   |
| 32      | 5         | 3.76%   |
| 24      | 3         | 2.26%   |
| 64      | 1         | 0.75%   |
| 1       | 1         | 0.75%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 113       | 84.96%  |
| Unknown | 19        | 14.29%  |
| 2       | 1         | 0.75%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 60        | 45.11%  |
| 1       | 48        | 36.09%  |
| Unknown | 25        | 18.8%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 36        | 27.07%  |
| KabyLake   | 17        | 12.78%  |
| CometLake  | 14        | 10.53%  |
| Zen 2      | 12        | 9.02%   |
| Zen 3      | 11        | 8.27%   |
| Zen+       | 10        | 7.52%   |
| IvyBridge  | 9         | 6.77%   |
| TigerLake  | 7         | 5.26%   |
| Zen        | 5         | 3.76%   |
| Haswell    | 3         | 2.26%   |
| Broadwell  | 3         | 2.26%   |
| Skylake    | 1         | 0.75%   |
| Silvermont | 1         | 0.75%   |
| Piledriver | 1         | 0.75%   |
| P6         | 1         | 0.75%   |
| IceLake    | 1         | 0.75%   |
| Bobcat     | 1         | 0.75%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 52        | 37.96%  |
| AMD                        | 43        | 31.39%  |
| Nvidia                     | 39        | 28.47%  |
| Matrox Electronics Systems | 2         | 1.46%   |
| ASPEED Technology          | 1         | 0.73%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                           | 9         | 6.47%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                            | 7         | 5.04%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series] | 7         | 5.04%   |
| Intel CometLake-U GT2 [UHD Graphics]                                 | 6         | 4.32%   |
| Intel CometLake-H GT2 [UHD Graphics]                                 | 5         | 3.6%    |
| Intel 3rd Gen Core processor Graphics Controller                     | 5         | 3.6%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]         | 5         | 3.6%    |
| Nvidia TU117M                                                        | 4         | 2.88%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                            | 4         | 2.88%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                             | 3         | 2.16%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                             | 3         | 2.16%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]     | 3         | 2.16%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                           | 2         | 1.44%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                           | 2         | 1.44%   |
| Nvidia GP108M [GeForce MX230]                                        | 2         | 1.44%   |
| Nvidia GP108 [GeForce GT 1030]                                       | 2         | 1.44%   |
| Nvidia GK208B [GeForce GT 710]                                       | 2         | 1.44%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                 | 2         | 1.44%   |
| Intel HD Graphics 620                                                | 2         | 1.44%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller          | 2         | 1.44%   |
| AMD Rembrandt [Radeon 680M]                                          | 2         | 1.44%   |
| AMD Lucienne                                                         | 2         | 1.44%   |
| AMD Barcelo                                                          | 2         | 1.44%   |
| Nvidia TU117M [GeForce MX450]                                        | 1         | 0.72%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                | 1         | 0.72%   |
| Nvidia TU117 [GeForce GTX 1650]                                      | 1         | 0.72%   |
| Nvidia TU116 [GeForce GTX 1660]                                      | 1         | 0.72%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                              | 1         | 0.72%   |
| Nvidia TU104GLM [Quadro RTX 5000 Mobile / Max-Q]                     | 1         | 0.72%   |
| Nvidia GT218 [GeForce 210]                                           | 1         | 0.72%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                           | 1         | 0.72%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                              | 1         | 0.72%   |
| Nvidia GP107GL [Quadro P620]                                         | 1         | 0.72%   |
| Nvidia GP107 [GeForce GTX 1050]                                      | 1         | 0.72%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                   | 1         | 0.72%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                  | 1         | 0.72%   |
| Nvidia GP104 [GeForce GTX 1080]                                      | 1         | 0.72%   |
| Nvidia GM206 [GeForce GTX 960]                                       | 1         | 0.72%   |
| Nvidia GM108M [GeForce MX130]                                        | 1         | 0.72%   |
| Nvidia GM108M [GeForce 940MX]                                        | 1         | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x AMD                  | 36        | 26.87%  |
| 1 x Intel                | 29        | 21.64%  |
| Other                    | 23        | 17.16%  |
| Intel + Nvidia           | 20        | 14.93%  |
| 1 x Nvidia               | 17        | 12.69%  |
| 2 x AMD                  | 2         | 1.49%   |
| 1 x Matrox               | 2         | 1.49%   |
| AMD + Nvidia             | 2         | 1.49%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.75%   |
| Intel + AMD              | 1         | 0.75%   |
| 1 x ASPEED               | 1         | 0.75%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 83        | 62.88%  |
| Proprietary | 26        | 19.7%   |
| Unknown     | 23        | 17.42%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 94        | 70.15%  |
| 1.01-2.0   | 11        | 8.21%   |
| 0.51-1.0   | 7         | 5.22%   |
| 0.01-0.5   | 7         | 5.22%   |
| 3.01-4.0   | 6         | 4.48%   |
| 7.01-8.0   | 4         | 2.99%   |
| 5.01-6.0   | 2         | 1.49%   |
| 8.01-16.0  | 2         | 1.49%   |
| 2.01-3.0   | 1         | 0.75%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| BOE                 | 14        | 15.73%  |
| LG Display          | 10        | 11.24%  |
| AU Optronics        | 9         | 10.11%  |
| Dell                | 7         | 7.87%   |
| Goldstar            | 5         | 5.62%   |
| Philips             | 4         | 4.49%   |
| Hewlett-Packard     | 4         | 4.49%   |
| Chimei Innolux      | 4         | 4.49%   |
| Samsung Electronics | 3         | 3.37%   |
| LG Electronics      | 3         | 3.37%   |
| Sony                | 2         | 2.25%   |
| Sharp               | 2         | 2.25%   |
| RTK                 | 2         | 2.25%   |
| Lenovo              | 2         | 2.25%   |
| InfoVision          | 2         | 2.25%   |
| BenQ                | 2         | 2.25%   |
| Apple               | 2         | 2.25%   |
| ViewSonic           | 1         | 1.12%   |
| SDC                 | 1         | 1.12%   |
| PANDA               | 1         | 1.12%   |
| LGD                 | 1         | 1.12%   |
| Iiyama              | 1         | 1.12%   |
| Idek Iiyama         | 1         | 1.12%   |
| HKC                 | 1         | 1.12%   |
| HJW                 | 1         | 1.12%   |
| Eizo                | 1         | 1.12%   |
| CSO                 | 1         | 1.12%   |
| AOC                 | 1         | 1.12%   |
| Unknown             | 1         | 1.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0258 1600x900 350x190mm 15.7-inch            | 3         | 3.3%    |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                  | 3         | 3.3%    |
| RTK WCS Display RTK1A1B 1920x1080 344x195mm 15.6-inch                  | 2         | 2.2%    |
| Philips LCD Monitor PHL08C3 1920x1080 600x340mm 27.2-inch              | 2         | 2.2%    |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch           | 2         | 2.2%    |
| ViewSonic LCD Monitor VSCD22B 1920x1080 520x290mm 23.4-inch            | 1         | 1.1%    |
| Sony TV SNY4B03 1920x1080 930x520mm 41.9-inch                          | 1         | 1.1%    |
| Sony TV  *30 SNY05D1 3840x2160 1660x930mm 74.9-inch                    | 1         | 1.1%    |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 380x210mm 17.1-inch                | 1         | 1.1%    |
| Sharp LCD Monitor SHP14B9 3840x2160 340x190mm 15.3-inch                | 1         | 1.1%    |
| SDC LCD Monitor 3520x1080                                              | 1         | 1.1%    |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                       | 1         | 1.1%    |
| Samsung Electronics LCD Monitor SDC3754 1600x900 380x210mm 17.1-inch   | 1         | 1.1%    |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1020x570mm 46.0-inch | 1         | 1.1%    |
| Philips PHL 273V7 PHLC156 1920x1080 600x340mm 27.2-inch                | 1         | 1.1%    |
| Philips LCD Monitor 271P4 3520x1080                                    | 1         | 1.1%    |
| Philips LCD Monitor 271P4                                              | 1         | 1.1%    |
| PANDA LCD Monitor NCP004F 1920x1080 310x170mm 13.9-inch                | 1         | 1.1%    |
| LGD LCD Monitor 1920x1080                                              | 1         | 1.1%    |
| LG Electronics LCD Monitor LX20D 1600x1200                             | 1         | 1.1%    |
| LG Electronics LCD Monitor LG Ultra HD 11520x2160                      | 1         | 1.1%    |
| LG Electronics LCD Monitor LG Ultra HD                                 | 1         | 1.1%    |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                        | 1         | 1.1%    |
| LG Display LCD Monitor LGD062E 1920x1080 340x190mm 15.3-inch           | 1         | 1.1%    |
| LG Display LCD Monitor LGD060A 1920x1080 290x170mm 13.2-inch           | 1         | 1.1%    |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch           | 1         | 1.1%    |
| LG Display LCD Monitor LGD05F1 1920x1080 310x170mm 13.9-inch           | 1         | 1.1%    |
| LG Display LCD Monitor LGD033E 1366x768 310x170mm 13.9-inch            | 1         | 1.1%    |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                  | 1         | 1.1%    |
| Lenovo LEN P44w-10 LEN61D5 3840x1200 1050x330mm 43.3-inch              | 1         | 1.1%    |
| InfoVision LCD Monitor IVO8544 1920x1080 290x170mm 13.2-inch           | 1         | 1.1%    |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch           | 1         | 1.1%    |
| Iiyama PL2474H IVM6146 1920x1080 520x290mm 23.4-inch                   | 1         | 1.1%    |
| Idek Iiyama LCD Monitor PL2792UH 3840x2160                             | 1         | 1.1%    |
| HKC LCD Monitor HKC3D05 1920x1080 340x190mm 15.3-inch                  | 1         | 1.1%    |
| HJW HDMI TO USB HJW0001 1920x1080 700x390mm 31.5-inch                  | 1         | 1.1%    |
| Hewlett-Packard LCD Monitor LA2306 3520x1080                           | 1         | 1.1%    |
| Hewlett-Packard LA2306 HWP2949 1920x1080 510x290mm 23.1-inch           | 1         | 1.1%    |
| Hewlett-Packard E242 HWP326E 1920x1200 520x320mm 24.0-inch             | 1         | 1.1%    |
| Hewlett-Packard E233 HPN345F 1920x1080 510x290mm 23.1-inch             | 1         | 1.1%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 50        | 56.18%  |
| 3840x2160 (4K)    | 9         | 10.11%  |
| 1600x900 (HD+)    | 6         | 6.74%   |
| 2560x1440 (QHD)   | 4         | 4.49%   |
| 1920x1200 (WUXGA) | 4         | 4.49%   |
| 2256x1504         | 3         | 3.37%   |
| 1366x768 (WXGA)   | 3         | 3.37%   |
| 2560x1600         | 2         | 2.25%   |
| Unknown           | 2         | 2.25%   |
| 4480x1440         | 1         | 1.12%   |
| 3840x1200         | 1         | 1.12%   |
| 3520x1080         | 1         | 1.12%   |
| 2160x1440         | 1         | 1.12%   |
| 1600x1200         | 1         | 1.12%   |
| 11520x2160        | 1         | 1.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 24        | 27.59%  |
| 15      | 18        | 20.69%  |
| Unknown | 10        | 11.49%  |
| 27      | 9         | 10.34%  |
| 24      | 6         | 6.9%    |
| 23      | 6         | 6.9%    |
| 17      | 3         | 3.45%   |
| 12      | 3         | 3.45%   |
| 74      | 1         | 1.15%   |
| 46      | 1         | 1.15%   |
| 43      | 1         | 1.15%   |
| 41      | 1         | 1.15%   |
| 32      | 1         | 1.15%   |
| 31      | 1         | 1.15%   |
| 22      | 1         | 1.15%   |
| 21      | 1         | 1.15%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 32        | 37.21%  |
| 501-600     | 19        | 22.09%  |
| 201-300     | 13        | 15.12%  |
| Unknown     | 10        | 11.63%  |
| 351-400     | 3         | 3.49%   |
| 601-700     | 2         | 2.33%   |
| 401-500     | 2         | 2.33%   |
| 1001-1500   | 2         | 2.33%   |
| 701-800     | 1         | 1.16%   |
| 1501-2000   | 1         | 1.16%   |
| 901-1000    | 1         | 1.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 60        | 75%     |
| Unknown | 9         | 11.25%  |
| 16/10   | 7         | 8.75%   |
| 3/2     | 3         | 3.75%   |
| 3.18    | 1         | 1.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 19        | 21.84%  |
| 91-100         | 13        | 14.94%  |
| 201-250        | 10        | 11.49%  |
| Unknown        | 10        | 11.49%  |
| 301-350        | 9         | 10.34%  |
| 71-80          | 5         | 5.75%   |
| 101-110        | 5         | 5.75%   |
| 251-300        | 4         | 4.6%    |
| 61-70          | 3         | 3.45%   |
| 121-130        | 3         | 3.45%   |
| 501-1000       | 3         | 3.45%   |
| 351-500        | 2         | 2.3%    |
| More than 1000 | 1         | 1.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 28        | 32.94%  |
| 51-100        | 21        | 24.71%  |
| 161-240       | 14        | 16.47%  |
| Unknown       | 10        | 11.76%  |
| 101-120       | 8         | 9.41%   |
| More than 240 | 3         | 3.53%   |
| 1-50          | 1         | 1.18%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 73        | 53.68%  |
| 0     | 52        | 38.24%  |
| 2     | 10        | 7.35%   |
| 3     | 1         | 0.74%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 85        | 44.74%  |
| Realtek Semiconductor           | 64        | 33.68%  |
| TP-Link                         | 6         | 3.16%   |
| Broadcom                        | 6         | 3.16%   |
| Ralink Technology               | 4         | 2.11%   |
| Qualcomm Atheros                | 4         | 2.11%   |
| Hewlett-Packard                 | 4         | 2.11%   |
| D-Link System                   | 3         | 1.58%   |
| Mellanox Technologies           | 2         | 1.05%   |
| Edimax Technology               | 2         | 1.05%   |
| Xiaomi                          | 1         | 0.53%   |
| Qualcomm Atheros Communications | 1         | 0.53%   |
| MediaTek                        | 1         | 0.53%   |
| Lenovo                          | 1         | 0.53%   |
| Google                          | 1         | 0.53%   |
| Emulex                          | 1         | 0.53%   |
| BUFFALO                         | 1         | 0.53%   |
| ASUSTek Computer                | 1         | 0.53%   |
| Arduino SA                      | 1         | 0.53%   |
| Aquantia                        | 1         | 0.53%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 45        | 19.4%   |
| Realtek RTL8125 2.5GbE Controller                                          | 13        | 5.6%    |
| Intel Wi-Fi 6 AX200                                                        | 13        | 5.6%    |
| Intel Wireless-AC 9260                                                     | 7         | 3.02%   |
| Intel Comet Lake PCH CNVi WiFi                                             | 7         | 3.02%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                     | 6         | 2.59%   |
| Intel I211 Gigabit Network Connection                                      | 6         | 2.59%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                          | 6         | 2.59%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 6         | 2.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 6         | 2.59%   |
| Intel Wireless 8265 / 8275                                                 | 5         | 2.16%   |
| Intel Wi-Fi 6 AX201                                                        | 5         | 2.16%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 4         | 1.72%   |
| Intel Wireless 7265                                                        | 4         | 1.72%   |
| Intel I210 Gigabit Network Connection                                      | 4         | 1.72%   |
| Intel Ethernet Controller I225-V                                           | 4         | 1.72%   |
| Intel 82574L Gigabit Network Connection                                    | 4         | 1.72%   |
| HP hs2350 HSPA+ Mobile Broadband Module Network Adapter                    | 4         | 1.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 3         | 1.29%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 3         | 1.29%   |
| Intel Ethernet Connection (4) I219-LM                                      | 3         | 1.29%   |
| Intel Ethernet Connection (14) I219-LM                                     | 3         | 1.29%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 3         | 1.29%   |
| Ralink MT7601U Wireless Adapter                                            | 2         | 0.86%   |
| Intel Wireless 7260                                                        | 2         | 0.86%   |
| Intel Ethernet Connection (11) I219-LM                                     | 2         | 0.86%   |
| Intel Ethernet Connection (10) I219-V                                      | 2         | 0.86%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 2         | 0.86%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                       | 1         | 0.43%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                     | 1         | 0.43%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]        | 1         | 0.43%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                | 1         | 0.43%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                   | 1         | 0.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 0.43%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                     | 1         | 0.43%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 1         | 0.43%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 1         | 0.43%   |
| Ralink RT5370 Wireless Adapter                                             | 1         | 0.43%   |
| Ralink RT2870/RT3070 Wireless Adapter                                      | 1         | 0.43%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 1         | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 70        | 66.04%  |
| Realtek Semiconductor           | 9         | 8.49%   |
| TP-Link                         | 6         | 5.66%   |
| Broadcom                        | 5         | 4.72%   |
| Ralink Technology               | 4         | 3.77%   |
| Qualcomm Atheros                | 3         | 2.83%   |
| D-Link System                   | 3         | 2.83%   |
| Edimax Technology               | 2         | 1.89%   |
| Qualcomm Atheros Communications | 1         | 0.94%   |
| MediaTek                        | 1         | 0.94%   |
| BUFFALO                         | 1         | 0.94%   |
| ASUSTek Computer                | 1         | 0.94%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                           | 13        | 12.26%  |
| Intel Wireless-AC 9260                                                        | 7         | 6.6%    |
| Intel Comet Lake PCH CNVi WiFi                                                | 7         | 6.6%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 6         | 5.66%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 6         | 5.66%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 6         | 5.66%   |
| Intel Wireless 8265 / 8275                                                    | 5         | 4.72%   |
| Intel Wi-Fi 6 AX201                                                           | 5         | 4.72%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 4         | 3.77%   |
| Intel Wireless 7265                                                           | 4         | 3.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 3         | 2.83%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 3         | 2.83%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]    | 3         | 2.83%   |
| Ralink MT7601U Wireless Adapter                                               | 2         | 1.89%   |
| Intel Wireless 7260                                                           | 2         | 1.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2         | 1.89%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1         | 0.94%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]           | 1         | 0.94%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                      | 1         | 0.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.94%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                        | 1         | 0.94%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 0.94%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1         | 0.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1         | 0.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 1         | 0.94%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 1         | 0.94%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1         | 0.94%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                 | 1         | 0.94%   |
| Intel Wireless 8260                                                           | 1         | 0.94%   |
| Intel Wi-Fi 6 AX201 160MHz                                                    | 1         | 0.94%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 1         | 0.94%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 0.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 0.94%   |
| Intel Centrino Advanced-N 6235                                                | 1         | 0.94%   |
| Intel Alder Lake-P PCH CNVi WiFi                                              | 1         | 0.94%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                | 1         | 0.94%   |
| Edimax EW-7711MAC 802.11ac Wireless Adapter                                   | 1         | 0.94%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]                      | 1         | 0.94%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                   | 1         | 0.94%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 1         | 0.94%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 57        | 51.35%  |
| Intel                 | 46        | 41.44%  |
| Broadcom              | 2         | 1.8%    |
| Xiaomi                | 1         | 0.9%    |
| Qualcomm Atheros      | 1         | 0.9%    |
| Lenovo                | 1         | 0.9%    |
| Google                | 1         | 0.9%    |
| Emulex                | 1         | 0.9%    |
| Aquantia              | 1         | 0.9%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 45        | 38.79%  |
| Realtek RTL8125 2.5GbE Controller                                             | 12        | 10.34%  |
| Intel I211 Gigabit Network Connection                                         | 6         | 5.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6         | 5.17%   |
| Intel I210 Gigabit Network Connection                                         | 4         | 3.45%   |
| Intel Ethernet Controller I225-V                                              | 4         | 3.45%   |
| Intel 82574L Gigabit Network Connection                                       | 4         | 3.45%   |
| Intel Ethernet Connection (4) I219-LM                                         | 3         | 2.59%   |
| Intel Ethernet Connection (14) I219-LM                                        | 3         | 2.59%   |
| Intel Ethernet Connection (11) I219-LM                                        | 2         | 1.72%   |
| Intel Ethernet Connection (10) I219-V                                         | 2         | 1.72%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                          | 1         | 0.86%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1         | 0.86%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 0.86%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1         | 0.86%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                              | 1         | 0.86%   |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller                           | 1         | 0.86%   |
| Intel I350 Gigabit Network Connection                                         | 1         | 0.86%   |
| Intel Ethernet Controller X550                                                | 1         | 0.86%   |
| Intel Ethernet Controller I225-LM                                             | 1         | 0.86%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 1         | 0.86%   |
| Intel Ethernet Connection I219-LM                                             | 1         | 0.86%   |
| Intel Ethernet Connection I218-LM                                             | 1         | 0.86%   |
| Intel Ethernet Connection I217-LM                                             | 1         | 0.86%   |
| Intel Ethernet Connection (7) I219-V                                          | 1         | 0.86%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1         | 0.86%   |
| Intel Ethernet Connection (5) I219-V                                          | 1         | 0.86%   |
| Intel Ethernet Connection (3) I218-LM                                         | 1         | 0.86%   |
| Intel Ethernet Connection (13) I219-V                                         | 1         | 0.86%   |
| Intel Ethernet Connection (11) I219-V                                         | 1         | 0.86%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 0.86%   |
| Google Nexus/Pixel Device (charging + debug)                                  | 1         | 0.86%   |
| Emulex OneConnect 10Gb NIC (be3)                                              | 1         | 0.86%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                             | 1         | 0.86%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 1         | 0.86%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 1         | 0.86%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 102       | 51%     |
| WiFi     | 88        | 44%     |
| Modem    | 6         | 3%      |
| Unknown  | 4         | 2%      |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 85        | 61.15%  |
| WiFi     | 51        | 36.69%  |
| Modem    | 3         | 2.16%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 70        | 53.03%  |
| 1     | 35        | 26.52%  |
| 0     | 15        | 11.36%  |
| 3     | 8         | 6.06%   |
| 4     | 3         | 2.27%   |
| 7     | 1         | 0.76%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 114       | 82.61%  |
| Yes  | 24        | 17.39%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 54        | 77.14%  |
| Apple                           | 4         | 5.71%   |
| IMC Networks                    | 3         | 4.29%   |
| Broadcom                        | 3         | 4.29%   |
| Realtek Semiconductor           | 2         | 2.86%   |
| Skylight Digital                | 1         | 1.43%   |
| Qualcomm Atheros Communications | 1         | 1.43%   |
| Opticis                         | 1         | 1.43%   |
| Cambridge Silicon Radio         | 1         | 1.43%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 17        | 24.29%  |
| Intel AX200 Bluetooth                               | 12        | 17.14%  |
| Intel Bluetooth wireless interface                  | 9         | 12.86%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 6         | 8.57%   |
| Intel AX210 Bluetooth                               | 5         | 7.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 5.71%   |
| Apple Bluetooth Host Controller                     | 3         | 4.29%   |
| Realtek Bluetooth Adapter                           | 2         | 2.86%   |
| IMC Networks Realtek Bluetooth Adapter              | 2         | 2.86%   |
| Skylight Digital Realtek Bluetooth Adapter          | 1         | 1.43%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.43%   |
| Opticis Realtek Bluetooth Adapter                   | 1         | 1.43%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.43%   |
| IMC Networks Bluetooth module                       | 1         | 1.43%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.43%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.43%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.43%   |
| Broadcom BCM2035 Bluetooth dongle                   | 1         | 1.43%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 1.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 61        | 37.65%  |
| AMD                     | 50        | 30.86%  |
| Nvidia                  | 32        | 19.75%  |
| Lenovo                  | 3         | 1.85%   |
| C-Media Electronics     | 3         | 1.85%   |
| Logitech                | 2         | 1.23%   |
| Yamaha                  | 1         | 0.62%   |
| Texas Instruments       | 1         | 0.62%   |
| SteelSeries ApS         | 1         | 0.62%   |
| JMTek                   | 1         | 0.62%   |
| GN Netcom               | 1         | 0.62%   |
| Generalplus Technology  | 1         | 0.62%   |
| Creative Labs           | 1         | 0.62%   |
| CMX Systems             | 1         | 0.62%   |
| Blue Microphones        | 1         | 0.62%   |
| AudioQuest              | 1         | 0.62%   |
| AKAI  Professional M.I. | 1         | 0.62%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                  | 30        | 14.93%  |
| AMD Renoir Radeon High Definition Audio Controller                      | 16        | 7.96%   |
| Intel Comet Lake PCH cAVS                                               | 11        | 5.47%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                     | 10        | 4.98%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller     | 9         | 4.48%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller          | 7         | 3.48%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller             | 7         | 3.48%   |
| Intel Comet Lake PCH-LP cAVS                                            | 6         | 2.99%   |
| Intel Cannon Lake PCH cAVS                                              | 6         | 2.99%   |
| AMD Starship/Matisse HD Audio Controller                                | 6         | 2.99%   |
| Nvidia GP107GL High Definition Audio Controller                         | 5         | 2.49%   |
| Intel Sunrise Point-LP HD Audio                                         | 4         | 1.99%   |
| AMD Rembrandt Radeon High Definition Audio Controller                   | 4         | 1.99%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                     | 4         | 1.99%   |
| Nvidia TU116 High Definition Audio Controller                           | 3         | 1.49%   |
| Intel Tiger Lake-H HD Audio Controller                                  | 3         | 1.49%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]               | 3         | 1.49%   |
| Nvidia GP108 High Definition Audio Controller                           | 2         | 1%      |
| Nvidia GK208 HDMI/DP Audio Controller                                   | 2         | 1%      |
| Nvidia GK107 HDMI Audio Controller                                      | 2         | 1%      |
| Nvidia GA104 High Definition Audio Controller                           | 2         | 1%      |
| Intel Wildcat Point-LP High Definition Audio Controller                 | 2         | 1%      |
| Intel Broadwell-U Audio Controller                                      | 2         | 1%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller     | 2         | 1%      |
| AMD SBx00 Azalia (Intel HDA)                                            | 2         | 1%      |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 2         | 1%      |
| AMD Navi 21/23 HDMI/DP Audio Controller                                 | 2         | 1%      |
| AMD Navi 10 HDMI Audio                                                  | 2         | 1%      |
| Yamaha Steinberg UR12                                                   | 1         | 0.5%    |
| Texas Instruments PCM2706 stereo audio DAC                              | 1         | 0.5%    |
| SteelSeries ApS SteelSeries Siberia 350                                 | 1         | 0.5%    |
| Nvidia TU106 High Definition Audio Controller                           | 1         | 0.5%    |
| Nvidia TU104 HD Audio Controller                                        | 1         | 0.5%    |
| Nvidia High Definition Audio Controller                                 | 1         | 0.5%    |
| Nvidia GP106 High Definition Audio Controller                           | 1         | 0.5%    |
| Nvidia GP104 High Definition Audio Controller                           | 1         | 0.5%    |
| Nvidia GM206 High Definition Audio Controller                           | 1         | 0.5%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]           | 1         | 0.5%    |
| Nvidia GA102 High Definition Audio Controller                           | 1         | 0.5%    |
| Logitech Yeti Nano HIDpp                                                | 1         | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 27        | 21.6%   |
| Micron Technology      | 17        | 13.6%   |
| SK hynix               | 16        | 12.8%   |
| Kingston               | 14        | 11.2%   |
| Crucial                | 12        | 9.6%    |
| Unknown                | 5         | 4%      |
| Corsair                | 5         | 4%      |
| Unknown                | 5         | 4%      |
| Smart                  | 3         | 2.4%    |
| Ramaxel Technology     | 3         | 2.4%    |
| G.Skill                | 3         | 2.4%    |
| Team                   | 2         | 1.6%    |
| Goodram                | 2         | 1.6%    |
| A-DATA Technology      | 2         | 1.6%    |
| Unknown (000000000C01) | 1         | 0.8%    |
| Transcend              | 1         | 0.8%    |
| PNY                    | 1         | 0.8%    |
| Neo Forza              | 1         | 0.8%    |
| KLEVV                  | 1         | 0.8%    |
| Golden Empire          | 1         | 0.8%    |
| Gold Key               | 1         | 0.8%    |
| Elpida                 | 1         | 0.8%    |
| 06F100000C01           | 1         | 0.8%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Unknown                                                    | 5         | 3.85%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s      | 4         | 3.08%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s     | 2         | 1.54%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s     | 2         | 1.54%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s     | 2         | 1.54%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s    | 2         | 1.54%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s      | 2         | 1.54%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s      | 2         | 1.54%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s       | 2         | 1.54%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s       | 2         | 1.54%   |
| Crucial RAM BL32G32C16S4B.M16FB1 32GB SODIMM DDR4 2667MT/s | 2         | 1.54%   |
| Corsair RAM CMK32GX4M2D3200C16 16GB DIMM DDR4 3200MT/s     | 2         | 1.54%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                  | 1         | 0.77%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                | 1         | 0.77%   |
| Unknown RAM Module 1GB SODIMM DDR                          | 1         | 0.77%   |
| Unknown RAM 3000 C16 Series 4096MB DIMM DDR4 2933MT/s      | 1         | 0.77%   |
| Unknown RAM 2G-08-10-12-1333 2GB DIMM DDR3 1333MT/s        | 1         | 0.77%   |
| Unknown (000000000C01) RAM Module 32GB DIMM DDR4 3200MT/s  | 1         | 0.77%   |
| Transcend RAM JM2666HLE-32G 32GB DIMM DDR4 2666MT/s        | 1         | 0.77%   |
| Team RAM TEAMGROUP-UD4-4133 8GB DIMM DDR4 4133MT/s         | 1         | 0.77%   |
| Team RAM TEAMGROUP-SD4-3200 32GB SODIMM DDR4 3200MT/s      | 1         | 0.77%   |
| Smart RAM SF4641G8CK8IWGKSEG 8GB SODIMM DDR4 2133MT/s      | 1         | 0.77%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s      | 1         | 0.77%   |
| Smart RAM Module 8GB DIMM DDR4 2667MT/s                    | 1         | 0.77%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1867MT/s               | 1         | 0.77%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s               | 1         | 0.77%   |
| SK hynix RAM HMAA4GU6CJR8N-XN 32GB DIMM DDR4 3200MT/s      | 1         | 0.77%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s    | 1         | 0.77%   |
| SK hynix RAM HMA82GR7JJR8N-VK 16GB DIMM DDR4 2667MT/s      | 1         | 0.77%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s     | 1         | 0.77%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s     | 1         | 0.77%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s     | 1         | 0.77%   |
| Samsung RAM Module 4GB SODIMM DDR4 3200MT/s                | 1         | 0.77%   |
| Samsung RAM M474A4G43AB1-CVF 32GB SODIMM DDR4 2933MT/s     | 1         | 0.77%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s      | 1         | 0.77%   |
| Samsung RAM M471B5674-M0-YK0 4GB Chip DDR3 1600MT/s        | 1         | 0.77%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s      | 1         | 0.77%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s      | 1         | 0.77%   |
| Samsung RAM M471A5244BB0-CWE 4GB SODIMM DDR4 3200MT/s      | 1         | 0.77%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s     | 1         | 0.77%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 85        | 77.27%  |
| DDR3   | 16        | 14.55%  |
| LPDDR5 | 2         | 1.82%   |
| LPDDR4 | 2         | 1.82%   |
| LPDDR3 | 2         | 1.82%   |
| DDR5   | 2         | 1.82%   |
| DDR    | 1         | 0.91%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 69        | 62.73%  |
| DIMM         | 33        | 30%     |
| Row Of Chips | 7         | 6.36%   |
| Chip         | 1         | 0.91%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 41        | 36.28%  |
| 16384 | 36        | 31.86%  |
| 32768 | 17        | 15.04%  |
| 4096  | 14        | 12.39%  |
| 2048  | 4         | 3.54%   |
| 1024  | 1         | 0.88%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 42        | 36.52%  |
| 2667    | 23        | 20%     |
| 2400    | 9         | 7.83%   |
| 1600    | 8         | 6.96%   |
| 1867    | 6         | 5.22%   |
| 2666    | 5         | 4.35%   |
| 2133    | 4         | 3.48%   |
| 2933    | 3         | 2.61%   |
| 4267    | 2         | 1.74%   |
| 3600    | 2         | 1.74%   |
| 1333    | 2         | 1.74%   |
| 6400    | 1         | 0.87%   |
| 5200    | 1         | 0.87%   |
| 4800    | 1         | 0.87%   |
| 4266    | 1         | 0.87%   |
| 4133    | 1         | 0.87%   |
| 3000    | 1         | 0.87%   |
| 1866    | 1         | 0.87%   |
| 1334    | 1         | 0.87%   |
| Unknown | 1         | 0.87%   |

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
| Chicony Electronics                    | 15        | 19.74%  |
| IMC Networks                           | 11        | 14.47%  |
| Logitech                               | 9         | 11.84%  |
| Microdia                               | 8         | 10.53%  |
| Realtek Semiconductor                  | 6         | 7.89%   |
| Lite-On Technology                     | 5         | 6.58%   |
| Bison Electronics                      | 5         | 6.58%   |
| Sunplus Innovation Technology          | 4         | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.95%   |
| Syntek                                 | 2         | 2.63%   |
| Shenzhen Kingcome Optoelectronic       | 2         | 2.63%   |
| Apple                                  | 2         | 2.63%   |
| Trust                                  | 1         | 1.32%   |
| Luxvisions Innotech Limited            | 1         | 1.32%   |
| GEMBIRD                                | 1         | 1.32%   |
| Aveo Technology                        | 1         | 1.32%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                         | 8         | 10.39%  |
| Chicony Integrated Camera                              | 7         | 9.09%   |
| Logitech Webcam C270                                   | 3         | 3.9%    |
| Lite-On Integrated Camera                              | 3         | 3.9%    |
| Chicony Integrated HP HD Webcam                        | 3         | 3.9%    |
| Bison Integrated Camera                                | 3         | 3.9%    |
| Sunplus Integrated_Webcam_HD                           | 2         | 2.6%    |
| Realtek Laptop Camera                                  | 2         | 2.6%    |
| Microdia USB Camera                                    | 2         | 2.6%    |
| Microdia Integrated Webcam                             | 2         | 2.6%    |
| Microdia HP Integrated Webcam                          | 2         | 2.6%    |
| Logitech C920 PRO HD Webcam                            | 2         | 2.6%    |
| Lite-On HP HD Camera                                   | 2         | 2.6%    |
| IMC Networks Realtek PC Camera                         | 2         | 2.6%    |
| Chicony ThinkPad T490 Webcam                           | 2         | 2.6%    |
| Bison HD Webcam                                        | 2         | 2.6%    |
| Apple FaceTime HD Camera (Built-in)                    | 2         | 2.6%    |
| Trust Canyon CNS-CWC6 Webcam                           | 1         | 1.3%    |
| Syntek Lenovo EasyCamera                               | 1         | 1.3%    |
| Syntek Integrated Camera                               | 1         | 1.3%    |
| Sunplus SPCA2650 AV Camera                             | 1         | 1.3%    |
| Sunplus Integrated_Webcam_FHD                          | 1         | 1.3%    |
| Shenzhen Kingcome Optoelectronic XiaoMi USB 2.0 Webcam | 1         | 1.3%    |
| Shenzhen Kingcome Optoelectronic 720p HD Camera        | 1         | 1.3%    |
| Realtek USB 2.0 Webcam                                 | 1         | 1.3%    |
| Realtek USB 2.0 PC Camera                              | 1         | 1.3%    |
| Realtek Integrated_Webcam_HD                           | 1         | 1.3%    |
| Realtek Composite Webcam                               | 1         | 1.3%    |
| Microdia USB 2.0 Camera                                | 1         | 1.3%    |
| Microdia Dell Integrated HD Webcam                     | 1         | 1.3%    |
| Luxvisions Innotech Limited HP HD Camera               | 1         | 1.3%    |
| Logitech Webcam C170                                   | 1         | 1.3%    |
| Logitech HD Pro Webcam C920                            | 1         | 1.3%    |
| Logitech C505 HD Webcam                                | 1         | 1.3%    |
| Logitech BRIO Ultra HD Webcam                          | 1         | 1.3%    |
| IMC Networks EasyCamera                                | 1         | 1.3%    |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]      | 1         | 1.3%    |
| Chicony USB2.0 0.3M UVC WebCam                         | 1         | 1.3%    |
| Chicony Integrated IR Camera                           | 1         | 1.3%    |
| Chicony HD Webcam                                      | 1         | 1.3%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 10        | 38.46%  |
| Validity Sensors           | 5         | 19.23%  |
| Shenzhen Goodix Technology | 5         | 19.23%  |
| FocalTech Systems          | 4         | 15.38%  |
| Elan Microelectronics      | 1         | 3.85%   |
| AuthenTec                  | 1         | 3.85%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 6         | 23.08%  |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 15.38%  |
| FocalTech Systems Fingerprint Reader                                       | 3         | 11.54%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 7.69%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 7.69%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 7.69%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 7.69%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.85%   |
| Shenzhen Goodix Fingerprint Reader SGX                                     | 1         | 3.85%   |
| FocalTech Systems FocalTech Fingerprint Device                             | 1         | 3.85%   |
| Elan Fingerprint Sensor                                                    | 1         | 3.85%   |
| AuthenTec AES2810                                                          | 1         | 3.85%   |

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
| 0     | 41        | 29.71%  |
| 2     | 34        | 24.64%  |
| 1     | 28        | 20.29%  |
| 4     | 17        | 12.32%  |
| 3     | 13        | 9.42%   |
| 5     | 4         | 2.9%    |
| 9     | 1         | 0.72%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 69        | 36.32%  |
| Bluetooth                | 40        | 21.05%  |
| Net/wireless             | 28        | 14.74%  |
| Fingerprint reader       | 25        | 13.16%  |
| Card reader              | 10        | 5.26%   |
| Net/ethernet             | 6         | 3.16%   |
| Sound                    | 5         | 2.63%   |
| Network                  | 4         | 2.11%   |
| Firewire controller      | 2         | 1.05%   |
| Modem                    | 1         | 0.53%   |

