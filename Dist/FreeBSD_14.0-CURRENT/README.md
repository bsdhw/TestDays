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

Total: 170

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
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
| ASUSTek       | PRIME H470M-PLUS            | Desktop     | [224614e9ab](https://bsd-hardware.info/?probe=224614e9ab) | May 10, 2022 |
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
| amd64 | 90        | 83.33%  |
| arm64 | 14        | 12.96%  |
| arm   | 2         | 1.85%   |
| riscv | 1         | 0.93%   |
| i386  | 1         | 0.93%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KDE5          | 28        | 24.78%  |
| Console       | 26        | 23.01%  |
| XFCE          | 14        | 12.39%  |
| MATE          | 9         | 7.96%   |
| TWM           | 6         | 5.31%   |
| GNOME         | 6         | 5.31%   |
| i3            | 5         | 4.42%   |
| Openbox       | 3         | 2.65%   |
| Cinnamon      | 3         | 2.65%   |
| LXQt          | 2         | 1.77%   |
| LXDE          | 2         | 1.77%   |
| Lumina        | 2         | 1.77%   |
| Xfwm4         | 1         | 0.88%   |
| spectrwm      | 1         | 0.88%   |
| Picom         | 1         | 0.88%   |
| GNUstep       | 1         | 0.88%   |
| Fluxbox       | 1         | 0.88%   |
| Enlightenment | 1         | 0.88%   |
| ctwm          | 1         | 0.88%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 79        | 70.54%  |
| Console | 31        | 27.68%  |
| Wayland | 2         | 1.79%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 50        | 45.05%  |
| SDDM    | 25        | 22.52%  |
| SLiM    | 14        | 12.61%  |
| GDM     | 11        | 9.91%   |
| XDM     | 7         | 6.31%   |
| LightDM | 3         | 2.7%    |
| Ly      | 1         | 0.9%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang             | Computers | Percent |
|------------------|-----------|---------|
| C                | 73        | 66.36%  |
| en_US            | 12        | 10.91%  |
| de_DE            | 5         | 4.55%   |
| Unknown          | 5         | 4.55%   |
| uk_UA            | 3         | 2.73%   |
| zh_CN            | 2         | 1.82%   |
| ru_RU            | 2         | 1.82%   |
| en_GB            | 2         | 1.82%   |
| sv_SE            | 1         | 0.91%   |
| pt_PT            | 1         | 0.91%   |
| pl_PL            | 1         | 0.91%   |
| it_IT.ISO8859-15 | 1         | 0.91%   |
| fr_FR            | 1         | 0.91%   |
| de_CH            | 1         | 0.91%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 96        | 88.89%  |
| BIOS | 12        | 11.11%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 78        | 72.22%  |
| Ufs  | 30        | 27.78%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 99        | 91.67%  |
| MBR  | 9         | 8.33%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 25        | 23.15%  |
| Dell                           | 12        | 11.11%  |
| ASUSTek Computer               | 11        | 10.19%  |
| Unknown                        | 11        | 10.19%  |
| Hewlett-Packard                | 9         | 8.33%   |
| Gigabyte Technology            | 7         | 6.48%   |
| MSI                            | 6         | 5.56%   |
| Raspberry Pi Foundation        | 4         | 3.7%    |
| ASRock                         | 3         | 2.78%   |
| Apple                          | 3         | 2.78%   |
| Intel                          | 2         | 1.85%   |
| Framework                      | 2         | 1.85%   |
| Beckhoff Automation            | 2         | 1.85%   |
| Valve                          | 1         | 0.93%   |
| System76                       | 1         | 0.93%   |
| pine64                         | 1         | 0.93%   |
| Notebook                       | 1         | 0.93%   |
| Matsushita Electric Industrial | 1         | 0.93%   |
| khadas                         | 1         | 0.93%   |
| HUAWEI                         | 1         | 0.93%   |
| Google                         | 1         | 0.93%   |
| friendlyelec                   | 1         | 0.93%   |
| Avell High Performance         | 1         | 0.93%   |
| A-DATA Technology              | 1         | 0.93%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 12        | 11.11%  |
| RPi Raspberry Pi                            | 3         | 2.78%   |
| HP EliteBook 8570p                          | 3         | 2.78%   |
| Framework Laptop                            | 2         | 1.85%   |
| Valve Jupiter                               | 1         | 0.93%   |
| System76 Gazelle                            | 1         | 0.93%   |
| RPi rpi                                     | 1         | 0.93%   |
| pine64 pinebook-pro-rk3399                  | 1         | 0.93%   |
| Notebook NS50_70MU                          | 1         | 0.93%   |
| MSI MS-7C79                                 | 1         | 0.93%   |
| MSI MS-7C75                                 | 1         | 0.93%   |
| MSI MS-7B89                                 | 1         | 0.93%   |
| MSI MS-7B86                                 | 1         | 0.93%   |
| MSI GE76 Raider 10UG                        | 1         | 0.93%   |
| MSI Bravo 15 A4DDR                          | 1         | 0.93%   |
| Matsushita Electric Industrial CF-T2BW1AXR  | 1         | 0.93%   |
| Lenovo XiaoXinPro-13ARE 2020 82DM           | 1         | 0.93%   |
| Lenovo ThinkPad X395 20NL001SMX             | 1         | 0.93%   |
| Lenovo ThinkPad X395 20NL000GPG             | 1         | 0.93%   |
| Lenovo ThinkPad X270 20HM004JBR             | 1         | 0.93%   |
| Lenovo ThinkPad X260 20F5A28AUK             | 1         | 0.93%   |
| Lenovo ThinkPad X13 Gen 1 20T2003PRT        | 1         | 0.93%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TLA055CD | 1         | 0.93%   |
| Lenovo ThinkPad X1 Extreme 20MF000BUS       | 1         | 0.93%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS1QC00    | 1         | 0.93%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS0BT00    | 1         | 0.93%   |
| Lenovo ThinkPad T495s 20QKS1812F            | 1         | 0.93%   |
| Lenovo ThinkPad T495 20NJ0010PB             | 1         | 0.93%   |
| Lenovo ThinkPad T470p 20J7S0PM00            | 1         | 0.93%   |
| Lenovo ThinkPad T430 2349H2G                | 1         | 0.93%   |
| Lenovo ThinkPad T14s Gen 2i 20WM00B7MX      | 1         | 0.93%   |
| Lenovo ThinkPad P15 Gen 1 20ST005VRT        | 1         | 0.93%   |
| Lenovo ThinkPad P14s Gen 1 20Y1CTO1WW       | 1         | 0.93%   |
| Lenovo ThinkPad E14 Gen 3 20Y7003SGE        | 1         | 0.93%   |
| Lenovo ThinkPad E14 20RBCTO1WW              | 1         | 0.93%   |
| Lenovo ThinkBook 14 G3 ACL 21A2             | 1         | 0.93%   |
| Lenovo Legion 5P 15IMH05H 82AW              | 1         | 0.93%   |
| Lenovo Legion 5 15IMH05 82AU                | 1         | 0.93%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY        | 1         | 0.93%   |
| Lenovo IdeaPad 330-15ARR 81D2               | 1         | 0.93%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo ThinkPad                            | 18        | 16.67%  |
| Unknown                                    | 12        | 11.11%  |
| ASUS PRIME                                 | 5         | 4.63%   |
| HP EliteBook                               | 4         | 3.7%    |
| Dell Latitude                              | 4         | 3.7%    |
| RPi Raspberry                              | 3         | 2.78%   |
| HP ProBook                                 | 3         | 2.78%   |
| Dell OptiPlex                              | 3         | 2.78%   |
| Lenovo Legion                              | 2         | 1.85%   |
| Lenovo IdeaPad                             | 2         | 1.85%   |
| Gigabyte X570                              | 2         | 1.85%   |
| Gigabyte B450M                             | 2         | 1.85%   |
| Framework Laptop                           | 2         | 1.85%   |
| Valve Jupiter                              | 1         | 0.93%   |
| System76 Gazelle                           | 1         | 0.93%   |
| RPi rpi                                    | 1         | 0.93%   |
| pine64 pinebook-pro-rk3399                 | 1         | 0.93%   |
| Notebook NS50                              | 1         | 0.93%   |
| MSI MS-7C79                                | 1         | 0.93%   |
| MSI MS-7C75                                | 1         | 0.93%   |
| MSI MS-7B89                                | 1         | 0.93%   |
| MSI MS-7B86                                | 1         | 0.93%   |
| MSI GE76                                   | 1         | 0.93%   |
| MSI Bravo                                  | 1         | 0.93%   |
| Matsushita Electric Industrial CF-T2BW1AXR | 1         | 0.93%   |
| Lenovo XiaoXinPro-13ARE                    | 1         | 0.93%   |
| Lenovo ThinkBook                           | 1         | 0.93%   |
| khadas edge-v                              | 1         | 0.93%   |
| Intel S2600WTTR                            | 1         | 0.93%   |
| Intel NUC11PHi7                            | 1         | 0.93%   |
| HUAWEI HN-WX9X                             | 1         | 0.93%   |
| HP ZBook                                   | 1         | 0.93%   |
| HP EliteDesk                               | 1         | 0.93%   |
| Google Akemi                               | 1         | 0.93%   |
| Gigabyte X399                              | 1         | 0.93%   |
| Gigabyte B550I                             | 1         | 0.93%   |
| Gigabyte 970A-UD3P                         | 1         | 0.93%   |
| friendlyelec nanopi-m4                     | 1         | 0.93%   |
| Dell Vostro                                | 1         | 0.93%   |
| Dell PowerEdge                             | 1         | 0.93%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 27        | 25%     |
| 2020    | 26        | 24.07%  |
| 2019    | 14        | 12.96%  |
| Unknown | 11        | 10.19%  |
| 2018    | 7         | 6.48%   |
| 2022    | 6         | 5.56%   |
| 2017    | 4         | 3.7%    |
| 2013    | 4         | 3.7%    |
| 2015    | 3         | 2.78%   |
| 2016    | 2         | 1.85%   |
| 2014    | 1         | 0.93%   |
| 2012    | 1         | 0.93%   |
| 2011    | 1         | 0.93%   |
| 2003    | 1         | 0.93%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 58        | 53.7%   |
| Desktop        | 38        | 35.19%  |
| System on chip | 7         | 6.48%   |
| Mini pc        | 2         | 1.85%   |
| Server         | 2         | 1.85%   |
| All in one     | 1         | 0.93%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 106       | 98.15%  |
| Yes  | 2         | 1.85%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 39        | 35.45%  |
| 8.01-16.0       | 23        | 20.91%  |
| 32.01-64.0      | 17        | 15.45%  |
| 64.01-256.0     | 15        | 13.64%  |
| 4.01-8.0        | 9         | 8.18%   |
| 0.51-1.0        | 2         | 1.82%   |
| More than 256.0 | 1         | 0.91%   |
| 3.01-4.0        | 1         | 0.91%   |
| 24.01-32.0      | 1         | 0.91%   |
| 1.01-2.0        | 1         | 0.91%   |
| 0.01-0.5        | 1         | 0.91%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.51-1.0    | 34        | 30.63%  |
| 1.01-2.0    | 30        | 27.03%  |
| 0.01-0.5    | 21        | 18.92%  |
| 2.01-3.0    | 12        | 10.81%  |
| 3.01-4.0    | 5         | 4.5%    |
| 24.01-32.0  | 2         | 1.8%    |
| 0           | 2         | 1.8%    |
| 4.01-8.0    | 1         | 0.9%    |
| 32.01-64.0  | 1         | 0.9%    |
| 64.01-256.0 | 1         | 0.9%    |
| 16.01-24.0  | 1         | 0.9%    |
| 8.01-16.0   | 1         | 0.9%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 55        | 47.83%  |
| 2      | 29        | 25.22%  |
| 0      | 13        | 11.3%   |
| 3      | 7         | 6.09%   |
| 6      | 5         | 4.35%   |
| 4      | 3         | 2.61%   |
| 15     | 1         | 0.87%   |
| 7      | 1         | 0.87%   |
| 5      | 1         | 0.87%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 95        | 86.36%  |
| Yes       | 15        | 13.64%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 84        | 77.78%  |
| No        | 24        | 22.22%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 68.52%  |
| No        | 34        | 31.48%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 55        | 50.46%  |
| No        | 54        | 49.54%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 20        | 18.52%  |
| Germany      | 13        | 12.04%  |
| UK           | 11        | 10.19%  |
| Russia       | 11        | 10.19%  |
| Brazil       | 6         | 5.56%   |
| Poland       | 5         | 4.63%   |
| Ukraine      | 4         | 3.7%    |
| Japan        | 4         | 3.7%    |
| China        | 4         | 3.7%    |
| Austria      | 4         | 3.7%    |
| Portugal     | 3         | 2.78%   |
| Switzerland  | 2         | 1.85%   |
| Sweden       | 2         | 1.85%   |
| Romania      | 2         | 1.85%   |
| Netherlands  | 2         | 1.85%   |
| Denmark      | 2         | 1.85%   |
| Turkey       | 1         | 0.93%   |
| Spain        | 1         | 0.93%   |
| Singapore    | 1         | 0.93%   |
| Saudi Arabia | 1         | 0.93%   |
| Peru         | 1         | 0.93%   |
| Jamaica      | 1         | 0.93%   |
| Italy        | 1         | 0.93%   |
| India        | 1         | 0.93%   |
| France       | 1         | 0.93%   |
| Croatia      | 1         | 0.93%   |
| Colombia     | 1         | 0.93%   |
| Belarus      | 1         | 0.93%   |
| Bangladesh   | 1         | 0.93%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Moscow                      | 5         | 4.17%   |
| Brighton                    | 5         | 4.17%   |
| St Petersburg               | 3         | 2.5%    |
| Seattle                     | 3         | 2.5%    |
| London                      | 3         | 2.5%    |
| Kyiv                        | 3         | 2.5%    |
| ЕЊta-ku                   | 2         | 1.67%   |
| Zurich                      | 2         | 1.67%   |
| Vienna                      | 2         | 1.67%   |
| Rio de Janeiro              | 2         | 1.67%   |
| Rietberg                    | 2         | 1.67%   |
| Northeim                    | 2         | 1.67%   |
| Graz                        | 2         | 1.67%   |
| Fuchu                       | 2         | 1.67%   |
| Egham                       | 2         | 1.67%   |
| Chicago                     | 2         | 1.67%   |
| Cambridge                   | 2         | 1.67%   |
| Berlin                      | 2         | 1.67%   |
| Zaporizhzhya                | 1         | 0.83%   |
| Wuhan                       | 1         | 0.83%   |
| Woodburn                    | 1         | 0.83%   |
| Wieliczka                   | 1         | 0.83%   |
| Washington                  | 1         | 0.83%   |
| Warsaw                      | 1         | 0.83%   |
| Vila Real de Santo António | 1         | 0.83%   |
| Vancouver                   | 1         | 0.83%   |
| Tynda                       | 1         | 0.83%   |
| Trosa                       | 1         | 0.83%   |
| Thrissur                    | 1         | 0.83%   |
| Teaneck                     | 1         | 0.83%   |
| Stuttgart                   | 1         | 0.83%   |
| Sollentuna                  | 1         | 0.83%   |
| Slavonski Brod              | 1         | 0.83%   |
| Singapore                   | 1         | 0.83%   |
| Shanghai                    | 1         | 0.83%   |
| Setagaya-ku                 | 1         | 0.83%   |
| Satu Mare                   | 1         | 0.83%   |
| Santa Monica                | 1         | 0.83%   |
| San Francisco               | 1         | 0.83%   |
| Ruthin                      | 1         | 0.83%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 30        | 45     | 21.58%  |
| WDC                 | 27        | 44     | 19.42%  |
| Toshiba             | 12        | 23     | 8.63%   |
| Seagate             | 10        | 26     | 7.19%   |
| Crucial             | 8         | 17     | 5.76%   |
| Kingston            | 7         | 10     | 5.04%   |
| HGST                | 7         | 22     | 5.04%   |
| A-DATA Technology   | 6         | 6      | 4.32%   |
| SK hynix            | 5         | 5      | 3.6%    |
| Intel               | 5         | 8      | 3.6%    |
| KIOXIA              | 4         | 4      | 2.88%   |
| Apple               | 3         | 3      | 2.16%   |
| Micron Technology   | 2         | 3      | 1.44%   |
| SSSTC               | 1         | 1      | 0.72%   |
| SPCC                | 1         | 1      | 0.72%   |
| Solid State Storage | 1         | 1      | 0.72%   |
| Silicon Motion      | 1         | 1      | 0.72%   |
| SanDisk             | 1         | 2      | 0.72%   |
| PNY                 | 1         | 1      | 0.72%   |
| Mushkin             | 1         | 1      | 0.72%   |
| LSI                 | 1         | 4      | 0.72%   |
| LITEON              | 1         | 1      | 0.72%   |
| Hitachi             | 1         | 2      | 0.72%   |
| Goodram             | 1         | 1      | 0.72%   |
| Fujitsu             | 1         | 2      | 0.72%   |
| Apacer              | 1         | 1      | 0.72%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB             | 5         | 3.23%   |
| HGST HTS725050A7E630 500GB           | 4         | 2.58%   |
| WDC WDS100T3X0C-00SJG0 1TB           | 3         | 1.94%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 3         | 1.94%   |
| Toshiba MQ04ABF100 1TB               | 3         | 1.94%   |
| Samsung HM251JX 250GB                | 3         | 1.94%   |
| HGST HTS721010A9E630 1TB             | 3         | 1.94%   |
| WDC WDS100T1X0E-00AFY0 1TB           | 2         | 1.29%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB   | 2         | 1.29%   |
| WDC PC SN730 NVMe 1024GB             | 2         | 1.29%   |
| Seagate ST1000LM049-2GH172 1TB       | 2         | 1.29%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 1.29%   |
| Samsung SSD 970 EVO Plus 1TB         | 2         | 1.29%   |
| Samsung SSD 870 EVO 1TB              | 2         | 1.29%   |
| Samsung SSD 860 EVO 250GB            | 2         | 1.29%   |
| Samsung SSD 850 EVO 250GB            | 2         | 1.29%   |
| Samsung MZVLB512HBJQ-000L7 512GB     | 2         | 1.29%   |
| KIOXIA KBG40ZNS256G NVMe 256GB       | 2         | 1.29%   |
| Kingston SA2000M81000G 1TB           | 2         | 1.29%   |
| Apple SSD SM256E 256GB               | 2         | 1.29%   |
| WDC WDS500G1X0E-00AFY0 500GB         | 1         | 0.65%   |
| WDC WDS250G2B0C-00PXH0 250GB         | 1         | 0.65%   |
| WDC WDS100T2B0A-00SM50 1TB           | 1         | 0.65%   |
| WDC WD60EFRX-68TGBN1 6TB             | 1         | 0.65%   |
| WDC WD5002ABYS-18B1B0 500GB          | 1         | 0.65%   |
| WDC WD40EZRZ-75GXCB0 4TB             | 1         | 0.65%   |
| WDC WD30EFRX-68EUZN0 3TB             | 1         | 0.65%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 1         | 0.65%   |
| WDC WD20EFRX-68AX9N0 2TB             | 1         | 0.65%   |
| WDC WD120EFAX-68UNTN0 12TB           | 1         | 0.65%   |
| WDC WD10SPZX-60Z10T0 1TB             | 1         | 0.65%   |
| WDC WD10SPZX-21Z10T0 1TB             | 1         | 0.65%   |
| WDC WD10JPVX-00JC3T0 1TB             | 1         | 0.65%   |
| WDC WD10JMVW-11AJGS3 1TB             | 1         | 0.65%   |
| WDC WD10EZEX-60WN4A0 1TB             | 1         | 0.65%   |
| WDC WD10EZEX-00RKKA0 1TB             | 1         | 0.65%   |
| WDC WD10EARX-00N0YB0 1TB             | 1         | 0.65%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB | 1         | 0.65%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB | 1         | 0.65%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB | 1         | 0.65%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 11        | 22     | 24.44%  |
| WDC                 | 10        | 16     | 22.22%  |
| Seagate             | 10        | 26     | 22.22%  |
| HGST                | 7         | 22     | 15.56%  |
| Samsung Electronics | 4         | 7      | 8.89%   |
| LSI                 | 1         | 4      | 2.22%   |
| Hitachi             | 1         | 2      | 2.22%   |
| Fujitsu             | 1         | 2      | 2.22%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 16     | 30.56%  |
| Crucial             | 5         | 10     | 13.89%  |
| A-DATA Technology   | 4         | 4      | 11.11%  |
| Kingston            | 3         | 5      | 8.33%   |
| Intel               | 3         | 6      | 8.33%   |
| Apple               | 3         | 3      | 8.33%   |
| WDC                 | 1         | 2      | 2.78%   |
| SK hynix            | 1         | 1      | 2.78%   |
| SanDisk             | 1         | 2      | 2.78%   |
| Micron Technology   | 1         | 1      | 2.78%   |
| LITEON              | 1         | 1      | 2.78%   |
| Goodram             | 1         | 1      | 2.78%   |
| Apacer              | 1         | 1      | 2.78%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 56        | 81     | 45.53%  |
| SSD  | 35        | 53     | 28.46%  |
| HDD  | 32        | 101    | 26.02%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 57        | 154    | 50.44%  |
| NVMe | 56        | 81     | 49.56%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 36        | 70     | 47.37%  |
| 0.51-1.0   | 23        | 41     | 30.26%  |
| 1.01-2.0   | 5         | 6      | 6.58%   |
| 4.01-10.0  | 4         | 23     | 5.26%   |
| 3.01-4.0   | 3         | 4      | 3.95%   |
| 2.01-3.0   | 2         | 3      | 2.63%   |
| 10.01-20.0 | 2         | 3      | 2.63%   |
| 20.01-50.0 | 1         | 4      | 1.32%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 30        | 26.32%  |
| 251-500        | 25        | 21.93%  |
| 501-1000       | 18        | 15.79%  |
| 1-20           | 11        | 9.65%   |
| 51-100         | 10        | 8.77%   |
| 21-50          | 8         | 7.02%   |
| 1001-2000      | 5         | 4.39%   |
| 2001-3000      | 4         | 3.51%   |
| More than 3000 | 3         | 2.63%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 71        | 61.74%  |
| 21-50          | 27        | 23.48%  |
| 101-250        | 8         | 6.96%   |
| 1001-2000      | 2         | 1.74%   |
| 501-1000       | 2         | 1.74%   |
| 51-100         | 2         | 1.74%   |
| More than 3000 | 1         | 0.87%   |
| 251-500        | 1         | 0.87%   |
| 0              | 1         | 0.87%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                     | Computers | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| HGST HTS725050A7E630 500GB                | 4         | 7      | 26.67%  |
| Samsung Electronics SSD 870 EVO 1TB       | 2         | 4      | 13.33%  |
| WDC WD60EFRX-68TGBN1 6TB                  | 1         | 3      | 6.67%   |
| WDC WD5002ABYS-18B1B0 500GB               | 1         | 1      | 6.67%   |
| WDC WD10SPZX-60Z10T0 1TB                  | 1         | 1      | 6.67%   |
| Samsung Electronics SSD PM851 mSATA 256GB | 1         | 1      | 6.67%   |
| Samsung Electronics HM251JX 250GB         | 1         | 1      | 6.67%   |
| Kingston SA400S37120G 120GB               | 1         | 1      | 6.67%   |
| Hitachi HUA722020ALA331 2TB               | 1         | 2      | 6.67%   |
| HGST HTS721010A9E630 1TB                  | 1         | 10     | 6.67%   |
| Fujitsu MHS2040AT D 40GB                  | 1         | 2      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 6      | 28.57%  |
| HGST                | 4         | 17     | 28.57%  |
| WDC                 | 3         | 5      | 21.43%  |
| Kingston            | 1         | 1      | 7.14%   |
| Hitachi             | 1         | 2      | 7.14%   |
| Fujitsu             | 1         | 2      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 4         | 17     | 40%     |
| WDC                 | 3         | 5      | 30%     |
| Samsung Electronics | 1         | 1      | 10%     |
| Hitachi             | 1         | 2      | 10%     |
| Fujitsu             | 1         | 2      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 27     | 75%     |
| SSD  | 3         | 6      | 25%     |

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
| Works    | 90        | 195    | 84.91%  |
| Malfunc  | 12        | 33     | 11.32%  |
| Detected | 4         | 7      | 3.77%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 46        | 31.94%  |
| AMD                            | 27        | 18.75%  |
| Samsung Electronics            | 20        | 13.89%  |
| SanDisk                        | 18        | 12.5%   |
| Kingston Technology Company    | 5         | 3.47%   |
| SK hynix                       | 4         | 2.78%   |
| Silicon Motion                 | 4         | 2.78%   |
| Micron/Crucial Technology      | 3         | 2.08%   |
| KIOXIA                         | 3         | 2.08%   |
| Toshiba                        | 2         | 1.39%   |
| Solid State Storage Technology | 2         | 1.39%   |
| Micron Technology              | 2         | 1.39%   |
| Marvell Technology Group       | 2         | 1.39%   |
| ASMedia Technology             | 2         | 1.39%   |
| ADATA Technology               | 2         | 1.39%   |
| Phison Electronics             | 1         | 0.69%   |
| Broadcom / LSI                 | 1         | 0.69%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 19        | 12.1%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 13        | 8.28%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 11        | 7.01%   |
| Intel Comet Lake SATA AHCI Controller                                          | 9         | 5.73%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 4.46%   |
| AMD 400 Series Chipset SATA Controller                                         | 7         | 4.46%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 6         | 3.82%   |
| Unknown                                                                        | 6         | 3.82%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 4         | 2.55%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 4         | 2.55%   |
| AMD 500 Series Chipset SATA Controller                                         | 4         | 2.55%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 3         | 1.91%   |
| Samsung NVMe SSD Controller 980                                                | 3         | 1.91%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 3         | 1.91%   |
| Kingston Company A2000 NVMe SSD                                                | 3         | 1.91%   |
| Toshiba XG6 NVMe SSD Controller                                                | 2         | 1.27%   |
| SK hynix BC511                                                                 | 2         | 1.27%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 1.27%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 1.27%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 1.27%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 1.27%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2         | 1.27%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 1.27%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.27%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 2         | 1.27%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 2         | 1.27%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 1.27%   |
| SK hynix PC300 NVMe Solid State Drive 512GB                                    | 1         | 0.64%   |
| SanDisk PC SN530                                                               | 1         | 0.64%   |
| Samsung SM951 AHCI                                                             | 1         | 0.64%   |
| Phison E12 NVMe Controller                                                     | 1         | 0.64%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 1         | 0.64%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                          | 1         | 0.64%   |
| Marvell Group 88SE9170 PCIe 2.0 x1 2-port SATA 6 Gb/s Controller               | 1         | 0.64%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 1         | 0.64%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 0.64%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1         | 0.64%   |
| Intel SSD 660P Series                                                          | 1         | 0.64%   |
| Intel NVMe Optane Memory Series                                                | 1         | 0.64%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 1         | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 68        | 49.28%  |
| NVMe | 64        | 46.38%  |
| IDE  | 4         | 2.9%    |
| RAID | 2         | 1.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 56        | 50.91%  |
| AMD      | 36        | 32.73%  |
| ARM      | 9         | 8.18%   |
| Unknown  | 8         | 7.27%   |
| Research | 1         | 0.91%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
|                                                 | 8         | 7.27%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 6         | 5.45%   |
| Intel Core i5-10210U CPU @ 1.60GHz              | 5         | 4.55%   |
| Intel Core i7-3520M CPU @ 2.90GHz               | 4         | 3.64%   |
| ARM Cortex-A72 r0p3                             | 4         | 3.64%   |
| AMD Ryzen 5 5600G with Radeon Graphics          | 4         | 3.64%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 3         | 2.73%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 2         | 1.82%   |
| Intel Core i7-7600U CPU @ 2.80GHz               | 2         | 1.82%   |
| Intel Core i5-10500T CPU @ 2.30GHz              | 2         | 1.82%   |
| Intel Core i5-10300H CPU @ 2.50GHz              | 2         | 1.82%   |
| ARM Cortex-A72 r0p2                             | 2         | 1.82%   |
| ARM Cortex-A53 r0p4                             | 2         | 1.82%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 2         | 1.82%   |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx | 2         | 1.82%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 2         | 1.82%   |
| AMD Ryzen 7 4700U with Radeon Graphics          | 2         | 1.82%   |
| AMD Ryzen 5 PRO 3500U w/ Radeon Vega Mobile Gfx | 2         | 1.82%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 2         | 1.82%   |
| Research Morello SoC r0p0                       | 1         | 0.91%   |
| Intel Xeon W-10885M CPU @ 2.40GHz               | 1         | 0.91%   |
| Intel Xeon E-2334 CPU @ 3.40GHz                 | 1         | 0.91%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz             | 1         | 0.91%   |
| Intel Pentium M processor 1000MHz               | 1         | 0.91%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 1         | 0.91%   |
| Intel Core i7-8700 CPU @ 3.20GHz                | 1         | 0.91%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 0.91%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 0.91%   |
| Intel Core i7-5600U CPU @ 2.60GHz               | 1         | 0.91%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz              | 1         | 0.91%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz              | 1         | 0.91%   |
| Intel Core i7-4600U CPU @ 2.10GHz               | 1         | 0.91%   |
| Intel Core i7-3770 CPU @ 3.40GHz                | 1         | 0.91%   |
| Intel Core i7-3687U CPU @ 2.10GHz               | 1         | 0.91%   |
| Intel Core i7-3615QM CPU @ 2.30GHz              | 1         | 0.91%   |
| Intel Core i7-10870H CPU @ 2.20GHz              | 1         | 0.91%   |
| Intel Core i7-10700K CPU @ 3.80GHz              | 1         | 0.91%   |
| Intel Core i7-10700 CPU @ 2.90GHz               | 1         | 0.91%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz              | 1         | 0.91%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 1         | 0.91%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 27        | 24.77%  |
| Other                  | 20        | 18.35%  |
| Intel Core i5          | 14        | 12.84%  |
| AMD Ryzen 5            | 11        | 10.09%  |
| ARM Cortex             | 8         | 7.34%   |
| AMD Ryzen 7            | 8         | 7.34%   |
| AMD Ryzen 9            | 5         | 4.59%   |
| Intel Xeon             | 3         | 2.75%   |
| AMD Ryzen 7 PRO        | 3         | 2.75%   |
| AMD Ryzen 5 PRO        | 2         | 1.83%   |
| Intel Pentium M        | 1         | 0.92%   |
| Intel Atom             | 1         | 0.92%   |
| AMD Ryzen Threadripper | 1         | 0.92%   |
| AMD Ryzen Embedded     | 1         | 0.92%   |
| AMD Ryzen 3            | 1         | 0.92%   |
| AMD FX                 | 1         | 0.92%   |
| AMD E                  | 1         | 0.92%   |
| AMD Athlon             | 1         | 0.92%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 24        | 22.02%  |
| 8       | 18        | 16.51%  |
| Unknown | 17        | 15.6%   |
| 2       | 16        | 14.68%  |
| 6       | 11        | 10.09%  |
| 16      | 8         | 7.34%   |
| 12      | 8         | 7.34%   |
| 32      | 3         | 2.75%   |
| 24      | 3         | 2.75%   |
| 1       | 1         | 0.92%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 95        | 87.16%  |
| Unknown | 13        | 11.93%  |
| 2       | 1         | 0.92%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 54        | 49.54%  |
| 1       | 37        | 33.94%  |
| Unknown | 18        | 16.51%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 22.94%  |
| KabyLake   | 14        | 12.84%  |
| CometLake  | 12        | 11.01%  |
| Zen+       | 10        | 9.17%   |
| Zen 2      | 10        | 9.17%   |
| IvyBridge  | 9         | 8.26%   |
| Zen 3      | 7         | 6.42%   |
| TigerLake  | 6         | 5.5%    |
| Zen        | 4         | 3.67%   |
| Haswell    | 3         | 2.75%   |
| Broadwell  | 3         | 2.75%   |
| Skylake    | 1         | 0.92%   |
| Silvermont | 1         | 0.92%   |
| Piledriver | 1         | 0.92%   |
| P6         | 1         | 0.92%   |
| IceLake    | 1         | 0.92%   |
| Bobcat     | 1         | 0.92%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 47        | 40.52%  |
| Nvidia                     | 33        | 28.45%  |
| AMD                        | 33        | 28.45%  |
| Matrox Electronics Systems | 2         | 1.72%   |
| ASPEED Technology          | 1         | 0.86%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                           | 7         | 5.93%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series] | 7         | 5.93%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                            | 6         | 5.08%   |
| Intel CometLake-U GT2 [UHD Graphics]                                 | 6         | 5.08%   |
| Intel 3rd Gen Core processor Graphics Controller                     | 5         | 4.24%   |
| Intel CometLake-H GT2 [UHD Graphics]                                 | 4         | 3.39%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]         | 4         | 3.39%   |
| Nvidia TU117M                                                        | 3         | 2.54%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                             | 3         | 2.54%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                            | 3         | 2.54%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                             | 3         | 2.54%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]     | 3         | 2.54%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                           | 2         | 1.69%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                           | 2         | 1.69%   |
| Nvidia GP108M [GeForce MX230]                                        | 2         | 1.69%   |
| Nvidia GP108 [GeForce GT 1030]                                       | 2         | 1.69%   |
| Nvidia GK208B [GeForce GT 710]                                       | 2         | 1.69%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                 | 2         | 1.69%   |
| Intel HD Graphics 620                                                | 2         | 1.69%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller          | 2         | 1.69%   |
| AMD Lucienne                                                         | 2         | 1.69%   |
| Nvidia TU117M [GeForce MX450]                                        | 1         | 0.85%   |
| Nvidia TU116 [GeForce GTX 1660]                                      | 1         | 0.85%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                              | 1         | 0.85%   |
| Nvidia TU104GLM [Quadro RTX 5000 Mobile / Max-Q]                     | 1         | 0.85%   |
| Nvidia GT218 [GeForce 210]                                           | 1         | 0.85%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                           | 1         | 0.85%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                              | 1         | 0.85%   |
| Nvidia GP107GL [Quadro P620]                                         | 1         | 0.85%   |
| Nvidia GP107 [GeForce GTX 1050]                                      | 1         | 0.85%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                   | 1         | 0.85%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                  | 1         | 0.85%   |
| Nvidia GM206 [GeForce GTX 960]                                       | 1         | 0.85%   |
| Nvidia GM108M [GeForce MX130]                                        | 1         | 0.85%   |
| Nvidia GM108M [GeForce 940MX]                                        | 1         | 0.85%   |
| Nvidia GM107M [GeForce GTX 860M]                                     | 1         | 0.85%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                    | 1         | 0.85%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                          | 1         | 0.85%   |
| Nvidia GK107GLM [Quadro K1100M]                                      | 1         | 0.85%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                           | 1         | 0.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 28        | 25.45%  |
| 1 x Intel      | 26        | 23.64%  |
| Intel + Nvidia | 19        | 17.27%  |
| Other          | 16        | 14.55%  |
| 1 x Nvidia     | 14        | 12.73%  |
| 2 x AMD        | 2         | 1.82%   |
| 1 x Matrox     | 2         | 1.82%   |
| Intel + AMD    | 1         | 0.91%   |
| 1 x ASPEED     | 1         | 0.91%   |
| AMD + Nvidia   | 1         | 0.91%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 70        | 64.81%  |
| Proprietary | 22        | 20.37%  |
| Unknown     | 16        | 14.81%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 80        | 72.73%  |
| 1.01-2.0   | 11        | 10%     |
| 0.51-1.0   | 6         | 5.45%   |
| 0.01-0.5   | 5         | 4.55%   |
| 3.01-4.0   | 4         | 3.64%   |
| 5.01-6.0   | 2         | 1.82%   |
| 7.01-8.0   | 1         | 0.91%   |
| 2.01-3.0   | 1         | 0.91%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| BOE                 | 14        | 17.07%  |
| LG Display          | 10        | 12.2%   |
| AU Optronics        | 9         | 10.98%  |
| Dell                | 6         | 7.32%   |
| Goldstar            | 5         | 6.1%    |
| Philips             | 4         | 4.88%   |
| Hewlett-Packard     | 4         | 4.88%   |
| Chimei Innolux      | 4         | 4.88%   |
| Samsung Electronics | 3         | 3.66%   |
| RTK                 | 2         | 2.44%   |
| LG Electronics      | 2         | 2.44%   |
| Lenovo              | 2         | 2.44%   |
| InfoVision          | 2         | 2.44%   |
| Apple               | 2         | 2.44%   |
| ViewSonic           | 1         | 1.22%   |
| Sony                | 1         | 1.22%   |
| Sharp               | 1         | 1.22%   |
| SDC                 | 1         | 1.22%   |
| PANDA               | 1         | 1.22%   |
| LGD                 | 1         | 1.22%   |
| Iiyama              | 1         | 1.22%   |
| HJW                 | 1         | 1.22%   |
| Eizo                | 1         | 1.22%   |
| CSO                 | 1         | 1.22%   |
| BenQ                | 1         | 1.22%   |
| AOC                 | 1         | 1.22%   |
| Unknown             | 1         | 1.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0258 1600x900 350x190mm 15.7-inch            | 3         | 3.57%   |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                  | 3         | 3.57%   |
| RTK WCS Display RTK1A1B 1920x1080 344x195mm 15.6-inch                  | 2         | 2.38%   |
| Philips LCD Monitor PHL08C3 1920x1080 600x340mm 27.2-inch              | 2         | 2.38%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch           | 2         | 2.38%   |
| ViewSonic LCD Monitor VSCD22B 1920x1080 520x290mm 23.4-inch            | 1         | 1.19%   |
| Sony TV SNY4B03 1920x1080 930x520mm 41.9-inch                          | 1         | 1.19%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 380x210mm 17.1-inch                | 1         | 1.19%   |
| SDC LCD Monitor 3520x1080                                              | 1         | 1.19%   |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                       | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SDC3754 1600x900 380x210mm 17.1-inch   | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1020x570mm 46.0-inch | 1         | 1.19%   |
| Philips PHL 273V7 PHLC156 1920x1080 600x340mm 27.2-inch                | 1         | 1.19%   |
| Philips LCD Monitor 271P4 3520x1080                                    | 1         | 1.19%   |
| Philips LCD Monitor 271P4                                              | 1         | 1.19%   |
| PANDA LCD Monitor NCP004F 1920x1080 310x170mm 13.9-inch                | 1         | 1.19%   |
| LGD LCD Monitor 1920x1080                                              | 1         | 1.19%   |
| LG Electronics LCD Monitor LX20D 1600x1200                             | 1         | 1.19%   |
| LG Electronics LCD Monitor LG Ultra HD 11520x2160                      | 1         | 1.19%   |
| LG Electronics LCD Monitor LG Ultra HD                                 | 1         | 1.19%   |
| LG Display LCD Monitor LGD062E 1920x1080 340x190mm 15.3-inch           | 1         | 1.19%   |
| LG Display LCD Monitor LGD060A 1920x1080 290x170mm 13.2-inch           | 1         | 1.19%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch           | 1         | 1.19%   |
| LG Display LCD Monitor LGD05F1 1920x1080 310x170mm 13.9-inch           | 1         | 1.19%   |
| LG Display LCD Monitor LGD033E 1366x768 310x170mm 13.9-inch            | 1         | 1.19%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                  | 1         | 1.19%   |
| Lenovo LEN P44w-10 LEN61D5 3840x1200 1050x330mm 43.3-inch              | 1         | 1.19%   |
| InfoVision LCD Monitor IVO8544 1920x1080 290x170mm 13.2-inch           | 1         | 1.19%   |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch           | 1         | 1.19%   |
| Iiyama PL2474H IVM6146 1920x1080 520x290mm 23.4-inch                   | 1         | 1.19%   |
| HJW HDMI TO USB HJW0001 1920x1080 700x390mm 31.5-inch                  | 1         | 1.19%   |
| Hewlett-Packard LCD Monitor LA2306 3520x1080                           | 1         | 1.19%   |
| Hewlett-Packard LA2306 HWP2949 1920x1080 510x290mm 23.1-inch           | 1         | 1.19%   |
| Hewlett-Packard E242 HWP326E 1920x1200 520x320mm 24.0-inch             | 1         | 1.19%   |
| Hewlett-Packard E233 HPN345F 1920x1080 510x290mm 23.1-inch             | 1         | 1.19%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch             | 1         | 1.19%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch             | 1         | 1.19%   |
| Goldstar 27GL650F GSM5B71 1920x1080 530x300mm 24.0-inch                | 1         | 1.19%   |
| Goldstar 27GK750F GSM770F 1920x1080 600x340mm 27.2-inch                | 1         | 1.19%   |
| Goldstar 23EA53 GSM59A8 1920x1080 510x290mm 23.1-inch                  | 1         | 1.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 47        | 58.02%  |
| 3840x2160 (4K)    | 6         | 7.41%   |
| 1600x900 (HD+)    | 6         | 7.41%   |
| 1920x1200 (WUXGA) | 4         | 4.94%   |
| 2560x1440 (QHD)   | 3         | 3.7%    |
| 2256x1504         | 3         | 3.7%    |
| 1366x768 (WXGA)   | 3         | 3.7%    |
| 2560x1600         | 2         | 2.47%   |
| Unknown           | 2         | 2.47%   |
| 3840x1200         | 1         | 1.23%   |
| 3520x1080         | 1         | 1.23%   |
| 2160x1440         | 1         | 1.23%   |
| 1600x1200         | 1         | 1.23%   |
| 11520x2160        | 1         | 1.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 24        | 30%     |
| 15      | 16        | 20%     |
| Unknown | 8         | 10%     |
| 27      | 7         | 8.75%   |
| 24      | 6         | 7.5%    |
| 23      | 6         | 7.5%    |
| 17      | 3         | 3.75%   |
| 12      | 3         | 3.75%   |
| 46      | 1         | 1.25%   |
| 43      | 1         | 1.25%   |
| 41      | 1         | 1.25%   |
| 32      | 1         | 1.25%   |
| 31      | 1         | 1.25%   |
| 22      | 1         | 1.25%   |
| 21      | 1         | 1.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 30        | 37.97%  |
| 501-600     | 17        | 21.52%  |
| 201-300     | 13        | 16.46%  |
| Unknown     | 8         | 10.13%  |
| 351-400     | 3         | 3.8%    |
| 601-700     | 2         | 2.53%   |
| 401-500     | 2         | 2.53%   |
| 1001-1500   | 2         | 2.53%   |
| 701-800     | 1         | 1.27%   |
| 901-1000    | 1         | 1.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 55        | 75.34%  |
| 16/10   | 7         | 9.59%   |
| Unknown | 7         | 9.59%   |
| 3/2     | 3         | 4.11%   |
| 3.18    | 1         | 1.37%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 19        | 23.75%  |
| 91-100         | 11        | 13.75%  |
| 201-250        | 10        | 12.5%   |
| Unknown        | 8         | 10%     |
| 301-350        | 7         | 8.75%   |
| 71-80          | 5         | 6.25%   |
| 101-110        | 5         | 6.25%   |
| 251-300        | 4         | 5%      |
| 61-70          | 3         | 3.75%   |
| 121-130        | 3         | 3.75%   |
| 501-1000       | 3         | 3.75%   |
| 351-500        | 2         | 2.5%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 27        | 34.62%  |
| 51-100        | 19        | 24.36%  |
| 161-240       | 14        | 17.95%  |
| Unknown       | 8         | 10.26%  |
| 101-120       | 7         | 8.97%   |
| More than 240 | 2         | 2.56%   |
| 1-50          | 1         | 1.28%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 60        | 54.05%  |
| 0     | 41        | 36.94%  |
| 2     | 9         | 8.11%   |
| 3     | 1         | 0.9%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 73        | 45.91%  |
| Realtek Semiconductor           | 48        | 30.19%  |
| TP-Link                         | 6         | 3.77%   |
| Broadcom                        | 6         | 3.77%   |
| Ralink Technology               | 4         | 2.52%   |
| Qualcomm Atheros                | 4         | 2.52%   |
| Hewlett-Packard                 | 4         | 2.52%   |
| Edimax Technology               | 2         | 1.26%   |
| D-Link System                   | 2         | 1.26%   |
| Xiaomi                          | 1         | 0.63%   |
| Qualcomm Atheros Communications | 1         | 0.63%   |
| Mellanox Technologies           | 1         | 0.63%   |
| Lenovo                          | 1         | 0.63%   |
| Google                          | 1         | 0.63%   |
| Emulex                          | 1         | 0.63%   |
| BUFFALO                         | 1         | 0.63%   |
| ASUSTek Computer                | 1         | 0.63%   |
| Arduino SA                      | 1         | 0.63%   |
| Aquantia                        | 1         | 0.63%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 39        | 19.8%   |
| Intel Wi-Fi 6 AX200                                                        | 10        | 5.08%   |
| Intel Comet Lake PCH CNVi WiFi                                             | 7         | 3.55%   |
| Intel Wireless-AC 9260                                                     | 6         | 3.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                          | 6         | 3.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 6         | 3.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 6         | 3.05%   |
| Intel Wireless 8265 / 8275                                                 | 5         | 2.54%   |
| Intel I211 Gigabit Network Connection                                      | 5         | 2.54%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 4         | 2.03%   |
| Realtek RTL8125 2.5GbE Controller                                          | 4         | 2.03%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                     | 4         | 2.03%   |
| Intel Wi-Fi 6 AX201                                                        | 4         | 2.03%   |
| Intel I210 Gigabit Network Connection                                      | 4         | 2.03%   |
| Intel 82574L Gigabit Network Connection                                    | 4         | 2.03%   |
| HP hs2350 HSPA+ Mobile Broadband Module Network Adapter                    | 4         | 2.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 3         | 1.52%   |
| Intel Ethernet Controller I225-V                                           | 3         | 1.52%   |
| Intel Ethernet Connection (14) I219-LM                                     | 3         | 1.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 2         | 1.02%   |
| Ralink MT7601U Wireless Adapter                                            | 2         | 1.02%   |
| Intel Wireless 7265                                                        | 2         | 1.02%   |
| Intel Wireless 7260                                                        | 2         | 1.02%   |
| Intel Ethernet Connection (4) I219-LM                                      | 2         | 1.02%   |
| Intel Ethernet Connection (11) I219-LM                                     | 2         | 1.02%   |
| Intel Ethernet Connection (10) I219-V                                      | 2         | 1.02%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 2         | 1.02%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 2         | 1.02%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                       | 1         | 0.51%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                     | 1         | 0.51%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]        | 1         | 0.51%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                   | 1         | 0.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 0.51%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                     | 1         | 0.51%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 1         | 0.51%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 1         | 0.51%   |
| Ralink RT5370 Wireless Adapter                                             | 1         | 0.51%   |
| Ralink RT2870/RT3070 Wireless Adapter                                      | 1         | 0.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 1         | 0.51%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 1         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 59        | 64.13%  |
| Realtek Semiconductor           | 8         | 8.7%    |
| TP-Link                         | 6         | 6.52%   |
| Broadcom                        | 5         | 5.43%   |
| Ralink Technology               | 4         | 4.35%   |
| Qualcomm Atheros                | 3         | 3.26%   |
| Edimax Technology               | 2         | 2.17%   |
| D-Link System                   | 2         | 2.17%   |
| Qualcomm Atheros Communications | 1         | 1.09%   |
| BUFFALO                         | 1         | 1.09%   |
| ASUSTek Computer                | 1         | 1.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                           | 10        | 10.87%  |
| Intel Comet Lake PCH CNVi WiFi                                                | 7         | 7.61%   |
| Intel Wireless-AC 9260                                                        | 6         | 6.52%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 6         | 6.52%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 6         | 6.52%   |
| Intel Wireless 8265 / 8275                                                    | 5         | 5.43%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 4         | 4.35%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 4         | 4.35%   |
| Intel Wi-Fi 6 AX201                                                           | 4         | 4.35%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 3         | 3.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 2.17%   |
| Ralink MT7601U Wireless Adapter                                               | 2         | 2.17%   |
| Intel Wireless 7265                                                           | 2         | 2.17%   |
| Intel Wireless 7260                                                           | 2         | 2.17%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2         | 2.17%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]    | 2         | 2.17%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1         | 1.09%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]           | 1         | 1.09%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                      | 1         | 1.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.09%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                        | 1         | 1.09%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 1.09%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1         | 1.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1         | 1.09%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 1         | 1.09%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 1         | 1.09%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1         | 1.09%   |
| Intel Wireless 8260                                                           | 1         | 1.09%   |
| Intel Wi-Fi 6 AX201 160MHz                                                    | 1         | 1.09%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 1         | 1.09%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 1.09%   |
| Intel Centrino Advanced-N 6235                                                | 1         | 1.09%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                | 1         | 1.09%   |
| Edimax EW-7711MAC 802.11ac Wireless Adapter                                   | 1         | 1.09%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]                      | 1         | 1.09%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                   | 1         | 1.09%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 1         | 1.09%   |
| Broadcom BCM4331 802.11a/b/g/n                                                | 1         | 1.09%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 1         | 1.09%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 1         | 1.09%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 43        | 46.24%  |
| Intel                 | 42        | 45.16%  |
| Broadcom              | 2         | 2.15%   |
| Xiaomi                | 1         | 1.08%   |
| Qualcomm Atheros      | 1         | 1.08%   |
| Lenovo                | 1         | 1.08%   |
| Google                | 1         | 1.08%   |
| Emulex                | 1         | 1.08%   |
| Aquantia              | 1         | 1.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 39        | 40.21%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6         | 6.19%   |
| Intel I211 Gigabit Network Connection                                         | 5         | 5.15%   |
| Intel I210 Gigabit Network Connection                                         | 4         | 4.12%   |
| Intel 82574L Gigabit Network Connection                                       | 4         | 4.12%   |
| Realtek RTL8125 2.5GbE Controller                                             | 3         | 3.09%   |
| Intel Ethernet Controller I225-V                                              | 3         | 3.09%   |
| Intel Ethernet Connection (14) I219-LM                                        | 3         | 3.09%   |
| Intel Ethernet Connection (4) I219-LM                                         | 2         | 2.06%   |
| Intel Ethernet Connection (11) I219-LM                                        | 2         | 2.06%   |
| Intel Ethernet Connection (10) I219-V                                         | 2         | 2.06%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                          | 1         | 1.03%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1         | 1.03%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 1.03%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1         | 1.03%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                              | 1         | 1.03%   |
| Intel I350 Gigabit Network Connection                                         | 1         | 1.03%   |
| Intel Ethernet Controller I225-LM                                             | 1         | 1.03%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 1         | 1.03%   |
| Intel Ethernet Connection I219-LM                                             | 1         | 1.03%   |
| Intel Ethernet Connection I218-LM                                             | 1         | 1.03%   |
| Intel Ethernet Connection I217-LM                                             | 1         | 1.03%   |
| Intel Ethernet Connection (7) I219-V                                          | 1         | 1.03%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1         | 1.03%   |
| Intel Ethernet Connection (5) I219-V                                          | 1         | 1.03%   |
| Intel Ethernet Connection (3) I218-LM                                         | 1         | 1.03%   |
| Intel Ethernet Connection (13) I219-V                                         | 1         | 1.03%   |
| Intel Ethernet Connection (11) I219-V                                         | 1         | 1.03%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 1.03%   |
| Google Nexus/Pixel Device (charging + debug)                                  | 1         | 1.03%   |
| Emulex OneConnect 10Gb NIC (be3)                                              | 1         | 1.03%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                             | 1         | 1.03%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 1         | 1.03%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 1         | 1.03%   |
| Unknown                                                                       | 1         | 1.03%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 85        | 50.6%   |
| WiFi     | 75        | 44.64%  |
| Modem    | 6         | 3.57%   |
| Unknown  | 2         | 1.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 71        | 59.66%  |
| WiFi     | 45        | 37.82%  |
| Modem    | 3         | 2.52%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 59        | 54.63%  |
| 1     | 25        | 23.15%  |
| 0     | 14        | 12.96%  |
| 3     | 7         | 6.48%   |
| 4     | 2         | 1.85%   |
| 7     | 1         | 0.93%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 92        | 80.7%   |
| Yes  | 22        | 19.3%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 44        | 78.57%  |
| Apple                           | 4         | 7.14%   |
| Realtek Semiconductor           | 2         | 3.57%   |
| IMC Networks                    | 2         | 3.57%   |
| Realtek                         | 1         | 1.79%   |
| Qualcomm Atheros Communications | 1         | 1.79%   |
| Cambridge Silicon Radio         | 1         | 1.79%   |
| Broadcom                        | 1         | 1.79%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 15        | 26.79%  |
| Intel AX200 Bluetooth                               | 9         | 16.07%  |
| Intel Bluetooth wireless interface                  | 7         | 12.5%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 5         | 8.93%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 7.14%   |
| Intel AX210 Bluetooth                               | 3         | 5.36%   |
| Apple Bluetooth Host Controller                     | 2         | 3.57%   |
| Realtek  Bluetooth Adapter                          | 1         | 1.79%   |
| Realtek Bluetooth Radio                             | 1         | 1.79%   |
| Realtek Bluetooth Radio                             | 1         | 1.79%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.79%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.79%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.79%   |
| IMC Networks Bluetooth module                       | 1         | 1.79%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.79%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.79%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 1.79%   |
| Apple Apple Broadcom Built-in Bluetooth             | 1         | 1.79%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 54        | 40.6%   |
| AMD                     | 40        | 30.08%  |
| Nvidia                  | 27        | 20.3%   |
| Lenovo                  | 3         | 2.26%   |
| Yamaha                  | 1         | 0.75%   |
| SteelSeries ApS         | 1         | 0.75%   |
| Logitech                | 1         | 0.75%   |
| GN Netcom               | 1         | 0.75%   |
| Generalplus Technology  | 1         | 0.75%   |
| CMX Systems             | 1         | 0.75%   |
| C-Media Electronics     | 1         | 0.75%   |
| AudioQuest              | 1         | 0.75%   |
| AKAI  Professional M.I. | 1         | 0.75%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                  | 22        | 13.41%  |
| AMD Renoir Radeon High Definition Audio Controller                      | 11        | 6.71%   |
| Intel Comet Lake PCH cAVS                                               | 10        | 6.1%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                     | 10        | 6.1%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller     | 9         | 5.49%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller             | 6         | 3.66%   |
| Intel Comet Lake PCH-LP cAVS                                            | 6         | 3.66%   |
| AMD Starship/Matisse HD Audio Controller                                | 6         | 3.66%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller          | 5         | 3.05%   |
| Nvidia GP107GL High Definition Audio Controller                         | 5         | 3.05%   |
| Intel Cannon Lake PCH cAVS                                              | 4         | 2.44%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                     | 4         | 2.44%   |
| Nvidia TU116 High Definition Audio Controller                           | 3         | 1.83%   |
| Intel Tiger Lake-H HD Audio Controller                                  | 3         | 1.83%   |
| Intel Sunrise Point-LP HD Audio                                         | 3         | 1.83%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]               | 3         | 1.83%   |
| Unknown                                                                 | 3         | 1.83%   |
| Nvidia GP108 High Definition Audio Controller                           | 2         | 1.22%   |
| Nvidia GK208 HDMI/DP Audio Controller                                   | 2         | 1.22%   |
| Nvidia GK107 HDMI Audio Controller                                      | 2         | 1.22%   |
| Intel Wildcat Point-LP High Definition Audio Controller                 | 2         | 1.22%   |
| Intel Broadwell-U Audio Controller                                      | 2         | 1.22%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller     | 2         | 1.22%   |
| AMD SBx00 Azalia (Intel HDA)                                            | 2         | 1.22%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 2         | 1.22%   |
| AMD Navi 10 HDMI Audio                                                  | 2         | 1.22%   |
| Yamaha Steinberg UR12                                                   | 1         | 0.61%   |
| SteelSeries ApS SteelSeries Siberia 350                                 | 1         | 0.61%   |
| Nvidia TU106 High Definition Audio Controller                           | 1         | 0.61%   |
| Nvidia TU104 HD Audio Controller                                        | 1         | 0.61%   |
| Nvidia High Definition Audio Controller                                 | 1         | 0.61%   |
| Nvidia GP106 High Definition Audio Controller                           | 1         | 0.61%   |
| Nvidia GM206 High Definition Audio Controller                           | 1         | 0.61%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]           | 1         | 0.61%   |
| Nvidia GA104 High Definition Audio Controller                           | 1         | 0.61%   |
| Logitech H390 headset with microphone                                   | 1         | 0.61%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                | 1         | 0.61%   |
| Lenovo ThinkPad Dock Audio                                              | 1         | 0.61%   |
| Lenovo Realtek USB Audio                                                | 1         | 0.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller        | 1         | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 21        | 20%     |
| SK hynix               | 15        | 14.29%  |
| Micron Technology      | 15        | 14.29%  |
| Kingston               | 11        | 10.48%  |
| Crucial                | 9         | 8.57%   |
| Unknown                | 5         | 4.76%   |
| Corsair                | 5         | 4.76%   |
| Smart                  | 3         | 2.86%   |
| Ramaxel Technology     | 3         | 2.86%   |
| Team                   | 2         | 1.9%    |
| Goodram                | 2         | 1.9%    |
| G.Skill                | 2         | 1.9%    |
| A-DATA Technology      | 2         | 1.9%    |
| Unknown                | 2         | 1.9%    |
| Unknown (000000000C01) | 1         | 0.95%   |
| Transcend              | 1         | 0.95%   |
| PNY                    | 1         | 0.95%   |
| Neo Forza              | 1         | 0.95%   |
| KLEVV                  | 1         | 0.95%   |
| Gold Key               | 1         | 0.95%   |
| Elpida                 | 1         | 0.95%   |
| 06F100000C01           | 1         | 0.95%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s      | 4         | 3.74%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s     | 2         | 1.87%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s     | 2         | 1.87%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s     | 2         | 1.87%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s    | 2         | 1.87%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s      | 2         | 1.87%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s      | 2         | 1.87%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s       | 2         | 1.87%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s       | 2         | 1.87%   |
| Crucial RAM BL32G32C16S4B.M16FB1 32GB SODIMM DDR4 2667MT/s | 2         | 1.87%   |
| Corsair RAM CMK32GX4M2D3200C16 16GB DIMM DDR4 3200MT/s     | 2         | 1.87%   |
| Unknown                                                    | 2         | 1.87%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                  | 1         | 0.93%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                | 1         | 0.93%   |
| Unknown RAM Module 1GB SODIMM DDR                          | 1         | 0.93%   |
| Unknown RAM 3000 C16 Series 4096MB DIMM DDR4 2933MT/s      | 1         | 0.93%   |
| Unknown RAM 2G-08-10-12-1333 2GB DIMM DDR3 1333MT/s        | 1         | 0.93%   |
| Unknown (000000000C01) RAM Module 32GB DIMM DDR4 3200MT/s  | 1         | 0.93%   |
| Transcend RAM JM2666HLE-32G 32GB DIMM DDR4 2666MT/s        | 1         | 0.93%   |
| Team RAM TEAMGROUP-UD4-4133 8GB DIMM DDR4 4133MT/s         | 1         | 0.93%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s      | 1         | 0.93%   |
| Smart RAM SF4641G8CK8IWGKSEG 8GB SODIMM DDR4 2133MT/s      | 1         | 0.93%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s      | 1         | 0.93%   |
| Smart RAM Module 8GB DIMM DDR4 2667MT/s                    | 1         | 0.93%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1867MT/s               | 1         | 0.93%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s               | 1         | 0.93%   |
| SK hynix RAM HMAA4GU6CJR8N-XN 32GB DIMM DDR4 3200MT/s      | 1         | 0.93%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s    | 1         | 0.93%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s     | 1         | 0.93%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s     | 1         | 0.93%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s     | 1         | 0.93%   |
| Samsung RAM M474A4G43AB1-CVF 32GB SODIMM DDR4 2933MT/s     | 1         | 0.93%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s      | 1         | 0.93%   |
| Samsung RAM M471B5674-M0-YK0 4GB Chip DDR3 1600MT/s        | 1         | 0.93%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s      | 1         | 0.93%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s      | 1         | 0.93%   |
| Samsung RAM M471A5244BB0-CWE 4GB SODIMM DDR4 3200MT/s      | 1         | 0.93%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s     | 1         | 0.93%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s     | 1         | 0.93%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s     | 1         | 0.93%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 72        | 77.42%  |
| DDR3   | 17        | 18.28%  |
| LPDDR5 | 1         | 1.08%   |
| LPDDR4 | 1         | 1.08%   |
| LPDDR3 | 1         | 1.08%   |
| DDR    | 1         | 1.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 61        | 65.59%  |
| DIMM         | 27        | 29.03%  |
| Row Of Chips | 4         | 4.3%    |
| Chip         | 1         | 1.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 38        | 39.58%  |
| 16384 | 28        | 29.17%  |
| 32768 | 14        | 14.58%  |
| 4096  | 12        | 12.5%   |
| 2048  | 3         | 3.13%   |
| 1024  | 1         | 1.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 34        | 35.05%  |
| 2667    | 21        | 21.65%  |
| 1600    | 9         | 9.28%   |
| 2400    | 6         | 6.19%   |
| 1867    | 6         | 6.19%   |
| 2666    | 4         | 4.12%   |
| 2933    | 3         | 3.09%   |
| 2133    | 3         | 3.09%   |
| 3600    | 2         | 2.06%   |
| 1333    | 2         | 2.06%   |
| 4267    | 1         | 1.03%   |
| 4266    | 1         | 1.03%   |
| 4133    | 1         | 1.03%   |
| 3000    | 1         | 1.03%   |
| 1866    | 1         | 1.03%   |
| 1334    | 1         | 1.03%   |
| Unknown | 1         | 1.03%   |

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
| Chicony Electronics                    | 15        | 23.44%  |
| IMC Networks                           | 10        | 15.63%  |
| Realtek Semiconductor                  | 6         | 9.38%   |
| Logitech                               | 6         | 9.38%   |
| Lite-On Technology                     | 5         | 7.81%   |
| Acer                                   | 5         | 7.81%   |
| Sunplus Innovation Technology          | 4         | 6.25%   |
| Microdia                               | 4         | 6.25%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 4.69%   |
| Syntek                                 | 2         | 3.13%   |
| Apple                                  | 2         | 3.13%   |
| GEMBIRD                                | 1         | 1.56%   |
| Aveo Technology                        | 1         | 1.56%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                             | 7         | 10.77%  |
| Chicony Integrated Camera                                                  | 7         | 10.77%  |
| Sunplus Integrated_Webcam_HD                                               | 3         | 4.62%   |
| Logitech Webcam C270                                                       | 3         | 4.62%   |
| Lite-On Integrated Camera                                                  | 3         | 4.62%   |
| Chicony Integrated HP HD Webcam                                            | 3         | 4.62%   |
| Acer Integrated Camera                                                     | 3         | 4.62%   |
| Realtek Laptop Camera                                                      | 2         | 3.08%   |
| Realtek Integrated_Webcam_HD                                               | 2         | 3.08%   |
| Microdia HP Integrated Webcam                                              | 2         | 3.08%   |
| Lite-On HP HD Camera                                                       | 2         | 3.08%   |
| Chicony ThinkPad T490 Webcam                                               | 2         | 3.08%   |
| Apple FaceTime HD Camera (Built-in)                                        | 2         | 3.08%   |
| Acer HD Webcam                                                             | 2         | 3.08%   |
| Syntek Lenovo EasyCamera                                                   | 1         | 1.54%   |
| Syntek Integrated Camera                                                   | 1         | 1.54%   |
| Sunplus Integrated_Webcam_FHD                                              | 1         | 1.54%   |
| Realtek USB 2 Webcam                                                       | 1         | 1.54%   |
| Realtek Realtek USB2.0 PC Camera                                           | 1         | 1.54%   |
| Microdia Integrated Webcam                                                 | 1         | 1.54%   |
| Microdia Dell Integrated HD Webcam                                         | 1         | 1.54%   |
| Logitech Webcam C170                                                       | 1         | 1.54%   |
| Logitech HD Pro Webcam C920                                                | 1         | 1.54%   |
| Logitech C920 PRO HD Webcam                                                | 1         | 1.54%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 1         | 1.54%   |
| IMC Networks HD Camera                                                     | 1         | 1.54%   |
| IMC Networks EasyCamera                                                    | 1         | 1.54%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]                          | 1         | 1.54%   |
| Chicony USB2.0 0.3M UVC WebCam                                             | 1         | 1.54%   |
| Chicony Integrated IR Camera                                               | 1         | 1.54%   |
| Chicony HD Webcam                                                          | 1         | 1.54%   |
| Chicony Chicony USB2.0 Camera                                              | 1         | 1.54%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 1.54%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed]                | 1         | 1.54%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam   | 1         | 1.54%   |
| Aveo USB2.0 Camera                                                         | 1         | 1.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 9         | 47.37%  |
| Validity Sensors           | 5         | 26.32%  |
| Shenzhen Goodix Technology | 4         | 21.05%  |
| AuthenTec                  | 1         | 5.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 6         | 31.58%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 10.53%  |
| Validity Sensors Synaptics WBDI                                            | 2         | 10.53%  |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 10.53%  |
| Shenzhen Goodix  FingerPrint Device                                        | 2         | 10.53%  |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 10.53%  |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 5.26%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 5.26%   |
| AuthenTec AES2810                                                          | 1         | 5.26%   |

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
| 0     | 32        | 28.57%  |
| 2     | 31        | 27.68%  |
| 1     | 19        | 16.96%  |
| 4     | 15        | 13.39%  |
| 3     | 10        | 8.93%   |
| 5     | 4         | 3.57%   |
| 9     | 1         | 0.89%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 61        | 37.42%  |
| Bluetooth                | 34        | 20.86%  |
| Net/wireless             | 27        | 16.56%  |
| Fingerprint reader       | 19        | 11.66%  |
| Card reader              | 9         | 5.52%   |
| Sound                    | 5         | 3.07%   |
| Net/ethernet             | 3         | 1.84%   |
| Network                  | 2         | 1.23%   |
| Firewire controller      | 2         | 1.23%   |
| Modem                    | 1         | 0.61%   |

