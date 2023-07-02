BSD - Tested Hardware & Statistics (Notebooks)
----------------------------------------------

A project to collect tested hardware configurations for BSD.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This report is for real hardware. Report for virtual hardware: [TestDays_VE](https://github.com/bsdhw/TestDays_VE)

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

Total: 3648

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T60 20076PU        | [cb47bfef12](https://bsd-hardware.info/?probe=cb47bfef12) | Jun 30, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [1aff07438c](https://bsd-hardware.info/?probe=1aff07438c) | Jun 28, 2023 |
| HP            | EliteBook 840 G3            | [17834256ca](https://bsd-hardware.info/?probe=17834256ca) | Jun 28, 2023 |
| Deciso        | NetBoard-A10                | [2eff359d8f](https://bsd-hardware.info/?probe=2eff359d8f) | Jun 28, 2023 |
| HP            | EliteBook 8570p             | [03c29939fc](https://bsd-hardware.info/?probe=03c29939fc) | Jun 28, 2023 |
| Deciso        | DEC2700 - OPNsense Appli... | [aedd3a8255](https://bsd-hardware.info/?probe=aedd3a8255) | Jun 28, 2023 |
| HP            | EliteBook 8570p             | [748ae83ba1](https://bsd-hardware.info/?probe=748ae83ba1) | Jun 27, 2023 |
| Dell          | XPS 13 9360                 | [648c09752f](https://bsd-hardware.info/?probe=648c09752f) | Jun 27, 2023 |
| HP            | EliteBook 850 G5            | [4bae8cd192](https://bsd-hardware.info/?probe=4bae8cd192) | Jun 27, 2023 |
| Deciso        | OPNsense Appliance          | [be0008eb2a](https://bsd-hardware.info/?probe=be0008eb2a) | Jun 26, 2023 |
| Dell          | Latitude 3420               | [057f065baa](https://bsd-hardware.info/?probe=057f065baa) | Jun 26, 2023 |
| Lenovo        | ThinkPad T440p 20AW000BU... | [9a7628d17b](https://bsd-hardware.info/?probe=9a7628d17b) | Jun 26, 2023 |
| Dell          | Inspiron 5570               | [a6e959358f](https://bsd-hardware.info/?probe=a6e959358f) | Jun 25, 2023 |
| HP            | EliteBook 8570p             | [e7dfbf94d0](https://bsd-hardware.info/?probe=e7dfbf94d0) | Jun 25, 2023 |
| Dell          | Latitude E4310              | [9cdd4909fe](https://bsd-hardware.info/?probe=9cdd4909fe) | Jun 24, 2023 |
| HP            | Laptop 15-bs1xx             | [dc0d876d7b](https://bsd-hardware.info/?probe=dc0d876d7b) | Jun 24, 2023 |
| HP            | Laptop 15-ra0xx             | [8c31502b68](https://bsd-hardware.info/?probe=8c31502b68) | Jun 24, 2023 |
| HP            | EliteBook 750 G1            | [e0af4797d4](https://bsd-hardware.info/?probe=e0af4797d4) | Jun 24, 2023 |
| HP            | EliteBook 750 G1            | [aba91c70d1](https://bsd-hardware.info/?probe=aba91c70d1) | Jun 24, 2023 |
| HP            | 250 G6 Notebook PC          | [f7df283c94](https://bsd-hardware.info/?probe=f7df283c94) | Jun 24, 2023 |
| Dell          | Latitude 5490               | [b638c1b2b1](https://bsd-hardware.info/?probe=b638c1b2b1) | Jun 23, 2023 |
| Unknown       | Unknown                     | [b324d1f4fc](https://bsd-hardware.info/?probe=b324d1f4fc) | Jun 23, 2023 |
| HP            | Pavilion g4                 | [ef66b5588a](https://bsd-hardware.info/?probe=ef66b5588a) | Jun 23, 2023 |
| HP            | 1000                        | [21faecd7a6](https://bsd-hardware.info/?probe=21faecd7a6) | Jun 23, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | [d194e8bc0d](https://bsd-hardware.info/?probe=d194e8bc0d) | Jun 22, 2023 |
| Acer          | Aspire 5749                 | [75ad2ddb6f](https://bsd-hardware.info/?probe=75ad2ddb6f) | Jun 22, 2023 |
| Lenovo        | ThinkPad T430 2347A45       | [6969cd9e1a](https://bsd-hardware.info/?probe=6969cd9e1a) | Jun 20, 2023 |
| Acer          | Aspire 5749                 | [1e91633580](https://bsd-hardware.info/?probe=1e91633580) | Jun 20, 2023 |
| Lenovo        | ThinkPad T430 2347A45       | [461a92a1a2](https://bsd-hardware.info/?probe=461a92a1a2) | Jun 20, 2023 |
| Unknown       | Unknown                     | [c017b848dc](https://bsd-hardware.info/?probe=c017b848dc) | Jun 19, 2023 |
| Apple         | MacBook2,1                  | [9e864bfe3b](https://bsd-hardware.info/?probe=9e864bfe3b) | Jun 18, 2023 |
| HP            | Pavilion 15                 | [9ba6acdb4b](https://bsd-hardware.info/?probe=9ba6acdb4b) | Jun 18, 2023 |
| Dell          | Latitude E6520              | [98868960d5](https://bsd-hardware.info/?probe=98868960d5) | Jun 18, 2023 |
| HP            | Stream Laptop 14-ds0xxx     | [81bbc73e72](https://bsd-hardware.info/?probe=81bbc73e72) | Jun 18, 2023 |
| Dell          | Inspiron 5559               | [b0659ff5bf](https://bsd-hardware.info/?probe=b0659ff5bf) | Jun 18, 2023 |
| Samsung       | NC210/NC110                 | [06f5a9210b](https://bsd-hardware.info/?probe=06f5a9210b) | Jun 17, 2023 |
| HP            | EliteBook 8570p             | [53bbc07cc8](https://bsd-hardware.info/?probe=53bbc07cc8) | Jun 17, 2023 |
| Apple         | MacBook7,1                  | [6412e6fb23](https://bsd-hardware.info/?probe=6412e6fb23) | Jun 16, 2023 |
| HUAWEI        | BOHB-WAX9                   | [d8079e6155](https://bsd-hardware.info/?probe=d8079e6155) | Jun 16, 2023 |
| Notebook      | NL5xRU                      | [04ca736537](https://bsd-hardware.info/?probe=04ca736537) | Jun 15, 2023 |
| Lenovo        | ThinkPad T480 20L6S2S800    | [722403df31](https://bsd-hardware.info/?probe=722403df31) | Jun 15, 2023 |
| Lenovo        | ThinkPad T430 2347GR2       | [834f9f8748](https://bsd-hardware.info/?probe=834f9f8748) | Jun 15, 2023 |
| Lenovo        | ThinkPad T450 20BV000BUS    | [7e1aa76e45](https://bsd-hardware.info/?probe=7e1aa76e45) | Jun 15, 2023 |
| Unknown       | Unknown                     | [e218344894](https://bsd-hardware.info/?probe=e218344894) | Jun 15, 2023 |
| Panasonic     | CFSX4-1                     | [ff83a965d2](https://bsd-hardware.info/?probe=ff83a965d2) | Jun 15, 2023 |
| Deciso        | OPNsense Appliance          | [43936f5f1c](https://bsd-hardware.info/?probe=43936f5f1c) | Jun 15, 2023 |
| Lenovo        | ThinkPad T430 2344BZU       | [01df487b47](https://bsd-hardware.info/?probe=01df487b47) | Jun 14, 2023 |
| ASUSTek       | 1015P                       | [c700224684](https://bsd-hardware.info/?probe=c700224684) | Jun 14, 2023 |
| MSI           | GE63 Raider RGB 8RE         | [ecdb80adc0](https://bsd-hardware.info/?probe=ecdb80adc0) | Jun 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [4841a6b1d2](https://bsd-hardware.info/?probe=4841a6b1d2) | Jun 14, 2023 |
| HP            | Compaq 6830s                | [1a06917a0f](https://bsd-hardware.info/?probe=1a06917a0f) | Jun 14, 2023 |
| Lenovo        | ThinkPad T530 2429AP0       | [ddf37e7b17](https://bsd-hardware.info/?probe=ddf37e7b17) | Jun 13, 2023 |
| Samsung       | NC210/NC110                 | [dad27d6099](https://bsd-hardware.info/?probe=dad27d6099) | Jun 13, 2023 |
| Fujitsu Si... | AMILO Li3710                | [f6540a4d85](https://bsd-hardware.info/?probe=f6540a4d85) | Jun 13, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [76809610f9](https://bsd-hardware.info/?probe=76809610f9) | Jun 13, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1CH0... | [b532f1ce9c](https://bsd-hardware.info/?probe=b532f1ce9c) | Jun 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [dd937d0914](https://bsd-hardware.info/?probe=dd937d0914) | Jun 12, 2023 |
| HP            | EliteBook 840 G6            | [1d3675e09e](https://bsd-hardware.info/?probe=1d3675e09e) | Jun 11, 2023 |
| Acer          | Aspire E5-571G              | [9279b8ab4e](https://bsd-hardware.info/?probe=9279b8ab4e) | Jun 11, 2023 |
| Samsung       | R530/R730/R540              | [b007264caa](https://bsd-hardware.info/?probe=b007264caa) | Jun 11, 2023 |
| HP            | 15                          | [4664b4c93f](https://bsd-hardware.info/?probe=4664b4c93f) | Jun 11, 2023 |
| Dell          | Inspiron 3180               | [cb769078b4](https://bsd-hardware.info/?probe=cb769078b4) | Jun 10, 2023 |
| Dell          | Inspiron 5593               | [8bedc249ea](https://bsd-hardware.info/?probe=8bedc249ea) | Jun 10, 2023 |
| Dell          | Inspiron 7548               | [c80bb80e8f](https://bsd-hardware.info/?probe=c80bb80e8f) | Jun 10, 2023 |
| Lenovo        | B40-30 80F10002BR           | [769c678314](https://bsd-hardware.info/?probe=769c678314) | Jun 10, 2023 |
| Lenovo        | ThinkPad T430 2347GR2       | [439e6a5034](https://bsd-hardware.info/?probe=439e6a5034) | Jun 10, 2023 |
| Unknown       | Unknown                     | [9afa1aea18](https://bsd-hardware.info/?probe=9afa1aea18) | Jun 10, 2023 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | [27ba75252a](https://bsd-hardware.info/?probe=27ba75252a) | Jun 09, 2023 |
| Lenovo        | ThinkPad T480 20L6S5VP4C    | [b891388109](https://bsd-hardware.info/?probe=b891388109) | Jun 07, 2023 |
| ASUSTek       | 1015BX                      | [ad05aaf9fe](https://bsd-hardware.info/?probe=ad05aaf9fe) | Jun 07, 2023 |
| Deciso        | NetBoard-A20                | [0754642fe6](https://bsd-hardware.info/?probe=0754642fe6) | Jun 07, 2023 |
| Unknown       | Unknown                     | [422b9d51a7](https://bsd-hardware.info/?probe=422b9d51a7) | Jun 06, 2023 |
| Dell          | Inspiron 5559               | [fe5f99c4b0](https://bsd-hardware.info/?probe=fe5f99c4b0) | Jun 06, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [9f18b1b304](https://bsd-hardware.info/?probe=9f18b1b304) | Jun 06, 2023 |
| Lenovo        | ThinkPad T500 2082BNU       | [dedd066084](https://bsd-hardware.info/?probe=dedd066084) | Jun 06, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [85c18dbbb5](https://bsd-hardware.info/?probe=85c18dbbb5) | Jun 06, 2023 |
| Lenovo        | IdeaPad Slim 9 14ITL5 82... | [03e1e6d302](https://bsd-hardware.info/?probe=03e1e6d302) | Jun 05, 2023 |
| Deciso        | Netboard A20                | [eb03ae7215](https://bsd-hardware.info/?probe=eb03ae7215) | Jun 05, 2023 |
| Toshiba       | Satellite C70-B             | [cf9ed85e65](https://bsd-hardware.info/?probe=cf9ed85e65) | Jun 05, 2023 |
| Toshiba       | Satellite C70-B             | [fc66ebba25](https://bsd-hardware.info/?probe=fc66ebba25) | Jun 05, 2023 |
| Lenovo        | S10-3                       | [f874a66e78](https://bsd-hardware.info/?probe=f874a66e78) | Jun 05, 2023 |
| Lenovo        | S10-3                       | [b76483ab8b](https://bsd-hardware.info/?probe=b76483ab8b) | Jun 05, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [e1a7d29d74](https://bsd-hardware.info/?probe=e1a7d29d74) | Jun 04, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [d0d9de7cf3](https://bsd-hardware.info/?probe=d0d9de7cf3) | Jun 04, 2023 |
| Deciso        | NetBoard-A10                | [ab3919bc32](https://bsd-hardware.info/?probe=ab3919bc32) | Jun 04, 2023 |
| Lenovo        | B590 20208                  | [dc65d735c8](https://bsd-hardware.info/?probe=dc65d735c8) | Jun 04, 2023 |
| Unknown       | Unknown                     | [a243045cc3](https://bsd-hardware.info/?probe=a243045cc3) | Jun 04, 2023 |
| Dell          | G5 5505                     | [5a3c1f19a0](https://bsd-hardware.info/?probe=5a3c1f19a0) | Jun 03, 2023 |
| Lenovo        | ThinkPad X240 20AMS0250T    | [047c7b72b4](https://bsd-hardware.info/?probe=047c7b72b4) | Jun 02, 2023 |
| Panasonic     | CF-NX1GDHYS                 | [fb1f293997](https://bsd-hardware.info/?probe=fb1f293997) | Jun 02, 2023 |
| Deciso        | NetBoard-A20                | [48a63a2328](https://bsd-hardware.info/?probe=48a63a2328) | Jun 02, 2023 |
| Dell          | G5 5505                     | [1b10aecc38](https://bsd-hardware.info/?probe=1b10aecc38) | Jun 02, 2023 |
| HP            | EliteBook 8570p             | [22572f1df6](https://bsd-hardware.info/?probe=22572f1df6) | Jun 01, 2023 |
| Dell          | Inspiron 5559               | [330c08c388](https://bsd-hardware.info/?probe=330c08c388) | Jun 01, 2023 |
| Dell          | Inspiron 5559               | [53cf3cea13](https://bsd-hardware.info/?probe=53cf3cea13) | Jun 01, 2023 |
| Lenovo        | ThinkPad E495 20NE000BSP    | [0e02b323ee](https://bsd-hardware.info/?probe=0e02b323ee) | Jun 01, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | [8cc6299ba9](https://bsd-hardware.info/?probe=8cc6299ba9) | May 31, 2023 |
| Lenovo        | ThinkPad X270 20HMCTO1WW    | [b5f507c034](https://bsd-hardware.info/?probe=b5f507c034) | May 31, 2023 |
| HP            | Pavilion Notebook           | [1bb0436fe5](https://bsd-hardware.info/?probe=1bb0436fe5) | May 30, 2023 |
| IGEL Techn... | H830C                       | [01e377524a](https://bsd-hardware.info/?probe=01e377524a) | May 29, 2023 |
| Apple         | MacBookPro10,2              | [c274e2c9db](https://bsd-hardware.info/?probe=c274e2c9db) | May 29, 2023 |
| Dell          | System XPS L702X            | [f56d7090f9](https://bsd-hardware.info/?probe=f56d7090f9) | May 28, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | [6701dce30e](https://bsd-hardware.info/?probe=6701dce30e) | May 28, 2023 |
| Dell          | Inspiron 5559               | [23cad3f06e](https://bsd-hardware.info/?probe=23cad3f06e) | May 28, 2023 |
| Deciso        | OPNsense Appliance          | [c47f62b522](https://bsd-hardware.info/?probe=c47f62b522) | May 28, 2023 |
| Fujitsu       | Unknown                     | [3b5c9ab914](https://bsd-hardware.info/?probe=3b5c9ab914) | May 27, 2023 |
| Toshiba       | NB250                       | [62c572e895](https://bsd-hardware.info/?probe=62c572e895) | May 27, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [3944241750](https://bsd-hardware.info/?probe=3944241750) | May 27, 2023 |
| Tactus        | GeoFlex 110                 | [df93ad7e83](https://bsd-hardware.info/?probe=df93ad7e83) | May 27, 2023 |
| HP            | EliteBook 8570p             | [65376d6b42](https://bsd-hardware.info/?probe=65376d6b42) | May 27, 2023 |
| Acer          | Nitro AN515-42              | [adc687fcfe](https://bsd-hardware.info/?probe=adc687fcfe) | May 26, 2023 |
| Lenovo        | ThinkPad X140e 20BMS03E0... | [580c52399f](https://bsd-hardware.info/?probe=580c52399f) | May 25, 2023 |
| Deciso        | NetBoard-A20                | [0c5fd49340](https://bsd-hardware.info/?probe=0c5fd49340) | May 25, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | [a2726e621b](https://bsd-hardware.info/?probe=a2726e621b) | May 25, 2023 |
| Timi          | TM1701                      | [1dd768a721](https://bsd-hardware.info/?probe=1dd768a721) | May 25, 2023 |
| Acer          | Nitro AN515-57              | [c39ea00de5](https://bsd-hardware.info/?probe=c39ea00de5) | May 25, 2023 |
| Dell          | System XPS L702X            | [857016be75](https://bsd-hardware.info/?probe=857016be75) | May 24, 2023 |
| Lenovo        | ThinkPad T430 2347CTO       | [68937b1686](https://bsd-hardware.info/?probe=68937b1686) | May 24, 2023 |
| Unknown       | Unknown                     | [3b4be5b07a](https://bsd-hardware.info/?probe=3b4be5b07a) | May 24, 2023 |
| HP            | EliteBook 8570p             | [a1a68c0f7d](https://bsd-hardware.info/?probe=a1a68c0f7d) | May 24, 2023 |
| Acer          | Aspire E5-573               | [7bcb7c96be](https://bsd-hardware.info/?probe=7bcb7c96be) | May 23, 2023 |
| ASUSTek       | K42Jc                       | [3da2928a08](https://bsd-hardware.info/?probe=3da2928a08) | May 23, 2023 |
| Dell          | Inspiron 5559               | [9a2c066dfa](https://bsd-hardware.info/?probe=9a2c066dfa) | May 23, 2023 |
| Lenovo        | ThinkPad X140e 20BMS03E0... | [84e3ac62d5](https://bsd-hardware.info/?probe=84e3ac62d5) | May 23, 2023 |
| HP            | EliteBook 8570p             | [b5f17b6bf8](https://bsd-hardware.info/?probe=b5f17b6bf8) | May 23, 2023 |
| Google        | Sentry                      | [107124dd66](https://bsd-hardware.info/?probe=107124dd66) | May 22, 2023 |
| Sony          | VPCEG15FB                   | [8777493861](https://bsd-hardware.info/?probe=8777493861) | May 21, 2023 |
| HP            | Pavilion Notebook           | [41ce3c5d11](https://bsd-hardware.info/?probe=41ce3c5d11) | May 21, 2023 |
| Apple         | MacBookPro10,1              | [643f7277de](https://bsd-hardware.info/?probe=643f7277de) | May 21, 2023 |
| HP            | ZBook 15 G3                 | [4965fc4251](https://bsd-hardware.info/?probe=4965fc4251) | May 21, 2023 |
| Acer          | Aspire A514-54              | [7aed9d938a](https://bsd-hardware.info/?probe=7aed9d938a) | May 21, 2023 |
| Dell          | Inspiron 5559               | [a87acae699](https://bsd-hardware.info/?probe=a87acae699) | May 21, 2023 |
| HP            | ProBook 455 G3              | [b6a6c91115](https://bsd-hardware.info/?probe=b6a6c91115) | May 21, 2023 |
| Lenovo        | ThinkPad 11e 20DAS0S300     | [44d30cfcf6](https://bsd-hardware.info/?probe=44d30cfcf6) | May 21, 2023 |
| Unknown       | Unknown                     | [2a2b4272f9](https://bsd-hardware.info/?probe=2a2b4272f9) | May 20, 2023 |
| Unknown       | Apple MacBook Pro (13-in... | [5e25a49c65](https://bsd-hardware.info/?probe=5e25a49c65) | May 20, 2023 |
| Packard Be... | EasyNote LJ65               | [36d3e7aaf7](https://bsd-hardware.info/?probe=36d3e7aaf7) | May 19, 2023 |
| HP            | EliteBook 8570p             | [70d54595c2](https://bsd-hardware.info/?probe=70d54595c2) | May 19, 2023 |
| Valve         | Jupiter                     | [7be0869603](https://bsd-hardware.info/?probe=7be0869603) | May 19, 2023 |
| Valve         | Jupiter                     | [ef56a2bd17](https://bsd-hardware.info/?probe=ef56a2bd17) | May 19, 2023 |
| Lenovo        | ThinkPad T560 20FJS03Q00    | [a2110471aa](https://bsd-hardware.info/?probe=a2110471aa) | May 18, 2023 |
| Deciso        | NetBoard-A20                | [313796fd3e](https://bsd-hardware.info/?probe=313796fd3e) | May 18, 2023 |
| Lenovo        | ThinkPad X201 3323BBG       | [7b529b0888](https://bsd-hardware.info/?probe=7b529b0888) | May 17, 2023 |
| Panasonic     | CF-30KAPAXAM                | [62910ad9d9](https://bsd-hardware.info/?probe=62910ad9d9) | May 17, 2023 |
| Dell          | Inspiron 5559               | [dca662fc41](https://bsd-hardware.info/?probe=dca662fc41) | May 16, 2023 |
| Lenovo        | ThinkPad T61 7659AS5        | [7732b2cfa7](https://bsd-hardware.info/?probe=7732b2cfa7) | May 15, 2023 |
| Dell          | Inspiron 3581               | [25c403ca33](https://bsd-hardware.info/?probe=25c403ca33) | May 15, 2023 |
| HP            | EliteBook 8570p             | [e252dc5ff2](https://bsd-hardware.info/?probe=e252dc5ff2) | May 15, 2023 |
| Lenovo        | ThinkPad T61 7659AS5        | [b6071c549a](https://bsd-hardware.info/?probe=b6071c549a) | May 15, 2023 |
| Dell          | Inspiron 3581               | [8d445a3fb3](https://bsd-hardware.info/?probe=8d445a3fb3) | May 14, 2023 |
| Sony          | SVF14A15CBB                 | [4ada2dca25](https://bsd-hardware.info/?probe=4ada2dca25) | May 14, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [526906c806](https://bsd-hardware.info/?probe=526906c806) | May 14, 2023 |
| Alienware     | 17 R4                       | [df734c8e64](https://bsd-hardware.info/?probe=df734c8e64) | May 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [8aede62ca8](https://bsd-hardware.info/?probe=8aede62ca8) | May 14, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [256915976d](https://bsd-hardware.info/?probe=256915976d) | May 12, 2023 |
| TUXEDO        | Aura 15 Gen1                | [3d889e8b9b](https://bsd-hardware.info/?probe=3d889e8b9b) | May 11, 2023 |
| Intel         | HuronRiver Platform         | [83494ffd65](https://bsd-hardware.info/?probe=83494ffd65) | May 11, 2023 |
| Medion        | Major X10                   | [99228fd9da](https://bsd-hardware.info/?probe=99228fd9da) | May 10, 2023 |
| Deciso        | NetBoard-A10                | [37ee98e0b6](https://bsd-hardware.info/?probe=37ee98e0b6) | May 09, 2023 |
| Apple         | MacBook5,1                  | [da07885adb](https://bsd-hardware.info/?probe=da07885adb) | May 09, 2023 |
| Notebook      | N7x0WU                      | [7a646e185a](https://bsd-hardware.info/?probe=7a646e185a) | May 09, 2023 |
| MSI           | GE62 6QC                    | [7c3fd3c9ca](https://bsd-hardware.info/?probe=7c3fd3c9ca) | May 08, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [95695f78c5](https://bsd-hardware.info/?probe=95695f78c5) | May 08, 2023 |
| Lenovo        | ThinkPad T410 2537N24       | [6cd0f02045](https://bsd-hardware.info/?probe=6cd0f02045) | May 08, 2023 |
| Matsushita... | CF-48V4KNDQM                | [79f10d24d6](https://bsd-hardware.info/?probe=79f10d24d6) | May 07, 2023 |
| HP            | Laptop 14-bs0xx             | [98ea66d6e8](https://bsd-hardware.info/?probe=98ea66d6e8) | May 07, 2023 |
| Deciso        | OPNsense Appliance          | [2745eadfd9](https://bsd-hardware.info/?probe=2745eadfd9) | May 07, 2023 |
| ASUSTek       | 1000HE                      | [36214f8bed](https://bsd-hardware.info/?probe=36214f8bed) | May 07, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [d2bd7a8764](https://bsd-hardware.info/?probe=d2bd7a8764) | May 07, 2023 |
| Acer          | V5-131                      | [9d3ba324bc](https://bsd-hardware.info/?probe=9d3ba324bc) | May 06, 2023 |
| Lenovo        | ThinkPad T500 205663G       | [d706da9400](https://bsd-hardware.info/?probe=d706da9400) | May 06, 2023 |
| Lenovo        | ThinkPad T480s 20L8A00KC... | [44ddee0eec](https://bsd-hardware.info/?probe=44ddee0eec) | May 06, 2023 |
| Panasonic     | CF-30KAPAXAM                | [1c918b79b0](https://bsd-hardware.info/?probe=1c918b79b0) | May 06, 2023 |
| Matsushita... | CF-51RCVDNLM                | [105a885451](https://bsd-hardware.info/?probe=105a885451) | May 05, 2023 |
| Lenovo        | ThinkPad T420s 41742BU      | [161fe49de4](https://bsd-hardware.info/?probe=161fe49de4) | May 05, 2023 |
| Lenovo        | ThinkPad X230 2325T4T       | [00303b7a59](https://bsd-hardware.info/?probe=00303b7a59) | May 05, 2023 |
| Lenovo        | ThinkPad X220 429043U       | [bb714a4350](https://bsd-hardware.info/?probe=bb714a4350) | May 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [28e76d5531](https://bsd-hardware.info/?probe=28e76d5531) | May 04, 2023 |
| Lenovo        | ThinkPad T430 2347GZU       | [8c3f486dbc](https://bsd-hardware.info/?probe=8c3f486dbc) | May 03, 2023 |
| Apple         | MacBookPro11,5              | [45bffd3275](https://bsd-hardware.info/?probe=45bffd3275) | May 03, 2023 |
| Lenovo        | Flex 2-15 20405             | [3773da7851](https://bsd-hardware.info/?probe=3773da7851) | May 03, 2023 |
| Panasonic     | CF-52PFPBSFQ                | [e2c3df29b5](https://bsd-hardware.info/?probe=e2c3df29b5) | May 03, 2023 |
| HP            | Compaq Presario CQ50        | [f296048a29](https://bsd-hardware.info/?probe=f296048a29) | May 03, 2023 |
| Samsung       | NC110P/NC108P/NC111P        | [ea55a6fecf](https://bsd-hardware.info/?probe=ea55a6fecf) | May 02, 2023 |
| Apple         | MacBook5,1                  | [a5a1ca2ee6](https://bsd-hardware.info/?probe=a5a1ca2ee6) | May 02, 2023 |
| Panasonic     | CF-53AAGHYDM                | [c7daf17edb](https://bsd-hardware.info/?probe=c7daf17edb) | May 02, 2023 |
| Lenovo        | ThinkPad L450 20DSS1S402    | [f899593f61](https://bsd-hardware.info/?probe=f899593f61) | May 01, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [b09acffe7b](https://bsd-hardware.info/?probe=b09acffe7b) | May 01, 2023 |
| Lenovo        | ThinkPad X260 20F5S2GM00    | [c4af168c4a](https://bsd-hardware.info/?probe=c4af168c4a) | May 01, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [cf504f51df](https://bsd-hardware.info/?probe=cf504f51df) | May 01, 2023 |
| ReachingTe... | DreamQuest Pro 2022         | [afd28a7425](https://bsd-hardware.info/?probe=afd28a7425) | Apr 30, 2023 |
| Fujitsu       | LIFEBOOK E752               | [44ea9fb6ae](https://bsd-hardware.info/?probe=44ea9fb6ae) | Apr 30, 2023 |
| Dell          | Latitude E5570              | [98e3f9821b](https://bsd-hardware.info/?probe=98e3f9821b) | Apr 29, 2023 |
| HP            | ProBook 640 G4              | [7b44e1591f](https://bsd-hardware.info/?probe=7b44e1591f) | Apr 29, 2023 |
| Deciso        | NetBoard-A10                | [79c36f752c](https://bsd-hardware.info/?probe=79c36f752c) | Apr 28, 2023 |
| Deciso        | NetBoard-A20                | [baa443b8ea](https://bsd-hardware.info/?probe=baa443b8ea) | Apr 28, 2023 |
| Apple         | MacBookPro8,3               | [08e155a558](https://bsd-hardware.info/?probe=08e155a558) | Apr 27, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [fc81710889](https://bsd-hardware.info/?probe=fc81710889) | Apr 27, 2023 |
| Apple         | MacBook5,1                  | [52174cc0ba](https://bsd-hardware.info/?probe=52174cc0ba) | Apr 27, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [692df89c1f](https://bsd-hardware.info/?probe=692df89c1f) | Apr 26, 2023 |
| Apple         | MacBook5,1                  | [4c7f33d6a9](https://bsd-hardware.info/?probe=4c7f33d6a9) | Apr 25, 2023 |
| Deciso        | NetBoard-A20                | [3d0f6b629d](https://bsd-hardware.info/?probe=3d0f6b629d) | Apr 25, 2023 |
| Shuttle       | DS437                       | [284decb573](https://bsd-hardware.info/?probe=284decb573) | Apr 25, 2023 |
| HP            | Pavilion Notebook           | [247810c987](https://bsd-hardware.info/?probe=247810c987) | Apr 24, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [7caed06fdb](https://bsd-hardware.info/?probe=7caed06fdb) | Apr 24, 2023 |
| Google        | Peppy                       | [d162160498](https://bsd-hardware.info/?probe=d162160498) | Apr 24, 2023 |
| Fujitsu Si... | AMILO Li3710                | [214b0c30e0](https://bsd-hardware.info/?probe=214b0c30e0) | Apr 23, 2023 |
| HP            | Unknown                     | [e2aa3620b4](https://bsd-hardware.info/?probe=e2aa3620b4) | Apr 23, 2023 |
| Lenovo        | ThinkPad X270 20HMS06Q1D    | [2df7c991f0](https://bsd-hardware.info/?probe=2df7c991f0) | Apr 23, 2023 |
| Lenovo        | G500 20236                  | [e7387bfd6e](https://bsd-hardware.info/?probe=e7387bfd6e) | Apr 23, 2023 |
| Dell          | Inspiron 3421               | [ef4870410f](https://bsd-hardware.info/?probe=ef4870410f) | Apr 23, 2023 |
| HP            | Pavilion Notebook           | [243a9c2f22](https://bsd-hardware.info/?probe=243a9c2f22) | Apr 22, 2023 |
| Intel Clie... | LAPBC510                    | [68b1300903](https://bsd-hardware.info/?probe=68b1300903) | Apr 22, 2023 |
| HP            | Pavilion 17                 | [0f891b4377](https://bsd-hardware.info/?probe=0f891b4377) | Apr 21, 2023 |
| Lenovo        | ThinkPad W520 4270CTO       | [51f0a87f01](https://bsd-hardware.info/?probe=51f0a87f01) | Apr 21, 2023 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [93b498fb0c](https://bsd-hardware.info/?probe=93b498fb0c) | Apr 21, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [e17bcecec8](https://bsd-hardware.info/?probe=e17bcecec8) | Apr 21, 2023 |
| Dell          | Latitude 7280               | [254acb5df8](https://bsd-hardware.info/?probe=254acb5df8) | Apr 20, 2023 |
| HP            | EliteBook 8570p             | [6e82f69c4c](https://bsd-hardware.info/?probe=6e82f69c4c) | Apr 20, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [541f3e7f7e](https://bsd-hardware.info/?probe=541f3e7f7e) | Apr 20, 2023 |
| ReachingTe... | DreamQuest Pro 2022         | [c4b2619dda](https://bsd-hardware.info/?probe=c4b2619dda) | Apr 20, 2023 |
| Dell          | Precision 5510              | [7028fde527](https://bsd-hardware.info/?probe=7028fde527) | Apr 20, 2023 |
| Lenovo        | ThinkPad X201 3626WNP       | [d642970071](https://bsd-hardware.info/?probe=d642970071) | Apr 19, 2023 |
| Packard Be... | DOT SE                      | [f456e964db](https://bsd-hardware.info/?probe=f456e964db) | Apr 19, 2023 |
| Dell          | Latitude 7410               | [d5c047907d](https://bsd-hardware.info/?probe=d5c047907d) | Apr 19, 2023 |
| Acer          | V5-131                      | [4c2332c3b8](https://bsd-hardware.info/?probe=4c2332c3b8) | Apr 19, 2023 |
| HP            | Unknown                     | [941c021569](https://bsd-hardware.info/?probe=941c021569) | Apr 18, 2023 |
| HP            | Laptop 14-dk1xxx            | [464059d8b1](https://bsd-hardware.info/?probe=464059d8b1) | Apr 18, 2023 |
| Medion        | E15302                      | [f47f32e1cc](https://bsd-hardware.info/?probe=f47f32e1cc) | Apr 17, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | [b8d2c0d81d](https://bsd-hardware.info/?probe=b8d2c0d81d) | Apr 16, 2023 |
| Apple         | MacBookPro11,5              | [4f6fb0c095](https://bsd-hardware.info/?probe=4f6fb0c095) | Apr 16, 2023 |
| Apple         | MacBookPro11,5              | [052f95c2a9](https://bsd-hardware.info/?probe=052f95c2a9) | Apr 16, 2023 |
| Toshiba       | PORTEGE R700                | [8b196955ac](https://bsd-hardware.info/?probe=8b196955ac) | Apr 15, 2023 |
| Apple         | MacBook3,1                  | [74986a169a](https://bsd-hardware.info/?probe=74986a169a) | Apr 15, 2023 |
| Dell          | Inspiron 3542               | [4dfa2f0148](https://bsd-hardware.info/?probe=4dfa2f0148) | Apr 15, 2023 |
| Unknown       | Unknown                     | [c221bccd5d](https://bsd-hardware.info/?probe=c221bccd5d) | Apr 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [b189b0988c](https://bsd-hardware.info/?probe=b189b0988c) | Apr 14, 2023 |
| Lenovo        | G570 20079                  | [0ebba481d1](https://bsd-hardware.info/?probe=0ebba481d1) | Apr 14, 2023 |
| Lenovo        | ThinkPad T440s 20ARA07PL... | [04ddab3620](https://bsd-hardware.info/?probe=04ddab3620) | Apr 14, 2023 |
| Lenovo        | ThinkPad R61 89208RU        | [e892cdffee](https://bsd-hardware.info/?probe=e892cdffee) | Apr 13, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [3d7bf4205b](https://bsd-hardware.info/?probe=3d7bf4205b) | Apr 13, 2023 |
| HMT           | W041-TF-A-45                | [298d106fd1](https://bsd-hardware.info/?probe=298d106fd1) | Apr 13, 2023 |
| Google        | Terra                       | [ef1619f65f](https://bsd-hardware.info/?probe=ef1619f65f) | Apr 13, 2023 |
| Google        | Terra                       | [bf598bc5bf](https://bsd-hardware.info/?probe=bf598bc5bf) | Apr 13, 2023 |
| Samsung       | 370E4K                      | [c363d008bf](https://bsd-hardware.info/?probe=c363d008bf) | Apr 13, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [bee20c6a4c](https://bsd-hardware.info/?probe=bee20c6a4c) | Apr 12, 2023 |
| Lenovo        | ThinkPad L540 20AUA34DJP    | [c7e40ee8ea](https://bsd-hardware.info/?probe=c7e40ee8ea) | Apr 12, 2023 |
| Lenovo        | ThinkPad X230 23257EP       | [e94085cd2d](https://bsd-hardware.info/?probe=e94085cd2d) | Apr 12, 2023 |
| Samsung       | N150/N210/N220              | [f6e5189f54](https://bsd-hardware.info/?probe=f6e5189f54) | Apr 11, 2023 |
| Lenovo        | ThinkPad X280 20KESB4T00    | [fb6c7b3b09](https://bsd-hardware.info/?probe=fb6c7b3b09) | Apr 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [add8280600](https://bsd-hardware.info/?probe=add8280600) | Apr 11, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X3C... | [0249b4e73f](https://bsd-hardware.info/?probe=0249b4e73f) | Apr 11, 2023 |
| Lenovo        | ThinkPad L540 20AUA34DJP    | [52aac5fc6f](https://bsd-hardware.info/?probe=52aac5fc6f) | Apr 11, 2023 |
| Unknown       | Unknown                     | [5bfbfb213e](https://bsd-hardware.info/?probe=5bfbfb213e) | Apr 09, 2023 |
| Fujitsu Si... | AMILO Li3710                | [6dabd5d84a](https://bsd-hardware.info/?probe=6dabd5d84a) | Apr 08, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [692b42afcd](https://bsd-hardware.info/?probe=692b42afcd) | Apr 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 34487... | [cec90ddd1b](https://bsd-hardware.info/?probe=cec90ddd1b) | Apr 08, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [f3ac765863](https://bsd-hardware.info/?probe=f3ac765863) | Apr 08, 2023 |
| Dell          | Latitude 7300               | [d036260cce](https://bsd-hardware.info/?probe=d036260cce) | Apr 08, 2023 |
| Dell          | XPS 13 9343                 | [8354aed46e](https://bsd-hardware.info/?probe=8354aed46e) | Apr 07, 2023 |
| Fujitsu       | CELSIUS H920                | [0551eecbcc](https://bsd-hardware.info/?probe=0551eecbcc) | Apr 06, 2023 |
| Acer          | Aspire 5250                 | [385751dbc3](https://bsd-hardware.info/?probe=385751dbc3) | Apr 06, 2023 |
| ASUSTek       | X200MA                      | [c30e92db89](https://bsd-hardware.info/?probe=c30e92db89) | Apr 06, 2023 |
| SIEMENS       | SIMATIC IPC127E             | [40a11e4c68](https://bsd-hardware.info/?probe=40a11e4c68) | Apr 06, 2023 |
| Fujitsu       | LIFEBOOK U810               | [3073cd605c](https://bsd-hardware.info/?probe=3073cd605c) | Apr 06, 2023 |
| Dell          | Inspiron 5567               | [a305360215](https://bsd-hardware.info/?probe=a305360215) | Apr 05, 2023 |
| IGEL Techn... | M340C                       | [6c8b2b7af7](https://bsd-hardware.info/?probe=6c8b2b7af7) | Apr 05, 2023 |
| Google        | Wolf                        | [2546416afd](https://bsd-hardware.info/?probe=2546416afd) | Apr 05, 2023 |
| HP            | Laptop 15-bw0xx             | [93ea83eef5](https://bsd-hardware.info/?probe=93ea83eef5) | Apr 03, 2023 |
| Fujitsu       | LIFEBOOK U810               | [c7718b4aa3](https://bsd-hardware.info/?probe=c7718b4aa3) | Apr 03, 2023 |
| Lenovo        | G570 20079                  | [76cc1653c3](https://bsd-hardware.info/?probe=76cc1653c3) | Apr 03, 2023 |
| Lenovo        | ThinkBook 14-IML 20RV       | [48b0a1024e](https://bsd-hardware.info/?probe=48b0a1024e) | Apr 02, 2023 |
| Apple         | MacBookPro12,1              | [640aad419a](https://bsd-hardware.info/?probe=640aad419a) | Apr 02, 2023 |
| Lenovo        | G50-30 80G0                 | [911a1723a2](https://bsd-hardware.info/?probe=911a1723a2) | Apr 02, 2023 |
| Lenovo        | ThinkPad T450s 20BW001KL... | [4f6a7e2739](https://bsd-hardware.info/?probe=4f6a7e2739) | Apr 02, 2023 |
| Lenovo        | ThinkPad T590 20N4001PUS    | [0b93ef8199](https://bsd-hardware.info/?probe=0b93ef8199) | Apr 02, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [9bac0139f1](https://bsd-hardware.info/?probe=9bac0139f1) | Apr 01, 2023 |
| ASUSTek       | X58C                        | [dad28a9d36](https://bsd-hardware.info/?probe=dad28a9d36) | Apr 01, 2023 |
| Chuwi         | Unknown                     | [5e687fcc83](https://bsd-hardware.info/?probe=5e687fcc83) | Apr 01, 2023 |
| Fujitsu       | CELSIUS H920                | [e6300dc691](https://bsd-hardware.info/?probe=e6300dc691) | Mar 31, 2023 |
| DNS           | W9x0LU                      | [6539659387](https://bsd-hardware.info/?probe=6539659387) | Mar 31, 2023 |
| HMT           | W041-TF-A-45                | [666df5a7e0](https://bsd-hardware.info/?probe=666df5a7e0) | Mar 31, 2023 |
| Acer          | Aspire 5745DG               | [2b8bf9802e](https://bsd-hardware.info/?probe=2b8bf9802e) | Mar 31, 2023 |
| Lenovo        | ThinkPad X220 4290DK6       | [96c83a2846](https://bsd-hardware.info/?probe=96c83a2846) | Mar 31, 2023 |
| Deciso        | NetBoard-A20                | [33ca458105](https://bsd-hardware.info/?probe=33ca458105) | Mar 30, 2023 |
| Intel         | Intel                       | [75e9733afd](https://bsd-hardware.info/?probe=75e9733afd) | Mar 30, 2023 |
| Toshiba       | Satellite L675D             | [0bf578daec](https://bsd-hardware.info/?probe=0bf578daec) | Mar 30, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [ff14982ad9](https://bsd-hardware.info/?probe=ff14982ad9) | Mar 29, 2023 |
| Dell          | Latitude 5590               | [7e87d436df](https://bsd-hardware.info/?probe=7e87d436df) | Mar 29, 2023 |
| Google        | Stout                       | [d8346bb5da](https://bsd-hardware.info/?probe=d8346bb5da) | Mar 29, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [0af5cebe20](https://bsd-hardware.info/?probe=0af5cebe20) | Mar 29, 2023 |
| Lenovo        | ThinkPad X230 23255NG       | [2ef93a7621](https://bsd-hardware.info/?probe=2ef93a7621) | Mar 29, 2023 |
| Dell          | Inspiron 5547               | [4f4f6e06d7](https://bsd-hardware.info/?probe=4f4f6e06d7) | Mar 29, 2023 |
| Unknown       | Unknown                     | [2a50573c9f](https://bsd-hardware.info/?probe=2a50573c9f) | Mar 29, 2023 |
| Lenovo        | ThinkPad T540p 20BFS10W0... | [30c5fc2625](https://bsd-hardware.info/?probe=30c5fc2625) | Mar 29, 2023 |
| Irbis         | NB78                        | [471efbc788](https://bsd-hardware.info/?probe=471efbc788) | Mar 29, 2023 |
| Unknown       | Unknown                     | [ee06e14aa2](https://bsd-hardware.info/?probe=ee06e14aa2) | Mar 29, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [f4e450fed1](https://bsd-hardware.info/?probe=f4e450fed1) | Mar 29, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [dddf27cde4](https://bsd-hardware.info/?probe=dddf27cde4) | Mar 28, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [c2ba6aca7d](https://bsd-hardware.info/?probe=c2ba6aca7d) | Mar 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [fb4eec9c34](https://bsd-hardware.info/?probe=fb4eec9c34) | Mar 27, 2023 |
| HP            | Pavilion dv6                | [ce2cc6852d](https://bsd-hardware.info/?probe=ce2cc6852d) | Mar 27, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [b4805cd318](https://bsd-hardware.info/?probe=b4805cd318) | Mar 27, 2023 |
| LG Electro... | COLUMBIA                    | [4872f6c377](https://bsd-hardware.info/?probe=4872f6c377) | Mar 27, 2023 |
| Dell          | Inspiron 7437               | [2c4de59558](https://bsd-hardware.info/?probe=2c4de59558) | Mar 27, 2023 |
| Lenovo        | IdeaPad S210 20256          | [2e22ee87c3](https://bsd-hardware.info/?probe=2e22ee87c3) | Mar 27, 2023 |
| Lenovo        | ThinkPad T410 2518A37       | [f5537face6](https://bsd-hardware.info/?probe=f5537face6) | Mar 27, 2023 |
| Lenovo        | ThinkPad T430 2349G5P       | [9ea67d3893](https://bsd-hardware.info/?probe=9ea67d3893) | Mar 27, 2023 |
| Dell          | Latitude 5420               | [4e22bbc131](https://bsd-hardware.info/?probe=4e22bbc131) | Mar 26, 2023 |
| LG Electro... | E500-L.A2M4A2               | [8dab794233](https://bsd-hardware.info/?probe=8dab794233) | Mar 26, 2023 |
| Dell          | Inspiron 5559               | [7652c9891e](https://bsd-hardware.info/?probe=7652c9891e) | Mar 26, 2023 |
| HP            | EliteBook Folio 9470m       | [ea2865cbf5](https://bsd-hardware.info/?probe=ea2865cbf5) | Mar 26, 2023 |
| Samsung       | R468/R418                   | [f620a5c6ec](https://bsd-hardware.info/?probe=f620a5c6ec) | Mar 25, 2023 |
| MouseCompu... | X5-aR5CEZAR-WA              | [b960dc3bde](https://bsd-hardware.info/?probe=b960dc3bde) | Mar 25, 2023 |
| Lenovo        | ThinkPad X220 4291AN9       | [1646bb53ab](https://bsd-hardware.info/?probe=1646bb53ab) | Mar 25, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [7df625b1df](https://bsd-hardware.info/?probe=7df625b1df) | Mar 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [a46f77ccdc](https://bsd-hardware.info/?probe=a46f77ccdc) | Mar 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b64571464f](https://bsd-hardware.info/?probe=b64571464f) | Mar 25, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | [8e798ca6ef](https://bsd-hardware.info/?probe=8e798ca6ef) | Mar 25, 2023 |
| eMachines     | eM350                       | [bb900ace2d](https://bsd-hardware.info/?probe=bb900ace2d) | Mar 25, 2023 |
| Alienware     | 14                          | [742d648570](https://bsd-hardware.info/?probe=742d648570) | Mar 25, 2023 |
| Acer          | AOD270                      | [73877008e9](https://bsd-hardware.info/?probe=73877008e9) | Mar 25, 2023 |
| Lenovo        | ThinkPad W541 20EF000NUS    | [34b156c20c](https://bsd-hardware.info/?probe=34b156c20c) | Mar 24, 2023 |
| MouseCompu... | X5-aR5CEZAR-WA              | [4cd1097c65](https://bsd-hardware.info/?probe=4cd1097c65) | Mar 24, 2023 |
| Intel         | H81U                        | [af9a6469c9](https://bsd-hardware.info/?probe=af9a6469c9) | Mar 24, 2023 |
| Dell          | G5 5587                     | [9b7714cbab](https://bsd-hardware.info/?probe=9b7714cbab) | Mar 24, 2023 |
| Dell          | G5 5587                     | [c118e0665f](https://bsd-hardware.info/?probe=c118e0665f) | Mar 24, 2023 |
| Dell          | Latitude 5500               | [8db518ef3d](https://bsd-hardware.info/?probe=8db518ef3d) | Mar 24, 2023 |
| Acer          | Aspire F5-573G              | [a8f794f3fb](https://bsd-hardware.info/?probe=a8f794f3fb) | Mar 24, 2023 |
| Acer          | Nitro AN515-53              | [a46e065fac](https://bsd-hardware.info/?probe=a46e065fac) | Mar 23, 2023 |
| Dell          | Inspiron 5559               | [f294f7ae04](https://bsd-hardware.info/?probe=f294f7ae04) | Mar 23, 2023 |
| Intel         | SandyBridge Platform        | [954a21f7de](https://bsd-hardware.info/?probe=954a21f7de) | Mar 23, 2023 |
| Lenovo        | ThinkPad T410 2518A37       | [42fffdf3f2](https://bsd-hardware.info/?probe=42fffdf3f2) | Mar 23, 2023 |
| Lenovo        | ThinkPad T61 7658CTO        | [f00e571f76](https://bsd-hardware.info/?probe=f00e571f76) | Mar 23, 2023 |
| Lenovo        | ThinkPad T430s 2356CV6      | [d9efc1e30b](https://bsd-hardware.info/?probe=d9efc1e30b) | Mar 22, 2023 |
| ASUSTek       | X71Vn                       | [6e96ea55ee](https://bsd-hardware.info/?probe=6e96ea55ee) | Mar 22, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [136a6641be](https://bsd-hardware.info/?probe=136a6641be) | Mar 21, 2023 |
| Lenovo        | ThinkPad X230 232578G       | [edf47cb2d4](https://bsd-hardware.info/?probe=edf47cb2d4) | Mar 21, 2023 |
| Lenovo        | ThinkPad T61 7659CA1        | [bba228ddc9](https://bsd-hardware.info/?probe=bba228ddc9) | Mar 20, 2023 |
| Lenovo        | G500 20236                  | [55dc82af1c](https://bsd-hardware.info/?probe=55dc82af1c) | Mar 20, 2023 |
| HUAWEI        | HVY-WXX9                    | [e1b5d66244](https://bsd-hardware.info/?probe=e1b5d66244) | Mar 20, 2023 |
| ASUSTek       | 1015PX                      | [d6c1199165](https://bsd-hardware.info/?probe=d6c1199165) | Mar 20, 2023 |
| Lenovo        | ThinkPad E595 20NF0002BM    | [83ee1d297d](https://bsd-hardware.info/?probe=83ee1d297d) | Mar 20, 2023 |
| ASUSTek       | K501UQ                      | [b7256fddbb](https://bsd-hardware.info/?probe=b7256fddbb) | Mar 19, 2023 |
| Apple         | MacBookPro5,1               | [9e300b5797](https://bsd-hardware.info/?probe=9e300b5797) | Mar 19, 2023 |
| MECHREVO S... | S1 Series                   | [58ae2c4605](https://bsd-hardware.info/?probe=58ae2c4605) | Mar 19, 2023 |
| Toshiba       | Satellite P300              | [81b7ca608e](https://bsd-hardware.info/?probe=81b7ca608e) | Mar 19, 2023 |
| Lenovo        | ThinkPad T520 4242PN3       | [3ea33f0cad](https://bsd-hardware.info/?probe=3ea33f0cad) | Mar 19, 2023 |
| ASUSTek       | G750JS                      | [bb6117addd](https://bsd-hardware.info/?probe=bb6117addd) | Mar 19, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [e35600705f](https://bsd-hardware.info/?probe=e35600705f) | Mar 19, 2023 |
| Samsung       | R520/R522/R620              | [096d52b83d](https://bsd-hardware.info/?probe=096d52b83d) | Mar 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [be9a45f529](https://bsd-hardware.info/?probe=be9a45f529) | Mar 18, 2023 |
| HP            | ProBook 640 G3              | [860471150b](https://bsd-hardware.info/?probe=860471150b) | Mar 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [a365a5b411](https://bsd-hardware.info/?probe=a365a5b411) | Mar 18, 2023 |
| Apple         | MacBook4,1                  | [6f2790802d](https://bsd-hardware.info/?probe=6f2790802d) | Mar 18, 2023 |
| Lenovo        | ThinkPad A275 20KCS07010    | [4d6daf66c1](https://bsd-hardware.info/?probe=4d6daf66c1) | Mar 18, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [c83b0dda87](https://bsd-hardware.info/?probe=c83b0dda87) | Mar 18, 2023 |
| Fujitsu       | LIFEBOOK AH530              | [50a5ed6b41](https://bsd-hardware.info/?probe=50a5ed6b41) | Mar 18, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [9ac4738956](https://bsd-hardware.info/?probe=9ac4738956) | Mar 18, 2023 |
| Dell          | Inspiron 5559               | [705ac0b37f](https://bsd-hardware.info/?probe=705ac0b37f) | Mar 18, 2023 |
| IGEL Techn... | M350C                       | [a04efafd2e](https://bsd-hardware.info/?probe=a04efafd2e) | Mar 18, 2023 |
| Dell          | Inspiron 5559               | [dcab531d1e](https://bsd-hardware.info/?probe=dcab531d1e) | Mar 18, 2023 |
| HP            | Pavilion dv5                | [113fe74799](https://bsd-hardware.info/?probe=113fe74799) | Mar 18, 2023 |
| IP3 Techno... | ACN1S                       | [d0761f4192](https://bsd-hardware.info/?probe=d0761f4192) | Mar 18, 2023 |
| HP            | EliteBook 850 G2            | [653dbe54a4](https://bsd-hardware.info/?probe=653dbe54a4) | Mar 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [6d9c564a33](https://bsd-hardware.info/?probe=6d9c564a33) | Mar 17, 2023 |
| Intel         | S1200RP_SE                  | [5ae9400f0b](https://bsd-hardware.info/?probe=5ae9400f0b) | Mar 17, 2023 |
| Lenovo        | ThinkPad T440p              | [575123c3ac](https://bsd-hardware.info/?probe=575123c3ac) | Mar 17, 2023 |
| Dell          | Inspiron 3442               | [cbb9f6bfbb](https://bsd-hardware.info/?probe=cbb9f6bfbb) | Mar 17, 2023 |
| Dell          | Latitude E5570              | [8b9aa95420](https://bsd-hardware.info/?probe=8b9aa95420) | Mar 17, 2023 |
| Toshiba       | Satellite L40               | [2297dcb7e7](https://bsd-hardware.info/?probe=2297dcb7e7) | Mar 17, 2023 |
| Dell          | Latitude E5570              | [937a7c9385](https://bsd-hardware.info/?probe=937a7c9385) | Mar 17, 2023 |
| Lenovo        | ThinkPad X201 36801T6       | [decaf0c347](https://bsd-hardware.info/?probe=decaf0c347) | Mar 17, 2023 |
| OEGStone      | W54_55SU1,SUW               | [7a2b28c47f](https://bsd-hardware.info/?probe=7a2b28c47f) | Mar 17, 2023 |
| Lenovo        | ThinkPad X61s 7667WQS       | [f1351003d1](https://bsd-hardware.info/?probe=f1351003d1) | Mar 17, 2023 |
| Dell          | Inspiron 5557               | [ff199c6d21](https://bsd-hardware.info/?probe=ff199c6d21) | Mar 16, 2023 |
| HP            | Unknown                     | [0b79535c7f](https://bsd-hardware.info/?probe=0b79535c7f) | Mar 16, 2023 |
| ASUSTek       | 1001P                       | [76eae56ba3](https://bsd-hardware.info/?probe=76eae56ba3) | Mar 15, 2023 |
| OEGStone      | W54_55SU1,SUW               | [64316408f0](https://bsd-hardware.info/?probe=64316408f0) | Mar 15, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [564b1ccce1](https://bsd-hardware.info/?probe=564b1ccce1) | Mar 15, 2023 |
| Acer          | Aspire E5-571G              | [ca34dac813](https://bsd-hardware.info/?probe=ca34dac813) | Mar 15, 2023 |
| Samsung       | 275E4E/275E5E               | [dd4f7ef594](https://bsd-hardware.info/?probe=dd4f7ef594) | Mar 15, 2023 |
| HP            | Pavilion TS Sleekbook 14    | [d57e5b1b88](https://bsd-hardware.info/?probe=d57e5b1b88) | Mar 15, 2023 |
| Acer          | Aspire V3-112P              | [104c10f9b0](https://bsd-hardware.info/?probe=104c10f9b0) | Mar 14, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [89a5ee25f9](https://bsd-hardware.info/?probe=89a5ee25f9) | Mar 14, 2023 |
| Acer          | TravelMate P249-G2-M        | [090f37a821](https://bsd-hardware.info/?probe=090f37a821) | Mar 14, 2023 |
| Dell          | Latitude D630               | [da1fa73418](https://bsd-hardware.info/?probe=da1fa73418) | Mar 14, 2023 |
| HP            | Laptop 14-bs0xx             | [cd76713b75](https://bsd-hardware.info/?probe=cd76713b75) | Mar 14, 2023 |
| Dynabook E... | Satellite Pro E10-G-101     | [c58a37ef03](https://bsd-hardware.info/?probe=c58a37ef03) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3448A... | [eaaf0fc8c7](https://bsd-hardware.info/?probe=eaaf0fc8c7) | Mar 14, 2023 |
| Toshiba       | Satellite L50-B             | [7052b38ba8](https://bsd-hardware.info/?probe=7052b38ba8) | Mar 14, 2023 |
| Lenovo        | ThinkPad L450 20DSS1S402    | [b4893ae18f](https://bsd-hardware.info/?probe=b4893ae18f) | Mar 14, 2023 |
| Toshiba       | Satellite A200              | [c49985d00b](https://bsd-hardware.info/?probe=c49985d00b) | Mar 13, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | [d9d7368322](https://bsd-hardware.info/?probe=d9d7368322) | Mar 13, 2023 |
| Dell          | Inspiron 5567               | [b878473783](https://bsd-hardware.info/?probe=b878473783) | Mar 13, 2023 |
| Acer          | Swift SF314-56              | [94c7da1b3f](https://bsd-hardware.info/?probe=94c7da1b3f) | Mar 13, 2023 |
| Acer          | Nitro AN515-55              | [e023282dcd](https://bsd-hardware.info/?probe=e023282dcd) | Mar 13, 2023 |
| Samsung       | R468/R418                   | [af44a29d38](https://bsd-hardware.info/?probe=af44a29d38) | Mar 13, 2023 |
| Dell          | Inspiron 7520               | [8b259d99ec](https://bsd-hardware.info/?probe=8b259d99ec) | Mar 13, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [5ce3dfe4a2](https://bsd-hardware.info/?probe=5ce3dfe4a2) | Mar 13, 2023 |
| Lenovo        | ThinkPad X200 74591P0       | [882cc7fc62](https://bsd-hardware.info/?probe=882cc7fc62) | Mar 13, 2023 |
| ASUSTek       | G74Sx                       | [6b7cf8fcac](https://bsd-hardware.info/?probe=6b7cf8fcac) | Mar 13, 2023 |
| Lenovo        | ThinkPad E495 20NEA00QUS    | [8b112aa100](https://bsd-hardware.info/?probe=8b112aa100) | Mar 13, 2023 |
| Toshiba       | Satellite C845              | [0b680543b7](https://bsd-hardware.info/?probe=0b680543b7) | Mar 13, 2023 |
| Sony          | VGN-FZ19VN                  | [73809d943a](https://bsd-hardware.info/?probe=73809d943a) | Mar 13, 2023 |
| Dell          | Inspiron 5567               | [b2ef9ff3dc](https://bsd-hardware.info/?probe=b2ef9ff3dc) | Mar 12, 2023 |
| Fujitsu       | LIFEBOOK E736               | [1040a34321](https://bsd-hardware.info/?probe=1040a34321) | Mar 12, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [9c1172aa29](https://bsd-hardware.info/?probe=9c1172aa29) | Mar 12, 2023 |
| HP            | Laptop 14-bs1xx             | [99446c8dd0](https://bsd-hardware.info/?probe=99446c8dd0) | Mar 12, 2023 |
| Lenovo        | ThinkPad X200 2024AY7       | [bb432faf36](https://bsd-hardware.info/?probe=bb432faf36) | Mar 12, 2023 |
| Lenovo        | ZIUS6                       | [d387825f01](https://bsd-hardware.info/?probe=d387825f01) | Mar 12, 2023 |
| Dell          | Latitude E6330              | [5c60cd3d04](https://bsd-hardware.info/?probe=5c60cd3d04) | Mar 12, 2023 |
| Lenovo        | ThinkPad T440p              | [6d372db804](https://bsd-hardware.info/?probe=6d372db804) | Mar 12, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [5bcd236c4a](https://bsd-hardware.info/?probe=5bcd236c4a) | Mar 12, 2023 |
| Deciso        | OPNsense Appliance          | [faebab61f2](https://bsd-hardware.info/?probe=faebab61f2) | Mar 12, 2023 |
| Google        | Kohaku                      | [88491d298e](https://bsd-hardware.info/?probe=88491d298e) | Mar 12, 2023 |
| Acer          | Nitro AN515-54              | [6e97a003ec](https://bsd-hardware.info/?probe=6e97a003ec) | Mar 12, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | [80dd48bca9](https://bsd-hardware.info/?probe=80dd48bca9) | Mar 12, 2023 |
| Dell          | Precision 7720              | [01f5f21b76](https://bsd-hardware.info/?probe=01f5f21b76) | Mar 12, 2023 |
| Acer          | Swift SF314-42              | [aa89c48cb7](https://bsd-hardware.info/?probe=aa89c48cb7) | Mar 12, 2023 |
| Apple         | MacBookAir1,1               | [2142f08b3f](https://bsd-hardware.info/?probe=2142f08b3f) | Mar 12, 2023 |
| HP            | Laptop 15-bs1xx             | [1df045ffd0](https://bsd-hardware.info/?probe=1df045ffd0) | Mar 11, 2023 |
| Lenovo        | ThinkPad T480s 20L8002WM... | [aa70f61a87](https://bsd-hardware.info/?probe=aa70f61a87) | Mar 11, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2BR0... | [56fa0d4656](https://bsd-hardware.info/?probe=56fa0d4656) | Mar 11, 2023 |
| Dell          | Latitude E5450              | [4bb2040221](https://bsd-hardware.info/?probe=4bb2040221) | Mar 11, 2023 |
| Lenovo        | ThinkPad L590 20Q7U04602    | [64a11e18da](https://bsd-hardware.info/?probe=64a11e18da) | Mar 11, 2023 |
| Star Labs     | StarBook                    | [80f6445f54](https://bsd-hardware.info/?probe=80f6445f54) | Mar 10, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | [a4366e53ba](https://bsd-hardware.info/?probe=a4366e53ba) | Mar 10, 2023 |
| Fujitsu       | FMVA532BSJ                  | [695e38d0ea](https://bsd-hardware.info/?probe=695e38d0ea) | Mar 10, 2023 |
| Intel         | Jasper Lake Client Platf... | [88de48013c](https://bsd-hardware.info/?probe=88de48013c) | Mar 10, 2023 |
| Intel         | Jasper Lake Client Platf... | [de93a79b7d](https://bsd-hardware.info/?probe=de93a79b7d) | Mar 10, 2023 |
| Lenovo        | ThinkPad T495 20NKS0HN1N    | [af190c38e9](https://bsd-hardware.info/?probe=af190c38e9) | Mar 10, 2023 |
| Lenovo        | ThinkPad T470 20HES0EV0A    | [dd6c3fa0f7](https://bsd-hardware.info/?probe=dd6c3fa0f7) | Mar 10, 2023 |
| Fujitsu       | CELSIUS H730                | [d2292bbcda](https://bsd-hardware.info/?probe=d2292bbcda) | Mar 10, 2023 |
| Fujitsu       | CELSIUS H730                | [223879138d](https://bsd-hardware.info/?probe=223879138d) | Mar 10, 2023 |
| Lenovo        | ThinkPad X230 23252G8       | [2ff46d6b7c](https://bsd-hardware.info/?probe=2ff46d6b7c) | Mar 10, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [e5a43dd311](https://bsd-hardware.info/?probe=e5a43dd311) | Mar 10, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | [44a8bf8fbc](https://bsd-hardware.info/?probe=44a8bf8fbc) | Mar 10, 2023 |
| HP            | EliteBook 2530p             | [e70d97f7d6](https://bsd-hardware.info/?probe=e70d97f7d6) | Mar 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [278a2a11cd](https://bsd-hardware.info/?probe=278a2a11cd) | Mar 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [ef85735453](https://bsd-hardware.info/?probe=ef85735453) | Mar 09, 2023 |
| Dell          | Latitude D620               | [8b3ad4e8b9](https://bsd-hardware.info/?probe=8b3ad4e8b9) | Mar 09, 2023 |
| Dell          | Latitude D620               | [d42a8ee079](https://bsd-hardware.info/?probe=d42a8ee079) | Mar 09, 2023 |
| Samsung       | 750XEE                      | [47d2204f58](https://bsd-hardware.info/?probe=47d2204f58) | Mar 08, 2023 |
| Lenovo        | ThinkPad X230 2324A14       | [124b3bdb95](https://bsd-hardware.info/?probe=124b3bdb95) | Mar 08, 2023 |
| Clevo         | W240EL/W250ELQ/W270ELQ      | [aafc670aa7](https://bsd-hardware.info/?probe=aafc670aa7) | Mar 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3444F... | [1a31b27b2a](https://bsd-hardware.info/?probe=1a31b27b2a) | Mar 08, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [9466e6d4f4](https://bsd-hardware.info/?probe=9466e6d4f4) | Mar 07, 2023 |
| Deciso        | OPNsense Appliance          | [1cca4a556d](https://bsd-hardware.info/?probe=1cca4a556d) | Mar 07, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [1a2543f92f](https://bsd-hardware.info/?probe=1a2543f92f) | Mar 06, 2023 |
| ASUSTek       | 1201N                       | [5dc595eb79](https://bsd-hardware.info/?probe=5dc595eb79) | Mar 05, 2023 |
| ASUSTek       | 1201N                       | [daa787f637](https://bsd-hardware.info/?probe=daa787f637) | Mar 05, 2023 |
| Lenovo        | G400s 20244                 | [215f16c5d9](https://bsd-hardware.info/?probe=215f16c5d9) | Mar 05, 2023 |
| Lenovo        | IdeaPad 310-14IKB 80TU      | [8037475831](https://bsd-hardware.info/?probe=8037475831) | Mar 05, 2023 |
| HP            | EliteBook 2730p             | [3c404c9d20](https://bsd-hardware.info/?probe=3c404c9d20) | Mar 05, 2023 |
| Acer          | TravelMate TX50-G2          | [81ab6d240f](https://bsd-hardware.info/?probe=81ab6d240f) | Mar 05, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E0T    | [6d7b30d2c4](https://bsd-hardware.info/?probe=6d7b30d2c4) | Mar 03, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [f9db95d778](https://bsd-hardware.info/?probe=f9db95d778) | Mar 03, 2023 |
| HP            | G62                         | [18487b3ab2](https://bsd-hardware.info/?probe=18487b3ab2) | Mar 02, 2023 |
| Sony          | SVE1511C5E                  | [0e972db389](https://bsd-hardware.info/?probe=0e972db389) | Mar 02, 2023 |
| Sony          | SVE1511C5E                  | [6aa87871c2](https://bsd-hardware.info/?probe=6aa87871c2) | Mar 01, 2023 |
| Deciso        | NetBoard-A10                | [ca59a5e6f4](https://bsd-hardware.info/?probe=ca59a5e6f4) | Feb 28, 2023 |
| HP            | 240 G6 Notebook PC          | [d872652e25](https://bsd-hardware.info/?probe=d872652e25) | Feb 28, 2023 |
| Lenovo        | ThinkPad T430 2349S31       | [2b13f68cd6](https://bsd-hardware.info/?probe=2b13f68cd6) | Feb 28, 2023 |
| Lenovo        | ThinkPad T480s 20L7002CU... | [0e051e7291](https://bsd-hardware.info/?probe=0e051e7291) | Feb 27, 2023 |
| Notebook      | N2x0WU                      | [9545f36dee](https://bsd-hardware.info/?probe=9545f36dee) | Feb 27, 2023 |
| ASUSTek       | X541SA                      | [9d406d735e](https://bsd-hardware.info/?probe=9d406d735e) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [115bd3bc38](https://bsd-hardware.info/?probe=115bd3bc38) | Feb 26, 2023 |
| HP            | EliteBook 8570p             | [1a4897cb53](https://bsd-hardware.info/?probe=1a4897cb53) | Feb 26, 2023 |
| Dell          | Inspiron 15 3515            | [b480a98b22](https://bsd-hardware.info/?probe=b480a98b22) | Feb 26, 2023 |
| Acer          | Aspire ES1-571              | [d736d59649](https://bsd-hardware.info/?probe=d736d59649) | Feb 26, 2023 |
| Acer          | Aspire ES1-571              | [48aa652a09](https://bsd-hardware.info/?probe=48aa652a09) | Feb 26, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | [59e609fbb2](https://bsd-hardware.info/?probe=59e609fbb2) | Feb 26, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [2ab690000c](https://bsd-hardware.info/?probe=2ab690000c) | Feb 25, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [ae0dc68ba6](https://bsd-hardware.info/?probe=ae0dc68ba6) | Feb 25, 2023 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | [45549e4faf](https://bsd-hardware.info/?probe=45549e4faf) | Feb 25, 2023 |
| Toshiba       | dynabook R63/P              | [c41c3adfa4](https://bsd-hardware.info/?probe=c41c3adfa4) | Feb 25, 2023 |
| Lenovo        | ThinkPad T440s 20AQ005SU... | [7750c38cd0](https://bsd-hardware.info/?probe=7750c38cd0) | Feb 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [b3e56e9656](https://bsd-hardware.info/?probe=b3e56e9656) | Feb 25, 2023 |
| Dell          | Latitude 5591               | [fb33d7a0c4](https://bsd-hardware.info/?probe=fb33d7a0c4) | Feb 25, 2023 |
| HP            | EliteBook 840 G1            | [0480ce43f2](https://bsd-hardware.info/?probe=0480ce43f2) | Feb 24, 2023 |
| Lenovo        | ThinkPad T530 24297XG       | [97d9b10c8a](https://bsd-hardware.info/?probe=97d9b10c8a) | Feb 24, 2023 |
| HP            | EliteBook 8570p             | [1e548fa114](https://bsd-hardware.info/?probe=1e548fa114) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [95c66df5a4](https://bsd-hardware.info/?probe=95c66df5a4) | Feb 24, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [aef791947c](https://bsd-hardware.info/?probe=aef791947c) | Feb 23, 2023 |
| Lenovo        | ThinkPad X280 20KFCTO1WW    | [3dae7e3ebb](https://bsd-hardware.info/?probe=3dae7e3ebb) | Feb 23, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [6669622646](https://bsd-hardware.info/?probe=6669622646) | Feb 23, 2023 |
| Deciso        | NetBoard-A20                | [d23ae47425](https://bsd-hardware.info/?probe=d23ae47425) | Feb 23, 2023 |
| Plaisio       | Turbo X                     | [e0a8a02bb9](https://bsd-hardware.info/?probe=e0a8a02bb9) | Feb 23, 2023 |
| Lenovo        | ThinkPad T440 20B60061MB    | [16a141cc35](https://bsd-hardware.info/?probe=16a141cc35) | Feb 23, 2023 |
| HP            | EliteBook 840 G1            | [77c17e4a2f](https://bsd-hardware.info/?probe=77c17e4a2f) | Feb 22, 2023 |
| Lenovo        | ThinkPad T460 20FMS06V00    | [7d7fa2bbc9](https://bsd-hardware.info/?probe=7d7fa2bbc9) | Feb 22, 2023 |
| Lenovo        | ThinkPad T440 20B60061MB    | [4867945cfb](https://bsd-hardware.info/?probe=4867945cfb) | Feb 22, 2023 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [d04d402809](https://bsd-hardware.info/?probe=d04d402809) | Feb 21, 2023 |
| Deciso        | Netboard A20                | [25077b7e64](https://bsd-hardware.info/?probe=25077b7e64) | Feb 21, 2023 |
| HP            | ZBook 15 G3                 | [ff6ddb74bb](https://bsd-hardware.info/?probe=ff6ddb74bb) | Feb 21, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [b2ed608da5](https://bsd-hardware.info/?probe=b2ed608da5) | Feb 21, 2023 |
| Lenovo        | ThinkPad L450 20DSS1S402    | [06e5309c55](https://bsd-hardware.info/?probe=06e5309c55) | Feb 20, 2023 |
| Lenovo        | ThinkPad T410 2537B94       | [9f9cb3e201](https://bsd-hardware.info/?probe=9f9cb3e201) | Feb 19, 2023 |
| Lenovo        | ThinkPad T460 20FMS3320G    | [c85f94d574](https://bsd-hardware.info/?probe=c85f94d574) | Feb 19, 2023 |
| Acer          | Aspire E1-421               | [db00abb833](https://bsd-hardware.info/?probe=db00abb833) | Feb 19, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [92bca4d026](https://bsd-hardware.info/?probe=92bca4d026) | Feb 19, 2023 |
| Lenovo        | G400s 20244                 | [f2c258a0ae](https://bsd-hardware.info/?probe=f2c258a0ae) | Feb 19, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | [d8ba5b3157](https://bsd-hardware.info/?probe=d8ba5b3157) | Feb 19, 2023 |
| Gigabyte      | GB-BSi3A-6100               | [e7ef795b9b](https://bsd-hardware.info/?probe=e7ef795b9b) | Feb 19, 2023 |
| Gigabyte      | GB-BSi3A-6100               | [cd2273037f](https://bsd-hardware.info/?probe=cd2273037f) | Feb 19, 2023 |
| Acer          | Aspire 7738                 | [e61cd20061](https://bsd-hardware.info/?probe=e61cd20061) | Feb 18, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | [820596f359](https://bsd-hardware.info/?probe=820596f359) | Feb 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [63b73012e6](https://bsd-hardware.info/?probe=63b73012e6) | Feb 18, 2023 |
| HP            | EliteBook 8570p             | [1ba2a827d9](https://bsd-hardware.info/?probe=1ba2a827d9) | Feb 18, 2023 |
| Lenovo        | ThinkPad W520 427638U       | [baa0e928a8](https://bsd-hardware.info/?probe=baa0e928a8) | Feb 18, 2023 |
| Dell          | Inspiron 5767               | [39b4581223](https://bsd-hardware.info/?probe=39b4581223) | Feb 18, 2023 |
| Lenovo        | ThinkPad T61p 6457UN2       | [67b2e8db2b](https://bsd-hardware.info/?probe=67b2e8db2b) | Feb 18, 2023 |
| Dell          | Inspiron 5767               | [fd58d235b3](https://bsd-hardware.info/?probe=fd58d235b3) | Feb 18, 2023 |
| Lenovo        | ThinkPad T61p 6457UN2       | [f7646f9d7f](https://bsd-hardware.info/?probe=f7646f9d7f) | Feb 18, 2023 |
| IGEL Techn... | H830C                       | [069249225f](https://bsd-hardware.info/?probe=069249225f) | Feb 17, 2023 |
| Lenovo        | ThinkPad R60e 0658W2M       | [dba66ebfb5](https://bsd-hardware.info/?probe=dba66ebfb5) | Feb 17, 2023 |
| Lenovo        | ThinkPad T430u 33522D5      | [d5bbbb8cbe](https://bsd-hardware.info/?probe=d5bbbb8cbe) | Feb 17, 2023 |
| Apple         | MacBookPro11,1              | [673f6c0a01](https://bsd-hardware.info/?probe=673f6c0a01) | Feb 17, 2023 |
| Google        | Lulu                        | [cf598483cf](https://bsd-hardware.info/?probe=cf598483cf) | Feb 17, 2023 |
| Lenovo        | ThinkPad 13 20GJCTO1WW      | [59713ca193](https://bsd-hardware.info/?probe=59713ca193) | Feb 15, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [0f4dd9a9bc](https://bsd-hardware.info/?probe=0f4dd9a9bc) | Feb 15, 2023 |
| Deciso        | OPNsense Appliance          | [1eda4c5b48](https://bsd-hardware.info/?probe=1eda4c5b48) | Feb 15, 2023 |
| Deciso        | NetBoard-A20                | [ffc9e123b4](https://bsd-hardware.info/?probe=ffc9e123b4) | Feb 14, 2023 |
| Deciso        | Netboard A20                | [7c91a0f01b](https://bsd-hardware.info/?probe=7c91a0f01b) | Feb 14, 2023 |
| Lenovo        | ThinkPad T430 2347FV6       | [cf016ce514](https://bsd-hardware.info/?probe=cf016ce514) | Feb 14, 2023 |
| HP            | OMEN by Gaming Laptop 16... | [00142b4e4c](https://bsd-hardware.info/?probe=00142b4e4c) | Feb 14, 2023 |
| MECHREVO S... | S1 Series                   | [26c3b9bf4f](https://bsd-hardware.info/?probe=26c3b9bf4f) | Feb 14, 2023 |
| MECHREVO S... | S1 Series                   | [1d948a1a23](https://bsd-hardware.info/?probe=1d948a1a23) | Feb 14, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [c176577762](https://bsd-hardware.info/?probe=c176577762) | Feb 14, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | [9137c7933c](https://bsd-hardware.info/?probe=9137c7933c) | Feb 13, 2023 |
| Acer          | Aspire one V1.05            | [eec371a28f](https://bsd-hardware.info/?probe=eec371a28f) | Feb 13, 2023 |
| Dell          | Inspiron 5567               | [df5f01d72e](https://bsd-hardware.info/?probe=df5f01d72e) | Feb 13, 2023 |
| Panasonic     | CF-30KAPAXAM                | [f686e3756c](https://bsd-hardware.info/?probe=f686e3756c) | Feb 13, 2023 |
| Shuttle       | DS437T                      | [9a16ad9fec](https://bsd-hardware.info/?probe=9a16ad9fec) | Feb 12, 2023 |
| Alienware     | m15                         | [3ab3e4b671](https://bsd-hardware.info/?probe=3ab3e4b671) | Feb 12, 2023 |
| HP            | ProBook 450 G2              | [acff807555](https://bsd-hardware.info/?probe=acff807555) | Feb 12, 2023 |
| Lenovo        | ThinkPad W520 42844DG       | [d341f3c6f6](https://bsd-hardware.info/?probe=d341f3c6f6) | Feb 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [8d49d50738](https://bsd-hardware.info/?probe=8d49d50738) | Feb 11, 2023 |
| Unknown       | Unknown                     | [c2735d8120](https://bsd-hardware.info/?probe=c2735d8120) | Feb 11, 2023 |
| Apple         | MacBookAir6,1               | [96fa5325d1](https://bsd-hardware.info/?probe=96fa5325d1) | Feb 11, 2023 |
| Acer          | Aspire A315-58              | [81827ccbca](https://bsd-hardware.info/?probe=81827ccbca) | Feb 10, 2023 |
| MSI           | GF76 12UE                   | [371f734e07](https://bsd-hardware.info/?probe=371f734e07) | Feb 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [a9928bd16e](https://bsd-hardware.info/?probe=a9928bd16e) | Feb 10, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [0c9cf4e002](https://bsd-hardware.info/?probe=0c9cf4e002) | Feb 09, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [ca1e51a042](https://bsd-hardware.info/?probe=ca1e51a042) | Feb 09, 2023 |
| Sony          | SVF1421E4E                  | [d0a9e97993](https://bsd-hardware.info/?probe=d0a9e97993) | Feb 09, 2023 |
| HP            | Laptop 14-df0xxx            | [1dc503f21d](https://bsd-hardware.info/?probe=1dc503f21d) | Feb 09, 2023 |
| Acer          | Aspire 4739Z                | [1e97a0b938](https://bsd-hardware.info/?probe=1e97a0b938) | Feb 09, 2023 |
| HP            | Pavilion dv6                | [d6c8ad1034](https://bsd-hardware.info/?probe=d6c8ad1034) | Feb 08, 2023 |
| ASUSTek       | N76VZ                       | [3b7e2ee70b](https://bsd-hardware.info/?probe=3b7e2ee70b) | Feb 08, 2023 |
| ASUSTek       | K84L                        | [d58c178c51](https://bsd-hardware.info/?probe=d58c178c51) | Feb 08, 2023 |
| HP            | Notebook                    | [507e85c092](https://bsd-hardware.info/?probe=507e85c092) | Feb 08, 2023 |
| ASUSTek       | 1201N                       | [3f44d6ed3f](https://bsd-hardware.info/?probe=3f44d6ed3f) | Feb 08, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [f3b0d5ac82](https://bsd-hardware.info/?probe=f3b0d5ac82) | Feb 08, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [4fc5363829](https://bsd-hardware.info/?probe=4fc5363829) | Feb 07, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [4d69517a13](https://bsd-hardware.info/?probe=4d69517a13) | Feb 07, 2023 |
| Panasonic     | CF-30KAPAXAM                | [baa7612257](https://bsd-hardware.info/?probe=baa7612257) | Feb 07, 2023 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | [3345f50844](https://bsd-hardware.info/?probe=3345f50844) | Feb 06, 2023 |
| HP            | Notebook                    | [8d8e5c294a](https://bsd-hardware.info/?probe=8d8e5c294a) | Feb 06, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [8083410c50](https://bsd-hardware.info/?probe=8083410c50) | Feb 06, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [78a978a8d4](https://bsd-hardware.info/?probe=78a978a8d4) | Feb 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [ef722fc37b](https://bsd-hardware.info/?probe=ef722fc37b) | Feb 06, 2023 |
| HP            | Victus by Gaming Laptop ... | [b97af82e5c](https://bsd-hardware.info/?probe=b97af82e5c) | Feb 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3448A... | [80f8e59cab](https://bsd-hardware.info/?probe=80f8e59cab) | Feb 05, 2023 |
| HP            | 650                         | [48099613ec](https://bsd-hardware.info/?probe=48099613ec) | Feb 05, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | [a98d28355d](https://bsd-hardware.info/?probe=a98d28355d) | Feb 05, 2023 |
| Deciso        | OPNsense Appliance          | [62452eaaaa](https://bsd-hardware.info/?probe=62452eaaaa) | Feb 05, 2023 |
| HP            | 2000                        | [7c997ce022](https://bsd-hardware.info/?probe=7c997ce022) | Feb 05, 2023 |
| Samsung       | 700T1C                      | [91d5c568d1](https://bsd-hardware.info/?probe=91d5c568d1) | Feb 05, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [c771b7daf4](https://bsd-hardware.info/?probe=c771b7daf4) | Feb 05, 2023 |
| Toshiba       | PORTEGE Z930                | [5462140da0](https://bsd-hardware.info/?probe=5462140da0) | Feb 05, 2023 |
| Notebook      | NV4XMB,ME,MZ                | [8a2bba8635](https://bsd-hardware.info/?probe=8a2bba8635) | Feb 05, 2023 |
| Deciso        | OPNsense Appliance          | [96df89832f](https://bsd-hardware.info/?probe=96df89832f) | Feb 04, 2023 |
| Lenovo        | ThinkPad P50 20EN0008GE     | [8cb09e34ec](https://bsd-hardware.info/?probe=8cb09e34ec) | Feb 04, 2023 |
| Lenovo        | G70-70 80HW006AGE           | [a52e13cf4e](https://bsd-hardware.info/?probe=a52e13cf4e) | Feb 04, 2023 |
| Lenovo        | B50-80 80EW                 | [97da411601](https://bsd-hardware.info/?probe=97da411601) | Feb 04, 2023 |
| Lenovo        | B50-80 80EW                 | [a8ec146fc6](https://bsd-hardware.info/?probe=a8ec146fc6) | Feb 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [0232c45faa](https://bsd-hardware.info/?probe=0232c45faa) | Feb 04, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [b7a491a010](https://bsd-hardware.info/?probe=b7a491a010) | Feb 03, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | [c0a6490fc8](https://bsd-hardware.info/?probe=c0a6490fc8) | Feb 03, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d36789c493](https://bsd-hardware.info/?probe=d36789c493) | Feb 02, 2023 |
| Lenovo        | ThinkPad T460 20FMS04200    | [3178015cd3](https://bsd-hardware.info/?probe=3178015cd3) | Feb 02, 2023 |
| Monster       | ABRA A7 V11.2               | [3e58da5c30](https://bsd-hardware.info/?probe=3e58da5c30) | Feb 02, 2023 |
| Unknown       | Unknown                     | [a7d54d41c8](https://bsd-hardware.info/?probe=a7d54d41c8) | Feb 02, 2023 |
| Monster       | ABRA A7 V11.2               | [3309453ed5](https://bsd-hardware.info/?probe=3309453ed5) | Feb 02, 2023 |
| HP            | Mini 210-1000               | [eaabd2a89d](https://bsd-hardware.info/?probe=eaabd2a89d) | Feb 02, 2023 |
| Lenovo        | ThinkPad E14 20RA0036RT     | [941da31f26](https://bsd-hardware.info/?probe=941da31f26) | Feb 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a54516414a](https://bsd-hardware.info/?probe=a54516414a) | Feb 01, 2023 |
| Lenovo        | ThinkPad T460p 20FW0018A... | [932e722b2d](https://bsd-hardware.info/?probe=932e722b2d) | Feb 01, 2023 |
| HP            | ENVY TS m6 Sleekbook        | [402494618a](https://bsd-hardware.info/?probe=402494618a) | Feb 01, 2023 |
| Unknown       | Unknown                     | [4cae5c6bb7](https://bsd-hardware.info/?probe=4cae5c6bb7) | Feb 01, 2023 |
| HP            | ENVY TS m6 Sleekbook        | [63d90da096](https://bsd-hardware.info/?probe=63d90da096) | Feb 01, 2023 |
| Acer          | Aspire ES1-520              | [efac696b1a](https://bsd-hardware.info/?probe=efac696b1a) | Jan 31, 2023 |
| MSI           | Modern 15 A5M               | [afda1bcf60](https://bsd-hardware.info/?probe=afda1bcf60) | Jan 31, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [341bae363a](https://bsd-hardware.info/?probe=341bae363a) | Jan 31, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [0b48f96d1e](https://bsd-hardware.info/?probe=0b48f96d1e) | Jan 31, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [c2f84d2103](https://bsd-hardware.info/?probe=c2f84d2103) | Jan 31, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [165d435f30](https://bsd-hardware.info/?probe=165d435f30) | Jan 31, 2023 |
| HP            | EliteBook 8440p             | [d732f4d6c4](https://bsd-hardware.info/?probe=d732f4d6c4) | Jan 31, 2023 |
| MSI           | Modern 15 A5M               | [26d140b290](https://bsd-hardware.info/?probe=26d140b290) | Jan 31, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [39ae8fb9c8](https://bsd-hardware.info/?probe=39ae8fb9c8) | Jan 30, 2023 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | [bccdd2f331](https://bsd-hardware.info/?probe=bccdd2f331) | Jan 30, 2023 |
| Dell          | Precision 5540              | [de7ac2f8d1](https://bsd-hardware.info/?probe=de7ac2f8d1) | Jan 30, 2023 |
| HP            | Pavilion Notebook           | [75b9ef6ee6](https://bsd-hardware.info/?probe=75b9ef6ee6) | Jan 30, 2023 |
| Apple         | MacBookAir5,1               | [eeed92ab62](https://bsd-hardware.info/?probe=eeed92ab62) | Jan 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3448A... | [6da773c078](https://bsd-hardware.info/?probe=6da773c078) | Jan 29, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [21398109dc](https://bsd-hardware.info/?probe=21398109dc) | Jan 29, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [2098b8808d](https://bsd-hardware.info/?probe=2098b8808d) | Jan 29, 2023 |
| IGEL Techn... | H830C                       | [322cc6bc3b](https://bsd-hardware.info/?probe=322cc6bc3b) | Jan 29, 2023 |
| Razer         | Blade Stealth               | [c0b9641604](https://bsd-hardware.info/?probe=c0b9641604) | Jan 29, 2023 |
| Lenovo        | IdeaPad 110-14AST 80TQ      | [aed5292edc](https://bsd-hardware.info/?probe=aed5292edc) | Jan 28, 2023 |
| Packard Be... | DOT S                       | [09a2057767](https://bsd-hardware.info/?probe=09a2057767) | Jan 28, 2023 |
| Razer         | Blade Stealth               | [14760d0c64](https://bsd-hardware.info/?probe=14760d0c64) | Jan 28, 2023 |
| Acer          | Aspire one V1.05            | [1cbfce4d7e](https://bsd-hardware.info/?probe=1cbfce4d7e) | Jan 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [d5f06d91db](https://bsd-hardware.info/?probe=d5f06d91db) | Jan 28, 2023 |
| HP            | Laptop 14s-fq1xxx           | [1603f38c4c](https://bsd-hardware.info/?probe=1603f38c4c) | Jan 28, 2023 |
| Lenovo        | ThinkPad T460 20FMS06V00    | [6914f6aab5](https://bsd-hardware.info/?probe=6914f6aab5) | Jan 28, 2023 |
| Lenovo        | ThinkPad E585 20KV0010US    | [9cfe2dd858](https://bsd-hardware.info/?probe=9cfe2dd858) | Jan 28, 2023 |
| Acer          | ES1-131-C2BM                | [400ef90a79](https://bsd-hardware.info/?probe=400ef90a79) | Jan 28, 2023 |
| Deciso        | NetBoard-A10                | [5b226a942e](https://bsd-hardware.info/?probe=5b226a942e) | Jan 27, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [448f9265f2](https://bsd-hardware.info/?probe=448f9265f2) | Jan 27, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [512bf8f61d](https://bsd-hardware.info/?probe=512bf8f61d) | Jan 27, 2023 |
| Dell          | Latitude 5400               | [a266199ace](https://bsd-hardware.info/?probe=a266199ace) | Jan 27, 2023 |
| Acer          | Aspire E3-112               | [513c7ff4be](https://bsd-hardware.info/?probe=513c7ff4be) | Jan 27, 2023 |
| Google        | Kefka                       | [83771661c6](https://bsd-hardware.info/?probe=83771661c6) | Jan 27, 2023 |
| Deciso        | Netboard A20                | [07de4617d2](https://bsd-hardware.info/?probe=07de4617d2) | Jan 26, 2023 |
| Lenovo        | B50-80 80EW                 | [7cbd8c5cbd](https://bsd-hardware.info/?probe=7cbd8c5cbd) | Jan 26, 2023 |
| HP            | EliteBook 840 G3            | [92c676e033](https://bsd-hardware.info/?probe=92c676e033) | Jan 26, 2023 |
| Google        | Cave                        | [76ac12f1e2](https://bsd-hardware.info/?probe=76ac12f1e2) | Jan 25, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [4eb4e63a2c](https://bsd-hardware.info/?probe=4eb4e63a2c) | Jan 25, 2023 |
| HP            | EliteBook 2560p             | [80c808de34](https://bsd-hardware.info/?probe=80c808de34) | Jan 25, 2023 |
| Timi          | TM1607                      | [57113d2886](https://bsd-hardware.info/?probe=57113d2886) | Jan 25, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [afeb216c1e](https://bsd-hardware.info/?probe=afeb216c1e) | Jan 25, 2023 |
| Lenovo        | G500 20236                  | [081d22fbe2](https://bsd-hardware.info/?probe=081d22fbe2) | Jan 24, 2023 |
| Lenovo        | G500 20236                  | [a35053ad38](https://bsd-hardware.info/?probe=a35053ad38) | Jan 24, 2023 |
| Lenovo        | ThinkPad X220 4291WF5       | [24544f4a94](https://bsd-hardware.info/?probe=24544f4a94) | Jan 24, 2023 |
| MSI           | PS63 Modern 8M              | [f740e313e5](https://bsd-hardware.info/?probe=f740e313e5) | Jan 24, 2023 |
| Lenovo        | ThinkPad T430 2342AG4       | [b5e972d19a](https://bsd-hardware.info/?probe=b5e972d19a) | Jan 24, 2023 |
| Timi          | TM1607                      | [27db14fdbd](https://bsd-hardware.info/?probe=27db14fdbd) | Jan 24, 2023 |
| Fujitsu       | LIFEBOOK S935               | [5c07c1a47e](https://bsd-hardware.info/?probe=5c07c1a47e) | Jan 24, 2023 |
| Dell          | XPS 13 9310                 | [7319560506](https://bsd-hardware.info/?probe=7319560506) | Jan 24, 2023 |
| Dell          | Latitude 3540               | [a180a149f5](https://bsd-hardware.info/?probe=a180a149f5) | Jan 24, 2023 |
| Deciso        | NetBoard-A20                | [0a40a0b8e2](https://bsd-hardware.info/?probe=0a40a0b8e2) | Jan 24, 2023 |
| Deciso        | NetBoard-A20                | [211bc64e5e](https://bsd-hardware.info/?probe=211bc64e5e) | Jan 24, 2023 |
| Dell          | Latitude 5580               | [90cd22ad55](https://bsd-hardware.info/?probe=90cd22ad55) | Jan 24, 2023 |
| Toshiba       | PORTEGE Z930                | [476203ee86](https://bsd-hardware.info/?probe=476203ee86) | Jan 23, 2023 |
| Apple         | MacBookPro9,2               | [aaccb6df1a](https://bsd-hardware.info/?probe=aaccb6df1a) | Jan 23, 2023 |
| Toshiba       | PORTEGE Z930                | [4af2cc1909](https://bsd-hardware.info/?probe=4af2cc1909) | Jan 23, 2023 |
| ASUSTek       | K50IN                       | [6f7a8f3338](https://bsd-hardware.info/?probe=6f7a8f3338) | Jan 23, 2023 |
| Medion        | S14409                      | [9a44efb64c](https://bsd-hardware.info/?probe=9a44efb64c) | Jan 23, 2023 |
| Lenovo        | ThinkPad W541 20EF000NUS    | [200a92d510](https://bsd-hardware.info/?probe=200a92d510) | Jan 23, 2023 |
| Star Labs     | StarBook                    | [d222f381b0](https://bsd-hardware.info/?probe=d222f381b0) | Jan 23, 2023 |
| Star Labs     | StarBook                    | [045d4bb6e8](https://bsd-hardware.info/?probe=045d4bb6e8) | Jan 23, 2023 |
| Dell          | Inspiron 15-7568            | [44e36adfa4](https://bsd-hardware.info/?probe=44e36adfa4) | Jan 23, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | [17fd94a4c0](https://bsd-hardware.info/?probe=17fd94a4c0) | Jan 23, 2023 |
| Dell          | Inspiron 3442               | [8b137bca84](https://bsd-hardware.info/?probe=8b137bca84) | Jan 23, 2023 |
| Timi          | TM1607                      | [7636a0ef8f](https://bsd-hardware.info/?probe=7636a0ef8f) | Jan 23, 2023 |
| Timi          | TM1607                      | [1ca46404a1](https://bsd-hardware.info/?probe=1ca46404a1) | Jan 23, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [881e97e41c](https://bsd-hardware.info/?probe=881e97e41c) | Jan 23, 2023 |
| Acer          | Aspire ES1-533              | [d2652b76cf](https://bsd-hardware.info/?probe=d2652b76cf) | Jan 22, 2023 |
| Dell          | Latitude E6400              | [dcc804a61f](https://bsd-hardware.info/?probe=dcc804a61f) | Jan 22, 2023 |
| Dell          | Latitude E6400              | [9dd8d0184f](https://bsd-hardware.info/?probe=9dd8d0184f) | Jan 22, 2023 |
| Lenovo        | ThinkPad T440p 20AN007FG... | [0883806434](https://bsd-hardware.info/?probe=0883806434) | Jan 22, 2023 |
| Lenovo        | ThinkPad P50 20EN0041MX     | [c27f1f53f2](https://bsd-hardware.info/?probe=c27f1f53f2) | Jan 22, 2023 |
| HP            | Laptop 15-bs0xx             | [7bd5f0c2e9](https://bsd-hardware.info/?probe=7bd5f0c2e9) | Jan 22, 2023 |
| Unknown       | Unknown                     | [8511097117](https://bsd-hardware.info/?probe=8511097117) | Jan 22, 2023 |
| Panasonic     | CF-C1BWFAZ1M                | [d129d929ac](https://bsd-hardware.info/?probe=d129d929ac) | Jan 22, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | [ab38c51298](https://bsd-hardware.info/?probe=ab38c51298) | Jan 22, 2023 |
| Unknown       | Unknown                     | [d5d2ce1b39](https://bsd-hardware.info/?probe=d5d2ce1b39) | Jan 22, 2023 |
| Acer          | Aspire ES1-571              | [a17d96dde0](https://bsd-hardware.info/?probe=a17d96dde0) | Jan 22, 2023 |
| Lenovo        | IdeaPad 110-14AST 80TQ      | [8ae819f673](https://bsd-hardware.info/?probe=8ae819f673) | Jan 21, 2023 |
| Datto         | 1000                        | [3d2880dd30](https://bsd-hardware.info/?probe=3d2880dd30) | Jan 21, 2023 |
| Lenovo        | ThinkPad T61 64644YG        | [3497ee2fcc](https://bsd-hardware.info/?probe=3497ee2fcc) | Jan 21, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [1d040b684b](https://bsd-hardware.info/?probe=1d040b684b) | Jan 21, 2023 |
| TUXEDO        | Aura 15 Gen1                | [e6ad419f5e](https://bsd-hardware.info/?probe=e6ad419f5e) | Jan 20, 2023 |
| Lenovo        | B50-80 80EW                 | [fa42e2faf7](https://bsd-hardware.info/?probe=fa42e2faf7) | Jan 20, 2023 |
| Acer          | TravelMate B311-31          | [dc3f072645](https://bsd-hardware.info/?probe=dc3f072645) | Jan 19, 2023 |
| Dell          | Precision 5540              | [683769b797](https://bsd-hardware.info/?probe=683769b797) | Jan 19, 2023 |
| Datto         | Unknown                     | [0b70f2b2b0](https://bsd-hardware.info/?probe=0b70f2b2b0) | Jan 18, 2023 |
| Unknown       | Unknown                     | [cbdab56490](https://bsd-hardware.info/?probe=cbdab56490) | Jan 18, 2023 |
| Datto         | 1000                        | [c2abd24ed6](https://bsd-hardware.info/?probe=c2abd24ed6) | Jan 18, 2023 |
| Intel         | H81U                        | [08d2539153](https://bsd-hardware.info/?probe=08d2539153) | Jan 18, 2023 |
| Unknown       | Unknown                     | [4ccf28379a](https://bsd-hardware.info/?probe=4ccf28379a) | Jan 17, 2023 |
| Intel         | H81U                        | [fe47328dd0](https://bsd-hardware.info/?probe=fe47328dd0) | Jan 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [dcdf55f06e](https://bsd-hardware.info/?probe=dcdf55f06e) | Jan 17, 2023 |
| Apple         | MacBookAir7,2               | [d8007634f3](https://bsd-hardware.info/?probe=d8007634f3) | Jan 17, 2023 |
| Lenovo        | B40-70 80F30005BR           | [17333d88cf](https://bsd-hardware.info/?probe=17333d88cf) | Jan 17, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [78327c664e](https://bsd-hardware.info/?probe=78327c664e) | Jan 16, 2023 |
| HP            | Pavilion dv6                | [9d87e4009a](https://bsd-hardware.info/?probe=9d87e4009a) | Jan 16, 2023 |
| HP            | ProBook 455 G7              | [600f7f4f4f](https://bsd-hardware.info/?probe=600f7f4f4f) | Jan 16, 2023 |
| HP            | ZBook 15 G4                 | [e98d329586](https://bsd-hardware.info/?probe=e98d329586) | Jan 15, 2023 |
| HP            | ZBook 15 G4                 | [86875f01c2](https://bsd-hardware.info/?probe=86875f01c2) | Jan 15, 2023 |
| HP            | Pavilion dv6                | [e42082b1c1](https://bsd-hardware.info/?probe=e42082b1c1) | Jan 15, 2023 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | [247370372d](https://bsd-hardware.info/?probe=247370372d) | Jan 15, 2023 |
| Lenovo        | B590 20208                  | [e4c2272546](https://bsd-hardware.info/?probe=e4c2272546) | Jan 15, 2023 |
| Deciso        | NetBoard-A10                | [624bfd62b5](https://bsd-hardware.info/?probe=624bfd62b5) | Jan 15, 2023 |
| Unknown       | Unknown                     | [c85b254f84](https://bsd-hardware.info/?probe=c85b254f84) | Jan 15, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [ad094a458b](https://bsd-hardware.info/?probe=ad094a458b) | Jan 14, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [ced6c29193](https://bsd-hardware.info/?probe=ced6c29193) | Jan 14, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | [035f9afc5d](https://bsd-hardware.info/?probe=035f9afc5d) | Jan 14, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | [9ded9cc6ec](https://bsd-hardware.info/?probe=9ded9cc6ec) | Jan 14, 2023 |
| HP            | Presario V2000 (EZ621UA#... | [847af5b70f](https://bsd-hardware.info/?probe=847af5b70f) | Jan 14, 2023 |
| HP            | Pavilion g6                 | [ceb79702f2](https://bsd-hardware.info/?probe=ceb79702f2) | Jan 13, 2023 |
| Dell          | Latitude E6420              | [cb7b02c421](https://bsd-hardware.info/?probe=cb7b02c421) | Jan 11, 2023 |
| Lenovo        | ThinkPad X220 4291LF6       | [25cddb26c3](https://bsd-hardware.info/?probe=25cddb26c3) | Jan 11, 2023 |
| Datto         | 1000                        | [ab1aa0f250](https://bsd-hardware.info/?probe=ab1aa0f250) | Jan 11, 2023 |
| Razer         | Blade Stealth               | [2464314a65](https://bsd-hardware.info/?probe=2464314a65) | Jan 11, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | [82e9263905](https://bsd-hardware.info/?probe=82e9263905) | Jan 11, 2023 |
| Lenovo        | B50-80 80EW                 | [ef45a319a3](https://bsd-hardware.info/?probe=ef45a319a3) | Jan 11, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [9bda43254c](https://bsd-hardware.info/?probe=9bda43254c) | Jan 10, 2023 |
| HP            | 2000                        | [7f29899321](https://bsd-hardware.info/?probe=7f29899321) | Jan 09, 2023 |
| Acer          | Aspire A514-54              | [470fa4f28a](https://bsd-hardware.info/?probe=470fa4f28a) | Jan 09, 2023 |
| Dell          | Inspiron 5558               | [97b65880b0](https://bsd-hardware.info/?probe=97b65880b0) | Jan 09, 2023 |
| Lenovo        | G50-80 80E5                 | [549b75038e](https://bsd-hardware.info/?probe=549b75038e) | Jan 08, 2023 |
| Lenovo        | G50-80 80E5                 | [5e81493c8d](https://bsd-hardware.info/?probe=5e81493c8d) | Jan 08, 2023 |
| Deciso        | OPNsense Appliance          | [cc421d80b4](https://bsd-hardware.info/?probe=cc421d80b4) | Jan 08, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [4014cc42ed](https://bsd-hardware.info/?probe=4014cc42ed) | Jan 08, 2023 |
| Dell          | XPS 13 9310                 | [e56cfbdedc](https://bsd-hardware.info/?probe=e56cfbdedc) | Jan 08, 2023 |
| Dell          | XPS 13 9310                 | [db483e3d46](https://bsd-hardware.info/?probe=db483e3d46) | Jan 08, 2023 |
| Lenovo        | B50-80 80EW                 | [b8f49b8d19](https://bsd-hardware.info/?probe=b8f49b8d19) | Jan 07, 2023 |
| Lenovo        | ThinkPad T400 2764CTO       | [26f8459193](https://bsd-hardware.info/?probe=26f8459193) | Jan 06, 2023 |
| Dell          | Latitude E6430              | [45f592a66f](https://bsd-hardware.info/?probe=45f592a66f) | Jan 06, 2023 |
| Deciso        | Netboard A20                | [3ff47d2ce0](https://bsd-hardware.info/?probe=3ff47d2ce0) | Jan 06, 2023 |
| Dell          | Latitude E6430              | [1c4bec17bb](https://bsd-hardware.info/?probe=1c4bec17bb) | Jan 06, 2023 |
| SLIMBOOK      | ESSENTIAL-15-11             | [3f758732d3](https://bsd-hardware.info/?probe=3f758732d3) | Jan 05, 2023 |
| HP            | EliteBook 8570p             | [17f5e2e3d2](https://bsd-hardware.info/?probe=17f5e2e3d2) | Jan 04, 2023 |
| Lenovo        | G50-70 20351                | [6a1ff80054](https://bsd-hardware.info/?probe=6a1ff80054) | Jan 04, 2023 |
| Lenovo        | ThinkPad T430 23446FP       | [a1517b13f6](https://bsd-hardware.info/?probe=a1517b13f6) | Jan 04, 2023 |
| Deciso        | NetBoard-A10                | [21c60a4db8](https://bsd-hardware.info/?probe=21c60a4db8) | Jan 04, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [aa6c483d4f](https://bsd-hardware.info/?probe=aa6c483d4f) | Jan 03, 2023 |
| Lenovo        | ThinkPad T61 64644YG        | [0657433463](https://bsd-hardware.info/?probe=0657433463) | Jan 03, 2023 |
| Lenovo        | ThinkPad T460s 20FAS3L00... | [ef6972d07a](https://bsd-hardware.info/?probe=ef6972d07a) | Jan 03, 2023 |
| Intel         | Milstead Platform           | [21ec3118ef](https://bsd-hardware.info/?probe=21ec3118ef) | Jan 02, 2023 |
| Notebook      | NS5x_NS7xPU                 | [7dc1fdfadb](https://bsd-hardware.info/?probe=7dc1fdfadb) | Jan 02, 2023 |
| Alienware     | m15 R4                      | [1438237430](https://bsd-hardware.info/?probe=1438237430) | Jan 02, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | [3b0ef08599](https://bsd-hardware.info/?probe=3b0ef08599) | Jan 01, 2023 |
| Lenovo        | ThinkPad X280 20KFCTO1WW    | [a9b3805c0b](https://bsd-hardware.info/?probe=a9b3805c0b) | Jan 01, 2023 |
| Lenovo        | IdeaPad L340-17IWL 81M0     | [22c4a06468](https://bsd-hardware.info/?probe=22c4a06468) | Dec 31, 2022 |
| Deciso        | OPNsense Appliance          | [21e1293019](https://bsd-hardware.info/?probe=21e1293019) | Dec 31, 2022 |
| Lenovo        | ThinkPad T410 2518C3U       | [c791e3e3fd](https://bsd-hardware.info/?probe=c791e3e3fd) | Dec 30, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B9450FA_... | [d5fa6c651c](https://bsd-hardware.info/?probe=d5fa6c651c) | Dec 30, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [956499202e](https://bsd-hardware.info/?probe=956499202e) | Dec 30, 2022 |
| Deciso        | OPNsense Appliance          | [8b4c84d972](https://bsd-hardware.info/?probe=8b4c84d972) | Dec 30, 2022 |
| Timi          | Redmi Book Pro 14 2022      | [ce5e882952](https://bsd-hardware.info/?probe=ce5e882952) | Dec 28, 2022 |
| Google        | Peppy                       | [e063619f03](https://bsd-hardware.info/?probe=e063619f03) | Dec 27, 2022 |
| Apple         | MacBookAir5,1               | [0d398d5c59](https://bsd-hardware.info/?probe=0d398d5c59) | Dec 27, 2022 |
| Deciso        | OPNsense Appliance          | [3fc9a4fd5c](https://bsd-hardware.info/?probe=3fc9a4fd5c) | Dec 26, 2022 |
| Deciso        | NetBoard-A10                | [b09ff8826c](https://bsd-hardware.info/?probe=b09ff8826c) | Dec 26, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [883dbf15e4](https://bsd-hardware.info/?probe=883dbf15e4) | Dec 25, 2022 |
| Star Labs     | Lite                        | [9ad15636dd](https://bsd-hardware.info/?probe=9ad15636dd) | Dec 25, 2022 |
| Alienware     | m15 R4                      | [deaef8f0ef](https://bsd-hardware.info/?probe=deaef8f0ef) | Dec 24, 2022 |
| Tactus        | GeoFlex 110                 | [955c355b47](https://bsd-hardware.info/?probe=955c355b47) | Dec 23, 2022 |
| Toshiba       | Satellite BE96-F299         | [ca475dd1d0](https://bsd-hardware.info/?probe=ca475dd1d0) | Dec 23, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [b38d32b139](https://bsd-hardware.info/?probe=b38d32b139) | Dec 23, 2022 |
| Sony          | VPCSB11FX                   | [966183e570](https://bsd-hardware.info/?probe=966183e570) | Dec 23, 2022 |
| Lenovo        | ThinkPad T480 20L6S13100    | [67daa912fa](https://bsd-hardware.info/?probe=67daa912fa) | Dec 23, 2022 |
| Dell          | Vostro 1400                 | [087a3d269f](https://bsd-hardware.info/?probe=087a3d269f) | Dec 23, 2022 |
| Acer          | Aspire ES1-533              | [570b96d0f7](https://bsd-hardware.info/?probe=570b96d0f7) | Dec 23, 2022 |
| Deciso        | OPNsense Appliance          | [062fb4cccd](https://bsd-hardware.info/?probe=062fb4cccd) | Dec 23, 2022 |
| Lenovo        | Yoga 710-11IKB 80V6         | [1d3ccd1fe6](https://bsd-hardware.info/?probe=1d3ccd1fe6) | Dec 22, 2022 |
| Dell          | Inspiron 15-3552            | [eea4262af2](https://bsd-hardware.info/?probe=eea4262af2) | Dec 22, 2022 |
| Dell          | Inspiron 15-3552            | [cae00eb4d6](https://bsd-hardware.info/?probe=cae00eb4d6) | Dec 22, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [527bf6bbe4](https://bsd-hardware.info/?probe=527bf6bbe4) | Dec 22, 2022 |
| Lenovo        | ThinkPad T60 1951A47        | [e254601f07](https://bsd-hardware.info/?probe=e254601f07) | Dec 21, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [af2a9d1a42](https://bsd-hardware.info/?probe=af2a9d1a42) | Dec 20, 2022 |
| Unknown       | Unknown                     | [364b3758b6](https://bsd-hardware.info/?probe=364b3758b6) | Dec 20, 2022 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [32207ea5d9](https://bsd-hardware.info/?probe=32207ea5d9) | Dec 19, 2022 |
| Lenovo        | ThinkPad T530 2392AQU       | [9a3cbe1893](https://bsd-hardware.info/?probe=9a3cbe1893) | Dec 19, 2022 |
| HUAWEI        | CREM-WXX9                   | [ced12f0b41](https://bsd-hardware.info/?probe=ced12f0b41) | Dec 19, 2022 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | [683591700f](https://bsd-hardware.info/?probe=683591700f) | Dec 19, 2022 |
| Lenovo        | ThinkPad X200 Tablet 744... | [ea686f63f5](https://bsd-hardware.info/?probe=ea686f63f5) | Dec 19, 2022 |
| Framework     | Laptop                      | [9dcd3592db](https://bsd-hardware.info/?probe=9dcd3592db) | Dec 19, 2022 |
| Dell          | Precision M4800             | [b7a834c4d0](https://bsd-hardware.info/?probe=b7a834c4d0) | Dec 18, 2022 |
| Dell          | Latitude E6430              | [b8f950de05](https://bsd-hardware.info/?probe=b8f950de05) | Dec 17, 2022 |
| HP            | EliteBook 8570p             | [7cf06451fd](https://bsd-hardware.info/?probe=7cf06451fd) | Dec 17, 2022 |
| Dell          | Latitude E6430              | [8d92a4e37e](https://bsd-hardware.info/?probe=8d92a4e37e) | Dec 17, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [3a9623cfb4](https://bsd-hardware.info/?probe=3a9623cfb4) | Dec 16, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [0314add226](https://bsd-hardware.info/?probe=0314add226) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [d19db2828c](https://bsd-hardware.info/?probe=d19db2828c) | Dec 16, 2022 |
| Lenovo        | B50-80 80EW                 | [e6778fa5fd](https://bsd-hardware.info/?probe=e6778fa5fd) | Dec 15, 2022 |
| ASUSTek       | K50IN                       | [b8bfdec836](https://bsd-hardware.info/?probe=b8bfdec836) | Dec 15, 2022 |
| Intel         | H81U                        | [fab3eecc66](https://bsd-hardware.info/?probe=fab3eecc66) | Dec 15, 2022 |
| Dell          | Latitude 5400               | [639993a130](https://bsd-hardware.info/?probe=639993a130) | Dec 15, 2022 |
| Dell          | Latitude 5400               | [5b9eb16e5e](https://bsd-hardware.info/?probe=5b9eb16e5e) | Dec 15, 2022 |
| HUAWEI        | KLVL-WXXW                   | [55f876d83f](https://bsd-hardware.info/?probe=55f876d83f) | Dec 15, 2022 |
| Lenovo        | G510 20238                  | [e5c4d51eab](https://bsd-hardware.info/?probe=e5c4d51eab) | Dec 15, 2022 |
| Intel         | H81U                        | [fe1c3cb754](https://bsd-hardware.info/?probe=fe1c3cb754) | Dec 14, 2022 |
| Lenovo        | B50-80 80EW                 | [9551c57fc3](https://bsd-hardware.info/?probe=9551c57fc3) | Dec 14, 2022 |
| Dell          | Vostro 15-3568              | [6fc0671dc6](https://bsd-hardware.info/?probe=6fc0671dc6) | Dec 14, 2022 |
| HP            | ProBook 430 G7              | [0e2278affa](https://bsd-hardware.info/?probe=0e2278affa) | Dec 14, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [babe4bb620](https://bsd-hardware.info/?probe=babe4bb620) | Dec 13, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0Y40... | [ce2b20b3a9](https://bsd-hardware.info/?probe=ce2b20b3a9) | Dec 13, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0Y40... | [7463e05c88](https://bsd-hardware.info/?probe=7463e05c88) | Dec 12, 2022 |
| HP            | Pavilion dv4                | [ee94a86a43](https://bsd-hardware.info/?probe=ee94a86a43) | Dec 12, 2022 |
| HP            | EliteBook 8570p             | [64c92d49d9](https://bsd-hardware.info/?probe=64c92d49d9) | Dec 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [809da57d90](https://bsd-hardware.info/?probe=809da57d90) | Dec 11, 2022 |
| Acer          | Swift SF114-34              | [0be43b76d1](https://bsd-hardware.info/?probe=0be43b76d1) | Dec 11, 2022 |
| HP            | EliteBook 8570p             | [6d10b2a0b4](https://bsd-hardware.info/?probe=6d10b2a0b4) | Dec 11, 2022 |
| Apple         | MacBook3,1                  | [7aef0a996b](https://bsd-hardware.info/?probe=7aef0a996b) | Dec 10, 2022 |
| Apple         | MacBookPro14,1              | [5234a39100](https://bsd-hardware.info/?probe=5234a39100) | Dec 10, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [2048ff5f71](https://bsd-hardware.info/?probe=2048ff5f71) | Dec 09, 2022 |
| HP            | 2000                        | [5414b7c943](https://bsd-hardware.info/?probe=5414b7c943) | Dec 09, 2022 |
| Deciso        | NetBoard-A10                | [79b2a5d3a5](https://bsd-hardware.info/?probe=79b2a5d3a5) | Dec 08, 2022 |
| Deciso        | NetBoard-A10                | [575d201794](https://bsd-hardware.info/?probe=575d201794) | Dec 07, 2022 |
| HP            | 245 G6                      | [49ce6aa725](https://bsd-hardware.info/?probe=49ce6aa725) | Dec 07, 2022 |
| DFI           | BE17X(170/171/173)          | [9822160345](https://bsd-hardware.info/?probe=9822160345) | Dec 05, 2022 |
| Acer          | Swift SF114-34              | [2c560bad00](https://bsd-hardware.info/?probe=2c560bad00) | Dec 05, 2022 |
| Google        | Lick                        | [8099b2df21](https://bsd-hardware.info/?probe=8099b2df21) | Dec 04, 2022 |
| Google        | Lick                        | [9eb2abcdcc](https://bsd-hardware.info/?probe=9eb2abcdcc) | Dec 03, 2022 |
| Google        | Lars                        | [4130b19cfa](https://bsd-hardware.info/?probe=4130b19cfa) | Dec 03, 2022 |
| Lenovo        | ThinkPad X250 20CLS5BU00    | [10619ac217](https://bsd-hardware.info/?probe=10619ac217) | Dec 03, 2022 |
| Apple         | MacBookPro14,1              | [ddeb9befdf](https://bsd-hardware.info/?probe=ddeb9befdf) | Dec 03, 2022 |
| HASEE Comp... | N95XKP6                     | [0bc2996a6d](https://bsd-hardware.info/?probe=0bc2996a6d) | Dec 02, 2022 |
| Dell          | Latitude 5590               | [0a17f04eba](https://bsd-hardware.info/?probe=0a17f04eba) | Dec 02, 2022 |
| Panasonic     | CF-54-1                     | [0c5820ea0d](https://bsd-hardware.info/?probe=0c5820ea0d) | Dec 01, 2022 |
| Dell          | Inspiron 3442               | [529cbab9aa](https://bsd-hardware.info/?probe=529cbab9aa) | Dec 01, 2022 |
| Acidanther... | MacBookPro15,1              | [57c3a4005a](https://bsd-hardware.info/?probe=57c3a4005a) | Dec 01, 2022 |
| HP            | Laptop 14s-fq0xxx           | [920a2fe2e9](https://bsd-hardware.info/?probe=920a2fe2e9) | Nov 30, 2022 |
| Panasonic     | CF-31-5                     | [7047afaaf4](https://bsd-hardware.info/?probe=7047afaaf4) | Nov 30, 2022 |
| GPD           | P3 MAX                      | [4a467c9616](https://bsd-hardware.info/?probe=4a467c9616) | Nov 30, 2022 |
| Apple         | MacBookPro8,1               | [3dd9e3557c](https://bsd-hardware.info/?probe=3dd9e3557c) | Nov 30, 2022 |
| Lenovo        | ThinkPad T430 2347G7G       | [640540cd67](https://bsd-hardware.info/?probe=640540cd67) | Nov 29, 2022 |
| HP            | Laptop 14s-fq0xxx           | [9618eb0cbe](https://bsd-hardware.info/?probe=9618eb0cbe) | Nov 29, 2022 |
| Acer          | TravelMate B115-M           | [13e318fec2](https://bsd-hardware.info/?probe=13e318fec2) | Nov 29, 2022 |
| Lenovo        | ThinkPad T460 20FMS0XL23    | [bc7585ec56](https://bsd-hardware.info/?probe=bc7585ec56) | Nov 28, 2022 |
| Toshiba       | TECRA Z40-C-12Z             | [149e5c3de3](https://bsd-hardware.info/?probe=149e5c3de3) | Nov 28, 2022 |
| Apple         | MacBook5,1                  | [3541df7dd2](https://bsd-hardware.info/?probe=3541df7dd2) | Nov 27, 2022 |
| Dell          | Inspiron 5558               | [10bece0518](https://bsd-hardware.info/?probe=10bece0518) | Nov 27, 2022 |
| HP            | EliteBook 8570p             | [3ad7cec298](https://bsd-hardware.info/?probe=3ad7cec298) | Nov 26, 2022 |
| Acer          | Aspire 5738                 | [067e8e4d58](https://bsd-hardware.info/?probe=067e8e4d58) | Nov 26, 2022 |
| Lenovo        | ThinkPad T430 23446FP       | [6c2ef140be](https://bsd-hardware.info/?probe=6c2ef140be) | Nov 25, 2022 |
| Dell          | Vostro 3501                 | [61f8a35700](https://bsd-hardware.info/?probe=61f8a35700) | Nov 25, 2022 |
| Sony          | SVP1321V9RB                 | [932facd689](https://bsd-hardware.info/?probe=932facd689) | Nov 25, 2022 |
| Dell          | Latitude D610               | [6ef8d8137b](https://bsd-hardware.info/?probe=6ef8d8137b) | Nov 24, 2022 |
| Deciso        | OPNsense Appliance          | [0bbf4f46e7](https://bsd-hardware.info/?probe=0bbf4f46e7) | Nov 24, 2022 |
| ASUSTek       | K55VD                       | [6fa29c4e4d](https://bsd-hardware.info/?probe=6fa29c4e4d) | Nov 24, 2022 |
| Deciso        | OPNsense Appliance          | [75a7bf9b27](https://bsd-hardware.info/?probe=75a7bf9b27) | Nov 24, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [3c11fc31b2](https://bsd-hardware.info/?probe=3c11fc31b2) | Nov 24, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [e32a104392](https://bsd-hardware.info/?probe=e32a104392) | Nov 24, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [a4d92a3b73](https://bsd-hardware.info/?probe=a4d92a3b73) | Nov 23, 2022 |
| Dell          | XPS 13 9343                 | [8ec61db3f0](https://bsd-hardware.info/?probe=8ec61db3f0) | Nov 22, 2022 |
| ASUSTek       | ZenBook UX434FL_UX434FL     | [56bc3b04fd](https://bsd-hardware.info/?probe=56bc3b04fd) | Nov 21, 2022 |
| Lenovo        | ThinkPad X230 2325T4T       | [f0cc17c7eb](https://bsd-hardware.info/?probe=f0cc17c7eb) | Nov 21, 2022 |
| HP            | ProBook 4540s               | [6dce896f40](https://bsd-hardware.info/?probe=6dce896f40) | Nov 20, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [8257d11669](https://bsd-hardware.info/?probe=8257d11669) | Nov 20, 2022 |
| Deciso        | NetBoard-A10                | [20058331ef](https://bsd-hardware.info/?probe=20058331ef) | Nov 19, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [eaf4ec693e](https://bsd-hardware.info/?probe=eaf4ec693e) | Nov 19, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | [7691355396](https://bsd-hardware.info/?probe=7691355396) | Nov 18, 2022 |
| Dell          | Latitude D630               | [1c600cc283](https://bsd-hardware.info/?probe=1c600cc283) | Nov 18, 2022 |
| Acer          | Aspire 5251                 | [046bc722cb](https://bsd-hardware.info/?probe=046bc722cb) | Nov 16, 2022 |
| HP            | EliteBook 8570p             | [436a2d30f6](https://bsd-hardware.info/?probe=436a2d30f6) | Nov 16, 2022 |
| Acer          | Aspire 5251                 | [c9eb0051ed](https://bsd-hardware.info/?probe=c9eb0051ed) | Nov 16, 2022 |
| Dell          | Vostro 3550                 | [2aeadb4dfc](https://bsd-hardware.info/?probe=2aeadb4dfc) | Nov 14, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [4c83122cc0](https://bsd-hardware.info/?probe=4c83122cc0) | Nov 14, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [7650f7619d](https://bsd-hardware.info/?probe=7650f7619d) | Nov 14, 2022 |
| Medion        | E15415                      | [e467080570](https://bsd-hardware.info/?probe=e467080570) | Nov 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3448A... | [1d2be7d46a](https://bsd-hardware.info/?probe=1d2be7d46a) | Nov 13, 2022 |
| Dell          | Latitude E7240              | [ea99621380](https://bsd-hardware.info/?probe=ea99621380) | Nov 12, 2022 |
| Google        | Akemi                       | [2d8e99f0c2](https://bsd-hardware.info/?probe=2d8e99f0c2) | Nov 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [4044f32351](https://bsd-hardware.info/?probe=4044f32351) | Nov 12, 2022 |
| Deciso        | Netboard A20                | [0320675a86](https://bsd-hardware.info/?probe=0320675a86) | Nov 10, 2022 |
| Dell          | Inspiron 3421               | [5c37012f33](https://bsd-hardware.info/?probe=5c37012f33) | Nov 10, 2022 |
| Deciso        | NetBoard-A20                | [61157ac2b6](https://bsd-hardware.info/?probe=61157ac2b6) | Nov 10, 2022 |
| Lenovo        | ThinkPad X260 20F5S2GM00    | [b8874a6df3](https://bsd-hardware.info/?probe=b8874a6df3) | Nov 10, 2022 |
| Deciso        | NetBoard-A10                | [1fc6403341](https://bsd-hardware.info/?probe=1fc6403341) | Nov 08, 2022 |
| Lenovo        | ThinkPad X270 20HMCTO1WW    | [9f15cb8acc](https://bsd-hardware.info/?probe=9f15cb8acc) | Nov 08, 2022 |
| HP            | EliteBook 840 G3            | [5807159f51](https://bsd-hardware.info/?probe=5807159f51) | Nov 08, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [2294352c5a](https://bsd-hardware.info/?probe=2294352c5a) | Nov 08, 2022 |
| HP            | ProBook 4540s               | [9c4be9deab](https://bsd-hardware.info/?probe=9c4be9deab) | Nov 07, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [45316a9769](https://bsd-hardware.info/?probe=45316a9769) | Nov 07, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [e8aea441aa](https://bsd-hardware.info/?probe=e8aea441aa) | Nov 06, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [c4fd2595e6](https://bsd-hardware.info/?probe=c4fd2595e6) | Nov 06, 2022 |
| Lenovo        | ThinkPad T430 23446FP       | [1373bd7f3e](https://bsd-hardware.info/?probe=1373bd7f3e) | Nov 05, 2022 |
| HP            | ProBook 4540s               | [7596b602c6](https://bsd-hardware.info/?probe=7596b602c6) | Nov 05, 2022 |
| Dell          | Precision M4500             | [ab63467f38](https://bsd-hardware.info/?probe=ab63467f38) | Nov 03, 2022 |
| Deciso        | NetBoard-A20                | [9c133326c9](https://bsd-hardware.info/?probe=9c133326c9) | Nov 03, 2022 |
| HP            | Laptop 15-da0xxx            | [72d95a4938](https://bsd-hardware.info/?probe=72d95a4938) | Nov 03, 2022 |
| Samsung       | 750TDA                      | [a880b1f616](https://bsd-hardware.info/?probe=a880b1f616) | Nov 02, 2022 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [7708c4bb19](https://bsd-hardware.info/?probe=7708c4bb19) | Nov 02, 2022 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [22d3fc953a](https://bsd-hardware.info/?probe=22d3fc953a) | Nov 01, 2022 |
| Dell          | Latitude 5591               | [40957fa567](https://bsd-hardware.info/?probe=40957fa567) | Oct 31, 2022 |
| Lenovo        | ThinkPad A485 20MU000VUS    | [b816902c0b](https://bsd-hardware.info/?probe=b816902c0b) | Oct 31, 2022 |
| Lenovo        | ThinkPad X220 429043U       | [e5716f886a](https://bsd-hardware.info/?probe=e5716f886a) | Oct 30, 2022 |
| HP            | Pavilion g6                 | [c4e84b8104](https://bsd-hardware.info/?probe=c4e84b8104) | Oct 30, 2022 |
| Lenovo        | ThinkPad T420s 41742BU      | [34f0a2bc03](https://bsd-hardware.info/?probe=34f0a2bc03) | Oct 30, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0BR0... | [2776d8c350](https://bsd-hardware.info/?probe=2776d8c350) | Oct 30, 2022 |
| Lenovo        | ThinkPad W530 24491A0       | [4a700f43f8](https://bsd-hardware.info/?probe=4a700f43f8) | Oct 30, 2022 |
| Lenovo        | ThinkPad T460 20FMS10N00    | [04ce25bd7f](https://bsd-hardware.info/?probe=04ce25bd7f) | Oct 29, 2022 |
| Samsung       | Q430/Q530                   | [fb98c8c797](https://bsd-hardware.info/?probe=fb98c8c797) | Oct 29, 2022 |
| Acer          | JM11-MS                     | [3ff8b20107](https://bsd-hardware.info/?probe=3ff8b20107) | Oct 29, 2022 |
| Fujitsu       | LIFEBOOK E752               | [e3c5057898](https://bsd-hardware.info/?probe=e3c5057898) | Oct 29, 2022 |
| Unknown       | Unknown                     | [2df5c5b434](https://bsd-hardware.info/?probe=2df5c5b434) | Oct 28, 2022 |
| Dell          | Inspiron 7720               | [6911e08b7e](https://bsd-hardware.info/?probe=6911e08b7e) | Oct 28, 2022 |
| Panasonic     | CF-53AAGHYDM                | [f2fafaa9e3](https://bsd-hardware.info/?probe=f2fafaa9e3) | Oct 27, 2022 |
| Apple         | MacBook4,1                  | [015f0a0a6d](https://bsd-hardware.info/?probe=015f0a0a6d) | Oct 27, 2022 |
| Matsushita... | CF-48V4KNDQM                | [d96fbc17b5](https://bsd-hardware.info/?probe=d96fbc17b5) | Oct 27, 2022 |
| Panasonic     | CF-52PFPBSFQ                | [088e0245af](https://bsd-hardware.info/?probe=088e0245af) | Oct 27, 2022 |
| Deciso        | NetBoard-A10                | [5d4c95dcac](https://bsd-hardware.info/?probe=5d4c95dcac) | Oct 26, 2022 |
| Matsushita... | CF-51RCVDNLM                | [6e8067d4d8](https://bsd-hardware.info/?probe=6e8067d4d8) | Oct 26, 2022 |
| Lenovo        | ThinkPad T420s 4174DL7      | [82d774e711](https://bsd-hardware.info/?probe=82d774e711) | Oct 26, 2022 |
| Lenovo        | ThinkPad T410 2537N24       | [b7a4ee06a6](https://bsd-hardware.info/?probe=b7a4ee06a6) | Oct 26, 2022 |
| Fujitsu       | LIFEBOOK E752               | [06e6c07e90](https://bsd-hardware.info/?probe=06e6c07e90) | Oct 25, 2022 |
| Samsung       | Q430/Q530                   | [4965215a13](https://bsd-hardware.info/?probe=4965215a13) | Oct 25, 2022 |
| Lenovo        | ThinkPad T430 2347GZU       | [f2236f17ee](https://bsd-hardware.info/?probe=f2236f17ee) | Oct 25, 2022 |
| ASUSTek       | 1000HE                      | [c4bbcf9537](https://bsd-hardware.info/?probe=c4bbcf9537) | Oct 24, 2022 |
| Intel         | H81U                        | [b0e1f80338](https://bsd-hardware.info/?probe=b0e1f80338) | Oct 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [caad4323ba](https://bsd-hardware.info/?probe=caad4323ba) | Oct 23, 2022 |
| Dell          | Latitude 5591               | [58b577382a](https://bsd-hardware.info/?probe=58b577382a) | Oct 23, 2022 |
| ASUSTek       | K53TA                       | [521283b723](https://bsd-hardware.info/?probe=521283b723) | Oct 22, 2022 |
| Alienware     | m15                         | [3304a767ba](https://bsd-hardware.info/?probe=3304a767ba) | Oct 22, 2022 |
| Google        | Edgar                       | [318a750368](https://bsd-hardware.info/?probe=318a750368) | Oct 22, 2022 |
| Lenovo        | G500 20236                  | [8a4e3767e9](https://bsd-hardware.info/?probe=8a4e3767e9) | Oct 22, 2022 |
| Apple         | MacBookPro8,1               | [623594855a](https://bsd-hardware.info/?probe=623594855a) | Oct 22, 2022 |
| Dell          | Precision M4500             | [66ded228ea](https://bsd-hardware.info/?probe=66ded228ea) | Oct 20, 2022 |
| Acer          | Aspire E1-570               | [3d62c50607](https://bsd-hardware.info/?probe=3d62c50607) | Oct 20, 2022 |
| MSI           | PS63 Modern 8M              | [949e472db5](https://bsd-hardware.info/?probe=949e472db5) | Oct 19, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | [bc229efed9](https://bsd-hardware.info/?probe=bc229efed9) | Oct 18, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | [0a8b1f727f](https://bsd-hardware.info/?probe=0a8b1f727f) | Oct 17, 2022 |
| Lenovo        | ThinkPad T61 765912G        | [50c3c93790](https://bsd-hardware.info/?probe=50c3c93790) | Oct 17, 2022 |
| Acer          | Aspire A514-54              | [e057b613a0](https://bsd-hardware.info/?probe=e057b613a0) | Oct 17, 2022 |
| Lenovo        | XiaoXinPro-13API 2019 81... | [dfa08657fd](https://bsd-hardware.info/?probe=dfa08657fd) | Oct 16, 2022 |
| HP            | SpectreXT Pro 13-b000 PC    | [f45ea42873](https://bsd-hardware.info/?probe=f45ea42873) | Oct 16, 2022 |
| Dell          | Inspiron 15 5510            | [22881028bc](https://bsd-hardware.info/?probe=22881028bc) | Oct 16, 2022 |
| HP            | Laptop 15q-bu0xx            | [99c01654a2](https://bsd-hardware.info/?probe=99c01654a2) | Oct 15, 2022 |
| Lenovo        | ThinkPad T430 23446FP       | [6b15856d20](https://bsd-hardware.info/?probe=6b15856d20) | Oct 15, 2022 |
| Unknown       | Unknown                     | [3b7146c456](https://bsd-hardware.info/?probe=3b7146c456) | Oct 14, 2022 |
| Unknown       | Unknown                     | [1ad8d9e64c](https://bsd-hardware.info/?probe=1ad8d9e64c) | Oct 14, 2022 |
| Intel         | H81U                        | [9b212d2264](https://bsd-hardware.info/?probe=9b212d2264) | Oct 13, 2022 |
| Lenovo        | ThinkPad T440s 20AR003SM... | [df62882c3b](https://bsd-hardware.info/?probe=df62882c3b) | Oct 12, 2022 |
| Dell          | Latitude 5591               | [04f53f51c8](https://bsd-hardware.info/?probe=04f53f51c8) | Oct 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | [a773a82ff4](https://bsd-hardware.info/?probe=a773a82ff4) | Oct 11, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [dec7108b53](https://bsd-hardware.info/?probe=dec7108b53) | Oct 11, 2022 |
| Dell          | Latitude 5591               | [eda94b6c48](https://bsd-hardware.info/?probe=eda94b6c48) | Oct 11, 2022 |
| Acer          | Aspire 5336                 | [127ddc93fb](https://bsd-hardware.info/?probe=127ddc93fb) | Oct 10, 2022 |
| Acer          | Aspire E5-722G              | [7a4eb565fe](https://bsd-hardware.info/?probe=7a4eb565fe) | Oct 10, 2022 |
| MSI           | GL65 Leopard 10SFSK         | [2ea7c7f9a2](https://bsd-hardware.info/?probe=2ea7c7f9a2) | Oct 10, 2022 |
| Dell          | Latitude E6420              | [48c26d2a17](https://bsd-hardware.info/?probe=48c26d2a17) | Oct 10, 2022 |
| Fujitsu       | LIFEBOOK U904               | [3a86733538](https://bsd-hardware.info/?probe=3a86733538) | Oct 09, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | [17d766d55a](https://bsd-hardware.info/?probe=17d766d55a) | Oct 08, 2022 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | [442a743538](https://bsd-hardware.info/?probe=442a743538) | Oct 08, 2022 |
| Lenovo        | ThinkPad X270 20HMS04P00    | [7647b7a0b2](https://bsd-hardware.info/?probe=7647b7a0b2) | Oct 07, 2022 |
| Acer          | Aspire ES1-523              | [92a125995f](https://bsd-hardware.info/?probe=92a125995f) | Oct 07, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | [601029d3fc](https://bsd-hardware.info/?probe=601029d3fc) | Oct 06, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [ce9cfa77aa](https://bsd-hardware.info/?probe=ce9cfa77aa) | Oct 05, 2022 |
| Acer          | Aspire F5-573               | [9c092c9cd7](https://bsd-hardware.info/?probe=9c092c9cd7) | Oct 05, 2022 |
| HP            | Compaq 6735s                | [f61208cfea](https://bsd-hardware.info/?probe=f61208cfea) | Oct 05, 2022 |
| HP            | Compaq 6735s                | [718126149c](https://bsd-hardware.info/?probe=718126149c) | Oct 05, 2022 |
| Acer          | TravelMate B115-M           | [86289a60aa](https://bsd-hardware.info/?probe=86289a60aa) | Oct 05, 2022 |
| Acer          | TravelMate B115-M           | [9f4642f6a5](https://bsd-hardware.info/?probe=9f4642f6a5) | Oct 05, 2022 |
| Dell          | Precision 5510              | [f69c9fb0ea](https://bsd-hardware.info/?probe=f69c9fb0ea) | Oct 04, 2022 |
| Dell          | Latitude E6420              | [07b078fdef](https://bsd-hardware.info/?probe=07b078fdef) | Oct 04, 2022 |
| Lenovo        | ThinkPad T410 2518C3U       | [627206d154](https://bsd-hardware.info/?probe=627206d154) | Oct 04, 2022 |
| Lenovo        | Legion 5 15IMH05 82AU       | [d89559e5c2](https://bsd-hardware.info/?probe=d89559e5c2) | Oct 03, 2022 |
| Toshiba       | NB300                       | [c18ae50101](https://bsd-hardware.info/?probe=c18ae50101) | Oct 03, 2022 |
| TUXEDO        | Aura 15 Gen1                | [e83d522905](https://bsd-hardware.info/?probe=e83d522905) | Oct 03, 2022 |
| Dell          | Precision M4500             | [6b987b43b1](https://bsd-hardware.info/?probe=6b987b43b1) | Oct 03, 2022 |
| TUXEDO        | Aura 15 Gen1                | [a49ac2701d](https://bsd-hardware.info/?probe=a49ac2701d) | Oct 02, 2022 |
| HP            | ProBook 4540s               | [df94757940](https://bsd-hardware.info/?probe=df94757940) | Oct 02, 2022 |
| Dell          | Precision M4800             | [0fcbdeeeb7](https://bsd-hardware.info/?probe=0fcbdeeeb7) | Oct 02, 2022 |
| HP            | 255 G8 Notebook PC          | [f9851a3257](https://bsd-hardware.info/?probe=f9851a3257) | Oct 01, 2022 |
| MSI           | GL65 Leopard 10SFSK         | [489567748e](https://bsd-hardware.info/?probe=489567748e) | Oct 01, 2022 |
| Lenovo        | ThinkPad E15 2ORES4XJ00     | [323a95e6a9](https://bsd-hardware.info/?probe=323a95e6a9) | Oct 01, 2022 |
| Deciso        | OPNsense Appliance          | [9b95ddf7b9](https://bsd-hardware.info/?probe=9b95ddf7b9) | Oct 01, 2022 |
| IBM           | ThinkPad T43 18714AG        | [5fd9a63834](https://bsd-hardware.info/?probe=5fd9a63834) | Sep 30, 2022 |
| Kraftway      | KW10T                       | [db27da2e88](https://bsd-hardware.info/?probe=db27da2e88) | Sep 29, 2022 |
| Lenovo        | ThinkPad W530 2436CTO       | [6515a18552](https://bsd-hardware.info/?probe=6515a18552) | Sep 29, 2022 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [62b9a56103](https://bsd-hardware.info/?probe=62b9a56103) | Sep 29, 2022 |
| Intel         | H81U                        | [fa8c32528a](https://bsd-hardware.info/?probe=fa8c32528a) | Sep 28, 2022 |
| Tactus        | GeoFlex 110                 | [0b93b5f915](https://bsd-hardware.info/?probe=0b93b5f915) | Sep 28, 2022 |
| Lenovo        | ThinkPad X61 Tablet 7763... | [1f37ebf2bb](https://bsd-hardware.info/?probe=1f37ebf2bb) | Sep 28, 2022 |
| Acer          | Swift SF313-52              | [83516dabac](https://bsd-hardware.info/?probe=83516dabac) | Sep 28, 2022 |
| Deciso        | OPNsense Appliance          | [659b695f09](https://bsd-hardware.info/?probe=659b695f09) | Sep 26, 2022 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | [b2024820d1](https://bsd-hardware.info/?probe=b2024820d1) | Sep 26, 2022 |
| Acer          | Swift SF313-52              | [6339e6b468](https://bsd-hardware.info/?probe=6339e6b468) | Sep 25, 2022 |
| Gigabyte      | GB-BSi5A-6200               | [c947635b8f](https://bsd-hardware.info/?probe=c947635b8f) | Sep 25, 2022 |
| Gigabyte      | GB-BSi5A-6200               | [533c7f35f1](https://bsd-hardware.info/?probe=533c7f35f1) | Sep 25, 2022 |
| IBM           | ThinkPad T40 23737CG        | [dfc9b64da2](https://bsd-hardware.info/?probe=dfc9b64da2) | Sep 25, 2022 |
| System76      | Gazelle                     | [d087321049](https://bsd-hardware.info/?probe=d087321049) | Sep 24, 2022 |
| Dell          | System Vostro 3750          | [166fbacd73](https://bsd-hardware.info/?probe=166fbacd73) | Sep 24, 2022 |
| Lenovo        | G475 20080                  | [fb07463a9a](https://bsd-hardware.info/?probe=fb07463a9a) | Sep 24, 2022 |
| Lenovo        | G475 20080                  | [c4b1acb6d1](https://bsd-hardware.info/?probe=c4b1acb6d1) | Sep 24, 2022 |
| System76      | Gazelle                     | [6d5d4f5021](https://bsd-hardware.info/?probe=6d5d4f5021) | Sep 24, 2022 |
| Lenovo        | ThinkPad T460p 20FW003PM... | [ac8e728222](https://bsd-hardware.info/?probe=ac8e728222) | Sep 24, 2022 |
| Deciso        | Netboard A20                | [388e27791d](https://bsd-hardware.info/?probe=388e27791d) | Sep 23, 2022 |
| Toshiba       | Satellite BE96-F299         | [15b93c9f4b](https://bsd-hardware.info/?probe=15b93c9f4b) | Sep 21, 2022 |
| Toshiba       | Satellite BE96-F299         | [9beae1547d](https://bsd-hardware.info/?probe=9beae1547d) | Sep 21, 2022 |
| Unknown       | Unknown                     | [fbd1af0e98](https://bsd-hardware.info/?probe=fbd1af0e98) | Sep 21, 2022 |
| Deciso        | OPNsense Appliance          | [5cec3595a3](https://bsd-hardware.info/?probe=5cec3595a3) | Sep 21, 2022 |
| Acer          | Aspire E5-771               | [0a58077c49](https://bsd-hardware.info/?probe=0a58077c49) | Sep 20, 2022 |
| Toshiba       | PORTEGE R700                | [10b85eccae](https://bsd-hardware.info/?probe=10b85eccae) | Sep 19, 2022 |
| HP            | EliteBook 840 G3            | [322c8947b6](https://bsd-hardware.info/?probe=322c8947b6) | Sep 19, 2022 |
| HP            | EliteBook 840 G3            | [0307c109b5](https://bsd-hardware.info/?probe=0307c109b5) | Sep 19, 2022 |
| Lenovo        | ThinkPad X250 20CLS1WP01    | [1b75ee6295](https://bsd-hardware.info/?probe=1b75ee6295) | Sep 19, 2022 |
| Dell          | Precision 7710              | [4c4937d824](https://bsd-hardware.info/?probe=4c4937d824) | Sep 18, 2022 |
| HP            | Pavilion dv6700             | [f3058f97f9](https://bsd-hardware.info/?probe=f3058f97f9) | Sep 18, 2022 |
| Lenovo        | ThinkPad X250 20CL001GUS    | [2f1f82558e](https://bsd-hardware.info/?probe=2f1f82558e) | Sep 18, 2022 |
| Fujitsu       | LIFEBOOK A532               | [91e0f723ea](https://bsd-hardware.info/?probe=91e0f723ea) | Sep 18, 2022 |
| Lenovo        | G50-30 80G0                 | [da4bd87fee](https://bsd-hardware.info/?probe=da4bd87fee) | Sep 17, 2022 |
| ASUSTek       | X455LJ                      | [431ad10ab2](https://bsd-hardware.info/?probe=431ad10ab2) | Sep 17, 2022 |
| HP            | EliteBook 840 G3            | [7bf7249432](https://bsd-hardware.info/?probe=7bf7249432) | Sep 16, 2022 |

...


System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| helloSystem 0.7.0    | 224       | 7.76%   |
| helloSystem 0.8.1    | 140       | 4.85%   |
| helloSystem 0.8.0    | 133       | 4.61%   |
| helloSystem 0.5.0    | 116       | 4.02%   |
| FreeBSD 13.1         | 113       | 3.92%   |
| FreeBSD 13.0         | 111       | 3.85%   |
| helloSystem 0.4.0    | 92        | 3.19%   |
| OpenBSD 6.8          | 90        | 3.12%   |
| FreeBSD 14.0-CURRENT | 73        | 2.53%   |
| helloSystem 0.6.0    | 71        | 2.46%   |
| FreeBSD 12.2         | 59        | 2.05%   |
| GhostBSD 20.04.02    | 58        | 2.01%   |
| OpenBSD 7.2          | 56        | 1.94%   |
| OpenBSD 6.9          | 55        | 1.91%   |
| OpenBSD 7.0          | 50        | 1.73%   |
| FreeBSD 13.2         | 47        | 1.63%   |
| OpenBSD 7.1          | 41        | 1.42%   |
| FreeBSD 13.1-p5      | 41        | 1.42%   |
| FreeBSD 13.0-p4      | 35        | 1.21%   |
| NomadBSD 1.3.2       | 34        | 1.18%   |
| FreeBSD 12.2-p2      | 34        | 1.18%   |
| NomadBSD 5806f915    | 32        | 1.11%   |
| OpenBSD 7.3          | 31        | 1.07%   |
| FreeBSD 13.0-CURRENT | 31        | 1.07%   |
| GhostBSD 21.08.27    | 29        | 1.01%   |
| FreeBSD 13.0-STABLE  | 28        | 0.97%   |
| FreeBSD 12.1         | 28        | 0.97%   |
| FreeBSD 12.1-p8      | 26        | 0.9%    |
| FreeBSD 13.0-p5      | 25        | 0.87%   |
| OpenBSD 6.7          | 23        | 0.8%    |
| FreeBSD 13.0-p3      | 23        | 0.8%    |
| FreeBSD 12.2-p4      | 23        | 0.8%    |
| FreeBSD 12.1-p10     | 23        | 0.8%    |
| helloSystem 0.8.2    | 22        | 0.76%   |
| FreeBSD 13.1-p7      | 22        | 0.76%   |
| FreeBSD 13.1-p2      | 21        | 0.73%   |
| FreeBSD 12.1-p5      | 20        | 0.69%   |
| FreeBSD 13.0-p7      | 19        | 0.66%   |
| NomadBSD 1.4         | 18        | 0.62%   |
| FreeBSD 12.2-p3      | 18        | 0.62%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 930       | 37.39%  |
| helloSystem | 755       | 30.36%  |
| OpenBSD     | 277       | 11.14%  |
| OPNsense    | 214       | 8.6%    |
| GhostBSD    | 149       | 5.99%   |
| NomadBSD    | 109       | 4.38%   |
| NetBSD      | 21        | 0.84%   |
| HardenedBSD | 7         | 0.28%   |
| FuryBSD     | 6         | 0.24%   |
| DragonFly   | 6         | 0.24%   |
| MidnightBSD | 4         | 0.16%   |
| FuguIta     | 4         | 0.16%   |
| OS108       | 2         | 0.08%   |
| PC-BSD      | 1         | 0.04%   |
| MyBee       | 1         | 0.04%   |
| LibertyBSD  | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| amd64  | 2322      | 96.27%  |
| i386   | 85        | 3.52%   |
| macppc | 3         | 0.12%   |
| arm64  | 2         | 0.08%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| helloDesktop  | 831       | 32.64%  |
| Console       | 351       | 13.79%  |
| XFCE          | 276       | 10.84%  |
| KDE5          | 213       | 8.37%   |
| MATE          | 182       | 7.15%   |
| fvwm          | 181       | 7.11%   |
| Openbox       | 118       | 4.63%   |
| GNOME         | 107       | 4.2%    |
| TWM           | 89        | 3.5%    |
| i3            | 76        | 2.99%   |
| Cinnamon      | 19        | 0.75%   |
| LXQt          | 15        | 0.59%   |
| AwesomeWM     | 15        | 0.59%   |
| Fluxbox       | 11        | 0.43%   |
| Enlightenment | 9         | 0.35%   |
| LXDE          | 8         | 0.31%   |
| xinitrc       | 6         | 0.24%   |
| Lumina        | 5         | 0.2%    |
| DWM           | 5         | 0.2%    |
| IceWM         | 4         | 0.16%   |
| CTWM          | 4         | 0.16%   |
| GNUstep       | 3         | 0.12%   |
| spectrwm      | 2         | 0.08%   |
| Picom         | 2         | 0.08%   |
| Mutter        | 2         | 0.08%   |
| Awesome       | 2         | 0.08%   |
| Xfwm4         | 1         | 0.04%   |
| X-Cinnamon    | 1         | 0.04%   |
| Window Maker  | 1         | 0.04%   |
| sway          | 1         | 0.04%   |
| StumpWM       | 1         | 0.04%   |
| sdorfehs      | 1         | 0.04%   |
| iwm           | 1         | 0.04%   |
| Compton       | 1         | 0.04%   |
| CDE           | 1         | 0.04%   |
| Budgie        | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2038      | 83.66%  |
| Console | 370       | 15.19%  |
| Wayland | 28        | 1.15%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 1023      | 40.81%  |
| Console | 860       | 34.3%   |
| SDDM    | 230       | 9.17%   |
| LightDM | 222       | 8.86%   |
| XDM     | 83        | 3.31%   |
| GDM     | 73        | 2.91%   |
| Ly      | 13        | 0.52%   |
| PCDM    | 2         | 0.08%   |
| WDM     | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| en_US           | 850       | 33.46%  |
| Unknown         | 720       | 28.35%  |
| C               | 497       | 19.57%  |
| ru_RU           | 68        | 2.68%   |
| fr_FR           | 60        | 2.36%   |
| de_DE           | 52        | 2.05%   |
| en              | 50        | 1.97%   |
| en_GB           | 36        | 1.42%   |
| es_ES           | 23        | 0.91%   |
| zh_CN           | 20        | 0.79%   |
| pl_PL           | 17        | 0.67%   |
| pt_BR           | 14        | 0.55%   |
| it_IT           | 10        | 0.39%   |
| en_CA           | 7         | 0.28%   |
| ru              | 6         | 0.24%   |
| pt              | 6         | 0.24%   |
| de              | 6         | 0.24%   |
| en_NZ           | 5         | 0.2%    |
| en_AU           | 5         | 0.2%    |
| cs_CZ           | 5         | 0.2%    |
| uk_UA           | 4         | 0.16%   |
| nb_NO           | 4         | 0.16%   |
| ja_JP           | 4         | 0.16%   |
| es              | 4         | 0.16%   |
| nl_NL           | 3         | 0.12%   |
| ko_KR           | 3         | 0.12%   |
| fi_FI           | 3         | 0.12%   |
| en_US.US-ASCII  | 3         | 0.12%   |
| en_US.ISO8859-1 | 3         | 0.12%   |
| tr_TR           | 2         | 0.08%   |
| it              | 2         | 0.08%   |
| hu_HU           | 2         | 0.08%   |
| fr              | 2         | 0.08%   |
| es_CO           | 2         | 0.08%   |
| es_AR           | 2         | 0.08%   |
| en_SG           | 2         | 0.08%   |
| en_IE           | 2         | 0.08%   |
| de_DE.ISO8859-1 | 2         | 0.08%   |
| de_CH           | 2         | 0.08%   |
| zh_TW           | 1         | 0.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1921      | 78.76%  |
| BIOS | 518       | 21.24%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Zfs     | 1334      | 53.57%  |
| Ufs     | 605       | 24.3%   |
| Ffs     | 282       | 11.33%  |
| Cd9660  | 262       | 10.52%  |
| Hammer2 | 5         | 0.2%    |
| Xfs     | 1         | 0.04%   |
| Nfs     | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 2129      | 87.47%  |
| MBR     | 276       | 11.34%  |
| Unknown | 24        | 0.99%   |
| BSD     | 5         | 0.21%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 798       | 33.11%  |
| Dell                           | 355       | 14.73%  |
| Hewlett-Packard                | 255       | 10.58%  |
| ASUSTek Computer               | 160       | 6.64%   |
| Acer                           | 135       | 5.6%    |
| Apple                          | 96        | 3.98%   |
| Deciso                         | 62        | 2.57%   |
| Toshiba                        | 56        | 2.32%   |
| Unknown                        | 49        | 2.03%   |
| Samsung Electronics            | 44        | 1.83%   |
| Sony                           | 33        | 1.37%   |
| MSI                            | 29        | 1.2%    |
| Fujitsu                        | 28        | 1.16%   |
| Intel                          | 21        | 0.87%   |
| Google                         | 21        | 0.87%   |
| TUXEDO                         | 17        | 0.71%   |
| Panasonic                      | 17        | 0.71%   |
| Notebook                       | 17        | 0.71%   |
| System76                       | 15        | 0.62%   |
| HUAWEI                         | 15        | 0.62%   |
| IBM                            | 13        | 0.54%   |
| Packard Bell                   | 9         | 0.37%   |
| Framework                      | 8         | 0.33%   |
| Alienware                      | 8         | 0.33%   |
| Timi                           | 7         | 0.29%   |
| LG Electronics                 | 6         | 0.25%   |
| Gigabyte Technology            | 6         | 0.25%   |
| Fujitsu Siemens                | 6         | 0.25%   |
| Shuttle                        | 5         | 0.21%   |
| Medion                         | 5         | 0.21%   |
| Gateway                        | 5         | 0.21%   |
| eMachines                      | 5         | 0.21%   |
| Star Labs                      | 4         | 0.17%   |
| SLIMBOOK                       | 4         | 0.17%   |
| Datto                          | 4         | 0.17%   |
| Clevo                          | 4         | 0.17%   |
| Razer                          | 3         | 0.12%   |
| Matsushita Electric Industrial | 3         | 0.12%   |
| IGEL Technology                | 3         | 0.12%   |
| GPD                            | 3         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 61        | 2.53%   |
| Deciso Netboard A20                 | 21        | 0.87%   |
| Deciso NetBoard-A10                 | 17        | 0.71%   |
| Deciso OPNsense Appliance           | 10        | 0.41%   |
| Intel H81U                          | 9         | 0.37%   |
| HP EliteBook 840 G3                 | 9         | 0.37%   |
| Dell Latitude E7240                 | 8         | 0.33%   |
| Dell Latitude E6420                 | 8         | 0.33%   |
| Deciso NetBoard-A20                 | 8         | 0.33%   |
| Framework Laptop                    | 7         | 0.29%   |
| Dell Latitude E6430                 | 7         | 0.29%   |
| Dell Inspiron 3542                  | 7         | 0.29%   |
| Dell Inspiron 3442                  | 7         | 0.29%   |
| Apple MacBook4,1                    | 7         | 0.29%   |
| Lenovo ThinkPad X200 745969G        | 6         | 0.25%   |
| HP Pavilion dv6                     | 6         | 0.25%   |
| HP Notebook                         | 6         | 0.25%   |
| Dell Latitude E5570                 | 6         | 0.25%   |
| Dell Inspiron 15-3567               | 6         | 0.25%   |
| Deciso DEC2700 - OPNsense Appliance | 6         | 0.25%   |
| Apple MacBookPro8,1                 | 6         | 0.25%   |
| Apple MacBook5,1                    | 6         | 0.25%   |
| HP Pavilion Notebook                | 5         | 0.21%   |
| HP Pavilion g6                      | 5         | 0.21%   |
| HP 2000                             | 5         | 0.21%   |
| Dell XPS 13 9360                    | 5         | 0.21%   |
| Dell Precision M4800                | 5         | 0.21%   |
| Dell Latitude E5470                 | 5         | 0.21%   |
| Dell Latitude 5400                  | 5         | 0.21%   |
| Dell Inspiron 3521                  | 5         | 0.21%   |
| Apple MacBookPro9,2                 | 5         | 0.21%   |
| Apple MacBookAir5,1                 | 5         | 0.21%   |
| TUXEDO Pulse 15 Gen1                | 4         | 0.17%   |
| System76 Lemur Pro                  | 4         | 0.17%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS  | 4         | 0.17%   |
| Lenovo ThinkPad X220 4286CTO        | 4         | 0.17%   |
| Lenovo ThinkPad T490 20N2CTO1WW     | 4         | 0.17%   |
| HP EliteBook 8570p                  | 4         | 0.17%   |
| Google Peppy                        | 4         | 0.17%   |
| Fujitsu LIFEBOOK A555               | 4         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 625       | 25.93%  |
| Dell Latitude       | 161       | 6.68%   |
| Dell Inspiron       | 99        | 4.11%   |
| Acer Aspire         | 89        | 3.69%   |
| Lenovo IdeaPad      | 69        | 2.86%   |
| Unknown             | 61        | 2.53%   |
| HP EliteBook        | 49        | 2.03%   |
| HP Pavilion         | 46        | 1.91%   |
| Toshiba Satellite   | 38        | 1.58%   |
| HP ProBook          | 35        | 1.45%   |
| Dell Precision      | 34        | 1.41%   |
| HP Laptop           | 32        | 1.33%   |
| Dell XPS            | 25        | 1.04%   |
| Fujitsu LIFEBOOK    | 22        | 0.91%   |
| Deciso Netboard     | 21        | 0.87%   |
| Dell Vostro         | 19        | 0.79%   |
| ASUS VivoBook       | 19        | 0.79%   |
| Deciso NetBoard-A10 | 17        | 0.71%   |
| Lenovo Yoga         | 15        | 0.62%   |
| Lenovo Legion       | 14        | 0.58%   |
| HP Compaq           | 13        | 0.54%   |
| HP ZBook            | 12        | 0.5%    |
| IBM ThinkPad        | 11        | 0.46%   |
| Deciso OPNsense     | 10        | 0.41%   |
| Apple MacBookPro8   | 10        | 0.41%   |
| Intel H81U          | 9         | 0.37%   |
| ASUS ASUS           | 9         | 0.37%   |
| Apple MacBookPro5   | 9         | 0.37%   |
| Framework Laptop    | 8         | 0.33%   |
| Deciso NetBoard-A20 | 8         | 0.33%   |
| ASUS ZenBook        | 8         | 0.33%   |
| Apple MacBookPro11  | 8         | 0.33%   |
| Apple MacBook5      | 8         | 0.33%   |
| Acer TravelMate     | 8         | 0.33%   |
| Acer Swift          | 8         | 0.33%   |
| Acer Nitro          | 8         | 0.33%   |
| TUXEDO Pulse        | 7         | 0.29%   |
| Toshiba PORTEGE     | 7         | 0.29%   |
| HP OMEN             | 7         | 0.29%   |
| Apple MacBook4      | 7         | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 240       | 9.96%   |
| 2019    | 219       | 9.09%   |
| 2021    | 195       | 8.09%   |
| 2013    | 181       | 7.51%   |
| 2011    | 180       | 7.47%   |
| 2018    | 175       | 7.26%   |
| 2012    | 152       | 6.31%   |
| 2015    | 148       | 6.14%   |
| 2022    | 146       | 6.06%   |
| 2016    | 143       | 5.93%   |
| 2010    | 122       | 5.06%   |
| 2014    | 121       | 5.02%   |
| 2017    | 117       | 4.85%   |
| 2009    | 92        | 3.82%   |
| 2008    | 71        | 2.95%   |
| 2007    | 44        | 1.83%   |
| 2006    | 24        | 1%      |
| Unknown | 11        | 0.46%   |
| 2023    | 10        | 0.41%   |
| 2005    | 6         | 0.25%   |
| 2004    | 5         | 0.21%   |
| 2003    | 5         | 0.21%   |
| 2002    | 3         | 0.12%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2410      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2365      | 98.13%  |
| Yes  | 45        | 1.87%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 885       | 36.29%  |
| 4.01-8.0    | 578       | 23.7%   |
| 16.01-24.0  | 548       | 22.47%  |
| 32.01-64.0  | 132       | 5.41%   |
| 2.01-3.0    | 120       | 4.92%   |
| 3.01-4.0    | 62        | 2.54%   |
| 24.01-32.0  | 31        | 1.27%   |
| 64.01-256.0 | 27        | 1.11%   |
| 0.51-1.0    | 26        | 1.07%   |
| 1.01-2.0    | 21        | 0.86%   |
| 0.01-0.5    | 8         | 0.33%   |
| 0           | 1         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Notebooks | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 1379      | 55.9%   |
| 0.51-1.0    | 676       | 27.4%   |
| 1.01-2.0    | 230       | 9.32%   |
| 2.01-3.0    | 71        | 2.88%   |
| Unknown     | 26        | 1.05%   |
| 4.01-8.0    | 25        | 1.01%   |
| 8.01-16.0   | 20        | 0.81%   |
| 0           | 20        | 0.81%   |
| 3.01-4.0    | 9         | 0.36%   |
| 24.01-32.0  | 4         | 0.16%   |
| 16.01-24.0  | 4         | 0.16%   |
| 32.01-64.0  | 2         | 0.08%   |
| 64.01-256.0 | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1804      | 73.07%  |
| 2      | 464       | 18.79%  |
| 0      | 123       | 4.98%   |
| 3      | 67        | 2.71%   |
| 4      | 10        | 0.41%   |
| 58     | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1744      | 71.74%  |
| Yes       | 687       | 28.26%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2078      | 86.19%  |
| No        | 333       | 13.81%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2245      | 93%     |
| No        | 169       | 7%      |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1577      | 64.74%  |
| No        | 859       | 35.26%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 468       | 19.27%  |
| Germany     | 269       | 11.07%  |
| Russia      | 164       | 6.75%   |
| France      | 122       | 5.02%   |
| Brazil      | 97        | 3.99%   |
| UK          | 94        | 3.87%   |
| Poland      | 79        | 3.25%   |
| Canada      | 75        | 3.09%   |
| China       | 70        | 2.88%   |
| Spain       | 64        | 2.63%   |
| Italy       | 64        | 2.63%   |
| Netherlands | 63        | 2.59%   |
| Indonesia   | 42        | 1.73%   |
| Australia   | 42        | 1.73%   |
| Ukraine     | 41        | 1.69%   |
| India       | 36        | 1.48%   |
| Switzerland | 35        | 1.44%   |
| Austria     | 33        | 1.36%   |
| Sweden      | 32        | 1.32%   |
| Czechia     | 26        | 1.07%   |
| Romania     | 25        | 1.03%   |
| Hungary     | 25        | 1.03%   |
| Japan       | 24        | 0.99%   |
| Norway      | 22        | 0.91%   |
| Mexico      | 22        | 0.91%   |
| Finland     | 20        | 0.82%   |
| Portugal    | 19        | 0.78%   |
| Bulgaria    | 17        | 0.7%    |
| Argentina   | 16        | 0.66%   |
| Turkey      | 15        | 0.62%   |
| Greece      | 14        | 0.58%   |
| Denmark     | 14        | 0.58%   |
| Colombia    | 13        | 0.54%   |
| Belgium     | 13        | 0.54%   |
| Philippines | 12        | 0.49%   |
| New Zealand | 12        | 0.49%   |
| Vietnam     | 11        | 0.45%   |
| Latvia      | 11        | 0.45%   |
| Ireland     | 10        | 0.41%   |
| Slovakia    | 9         | 0.37%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 61        | 2.32%   |
| Berlin            | 29        | 1.11%   |
| Vienna            | 27        | 1.03%   |
| Montreal          | 24        | 0.91%   |
| Paris             | 22        | 0.84%   |
| Brooklyn          | 22        | 0.84%   |
| St Petersburg     | 19        | 0.72%   |
| Zurich            | 17        | 0.65%   |
| Warsaw            | 16        | 0.61%   |
| Jakarta           | 16        | 0.61%   |
| Amsterdam         | 15        | 0.57%   |
| Saint-Laurent     | 14        | 0.53%   |
| Kyiv              | 14        | 0.53%   |
| Seattle           | 12        | 0.46%   |
| Rome              | 12        | 0.46%   |
| Madrid            | 12        | 0.46%   |
| Sydney            | 11        | 0.42%   |
| Riga              | 11        | 0.42%   |
| Munich            | 11        | 0.42%   |
| Portland          | 10        | 0.38%   |
| London            | 10        | 0.38%   |
| Frankfurt am Main | 10        | 0.38%   |
| Dublin            | 10        | 0.38%   |
| Sao Paulo         | 9         | 0.34%   |
| New York          | 9         | 0.34%   |
| Los Angeles       | 9         | 0.34%   |
| Krakow            | 9         | 0.34%   |
| Budapest          | 9         | 0.34%   |
| Bucharest         | 9         | 0.34%   |
| Wroclaw           | 8         | 0.3%    |
| Sofia             | 8         | 0.3%    |
| Milan             | 8         | 0.3%    |
| Brighton          | 8         | 0.3%    |
| Barcelona         | 8         | 0.3%    |
| Athens            | 8         | 0.3%    |
| Vilnius           | 7         | 0.27%   |
| Vancouver         | 7         | 0.27%   |
| Shanghai          | 7         | 0.27%   |
| Perth             | 7         | 0.27%   |
| Hamburg           | 7         | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 484       | 645    | 17.47%  |
| WDC                 | 350       | 451    | 12.63%  |
| Seagate             | 245       | 306    | 8.84%   |
| Toshiba             | 197       | 274    | 7.11%   |
| Kingston            | 170       | 209    | 6.13%   |
| SanDisk             | 140       | 163    | 5.05%   |
| Crucial             | 136       | 180    | 4.91%   |
| Transcend           | 105       | 146    | 3.79%   |
| Hitachi             | 105       | 125    | 3.79%   |
| Intel               | 88        | 110    | 3.18%   |
| NVMe                | 78        | 105    | 2.81%   |
| SK hynix            | 58        | 68     | 2.09%   |
| HGST                | 58        | 131    | 2.09%   |
| A-DATA Technology   | 46        | 62     | 1.66%   |
| Micron Technology   | 43        | 51     | 1.55%   |
| Apple               | 36        | 38     | 1.3%    |
| PNY                 | 23        | 26     | 0.83%   |
| Fujitsu             | 23        | 32     | 0.83%   |
| SPCC                | 22        | 27     | 0.79%   |
| Phison              | 18        | 25     | 0.65%   |
| KIOXIA              | 18        | 18     | 0.65%   |
| KingSpec            | 17        | 21     | 0.61%   |
| China               | 16        | 18     | 0.58%   |
| Gigabyte Technology | 15        | 20     | 0.54%   |
| LITEON              | 13        | 18     | 0.47%   |
| OCZ                 | 12        | 16     | 0.43%   |
| Patriot             | 11        | 14     | 0.4%    |
| Intenso             | 11        | 12     | 0.4%    |
| Corsair             | 11        | 11     | 0.4%    |
| FORESEE             | 10        | 12     | 0.36%   |
| Apacer              | 10        | 12     | 0.36%   |
| SSSTC               | 9         | 9      | 0.32%   |
| OWC                 | 9         | 10     | 0.32%   |
| Hewlett-Packard     | 9         | 12     | 0.32%   |
| Silicon Motion      | 8         | 8      | 0.29%   |
| Netac               | 7         | 7      | 0.25%   |
| LITEONIT            | 7         | 7      | 0.25%   |
| Lexar               | 7         | 13     | 0.25%   |
| Team                | 6         | 7      | 0.22%   |
| Plextor             | 6         | 6      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB         | 39        | 1.36%   |
| Seagate ST1000LM035-1RK172 1TB      | 33        | 1.15%   |
| Transcend TS256GMTS952T2 256GB      | 28        | 0.98%   |
| Toshiba MQ01ABD100 1TB              | 28        | 0.98%   |
| Samsung SSD 860 EVO 500GB           | 24        | 0.84%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 23        | 0.8%    |
| Toshiba MQ01ABF050 500GB            | 22        | 0.77%   |
| Crucial CT500MX500SSD1 500GB        | 22        | 0.77%   |
| Transcend TS256GMTE652T2 256GB      | 21        | 0.73%   |
| Samsung SSD 850 EVO 250GB           | 20        | 0.7%    |
| HGST HTS721010A9E630 1TB            | 17        | 0.59%   |
| Kingston SA400S37120G 120GB         | 16        | 0.56%   |
| Samsung SSD 850 EVO 500GB           | 15        | 0.52%   |
| HGST HTS725050A7E630 500GB          | 14        | 0.49%   |
| WDC WDS240G2G0A-00JH30 240GB        | 13        | 0.45%   |
| Seagate ST500LT012-9WS142 500GB     | 13        | 0.45%   |
| Samsung SSD 860 EVO 250GB           | 13        | 0.45%   |
| Kingston SA400S37480G 480GB         | 13        | 0.45%   |
| Crucial CT1000MX500SSD1 1TB         | 13        | 0.45%   |
| Toshiba MQ04ABF100 1TB              | 12        | 0.42%   |
| Seagate ST9500325AS 500GB           | 12        | 0.42%   |
| Seagate ST500LT012-1DG142 500GB     | 11        | 0.38%   |
| SanDisk SSD PLUS 240GB              | 11        | 0.38%   |
| Kingston SV300S37A120G 120GB        | 11        | 0.38%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 10        | 0.35%   |
| Seagate ST9500420AS 500GB           | 10        | 0.35%   |
| Samsung SSD 970 EVO Plus 1TB        | 10        | 0.35%   |
| Samsung SSD 860 EVO 1TB             | 10        | 0.35%   |
| Samsung MZVLW256HEHP-000L7 256GB    | 10        | 0.35%   |
| Intel SSDPEKKF256G8L 256GB          | 10        | 0.35%   |
| Crucial CT240BX500SSD1 240GB        | 10        | 0.35%   |
| Seagate ST9320423AS 320GB           | 9         | 0.31%   |
| Seagate ST1000LM049-2GH172 1TB      | 9         | 0.31%   |
| Seagate ST1000LM048-2E7172 1TB      | 9         | 0.31%   |
| Samsung HM321HI 320GB               | 9         | 0.31%   |
| Crucial CT480BX500SSD1 480GB        | 9         | 0.31%   |
| WDC WD10JPVX-22JC3T0 1TB            | 8         | 0.28%   |
| Transcend TS128GMTE110S 128GB       | 8         | 0.28%   |
| Seagate ST500LM021-1KJ152 500GB     | 8         | 0.28%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 8         | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                                 | Notebooks | Drives | Percent |
|----------------------------------------|-----------|--------|---------|
| Seagate                                | 244       | 305    | 27.23%  |
| WDC                                    | 222       | 281    | 24.78%  |
| Toshiba                                | 140       | 193    | 15.63%  |
| Hitachi                                | 105       | 125    | 11.72%  |
| HGST                                   | 58        | 131    | 6.47%   |
| NVMe                                   | 54        | 71     | 6.03%   |
| Samsung Electronics                    | 31        | 35     | 3.46%   |
| Fujitsu                                | 22        | 30     | 2.46%   |
| Apple                                  | 4         | 4      | 0.45%   |
| Product:              USB Flash Memory | 2         | 2      | 0.22%   |
| Lexar                                  | 2         | 2      | 0.22%   |
| Generic                                | 2         | 2      | 0.22%   |
| Verbatim                               | 1         | 1      | 0.11%   |
| USB                                    | 1         | 1      | 0.11%   |
| UFD 2.0                                | 1         | 1      | 0.11%   |
| SMI                                    | 1         | 1      | 0.11%   |
| OPENBSD                                | 1         | 1      | 0.11%   |
| LDLC F6+                               | 1         | 1      | 0.11%   |
| Jetflash                               | 1         | 1      | 0.11%   |
| IBM/Hitachi                            | 1         | 1      | 0.11%   |
| HPE                                    | 1         | 5      | 0.11%   |
| General                                | 1         | 1      | 0.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 285       | 374    | 21.56%  |
| Kingston            | 145       | 178    | 10.97%  |
| SanDisk             | 139       | 162    | 10.51%  |
| Crucial             | 115       | 149    | 8.7%    |
| Transcend           | 71        | 108    | 5.37%   |
| WDC                 | 63        | 81     | 4.77%   |
| Intel               | 53        | 71     | 4.01%   |
| Apple               | 32        | 34     | 2.42%   |
| A-DATA Technology   | 28        | 39     | 2.12%   |
| Toshiba             | 27        | 33     | 2.04%   |
| SK hynix            | 22        | 23     | 1.66%   |
| PNY                 | 21        | 24     | 1.59%   |
| NVMe                | 21        | 24     | 1.59%   |
| Micron Technology   | 21        | 25     | 1.59%   |
| SPCC                | 20        | 24     | 1.51%   |
| KingSpec            | 17        | 21     | 1.29%   |
| China               | 16        | 18     | 1.21%   |
| OCZ                 | 12        | 16     | 0.91%   |
| LITEON              | 12        | 17     | 0.91%   |
| Patriot             | 11        | 14     | 0.83%   |
| Intenso             | 11        | 12     | 0.83%   |
| Corsair             | 11        | 11     | 0.83%   |
| Gigabyte Technology | 10        | 13     | 0.76%   |
| Apacer              | 10        | 12     | 0.76%   |
| OWC                 | 9         | 10     | 0.68%   |
| Hewlett-Packard     | 8         | 11     | 0.61%   |
| Netac               | 7         | 7      | 0.53%   |
| LITEONIT            | 7         | 7      | 0.53%   |
| Team                | 6         | 7      | 0.45%   |
| Plextor             | 6         | 6      | 0.45%   |
| GOODRAM             | 6         | 6      | 0.45%   |
| Phison              | 5         | 6      | 0.38%   |
| Lexar               | 5         | 11     | 0.38%   |
| Kston               | 5         | 7      | 0.38%   |
| Hoodisk             | 5         | 6      | 0.38%   |
| Zheino              | 4         | 7      | 0.3%    |
| Mushkin             | 4         | 4      | 0.3%    |
| FORESEE             | 4         | 6      | 0.3%    |
| Leven               | 3         | 3      | 0.23%   |
| KingDian            | 3         | 3      | 0.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1193      | 1665   | 46.29%  |
| HDD  | 842       | 1195   | 32.67%  |
| NVMe | 542       | 721    | 21.03%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1876      | 2860   | 77.58%  |
| NVMe | 542       | 721    | 22.42%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Notebooks | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 1515      | 2129   | 75.11%  |
| 0.51-1.0        | 419       | 572    | 20.77%  |
| 1.01-2.0        | 71        | 98     | 3.52%   |
| 3.01-4.0        | 4         | 52     | 0.2%    |
| 4.01-10.0       | 3         | 3      | 0.15%   |
| More than 100.0 | 2         | 2      | 0.1%    |
| 2.01-3.0        | 2         | 3      | 0.1%    |
| 0               | 1         | 1      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 798       | 31.34%  |
| 1-20           | 605       | 23.76%  |
| 251-500        | 514       | 20.19%  |
| 501-1000       | 227       | 8.92%   |
| 51-100         | 198       | 7.78%   |
| 21-50          | 136       | 5.34%   |
| 1001-2000      | 42        | 1.65%   |
| Unknown        | 22        | 0.86%   |
| 2001-3000      | 3         | 0.12%   |
| More than 3000 | 1         | 0.04%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 2086      | 83.47%  |
| 21-50          | 207       | 8.28%   |
| 51-100         | 81        | 3.24%   |
| 101-250        | 71        | 2.84%   |
| Unknown        | 22        | 0.88%   |
| 251-500        | 20        | 0.8%    |
| 501-1000       | 11        | 0.44%   |
| More than 3000 | 1         | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB              | 11        | 12     | 2.58%   |
| Seagate ST500LT012-9WS142 500GB     | 10        | 14     | 2.35%   |
| HGST HTS725050A7E630 500GB          | 9         | 15     | 2.11%   |
| Seagate ST9500420AS 500GB           | 8         | 10     | 1.88%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 8         | 10     | 1.88%   |
| Toshiba MQ01ABF050 500GB            | 6         | 8      | 1.41%   |
| Seagate ST9320423AS 320GB           | 6         | 6      | 1.41%   |
| Seagate ST500LT012-1DG142 500GB     | 6         | 6      | 1.41%   |
| Seagate ST500LM021-1KJ152 500GB     | 6         | 6      | 1.41%   |
| Seagate ST9500325AS 500GB           | 5         | 7      | 1.17%   |
| Seagate ST1000LM035-1RK172 1TB      | 5         | 6      | 1.17%   |
| Hitachi HTS541612J9SA00 120GB       | 5         | 5      | 1.17%   |
| Toshiba MK3261GSYN 320GB            | 4         | 6      | 0.94%   |
| Seagate ST9320325AS 320GB           | 4         | 4      | 0.94%   |
| Hitachi HTS547550A9E384 500GB       | 4         | 4      | 0.94%   |
| Hitachi HTS545050B9A300 500GB       | 4         | 5      | 0.94%   |
| Hitachi HTS545032B9A300 320GB       | 4         | 6      | 0.94%   |
| Toshiba MQ01ABD075 752GB            | 3         | 3      | 0.7%    |
| Toshiba MQ01ABD032 320GB            | 3         | 4      | 0.7%    |
| Seagate ST9160412AS 160GB           | 3         | 3      | 0.7%    |
| Seagate ST750LM022 HN-M750MBB 752GB | 3         | 3      | 0.7%    |
| Seagate ST320LT020-9YG142 320GB     | 3         | 4      | 0.7%    |
| Seagate ST320LT007-9ZV142 320GB     | 3         | 3      | 0.7%    |
| SanDisk SSD PLUS 240GB              | 3         | 3      | 0.7%    |
| Micron Technology 1100 SATA 256GB   | 3         | 3      | 0.7%    |
| Kingston SA400S37240G 240GB         | 3         | 3      | 0.7%    |
| Intel SSDSC2BF180A4L 180GB          | 3         | 3      | 0.7%    |
| Hitachi HTS545050A7E380 500GB       | 3         | 3      | 0.7%    |
| Hitachi HTS545025B9SA02 250GB       | 3         | 5      | 0.7%    |
| Hitachi HTS542525K9A300 250GB       | 3         | 3      | 0.7%    |
| HGST HTS721010A9E630 1TB            | 3         | 19     | 0.7%    |
| HGST HTS541010A9E680 1TB            | 3         | 4      | 0.7%    |
| WDC WD6400BEVT-22A0RT0 640GB        | 2         | 2      | 0.47%   |
| WDC WD3200BPVT-80JJ5T0 320GB        | 2         | 2      | 0.47%   |
| WDC WD3200BPVT-75ZEST0 320GB        | 2         | 2      | 0.47%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 2         | 2      | 0.47%   |
| WDC WD10JPVX-75JC3T0 1TB            | 2         | 2      | 0.47%   |
| WDC WD10JPVX-60JC3T1 1TB            | 2         | 2      | 0.47%   |
| WDC WD10JPVX-60JC3T0 1TB            | 2         | 2      | 0.47%   |
| Toshiba MQ04ABF100 1TB              | 2         | 2      | 0.47%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 101       | 128    | 23.99%  |
| Toshiba             | 62        | 86     | 14.73%  |
| Hitachi             | 59        | 68     | 14.01%  |
| WDC                 | 52        | 55     | 12.35%  |
| Samsung Electronics | 27        | 30     | 6.41%   |
| Kingston            | 22        | 24     | 5.23%   |
| HGST                | 21        | 47     | 4.99%   |
| Intel               | 16        | 19     | 3.8%    |
| SanDisk             | 10        | 11     | 2.38%   |
| Micron Technology   | 7         | 7      | 1.66%   |
| Crucial             | 7         | 11     | 1.66%   |
| Fujitsu             | 5         | 8      | 1.19%   |
| Apple               | 4         | 4      | 0.95%   |
| A-DATA Technology   | 4         | 9      | 0.95%   |
| SK hynix            | 3         | 3      | 0.71%   |
| OCZ                 | 3         | 3      | 0.71%   |
| Corsair             | 3         | 3      | 0.71%   |
| SSSTC               | 2         | 2      | 0.48%   |
| LITEON              | 2         | 2      | 0.48%   |
| China               | 2         | 3      | 0.48%   |
| Transcend           | 1         | 1      | 0.24%   |
| SMI                 | 1         | 1      | 0.24%   |
| Patriot             | 1         | 1      | 0.24%   |
| Kston               | 1         | 1      | 0.24%   |
| KingSpec            | 1         | 1      | 0.24%   |
| IBM/Hitachi         | 1         | 1      | 0.24%   |
| Hewlett-Packard     | 1         | 2      | 0.24%   |
| Fanxiang            | 1         | 1      | 0.24%   |
| AGI                 | 1         | 1      | 0.24%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 101       | 128    | 32.69%  |
| Toshiba             | 60        | 80     | 19.42%  |
| Hitachi             | 59        | 68     | 19.09%  |
| WDC                 | 51        | 54     | 16.5%   |
| HGST                | 21        | 47     | 6.8%    |
| Samsung Electronics | 10        | 12     | 3.24%   |
| Fujitsu             | 5         | 8      | 1.62%   |
| IBM/Hitachi         | 1         | 1      | 0.32%   |
| Apple               | 1         | 1      | 0.32%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 298       | 399    | 72.68%  |
| SSD  | 107       | 129    | 26.1%   |
| NVMe | 5         | 5      | 1.22%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| SanDisk pSSD 128GB                | 2         | 2      | 33.33%  |
| Samsung Electronics HM500JJ 500GB | 1         | 1      | 16.67%  |
| Samsung Electronics HM250JI 250GB | 1         | 1      | 16.67%  |
| HPE MK000480GWUGF 480GB           | 1         | 1      | 16.67%  |
| Hitachi HTS545025B9A300 250GB     | 1         | 1      | 16.67%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 2         | 2      | 33.33%  |
| Samsung Electronics | 2         | 2      | 33.33%  |
| HPE                 | 1         | 1      | 16.67%  |
| Hitachi             | 1         | 1      | 16.67%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1922      | 2910   | 78.96%  |
| Malfunc  | 409       | 533    | 16.8%   |
| Detected | 97        | 132    | 3.99%   |
| Failed   | 6         | 6      | 0.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 1774      | 66.14%  |
| AMD                                     | 232       | 8.65%   |
| Samsung Electronics                     | 223       | 8.31%   |
| SanDisk                                 | 97        | 3.62%   |
| SK hynix                                | 43        | 1.6%    |
| Transcend                               | 31        | 1.16%   |
| Toshiba                                 | 31        | 1.16%   |
| Phison Electronics                      | 29        | 1.08%   |
| Kingston Technology Company             | 29        | 1.08%   |
| Nvidia                                  | 25        | 0.93%   |
| Micron Technology                       | 24        | 0.89%   |
| Micron/Crucial Technology               | 21        | 0.78%   |
| KIOXIA                                  | 21        | 0.78%   |
| Silicon Motion                          | 20        | 0.75%   |
| ADATA Technology                        | 15        | 0.56%   |
| Solid State Storage Technology          | 8         | 0.3%    |
| Silicon Integrated Systems [SiS]        | 8         | 0.3%    |
| Realtek Semiconductor                   | 7         | 0.26%   |
| Union Memory (Shenzhen)                 | 6         | 0.22%   |
| Marvell Technology Group                | 6         | 0.22%   |
| Lenovo                                  | 6         | 0.22%   |
| Shenzhen Longsys Electronics            | 5         | 0.19%   |
| JMicron Technology                      | 5         | 0.19%   |
| Shenzhen Unionmemory Information System | 3         | 0.11%   |
| MAXIO Technology (Hangzhou)             | 3         | 0.11%   |
| Biwin Storage Technology                | 3         | 0.11%   |
| VIA Technologies                        | 2         | 0.07%   |
| ULi Electronics                         | 1         | 0.04%   |
| Lite-On Technology                      | 1         | 0.04%   |
| INNOGRIT                                | 1         | 0.04%   |
| Broadcom / LSI                          | 1         | 0.04%   |
| Apple                                   | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 242       | 8.39%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 218       | 7.56%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 193       | 6.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 180       | 6.24%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 142       | 4.93%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 116       | 4.02%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 105       | 3.64%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 93        | 3.23%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 88        | 3.05%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 68        | 2.36%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 67        | 2.32%   |
| Unknown                                                                          | 64        | 2.22%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 55        | 1.91%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 52        | 1.8%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 45        | 1.56%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 43        | 1.49%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 42        | 1.46%   |
| Samsung NVMe SSD Controller 980                                                  | 39        | 1.35%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 34        | 1.18%   |
| Intel Comet Lake SATA AHCI Controller                                            | 34        | 1.18%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 30        | 1.04%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 29        | 1.01%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 28        | 0.97%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 27        | 0.94%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 27        | 0.94%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 26        | 0.9%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 25        | 0.87%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 24        | 0.83%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 24        | 0.83%   |
| Nvidia MCP79 AHCI Controller                                                     | 23        | 0.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 23        | 0.8%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 23        | 0.8%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 20        | 0.69%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 19        | 0.66%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 19        | 0.66%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 18        | 0.62%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 17        | 0.59%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 15        | 0.52%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 14        | 0.49%   |
| Samsung SM951 AHCI                                                               | 14        | 0.49%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1819      | 65.67%  |
| NVMe | 605       | 21.84%  |
| IDE  | 243       | 8.77%   |
| RAID | 102       | 3.68%   |
| SAS  | 1         | 0.04%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 2059      | 85.33%  |
| AMD          | 347       | 14.38%  |
| PowerPC      | 2         | 0.08%   |
| Unknown      | 2         | 0.08%   |
| ARM          | 1         | 0.04%   |
| 123456789ABC | 1         | 0.04%   |
| 11th         | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz       | 61        | 2.51%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 52        | 2.14%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 47        | 1.94%   |
| Intel CPU Version                       | 41        | 1.69%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 36        | 1.48%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 33        | 1.36%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 30        | 1.24%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 30        | 1.24%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 29        | 1.2%    |
| AMD Ryzen Embedded V1500B               | 29        | 1.2%    |
| Intel Core i5-6200U CPU @ 2.30GHz       | 28        | 1.15%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 27        | 1.11%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 26        | 1.07%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 25        | 1.03%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 23        | 0.95%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 23        | 0.95%   |
| AMD EPYC 3201 8-Core Processor          | 23        | 0.95%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 22        | 0.91%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 21        | 0.87%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 19        | 0.78%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 19        | 0.78%   |
| Intel Core 2 Duo                        | 19        | 0.78%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 18        | 0.74%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 18        | 0.74%   |
| Intel Core i3-6006U CPU @ 2.00GHz       | 18        | 0.74%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 18        | 0.74%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 18        | 0.74%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 17        | 0.7%    |
| Intel Core i5-8265U CPU @ 1.60GHz       | 17        | 0.7%    |
| Intel Core i3-4005U CPU @ 1.70GHz       | 17        | 0.7%    |
| AMD Ryzen 7 4800H with Radeon Graphics  | 17        | 0.7%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 16        | 0.66%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 15        | 0.62%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 15        | 0.62%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 15        | 0.62%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 15        | 0.62%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 15        | 0.62%   |
| Intel Core i5-2540M CPU @ 2.60GHz       | 15        | 0.62%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 14        | 0.58%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 13        | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 743       | 30.72%  |
| Intel Core i7           | 514       | 21.25%  |
| Intel Core i3           | 168       | 6.95%   |
| Other                   | 156       | 6.45%   |
| Intel Core 2 Duo        | 151       | 6.24%   |
| Intel Celeron           | 128       | 5.29%   |
| AMD Ryzen 7             | 69        | 2.85%   |
| AMD Ryzen 5             | 54        | 2.23%   |
| Intel Atom              | 50        | 2.07%   |
| Intel Pentium           | 43        | 1.78%   |
| AMD EPYC                | 33        | 1.36%   |
| AMD Ryzen Embedded      | 30        | 1.24%   |
| Intel Pentium M         | 20        | 0.83%   |
| AMD A6                  | 18        | 0.74%   |
| Intel Genuine           | 17        | 0.7%    |
| Intel Core 2            | 17        | 0.7%    |
| AMD Ryzen 7 PRO         | 15        | 0.62%   |
| Intel Xeon              | 14        | 0.58%   |
| AMD Ryzen 3             | 12        | 0.5%    |
| Intel Pentium Silver    | 11        | 0.45%   |
| AMD Ryzen 5 PRO         | 11        | 0.45%   |
| AMD E1                  | 11        | 0.45%   |
| AMD E                   | 10        | 0.41%   |
| AMD A8                  | 10        | 0.41%   |
| Intel Pentium Dual      | 8         | 0.33%   |
| AMD A4                  | 8         | 0.33%   |
| AMD A10                 | 8         | 0.33%   |
| Intel Pentium Dual-Core | 6         | 0.25%   |
| Intel Core m3           | 6         | 0.25%   |
| Intel Core i9           | 6         | 0.25%   |
| AMD E2                  | 5         | 0.21%   |
| Intel Pentium 4         | 4         | 0.17%   |
| Intel Core M            | 4         | 0.17%   |
| Intel Core Duo          | 4         | 0.17%   |
| Intel Celeron M         | 4         | 0.17%   |
| AMD GX                  | 4         | 0.17%   |
| AMD C-50                | 4         | 0.17%   |
| Intel 686-class         | 3         | 0.12%   |
| AMD Ryzen 9             | 3         | 0.12%   |
| AMD C-60                | 3         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1235      | 51.01%  |
| 4       | 610       | 25.2%   |
| Unknown | 205       | 8.47%   |
| 8       | 133       | 5.49%   |
| 6       | 67        | 2.77%   |
| 1       | 67        | 2.77%   |
| 16      | 63        | 2.6%    |
| 12      | 32        | 1.32%   |
| 10      | 6         | 0.25%   |
| 20      | 2         | 0.08%   |
| 24      | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 2319      | 95.83%  |
| Unknown | 63        | 2.6%    |
| 2       | 38        | 1.57%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1557      | 64.34%  |
| 1       | 620       | 25.62%  |
| Unknown | 243       | 10.04%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 405       | 16.76%  |
| IvyBridge       | 247       | 10.22%  |
| Haswell         | 225       | 9.31%   |
| SandyBridge     | 217       | 8.98%   |
| Skylake         | 173       | 7.16%   |
| Penryn          | 139       | 5.75%   |
| Broadwell       | 128       | 5.3%    |
| Westmere        | 101       | 4.18%   |
| Core            | 86        | 3.56%   |
| Zen             | 78        | 3.23%   |
| Unknown         | 74        | 3.06%   |
| Bonnell         | 60        | 2.48%   |
| Silvermont      | 56        | 2.32%   |
| TigerLake       | 54        | 2.23%   |
| Zen 2           | 50        | 2.07%   |
| Zen+            | 47        | 1.94%   |
| P6              | 34        | 1.41%   |
| CometLake       | 33        | 1.37%   |
| Zen 3           | 29        | 1.2%    |
| Goldmont plus   | 24        | 0.99%   |
| Excavator       | 23        | 0.95%   |
| Bobcat          | 22        | 0.91%   |
| Goldmont        | 18        | 0.74%   |
| Puma            | 17        | 0.7%    |
| Jaguar          | 16        | 0.66%   |
| IceLake         | 15        | 0.62%   |
| K10             | 9         | 0.37%   |
| Piledriver      | 8         | 0.33%   |
| NetBurst        | 7         | 0.29%   |
| K10 Llano       | 6         | 0.25%   |
| K8 Hammer       | 5         | 0.21%   |
| Nehalem         | 4         | 0.17%   |
| Steamroller     | 3         | 0.12%   |
| K8 & K10 hybrid | 3         | 0.12%   |
| Geode           | 1         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1860      | 67.44%  |
| Nvidia                           | 462       | 16.75%  |
| AMD                              | 421       | 15.26%  |
| Silicon Integrated Systems [SiS] | 6         | 0.22%   |
| Silicon Motion                   | 3         | 0.11%   |
| VIA Technologies                 | 2         | 0.07%   |
| Trident Microsystems             | 1         | 0.04%   |
| S3 Graphics                      | 1         | 0.04%   |
| Matrox Electronics Systems       | 1         | 0.04%   |
| ATI                              | 1         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 230       | 8%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 201       | 6.99%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 155       | 5.39%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 123       | 4.28%   |
| Intel HD Graphics 5500                                                                   | 110       | 3.83%   |
| Intel UHD Graphics 620                                                                   | 93        | 3.24%   |
| Intel HD Graphics 620                                                                    | 89        | 3.1%    |
| Intel Core Processor Integrated Graphics Controller                                      | 79        | 2.75%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 74        | 2.57%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 62        | 2.16%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 57        | 1.98%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 57        | 1.98%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 52        | 1.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 52        | 1.81%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 51        | 1.77%   |
| AMD Renoir                                                                               | 49        | 1.7%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 48        | 1.67%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 46        | 1.6%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 44        | 1.53%   |
| Intel HD Graphics 530                                                                    | 34        | 1.18%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 30        | 1.04%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 30        | 1.04%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 25        | 0.87%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 25        | 0.87%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 24        | 0.84%   |
| AMD Lucienne                                                                             | 23        | 0.8%    |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 22        | 0.77%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 22        | 0.77%   |
| Intel HD Graphics 630                                                                    | 22        | 0.77%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 21        | 0.73%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 20        | 0.7%    |
| Nvidia C79 [GeForce 9400M]                                                               | 19        | 0.66%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 18        | 0.63%   |
| Nvidia TU117M                                                                            | 17        | 0.59%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 16        | 0.56%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 15        | 0.52%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 15        | 0.52%   |
| Nvidia GP108M [GeForce MX150]                                                            | 14        | 0.49%   |
| Intel HD Graphics 500                                                                    | 14        | 0.49%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 13        | 0.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1279      | 52.76%  |
| 1 x AMD                  | 306       | 12.62%  |
| Intel + Nvidia           | 304       | 12.54%  |
| 2 x Intel                | 206       | 8.5%    |
| 1 x Nvidia               | 128       | 5.28%   |
| Intel + AMD              | 73        | 3.01%   |
| Other                    | 67        | 2.76%   |
| AMD + Nvidia             | 28        | 1.16%   |
| 2 x AMD                  | 12        | 0.5%    |
| 1 x SiS                  | 6         | 0.25%   |
| 2 x Nvidia               | 5         | 0.21%   |
| 1 x Silicon Motion       | 3         | 0.12%   |
| 1 x VIA                  | 2         | 0.08%   |
| 2 x Intel + 1 x Nvidia   | 1         | 0.04%   |
| 1 x Trident Microsystems | 1         | 0.04%   |
| 1 x S3 Graphics          | 1         | 0.04%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.04%   |
| AMD + Matrox             | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2138      | 87.62%  |
| Unknown     | 153       | 6.27%   |
| Proprietary | 149       | 6.11%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2132      | 86.88%  |
| 0.01-0.5   | 154       | 6.28%   |
| 1.01-2.0   | 67        | 2.73%   |
| 0.51-1.0   | 49        | 2%      |
| 3.01-4.0   | 29        | 1.18%   |
| 7.01-8.0   | 10        | 0.41%   |
| 5.01-6.0   | 8         | 0.33%   |
| 2.01-3.0   | 4         | 0.16%   |
| 8.01-16.0  | 1         | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 333       | 19.3%   |
| LG Display              | 322       | 18.67%  |
| Chimei Innolux          | 208       | 12.06%  |
| BOE                     | 189       | 10.96%  |
| Samsung Electronics     | 145       | 8.41%   |
| Lenovo                  | 100       | 5.8%    |
| Apple                   | 55        | 3.19%   |
| Sharp                   | 37        | 2.14%   |
| Chi Mei Optoelectronics | 35        | 2.03%   |
| Dell                    | 25        | 1.45%   |
| InfoVision              | 23        | 1.33%   |
| Hewlett-Packard         | 18        | 1.04%   |
| Goldstar                | 17        | 0.99%   |
| PANDA                   | 16        | 0.93%   |
| AOC                     | 16        | 0.93%   |
| LG Philips              | 14        | 0.81%   |
| BenQ                    | 14        | 0.81%   |
| Philips                 | 13        | 0.75%   |
| Acer                    | 11        | 0.64%   |
| Ancor Communications    | 10        | 0.58%   |
| LGD                     | 9         | 0.52%   |
| HannStar                | 9         | 0.52%   |
| CSO                     | 8         | 0.46%   |
| CPT                     | 7         | 0.41%   |
| Panasonic               | 6         | 0.35%   |
| Toshiba                 | 5         | 0.29%   |
| JDI                     | 5         | 0.29%   |
| Iiyama                  | 5         | 0.29%   |
| ViewSonic               | 4         | 0.23%   |
| Sceptre Tech            | 4         | 0.23%   |
| IBM                     | 4         | 0.23%   |
| Fujitsu Siemens         | 4         | 0.23%   |
| Unknown                 | 4         | 0.23%   |
| Lenovo Group Limited    | 3         | 0.17%   |
| Eizo                    | 3         | 0.17%   |
| ASUSTek Computer        | 3         | 0.17%   |
| Vizio                   | 2         | 0.12%   |
| Unknown                 | 2         | 0.12%   |
| Sony                    | 2         | 0.12%   |
| Nvidia                  | 2         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 21        | 1.21%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 15        | 0.86%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch         | 13        | 0.75%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 12        | 0.69%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch                  | 10        | 0.58%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch                  | 10        | 0.58%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch          | 10        | 0.58%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch                  | 9         | 0.52%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch            | 9         | 0.52%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch            | 9         | 0.52%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch           | 9         | 0.52%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch            | 9         | 0.52%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch     | 8         | 0.46%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch     | 8         | 0.46%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch             | 8         | 0.46%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch              | 8         | 0.46%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch                 | 8         | 0.46%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch                  | 8         | 0.46%   |
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch                  | 8         | 0.46%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch         | 8         | 0.46%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch            | 8         | 0.46%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch     | 7         | 0.4%    |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch             | 7         | 0.4%    |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch                  | 7         | 0.4%    |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch                | 7         | 0.4%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch          | 7         | 0.4%    |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 310x170mm 13.9-inch         | 7         | 0.4%    |
| Chimei Innolux LCD Monitor CMN1482 1600x900 310x170mm 13.9-inch          | 7         | 0.4%    |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                    | 7         | 0.4%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch           | 7         | 0.4%    |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch           | 7         | 0.4%    |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch             | 6         | 0.35%   |
| LG Display LCD Monitor LGD0456 1366x768 340x190mm 15.3-inch              | 6         | 0.35%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch              | 6         | 0.35%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch                  | 6         | 0.35%   |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch                  | 6         | 0.35%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 310x170mm 13.9-inch         | 6         | 0.35%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 280x160mm 12.7-inch         | 6         | 0.35%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 6         | 0.35%   |
| BOE LCD Monitor BOE0742 1920x1080 310x170mm 13.9-inch                    | 6         | 0.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 599       | 35.61%  |
| 1366x768 (WXGA)    | 567       | 33.71%  |
| 1280x800 (WXGA)    | 108       | 6.42%   |
| 1600x900 (HD+)     | 105       | 6.24%   |
| 3840x2160 (4K)     | 49        | 2.91%   |
| 2560x1440 (QHD)    | 49        | 2.91%   |
| 1440x900 (WXGA+)   | 30        | 1.78%   |
| 1024x600           | 29        | 1.72%   |
| 1920x1200 (WUXGA)  | 21        | 1.25%   |
| 1680x1050 (WSXGA+) | 13        | 0.77%   |
| 1280x1024 (SXGA)   | 12        | 0.71%   |
| 3200x1800 (QHD+)   | 10        | 0.59%   |
| 2880x1800          | 8         | 0.48%   |
| 2560x1600          | 8         | 0.48%   |
| 2560x1080          | 8         | 0.48%   |
| 2256x1504          | 8         | 0.48%   |
| 1024x768 (XGA)     | 7         | 0.42%   |
| 2880x1620          | 6         | 0.36%   |
| Unknown            | 6         | 0.36%   |
| 3440x1440          | 5         | 0.3%    |
| 1920x540           | 4         | 0.24%   |
| 3000x2000          | 3         | 0.18%   |
| 2160x1440          | 3         | 0.18%   |
| 3840x2400          | 2         | 0.12%   |
| 1400x1050          | 2         | 0.12%   |
| 1360x768           | 2         | 0.12%   |
| 9600x2160          | 1         | 0.06%   |
| 720x1280           | 1         | 0.06%   |
| 7040x1440          | 1         | 0.06%   |
| 5760x2160          | 1         | 0.06%   |
| 5760x1080          | 1         | 0.06%   |
| 4480x1080          | 1         | 0.06%   |
| 3840x1600          | 1         | 0.06%   |
| 3840x1200          | 1         | 0.06%   |
| 3840x1080          | 1         | 0.06%   |
| 3520x1080          | 1         | 0.06%   |
| 3200x2000          | 1         | 0.06%   |
| 2520x1680          | 1         | 0.06%   |
| 2240x1400          | 1         | 0.06%   |
| 1440x960           | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 582       | 33.86%  |
| 13      | 528       | 30.72%  |
| 12      | 157       | 9.13%   |
| 17      | 65        | 3.78%   |
| 14      | 64        | 3.72%   |
| 11      | 54        | 3.14%   |
| 24      | 45        | 2.62%   |
| 27      | 37        | 2.15%   |
| Unknown | 37        | 2.15%   |
| 10      | 27        | 1.57%   |
| 23      | 25        | 1.45%   |
| 21      | 14        | 0.81%   |
| 19      | 14        | 0.81%   |
| 34      | 9         | 0.52%   |
| 31      | 9         | 0.52%   |
| 18      | 8         | 0.47%   |
| 9       | 6         | 0.35%   |
| 22      | 4         | 0.23%   |
| 64      | 3         | 0.17%   |
| 29      | 3         | 0.17%   |
| 26      | 3         | 0.17%   |
| 20      | 3         | 0.17%   |
| 16      | 3         | 0.17%   |
| 42      | 2         | 0.12%   |
| 40      | 2         | 0.12%   |
| 39      | 2         | 0.12%   |
| 54      | 1         | 0.06%   |
| 49      | 1         | 0.06%   |
| 48      | 1         | 0.06%   |
| 46      | 1         | 0.06%   |
| 43      | 1         | 0.06%   |
| 37      | 1         | 0.06%   |
| 35      | 1         | 0.06%   |
| 33      | 1         | 0.06%   |
| 32      | 1         | 0.06%   |
| 28      | 1         | 0.06%   |
| 8       | 1         | 0.06%   |
| 6       | 1         | 0.06%   |
| 5       | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 974       | 56.83%  |
| 201-300     | 446       | 26.02%  |
| 501-600     | 98        | 5.72%   |
| 351-400     | 69        | 4.03%   |
| 401-500     | 37        | 2.16%   |
| Unknown     | 37        | 2.16%   |
| 601-700     | 21        | 1.23%   |
| 701-800     | 11        | 0.64%   |
| 1001-1500   | 8         | 0.47%   |
| 801-900     | 6         | 0.35%   |
| 101-200     | 4         | 0.23%   |
| 901-1000    | 2         | 0.12%   |
| 1-100       | 1         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1299      | 81.44%  |
| 16/10   | 189       | 11.85%  |
| Unknown | 34        | 2.13%   |
| 3/2     | 28        | 1.76%   |
| 4/3     | 14        | 0.88%   |
| 21/9    | 14        | 0.88%   |
| 5/4     | 12        | 0.75%   |
| 6/5     | 1         | 0.06%   |
| 3.18    | 1         | 0.06%   |
| 11/10   | 1         | 0.06%   |
| 1.96    | 1         | 0.06%   |
| 0.46    | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 499       | 28.99%  |
| 91-100         | 457       | 26.55%  |
| 61-70          | 156       | 9.06%   |
| 101-110        | 131       | 7.61%   |
| 71-80          | 85        | 4.94%   |
| 201-250        | 78        | 4.53%   |
| 121-130        | 56        | 3.25%   |
| 51-60          | 53        | 3.08%   |
| 301-350        | 42        | 2.44%   |
| Unknown        | 37        | 2.15%   |
| 41-50          | 31        | 1.8%    |
| 351-500        | 22        | 1.28%   |
| 151-200        | 17        | 0.99%   |
| 141-150        | 13        | 0.76%   |
| 251-300        | 12        | 0.7%    |
| 501-1000       | 10        | 0.58%   |
| 131-140        | 6         | 0.35%   |
| 111-120        | 6         | 0.35%   |
| More than 1000 | 5         | 0.29%   |
| 1-40           | 5         | 0.29%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 716       | 42.17%  |
| 101-120       | 529       | 31.15%  |
| 51-100        | 213       | 12.54%  |
| 161-240       | 154       | 9.07%   |
| More than 240 | 46        | 2.71%   |
| Unknown       | 37        | 2.18%   |
| 1-50          | 3         | 0.18%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1690      | 68.15%  |
| 0     | 608       | 24.52%  |
| 2     | 174       | 7.02%   |
| 3     | 7         | 0.28%   |
| 4     | 1         | 0.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1606      | 42.46%  |
| Realtek Semiconductor             | 932       | 24.64%  |
| Qualcomm Atheros                  | 473       | 12.51%  |
| Broadcom                          | 268       | 7.09%   |
| AMD                               | 63        | 1.67%   |
| Marvell Technology Group          | 56        | 1.48%   |
| Ralink Technology                 | 33        | 0.87%   |
| Ericsson Business Mobile Networks | 33        | 0.87%   |
| TP-Link                           | 30        | 0.79%   |
| Sierra Wireless                   | 27        | 0.71%   |
| Edimax Technology                 | 24        | 0.63%   |
| Nvidia                            | 23        | 0.61%   |
| Ralink                            | 20        | 0.53%   |
| Samsung Electronics               | 18        | 0.48%   |
| MediaTek                          | 16        | 0.42%   |
| Xiaomi                            | 14        | 0.37%   |
| Dell                              | 13        | 0.34%   |
| Google                            | 12        | 0.32%   |
| JMicron Technology                | 11        | 0.29%   |
| Huawei Technologies               | 10        | 0.26%   |
| Hewlett-Packard                   | 10        | 0.26%   |
| Silicon Integrated Systems [SiS]  | 8         | 0.21%   |
| D-Link System                     | 8         | 0.21%   |
| NetGear                           | 7         | 0.19%   |
| D-Link                            | 6         | 0.16%   |
| Qualcomm Atheros Communications   | 5         | 0.13%   |
| Qualcomm                          | 5         | 0.13%   |
| ASUSTek Computer                  | 5         | 0.13%   |
| Apple                             | 4         | 0.11%   |
| Fibocom                           | 3         | 0.08%   |
| VIA Technologies                  | 2         | 0.05%   |
| Realtek                           | 2         | 0.05%   |
| OPPO Electronics                  | 2         | 0.05%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.05%   |
| Novatel Wireless                  | 2         | 0.05%   |
| Lenovo                            | 2         | 0.05%   |
| BUFFALO                           | 2         | 0.05%   |
| Atheros                           | 2         | 0.05%   |
| Arduino SA                        | 2         | 0.05%   |
| Van Ooijen Technische Informatica | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 606       | 12.55%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 209       | 4.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 198       | 4.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 151       | 3.13%   |
| Intel Wireless 8265 / 8275                                              | 140       | 2.9%    |
| Intel Wireless 7260                                                     | 116       | 2.4%    |
| Intel Wireless 8260                                                     | 111       | 2.3%    |
| Intel Wireless 7265                                                     | 111       | 2.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 88        | 1.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 77        | 1.59%   |
| Intel Wi-Fi 6 AX200                                                     | 76        | 1.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 75        | 1.55%   |
| Intel Ethernet Connection I219-LM                                       | 67        | 1.39%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0               | 62        | 1.28%   |
| Intel I210 Gigabit Network Connection                                   | 57        | 1.18%   |
| Intel Ethernet Connection (4) I219-LM                                   | 54        | 1.12%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 53        | 1.1%    |
| Intel Ethernet Connection (3) I218-LM                                   | 51        | 1.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 50        | 1.04%   |
| Intel 82577LM Gigabit Network Connection                                | 49        | 1.01%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 48        | 0.99%   |
| Intel Ethernet Connection I218-LM                                       | 47        | 0.97%   |
| Intel Wi-Fi 6 AX201                                                     | 45        | 0.93%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 43        | 0.89%   |
| Intel Ethernet Connection I217-LM                                       | 40        | 0.83%   |
| Intel Wireless 3165                                                     | 39        | 0.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 38        | 0.79%   |
| Intel 82567LM Gigabit Network Connection                                | 38        | 0.79%   |
| Intel Centrino Ultimate-N 6300                                          | 37        | 0.77%   |
| Intel Wireless-AC 9260                                                  | 36        | 0.75%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 36        | 0.75%   |
| Intel I211 Gigabit Network Connection                                   | 35        | 0.72%   |
| Intel Centrino Advanced-N 6200                                          | 33        | 0.68%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 33        | 0.68%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 33        | 0.68%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 32        | 0.66%   |
| Intel Ethernet Connection (4) I219-V                                    | 31        | 0.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 30        | 0.62%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 29        | 0.6%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 28        | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1406      | 56.88%  |
| Qualcomm Atheros                | 415       | 16.79%  |
| Realtek Semiconductor           | 263       | 10.64%  |
| Broadcom                        | 202       | 8.17%   |
| Ralink Technology               | 33        | 1.33%   |
| TP-Link                         | 30        | 1.21%   |
| Edimax Technology               | 24        | 0.97%   |
| Sierra Wireless                 | 21        | 0.85%   |
| Ralink                          | 20        | 0.81%   |
| MediaTek                        | 14        | 0.57%   |
| NetGear                         | 7         | 0.28%   |
| D-Link System                   | 7         | 0.28%   |
| D-Link                          | 6         | 0.24%   |
| Qualcomm Atheros Communications | 5         | 0.2%    |
| Dell                            | 5         | 0.2%    |
| ASUSTek Computer                | 5         | 0.2%    |
| BUFFALO                         | 2         | 0.08%   |
| Atheros                         | 2         | 0.08%   |
| Sagem                           | 1         | 0.04%   |
| Micro Star International        | 1         | 0.04%   |
| Mercucys                        | 1         | 0.04%   |
| IMC Networks                    | 1         | 0.04%   |
| AboCom Systems                  | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 151       | 6.03%   |
| Intel Wireless 8265 / 8275                                              | 140       | 5.59%   |
| Intel Wireless 7260                                                     | 116       | 4.63%   |
| Intel Wireless 8260                                                     | 111       | 4.43%   |
| Intel Wireless 7265                                                     | 111       | 4.43%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 88        | 3.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 77        | 3.08%   |
| Intel Wi-Fi 6 AX200                                                     | 76        | 3.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 75        | 3%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 53        | 2.12%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 50        | 2%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 48        | 1.92%   |
| Intel Wi-Fi 6 AX201                                                     | 45        | 1.8%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 43        | 1.72%   |
| Intel Wireless 3165                                                     | 39        | 1.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 38        | 1.52%   |
| Intel Wireless-AC 9260                                                  | 36        | 1.44%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 36        | 1.44%   |
| Intel Centrino Ultimate-N 6300                                          | 36        | 1.44%   |
| Intel Centrino Advanced-N 6200                                          | 33        | 1.32%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 33        | 1.32%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 33        | 1.32%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 32        | 1.28%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 30        | 1.2%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 29        | 1.16%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 28        | 1.12%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 26        | 1.04%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 25        | 1%      |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 25        | 1%      |
| Intel Wireless 3160                                                     | 24        | 0.96%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 23        | 0.92%   |
| Intel WiFi Link 5100                                                    | 23        | 0.92%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 23        | 0.92%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 23        | 0.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 22        | 0.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 22        | 0.88%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 22        | 0.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 22        | 0.88%   |
| Intel Centrino Advanced-N 6235                                          | 22        | 0.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 21        | 0.84%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 904       | 41.07%  |
| Realtek Semiconductor                  | 824       | 37.44%  |
| Qualcomm Atheros                       | 127       | 5.77%   |
| Broadcom                               | 112       | 5.09%   |
| AMD                                    | 62        | 2.82%   |
| Marvell Technology Group               | 56        | 2.54%   |
| Nvidia                                 | 23        | 1.04%   |
| Samsung Electronics                    | 18        | 0.82%   |
| Xiaomi                                 | 14        | 0.64%   |
| JMicron Technology                     | 11        | 0.5%    |
| Google                                 | 9         | 0.41%   |
| Silicon Integrated Systems [SiS]       | 7         | 0.32%   |
| Qualcomm                               | 5         | 0.23%   |
| Huawei Technologies                    | 4         | 0.18%   |
| Apple                                  | 3         | 0.14%   |
| VIA Technologies                       | 2         | 0.09%   |
| Realtek                                | 2         | 0.09%   |
| OPPO Electronics                       | 2         | 0.09%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.09%   |
| Novatel Wireless                       | 2         | 0.09%   |
| MediaTek                               | 2         | 0.09%   |
| Lenovo                                 | 2         | 0.09%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.05%   |
| National Semiconductor                 | 1         | 0.05%   |
| Microsoft                              | 1         | 0.05%   |
| ICS Advent                             | 1         | 0.05%   |
| HMD Global                             | 1         | 0.05%   |
| Attansic                               | 1         | 0.05%   |
| Aquantia                               | 1         | 0.05%   |
| 3Com                                   | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 606       | 27.32%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 209       | 9.42%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 198       | 8.93%   |
| Intel Ethernet Connection I219-LM                                 | 67        | 3.02%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0         | 62        | 2.8%    |
| Intel I210 Gigabit Network Connection                             | 57        | 2.57%   |
| Intel Ethernet Connection (4) I219-LM                             | 54        | 2.43%   |
| Intel Ethernet Connection (3) I218-LM                             | 51        | 2.3%    |
| Intel 82577LM Gigabit Network Connection                          | 49        | 2.21%   |
| Intel Ethernet Connection I218-LM                                 | 47        | 2.12%   |
| Intel Ethernet Connection I217-LM                                 | 40        | 1.8%    |
| Intel 82567LM Gigabit Network Connection                          | 38        | 1.71%   |
| Intel I211 Gigabit Network Connection                             | 35        | 1.58%   |
| Intel Ethernet Connection (4) I219-V                              | 31        | 1.4%    |
| Intel Ethernet Connection (2) I219-LM                             | 24        | 1.08%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 22        | 0.99%   |
| Nvidia MCP79 Ethernet                                             | 22        | 0.99%   |
| Intel 82566MM Gigabit Network Connection                          | 21        | 0.95%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 18        | 0.81%   |
| Intel Ethernet Connection I219-V                                  | 17        | 0.77%   |
| Intel Ethernet Connection (6) I219-V                              | 16        | 0.72%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 16        | 0.72%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 15        | 0.68%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 14        | 0.63%   |
| Intel Ethernet Connection (6) I219-LM                             | 14        | 0.63%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 12        | 0.54%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 12        | 0.54%   |
| Intel Ethernet Connection (7) I219-LM                             | 12        | 0.54%   |
| Intel 82574L Gigabit Network Connection                           | 12        | 0.54%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 11        | 0.5%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 11        | 0.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 10        | 0.45%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 10        | 0.45%   |
| Intel Ethernet Connection (3) I218-V                              | 10        | 0.45%   |
| Intel 82573L Gigabit Ethernet Controller                          | 10        | 0.45%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 9         | 0.41%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 9         | 0.41%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 9         | 0.41%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 9         | 0.41%   |
| Intel Ethernet Connection (10) I219-V                             | 9         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2245      | 50.64%  |
| Ethernet | 2078      | 46.88%  |
| Modem    | 60        | 1.35%   |
| Unknown  | 50        | 1.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1556      | 50.1%   |
| Ethernet | 1526      | 49.13%  |
| Modem    | 13        | 0.42%   |
| Unknown  | 11        | 0.35%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1856      | 76.82%  |
| 1     | 400       | 16.56%  |
| 6     | 57        | 2.36%   |
| 3     | 52        | 2.15%   |
| 5     | 29        | 1.2%    |
| 0     | 14        | 0.58%   |
| 8     | 3         | 0.12%   |
| 4     | 3         | 0.12%   |
| 10    | 1         | 0.04%   |
| 7     | 1         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2257      | 92.16%  |
| Yes  | 192       | 7.84%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 861       | 53.95%  |
| Broadcom                        | 166       | 10.4%   |
| Qualcomm Atheros Communications | 110       | 6.89%   |
| Realtek Semiconductor           | 91        | 5.7%    |
| Apple                           | 89        | 5.58%   |
| IMC Networks                    | 54        | 3.38%   |
| Foxconn / Hon Hai               | 52        | 3.26%   |
| Lite-On Technology              | 44        | 2.76%   |
| Dell                            | 32        | 2.01%   |
| Hewlett-Packard                 | 25        | 1.57%   |
| Alps Electric                   | 18        | 1.13%   |
| Cambridge Silicon Radio         | 15        | 0.94%   |
| ASUSTek Computer                | 14        | 0.88%   |
| Ralink                          | 9         | 0.56%   |
| Skylight Digital                | 6         | 0.38%   |
| Toshiba                         | 2         | 0.13%   |
| Creative Technology             | 2         | 0.13%   |
| TP-Link                         | 1         | 0.06%   |
| Taiyo Yuden                     | 1         | 0.06%   |
| Ralink Technology               | 1         | 0.06%   |
| Opticis                         | 1         | 0.06%   |
| Esel International              | 1         | 0.06%   |
| Askey Computer                  | 1         | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 441       | 27.58%  |
| Intel AX201 Bluetooth                                       | 113       | 7.07%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 103       | 6.44%   |
| Intel AX200 Bluetooth                                       | 73        | 4.57%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 58        | 3.63%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 51        | 3.19%   |
| Apple Bluetooth Host Controller                             | 49        | 3.06%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 33        | 2.06%   |
| Intel Wireless-AC 3168 Bluetooth                            | 30        | 1.88%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 29        | 1.81%   |
| Realtek Bluetooth Adapter                                   | 26        | 1.63%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 23        | 1.44%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 22        | 1.38%   |
| Intel AX210 Bluetooth                                       | 21        | 1.31%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 17        | 1.06%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 17        | 1.06%   |
| Realtek  Bluetooth 4.2 Adapter                              | 15        | 0.94%   |
| Lite-On Atheros AR3012 Bluetooth                            | 15        | 0.94%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 15        | 0.94%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 15        | 0.94%   |
| Apple Broadcom Built-in Bluetooth                           | 14        | 0.88%   |
| Dell DW375 Bluetooth Module                                 | 13        | 0.81%   |
| Apple Built-in iSight (no firmware loaded)                  | 13        | 0.81%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 12        | 0.75%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 12        | 0.75%   |
| Alps Electric UGTZ4 Bluetooth                               | 12        | 0.75%   |
| Realtek Bluetooth 4.0 Adapter                               | 11        | 0.69%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 11        | 0.69%   |
| IMC Networks Realtek Bluetooth Adapter                      | 11        | 0.69%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 11        | 0.69%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 11        | 0.69%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 10        | 0.63%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 10        | 0.63%   |
| Realtek RTL8723B Bluetooth                                  | 9         | 0.56%   |
| Ralink RT3290 Bluetooth                                     | 9         | 0.56%   |
| HP Broadcom 2070 Bluetooth Combo                            | 9         | 0.56%   |
| Realtek RTL8821A Bluetooth                                  | 8         | 0.5%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 8         | 0.5%    |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 8         | 0.5%    |
| IMC Networks Bluetooth module                               | 8         | 0.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1995      | 74.94%  |
| AMD                                          | 391       | 14.69%  |
| Nvidia                                       | 178       | 6.69%   |
| Lenovo                                       | 15        | 0.56%   |
| Silicon Integrated Systems [SiS]             | 8         | 0.3%    |
| Texas Instruments                            | 7         | 0.26%   |
| Realtek Semiconductor                        | 7         | 0.26%   |
| GN Netcom                                    | 7         | 0.26%   |
| Logitech                                     | 6         | 0.23%   |
| C-Media Electronics                          | 6         | 0.23%   |
| SteelSeries ApS                              | 3         | 0.11%   |
| Plantronics                                  | 3         | 0.11%   |
| Kingston Technology                          | 3         | 0.11%   |
| Creative Technology                          | 3         | 0.11%   |
| ASUSTek Computer                             | 3         | 0.11%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.08%   |
| VIA Technologies                             | 2         | 0.08%   |
| JMTek                                        | 2         | 0.08%   |
| Generalplus Technology                       | 2         | 0.08%   |
| ESS Technology                               | 2         | 0.08%   |
| CMX Systems                                  | 2         | 0.08%   |
| XMOS                                         | 1         | 0.04%   |
| ULi Electronics                              | 1         | 0.04%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.04%   |
| Sony                                         | 1         | 0.04%   |
| RODE Microphones                             | 1         | 0.04%   |
| Phison Electronics                           | 1         | 0.04%   |
| Microsoft                                    | 1         | 0.04%   |
| M-Audio                                      | 1         | 0.04%   |
| Hewlett-Packard                              | 1         | 0.04%   |
| Elitegroup Computer Systems (ECS)            | 1         | 0.04%   |
| DSEA A/S                                     | 1         | 0.04%   |
| Conexant Systems                             | 1         | 0.04%   |
| Cambridge Silicon Radio                      | 1         | 0.04%   |
| Cambridge Audio                              | 1         | 0.04%   |
| Blue Microphones                             | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 321       | 9.89%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 263       | 8.1%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 192       | 5.91%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 190       | 5.85%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 153       | 4.71%   |
| Intel 8 Series HD Audio Controller                                                                | 153       | 4.71%   |
| Intel Broadwell-U Audio Controller                                                                | 128       | 3.94%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 122       | 3.76%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 107       | 3.3%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 101       | 3.11%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 87        | 2.68%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 86        | 2.65%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 74        | 2.28%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 67        | 2.06%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 66        | 2.03%   |
| Intel Cannon Lake PCH cAVS                                                                        | 62        | 1.91%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 58        | 1.79%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 57        | 1.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 55        | 1.69%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 55        | 1.69%   |
| AMD FCH Azalia Controller                                                                         | 55        | 1.69%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 38        | 1.17%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 38        | 1.17%   |
| AMD Kabini HDMI/DP Audio                                                                          | 37        | 1.14%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 35        | 1.08%   |
| Intel Comet Lake PCH cAVS                                                                         | 32        | 0.99%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 32        | 0.99%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 28        | 0.86%   |
| Intel CM238 HD Audio Controller                                                                   | 27        | 0.83%   |
| Nvidia MCP79 High Definition Audio                                                                | 24        | 0.74%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 24        | 0.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 24        | 0.74%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 21        | 0.65%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 18        | 0.55%   |
| AMD Wrestler HDMI Audio                                                                           | 18        | 0.55%   |
| AMD High Definition Audio Controller                                                              | 18        | 0.55%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 15        | 0.46%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 15        | 0.46%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 13        | 0.4%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 13        | 0.4%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 695       | 26.83%  |
| SK hynix            | 531       | 20.5%   |
| Micron Technology   | 258       | 9.96%   |
| Kingston            | 228       | 8.8%    |
| Unknown             | 200       | 7.72%   |
| Crucial             | 106       | 4.09%   |
| Transcend           | 77        | 2.97%   |
| Unknown             | 71        | 2.74%   |
| Elpida              | 66        | 2.55%   |
| Ramaxel Technology  | 60        | 2.32%   |
| A-DATA Technology   | 40        | 1.54%   |
| Nanya Technology    | 38        | 1.47%   |
| Corsair             | 32        | 1.24%   |
| Smart               | 27        | 1.04%   |
| G.Skill             | 19        | 0.73%   |
| Team                | 12        | 0.46%   |
| Unknown (ABCD)      | 10        | 0.39%   |
| 48spaces            | 9         | 0.35%   |
| PNY                 | 8         | 0.31%   |
| Teikon              | 7         | 0.27%   |
| GOODRAM             | 7         | 0.27%   |
| Apacer              | 7         | 0.27%   |
| Smart Brazil        | 5         | 0.19%   |
| Patriot             | 5         | 0.19%   |
| Neo Forza           | 5         | 0.19%   |
| Avant               | 5         | 0.19%   |
| ASint Technology    | 5         | 0.19%   |
| High Bridge         | 4         | 0.15%   |
| Goldkey             | 3         | 0.12%   |
| V-GeN               | 2         | 0.08%   |
| Toshiba             | 2         | 0.08%   |
| Super Talent        | 2         | 0.08%   |
| Silicon Power       | 2         | 0.08%   |
| SHARETRONIC         | 2         | 0.08%   |
| Sesame              | 2         | 0.08%   |
| PUSKILL             | 2         | 0.08%   |
| Magnum Tech         | 2         | 0.08%   |
| KomputerBay         | 2         | 0.08%   |
| GSkill              | 2         | 0.08%   |
| V-Color             | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Unknown                                                 | 71        | 2.57%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s   | 46        | 1.66%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 42        | 1.52%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s  | 39        | 1.41%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 38        | 1.37%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s   | 37        | 1.34%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s     | 34        | 1.23%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s  | 33        | 1.19%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s              | 32        | 1.16%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s   | 31        | 1.12%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s   | 29        | 1.05%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s   | 26        | 0.94%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s   | 23        | 0.83%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s   | 23        | 0.83%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s   | 23        | 0.83%   |
| Samsung RAM M471B5273DH0-CK0 8GB SODIMM DDR3 1600MT/s   | 20        | 0.72%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s   | 20        | 0.72%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s   | 18        | 0.65%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 17        | 0.61%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s   | 17        | 0.61%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM 1333MT/s        | 16        | 0.58%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s   | 16        | 0.58%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s   | 15        | 0.54%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s   | 14        | 0.51%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s              | 13        | 0.47%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s  | 13        | 0.47%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s  | 13        | 0.47%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s   | 13        | 0.47%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s | 13        | 0.47%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s  | 12        | 0.43%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s   | 12        | 0.43%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s   | 12        | 0.43%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s   | 12        | 0.43%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s   | 12        | 0.43%   |
| Unknown RAM Module 2GB SODIMM DDR2                      | 11        | 0.4%    |
| Transcend RAM TS1GLH64V6B3 8GB SODIMM DDR4 1333MT/s     | 11        | 0.4%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s  | 11        | 0.4%    |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s  | 11        | 0.4%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s  | 11        | 0.4%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s   | 11        | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 1054      | 48.3%   |
| DDR4    | 757       | 34.69%  |
| DDR2    | 170       | 7.79%   |
| LPDDR3  | 63        | 2.89%   |
| LPDDR4  | 39        | 1.79%   |
| Unknown | 29        | 1.33%   |
| DDR     | 26        | 1.19%   |
| SDRAM   | 18        | 0.82%   |
| DRAM    | 9         | 0.41%   |
| DDR5    | 8         | 0.37%   |
| LPDDR5  | 6         | 0.27%   |
| RAM     | 2         | 0.09%   |
| SRAM    | 1         | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 2018      | 91.98%  |
| Row Of Chips | 102       | 4.65%   |
| Chip         | 47        | 2.14%   |
| Unknown      | 17        | 0.77%   |
| DIMM         | 10        | 0.46%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 816       | 33.83%  |
| 8192  | 807       | 33.46%  |
| 2048  | 420       | 17.41%  |
| 16384 | 226       | 9.37%   |
| 1024  | 86        | 3.57%   |
| 32768 | 32        | 1.33%   |
| 512   | 16        | 0.66%   |
| 256   | 6         | 0.25%   |
| 128   | 2         | 0.08%   |
| 2560  | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 654       | 27.74%  |
| 2667    | 308       | 13.06%  |
| 1333    | 220       | 9.33%   |
| 2400    | 201       | 8.52%   |
| 3200    | 190       | 8.06%   |
| 2133    | 154       | 6.53%   |
| 1334    | 137       | 5.81%   |
| 667     | 115       | 4.88%   |
| Unknown | 72        | 3.05%   |
| 1067    | 71        | 3.01%   |
| 1867    | 64        | 2.71%   |
| 800     | 56        | 2.37%   |
| 533     | 23        | 0.98%   |
| 4267    | 20        | 0.85%   |
| 1066    | 17        | 0.72%   |
| 975     | 11        | 0.47%   |
| 4800    | 8         | 0.34%   |
| 4266    | 5         | 0.21%   |
| 2048    | 5         | 0.21%   |
| 1866    | 5         | 0.21%   |
| 6400    | 4         | 0.17%   |
| 1200    | 4         | 0.17%   |
| 333     | 3         | 0.13%   |
| 3733    | 2         | 0.08%   |
| 2933    | 2         | 0.08%   |
| 166     | 2         | 0.08%   |
| 1596    | 1         | 0.04%   |
| 666     | 1         | 0.04%   |
| 266     | 1         | 0.04%   |
| 200     | 1         | 0.04%   |
| 100     | 1         | 0.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| ELGIN               | 2         | 40%     |
| Samsung Electronics | 1         | 20%     |
| Prolific Technology | 1         | 20%     |
| Hewlett-Packard     | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| ELGIN L42PRO                       | 2         | 40%     |
| Samsung ML-1610 Mono Laser Printer | 1         | 20%     |
| Prolific PL2305 Parallel Port      | 1         | 20%     |
| HP LaserJet 1020                   | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 120 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 503       | 29.96%  |
| Bison Electronics                      | 187       | 11.14%  |
| IMC Networks                           | 164       | 9.77%   |
| Realtek Semiconductor                  | 144       | 8.58%   |
| Microdia                               | 143       | 8.52%   |
| Sunplus Innovation Technology          | 95        | 5.66%   |
| Suyin                                  | 61        | 3.63%   |
| Lite-On Technology                     | 59        | 3.51%   |
| Quanta                                 | 39        | 2.32%   |
| Cheng Uei Precision Industry (Foxlink) | 39        | 2.32%   |
| Syntek                                 | 35        | 2.08%   |
| Apple                                  | 27        | 1.61%   |
| Silicon Motion                         | 26        | 1.55%   |
| Lenovo                                 | 24        | 1.43%   |
| Luxvisions Innotech Limited            | 20        | 1.19%   |
| Alcor Micro                            | 20        | 1.19%   |
| ALi                                    | 14        | 0.83%   |
| Z-Star Microelectronics                | 11        | 0.66%   |
| Ricoh                                  | 11        | 0.66%   |
| Logitech                               | 11        | 0.66%   |
| Importek                               | 8         | 0.48%   |
| Supreme Electronics                    | 5         | 0.3%    |
| Shenzhen Kingcome Optoelectronic       | 3         | 0.18%   |
| Primax Electronics                     | 3         | 0.18%   |
| Intel                                  | 3         | 0.18%   |
| DigiTech                               | 3         | 0.18%   |
| USB Camera                             | 2         | 0.12%   |
| Unknown                                | 2         | 0.12%   |
| Tripath Technology                     | 2         | 0.12%   |
| Pixart Imaging                         | 2         | 0.12%   |
| OmniVision Technologies                | 2         | 0.12%   |
| Jiangxi Shinetech Optical              | 2         | 0.12%   |
| Y Media                                | 1         | 0.06%   |
| SIMPLO Technology                      | 1         | 0.06%   |
| Nanchang BYD Electronics               | 1         | 0.06%   |
| Goodong Industry                       | 1         | 0.06%   |
| Genesys Logic                          | 1         | 0.06%   |
| Foxconn / Hon Hai                      | 1         | 0.06%   |
| Denron                                 | 1         | 0.06%   |
| Cubeternet                             | 1         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 152       | 8.96%   |
| Bison Integrated Camera                       | 87        | 5.13%   |
| IMC Networks Integrated Camera                | 53        | 3.13%   |
| Microdia Integrated_Webcam_HD                 | 42        | 2.48%   |
| Realtek Integrated_Webcam_HD                  | 41        | 2.42%   |
| Lite-On Integrated Camera                     | 39        | 2.3%    |
| Chicony HD WebCam                             | 37        | 2.18%   |
| Chicony Lenovo Integrated Camera (0.3MP)      | 35        | 2.06%   |
| Microdia Integrated Webcam                    | 34        | 2%      |
| Sunplus Integrated_Webcam_HD                  | 27        | 1.59%   |
| Realtek USB 2.0 PC Camera                     | 23        | 1.36%   |
| Bison Lenovo EasyCamera                       | 23        | 1.36%   |
| Chicony Integrated Camera (1280x720@30)       | 22        | 1.3%    |
| IMC Networks Realtek PC Camera                | 19        | 1.12%   |
| IMC Networks EasyCamera                       | 19        | 1.12%   |
| Chicony Integrated Camera [ThinkPad]          | 18        | 1.06%   |
| Bison SunplusIT Integrated Camera             | 16        | 0.94%   |
| Apple FaceTime HD Camera                      | 16        | 0.94%   |
| Chicony Realtek DMFT RGB                      | 15        | 0.88%   |
| Chicony Integrated IR Camera                  | 15        | 0.88%   |
| Syntek Lenovo EasyCamera                      | 14        | 0.83%   |
| Lenovo Integrated Webcam [R5U877]             | 14        | 0.83%   |
| Chicony HP HD Webcam [Fixed]                  | 14        | 0.83%   |
| Sunplus Laptop_Integrated_Webcam_FHD          | 13        | 0.77%   |
| Chicony Lenovo EasyCamera                     | 12        | 0.71%   |
| Chicony Chicony USB2.0 Camera                 | 12        | 0.71%   |
| Bison ThinkPad Integrated Camera              | 12        | 0.71%   |
| Syntek EasyCamera                             | 11        | 0.65%   |
| Realtek USB Camera                            | 11        | 0.65%   |
| Microdia Dell Laptop Integrated Webcam HD     | 11        | 0.65%   |
| Chicony FJ Camera                             | 11        | 0.65%   |
| Bison Lenovo Integrated Webcam                | 11        | 0.65%   |
| Luxvisions Innotech Limited Integrated Camera | 10        | 0.59%   |
| IMC Networks Realtek DMFT RGB                 | 10        | 0.59%   |
| IMC Networks Integrated Webcam                | 10        | 0.59%   |
| Bison HD Webcam                               | 10        | 0.59%   |
| Suyin Integrated_Webcam_HD                    | 9         | 0.53%   |
| Sunplus HD WebCam                             | 9         | 0.53%   |
| Microdia Laptop_Integrated_Webcam_HD          | 9         | 0.53%   |
| Lenovo Integrated Webcam                      | 9         | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 178       | 37.24%  |
| Synaptics                  | 91        | 19.04%  |
| Upek                       | 56        | 11.72%  |
| AuthenTec                  | 43        | 9%      |
| Shenzhen Goodix Technology | 37        | 7.74%   |
| STMicroelectronics         | 26        | 5.44%   |
| Broadcom                   | 15        | 3.14%   |
| LighTuning Technology      | 12        | 2.51%   |
| Elan Microelectronics      | 12        | 2.51%   |
| FocalTech Systems          | 5         | 1.05%   |
| Samsung Electronics        | 2         | 0.42%   |
| Next Biometrics            | 1         | 0.21%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 61        | 12.76%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 53        | 11.09%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 39        | 8.16%   |
| Shenzhen Goodix Fingerprint Reader                                           | 29        | 6.07%   |
| Validity Sensors Synaptics WBDI                                              | 28        | 5.86%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 27        | 5.65%   |
| STMicroelectronics Fingerprint Reader                                        | 26        | 5.44%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 22        | 4.6%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 16        | 3.35%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 15        | 3.14%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 15        | 3.14%   |
| AuthenTec AES2810                                                            | 13        | 2.72%   |
| Elan Fingerprint Sensor                                                      | 12        | 2.51%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 10        | 2.09%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 8         | 1.67%   |
| AuthenTec AES1660                                                            | 8         | 1.67%   |
| Validity Sensors VFS491                                                      | 6         | 1.26%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 6         | 1.26%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                     | 6         | 1.26%   |
| AuthenTec AES1600                                                            | 6         | 1.26%   |
| Validity Sensors Fingerprint scanner                                         | 5         | 1.05%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 5         | 1.05%   |
| Shenzhen Goodix  Fingerprint Device                                          | 5         | 1.05%   |
| Validity Sensors VFS451 Fingerprint Reader                                   | 4         | 0.84%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint   | 4         | 0.84%   |
| Validity Sensors Swipe Fingerprint Sensor                                    | 4         | 0.84%   |
| Synaptics WBDI Fingerprint Reader USB 086                                    | 4         | 0.84%   |
| Synaptics WBDI                                                               | 4         | 0.84%   |
| FocalTech Systems Fingerprint Reader                                         | 4         | 0.84%   |
| Validity Sensors VFS Fingerprint sensor                                      | 3         | 0.63%   |
| Upek TCS5B Fingerprint sensor                                                | 3         | 0.63%   |
| Shenzhen Goodix Fingerprint Reader SGX                                       | 3         | 0.63%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 3         | 0.63%   |
| AuthenTec AES2660                                                            | 3         | 0.63%   |
| Synaptics UWP WBDI Device                                                    | 2         | 0.42%   |
| Synaptics UWP WBDI                                                           | 2         | 0.42%   |
| Samsung CanvasBio Fingerprint Reader                                         | 2         | 0.42%   |
| AuthenTec AES2550 Fingerprint Sensor                                         | 2         | 0.42%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                            | 1         | 0.21%   |
| Validity Sensors VFS301 Fingerprint Reader                                   | 1         | 0.21%   |

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
| 1     | 834       | 32.94%  |
| 2     | 723       | 28.55%  |
| 3     | 394       | 15.56%  |
| 0     | 350       | 13.82%  |
| 4     | 167       | 6.6%    |
| 5     | 43        | 1.7%    |
| 6     | 14        | 0.55%   |
| 7     | 5         | 0.2%    |
| 9     | 1         | 0.04%   |
| 8     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 1677      | 42%     |
| Bluetooth                | 543       | 13.6%   |
| Card reader              | 476       | 11.92%  |
| Net/wireless             | 475       | 11.9%   |
| Fingerprint reader       | 407       | 10.19%  |
| Firewire controller      | 161       | 4.03%   |
| Graphics card            | 72        | 1.8%    |
| Sound                    | 46        | 1.15%   |
| Storage                  | 42        | 1.05%   |
| Network                  | 38        | 0.95%   |
| Modem                    | 22        | 0.55%   |
| Net/ethernet             | 17        | 0.43%   |
| Storage/ata              | 8         | 0.2%    |
| Storage/raid             | 3         | 0.08%   |
| Storage/nvme             | 2         | 0.05%   |
| Storage/ide              | 2         | 0.05%   |
| Dvb card                 | 2         | 0.05%   |

