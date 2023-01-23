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

Total: 182

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
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
| amd64 | 95        | 82.61%  |
| arm64 | 16        | 13.91%  |
| arm   | 2         | 1.74%   |
| riscv | 1         | 0.87%   |
| i386  | 1         | 0.87%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 29        | 24.17%  |
| KDE5          | 28        | 23.33%  |
| XFCE          | 15        | 12.5%   |
| MATE          | 9         | 7.5%    |
| TWM           | 7         | 5.83%   |
| GNOME         | 7         | 5.83%   |
| i3            | 5         | 4.17%   |
| Openbox       | 3         | 2.5%    |
| Cinnamon      | 3         | 2.5%    |
| LXQt          | 2         | 1.67%   |
| LXDE          | 2         | 1.67%   |
| Lumina        | 2         | 1.67%   |
| Xfwm4         | 1         | 0.83%   |
| sway          | 1         | 0.83%   |
| spectrwm      | 1         | 0.83%   |
| Picom         | 1         | 0.83%   |
| GNUstep       | 1         | 0.83%   |
| Fluxbox       | 1         | 0.83%   |
| Enlightenment | 1         | 0.83%   |
| ctwm          | 1         | 0.83%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 83        | 69.75%  |
| Console | 34        | 28.57%  |
| Wayland | 2         | 1.68%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 56        | 47.46%  |
| SDDM    | 25        | 21.19%  |
| SLiM    | 15        | 12.71%  |
| GDM     | 11        | 9.32%   |
| XDM     | 7         | 5.93%   |
| LightDM | 3         | 2.54%   |
| Ly      | 1         | 0.85%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang             | Computers | Percent |
|------------------|-----------|---------|
| C                | 77        | 65.81%  |
| en_US            | 15        | 12.82%  |
| de_DE            | 5         | 4.27%   |
| Unknown          | 5         | 4.27%   |
| uk_UA            | 3         | 2.56%   |
| zh_CN            | 2         | 1.71%   |
| ru_RU            | 2         | 1.71%   |
| en_GB            | 2         | 1.71%   |
| sv_SE            | 1         | 0.85%   |
| pt_PT            | 1         | 0.85%   |
| pl_PL            | 1         | 0.85%   |
| it_IT.ISO8859-15 | 1         | 0.85%   |
| fr_FR            | 1         | 0.85%   |
| de_CH            | 1         | 0.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 103       | 89.57%  |
| BIOS | 12        | 10.43%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 83        | 72.17%  |
| Ufs  | 32        | 27.83%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 106       | 92.17%  |
| MBR  | 9         | 7.83%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 25        | 21.74%  |
| Unknown                        | 14        | 12.17%  |
| Dell                           | 13        | 11.3%   |
| ASUSTek Computer               | 12        | 10.43%  |
| Hewlett-Packard                | 9         | 7.83%   |
| Gigabyte Technology            | 7         | 6.09%   |
| MSI                            | 6         | 5.22%   |
| Raspberry Pi Foundation        | 4         | 3.48%   |
| ASRock                         | 4         | 3.48%   |
| Apple                          | 3         | 2.61%   |
| Intel                          | 2         | 1.74%   |
| Framework                      | 2         | 1.74%   |
| Beckhoff Automation            | 2         | 1.74%   |
| Valve                          | 1         | 0.87%   |
| Timi                           | 1         | 0.87%   |
| System76                       | 1         | 0.87%   |
| pine64                         | 1         | 0.87%   |
| Notebook                       | 1         | 0.87%   |
| Matsushita Electric Industrial | 1         | 0.87%   |
| khadas                         | 1         | 0.87%   |
| HUAWEI                         | 1         | 0.87%   |
| Google                         | 1         | 0.87%   |
| friendlyelec                   | 1         | 0.87%   |
| Avell High Performance         | 1         | 0.87%   |
| A-DATA Technology              | 1         | 0.87%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 15        | 13.04%  |
| RPi Raspberry Pi                            | 3         | 2.61%   |
| HP EliteBook 8570p                          | 3         | 2.61%   |
| Framework Laptop                            | 2         | 1.74%   |
| Valve Jupiter                               | 1         | 0.87%   |
| Timi Redmi Book Pro 14 2022                 | 1         | 0.87%   |
| System76 Gazelle                            | 1         | 0.87%   |
| RPi rpi                                     | 1         | 0.87%   |
| pine64 pinebook-pro-rk3399                  | 1         | 0.87%   |
| Notebook NS50_70MU                          | 1         | 0.87%   |
| MSI MS-7C79                                 | 1         | 0.87%   |
| MSI MS-7C75                                 | 1         | 0.87%   |
| MSI MS-7B89                                 | 1         | 0.87%   |
| MSI MS-7B86                                 | 1         | 0.87%   |
| MSI GE76 Raider 10UG                        | 1         | 0.87%   |
| MSI Bravo 15 A4DDR                          | 1         | 0.87%   |
| Matsushita Electric Industrial CF-T2BW1AXR  | 1         | 0.87%   |
| Lenovo XiaoXinPro-13ARE 2020 82DM           | 1         | 0.87%   |
| Lenovo ThinkPad X395 20NL001SMX             | 1         | 0.87%   |
| Lenovo ThinkPad X395 20NL000GPG             | 1         | 0.87%   |
| Lenovo ThinkPad X270 20HM004JBR             | 1         | 0.87%   |
| Lenovo ThinkPad X260 20F5A28AUK             | 1         | 0.87%   |
| Lenovo ThinkPad X13 Gen 1 20T2003PRT        | 1         | 0.87%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TLA055CD | 1         | 0.87%   |
| Lenovo ThinkPad X1 Extreme 20MF000BUS       | 1         | 0.87%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS1QC00    | 1         | 0.87%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS0BT00    | 1         | 0.87%   |
| Lenovo ThinkPad T495s 20QKS1812F            | 1         | 0.87%   |
| Lenovo ThinkPad T495 20NJ0010PB             | 1         | 0.87%   |
| Lenovo ThinkPad T470p 20J7S0PM00            | 1         | 0.87%   |
| Lenovo ThinkPad T430 2349H2G                | 1         | 0.87%   |
| Lenovo ThinkPad T14s Gen 2i 20WM00B7MX      | 1         | 0.87%   |
| Lenovo ThinkPad P15 Gen 1 20ST005VRT        | 1         | 0.87%   |
| Lenovo ThinkPad P14s Gen 1 20Y1CTO1WW       | 1         | 0.87%   |
| Lenovo ThinkPad E14 Gen 3 20Y7003SGE        | 1         | 0.87%   |
| Lenovo ThinkPad E14 20RBCTO1WW              | 1         | 0.87%   |
| Lenovo ThinkBook 14 G3 ACL 21A2             | 1         | 0.87%   |
| Lenovo Legion 5P 15IMH05H 82AW              | 1         | 0.87%   |
| Lenovo Legion 5 15IMH05 82AU                | 1         | 0.87%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY        | 1         | 0.87%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo ThinkPad                            | 18        | 15.65%  |
| Unknown                                    | 15        | 13.04%  |
| ASUS PRIME                                 | 6         | 5.22%   |
| HP EliteBook                               | 4         | 3.48%   |
| Dell Latitude                              | 4         | 3.48%   |
| RPi Raspberry                              | 3         | 2.61%   |
| HP ProBook                                 | 3         | 2.61%   |
| Dell OptiPlex                              | 3         | 2.61%   |
| Lenovo Legion                              | 2         | 1.74%   |
| Lenovo IdeaPad                             | 2         | 1.74%   |
| Gigabyte X570                              | 2         | 1.74%   |
| Gigabyte B450M                             | 2         | 1.74%   |
| Framework Laptop                           | 2         | 1.74%   |
| Valve Jupiter                              | 1         | 0.87%   |
| Timi Redmi                                 | 1         | 0.87%   |
| System76 Gazelle                           | 1         | 0.87%   |
| RPi rpi                                    | 1         | 0.87%   |
| pine64 pinebook-pro-rk3399                 | 1         | 0.87%   |
| Notebook NS50                              | 1         | 0.87%   |
| MSI MS-7C79                                | 1         | 0.87%   |
| MSI MS-7C75                                | 1         | 0.87%   |
| MSI MS-7B89                                | 1         | 0.87%   |
| MSI MS-7B86                                | 1         | 0.87%   |
| MSI GE76                                   | 1         | 0.87%   |
| MSI Bravo                                  | 1         | 0.87%   |
| Matsushita Electric Industrial CF-T2BW1AXR | 1         | 0.87%   |
| Lenovo XiaoXinPro-13ARE                    | 1         | 0.87%   |
| Lenovo ThinkBook                           | 1         | 0.87%   |
| khadas edge-v                              | 1         | 0.87%   |
| Intel S2600WTTR                            | 1         | 0.87%   |
| Intel NUC11PHi7                            | 1         | 0.87%   |
| HUAWEI HN-WX9X                             | 1         | 0.87%   |
| HP ZBook                                   | 1         | 0.87%   |
| HP EliteDesk                               | 1         | 0.87%   |
| Google Akemi                               | 1         | 0.87%   |
| Gigabyte X399                              | 1         | 0.87%   |
| Gigabyte B550I                             | 1         | 0.87%   |
| Gigabyte 970A-UD3P                         | 1         | 0.87%   |
| friendlyelec nanopi-m4                     | 1         | 0.87%   |
| Dell Vostro                                | 1         | 0.87%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 28        | 24.35%  |
| 2021    | 27        | 23.48%  |
| 2019    | 14        | 12.17%  |
| Unknown | 13        | 11.3%   |
| 2022    | 9         | 7.83%   |
| 2018    | 7         | 6.09%   |
| 2017    | 4         | 3.48%   |
| 2013    | 4         | 3.48%   |
| 2015    | 3         | 2.61%   |
| 2016    | 2         | 1.74%   |
| 2014    | 1         | 0.87%   |
| 2012    | 1         | 0.87%   |
| 2011    | 1         | 0.87%   |
| 2003    | 1         | 0.87%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 60        | 52.17%  |
| Desktop        | 43        | 37.39%  |
| System on chip | 7         | 6.09%   |
| Mini pc        | 2         | 1.74%   |
| Server         | 2         | 1.74%   |
| All in one     | 1         | 0.87%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 113       | 98.26%  |
| Yes  | 2         | 1.74%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 42        | 35.9%   |
| 8.01-16.0       | 23        | 19.66%  |
| 32.01-64.0      | 18        | 15.38%  |
| 64.01-256.0     | 16        | 13.68%  |
| 4.01-8.0        | 9         | 7.69%   |
| 3.01-4.0        | 3         | 2.56%   |
| 0.51-1.0        | 2         | 1.71%   |
| More than 256.0 | 1         | 0.85%   |
| 24.01-32.0      | 1         | 0.85%   |
| 1.01-2.0        | 1         | 0.85%   |
| 0.01-0.5        | 1         | 0.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.51-1.0    | 35        | 29.66%  |
| 1.01-2.0    | 33        | 27.97%  |
| 0.01-0.5    | 23        | 19.49%  |
| 2.01-3.0    | 13        | 11.02%  |
| 3.01-4.0    | 5         | 4.24%   |
| 24.01-32.0  | 2         | 1.69%   |
| 0           | 2         | 1.69%   |
| 4.01-8.0    | 1         | 0.85%   |
| 32.01-64.0  | 1         | 0.85%   |
| 64.01-256.0 | 1         | 0.85%   |
| 16.01-24.0  | 1         | 0.85%   |
| 8.01-16.0   | 1         | 0.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 58        | 47.54%  |
| 2      | 30        | 24.59%  |
| 0      | 15        | 12.3%   |
| 3      | 8         | 6.56%   |
| 6      | 5         | 4.1%    |
| 4      | 3         | 2.46%   |
| 15     | 1         | 0.82%   |
| 7      | 1         | 0.82%   |
| 5      | 1         | 0.82%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 102       | 87.18%  |
| Yes       | 15        | 12.82%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 88        | 76.52%  |
| No        | 27        | 23.48%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 77        | 66.96%  |
| No        | 38        | 33.04%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 59        | 50.86%  |
| No        | 57        | 49.14%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 20        | 17.39%  |
| Russia       | 16        | 13.91%  |
| Germany      | 14        | 12.17%  |
| UK           | 11        | 9.57%   |
| Brazil       | 6         | 5.22%   |
| Poland       | 5         | 4.35%   |
| Ukraine      | 4         | 3.48%   |
| Japan        | 4         | 3.48%   |
| China        | 4         | 3.48%   |
| Austria      | 4         | 3.48%   |
| Portugal     | 3         | 2.61%   |
| Switzerland  | 2         | 1.74%   |
| Sweden       | 2         | 1.74%   |
| Romania      | 2         | 1.74%   |
| Netherlands  | 2         | 1.74%   |
| France       | 2         | 1.74%   |
| Denmark      | 2         | 1.74%   |
| Turkey       | 1         | 0.87%   |
| Spain        | 1         | 0.87%   |
| Singapore    | 1         | 0.87%   |
| Saudi Arabia | 1         | 0.87%   |
| Peru         | 1         | 0.87%   |
| Jamaica      | 1         | 0.87%   |
| Italy        | 1         | 0.87%   |
| India        | 1         | 0.87%   |
| Croatia      | 1         | 0.87%   |
| Colombia     | 1         | 0.87%   |
| Belarus      | 1         | 0.87%   |
| Bangladesh   | 1         | 0.87%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Moscow                      | 8         | 6.25%   |
| Brighton                    | 5         | 3.91%   |
| St Petersburg               | 3         | 2.34%   |
| Seattle                     | 3         | 2.34%   |
| London                      | 3         | 2.34%   |
| Kyiv                        | 3         | 2.34%   |
| ЕЊta-ku                   | 2         | 1.56%   |
| Zurich                      | 2         | 1.56%   |
| Vienna                      | 2         | 1.56%   |
| Rio de Janeiro              | 2         | 1.56%   |
| Rietberg                    | 2         | 1.56%   |
| Northeim                    | 2         | 1.56%   |
| Krasnodar                   | 2         | 1.56%   |
| Graz                        | 2         | 1.56%   |
| Fuchu                       | 2         | 1.56%   |
| Egham                       | 2         | 1.56%   |
| Chicago                     | 2         | 1.56%   |
| Cambridge                   | 2         | 1.56%   |
| Berlin                      | 2         | 1.56%   |
| Zaporizhzhya                | 1         | 0.78%   |
| Wuhan                       | 1         | 0.78%   |
| Woodburn                    | 1         | 0.78%   |
| Wieliczka                   | 1         | 0.78%   |
| Washington                  | 1         | 0.78%   |
| Warsaw                      | 1         | 0.78%   |
| Vila Real de Santo António | 1         | 0.78%   |
| Vancouver                   | 1         | 0.78%   |
| Tynda                       | 1         | 0.78%   |
| Trosa                       | 1         | 0.78%   |
| Thrissur                    | 1         | 0.78%   |
| Teaneck                     | 1         | 0.78%   |
| Stuttgart                   | 1         | 0.78%   |
| Stolberg                    | 1         | 0.78%   |
| Sollentuna                  | 1         | 0.78%   |
| Slavonski Brod              | 1         | 0.78%   |
| Singapore                   | 1         | 0.78%   |
| Shanghai                    | 1         | 0.78%   |
| Setagaya-ku                 | 1         | 0.78%   |
| Satu Mare                   | 1         | 0.78%   |
| Santa Monica                | 1         | 0.78%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 32        | 49     | 22.07%  |
| WDC                 | 28        | 45     | 19.31%  |
| Toshiba             | 12        | 24     | 8.28%   |
| Seagate             | 10        | 26     | 6.9%    |
| Crucial             | 8         | 17     | 5.52%   |
| Kingston            | 7         | 10     | 4.83%   |
| HGST                | 7         | 24     | 4.83%   |
| A-DATA Technology   | 6         | 6      | 4.14%   |
| SK hynix            | 5         | 5      | 3.45%   |
| KIOXIA              | 5         | 5      | 3.45%   |
| Intel               | 5         | 8      | 3.45%   |
| Micron Technology   | 3         | 4      | 2.07%   |
| Apple               | 3         | 3      | 2.07%   |
| SSSTC               | 1         | 1      | 0.69%   |
| SPCC                | 1         | 1      | 0.69%   |
| Solid State Storage | 1         | 1      | 0.69%   |
| Silicon Motion      | 1         | 1      | 0.69%   |
| SanDisk             | 1         | 2      | 0.69%   |
| PNY                 | 1         | 1      | 0.69%   |
| Mushkin             | 1         | 1      | 0.69%   |
| LSI                 | 1         | 4      | 0.69%   |
| LITEON              | 1         | 1      | 0.69%   |
| Hitachi             | 1         | 2      | 0.69%   |
| Goodram             | 1         | 1      | 0.69%   |
| Fujitsu             | 1         | 2      | 0.69%   |
| FORESEE             | 1         | 1      | 0.69%   |
| Apacer              | 1         | 1      | 0.69%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB             | 5         | 3.07%   |
| HGST HTS725050A7E630 500GB           | 4         | 2.45%   |
| WDC WDS100T3X0C-00SJG0 1TB           | 3         | 1.84%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 3         | 1.84%   |
| Toshiba MQ04ABF100 1TB               | 3         | 1.84%   |
| Samsung SSD 980 PRO 1TB              | 3         | 1.84%   |
| Samsung SSD 870 EVO 1TB              | 3         | 1.84%   |
| Samsung HM251JX 250GB                | 3         | 1.84%   |
| HGST HTS721010A9E630 1TB             | 3         | 1.84%   |
| WDC WDS100T1X0E-00AFY0 1TB           | 2         | 1.23%   |
| WDC WD30EFRX-68EUZN0 3TB             | 2         | 1.23%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB   | 2         | 1.23%   |
| WDC PC SN730 NVMe 1024GB             | 2         | 1.23%   |
| Seagate ST1000LM049-2GH172 1TB       | 2         | 1.23%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 1.23%   |
| Samsung SSD 970 EVO Plus 1TB         | 2         | 1.23%   |
| Samsung SSD 860 EVO 250GB            | 2         | 1.23%   |
| Samsung SSD 850 EVO 250GB            | 2         | 1.23%   |
| Samsung MZVLB512HBJQ-000L7 512GB     | 2         | 1.23%   |
| KIOXIA KBG40ZNS256G NVMe 256GB       | 2         | 1.23%   |
| Kingston SA2000M81000G 1TB           | 2         | 1.23%   |
| Apple SSD SM256E 256GB               | 2         | 1.23%   |
| WDC WDS500G1X0E-00AFY0 500GB         | 1         | 0.61%   |
| WDC WDS250G2B0C-00PXH0 250GB         | 1         | 0.61%   |
| WDC WDS100T2B0A-00SM50 1TB           | 1         | 0.61%   |
| WDC WD60EFRX-68TGBN1 6TB             | 1         | 0.61%   |
| WDC WD5002ABYS-18B1B0 500GB          | 1         | 0.61%   |
| WDC WD40EZRZ-75GXCB0 4TB             | 1         | 0.61%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 1         | 0.61%   |
| WDC WD20EFRX-68AX9N0 2TB             | 1         | 0.61%   |
| WDC WD120EFAX-68UNTN0 12TB           | 1         | 0.61%   |
| WDC WD10SPZX-60Z10T0 1TB             | 1         | 0.61%   |
| WDC WD10SPZX-21Z10T0 1TB             | 1         | 0.61%   |
| WDC WD10JPVX-00JC3T0 1TB             | 1         | 0.61%   |
| WDC WD10JMVW-11AJGS3 1TB             | 1         | 0.61%   |
| WDC WD10EZEX-60WN4A0 1TB             | 1         | 0.61%   |
| WDC WD10EZEX-00RKKA0 1TB             | 1         | 0.61%   |
| WDC WD10EARX-00N0YB0 1TB             | 1         | 0.61%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB | 1         | 0.61%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB | 1         | 0.61%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 11        | 17     | 23.91%  |
| Toshiba             | 11        | 23     | 23.91%  |
| Seagate             | 10        | 26     | 21.74%  |
| HGST                | 7         | 24     | 15.22%  |
| Samsung Electronics | 4         | 7      | 8.7%    |
| LSI                 | 1         | 4      | 2.17%   |
| Hitachi             | 1         | 2      | 2.17%   |
| Fujitsu             | 1         | 2      | 2.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 17     | 32.43%  |
| Crucial             | 5         | 10     | 13.51%  |
| A-DATA Technology   | 4         | 4      | 10.81%  |
| Kingston            | 3         | 5      | 8.11%   |
| Intel               | 3         | 6      | 8.11%   |
| Apple               | 3         | 3      | 8.11%   |
| WDC                 | 1         | 2      | 2.7%    |
| SK hynix            | 1         | 1      | 2.7%    |
| SanDisk             | 1         | 2      | 2.7%    |
| Micron Technology   | 1         | 1      | 2.7%    |
| LITEON              | 1         | 1      | 2.7%    |
| Goodram             | 1         | 1      | 2.7%    |
| Apacer              | 1         | 1      | 2.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 61        | 87     | 46.92%  |
| SSD  | 36        | 54     | 27.69%  |
| HDD  | 33        | 105    | 25.38%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 61        | 87     | 50.83%  |
| SATA | 59        | 159    | 49.17%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 36        | 71     | 46.15%  |
| 0.51-1.0   | 24        | 44     | 30.77%  |
| 1.01-2.0   | 5         | 6      | 6.41%   |
| 4.01-10.0  | 4         | 23     | 5.13%   |
| 3.01-4.0   | 3         | 4      | 3.85%   |
| 2.01-3.0   | 3         | 4      | 3.85%   |
| 10.01-20.0 | 2         | 3      | 2.56%   |
| 20.01-50.0 | 1         | 4      | 1.28%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 32        | 26.45%  |
| 251-500        | 29        | 23.97%  |
| 501-1000       | 18        | 14.88%  |
| 1-20           | 12        | 9.92%   |
| 51-100         | 10        | 8.26%   |
| 21-50          | 8         | 6.61%   |
| 1001-2000      | 5         | 4.13%   |
| 2001-3000      | 4         | 3.31%   |
| More than 3000 | 3         | 2.48%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 76        | 62.3%   |
| 21-50          | 29        | 23.77%  |
| 101-250        | 8         | 6.56%   |
| 1001-2000      | 2         | 1.64%   |
| 501-1000       | 2         | 1.64%   |
| 51-100         | 2         | 1.64%   |
| More than 3000 | 1         | 0.82%   |
| 251-500        | 1         | 0.82%   |
| 0              | 1         | 0.82%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                     | Computers | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| HGST HTS725050A7E630 500GB                | 4         | 7      | 25%     |
| Samsung Electronics SSD 870 EVO 1TB       | 3         | 5      | 18.75%  |
| WDC WD60EFRX-68TGBN1 6TB                  | 1         | 3      | 6.25%   |
| WDC WD5002ABYS-18B1B0 500GB               | 1         | 1      | 6.25%   |
| WDC WD10SPZX-60Z10T0 1TB                  | 1         | 1      | 6.25%   |
| Samsung Electronics SSD PM851 mSATA 256GB | 1         | 1      | 6.25%   |
| Samsung Electronics HM251JX 250GB         | 1         | 1      | 6.25%   |
| Kingston SA400S37120G 120GB               | 1         | 1      | 6.25%   |
| Hitachi HUA722020ALA331 2TB               | 1         | 2      | 6.25%   |
| HGST HTS721010A9E630 1TB                  | 1         | 12     | 6.25%   |
| Fujitsu MHS2040AT D 40GB                  | 1         | 2      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 7      | 33.33%  |
| HGST                | 4         | 19     | 26.67%  |
| WDC                 | 3         | 5      | 20%     |
| Kingston            | 1         | 1      | 6.67%   |
| Hitachi             | 1         | 2      | 6.67%   |
| Fujitsu             | 1         | 2      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 4         | 19     | 40%     |
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
| HDD  | 9         | 29     | 69.23%  |
| SSD  | 4         | 7      | 30.77%  |

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
| Works    | 95        | 203    | 84.82%  |
| Malfunc  | 13        | 36     | 11.61%  |
| Detected | 4         | 7      | 3.57%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 48        | 31.37%  |
| AMD                            | 28        | 18.3%   |
| Samsung Electronics            | 22        | 14.38%  |
| SanDisk                        | 18        | 11.76%  |
| Silicon Motion                 | 6         | 3.92%   |
| Kingston Technology Company    | 5         | 3.27%   |
| SK hynix                       | 4         | 2.61%   |
| KIOXIA                         | 4         | 2.61%   |
| Micron/Crucial Technology      | 3         | 1.96%   |
| Micron Technology              | 3         | 1.96%   |
| Toshiba                        | 2         | 1.31%   |
| Solid State Storage Technology | 2         | 1.31%   |
| Marvell Technology Group       | 2         | 1.31%   |
| ASMedia Technology             | 2         | 1.31%   |
| ADATA Technology               | 2         | 1.31%   |
| Phison Electronics             | 1         | 0.65%   |
| Broadcom / LSI                 | 1         | 0.65%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 20        | 11.98%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 14        | 8.38%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 11        | 6.59%   |
| Intel Comet Lake SATA AHCI Controller                                          | 9         | 5.39%   |
| Unknown                                                                        | 8         | 4.79%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 4.19%   |
| AMD 400 Series Chipset SATA Controller                                         | 7         | 4.19%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 6         | 3.59%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 6         | 3.59%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 2.4%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 4         | 2.4%    |
| AMD 500 Series Chipset SATA Controller                                         | 4         | 2.4%    |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 3         | 1.8%    |
| Samsung NVMe SSD Controller 980                                                | 3         | 1.8%    |
| KIOXIA NVMe SSD Controller BG4                                                 | 3         | 1.8%    |
| Kingston Company A2000 NVMe SSD                                                | 3         | 1.8%    |
| Toshiba XG6 NVMe SSD Controller                                                | 2         | 1.2%    |
| SK hynix BC511                                                                 | 2         | 1.2%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 1.2%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 1.2%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 1.2%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2         | 1.2%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 1.2%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 1.2%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 1.2%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.2%    |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 2         | 1.2%    |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 2         | 1.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 1.2%    |
| SK hynix PC300 NVMe Solid State Drive 512GB                                    | 1         | 0.6%    |
| SanDisk PC SN530                                                               | 1         | 0.6%    |
| Samsung SM951 AHCI                                                             | 1         | 0.6%    |
| Phison E12 NVMe Controller                                                     | 1         | 0.6%    |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 1         | 0.6%    |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                          | 1         | 0.6%    |
| Marvell Group 88SE9170 PCIe 2.0 x1 2-port SATA 6 Gb/s Controller               | 1         | 0.6%    |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 1         | 0.6%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 0.6%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1         | 0.6%    |
| Intel SSD 660P Series                                                          | 1         | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 71        | 48.3%   |
| NVMe | 70        | 47.62%  |
| IDE  | 4         | 2.72%   |
| RAID | 2         | 1.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 58        | 49.57%  |
| AMD      | 39        | 33.33%  |
| ARM      | 11        | 9.4%    |
| Unknown  | 8         | 6.84%   |
| Research | 1         | 0.85%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
|                                                 | 8         | 6.84%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 6         | 5.13%   |
| Intel Core i5-10210U CPU @ 1.60GHz              | 5         | 4.27%   |
| Intel Core i7-3520M CPU @ 2.90GHz               | 4         | 3.42%   |
| ARM Cortex-A72 r0p3                             | 4         | 3.42%   |
| AMD Ryzen 5 5600G with Radeon Graphics          | 4         | 3.42%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 3         | 2.56%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 2         | 1.71%   |
| Intel Core i7-7600U CPU @ 2.80GHz               | 2         | 1.71%   |
| Intel Core i5-10500T CPU @ 2.30GHz              | 2         | 1.71%   |
| Intel Core i5-10300H CPU @ 2.50GHz              | 2         | 1.71%   |
| ARM Cortex-A72 r0p2                             | 2         | 1.71%   |
| ARM Cortex-A55 r2p0                             | 2         | 1.71%   |
| ARM Cortex-A53 r0p4                             | 2         | 1.71%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 2         | 1.71%   |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx | 2         | 1.71%   |
| AMD Ryzen 7 4800U with Radeon Graphics          | 2         | 1.71%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 2         | 1.71%   |
| AMD Ryzen 7 4700U with Radeon Graphics          | 2         | 1.71%   |
| AMD Ryzen 5 PRO 3500U w/ Radeon Vega Mobile Gfx | 2         | 1.71%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 2         | 1.71%   |
| Research Morello SoC r0p0                       | 1         | 0.85%   |
| Intel Xeon W-10885M CPU @ 2.40GHz               | 1         | 0.85%   |
| Intel Xeon E-2334 CPU @ 3.40GHz                 | 1         | 0.85%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz             | 1         | 0.85%   |
| Intel Pentium M processor 1000MHz               | 1         | 0.85%   |
| Intel Core i7-9850H CPU @ 2.60GHz               | 1         | 0.85%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 1         | 0.85%   |
| Intel Core i7-8700 CPU @ 3.20GHz                | 1         | 0.85%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 0.85%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 0.85%   |
| Intel Core i7-5600U CPU @ 2.60GHz               | 1         | 0.85%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz              | 1         | 0.85%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz              | 1         | 0.85%   |
| Intel Core i7-4600U CPU @ 2.10GHz               | 1         | 0.85%   |
| Intel Core i7-3770 CPU @ 3.40GHz                | 1         | 0.85%   |
| Intel Core i7-3687U CPU @ 2.10GHz               | 1         | 0.85%   |
| Intel Core i7-3615QM CPU @ 2.30GHz              | 1         | 0.85%   |
| Intel Core i7-10870H CPU @ 2.20GHz              | 1         | 0.85%   |
| Intel Core i7-10700K CPU @ 3.80GHz              | 1         | 0.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 28        | 24.14%  |
| Other                  | 20        | 17.24%  |
| Intel Core i5          | 15        | 12.93%  |
| AMD Ryzen 5            | 12        | 10.34%  |
| ARM Cortex             | 10        | 8.62%   |
| AMD Ryzen 7            | 10        | 8.62%   |
| AMD Ryzen 9            | 5         | 4.31%   |
| Intel Xeon             | 3         | 2.59%   |
| AMD Ryzen 7 PRO        | 3         | 2.59%   |
| AMD Ryzen 5 PRO        | 2         | 1.72%   |
| Intel Pentium M        | 1         | 0.86%   |
| Intel Atom             | 1         | 0.86%   |
| AMD Ryzen Threadripper | 1         | 0.86%   |
| AMD Ryzen Embedded     | 1         | 0.86%   |
| AMD Ryzen 3            | 1         | 0.86%   |
| AMD FX                 | 1         | 0.86%   |
| AMD E                  | 1         | 0.86%   |
| AMD Athlon             | 1         | 0.86%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 24        | 20.69%  |
| Unknown | 19        | 16.38%  |
| 8       | 18        | 15.52%  |
| 2       | 16        | 13.79%  |
| 6       | 13        | 11.21%  |
| 16      | 10        | 8.62%   |
| 12      | 9         | 7.76%   |
| 32      | 3         | 2.59%   |
| 24      | 3         | 2.59%   |
| 1       | 1         | 0.86%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 100       | 86.21%  |
| Unknown | 15        | 12.93%  |
| 2       | 1         | 0.86%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 55        | 47.41%  |
| 1       | 41        | 35.34%  |
| Unknown | 20        | 17.24%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 28        | 24.14%  |
| KabyLake   | 16        | 13.79%  |
| CometLake  | 12        | 10.34%  |
| Zen 2      | 11        | 9.48%   |
| Zen+       | 10        | 8.62%   |
| IvyBridge  | 9         | 7.76%   |
| Zen 3      | 8         | 6.9%    |
| TigerLake  | 6         | 5.17%   |
| Zen        | 4         | 3.45%   |
| Haswell    | 3         | 2.59%   |
| Broadwell  | 3         | 2.59%   |
| Skylake    | 1         | 0.86%   |
| Silvermont | 1         | 0.86%   |
| Piledriver | 1         | 0.86%   |
| P6         | 1         | 0.86%   |
| IceLake    | 1         | 0.86%   |
| Bobcat     | 1         | 0.86%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 48        | 39.02%  |
| AMD                        | 37        | 30.08%  |
| Nvidia                     | 35        | 28.46%  |
| Matrox Electronics Systems | 2         | 1.63%   |
| ASPEED Technology          | 1         | 0.81%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                           | 8         | 6.4%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series] | 7         | 5.6%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                            | 6         | 4.8%    |
| Intel CometLake-U GT2 [UHD Graphics]                                 | 6         | 4.8%    |
| Intel 3rd Gen Core processor Graphics Controller                     | 5         | 4%      |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]         | 5         | 4%      |
| Intel CometLake-H GT2 [UHD Graphics]                                 | 4         | 3.2%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                            | 4         | 3.2%    |
| Nvidia TU117M                                                        | 3         | 2.4%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                             | 3         | 2.4%    |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                             | 3         | 2.4%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]     | 3         | 2.4%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                           | 2         | 1.6%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                           | 2         | 1.6%    |
| Nvidia GP108M [GeForce MX230]                                        | 2         | 1.6%    |
| Nvidia GP108 [GeForce GT 1030]                                       | 2         | 1.6%    |
| Nvidia GK208B [GeForce GT 710]                                       | 2         | 1.6%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                 | 2         | 1.6%    |
| Intel HD Graphics 620                                                | 2         | 1.6%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller          | 2         | 1.6%    |
| AMD Lucienne                                                         | 2         | 1.6%    |
| Nvidia TU117M [GeForce MX450]                                        | 1         | 0.8%    |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                | 1         | 0.8%    |
| Nvidia TU116 [GeForce GTX 1660]                                      | 1         | 0.8%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                              | 1         | 0.8%    |
| Nvidia TU104GLM [Quadro RTX 5000 Mobile / Max-Q]                     | 1         | 0.8%    |
| Nvidia GT218 [GeForce 210]                                           | 1         | 0.8%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                           | 1         | 0.8%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                              | 1         | 0.8%    |
| Nvidia GP107GL [Quadro P620]                                         | 1         | 0.8%    |
| Nvidia GP107 [GeForce GTX 1050]                                      | 1         | 0.8%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                   | 1         | 0.8%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                  | 1         | 0.8%    |
| Nvidia GM206 [GeForce GTX 960]                                       | 1         | 0.8%    |
| Nvidia GM108M [GeForce MX130]                                        | 1         | 0.8%    |
| Nvidia GM108M [GeForce 940MX]                                        | 1         | 0.8%    |
| Nvidia GM107M [GeForce GTX 860M]                                     | 1         | 0.8%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                    | 1         | 0.8%    |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                          | 1         | 0.8%    |
| Nvidia GK107GLM [Quadro K1100M]                                      | 1         | 0.8%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x AMD                  | 31        | 26.5%   |
| 1 x Intel                | 26        | 22.22%  |
| Intel + Nvidia           | 19        | 16.24%  |
| Other                    | 18        | 15.38%  |
| 1 x Nvidia               | 15        | 12.82%  |
| 2 x AMD                  | 2         | 1.71%   |
| 1 x Matrox               | 2         | 1.71%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.85%   |
| Intel + AMD              | 1         | 0.85%   |
| 1 x ASPEED               | 1         | 0.85%   |
| AMD + Nvidia             | 1         | 0.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 74        | 64.35%  |
| Proprietary | 23        | 20%     |
| Unknown     | 18        | 15.65%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 84        | 71.79%  |
| 1.01-2.0   | 11        | 9.4%    |
| 0.51-1.0   | 7         | 5.98%   |
| 0.01-0.5   | 5         | 4.27%   |
| 3.01-4.0   | 4         | 3.42%   |
| 7.01-8.0   | 2         | 1.71%   |
| 5.01-6.0   | 2         | 1.71%   |
| 2.01-3.0   | 1         | 0.85%   |
| 8.01-16.0  | 1         | 0.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| BOE                 | 14        | 16.47%  |
| LG Display          | 10        | 11.76%  |
| AU Optronics        | 9         | 10.59%  |
| Dell                | 7         | 8.24%   |
| Goldstar            | 5         | 5.88%   |
| Philips             | 4         | 4.71%   |
| Hewlett-Packard     | 4         | 4.71%   |
| Chimei Innolux      | 4         | 4.71%   |
| Samsung Electronics | 3         | 3.53%   |
| Sharp               | 2         | 2.35%   |
| RTK                 | 2         | 2.35%   |
| LG Electronics      | 2         | 2.35%   |
| Lenovo              | 2         | 2.35%   |
| InfoVision          | 2         | 2.35%   |
| BenQ                | 2         | 2.35%   |
| Apple               | 2         | 2.35%   |
| ViewSonic           | 1         | 1.18%   |
| Sony                | 1         | 1.18%   |
| SDC                 | 1         | 1.18%   |
| PANDA               | 1         | 1.18%   |
| LGD                 | 1         | 1.18%   |
| Iiyama              | 1         | 1.18%   |
| HJW                 | 1         | 1.18%   |
| Eizo                | 1         | 1.18%   |
| CSO                 | 1         | 1.18%   |
| AOC                 | 1         | 1.18%   |
| Unknown             | 1         | 1.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0258 1600x900 350x190mm 15.7-inch            | 3         | 3.45%   |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                  | 3         | 3.45%   |
| RTK WCS Display RTK1A1B 1920x1080 344x195mm 15.6-inch                  | 2         | 2.3%    |
| Philips LCD Monitor PHL08C3 1920x1080 600x340mm 27.2-inch              | 2         | 2.3%    |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch           | 2         | 2.3%    |
| ViewSonic LCD Monitor VSCD22B 1920x1080 520x290mm 23.4-inch            | 1         | 1.15%   |
| Sony TV SNY4B03 1920x1080 930x520mm 41.9-inch                          | 1         | 1.15%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 380x210mm 17.1-inch                | 1         | 1.15%   |
| Sharp LCD Monitor SHP14B9 3840x2160 340x190mm 15.3-inch                | 1         | 1.15%   |
| SDC LCD Monitor 3520x1080                                              | 1         | 1.15%   |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                       | 1         | 1.15%   |
| Samsung Electronics LCD Monitor SDC3754 1600x900 380x210mm 17.1-inch   | 1         | 1.15%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1020x570mm 46.0-inch | 1         | 1.15%   |
| Philips PHL 273V7 PHLC156 1920x1080 600x340mm 27.2-inch                | 1         | 1.15%   |
| Philips LCD Monitor 271P4 3520x1080                                    | 1         | 1.15%   |
| Philips LCD Monitor 271P4                                              | 1         | 1.15%   |
| PANDA LCD Monitor NCP004F 1920x1080 310x170mm 13.9-inch                | 1         | 1.15%   |
| LGD LCD Monitor 1920x1080                                              | 1         | 1.15%   |
| LG Electronics LCD Monitor LX20D 1600x1200                             | 1         | 1.15%   |
| LG Electronics LCD Monitor LG Ultra HD 11520x2160                      | 1         | 1.15%   |
| LG Electronics LCD Monitor LG Ultra HD                                 | 1         | 1.15%   |
| LG Display LCD Monitor LGD062E 1920x1080 340x190mm 15.3-inch           | 1         | 1.15%   |
| LG Display LCD Monitor LGD060A 1920x1080 290x170mm 13.2-inch           | 1         | 1.15%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch           | 1         | 1.15%   |
| LG Display LCD Monitor LGD05F1 1920x1080 310x170mm 13.9-inch           | 1         | 1.15%   |
| LG Display LCD Monitor LGD033E 1366x768 310x170mm 13.9-inch            | 1         | 1.15%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                  | 1         | 1.15%   |
| Lenovo LEN P44w-10 LEN61D5 3840x1200 1050x330mm 43.3-inch              | 1         | 1.15%   |
| InfoVision LCD Monitor IVO8544 1920x1080 290x170mm 13.2-inch           | 1         | 1.15%   |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch           | 1         | 1.15%   |
| Iiyama PL2474H IVM6146 1920x1080 520x290mm 23.4-inch                   | 1         | 1.15%   |
| HJW HDMI TO USB HJW0001 1920x1080 700x390mm 31.5-inch                  | 1         | 1.15%   |
| Hewlett-Packard LCD Monitor LA2306 3520x1080                           | 1         | 1.15%   |
| Hewlett-Packard LA2306 HWP2949 1920x1080 510x290mm 23.1-inch           | 1         | 1.15%   |
| Hewlett-Packard E242 HWP326E 1920x1200 520x320mm 24.0-inch             | 1         | 1.15%   |
| Hewlett-Packard E233 HPN345F 1920x1080 510x290mm 23.1-inch             | 1         | 1.15%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch             | 1         | 1.15%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch             | 1         | 1.15%   |
| Goldstar 27GL650F GSM5B71 1920x1080 530x300mm 24.0-inch                | 1         | 1.15%   |
| Goldstar 27GK750F GSM770F 1920x1080 600x340mm 27.2-inch                | 1         | 1.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 48        | 57.14%  |
| 3840x2160 (4K)    | 7         | 8.33%   |
| 1600x900 (HD+)    | 6         | 7.14%   |
| 2560x1440 (QHD)   | 4         | 4.76%   |
| 1920x1200 (WUXGA) | 4         | 4.76%   |
| 2256x1504         | 3         | 3.57%   |
| 1366x768 (WXGA)   | 3         | 3.57%   |
| 2560x1600         | 2         | 2.38%   |
| Unknown           | 2         | 2.38%   |
| 3840x1200         | 1         | 1.19%   |
| 3520x1080         | 1         | 1.19%   |
| 2160x1440         | 1         | 1.19%   |
| 1600x1200         | 1         | 1.19%   |
| 11520x2160        | 1         | 1.19%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 24        | 28.92%  |
| 15      | 17        | 20.48%  |
| 27      | 9         | 10.84%  |
| Unknown | 8         | 9.64%   |
| 24      | 6         | 7.23%   |
| 23      | 6         | 7.23%   |
| 17      | 3         | 3.61%   |
| 12      | 3         | 3.61%   |
| 46      | 1         | 1.2%    |
| 43      | 1         | 1.2%    |
| 41      | 1         | 1.2%    |
| 32      | 1         | 1.2%    |
| 31      | 1         | 1.2%    |
| 22      | 1         | 1.2%    |
| 21      | 1         | 1.2%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 31        | 37.8%   |
| 501-600     | 19        | 23.17%  |
| 201-300     | 13        | 15.85%  |
| Unknown     | 8         | 9.76%   |
| 351-400     | 3         | 3.66%   |
| 601-700     | 2         | 2.44%   |
| 401-500     | 2         | 2.44%   |
| 1001-1500   | 2         | 2.44%   |
| 701-800     | 1         | 1.22%   |
| 901-1000    | 1         | 1.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 58        | 76.32%  |
| 16/10   | 7         | 9.21%   |
| Unknown | 7         | 9.21%   |
| 3/2     | 3         | 3.95%   |
| 3.18    | 1         | 1.32%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 19        | 22.89%  |
| 91-100         | 12        | 14.46%  |
| 201-250        | 10        | 12.05%  |
| 301-350        | 9         | 10.84%  |
| Unknown        | 8         | 9.64%   |
| 71-80          | 5         | 6.02%   |
| 101-110        | 5         | 6.02%   |
| 251-300        | 4         | 4.82%   |
| 61-70          | 3         | 3.61%   |
| 121-130        | 3         | 3.61%   |
| 501-1000       | 3         | 3.61%   |
| 351-500        | 2         | 2.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 27        | 33.33%  |
| 51-100        | 20        | 24.69%  |
| 161-240       | 14        | 17.28%  |
| 101-120       | 8         | 9.88%   |
| Unknown       | 8         | 9.88%   |
| More than 240 | 3         | 3.7%    |
| 1-50          | 1         | 1.23%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 63        | 53.39%  |
| 0     | 45        | 38.14%  |
| 2     | 9         | 7.63%   |
| 3     | 1         | 0.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 75        | 44.91%  |
| Realtek Semiconductor           | 54        | 32.34%  |
| TP-Link                         | 6         | 3.59%   |
| Broadcom                        | 6         | 3.59%   |
| Ralink Technology               | 4         | 2.4%    |
| Qualcomm Atheros                | 4         | 2.4%    |
| Hewlett-Packard                 | 4         | 2.4%    |
| Edimax Technology               | 2         | 1.2%    |
| D-Link System                   | 2         | 1.2%    |
| Xiaomi                          | 1         | 0.6%    |
| Qualcomm Atheros Communications | 1         | 0.6%    |
| Mellanox Technologies           | 1         | 0.6%    |
| Lenovo                          | 1         | 0.6%    |
| Google                          | 1         | 0.6%    |
| Emulex                          | 1         | 0.6%    |
| BUFFALO                         | 1         | 0.6%    |
| ASUSTek Computer                | 1         | 0.6%    |
| Arduino SA                      | 1         | 0.6%    |
| Aquantia                        | 1         | 0.6%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 41        | 19.9%   |
| Intel Wi-Fi 6 AX200                                                        | 11        | 5.34%   |
| Realtek RTL8125 2.5GbE Controller                                          | 7         | 3.4%    |
| Intel Wireless-AC 9260                                                     | 7         | 3.4%    |
| Intel Comet Lake PCH CNVi WiFi                                             | 7         | 3.4%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                          | 6         | 2.91%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 6         | 2.91%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 6         | 2.91%   |
| Intel Wireless 8265 / 8275                                                 | 5         | 2.43%   |
| Intel I211 Gigabit Network Connection                                      | 5         | 2.43%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 4         | 1.94%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                     | 4         | 1.94%   |
| Intel Wi-Fi 6 AX201                                                        | 4         | 1.94%   |
| Intel I210 Gigabit Network Connection                                      | 4         | 1.94%   |
| Intel 82574L Gigabit Network Connection                                    | 4         | 1.94%   |
| HP hs2350 HSPA+ Mobile Broadband Module Network Adapter                    | 4         | 1.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 3         | 1.46%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 3         | 1.46%   |
| Intel Ethernet Controller I225-V                                           | 3         | 1.46%   |
| Intel Ethernet Connection (14) I219-LM                                     | 3         | 1.46%   |
| Ralink MT7601U Wireless Adapter                                            | 2         | 0.97%   |
| Intel Wireless 7265                                                        | 2         | 0.97%   |
| Intel Wireless 7260                                                        | 2         | 0.97%   |
| Intel Ethernet Connection (4) I219-LM                                      | 2         | 0.97%   |
| Intel Ethernet Connection (11) I219-LM                                     | 2         | 0.97%   |
| Intel Ethernet Connection (10) I219-V                                      | 2         | 0.97%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 2         | 0.97%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 2         | 0.97%   |
| Unknown                                                                    | 2         | 0.97%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                       | 1         | 0.49%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                     | 1         | 0.49%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]        | 1         | 0.49%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                   | 1         | 0.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 0.49%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                     | 1         | 0.49%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 1         | 0.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 1         | 0.49%   |
| Ralink RT5370 Wireless Adapter                                             | 1         | 0.49%   |
| Ralink RT2870/RT3070 Wireless Adapter                                      | 1         | 0.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 1         | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 61        | 64.21%  |
| Realtek Semiconductor           | 9         | 9.47%   |
| TP-Link                         | 6         | 6.32%   |
| Broadcom                        | 5         | 5.26%   |
| Ralink Technology               | 4         | 4.21%   |
| Qualcomm Atheros                | 3         | 3.16%   |
| Edimax Technology               | 2         | 2.11%   |
| D-Link System                   | 2         | 2.11%   |
| Qualcomm Atheros Communications | 1         | 1.05%   |
| BUFFALO                         | 1         | 1.05%   |
| ASUSTek Computer                | 1         | 1.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                           | 11        | 11.58%  |
| Intel Wireless-AC 9260                                                        | 7         | 7.37%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 7         | 7.37%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 6         | 6.32%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 6         | 6.32%   |
| Intel Wireless 8265 / 8275                                                    | 5         | 5.26%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 4         | 4.21%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 4         | 4.21%   |
| Intel Wi-Fi 6 AX201                                                           | 4         | 4.21%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 3         | 3.16%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 3         | 3.16%   |
| Ralink MT7601U Wireless Adapter                                               | 2         | 2.11%   |
| Intel Wireless 7265                                                           | 2         | 2.11%   |
| Intel Wireless 7260                                                           | 2         | 2.11%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2         | 2.11%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]    | 2         | 2.11%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1         | 1.05%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]           | 1         | 1.05%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                      | 1         | 1.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.05%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                        | 1         | 1.05%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 1.05%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1         | 1.05%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1         | 1.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 1         | 1.05%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 1         | 1.05%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1         | 1.05%   |
| Intel Wireless 8260                                                           | 1         | 1.05%   |
| Intel Wi-Fi 6 AX201 160MHz                                                    | 1         | 1.05%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 1         | 1.05%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 1.05%   |
| Intel Centrino Advanced-N 6235                                                | 1         | 1.05%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                | 1         | 1.05%   |
| Edimax EW-7711MAC 802.11ac Wireless Adapter                                   | 1         | 1.05%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]                      | 1         | 1.05%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                   | 1         | 1.05%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 1         | 1.05%   |
| Broadcom BCM4331 802.11a/b/g/n                                                | 1         | 1.05%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 1         | 1.05%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 1         | 1.05%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 47        | 48.45%  |
| Intel                 | 42        | 43.3%   |
| Broadcom              | 2         | 2.06%   |
| Xiaomi                | 1         | 1.03%   |
| Qualcomm Atheros      | 1         | 1.03%   |
| Lenovo                | 1         | 1.03%   |
| Google                | 1         | 1.03%   |
| Emulex                | 1         | 1.03%   |
| Aquantia              | 1         | 1.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 41        | 40.2%   |
| Realtek RTL8125 2.5GbE Controller                                             | 6         | 5.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6         | 5.88%   |
| Intel I211 Gigabit Network Connection                                         | 5         | 4.9%    |
| Intel I210 Gigabit Network Connection                                         | 4         | 3.92%   |
| Intel 82574L Gigabit Network Connection                                       | 4         | 3.92%   |
| Intel Ethernet Controller I225-V                                              | 3         | 2.94%   |
| Intel Ethernet Connection (14) I219-LM                                        | 3         | 2.94%   |
| Intel Ethernet Connection (4) I219-LM                                         | 2         | 1.96%   |
| Intel Ethernet Connection (11) I219-LM                                        | 2         | 1.96%   |
| Intel Ethernet Connection (10) I219-V                                         | 2         | 1.96%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                          | 1         | 0.98%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1         | 0.98%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 0.98%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1         | 0.98%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                              | 1         | 0.98%   |
| Intel I350 Gigabit Network Connection                                         | 1         | 0.98%   |
| Intel Ethernet Controller I225-LM                                             | 1         | 0.98%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 1         | 0.98%   |
| Intel Ethernet Connection I219-LM                                             | 1         | 0.98%   |
| Intel Ethernet Connection I218-LM                                             | 1         | 0.98%   |
| Intel Ethernet Connection I217-LM                                             | 1         | 0.98%   |
| Intel Ethernet Connection (7) I219-V                                          | 1         | 0.98%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1         | 0.98%   |
| Intel Ethernet Connection (5) I219-V                                          | 1         | 0.98%   |
| Intel Ethernet Connection (3) I218-LM                                         | 1         | 0.98%   |
| Intel Ethernet Connection (13) I219-V                                         | 1         | 0.98%   |
| Intel Ethernet Connection (11) I219-V                                         | 1         | 0.98%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 0.98%   |
| Google Nexus/Pixel Device (charging + debug)                                  | 1         | 0.98%   |
| Emulex OneConnect 10Gb NIC (be3)                                              | 1         | 0.98%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                             | 1         | 0.98%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 1         | 0.98%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 1         | 0.98%   |
| Unknown                                                                       | 1         | 0.98%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 89        | 50.57%  |
| WiFi     | 78        | 44.32%  |
| Modem    | 6         | 3.41%   |
| Unknown  | 3         | 1.7%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 74        | 59.68%  |
| WiFi     | 47        | 37.9%   |
| Modem    | 3         | 2.42%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 60        | 52.17%  |
| 1     | 30        | 26.09%  |
| 0     | 14        | 12.17%  |
| 3     | 8         | 6.96%   |
| 4     | 2         | 1.74%   |
| 7     | 1         | 0.87%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 99        | 81.82%  |
| Yes  | 22        | 18.18%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 46        | 76.67%  |
| Apple                           | 4         | 6.67%   |
| IMC Networks                    | 3         | 5%      |
| Realtek Semiconductor           | 2         | 3.33%   |
| Realtek                         | 1         | 1.67%   |
| Qualcomm Atheros Communications | 1         | 1.67%   |
| Opticis                         | 1         | 1.67%   |
| Cambridge Silicon Radio         | 1         | 1.67%   |
| Broadcom                        | 1         | 1.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 15        | 25%     |
| Intel AX200 Bluetooth                               | 10        | 16.67%  |
| Intel Bluetooth wireless interface                  | 7         | 11.67%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 6         | 10%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 6.67%   |
| Intel AX210 Bluetooth                               | 3         | 5%      |
| Apple Bluetooth Host Controller                     | 2         | 3.33%   |
| Realtek  Bluetooth Adapter                          | 1         | 1.67%   |
| Realtek Bluetooth Radio                             | 1         | 1.67%   |
| Realtek Bluetooth Radio                             | 1         | 1.67%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.67%   |
| Opticis Bluetooth Radio                             | 1         | 1.67%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.67%   |
| IMC Networks Realtek Bluetooth Adapter              | 1         | 1.67%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.67%   |
| IMC Networks Bluetooth module                       | 1         | 1.67%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.67%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.67%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 1.67%   |
| Apple Apple Broadcom Built-in Bluetooth             | 1         | 1.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 56        | 39.16%  |
| AMD                     | 44        | 30.77%  |
| Nvidia                  | 28        | 19.58%  |
| Lenovo                  | 3         | 2.1%    |
| Yamaha                  | 1         | 0.7%    |
| Texas Instruments       | 1         | 0.7%    |
| SteelSeries ApS         | 1         | 0.7%    |
| Logitech                | 1         | 0.7%    |
| JMTek                   | 1         | 0.7%    |
| GN Netcom               | 1         | 0.7%    |
| Generalplus Technology  | 1         | 0.7%    |
| CMX Systems             | 1         | 0.7%    |
| C-Media Electronics     | 1         | 0.7%    |
| Blue Microphones        | 1         | 0.7%    |
| AudioQuest              | 1         | 0.7%    |
| AKAI  Professional M.I. | 1         | 0.7%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                  | 25        | 14.12%  |
| AMD Renoir Radeon High Definition Audio Controller                      | 13        | 7.34%   |
| Intel Comet Lake PCH cAVS                                               | 10        | 5.65%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                     | 10        | 5.65%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller     | 9         | 5.08%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller             | 6         | 3.39%   |
| Intel Comet Lake PCH-LP cAVS                                            | 6         | 3.39%   |
| Intel Cannon Lake PCH cAVS                                              | 6         | 3.39%   |
| AMD Starship/Matisse HD Audio Controller                                | 6         | 3.39%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller          | 5         | 2.82%   |
| Nvidia GP107GL High Definition Audio Controller                         | 5         | 2.82%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                     | 4         | 2.26%   |
| Nvidia TU116 High Definition Audio Controller                           | 3         | 1.69%   |
| Intel Tiger Lake-H HD Audio Controller                                  | 3         | 1.69%   |
| Intel Sunrise Point-LP HD Audio                                         | 3         | 1.69%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]               | 3         | 1.69%   |
| Unknown                                                                 | 3         | 1.69%   |
| Nvidia GP108 High Definition Audio Controller                           | 2         | 1.13%   |
| Nvidia GK208 HDMI/DP Audio Controller                                   | 2         | 1.13%   |
| Nvidia GK107 HDMI Audio Controller                                      | 2         | 1.13%   |
| Nvidia GA104 High Definition Audio Controller                           | 2         | 1.13%   |
| Intel Wildcat Point-LP High Definition Audio Controller                 | 2         | 1.13%   |
| Intel Broadwell-U Audio Controller                                      | 2         | 1.13%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller     | 2         | 1.13%   |
| AMD SBx00 Azalia (Intel HDA)                                            | 2         | 1.13%   |
| AMD Rembrandt Radeon High Definition Audio Controller                   | 2         | 1.13%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 2         | 1.13%   |
| AMD Navi 10 HDMI Audio                                                  | 2         | 1.13%   |
| Yamaha Steinberg UR12                                                   | 1         | 0.56%   |
| Texas Instruments PCM2706 stereo audio DAC                              | 1         | 0.56%   |
| SteelSeries ApS SteelSeries Siberia 350                                 | 1         | 0.56%   |
| Nvidia TU106 High Definition Audio Controller                           | 1         | 0.56%   |
| Nvidia TU104 HD Audio Controller                                        | 1         | 0.56%   |
| Nvidia High Definition Audio Controller                                 | 1         | 0.56%   |
| Nvidia GP106 High Definition Audio Controller                           | 1         | 0.56%   |
| Nvidia GM206 High Definition Audio Controller                           | 1         | 0.56%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]           | 1         | 0.56%   |
| Logitech H390 headset with microphone                                   | 1         | 0.56%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                | 1         | 0.56%   |
| Lenovo ThinkPad Dock Audio                                              | 1         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 22        | 20%     |
| SK hynix               | 15        | 13.64%  |
| Micron Technology      | 15        | 13.64%  |
| Kingston               | 13        | 11.82%  |
| Crucial                | 10        | 9.09%   |
| Unknown                | 5         | 4.55%   |
| Corsair                | 5         | 4.55%   |
| Smart                  | 3         | 2.73%   |
| Ramaxel Technology     | 3         | 2.73%   |
| Unknown                | 3         | 2.73%   |
| Team                   | 2         | 1.82%   |
| Goodram                | 2         | 1.82%   |
| G.Skill                | 2         | 1.82%   |
| A-DATA Technology      | 2         | 1.82%   |
| Unknown (000000000C01) | 1         | 0.91%   |
| Transcend              | 1         | 0.91%   |
| PNY                    | 1         | 0.91%   |
| Neo Forza              | 1         | 0.91%   |
| KLEVV                  | 1         | 0.91%   |
| Gold Key               | 1         | 0.91%   |
| Elpida                 | 1         | 0.91%   |
| 06F100000C01           | 1         | 0.91%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s      | 4         | 3.57%   |
| Unknown                                                    | 3         | 2.68%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s     | 2         | 1.79%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s     | 2         | 1.79%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s     | 2         | 1.79%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s    | 2         | 1.79%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s      | 2         | 1.79%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s      | 2         | 1.79%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s       | 2         | 1.79%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s       | 2         | 1.79%   |
| Crucial RAM BL32G32C16S4B.M16FB1 32GB SODIMM DDR4 2667MT/s | 2         | 1.79%   |
| Corsair RAM CMK32GX4M2D3200C16 16GB DIMM DDR4 3200MT/s     | 2         | 1.79%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                  | 1         | 0.89%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                | 1         | 0.89%   |
| Unknown RAM Module 1GB SODIMM DDR                          | 1         | 0.89%   |
| Unknown RAM 3000 C16 Series 4096MB DIMM DDR4 2933MT/s      | 1         | 0.89%   |
| Unknown RAM 2G-08-10-12-1333 2GB DIMM DDR3 1333MT/s        | 1         | 0.89%   |
| Unknown (000000000C01) RAM Module 32GB DIMM DDR4 3200MT/s  | 1         | 0.89%   |
| Transcend RAM JM2666HLE-32G 32GB DIMM DDR4 2666MT/s        | 1         | 0.89%   |
| Team RAM TEAMGROUP-UD4-4133 8GB DIMM DDR4 4133MT/s         | 1         | 0.89%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s       | 1         | 0.89%   |
| Smart RAM SF4641G8CK8IWGKSEG 8GB SODIMM DDR4 2133MT/s      | 1         | 0.89%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s      | 1         | 0.89%   |
| Smart RAM Module 8GB DIMM DDR4 2667MT/s                    | 1         | 0.89%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1867MT/s               | 1         | 0.89%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s               | 1         | 0.89%   |
| SK hynix RAM HMAA4GU6CJR8N-XN 32GB DIMM DDR4 3200MT/s      | 1         | 0.89%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s    | 1         | 0.89%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s     | 1         | 0.89%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s     | 1         | 0.89%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s     | 1         | 0.89%   |
| Samsung RAM M474A4G43AB1-CVF 32GB SODIMM DDR4 2933MT/s     | 1         | 0.89%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s      | 1         | 0.89%   |
| Samsung RAM M471B5674-M0-YK0 4GB Chip DDR3 1600MT/s        | 1         | 0.89%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s      | 1         | 0.89%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s      | 1         | 0.89%   |
| Samsung RAM M471A5244BB0-CWE 4GB SODIMM DDR4 3200MT/s      | 1         | 0.89%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s     | 1         | 0.89%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s     | 1         | 0.89%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s     | 1         | 0.89%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 77        | 78.57%  |
| DDR3   | 16        | 16.33%  |
| LPDDR5 | 2         | 2.04%   |
| LPDDR4 | 1         | 1.02%   |
| LPDDR3 | 1         | 1.02%   |
| DDR    | 1         | 1.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 64        | 65.31%  |
| DIMM         | 28        | 28.57%  |
| Row Of Chips | 5         | 5.1%    |
| Chip         | 1         | 1.02%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 39        | 38.61%  |
| 16384 | 30        | 29.7%   |
| 32768 | 15        | 14.85%  |
| 4096  | 13        | 12.87%  |
| 2048  | 3         | 2.97%   |
| 1024  | 1         | 0.99%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 37        | 36.27%  |
| 2667    | 21        | 20.59%  |
| 2400    | 8         | 7.84%   |
| 1600    | 8         | 7.84%   |
| 1867    | 6         | 5.88%   |
| 2666    | 4         | 3.92%   |
| 2933    | 3         | 2.94%   |
| 2133    | 3         | 2.94%   |
| 3600    | 2         | 1.96%   |
| 1333    | 2         | 1.96%   |
| 6400    | 1         | 0.98%   |
| 4267    | 1         | 0.98%   |
| 4266    | 1         | 0.98%   |
| 4133    | 1         | 0.98%   |
| 3000    | 1         | 0.98%   |
| 1866    | 1         | 0.98%   |
| 1334    | 1         | 0.98%   |
| Unknown | 1         | 0.98%   |

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
| Chicony Electronics                    | 15        | 21.74%  |
| IMC Networks                           | 10        | 14.49%  |
| Logitech                               | 8         | 11.59%  |
| Realtek Semiconductor                  | 6         | 8.7%    |
| Microdia                               | 6         | 8.7%    |
| Lite-On Technology                     | 5         | 7.25%   |
| Acer                                   | 5         | 7.25%   |
| Sunplus Innovation Technology          | 4         | 5.8%    |
| Cheng Uei Precision Industry (Foxlink) | 3         | 4.35%   |
| Syntek                                 | 2         | 2.9%    |
| Apple                                  | 2         | 2.9%    |
| SunplusIT                              | 1         | 1.45%   |
| GEMBIRD                                | 1         | 1.45%   |
| Aveo Technology                        | 1         | 1.45%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                             | 7         | 10%     |
| Chicony Integrated Camera                                                  | 7         | 10%     |
| Sunplus Integrated_Webcam_HD                                               | 3         | 4.29%   |
| Logitech Webcam C270                                                       | 3         | 4.29%   |
| Lite-On Integrated Camera                                                  | 3         | 4.29%   |
| Chicony Integrated HP HD Webcam                                            | 3         | 4.29%   |
| Acer Integrated Camera                                                     | 3         | 4.29%   |
| Realtek Laptop Camera                                                      | 2         | 2.86%   |
| Realtek Integrated_Webcam_HD                                               | 2         | 2.86%   |
| Microdia Integrated Webcam                                                 | 2         | 2.86%   |
| Microdia HP Integrated Webcam                                              | 2         | 2.86%   |
| Logitech C920 PRO HD Webcam                                                | 2         | 2.86%   |
| Lite-On HP HD Camera                                                       | 2         | 2.86%   |
| Chicony ThinkPad T490 Webcam                                               | 2         | 2.86%   |
| Apple FaceTime HD Camera (Built-in)                                        | 2         | 2.86%   |
| Acer HD Webcam                                                             | 2         | 2.86%   |
| Syntek Lenovo EasyCamera                                                   | 1         | 1.43%   |
| Syntek Integrated Camera                                                   | 1         | 1.43%   |
| SunplusIT XiaoMi USB 2.0 Webcam                                            | 1         | 1.43%   |
| Sunplus Integrated_Webcam_FHD                                              | 1         | 1.43%   |
| Realtek USB 2 Webcam                                                       | 1         | 1.43%   |
| Realtek Realtek USB2.0 PC Camera                                           | 1         | 1.43%   |
| Microdia USB 2.0 Camera                                                    | 1         | 1.43%   |
| Microdia Dell Integrated HD Webcam                                         | 1         | 1.43%   |
| Logitech Webcam C170                                                       | 1         | 1.43%   |
| Logitech HD Pro Webcam C920                                                | 1         | 1.43%   |
| Logitech C505 HD Webcam                                                    | 1         | 1.43%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 1         | 1.43%   |
| IMC Networks HD Camera                                                     | 1         | 1.43%   |
| IMC Networks EasyCamera                                                    | 1         | 1.43%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]                          | 1         | 1.43%   |
| Chicony USB2.0 0.3M UVC WebCam                                             | 1         | 1.43%   |
| Chicony Integrated IR Camera                                               | 1         | 1.43%   |
| Chicony HD Webcam                                                          | 1         | 1.43%   |
| Chicony Chicony USB2.0 Camera                                              | 1         | 1.43%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 1.43%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed]                | 1         | 1.43%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam   | 1         | 1.43%   |
| Aveo USB2.0 Camera                                                         | 1         | 1.43%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 9         | 42.86%  |
| Validity Sensors           | 5         | 23.81%  |
| Shenzhen Goodix Technology | 5         | 23.81%  |
| Focal-systems.Corp         | 1         | 4.76%   |
| AuthenTec                  | 1         | 4.76%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 6         | 28.57%  |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 14.29%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 9.52%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 9.52%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 9.52%   |
| Shenzhen Goodix  FingerPrint Device                                        | 2         | 9.52%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 4.76%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 4.76%   |
| Focal-systems.Corp FocalTech Fingerprint reader                            | 1         | 4.76%   |
| AuthenTec AES2810                                                          | 1         | 4.76%   |

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
| 0     | 33        | 27.73%  |
| 2     | 32        | 26.89%  |
| 1     | 23        | 19.33%  |
| 4     | 16        | 13.45%  |
| 3     | 10        | 8.4%    |
| 5     | 4         | 3.36%   |
| 9     | 1         | 0.84%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 64        | 37.43%  |
| Bluetooth                | 35        | 20.47%  |
| Net/wireless             | 27        | 15.79%  |
| Fingerprint reader       | 20        | 11.7%   |
| Card reader              | 9         | 5.26%   |
| Sound                    | 5         | 2.92%   |
| Network                  | 4         | 2.34%   |
| Net/ethernet             | 4         | 2.34%   |
| Firewire controller      | 2         | 1.17%   |
| Modem                    | 1         | 0.58%   |

