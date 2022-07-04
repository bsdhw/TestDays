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

Total: 184

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Dell          | Latitude 5521               | Notebook    | [2c9d24a69e](https://bsd-hardware.info/?probe=2c9d24a69e) | Jun 19, 2022 |
| Dell          | Latitude 5410               | Notebook    | [3334ff3727](https://bsd-hardware.info/?probe=3334ff3727) | Jun 06, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [1067f6ab27](https://bsd-hardware.info/?probe=1067f6ab27) | Jun 03, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [3d0fdb11ff](https://bsd-hardware.info/?probe=3d0fdb11ff) | May 27, 2022 |
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
| HP            | EliteBook 8570p             | Notebook    | [c4dee3f070](https://bsd-hardware.info/?probe=c4dee3f070) | Apr 21, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [d9acb17caf](https://bsd-hardware.info/?probe=d9acb17caf) | Apr 20, 2022 |
| Dell          | 0FKD45 A03                  | Server      | [dde6af4613](https://bsd-hardware.info/?probe=dde6af4613) | Apr 19, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [ee73e0cddb](https://bsd-hardware.info/?probe=ee73e0cddb) | Apr 07, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [0c73871c49](https://bsd-hardware.info/?probe=0c73871c49) | Apr 04, 2022 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [1868573e9a](https://bsd-hardware.info/?probe=1868573e9a) | Apr 02, 2022 |
| Lenovo        | ThinkPad X260 20F5A28AUK    | Notebook    | [f53c625efd](https://bsd-hardware.info/?probe=f53c625efd) | Mar 30, 2022 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | Notebook    | [859a429ad0](https://bsd-hardware.info/?probe=859a429ad0) | Mar 24, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [e9f59e748e](https://bsd-hardware.info/?probe=e9f59e748e) | Mar 24, 2022 |
| Dell          | 0DNFFW A00                  | All in one  | [30432daccb](https://bsd-hardware.info/?probe=30432daccb) | Mar 23, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [6858ad2b12](https://bsd-hardware.info/?probe=6858ad2b12) | Mar 22, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [7e1e137c8f](https://bsd-hardware.info/?probe=7e1e137c8f) | Mar 20, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [dafb1bbb92](https://bsd-hardware.info/?probe=dafb1bbb92) | Mar 20, 2022 |
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
| HP            | EliteBook 8570p             | Notebook    | [1520fece28](https://bsd-hardware.info/?probe=1520fece28) | Jan 17, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [5f106ee686](https://bsd-hardware.info/?probe=5f106ee686) | Jan 15, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [825d20fcf7](https://bsd-hardware.info/?probe=825d20fcf7) | Jan 14, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b953d9d2e6](https://bsd-hardware.info/?probe=b953d9d2e6) | Jan 13, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20T20... | Notebook    | [6836fc60f6](https://bsd-hardware.info/?probe=6836fc60f6) | Jan 09, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [2cc4698cbc](https://bsd-hardware.info/?probe=2cc4698cbc) | Jan 09, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [2481037b2a](https://bsd-hardware.info/?probe=2481037b2a) | Jan 09, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [6c208c85a5](https://bsd-hardware.info/?probe=6c208c85a5) | Jan 06, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [7ea8daae8d](https://bsd-hardware.info/?probe=7ea8daae8d) | Jan 05, 2022 |
| ASUSTek       | TUF GAMING B550-PLUS        | Desktop     | [ea4719600a](https://bsd-hardware.info/?probe=ea4719600a) | Jan 05, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [1bbb37d4c6](https://bsd-hardware.info/?probe=1bbb37d4c6) | Jan 03, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [0a180d834c](https://bsd-hardware.info/?probe=0a180d834c) | Jan 03, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [e67007df20](https://bsd-hardware.info/?probe=e67007df20) | Jan 01, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [b956c2a933](https://bsd-hardware.info/?probe=b956c2a933) | Dec 28, 2021 |
| friendlyel... | nanopi-m4                   | Desktop     | [bb29e50061](https://bsd-hardware.info/?probe=bb29e50061) | Dec 27, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [42b4bcbcc2](https://bsd-hardware.info/?probe=42b4bcbcc2) | Dec 27, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [695d7201d4](https://bsd-hardware.info/?probe=695d7201d4) | Dec 27, 2021 |
| khadas        | edge-v                      | Desktop     | [42c428aac0](https://bsd-hardware.info/?probe=42c428aac0) | Dec 26, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [44d3e7366c](https://bsd-hardware.info/?probe=44d3e7366c) | Dec 20, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [b872e9b044](https://bsd-hardware.info/?probe=b872e9b044) | Dec 18, 2021 |
| HP            | ProBook 440 G6              | Notebook    | [7a8a66430a](https://bsd-hardware.info/?probe=7a8a66430a) | Dec 13, 2021 |
| HP            | ProBook 440 G6              | Notebook    | [f3c014b120](https://bsd-hardware.info/?probe=f3c014b120) | Dec 12, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [045ffeb9b3](https://bsd-hardware.info/?probe=045ffeb9b3) | Dec 12, 2021 |
| Unknown       | Unknown                     | Desktop     | [b726a1b3e3](https://bsd-hardware.info/?probe=b726a1b3e3) | Dec 11, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [9a8d19aa04](https://bsd-hardware.info/?probe=9a8d19aa04) | Dec 11, 2021 |
| Unknown       | Unknown                     | Desktop     | [7633cb9296](https://bsd-hardware.info/?probe=7633cb9296) | Dec 11, 2021 |
| ASUSTek       | 1215B                       | Notebook    | [6dbcac684f](https://bsd-hardware.info/?probe=6dbcac684f) | Dec 04, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [92fc69392b](https://bsd-hardware.info/?probe=92fc69392b) | Nov 27, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [d3888a4c7d](https://bsd-hardware.info/?probe=d3888a4c7d) | Nov 21, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [822a2481bb](https://bsd-hardware.info/?probe=822a2481bb) | Nov 17, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [ea51e03be6](https://bsd-hardware.info/?probe=ea51e03be6) | Nov 13, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [28a264a128](https://bsd-hardware.info/?probe=28a264a128) | Nov 09, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [d0b487888a](https://bsd-hardware.info/?probe=d0b487888a) | Nov 08, 2021 |
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
| HP            | EliteBook 8570p             | Notebook    | [1b48acadd5](https://bsd-hardware.info/?probe=1b48acadd5) | Oct 10, 2021 |
| Framework     | Laptop                      | Notebook    | [e5aca4b7d0](https://bsd-hardware.info/?probe=e5aca4b7d0) | Oct 02, 2021 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [1aa5ced5a0](https://bsd-hardware.info/?probe=1aa5ced5a0) | Sep 23, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [646148fc25](https://bsd-hardware.info/?probe=646148fc25) | Sep 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [0b73df29bf](https://bsd-hardware.info/?probe=0b73df29bf) | Sep 15, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [5a4e53da56](https://bsd-hardware.info/?probe=5a4e53da56) | Sep 12, 2021 |
| Lenovo        | ThinkPad X395 20NL000GPG    | Notebook    | [d7812a2905](https://bsd-hardware.info/?probe=d7812a2905) | Sep 10, 2021 |
| Lenovo        | ThinkPad X395 20NL000GPG    | Notebook    | [cdde22fb04](https://bsd-hardware.info/?probe=cdde22fb04) | Sep 10, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [7a289e8d1b](https://bsd-hardware.info/?probe=7a289e8d1b) | Sep 06, 2021 |
| Gigabyte      | X399 DESIGNARE EX-CF        | Desktop     | [a78cc6a11b](https://bsd-hardware.info/?probe=a78cc6a11b) | Sep 04, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [fae9e84f60](https://bsd-hardware.info/?probe=fae9e84f60) | Aug 27, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [76f004bd26](https://bsd-hardware.info/?probe=76f004bd26) | Aug 26, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [a98c6adb40](https://bsd-hardware.info/?probe=a98c6adb40) | Aug 22, 2021 |
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
| Lenovo        | XiaoXinPro-13ARE 2020 82... | Notebook    | [e0e6f62814](https://bsd-hardware.info/?probe=e0e6f62814) | Jul 19, 2021 |
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
| HP            | EliteBook 8570p             | Notebook    | [062fe5ec40](https://bsd-hardware.info/?probe=062fe5ec40) | May 09, 2021 |
| Dell          | G5 5505                     | Notebook    | [ba74d8eee0](https://bsd-hardware.info/?probe=ba74d8eee0) | May 08, 2021 |
| Dell          | G5 5505                     | Notebook    | [23ae99e489](https://bsd-hardware.info/?probe=23ae99e489) | May 08, 2021 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | Notebook    | [2be8cf963c](https://bsd-hardware.info/?probe=2be8cf963c) | May 02, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [c2d56fc369](https://bsd-hardware.info/?probe=c2d56fc369) | Apr 29, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [e90abb54c9](https://bsd-hardware.info/?probe=e90abb54c9) | Apr 25, 2021 |
| pine64        | pinebook-pro-rk3399         | Desktop     | [79713a2668](https://bsd-hardware.info/?probe=79713a2668) | Apr 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [4993ad0feb](https://bsd-hardware.info/?probe=4993ad0feb) | Apr 25, 2021 |
| pine64        | pinebook-pro-rk3399         | Desktop     | [0f04e5f048](https://bsd-hardware.info/?probe=0f04e5f048) | Apr 11, 2021 |
| HUAWEI        | HN-WX9X                     | Notebook    | [d776625073](https://bsd-hardware.info/?probe=d776625073) | Apr 11, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [d9ec051372](https://bsd-hardware.info/?probe=d9ec051372) | Apr 06, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [325186171a](https://bsd-hardware.info/?probe=325186171a) | Apr 02, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [cdeafa0952](https://bsd-hardware.info/?probe=cdeafa0952) | Apr 02, 2021 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [342e914968](https://bsd-hardware.info/?probe=342e914968) | Mar 29, 2021 |
| pine64        | pinebook-pro-rk3399         | Desktop     | [ea524ab4c4](https://bsd-hardware.info/?probe=ea524ab4c4) | Mar 28, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [ed80dc9019](https://bsd-hardware.info/?probe=ed80dc9019) | Mar 27, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [dd877e6c6c](https://bsd-hardware.info/?probe=dd877e6c6c) | Mar 27, 2021 |
| pine64        | pinebook-pro-rk3399         | Desktop     | [835da13d39](https://bsd-hardware.info/?probe=835da13d39) | Mar 18, 2021 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [cc3151bc6f](https://bsd-hardware.info/?probe=cc3151bc6f) | Mar 17, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [e3f20f8770](https://bsd-hardware.info/?probe=e3f20f8770) | Mar 17, 2021 |
| Lenovo        | ThinkPad X395 20NL001SMX    | Notebook    | [cd016e96ee](https://bsd-hardware.info/?probe=cd016e96ee) | Mar 17, 2021 |
| MSI           | B450 GAMING PLUS            | Desktop     | [547fd655f0](https://bsd-hardware.info/?probe=547fd655f0) | Mar 13, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [9fed35d792](https://bsd-hardware.info/?probe=9fed35d792) | Mar 10, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [1fcde7c0e1](https://bsd-hardware.info/?probe=1fcde7c0e1) | Mar 09, 2021 |
| pine64        | pinebook-pro-rk3399         | Desktop     | [c00bcdcc87](https://bsd-hardware.info/?probe=c00bcdcc87) | Mar 06, 2021 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | Notebook    | [f2c2e5345a](https://bsd-hardware.info/?probe=f2c2e5345a) | Feb 27, 2021 |
| pine64        | pinebook-pro-rk3399         | Desktop     | [3abcd73d48](https://bsd-hardware.info/?probe=3abcd73d48) | Feb 26, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [29936dd1c0](https://bsd-hardware.info/?probe=29936dd1c0) | Feb 25, 2021 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | Notebook    | [aacafb6ace](https://bsd-hardware.info/?probe=aacafb6ace) | Feb 24, 2021 |
| Unknown       | Unknown                     | Desktop     | [74b11992d7](https://bsd-hardware.info/?probe=74b11992d7) | Feb 20, 2021 |
| Raspberry ... | rpi                         | Desktop     | [92ee9b3619](https://bsd-hardware.info/?probe=92ee9b3619) | Feb 18, 2021 |
| pine64        | pinebook-pro-rk3399         | Desktop     | [b750f83194](https://bsd-hardware.info/?probe=b750f83194) | Feb 17, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [a601b10377](https://bsd-hardware.info/?probe=a601b10377) | Feb 16, 2021 |
| A-DATA Tec... | XENIA159GENI72060           | Notebook    | [be88e8f865](https://bsd-hardware.info/?probe=be88e8f865) | Feb 15, 2021 |
| Lenovo        | ThinkPad T495s 20QKS1812... | Notebook    | [0e5e228d18](https://bsd-hardware.info/?probe=0e5e228d18) | Feb 13, 2021 |
| Lenovo        | ThinkPad T495s 20QKS1812... | Notebook    | [2d93a6bebc](https://bsd-hardware.info/?probe=2d93a6bebc) | Feb 13, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [ba7f82b343](https://bsd-hardware.info/?probe=ba7f82b343) | Feb 12, 2021 |
| Matsushita... | CF-T2BW1AXR                 | Notebook    | [f6ec2858a5](https://bsd-hardware.info/?probe=f6ec2858a5) | Feb 10, 2021 |
| pine64        | pinebook-pro-rk3399         | Desktop     | [2befc5e754](https://bsd-hardware.info/?probe=2befc5e754) | Feb 10, 2021 |
| pine64        | pinebook-pro-rk3399         | Desktop     | [5a55b22f44](https://bsd-hardware.info/?probe=5a55b22f44) | Feb 09, 2021 |
| Dell          | 0D9JG3 A00                  | Desktop     | [65dd4083c5](https://bsd-hardware.info/?probe=65dd4083c5) | Feb 09, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [72137c63f8](https://bsd-hardware.info/?probe=72137c63f8) | Feb 09, 2021 |
| pine64        | pinebook-pro-rk3399         | Desktop     | [97e72f0066](https://bsd-hardware.info/?probe=97e72f0066) | Feb 06, 2021 |
| Dell          | Latitude E5430 vPro         | Notebook    | [bee421a110](https://bsd-hardware.info/?probe=bee421a110) | Feb 06, 2021 |
| Dell          | Latitude E5430 vPro         | Notebook    | [e8157ac6a3](https://bsd-hardware.info/?probe=e8157ac6a3) | Feb 06, 2021 |
| Lenovo        | ThinkPad T430 2349H2G       | Notebook    | [229db16a93](https://bsd-hardware.info/?probe=229db16a93) | Feb 05, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [46c938b853](https://bsd-hardware.info/?probe=46c938b853) | Feb 01, 2021 |
| pine64        | pinebook-pro-rk3399         | Desktop     | [1720175648](https://bsd-hardware.info/?probe=1720175648) | Jan 27, 2021 |
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
| amd64 | 81        | 83.51%  |
| arm64 | 12        | 12.37%  |
| arm   | 2         | 2.06%   |
| riscv | 1         | 1.03%   |
| i386  | 1         | 1.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KDE5          | 27        | 26.21%  |
| Console       | 23        | 22.33%  |
| XFCE          | 11        | 10.68%  |
| MATE          | 8         | 7.77%   |
| TWM           | 6         | 5.83%   |
| i3            | 5         | 4.85%   |
| GNOME         | 5         | 4.85%   |
| Openbox       | 3         | 2.91%   |
| Cinnamon      | 3         | 2.91%   |
| LXDE          | 2         | 1.94%   |
| Lumina        | 2         | 1.94%   |
| Xfwm4         | 1         | 0.97%   |
| Picom         | 1         | 0.97%   |
| LXQt          | 1         | 0.97%   |
| GNUstep       | 1         | 0.97%   |
| Fluxbox       | 1         | 0.97%   |
| Enlightenment | 1         | 0.97%   |
| ctwm          | 1         | 0.97%   |
| akonadi_newm  | 1         | 0.97%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 71        | 70.3%   |
| Console | 28        | 27.72%  |
| Wayland | 2         | 1.98%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 44        | 44%     |
| SDDM    | 24        | 24%     |
| SLiM    | 12        | 12%     |
| GDM     | 10        | 10%     |
| XDM     | 6         | 6%      |
| LightDM | 3         | 3%      |
| Ly      | 1         | 1%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Computers | Percent |
|------------------|-----------|---------|
| C                | 64        | 64%     |
| en_US            | 12        | 12%     |
| Unknown          | 5         | 5%      |
| de_DE            | 4         | 4%      |
| uk_UA            | 3         | 3%      |
| en_GB            | 3         | 3%      |
| zh_CN            | 2         | 2%      |
| sv_SE            | 1         | 1%      |
| ru_RU            | 1         | 1%      |
| pt_PT            | 1         | 1%      |
| pl_PL            | 1         | 1%      |
| it_IT.ISO8859-15 | 1         | 1%      |
| fr_FR            | 1         | 1%      |
| de_CH            | 1         | 1%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 85        | 87.63%  |
| BIOS | 12        | 12.37%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 69        | 71.13%  |
| Ufs  | 28        | 28.87%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 88        | 90.72%  |
| MBR  | 9         | 9.28%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 24        | 24.74%  |
| ASUSTek Computer               | 11        | 11.34%  |
| Dell                           | 10        | 10.31%  |
| Hewlett-Packard                | 9         | 9.28%   |
| Unknown                        | 9         | 9.28%   |
| Gigabyte Technology            | 7         | 7.22%   |
| Raspberry Pi Foundation        | 4         | 4.12%   |
| MSI                            | 3         | 3.09%   |
| Framework                      | 3         | 3.09%   |
| ASRock                         | 3         | 3.09%   |
| Intel                          | 2         | 2.06%   |
| Beckhoff Automation            | 2         | 2.06%   |
| Apple                          | 2         | 2.06%   |
| pine64                         | 1         | 1.03%   |
| Notebook                       | 1         | 1.03%   |
| Matsushita Electric Industrial | 1         | 1.03%   |
| khadas                         | 1         | 1.03%   |
| HUAWEI                         | 1         | 1.03%   |
| friendlyelec                   | 1         | 1.03%   |
| Avell High Performance         | 1         | 1.03%   |
| A-DATA Technology              | 1         | 1.03%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 10        | 10.31%  |
| RPi Raspberry Pi                            | 3         | 3.09%   |
| HP EliteBook 8570p                          | 3         | 3.09%   |
| Framework Laptop                            | 3         | 3.09%   |
| RPi rpi                                     | 1         | 1.03%   |
| pine64 pinebook-pro-rk3399                  | 1         | 1.03%   |
| Notebook NS50_70MU                          | 1         | 1.03%   |
| MSI MS-7B86                                 | 1         | 1.03%   |
| MSI GE76 Raider 10UG                        | 1         | 1.03%   |
| MSI Bravo 15 A4DDR                          | 1         | 1.03%   |
| Matsushita Electric Industrial CF-T2BW1AXR  | 1         | 1.03%   |
| Lenovo XiaoXinPro-13ARE 2020 82DM           | 1         | 1.03%   |
| Lenovo ThinkPad X395 20NL001SMX             | 1         | 1.03%   |
| Lenovo ThinkPad X395 20NL000GPG             | 1         | 1.03%   |
| Lenovo ThinkPad X270 20HM004JBR             | 1         | 1.03%   |
| Lenovo ThinkPad X260 20F5A28AUK             | 1         | 1.03%   |
| Lenovo ThinkPad X13 Gen 1 20T2003PRT        | 1         | 1.03%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TLA055CD | 1         | 1.03%   |
| Lenovo ThinkPad X1 Extreme 20MF000BUS       | 1         | 1.03%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS1QC00    | 1         | 1.03%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS0BT00    | 1         | 1.03%   |
| Lenovo ThinkPad T495s 20QKS1812F            | 1         | 1.03%   |
| Lenovo ThinkPad T470p 20J7S0PM00            | 1         | 1.03%   |
| Lenovo ThinkPad T430 2349H2G                | 1         | 1.03%   |
| Lenovo ThinkPad T14s Gen 2i 20WM00B7MX      | 1         | 1.03%   |
| Lenovo ThinkPad P15 Gen 1 20ST005VRT        | 1         | 1.03%   |
| Lenovo ThinkPad P14s Gen 1 20Y1CTO1WW       | 1         | 1.03%   |
| Lenovo ThinkPad E14 Gen 3 20Y7003SGE        | 1         | 1.03%   |
| Lenovo ThinkPad E14 20RBCTO1WW              | 1         | 1.03%   |
| Lenovo ThinkBook 14 G3 ACL 21A2             | 1         | 1.03%   |
| Lenovo Legion 5P 15IMH05H 82AW              | 1         | 1.03%   |
| Lenovo Legion 5 15IMH05 82AU                | 1         | 1.03%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY        | 1         | 1.03%   |
| Lenovo IdeaPad 330-15ARR 81D2               | 1         | 1.03%   |
| khadas edge-v                               | 1         | 1.03%   |
| Intel S2600WTTR                             | 1         | 1.03%   |
| Intel NUC11PHi7                             | 1         | 1.03%   |
| HUAWEI HN-WX9X                              | 1         | 1.03%   |
| HP ZBook 17 G2                              | 1         | 1.03%   |
| HP ProBook 455 G7                           | 1         | 1.03%   |
| HP ProBook 440 G7                           | 1         | 1.03%   |
| HP ProBook 440 G6                           | 1         | 1.03%   |
| HP EliteDesk 800 G4 SFF                     | 1         | 1.03%   |
| HP EliteBook Folio 9470m                    | 1         | 1.03%   |
| Gigabyte X570 AORUS MASTER                  | 1         | 1.03%   |
| Gigabyte X570 AORUS ELITE                   | 1         | 1.03%   |
| Gigabyte X399 DESIGNARE EX                  | 1         | 1.03%   |
| Gigabyte B550I AORUS PRO AX                 | 1         | 1.03%   |
| Gigabyte B450M S2H                          | 1         | 1.03%   |
| Gigabyte B450M DS3H                         | 1         | 1.03%   |
| Gigabyte 970A-UD3P                          | 1         | 1.03%   |
| friendlyelec nanopi-m4                      | 1         | 1.03%   |
| Dell Vostro 5490                            | 1         | 1.03%   |
| Dell PowerEdge T150                         | 1         | 1.03%   |
| Dell OptiPlex 5490 AIO                      | 1         | 1.03%   |
| Dell OptiPlex 5080                          | 1         | 1.03%   |
| Dell Latitude E5430 vPro                    | 1         | 1.03%   |
| Dell Latitude 5521                          | 1         | 1.03%   |
| Dell Latitude 5410                          | 1         | 1.03%   |
| Dell Inspiron 3793                          | 1         | 1.03%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo ThinkPad                            | 17        | 17.53%  |
| Unknown                                    | 10        | 10.31%  |
| ASUS PRIME                                 | 5         | 5.15%   |
| HP EliteBook                               | 4         | 4.12%   |
| RPi Raspberry                              | 3         | 3.09%   |
| HP ProBook                                 | 3         | 3.09%   |
| Framework Laptop                           | 3         | 3.09%   |
| Dell Latitude                              | 3         | 3.09%   |
| Lenovo Legion                              | 2         | 2.06%   |
| Lenovo IdeaPad                             | 2         | 2.06%   |
| Gigabyte X570                              | 2         | 2.06%   |
| Gigabyte B450M                             | 2         | 2.06%   |
| Dell OptiPlex                              | 2         | 2.06%   |
| RPi rpi                                    | 1         | 1.03%   |
| pine64 pinebook-pro-rk3399                 | 1         | 1.03%   |
| Notebook NS50                              | 1         | 1.03%   |
| MSI MS-7B86                                | 1         | 1.03%   |
| MSI GE76                                   | 1         | 1.03%   |
| MSI Bravo                                  | 1         | 1.03%   |
| Matsushita Electric Industrial CF-T2BW1AXR | 1         | 1.03%   |
| Lenovo XiaoXinPro-13ARE                    | 1         | 1.03%   |
| Lenovo ThinkBook                           | 1         | 1.03%   |
| khadas edge-v                              | 1         | 1.03%   |
| Intel S2600WTTR                            | 1         | 1.03%   |
| Intel NUC11PHi7                            | 1         | 1.03%   |
| HUAWEI HN-WX9X                             | 1         | 1.03%   |
| HP ZBook                                   | 1         | 1.03%   |
| HP EliteDesk                               | 1         | 1.03%   |
| Gigabyte X399                              | 1         | 1.03%   |
| Gigabyte B550I                             | 1         | 1.03%   |
| Gigabyte 970A-UD3P                         | 1         | 1.03%   |
| friendlyelec nanopi-m4                     | 1         | 1.03%   |
| Dell Vostro                                | 1         | 1.03%   |
| Dell PowerEdge                             | 1         | 1.03%   |
| Dell Inspiron                              | 1         | 1.03%   |
| Dell G5                                    | 1         | 1.03%   |
| Dell G3                                    | 1         | 1.03%   |
| Beckhoff Automation CX2033-0185            | 1         | 1.03%   |
| Beckhoff Automation CBxx63                 | 1         | 1.03%   |
| Avell High Performance A62                 | 1         | 1.03%   |
| ASUS VivoBook                              | 1         | 1.03%   |
| ASUS TUF                                   | 1         | 1.03%   |
| ASUS ROG                                   | 1         | 1.03%   |
| ASUS P8H77-M                               | 1         | 1.03%   |
| ASUS MINIPC                                | 1         | 1.03%   |
| ASUS 1215B                                 | 1         | 1.03%   |
| ASRock X570                                | 1         | 1.03%   |
| ASRock B550                                | 1         | 1.03%   |
| ASRock B450                                | 1         | 1.03%   |
| Apple MacBookPro12                         | 1         | 1.03%   |
| Apple MacBookPro10                         | 1         | 1.03%   |
| A-DATA XENIA159GENI72060                   | 1         | 1.03%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 26        | 26.8%   |
| 2021    | 24        | 24.74%  |
| 2019    | 12        | 12.37%  |
| Unknown | 9         | 9.28%   |
| 2018    | 7         | 7.22%   |
| 2017    | 4         | 4.12%   |
| 2013    | 4         | 4.12%   |
| 2022    | 3         | 3.09%   |
| 2015    | 3         | 3.09%   |
| 2016    | 2         | 2.06%   |
| 2012    | 1         | 1.03%   |
| 2011    | 1         | 1.03%   |
| 2003    | 1         | 1.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 53        | 54.64%  |
| Desktop        | 32        | 32.99%  |
| System on chip | 7         | 7.22%   |
| Mini pc        | 2         | 2.06%   |
| Server         | 2         | 2.06%   |
| All in one     | 1         | 1.03%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 97        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 36        | 36.73%  |
| 8.01-16.0       | 19        | 19.39%  |
| 32.01-64.0      | 16        | 16.33%  |
| 64.01-256.0     | 13        | 13.27%  |
| 4.01-8.0        | 7         | 7.14%   |
| 0.51-1.0        | 2         | 2.04%   |
| More than 256.0 | 1         | 1.02%   |
| 3.01-4.0        | 1         | 1.02%   |
| 24.01-32.0      | 1         | 1.02%   |
| 1.01-2.0        | 1         | 1.02%   |
| 0.01-0.5        | 1         | 1.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.51-1.0    | 34        | 34.69%  |
| 1.01-2.0    | 26        | 26.53%  |
| 0.01-0.5    | 15        | 15.31%  |
| 2.01-3.0    | 9         | 9.18%   |
| 3.01-4.0    | 5         | 5.1%    |
| 24.01-32.0  | 2         | 2.04%   |
| 0           | 2         | 2.04%   |
| 4.01-8.0    | 1         | 1.02%   |
| 32.01-64.0  | 1         | 1.02%   |
| 64.01-256.0 | 1         | 1.02%   |
| 16.01-24.0  | 1         | 1.02%   |
| 8.01-16.0   | 1         | 1.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 49        | 48.04%  |
| 2      | 27        | 26.47%  |
| 0      | 11        | 10.78%  |
| 6      | 5         | 4.9%    |
| 3      | 5         | 4.9%    |
| 4      | 2         | 1.96%   |
| 15     | 1         | 0.98%   |
| 7      | 1         | 0.98%   |
| 5      | 1         | 0.98%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 85        | 85.86%  |
| Yes       | 14        | 14.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 76        | 78.35%  |
| No        | 21        | 21.65%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 68        | 70.1%   |
| No        | 29        | 29.9%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 50        | 51.02%  |
| No        | 48        | 48.98%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 17        | 17.53%  |
| UK           | 10        | 10.31%  |
| Russia       | 10        | 10.31%  |
| Germany      | 10        | 10.31%  |
| Brazil       | 6         | 6.19%   |
| Ukraine      | 4         | 4.12%   |
| Poland       | 4         | 4.12%   |
| Japan        | 4         | 4.12%   |
| China        | 4         | 4.12%   |
| Austria      | 4         | 4.12%   |
| Portugal     | 3         | 3.09%   |
| Switzerland  | 2         | 2.06%   |
| Sweden       | 2         | 2.06%   |
| Netherlands  | 2         | 2.06%   |
| Turkey       | 1         | 1.03%   |
| Spain        | 1         | 1.03%   |
| Singapore    | 1         | 1.03%   |
| Saudi Arabia | 1         | 1.03%   |
| Romania      | 1         | 1.03%   |
| Peru         | 1         | 1.03%   |
| Jamaica      | 1         | 1.03%   |
| Italy        | 1         | 1.03%   |
| India        | 1         | 1.03%   |
| France       | 1         | 1.03%   |
| Denmark      | 1         | 1.03%   |
| Croatia      | 1         | 1.03%   |
| Colombia     | 1         | 1.03%   |
| Belarus      | 1         | 1.03%   |
| Bangladesh   | 1         | 1.03%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Moscow                      | 5         | 4.63%   |
| Brighton                    | 5         | 4.63%   |
| ЕЊta-ku                   | 3         | 2.78%   |
| St Petersburg               | 3         | 2.78%   |
| London                      | 3         | 2.78%   |
| Kyiv                        | 3         | 2.78%   |
| Zurich                      | 2         | 1.85%   |
| Vienna                      | 2         | 1.85%   |
| Seattle                     | 2         | 1.85%   |
| Rio de Janeiro              | 2         | 1.85%   |
| Rietberg                    | 2         | 1.85%   |
| Northeim                    | 2         | 1.85%   |
| Graz                        | 2         | 1.85%   |
| Fuchu                       | 2         | 1.85%   |
| Egham                       | 2         | 1.85%   |
| Chicago                     | 2         | 1.85%   |
| Berlin                      | 2         | 1.85%   |
| Zaporizhzhya                | 1         | 0.93%   |
| Wuhan                       | 1         | 0.93%   |
| Worthing                    | 1         | 0.93%   |
| Woodburn                    | 1         | 0.93%   |
| Wieliczka                   | 1         | 0.93%   |
| Washington                  | 1         | 0.93%   |
| Warsaw                      | 1         | 0.93%   |
| Vila Real de Santo António | 1         | 0.93%   |
| Vancouver                   | 1         | 0.93%   |
| Trosa                       | 1         | 0.93%   |
| Thrissur                    | 1         | 0.93%   |
| Teaneck                     | 1         | 0.93%   |
| Stuttgart                   | 1         | 0.93%   |
| Sollentuna                  | 1         | 0.93%   |
| Slavonski Brod              | 1         | 0.93%   |
| Singapore                   | 1         | 0.93%   |
| Shanghai                    | 1         | 0.93%   |
| Setagaya-ku                 | 1         | 0.93%   |
| Santa Monica                | 1         | 0.93%   |
| San Francisco               | 1         | 0.93%   |
| Ruthin                      | 1         | 0.93%   |
| Rostov-on-Don               | 1         | 0.93%   |
| Riyadh                      | 1         | 0.93%   |
| Resana                      | 1         | 0.93%   |
| Poulsbo                     | 1         | 0.93%   |
| Pobiedziska                 | 1         | 0.93%   |
| Omaha                       | 1         | 0.93%   |
| New York                    | 1         | 0.93%   |
| Montclair                   | 1         | 0.93%   |
| Minsk                       | 1         | 0.93%   |
| Milan                       | 1         | 0.93%   |
| Medellín                   | 1         | 0.93%   |
| Manchester                  | 1         | 0.93%   |
| Maia                        | 1         | 0.93%   |
| Madrid                      | 1         | 0.93%   |
| Lubin                       | 1         | 0.93%   |
| Lima                        | 1         | 0.93%   |
| Lake Forest                 | 1         | 0.93%   |
| Kunitachi                   | 1         | 0.93%   |
| Kislovodsk                  | 1         | 0.93%   |
| Kingston                    | 1         | 0.93%   |
| Khabarovsk                  | 1         | 0.93%   |
| JoГЈo Pessoa              | 1         | 0.93%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 26        | 41     | 20.8%   |
| Samsung Electronics | 25        | 36     | 20%     |
| Toshiba             | 12        | 25     | 9.6%    |
| Crucial             | 8         | 17     | 6.4%    |
| Seagate             | 7         | 22     | 5.6%    |
| Kingston            | 7         | 10     | 5.6%    |
| HGST                | 7         | 23     | 5.6%    |
| A-DATA Technology   | 5         | 5      | 4%      |
| SK hynix            | 4         | 4      | 3.2%    |
| Intel               | 4         | 5      | 3.2%    |
| KIOXIA              | 3         | 3      | 2.4%    |
| Micron Technology   | 2         | 3      | 1.6%    |
| Apple               | 2         | 2      | 1.6%    |
| SSSTC               | 1         | 1      | 0.8%    |
| SPCC                | 1         | 1      | 0.8%    |
| Solid State Storage | 1         | 1      | 0.8%    |
| Silicon Motion      | 1         | 1      | 0.8%    |
| SanDisk             | 1         | 2      | 0.8%    |
| PNY                 | 1         | 1      | 0.8%    |
| Mushkin             | 1         | 1      | 0.8%    |
| LSI                 | 1         | 4      | 0.8%    |
| LITEON              | 1         | 1      | 0.8%    |
| Hitachi             | 1         | 2      | 0.8%    |
| Goodram             | 1         | 1      | 0.8%    |
| Fujitsu             | 1         | 2      | 0.8%    |
| Apacer              | 1         | 1      | 0.8%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB                           | 5         | 3.6%    |
| HGST HTS725050A7E630 500GB                         | 4         | 2.88%   |
| WDC WDS100T3X0C-00SJG0 1TB                         | 3         | 2.16%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB               | 3         | 2.16%   |
| Toshiba MQ04ABF100 1TB                             | 3         | 2.16%   |
| Samsung HM251JX 250GB                              | 3         | 2.16%   |
| HGST HTS721010A9E630 1TB                           | 3         | 2.16%   |
| WDC WDS100T1X0E-00AFY0 1TB                         | 2         | 1.44%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB                 | 2         | 1.44%   |
| WDC PC SN730 NVMe 1024GB                           | 2         | 1.44%   |
| Samsung SSD 870 EVO 1TB                            | 2         | 1.44%   |
| Samsung SSD 850 EVO 250GB                          | 2         | 1.44%   |
| Samsung MZVLB512HBJQ-000L7 512GB                   | 2         | 1.44%   |
| KIOXIA KBG40ZNS256G NVMe 256GB                     | 2         | 1.44%   |
| Kingston SA2000M81000G 1TB                         | 2         | 1.44%   |
| WDC WDS500G1X0E-00AFY0 500GB                       | 1         | 0.72%   |
| WDC WDS250G2B0C-00PXH0 250GB                       | 1         | 0.72%   |
| WDC WDS100T2B0A-00SM50 1TB                         | 1         | 0.72%   |
| WDC WD60EFRX-68TGBN1 6TB                           | 1         | 0.72%   |
| WDC WD5002ABYS-18B1B0 500GB                        | 1         | 0.72%   |
| WDC WD40EZRZ-75GXCB0 4TB                           | 1         | 0.72%   |
| WDC WD30EFRX-68EUZN0 3TB                           | 1         | 0.72%   |
| WDC WD20EFRX-68AX9N0 2TB                           | 1         | 0.72%   |
| WDC WD120EFAX-68UNTN0 12TB                         | 1         | 0.72%   |
| WDC WD10SPZX-60Z10T0 1TB                           | 1         | 0.72%   |
| WDC WD10SPZX-21Z10T0 1TB                           | 1         | 0.72%   |
| WDC WD10JPVX-00JC3T0 1TB                           | 1         | 0.72%   |
| WDC WD10JMVW-11AJGS3 1TB                           | 1         | 0.72%   |
| WDC WD10EZEX-60WN4A0 1TB                           | 1         | 0.72%   |
| WDC WD10EZEX-00RKKA0 1TB                           | 1         | 0.72%   |
| WDC WD10EARX-00N0YB0 1TB                           | 1         | 0.72%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB               | 1         | 0.72%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB               | 1         | 0.72%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB               | 1         | 0.72%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB               | 1         | 0.72%   |
| Toshiba MQ01ABD100 1TB                             | 1         | 0.72%   |
| Toshiba MG09ACA18TE 18TB                           | 1         | 0.72%   |
| Toshiba MG06ACA800E 8TB                            | 1         | 0.72%   |
| Toshiba KXG6APNV2T04 2TB                           | 1         | 0.72%   |
| SSSTC CL1-3D256-Q11 NVMe 256GB                     | 1         | 0.72%   |
| SPCC M.2 PCIe SSD 1TB                              | 1         | 0.72%   |
| Solid State Storage CL1-3D128-Q11 NVMe SSSTC 128GB | 1         | 0.72%   |
| SK hynix PC300 HFS512GD9MND-5510A 512GB            | 1         | 0.72%   |
| SK hynix HFS128G39TND-N210A 128GB                  | 1         | 0.72%   |
| SK hynix BC511 NVMe 256GB                          | 1         | 0.72%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB            | 1         | 0.72%   |
| Silicon Motion NE-256 256GB                        | 1         | 0.72%   |
| Seagate ST5000LM000-2U8170 5TB                     | 1         | 0.72%   |
| Seagate ST5000LM000-2AN170 5TB                     | 1         | 0.72%   |
| Seagate ST4000DM000-1F2168 4TB                     | 1         | 0.72%   |
| Seagate ST3750640AS 752GB                          | 1         | 0.72%   |
| Seagate ST32000641AS 2TB                           | 1         | 0.72%   |
| Seagate ST3000DM007-1WY10G 3TB                     | 1         | 0.72%   |
| Seagate ST3000DM001-1ER166 3TB                     | 1         | 0.72%   |
| Seagate ST1000LM035-1RK172 1TB                     | 1         | 0.72%   |
| SanDisk SDSSDH3500G 500GB                          | 1         | 0.72%   |
| Samsung SSD 970 EVO Plus 1TB                       | 1         | 0.72%   |
| Samsung SSD 970 EVO 1TB                            | 1         | 0.72%   |
| Samsung SSD 870 QVO 1TB                            | 1         | 0.72%   |
| Samsung SSD 860 EVO M.2 250GB                      | 1         | 0.72%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 11        | 24     | 26.83%  |
| WDC                 | 9         | 15     | 21.95%  |
| Seagate             | 7         | 22     | 17.07%  |
| HGST                | 7         | 23     | 17.07%  |
| Samsung Electronics | 4         | 7      | 9.76%   |
| LSI                 | 1         | 4      | 2.44%   |
| Hitachi             | 1         | 2      | 2.44%   |
| Fujitsu             | 1         | 2      | 2.44%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 14     | 29.03%  |
| Crucial             | 5         | 10     | 16.13%  |
| Kingston            | 3         | 5      | 9.68%   |
| A-DATA Technology   | 3         | 3      | 9.68%   |
| Intel               | 2         | 3      | 6.45%   |
| Apple               | 2         | 2      | 6.45%   |
| WDC                 | 1         | 2      | 3.23%   |
| SK hynix            | 1         | 1      | 3.23%   |
| SanDisk             | 1         | 2      | 3.23%   |
| Micron Technology   | 1         | 1      | 3.23%   |
| LITEON              | 1         | 1      | 3.23%   |
| Goodram             | 1         | 1      | 3.23%   |
| Apacer              | 1         | 1      | 3.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 51        | 70     | 46.36%  |
| SSD  | 30        | 46     | 27.27%  |
| HDD  | 29        | 99     | 26.36%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 51        | 70     | 51%     |
| SATA | 49        | 145    | 49%     |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 31        | 67     | 46.27%  |
| 0.51-1.0   | 20        | 36     | 29.85%  |
| 1.01-2.0   | 4         | 5      | 5.97%   |
| 4.01-10.0  | 4         | 23     | 5.97%   |
| 3.01-4.0   | 3         | 4      | 4.48%   |
| 2.01-3.0   | 2         | 3      | 2.99%   |
| 10.01-20.0 | 2         | 3      | 2.99%   |
| 20.01-50.0 | 1         | 4      | 1.49%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 25        | 24.51%  |
| 251-500        | 24        | 23.53%  |
| 501-1000       | 17        | 16.67%  |
| 1-20           | 11        | 10.78%  |
| 21-50          | 8         | 7.84%   |
| 51-100         | 7         | 6.86%   |
| 1001-2000      | 5         | 4.9%    |
| More than 3000 | 3         | 2.94%   |
| 2001-3000      | 2         | 1.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 62        | 60.78%  |
| 21-50          | 25        | 24.51%  |
| 101-250        | 7         | 6.86%   |
| 501-1000       | 2         | 1.96%   |
| 51-100         | 2         | 1.96%   |
| More than 3000 | 1         | 0.98%   |
| 251-500        | 1         | 0.98%   |
| 1001-2000      | 1         | 0.98%   |
| 0              | 1         | 0.98%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| HGST HTS725050A7E630 500GB          | 4         | 9      | 28.57%  |
| Samsung Electronics SSD 870 EVO 1TB | 2         | 4      | 14.29%  |
| WDC WD60EFRX-68TGBN1 6TB            | 1         | 3      | 7.14%   |
| WDC WD5002ABYS-18B1B0 500GB         | 1         | 1      | 7.14%   |
| WDC WD10SPZX-60Z10T0 1TB            | 1         | 1      | 7.14%   |
| Samsung Electronics HM251JX 250GB   | 1         | 1      | 7.14%   |
| Kingston SA400S37120G 120GB         | 1         | 1      | 7.14%   |
| Hitachi HUA722020ALA331 2TB         | 1         | 2      | 7.14%   |
| HGST HTS721010A9E630 1TB            | 1         | 9      | 7.14%   |
| Fujitsu MHS2040AT D 40GB            | 1         | 2      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 4         | 18     | 30.77%  |
| WDC                 | 3         | 5      | 23.08%  |
| Samsung Electronics | 3         | 5      | 23.08%  |
| Kingston            | 1         | 1      | 7.69%   |
| Hitachi             | 1         | 2      | 7.69%   |
| Fujitsu             | 1         | 2      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 4         | 18     | 40%     |
| WDC                 | 3         | 5      | 30%     |
| Samsung Electronics | 1         | 1      | 10%     |
| Hitachi             | 1         | 2      | 10%     |
| Fujitsu             | 1         | 2      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 28     | 81.82%  |
| SSD  | 2         | 5      | 18.18%  |

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
| Works    | 82        | 175    | 84.54%  |
| Malfunc  | 11        | 33     | 11.34%  |
| Detected | 4         | 7      | 4.12%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 39        | 30.47%  |
| AMD                            | 26        | 20.31%  |
| SanDisk                        | 18        | 14.06%  |
| Samsung Electronics            | 16        | 12.5%   |
| Silicon Motion                 | 4         | 3.13%   |
| Kingston Technology Company    | 4         | 3.13%   |
| SK hynix                       | 3         | 2.34%   |
| Micron/Crucial Technology      | 3         | 2.34%   |
| Toshiba                        | 2         | 1.56%   |
| Solid State Storage Technology | 2         | 1.56%   |
| Micron Technology              | 2         | 1.56%   |
| KIOXIA                         | 2         | 1.56%   |
| ASMedia Technology             | 2         | 1.56%   |
| ADATA Technology               | 2         | 1.56%   |
| Phison Electronics             | 1         | 0.78%   |
| Marvell Technology Group       | 1         | 0.78%   |
| Broadcom / LSI                 | 1         | 0.78%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 19        | 13.57%  |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 11        | 7.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 10        | 7.14%   |
| Intel Comet Lake SATA AHCI Controller                                          | 6         | 4.29%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 4.29%   |
| AMD 400 Series Chipset SATA Controller                                         | 6         | 4.29%   |
| Unknown                                                                        | 6         | 4.29%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 4         | 2.86%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 4         | 2.86%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 4         | 2.86%   |
| AMD 500 Series Chipset SATA Controller                                         | 4         | 2.86%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 3         | 2.14%   |
| Toshiba XG6 NVMe SSD Controller                                                | 2         | 1.43%   |
| SK hynix BC511                                                                 | 2         | 1.43%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 1.43%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 1.43%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 1.43%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 1.43%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2         | 1.43%   |
| KIOXIA unknown                                                                 | 2         | 1.43%   |
| Kingston Company A2000 NVMe SSD                                                | 2         | 1.43%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 1.43%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.43%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 2         | 1.43%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 2         | 1.43%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 1.43%   |
| SK hynix PC300 NVMe Solid State Drive 512GB                                    | 1         | 0.71%   |
| SanDisk PC SN530                                                               | 1         | 0.71%   |
| Samsung SM951 AHCI                                                             | 1         | 0.71%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 0.71%   |
| Phison E12 NVMe Controller                                                     | 1         | 0.71%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 1         | 0.71%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                          | 1         | 0.71%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 1         | 0.71%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 0.71%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1         | 0.71%   |
| Intel SSD 660P Series                                                          | 1         | 0.71%   |
| Intel NVMe Optane Memory Series                                                | 1         | 0.71%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 1         | 0.71%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 0.71%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 0.71%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1         | 0.71%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 0.71%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 1         | 0.71%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 1         | 0.71%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 0.71%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 1         | 0.71%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 1         | 0.71%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]    | 1         | 0.71%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]    | 1         | 0.71%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                 | 1         | 0.71%   |
| ASMedia ASM1166 Serial ATA Controller                                          | 1         | 0.71%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 1         | 0.71%   |
| AMD X399 Series Chipset SATA Controller                                        | 1         | 0.71%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 1         | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 59        | 47.97%  |
| NVMe | 58        | 47.15%  |
| IDE  | 4         | 3.25%   |
| RAID | 2         | 1.63%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 49        | 50%     |
| AMD     | 33        | 33.67%  |
| ARM     | 8         | 8.16%   |
| Unknown | 8         | 8.16%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
|                                                 | 8         | 8.16%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 6         | 6.12%   |
| Intel Core i7-3520M CPU @ 2.90GHz               | 4         | 4.08%   |
| Intel Core i5-10210U CPU @ 1.60GHz              | 4         | 4.08%   |
| ARM Cortex-A72 r0p3                             | 4         | 4.08%   |
| AMD Ryzen 5 5600G with Radeon Graphics          | 4         | 4.08%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 3         | 3.06%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 2         | 2.04%   |
| Intel Core i7-7600U CPU @ 2.80GHz               | 2         | 2.04%   |
| Intel Core i5-10500T CPU @ 2.30GHz              | 2         | 2.04%   |
| Intel Core i5-10300H CPU @ 2.50GHz              | 2         | 2.04%   |
| ARM Cortex-A72 r0p2                             | 2         | 2.04%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 2         | 2.04%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 2         | 2.04%   |
| AMD Ryzen 7 4700U with Radeon Graphics          | 2         | 2.04%   |
| AMD Ryzen 5 PRO 3500U w/ Radeon Vega Mobile Gfx | 2         | 2.04%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 2         | 2.04%   |
| Intel Xeon W-10885M CPU @ 2.40GHz               | 1         | 1.02%   |
| Intel Xeon E-2334 CPU @ 3.40GHz                 | 1         | 1.02%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz             | 1         | 1.02%   |
| Intel Pentium M processor 1000MHz               | 1         | 1.02%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 1         | 1.02%   |
| Intel Core i7-8700 CPU @ 3.20GHz                | 1         | 1.02%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 1.02%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 1.02%   |
| Intel Core i7-5600U CPU @ 2.60GHz               | 1         | 1.02%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz              | 1         | 1.02%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz              | 1         | 1.02%   |
| Intel Core i7-3770 CPU @ 3.40GHz                | 1         | 1.02%   |
| Intel Core i7-3687U CPU @ 2.10GHz               | 1         | 1.02%   |
| Intel Core i7-3615QM CPU @ 2.30GHz              | 1         | 1.02%   |
| Intel Core i7-10870H CPU @ 2.20GHz              | 1         | 1.02%   |
| Intel Core i7-10700 CPU @ 2.90GHz               | 1         | 1.02%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz              | 1         | 1.02%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 1         | 1.02%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 1         | 1.02%   |
| Intel Core i5-5257U CPU @ 2.70GHz               | 1         | 1.02%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 1         | 1.02%   |
| Intel Core i5-10400 CPU @ 2.90GHz               | 1         | 1.02%   |
| Intel Atom CPU E3827 @ 1.74GHz                  | 1         | 1.02%   |
| Intel 11th Gen Core i7-11850H @ 2.50GHz         | 1         | 1.02%   |
| ARM Cortex-A53 r0p4                             | 1         | 1.02%   |
| ARM ARM1176 r0p7 (ECO: 0x00000000)              | 1         | 1.02%   |
| AMD Ryzen Threadripper 1950X 16-Core Processor  | 1         | 1.02%   |
| AMD Ryzen Embedded V1202B with Radeon Vega Gfx  | 1         | 1.02%   |
| AMD Ryzen 9 5950X 16-Core Processor             | 1         | 1.02%   |
| AMD Ryzen 9 5900X 12-Core Processor             | 1         | 1.02%   |
| AMD Ryzen 9 3950X 16-Core Processor             | 1         | 1.02%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics      | 1         | 1.02%   |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx | 1         | 1.02%   |
| AMD Ryzen 7 5800X 8-Core Processor              | 1         | 1.02%   |
| AMD Ryzen 7 5700U with Radeon Graphics          | 1         | 1.02%   |
| AMD Ryzen 7 4800U with Radeon Graphics          | 1         | 1.02%   |
| AMD Ryzen 7 2700X Eight-Core Processor          | 1         | 1.02%   |
| AMD Ryzen 5 5500U with Radeon Graphics          | 1         | 1.02%   |
| AMD Ryzen 5 4600H with Radeon Graphics          | 1         | 1.02%   |
| AMD Ryzen 5 2600X Six-Core Processor            | 1         | 1.02%   |
| AMD Ryzen 5 2600 Six-Core Processor             | 1         | 1.02%   |
| AMD Ryzen 5 2400GE with Radeon Vega Graphics    | 1         | 1.02%   |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx   | 1         | 1.02%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 25        | 25.51%  |
| Other                  | 16        | 16.33%  |
| Intel Core i5          | 12        | 12.24%  |
| AMD Ryzen 5            | 11        | 11.22%  |
| AMD Ryzen 7            | 8         | 8.16%   |
| ARM Cortex             | 7         | 7.14%   |
| AMD Ryzen 9            | 5         | 5.1%    |
| Intel Xeon             | 3         | 3.06%   |
| AMD Ryzen 7 PRO        | 2         | 2.04%   |
| AMD Ryzen 5 PRO        | 2         | 2.04%   |
| Intel Pentium M        | 1         | 1.02%   |
| Intel Atom             | 1         | 1.02%   |
| AMD Ryzen Threadripper | 1         | 1.02%   |
| AMD Ryzen Embedded     | 1         | 1.02%   |
| AMD Ryzen 3            | 1         | 1.02%   |
| AMD FX                 | 1         | 1.02%   |
| AMD E                  | 1         | 1.02%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 22        | 22.68%  |
| Unknown | 15        | 15.46%  |
| 2       | 14        | 14.43%  |
| 8       | 13        | 13.4%   |
| 6       | 10        | 10.31%  |
| 16      | 8         | 8.25%   |
| 12      | 8         | 8.25%   |
| 32      | 3         | 3.09%   |
| 24      | 3         | 3.09%   |
| 1       | 1         | 1.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 86        | 87.76%  |
| Unknown | 11        | 11.22%  |
| 2       | 1         | 1.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 47        | 48.45%  |
| 1       | 34        | 35.05%  |
| Unknown | 16        | 16.49%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 19        | 19.59%  |
| KabyLake   | 13        | 13.4%   |
| CometLake  | 11        | 11.34%  |
| Zen 2      | 10        | 10.31%  |
| Zen+       | 8         | 8.25%   |
| IvyBridge  | 8         | 8.25%   |
| Zen 3      | 7         | 7.22%   |
| TigerLake  | 6         | 6.19%   |
| Zen        | 4         | 4.12%   |
| Broadwell  | 3         | 3.09%   |
| Haswell    | 2         | 2.06%   |
| Skylake    | 1         | 1.03%   |
| Silvermont | 1         | 1.03%   |
| Piledriver | 1         | 1.03%   |
| P6         | 1         | 1.03%   |
| IceLake    | 1         | 1.03%   |
| Bobcat     | 1         | 1.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 42        | 40.38%  |
| AMD                        | 30        | 28.85%  |
| Nvidia                     | 29        | 27.88%  |
| Matrox Electronics Systems | 2         | 1.92%   |
| ASPEED Technology          | 1         | 0.96%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                               | 7         | 6.6%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                | 6         | 5.66%   |
| Intel CometLake-U GT2 [UHD Graphics]                                     | 5         | 4.72%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]     | 5         | 4.72%   |
| Intel CometLake-H GT2 [UHD Graphics]                                     | 4         | 3.77%   |
| Intel 3rd Gen Core processor Graphics Controller                         | 4         | 3.77%   |
| AMD Cezanne                                                              | 4         | 3.77%   |
| Nvidia TU117M                                                            | 3         | 2.83%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                 | 3         | 2.83%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                | 3         | 2.83%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                 | 3         | 2.83%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]         | 3         | 2.83%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                               | 2         | 1.89%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                               | 2         | 1.89%   |
| Nvidia GP108M [GeForce MX230]                                            | 2         | 1.89%   |
| Nvidia GK208B [GeForce GT 710]                                           | 2         | 1.89%   |
| Intel HD Graphics 620                                                    | 2         | 1.89%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller              | 2         | 1.89%   |
| AMD Lucienne                                                             | 2         | 1.89%   |
| Nvidia TU117M [GeForce MX450]                                            | 1         | 0.94%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                  | 1         | 0.94%   |
| Nvidia TU104GLM [Quadro RTX 5000 Mobile / Max-Q]                         | 1         | 0.94%   |
| Nvidia GT218 [GeForce 210]                                               | 1         | 0.94%   |
| Nvidia GP108 [GeForce GT 1030]                                           | 1         | 0.94%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                               | 1         | 0.94%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                  | 1         | 0.94%   |
| Nvidia GP107GL [Quadro P620]                                             | 1         | 0.94%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                       | 1         | 0.94%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                      | 1         | 0.94%   |
| Nvidia GM206 [GeForce GTX 960]                                           | 1         | 0.94%   |
| Nvidia GM108M [GeForce MX130]                                            | 1         | 0.94%   |
| Nvidia GM108M [GeForce 940MX]                                            | 1         | 0.94%   |
| Nvidia GM107M [GeForce GTX 860M]                                         | 1         | 0.94%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                        | 1         | 0.94%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                              | 1         | 0.94%   |
| Nvidia GK107GLM [Quadro K1100M]                                          | 1         | 0.94%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                          | 1         | 0.94%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)        | 1         | 0.94%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller | 1         | 0.94%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                               | 1         | 0.94%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                     | 1         | 0.94%   |
| Intel Skylake GT2 [HD Graphics 520]                                      | 1         | 0.94%   |
| Intel JasperLake [UHD Graphics]                                          | 1         | 0.94%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                   | 1         | 0.94%   |
| Intel Iris Plus Graphics G7                                              | 1         | 0.94%   |
| Intel Iris Graphics 6100                                                 | 1         | 0.94%   |
| Intel HD Graphics 630                                                    | 1         | 0.94%   |
| Intel HD Graphics 5500                                                   | 1         | 0.94%   |
| Intel Comet Lake-H WS GT2 Integrated UHD Graphics Controller             | 1         | 0.94%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                | 1         | 0.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display             | 1         | 0.94%   |
| Intel 82852/855GM Integrated Graphics Device                             | 1         | 0.94%   |
| ASPEED Technology ASPEED Graphics Family                                 | 1         | 0.94%   |
| AMD Wrestler [Radeon HD 6320]                                            | 1         | 0.94%   |
| AMD RV630 XT [Radeon HD 2600 XT]                                         | 1         | 0.94%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]    | 1         | 0.94%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                           | 1         | 0.94%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                  | 1         | 0.94%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                  | 1         | 0.94%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                       | 1         | 0.94%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 25        | 25.51%  |
| 1 x Intel      | 23        | 23.47%  |
| Intel + Nvidia | 17        | 17.35%  |
| Other          | 14        | 14.29%  |
| 1 x Nvidia     | 12        | 12.24%  |
| 2 x AMD        | 2         | 2.04%   |
| 1 x Matrox     | 2         | 2.04%   |
| Intel + AMD    | 1         | 1.02%   |
| 1 x ASPEED     | 1         | 1.02%   |
| AMD + Nvidia   | 1         | 1.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 64        | 65.98%  |
| Proprietary | 19        | 19.59%  |
| Unknown     | 14        | 14.43%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 72        | 72.73%  |
| 1.01-2.0   | 9         | 9.09%   |
| 0.51-1.0   | 6         | 6.06%   |
| 0.01-0.5   | 5         | 5.05%   |
| 3.01-4.0   | 4         | 4.04%   |
| 7.01-8.0   | 1         | 1.01%   |
| 5.01-6.0   | 1         | 1.01%   |
| 2.01-3.0   | 1         | 1.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| BOE                 | 12        | 15.79%  |
| LG Display          | 10        | 13.16%  |
| AU Optronics        | 9         | 11.84%  |
| Philips             | 4         | 5.26%   |
| Hewlett-Packard     | 4         | 5.26%   |
| Goldstar            | 4         | 5.26%   |
| Dell                | 4         | 5.26%   |
| Chimei Innolux      | 4         | 5.26%   |
| Samsung Electronics | 3         | 3.95%   |
| RTK                 | 2         | 2.63%   |
| LG Electronics      | 2         | 2.63%   |
| Lenovo              | 2         | 2.63%   |
| Apple               | 2         | 2.63%   |
| ViewSonic           | 1         | 1.32%   |
| Sony                | 1         | 1.32%   |
| Sharp               | 1         | 1.32%   |
| SDC                 | 1         | 1.32%   |
| PANDA               | 1         | 1.32%   |
| LGD                 | 1         | 1.32%   |
| InfoVision          | 1         | 1.32%   |
| Iiyama              | 1         | 1.32%   |
| HJW                 | 1         | 1.32%   |
| Eizo                | 1         | 1.32%   |
| CSO                 | 1         | 1.32%   |
| BenQ                | 1         | 1.32%   |
| AOC                 | 1         | 1.32%   |
| Unknown             | 1         | 1.32%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0258 1600x900 350x190mm 15.7-inch            | 3         | 3.85%   |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                  | 3         | 3.85%   |
| RTK WCS Display RTK1A1B 1920x1080 344x195mm 15.6-inch                  | 2         | 2.56%   |
| Philips LCD Monitor PHL08C3 1920x1080 600x340mm 27.2-inch              | 2         | 2.56%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch           | 2         | 2.56%   |
| ViewSonic LCD Monitor VSCD22B 1920x1080 520x290mm 23.4-inch            | 1         | 1.28%   |
| Sony TV SNY4B03 1920x1080 930x520mm 41.9-inch                          | 1         | 1.28%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 380x210mm 17.1-inch                | 1         | 1.28%   |
| SDC LCD Monitor 3520x1080                                              | 1         | 1.28%   |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                       | 1         | 1.28%   |
| Samsung Electronics LCD Monitor SDC3754 1600x900 380x210mm 17.1-inch   | 1         | 1.28%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1020x570mm 46.0-inch | 1         | 1.28%   |
| Philips PHL 273V7 PHLC156 1920x1080 600x340mm 27.2-inch                | 1         | 1.28%   |
| Philips LCD Monitor 271P4 3520x1080                                    | 1         | 1.28%   |
| Philips LCD Monitor 271P4                                              | 1         | 1.28%   |
| PANDA LCD Monitor NCP004F 1920x1080 310x170mm 13.9-inch                | 1         | 1.28%   |
| LGD LCD Monitor 1920x1080                                              | 1         | 1.28%   |
| LG Electronics LCD Monitor LX20D 1600x1200                             | 1         | 1.28%   |
| LG Electronics LCD Monitor LG Ultra HD 11520x2160                      | 1         | 1.28%   |
| LG Electronics LCD Monitor LG Ultra HD                                 | 1         | 1.28%   |
| LG Display LCD Monitor LGD062E 1920x1080 340x190mm 15.3-inch           | 1         | 1.28%   |
| LG Display LCD Monitor LGD060A 1920x1080 290x170mm 13.2-inch           | 1         | 1.28%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch           | 1         | 1.28%   |
| LG Display LCD Monitor LGD05F1 1920x1080 310x170mm 13.9-inch           | 1         | 1.28%   |
| LG Display LCD Monitor LGD033E 1366x768 310x170mm 13.9-inch            | 1         | 1.28%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                  | 1         | 1.28%   |
| Lenovo LEN P44w-10 LEN61D5 3840x1200 1050x330mm 43.3-inch              | 1         | 1.28%   |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch           | 1         | 1.28%   |
| Iiyama PL2474H IVM6146 1920x1080 520x290mm 23.4-inch                   | 1         | 1.28%   |
| HJW HDMI TO USB HJW0001 1920x1080 700x390mm 31.5-inch                  | 1         | 1.28%   |
| Hewlett-Packard LCD Monitor LA2306 3520x1080                           | 1         | 1.28%   |
| Hewlett-Packard LA2306 HWP2949 1920x1080 510x290mm 23.1-inch           | 1         | 1.28%   |
| Hewlett-Packard E242 HWP326E 1920x1200 520x320mm 24.0-inch             | 1         | 1.28%   |
| Hewlett-Packard E233 HPN345F 1920x1080 510x290mm 23.1-inch             | 1         | 1.28%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch             | 1         | 1.28%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch             | 1         | 1.28%   |
| Goldstar 27GK750F GSM770F 1920x1080 600x340mm 27.2-inch                | 1         | 1.28%   |
| Goldstar 23EA53 GSM59A8 1920x1080 510x290mm 23.1-inch                  | 1         | 1.28%   |
| Eizo FX2431 ENC2036 1920x1200 520x330mm 24.2-inch                      | 1         | 1.28%   |
| Dell U2718Q DELA0EC 3840x2160 610x350mm 27.7-inch                      | 1         | 1.28%   |
| Dell U2518D DEL413C 2560x1440 550x310mm 24.9-inch                      | 1         | 1.28%   |
| Dell LCD Monitor U2715H 2560x1440                                      | 1         | 1.28%   |
| Dell LCD Monitor DEL9408 1920x1080 520x290mm 23.4-inch                 | 1         | 1.28%   |
| CSO LCD Monitor CSO1500 3840x2160 340x190mm 15.3-inch                  | 1         | 1.28%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 280x180mm 13.1-inch       | 1         | 1.28%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 340x190mm 15.3-inch       | 1         | 1.28%   |
| Chimei Innolux LCD Monitor CMN1484 1600x900 310x170mm 13.9-inch        | 1         | 1.28%   |
| Chimei Innolux LCD Monitor CMN13A2 1920x1080 290x170mm 13.2-inch       | 1         | 1.28%   |
| BOE LCD Monitor BOE0982 3840x2160 310x170mm 13.9-inch                  | 1         | 1.28%   |
| BOE LCD Monitor BOE0928 1920x1080 340x190mm 15.3-inch                  | 1         | 1.28%   |
| BOE LCD Monitor BOE08D7 1920x1080 310x170mm 13.9-inch                  | 1         | 1.28%   |
| BOE LCD Monitor BOE084D 1920x1080 340x190mm 15.3-inch                  | 1         | 1.28%   |
| BOE LCD Monitor BOE07F1 1920x1080 340x190mm 15.3-inch                  | 1         | 1.28%   |
| BOE LCD Monitor BOE07BB 1920x1080 310x170mm 13.9-inch                  | 1         | 1.28%   |
| BOE LCD Monitor BOE0792 1920x1080 340x190mm 15.3-inch                  | 1         | 1.28%   |
| BOE LCD Monitor BOE075A 1366x768 310x170mm 13.9-inch                   | 1         | 1.28%   |
| BOE LCD Monitor BOE0747 1920x1080 340x190mm 15.3-inch                  | 1         | 1.28%   |
| BenQ GW2280 BNQ78E8 1920x1080 480x270mm 21.7-inch                      | 1         | 1.28%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 340x190mm 15.3-inch         | 1         | 1.28%   |
| AU Optronics LCD Monitor AUOD0ED 1920x1080 340x190mm 15.3-inch         | 1         | 1.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 43        | 57.33%  |
| 3840x2160 (4K)    | 6         | 8%      |
| 1600x900 (HD+)    | 6         | 8%      |
| 2560x1440 (QHD)   | 3         | 4%      |
| 2256x1504         | 3         | 4%      |
| 1920x1200 (WUXGA) | 3         | 4%      |
| 2560x1600         | 2         | 2.67%   |
| 1366x768 (WXGA)   | 2         | 2.67%   |
| Unknown           | 2         | 2.67%   |
| 3840x1200         | 1         | 1.33%   |
| 3520x1080         | 1         | 1.33%   |
| 2160x1440         | 1         | 1.33%   |
| 1600x1200         | 1         | 1.33%   |
| 11520x2160        | 1         | 1.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 22        | 29.73%  |
| 15      | 16        | 21.62%  |
| 27      | 7         | 9.46%   |
| Unknown | 7         | 9.46%   |
| 23      | 6         | 8.11%   |
| 24      | 4         | 5.41%   |
| 17      | 3         | 4.05%   |
| 12      | 2         | 2.7%    |
| 46      | 1         | 1.35%   |
| 43      | 1         | 1.35%   |
| 41      | 1         | 1.35%   |
| 32      | 1         | 1.35%   |
| 31      | 1         | 1.35%   |
| 22      | 1         | 1.35%   |
| 21      | 1         | 1.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 29        | 39.73%  |
| 501-600     | 15        | 20.55%  |
| 201-300     | 11        | 15.07%  |
| Unknown     | 7         | 9.59%   |
| 351-400     | 3         | 4.11%   |
| 601-700     | 2         | 2.74%   |
| 401-500     | 2         | 2.74%   |
| 1001-1500   | 2         | 2.74%   |
| 701-800     | 1         | 1.37%   |
| 901-1000    | 1         | 1.37%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 51        | 76.12%  |
| 16/10   | 6         | 8.96%   |
| Unknown | 6         | 8.96%   |
| 3/2     | 3         | 4.48%   |
| 3.18    | 1         | 1.49%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 18        | 24.32%  |
| 91-100         | 11        | 14.86%  |
| 201-250        | 9         | 12.16%  |
| 301-350        | 7         | 9.46%   |
| Unknown        | 7         | 9.46%   |
| 101-110        | 5         | 6.76%   |
| 71-80          | 4         | 5.41%   |
| 251-300        | 3         | 4.05%   |
| 121-130        | 3         | 4.05%   |
| 501-1000       | 3         | 4.05%   |
| 61-70          | 2         | 2.7%    |
| 351-500        | 2         | 2.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 25        | 34.72%  |
| 51-100        | 17        | 23.61%  |
| 161-240       | 13        | 18.06%  |
| 101-120       | 7         | 9.72%   |
| Unknown       | 7         | 9.72%   |
| More than 240 | 2         | 2.78%   |
| 1-50          | 1         | 1.39%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 53        | 53.54%  |
| 0     | 36        | 36.36%  |
| 2     | 9         | 9.09%   |
| 3     | 1         | 1.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 67        | 46.53%  |
| Realtek Semiconductor           | 42        | 29.17%  |
| TP-Link                         | 5         | 3.47%   |
| Broadcom                        | 5         | 3.47%   |
| Ralink Technology               | 4         | 2.78%   |
| Qualcomm Atheros                | 4         | 2.78%   |
| Hewlett-Packard                 | 4         | 2.78%   |
| Edimax Technology               | 2         | 1.39%   |
| D-Link System                   | 2         | 1.39%   |
| Qualcomm Atheros Communications | 1         | 0.69%   |
| Mellanox Technologies           | 1         | 0.69%   |
| Lenovo                          | 1         | 0.69%   |
| Google                          | 1         | 0.69%   |
| Emulex                          | 1         | 0.69%   |
| BUFFALO                         | 1         | 0.69%   |
| ASUSTek Computer                | 1         | 0.69%   |
| Arduino SA                      | 1         | 0.69%   |
| Aquantia                        | 1         | 0.69%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 35        | 19.44%  |
| Intel Wi-Fi 6 AX200                                                           | 10        | 5.56%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 6         | 3.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6         | 3.33%   |
| Intel Wireless-AC 9260                                                        | 5         | 2.78%   |
| Intel Wireless 8265 / 8275                                                    | 5         | 2.78%   |
| Intel I211 Gigabit Network Connection                                         | 5         | 2.78%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 5         | 2.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 5         | 2.78%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 4         | 2.22%   |
| Intel Wi-Fi 6 AX201                                                           | 4         | 2.22%   |
| Intel I210 Gigabit Network Connection                                         | 4         | 2.22%   |
| HP hs2350 HSPA+ Mobile Broadband Module Network Adapter                       | 4         | 2.22%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 3         | 1.67%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 3         | 1.67%   |
| Realtek RTL8125 2.5GbE Controller                                             | 3         | 1.67%   |
| Intel Ethernet Controller I225-V                                              | 3         | 1.67%   |
| Intel 82574L Gigabit Network Connection                                       | 3         | 1.67%   |
| Ralink MT7601U Wireless Adapter                                               | 2         | 1.11%   |
| Intel Wireless 7265                                                           | 2         | 1.11%   |
| Intel Wireless 7260                                                           | 2         | 1.11%   |
| Intel Ethernet Connection (4) I219-LM                                         | 2         | 1.11%   |
| Intel Ethernet Connection (14) I219-LM                                        | 2         | 1.11%   |
| Intel Ethernet Connection (11) I219-LM                                        | 2         | 1.11%   |
| Intel Ethernet Connection (10) I219-V                                         | 2         | 1.11%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2         | 1.11%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]    | 2         | 1.11%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1         | 0.56%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]           | 1         | 0.56%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                      | 1         | 0.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.56%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                        | 1         | 0.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1         | 0.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 0.56%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 0.56%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1         | 0.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1         | 0.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 1         | 0.56%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 1         | 0.56%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1         | 0.56%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1         | 0.56%   |
| Mellanox MT27710 Family [ConnectX-4 Lx]                                       | 1         | 0.56%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                              | 1         | 0.56%   |
| Intel Wireless 8260                                                           | 1         | 0.56%   |
| Intel Wi-Fi 6 AX201 160MHz                                                    | 1         | 0.56%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 0.56%   |
| Intel I350 Gigabit Network Connection                                         | 1         | 0.56%   |
| Intel Ethernet Controller I225-LM                                             | 1         | 0.56%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 1         | 0.56%   |
| Intel Ethernet Connection I219-LM                                             | 1         | 0.56%   |
| Intel Ethernet Connection I217-LM                                             | 1         | 0.56%   |
| Intel Ethernet Connection (7) I219-V                                          | 1         | 0.56%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1         | 0.56%   |
| Intel Ethernet Connection (5) I219-V                                          | 1         | 0.56%   |
| Intel Ethernet Connection (3) I218-LM                                         | 1         | 0.56%   |
| Intel Ethernet Connection (13) I219-V                                         | 1         | 0.56%   |
| Intel Ethernet Connection (11) I219-V                                         | 1         | 0.56%   |
| Intel Centrino Advanced-N 6235                                                | 1         | 0.56%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller             | 1         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 54        | 64.29%  |
| Realtek Semiconductor           | 7         | 8.33%   |
| TP-Link                         | 5         | 5.95%   |
| Ralink Technology               | 4         | 4.76%   |
| Broadcom                        | 4         | 4.76%   |
| Qualcomm Atheros                | 3         | 3.57%   |
| Edimax Technology               | 2         | 2.38%   |
| D-Link System                   | 2         | 2.38%   |
| Qualcomm Atheros Communications | 1         | 1.19%   |
| BUFFALO                         | 1         | 1.19%   |
| ASUSTek Computer                | 1         | 1.19%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                           | 10        | 11.9%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 6         | 7.14%   |
| Intel Wireless-AC 9260                                                        | 5         | 5.95%   |
| Intel Wireless 8265 / 8275                                                    | 5         | 5.95%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 5         | 5.95%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 5         | 5.95%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 4         | 4.76%   |
| Intel Wi-Fi 6 AX201                                                           | 4         | 4.76%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 3         | 3.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 3         | 3.57%   |
| Ralink MT7601U Wireless Adapter                                               | 2         | 2.38%   |
| Intel Wireless 7265                                                           | 2         | 2.38%   |
| Intel Wireless 7260                                                           | 2         | 2.38%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2         | 2.38%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]    | 2         | 2.38%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1         | 1.19%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]           | 1         | 1.19%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                      | 1         | 1.19%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.19%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.19%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                        | 1         | 1.19%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 1.19%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1         | 1.19%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1         | 1.19%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 1         | 1.19%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 1         | 1.19%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1         | 1.19%   |
| Intel Wireless 8260                                                           | 1         | 1.19%   |
| Intel Wi-Fi 6 AX201 160MHz                                                    | 1         | 1.19%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 1.19%   |
| Intel Centrino Advanced-N 6235                                                | 1         | 1.19%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                | 1         | 1.19%   |
| Edimax EW-7711MAC 802.11ac Wireless Adapter                                   | 1         | 1.19%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]                      | 1         | 1.19%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                   | 1         | 1.19%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 1         | 1.19%   |
| Broadcom BCM4331 802.11a/b/g/n                                                | 1         | 1.19%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 1         | 1.19%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                                           | 1         | 1.19%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 39        | 45.88%  |
| Intel                 | 39        | 45.88%  |
| Broadcom              | 2         | 2.35%   |
| Qualcomm Atheros      | 1         | 1.18%   |
| Lenovo                | 1         | 1.18%   |
| Google                | 1         | 1.18%   |
| Emulex                | 1         | 1.18%   |
| Aquantia              | 1         | 1.18%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 35        | 39.33%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6         | 6.74%   |
| Intel I211 Gigabit Network Connection                                         | 5         | 5.62%   |
| Intel I210 Gigabit Network Connection                                         | 4         | 4.49%   |
| Realtek RTL8125 2.5GbE Controller                                             | 3         | 3.37%   |
| Intel Ethernet Controller I225-V                                              | 3         | 3.37%   |
| Intel 82574L Gigabit Network Connection                                       | 3         | 3.37%   |
| Intel Ethernet Connection (4) I219-LM                                         | 2         | 2.25%   |
| Intel Ethernet Connection (14) I219-LM                                        | 2         | 2.25%   |
| Intel Ethernet Connection (11) I219-LM                                        | 2         | 2.25%   |
| Intel Ethernet Connection (10) I219-V                                         | 2         | 2.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1         | 1.12%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 1.12%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1         | 1.12%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                              | 1         | 1.12%   |
| Intel I350 Gigabit Network Connection                                         | 1         | 1.12%   |
| Intel Ethernet Controller I225-LM                                             | 1         | 1.12%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 1         | 1.12%   |
| Intel Ethernet Connection I219-LM                                             | 1         | 1.12%   |
| Intel Ethernet Connection I217-LM                                             | 1         | 1.12%   |
| Intel Ethernet Connection (7) I219-V                                          | 1         | 1.12%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1         | 1.12%   |
| Intel Ethernet Connection (5) I219-V                                          | 1         | 1.12%   |
| Intel Ethernet Connection (3) I218-LM                                         | 1         | 1.12%   |
| Intel Ethernet Connection (13) I219-V                                         | 1         | 1.12%   |
| Intel Ethernet Connection (11) I219-V                                         | 1         | 1.12%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 1.12%   |
| Google Nexus/Pixel Device (charging + debug)                                  | 1         | 1.12%   |
| Emulex OneConnect 10Gb NIC (be3)                                              | 1         | 1.12%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                             | 1         | 1.12%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 1         | 1.12%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 1         | 1.12%   |
| Unknown                                                                       | 1         | 1.12%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 77        | 50.33%  |
| WiFi     | 69        | 45.1%   |
| Modem    | 6         | 3.92%   |
| Unknown  | 1         | 0.65%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 67        | 61.47%  |
| WiFi     | 39        | 35.78%  |
| Modem    | 3         | 2.75%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 56        | 57.73%  |
| 1     | 19        | 19.59%  |
| 0     | 13        | 13.4%   |
| 3     | 6         | 6.19%   |
| 4     | 2         | 2.06%   |
| 7     | 1         | 1.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 81        | 79.41%  |
| Yes  | 21        | 20.59%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 40        | 80%     |
| Apple                           | 3         | 6%      |
| Realtek Semiconductor           | 2         | 4%      |
| Realtek                         | 1         | 2%      |
| Qualcomm Atheros Communications | 1         | 2%      |
| IMC Networks                    | 1         | 2%      |
| Cambridge Silicon Radio         | 1         | 2%      |
| Broadcom                        | 1         | 2%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 12        | 24%     |
| Intel AX200 Bluetooth                               | 9         | 18%     |
| Intel Bluetooth wireless interface                  | 7         | 14%     |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4         | 8%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 8%      |
| Intel AX210 Bluetooth                               | 3         | 6%      |
| Apple Bluetooth Host Controller                     | 2         | 4%      |
| Realtek  Bluetooth Adapter                          | 1         | 2%      |
| Realtek Bluetooth Radio                             | 1         | 2%      |
| Realtek Bluetooth Radio                             | 1         | 2%      |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 2%      |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2%      |
| IMC Networks Bluetooth module                       | 1         | 2%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2%      |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 2%      |
| Apple Apple Broadcom Built-in Bluetooth             | 1         | 2%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 47        | 39.5%   |
| AMD                     | 37        | 31.09%  |
| Nvidia                  | 23        | 19.33%  |
| Lenovo                  | 3         | 2.52%   |
| Yamaha                  | 1         | 0.84%   |
| SteelSeries ApS         | 1         | 0.84%   |
| Logitech                | 1         | 0.84%   |
| GN Netcom               | 1         | 0.84%   |
| Generalplus Technology  | 1         | 0.84%   |
| CMX Systems             | 1         | 0.84%   |
| C-Media Electronics     | 1         | 0.84%   |
| AudioQuest              | 1         | 0.84%   |
| AKAI  Professional M.I. | 1         | 0.84%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 20        | 13.61%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 11        | 7.48%   |
| Intel Comet Lake PCH cAVS                                                  | 9         | 6.12%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 5.44%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8         | 5.44%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 4.08%   |
| AMD Starship/Matisse HD Audio Controller                                   | 6         | 4.08%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5         | 3.4%    |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 3.4%    |
| Nvidia GP107GL High Definition Audio Controller                            | 4         | 2.72%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 2.72%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4         | 2.72%   |
| Intel Sunrise Point-LP HD Audio                                            | 3         | 2.04%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 3         | 2.04%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 1.36%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 1.36%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 1.36%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 1.36%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 1.36%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 1.36%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 1.36%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2         | 1.36%   |
| AMD Navi 10 HDMI Audio                                                     | 2         | 1.36%   |
| Yamaha Steinberg UR12                                                      | 1         | 0.68%   |
| SteelSeries ApS SteelSeries Siberia 350                                    | 1         | 0.68%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.68%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 0.68%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.68%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 0.68%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.68%   |
| Nvidia GM206 High Definition Audio Controller                              | 1         | 0.68%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.68%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 0.68%   |
| Logitech H390 headset with microphone                                      | 1         | 0.68%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                   | 1         | 0.68%   |
| Lenovo ThinkPad Dock Audio                                                 | 1         | 0.68%   |
| Lenovo Realtek USB Audio                                                   | 1         | 0.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 0.68%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 0.68%   |
| Intel Jasper Lake HD Audio                                                 | 1         | 0.68%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 0.68%   |
| Intel CM238 HD Audio Controller                                            | 1         | 0.68%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 0.68%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 0.68%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 1         | 0.68%   |
| GN Netcom Jabra SPEAK 410 USB                                              | 1         | 0.68%   |
| Generalplus Technology USB Audio Device                                    | 1         | 0.68%   |
| CMX Systems USB PnP Audio Device                                           | 1         | 0.68%   |
| C-Media Electronics Anua Mic CM 900                                        | 1         | 0.68%   |
| AudioQuest DragonFly                                                       | 1         | 0.68%   |
| AMD Wrestler HDMI Audio                                                    | 1         | 0.68%   |
| AMD RV630 HDMI Audio [Radeon HD 2600 PRO/XT / HD 3610]                     | 1         | 0.68%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1         | 0.68%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1         | 0.68%   |
| AKAI  Professional M.I. LPK25 MIDI Keyboard                                | 1         | 0.68%   |
| Unknown                                                                    | 1         | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 20        | 21.28%  |
| SK hynix               | 14        | 14.89%  |
| Micron Technology      | 14        | 14.89%  |
| Kingston               | 11        | 11.7%   |
| Crucial                | 8         | 8.51%   |
| Corsair                | 5         | 5.32%   |
| Unknown                | 5         | 5.32%   |
| Smart                  | 3         | 3.19%   |
| Team                   | 2         | 2.13%   |
| Ramaxel Technology     | 2         | 2.13%   |
| Goodram                | 2         | 2.13%   |
| Unknown (000000000C01) | 1         | 1.06%   |
| Transcend              | 1         | 1.06%   |
| PNY                    | 1         | 1.06%   |
| KLEVV                  | 1         | 1.06%   |
| Gold Key               | 1         | 1.06%   |
| G.Skill                | 1         | 1.06%   |
| A-DATA Technology      | 1         | 1.06%   |
| 06F100000C01           | 1         | 1.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown                                                      | 5         | 5.21%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s        | 4         | 4.17%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 2.08%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 2         | 2.08%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s       | 2         | 2.08%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 2         | 2.08%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s        | 2         | 2.08%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s         | 2         | 2.08%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s         | 2         | 2.08%   |
| Crucial RAM BL32G32C16S4B.M16FB1 32GB SODIMM DDR4 2667MT/s   | 2         | 2.08%   |
| Corsair RAM CMK32GX4M2D3200C16 16GB DIMM DDR4 3200MT/s       | 2         | 2.08%   |
| Unknown (000000000C01) RAM Module 32GB DIMM DDR4 3200MT/s    | 1         | 1.04%   |
| Transcend RAM JM2666HLE-32G 32GB DIMM DDR4 2666MT/s          | 1         | 1.04%   |
| Team RAM TEAMGROUP-UD4-4133 8GB DIMM DDR4 4133MT/s           | 1         | 1.04%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s        | 1         | 1.04%   |
| Smart RAM SF4641G8CK8IWGKSEG 8GB SODIMM DDR4 2133MT/s        | 1         | 1.04%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s        | 1         | 1.04%   |
| Smart RAM Module 8GB DIMM DDR4 2667MT/s                      | 1         | 1.04%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1867MT/s                 | 1         | 1.04%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                 | 1         | 1.04%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s      | 1         | 1.04%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 1.04%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 1         | 1.04%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 1.04%   |
| Samsung RAM M474A4G43AB1-CVF 32GB SODIMM DDR4 2933MT/s       | 1         | 1.04%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s        | 1         | 1.04%   |
| Samsung RAM M471B5674-M0-YK0 4GB Chip DDR3 1600MT/s          | 1         | 1.04%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 1         | 1.04%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s        | 1         | 1.04%   |
| Samsung RAM M471A5244BB0-CWE 4GB SODIMM DDR4 3200MT/s        | 1         | 1.04%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s       | 1         | 1.04%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s       | 1         | 1.04%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s       | 1         | 1.04%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 1         | 1.04%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s  | 1         | 1.04%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 1.04%   |
| Samsung RAM M378A4G43MB1-CTD 32GB DIMM DDR4 2666MT/s         | 1         | 1.04%   |
| Samsung RAM K4EBE304EB-EGCF 8GB Row Of Chips LPDDR3 1867MT/s | 1         | 1.04%   |
| Ramaxel RAM RMSA3320MJ78HAF-3200 8GB SODIMM DDR4 3200MT/s    | 1         | 1.04%   |
| Ramaxel RAM RMSA3300MH78HBF-2666 16GB SODIMM DDR4 2400MT/s   | 1         | 1.04%   |
| PNY RAM 16GU2X16LIII43-12-K 16GB SODIMM DDR4 2667MT/s        | 1         | 1.04%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                   | 1         | 1.04%   |
| Micron RAM Module 16GB DIMM DDR4 2400MT/s                    | 1         | 1.04%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s  | 1         | 1.04%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s        | 1         | 1.04%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s   | 1         | 1.04%   |
| Micron RAM 4ATF1G64HZ-3G2B2 8GB SODIMM DDR4 3200MT/s         | 1         | 1.04%   |
| Micron RAM 18ASF4G72AZ-3G2B1 32GB DIMM DDR4 3200MT/s         | 1         | 1.04%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s        | 1         | 1.04%   |
| Micron RAM 16ATF2G64HZ-2G6J1 16GB SODIMM DDR4 2667MT/s       | 1         | 1.04%   |
| Micron RAM 16ATF2G64AZ-3G2J1 16GB DIMM DDR4 3200MT/s         | 1         | 1.04%   |
| KLEVV RAM KD4AGSA8M-32N220A 16GB SODIMM DDR4 3200MT/s        | 1         | 1.04%   |
| Kingston RAM Module 8GB SODIMM DDR4 2667MT/s                 | 1         | 1.04%   |
| Kingston RAM Module 16GB SODIMM DDR4 2667MT/s                | 1         | 1.04%   |
| Kingston RAM Module 16GB SODIMM DDR4 2400MT/s                | 1         | 1.04%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 2933MT/s         | 1         | 1.04%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s       | 1         | 1.04%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 2666MT/s          | 1         | 1.04%   |
| Kingston RAM KHX2400C14S4/4G 4GB SODIMM DDR4 2400MT/s        | 1         | 1.04%   |
| Kingston RAM KHX1600C10D3/ 8GB DIMM DDR3 1600MT/s            | 1         | 1.04%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 65        | 78.31%  |
| DDR3   | 15        | 18.07%  |
| LPDDR4 | 1         | 1.2%    |
| LPDDR3 | 1         | 1.2%    |
| DDR    | 1         | 1.2%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 56        | 66.67%  |
| DIMM         | 23        | 27.38%  |
| Row Of Chips | 4         | 4.76%   |
| Chip         | 1         | 1.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 34        | 39.53%  |
| 16384 | 27        | 31.4%   |
| 32768 | 12        | 13.95%  |
| 4096  | 10        | 11.63%  |
| 2048  | 2         | 2.33%   |
| 1024  | 1         | 1.16%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 31        | 35.63%  |
| 2667    | 18        | 20.69%  |
| 1600    | 8         | 9.2%    |
| 1867    | 6         | 6.9%    |
| 2400    | 5         | 5.75%   |
| 2666    | 4         | 4.6%    |
| 2133    | 4         | 4.6%    |
| 2933    | 3         | 3.45%   |
| 1333    | 2         | 2.3%    |
| 4267    | 1         | 1.15%   |
| 4133    | 1         | 1.15%   |
| 3600    | 1         | 1.15%   |
| 3000    | 1         | 1.15%   |
| 1334    | 1         | 1.15%   |
| Unknown | 1         | 1.15%   |

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
| Chicony Electronics                    | 14        | 23.73%  |
| IMC Networks                           | 10        | 16.95%  |
| Realtek Semiconductor                  | 6         | 10.17%  |
| Logitech                               | 6         | 10.17%  |
| Lite-On Technology                     | 5         | 8.47%   |
| Acer                                   | 5         | 8.47%   |
| Sunplus Innovation Technology          | 4         | 6.78%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 5.08%   |
| Microdia                               | 2         | 3.39%   |
| Syntek                                 | 1         | 1.69%   |
| GEMBIRD                                | 1         | 1.69%   |
| Aveo Technology                        | 1         | 1.69%   |
| Apple                                  | 1         | 1.69%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                             | 7         | 11.67%  |
| Chicony Integrated Camera                                                  | 6         | 10%     |
| Sunplus Integrated_Webcam_HD                                               | 3         | 5%      |
| Logitech Webcam C270                                                       | 3         | 5%      |
| Lite-On Integrated Camera                                                  | 3         | 5%      |
| Chicony Integrated HP HD Webcam                                            | 3         | 5%      |
| Acer Integrated Camera                                                     | 3         | 5%      |
| Realtek Laptop Camera                                                      | 2         | 3.33%   |
| Realtek Integrated_Webcam_HD                                               | 2         | 3.33%   |
| Lite-On HP HD Camera                                                       | 2         | 3.33%   |
| Acer HD Webcam                                                             | 2         | 3.33%   |
| Syntek Lenovo EasyCamera                                                   | 1         | 1.67%   |
| Sunplus Integrated_Webcam_FHD                                              | 1         | 1.67%   |
| Realtek USB 2 Webcam                                                       | 1         | 1.67%   |
| Realtek Realtek USB2.0 PC Camera                                           | 1         | 1.67%   |
| Microdia HP Integrated Webcam                                              | 1         | 1.67%   |
| Microdia Dell Integrated HD Webcam                                         | 1         | 1.67%   |
| Logitech Webcam C170                                                       | 1         | 1.67%   |
| Logitech HD Pro Webcam C920                                                | 1         | 1.67%   |
| Logitech C920 PRO HD Webcam                                                | 1         | 1.67%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 1         | 1.67%   |
| IMC Networks HD Camera                                                     | 1         | 1.67%   |
| IMC Networks EasyCamera                                                    | 1         | 1.67%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]                          | 1         | 1.67%   |
| Chicony USB2.0 0.3M UVC WebCam                                             | 1         | 1.67%   |
| Chicony ThinkPad T490 Webcam                                               | 1         | 1.67%   |
| Chicony Ltd., Integrated Camera                                            | 1         | 1.67%   |
| Chicony Integrated IR Camera                                               | 1         | 1.67%   |
| Chicony HD Webcam                                                          | 1         | 1.67%   |
| Chicony Chicony USB2.0 Camera                                              | 1         | 1.67%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 1.67%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed]                | 1         | 1.67%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam   | 1         | 1.67%   |
| Aveo USB2.0 Camera                                                         | 1         | 1.67%   |
| Apple FaceTime HD Camera (Built-in)                                        | 1         | 1.67%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 8         | 44.44%  |
| Validity Sensors           | 5         | 27.78%  |
| Shenzhen Goodix Technology | 4         | 22.22%  |
| AuthenTec                  | 1         | 5.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 27.78%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 11.11%  |
| Validity Sensors Synaptics WBDI                                            | 2         | 11.11%  |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 11.11%  |
| Shenzhen Goodix  FingerPrint Device                                        | 2         | 11.11%  |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 11.11%  |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 5.56%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 5.56%   |
| AuthenTec AES2810                                                          | 1         | 5.56%   |

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
| 0     | 28        | 28.28%  |
| 2     | 27        | 27.27%  |
| 4     | 15        | 15.15%  |
| 1     | 15        | 15.15%  |
| 3     | 10        | 10.1%   |
| 5     | 3         | 3.03%   |
| 9     | 1         | 1.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 53        | 35.57%  |
| Bluetooth                | 31        | 20.81%  |
| Net/wireless             | 27        | 18.12%  |
| Fingerprint reader       | 18        | 12.08%  |
| Card reader              | 8         | 5.37%   |
| Sound                    | 5         | 3.36%   |
| Net/ethernet             | 3         | 2.01%   |
| Firewire controller      | 2         | 1.34%   |
| Network                  | 1         | 0.67%   |
| Modem                    | 1         | 0.67%   |

