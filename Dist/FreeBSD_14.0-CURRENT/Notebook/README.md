FreeBSD 14.0-CURRENT - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------------

A project to collect tested hardware configurations for FreeBSD 14.0-CURRENT.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 156

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T495s 20QKS1812... | [0238ea2cab](https://bsd-hardware.info/?probe=0238ea2cab) | Aug 19, 2023 |
| Dell          | Inspiron 14-3467            | [5db7e9b7a1](https://bsd-hardware.info/?probe=5db7e9b7a1) | Aug 05, 2023 |
| ASUSTek       | ROG Strix G513QC_G513QC     | [b90e62e27d](https://bsd-hardware.info/?probe=b90e62e27d) | Aug 04, 2023 |
| HP            | EliteBook 8570p             | [2619fadb11](https://bsd-hardware.info/?probe=2619fadb11) | Jul 29, 2023 |
| HP            | EliteBook 8570p             | [9f4f71236e](https://bsd-hardware.info/?probe=9f4f71236e) | Jul 21, 2023 |
| HP            | EliteBook 8570p             | [44b85aad5e](https://bsd-hardware.info/?probe=44b85aad5e) | Jul 07, 2023 |
| HP            | EliteBook 8570p             | [03c29939fc](https://bsd-hardware.info/?probe=03c29939fc) | Jun 28, 2023 |
| HP            | EliteBook 8570p             | [748ae83ba1](https://bsd-hardware.info/?probe=748ae83ba1) | Jun 27, 2023 |
| HP            | EliteBook 850 G5            | [4bae8cd192](https://bsd-hardware.info/?probe=4bae8cd192) | Jun 27, 2023 |
| HP            | EliteBook 8570p             | [e7dfbf94d0](https://bsd-hardware.info/?probe=e7dfbf94d0) | Jun 25, 2023 |
| HP            | EliteBook 8570p             | [53bbc07cc8](https://bsd-hardware.info/?probe=53bbc07cc8) | Jun 17, 2023 |
| Lenovo        | IdeaPad Slim 9 14ITL5 82... | [03e1e6d302](https://bsd-hardware.info/?probe=03e1e6d302) | Jun 05, 2023 |
| Dell          | G5 5505                     | [5a3c1f19a0](https://bsd-hardware.info/?probe=5a3c1f19a0) | Jun 03, 2023 |
| Dell          | G5 5505                     | [1b10aecc38](https://bsd-hardware.info/?probe=1b10aecc38) | Jun 02, 2023 |
| HP            | EliteBook 8570p             | [22572f1df6](https://bsd-hardware.info/?probe=22572f1df6) | Jun 01, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | [8cc6299ba9](https://bsd-hardware.info/?probe=8cc6299ba9) | May 31, 2023 |
| HP            | EliteBook 8570p             | [65376d6b42](https://bsd-hardware.info/?probe=65376d6b42) | May 27, 2023 |
| HP            | EliteBook 8570p             | [a1a68c0f7d](https://bsd-hardware.info/?probe=a1a68c0f7d) | May 24, 2023 |
| HP            | EliteBook 8570p             | [70d54595c2](https://bsd-hardware.info/?probe=70d54595c2) | May 19, 2023 |
| Valve         | Jupiter                     | [7be0869603](https://bsd-hardware.info/?probe=7be0869603) | May 19, 2023 |
| Valve         | Jupiter                     | [ef56a2bd17](https://bsd-hardware.info/?probe=ef56a2bd17) | May 19, 2023 |
| Dell          | Inspiron 3581               | [25c403ca33](https://bsd-hardware.info/?probe=25c403ca33) | May 15, 2023 |
| HP            | EliteBook 8570p             | [e252dc5ff2](https://bsd-hardware.info/?probe=e252dc5ff2) | May 15, 2023 |
| Dell          | Inspiron 3581               | [8d445a3fb3](https://bsd-hardware.info/?probe=8d445a3fb3) | May 14, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [526906c806](https://bsd-hardware.info/?probe=526906c806) | May 14, 2023 |
| Alienware     | 17 R4                       | [df734c8e64](https://bsd-hardware.info/?probe=df734c8e64) | May 14, 2023 |
| HP            | EliteBook 8570p             | [6e82f69c4c](https://bsd-hardware.info/?probe=6e82f69c4c) | Apr 20, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [3d7bf4205b](https://bsd-hardware.info/?probe=3d7bf4205b) | Apr 13, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [c83b0dda87](https://bsd-hardware.info/?probe=c83b0dda87) | Mar 18, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [9ac4738956](https://bsd-hardware.info/?probe=9ac4738956) | Mar 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [6d9c564a33](https://bsd-hardware.info/?probe=6d9c564a33) | Mar 17, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | [44a8bf8fbc](https://bsd-hardware.info/?probe=44a8bf8fbc) | Mar 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [278a2a11cd](https://bsd-hardware.info/?probe=278a2a11cd) | Mar 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [ef85735453](https://bsd-hardware.info/?probe=ef85735453) | Mar 09, 2023 |
| Samsung       | 750XEE                      | [47d2204f58](https://bsd-hardware.info/?probe=47d2204f58) | Mar 08, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [f9db95d778](https://bsd-hardware.info/?probe=f9db95d778) | Mar 03, 2023 |
| HP            | EliteBook 8570p             | [1a4897cb53](https://bsd-hardware.info/?probe=1a4897cb53) | Feb 26, 2023 |
| HP            | EliteBook 8570p             | [1e548fa114](https://bsd-hardware.info/?probe=1e548fa114) | Feb 24, 2023 |
| HP            | EliteBook 8570p             | [1ba2a827d9](https://bsd-hardware.info/?probe=1ba2a827d9) | Feb 18, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [165d435f30](https://bsd-hardware.info/?probe=165d435f30) | Jan 31, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [448f9265f2](https://bsd-hardware.info/?probe=448f9265f2) | Jan 27, 2023 |
| Dell          | Precision 5540              | [683769b797](https://bsd-hardware.info/?probe=683769b797) | Jan 19, 2023 |
| HP            | EliteBook 8570p             | [17f5e2e3d2](https://bsd-hardware.info/?probe=17f5e2e3d2) | Jan 04, 2023 |
| Timi          | Redmi Book Pro 14 2022      | [ce5e882952](https://bsd-hardware.info/?probe=ce5e882952) | Dec 28, 2022 |
| HP            | EliteBook 8570p             | [7cf06451fd](https://bsd-hardware.info/?probe=7cf06451fd) | Dec 17, 2022 |
| HP            | EliteBook 8570p             | [64c92d49d9](https://bsd-hardware.info/?probe=64c92d49d9) | Dec 12, 2022 |
| HP            | EliteBook 8570p             | [6d10b2a0b4](https://bsd-hardware.info/?probe=6d10b2a0b4) | Dec 11, 2022 |
| HP            | EliteBook 8570p             | [3ad7cec298](https://bsd-hardware.info/?probe=3ad7cec298) | Nov 26, 2022 |
| HP            | EliteBook 8570p             | [436a2d30f6](https://bsd-hardware.info/?probe=436a2d30f6) | Nov 16, 2022 |
| Dell          | Latitude E7240              | [ea99621380](https://bsd-hardware.info/?probe=ea99621380) | Nov 12, 2022 |
| Google        | Akemi                       | [2d8e99f0c2](https://bsd-hardware.info/?probe=2d8e99f0c2) | Nov 12, 2022 |
| Lenovo        | Legion 5 15IMH05 82AU       | [d89559e5c2](https://bsd-hardware.info/?probe=d89559e5c2) | Oct 03, 2022 |
| System76      | Gazelle                     | [6d5d4f5021](https://bsd-hardware.info/?probe=6d5d4f5021) | Sep 24, 2022 |
| HP            | EliteBook 8570p             | [7c6751649b](https://bsd-hardware.info/?probe=7c6751649b) | Sep 07, 2022 |
| Valve         | Jupiter                     | [4e58d828cc](https://bsd-hardware.info/?probe=4e58d828cc) | Sep 01, 2022 |
| HP            | EliteBook 8570p             | [978f01c546](https://bsd-hardware.info/?probe=978f01c546) | Jul 16, 2022 |
| Lenovo        | ThinkPad T495 20NJ0010PB    | [078888676a](https://bsd-hardware.info/?probe=078888676a) | Jul 13, 2022 |
| Apple         | MacBookAir5,2               | [894b6f82cf](https://bsd-hardware.info/?probe=894b6f82cf) | Jul 13, 2022 |
| Toshiba       | Satellite L305D             | [ed950787b0](https://bsd-hardware.info/?probe=ed950787b0) | Jul 10, 2022 |
| Dell          | Latitude 5521               | [2c9d24a69e](https://bsd-hardware.info/?probe=2c9d24a69e) | Jun 19, 2022 |
| Dell          | Latitude 5410               | [3334ff3727](https://bsd-hardware.info/?probe=3334ff3727) | Jun 06, 2022 |
| HP            | EliteBook 8570p             | [1067f6ab27](https://bsd-hardware.info/?probe=1067f6ab27) | Jun 03, 2022 |
| HP            | ProBook 455 G7              | [c6944afe69](https://bsd-hardware.info/?probe=c6944afe69) | May 19, 2022 |
| Lenovo        | ThinkPad T495s 20QKS1812... | [89db84f7ec](https://bsd-hardware.info/?probe=89db84f7ec) | May 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [015bf0fea4](https://bsd-hardware.info/?probe=015bf0fea4) | May 06, 2022 |
| Framework     | Laptop                      | [5d6cb039ea](https://bsd-hardware.info/?probe=5d6cb039ea) | Apr 25, 2022 |
| HP            | EliteBook 8570p             | [0c73871c49](https://bsd-hardware.info/?probe=0c73871c49) | Apr 04, 2022 |
| MSI           | Bravo 15 A4DDR              | [1868573e9a](https://bsd-hardware.info/?probe=1868573e9a) | Apr 02, 2022 |
| Lenovo        | ThinkPad X260 20F5A28AUK    | [f53c625efd](https://bsd-hardware.info/?probe=f53c625efd) | Mar 30, 2022 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | [859a429ad0](https://bsd-hardware.info/?probe=859a429ad0) | Mar 24, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [6858ad2b12](https://bsd-hardware.info/?probe=6858ad2b12) | Mar 22, 2022 |
| HP            | EliteBook 8570p             | [7e1e137c8f](https://bsd-hardware.info/?probe=7e1e137c8f) | Mar 20, 2022 |
| Acer          | Aspire A114-33              | [6e7384f4cc](https://bsd-hardware.info/?probe=6e7384f4cc) | Mar 15, 2022 |
| Apple         | MacBookPro12,1              | [e04a1b354c](https://bsd-hardware.info/?probe=e04a1b354c) | Mar 11, 2022 |
| Apple         | MacBookPro12,1              | [ac59621182](https://bsd-hardware.info/?probe=ac59621182) | Mar 10, 2022 |
| Framework     | Laptop                      | [1f58e0594f](https://bsd-hardware.info/?probe=1f58e0594f) | Mar 01, 2022 |
| Apple         | MacBookPro10,1              | [64ccf1e6a0](https://bsd-hardware.info/?probe=64ccf1e6a0) | Feb 18, 2022 |
| Notebook      | NS50_70MU                   | [3b3ff8b95d](https://bsd-hardware.info/?probe=3b3ff8b95d) | Feb 05, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [e660899158](https://bsd-hardware.info/?probe=e660899158) | Feb 03, 2022 |
| Dell          | G3 3500                     | [536a7a1b38](https://bsd-hardware.info/?probe=536a7a1b38) | Jan 31, 2022 |
| HP            | EliteBook 8570p             | [f47789d894](https://bsd-hardware.info/?probe=f47789d894) | Jan 29, 2022 |
| MSI           | GE76 Raider 10UG            | [b48b628936](https://bsd-hardware.info/?probe=b48b628936) | Jan 27, 2022 |
| HP            | EliteBook 8570p             | [61406080a7](https://bsd-hardware.info/?probe=61406080a7) | Jan 18, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20T20... | [6836fc60f6](https://bsd-hardware.info/?probe=6836fc60f6) | Jan 09, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [6c208c85a5](https://bsd-hardware.info/?probe=6c208c85a5) | Jan 06, 2022 |
| HP            | EliteBook 8570p             | [1bbb37d4c6](https://bsd-hardware.info/?probe=1bbb37d4c6) | Jan 03, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [42b4bcbcc2](https://bsd-hardware.info/?probe=42b4bcbcc2) | Dec 27, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [695d7201d4](https://bsd-hardware.info/?probe=695d7201d4) | Dec 27, 2021 |
| HP            | EliteBook Folio 9470m       | [b872e9b044](https://bsd-hardware.info/?probe=b872e9b044) | Dec 18, 2021 |
| HP            | ProBook 440 G6              | [7a8a66430a](https://bsd-hardware.info/?probe=7a8a66430a) | Dec 13, 2021 |
| HP            | ProBook 440 G6              | [f3c014b120](https://bsd-hardware.info/?probe=f3c014b120) | Dec 12, 2021 |
| ASUSTek       | 1215B                       | [6dbcac684f](https://bsd-hardware.info/?probe=6dbcac684f) | Dec 04, 2021 |
| HP            | EliteBook 8570p             | [822a2481bb](https://bsd-hardware.info/?probe=822a2481bb) | Nov 17, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [e54d79065e](https://bsd-hardware.info/?probe=e54d79065e) | Nov 02, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [a71d3392eb](https://bsd-hardware.info/?probe=a71d3392eb) | Nov 02, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0PM0... | [7a61d90a55](https://bsd-hardware.info/?probe=7a61d90a55) | Oct 28, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [d910c79d75](https://bsd-hardware.info/?probe=d910c79d75) | Oct 24, 2021 |
| HP            | EliteBook 8570p             | [86613b04d3](https://bsd-hardware.info/?probe=86613b04d3) | Oct 17, 2021 |
| Valve         | Jupiter                     | [e5aca4b7d0](https://bsd-hardware.info/?probe=e5aca4b7d0) | Oct 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [0b73df29bf](https://bsd-hardware.info/?probe=0b73df29bf) | Sep 15, 2021 |
| Lenovo        | ThinkPad X395 20NL000GPG    | [d7812a2905](https://bsd-hardware.info/?probe=d7812a2905) | Sep 10, 2021 |
| Lenovo        | ThinkPad X395 20NL000GPG    | [cdde22fb04](https://bsd-hardware.info/?probe=cdde22fb04) | Sep 10, 2021 |
| HP            | EliteBook 8570p             | [fae9e84f60](https://bsd-hardware.info/?probe=fae9e84f60) | Aug 27, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [76f004bd26](https://bsd-hardware.info/?probe=76f004bd26) | Aug 26, 2021 |
| HP            | EliteBook 8570p             | [71092e78e2](https://bsd-hardware.info/?probe=71092e78e2) | Aug 17, 2021 |
| HP            | EliteBook 8570p             | [6e97c9a59e](https://bsd-hardware.info/?probe=6e97c9a59e) | Aug 14, 2021 |
| Lenovo        | Unknown                     | [e16ce5e864](https://bsd-hardware.info/?probe=e16ce5e864) | Aug 08, 2021 |
| HP            | ZBook 17 G2                 | [f2d911563a](https://bsd-hardware.info/?probe=f2d911563a) | Aug 07, 2021 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [6d5e1a13d0](https://bsd-hardware.info/?probe=6d5e1a13d0) | Aug 07, 2021 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | [bf56b2a81a](https://bsd-hardware.info/?probe=bf56b2a81a) | Aug 05, 2021 |
| HP            | ZBook 17 G2                 | [2faf8af7be](https://bsd-hardware.info/?probe=2faf8af7be) | Jul 30, 2021 |
| HP            | ZBook 17 G2                 | [c7fb9e9dee](https://bsd-hardware.info/?probe=c7fb9e9dee) | Jul 27, 2021 |
| HP            | ZBook 17 G2                 | [50c349b7b5](https://bsd-hardware.info/?probe=50c349b7b5) | Jul 27, 2021 |
| HP            | ZBook 17 G2                 | [6149ab50a8](https://bsd-hardware.info/?probe=6149ab50a8) | Jul 24, 2021 |
| Dell          | G5 5505                     | [9933a09c4f](https://bsd-hardware.info/?probe=9933a09c4f) | Jul 24, 2021 |
| HP            | ZBook 17 G2                 | [1ef99f31dd](https://bsd-hardware.info/?probe=1ef99f31dd) | Jul 23, 2021 |
| Avell High... | A62 LIV                     | [5983302b1d](https://bsd-hardware.info/?probe=5983302b1d) | Jul 21, 2021 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | [b0da42c20d](https://bsd-hardware.info/?probe=b0da42c20d) | Jul 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [9c9d4cc782](https://bsd-hardware.info/?probe=9c9d4cc782) | Jul 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [3d5e512e18](https://bsd-hardware.info/?probe=3d5e512e18) | Jul 18, 2021 |
| HP            | ProBook 440 G7              | [63dc88528c](https://bsd-hardware.info/?probe=63dc88528c) | Jul 17, 2021 |
| HP            | ProBook 440 G7              | [7138e2a9e7](https://bsd-hardware.info/?probe=7138e2a9e7) | Jul 17, 2021 |
| HP            | ProBook 440 G7              | [b73eb50747](https://bsd-hardware.info/?probe=b73eb50747) | Jul 16, 2021 |
| HP            | EliteBook 8570p             | [462fc329a9](https://bsd-hardware.info/?probe=462fc329a9) | Jul 16, 2021 |
| HP            | ProBook 440 G7              | [d2866f01b5](https://bsd-hardware.info/?probe=d2866f01b5) | Jul 16, 2021 |
| HP            | EliteBook 8570p             | [cc24e867fc](https://bsd-hardware.info/?probe=cc24e867fc) | Jun 19, 2021 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | [3d50ba4d85](https://bsd-hardware.info/?probe=3d50ba4d85) | Jun 13, 2021 |
| Dell          | G5 5505                     | [97319295ee](https://bsd-hardware.info/?probe=97319295ee) | Jun 13, 2021 |
| Dell          | Vostro 5490                 | [cf3508718c](https://bsd-hardware.info/?probe=cf3508718c) | Jun 11, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [4ac6c9b3eb](https://bsd-hardware.info/?probe=4ac6c9b3eb) | Jun 08, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [8fc867cfae](https://bsd-hardware.info/?probe=8fc867cfae) | Jun 06, 2021 |
| HP            | EliteBook 8570p             | [52ba4e835f](https://bsd-hardware.info/?probe=52ba4e835f) | Jun 03, 2021 |
| Lenovo        | ThinkPad X270 20HM004JBR    | [88c27e65d7](https://bsd-hardware.info/?probe=88c27e65d7) | May 23, 2021 |
| Dell          | G5 5505                     | [ba74d8eee0](https://bsd-hardware.info/?probe=ba74d8eee0) | May 08, 2021 |
| Dell          | G5 5505                     | [23ae99e489](https://bsd-hardware.info/?probe=23ae99e489) | May 08, 2021 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | [2be8cf963c](https://bsd-hardware.info/?probe=2be8cf963c) | May 02, 2021 |
| Dell          | Inspiron 3793               | [c2d56fc369](https://bsd-hardware.info/?probe=c2d56fc369) | Apr 29, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [4993ad0feb](https://bsd-hardware.info/?probe=4993ad0feb) | Apr 25, 2021 |
| HUAWEI        | HN-WX9X                     | [d776625073](https://bsd-hardware.info/?probe=d776625073) | Apr 11, 2021 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [342e914968](https://bsd-hardware.info/?probe=342e914968) | Mar 29, 2021 |
| HP            | EliteBook 8570p             | [ed80dc9019](https://bsd-hardware.info/?probe=ed80dc9019) | Mar 27, 2021 |
| HP            | ProBook 455 G7              | [dd877e6c6c](https://bsd-hardware.info/?probe=dd877e6c6c) | Mar 27, 2021 |
| Lenovo        | ThinkPad X395 20NL001SMX    | [cd016e96ee](https://bsd-hardware.info/?probe=cd016e96ee) | Mar 17, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [9fed35d792](https://bsd-hardware.info/?probe=9fed35d792) | Mar 10, 2021 |
| HP            | ProBook 455 G7              | [1fcde7c0e1](https://bsd-hardware.info/?probe=1fcde7c0e1) | Mar 09, 2021 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | [aacafb6ace](https://bsd-hardware.info/?probe=aacafb6ace) | Feb 24, 2021 |
| A-DATA Tec... | XENIA159GENI72060           | [be88e8f865](https://bsd-hardware.info/?probe=be88e8f865) | Feb 15, 2021 |
| Lenovo        | ThinkPad T495s 20QKS1812... | [0e5e228d18](https://bsd-hardware.info/?probe=0e5e228d18) | Feb 13, 2021 |
| Lenovo        | ThinkPad T495s 20QKS1812... | [2d93a6bebc](https://bsd-hardware.info/?probe=2d93a6bebc) | Feb 13, 2021 |
| Matsushita... | CF-T2BW1AXR                 | [f6ec2858a5](https://bsd-hardware.info/?probe=f6ec2858a5) | Feb 10, 2021 |
| HP            | EliteBook 8570p             | [72137c63f8](https://bsd-hardware.info/?probe=72137c63f8) | Feb 09, 2021 |
| Dell          | Latitude E5430 vPro         | [bee421a110](https://bsd-hardware.info/?probe=bee421a110) | Feb 06, 2021 |
| Dell          | Latitude E5430 vPro         | [e8157ac6a3](https://bsd-hardware.info/?probe=e8157ac6a3) | Feb 06, 2021 |
| Lenovo        | ThinkPad T430 2349H2G       | [229db16a93](https://bsd-hardware.info/?probe=229db16a93) | Feb 05, 2021 |
| HP            | EliteBook 8570p             | [46c938b853](https://bsd-hardware.info/?probe=46c938b853) | Feb 01, 2021 |
| Matsushita... | CF-T2BW1AXR                 | [c16cd20c42](https://bsd-hardware.info/?probe=c16cd20c42) | Jan 25, 2021 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 74        | 98.67%  |
| i386  | 1         | 1.33%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KDE5          | 22        | 27.16%  |
| XFCE          | 12        | 14.81%  |
| Console       | 9         | 11.11%  |
| TWM           | 6         | 7.41%   |
| GNOME         | 6         | 7.41%   |
| MATE          | 5         | 6.17%   |
| i3            | 5         | 6.17%   |
| Cinnamon      | 3         | 3.7%    |
| LXDE          | 2         | 2.47%   |
| Lumina        | 2         | 2.47%   |
| Xfwm4         | 1         | 1.23%   |
| sway          | 1         | 1.23%   |
| Picom         | 1         | 1.23%   |
| LXQt          | 1         | 1.23%   |
| GNUstep       | 1         | 1.23%   |
| Fluxbox       | 1         | 1.23%   |
| Enlightenment | 1         | 1.23%   |
| ctwm          | 1         | 1.23%   |
| Budgie        | 1         | 1.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 64        | 82.05%  |
| Console | 12        | 15.38%  |
| Wayland | 2         | 2.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 27        | 34.18%  |
| SDDM    | 23        | 29.11%  |
| SLiM    | 10        | 12.66%  |
| GDM     | 8         | 10.13%  |
| XDM     | 6         | 7.59%   |
| LightDM | 4         | 5.06%   |
| Ly      | 1         | 1.27%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Notebooks | Percent |
|------------------|-----------|---------|
| C                | 56        | 72.73%  |
| en_US            | 7         | 9.09%   |
| Unknown          | 3         | 3.9%    |
| zh_CN            | 2         | 2.6%    |
| fr_FR            | 2         | 2.6%    |
| en_GB            | 2         | 2.6%    |
| ru_RU            | 1         | 1.3%    |
| pt_PT            | 1         | 1.3%    |
| pl_PL            | 1         | 1.3%    |
| it_IT.ISO8859-15 | 1         | 1.3%    |
| de_DE            | 1         | 1.3%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 69        | 92%     |
| BIOS | 6         | 8%      |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Zfs  | 58        | 76.32%  |
| Ufs  | 17        | 22.37%  |
| Nfs  | 1         | 1.32%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 73        | 97.33%  |
| MBR  | 2         | 2.67%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 29        | 38.67%  |
| Dell                           | 11        | 14.67%  |
| Hewlett-Packard                | 10        | 13.33%  |
| ASUSTek Computer               | 4         | 5.33%   |
| Apple                          | 3         | 4%      |
| Valve                          | 2         | 2.67%   |
| MSI                            | 2         | 2.67%   |
| Framework                      | 2         | 2.67%   |
| F-Plus Mobile                  | 2         | 2.67%   |
| Timi                           | 1         | 1.33%   |
| System76                       | 1         | 1.33%   |
| Samsung Electronics            | 1         | 1.33%   |
| Notebook                       | 1         | 1.33%   |
| Matsushita Electric Industrial | 1         | 1.33%   |
| HUAWEI                         | 1         | 1.33%   |
| Google                         | 1         | 1.33%   |
| Avell High Performance         | 1         | 1.33%   |
| Alienware                      | 1         | 1.33%   |
| A-DATA Technology              | 1         | 1.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| HP EliteBook 8570p                          | 3         | 4%      |
| Valve Jupiter                               | 2         | 2.67%   |
| Framework Laptop                            | 2         | 2.67%   |
| F-Plus Mobile FLAPTOP r                     | 2         | 2.67%   |
| Timi Redmi Book Pro 14 2022                 | 1         | 1.33%   |
| System76 Gazelle                            | 1         | 1.33%   |
| Samsung 750XEE                              | 1         | 1.33%   |
| Notebook NS50_70MU                          | 1         | 1.33%   |
| MSI GE76 Raider 10UG                        | 1         | 1.33%   |
| MSI Bravo 15 A4DDR                          | 1         | 1.33%   |
| Matsushita Electric Industrial CF-T2BW1AXR  | 1         | 1.33%   |
| Lenovo XiaoXinPro-13ARE 2020 82DM           | 1         | 1.33%   |
| Lenovo ThinkPad X395 20NL001SMX             | 1         | 1.33%   |
| Lenovo ThinkPad X395 20NL000GPG             | 1         | 1.33%   |
| Lenovo ThinkPad X270 20HM004JBR             | 1         | 1.33%   |
| Lenovo ThinkPad X260 20F5A28AUK             | 1         | 1.33%   |
| Lenovo ThinkPad X13 Gen 1 20T2003PRT        | 1         | 1.33%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TLA055CD | 1         | 1.33%   |
| Lenovo ThinkPad X1 Extreme 20MF000BUS       | 1         | 1.33%   |
| Lenovo ThinkPad X1 Carbon 6th 20KHCTO1WW    | 1         | 1.33%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS1QC00    | 1         | 1.33%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS0BT00    | 1         | 1.33%   |
| Lenovo ThinkPad T495s 20QKS1812F            | 1         | 1.33%   |
| Lenovo ThinkPad T495 20NJ0010PB             | 1         | 1.33%   |
| Lenovo ThinkPad T470p 20J7S0PM00            | 1         | 1.33%   |
| Lenovo ThinkPad T430 2349H2G                | 1         | 1.33%   |
| Lenovo ThinkPad T15p Gen 3 21DA000QUS       | 1         | 1.33%   |
| Lenovo ThinkPad T14s Gen 2i 20WM00B7MX      | 1         | 1.33%   |
| Lenovo ThinkPad T14s Gen 1 20UH0019PB       | 1         | 1.33%   |
| Lenovo ThinkPad P15 Gen 1 20ST005VRT        | 1         | 1.33%   |
| Lenovo ThinkPad P14s Gen 1 20Y1CTO1WW       | 1         | 1.33%   |
| Lenovo ThinkPad E14 Gen 3 20Y7003SGE        | 1         | 1.33%   |
| Lenovo ThinkPad E14 20RBCTO1WW              | 1         | 1.33%   |
| Lenovo ThinkBook 14 G3 ACL 21A2             | 1         | 1.33%   |
| Lenovo Legion 5P 15IMH05H 82AW              | 1         | 1.33%   |
| Lenovo Legion 5 15IMH05 82AU                | 1         | 1.33%   |
| Lenovo IdeaPad Slim 9 14ITL5 82D2           | 1         | 1.33%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY        | 1         | 1.33%   |
| Lenovo IdeaPad 330-15ARR 81D2               | 1         | 1.33%   |
| HUAWEI HN-WX9X                              | 1         | 1.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo ThinkPad                            | 21        | 28%     |
| HP EliteBook                               | 5         | 6.67%   |
| HP ProBook                                 | 4         | 5.33%   |
| Dell Latitude                              | 4         | 5.33%   |
| Lenovo IdeaPad                             | 3         | 4%      |
| Dell Inspiron                              | 3         | 4%      |
| Valve Jupiter                              | 2         | 2.67%   |
| Lenovo Legion                              | 2         | 2.67%   |
| Framework Laptop                           | 2         | 2.67%   |
| F-Plus Mobile FLAPTOP                      | 2         | 2.67%   |
| Timi Redmi                                 | 1         | 1.33%   |
| System76 Gazelle                           | 1         | 1.33%   |
| Samsung 750XEE                             | 1         | 1.33%   |
| Notebook NS50                              | 1         | 1.33%   |
| MSI GE76                                   | 1         | 1.33%   |
| MSI Bravo                                  | 1         | 1.33%   |
| Matsushita Electric Industrial CF-T2BW1AXR | 1         | 1.33%   |
| Lenovo XiaoXinPro-13ARE                    | 1         | 1.33%   |
| Lenovo ThinkBook                           | 1         | 1.33%   |
| HUAWEI HN-WX9X                             | 1         | 1.33%   |
| HP ZBook                                   | 1         | 1.33%   |
| Google Akemi                               | 1         | 1.33%   |
| Dell Vostro                                | 1         | 1.33%   |
| Dell Precision                             | 1         | 1.33%   |
| Dell G5                                    | 1         | 1.33%   |
| Dell G3                                    | 1         | 1.33%   |
| Avell High Performance A62                 | 1         | 1.33%   |
| ASUS VivoBook                              | 1         | 1.33%   |
| ASUS ROG                                   | 1         | 1.33%   |
| ASUS ASUS                                  | 1         | 1.33%   |
| ASUS 1215B                                 | 1         | 1.33%   |
| Apple MacBookPro12                         | 1         | 1.33%   |
| Apple MacBookPro10                         | 1         | 1.33%   |
| Apple MacBookAir5                          | 1         | 1.33%   |
| Alienware 17                               | 1         | 1.33%   |
| A-DATA XENIA159GENI72060                   | 1         | 1.33%   |
| Unknown                                    | 1         | 1.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 17        | 22.67%  |
| 2020 | 17        | 22.67%  |
| 2022 | 12        | 16%     |
| 2019 | 8         | 10.67%  |
| 2017 | 4         | 5.33%   |
| 2013 | 4         | 5.33%   |
| 2023 | 3         | 4%      |
| 2018 | 3         | 4%      |
| 2015 | 3         | 4%      |
| 2016 | 1         | 1.33%   |
| 2014 | 1         | 1.33%   |
| 2011 | 1         | 1.33%   |
| 2003 | 1         | 1.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 75        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 73        | 97.33%  |
| Yes  | 2         | 2.67%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 35        | 45.45%  |
| 8.01-16.0   | 18        | 23.38%  |
| 32.01-64.0  | 15        | 19.48%  |
| 64.01-256.0 | 4         | 5.19%   |
| 4.01-8.0    | 3         | 3.9%    |
| 24.01-32.0  | 1         | 1.3%    |
| 1.01-2.0    | 1         | 1.3%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.51-1.0   | 31        | 40.26%  |
| 1.01-2.0   | 25        | 32.47%  |
| 2.01-3.0   | 8         | 10.39%  |
| 0.01-0.5   | 8         | 10.39%  |
| 3.01-4.0   | 2         | 2.6%    |
| 24.01-32.0 | 2         | 2.6%    |
| 8.01-16.0  | 1         | 1.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 55        | 67.07%  |
| 2      | 23        | 28.05%  |
| 3      | 3         | 3.66%   |
| 0      | 1         | 1.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 70        | 90.91%  |
| Yes       | 7         | 9.09%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 58        | 77.33%  |
| No        | 17        | 22.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 98.67%  |
| No        | 1         | 1.33%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 59        | 77.63%  |
| No        | 17        | 22.37%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 14        | 18.67%  |
| UK          | 8         | 10.67%  |
| Russia      | 8         | 10.67%  |
| Germany     | 7         | 9.33%   |
| Poland      | 5         | 6.67%   |
| China       | 5         | 6.67%   |
| Brazil      | 3         | 4%      |
| Portugal    | 2         | 2.67%   |
| France      | 2         | 2.67%   |
| Canada      | 2         | 2.67%   |
| Austria     | 2         | 2.67%   |
| Ukraine     | 1         | 1.33%   |
| Turkey      | 1         | 1.33%   |
| Taiwan      | 1         | 1.33%   |
| Switzerland | 1         | 1.33%   |
| Sweden      | 1         | 1.33%   |
| Spain       | 1         | 1.33%   |
| Peru        | 1         | 1.33%   |
| Netherlands | 1         | 1.33%   |
| Jordan      | 1         | 1.33%   |
| Japan       | 1         | 1.33%   |
| Italy       | 1         | 1.33%   |
| India       | 1         | 1.33%   |
| Denmark     | 1         | 1.33%   |
| Croatia     | 1         | 1.33%   |
| Colombia    | 1         | 1.33%   |
| Belarus     | 1         | 1.33%   |
| Bangladesh  | 1         | 1.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City            | Notebooks | Percent |
|-----------------|-----------|---------|
| Brighton        | 5         | 5.62%   |
| Moscow          | 4         | 4.49%   |
| Seattle         | 3         | 3.37%   |
| London          | 3         | 3.37%   |
| Warsaw          | 2         | 2.25%   |
| Vienna          | 2         | 2.25%   |
| St Petersburg   | 2         | 2.25%   |
| Shoreham-by-Sea | 2         | 2.25%   |
| ЕЊta-ku       | 1         | 1.12%   |
| Zurich          | 1         | 1.12%   |
| Wuhan           | 1         | 1.12%   |
| Wieliczka       | 1         | 1.12%   |
| Washington      | 1         | 1.12%   |
| Voznesensk      | 1         | 1.12%   |
| Vancouver       | 1         | 1.12%   |
| Trosa           | 1         | 1.12%   |
| Toronto         | 1         | 1.12%   |
| Thrissur        | 1         | 1.12%   |
| Taipei          | 1         | 1.12%   |
| Stuttgart       | 1         | 1.12%   |
| Slavonski Brod  | 1         | 1.12%   |
| Shanghai        | 1         | 1.12%   |
| Rostov-on-Don   | 1         | 1.12%   |
| Riverside       | 1         | 1.12%   |
| Resana          | 1         | 1.12%   |
| Poulsbo         | 1         | 1.12%   |
| Pobiedziska     | 1         | 1.12%   |
| Paris           | 1         | 1.12%   |
| Omaha           | 1         | 1.12%   |
| Olympia         | 1         | 1.12%   |
| Northeim        | 1         | 1.12%   |
| New York        | 1         | 1.12%   |
| Neumünster     | 1         | 1.12%   |
| Montclair       | 1         | 1.12%   |
| Minsk           | 1         | 1.12%   |
| Milan           | 1         | 1.12%   |
| Medellín       | 1         | 1.12%   |
| Manchester      | 1         | 1.12%   |
| Maia            | 1         | 1.12%   |
| Madrid          | 1         | 1.12%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 26        | 33     | 26.26%  |
| WDC                 | 13        | 20     | 13.13%  |
| Toshiba             | 11        | 20     | 11.11%  |
| KIOXIA              | 6         | 6      | 6.06%   |
| HGST                | 6         | 27     | 6.06%   |
| Seagate             | 5         | 7      | 5.05%   |
| Kingston            | 4         | 6      | 4.04%   |
| Crucial             | 4         | 7      | 4.04%   |
| SK hynix            | 3         | 3      | 3.03%   |
| Apple               | 3         | 3      | 3.03%   |
| A-DATA Technology   | 3         | 3      | 3.03%   |
| Micron Technology   | 2         | 2      | 2.02%   |
| Intel               | 2         | 2      | 2.02%   |
| FORESEE             | 2         | 2      | 2.02%   |
| UMIS                | 1         | 1      | 1.01%   |
| SSSTC               | 1         | 1      | 1.01%   |
| SPCC                | 1         | 1      | 1.01%   |
| Solid State Storage | 1         | 1      | 1.01%   |
| Silicon Motion      | 1         | 1      | 1.01%   |
| SanDisk             | 1         | 2      | 1.01%   |
| Mushkin             | 1         | 1      | 1.01%   |
| LITEON              | 1         | 1      | 1.01%   |
| Fujitsu             | 1         | 2      | 1.01%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB                           | 7         | 6.67%   |
| HGST HTS725050A7E630 500GB                         | 4         | 3.81%   |
| Samsung HM251JX 250GB                              | 3         | 2.86%   |
| HGST HTS721010A9E630 1TB                           | 3         | 2.86%   |
| WDC WDS100T3X0C-00SJG0 1TB                         | 2         | 1.9%    |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB                 | 2         | 1.9%    |
| WDC PC SN730 NVMe 1024GB                           | 2         | 1.9%    |
| Toshiba MQ04ABF100 1TB                             | 2         | 1.9%    |
| Seagate ST1000LM035-1RK172 1TB                     | 2         | 1.9%    |
| Samsung SSD 970 EVO Plus 1TB                       | 2         | 1.9%    |
| Samsung MZVLB512HBJQ-000L7 512GB                   | 2         | 1.9%    |
| Samsung MZVLB1T0HBLR-000L2 1TB                     | 2         | 1.9%    |
| KIOXIA KBG40ZNS512G NVMe 512GB                     | 2         | 1.9%    |
| KIOXIA KBG40ZNS256G NVMe 256GB                     | 2         | 1.9%    |
| FORESEE XP1000F001T 1TB                            | 2         | 1.9%    |
| Apple SSD SM256E 256GB                             | 2         | 1.9%    |
| WDC WDS500G1X0E-00AFY0 500GB                       | 1         | 0.95%   |
| WDC WDS100T1X0E-00AFY0 1TB                         | 1         | 0.95%   |
| WDC WD10SPZX-60Z10T0 1TB                           | 1         | 0.95%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB               | 1         | 0.95%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB               | 1         | 0.95%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB               | 1         | 0.95%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB               | 1         | 0.95%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB               | 1         | 0.95%   |
| UMIS RPETJ1T24MGE2QDQ 1TB                          | 1         | 0.95%   |
| Toshiba THNSN51T02DUK NVMe 1024GB                  | 1         | 0.95%   |
| Toshiba KXG6APNV2T04 2TB                           | 1         | 0.95%   |
| SSSTC CL1-8D512 512GB                              | 1         | 0.95%   |
| SPCC M.2 PCIe SSD 1TB                              | 1         | 0.95%   |
| Solid State Storage CL1-3D128-Q11 NVMe SSSTC 128GB | 1         | 0.95%   |
| SK hynix PC300 HFS512GD9MND-5510A 512GB            | 1         | 0.95%   |
| SK hynix BC511 NVMe 256GB                          | 1         | 0.95%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB            | 1         | 0.95%   |
| Silicon Motion NE-256 256GB                        | 1         | 0.95%   |
| Seagate ST2000LM007-1R8174 2TB                     | 1         | 0.95%   |
| Seagate ST1000LM049-2GH172 1TB                     | 1         | 0.95%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 1         | 0.95%   |
| SanDisk SDSSDH3500G 500GB                          | 1         | 0.95%   |
| Samsung SSD PM851 mSATA 256GB                      | 1         | 0.95%   |
| Samsung SSD 980 PRO 1TB                            | 1         | 0.95%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 9         | 17     | 36%     |
| HGST                | 6         | 27     | 24%     |
| Seagate             | 5         | 7      | 20%     |
| Samsung Electronics | 3         | 3      | 12%     |
| WDC                 | 1         | 1      | 4%      |
| Fujitsu             | 1         | 2      | 4%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 5      | 28.57%  |
| Apple               | 3         | 3      | 21.43%  |
| Kingston            | 2         | 3      | 14.29%  |
| SanDisk             | 1         | 2      | 7.14%   |
| LITEON              | 1         | 1      | 7.14%   |
| Intel               | 1         | 1      | 7.14%   |
| Crucial             | 1         | 1      | 7.14%   |
| A-DATA Technology   | 1         | 1      | 7.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 54        | 78     | 62.79%  |
| HDD  | 18        | 57     | 20.93%  |
| SSD  | 14        | 17     | 16.28%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 54        | 78     | 62.79%  |
| SATA | 32        | 74     | 37.21%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 23        | 44     | 69.7%   |
| 0.51-1.0   | 9         | 29     | 27.27%  |
| 1.01-2.0   | 1         | 1      | 3.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 24        | 29.63%  |
| 101-250    | 20        | 24.69%  |
| 501-1000   | 16        | 19.75%  |
| 51-100     | 8         | 9.88%   |
| 21-50      | 5         | 6.17%   |
| 1001-2000  | 4         | 4.94%   |
| 1-20       | 3         | 3.7%    |
| 2001-3000  | 1         | 1.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 46        | 56.79%  |
| 21-50    | 27        | 33.33%  |
| 101-250  | 5         | 6.17%   |
| 251-500  | 1         | 1.23%   |
| 501-1000 | 1         | 1.23%   |
| 51-100   | 1         | 1.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                     | Notebooks | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| HGST HTS725050A7E630 500GB                | 4         | 7      | 44.44%  |
| WDC WD10SPZX-60Z10T0 1TB                  | 1         | 1      | 11.11%  |
| Samsung Electronics SSD PM851 mSATA 256GB | 1         | 1      | 11.11%  |
| Samsung Electronics HM251JX 250GB         | 1         | 1      | 11.11%  |
| HGST HTS721010A9E630 1TB                  | 1         | 17     | 11.11%  |
| Fujitsu MHS2040AT D 40GB                  | 1         | 2      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 4         | 24     | 50%     |
| Samsung Electronics | 2         | 2      | 25%     |
| WDC                 | 1         | 1      | 12.5%   |
| Fujitsu             | 1         | 2      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 4         | 24     | 57.14%  |
| WDC                 | 1         | 1      | 14.29%  |
| Samsung Electronics | 1         | 1      | 14.29%  |
| Fujitsu             | 1         | 2      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 28     | 85.71%  |
| SSD  | 1         | 1      | 14.29%  |

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
| Works    | 72        | 120    | 87.8%   |
| Malfunc  | 7         | 29     | 8.54%   |
| Detected | 3         | 3      | 3.66%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 38        | 35.19%  |
| Samsung Electronics                     | 20        | 18.52%  |
| SanDisk                                 | 13        | 12.04%  |
| AMD                                     | 8         | 7.41%   |
| KIOXIA                                  | 5         | 4.63%   |
| Toshiba                                 | 4         | 3.7%    |
| SK hynix                                | 3         | 2.78%   |
| Micron Technology                       | 3         | 2.78%   |
| Solid State Storage Technology          | 2         | 1.85%   |
| Silicon Motion                          | 2         | 1.85%   |
| Shenzhen Longsys Electronics            | 2         | 1.85%   |
| Micron/Crucial Technology               | 2         | 1.85%   |
| Kingston Technology Company             | 2         | 1.85%   |
| ADATA Technology                        | 2         | 1.85%   |
| Shenzhen Unionmemory Information System | 1         | 0.93%   |
| MAXIO Technology (Hangzhou)             | 1         | 0.93%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 12        | 10.71%  |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 9         | 8.04%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 6.25%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 7         | 6.25%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 5         | 4.46%   |
| Intel Comet Lake SATA AHCI Controller                                          | 5         | 4.46%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 5         | 4.46%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 4         | 3.57%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 2.68%   |
| Toshiba XG6 NVMe SSD Controller                                                | 2         | 1.79%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                 | 2         | 1.79%   |
| SK hynix BC511 NVMe SSD                                                        | 2         | 1.79%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 2         | 1.79%   |
| Shenzhen Longsys Lexar NM620 NVME SSD (DRAM-less)                              | 2         | 1.79%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 1.79%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 1.79%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 2         | 1.79%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 1.79%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.79%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 2         | 1.79%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 2         | 1.79%   |
| Toshiba XG5 NVMe SSD Controller                                                | 1         | 0.89%   |
| Toshiba XG4 NVMe SSD Controller                                                | 1         | 0.89%   |
| SK hynix PC300 NVMe Solid State Drive 512GB                                    | 1         | 0.89%   |
| Shenzhen Unionmemory Information System AM630 PCIe 4.0 NVMe SSD 1024GB         | 1         | 0.89%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 1         | 0.89%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 1         | 0.89%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 1         | 0.89%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.89%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 1         | 0.89%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1         | 0.89%   |
| Micron 2300 NVMe SSD [Santana]                                                 | 1         | 0.89%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 1         | 0.89%   |
| Micron 2200S NVMe SSD [Cassandra]                                              | 1         | 0.89%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                   | 1         | 0.89%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                     | 1         | 0.89%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 1         | 0.89%   |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD                                 | 1         | 0.89%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 0.89%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1         | 0.89%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 56        | 54.9%   |
| SATA | 41        | 40.2%   |
| IDE  | 3         | 2.94%   |
| RAID | 2         | 1.96%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 53        | 69.74%  |
| AMD    | 23        | 30.26%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-10210U CPU @ 1.60GHz              | 5         | 6.58%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 5         | 6.58%   |
| Intel Core i7-3520M CPU @ 2.90GHz               | 4         | 5.26%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 3         | 3.95%   |
| Intel Core i5-10300H CPU @ 2.50GHz              | 3         | 3.95%   |
| Intel Core i7-7600U CPU @ 2.80GHz               | 2         | 2.63%   |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx | 2         | 2.63%   |
| AMD Ryzen 7 5825U with Radeon Graphics          | 2         | 2.63%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 2         | 2.63%   |
| AMD Ryzen 5 PRO 3500U w/ Radeon Vega Mobile Gfx | 2         | 2.63%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 2         | 2.63%   |
| AMD Custom APU 0405                             | 2         | 2.63%   |
| Intel Xeon W-10885M CPU @ 2.40GHz               | 1         | 1.32%   |
| Intel Pentium M processor 1000MHz               | 1         | 1.32%   |
| Intel Core i7-9850H CPU @ 2.60GHz               | 1         | 1.32%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 1         | 1.32%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 1         | 1.32%   |
| Intel Core i7-8650U CPU @ 1.90GHz               | 1         | 1.32%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 1.32%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 1         | 1.32%   |
| Intel Core i7-7820HK CPU @ 2.90GHz              | 1         | 1.32%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 1.32%   |
| Intel Core i7-5600U CPU @ 2.60GHz               | 1         | 1.32%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz              | 1         | 1.32%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz              | 1         | 1.32%   |
| Intel Core i7-4600U CPU @ 2.10GHz               | 1         | 1.32%   |
| Intel Core i7-3687U CPU @ 2.10GHz               | 1         | 1.32%   |
| Intel Core i7-3615QM CPU @ 2.30GHz              | 1         | 1.32%   |
| Intel Core i7-10870H CPU @ 2.20GHz              | 1         | 1.32%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz              | 1         | 1.32%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 1         | 1.32%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 1         | 1.32%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 1         | 1.32%   |
| Intel Core i5-5257U CPU @ 2.70GHz               | 1         | 1.32%   |
| Intel Core i5-3427U CPU @ 1.80GHz               | 1         | 1.32%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 1         | 1.32%   |
| Intel Core i3-7020U CPU @ 2.30GHz               | 1         | 1.32%   |
| Intel 12th Gen Core i7-12800H                   | 1         | 1.32%   |
| Intel 12th Gen Core i7-1260P                    | 1         | 1.32%   |
| Intel 11th Gen Core i7-1195G7 @ 2.90GHz         | 1         | 1.32%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel Core i7   | 26        | 34.67%  |
| Intel Core i5   | 13        | 17.33%  |
| Other           | 12        | 16%     |
| AMD Ryzen 7     | 8         | 10.67%  |
| AMD Ryzen 5     | 4         | 5.33%   |
| AMD Ryzen 7 PRO | 3         | 4%      |
| AMD Ryzen 5 PRO | 3         | 4%      |
| Intel Xeon      | 1         | 1.33%   |
| Intel Pentium M | 1         | 1.33%   |
| Intel Core i3   | 1         | 1.33%   |
| AMD Ryzen 9     | 1         | 1.33%   |
| AMD Ryzen 3     | 1         | 1.33%   |
| AMD E           | 1         | 1.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 26        | 34.21%  |
| 2      | 16        | 21.05%  |
| 8      | 14        | 18.42%  |
| 16     | 9         | 11.84%  |
| 6      | 6         | 7.89%   |
| 12     | 3         | 3.95%   |
| 10     | 1         | 1.32%   |
| 1      | 1         | 1.32%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 75        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 52        | 68.42%  |
| 1       | 23        | 30.26%  |
| Unknown | 1         | 1.32%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| KabyLake  | 18        | 23.68%  |
| Unknown   | 9         | 11.84%  |
| IvyBridge | 8         | 10.53%  |
| CometLake | 8         | 10.53%  |
| Zen 2     | 7         | 9.21%   |
| TigerLake | 7         | 9.21%   |
| Zen+      | 6         | 7.89%   |
| Zen 3     | 3         | 3.95%   |
| Haswell   | 3         | 3.95%   |
| Broadwell | 2         | 2.63%   |
| Zen       | 1         | 1.32%   |
| Skylake   | 1         | 1.32%   |
| P6        | 1         | 1.32%   |
| IceLake   | 1         | 1.32%   |
| Bobcat    | 1         | 1.32%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 49        | 48.51%  |
| AMD    | 28        | 27.72%  |
| Nvidia | 24        | 23.76%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                            | 7         | 6.8%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]        | 7         | 6.8%    |
| Intel CometLake-U GT2 [UHD Graphics]                                 | 6         | 5.83%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series] | 6         | 5.83%   |
| Intel CometLake-H GT2 [UHD Graphics]                                 | 5         | 4.85%   |
| Intel 3rd Gen Core processor Graphics Controller                     | 5         | 4.85%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                      | 4         | 3.88%   |
| Intel HD Graphics 620                                                | 4         | 3.88%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                            | 3         | 2.91%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                             | 3         | 2.91%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                           | 2         | 1.94%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                           | 2         | 1.94%   |
| Nvidia GP108M [GeForce MX230]                                        | 2         | 1.94%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                              | 2         | 1.94%   |
| Intel UHD Graphics 620                                               | 2         | 1.94%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                 | 2         | 1.94%   |
| Intel HD Graphics 630                                                | 2         | 1.94%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                            | 2         | 1.94%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller          | 2         | 1.94%   |
| AMD VanGogh [AMD Custom GPU 0405]                                    | 2         | 1.94%   |
| AMD Lucienne                                                         | 2         | 1.94%   |
| AMD Barcelo                                                          | 2         | 1.94%   |
| Nvidia TU117M [GeForce MX450]                                        | 1         | 0.97%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                | 1         | 0.97%   |
| Nvidia TU104GLM [Quadro RTX 5000 Mobile / Max-Q]                     | 1         | 0.97%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                           | 1         | 0.97%   |
| Nvidia GP104BM [GeForce GTX 1080 Mobile]                             | 1         | 0.97%   |
| Nvidia GM108M [GeForce MX130]                                        | 1         | 0.97%   |
| Nvidia GM108M [GeForce 940MX]                                        | 1         | 0.97%   |
| Nvidia GM107M [GeForce GTX 860M]                                     | 1         | 0.97%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                          | 1         | 0.97%   |
| Nvidia GK107GLM [Quadro K1100M]                                      | 1         | 0.97%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                           | 1         | 0.97%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                      | 1         | 0.97%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                           | 1         | 0.97%   |
| Intel Skylake GT2 [HD Graphics 520]                                  | 1         | 0.97%   |
| Intel JasperLake [UHD Graphics]                                      | 1         | 0.97%   |
| Intel Iris Plus Graphics G7                                          | 1         | 0.97%   |
| Intel Iris Graphics 6100                                             | 1         | 0.97%   |
| Intel HD Graphics 5500                                               | 1         | 0.97%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 27        | 35.06%  |
| 1 x AMD                  | 22        | 28.57%  |
| Intel + Nvidia           | 19        | 24.68%  |
| 1 x Nvidia               | 3         | 3.9%    |
| 2 x AMD                  | 2         | 2.6%    |
| AMD + Nvidia             | 2         | 2.6%    |
| Intel + AMD + 1 x Nvidia | 1         | 1.3%    |
| Intel + AMD              | 1         | 1.3%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 64        | 85.33%  |
| Proprietary | 11        | 14.67%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 59        | 75.64%  |
| 0.01-0.5   | 7         | 8.97%   |
| 1.01-2.0   | 4         | 5.13%   |
| 0.51-1.0   | 4         | 5.13%   |
| 7.01-8.0   | 1         | 1.28%   |
| 5.01-6.0   | 1         | 1.28%   |
| 3.01-4.0   | 1         | 1.28%   |
| 8.01-16.0  | 1         | 1.28%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| BOE                 | 14        | 21.21%  |
| AU Optronics        | 13        | 19.7%   |
| LG Display          | 10        | 15.15%  |
| Chimei Innolux      | 5         | 7.58%   |
| Hewlett-Packard     | 4         | 6.06%   |
| Philips             | 3         | 4.55%   |
| Sharp               | 2         | 3.03%   |
| InfoVision          | 2         | 3.03%   |
| Apple               | 2         | 3.03%   |
| ViewSonic           | 1         | 1.52%   |
| SDC                 | 1         | 1.52%   |
| Samsung Electronics | 1         | 1.52%   |
| PANDA               | 1         | 1.52%   |
| LGD                 | 1         | 1.52%   |
| Lenovo              | 1         | 1.52%   |
| Iiyama              | 1         | 1.52%   |
| HKC                 | 1         | 1.52%   |
| HJW                 | 1         | 1.52%   |
| Dell                | 1         | 1.52%   |
| CSO                 | 1         | 1.52%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0258 1600x900 350x190mm 15.7-inch          | 3         | 4.48%   |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                | 3         | 4.48%   |
| Philips 271P4 PHL08C3 1920x1080 600x340mm 27.2-inch                  | 2         | 2.99%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch         | 2         | 2.99%   |
| ViewSonic VG2439 Series VSCD22B 1920x1080 520x290mm 23.4-inch        | 1         | 1.49%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 380x210mm 17.1-inch              | 1         | 1.49%   |
| Sharp LCD Monitor SHP14B9 3840x2160 340x190mm 15.3-inch              | 1         | 1.49%   |
| SDC LCD Monitor 3520x1080                                            | 1         | 1.49%   |
| Samsung Electronics LCD Monitor SDC3754 1600x900 380x210mm 17.1-inch | 1         | 1.49%   |
| Philips LCD Monitor 271P4 3520x1080                                  | 1         | 1.49%   |
| Philips LCD Monitor 271P4                                            | 1         | 1.49%   |
| PANDA LCD Monitor NCP004F 1920x1080 310x170mm 13.9-inch              | 1         | 1.49%   |
| LGD LCD Monitor 1920x1080                                            | 1         | 1.49%   |
| LG Display LCD Monitor LGD062E 1920x1080 340x190mm 15.3-inch         | 1         | 1.49%   |
| LG Display LCD Monitor LGD060A 1920x1080 290x170mm 13.2-inch         | 1         | 1.49%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch         | 1         | 1.49%   |
| LG Display LCD Monitor LGD05F1 1920x1080 310x170mm 13.9-inch         | 1         | 1.49%   |
| LG Display LCD Monitor LGD033E 1366x768 310x170mm 13.9-inch          | 1         | 1.49%   |
| Lenovo LEN P44w-10 LEN61D5 3840x1200 1050x330mm 43.3-inch            | 1         | 1.49%   |
| InfoVision LCD Monitor IVO8544 1920x1080 290x170mm 13.2-inch         | 1         | 1.49%   |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch         | 1         | 1.49%   |
| Iiyama PL2474H IVM6146 1920x1080 520x290mm 23.4-inch                 | 1         | 1.49%   |
| HKC LCD Monitor HKC3D05 1920x1080 340x190mm 15.3-inch                | 1         | 1.49%   |
| HJW HDMI TO USB HJW0001 1920x1080 700x390mm 31.5-inch                | 1         | 1.49%   |
| Hewlett-Packard LCD Monitor LA2306 3520x1080                         | 1         | 1.49%   |
| Hewlett-Packard LA2405x HWP301F 1920x1200 520x320mm 24.0-inch        | 1         | 1.49%   |
| Hewlett-Packard LA2306 HWP2949 1920x1080 510x290mm 23.1-inch         | 1         | 1.49%   |
| Hewlett-Packard E242 HWP326E 1920x1200 520x320mm 24.0-inch           | 1         | 1.49%   |
| Dell U2718Q DELA0EC 3840x2160 610x350mm 27.7-inch                    | 1         | 1.49%   |
| CSO LCD Monitor CSO1500 3840x2160 340x190mm 15.3-inch                | 1         | 1.49%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 280x180mm 13.1-inch     | 1         | 1.49%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 340x190mm 15.3-inch     | 1         | 1.49%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 310x170mm 13.9-inch     | 1         | 1.49%   |
| Chimei Innolux LCD Monitor CMN1484 1600x900 310x170mm 13.9-inch      | 1         | 1.49%   |
| Chimei Innolux LCD Monitor CMN13A2 1920x1080 290x170mm 13.2-inch     | 1         | 1.49%   |
| BOE LCD Monitor BOE0982 3840x2160 310x170mm 13.9-inch                | 1         | 1.49%   |
| BOE LCD Monitor BOE0928 1920x1080 340x190mm 15.3-inch                | 1         | 1.49%   |
| BOE LCD Monitor BOE08D7 1920x1080 310x170mm 13.9-inch                | 1         | 1.49%   |
| BOE LCD Monitor BOE084D 1920x1080 340x190mm 15.3-inch                | 1         | 1.49%   |
| BOE LCD Monitor BOE0802 1920x1080 340x190mm 15.3-inch                | 1         | 1.49%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 37        | 57.81%  |
| 1600x900 (HD+)    | 6         | 9.38%   |
| 3840x2160 (4K)    | 5         | 7.81%   |
| 2256x1504         | 3         | 4.69%   |
| 1920x1200 (WUXGA) | 3         | 4.69%   |
| 1366x768 (WXGA)   | 3         | 4.69%   |
| 2560x1600         | 2         | 3.13%   |
| 3840x1200         | 1         | 1.56%   |
| 3520x1080         | 1         | 1.56%   |
| 2560x1440 (QHD)   | 1         | 1.56%   |
| 2160x1440         | 1         | 1.56%   |
| Unknown           | 1         | 1.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 25        | 39.06%  |
| 15      | 19        | 29.69%  |
| 27      | 3         | 4.69%   |
| 23      | 3         | 4.69%   |
| 17      | 3         | 4.69%   |
| 12      | 3         | 4.69%   |
| Unknown | 3         | 4.69%   |
| 24      | 2         | 3.13%   |
| 43      | 1         | 1.56%   |
| 31      | 1         | 1.56%   |
| 22      | 1         | 1.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 34        | 53.97%  |
| 201-300     | 13        | 20.63%  |
| 501-600     | 6         | 9.52%   |
| 351-400     | 3         | 4.76%   |
| Unknown     | 3         | 4.76%   |
| 601-700     | 2         | 3.17%   |
| 401-500     | 1         | 1.59%   |
| 1001-1500   | 1         | 1.59%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 45        | 77.59%  |
| 16/10   | 6         | 10.34%  |
| 3/2     | 3         | 5.17%   |
| Unknown | 3         | 5.17%   |
| 3.18    | 1         | 1.72%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 20        | 31.25%  |
| 91-100         | 16        | 25%     |
| 71-80          | 5         | 7.81%   |
| 201-250        | 4         | 6.25%   |
| 61-70          | 3         | 4.69%   |
| 301-350        | 3         | 4.69%   |
| 121-130        | 3         | 4.69%   |
| 101-110        | 3         | 4.69%   |
| Unknown        | 3         | 4.69%   |
| 251-300        | 2         | 3.13%   |
| 351-500        | 1         | 1.56%   |
| 501-1000       | 1         | 1.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 29        | 46.03%  |
| 161-240       | 12        | 19.05%  |
| 51-100        | 9         | 14.29%  |
| 101-120       | 6         | 9.52%   |
| More than 240 | 4         | 6.35%   |
| Unknown       | 3         | 4.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 49        | 62.03%  |
| 0     | 21        | 26.58%  |
| 2     | 8         | 10.13%  |
| 3     | 1         | 1.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 59        | 44.7%   |
| Realtek Semiconductor | 38        | 28.79%  |
| TP-Link               | 6         | 4.55%   |
| Qualcomm Atheros      | 6         | 4.55%   |
| Broadcom              | 5         | 3.79%   |
| Hewlett-Packard       | 4         | 3.03%   |
| D-Link System         | 3         | 2.27%   |
| Ralink Technology     | 2         | 1.52%   |
| MediaTek              | 2         | 1.52%   |
| Edimax Technology     | 2         | 1.52%   |
| Xiaomi                | 1         | 0.76%   |
| Lenovo                | 1         | 0.76%   |
| Huawei Technologies   | 1         | 0.76%   |
| Google                | 1         | 0.76%   |
| BUFFALO               | 1         | 0.76%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 29        | 17.79%  |
| Intel Wi-Fi 6 AX200                                                        | 7         | 4.29%   |
| Intel Wireless-AC 9260                                                     | 6         | 3.68%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                          | 6         | 3.68%   |
| Intel Comet Lake PCH CNVi WiFi                                             | 6         | 3.68%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 6         | 3.68%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 6         | 3.68%   |
| Intel Wireless 8265 / 8275                                                 | 5         | 3.07%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                     | 5         | 3.07%   |
| Intel Wi-Fi 6 AX201                                                        | 5         | 3.07%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 4         | 2.45%   |
| HP hs2350 HSPA+ Mobile Broadband Module Network Adapter                    | 4         | 2.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 3         | 1.84%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 3         | 1.84%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 3         | 1.84%   |
| Intel Wireless 7265                                                        | 3         | 1.84%   |
| Intel Ethernet Connection (4) I219-LM                                      | 3         | 1.84%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 3         | 1.84%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 2         | 1.23%   |
| Ralink MT7601U Wireless Adapter                                            | 2         | 1.23%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 2         | 1.23%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter              | 2         | 1.23%   |
| Intel Wireless 7260                                                        | 2         | 1.23%   |
| Intel Ethernet Connection (10) I219-V                                      | 2         | 1.23%   |
| Intel Alder Lake-P PCH CNVi WiFi                                           | 2         | 1.23%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 1         | 0.61%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                | 1         | 0.61%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]        | 1         | 0.61%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                         | 1         | 0.61%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                | 1         | 0.61%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                   | 1         | 0.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 0.61%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                     | 1         | 0.61%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 1         | 0.61%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.61%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 1         | 0.61%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                           | 1         | 0.61%   |
| Intel Wireless 8260                                                        | 1         | 0.61%   |
| Intel Wi-Fi 6 AX201 160MHz                                                 | 1         | 0.61%   |
| Intel Tiger Lake PCH CNVi WiFi                                             | 1         | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 59        | 62.77%  |
| Realtek Semiconductor | 9         | 9.57%   |
| TP-Link               | 6         | 6.38%   |
| Qualcomm Atheros      | 5         | 5.32%   |
| Broadcom              | 5         | 5.32%   |
| D-Link System         | 3         | 3.19%   |
| Ralink Technology     | 2         | 2.13%   |
| MediaTek              | 2         | 2.13%   |
| Edimax Technology     | 2         | 2.13%   |
| BUFFALO               | 1         | 1.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                        | 7         | 7.45%   |
| Intel Wireless-AC 9260                                                     | 6         | 6.38%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                          | 6         | 6.38%   |
| Intel Comet Lake PCH CNVi WiFi                                             | 6         | 6.38%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 6         | 6.38%   |
| Intel Wireless 8265 / 8275                                                 | 5         | 5.32%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                     | 5         | 5.32%   |
| Intel Wi-Fi 6 AX201                                                        | 5         | 5.32%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 4         | 4.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 3         | 3.19%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 3         | 3.19%   |
| Intel Wireless 7265                                                        | 3         | 3.19%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 3         | 3.19%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 2         | 2.13%   |
| Ralink MT7601U Wireless Adapter                                            | 2         | 2.13%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 2         | 2.13%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter              | 2         | 2.13%   |
| Intel Wireless 7260                                                        | 2         | 2.13%   |
| Intel Alder Lake-P PCH CNVi WiFi                                           | 2         | 2.13%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                | 1         | 1.06%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]        | 1         | 1.06%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                         | 1         | 1.06%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                   | 1         | 1.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 1.06%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                     | 1         | 1.06%   |
| Intel Wireless 8260                                                        | 1         | 1.06%   |
| Intel Wi-Fi 6 AX201 160MHz                                                 | 1         | 1.06%   |
| Intel Tiger Lake PCH CNVi WiFi                                             | 1         | 1.06%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                  | 1         | 1.06%   |
| Intel Centrino Advanced-N 6235                                             | 1         | 1.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 1         | 1.06%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]             | 1         | 1.06%   |
| Edimax EW-7711MAC 802.11ac Wireless Adapter                                | 1         | 1.06%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]                   | 1         | 1.06%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                | 1         | 1.06%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter               | 1         | 1.06%   |
| Broadcom BCM4331 802.11a/b/g/n                                             | 1         | 1.06%   |
| Broadcom BCM43224 802.11a/b/g/n                                            | 1         | 1.06%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                        | 1         | 1.06%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 33        | 52.38%  |
| Intel                 | 23        | 36.51%  |
| Qualcomm Atheros      | 2         | 3.17%   |
| Xiaomi                | 1         | 1.59%   |
| Lenovo                | 1         | 1.59%   |
| Huawei Technologies   | 1         | 1.59%   |
| Google                | 1         | 1.59%   |
| Broadcom              | 1         | 1.59%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 29        | 46.03%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 9.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 4.76%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 4.76%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 3.17%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.59%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.59%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.59%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.59%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                  | 1         | 1.59%   |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller               | 1         | 1.59%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.59%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.59%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.59%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.59%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 1.59%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.59%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.59%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 1.59%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 1.59%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.59%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 1.59%   |
| Huawei USB Device                                                 | 1         | 1.59%   |
| Google Nexus/Pixel Device (charging + debug)                      | 1         | 1.59%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.59%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 75        | 53.57%  |
| Ethernet | 59        | 42.14%  |
| Modem    | 5         | 3.57%   |
| Unknown  | 1         | 0.71%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 46        | 50.55%  |
| Ethernet | 42        | 46.15%  |
| Modem    | 3         | 3.3%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 56        | 74.67%  |
| 1     | 17        | 22.67%  |
| 3     | 2         | 2.67%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 66        | 81.48%  |
| Yes  | 15        | 18.52%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 45        | 73.77%  |
| IMC Networks                    | 4         | 6.56%   |
| Apple                           | 4         | 6.56%   |
| Realtek Semiconductor           | 2         | 3.28%   |
| Qualcomm Atheros Communications | 2         | 3.28%   |
| Broadcom                        | 2         | 3.28%   |
| Skylight Digital                | 1         | 1.64%   |
| Opticis                         | 1         | 1.64%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                          | 16        | 26.23%  |
| Intel Bluetooth wireless interface             | 8         | 13.11%  |
| Intel AX200 Bluetooth                          | 7         | 11.48%  |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 5         | 8.2%    |
| Intel AX210 Bluetooth                          | 4         | 6.56%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 3         | 4.92%   |
| Apple Bluetooth Host Controller                | 3         | 4.92%   |
| Realtek Bluetooth Adapter                      | 2         | 3.28%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0         | 2         | 3.28%   |
| IMC Networks Realtek Bluetooth Adapter         | 2         | 3.28%   |
| Skylight Digital Realtek Bluetooth Adapter     | 1         | 1.64%   |
| Opticis Realtek Bluetooth Adapter              | 1         | 1.64%   |
| Intel Centrino Bluetooth Wireless Transceiver  | 1         | 1.64%   |
| Intel AX211 Bluetooth                          | 1         | 1.64%   |
| IMC Networks MediaTek Bluetooth Adapter        | 1         | 1.64%   |
| IMC Networks Bluetooth module                  | 1         | 1.64%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 1         | 1.64%   |
| Broadcom BCM2035 Bluetooth dongle              | 1         | 1.64%   |
| Apple Built-in Bluetooth 2.0+EDR HCI           | 1         | 1.64%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 54        | 50.94%  |
| AMD                    | 27        | 25.47%  |
| Nvidia                 | 15        | 14.15%  |
| Lenovo                 | 3         | 2.83%   |
| CMX Systems            | 2         | 1.89%   |
| Texas Instruments      | 1         | 0.94%   |
| SteelSeries ApS        | 1         | 0.94%   |
| Logitech               | 1         | 0.94%   |
| Generalplus Technology | 1         | 0.94%   |
| C-Media Electronics    | 1         | 0.94%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                              | 20        | 15.27%  |
| AMD Renoir Radeon High Definition Audio Controller                  | 10        | 7.63%   |
| Intel Comet Lake PCH cAVS                                           | 8         | 6.11%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 8         | 6.11%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 7         | 5.34%   |
| Intel Sunrise Point-LP HD Audio                                     | 7         | 5.34%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 7         | 5.34%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller      | 6         | 4.58%   |
| Intel Comet Lake PCH-LP cAVS                                        | 6         | 4.58%   |
| Intel Cannon Lake PCH cAVS                                          | 3         | 2.29%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]           | 3         | 2.29%   |
| AMD Rembrandt Radeon High Definition Audio Controller               | 3         | 2.29%   |
| Nvidia TU116 High Definition Audio Controller                       | 2         | 1.53%   |
| Nvidia GK107 HDMI Audio Controller                                  | 2         | 1.53%   |
| Intel Wildcat Point-LP High Definition Audio Controller             | 2         | 1.53%   |
| Intel Tiger Lake-H HD Audio Controller                              | 2         | 1.53%   |
| Intel CM238 HD Audio Controller                                     | 2         | 1.53%   |
| Intel Broadwell-U Audio Controller                                  | 2         | 1.53%   |
| Intel Alder Lake PCH-P High Definition Audio Controller             | 2         | 1.53%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 2         | 1.53%   |
| CMX Systems USB PnP Audio Device                                    | 2         | 1.53%   |
| AMD Navi 10 HDMI Audio                                              | 2         | 1.53%   |
| Unknown                                                             | 2         | 1.53%   |
| Texas Instruments PCM2706 stereo audio DAC                          | 1         | 0.76%   |
| SteelSeries ApS SteelSeries Siberia 350                             | 1         | 0.76%   |
| Nvidia TU104 HD Audio Controller                                    | 1         | 0.76%   |
| Nvidia GP107GL High Definition Audio Controller                     | 1         | 0.76%   |
| Nvidia GA104 High Definition Audio Controller                       | 1         | 0.76%   |
| Logitech Yeti Nano HIDpp                                            | 1         | 0.76%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                            | 1         | 0.76%   |
| Lenovo ThinkPad Dock Audio                                          | 1         | 0.76%   |
| Lenovo Realtek USB Audio                                            | 1         | 0.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 1         | 0.76%   |
| Intel Jasper Lake HD Audio                                          | 1         | 0.76%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller           | 1         | 0.76%   |
| Intel Haswell-ULT HD Audio Controller                               | 1         | 0.76%   |
| Intel Cannon Point-LP High Definition Audio Controller              | 1         | 0.76%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller   | 1         | 0.76%   |
| Intel 8 Series HD Audio Controller                                  | 1         | 0.76%   |
| Generalplus Technology USB Audio Device                             | 1         | 0.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 26        | 29.21%  |
| SK hynix            | 16        | 17.98%  |
| Micron Technology   | 13        | 14.61%  |
| Kingston            | 8         | 8.99%   |
| Crucial             | 6         | 6.74%   |
| Unknown             | 4         | 4.49%   |
| Ramaxel Technology  | 3         | 3.37%   |
| Unknown             | 2         | 2.25%   |
| Smart               | 2         | 2.25%   |
| Team                | 1         | 1.12%   |
| PNY                 | 1         | 1.12%   |
| Neo Forza           | 1         | 1.12%   |
| GOODRAM             | 1         | 1.12%   |
| Gold Key            | 1         | 1.12%   |
| G.Skill             | 1         | 1.12%   |
| Elpida              | 1         | 1.12%   |
| A-DATA Technology   | 1         | 1.12%   |
| 0B45000080CE        | 1         | 1.12%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s          | 4         | 4.44%   |
| Unknown                                                        | 4         | 4.44%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s         | 3         | 3.33%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 2         | 2.22%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s         | 2         | 2.22%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s          | 2         | 2.22%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s          | 2         | 2.22%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s           | 2         | 2.22%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s           | 2         | 2.22%   |
| Crucial RAM BL32G32C16S4B.M16FB1 32GB SODIMM DDR4 2667MT/s     | 2         | 2.22%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                    | 1         | 1.11%   |
| Unknown RAM Module 1GB SODIMM DDR                              | 1         | 1.11%   |
| Team RAM TEAMGROUP-SD4-3200 32GB SODIMM DDR4 3200MT/s          | 1         | 1.11%   |
| Smart RAM SF4641G8CK8IWGKSEG 8GB SODIMM DDR4 2133MT/s          | 1         | 1.11%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s          | 1         | 1.11%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1867MT/s                   | 1         | 1.11%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                   | 1         | 1.11%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s         | 1         | 1.11%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s         | 1         | 1.11%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s        | 1         | 1.11%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s        | 1         | 1.11%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 1         | 1.11%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s         | 1         | 1.11%   |
| SK hynix RAM HCNNNCRMBLPR-NEE 2GB Row Of Chips LPDDR4 4267MT/s | 1         | 1.11%   |
| Samsung RAM Module 4GB SODIMM DDR4 3200MT/s                    | 1         | 1.11%   |
| Samsung RAM M474A4G43AB1-CVF 32GB SODIMM DDR4 2933MT/s         | 1         | 1.11%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s          | 1         | 1.11%   |
| Samsung RAM M471B5674-M0-YK0 4GB Chip DDR3 1600MT/s            | 1         | 1.11%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 1         | 1.11%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s          | 1         | 1.11%   |
| Samsung RAM M471A5244BB0-CWE 4GB SODIMM DDR4 3200MT/s          | 1         | 1.11%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s         | 1         | 1.11%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s         | 1         | 1.11%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2400MT/s         | 1         | 1.11%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s         | 1         | 1.11%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s         | 1         | 1.11%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s          | 1         | 1.11%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s          | 1         | 1.11%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s    | 1         | 1.11%   |
| Samsung RAM K4UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s   | 1         | 1.11%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 54        | 70.13%  |
| DDR3   | 13        | 16.88%  |
| LPDDR5 | 3         | 3.9%    |
| LPDDR4 | 3         | 3.9%    |
| LPDDR3 | 2         | 2.6%    |
| DDR5   | 1         | 1.3%    |
| DDR    | 1         | 1.3%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 68        | 88.31%  |
| Row Of Chips | 8         | 10.39%  |
| Chip         | 1         | 1.3%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 31        | 38.27%  |
| 16384 | 22        | 27.16%  |
| 4096  | 16        | 19.75%  |
| 32768 | 7         | 8.64%   |
| 2048  | 4         | 4.94%   |
| 1024  | 1         | 1.23%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 26        | 32.5%   |
| 2667    | 18        | 22.5%   |
| 2400    | 8         | 10%     |
| 1600    | 7         | 8.75%   |
| 1867    | 6         | 7.5%    |
| 4267    | 3         | 3.75%   |
| 2133    | 3         | 3.75%   |
| 4266    | 2         | 2.5%    |
| 2933    | 2         | 2.5%    |
| 6400    | 1         | 1.25%   |
| 4800    | 1         | 1.25%   |
| 1334    | 1         | 1.25%   |
| 1333    | 1         | 1.25%   |
| Unknown | 1         | 1.25%   |

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
| Chicony Electronics                    | 17        | 24.64%  |
| IMC Networks                           | 12        | 17.39%  |
| Realtek Semiconductor                  | 8         | 11.59%  |
| Microdia                               | 6         | 8.7%    |
| Lite-On Technology                     | 5         | 7.25%   |
| Bison Electronics                      | 5         | 7.25%   |
| Sunplus Innovation Technology          | 3         | 4.35%   |
| Logitech                               | 3         | 4.35%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 4.35%   |
| Syntek                                 | 2         | 2.9%    |
| Shenzhen Kingcome Optoelectronic       | 2         | 2.9%    |
| Apple                                  | 2         | 2.9%    |
| Luxvisions Innotech Limited            | 1         | 1.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                             | 9         | 12.86%  |
| Chicony Integrated Camera                                                  | 8         | 11.43%  |
| Lite-On Integrated Camera                                                  | 3         | 4.29%   |
| Chicony Integrated HP HD Webcam                                            | 3         | 4.29%   |
| Bison Integrated Camera                                                    | 3         | 4.29%   |
| Sunplus Integrated_Webcam_HD                                               | 2         | 2.86%   |
| Realtek USB 2.0 Webcam                                                     | 2         | 2.86%   |
| Realtek Laptop Camera                                                      | 2         | 2.86%   |
| Microdia USB Camera                                                        | 2         | 2.86%   |
| Microdia Integrated Webcam                                                 | 2         | 2.86%   |
| Logitech Webcam C270                                                       | 2         | 2.86%   |
| Lite-On HP HD Camera                                                       | 2         | 2.86%   |
| IMC Networks Realtek PC Camera                                             | 2         | 2.86%   |
| Chicony ThinkPad T490 Webcam                                               | 2         | 2.86%   |
| Bison HD Webcam                                                            | 2         | 2.86%   |
| Apple FaceTime HD Camera (Built-in)                                        | 2         | 2.86%   |
| Syntek Lenovo EasyCamera                                                   | 1         | 1.43%   |
| Syntek Integrated Camera                                                   | 1         | 1.43%   |
| Sunplus hama C-600 Pro Webcam                                              | 1         | 1.43%   |
| Shenzhen Kingcome Optoelectronic XiaoMi USB 2.0 Webcam                     | 1         | 1.43%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera                            | 1         | 1.43%   |
| Realtek USB 2.0 PC Camera                                                  | 1         | 1.43%   |
| Realtek Integrated_Webcam_HD                                               | 1         | 1.43%   |
| Realtek Integrated Webcam                                                  | 1         | 1.43%   |
| Realtek Composite Webcam                                                   | 1         | 1.43%   |
| Microdia Integrated_Webcam_FHD                                             | 1         | 1.43%   |
| Microdia Dell Integrated HD Webcam                                         | 1         | 1.43%   |
| Luxvisions Innotech Limited HP HD Camera                                   | 1         | 1.43%   |
| Logitech HD Pro Webcam C920                                                | 1         | 1.43%   |
| IMC Networks EasyCamera                                                    | 1         | 1.43%   |
| Chicony USB2.0 0.3M UVC WebCam                                             | 1         | 1.43%   |
| Chicony Integrated IR Camera                                               | 1         | 1.43%   |
| Chicony HP Universal Camera                                                | 1         | 1.43%   |
| Chicony HD Webcam                                                          | 1         | 1.43%   |
| Chicony Chicony USB2.0 Camera                                              | 1         | 1.43%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 1.43%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed]                | 1         | 1.43%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam   | 1         | 1.43%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 11        | 42.31%  |
| Validity Sensors           | 5         | 19.23%  |
| Shenzhen Goodix Technology | 5         | 19.23%  |
| FocalTech Systems          | 3         | 11.54%  |
| Elan Microelectronics      | 1         | 3.85%   |
| AuthenTec                  | 1         | 3.85%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 7         | 26.92%  |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 15.38%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 7.69%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 7.69%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 7.69%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 7.69%   |
| FocalTech Systems Fingerprint Reader                                       | 2         | 7.69%   |
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

![Unsupported Devices](./images/pie_chart_bsd/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 31        | 37.8%   |
| 1     | 15        | 18.29%  |
| 4     | 14        | 17.07%  |
| 3     | 14        | 17.07%  |
| 5     | 4         | 4.88%   |
| 0     | 3         | 3.66%   |
| 9     | 1         | 1.22%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 59        | 35.33%  |
| Bluetooth                | 35        | 20.96%  |
| Net/wireless             | 27        | 16.17%  |
| Fingerprint reader       | 25        | 14.97%  |
| Card reader              | 12        | 7.19%   |
| Firewire controller      | 3         | 1.8%    |
| Sound                    | 2         | 1.2%    |
| Net/ethernet             | 2         | 1.2%    |
| Network                  | 1         | 0.6%    |
| Modem                    | 1         | 0.6%    |

