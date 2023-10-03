FreeBSD - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for FreeBSD.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/FreeBSD/Desktop/README.md) and [notebooks](/Dist/FreeBSD/Notebook/README.md).

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

Total: 3714

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Google        | Auron_Paine                 | Notebook    | [021624028a](https://bsd-hardware.info/?probe=021624028a) | Oct 01, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [7a6b97e997](https://bsd-hardware.info/?probe=7a6b97e997) | Oct 01, 2023 |
| MSI           | H81M-P33                    | Desktop     | [da12fe3c05](https://bsd-hardware.info/?probe=da12fe3c05) | Oct 01, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [6975204e47](https://bsd-hardware.info/?probe=6975204e47) | Oct 01, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [c6903de57a](https://bsd-hardware.info/?probe=c6903de57a) | Sep 30, 2023 |
| Gigabyte      | B450M S2H V2                | Desktop     | [31da8655d1](https://bsd-hardware.info/?probe=31da8655d1) | Sep 28, 2023 |
| Dell          | 0J555H A00                  | Server      | [3c395551d4](https://bsd-hardware.info/?probe=3c395551d4) | Sep 28, 2023 |
| Supermicro    | M11SDV-8C+-LN4F             | Server      | [c35034519a](https://bsd-hardware.info/?probe=c35034519a) | Sep 28, 2023 |
| Biostar       | A55MLC2                     | Desktop     | [fac0f247d0](https://bsd-hardware.info/?probe=fac0f247d0) | Sep 28, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [0c56aeb6b5](https://bsd-hardware.info/?probe=0c56aeb6b5) | Sep 27, 2023 |
| ASUSTek       | P9D-MV Series               | Server      | [0a035e25a9](https://bsd-hardware.info/?probe=0a035e25a9) | Sep 26, 2023 |
| Dell          | 07T4MC A09                  | Desktop     | [bde8cc45df](https://bsd-hardware.info/?probe=bde8cc45df) | Sep 26, 2023 |
| Dell          | 07T4MC A09                  | Desktop     | [0ce8f84155](https://bsd-hardware.info/?probe=0ce8f84155) | Sep 26, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D60... | Notebook    | [231aedbf9e](https://bsd-hardware.info/?probe=231aedbf9e) | Sep 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [1ba135fef1](https://bsd-hardware.info/?probe=1ba135fef1) | Sep 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [9c8516c8a8](https://bsd-hardware.info/?probe=9c8516c8a8) | Sep 24, 2023 |
| Dell          | Latitude 3410               | Notebook    | [1bd71b0bf0](https://bsd-hardware.info/?probe=1bd71b0bf0) | Sep 24, 2023 |
| MSI           | H81M-P33                    | Desktop     | [971f3fdba1](https://bsd-hardware.info/?probe=971f3fdba1) | Sep 24, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [6538212bd6](https://bsd-hardware.info/?probe=6538212bd6) | Sep 24, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [f7aee1db53](https://bsd-hardware.info/?probe=f7aee1db53) | Sep 24, 2023 |
| AZW           | SEi V1.0                    | Desktop     | [1d0307b36d](https://bsd-hardware.info/?probe=1d0307b36d) | Sep 23, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [de1bdf0601](https://bsd-hardware.info/?probe=de1bdf0601) | Sep 21, 2023 |
| Dell          | G16 7630                    | Notebook    | [4e39a5ebdf](https://bsd-hardware.info/?probe=4e39a5ebdf) | Sep 21, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [f29233649e](https://bsd-hardware.info/?probe=f29233649e) | Sep 20, 2023 |
| Lenovo        | ThinkPad L390 20NRS00Q00    | Notebook    | [b9885ea126](https://bsd-hardware.info/?probe=b9885ea126) | Sep 17, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [ab77dcfd74](https://bsd-hardware.info/?probe=ab77dcfd74) | Sep 15, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [6fc18e3db7](https://bsd-hardware.info/?probe=6fc18e3db7) | Sep 15, 2023 |
| Lenovo        | ThinkPad T480s 20L7S24F0... | Notebook    | [bb7eb8b380](https://bsd-hardware.info/?probe=bb7eb8b380) | Sep 15, 2023 |
| MECHREVO      | WUJIE 16                    | Notebook    | [17b7c850c4](https://bsd-hardware.info/?probe=17b7c850c4) | Sep 14, 2023 |
| Alienware     | m15                         | Notebook    | [609d2ce1ce](https://bsd-hardware.info/?probe=609d2ce1ce) | Sep 14, 2023 |
| HP            | Pavilion dv5                | Notebook    | [b7dad77d0d](https://bsd-hardware.info/?probe=b7dad77d0d) | Sep 14, 2023 |
| GPU Compan... | GWTC116-2                   | Notebook    | [03a8809fe4](https://bsd-hardware.info/?probe=03a8809fe4) | Sep 13, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [67d1f42d7c](https://bsd-hardware.info/?probe=67d1f42d7c) | Sep 13, 2023 |
| GPU Compan... | GWTC116-2                   | Notebook    | [7ba189ff8a](https://bsd-hardware.info/?probe=7ba189ff8a) | Sep 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [5dee3a945f](https://bsd-hardware.info/?probe=5dee3a945f) | Sep 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [9fee6e83fc](https://bsd-hardware.info/?probe=9fee6e83fc) | Sep 13, 2023 |
| HP            | 212B                        | Desktop     | [3370718b29](https://bsd-hardware.info/?probe=3370718b29) | Sep 13, 2023 |
| HP            | ProBook 4530s               | Notebook    | [0b47c15c42](https://bsd-hardware.info/?probe=0b47c15c42) | Sep 12, 2023 |
| HP            | ProBook 4530s               | Notebook    | [4b6daa1f1c](https://bsd-hardware.info/?probe=4b6daa1f1c) | Sep 12, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [78bc36f5a9](https://bsd-hardware.info/?probe=78bc36f5a9) | Sep 11, 2023 |
| Dell          | BlackfordESB2               | Server      | [36b37267be](https://bsd-hardware.info/?probe=36b37267be) | Sep 11, 2023 |
| HP            | Mini 110-3100               | Notebook    | [14f75b6704](https://bsd-hardware.info/?probe=14f75b6704) | Sep 11, 2023 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [095b8aa8fb](https://bsd-hardware.info/?probe=095b8aa8fb) | Sep 11, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [e2d694053a](https://bsd-hardware.info/?probe=e2d694053a) | Sep 10, 2023 |
| MSI           | H81M-P33                    | Desktop     | [57a847859f](https://bsd-hardware.info/?probe=57a847859f) | Sep 10, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [b7e0d87f47](https://bsd-hardware.info/?probe=b7e0d87f47) | Sep 10, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [c2378b3e83](https://bsd-hardware.info/?probe=c2378b3e83) | Sep 10, 2023 |
| Lenovo        | ThinkPad T480s 20L8S3LR0... | Notebook    | [cbac96a24f](https://bsd-hardware.info/?probe=cbac96a24f) | Sep 09, 2023 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [6be22d7887](https://bsd-hardware.info/?probe=6be22d7887) | Sep 09, 2023 |
| MSI           | PRESTIGE X570 CREATION      | Desktop     | [7947ecdca3](https://bsd-hardware.info/?probe=7947ecdca3) | Sep 08, 2023 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | Notebook    | [d331bd9a11](https://bsd-hardware.info/?probe=d331bd9a11) | Sep 08, 2023 |
| Lenovo        | IdeaPad 1 11ADA05 82GV      | Notebook    | [d9d6fc45f8](https://bsd-hardware.info/?probe=d9d6fc45f8) | Sep 08, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [24e745026c](https://bsd-hardware.info/?probe=24e745026c) | Sep 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [29578638c1](https://bsd-hardware.info/?probe=29578638c1) | Sep 08, 2023 |
| HP            | 8158 A01                    | Mini pc     | [ae22c1bea5](https://bsd-hardware.info/?probe=ae22c1bea5) | Sep 08, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [cbde759aa2](https://bsd-hardware.info/?probe=cbde759aa2) | Sep 07, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [22ec8197cc](https://bsd-hardware.info/?probe=22ec8197cc) | Sep 07, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [e011df1d78](https://bsd-hardware.info/?probe=e011df1d78) | Sep 07, 2023 |
| Unknown       | Unknown                     | Notebook    | [516b89740b](https://bsd-hardware.info/?probe=516b89740b) | Sep 06, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [40b4e58c88](https://bsd-hardware.info/?probe=40b4e58c88) | Sep 06, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [0b7d85b124](https://bsd-hardware.info/?probe=0b7d85b124) | Sep 06, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [67e9eafa7e](https://bsd-hardware.info/?probe=67e9eafa7e) | Sep 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [50f509c032](https://bsd-hardware.info/?probe=50f509c032) | Sep 05, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [cfecf51114](https://bsd-hardware.info/?probe=cfecf51114) | Sep 04, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [1bde5a65b6](https://bsd-hardware.info/?probe=1bde5a65b6) | Sep 03, 2023 |
| Lenovo        | ThinkPad X260 20F6006XUK    | Notebook    | [e4f0ac6bb9](https://bsd-hardware.info/?probe=e4f0ac6bb9) | Sep 03, 2023 |
| Lenovo        | ThinkPad X260 20F6006XUK    | Notebook    | [4bce25bd89](https://bsd-hardware.info/?probe=4bce25bd89) | Sep 03, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [d240fba8b7](https://bsd-hardware.info/?probe=d240fba8b7) | Sep 03, 2023 |
| MSI           | H81M-P33                    | Desktop     | [b47290007a](https://bsd-hardware.info/?probe=b47290007a) | Sep 03, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [ef4604a40f](https://bsd-hardware.info/?probe=ef4604a40f) | Sep 03, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [8d37c44440](https://bsd-hardware.info/?probe=8d37c44440) | Sep 03, 2023 |
| AAEON         | FWS-2363 V1.0               | Desktop     | [098bc5466b](https://bsd-hardware.info/?probe=098bc5466b) | Sep 03, 2023 |
| Shuttle       | DS20U                       | Desktop     | [d034a8e5b8](https://bsd-hardware.info/?probe=d034a8e5b8) | Sep 02, 2023 |
| Intel         | HM570                       | Desktop     | [de018603ae](https://bsd-hardware.info/?probe=de018603ae) | Sep 02, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [1bfe26df6e](https://bsd-hardware.info/?probe=1bfe26df6e) | Sep 02, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [82ac08abc0](https://bsd-hardware.info/?probe=82ac08abc0) | Aug 31, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [0ebdda5146](https://bsd-hardware.info/?probe=0ebdda5146) | Aug 31, 2023 |
| HP            | 802F                        | Desktop     | [1f64f7e11f](https://bsd-hardware.info/?probe=1f64f7e11f) | Aug 30, 2023 |
| SolidRun      | CEX7 Platform               | Desktop     | [b83ebfd33b](https://bsd-hardware.info/?probe=b83ebfd33b) | Aug 29, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [0dda7a609c](https://bsd-hardware.info/?probe=0dda7a609c) | Aug 29, 2023 |
| Nvidia        | MCP79                       | Desktop     | [0897b3a117](https://bsd-hardware.info/?probe=0897b3a117) | Aug 29, 2023 |
| Supermicro    | X9DRD-iF                    | Desktop     | [be36f2fe2b](https://bsd-hardware.info/?probe=be36f2fe2b) | Aug 28, 2023 |
| Lenovo        | ThinkPad T450 20BV000BUS    | Notebook    | [f0fb53394d](https://bsd-hardware.info/?probe=f0fb53394d) | Aug 28, 2023 |
| Lenovo        | ThinkPad T430 2347GR2       | Notebook    | [dc8ad6c7c5](https://bsd-hardware.info/?probe=dc8ad6c7c5) | Aug 28, 2023 |
| Lenovo        | ThinkPad T430 2347GR2       | Notebook    | [c8c17a9db2](https://bsd-hardware.info/?probe=c8c17a9db2) | Aug 28, 2023 |
| MSI           | PRESTIGE X570 CREATION      | Desktop     | [df915d5ab9](https://bsd-hardware.info/?probe=df915d5ab9) | Aug 27, 2023 |
| MSI           | H81M-P33                    | Desktop     | [2e9a066a01](https://bsd-hardware.info/?probe=2e9a066a01) | Aug 27, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [9898ae1ead](https://bsd-hardware.info/?probe=9898ae1ead) | Aug 27, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [0bb56ff672](https://bsd-hardware.info/?probe=0bb56ff672) | Aug 27, 2023 |
| Dell          | G5 5590                     | Notebook    | [2e496efada](https://bsd-hardware.info/?probe=2e496efada) | Aug 26, 2023 |
| Dell          | G5 5590                     | Notebook    | [fd4f457391](https://bsd-hardware.info/?probe=fd4f457391) | Aug 26, 2023 |
| SolidRun      | CEX7 Platform               | Desktop     | [4d51e18ce4](https://bsd-hardware.info/?probe=4d51e18ce4) | Aug 25, 2023 |
| Supermicro    | X10DRi-LN4+                 | Server      | [4978b62b97](https://bsd-hardware.info/?probe=4978b62b97) | Aug 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [f1a43ebe23](https://bsd-hardware.info/?probe=f1a43ebe23) | Aug 24, 2023 |
| MSI           | G31M3-L V2                  | Desktop     | [7335b3dea2](https://bsd-hardware.info/?probe=7335b3dea2) | Aug 22, 2023 |
| Dell          | 068CDY A01                  | Server      | [c3e69db640](https://bsd-hardware.info/?probe=c3e69db640) | Aug 22, 2023 |
| MSI           | MEG X570 ACE                | Desktop     | [0d69491bdd](https://bsd-hardware.info/?probe=0d69491bdd) | Aug 21, 2023 |
| MSI           | MEG X570 ACE                | Desktop     | [913cc77381](https://bsd-hardware.info/?probe=913cc77381) | Aug 21, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [3ac93594a2](https://bsd-hardware.info/?probe=3ac93594a2) | Aug 20, 2023 |
| Lenovo        | ThinkCentre M90p 3853RN9    | Desktop     | [818c1b5f31](https://bsd-hardware.info/?probe=818c1b5f31) | Aug 20, 2023 |
| Shuttle       | DS20U                       | Desktop     | [5c511e0613](https://bsd-hardware.info/?probe=5c511e0613) | Aug 20, 2023 |
| AZW           | SER                         | Mini pc     | [db297e2cda](https://bsd-hardware.info/?probe=db297e2cda) | Aug 20, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0UD0... | Notebook    | [3c3610a93f](https://bsd-hardware.info/?probe=3c3610a93f) | Aug 19, 2023 |
| Lenovo        | ThinkPad T495s 20QKS1812... | Notebook    | [0238ea2cab](https://bsd-hardware.info/?probe=0238ea2cab) | Aug 19, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [301a7c7b63](https://bsd-hardware.info/?probe=301a7c7b63) | Aug 19, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [3b430afdad](https://bsd-hardware.info/?probe=3b430afdad) | Aug 18, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [66449212d1](https://bsd-hardware.info/?probe=66449212d1) | Aug 18, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [434ec73823](https://bsd-hardware.info/?probe=434ec73823) | Aug 18, 2023 |
| Dell          | Latitude 3420               | Notebook    | [0e171f3f87](https://bsd-hardware.info/?probe=0e171f3f87) | Aug 18, 2023 |
| Lenovo        | 30C7 SDK0J40700 WIN 3258... | Desktop     | [9e92903663](https://bsd-hardware.info/?probe=9e92903663) | Aug 18, 2023 |
| MSI           | MS-7721                     | Desktop     | [678c81c8c1](https://bsd-hardware.info/?probe=678c81c8c1) | Aug 18, 2023 |
| Dell          | 05FT2M A04                  | Server      | [73afce6eeb](https://bsd-hardware.info/?probe=73afce6eeb) | Aug 17, 2023 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [7aa7ba9ea9](https://bsd-hardware.info/?probe=7aa7ba9ea9) | Aug 17, 2023 |
| Supermicro    | M12SWA-TF                   | Desktop     | [2e38f0b91a](https://bsd-hardware.info/?probe=2e38f0b91a) | Aug 16, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [9a8ad54cd3](https://bsd-hardware.info/?probe=9a8ad54cd3) | Aug 16, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [fc152ce8d4](https://bsd-hardware.info/?probe=fc152ce8d4) | Aug 16, 2023 |
| Lenovo        | IdeaPad Slim 9 14ITL5 82... | Notebook    | [be7bd4b126](https://bsd-hardware.info/?probe=be7bd4b126) | Aug 15, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [cc946b2a89](https://bsd-hardware.info/?probe=cc946b2a89) | Aug 15, 2023 |
| Lenovo        | ThinkPad T460p 20FXS06A1... | Notebook    | [378d093019](https://bsd-hardware.info/?probe=378d093019) | Aug 15, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [664ee85747](https://bsd-hardware.info/?probe=664ee85747) | Aug 15, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [2529ce32a7](https://bsd-hardware.info/?probe=2529ce32a7) | Aug 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [80fbf43a6c](https://bsd-hardware.info/?probe=80fbf43a6c) | Aug 13, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [fbb75a1ace](https://bsd-hardware.info/?probe=fbb75a1ace) | Aug 13, 2023 |
| MSI           | H81M-P33                    | Desktop     | [c7b0e4ca6c](https://bsd-hardware.info/?probe=c7b0e4ca6c) | Aug 13, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [245d908d1a](https://bsd-hardware.info/?probe=245d908d1a) | Aug 13, 2023 |
| MSI           | Modern 14 B11SBL            | Notebook    | [1e02b41824](https://bsd-hardware.info/?probe=1e02b41824) | Aug 12, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [46a6b88b33](https://bsd-hardware.info/?probe=46a6b88b33) | Aug 11, 2023 |
| ASUSTek       | 1001P                       | Notebook    | [ac53dba211](https://bsd-hardware.info/?probe=ac53dba211) | Aug 11, 2023 |
| PC Engines    | APU2                        | Desktop     | [2e9106fc92](https://bsd-hardware.info/?probe=2e9106fc92) | Aug 11, 2023 |
| Gigabyte      | AX370M-DS3H-CF              | Desktop     | [7b00ddd0a1](https://bsd-hardware.info/?probe=7b00ddd0a1) | Aug 11, 2023 |
| PC Engines    | apu1                        | Desktop     | [0b3594d9a3](https://bsd-hardware.info/?probe=0b3594d9a3) | Aug 11, 2023 |
| ASUSTek       | 1001P                       | Notebook    | [2424d8acdc](https://bsd-hardware.info/?probe=2424d8acdc) | Aug 11, 2023 |
| MSI           | PRESTIGE X570 CREATION      | Desktop     | [65092dde79](https://bsd-hardware.info/?probe=65092dde79) | Aug 09, 2023 |
| Notebook      | N7x0WU                      | Notebook    | [418b98798e](https://bsd-hardware.info/?probe=418b98798e) | Aug 09, 2023 |
| Notebook      | N7x0WU                      | Notebook    | [60d49b408a](https://bsd-hardware.info/?probe=60d49b408a) | Aug 09, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [2f6574d368](https://bsd-hardware.info/?probe=2f6574d368) | Aug 08, 2023 |
| MSI           | Modern 14 B11SBL            | Notebook    | [ba3ab230dc](https://bsd-hardware.info/?probe=ba3ab230dc) | Aug 08, 2023 |
| MSI           | Modern 14 B11SBL            | Notebook    | [48483213f9](https://bsd-hardware.info/?probe=48483213f9) | Aug 06, 2023 |
| Supermicro    | X10DRI-TB                   | Server      | [d4e7a4dde7](https://bsd-hardware.info/?probe=d4e7a4dde7) | Aug 06, 2023 |
| MSI           | H81M-P33                    | Desktop     | [1f7493ada9](https://bsd-hardware.info/?probe=1f7493ada9) | Aug 06, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [46b9ec2e56](https://bsd-hardware.info/?probe=46b9ec2e56) | Aug 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [5bd8b552e6](https://bsd-hardware.info/?probe=5bd8b552e6) | Aug 06, 2023 |
| Dell          | Inspiron 14-3467            | Notebook    | [5db7e9b7a1](https://bsd-hardware.info/?probe=5db7e9b7a1) | Aug 05, 2023 |
| ASUSTek       | ROG Strix G513QC_G513QC     | Notebook    | [b90e62e27d](https://bsd-hardware.info/?probe=b90e62e27d) | Aug 04, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [4a2c98005b](https://bsd-hardware.info/?probe=4a2c98005b) | Aug 04, 2023 |
| Intel         | NUC12WSBi3 M36953-303       | Mini pc     | [f809d834df](https://bsd-hardware.info/?probe=f809d834df) | Aug 03, 2023 |
| ASRock        | B550 PG Velocita            | Desktop     | [3ff5fcfbc0](https://bsd-hardware.info/?probe=3ff5fcfbc0) | Aug 02, 2023 |
| HP            | 8298                        | Desktop     | [961bfad69a](https://bsd-hardware.info/?probe=961bfad69a) | Aug 01, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [be9b9caa66](https://bsd-hardware.info/?probe=be9b9caa66) | Jul 31, 2023 |
| AZW           | SER                         | Mini pc     | [287fdf7e70](https://bsd-hardware.info/?probe=287fdf7e70) | Jul 30, 2023 |
| ASUSTek       | PRIME A320I-K               | Desktop     | [09f173d4b6](https://bsd-hardware.info/?probe=09f173d4b6) | Jul 30, 2023 |
| MSI           | H81M-P33                    | Desktop     | [9c27c27611](https://bsd-hardware.info/?probe=9c27c27611) | Jul 30, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [a2dbe84ed3](https://bsd-hardware.info/?probe=a2dbe84ed3) | Jul 30, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [591f8397a9](https://bsd-hardware.info/?probe=591f8397a9) | Jul 30, 2023 |
| Acer          | Aspire E5-511               | Notebook    | [93faaaff91](https://bsd-hardware.info/?probe=93faaaff91) | Jul 30, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [2619fadb11](https://bsd-hardware.info/?probe=2619fadb11) | Jul 29, 2023 |
| ASUSTek       | P8P67                       | Desktop     | [0e10359af8](https://bsd-hardware.info/?probe=0e10359af8) | Jul 29, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [64137e0eec](https://bsd-hardware.info/?probe=64137e0eec) | Jul 29, 2023 |
| AZW           | SER V2.0                    | Mini pc     | [14d1fdc0b1](https://bsd-hardware.info/?probe=14d1fdc0b1) | Jul 24, 2023 |
| Dell          | 0PTTT9 A01                  | Desktop     | [a3624fdcfc](https://bsd-hardware.info/?probe=a3624fdcfc) | Jul 24, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [f54cfd9d27](https://bsd-hardware.info/?probe=f54cfd9d27) | Jul 23, 2023 |
| MSI           | H81M-P33                    | Desktop     | [14b1509851](https://bsd-hardware.info/?probe=14b1509851) | Jul 23, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [7b725a65c4](https://bsd-hardware.info/?probe=7b725a65c4) | Jul 23, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [877ddd1995](https://bsd-hardware.info/?probe=877ddd1995) | Jul 23, 2023 |
| Chuwi         | LarkBox X                   | Mini pc     | [f77e9a46c3](https://bsd-hardware.info/?probe=f77e9a46c3) | Jul 22, 2023 |
| HP            | ProBook x360 11 G7 Educa... | Convertible | [22e1b9f0d5](https://bsd-hardware.info/?probe=22e1b9f0d5) | Jul 22, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [56fc67d3eb](https://bsd-hardware.info/?probe=56fc67d3eb) | Jul 22, 2023 |
| NOBLEX        | SF20BA                      | Notebook    | [a6a17eb5ca](https://bsd-hardware.info/?probe=a6a17eb5ca) | Jul 21, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [9f4f71236e](https://bsd-hardware.info/?probe=9f4f71236e) | Jul 21, 2023 |
| Lenovo        | ThinkPad T440s 20ARS1BK0... | Notebook    | [01f4886e09](https://bsd-hardware.info/?probe=01f4886e09) | Jul 21, 2023 |
| HPE           | ProLiant DL360 Gen10        | Server      | [115edf7c58](https://bsd-hardware.info/?probe=115edf7c58) | Jul 20, 2023 |
| Dell          | Precision 5550              | Notebook    | [4c9dd227a7](https://bsd-hardware.info/?probe=4c9dd227a7) | Jul 20, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [ce0f05e871](https://bsd-hardware.info/?probe=ce0f05e871) | Jul 18, 2023 |
| Samsung       | 100NZB                      | Notebook    | [5515e88fc1](https://bsd-hardware.info/?probe=5515e88fc1) | Jul 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [4a82a6a375](https://bsd-hardware.info/?probe=4a82a6a375) | Jul 17, 2023 |
| HUAWEI        | MRG-WXX                     | Notebook    | [ff4dbbacdf](https://bsd-hardware.info/?probe=ff4dbbacdf) | Jul 15, 2023 |
| Intel         | HM570                       | Desktop     | [a9abbf1e12](https://bsd-hardware.info/?probe=a9abbf1e12) | Jul 15, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [12124d8753](https://bsd-hardware.info/?probe=12124d8753) | Jul 15, 2023 |
| Lenovo        | ThinkPad T470s 20HGS3AX0... | Notebook    | [785b9af1f4](https://bsd-hardware.info/?probe=785b9af1f4) | Jul 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [a322b1ee22](https://bsd-hardware.info/?probe=a322b1ee22) | Jul 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [88fae8d98c](https://bsd-hardware.info/?probe=88fae8d98c) | Jul 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [1516e2960a](https://bsd-hardware.info/?probe=1516e2960a) | Jul 13, 2023 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [91965a9c00](https://bsd-hardware.info/?probe=91965a9c00) | Jul 13, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [bc36695565](https://bsd-hardware.info/?probe=bc36695565) | Jul 13, 2023 |
| Radxa         | rock-pi-n10a                | Desktop     | [a9767501e2](https://bsd-hardware.info/?probe=a9767501e2) | Jul 12, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [08b0409497](https://bsd-hardware.info/?probe=08b0409497) | Jul 12, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [f573d1d5c4](https://bsd-hardware.info/?probe=f573d1d5c4) | Jul 11, 2023 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [d0f09cc8c4](https://bsd-hardware.info/?probe=d0f09cc8c4) | Jul 11, 2023 |
| ASRock        | Z690 PG Riptide             | Desktop     | [813e46e924](https://bsd-hardware.info/?probe=813e46e924) | Jul 10, 2023 |
| MSI           | H81M-P33                    | Desktop     | [f0de15f4e2](https://bsd-hardware.info/?probe=f0de15f4e2) | Jul 09, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [3bb3ebc39d](https://bsd-hardware.info/?probe=3bb3ebc39d) | Jul 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [87bb7727a2](https://bsd-hardware.info/?probe=87bb7727a2) | Jul 09, 2023 |
| Getac         | F110G2                      | Notebook    | [b7b9efc38d](https://bsd-hardware.info/?probe=b7b9efc38d) | Jul 09, 2023 |
| Lenovo        | ThinkPad X250 20CLS13Q06    | Notebook    | [c318ab3cc7](https://bsd-hardware.info/?probe=c318ab3cc7) | Jul 09, 2023 |
| Lenovo        | ThinkPad T480s 20L8S45W0... | Notebook    | [80ac9dddda](https://bsd-hardware.info/?probe=80ac9dddda) | Jul 08, 2023 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | Notebook    | [4274ca291e](https://bsd-hardware.info/?probe=4274ca291e) | Jul 08, 2023 |
| HP            | 3397                        | Desktop     | [3d32ba4cd9](https://bsd-hardware.info/?probe=3d32ba4cd9) | Jul 08, 2023 |
| Dell          | 0PTTT9 A01                  | Desktop     | [0f55bad1af](https://bsd-hardware.info/?probe=0f55bad1af) | Jul 08, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | Notebook    | [7119cd7ae3](https://bsd-hardware.info/?probe=7119cd7ae3) | Jul 08, 2023 |
| MSI           | MAG B560 TORPEDO            | Desktop     | [e0d3f841c7](https://bsd-hardware.info/?probe=e0d3f841c7) | Jul 07, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [44b85aad5e](https://bsd-hardware.info/?probe=44b85aad5e) | Jul 07, 2023 |
| MSI           | H510I PRO WIFI              | Desktop     | [743d249ba5](https://bsd-hardware.info/?probe=743d249ba5) | Jul 07, 2023 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [e36e748937](https://bsd-hardware.info/?probe=e36e748937) | Jul 06, 2023 |
| ASRock        | Z690 PG Riptide             | Desktop     | [364cf5800b](https://bsd-hardware.info/?probe=364cf5800b) | Jul 06, 2023 |
| Lenovo        | ThinkPad T590 20N4001PUS    | Notebook    | [9e3b26b01b](https://bsd-hardware.info/?probe=9e3b26b01b) | Jul 06, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [2519fb81d6](https://bsd-hardware.info/?probe=2519fb81d6) | Jul 05, 2023 |
| HP            | 82F2 A01                    | Desktop     | [a77d73b637](https://bsd-hardware.info/?probe=a77d73b637) | Jul 04, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1HL0... | Notebook    | [f7b57506f0](https://bsd-hardware.info/?probe=f7b57506f0) | Jul 04, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | Notebook    | [f74b33bc25](https://bsd-hardware.info/?probe=f74b33bc25) | Jul 03, 2023 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [fd5fa70fb7](https://bsd-hardware.info/?probe=fd5fa70fb7) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [e569621be2](https://bsd-hardware.info/?probe=e569621be2) | Jul 03, 2023 |
| Gigabyte      | H270N-WIFI-CF               | Desktop     | [553cd9ecae](https://bsd-hardware.info/?probe=553cd9ecae) | Jul 03, 2023 |
| ASRock        | J3455B-ITX                  | Desktop     | [3c80c960d3](https://bsd-hardware.info/?probe=3c80c960d3) | Jul 03, 2023 |
| ASRock        | J3455B-ITX                  | Desktop     | [051ddf6f8d](https://bsd-hardware.info/?probe=051ddf6f8d) | Jul 03, 2023 |
| Gigabyte      | H270N-WIFI-CF               | Desktop     | [dfdb0bd650](https://bsd-hardware.info/?probe=dfdb0bd650) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [e68bb73773](https://bsd-hardware.info/?probe=e68bb73773) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [3b4a248520](https://bsd-hardware.info/?probe=3b4a248520) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [0a2a221aae](https://bsd-hardware.info/?probe=0a2a221aae) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [7e5ee8de12](https://bsd-hardware.info/?probe=7e5ee8de12) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [3b50a90ebc](https://bsd-hardware.info/?probe=3b50a90ebc) | Jul 03, 2023 |
| Gigabyte      | M85M-US2H                   | Desktop     | [e0a38ef6ad](https://bsd-hardware.info/?probe=e0a38ef6ad) | Jul 03, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | Notebook    | [f9f815c60e](https://bsd-hardware.info/?probe=f9f815c60e) | Jul 02, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | Notebook    | [39e46fd477](https://bsd-hardware.info/?probe=39e46fd477) | Jul 02, 2023 |
| MSI           | H81M-P33                    | Desktop     | [71edaf952e](https://bsd-hardware.info/?probe=71edaf952e) | Jul 02, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [98254451c1](https://bsd-hardware.info/?probe=98254451c1) | Jul 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [977d44457e](https://bsd-hardware.info/?probe=977d44457e) | Jul 02, 2023 |
| Dell          | 03KWTV A00                  | Desktop     | [d8f6429e70](https://bsd-hardware.info/?probe=d8f6429e70) | Jul 02, 2023 |
| Gigabyte      | H77M-D3H                    | Desktop     | [9f6d45e43e](https://bsd-hardware.info/?probe=9f6d45e43e) | Jul 02, 2023 |
| Gigabyte      | H77M-D3H                    | Desktop     | [3eb03fa8a7](https://bsd-hardware.info/?probe=3eb03fa8a7) | Jul 02, 2023 |
| Gigabyte      | B360M D2V                   | Desktop     | [bf5f6fd6dd](https://bsd-hardware.info/?probe=bf5f6fd6dd) | Jun 30, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [6479d60da2](https://bsd-hardware.info/?probe=6479d60da2) | Jun 30, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [b6cfa09740](https://bsd-hardware.info/?probe=b6cfa09740) | Jun 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [c07f4ffa1e](https://bsd-hardware.info/?probe=c07f4ffa1e) | Jun 29, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [1aff07438c](https://bsd-hardware.info/?probe=1aff07438c) | Jun 28, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [03c29939fc](https://bsd-hardware.info/?probe=03c29939fc) | Jun 28, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [748ae83ba1](https://bsd-hardware.info/?probe=748ae83ba1) | Jun 27, 2023 |
| HP            | EliteBook 850 G5            | Notebook    | [4bae8cd192](https://bsd-hardware.info/?probe=4bae8cd192) | Jun 27, 2023 |
| Intel         | NUC12WSBi3 M36953-303       | Mini pc     | [6823b41760](https://bsd-hardware.info/?probe=6823b41760) | Jun 27, 2023 |
| Dell          | Latitude 3420               | Notebook    | [057f065baa](https://bsd-hardware.info/?probe=057f065baa) | Jun 26, 2023 |
| Lenovo        | ThinkPad T440p 20AW000BU... | Notebook    | [9a7628d17b](https://bsd-hardware.info/?probe=9a7628d17b) | Jun 26, 2023 |
| MSI           | H81M-P33                    | Desktop     | [80bd24461a](https://bsd-hardware.info/?probe=80bd24461a) | Jun 25, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [e368d55893](https://bsd-hardware.info/?probe=e368d55893) | Jun 25, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [483865aca5](https://bsd-hardware.info/?probe=483865aca5) | Jun 25, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [e7dfbf94d0](https://bsd-hardware.info/?probe=e7dfbf94d0) | Jun 25, 2023 |
| HP            | Pavilion g4                 | Notebook    | [ef66b5588a](https://bsd-hardware.info/?probe=ef66b5588a) | Jun 23, 2023 |
| HP            | 1000                        | Notebook    | [21faecd7a6](https://bsd-hardware.info/?probe=21faecd7a6) | Jun 23, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | Notebook    | [d194e8bc0d](https://bsd-hardware.info/?probe=d194e8bc0d) | Jun 22, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [6172c8b66f](https://bsd-hardware.info/?probe=6172c8b66f) | Jun 22, 2023 |
| ASUSTek       | P5K PRO                     | Desktop     | [f0b283fdaf](https://bsd-hardware.info/?probe=f0b283fdaf) | Jun 19, 2023 |
| Apple         | MacBook2,1                  | Notebook    | [9e864bfe3b](https://bsd-hardware.info/?probe=9e864bfe3b) | Jun 18, 2023 |
| Dell          | Latitude E6520              | Notebook    | [98868960d5](https://bsd-hardware.info/?probe=98868960d5) | Jun 18, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [b0659ff5bf](https://bsd-hardware.info/?probe=b0659ff5bf) | Jun 18, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [53bbc07cc8](https://bsd-hardware.info/?probe=53bbc07cc8) | Jun 17, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [705c750691](https://bsd-hardware.info/?probe=705c750691) | Jun 17, 2023 |
| AZW           | SER                         | Mini pc     | [278b419d40](https://bsd-hardware.info/?probe=278b419d40) | Jun 17, 2023 |
| Lenovo        | ThinkCentre A70 7099A5P     | Desktop     | [4e827b2cbf](https://bsd-hardware.info/?probe=4e827b2cbf) | Jun 16, 2023 |
| Lenovo        | ThinkCentre A70 7099A5P     | Desktop     | [3d71827388](https://bsd-hardware.info/?probe=3d71827388) | Jun 16, 2023 |
| IBM           | 69Y5698                     | Server      | [9f5eb975e0](https://bsd-hardware.info/?probe=9f5eb975e0) | Jun 16, 2023 |
| Dell          | 053CWD A00                  | Desktop     | [7a5418ac7e](https://bsd-hardware.info/?probe=7a5418ac7e) | Jun 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [6b4f214b72](https://bsd-hardware.info/?probe=6b4f214b72) | Jun 15, 2023 |
| Notebook      | NL5xRU                      | Notebook    | [04ca736537](https://bsd-hardware.info/?probe=04ca736537) | Jun 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [615e7cbf52](https://bsd-hardware.info/?probe=615e7cbf52) | Jun 15, 2023 |
| Lenovo        | ThinkPad T480 20L6S2S800    | Notebook    | [722403df31](https://bsd-hardware.info/?probe=722403df31) | Jun 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [8357f0f72e](https://bsd-hardware.info/?probe=8357f0f72e) | Jun 15, 2023 |
| Lenovo        | ThinkPad T430 2347GR2       | Notebook    | [834f9f8748](https://bsd-hardware.info/?probe=834f9f8748) | Jun 15, 2023 |
| Lenovo        | ThinkPad T450 20BV000BUS    | Notebook    | [7e1aa76e45](https://bsd-hardware.info/?probe=7e1aa76e45) | Jun 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [f41e1f2b83](https://bsd-hardware.info/?probe=f41e1f2b83) | Jun 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [4841a6b1d2](https://bsd-hardware.info/?probe=4841a6b1d2) | Jun 14, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [6e8e70ddc2](https://bsd-hardware.info/?probe=6e8e70ddc2) | Jun 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [c19a29f083](https://bsd-hardware.info/?probe=c19a29f083) | Jun 13, 2023 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [f6540a4d85](https://bsd-hardware.info/?probe=f6540a4d85) | Jun 13, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [5a21ed950e](https://bsd-hardware.info/?probe=5a21ed950e) | Jun 13, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [1d3675e09e](https://bsd-hardware.info/?probe=1d3675e09e) | Jun 11, 2023 |
| Acer          | Aspire E5-571G              | Notebook    | [9279b8ab4e](https://bsd-hardware.info/?probe=9279b8ab4e) | Jun 11, 2023 |
| MSI           | H81M-P33                    | Desktop     | [3d9a05635f](https://bsd-hardware.info/?probe=3d9a05635f) | Jun 11, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [b8f3eeed4b](https://bsd-hardware.info/?probe=b8f3eeed4b) | Jun 11, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [9c888141fb](https://bsd-hardware.info/?probe=9c888141fb) | Jun 11, 2023 |
| Lenovo        | B40-30 80F10002BR           | Notebook    | [769c678314](https://bsd-hardware.info/?probe=769c678314) | Jun 10, 2023 |
| Lenovo        | ThinkPad T430 2347GR2       | Notebook    | [439e6a5034](https://bsd-hardware.info/?probe=439e6a5034) | Jun 10, 2023 |
| MSI           | PRESTIGE X570 CREATION      | Desktop     | [7e0151a93f](https://bsd-hardware.info/?probe=7e0151a93f) | Jun 10, 2023 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | Notebook    | [27ba75252a](https://bsd-hardware.info/?probe=27ba75252a) | Jun 09, 2023 |
| Lenovo        | ThinkPad T480 20L6S5VP4C    | Notebook    | [b891388109](https://bsd-hardware.info/?probe=b891388109) | Jun 07, 2023 |
| Lenovo        | ThinkPad T500 2082BNU       | Notebook    | [dedd066084](https://bsd-hardware.info/?probe=dedd066084) | Jun 06, 2023 |
| ASRock        | Z590 Pro4                   | Desktop     | [d04a63aa31](https://bsd-hardware.info/?probe=d04a63aa31) | Jun 06, 2023 |
| Lenovo        | IdeaPad Slim 9 14ITL5 82... | Notebook    | [03e1e6d302](https://bsd-hardware.info/?probe=03e1e6d302) | Jun 05, 2023 |
| HP            | 212B                        | Desktop     | [4db61072c4](https://bsd-hardware.info/?probe=4db61072c4) | Jun 05, 2023 |
| Toshiba       | Satellite C70-B             | Notebook    | [cf9ed85e65](https://bsd-hardware.info/?probe=cf9ed85e65) | Jun 05, 2023 |
| Toshiba       | Satellite C70-B             | Notebook    | [fc66ebba25](https://bsd-hardware.info/?probe=fc66ebba25) | Jun 05, 2023 |
| MSI           | H81M-P33                    | Desktop     | [88598bfbf5](https://bsd-hardware.info/?probe=88598bfbf5) | Jun 04, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [fac0ed387e](https://bsd-hardware.info/?probe=fac0ed387e) | Jun 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [3c76deca15](https://bsd-hardware.info/?probe=3c76deca15) | Jun 04, 2023 |
| Lenovo        | B590 20208                  | Notebook    | [dc65d735c8](https://bsd-hardware.info/?probe=dc65d735c8) | Jun 04, 2023 |
| ASRock        | Z590 Pro4                   | Desktop     | [314d462dcd](https://bsd-hardware.info/?probe=314d462dcd) | Jun 04, 2023 |
| Dell          | G5 5505                     | Notebook    | [5a3c1f19a0](https://bsd-hardware.info/?probe=5a3c1f19a0) | Jun 03, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [d4247f35c8](https://bsd-hardware.info/?probe=d4247f35c8) | Jun 02, 2023 |
| Dell          | G5 5505                     | Notebook    | [1b10aecc38](https://bsd-hardware.info/?probe=1b10aecc38) | Jun 02, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [22572f1df6](https://bsd-hardware.info/?probe=22572f1df6) | Jun 01, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | Notebook    | [8cc6299ba9](https://bsd-hardware.info/?probe=8cc6299ba9) | May 31, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [2445651c96](https://bsd-hardware.info/?probe=2445651c96) | May 31, 2023 |
| Lenovo        | ThinkPad X270 20HMCTO1WW    | Notebook    | [b5f507c034](https://bsd-hardware.info/?probe=b5f507c034) | May 31, 2023 |
| ASRock        | Z590 Pro4                   | Desktop     | [a9b9a2e045](https://bsd-hardware.info/?probe=a9b9a2e045) | May 29, 2023 |
| ASRock        | Z590 Pro4                   | Desktop     | [e63f1f4874](https://bsd-hardware.info/?probe=e63f1f4874) | May 29, 2023 |
| ASRock        | Z590 Pro4                   | Desktop     | [382fe30ec1](https://bsd-hardware.info/?probe=382fe30ec1) | May 28, 2023 |
| Gigabyte      | H170-D3HP-CF                | Desktop     | [d5fdf2ff2c](https://bsd-hardware.info/?probe=d5fdf2ff2c) | May 28, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | Notebook    | [6701dce30e](https://bsd-hardware.info/?probe=6701dce30e) | May 28, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [28c84f71fd](https://bsd-hardware.info/?probe=28c84f71fd) | May 28, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [cf8b2af78b](https://bsd-hardware.info/?probe=cf8b2af78b) | May 28, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [3944241750](https://bsd-hardware.info/?probe=3944241750) | May 27, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [65376d6b42](https://bsd-hardware.info/?probe=65376d6b42) | May 27, 2023 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | Desktop     | [8514299fe4](https://bsd-hardware.info/?probe=8514299fe4) | May 26, 2023 |
| Acer          | Nitro AN515-42              | Notebook    | [adc687fcfe](https://bsd-hardware.info/?probe=adc687fcfe) | May 26, 2023 |
| ASRockRack    | GENOAD8UD-2T/X550           | Desktop     | [c6b62c6b5b](https://bsd-hardware.info/?probe=c6b62c6b5b) | May 26, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [81775d5ca1](https://bsd-hardware.info/?probe=81775d5ca1) | May 26, 2023 |
| Supermicro    | M11SDV-8C-LN4F              | Server      | [3797f9d0a9](https://bsd-hardware.info/?probe=3797f9d0a9) | May 24, 2023 |
| Lenovo        | ThinkPad T430 2347CTO       | Notebook    | [68937b1686](https://bsd-hardware.info/?probe=68937b1686) | May 24, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [a1a68c0f7d](https://bsd-hardware.info/?probe=a1a68c0f7d) | May 24, 2023 |
| Acer          | Aspire E5-573               | Notebook    | [7bcb7c96be](https://bsd-hardware.info/?probe=7bcb7c96be) | May 23, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [9a2c066dfa](https://bsd-hardware.info/?probe=9a2c066dfa) | May 23, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [b5f17b6bf8](https://bsd-hardware.info/?probe=b5f17b6bf8) | May 23, 2023 |
| ASUSTek       | PRIME A520M-A II            | Desktop     | [eba55377e0](https://bsd-hardware.info/?probe=eba55377e0) | May 22, 2023 |
| MSI           | H81M-P33                    | Desktop     | [cadb0f588f](https://bsd-hardware.info/?probe=cadb0f588f) | May 21, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [4a55c4a669](https://bsd-hardware.info/?probe=4a55c4a669) | May 21, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [f2fb56c7dc](https://bsd-hardware.info/?probe=f2fb56c7dc) | May 21, 2023 |
| Acer          | Aspire A514-54              | Notebook    | [7aed9d938a](https://bsd-hardware.info/?probe=7aed9d938a) | May 21, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [a87acae699](https://bsd-hardware.info/?probe=a87acae699) | May 21, 2023 |
| HP            | 158B                        | Desktop     | [1ef3762103](https://bsd-hardware.info/?probe=1ef3762103) | May 20, 2023 |
| HP            | 158B                        | Desktop     | [a9c63041a6](https://bsd-hardware.info/?probe=a9c63041a6) | May 20, 2023 |
| Intel         | NUC11PHBi7 M26151-405       | Mini pc     | [186e5d4e15](https://bsd-hardware.info/?probe=186e5d4e15) | May 19, 2023 |
| ASUSTek       | WS-C621E-SAGE Series        | Server      | [47d985333c](https://bsd-hardware.info/?probe=47d985333c) | May 19, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [70d54595c2](https://bsd-hardware.info/?probe=70d54595c2) | May 19, 2023 |
| Valve         | Jupiter                     | Notebook    | [7be0869603](https://bsd-hardware.info/?probe=7be0869603) | May 19, 2023 |
| Valve         | Jupiter                     | Notebook    | [ef56a2bd17](https://bsd-hardware.info/?probe=ef56a2bd17) | May 19, 2023 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [9350bb37db](https://bsd-hardware.info/?probe=9350bb37db) | May 18, 2023 |
| Lenovo        | ThinkPad T560 20FJS03Q00    | Notebook    | [a2110471aa](https://bsd-hardware.info/?probe=a2110471aa) | May 18, 2023 |
| Supermicro    | M11SDV-8C-LN4F              | Server      | [73335cbb47](https://bsd-hardware.info/?probe=73335cbb47) | May 17, 2023 |
| Gigabyte      | H170-D3HP-CF                | Desktop     | [830100249f](https://bsd-hardware.info/?probe=830100249f) | May 17, 2023 |
| Panasonic     | CF-30KAPAXAM                | Notebook    | [62910ad9d9](https://bsd-hardware.info/?probe=62910ad9d9) | May 17, 2023 |
| Supermicro    | M11SDV-8C-LN4F              | Server      | [12b0e44025](https://bsd-hardware.info/?probe=12b0e44025) | May 17, 2023 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | Desktop     | [27be69ed61](https://bsd-hardware.info/?probe=27be69ed61) | May 15, 2023 |
| Dell          | Inspiron 3581               | Notebook    | [25c403ca33](https://bsd-hardware.info/?probe=25c403ca33) | May 15, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [e252dc5ff2](https://bsd-hardware.info/?probe=e252dc5ff2) | May 15, 2023 |
| Dell          | Inspiron 3581               | Notebook    | [8d445a3fb3](https://bsd-hardware.info/?probe=8d445a3fb3) | May 14, 2023 |
| ASRock        | Z790M-ITX WiFi              | Desktop     | [3bf2cd6d1e](https://bsd-hardware.info/?probe=3bf2cd6d1e) | May 14, 2023 |
| MSI           | B450M MORTAR                | Desktop     | [7d0fe109f0](https://bsd-hardware.info/?probe=7d0fe109f0) | May 14, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [526906c806](https://bsd-hardware.info/?probe=526906c806) | May 14, 2023 |
| MSI           | B85M-G43                    | Desktop     | [6d2160dcee](https://bsd-hardware.info/?probe=6d2160dcee) | May 14, 2023 |
| Alienware     | 17 R4                       | Notebook    | [df734c8e64](https://bsd-hardware.info/?probe=df734c8e64) | May 14, 2023 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | Desktop     | [47800f4d42](https://bsd-hardware.info/?probe=47800f4d42) | May 14, 2023 |
| MSI           | H81M-P33                    | Desktop     | [ebf1ee8152](https://bsd-hardware.info/?probe=ebf1ee8152) | May 14, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [2bf04b4cf1](https://bsd-hardware.info/?probe=2bf04b4cf1) | May 14, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ae7796a444](https://bsd-hardware.info/?probe=ae7796a444) | May 14, 2023 |
| HP            | 802F                        | Desktop     | [fdf293f78f](https://bsd-hardware.info/?probe=fdf293f78f) | May 14, 2023 |
| Supermicro    | M11SDV-8C-LN4F              | Server      | [71ad6e7c1c](https://bsd-hardware.info/?probe=71ad6e7c1c) | May 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [8aede62ca8](https://bsd-hardware.info/?probe=8aede62ca8) | May 14, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [a477479a00](https://bsd-hardware.info/?probe=a477479a00) | May 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [de9fcd9543](https://bsd-hardware.info/?probe=de9fcd9543) | May 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [990b3eb510](https://bsd-hardware.info/?probe=990b3eb510) | May 12, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [d72b0581a4](https://bsd-hardware.info/?probe=d72b0581a4) | May 11, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [b5ce0177b2](https://bsd-hardware.info/?probe=b5ce0177b2) | May 10, 2023 |
| Medion        | Major X10                   | Notebook    | [99228fd9da](https://bsd-hardware.info/?probe=99228fd9da) | May 10, 2023 |
| Intel         | NUC11PHBi7 M26151-405       | Mini pc     | [89cd98c281](https://bsd-hardware.info/?probe=89cd98c281) | May 10, 2023 |
| Notebook      | N7x0WU                      | Notebook    | [7a646e185a](https://bsd-hardware.info/?probe=7a646e185a) | May 09, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [dcea67b6a6](https://bsd-hardware.info/?probe=dcea67b6a6) | May 08, 2023 |
| MSI           | H81M-P33                    | Desktop     | [55cfed4de4](https://bsd-hardware.info/?probe=55cfed4de4) | May 07, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [0cb51a327e](https://bsd-hardware.info/?probe=0cb51a327e) | May 07, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [7e41914431](https://bsd-hardware.info/?probe=7e41914431) | May 07, 2023 |
| HP            | 805D                        | Desktop     | [648c680432](https://bsd-hardware.info/?probe=648c680432) | May 07, 2023 |
| Panasonic     | CF-30KAPAXAM                | Notebook    | [1c918b79b0](https://bsd-hardware.info/?probe=1c918b79b0) | May 06, 2023 |
| ASUSTek       | P5K SE/EPU                  | Desktop     | [4cde43ac30](https://bsd-hardware.info/?probe=4cde43ac30) | May 04, 2023 |
| ASUSTek       | WS-C621E-SAGE Series        | Server      | [a80b700f3a](https://bsd-hardware.info/?probe=a80b700f3a) | May 04, 2023 |
| Supermicro    | X10DRi-T                    | Desktop     | [ba54a43cb4](https://bsd-hardware.info/?probe=ba54a43cb4) | May 03, 2023 |
| HP            | 1589                        | Desktop     | [4aee1909c8](https://bsd-hardware.info/?probe=4aee1909c8) | May 03, 2023 |
| Samsung       | NC110P/NC108P/NC111P        | Notebook    | [ea55a6fecf](https://bsd-hardware.info/?probe=ea55a6fecf) | May 02, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [b09acffe7b](https://bsd-hardware.info/?probe=b09acffe7b) | May 01, 2023 |
| Unknown       | HX90                        | Desktop     | [b3300c45bc](https://bsd-hardware.info/?probe=b3300c45bc) | May 01, 2023 |
| AZW           | SER                         | Mini pc     | [d3d9ba6f52](https://bsd-hardware.info/?probe=d3d9ba6f52) | Apr 30, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [9d82570c34](https://bsd-hardware.info/?probe=9d82570c34) | Apr 30, 2023 |
| Dell          | 0FF3FN A00                  | Desktop     | [717b46840a](https://bsd-hardware.info/?probe=717b46840a) | Apr 30, 2023 |
| Dell          | 0H634K A00                  | Desktop     | [5e783a1c2e](https://bsd-hardware.info/?probe=5e783a1c2e) | Apr 30, 2023 |
| GVC           | DR 738                      | Desktop     | [21b338db1b](https://bsd-hardware.info/?probe=21b338db1b) | Apr 30, 2023 |
| MSI           | H81M-P33                    | Desktop     | [e28acf1164](https://bsd-hardware.info/?probe=e28acf1164) | Apr 30, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [33d1b6e2d2](https://bsd-hardware.info/?probe=33d1b6e2d2) | Apr 30, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [b0d9eaaceb](https://bsd-hardware.info/?probe=b0d9eaaceb) | Apr 30, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [ce8453fcce](https://bsd-hardware.info/?probe=ce8453fcce) | Apr 27, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [fc81710889](https://bsd-hardware.info/?probe=fc81710889) | Apr 27, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [692df89c1f](https://bsd-hardware.info/?probe=692df89c1f) | Apr 26, 2023 |
| Gigabyte      | B360M D2V                   | Desktop     | [d4881f1fb6](https://bsd-hardware.info/?probe=d4881f1fb6) | Apr 25, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [d3373e972b](https://bsd-hardware.info/?probe=d3373e972b) | Apr 24, 2023 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [214b0c30e0](https://bsd-hardware.info/?probe=214b0c30e0) | Apr 23, 2023 |
| HP            | Unknown                     | Notebook    | [e2aa3620b4](https://bsd-hardware.info/?probe=e2aa3620b4) | Apr 23, 2023 |
| MSI           | H81M-P33                    | Desktop     | [6df7a17ff2](https://bsd-hardware.info/?probe=6df7a17ff2) | Apr 23, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [37564b68c3](https://bsd-hardware.info/?probe=37564b68c3) | Apr 23, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [d44a98739c](https://bsd-hardware.info/?probe=d44a98739c) | Apr 23, 2023 |
| Dell          | 0569RT A04                  | Server      | [cff2ebd06b](https://bsd-hardware.info/?probe=cff2ebd06b) | Apr 23, 2023 |
| Intel         | NUC11PHBi7 M26151-402       | Mini pc     | [596ddff446](https://bsd-hardware.info/?probe=596ddff446) | Apr 22, 2023 |
| ASUSTek       | P8H77-V                     | Desktop     | [60f61f7ecb](https://bsd-hardware.info/?probe=60f61f7ecb) | Apr 22, 2023 |
| Intel Clie... | LAPBC510                    | Notebook    | [68b1300903](https://bsd-hardware.info/?probe=68b1300903) | Apr 22, 2023 |
| Lenovo        | ThinkPad W520 4270CTO       | Notebook    | [51f0a87f01](https://bsd-hardware.info/?probe=51f0a87f01) | Apr 21, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [e17bcecec8](https://bsd-hardware.info/?probe=e17bcecec8) | Apr 21, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [838979f891](https://bsd-hardware.info/?probe=838979f891) | Apr 20, 2023 |
| Dell          | Latitude 7280               | Notebook    | [254acb5df8](https://bsd-hardware.info/?probe=254acb5df8) | Apr 20, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [6e82f69c4c](https://bsd-hardware.info/?probe=6e82f69c4c) | Apr 20, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [541f3e7f7e](https://bsd-hardware.info/?probe=541f3e7f7e) | Apr 20, 2023 |
| Dell          | Precision 5510              | Notebook    | [7028fde527](https://bsd-hardware.info/?probe=7028fde527) | Apr 20, 2023 |
| HP            | 158B                        | Desktop     | [40fe372619](https://bsd-hardware.info/?probe=40fe372619) | Apr 20, 2023 |
| Lenovo        | ThinkPad X201 3626WNP       | Notebook    | [d642970071](https://bsd-hardware.info/?probe=d642970071) | Apr 19, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [3852dcb332](https://bsd-hardware.info/?probe=3852dcb332) | Apr 19, 2023 |
| ASUSTek       | Pro B560M-C                 | Desktop     | [b341a9c9c9](https://bsd-hardware.info/?probe=b341a9c9c9) | Apr 19, 2023 |
| HP            | Unknown                     | Notebook    | [941c021569](https://bsd-hardware.info/?probe=941c021569) | Apr 18, 2023 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [464059d8b1](https://bsd-hardware.info/?probe=464059d8b1) | Apr 18, 2023 |
| Lenovo        | YangTianM6880N              | Desktop     | [a567c3062c](https://bsd-hardware.info/?probe=a567c3062c) | Apr 18, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | Notebook    | [b8d2c0d81d](https://bsd-hardware.info/?probe=b8d2c0d81d) | Apr 16, 2023 |
| MSI           | H81M-P33                    | Desktop     | [e285cc821f](https://bsd-hardware.info/?probe=e285cc821f) | Apr 16, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [b79bdd39da](https://bsd-hardware.info/?probe=b79bdd39da) | Apr 16, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [e6734bf5e3](https://bsd-hardware.info/?probe=e6734bf5e3) | Apr 16, 2023 |
| Lenovo        | Larne CRB 31900002 WIN      | All in one  | [1f18ec4466](https://bsd-hardware.info/?probe=1f18ec4466) | Apr 16, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [cf533da9bf](https://bsd-hardware.info/?probe=cf533da9bf) | Apr 16, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [4dfa2f0148](https://bsd-hardware.info/?probe=4dfa2f0148) | Apr 15, 2023 |
| ASUSTek       | PRIME X299-A II             | Desktop     | [8c345e7a24](https://bsd-hardware.info/?probe=8c345e7a24) | Apr 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [926ab149ae](https://bsd-hardware.info/?probe=926ab149ae) | Apr 14, 2023 |
| HP            | ProLiant DL180 G6           | Server      | [4ccb132836](https://bsd-hardware.info/?probe=4ccb132836) | Apr 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [b189b0988c](https://bsd-hardware.info/?probe=b189b0988c) | Apr 14, 2023 |
| Lenovo        | ThinkPad R61 89208RU        | Notebook    | [e892cdffee](https://bsd-hardware.info/?probe=e892cdffee) | Apr 13, 2023 |
| F-Plus Mob... | FLAPTOP r                   | Notebook    | [3d7bf4205b](https://bsd-hardware.info/?probe=3d7bf4205b) | Apr 13, 2023 |
| HMT           | W041-TF-A-45                | Notebook    | [298d106fd1](https://bsd-hardware.info/?probe=298d106fd1) | Apr 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [e2b6422180](https://bsd-hardware.info/?probe=e2b6422180) | Apr 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [f54d0b103e](https://bsd-hardware.info/?probe=f54d0b103e) | Apr 13, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [4ae38adc2a](https://bsd-hardware.info/?probe=4ae38adc2a) | Apr 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [c960f2dc8b](https://bsd-hardware.info/?probe=c960f2dc8b) | Apr 12, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [bee20c6a4c](https://bsd-hardware.info/?probe=bee20c6a4c) | Apr 12, 2023 |
| HP            | 212B                        | Desktop     | [0fb2a36b23](https://bsd-hardware.info/?probe=0fb2a36b23) | Apr 12, 2023 |
| Supermicro    | M11SDV-8C+-LN4F             | Server      | [f7bcf353a9](https://bsd-hardware.info/?probe=f7bcf353a9) | Apr 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [add8280600](https://bsd-hardware.info/?probe=add8280600) | Apr 11, 2023 |
| MSI           | H81M-P33                    | Desktop     | [90ab4216eb](https://bsd-hardware.info/?probe=90ab4216eb) | Apr 09, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [62358071bf](https://bsd-hardware.info/?probe=62358071bf) | Apr 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [a06682a305](https://bsd-hardware.info/?probe=a06682a305) | Apr 09, 2023 |
| HP            | 212B                        | Desktop     | [6dc537109d](https://bsd-hardware.info/?probe=6dc537109d) | Apr 09, 2023 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [6dabd5d84a](https://bsd-hardware.info/?probe=6dabd5d84a) | Apr 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [f96c113329](https://bsd-hardware.info/?probe=f96c113329) | Apr 08, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [a305360215](https://bsd-hardware.info/?probe=a305360215) | Apr 05, 2023 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [a4957dcdd6](https://bsd-hardware.info/?probe=a4957dcdd6) | Apr 04, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [ee2b566f14](https://bsd-hardware.info/?probe=ee2b566f14) | Apr 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [c801b9e5af](https://bsd-hardware.info/?probe=c801b9e5af) | Apr 03, 2023 |
| HP            | 81C6 MVB 0C                 | Server      | [65d2113596](https://bsd-hardware.info/?probe=65d2113596) | Apr 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [9b2420726f](https://bsd-hardware.info/?probe=9b2420726f) | Apr 03, 2023 |
| HP            | 212B                        | Desktop     | [00c0cbbc9a](https://bsd-hardware.info/?probe=00c0cbbc9a) | Apr 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [414cbf5935](https://bsd-hardware.info/?probe=414cbf5935) | Apr 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [6b79c64c73](https://bsd-hardware.info/?probe=6b79c64c73) | Apr 03, 2023 |
| Gigabyte      | GB-BSi3-1115G4              | Desktop     | [2a7e5e0e71](https://bsd-hardware.info/?probe=2a7e5e0e71) | Apr 02, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [911a1723a2](https://bsd-hardware.info/?probe=911a1723a2) | Apr 02, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [01bf5e8678](https://bsd-hardware.info/?probe=01bf5e8678) | Apr 02, 2023 |
| MSI           | H81M-P33                    | Desktop     | [0013b5dfa4](https://bsd-hardware.info/?probe=0013b5dfa4) | Apr 02, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [ff7383d618](https://bsd-hardware.info/?probe=ff7383d618) | Apr 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [d4cc6cf349](https://bsd-hardware.info/?probe=d4cc6cf349) | Apr 02, 2023 |
| Lenovo        | ThinkPad T590 20N4001PUS    | Notebook    | [0b93ef8199](https://bsd-hardware.info/?probe=0b93ef8199) | Apr 02, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [9bac0139f1](https://bsd-hardware.info/?probe=9bac0139f1) | Apr 01, 2023 |
| Chuwi         | Unknown                     | Notebook    | [5e687fcc83](https://bsd-hardware.info/?probe=5e687fcc83) | Apr 01, 2023 |
| ASRock        | X570S PG Riptide            | Desktop     | [8ccb321056](https://bsd-hardware.info/?probe=8ccb321056) | Apr 01, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [c7944c3ce9](https://bsd-hardware.info/?probe=c7944c3ce9) | Mar 31, 2023 |
| SolidRun      | CEX7 Platform               | Desktop     | [8e2e4d6686](https://bsd-hardware.info/?probe=8e2e4d6686) | Mar 31, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [3c3a780d95](https://bsd-hardware.info/?probe=3c3a780d95) | Mar 31, 2023 |
| ASRockRack    | EPYCD8-2T                   | Desktop     | [75f414997a](https://bsd-hardware.info/?probe=75f414997a) | Mar 31, 2023 |
| HP            | 339A                        | Desktop     | [ad10416fe3](https://bsd-hardware.info/?probe=ad10416fe3) | Mar 31, 2023 |
| Biostar       | TH67B                       | Desktop     | [234c5e0b83](https://bsd-hardware.info/?probe=234c5e0b83) | Mar 31, 2023 |
| HMT           | W041-TF-A-45                | Notebook    | [666df5a7e0](https://bsd-hardware.info/?probe=666df5a7e0) | Mar 31, 2023 |
| ASRock        | X570M Pro4                  | Desktop     | [1d7c737c38](https://bsd-hardware.info/?probe=1d7c737c38) | Mar 29, 2023 |
| Google        | Stout                       | Notebook    | [d8346bb5da](https://bsd-hardware.info/?probe=d8346bb5da) | Mar 29, 2023 |
| Alienware     | 049PDM A00                  | Desktop     | [139d115cdb](https://bsd-hardware.info/?probe=139d115cdb) | Mar 29, 2023 |
| Shuttle       | FH110                       | Desktop     | [4fa8a9cc08](https://bsd-hardware.info/?probe=4fa8a9cc08) | Mar 28, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [b4805cd318](https://bsd-hardware.info/?probe=b4805cd318) | Mar 27, 2023 |
| ASRock        | X570S PG Riptide            | Desktop     | [0d66edbd38](https://bsd-hardware.info/?probe=0d66edbd38) | Mar 27, 2023 |
| Dell          | 0VD5HY A00                  | Desktop     | [1b54a68123](https://bsd-hardware.info/?probe=1b54a68123) | Mar 26, 2023 |
| Dell          | 0C2GT0 A05                  | Server      | [2d32ae23e6](https://bsd-hardware.info/?probe=2d32ae23e6) | Mar 26, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [7652c9891e](https://bsd-hardware.info/?probe=7652c9891e) | Mar 26, 2023 |
| MSI           | H81M-P33                    | Desktop     | [f07e9fd36c](https://bsd-hardware.info/?probe=f07e9fd36c) | Mar 26, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [3f21567fdf](https://bsd-hardware.info/?probe=3f21567fdf) | Mar 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [38a22651c6](https://bsd-hardware.info/?probe=38a22651c6) | Mar 26, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [a46f77ccdc](https://bsd-hardware.info/?probe=a46f77ccdc) | Mar 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [b64571464f](https://bsd-hardware.info/?probe=b64571464f) | Mar 25, 2023 |
| HP            | 1497                        | Desktop     | [08daaf3be1](https://bsd-hardware.info/?probe=08daaf3be1) | Mar 25, 2023 |
| HP            | 21B4 A01                    | Desktop     | [8de4b8231a](https://bsd-hardware.info/?probe=8de4b8231a) | Mar 25, 2023 |
| HP            | 1497                        | Desktop     | [fc6a7ebc91](https://bsd-hardware.info/?probe=fc6a7ebc91) | Mar 25, 2023 |
| eMachines     | eM350                       | Notebook    | [bb900ace2d](https://bsd-hardware.info/?probe=bb900ace2d) | Mar 25, 2023 |
| HP            | 1497                        | Desktop     | [e98b5284d9](https://bsd-hardware.info/?probe=e98b5284d9) | Mar 25, 2023 |
| Alienware     | 14                          | Notebook    | [742d648570](https://bsd-hardware.info/?probe=742d648570) | Mar 25, 2023 |
| Acer          | AOD270                      | Notebook    | [73877008e9](https://bsd-hardware.info/?probe=73877008e9) | Mar 25, 2023 |
| Acer          | Nitro AN515-53              | Notebook    | [a46e065fac](https://bsd-hardware.info/?probe=a46e065fac) | Mar 23, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [f294f7ae04](https://bsd-hardware.info/?probe=f294f7ae04) | Mar 23, 2023 |
| HP            | 3397                        | Desktop     | [a3a77965fc](https://bsd-hardware.info/?probe=a3a77965fc) | Mar 23, 2023 |
| Intel         | SandyBridge Platform        | Notebook    | [954a21f7de](https://bsd-hardware.info/?probe=954a21f7de) | Mar 23, 2023 |
| Dell          | Edge Gateway 5100           | Mini pc     | [7cb4288db0](https://bsd-hardware.info/?probe=7cb4288db0) | Mar 23, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [e1b5d66244](https://bsd-hardware.info/?probe=e1b5d66244) | Mar 20, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [4dc54510d2](https://bsd-hardware.info/?probe=4dc54510d2) | Mar 19, 2023 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [cab50cddd5](https://bsd-hardware.info/?probe=cab50cddd5) | Mar 19, 2023 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [ff4dda40eb](https://bsd-hardware.info/?probe=ff4dda40eb) | Mar 19, 2023 |
| MSI           | H81M-P33                    | Desktop     | [17f0f138ee](https://bsd-hardware.info/?probe=17f0f138ee) | Mar 19, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [da50d91be4](https://bsd-hardware.info/?probe=da50d91be4) | Mar 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [726abe2f1d](https://bsd-hardware.info/?probe=726abe2f1d) | Mar 19, 2023 |
| HP            | 212B                        | Desktop     | [d4d93ad679](https://bsd-hardware.info/?probe=d4d93ad679) | Mar 19, 2023 |
| GVC           | DR 738                      | Desktop     | [88455ed9e7](https://bsd-hardware.info/?probe=88455ed9e7) | Mar 18, 2023 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [c83b0dda87](https://bsd-hardware.info/?probe=c83b0dda87) | Mar 18, 2023 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [9ac4738956](https://bsd-hardware.info/?probe=9ac4738956) | Mar 18, 2023 |
| IP3 Techno... | ACN1S                       | Notebook    | [d0761f4192](https://bsd-hardware.info/?probe=d0761f4192) | Mar 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [6d9c564a33](https://bsd-hardware.info/?probe=6d9c564a33) | Mar 17, 2023 |
| HP            | 3397                        | Desktop     | [2851f91f5f](https://bsd-hardware.info/?probe=2851f91f5f) | Mar 17, 2023 |
| ASUSTek       | 1001P                       | Notebook    | [76eae56ba3](https://bsd-hardware.info/?probe=76eae56ba3) | Mar 15, 2023 |
| OEGStone      | W54_55SU1,SUW               | Notebook    | [64316408f0](https://bsd-hardware.info/?probe=64316408f0) | Mar 15, 2023 |
| Acer          | Aspire V3-112P              | Notebook    | [104c10f9b0](https://bsd-hardware.info/?probe=104c10f9b0) | Mar 14, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [b878473783](https://bsd-hardware.info/?probe=b878473783) | Mar 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [49764ec5fa](https://bsd-hardware.info/?probe=49764ec5fa) | Mar 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [a8a9ed7f9e](https://bsd-hardware.info/?probe=a8a9ed7f9e) | Mar 13, 2023 |
| Lenovo        | ThinkPad E495 20NEA00QUS    | Notebook    | [8b112aa100](https://bsd-hardware.info/?probe=8b112aa100) | Mar 13, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [b2ef9ff3dc](https://bsd-hardware.info/?probe=b2ef9ff3dc) | Mar 12, 2023 |
| HP            | 0AA8h                       | Desktop     | [15ddd97321](https://bsd-hardware.info/?probe=15ddd97321) | Mar 12, 2023 |
| Supermicro    | X7DWE                       | Desktop     | [e40b569ff7](https://bsd-hardware.info/?probe=e40b569ff7) | Mar 12, 2023 |
| MSI           | H81M-P33                    | Desktop     | [12dbc1a2b3](https://bsd-hardware.info/?probe=12dbc1a2b3) | Mar 12, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [bcd9058821](https://bsd-hardware.info/?probe=bcd9058821) | Mar 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [d93ae717cc](https://bsd-hardware.info/?probe=d93ae717cc) | Mar 12, 2023 |
| Google        | Kohaku                      | Notebook    | [88491d298e](https://bsd-hardware.info/?probe=88491d298e) | Mar 12, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | Notebook    | [80dd48bca9](https://bsd-hardware.info/?probe=80dd48bca9) | Mar 12, 2023 |
| Dell          | Precision 7720              | Notebook    | [01f5f21b76](https://bsd-hardware.info/?probe=01f5f21b76) | Mar 12, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [c8abf1f5bf](https://bsd-hardware.info/?probe=c8abf1f5bf) | Mar 11, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [3548f4efa2](https://bsd-hardware.info/?probe=3548f4efa2) | Mar 11, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | Notebook    | [a4366e53ba](https://bsd-hardware.info/?probe=a4366e53ba) | Mar 10, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [654bdb4eb2](https://bsd-hardware.info/?probe=654bdb4eb2) | Mar 10, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [62c09245a4](https://bsd-hardware.info/?probe=62c09245a4) | Mar 10, 2023 |
| Gigabyte      | B360M D2V                   | Desktop     | [6ac60b8104](https://bsd-hardware.info/?probe=6ac60b8104) | Mar 10, 2023 |
| Intel         | Jasper Lake Client Platf... | Notebook    | [88de48013c](https://bsd-hardware.info/?probe=88de48013c) | Mar 10, 2023 |
| Lenovo        | ThinkPad T495 20NKS0HN1N    | Notebook    | [af190c38e9](https://bsd-hardware.info/?probe=af190c38e9) | Mar 10, 2023 |
| Fujitsu       | CELSIUS H730                | Notebook    | [223879138d](https://bsd-hardware.info/?probe=223879138d) | Mar 10, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [e5a43dd311](https://bsd-hardware.info/?probe=e5a43dd311) | Mar 10, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | Notebook    | [44a8bf8fbc](https://bsd-hardware.info/?probe=44a8bf8fbc) | Mar 10, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [970f35af17](https://bsd-hardware.info/?probe=970f35af17) | Mar 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [278a2a11cd](https://bsd-hardware.info/?probe=278a2a11cd) | Mar 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [ef85735453](https://bsd-hardware.info/?probe=ef85735453) | Mar 09, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [58090b9dbf](https://bsd-hardware.info/?probe=58090b9dbf) | Mar 09, 2023 |
| Dell          | Latitude D620               | Notebook    | [8b3ad4e8b9](https://bsd-hardware.info/?probe=8b3ad4e8b9) | Mar 09, 2023 |
| Dell          | Latitude D620               | Notebook    | [d42a8ee079](https://bsd-hardware.info/?probe=d42a8ee079) | Mar 09, 2023 |
| ASRock        | H610M-HVS/M.2 R2.0          | Desktop     | [98fe8cc428](https://bsd-hardware.info/?probe=98fe8cc428) | Mar 09, 2023 |
| Samsung       | 750XEE                      | Notebook    | [47d2204f58](https://bsd-hardware.info/?probe=47d2204f58) | Mar 08, 2023 |
| Lenovo        | ThinkPad X230 2324A14       | Notebook    | [124b3bdb95](https://bsd-hardware.info/?probe=124b3bdb95) | Mar 08, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [9466e6d4f4](https://bsd-hardware.info/?probe=9466e6d4f4) | Mar 07, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [1a2543f92f](https://bsd-hardware.info/?probe=1a2543f92f) | Mar 06, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [2ba0e18863](https://bsd-hardware.info/?probe=2ba0e18863) | Mar 05, 2023 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [a3f77b82cc](https://bsd-hardware.info/?probe=a3f77b82cc) | Mar 05, 2023 |
| MSI           | H81M-P33                    | Desktop     | [dfa124b6f9](https://bsd-hardware.info/?probe=dfa124b6f9) | Mar 05, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [64513c0ff5](https://bsd-hardware.info/?probe=64513c0ff5) | Mar 05, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ebba69095d](https://bsd-hardware.info/?probe=ebba69095d) | Mar 05, 2023 |
| ASRock        | E350M1                      | Desktop     | [461f8cca23](https://bsd-hardware.info/?probe=461f8cca23) | Mar 04, 2023 |
| Intel         | D510MO AAE76523-403         | Desktop     | [0da634580f](https://bsd-hardware.info/?probe=0da634580f) | Mar 03, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E0T    | Notebook    | [6d7b30d2c4](https://bsd-hardware.info/?probe=6d7b30d2c4) | Mar 03, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [f9db95d778](https://bsd-hardware.info/?probe=f9db95d778) | Mar 03, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [3daad10634](https://bsd-hardware.info/?probe=3daad10634) | Mar 02, 2023 |
| ASRock        | H470M-STX                   | Desktop     | [98096adfaa](https://bsd-hardware.info/?probe=98096adfaa) | Mar 01, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [d675a5bab2](https://bsd-hardware.info/?probe=d675a5bab2) | Feb 28, 2023 |
| Lenovo        | Kabini CRB 31900058 STD     | Desktop     | [735f2f3ece](https://bsd-hardware.info/?probe=735f2f3ece) | Feb 28, 2023 |
| Lenovo        | ThinkPad T480s 20L7002CU... | Notebook    | [0e051e7291](https://bsd-hardware.info/?probe=0e051e7291) | Feb 27, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [ffbb7e1a96](https://bsd-hardware.info/?probe=ffbb7e1a96) | Feb 27, 2023 |
| Lenovo        | Kabini CRB 31900058 STD     | Desktop     | [b0fcea0c90](https://bsd-hardware.info/?probe=b0fcea0c90) | Feb 27, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [e85ed3f609](https://bsd-hardware.info/?probe=e85ed3f609) | Feb 27, 2023 |
| ASUSTek       | X541SA                      | Notebook    | [9d406d735e](https://bsd-hardware.info/?probe=9d406d735e) | Feb 26, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [1a4897cb53](https://bsd-hardware.info/?probe=1a4897cb53) | Feb 26, 2023 |
| MSI           | H81M-P33                    | Desktop     | [806efadc12](https://bsd-hardware.info/?probe=806efadc12) | Feb 26, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [efb350b5f2](https://bsd-hardware.info/?probe=efb350b5f2) | Feb 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [62567aa5d4](https://bsd-hardware.info/?probe=62567aa5d4) | Feb 26, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | Notebook    | [2ab690000c](https://bsd-hardware.info/?probe=2ab690000c) | Feb 25, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | Notebook    | [ae0dc68ba6](https://bsd-hardware.info/?probe=ae0dc68ba6) | Feb 25, 2023 |
| Lenovo        | ThinkPad T530 24297XG       | Notebook    | [97d9b10c8a](https://bsd-hardware.info/?probe=97d9b10c8a) | Feb 24, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [1e548fa114](https://bsd-hardware.info/?probe=1e548fa114) | Feb 24, 2023 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [b2681fdfb4](https://bsd-hardware.info/?probe=b2681fdfb4) | Feb 23, 2023 |
| Lenovo        | ThinkPad X280 20KFCTO1WW    | Notebook    | [3dae7e3ebb](https://bsd-hardware.info/?probe=3dae7e3ebb) | Feb 23, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | Notebook    | [6669622646](https://bsd-hardware.info/?probe=6669622646) | Feb 23, 2023 |
| Gigabyte      | Z87X-OC-CF                  | Desktop     | [dca82c50d0](https://bsd-hardware.info/?probe=dca82c50d0) | Feb 23, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [e55635df08](https://bsd-hardware.info/?probe=e55635df08) | Feb 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [9e92cf3575](https://bsd-hardware.info/?probe=9e92cf3575) | Feb 22, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [b2ed608da5](https://bsd-hardware.info/?probe=b2ed608da5) | Feb 21, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [8eb068a097](https://bsd-hardware.info/?probe=8eb068a097) | Feb 20, 2023 |
| MSI           | H81M-P33                    | Desktop     | [28f48b7936](https://bsd-hardware.info/?probe=28f48b7936) | Feb 19, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [b3525afaa7](https://bsd-hardware.info/?probe=b3525afaa7) | Feb 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [19c7044a7d](https://bsd-hardware.info/?probe=19c7044a7d) | Feb 19, 2023 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [c30dd3fbca](https://bsd-hardware.info/?probe=c30dd3fbca) | Feb 19, 2023 |
| Intel         | NUC5PPYB H76558-102         | Mini pc     | [a27331804b](https://bsd-hardware.info/?probe=a27331804b) | Feb 19, 2023 |
| Intel         | DN2820FYK H24582-203        | Desktop     | [dd0d96422f](https://bsd-hardware.info/?probe=dd0d96422f) | Feb 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [63b73012e6](https://bsd-hardware.info/?probe=63b73012e6) | Feb 18, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [1ba2a827d9](https://bsd-hardware.info/?probe=1ba2a827d9) | Feb 18, 2023 |
| Lenovo        | ThinkPad R60e 0658W2M       | Notebook    | [dba66ebfb5](https://bsd-hardware.info/?probe=dba66ebfb5) | Feb 17, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | Desktop     | [b241a8afd7](https://bsd-hardware.info/?probe=b241a8afd7) | Feb 16, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [dd083df1a2](https://bsd-hardware.info/?probe=dd083df1a2) | Feb 16, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [0f4dd9a9bc](https://bsd-hardware.info/?probe=0f4dd9a9bc) | Feb 15, 2023 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [6f4b514959](https://bsd-hardware.info/?probe=6f4b514959) | Feb 14, 2023 |
| Lenovo        | ThinkPad T430 2347FV6       | Notebook    | [cf016ce514](https://bsd-hardware.info/?probe=cf016ce514) | Feb 14, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [c176577762](https://bsd-hardware.info/?probe=c176577762) | Feb 14, 2023 |
| Fujitsu       | D3413-A1 S26361-D3413-A1    | Desktop     | [d69aba5432](https://bsd-hardware.info/?probe=d69aba5432) | Feb 14, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [b3f41e1cb4](https://bsd-hardware.info/?probe=b3f41e1cb4) | Feb 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [b962baf73d](https://bsd-hardware.info/?probe=b962baf73d) | Feb 13, 2023 |
| Acer          | Aspire one V1.05            | Notebook    | [eec371a28f](https://bsd-hardware.info/?probe=eec371a28f) | Feb 13, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [df5f01d72e](https://bsd-hardware.info/?probe=df5f01d72e) | Feb 13, 2023 |
| Panasonic     | CF-30KAPAXAM                | Notebook    | [f686e3756c](https://bsd-hardware.info/?probe=f686e3756c) | Feb 13, 2023 |
| ASUSTek       | P8Z68 DELUXE                | Desktop     | [f65675c771](https://bsd-hardware.info/?probe=f65675c771) | Feb 13, 2023 |
| ASUSTek       | H170I-PRO                   | Desktop     | [63000ada74](https://bsd-hardware.info/?probe=63000ada74) | Feb 12, 2023 |
| HP            | 212B                        | Desktop     | [0e13beb9f6](https://bsd-hardware.info/?probe=0e13beb9f6) | Feb 12, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO S      | Desktop     | [5507e05838](https://bsd-hardware.info/?probe=5507e05838) | Feb 12, 2023 |
| Alienware     | m15                         | Notebook    | [3ab3e4b671](https://bsd-hardware.info/?probe=3ab3e4b671) | Feb 12, 2023 |
| MSI           | H81M-P33                    | Desktop     | [84aff26f99](https://bsd-hardware.info/?probe=84aff26f99) | Feb 12, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [4e899d9a1c](https://bsd-hardware.info/?probe=4e899d9a1c) | Feb 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [d16e93b7f3](https://bsd-hardware.info/?probe=d16e93b7f3) | Feb 12, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [acff807555](https://bsd-hardware.info/?probe=acff807555) | Feb 12, 2023 |
| ASUSTek       | PRIME H410M-K               | Desktop     | [d2edba8775](https://bsd-hardware.info/?probe=d2edba8775) | Feb 11, 2023 |
| Gigabyte      | Z490 VISION G               | Desktop     | [6f8ad1a8b9](https://bsd-hardware.info/?probe=6f8ad1a8b9) | Feb 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [8d49d50738](https://bsd-hardware.info/?probe=8d49d50738) | Feb 11, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [81827ccbca](https://bsd-hardware.info/?probe=81827ccbca) | Feb 10, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [4284c60268](https://bsd-hardware.info/?probe=4284c60268) | Feb 10, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [0c9cf4e002](https://bsd-hardware.info/?probe=0c9cf4e002) | Feb 09, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [ca1e51a042](https://bsd-hardware.info/?probe=ca1e51a042) | Feb 09, 2023 |
| ASUSTek       | P7P55D DELUXE               | Desktop     | [dd9685a909](https://bsd-hardware.info/?probe=dd9685a909) | Feb 09, 2023 |
| HP            | Pavilion dv6                | Notebook    | [d6c8ad1034](https://bsd-hardware.info/?probe=d6c8ad1034) | Feb 08, 2023 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [33af90dd93](https://bsd-hardware.info/?probe=33af90dd93) | Feb 08, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [f3b0d5ac82](https://bsd-hardware.info/?probe=f3b0d5ac82) | Feb 08, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [4fc5363829](https://bsd-hardware.info/?probe=4fc5363829) | Feb 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [ef722fc37b](https://bsd-hardware.info/?probe=ef722fc37b) | Feb 06, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [ec37957aed](https://bsd-hardware.info/?probe=ec37957aed) | Feb 05, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [a98d28355d](https://bsd-hardware.info/?probe=a98d28355d) | Feb 05, 2023 |
| MSI           | H81M-P33                    | Desktop     | [6f8f329a5b](https://bsd-hardware.info/?probe=6f8f329a5b) | Feb 05, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [bd418783d4](https://bsd-hardware.info/?probe=bd418783d4) | Feb 05, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ec1ab0bf97](https://bsd-hardware.info/?probe=ec1ab0bf97) | Feb 05, 2023 |
| Samsung       | 700T1C                      | Notebook    | [91d5c568d1](https://bsd-hardware.info/?probe=91d5c568d1) | Feb 05, 2023 |
| Toshiba       | PORTEGE Z930                | Notebook    | [5462140da0](https://bsd-hardware.info/?probe=5462140da0) | Feb 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [0232c45faa](https://bsd-hardware.info/?probe=0232c45faa) | Feb 04, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [b7a491a010](https://bsd-hardware.info/?probe=b7a491a010) | Feb 03, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d36789c493](https://bsd-hardware.info/?probe=d36789c493) | Feb 02, 2023 |
| Lenovo        | ThinkPad T460 20FMS04200    | Notebook    | [3178015cd3](https://bsd-hardware.info/?probe=3178015cd3) | Feb 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [a54516414a](https://bsd-hardware.info/?probe=a54516414a) | Feb 01, 2023 |
| Lenovo        | ThinkPad T460p 20FW0018A... | Notebook    | [932e722b2d](https://bsd-hardware.info/?probe=932e722b2d) | Feb 01, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [6d46662662](https://bsd-hardware.info/?probe=6d46662662) | Jan 31, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [82ab576c6c](https://bsd-hardware.info/?probe=82ab576c6c) | Jan 31, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [341bae363a](https://bsd-hardware.info/?probe=341bae363a) | Jan 31, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [0b48f96d1e](https://bsd-hardware.info/?probe=0b48f96d1e) | Jan 31, 2023 |
| F-Plus Mob... | FLAPTOP r                   | Notebook    | [c2f84d2103](https://bsd-hardware.info/?probe=c2f84d2103) | Jan 31, 2023 |
| F-Plus Mob... | FLAPTOP r                   | Notebook    | [165d435f30](https://bsd-hardware.info/?probe=165d435f30) | Jan 31, 2023 |
| ASRock        | 970 Extreme3                | Desktop     | [5e2fd4b48f](https://bsd-hardware.info/?probe=5e2fd4b48f) | Jan 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [39ae8fb9c8](https://bsd-hardware.info/?probe=39ae8fb9c8) | Jan 30, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [75b9ef6ee6](https://bsd-hardware.info/?probe=75b9ef6ee6) | Jan 30, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [21398109dc](https://bsd-hardware.info/?probe=21398109dc) | Jan 29, 2023 |
| MSI           | H81M-P33                    | Desktop     | [e6626da98c](https://bsd-hardware.info/?probe=e6626da98c) | Jan 29, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [3d5ea9f313](https://bsd-hardware.info/?probe=3d5ea9f313) | Jan 29, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [9b7532b795](https://bsd-hardware.info/?probe=9b7532b795) | Jan 29, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [2098b8808d](https://bsd-hardware.info/?probe=2098b8808d) | Jan 29, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [1c4edf62e6](https://bsd-hardware.info/?probe=1c4edf62e6) | Jan 28, 2023 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [8fd7f80256](https://bsd-hardware.info/?probe=8fd7f80256) | Jan 28, 2023 |
| Acer          | Aspire one V1.05            | Notebook    | [1cbfce4d7e](https://bsd-hardware.info/?probe=1cbfce4d7e) | Jan 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [d5f06d91db](https://bsd-hardware.info/?probe=d5f06d91db) | Jan 28, 2023 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [1603f38c4c](https://bsd-hardware.info/?probe=1603f38c4c) | Jan 28, 2023 |
| ASUSTek       | WS-C621E-SAGE Series        | Server      | [d32c9457b9](https://bsd-hardware.info/?probe=d32c9457b9) | Jan 28, 2023 |
| F-Plus Mob... | FLAPTOP r                   | Notebook    | [448f9265f2](https://bsd-hardware.info/?probe=448f9265f2) | Jan 27, 2023 |
| F-Plus Mob... | FLAPTOP r                   | Notebook    | [512bf8f61d](https://bsd-hardware.info/?probe=512bf8f61d) | Jan 27, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [92c676e033](https://bsd-hardware.info/?probe=92c676e033) | Jan 26, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [87e25e2abd](https://bsd-hardware.info/?probe=87e25e2abd) | Jan 26, 2023 |
| Shuttle       | DS20U                       | Desktop     | [71033e4a64](https://bsd-hardware.info/?probe=71033e4a64) | Jan 26, 2023 |
| IBM           | 9210MML                     | Desktop     | [8b7e2413ee](https://bsd-hardware.info/?probe=8b7e2413ee) | Jan 25, 2023 |
| ADI Engine... | RCC-VE                      | Desktop     | [e2941c00fc](https://bsd-hardware.info/?probe=e2941c00fc) | Jan 25, 2023 |
| Supermicro    | X11SSH-F                    | Server      | [106cf811d8](https://bsd-hardware.info/?probe=106cf811d8) | Jan 25, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [4eb4e63a2c](https://bsd-hardware.info/?probe=4eb4e63a2c) | Jan 25, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [afeb216c1e](https://bsd-hardware.info/?probe=afeb216c1e) | Jan 25, 2023 |
| ASUSTek       | WS-C621E-SAGE Series        | Server      | [ab59ccf04c](https://bsd-hardware.info/?probe=ab59ccf04c) | Jan 24, 2023 |
| Lenovo        | ThinkPad X220 4291WF5       | Notebook    | [24544f4a94](https://bsd-hardware.info/?probe=24544f4a94) | Jan 24, 2023 |
| Lenovo        | ThinkPad T430 2342AG4       | Notebook    | [b5e972d19a](https://bsd-hardware.info/?probe=b5e972d19a) | Jan 24, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [7319560506](https://bsd-hardware.info/?probe=7319560506) | Jan 24, 2023 |
| Medion        | S14409                      | Notebook    | [9a44efb64c](https://bsd-hardware.info/?probe=9a44efb64c) | Jan 23, 2023 |
| Dell          | Latitude E6400              | Notebook    | [dcc804a61f](https://bsd-hardware.info/?probe=dcc804a61f) | Jan 22, 2023 |
| Dell          | Latitude E6400              | Notebook    | [9dd8d0184f](https://bsd-hardware.info/?probe=9dd8d0184f) | Jan 22, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [26d1d923d6](https://bsd-hardware.info/?probe=26d1d923d6) | Jan 22, 2023 |
| MSI           | H81M-P33                    | Desktop     | [0bbc074f1c](https://bsd-hardware.info/?probe=0bbc074f1c) | Jan 22, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [28d8d82d34](https://bsd-hardware.info/?probe=28d8d82d34) | Jan 22, 2023 |
| Unknown       | AMD-GX3                     | Desktop     | [a38ff8331a](https://bsd-hardware.info/?probe=a38ff8331a) | Jan 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [3afbfc6cea](https://bsd-hardware.info/?probe=3afbfc6cea) | Jan 20, 2023 |
| Unknown       | YL-SKUL6                    | Desktop     | [ef4abfe322](https://bsd-hardware.info/?probe=ef4abfe322) | Jan 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [e13627df1a](https://bsd-hardware.info/?probe=e13627df1a) | Jan 20, 2023 |
| Acer          | TravelMate B311-31          | Notebook    | [dc3f072645](https://bsd-hardware.info/?probe=dc3f072645) | Jan 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [35e269ef1c](https://bsd-hardware.info/?probe=35e269ef1c) | Jan 19, 2023 |
| Dell          | Precision 5540              | Notebook    | [683769b797](https://bsd-hardware.info/?probe=683769b797) | Jan 19, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [b528c0bbe3](https://bsd-hardware.info/?probe=b528c0bbe3) | Jan 18, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [c3281eb186](https://bsd-hardware.info/?probe=c3281eb186) | Jan 18, 2023 |
| Fujitsu       | D3031 S26361-D3031-A100-... | Server      | [ed566c9a5c](https://bsd-hardware.info/?probe=ed566c9a5c) | Jan 18, 2023 |
| Fujitsu       | PRIMERGY RX200 S6           | Desktop     | [f7de27b0ca](https://bsd-hardware.info/?probe=f7de27b0ca) | Jan 18, 2023 |
| Fujitsu       | D3031 S26361-D3031-A100-... | Server      | [cfb839082b](https://bsd-hardware.info/?probe=cfb839082b) | Jan 18, 2023 |
| Lenovo        | H30-05 90BJ0085SP           | Desktop     | [d491694079](https://bsd-hardware.info/?probe=d491694079) | Jan 18, 2023 |
| Fujitsu       | PRIMERGY RX200 S6           | Desktop     | [9eee9cc526](https://bsd-hardware.info/?probe=9eee9cc526) | Jan 18, 2023 |
| Intel         | DH67BL AAG10189-206         | Desktop     | [37ae895d75](https://bsd-hardware.info/?probe=37ae895d75) | Jan 17, 2023 |
| Intel         | DQ45CB AAE30148-302         | Desktop     | [349da05405](https://bsd-hardware.info/?probe=349da05405) | Jan 17, 2023 |
| HP            | 1998                        | Desktop     | [6c36e5e82e](https://bsd-hardware.info/?probe=6c36e5e82e) | Jan 17, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [78327c664e](https://bsd-hardware.info/?probe=78327c664e) | Jan 16, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [7ef714a7f1](https://bsd-hardware.info/?probe=7ef714a7f1) | Jan 16, 2023 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | Notebook    | [247370372d](https://bsd-hardware.info/?probe=247370372d) | Jan 15, 2023 |
| AZW           | SEi                         | Mini pc     | [362a33bd50](https://bsd-hardware.info/?probe=362a33bd50) | Jan 15, 2023 |
| MSI           | H81M-P33                    | Desktop     | [800b3bc34b](https://bsd-hardware.info/?probe=800b3bc34b) | Jan 15, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [ffbcac312f](https://bsd-hardware.info/?probe=ffbcac312f) | Jan 15, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [48e7397e29](https://bsd-hardware.info/?probe=48e7397e29) | Jan 15, 2023 |
| Lenovo        | B590 20208                  | Notebook    | [e4c2272546](https://bsd-hardware.info/?probe=e4c2272546) | Jan 15, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [05cc17947c](https://bsd-hardware.info/?probe=05cc17947c) | Jan 15, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [ad094a458b](https://bsd-hardware.info/?probe=ad094a458b) | Jan 14, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [f682e06d06](https://bsd-hardware.info/?probe=f682e06d06) | Jan 13, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [917972b6ae](https://bsd-hardware.info/?probe=917972b6ae) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [bd60eadfc4](https://bsd-hardware.info/?probe=bd60eadfc4) | Jan 12, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [95ebd841b2](https://bsd-hardware.info/?probe=95ebd841b2) | Jan 12, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [3126dc27f1](https://bsd-hardware.info/?probe=3126dc27f1) | Jan 12, 2023 |
| Dell          | Latitude E6420              | Notebook    | [cb7b02c421](https://bsd-hardware.info/?probe=cb7b02c421) | Jan 11, 2023 |
| Lenovo        | ThinkPad X220 4291LF6       | Notebook    | [25cddb26c3](https://bsd-hardware.info/?probe=25cddb26c3) | Jan 11, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [864db5c1f9](https://bsd-hardware.info/?probe=864db5c1f9) | Jan 11, 2023 |
| ASRockRack    | X470D4U2/1N1                | Desktop     | [07f15d0014](https://bsd-hardware.info/?probe=07f15d0014) | Jan 11, 2023 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [2428fe6bd3](https://bsd-hardware.info/?probe=2428fe6bd3) | Jan 10, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [9bda43254c](https://bsd-hardware.info/?probe=9bda43254c) | Jan 10, 2023 |
| HP            | ProLiant DL160 Gen9         | Server      | [3a9ec9299c](https://bsd-hardware.info/?probe=3a9ec9299c) | Jan 09, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [8def3dc9b2](https://bsd-hardware.info/?probe=8def3dc9b2) | Jan 09, 2023 |
| Acer          | Aspire A514-54              | Notebook    | [470fa4f28a](https://bsd-hardware.info/?probe=470fa4f28a) | Jan 09, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [97b65880b0](https://bsd-hardware.info/?probe=97b65880b0) | Jan 09, 2023 |
| MSI           | H81M-P33                    | Desktop     | [585a3dc78c](https://bsd-hardware.info/?probe=585a3dc78c) | Jan 08, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [1e9d8cc278](https://bsd-hardware.info/?probe=1e9d8cc278) | Jan 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [490261883c](https://bsd-hardware.info/?probe=490261883c) | Jan 08, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [e56cfbdedc](https://bsd-hardware.info/?probe=e56cfbdedc) | Jan 08, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [db483e3d46](https://bsd-hardware.info/?probe=db483e3d46) | Jan 08, 2023 |
| Supermicro    | X10DRL-i                    | Server      | [c0fa5bb871](https://bsd-hardware.info/?probe=c0fa5bb871) | Jan 06, 2023 |
| MSI           | MEG Z690 UNIFY-X            | Desktop     | [e70cd80d11](https://bsd-hardware.info/?probe=e70cd80d11) | Jan 05, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [219200b0b6](https://bsd-hardware.info/?probe=219200b0b6) | Jan 05, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [cc9d84d5ed](https://bsd-hardware.info/?probe=cc9d84d5ed) | Jan 05, 2023 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [9dc3183152](https://bsd-hardware.info/?probe=9dc3183152) | Jan 04, 2023 |
| Supermicro    | X10DRiB                     | Desktop     | [d120c268f7](https://bsd-hardware.info/?probe=d120c268f7) | Jan 04, 2023 |
| Supermicro    | X10DRI-TB                   | Server      | [3bd4e1dc9c](https://bsd-hardware.info/?probe=3bd4e1dc9c) | Jan 04, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [17f5e2e3d2](https://bsd-hardware.info/?probe=17f5e2e3d2) | Jan 04, 2023 |
| Lenovo        | ThinkPad T430 23446FP       | Notebook    | [a1517b13f6](https://bsd-hardware.info/?probe=a1517b13f6) | Jan 04, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [409d119307](https://bsd-hardware.info/?probe=409d119307) | Jan 02, 2023 |
| Intel         | DH77KC AAG39641-400         | Desktop     | [d66b90249d](https://bsd-hardware.info/?probe=d66b90249d) | Jan 02, 2023 |
| Alienware     | m15 R4                      | Notebook    | [1438237430](https://bsd-hardware.info/?probe=1438237430) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [1697219032](https://bsd-hardware.info/?probe=1697219032) | Jan 02, 2023 |
| Shuttle       | DS20U                       | Desktop     | [a5aa09e49f](https://bsd-hardware.info/?probe=a5aa09e49f) | Jan 01, 2023 |
| Lenovo        | ThinkPad X280 20KFCTO1WW    | Notebook    | [a9b3805c0b](https://bsd-hardware.info/?probe=a9b3805c0b) | Jan 01, 2023 |
| MSI           | H81M-P33                    | Desktop     | [0a57dcce99](https://bsd-hardware.info/?probe=0a57dcce99) | Jan 01, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [d3306559de](https://bsd-hardware.info/?probe=d3306559de) | Jan 01, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [772779fadf](https://bsd-hardware.info/?probe=772779fadf) | Jan 01, 2023 |
| Lenovo        | IdeaPad L340-17IWL 81M0     | Notebook    | [22c4a06468](https://bsd-hardware.info/?probe=22c4a06468) | Dec 31, 2022 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [ab7e64f657](https://bsd-hardware.info/?probe=ab7e64f657) | Dec 31, 2022 |
| Lenovo        | 30D9 SDK0J40700 WIN 3258... | Desktop     | [ac867149f2](https://bsd-hardware.info/?probe=ac867149f2) | Dec 31, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [956499202e](https://bsd-hardware.info/?probe=956499202e) | Dec 30, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [d22c37fa81](https://bsd-hardware.info/?probe=d22c37fa81) | Dec 29, 2022 |
| MSI           | H270 GAMING M3              | Desktop     | [5d14519e73](https://bsd-hardware.info/?probe=5d14519e73) | Dec 28, 2022 |
| MSI           | H270 GAMING M3              | Desktop     | [5dcdab1ee3](https://bsd-hardware.info/?probe=5dcdab1ee3) | Dec 28, 2022 |
| Timi          | Redmi Book Pro 14 2022      | Notebook    | [ce5e882952](https://bsd-hardware.info/?probe=ce5e882952) | Dec 28, 2022 |
| Google        | Peppy                       | Notebook    | [e063619f03](https://bsd-hardware.info/?probe=e063619f03) | Dec 27, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [07dc4a3178](https://bsd-hardware.info/?probe=07dc4a3178) | Dec 27, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [50c8cb79f7](https://bsd-hardware.info/?probe=50c8cb79f7) | Dec 26, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [bc829dbb1a](https://bsd-hardware.info/?probe=bc829dbb1a) | Dec 25, 2022 |
| MSI           | H81M-P33                    | Desktop     | [f73a37ab81](https://bsd-hardware.info/?probe=f73a37ab81) | Dec 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [2e842ddb27](https://bsd-hardware.info/?probe=2e842ddb27) | Dec 25, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [883dbf15e4](https://bsd-hardware.info/?probe=883dbf15e4) | Dec 25, 2022 |
| Supermicro    | X10SRH-CLN4FA               | Desktop     | [84c360ad02](https://bsd-hardware.info/?probe=84c360ad02) | Dec 24, 2022 |
| Alienware     | m15 R4                      | Notebook    | [deaef8f0ef](https://bsd-hardware.info/?probe=deaef8f0ef) | Dec 24, 2022 |
| Dell          | 0H28RR A04                  | Server      | [8e22402d9e](https://bsd-hardware.info/?probe=8e22402d9e) | Dec 24, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [a2bc442acd](https://bsd-hardware.info/?probe=a2bc442acd) | Dec 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [d702dfcde2](https://bsd-hardware.info/?probe=d702dfcde2) | Dec 23, 2022 |
| Dell          | Vostro 1400                 | Notebook    | [087a3d269f](https://bsd-hardware.info/?probe=087a3d269f) | Dec 23, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [527bf6bbe4](https://bsd-hardware.info/?probe=527bf6bbe4) | Dec 22, 2022 |
| Supermicro    | X9DR3-F                     | Desktop     | [b8c89bdca8](https://bsd-hardware.info/?probe=b8c89bdca8) | Dec 22, 2022 |
| Supermicro    | X9DR3-F                     | Desktop     | [b0d1792185](https://bsd-hardware.info/?probe=b0d1792185) | Dec 21, 2022 |
| ASRock        | 4X4-4000 Series             | Desktop     | [009ef73bd1](https://bsd-hardware.info/?probe=009ef73bd1) | Dec 20, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [8de4ff8626](https://bsd-hardware.info/?probe=8de4ff8626) | Dec 20, 2022 |
| Lenovo        | ThinkPad T530 2392AQU       | Notebook    | [9a3cbe1893](https://bsd-hardware.info/?probe=9a3cbe1893) | Dec 19, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [0eea35e069](https://bsd-hardware.info/?probe=0eea35e069) | Dec 19, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [ced12f0b41](https://bsd-hardware.info/?probe=ced12f0b41) | Dec 19, 2022 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | Notebook    | [683591700f](https://bsd-hardware.info/?probe=683591700f) | Dec 19, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [b730e64d4a](https://bsd-hardware.info/?probe=b730e64d4a) | Dec 19, 2022 |
| Acer          | Veriton M680G               | Desktop     | [cb44a9e848](https://bsd-hardware.info/?probe=cb44a9e848) | Dec 19, 2022 |
| Acer          | Veriton M680G               | Desktop     | [f7184d9158](https://bsd-hardware.info/?probe=f7184d9158) | Dec 19, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [c233fa7d25](https://bsd-hardware.info/?probe=c233fa7d25) | Dec 18, 2022 |
| Dell          | Precision M4800             | Notebook    | [b7a834c4d0](https://bsd-hardware.info/?probe=b7a834c4d0) | Dec 18, 2022 |
| ASRock        | B660M-ITX/ac                | Desktop     | [f6c8eb4e18](https://bsd-hardware.info/?probe=f6c8eb4e18) | Dec 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [c1b0b83306](https://bsd-hardware.info/?probe=c1b0b83306) | Dec 18, 2022 |
| MSI           | H81M-P33                    | Desktop     | [78e4743abd](https://bsd-hardware.info/?probe=78e4743abd) | Dec 18, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [f232e5746e](https://bsd-hardware.info/?probe=f232e5746e) | Dec 18, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [108c9de5cc](https://bsd-hardware.info/?probe=108c9de5cc) | Dec 18, 2022 |
| Dell          | Latitude E6430              | Notebook    | [b8f950de05](https://bsd-hardware.info/?probe=b8f950de05) | Dec 17, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [7cf06451fd](https://bsd-hardware.info/?probe=7cf06451fd) | Dec 17, 2022 |
| BESSTAR Te... | UM350                       | Desktop     | [b7e599f99d](https://bsd-hardware.info/?probe=b7e599f99d) | Dec 17, 2022 |
| Dell          | Latitude E6430              | Notebook    | [8d92a4e37e](https://bsd-hardware.info/?probe=8d92a4e37e) | Dec 17, 2022 |
| Lenovo        | B50-80 80EW                 | Notebook    | [e6778fa5fd](https://bsd-hardware.info/?probe=e6778fa5fd) | Dec 15, 2022 |
| ASUSTek       | K50IN                       | Notebook    | [b8bfdec836](https://bsd-hardware.info/?probe=b8bfdec836) | Dec 15, 2022 |
| Dell          | Latitude 5400               | Notebook    | [639993a130](https://bsd-hardware.info/?probe=639993a130) | Dec 15, 2022 |
| Dell          | Latitude 5400               | Notebook    | [5b9eb16e5e](https://bsd-hardware.info/?probe=5b9eb16e5e) | Dec 15, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [55f876d83f](https://bsd-hardware.info/?probe=55f876d83f) | Dec 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [7c644cc639](https://bsd-hardware.info/?probe=7c644cc639) | Dec 15, 2022 |
| Dell          | Vostro 15-3568              | Notebook    | [6fc0671dc6](https://bsd-hardware.info/?probe=6fc0671dc6) | Dec 14, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [617f431099](https://bsd-hardware.info/?probe=617f431099) | Dec 14, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [babe4bb620](https://bsd-hardware.info/?probe=babe4bb620) | Dec 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [f52a3d3fa6](https://bsd-hardware.info/?probe=f52a3d3fa6) | Dec 13, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [f51b401c31](https://bsd-hardware.info/?probe=f51b401c31) | Dec 13, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0Y40... | Notebook    | [ce2b20b3a9](https://bsd-hardware.info/?probe=ce2b20b3a9) | Dec 13, 2022 |
| Huanan        | X99-F8D V2.4                | Desktop     | [3d06b605c5](https://bsd-hardware.info/?probe=3d06b605c5) | Dec 13, 2022 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [353c3d5cee](https://bsd-hardware.info/?probe=353c3d5cee) | Dec 12, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0Y40... | Notebook    | [7463e05c88](https://bsd-hardware.info/?probe=7463e05c88) | Dec 12, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [64c92d49d9](https://bsd-hardware.info/?probe=64c92d49d9) | Dec 12, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [73cb5d86bc](https://bsd-hardware.info/?probe=73cb5d86bc) | Dec 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [809da57d90](https://bsd-hardware.info/?probe=809da57d90) | Dec 11, 2022 |
| Biostar       | A68N-5600E                  | Desktop     | [5274876096](https://bsd-hardware.info/?probe=5274876096) | Dec 11, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [0be43b76d1](https://bsd-hardware.info/?probe=0be43b76d1) | Dec 11, 2022 |
| MSI           | H81M-P33                    | Desktop     | [1f110891d0](https://bsd-hardware.info/?probe=1f110891d0) | Dec 11, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [028383847e](https://bsd-hardware.info/?probe=028383847e) | Dec 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [99502ebe9a](https://bsd-hardware.info/?probe=99502ebe9a) | Dec 11, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [6d10b2a0b4](https://bsd-hardware.info/?probe=6d10b2a0b4) | Dec 11, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [1d8397a653](https://bsd-hardware.info/?probe=1d8397a653) | Dec 10, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [2048ff5f71](https://bsd-hardware.info/?probe=2048ff5f71) | Dec 09, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [c30f53fc6d](https://bsd-hardware.info/?probe=c30f53fc6d) | Dec 09, 2022 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [10b6c81bce](https://bsd-hardware.info/?probe=10b6c81bce) | Dec 09, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [c953c78309](https://bsd-hardware.info/?probe=c953c78309) | Dec 07, 2022 |
| HP            | 82A2                        | Desktop     | [c612b7e283](https://bsd-hardware.info/?probe=c612b7e283) | Dec 06, 2022 |
| Huanan        | X99-F8D V2.4                | Desktop     | [f6685811a3](https://bsd-hardware.info/?probe=f6685811a3) | Dec 05, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [2c560bad00](https://bsd-hardware.info/?probe=2c560bad00) | Dec 05, 2022 |
| Google        | Lick                        | Notebook    | [8099b2df21](https://bsd-hardware.info/?probe=8099b2df21) | Dec 04, 2022 |
| MSI           | H81M-P33                    | Desktop     | [d72a45fb8f](https://bsd-hardware.info/?probe=d72a45fb8f) | Dec 04, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [595d174631](https://bsd-hardware.info/?probe=595d174631) | Dec 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [8ee41750dc](https://bsd-hardware.info/?probe=8ee41750dc) | Dec 04, 2022 |
| Google        | Lick                        | Notebook    | [9eb2abcdcc](https://bsd-hardware.info/?probe=9eb2abcdcc) | Dec 03, 2022 |
| Google        | Lars                        | Notebook    | [4130b19cfa](https://bsd-hardware.info/?probe=4130b19cfa) | Dec 03, 2022 |
| Lenovo        | ThinkPad X250 20CLS5BU00    | Notebook    | [10619ac217](https://bsd-hardware.info/?probe=10619ac217) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [aeb690b9f3](https://bsd-hardware.info/?probe=aeb690b9f3) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [d4e60c5984](https://bsd-hardware.info/?probe=d4e60c5984) | Dec 03, 2022 |
| Intel         | NUC11ATBC4 M53051-400       | Mini pc     | [6fe2ba74b7](https://bsd-hardware.info/?probe=6fe2ba74b7) | Dec 01, 2022 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [087264570d](https://bsd-hardware.info/?probe=087264570d) | Nov 30, 2022 |
| Panasonic     | CF-31-5                     | Notebook    | [7047afaaf4](https://bsd-hardware.info/?probe=7047afaaf4) | Nov 30, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [3dd9e3557c](https://bsd-hardware.info/?probe=3dd9e3557c) | Nov 30, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [1d61d0cf62](https://bsd-hardware.info/?probe=1d61d0cf62) | Nov 29, 2022 |
| ASRockRack    | X470D4U                     | Desktop     | [38d7f55ef7](https://bsd-hardware.info/?probe=38d7f55ef7) | Nov 29, 2022 |
| Lenovo        | ThinkPad T430 2347G7G       | Notebook    | [640540cd67](https://bsd-hardware.info/?probe=640540cd67) | Nov 29, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [929e4bda1e](https://bsd-hardware.info/?probe=929e4bda1e) | Nov 29, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [7c9ee800c5](https://bsd-hardware.info/?probe=7c9ee800c5) | Nov 29, 2022 |
| Acer          | TravelMate B115-M           | Notebook    | [13e318fec2](https://bsd-hardware.info/?probe=13e318fec2) | Nov 29, 2022 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [378270eba0](https://bsd-hardware.info/?probe=378270eba0) | Nov 28, 2022 |
| MSI           | H81M-P33                    | Desktop     | [597d48d1c9](https://bsd-hardware.info/?probe=597d48d1c9) | Nov 27, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [10d76fd431](https://bsd-hardware.info/?probe=10d76fd431) | Nov 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [383341b2f1](https://bsd-hardware.info/?probe=383341b2f1) | Nov 27, 2022 |
| ASRock        | Q1900B-ITX                  | Desktop     | [c93690c7ca](https://bsd-hardware.info/?probe=c93690c7ca) | Nov 27, 2022 |
| Shuttle       | FZ270                       | Desktop     | [04a7f49322](https://bsd-hardware.info/?probe=04a7f49322) | Nov 27, 2022 |
| Shuttle       | FZ270                       | Desktop     | [10016f39b9](https://bsd-hardware.info/?probe=10016f39b9) | Nov 27, 2022 |
| ASRock        | Q1900B-ITX                  | Desktop     | [675c9fdf94](https://bsd-hardware.info/?probe=675c9fdf94) | Nov 27, 2022 |
| ASRock        | Q1900B-ITX                  | Desktop     | [a337eb9e5f](https://bsd-hardware.info/?probe=a337eb9e5f) | Nov 27, 2022 |
| Shuttle       | FH270                       | Desktop     | [192351ac6f](https://bsd-hardware.info/?probe=192351ac6f) | Nov 27, 2022 |
| Shuttle       | FH270                       | Desktop     | [3b68d89092](https://bsd-hardware.info/?probe=3b68d89092) | Nov 27, 2022 |
| Dell          | 0VRCY5 A14                  | Server      | [5048d00fd8](https://bsd-hardware.info/?probe=5048d00fd8) | Nov 27, 2022 |
| Dell          | 0VRCY5 A14                  | Server      | [60bdb57227](https://bsd-hardware.info/?probe=60bdb57227) | Nov 27, 2022 |
| Dell          | 0VRCY5 A14                  | Server      | [ebdca950cc](https://bsd-hardware.info/?probe=ebdca950cc) | Nov 27, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [5f0b8df8d0](https://bsd-hardware.info/?probe=5f0b8df8d0) | Nov 27, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [3ad7cec298](https://bsd-hardware.info/?probe=3ad7cec298) | Nov 26, 2022 |
| Lenovo        | ThinkPad T430 23446FP       | Notebook    | [6c2ef140be](https://bsd-hardware.info/?probe=6c2ef140be) | Nov 25, 2022 |
| Supermicro    | M11SDV-8C+-LN4F             | Server      | [bcf17b19ec](https://bsd-hardware.info/?probe=bcf17b19ec) | Nov 25, 2022 |
| Dell          | 0PTTT9 A01                  | Desktop     | [74575d6dfe](https://bsd-hardware.info/?probe=74575d6dfe) | Nov 25, 2022 |
| Sony          | SVP1321V9RB                 | Notebook    | [932facd689](https://bsd-hardware.info/?probe=932facd689) | Nov 25, 2022 |
| ASRock        | B450M-HDV                   | Desktop     | [d0009172b1](https://bsd-hardware.info/?probe=d0009172b1) | Nov 24, 2022 |
| ASRock        | B450M-HDV                   | Desktop     | [25cc0129d9](https://bsd-hardware.info/?probe=25cc0129d9) | Nov 24, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [45d96a0b5a](https://bsd-hardware.info/?probe=45d96a0b5a) | Nov 24, 2022 |
| Apple         | Mac-F2208EC8                | Mini pc     | [0ed70ba3c3](https://bsd-hardware.info/?probe=0ed70ba3c3) | Nov 23, 2022 |
| Dell          | XPS 13 9343                 | Notebook    | [8ec61db3f0](https://bsd-hardware.info/?probe=8ec61db3f0) | Nov 22, 2022 |
| Gigabyte      | Z590I AORUS ULTRA           | Desktop     | [e55eb53894](https://bsd-hardware.info/?probe=e55eb53894) | Nov 21, 2022 |
| ASUSTek       | ZenBook UX434FL_UX434FL     | Notebook    | [56bc3b04fd](https://bsd-hardware.info/?probe=56bc3b04fd) | Nov 21, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [f7129f1c87](https://bsd-hardware.info/?probe=f7129f1c87) | Nov 21, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [17aa370584](https://bsd-hardware.info/?probe=17aa370584) | Nov 21, 2022 |
| HP            | ProBook 4540s               | Notebook    | [6dce896f40](https://bsd-hardware.info/?probe=6dce896f40) | Nov 20, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [8257d11669](https://bsd-hardware.info/?probe=8257d11669) | Nov 20, 2022 |
| MSI           | H81M-P33                    | Desktop     | [d3303d1962](https://bsd-hardware.info/?probe=d3303d1962) | Nov 20, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [b1512a254c](https://bsd-hardware.info/?probe=b1512a254c) | Nov 20, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [521e5ffa8e](https://bsd-hardware.info/?probe=521e5ffa8e) | Nov 20, 2022 |
| TOPFEEL       | H110D4-P1                   | Desktop     | [90b1dfc430](https://bsd-hardware.info/?probe=90b1dfc430) | Nov 19, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [eaf4ec693e](https://bsd-hardware.info/?probe=eaf4ec693e) | Nov 19, 2022 |
| Huanan        | X99-F8D V2.4                | Desktop     | [9faf79b3f3](https://bsd-hardware.info/?probe=9faf79b3f3) | Nov 18, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [7691355396](https://bsd-hardware.info/?probe=7691355396) | Nov 18, 2022 |
| Foxconn       | 2AB1                        | Desktop     | [f732942dd9](https://bsd-hardware.info/?probe=f732942dd9) | Nov 18, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [436a2d30f6](https://bsd-hardware.info/?probe=436a2d30f6) | Nov 16, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [15657b37e2](https://bsd-hardware.info/?probe=15657b37e2) | Nov 15, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [f4a8c42773](https://bsd-hardware.info/?probe=f4a8c42773) | Nov 15, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [2aeadb4dfc](https://bsd-hardware.info/?probe=2aeadb4dfc) | Nov 14, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [4c83122cc0](https://bsd-hardware.info/?probe=4c83122cc0) | Nov 14, 2022 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [443891740b](https://bsd-hardware.info/?probe=443891740b) | Nov 13, 2022 |
| Medion        | E15415                      | Notebook    | [e467080570](https://bsd-hardware.info/?probe=e467080570) | Nov 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [6f1e732a53](https://bsd-hardware.info/?probe=6f1e732a53) | Nov 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [15e38a5ca8](https://bsd-hardware.info/?probe=15e38a5ca8) | Nov 13, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [2b1175a4df](https://bsd-hardware.info/?probe=2b1175a4df) | Nov 13, 2022 |
| MSI           | H81M-P33                    | Desktop     | [98b0980231](https://bsd-hardware.info/?probe=98b0980231) | Nov 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [072f2a6c27](https://bsd-hardware.info/?probe=072f2a6c27) | Nov 13, 2022 |
| Dell          | Latitude E7240              | Notebook    | [ea99621380](https://bsd-hardware.info/?probe=ea99621380) | Nov 12, 2022 |
| Huanan        | X99-F8D V2.4                | Desktop     | [22ec05d988](https://bsd-hardware.info/?probe=22ec05d988) | Nov 12, 2022 |
| Google        | Akemi                       | Notebook    | [2d8e99f0c2](https://bsd-hardware.info/?probe=2d8e99f0c2) | Nov 12, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [569d5b0cca](https://bsd-hardware.info/?probe=569d5b0cca) | Nov 10, 2022 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [87d7d4435b](https://bsd-hardware.info/?probe=87d7d4435b) | Nov 10, 2022 |
| HP            | 21B4 A01                    | Desktop     | [c064c50fea](https://bsd-hardware.info/?probe=c064c50fea) | Nov 09, 2022 |
| HP            | 21B4 A01                    | Desktop     | [e5c599dfab](https://bsd-hardware.info/?probe=e5c599dfab) | Nov 09, 2022 |
| ZOTAC         | ZBOX-QCM7T3000/EN072080S... | Mini pc     | [62ab446b5d](https://bsd-hardware.info/?probe=62ab446b5d) | Nov 09, 2022 |
| HP            | 21B4 A01                    | Desktop     | [0a3ba5478b](https://bsd-hardware.info/?probe=0a3ba5478b) | Nov 09, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [c32a7b407d](https://bsd-hardware.info/?probe=c32a7b407d) | Nov 09, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [32331d772c](https://bsd-hardware.info/?probe=32331d772c) | Nov 08, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [127e0126d1](https://bsd-hardware.info/?probe=127e0126d1) | Nov 08, 2022 |
| Lenovo        | ThinkPad X270 20HMCTO1WW    | Notebook    | [9f15cb8acc](https://bsd-hardware.info/?probe=9f15cb8acc) | Nov 08, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [5807159f51](https://bsd-hardware.info/?probe=5807159f51) | Nov 08, 2022 |
| Google        | Zako                        | Desktop     | [5d4b53e2d4](https://bsd-hardware.info/?probe=5d4b53e2d4) | Nov 08, 2022 |
| HP            | ProBook 4540s               | Notebook    | [9c4be9deab](https://bsd-hardware.info/?probe=9c4be9deab) | Nov 07, 2022 |
| ONDA          | N78G5D3 Ver:5.00            | Desktop     | [009bc44d12](https://bsd-hardware.info/?probe=009bc44d12) | Nov 07, 2022 |
| Acer          | RS880M05                    | Desktop     | [455f9b5026](https://bsd-hardware.info/?probe=455f9b5026) | Nov 07, 2022 |
| MSI           | H81M-P33                    | Desktop     | [750d2f53c7](https://bsd-hardware.info/?probe=750d2f53c7) | Nov 06, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [e427ea787e](https://bsd-hardware.info/?probe=e427ea787e) | Nov 06, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [c6abe84145](https://bsd-hardware.info/?probe=c6abe84145) | Nov 06, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [c4fd2595e6](https://bsd-hardware.info/?probe=c4fd2595e6) | Nov 06, 2022 |
| Lenovo        | ThinkPad T430 23446FP       | Notebook    | [1373bd7f3e](https://bsd-hardware.info/?probe=1373bd7f3e) | Nov 05, 2022 |
| HP            | ProBook 4540s               | Notebook    | [7596b602c6](https://bsd-hardware.info/?probe=7596b602c6) | Nov 05, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d27fd3b1a7](https://bsd-hardware.info/?probe=d27fd3b1a7) | Nov 04, 2022 |
| Lenovo        | YangTianM6880N              | Desktop     | [2e9c3b7368](https://bsd-hardware.info/?probe=2e9c3b7368) | Nov 04, 2022 |
| BESSTAR Te... | HM80                        | Desktop     | [d5c5f30a2d](https://bsd-hardware.info/?probe=d5c5f30a2d) | Nov 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [58c2f4b4f7](https://bsd-hardware.info/?probe=58c2f4b4f7) | Nov 04, 2022 |
| Samsung       | 750TDA                      | Notebook    | [a880b1f616](https://bsd-hardware.info/?probe=a880b1f616) | Nov 02, 2022 |
| HP            | ProLiant DL180 G6           | Server      | [289d2f383b](https://bsd-hardware.info/?probe=289d2f383b) | Nov 02, 2022 |
| Gigabyte      | Z97X-UD5H                   | Desktop     | [d7141b866c](https://bsd-hardware.info/?probe=d7141b866c) | Nov 02, 2022 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [bb0f8a5bfc](https://bsd-hardware.info/?probe=bb0f8a5bfc) | Oct 31, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | Desktop     | [cce93ff157](https://bsd-hardware.info/?probe=cce93ff157) | Oct 30, 2022 |
| MSI           | H81M-P33                    | Desktop     | [b67d6a7bb2](https://bsd-hardware.info/?probe=b67d6a7bb2) | Oct 30, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [8161bfd24d](https://bsd-hardware.info/?probe=8161bfd24d) | Oct 30, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [a0896f17e4](https://bsd-hardware.info/?probe=a0896f17e4) | Oct 30, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0BR0... | Notebook    | [2776d8c350](https://bsd-hardware.info/?probe=2776d8c350) | Oct 30, 2022 |
| Lenovo        | ThinkPad T460 20FMS10N00    | Notebook    | [04ce25bd7f](https://bsd-hardware.info/?probe=04ce25bd7f) | Oct 29, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [6911e08b7e](https://bsd-hardware.info/?probe=6911e08b7e) | Oct 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [caad4323ba](https://bsd-hardware.info/?probe=caad4323ba) | Oct 23, 2022 |
| MSI           | H81M-P33                    | Desktop     | [626f503cad](https://bsd-hardware.info/?probe=626f503cad) | Oct 23, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [2b98739799](https://bsd-hardware.info/?probe=2b98739799) | Oct 23, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [56dac6bc80](https://bsd-hardware.info/?probe=56dac6bc80) | Oct 23, 2022 |
| IBM           | 49Y6512                     | Server      | [1bc9e20b16](https://bsd-hardware.info/?probe=1bc9e20b16) | Oct 23, 2022 |
| Acer          | Revo RN86                   | Desktop     | [692ea69bab](https://bsd-hardware.info/?probe=692ea69bab) | Oct 21, 2022 |
| HP            | 18E4                        | Desktop     | [d66ffbbf6d](https://bsd-hardware.info/?probe=d66ffbbf6d) | Oct 21, 2022 |
| Dell          | Precision M4500             | Notebook    | [66ded228ea](https://bsd-hardware.info/?probe=66ded228ea) | Oct 20, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [348bef7dba](https://bsd-hardware.info/?probe=348bef7dba) | Oct 20, 2022 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | Desktop     | [3e2f5956c1](https://bsd-hardware.info/?probe=3e2f5956c1) | Oct 19, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [bc229efed9](https://bsd-hardware.info/?probe=bc229efed9) | Oct 18, 2022 |
| Unknown       | Unknown                     | Desktop     | [20ff21d751](https://bsd-hardware.info/?probe=20ff21d751) | Oct 18, 2022 |
| Lenovo        | 30D0 NOK                    | Desktop     | [d1fab8bd54](https://bsd-hardware.info/?probe=d1fab8bd54) | Oct 18, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [0a8b1f727f](https://bsd-hardware.info/?probe=0a8b1f727f) | Oct 17, 2022 |
| Acer          | Aspire A514-54              | Notebook    | [e057b613a0](https://bsd-hardware.info/?probe=e057b613a0) | Oct 17, 2022 |
| Lenovo        | XiaoXinPro-13API 2019 81... | Notebook    | [dfa08657fd](https://bsd-hardware.info/?probe=dfa08657fd) | Oct 16, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [22881028bc](https://bsd-hardware.info/?probe=22881028bc) | Oct 16, 2022 |
| TYAN Compu... | Intel 440BX/GX Rev. 4       | Desktop     | [8d99f317e4](https://bsd-hardware.info/?probe=8d99f317e4) | Oct 15, 2022 |
| Dell          | 0G1548 A00                  | Desktop     | [226af33d5b](https://bsd-hardware.info/?probe=226af33d5b) | Oct 15, 2022 |
| ASRock        | G41C-GS R2.0                | Desktop     | [06214241b3](https://bsd-hardware.info/?probe=06214241b3) | Oct 15, 2022 |
| Lenovo        | ThinkPad T430 23446FP       | Notebook    | [6b15856d20](https://bsd-hardware.info/?probe=6b15856d20) | Oct 15, 2022 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [e67cb3a0c5](https://bsd-hardware.info/?probe=e67cb3a0c5) | Oct 14, 2022 |
| IBM           | 49Y6512                     | Server      | [4471bf6465](https://bsd-hardware.info/?probe=4471bf6465) | Oct 14, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [10358c7207](https://bsd-hardware.info/?probe=10358c7207) | Oct 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [b20b6c7997](https://bsd-hardware.info/?probe=b20b6c7997) | Oct 13, 2022 |
| IBM           | 49Y6512                     | Server      | [1ead286cbe](https://bsd-hardware.info/?probe=1ead286cbe) | Oct 13, 2022 |
| Lenovo        | ThinkPad T440s 20AR003SM... | Notebook    | [df62882c3b](https://bsd-hardware.info/?probe=df62882c3b) | Oct 12, 2022 |
| HP            | 1589                        | Desktop     | [0696d30d3f](https://bsd-hardware.info/?probe=0696d30d3f) | Oct 12, 2022 |
| Dell          | 0WC7KF A00                  | All in one  | [5f271a82bf](https://bsd-hardware.info/?probe=5f271a82bf) | Oct 11, 2022 |
| Dell          | 0WC7KF A00                  | All in one  | [0f87a99ca7](https://bsd-hardware.info/?probe=0f87a99ca7) | Oct 11, 2022 |
| Lenovo        | 316E NOK                    | Mini pc     | [2a7c8f55cb](https://bsd-hardware.info/?probe=2a7c8f55cb) | Oct 10, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [c79fa6f001](https://bsd-hardware.info/?probe=c79fa6f001) | Oct 09, 2022 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [442a743538](https://bsd-hardware.info/?probe=442a743538) | Oct 08, 2022 |
| Supermicro    | X8DT6                       | Server      | [2bd1529913](https://bsd-hardware.info/?probe=2bd1529913) | Oct 07, 2022 |
| ASRockRack    | EP2C612D16FM                | Desktop     | [30a582fccb](https://bsd-hardware.info/?probe=30a582fccb) | Oct 07, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | Notebook    | [601029d3fc](https://bsd-hardware.info/?probe=601029d3fc) | Oct 06, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [ce9cfa77aa](https://bsd-hardware.info/?probe=ce9cfa77aa) | Oct 05, 2022 |
| HP            | Compaq 6735s                | Notebook    | [f61208cfea](https://bsd-hardware.info/?probe=f61208cfea) | Oct 05, 2022 |
| HP            | Compaq 6735s                | Notebook    | [718126149c](https://bsd-hardware.info/?probe=718126149c) | Oct 05, 2022 |
| Acer          | TravelMate B115-M           | Notebook    | [86289a60aa](https://bsd-hardware.info/?probe=86289a60aa) | Oct 05, 2022 |
| Acer          | TravelMate B115-M           | Notebook    | [9f4642f6a5](https://bsd-hardware.info/?probe=9f4642f6a5) | Oct 05, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [2620fd3511](https://bsd-hardware.info/?probe=2620fd3511) | Oct 04, 2022 |
| Dell          | Precision 5510              | Notebook    | [f69c9fb0ea](https://bsd-hardware.info/?probe=f69c9fb0ea) | Oct 04, 2022 |
| ASRock        | Z77 Extreme4                | Desktop     | [459c674b3b](https://bsd-hardware.info/?probe=459c674b3b) | Oct 04, 2022 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [d89559e5c2](https://bsd-hardware.info/?probe=d89559e5c2) | Oct 03, 2022 |
| Toshiba       | NB300                       | Notebook    | [c18ae50101](https://bsd-hardware.info/?probe=c18ae50101) | Oct 03, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [e83d522905](https://bsd-hardware.info/?probe=e83d522905) | Oct 03, 2022 |
| Dell          | Precision M4500             | Notebook    | [6b987b43b1](https://bsd-hardware.info/?probe=6b987b43b1) | Oct 03, 2022 |
| IBM           | 9210MML                     | Desktop     | [a6e7d7483f](https://bsd-hardware.info/?probe=a6e7d7483f) | Oct 03, 2022 |
| HPE           | ProLiant ML30 Gen10         | Desktop     | [f1b45790d4](https://bsd-hardware.info/?probe=f1b45790d4) | Oct 02, 2022 |
| Dell          | Precision M4800             | Notebook    | [0fcbdeeeb7](https://bsd-hardware.info/?probe=0fcbdeeeb7) | Oct 02, 2022 |
| HP            | 212B                        | Desktop     | [7bc6506336](https://bsd-hardware.info/?probe=7bc6506336) | Oct 01, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [f9851a3257](https://bsd-hardware.info/?probe=f9851a3257) | Oct 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [bdabafdcb1](https://bsd-hardware.info/?probe=bdabafdcb1) | Oct 01, 2022 |
| Supermicro    | X10SLH-F/X10SLM+-F          | Server      | [6f95477df3](https://bsd-hardware.info/?probe=6f95477df3) | Sep 30, 2022 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [8e658fe40f](https://bsd-hardware.info/?probe=8e658fe40f) | Sep 30, 2022 |
| IBM           | ThinkPad T43 18714AG        | Notebook    | [5fd9a63834](https://bsd-hardware.info/?probe=5fd9a63834) | Sep 30, 2022 |
| AMI           | MNHO-048                    | Desktop     | [2ec6e55a75](https://bsd-hardware.info/?probe=2ec6e55a75) | Sep 28, 2022 |
| Acer          | Swift SF313-52              | Notebook    | [83516dabac](https://bsd-hardware.info/?probe=83516dabac) | Sep 28, 2022 |
| MSI           | A520M-A PRO                 | Desktop     | [7e75a1888b](https://bsd-hardware.info/?probe=7e75a1888b) | Sep 27, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [433857f5f7](https://bsd-hardware.info/?probe=433857f5f7) | Sep 27, 2022 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | Notebook    | [b2024820d1](https://bsd-hardware.info/?probe=b2024820d1) | Sep 26, 2022 |
| Acer          | Swift SF313-52              | Notebook    | [6339e6b468](https://bsd-hardware.info/?probe=6339e6b468) | Sep 25, 2022 |
| Pegatron      | H81-X1                      | Desktop     | [a27c76c490](https://bsd-hardware.info/?probe=a27c76c490) | Sep 25, 2022 |
| ASUSTek       | P9D-X Series                | Server      | [3494695f54](https://bsd-hardware.info/?probe=3494695f54) | Sep 25, 2022 |
| Gigabyte      | GB-BSi5A-6200               | Notebook    | [c947635b8f](https://bsd-hardware.info/?probe=c947635b8f) | Sep 25, 2022 |
| Gigabyte      | GB-BSi5A-6200               | Notebook    | [533c7f35f1](https://bsd-hardware.info/?probe=533c7f35f1) | Sep 25, 2022 |
| Supermicro    | X10SRi-FB                   | Server      | [59ff2014e5](https://bsd-hardware.info/?probe=59ff2014e5) | Sep 25, 2022 |
| Intel         | S1200SP H57532-210          | Server      | [ab6e70abca](https://bsd-hardware.info/?probe=ab6e70abca) | Sep 25, 2022 |
| Supermicro    | X8DT3                       | Server      | [eda1df037b](https://bsd-hardware.info/?probe=eda1df037b) | Sep 25, 2022 |
| Supermicro    | X7DB8                       | Desktop     | [6ebc173873](https://bsd-hardware.info/?probe=6ebc173873) | Sep 25, 2022 |
| Deciso        | Netboard A10 V2.1           | Desktop     | [8bbf714f6d](https://bsd-hardware.info/?probe=8bbf714f6d) | Sep 25, 2022 |
| Deciso        | Netboard A10 V2.1           | Desktop     | [60d4585ece](https://bsd-hardware.info/?probe=60d4585ece) | Sep 25, 2022 |
| IBM           | ThinkPad T40 23737CG        | Notebook    | [dfc9b64da2](https://bsd-hardware.info/?probe=dfc9b64da2) | Sep 25, 2022 |
| System76      | Gazelle                     | Notebook    | [d087321049](https://bsd-hardware.info/?probe=d087321049) | Sep 24, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [dbda136daa](https://bsd-hardware.info/?probe=dbda136daa) | Sep 24, 2022 |
| Dell          | System Vostro 3750          | Notebook    | [166fbacd73](https://bsd-hardware.info/?probe=166fbacd73) | Sep 24, 2022 |
| System76      | Gazelle                     | Notebook    | [6d5d4f5021](https://bsd-hardware.info/?probe=6d5d4f5021) | Sep 24, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/FreeBSD/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart_bsd/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| FreeBSD 13.1         | 234       | 8.18%   |
| FreeBSD 13.0         | 223       | 7.8%    |
| FreeBSD 14.0-CURRENT | 152       | 5.32%   |
| FreeBSD 12.2         | 141       | 4.93%   |
| FreeBSD 13.2         | 135       | 4.72%   |
| FreeBSD 12.2-p2      | 96        | 3.36%   |
| FreeBSD 13.0-p4      | 85        | 2.97%   |
| FreeBSD 13.1-p5      | 83        | 2.9%    |
| FreeBSD 12.1-p10     | 79        | 2.76%   |
| FreeBSD 13.0-p5      | 76        | 2.66%   |
| FreeBSD 13.0-STABLE  | 72        | 2.52%   |
| FreeBSD 13.1-p2      | 71        | 2.48%   |
| FreeBSD 12.1-p8      | 69        | 2.41%   |
| FreeBSD 13.0-CURRENT | 66        | 2.31%   |
| FreeBSD 12.1         | 58        | 2.03%   |
| FreeBSD 12.1-p5      | 55        | 1.92%   |
| FreeBSD 13.1-p7      | 53        | 1.85%   |
| FreeBSD 12.2-p3      | 52        | 1.82%   |
| FreeBSD 12.1-STABLE  | 49        | 1.71%   |
| FreeBSD 12.1-p7      | 48        | 1.68%   |
| FreeBSD 13.0-p3      | 47        | 1.64%   |
| FreeBSD 12.2-p4      | 47        | 1.64%   |
| FreeBSD 13.0-p7      | 45        | 1.57%   |
| FreeBSD 13.0-p11     | 37        | 1.29%   |
| FreeBSD 12.2-p6      | 35        | 1.22%   |
| FreeBSD 13.1-STABLE  | 34        | 1.19%   |
| FreeBSD 13.2-p2      | 33        | 1.15%   |
| FreeBSD 13.0-p2      | 33        | 1.15%   |
| FreeBSD 12.2-STABLE  | 32        | 1.12%   |
| FreeBSD 13.1-p1      | 28        | 0.98%   |
| FreeBSD 13.0-p6      | 25        | 0.87%   |
| FreeBSD 12.3         | 23        | 0.8%    |
| FreeBSD 13.0-p10     | 22        | 0.77%   |
| FreeBSD 13.2-p1      | 21        | 0.73%   |
| FreeBSD 13.1-p4      | 21        | 0.73%   |
| FreeBSD 12.1-p6      | 21        | 0.73%   |
| FreeBSD 12.2-p10     | 17        | 0.59%   |
| FreeBSD 12.1-p4      | 17        | 0.59%   |
| FreeBSD 13.1-p3      | 16        | 0.56%   |
| FreeBSD 12.3-p5      | 16        | 0.56%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| FreeBSD | 2366      | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| amd64   | 2187      | 92.4%   |
| arm64   | 85        | 3.59%   |
| i386    | 76        | 3.21%   |
| arm     | 13        | 0.55%   |
| powerpc | 4         | 0.17%   |
| sparc64 | 1         | 0.04%   |
| riscv   | 1         | 0.04%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 809       | 32.9%   |
| XFCE          | 402       | 16.35%  |
| KDE5          | 394       | 16.02%  |
| TWM           | 174       | 7.08%   |
| GNOME         | 172       | 6.99%   |
| MATE          | 133       | 5.41%   |
| i3            | 108       | 4.39%   |
| Openbox       | 61        | 2.48%   |
| LXQt          | 28        | 1.14%   |
| Cinnamon      | 27        | 1.1%    |
| AwesomeWM     | 26        | 1.06%   |
| Fluxbox       | 20        | 0.81%   |
| Enlightenment | 17        | 0.69%   |
| LXDE          | 16        | 0.65%   |
| Lumina        | 11        | 0.45%   |
| DWM           | 9         | 0.37%   |
| GNUstep       | 5         | 0.2%    |
| xfwm          | 4         | 0.16%   |
| X-Cinnamon    | 4         | 0.16%   |
| Picom         | 4         | 0.16%   |
| CDE           | 4         | 0.16%   |
| Window Maker  | 3         | 0.12%   |
| spectrwm      | 3         | 0.12%   |
| KDE           | 3         | 0.12%   |
| IceWM         | 3         | 0.12%   |
| StumpWM       | 2         | 0.08%   |
| helloDesktop  | 2         | 0.08%   |
| Compton       | 2         | 0.08%   |
| Budgie        | 2         | 0.08%   |
| xinitrc       | 1         | 0.04%   |
| Xfwm4         | 1         | 0.04%   |
| sway          | 1         | 0.04%   |
| Potato        | 1         | 0.04%   |
| plasma        | 1         | 0.04%   |
| KWin          | 1         | 0.04%   |
| ctwm          | 1         | 0.04%   |
| bspwm         | 1         | 0.04%   |
| Blackbox      | 1         | 0.04%   |
| awesome       | 1         | 0.04%   |
| akonadi_newm  | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1481      | 61.55%  |
| Console | 869       | 36.12%  |
| Wayland | 55        | 2.29%   |
| Tty     | 1         | 0.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 1346      | 55.07%  |
| SDDM    | 384       | 15.71%  |
| SLiM    | 257       | 10.52%  |
| XDM     | 163       | 6.67%   |
| LightDM | 156       | 6.38%   |
| GDM     | 114       | 4.66%   |
| Ly      | 21        | 0.86%   |
| PCDM    | 2         | 0.08%   |
| WDM     | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang             | Computers | Percent |
|------------------|-----------|---------|
| C                | 1028      | 41.43%  |
| Unknown          | 653       | 26.32%  |
| en_US            | 350       | 14.11%  |
| ru_RU            | 131       | 5.28%   |
| de_DE            | 47        | 1.89%   |
| fr_FR            | 44        | 1.77%   |
| en_GB            | 34        | 1.37%   |
| zh_CN            | 16        | 0.64%   |
| en_CA            | 15        | 0.6%    |
| pt_BR            | 12        | 0.48%   |
| pl_PL            | 10        | 0.4%    |
| es_ES            | 10        | 0.4%    |
| uk_UA            | 9         | 0.36%   |
| ja_JP            | 9         | 0.36%   |
| en_AU            | 9         | 0.36%   |
| en_IE            | 8         | 0.32%   |
| nb_NO            | 7         | 0.28%   |
| it_IT            | 7         | 0.28%   |
| ru_RU.KOI8-R     | 4         | 0.16%   |
| fi_FI            | 4         | 0.16%   |
| en_US.ISO8859-1  | 4         | 0.16%   |
| en_NZ            | 4         | 0.16%   |
| el_GR            | 4         | 0.16%   |
| cs_CZ            | 4         | 0.16%   |
| es_AR            | 3         | 0.12%   |
| en_US.US-ASCII   | 3         | 0.12%   |
| de_DE.ISO8859-1  | 3         | 0.12%   |
| de_CH            | 3         | 0.12%   |
| zh_TW            | 2         | 0.08%   |
| sv_SE            | 2         | 0.08%   |
| pt_PT            | 2         | 0.08%   |
| nl_NL            | 2         | 0.08%   |
| it_IT.ISO8859-15 | 2         | 0.08%   |
| es_MX            | 2         | 0.08%   |
| en_SG            | 2         | 0.08%   |
| en_GB.US-ASCII   | 2         | 0.08%   |
| en_GB.ISO8859-1  | 2         | 0.08%   |
| zh_CN.GB2312     | 1         | 0.04%   |
| sv_SE.US-ASCII   | 1         | 0.04%   |
| sl_SI            | 1         | 0.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1510      | 63.26%  |
| BIOS | 877       | 36.74%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Zfs     | 1521      | 63.59%  |
| Ufs     | 865       | 36.16%  |
| Nfs     | 2         | 0.08%   |
| Cd9660  | 2         | 0.08%   |
| Xfs     | 1         | 0.04%   |
| Unknown | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 2102      | 88.36%  |
| MBR     | 256       | 10.76%  |
| BSD     | 12        | 0.5%    |
| Unknown | 9         | 0.38%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 407       | 17.2%   |
| Dell                    | 325       | 13.74%  |
| ASUSTek Computer        | 295       | 12.47%  |
| Hewlett-Packard         | 211       | 8.92%   |
| Gigabyte Technology     | 140       | 5.92%   |
| ASRock                  | 110       | 4.65%   |
| Unknown                 | 99        | 4.18%   |
| MSI                     | 97        | 4.1%    |
| Supermicro              | 88        | 3.72%   |
| Intel                   | 85        | 3.59%   |
| Acer                    | 69        | 2.92%   |
| Apple                   | 45        | 1.9%    |
| Fujitsu                 | 30        | 1.27%   |
| Toshiba                 | 22        | 0.93%   |
| Raspberry Pi Foundation | 21        | 0.89%   |
| IBM                     | 19        | 0.8%    |
| Samsung Electronics     | 18        | 0.76%   |
| PC Engines              | 16        | 0.68%   |
| ASRockRack              | 15        | 0.63%   |
| System76                | 13        | 0.55%   |
| HUAWEI                  | 13        | 0.55%   |
| Google                  | 13        | 0.55%   |
| Sony                    | 9         | 0.38%   |
| TUXEDO                  | 8         | 0.34%   |
| Shuttle                 | 8         | 0.34%   |
| HPE                     | 8         | 0.34%   |
| Sun Microsystems        | 6         | 0.25%   |
| Notebook                | 6         | 0.25%   |
| Biostar                 | 6         | 0.25%   |
| AMI                     | 6         | 0.25%   |
| Alienware               | 6         | 0.25%   |
| Panasonic               | 5         | 0.21%   |
| Gateway                 | 5         | 0.21%   |
| Framework               | 5         | 0.21%   |
| Deciso                  | 5         | 0.21%   |
| Cisco Systems           | 5         | 0.21%   |
| Beckhoff Automation     | 5         | 0.21%   |
| AZW                     | 5         | 0.21%   |
| Wistron                 | 4         | 0.17%   |
| Pegatron                | 4         | 0.17%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| Unknown                          | 104       | 4.4%    |
| ASUS All Series                  | 27        | 1.14%   |
| Supermicro Super Server          | 24        | 1.01%   |
| RPi Raspberry Pi                 | 20        | 0.85%   |
| Dell OEM-R 720xd                 | 13        | 0.55%   |
| HP ProLiant MicroServer Gen8     | 10        | 0.42%   |
| Intel Nobilis                    | 9         | 0.38%   |
| PC Engines APU2                  | 8         | 0.34%   |
| Dell PowerEdge R710              | 7         | 0.3%    |
| HP ProLiant MicroServer          | 6         | 0.25%   |
| ASUS TUF GAMING X570-PLUS        | 6         | 0.25%   |
| MSI MS-7C02                      | 5         | 0.21%   |
| HP Z440 Workstation              | 5         | 0.21%   |
| HP EliteBook 840 G3              | 5         | 0.21%   |
| Gigabyte B360N WIFI              | 5         | 0.21%   |
| Framework Laptop                 | 5         | 0.21%   |
| Dell PowerEdge R720              | 5         | 0.21%   |
| Dell OptiPlex 9020               | 5         | 0.21%   |
| Dell Latitude E7240              | 5         | 0.21%   |
| ASRock X570 Phantom Gaming 4     | 5         | 0.21%   |
| System76 Lemur Pro               | 4         | 0.17%   |
| Supermicro X9SCL/X9SCM           | 4         | 0.17%   |
| Supermicro X10SLL-F              | 4         | 0.17%   |
| Sun Microsystems Sun Fire X4150  | 4         | 0.17%   |
| MSI MS-7B89                      | 4         | 0.17%   |
| HPE ProLiant MicroServer Gen10   | 4         | 0.17%   |
| HP Z620 Workstation              | 4         | 0.17%   |
| HP Z420 Workstation              | 4         | 0.17%   |
| HP t620 Quad Core TC             | 4         | 0.17%   |
| HP EliteBook 8570p               | 4         | 0.17%   |
| HP Compaq Elite 8300 SFF         | 4         | 0.17%   |
| Gigabyte X570 I AORUS PRO WIFI   | 4         | 0.17%   |
| Gigabyte B450M DS3H              | 4         | 0.17%   |
| Fujitsu D3401-H2 S26361-D3401-H2 | 4         | 0.17%   |
| Dell PowerEdge T30               | 4         | 0.17%   |
| Dell PowerEdge R610              | 4         | 0.17%   |
| Dell OptiPlex 7040               | 4         | 0.17%   |
| Dell OptiPlex 3010               | 4         | 0.17%   |
| Dell Latitude E6430              | 4         | 0.17%   |
| Dell Inspiron 15 7000 Gaming     | 4         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 295       | 12.47%  |
| Unknown            | 104       | 4.4%    |
| Dell Latitude      | 76        | 3.21%   |
| Dell PowerEdge     | 58        | 2.45%   |
| Dell Inspiron      | 50        | 2.11%   |
| ASUS PRIME         | 44        | 1.86%   |
| Dell OptiPlex      | 42        | 1.78%   |
| Acer Aspire        | 40        | 1.69%   |
| Lenovo IdeaPad     | 35        | 1.48%   |
| HP ProLiant        | 35        | 1.48%   |
| Dell Precision     | 34        | 1.44%   |
| HP Compaq          | 29        | 1.23%   |
| ASUS ROG           | 27        | 1.14%   |
| ASUS All           | 27        | 1.14%   |
| Supermicro Super   | 24        | 1.01%   |
| ASUS TUF           | 24        | 1.01%   |
| RPi Raspberry      | 20        | 0.85%   |
| HP EliteBook       | 19        | 0.8%    |
| Lenovo ThinkCentre | 18        | 0.76%   |
| HP ProBook         | 18        | 0.76%   |
| Dell XPS           | 18        | 0.76%   |
| Toshiba Satellite  | 14        | 0.59%   |
| Dell Vostro        | 14        | 0.59%   |
| HP Pavilion        | 13        | 0.55%   |
| Dell OEM-R         | 13        | 0.55%   |
| ASRock X570        | 13        | 0.55%   |
| IBM System         | 12        | 0.51%   |
| HP Laptop          | 10        | 0.42%   |
| Intel Nobilis      | 9         | 0.38%   |
| HP EliteDesk       | 9         | 0.38%   |
| Gigabyte X570      | 9         | 0.38%   |
| ASUS ZenBook       | 9         | 0.38%   |
| PC Engines APU2    | 8         | 0.34%   |
| HPE ProLiant       | 8         | 0.34%   |
| HP ENVY            | 8         | 0.34%   |
| Gigabyte B450M     | 8         | 0.34%   |
| ASUS ASUS          | 8         | 0.34%   |
| ASRock X370        | 8         | 0.34%   |
| Lenovo Legion      | 7         | 0.3%    |
| HP t620            | 7         | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 259       | 10.95%  |
| 2019    | 240       | 10.14%  |
| 2018    | 213       | 9%      |
| 2021    | 205       | 8.66%   |
| 2011    | 152       | 6.42%   |
| 2013    | 146       | 6.17%   |
| 2014    | 130       | 5.49%   |
| 2017    | 122       | 5.16%   |
| 2015    | 122       | 5.16%   |
| 2012    | 116       | 4.9%    |
| 2022    | 115       | 4.86%   |
| 2016    | 115       | 4.86%   |
| 2010    | 99        | 4.18%   |
| Unknown | 93        | 3.93%   |
| 2009    | 72        | 3.04%   |
| 2008    | 66        | 2.79%   |
| 2007    | 34        | 1.44%   |
| 2023    | 29        | 1.23%   |
| 2006    | 16        | 0.68%   |
| 2005    | 6         | 0.25%   |
| 2004    | 6         | 0.25%   |
| 2003    | 5         | 0.21%   |
| 2002    | 4         | 0.17%   |
| 2001    | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 1028      | 43.45%  |
| Notebook       | 983       | 41.55%  |
| Server         | 188       | 7.95%   |
| Mini pc        | 67        | 2.83%   |
| System on chip | 53        | 2.24%   |
| Convertible    | 25        | 1.06%   |
| All in one     | 21        | 0.89%   |
| Tablet         | 1         | 0.04%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2320      | 98.06%  |
| Yes  | 46        | 1.94%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 621       | 25.91%  |
| 8.01-16.0       | 611       | 25.49%  |
| 32.01-64.0      | 347       | 14.48%  |
| 4.01-8.0        | 308       | 12.85%  |
| 64.01-256.0     | 217       | 9.05%   |
| 2.01-3.0        | 88        | 3.67%   |
| 3.01-4.0        | 51        | 2.13%   |
| 24.01-32.0      | 50        | 2.09%   |
| 0.51-1.0        | 50        | 2.09%   |
| 1.01-2.0        | 18        | 0.75%   |
| 0.01-0.5        | 18        | 0.75%   |
| More than 256.0 | 17        | 0.71%   |
| Unknown         | 1         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 0.01-0.5        | 805       | 32.82%  |
| 0.51-1.0        | 757       | 30.86%  |
| 1.01-2.0        | 438       | 17.86%  |
| 2.01-3.0        | 112       | 4.57%   |
| 4.01-8.0        | 91        | 3.71%   |
| 3.01-4.0        | 71        | 2.89%   |
| 8.01-16.0       | 52        | 2.12%   |
| 24.01-32.0      | 31        | 1.26%   |
| 0               | 30        | 1.22%   |
| 32.01-64.0      | 23        | 0.94%   |
| 16.01-24.0      | 22        | 0.9%    |
| 64.01-256.0     | 19        | 0.77%   |
| More than 256.0 | 1         | 0.04%   |
| Unknown         | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1156      | 47.09%  |
| 2      | 514       | 20.94%  |
| 3      | 208       | 8.47%   |
| 0      | 180       | 7.33%   |
| 4      | 136       | 5.54%   |
| 5      | 84        | 3.42%   |
| 6      | 56        | 2.28%   |
| 7      | 29        | 1.18%   |
| 8      | 20        | 0.81%   |
| 10     | 12        | 0.49%   |
| 12     | 10        | 0.41%   |
| 14     | 9         | 0.37%   |
| 11     | 8         | 0.33%   |
| 9      | 8         | 0.33%   |
| 18     | 3         | 0.12%   |
| 58     | 2         | 0.08%   |
| 25     | 2         | 0.08%   |
| 24     | 2         | 0.08%   |
| 23     | 2         | 0.08%   |
| 17     | 2         | 0.08%   |
| 16     | 2         | 0.08%   |
| 15     | 2         | 0.08%   |
| 13     | 2         | 0.08%   |
| 63     | 1         | 0.04%   |
| 40     | 1         | 0.04%   |
| 30     | 1         | 0.04%   |
| 28     | 1         | 0.04%   |
| 21     | 1         | 0.04%   |
| 19     | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1723      | 72.21%  |
| Yes       | 663       | 27.79%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2082      | 87.96%  |
| No        | 285       | 12.04%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1324      | 55.56%  |
| No        | 1059      | 44.44%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1427      | 59.73%  |
| Yes       | 962       | 40.27%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 535       | 22.44%  |
| Russia      | 264       | 11.07%  |
| Germany     | 238       | 9.98%   |
| France      | 123       | 5.16%   |
| Canada      | 91        | 3.82%   |
| Poland      | 88        | 3.69%   |
| UK          | 87        | 3.65%   |
| Brazil      | 53        | 2.22%   |
| Australia   | 53        | 2.22%   |
| China       | 52        | 2.18%   |
| Netherlands | 50        | 2.1%    |
| Czechia     | 50        | 2.1%    |
| Ukraine     | 48        | 2.01%   |
| Japan       | 38        | 1.59%   |
| Austria     | 38        | 1.59%   |
| Switzerland | 35        | 1.47%   |
| Spain       | 33        | 1.38%   |
| Italy       | 33        | 1.38%   |
| Sweden      | 29        | 1.22%   |
| Norway      | 26        | 1.09%   |
| Indonesia   | 25        | 1.05%   |
| Finland     | 25        | 1.05%   |
| Romania     | 24        | 1.01%   |
| India       | 24        | 1.01%   |
| Ireland     | 19        | 0.8%    |
| Argentina   | 18        | 0.76%   |
| Greece      | 17        | 0.71%   |
| Thailand    | 16        | 0.67%   |
| Denmark     | 14        | 0.59%   |
| Portugal    | 13        | 0.55%   |
| New Zealand | 13        | 0.55%   |
| Belgium     | 13        | 0.55%   |
| Hungary     | 12        | 0.5%    |
| Bulgaria    | 12        | 0.5%    |
| Taiwan      | 11        | 0.46%   |
| Mexico      | 9         | 0.38%   |
| Croatia     | 9         | 0.38%   |
| Slovenia    | 8         | 0.34%   |
| Serbia      | 8         | 0.34%   |
| Singapore   | 7         | 0.29%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Moscow        | 98        | 3.85%   |
| Vienna        | 31        | 1.22%   |
| Berlin        | 29        | 1.14%   |
| St Petersburg | 27        | 1.06%   |
| Brooklyn      | 27        | 1.06%   |
| Sydney        | 25        | 0.98%   |
| Kyiv          | 23        | 0.9%    |
| Paris         | 19        | 0.75%   |
| Gdynia        | 18        | 0.71%   |
| Warsaw        | 17        | 0.67%   |
| Krasnodar     | 17        | 0.67%   |
| Amsterdam     | 17        | 0.67%   |
| Ludwigsburg   | 16        | 0.63%   |
| London        | 16        | 0.63%   |
| Grand Rapids  | 16        | 0.63%   |
| Montreal      | 15        | 0.59%   |
| Helsinki      | 15        | 0.59%   |
| Chicago       | 15        | 0.59%   |
| Zurich        | 14        | 0.55%   |
| Prague        | 14        | 0.55%   |
| Yekaterinburg | 13        | 0.51%   |
| Dublin        | 13        | 0.51%   |
| Tuklaty       | 12        | 0.47%   |
| Portland      | 12        | 0.47%   |
| Seattle       | 11        | 0.43%   |
| Ozersk        | 10        | 0.39%   |
| Jakarta       | 10        | 0.39%   |
| Hamburg       | 10        | 0.39%   |
| Sofia         | 9         | 0.35%   |
| Oslo          | 9         | 0.35%   |
| Novosibirsk   | 9         | 0.35%   |
| Munich        | 9         | 0.35%   |
| Madrid        | 9         | 0.35%   |
| Lexington     | 9         | 0.35%   |
| Brno          | 9         | 0.35%   |
| Athens        | 9         | 0.35%   |
| Shenzhen      | 8         | 0.31%   |
| Rochester     | 8         | 0.31%   |
| Poway         | 8         | 0.31%   |
| New York      | 8         | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 642       | 1927   | 18.99%  |
| Samsung Electronics | 571       | 1105   | 16.89%  |
| Seagate             | 471       | 1231   | 13.93%  |
| Toshiba             | 212       | 477    | 6.27%   |
| Kingston            | 198       | 259    | 5.86%   |
| Crucial             | 187       | 295    | 5.53%   |
| Intel               | 143       | 273    | 4.23%   |
| Hitachi             | 106       | 279    | 3.14%   |
| SanDisk             | 93        | 129    | 2.75%   |
| HGST                | 93        | 347    | 2.75%   |
| A-DATA Technology   | 59        | 75     | 1.75%   |
| SK hynix            | 52        | 62     | 1.54%   |
| Micron Technology   | 47        | 76     | 1.39%   |
| Transcend           | 45        | 59     | 1.33%   |
| Hewlett-Packard     | 31        | 168    | 0.92%   |
| Phison              | 24        | 34     | 0.71%   |
| PNY                 | 20        | 31     | 0.59%   |
| KIOXIA              | 19        | 19     | 0.56%   |
| SPCC                | 18        | 37     | 0.53%   |
| OCZ                 | 18        | 22     | 0.53%   |
| Corsair             | 18        | 43     | 0.53%   |
| Apple               | 16        | 17     | 0.47%   |
| KingSpec            | 13        | 19     | 0.38%   |
| Silicon Motion      | 12        | 14     | 0.35%   |
| LITEON              | 11        | 16     | 0.33%   |
| GOODRAM             | 11        | 21     | 0.33%   |
| Gigabyte Technology | 11        | 14     | 0.33%   |
| Patriot             | 10        | 13     | 0.3%    |
| Maxtor              | 10        | 14     | 0.3%    |
| Fujitsu             | 10        | 15     | 0.3%    |
| China               | 9         | 10     | 0.27%   |
| OWC                 | 8         | 12     | 0.24%   |
| Intenso             | 8         | 9      | 0.24%   |
| FORESEE             | 8         | 8      | 0.24%   |
| Apacer              | 8         | 8      | 0.24%   |
| Plextor             | 7         | 13     | 0.21%   |
| Mushkin             | 7         | 8      | 0.21%   |
| Lenovo              | 7         | 7      | 0.21%   |
| Team                | 6         | 8      | 0.18%   |
| Hikvision           | 6         | 7      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB        | 45        | 1.12%   |
| Samsung SSD 850 EVO 250GB          | 29        | 0.72%   |
| WDC WD40EFRX-68N32N0 4TB           | 24        | 0.6%    |
| Seagate ST1000DM010-2EP102 1TB     | 24        | 0.6%    |
| Samsung SSD 970 EVO Plus 1TB       | 24        | 0.6%    |
| Kingston SA400S37120G 120GB        | 24        | 0.6%    |
| Samsung SSD 860 EVO 500GB          | 23        | 0.57%   |
| WDC WD30EFRX-68EUZN0 3TB           | 22        | 0.55%   |
| WDC WD10EZEX-08WN4A0 1TB           | 22        | 0.55%   |
| Samsung SSD 850 EVO 500GB          | 21        | 0.52%   |
| Crucial CT500MX500SSD1 500GB       | 20        | 0.5%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 19        | 0.47%   |
| Samsung SSD 860 EVO 250GB          | 18        | 0.45%   |
| WDC WD800JD-75MSA3 80GB            | 17        | 0.42%   |
| Seagate ST2000DM008-2FR102 2TB     | 17        | 0.42%   |
| HGST HTS721010A9E630 1TB           | 17        | 0.42%   |
| Toshiba MQ01ABD100 1TB             | 16        | 0.4%    |
| Toshiba DT01ACA100 1TB             | 16        | 0.4%    |
| Seagate ST4000DM000-1F2168 4TB     | 16        | 0.4%    |
| Seagate ST1000LM035-1RK172 1TB     | 16        | 0.4%    |
| Samsung SSD 970 EVO Plus 500GB     | 16        | 0.4%    |
| Kingston SA400S37480G 480GB        | 16        | 0.4%    |
| Crucial CT250MX500SSD1 250GB       | 16        | 0.4%    |
| Crucial CT240BX500SSD1 240GB       | 16        | 0.4%    |
| Samsung SSD 870 EVO 1TB            | 15        | 0.37%   |
| Crucial CT1000MX500SSD1 1TB        | 15        | 0.37%   |
| Toshiba MQ01ABF050 500GB           | 14        | 0.35%   |
| Samsung SSD 860 EVO 1TB            | 14        | 0.35%   |
| WDC WD20EFRX-68EUZN0 2TB           | 13        | 0.32%   |
| Seagate ST1000DM003-1CH162 1TB     | 13        | 0.32%   |
| Seagate ST500DM002-1BD142 500GB    | 12        | 0.3%    |
| Seagate ST4000VN008-2DR166 4TB     | 12        | 0.3%    |
| Samsung SSD 970 EVO 500GB          | 12        | 0.3%    |
| Samsung SSD 850 EVO 1TB            | 12        | 0.3%    |
| Kingston SV300S37A120G 120GB       | 12        | 0.3%    |
| Seagate ST2000LM007-1R8174 2TB     | 11        | 0.27%   |
| Seagate ST2000DM001-1CH164 2TB     | 11        | 0.27%   |
| Seagate ST1000LM048-2E7172 1TB     | 11        | 0.27%   |
| Samsung SSD 980 PRO 1TB            | 11        | 0.27%   |
| Crucial CT2000MX500SSD1 2TB        | 11        | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor               | Computers | Drives | Percent |
|----------------------|-----------|--------|---------|
| WDC                  | 511       | 1658   | 34.88%  |
| Seagate              | 465       | 1218   | 31.74%  |
| Toshiba              | 174       | 419    | 11.88%  |
| Hitachi              | 105       | 275    | 7.17%   |
| HGST                 | 93        | 343    | 6.35%   |
| Samsung Electronics  | 49        | 79     | 3.34%   |
| Hewlett-Packard      | 21        | 155    | 1.43%   |
| Maxtor               | 10        | 14     | 0.68%   |
| Fujitsu              | 10        | 15     | 0.68%   |
| Apple                | 6         | 7      | 0.41%   |
| HPE                  | 3         | 17     | 0.2%    |
| IBM/Hitachi          | 2         | 2      | 0.14%   |
| HPT                  | 2         | 9      | 0.14%   |
| Dell                 | 2         | 5      | 0.14%   |
| Areca                | 2         | 3      | 0.14%   |
| Adaptec              | 2         | 12     | 0.14%   |
| WD MediaMax          | 1         | 2      | 0.07%   |
| SYNOLOGY             | 1         | 1      | 0.07%   |
| QUANTUM              | 1         | 2      | 0.07%   |
| NETAPP               | 1         | 2      | 0.07%   |
| MaxDigital           | 1         | 1      | 0.07%   |
| LSI                  | 1         | 4      | 0.07%   |
| IBM                  | 1         | 1      | 0.07%   |
| ExcelStor Technology | 1         | 4      | 0.07%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 309       | 651    | 23.7%   |
| Kingston            | 164       | 213    | 12.58%  |
| Crucial             | 150       | 230    | 11.5%   |
| Intel               | 94        | 210    | 7.21%   |
| SanDisk             | 92        | 128    | 7.06%   |
| WDC                 | 78        | 127    | 5.98%   |
| A-DATA Technology   | 41        | 53     | 3.14%   |
| Transcend           | 40        | 52     | 3.07%   |
| Micron Technology   | 28        | 47     | 2.15%   |
| Toshiba             | 20        | 21     | 1.53%   |
| SK hynix            | 19        | 22     | 1.46%   |
| OCZ                 | 18        | 22     | 1.38%   |
| PNY                 | 15        | 25     | 1.15%   |
| KingSpec            | 13        | 19     | 1%      |
| SPCC                | 12        | 29     | 0.92%   |
| Corsair             | 12        | 16     | 0.92%   |
| Patriot             | 10        | 13     | 0.77%   |
| LITEON              | 10        | 15     | 0.77%   |
| Apple               | 10        | 10     | 0.77%   |
| China               | 9         | 10     | 0.69%   |
| OWC                 | 8         | 12     | 0.61%   |
| Intenso             | 8         | 9      | 0.61%   |
| GOODRAM             | 8         | 17     | 0.61%   |
| Apacer              | 8         | 8      | 0.61%   |
| Hewlett-Packard     | 6         | 6      | 0.46%   |
| Gigabyte Technology | 6         | 7      | 0.46%   |
| Team                | 5         | 7      | 0.38%   |
| Seagate             | 5         | 7      | 0.38%   |
| Plextor             | 5         | 8      | 0.38%   |
| Mushkin             | 5         | 5      | 0.38%   |
| MidasForce          | 5         | 5      | 0.38%   |
| Verbatim            | 4         | 4      | 0.31%   |
| Phison              | 4         | 5      | 0.31%   |
| LITEONIT            | 4         | 4      | 0.31%   |
| Hoodisk             | 4         | 6      | 0.31%   |
| Hikvision           | 4         | 5      | 0.31%   |
| Zheino              | 3         | 4      | 0.23%   |
| Vaseky              | 3         | 3      | 0.23%   |
| Supermicro          | 3         | 3      | 0.23%   |
| ORICO               | 3         | 3      | 0.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1142      | 4248   | 39.24%  |
| SSD  | 1121      | 2135   | 38.52%  |
| NVMe | 647       | 1018   | 22.23%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1821      | 6383   | 73.78%  |
| NVMe | 647       | 1018   | 26.22%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1323      | 2465   | 51.8%   |
| 0.51-1.0   | 553       | 1179   | 21.65%  |
| 1.01-2.0   | 264       | 697    | 10.34%  |
| 3.01-4.0   | 156       | 721    | 6.11%   |
| 4.01-10.0  | 132       | 793    | 5.17%   |
| 2.01-3.0   | 88        | 320    | 3.45%   |
| 10.01-20.0 | 35        | 202    | 1.37%   |
| 20.01-50.0 | 3         | 6      | 0.12%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 748       | 30.36%  |
| 251-500        | 562       | 22.81%  |
| 501-1000       | 356       | 14.45%  |
| 51-100         | 261       | 10.59%  |
| 21-50          | 173       | 7.02%   |
| 1-20           | 127       | 5.15%   |
| 1001-2000      | 117       | 4.75%   |
| More than 3000 | 66        | 2.68%   |
| 2001-3000      | 30        | 1.22%   |
| Unknown        | 24        | 0.97%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1757      | 71.45%  |
| 21-50          | 324       | 13.18%  |
| 51-100         | 118       | 4.8%    |
| 101-250        | 92        | 3.74%   |
| 251-500        | 53        | 2.16%   |
| 501-1000       | 41        | 1.67%   |
| Unknown        | 24        | 0.98%   |
| More than 3000 | 21        | 0.85%   |
| 1001-2000      | 15        | 0.61%   |
| 2001-3000      | 12        | 0.49%   |
| 0              | 2         | 0.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD30EFRX-68EUZN0 3TB            | 7         | 24     | 1.4%    |
| HGST HTS725050A7E630 500GB          | 7         | 15     | 1.4%    |
| Seagate ST500LT012-1DG142 500GB     | 6         | 6      | 1.2%    |
| Seagate ST3500413AS 500GB           | 6         | 9      | 1.2%    |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 6         | 7      | 1.2%    |
| WDC WD20EFRX-68EUZN0 2TB            | 5         | 12     | 1%      |
| Samsung Electronics SSD 870 EVO 1TB | 5         | 7      | 1%      |
| WDC WD40EFRX-68WT0N0 4TB            | 4         | 12     | 0.8%    |
| Seagate ST9500420AS 500GB           | 4         | 6      | 0.8%    |
| Seagate ST9250315AS 250GB           | 4         | 4      | 0.8%    |
| Seagate ST500LT012-9WS142 500GB     | 4         | 7      | 0.8%    |
| Samsung Electronics HD501LJ 500GB   | 4         | 6      | 0.8%    |
| HGST HTS721010A9E630 1TB            | 4         | 22     | 0.8%    |
| WDC WD2000FYYZ-01UL1B2 2TB          | 3         | 5      | 0.6%    |
| Toshiba MQ01ABF050 500GB            | 3         | 3      | 0.6%    |
| Toshiba MQ01ABD100 1TB              | 3         | 3      | 0.6%    |
| Seagate ST380013AS 80GB             | 3         | 4      | 0.6%    |
| Seagate ST3500418AS 500GB           | 3         | 6      | 0.6%    |
| Seagate ST320LT007-9ZV142 320GB     | 3         | 3      | 0.6%    |
| Seagate ST2000DM001-9YN164 2TB      | 3         | 3      | 0.6%    |
| Seagate ST1000DM003-1CH162 1TB      | 3         | 4      | 0.6%    |
| Samsung Electronics HD154UI 1.5TB   | 3         | 4      | 0.6%    |
| Samsung Electronics HD103UJ 1TB     | 3         | 6      | 0.6%    |
| Kingston SNS4151S316GD 16GB         | 3         | 3      | 0.6%    |
| Intel SSDSA2M080G2GC 80GB           | 3         | 3      | 0.6%    |
| Hitachi HTS547550A9E384 500GB       | 3         | 3      | 0.6%    |
| Crucial CT525MX300SSD1 528GB        | 3         | 3      | 0.6%    |
| WDC WDS240G2G0A-00JH30 240GB        | 2         | 2      | 0.4%    |
| WDC WD5000LPLX-22ZNTT0 500GB        | 2         | 2      | 0.4%    |
| WDC WD5000LPLX-00ZNTT0 500GB        | 2         | 3      | 0.4%    |
| WDC WD5000AAKX-60U6AA0 500GB        | 2         | 2      | 0.4%    |
| WDC WD5000AAKX-083CA0 500GB         | 2         | 2      | 0.4%    |
| WDC WD40EFRX-68N32N0 4TB            | 2         | 5      | 0.4%    |
| WDC WD3200BPVT-80JJ5T0 320GB        | 2         | 2      | 0.4%    |
| WDC WD20EARS-00MVWB0 2TB            | 2         | 2      | 0.4%    |
| WDC WD2002FYPS-02W3B0 2TB           | 2         | 2      | 0.4%    |
| WDC WD2002FYPS-01U1B0 2TB           | 2         | 3      | 0.4%    |
| WDC WD2000FYYZ-01UL1B1 2TB          | 2         | 4      | 0.4%    |
| WDC WD15EARS-00Z5B1 1.5TB           | 2         | 2      | 0.4%    |
| WDC WD15EADS-00P8B0 1.5TB           | 2         | 2      | 0.4%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor               | Computers | Drives | Percent |
|----------------------|-----------|--------|---------|
| Seagate              | 116       | 166    | 24.63%  |
| WDC                  | 107       | 208    | 22.72%  |
| Samsung Electronics  | 43        | 57     | 9.13%   |
| Hitachi              | 41        | 66     | 8.7%    |
| Toshiba              | 34        | 63     | 7.22%   |
| Intel                | 21        | 29     | 4.46%   |
| Kingston             | 18        | 20     | 3.82%   |
| HGST                 | 16        | 45     | 3.4%    |
| Crucial              | 13        | 19     | 2.76%   |
| SanDisk              | 8         | 10     | 1.7%    |
| Micron Technology    | 7         | 13     | 1.49%   |
| Maxtor               | 7         | 11     | 1.49%   |
| A-DATA Technology    | 7         | 9      | 1.49%   |
| SK hynix             | 4         | 6      | 0.85%   |
| Hewlett-Packard      | 4         | 7      | 0.85%   |
| OCZ                  | 3         | 4      | 0.64%   |
| Apple                | 3         | 3      | 0.64%   |
| Fujitsu              | 2         | 5      | 0.42%   |
| Corsair              | 2         | 4      | 0.42%   |
| walram               | 1         | 1      | 0.21%   |
| Transcend            | 1         | 1      | 0.21%   |
| SSSTC                | 1         | 1      | 0.21%   |
| SPCC                 | 1         | 1      | 0.21%   |
| SMI                  | 1         | 1      | 0.21%   |
| Plextor              | 1         | 1      | 0.21%   |
| Phison               | 1         | 1      | 0.21%   |
| LITEON               | 1         | 1      | 0.21%   |
| Lexar                | 1         | 1      | 0.21%   |
| IBM/Hitachi          | 1         | 1      | 0.21%   |
| GK                   | 1         | 1      | 0.21%   |
| Fanxiang             | 1         | 1      | 0.21%   |
| ExcelStor Technology | 1         | 2      | 0.21%   |
| Apacer               | 1         | 1      | 0.21%   |
| AMD                  | 1         | 2      | 0.21%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor               | Computers | Drives | Percent |
|----------------------|-----------|--------|---------|
| Seagate              | 115       | 165    | 33.14%  |
| WDC                  | 104       | 205    | 29.97%  |
| Hitachi              | 41        | 66     | 11.82%  |
| Toshiba              | 33        | 62     | 9.51%   |
| Samsung Electronics  | 22        | 29     | 6.34%   |
| HGST                 | 16        | 45     | 4.61%   |
| Maxtor               | 7         | 11     | 2.02%   |
| Hewlett-Packard      | 3         | 6      | 0.86%   |
| Fujitsu              | 2         | 5      | 0.58%   |
| Apple                | 2         | 2      | 0.58%   |
| IBM/Hitachi          | 1         | 1      | 0.29%   |
| ExcelStor Technology | 1         | 2      | 0.29%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 322       | 599    | 72.52%  |
| SSD  | 118       | 159    | 26.58%  |
| NVMe | 4         | 4      | 0.9%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart_bsd/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD20EARS-00MVWB0 2TB          | 1         | 1      | 14.29%  |
| Toshiba MG05ACA800E 8TB           | 1         | 1      | 14.29%  |
| SanDisk pSSD 256GB                | 1         | 1      | 14.29%  |
| Samsung Electronics HM250JI 250GB | 1         | 1      | 14.29%  |
| Maxtor 6E040L0 40GB               | 1         | 1      | 14.29%  |
| Hitachi HUS724040ALE641 4TB       | 1         | 14     | 14.29%  |
| Crucial M4-CT256M4SSD1 256GB      | 1         | 1      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 14.29%  |
| Toshiba             | 1         | 1      | 14.29%  |
| SanDisk             | 1         | 1      | 14.29%  |
| Samsung Electronics | 1         | 1      | 14.29%  |
| Maxtor              | 1         | 1      | 14.29%  |
| Hitachi             | 1         | 14     | 14.29%  |
| Crucial             | 1         | 1      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1990      | 6373   | 79.86%  |
| Malfunc  | 427       | 762    | 17.13%  |
| Detected | 68        | 246    | 2.73%   |
| Failed   | 7         | 20     | 0.28%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 1552      | 49.95%  |
| AMD                                     | 415       | 13.36%  |
| Samsung Electronics                     | 268       | 8.63%   |
| Broadcom / LSI                          | 162       | 5.21%   |
| SanDisk                                 | 106       | 3.41%   |
| ASMedia Technology                      | 65        | 2.09%   |
| Marvell Technology Group                | 61        | 1.96%   |
| Phison Electronics                      | 44        | 1.42%   |
| Silicon Motion                          | 43        | 1.38%   |
| Kingston Technology Company             | 38        | 1.22%   |
| SK hynix                                | 35        | 1.13%   |
| Micron/Crucial Technology               | 33        | 1.06%   |
| Nvidia                                  | 32        | 1.03%   |
| JMicron Technology                      | 27        | 0.87%   |
| Toshiba                                 | 25        | 0.8%    |
| Micron Technology                       | 23        | 0.74%   |
| Adaptec                                 | 22        | 0.71%   |
| KIOXIA                                  | 20        | 0.64%   |
| Hewlett-Packard                         | 16        | 0.51%   |
| ADATA Technology                        | 16        | 0.51%   |
| Silicon Image                           | 9         | 0.29%   |
| Realtek Semiconductor                   | 8         | 0.26%   |
| VIA Technologies                        | 7         | 0.23%   |
| Areca Technology                        | 7         | 0.23%   |
| Union Memory (Shenzhen)                 | 6         | 0.19%   |
| Silicon Integrated Systems [SiS]        | 6         | 0.19%   |
| Chelsio Communications                  | 6         | 0.19%   |
| Solid State Storage Technology          | 5         | 0.16%   |
| Shenzhen Longsys Electronics            | 5         | 0.16%   |
| Seagate Technology                      | 5         | 0.16%   |
| Lite-On Technology                      | 5         | 0.16%   |
| 3ware                                   | 5         | 0.16%   |
| MAXIO Technology (Hangzhou)             | 4         | 0.13%   |
| Lenovo                                  | 4         | 0.13%   |
| Transcend                               | 3         | 0.1%    |
| Integrated Technology Express           | 3         | 0.1%    |
| Broadcom                                | 3         | 0.1%    |
| ULi Electronics                         | 2         | 0.06%   |
| Shenzhen Unionmemory Information System | 2         | 0.06%   |
| Promise Technology                      | 2         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 271       | 7.54%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 151       | 4.2%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 103       | 2.87%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 100       | 2.78%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 81        | 2.25%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 78        | 2.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 78        | 2.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 76        | 2.11%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 65        | 1.81%   |
| AMD 400 Series Chipset SATA Controller                                         | 64        | 1.78%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 58        | 1.61%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 54        | 1.5%    |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                   | 53        | 1.47%   |
| Intel Comet Lake SATA AHCI Controller                                          | 43        | 1.2%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 41        | 1.14%   |
| Samsung NVMe SSD Controller 980                                                | 40        | 1.11%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 40        | 1.11%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 39        | 1.09%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 38        | 1.06%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 37        | 1.03%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 37        | 1.03%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 37        | 1.03%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 37        | 1.03%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 37        | 1.03%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 36        | 1%      |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 35        | 0.97%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 35        | 0.97%   |
| AMD 500 Series Chipset SATA Controller                                         | 35        | 0.97%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 34        | 0.95%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 34        | 0.95%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 32        | 0.89%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 31        | 0.86%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 29        | 0.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 28        | 0.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 28        | 0.78%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 27        | 0.75%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 26        | 0.72%   |
| Phison E12 NVMe Controller                                                     | 25        | 0.7%    |
| Intel SATA Controller [RAID mode]                                              | 24        | 0.67%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 24        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1707      | 55.06%  |
| NVMe | 700       | 22.58%  |
| IDE  | 346       | 11.16%  |
| RAID | 206       | 6.65%   |
| SAS  | 104       | 3.35%   |
| SCSI | 37        | 1.19%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Intel              | 1765      | 74.41%  |
| AMD                | 497       | 20.95%  |
| ARM                | 86        | 3.63%   |
| Unknown            | 14        | 0.59%   |
| IBM                | 2         | 0.08%   |
| VIA                | 1         | 0.04%   |
| Sun                | 1         | 0.04%   |
| Rockchip           | 1         | 0.04%   |
| Research           | 1         | 0.04%   |
| NXP                | 1         | 0.04%   |
| Motorola           | 1         | 0.04%   |
| i                  | 1         | 0.04%   |
| Baikal Electronics | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| ARM Cortex-A72 r0p3                     | 30        | 1.26%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 24        | 1.01%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 21        | 0.88%   |
| ARM Cortex-A53 r0p4                     | 21        | 0.88%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 19        | 0.8%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 18        | 0.75%   |
| Intel CPU Version                       | 17        | 0.71%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 17        | 0.71%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 16        | 0.67%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 16        | 0.67%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 16        | 0.67%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz     | 15        | 0.63%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 15        | 0.63%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 15        | 0.63%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 15        | 0.63%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 15        | 0.63%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 15        | 0.63%   |
|                                         | 14        | 0.59%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 13        | 0.54%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 13        | 0.54%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 13        | 0.54%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 12        | 0.5%    |
| Intel Core i5-5200U CPU @ 2.20GHz       | 12        | 0.5%    |
| Intel Celeron CPU J1900 @ 1.99GHz       | 12        | 0.5%    |
| AMD GX-412TC SOC                        | 12        | 0.5%    |
| Intel Core i7-3770 CPU @ 3.40GHz        | 11        | 0.46%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 11        | 0.46%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 11        | 0.46%   |
| ARM Cortex-A55 r2p0                     | 11        | 0.46%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 11        | 0.46%   |
| AMD Ryzen 7 2700X Eight-Core Processor  | 11        | 0.46%   |
| AMD FX-8350 Eight-Core Processor        | 11        | 0.46%   |
| Intel Xeon                              | 10        | 0.42%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 10        | 0.42%   |
| Intel Core i7-7700 CPU @ 3.60GHz        | 10        | 0.42%   |
| AMD Ryzen 9 5950X 16-Core Processor     | 10        | 0.42%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 10        | 0.42%   |
| AMD Ryzen 7 1700 Eight-Core Processor   | 10        | 0.42%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 9         | 0.38%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 9         | 0.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 467       | 19.65%  |
| Intel Core i7          | 394       | 16.58%  |
| Intel Xeon             | 258       | 10.85%  |
| Other                  | 160       | 6.73%   |
| AMD Ryzen 7            | 113       | 4.75%   |
| Intel Core i3          | 111       | 4.67%   |
| Intel Celeron          | 108       | 4.54%   |
| AMD Ryzen 5            | 87        | 3.66%   |
| Intel Core 2 Duo       | 78        | 3.28%   |
| ARM Cortex             | 78        | 3.28%   |
| Intel Atom             | 57        | 2.4%    |
| Intel Pentium          | 43        | 1.81%   |
| AMD Ryzen 9            | 41        | 1.72%   |
| AMD FX                 | 28        | 1.18%   |
| AMD Ryzen 3            | 26        | 1.09%   |
| AMD GX                 | 24        | 1.01%   |
| Intel Xeon Silver      | 15        | 0.63%   |
| Intel Pentium 4        | 15        | 0.63%   |
| Intel Core 2 Quad      | 15        | 0.63%   |
| AMD Ryzen 7 PRO        | 15        | 0.63%   |
| Intel Core 2           | 14        | 0.59%   |
| AMD Ryzen 5 PRO        | 13        | 0.55%   |
| AMD EPYC               | 13        | 0.55%   |
| Intel Pentium M        | 12        | 0.5%    |
| Intel Core i9          | 12        | 0.5%    |
| AMD Opteron            | 12        | 0.5%    |
| AMD Ryzen Threadripper | 10        | 0.42%   |
| AMD Athlon 64 X2       | 8         | 0.34%   |
| AMD Athlon             | 8         | 0.34%   |
| Intel Pentium Silver   | 7         | 0.29%   |
| AMD Turion II Neo      | 7         | 0.29%   |
| AMD Phenom II X6       | 7         | 0.29%   |
| AMD E                  | 7         | 0.29%   |
| AMD A10                | 7         | 0.29%   |
| AMD Phenom II X4       | 6         | 0.25%   |
| AMD A8                 | 6         | 0.25%   |
| AMD A6                 | 6         | 0.25%   |
| Intel Xeon Gold        | 5         | 0.21%   |
| Intel Pentium Dual     | 5         | 0.21%   |
| Intel Genuine          | 5         | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 774       | 32.53%  |
| 2       | 641       | 26.94%  |
| Unknown | 231       | 9.71%   |
| 8       | 175       | 7.36%   |
| 16      | 154       | 6.47%   |
| 6       | 141       | 5.93%   |
| 12      | 100       | 4.2%    |
| 1       | 57        | 2.4%    |
| 24      | 31        | 1.3%    |
| 32      | 26        | 1.09%   |
| 10      | 19        | 0.8%    |
| 20      | 13        | 0.55%   |
| 64      | 5         | 0.21%   |
| 14      | 3         | 0.13%   |
| 48      | 2         | 0.08%   |
| 28      | 2         | 0.08%   |
| 3       | 2         | 0.08%   |
| 128     | 1         | 0.04%   |
| 40      | 1         | 0.04%   |
| 11      | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2133      | 89.92%  |
| 2       | 141       | 5.94%   |
| Unknown | 97        | 4.09%   |
| 4       | 1         | 0.04%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1186      | 49.96%  |
| 1       | 929       | 39.13%  |
| Unknown | 259       | 10.91%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 344       | 14.48%  |
| Haswell         | 194       | 8.17%   |
| Unknown         | 193       | 8.13%   |
| IvyBridge       | 192       | 8.08%   |
| SandyBridge     | 168       | 7.07%   |
| Skylake         | 152       | 6.4%    |
| Zen 2           | 111       | 4.67%   |
| Penryn          | 89        | 3.75%   |
| Broadwell       | 85        | 3.58%   |
| Westmere        | 75        | 3.16%   |
| Zen+            | 68        | 2.86%   |
| Zen 3           | 67        | 2.82%   |
| Core            | 67        | 2.82%   |
| Silvermont      | 59        | 2.48%   |
| CometLake       | 59        | 2.48%   |
| Zen             | 54        | 2.27%   |
| Bonnell         | 53        | 2.23%   |
| TigerLake       | 51        | 2.15%   |
| K10             | 37        | 1.56%   |
| Piledriver      | 34        | 1.43%   |
| Nehalem         | 31        | 1.31%   |
| Puma            | 27        | 1.14%   |
| NetBurst        | 24        | 1.01%   |
| Goldmont plus   | 24        | 1.01%   |
| P6              | 18        | 0.76%   |
| Goldmont        | 17        | 0.72%   |
| Excavator       | 16        | 0.67%   |
| Bobcat          | 16        | 0.67%   |
| K8 Hammer       | 15        | 0.63%   |
| Jaguar          | 13        | 0.55%   |
| IceLake         | 9         | 0.38%   |
| Bulldozer       | 4         | 0.17%   |
| Steamroller     | 3         | 0.13%   |
| K8 & K10 hybrid | 2         | 0.08%   |
| K10 Llano       | 2         | 0.08%   |
| Geode           | 2         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1207      | 48.26%  |
| Nvidia                                       | 568       | 22.71%  |
| AMD                                          | 491       | 19.63%  |
| Matrox Electronics Systems                   | 141       | 5.64%   |
| ASPEED Technology                            | 82        | 3.28%   |
| Silicon Integrated Systems [SiS]             | 3         | 0.12%   |
| XGI Technology (eXtreme Graphics Innovation) | 2         | 0.08%   |
| VIA Technologies                             | 2         | 0.08%   |
| S3 Graphics                                  | 2         | 0.08%   |
| Silicon Motion                               | 1         | 0.04%   |
| NVidia / SGS Thomson (Joint Venture)         | 1         | 0.04%   |
| Huawei Technologies                          | 1         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 102       | 3.96%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 82        | 3.18%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 76        | 2.95%   |
| Intel UHD Graphics 620                                                                   | 58        | 2.25%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 50        | 1.94%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 49        | 1.9%    |
| Intel HD Graphics 5500                                                                   | 49        | 1.9%    |
| Intel HD Graphics 620                                                                    | 47        | 1.82%   |
| Intel HD Graphics 530                                                                    | 45        | 1.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 44        | 1.71%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 44        | 1.71%   |
| AMD Renoir                                                                               | 43        | 1.67%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 41        | 1.59%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 38        | 1.47%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 37        | 1.43%   |
| Intel HD Graphics 630                                                                    | 36        | 1.4%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 35        | 1.36%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 35        | 1.36%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 33        | 1.28%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 32        | 1.24%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 31        | 1.2%    |
| Matrox Electronics Systems G200eR2                                                       | 30        | 1.16%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 30        | 1.16%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 29        | 1.12%   |
| Intel Core Processor Integrated Graphics Controller                                      | 28        | 1.09%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 27        | 1.05%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 26        | 1.01%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 26        | 1.01%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 26        | 1.01%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 24        | 0.93%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 23        | 0.89%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 22        | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 22        | 0.85%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 21        | 0.81%   |
| AMD ES1000                                                                               | 21        | 0.81%   |
| Matrox Electronics Systems MGA G200EH                                                    | 19        | 0.74%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 19        | 0.74%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 18        | 0.7%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 18        | 0.7%    |
| AMD Lucienne                                                                             | 18        | 0.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| 1 x Intel                                | 894       | 37.53%  |
| 1 x AMD                                  | 412       | 17.3%   |
| 1 x Nvidia                               | 358       | 15.03%  |
| Intel + Nvidia                           | 178       | 7.47%   |
| 1 x Matrox                               | 140       | 5.88%   |
| Other                                    | 129       | 5.42%   |
| 2 x Intel                                | 95        | 3.99%   |
| 1 x ASPEED                               | 72        | 3.02%   |
| Intel + AMD                              | 36        | 1.51%   |
| 2 x AMD                                  | 20        | 0.84%   |
| AMD + Nvidia                             | 18        | 0.76%   |
| Nvidia + ASPEED                          | 8         | 0.34%   |
| 2 x Nvidia                               | 5         | 0.21%   |
| 1 x SiS                                  | 3         | 0.13%   |
| 1 x XGI                                  | 2         | 0.08%   |
| 1 x VIA                                  | 2         | 0.08%   |
| 1 x S3 Graphics                          | 2         | 0.08%   |
| AMD + ASPEED                             | 2         | 0.08%   |
| 1 x Silicon Motion                       | 1         | 0.04%   |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1         | 0.04%   |
| Nvidia + Huawei Technologies             | 1         | 0.04%   |
| Intel + Matrox                           | 1         | 0.04%   |
| Intel + ASPEED                           | 1         | 0.04%   |
| Intel + AMD + 1 x Nvidia                 | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1872      | 78.42%  |
| Proprietary | 373       | 15.63%  |
| Unknown     | 142       | 5.95%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1819      | 75.54%  |
| 1.01-2.0   | 147       | 6.1%    |
| 0.01-0.5   | 124       | 5.15%   |
| 0.51-1.0   | 94        | 3.9%    |
| 3.01-4.0   | 84        | 3.49%   |
| 7.01-8.0   | 73        | 3.03%   |
| 5.01-6.0   | 36        | 1.5%    |
| 8.01-16.0  | 16        | 0.66%   |
| 2.01-3.0   | 14        | 0.58%   |
| 4.01-5.0   | 1         | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 169       | 11.78%  |
| Samsung Electronics     | 154       | 10.73%  |
| LG Display              | 143       | 9.97%   |
| Dell                    | 116       | 8.08%   |
| Chimei Innolux          | 92        | 6.41%   |
| BOE                     | 90        | 6.27%   |
| Goldstar                | 70        | 4.88%   |
| Lenovo                  | 51        | 3.55%   |
| Hewlett-Packard         | 49        | 3.41%   |
| Acer                    | 48        | 3.34%   |
| AOC                     | 40        | 2.79%   |
| Philips                 | 31        | 2.16%   |
| BenQ                    | 31        | 2.16%   |
| Sharp                   | 27        | 1.88%   |
| Apple                   | 27        | 1.88%   |
| Ancor Communications    | 26        | 1.81%   |
| Iiyama                  | 25        | 1.74%   |
| LG Electronics          | 20        | 1.39%   |
| ViewSonic               | 17        | 1.18%   |
| Sony                    | 12        | 0.84%   |
| InfoVision              | 12        | 0.84%   |
| Chi Mei Optoelectronics | 12        | 0.84%   |
| Eizo                    | 10        | 0.7%    |
| unknown                 | 9         | 0.63%   |
| NEC Computers           | 9         | 0.63%   |
| LGD                     | 8         | 0.56%   |
| ASUSTek Computer        | 8         | 0.56%   |
| Sceptre Tech            | 7         | 0.49%   |
| PANDA                   | 7         | 0.49%   |
| Idek Iiyama             | 7         | 0.49%   |
| Toshiba                 | 6         | 0.42%   |
| LG Philips              | 6         | 0.42%   |
| CSO                     | 6         | 0.42%   |
| Panasonic               | 5         | 0.35%   |
| JDI                     | 5         | 0.35%   |
| Unknown                 | 5         | 0.35%   |
| MSI                     | 4         | 0.28%   |
| Lenovo Group Limited    | 4         | 0.28%   |
| HannStar                | 4         | 0.28%   |
| CPT                     | 4         | 0.28%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch        | 10        | 0.67%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch          | 7         | 0.47%   |
| Iiyama PL2775HD IVM6604 1920x1080 600x340mm 27.2-inch                | 6         | 0.4%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch     | 6         | 0.4%    |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch     | 6         | 0.4%    |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch      | 6         | 0.4%    |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch           | 5         | 0.33%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch           | 5         | 0.33%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch           | 5         | 0.33%   |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                    | 5         | 0.33%   |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 340x190mm 15.3-inch       | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch        | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch        | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch       | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch       | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch       | 5         | 0.33%   |
| Unknown                                                              | 5         | 0.33%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch       | 4         | 0.27%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch | 4         | 0.27%   |
| MSI G241 MSI3BA4 1920x1080 530x300mm 24.0-inch                       | 4         | 0.27%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch         | 4         | 0.27%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch         | 4         | 0.27%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch          | 4         | 0.27%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch             | 4         | 0.27%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch              | 4         | 0.27%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch              | 4         | 0.27%   |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch              | 4         | 0.27%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch            | 4         | 0.27%   |
| Dell U2414H DELA0A2 1920x1080 530x300mm 24.0-inch                    | 4         | 0.27%   |
| Dell U2412M DELA07B 1920x1200 520x320mm 24.0-inch                    | 4         | 0.27%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 310x170mm 13.9-inch     | 4         | 0.27%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 280x160mm 12.7-inch     | 4         | 0.27%   |
| AOC 24G1WG4 AOC2401 1920x1080 520x290mm 23.4-inch                    | 4         | 0.27%   |
| ViewSonic VG2439 Series VSCD22B 1920x1080 520x290mm 23.4-inch        | 3         | 0.2%    |
| Sharp LCD Monitor SHP1449 1920x1080 290x170mm 13.2-inch              | 3         | 0.2%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch    | 3         | 0.2%    |
| Samsung Electronics S22B300 SAM08AC 1920x1080 480x270mm 21.7-inch    | 3         | 0.2%    |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch              | 3         | 0.2%    |
| Philips 271P4 PHL08C3 1920x1080 600x340mm 27.2-inch                  | 3         | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 606       | 42.98%  |
| 1366x768 (WXGA)    | 205       | 14.54%  |
| 3840x2160 (4K)     | 96        | 6.81%   |
| 2560x1440 (QHD)    | 85        | 6.03%   |
| 1920x1200 (WUXGA)  | 64        | 4.54%   |
| 1600x900 (HD+)     | 60        | 4.26%   |
| 1280x1024 (SXGA)   | 46        | 3.26%   |
| 1280x800 (WXGA)    | 35        | 2.48%   |
| 1680x1050 (WSXGA+) | 25        | 1.77%   |
| Unknown            | 24        | 1.7%    |
| 1440x900 (WXGA+)   | 22        | 1.56%   |
| 2560x1080          | 17        | 1.21%   |
| 1024x600           | 17        | 1.21%   |
| 3440x1440          | 16        | 1.13%   |
| 2560x1600          | 10        | 0.71%   |
| 1024x768 (XGA)     | 8         | 0.57%   |
| 3840x1080          | 6         | 0.43%   |
| 2256x1504          | 6         | 0.43%   |
| 3200x1800 (QHD+)   | 5         | 0.35%   |
| 1600x1200          | 5         | 0.35%   |
| 1920x540           | 4         | 0.28%   |
| 3840x1200          | 3         | 0.21%   |
| 3000x2000          | 3         | 0.21%   |
| 2880x1620          | 3         | 0.21%   |
| 2160x1440          | 3         | 0.21%   |
| 1360x768           | 3         | 0.21%   |
| 5760x1080          | 2         | 0.14%   |
| 2880x1800          | 2         | 0.14%   |
| 1400x1050          | 2         | 0.14%   |
| 1280x720 (HD)      | 2         | 0.14%   |
| 7680x2160          | 1         | 0.07%   |
| 5760x2160          | 1         | 0.07%   |
| 5760x1256          | 1         | 0.07%   |
| 5760x1200          | 1         | 0.07%   |
| 5440x1080          | 1         | 0.07%   |
| 4480x1440          | 1         | 0.07%   |
| 4480x1080          | 1         | 0.07%   |
| 3840x1600          | 1         | 0.07%   |
| 3640x1920          | 1         | 0.07%   |
| 3600x1080          | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 274       | 19.15%  |
| 15      | 242       | 16.91%  |
| Unknown | 145       | 10.13%  |
| 27      | 122       | 8.53%   |
| 24      | 121       | 8.46%   |
| 21      | 75        | 5.24%   |
| 23      | 70        | 4.89%   |
| 12      | 66        | 4.61%   |
| 17      | 47        | 3.28%   |
| 19      | 42        | 2.94%   |
| 14      | 31        | 2.17%   |
| 31      | 27        | 1.89%   |
| 11      | 22        | 1.54%   |
| 34      | 20        | 1.4%    |
| 22      | 18        | 1.26%   |
| 18      | 16        | 1.12%   |
| 10      | 14        | 0.98%   |
| 20      | 10        | 0.7%    |
| 29      | 7         | 0.49%   |
| 26      | 5         | 0.35%   |
| 25      | 5         | 0.35%   |
| 64      | 4         | 0.28%   |
| 46      | 4         | 0.28%   |
| 42      | 4         | 0.28%   |
| 32      | 4         | 0.28%   |
| 9       | 4         | 0.28%   |
| 52      | 3         | 0.21%   |
| 43      | 3         | 0.21%   |
| 40      | 3         | 0.21%   |
| 16      | 3         | 0.21%   |
| 54      | 2         | 0.14%   |
| 49      | 2         | 0.14%   |
| 48      | 2         | 0.14%   |
| 41      | 2         | 0.14%   |
| 39      | 2         | 0.14%   |
| 74      | 1         | 0.07%   |
| 57      | 1         | 0.07%   |
| 55      | 1         | 0.07%   |
| 47      | 1         | 0.07%   |
| 37      | 1         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 468       | 33.14%  |
| 501-600     | 298       | 21.1%   |
| 201-300     | 204       | 14.45%  |
| Unknown     | 145       | 10.27%  |
| 401-500     | 135       | 9.56%   |
| 351-400     | 50        | 3.54%   |
| 601-700     | 46        | 3.26%   |
| 701-800     | 25        | 1.77%   |
| 1001-1500   | 20        | 1.42%   |
| 901-1000    | 10        | 0.71%   |
| 801-900     | 6         | 0.42%   |
| 101-200     | 3         | 0.21%   |
| 1501-2000   | 1         | 0.07%   |
| 1-100       | 1         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 931       | 70.37%  |
| 16/10   | 136       | 10.28%  |
| Unknown | 136       | 10.28%  |
| 5/4     | 37        | 2.8%    |
| 21/9    | 29        | 2.19%   |
| 3/2     | 24        | 1.81%   |
| 4/3     | 20        | 1.51%   |
| 6/5     | 3         | 0.23%   |
| 32/9    | 2         | 0.15%   |
| 3.18    | 1         | 0.08%   |
| 11/10   | 1         | 0.08%   |
| 1.96    | 1         | 0.08%   |
| 1.00    | 1         | 0.08%   |
| 0.46    | 1         | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 249       | 17.52%  |
| 201-250        | 231       | 16.26%  |
| 91-100         | 185       | 13.02%  |
| Unknown        | 145       | 10.2%   |
| 301-350        | 129       | 9.08%   |
| 61-70          | 66        | 4.64%   |
| 101-110        | 61        | 4.29%   |
| 151-200        | 57        | 4.01%   |
| 351-500        | 56        | 3.94%   |
| 251-300        | 49        | 3.45%   |
| 71-80          | 44        | 3.1%    |
| 141-150        | 31        | 2.18%   |
| 121-130        | 30        | 2.11%   |
| 51-60          | 22        | 1.55%   |
| 501-1000       | 22        | 1.55%   |
| 41-50          | 15        | 1.06%   |
| More than 1000 | 14        | 0.99%   |
| 111-120        | 8         | 0.56%   |
| 1-40           | 4         | 0.28%   |
| 131-140        | 3         | 0.21%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 409       | 29.36%  |
| 121-160       | 377       | 27.06%  |
| 101-120       | 302       | 21.68%  |
| Unknown       | 145       | 10.41%  |
| 161-240       | 117       | 8.4%    |
| More than 240 | 32        | 2.3%    |
| 1-50          | 11        | 0.79%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1171      | 48.41%  |
| 0     | 1054      | 43.57%  |
| 2     | 178       | 7.36%   |
| 3     | 15        | 0.62%   |
| 4     | 1         | 0.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1427      | 44%     |
| Realtek Semiconductor             | 905       | 27.91%  |
| Qualcomm Atheros                  | 264       | 8.14%   |
| Broadcom                          | 257       | 7.92%   |
| Marvell Technology Group          | 36        | 1.11%   |
| Ralink Technology                 | 31        | 0.96%   |
| TP-Link                           | 30        | 0.93%   |
| Mellanox Technologies             | 18        | 0.56%   |
| Ralink                            | 17        | 0.52%   |
| MediaTek                          | 15        | 0.46%   |
| Nvidia                            | 14        | 0.43%   |
| Edimax Technology                 | 14        | 0.43%   |
| Xiaomi                            | 11        | 0.34%   |
| Samsung Electronics               | 11        | 0.34%   |
| Sierra Wireless                   | 10        | 0.31%   |
| D-Link System                     | 10        | 0.31%   |
| VIA Technologies                  | 9         | 0.28%   |
| Hewlett-Packard                   | 9         | 0.28%   |
| Aquantia                          | 9         | 0.28%   |
| Ericsson Business Mobile Networks | 8         | 0.25%   |
| Dell                              | 7         | 0.22%   |
| IBM                               | 6         | 0.19%   |
| Huawei Technologies               | 6         | 0.19%   |
| Google                            | 6         | 0.19%   |
| Chelsio Communications            | 6         | 0.19%   |
| American Megatrends               | 6         | 0.19%   |
| D-Link                            | 5         | 0.15%   |
| Arduino SA                        | 5         | 0.15%   |
| Apple                             | 5         | 0.15%   |
| Silicon Integrated Systems [SiS]  | 4         | 0.12%   |
| Qualcomm                          | 4         | 0.12%   |
| NetGear                           | 4         | 0.12%   |
| Emulex                            | 4         | 0.12%   |
| 3Com                              | 4         | 0.12%   |
| IMC Networks                      | 3         | 0.09%   |
| Dresden Elektronik                | 3         | 0.09%   |
| Cisco Systems                     | 3         | 0.09%   |
| AMD                               | 3         | 0.09%   |
| Solarflare Communications         | 2         | 0.06%   |
| Qualcomm Atheros Communications   | 2         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 666       | 16.65%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 139       | 3.47%   |
| Intel I211 Gigabit Network Connection                                         | 104       | 2.6%    |
| Intel Wireless 8265 / 8275                                                    | 97        | 2.42%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 92        | 2.3%    |
| Intel Wi-Fi 6 AX200                                                           | 89        | 2.22%   |
| Intel I210 Gigabit Network Connection                                         | 78        | 1.95%   |
| Intel 82574L Gigabit Network Connection                                       | 66        | 1.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 63        | 1.57%   |
| Intel Wireless 8260                                                           | 58        | 1.45%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 58        | 1.45%   |
| Intel Wireless 7265                                                           | 57        | 1.42%   |
| Intel I350 Gigabit Network Connection                                         | 52        | 1.3%    |
| Realtek RTL8125 2.5GbE Controller                                             | 48        | 1.2%    |
| Intel Ethernet Connection I217-LM                                             | 45        | 1.12%   |
| Intel Wireless 7260                                                           | 42        | 1.05%   |
| Intel Wi-Fi 6 AX201                                                           | 41        | 1.02%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 39        | 0.97%   |
| Intel Wireless-AC 9260                                                        | 38        | 0.95%   |
| Intel Ethernet Connection (2) I219-LM                                         | 37        | 0.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 33        | 0.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 33        | 0.82%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 32        | 0.8%    |
| Intel Ethernet Connection (4) I219-LM                                         | 31        | 0.77%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 30        | 0.75%   |
| Intel Ethernet Connection (4) I219-V                                          | 28        | 0.7%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 28        | 0.7%    |
| Intel Ethernet Connection I219-LM                                             | 26        | 0.65%   |
| Intel Ethernet Connection (2) I219-V                                          | 26        | 0.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 26        | 0.65%   |
| Intel 82579V Gigabit Network Connection                                       | 26        | 0.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 25        | 0.62%   |
| Intel Ethernet Controller I225-V                                              | 25        | 0.62%   |
| Intel Ethernet Connection (7) I219-V                                          | 25        | 0.62%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 24        | 0.6%    |
| Intel Ethernet Connection (3) I218-LM                                         | 24        | 0.6%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 23        | 0.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 22        | 0.55%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 22        | 0.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 21        | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 838       | 57.71%  |
| Qualcomm Atheros                      | 216       | 14.88%  |
| Realtek Semiconductor                 | 159       | 10.95%  |
| Broadcom                              | 93        | 6.4%    |
| Ralink Technology                     | 31        | 2.13%   |
| TP-Link                               | 30        | 2.07%   |
| Ralink                                | 17        | 1.17%   |
| MediaTek                              | 14        | 0.96%   |
| Edimax Technology                     | 14        | 0.96%   |
| Sierra Wireless                       | 7         | 0.48%   |
| D-Link                                | 5         | 0.34%   |
| NetGear                               | 4         | 0.28%   |
| D-Link System                         | 4         | 0.28%   |
| IMC Networks                          | 3         | 0.21%   |
| Dell                                  | 3         | 0.21%   |
| Qualcomm Atheros Communications       | 2         | 0.14%   |
| Atheros                               | 2         | 0.14%   |
| ASUSTek Computer                      | 2         | 0.14%   |
| AboCom Systems                        | 2         | 0.14%   |
| Sagem                                 | 1         | 0.07%   |
| Qualcomm Technologies                 | 1         | 0.07%   |
| Marvell Technology Group              | 1         | 0.07%   |
| Linksys                               | 1         | 0.07%   |
| BUFFALO                               | 1         | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 97        | 6.63%   |
| Intel Wi-Fi 6 AX200                                                     | 89        | 6.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 63        | 4.31%   |
| Intel Wireless 8260                                                     | 58        | 3.96%   |
| Intel Wireless 7265                                                     | 57        | 3.9%    |
| Intel Wireless 7260                                                     | 42        | 2.87%   |
| Intel Wi-Fi 6 AX201                                                     | 41        | 2.8%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 39        | 2.67%   |
| Intel Wireless-AC 9260                                                  | 38        | 2.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 33        | 2.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 33        | 2.26%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 32        | 2.19%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 30        | 2.05%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 28        | 1.91%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 26        | 1.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 25        | 1.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 24        | 1.64%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 22        | 1.5%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 22        | 1.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 21        | 1.44%   |
| Intel Wireless 3165                                                     | 21        | 1.44%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 20        | 1.37%   |
| Intel Centrino Ultimate-N 6300                                          | 20        | 1.37%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 19        | 1.3%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 16        | 1.09%   |
| Ralink RT5370 Wireless Adapter                                          | 15        | 1.03%   |
| Intel Wireless 3160                                                     | 15        | 1.03%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 15        | 1.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 14        | 0.96%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 12        | 0.82%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 12        | 0.82%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 12        | 0.82%   |
| Intel Centrino Advanced-N 6235                                          | 12        | 0.82%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 12        | 0.82%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 11        | 0.75%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 11        | 0.75%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 11        | 0.75%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 11        | 0.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 10        | 0.68%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 10        | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 1016      | 44.76%  |
| Realtek Semiconductor                  | 824       | 36.3%   |
| Broadcom                               | 190       | 8.37%   |
| Qualcomm Atheros                       | 75        | 3.3%    |
| Marvell Technology Group               | 35        | 1.54%   |
| Nvidia                                 | 14        | 0.62%   |
| Xiaomi                                 | 11        | 0.48%   |
| Samsung Electronics                    | 11        | 0.48%   |
| VIA Technologies                       | 9         | 0.4%    |
| Aquantia                               | 9         | 0.4%    |
| D-Link System                          | 6         | 0.26%   |
| Chelsio Communications                 | 6         | 0.26%   |
| American Megatrends                    | 6         | 0.26%   |
| Google                                 | 5         | 0.22%   |
| Qualcomm                               | 4         | 0.18%   |
| Emulex                                 | 4         | 0.18%   |
| Apple                                  | 4         | 0.18%   |
| 3Com                                   | 4         | 0.18%   |
| Silicon Integrated Systems [SiS]       | 3         | 0.13%   |
| Cisco Systems                          | 3         | 0.13%   |
| AMD                                    | 3         | 0.13%   |
| Solarflare Communications              | 2         | 0.09%   |
| QLogic                                 | 2         | 0.09%   |
| MYRICOM                                | 2         | 0.09%   |
| Lenovo                                 | 2         | 0.09%   |
| JMicron Technology                     | 2         | 0.09%   |
| Huawei Technologies                    | 2         | 0.09%   |
| ADMtek                                 | 2         | 0.09%   |
| U.S. Robotics                          | 1         | 0.04%   |
| Tehuti Networks                        | 1         | 0.04%   |
| Sundance Technology Inc / IC Plus      | 1         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.04%   |
| Realtek                                | 1         | 0.04%   |
| OPPO Electronics                       | 1         | 0.04%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.04%   |
| National Semiconductor                 | 1         | 0.04%   |
| MediaTek                               | 1         | 0.04%   |
| Insyde Software                        | 1         | 0.04%   |
| HMD Global                             | 1         | 0.04%   |
| Davicom Semiconductor                  | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 666       | 27.37%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 139       | 5.71%   |
| Intel I211 Gigabit Network Connection                                         | 104       | 4.27%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 92        | 3.78%   |
| Intel I210 Gigabit Network Connection                                         | 78        | 3.21%   |
| Intel 82574L Gigabit Network Connection                                       | 66        | 2.71%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 58        | 2.38%   |
| Intel I350 Gigabit Network Connection                                         | 52        | 2.14%   |
| Intel Ethernet Connection I217-LM                                             | 45        | 1.85%   |
| Realtek RTL8125 2.5GbE Controller                                             | 42        | 1.73%   |
| Intel Ethernet Connection (2) I219-LM                                         | 37        | 1.52%   |
| Intel Ethernet Connection (4) I219-LM                                         | 31        | 1.27%   |
| Intel Ethernet Connection (4) I219-V                                          | 28        | 1.15%   |
| Intel Ethernet Connection I219-LM                                             | 26        | 1.07%   |
| Intel Ethernet Connection (2) I219-V                                          | 26        | 1.07%   |
| Intel 82579V Gigabit Network Connection                                       | 26        | 1.07%   |
| Intel Ethernet Controller I225-V                                              | 25        | 1.03%   |
| Intel Ethernet Connection (7) I219-V                                          | 25        | 1.03%   |
| Intel Ethernet Connection (3) I218-LM                                         | 24        | 0.99%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 23        | 0.95%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 21        | 0.86%   |
| Intel 82576 Gigabit Network Connection                                        | 18        | 0.74%   |
| Intel Ethernet Connection (7) I219-LM                                         | 16        | 0.66%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 16        | 0.66%   |
| Intel Ethernet Connection I218-LM                                             | 15        | 0.62%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 13        | 0.53%   |
| Intel Ethernet Connection I219-V                                              | 13        | 0.53%   |
| Intel 82577LM Gigabit Network Connection                                      | 13        | 0.53%   |
| Nvidia MCP79 Ethernet                                                         | 12        | 0.49%   |
| Intel Ethernet Controller X550                                                | 12        | 0.49%   |
| Intel Ethernet Connection (2) I218-V                                          | 12        | 0.49%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 12        | 0.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 11        | 0.45%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 11        | 0.45%   |
| Intel Ethernet Connection (6) I219-V                                          | 11        | 0.45%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 11        | 0.45%   |
| Intel Ethernet Connection (10) I219-V                                         | 10        | 0.41%   |
| Intel 82567LM Gigabit Network Connection                                      | 10        | 0.41%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)                        | 10        | 0.41%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                             | 10        | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2084      | 59.29%  |
| WiFi     | 1326      | 37.72%  |
| Unknown  | 55        | 1.56%   |
| Modem    | 50        | 1.42%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1819      | 67.62%  |
| WiFi     | 856       | 31.82%  |
| Unknown  | 10        | 0.37%   |
| Modem    | 5         | 0.19%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1235      | 51.78%  |
| 1     | 743       | 31.15%  |
| 3     | 134       | 5.62%   |
| 4     | 114       | 4.78%   |
| 0     | 95        | 3.98%   |
| 6     | 28        | 1.17%   |
| 5     | 21        | 0.88%   |
| 8     | 6         | 0.25%   |
| 7     | 5         | 0.21%   |
| 10    | 3         | 0.13%   |
| 9     | 1         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2154      | 89.3%   |
| Yes  | 258       | 10.7%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 590       | 60.64%  |
| Broadcom                        | 66        | 6.78%   |
| Qualcomm Atheros Communications | 56        | 5.76%   |
| Realtek Semiconductor           | 51        | 5.24%   |
| Apple                           | 44        | 4.52%   |
| Cambridge Silicon Radio         | 33        | 3.39%   |
| IMC Networks                    | 23        | 2.36%   |
| Foxconn / Hon Hai               | 22        | 2.26%   |
| Lite-On Technology              | 20        | 2.06%   |
| ASUSTek Computer                | 18        | 1.85%   |
| Dell                            | 14        | 1.44%   |
| Hewlett-Packard                 | 12        | 1.23%   |
| Skylight Digital                | 5         | 0.51%   |
| MediaTek                        | 4         | 0.41%   |
| Alps Electric                   | 4         | 0.41%   |
| TP-Link                         | 2         | 0.21%   |
| Ralink                          | 2         | 0.21%   |
| Toshiba                         | 1         | 0.1%    |
| Ralink Technology               | 1         | 0.1%    |
| Opticis                         | 1         | 0.1%    |
| Micro Star International        | 1         | 0.1%    |
| Esel International              | 1         | 0.1%    |
| Creative Technology             | 1         | 0.1%    |
| Corsair                         | 1         | 0.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 222       | 22.75%  |
| Intel AX201 Bluetooth                                       | 93        | 9.53%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 86        | 8.81%   |
| Intel AX200 Bluetooth                                       | 86        | 8.81%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 34        | 3.48%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 33        | 3.38%   |
| Intel Wireless-AC 3168 Bluetooth                            | 25        | 2.56%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 23        | 2.36%   |
| Apple Bluetooth Host Controller                             | 22        | 2.25%   |
| Realtek Bluetooth Adapter                                   | 21        | 2.15%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 21        | 2.15%   |
| Intel AX210 Bluetooth                                       | 17        | 1.74%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 14        | 1.43%   |
| Realtek  Bluetooth 4.2 Adapter                              | 12        | 1.23%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 12        | 1.23%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 10        | 1.02%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 10        | 1.02%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 8         | 0.82%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 8         | 0.82%   |
| Intel Wireless Bluetooth                                    | 8         | 0.82%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 8         | 0.82%   |
| IMC Networks Realtek Bluetooth Adapter                      | 8         | 0.82%   |
| Lite-On Atheros AR3012 Bluetooth                            | 7         | 0.72%   |
| Dell DW375 Bluetooth Module                                 | 7         | 0.72%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 7         | 0.72%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 6         | 0.61%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 6         | 0.61%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 6         | 0.61%   |
| Apple Built-in iSight (no firmware loaded)                  | 6         | 0.61%   |
| Skylight Digital Realtek Bluetooth Adapter                  | 5         | 0.51%   |
| Realtek Bluetooth 4.2 Adapter                               | 5         | 0.51%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 5         | 0.51%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 5         | 0.51%   |
| Realtek Bluetooth 4.0 Adapter                               | 4         | 0.41%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 4         | 0.41%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter                  | 4         | 0.41%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 4         | 0.41%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 3         | 0.31%   |
| Realtek RTL8723B Bluetooth                                  | 3         | 0.31%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 3         | 0.31%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1406      | 54.86%  |
| AMD                                          | 520       | 20.29%  |
| Nvidia                                       | 412       | 16.07%  |
| C-Media Electronics                          | 28        | 1.09%   |
| Logitech                                     | 20        | 0.78%   |
| Creative Labs                                | 16        | 0.62%   |
| Texas Instruments                            | 13        | 0.51%   |
| Lenovo                                       | 13        | 0.51%   |
| Realtek Semiconductor                        | 11        | 0.43%   |
| GN Netcom                                    | 7         | 0.27%   |
| ASUSTek Computer                             | 7         | 0.27%   |
| Silicon Integrated Systems [SiS]             | 6         | 0.23%   |
| Kingston Technology                          | 6         | 0.23%   |
| JMTek                                        | 6         | 0.23%   |
| SteelSeries ApS                              | 5         | 0.2%    |
| Plantronics                                  | 5         | 0.2%    |
| Generalplus Technology                       | 5         | 0.2%    |
| BEHRINGER International                      | 5         | 0.2%    |
| Sony                                         | 4         | 0.16%   |
| Focusrite-Novation                           | 4         | 0.16%   |
| Creative Technology                          | 4         | 0.16%   |
| Blue Microphones                             | 4         | 0.16%   |
| Thesycon Systemsoftware & Consulting         | 3         | 0.12%   |
| Tenx Technology                              | 3         | 0.12%   |
| M-Audio                                      | 3         | 0.12%   |
| Yamaha                                       | 2         | 0.08%   |
| VIA Technologies                             | 2         | 0.08%   |
| Trust                                        | 2         | 0.08%   |
| Samsung Electronics                          | 2         | 0.08%   |
| Microsoft                                    | 2         | 0.08%   |
| Micro Star International                     | 2         | 0.08%   |
| FiiO Electronics Technology                  | 2         | 0.08%   |
| Corsair                                      | 2         | 0.08%   |
| CMX Systems                                  | 2         | 0.08%   |
| Cambridge Silicon Radio                      | 2         | 0.08%   |
| Apple                                        | 2         | 0.08%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.04%   |
| XMOS                                         | 1         | 0.04%   |
| Xilinx                                       | 1         | 0.04%   |
| ULi Electronics                              | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 170       | 5.62%   |
| AMD Family 17h/19h HD Audio Controller                                     | 160       | 5.29%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 139       | 4.59%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 127       | 4.2%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 93        | 3.07%   |
| AMD Starship/Matisse HD Audio Controller                                   | 87        | 2.87%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 81        | 2.68%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 73        | 2.41%   |
| Intel Cannon Lake PCH cAVS                                                 | 70        | 2.31%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 65        | 2.15%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 62        | 2.05%   |
| Intel Broadwell-U Audio Controller                                         | 58        | 1.92%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 57        | 1.88%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 54        | 1.78%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 53        | 1.75%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 51        | 1.68%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 50        | 1.65%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 46        | 1.52%   |
| Intel Haswell-ULT HD Audio Controller                                      | 45        | 1.49%   |
| Intel 8 Series HD Audio Controller                                         | 45        | 1.49%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 44        | 1.45%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 40        | 1.32%   |
| Intel Comet Lake PCH-LP cAVS                                               | 39        | 1.29%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 39        | 1.29%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 38        | 1.26%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 35        | 1.16%   |
| Intel Comet Lake PCH cAVS                                                  | 35        | 1.16%   |
| AMD FCH Azalia Controller                                                  | 34        | 1.12%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 33        | 1.09%   |
| Intel 200 Series PCH HD Audio                                              | 33        | 1.09%   |
| AMD Kabini HDMI/DP Audio                                                   | 29        | 0.96%   |
| Nvidia TU116 High Definition Audio Controller                              | 28        | 0.93%   |
| Nvidia GP107GL High Definition Audio Controller                            | 28        | 0.93%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 25        | 0.83%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 24        | 0.79%   |
| Nvidia GP108 High Definition Audio Controller                              | 23        | 0.76%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 23        | 0.76%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 23        | 0.76%   |
| Nvidia High Definition Audio Controller                                    | 21        | 0.69%   |
| Nvidia GF119 HDMI Audio Controller                                         | 20        | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 546       | 21.06%  |
| SK hynix                     | 424       | 16.35%  |
| Kingston                     | 323       | 12.46%  |
| Unknown                      | 273       | 10.53%  |
| Micron Technology            | 245       | 9.45%   |
| Crucial                      | 161       | 6.21%   |
| Corsair                      | 154       | 5.94%   |
| G.Skill                      | 77        | 2.97%   |
| Unknown                      | 50        | 1.93%   |
| Ramaxel Technology           | 40        | 1.54%   |
| A-DATA Technology            | 38        | 1.47%   |
| Elpida                       | 24        | 0.93%   |
| Nanya Technology             | 23        | 0.89%   |
| Team                         | 18        | 0.69%   |
| Transcend                    | 17        | 0.66%   |
| Goodram                      | 16        | 0.62%   |
| Patriot                      | 15        | 0.58%   |
| Hewlett-Packard              | 13        | 0.5%    |
| Unknown (ABCD)               | 10        | 0.39%   |
| Avant                        | 9         | 0.35%   |
| Smart                        | 7         | 0.27%   |
| Super Talent                 | 6         | 0.23%   |
| PNY                          | 6         | 0.23%   |
| Patriot Memory (PDP Systems) | 6         | 0.23%   |
| Goldkey                      | 6         | 0.23%   |
| Neo Forza                    | 5         | 0.19%   |
| AMD                          | 5         | 0.19%   |
| Qimonda                      | 4         | 0.15%   |
| HPE                          | 4         | 0.15%   |
| Apacer                       | 4         | 0.15%   |
| 48spaces                     | 4         | 0.15%   |
| Golden Empire                | 3         | 0.12%   |
| V-GeN                        | 2         | 0.08%   |
| V-Color                      | 2         | 0.08%   |
| Toshiba                      | 2         | 0.08%   |
| Tigo                         | 2         | 0.08%   |
| Silicon Power                | 2         | 0.08%   |
| PUSKILL                      | 2         | 0.08%   |
| Magnum Tech                  | 2         | 0.08%   |
| KomputerBay                  | 2         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown                                                      | 50        | 1.76%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 21        | 0.74%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 21        | 0.74%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 18        | 0.64%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s       | 18        | 0.64%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 17        | 0.6%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s        | 17        | 0.6%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 16        | 0.56%   |
| Samsung RAM M393B1G70QH0-YK0 8192MB DIMM DDR3 1600MT/s       | 15        | 0.53%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 13        | 0.46%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s        | 13        | 0.46%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 13        | 0.46%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s        | 13        | 0.46%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s        | 12        | 0.42%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s      | 11        | 0.39%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 11        | 0.39%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 11        | 0.39%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 10        | 0.35%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 10        | 0.35%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 10        | 0.35%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s        | 10        | 0.35%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 10        | 0.35%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 9         | 0.32%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s        | 9         | 0.32%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s        | 9         | 0.32%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 8         | 0.28%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s        | 8         | 0.28%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s       | 8         | 0.28%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 8         | 0.28%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s        | 8         | 0.28%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                    | 7         | 0.25%   |
| Unknown RAM Module 2GB SODIMM DDR2                           | 7         | 0.25%   |
| SK hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s         | 7         | 0.25%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 7         | 0.25%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s       | 7         | 0.25%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s | 7         | 0.25%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s            | 7         | 0.25%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s      | 7         | 0.25%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                         | 6         | 0.21%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                 | 6         | 0.21%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind         | Computers | Percent |
|--------------|-----------|---------|
| DDR4         | 959       | 42.62%  |
| DDR3         | 870       | 38.67%  |
| DDR2         | 146       | 6.49%   |
| Unknown      | 71        | 3.16%   |
| LPDDR3       | 52        | 2.31%   |
| LPDDR4       | 44        | 1.96%   |
| SDRAM        | 41        | 1.82%   |
| DDR          | 34        | 1.51%   |
| DDR5         | 15        | 0.67%   |
| LPDDR5       | 8         | 0.36%   |
| DRAM         | 7         | 0.31%   |
| SRAM         | 1         | 0.04%   |
| RAM          | 1         | 0.04%   |
| DDR2 FB-DIMM | 1         | 0.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1057      | 46.92%  |
| DIMM         | 1049      | 46.56%  |
| Row Of Chips | 96        | 4.26%   |
| Chip         | 30        | 1.33%   |
| Unknown      | 8         | 0.36%   |
| FB-DIMM      | 7         | 0.31%   |
| RIMM         | 6         | 0.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 868       | 35.2%   |
| 4096   | 627       | 25.43%  |
| 16384  | 411       | 16.67%  |
| 2048   | 311       | 12.61%  |
| 32768  | 115       | 4.66%   |
| 1024   | 94        | 3.81%   |
| 512    | 24        | 0.97%   |
| 256    | 5         | 0.2%    |
| 65536  | 3         | 0.12%   |
| 128    | 2         | 0.08%   |
| 131072 | 1         | 0.04%   |
| 3072   | 1         | 0.04%   |
| 2560   | 1         | 0.04%   |
| 64     | 1         | 0.04%   |
| 32     | 1         | 0.04%   |
| 8      | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 521       | 21.72%  |
| 3200    | 293       | 12.21%  |
| 1333    | 273       | 11.38%  |
| 2400    | 245       | 10.21%  |
| 2667    | 230       | 9.59%   |
| 2133    | 196       | 8.17%   |
| 667     | 85        | 3.54%   |
| 800     | 77        | 3.21%   |
| Unknown | 60        | 2.5%    |
| 1334    | 53        | 2.21%   |
| 1867    | 47        | 1.96%   |
| 2666    | 40        | 1.67%   |
| 1067    | 35        | 1.46%   |
| 1066    | 28        | 1.17%   |
| 4267    | 26        | 1.08%   |
| 533     | 26        | 1.08%   |
| 2933    | 23        | 0.96%   |
| 3000    | 21        | 0.88%   |
| 3600    | 20        | 0.83%   |
| 1866    | 16        | 0.67%   |
| 4800    | 13        | 0.54%   |
| 400     | 8         | 0.33%   |
| 6400    | 7         | 0.29%   |
| 975     | 6         | 0.25%   |
| 266     | 6         | 0.25%   |
| 4266    | 5         | 0.21%   |
| 2048    | 5         | 0.21%   |
| 3400    | 4         | 0.17%   |
| 4000    | 3         | 0.13%   |
| 1639    | 3         | 0.13%   |
| 333     | 3         | 0.13%   |
| 5200    | 2         | 0.08%   |
| 3534    | 2         | 0.08%   |
| 1332    | 2         | 0.08%   |
| 65535   | 1         | 0.04%   |
| 4133    | 1         | 0.04%   |
| 3500    | 1         | 0.04%   |
| 3066    | 1         | 0.04%   |
| 2800    | 1         | 0.04%   |
| 2134    | 1         | 0.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart_bsd/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 4         | 26.67%  |
| Prolific Technology | 2         | 13.33%  |
| Hewlett-Packard     | 2         | 13.33%  |
| ELGIN               | 2         | 13.33%  |
| Seiko Epson         | 1         | 6.67%   |
| Samsung Electronics | 1         | 6.67%   |
| QinHeng Electronics | 1         | 6.67%   |
| Dymo-CoStar         | 1         | 6.67%   |
| Canon               | 1         | 6.67%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart_bsd/printer_model.svg)


| Model                                                                                      | Computers | Percent |
|--------------------------------------------------------------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port                                                              | 2         | 13.33%  |
| ELGIN L42PRO                                                                               | 2         | 13.33%  |
| Seiko Epson Printer                                                                        | 1         | 6.67%   |
| Samsung ML-1610 Mono Laser Printer                                                         | 1         | 6.67%   |
| QinHeng CH340S                                                                             | 1         | 6.67%   |
| HP LaserJet 1012                                                                           | 1         | 6.67%   |
| HP HP LaserJet M14-M17 Printer HP LEDM IPP Printer HP LEDM IPP Printer HP LEDM IPP Printer | 1         | 6.67%   |
| Dymo-CoStar LabelWriter 450                                                                | 1         | 6.67%   |
| Canon LBP2900                                                                              | 1         | 6.67%   |
| Brother MFC-7360N                                                                          | 1         | 6.67%   |
| Brother HL-L5200DW series                                                                  | 1         | 6.67%   |
| Brother HL-2030 Laser Printer                                                              | 1         | 6.67%   |
| Brother HL-1430 Laser Printer                                                              | 1         | 6.67%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart_bsd/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 5         | 71.43%  |
| Seiko Epson     | 1         | 14.29%  |
| Hewlett-Packard | 1         | 14.29%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart_bsd/scanner_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                             | 2         | 28.57%  |
| Seiko Epson WF-2850 Series EPSON Scanner USB2.0 Printer EPSON Utility USB2.0 Faxout | 1         | 14.29%  |
| HP ScanJet 5300c/5370c                                                              | 1         | 14.29%  |
| Canon CanoScan LIDE 25                                                              | 1         | 14.29%  |
| Canon CanoScan LiDE 220                                                             | 1         | 14.29%  |
| Canon CanoScan LiDE 120                                                             | 1         | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 248       | 28.57%  |
| IMC Networks                           | 93        | 10.71%  |
| Microdia                               | 82        | 9.45%   |
| Bison Electronics                      | 80        | 9.22%   |
| Realtek Semiconductor                  | 65        | 7.49%   |
| Sunplus Innovation Technology          | 51        | 5.88%   |
| Logitech                               | 47        | 5.41%   |
| Lite-On Technology                     | 25        | 2.88%   |
| Suyin                                  | 24        | 2.76%   |
| Cheng Uei Precision Industry (Foxlink) | 17        | 1.96%   |
| Syntek                                 | 16        | 1.84%   |
| Quanta                                 | 14        | 1.61%   |
| Apple                                  | 13        | 1.5%    |
| Silicon Motion                         | 10        | 1.15%   |
| Luxvisions Innotech Limited            | 10        | 1.15%   |
| Lenovo                                 | 8         | 0.92%   |
| Z-Star Microelectronics                | 7         | 0.81%   |
| Shenzhen Kingcome Optoelectronic       | 5         | 0.58%   |
| ALi                                    | 5         | 0.58%   |
| Importek                               | 4         | 0.46%   |
| Alcor Micro                            | 4         | 0.46%   |
| Supreme Electronics                    | 3         | 0.35%   |
| Ricoh                                  | 3         | 0.35%   |
| ARC International                      | 3         | 0.35%   |
| WCM_USB                                | 2         | 0.23%   |
| Trust                                  | 2         | 0.23%   |
| SHENZHEN EMEET TECHNOLOGY              | 2         | 0.23%   |
| Primax Electronics                     | 2         | 0.23%   |
| Pixart Imaging                         | 2         | 0.23%   |
| OmniVision Technologies                | 2         | 0.23%   |
| Jiangxi Shinetech Optical              | 2         | 0.23%   |
| Intel                                  | 2         | 0.23%   |
| Cubeternet                             | 2         | 0.23%   |
| YGTek                                  | 1         | 0.12%   |
| Valve Software                         | 1         | 0.12%   |
| USB Camera                             | 1         | 0.12%   |
| Unknown                                | 1         | 0.12%   |
| Sonix Technology                       | 1         | 0.12%   |
| Qtech                                  | 1         | 0.12%   |
| Huawei Technologies                    | 1         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 79        | 8.98%   |
| Bison Integrated Camera                       | 42        | 4.77%   |
| IMC Networks Integrated Camera                | 37        | 4.2%    |
| Microdia Integrated_Webcam_HD                 | 21        | 2.39%   |
| Chicony HD WebCam                             | 19        | 2.16%   |
| Realtek Integrated_Webcam_HD                  | 18        | 2.05%   |
| Microdia Integrated Webcam                    | 18        | 2.05%   |
| Chicony Lenovo Integrated Camera (0.3MP)      | 18        | 2.05%   |
| Sunplus Integrated_Webcam_HD                  | 16        | 1.82%   |
| Chicony Integrated Camera (1280x720@30)       | 16        | 1.82%   |
| Lite-On Integrated Camera                     | 15        | 1.7%    |
| Logitech Webcam C270                          | 14        | 1.59%   |
| Realtek USB 2.0 PC Camera                     | 11        | 1.25%   |
| IMC Networks Realtek PC Camera                | 11        | 1.25%   |
| IMC Networks EasyCamera                       | 10        | 1.14%   |
| Chicony Realtek DMFT RGB                      | 9         | 1.02%   |
| Bison SunplusIT Integrated Camera             | 9         | 1.02%   |
| Bison Lenovo EasyCamera                       | 9         | 1.02%   |
| Syntek Integrated Camera                      | 8         | 0.91%   |
| Sunplus Laptop_Integrated_Webcam_FHD          | 8         | 0.91%   |
| Logitech HD Pro Webcam C920                   | 8         | 0.91%   |
| Chicony Integrated IR Camera                  | 8         | 0.91%   |
| Chicony Chicony USB2.0 Camera                 | 8         | 0.91%   |
| Chicony ThinkPad T490 Webcam                  | 7         | 0.8%    |
| Apple FaceTime HD Camera                      | 7         | 0.8%    |
| Quanta HD Webcam                              | 6         | 0.68%   |
| Microdia Integrated Webcam HD                 | 6         | 0.68%   |
| Luxvisions Innotech Limited Integrated Camera | 6         | 0.68%   |
| IMC Networks Integrated Webcam                | 6         | 0.68%   |
| Chicony Integrated HP HD Webcam               | 6         | 0.68%   |
| Syntek EasyCamera                             | 5         | 0.57%   |
| Sunplus Laptop Integrated WebCam HD           | 5         | 0.57%   |
| Sunplus HD WebCam                             | 5         | 0.57%   |
| Realtek Integrated Webcam                     | 5         | 0.57%   |
| Lenovo Integrated Webcam [R5U877]             | 5         | 0.57%   |
| IMC Networks UVC VGA Webcam                   | 5         | 0.57%   |
| Chicony Integrated Camera [ThinkPad]          | 5         | 0.57%   |
| Bison ThinkPad Integrated Camera              | 5         | 0.57%   |
| Apple FaceTime HD Camera (Built-in)           | 5         | 0.57%   |
| Realtek HD WebCam                             | 4         | 0.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 77        | 31.43%  |
| Synaptics                  | 67        | 27.35%  |
| Shenzhen Goodix Technology | 32        | 13.06%  |
| Upek                       | 21        | 8.57%   |
| AuthenTec                  | 12        | 4.9%    |
| STMicroelectronics         | 10        | 4.08%   |
| Broadcom                   | 8         | 3.27%   |
| LighTuning Technology      | 6         | 2.45%   |
| FocalTech Systems          | 5         | 2.04%   |
| Elan Microelectronics      | 5         | 2.04%   |
| Samsung Electronics        | 1         | 0.41%   |
| DigitalPersona             | 1         | 0.41%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 29        | 11.84%  |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 23        | 9.39%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 23        | 9.39%   |
| Shenzhen Goodix Fingerprint Reader                                           | 22        | 8.98%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 21        | 8.57%   |
| Validity Sensors Synaptics WBDI                                              | 18        | 7.35%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 11        | 4.49%   |
| STMicroelectronics Fingerprint Reader                                        | 10        | 4.08%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 3.27%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 7         | 2.86%   |
| Shenzhen Goodix  Fingerprint Device                                          | 7         | 2.86%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 6         | 2.45%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 5         | 2.04%   |
| Elan Fingerprint Sensor                                                      | 5         | 2.04%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 4         | 1.63%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                     | 4         | 1.63%   |
| FocalTech Systems Fingerprint Reader                                         | 4         | 1.63%   |
| AuthenTec AES2810                                                            | 4         | 1.63%   |
| AuthenTec AES1660                                                            | 4         | 1.63%   |
| Synaptics UWP WBDI                                                           | 3         | 1.22%   |
| Shenzhen Goodix Fingerprint Reader SGX                                       | 3         | 1.22%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 3         | 1.22%   |
| Validity Sensors VFS491                                                      | 2         | 0.82%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 2         | 0.82%   |
| Validity Sensors VFS Fingerprint sensor                                      | 2         | 0.82%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint   | 2         | 0.82%   |
| Synaptics WBDI                                                               | 2         | 0.82%   |
| Validity Sensors VFS451 Fingerprint Reader                                   | 1         | 0.41%   |
| Validity Sensors VFS101 Fingerprint Reader                                   | 1         | 0.41%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                  | 1         | 0.41%   |
| Validity Sensors Fingerprint scanner                                         | 1         | 0.41%   |
| Synaptics WBDI Fingerprint Reader USB 102                                    | 1         | 0.41%   |
| Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint                    | 1         | 0.41%   |
| Samsung CanvasBio Fingerprint Reader                                         | 1         | 0.41%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 1         | 0.41%   |
| FocalTech Systems FocalTech Fingerprint Device                               | 1         | 0.41%   |
| DigitalPersona Fingerprint Reader                                            | 1         | 0.41%   |
| AuthenTec AES2660                                                            | 1         | 0.41%   |

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
| 1     | 771       | 31.37%  |
| 0     | 690       | 28.07%  |
| 2     | 567       | 23.07%  |
| 3     | 286       | 11.64%  |
| 4     | 109       | 4.43%   |
| 5     | 21        | 0.85%   |
| 6     | 11        | 0.45%   |
| 7     | 2         | 0.08%   |
| 9     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 1342      | 46.18%  |
| Bluetooth                | 424       | 14.59%  |
| Net/wireless             | 318       | 10.94%  |
| Card reader              | 254       | 8.74%   |
| Fingerprint reader       | 239       | 8.22%   |
| Firewire controller      | 168       | 5.78%   |
| Sound                    | 40        | 1.38%   |
| Net/ethernet             | 40        | 1.38%   |
| Network                  | 34        | 1.17%   |
| Storage                  | 21        | 0.72%   |
| Modem                    | 14        | 0.48%   |
| Dvb card                 | 6         | 0.21%   |
| Storage/raid             | 2         | 0.07%   |
| Storage/ide              | 2         | 0.07%   |
| Storage/nvme             | 1         | 0.03%   |
| Graphics card            | 1         | 0.03%   |

