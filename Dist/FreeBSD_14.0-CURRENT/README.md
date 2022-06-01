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

Total: 181

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
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
| Unknown       | Unknown                     | Desktop     | [6e7384f4cc](https://bsd-hardware.info/?probe=6e7384f4cc) | Mar 15, 2022 |
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

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 79        | 83.16%  |
| arm64 | 12        | 12.63%  |
| arm   | 2         | 2.11%   |
| riscv | 1         | 1.05%   |
| i386  | 1         | 1.05%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KDE5          | 26        | 25.74%  |
| Console       | 23        | 22.77%  |
| XFCE          | 11        | 10.89%  |
| MATE          | 8         | 7.92%   |
| TWM           | 5         | 4.95%   |
| i3            | 5         | 4.95%   |
| GNOME         | 5         | 4.95%   |
| Openbox       | 3         | 2.97%   |
| Cinnamon      | 3         | 2.97%   |
| LXDE          | 2         | 1.98%   |
| Lumina        | 2         | 1.98%   |
| Xfwm4         | 1         | 0.99%   |
| Picom         | 1         | 0.99%   |
| LXQt          | 1         | 0.99%   |
| GNUstep       | 1         | 0.99%   |
| Fluxbox       | 1         | 0.99%   |
| Enlightenment | 1         | 0.99%   |
| ctwm          | 1         | 0.99%   |
| akonadi_newm  | 1         | 0.99%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 69        | 69.7%   |
| Console | 28        | 28.28%  |
| Wayland | 2         | 2.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 44        | 44.9%   |
| SDDM    | 24        | 24.49%  |
| SLiM    | 11        | 11.22%  |
| GDM     | 9         | 9.18%   |
| XDM     | 6         | 6.12%   |
| LightDM | 3         | 3.06%   |
| Ly      | 1         | 1.02%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang             | Computers | Percent |
|------------------|-----------|---------|
| C                | 63        | 64.29%  |
| en_US            | 12        | 12.24%  |
| Unknown          | 5         | 5.1%    |
| uk_UA            | 3         | 3.06%   |
| en_GB            | 3         | 3.06%   |
| de_DE            | 3         | 3.06%   |
| zh_CN            | 2         | 2.04%   |
| sv_SE            | 1         | 1.02%   |
| ru_RU            | 1         | 1.02%   |
| pt_PT            | 1         | 1.02%   |
| pl_PL            | 1         | 1.02%   |
| it_IT.ISO8859-15 | 1         | 1.02%   |
| fr_FR            | 1         | 1.02%   |
| de_CH            | 1         | 1.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 83        | 87.37%  |
| BIOS | 12        | 12.63%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 69        | 72.63%  |
| Ufs  | 26        | 27.37%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 86        | 90.53%  |
| MBR  | 9         | 9.47%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 24        | 25.26%  |
| ASUSTek Computer               | 11        | 11.58%  |
| Hewlett-Packard                | 9         | 9.47%   |
| Unknown                        | 9         | 9.47%   |
| Dell                           | 8         | 8.42%   |
| Gigabyte Technology            | 7         | 7.37%   |
| Raspberry Pi Foundation        | 4         | 4.21%   |
| MSI                            | 3         | 3.16%   |
| Framework                      | 3         | 3.16%   |
| ASRock                         | 3         | 3.16%   |
| Intel                          | 2         | 2.11%   |
| Beckhoff Automation            | 2         | 2.11%   |
| Apple                          | 2         | 2.11%   |
| pine64                         | 1         | 1.05%   |
| Notebook                       | 1         | 1.05%   |
| Matsushita Electric Industrial | 1         | 1.05%   |
| khadas                         | 1         | 1.05%   |
| HUAWEI                         | 1         | 1.05%   |
| friendlyelec                   | 1         | 1.05%   |
| Avell High Performance         | 1         | 1.05%   |
| A-DATA Technology              | 1         | 1.05%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 10        | 10.53%  |
| RPi Raspberry Pi                            | 3         | 3.16%   |
| HP EliteBook 8570p                          | 3         | 3.16%   |
| Framework Laptop                            | 3         | 3.16%   |
| RPi rpi                                     | 1         | 1.05%   |
| pine64 pinebook-pro-rk3399                  | 1         | 1.05%   |
| Notebook NS50_70MU                          | 1         | 1.05%   |
| MSI MS-7B86                                 | 1         | 1.05%   |
| MSI GE76 Raider 10UG                        | 1         | 1.05%   |
| MSI Bravo 15 A4DDR                          | 1         | 1.05%   |
| Matsushita Electric Industrial CF-T2BW1AXR  | 1         | 1.05%   |
| Lenovo XiaoXinPro-13ARE 2020 82DM           | 1         | 1.05%   |
| Lenovo ThinkPad X395 20NL001SMX             | 1         | 1.05%   |
| Lenovo ThinkPad X395 20NL000GPG             | 1         | 1.05%   |
| Lenovo ThinkPad X270 20HM004JBR             | 1         | 1.05%   |
| Lenovo ThinkPad X260 20F5A28AUK             | 1         | 1.05%   |
| Lenovo ThinkPad X13 Gen 1 20T2003PRT        | 1         | 1.05%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TLA055CD | 1         | 1.05%   |
| Lenovo ThinkPad X1 Extreme 20MF000BUS       | 1         | 1.05%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS1QC00    | 1         | 1.05%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS0BT00    | 1         | 1.05%   |
| Lenovo ThinkPad T495s 20QKS1812F            | 1         | 1.05%   |
| Lenovo ThinkPad T470p 20J7S0PM00            | 1         | 1.05%   |
| Lenovo ThinkPad T430 2349H2G                | 1         | 1.05%   |
| Lenovo ThinkPad T14s Gen 2i 20WM00B7MX      | 1         | 1.05%   |
| Lenovo ThinkPad P15 Gen 1 20ST005VRT        | 1         | 1.05%   |
| Lenovo ThinkPad P14s Gen 1 20Y1CTO1WW       | 1         | 1.05%   |
| Lenovo ThinkPad E14 Gen 3 20Y7003SGE        | 1         | 1.05%   |
| Lenovo ThinkPad E14 20RBCTO1WW              | 1         | 1.05%   |
| Lenovo ThinkBook 14 G3 ACL 21A2             | 1         | 1.05%   |
| Lenovo Legion 5P 15IMH05H 82AW              | 1         | 1.05%   |
| Lenovo Legion 5 15IMH05 82AU                | 1         | 1.05%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY        | 1         | 1.05%   |
| Lenovo IdeaPad 330-15ARR 81D2               | 1         | 1.05%   |
| khadas edge-v                               | 1         | 1.05%   |
| Intel S2600WTTR                             | 1         | 1.05%   |
| Intel NUC11PHi7                             | 1         | 1.05%   |
| HUAWEI HN-WX9X                              | 1         | 1.05%   |
| HP ZBook 17 G2                              | 1         | 1.05%   |
| HP ProBook 455 G7                           | 1         | 1.05%   |
| HP ProBook 440 G7                           | 1         | 1.05%   |
| HP ProBook 440 G6                           | 1         | 1.05%   |
| HP EliteDesk 800 G4 SFF                     | 1         | 1.05%   |
| HP EliteBook Folio 9470m                    | 1         | 1.05%   |
| Gigabyte X570 AORUS MASTER                  | 1         | 1.05%   |
| Gigabyte X570 AORUS ELITE                   | 1         | 1.05%   |
| Gigabyte X399 DESIGNARE EX                  | 1         | 1.05%   |
| Gigabyte B550I AORUS PRO AX                 | 1         | 1.05%   |
| Gigabyte B450M S2H                          | 1         | 1.05%   |
| Gigabyte B450M DS3H                         | 1         | 1.05%   |
| Gigabyte 970A-UD3P                          | 1         | 1.05%   |
| friendlyelec nanopi-m4                      | 1         | 1.05%   |
| Dell Vostro 5490                            | 1         | 1.05%   |
| Dell PowerEdge T150                         | 1         | 1.05%   |
| Dell OptiPlex 5490 AIO                      | 1         | 1.05%   |
| Dell OptiPlex 5080                          | 1         | 1.05%   |
| Dell Latitude E5430 vPro                    | 1         | 1.05%   |
| Dell Inspiron 3793                          | 1         | 1.05%   |
| Dell G5 5505                                | 1         | 1.05%   |
| Dell G3 3500                                | 1         | 1.05%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo ThinkPad                            | 17        | 17.89%  |
| Unknown                                    | 10        | 10.53%  |
| ASUS PRIME                                 | 5         | 5.26%   |
| HP EliteBook                               | 4         | 4.21%   |
| RPi Raspberry                              | 3         | 3.16%   |
| HP ProBook                                 | 3         | 3.16%   |
| Framework Laptop                           | 3         | 3.16%   |
| Lenovo Legion                              | 2         | 2.11%   |
| Lenovo IdeaPad                             | 2         | 2.11%   |
| Gigabyte X570                              | 2         | 2.11%   |
| Gigabyte B450M                             | 2         | 2.11%   |
| Dell OptiPlex                              | 2         | 2.11%   |
| RPi rpi                                    | 1         | 1.05%   |
| pine64 pinebook-pro-rk3399                 | 1         | 1.05%   |
| Notebook NS50                              | 1         | 1.05%   |
| MSI MS-7B86                                | 1         | 1.05%   |
| MSI GE76                                   | 1         | 1.05%   |
| MSI Bravo                                  | 1         | 1.05%   |
| Matsushita Electric Industrial CF-T2BW1AXR | 1         | 1.05%   |
| Lenovo XiaoXinPro-13ARE                    | 1         | 1.05%   |
| Lenovo ThinkBook                           | 1         | 1.05%   |
| khadas edge-v                              | 1         | 1.05%   |
| Intel S2600WTTR                            | 1         | 1.05%   |
| Intel NUC11PHi7                            | 1         | 1.05%   |
| HUAWEI HN-WX9X                             | 1         | 1.05%   |
| HP ZBook                                   | 1         | 1.05%   |
| HP EliteDesk                               | 1         | 1.05%   |
| Gigabyte X399                              | 1         | 1.05%   |
| Gigabyte B550I                             | 1         | 1.05%   |
| Gigabyte 970A-UD3P                         | 1         | 1.05%   |
| friendlyelec nanopi-m4                     | 1         | 1.05%   |
| Dell Vostro                                | 1         | 1.05%   |
| Dell PowerEdge                             | 1         | 1.05%   |
| Dell Latitude                              | 1         | 1.05%   |
| Dell Inspiron                              | 1         | 1.05%   |
| Dell G5                                    | 1         | 1.05%   |
| Dell G3                                    | 1         | 1.05%   |
| Beckhoff Automation CX2033-0185            | 1         | 1.05%   |
| Beckhoff Automation CBxx63                 | 1         | 1.05%   |
| Avell High Performance A62                 | 1         | 1.05%   |
| ASUS VivoBook                              | 1         | 1.05%   |
| ASUS TUF                                   | 1         | 1.05%   |
| ASUS ROG                                   | 1         | 1.05%   |
| ASUS P8H77-M                               | 1         | 1.05%   |
| ASUS MINIPC                                | 1         | 1.05%   |
| ASUS 1215B                                 | 1         | 1.05%   |
| ASRock X570                                | 1         | 1.05%   |
| ASRock B550                                | 1         | 1.05%   |
| ASRock B450                                | 1         | 1.05%   |
| Apple MacBookPro12                         | 1         | 1.05%   |
| Apple MacBookPro10                         | 1         | 1.05%   |
| A-DATA XENIA159GENI72060                   | 1         | 1.05%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 25        | 26.32%  |
| 2021    | 24        | 25.26%  |
| 2019    | 12        | 12.63%  |
| Unknown | 9         | 9.47%   |
| 2018    | 7         | 7.37%   |
| 2017    | 4         | 4.21%   |
| 2013    | 4         | 4.21%   |
| 2015    | 3         | 3.16%   |
| 2022    | 2         | 2.11%   |
| 2016    | 2         | 2.11%   |
| 2012    | 1         | 1.05%   |
| 2011    | 1         | 1.05%   |
| 2003    | 1         | 1.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 51        | 53.68%  |
| Desktop        | 32        | 33.68%  |
| System on chip | 7         | 7.37%   |
| Mini pc        | 2         | 2.11%   |
| Server         | 2         | 2.11%   |
| All in one     | 1         | 1.05%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 95        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 35        | 36.46%  |
| 8.01-16.0       | 18        | 18.75%  |
| 32.01-64.0      | 16        | 16.67%  |
| 64.01-256.0     | 13        | 13.54%  |
| 4.01-8.0        | 7         | 7.29%   |
| 0.51-1.0        | 2         | 2.08%   |
| More than 256.0 | 1         | 1.04%   |
| 3.01-4.0        | 1         | 1.04%   |
| 24.01-32.0      | 1         | 1.04%   |
| 1.01-2.0        | 1         | 1.04%   |
| 0.01-0.5        | 1         | 1.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.51-1.0    | 32        | 33.33%  |
| 1.01-2.0    | 26        | 27.08%  |
| 0.01-0.5    | 15        | 15.63%  |
| 2.01-3.0    | 9         | 9.38%   |
| 3.01-4.0    | 5         | 5.21%   |
| 24.01-32.0  | 2         | 2.08%   |
| 0           | 2         | 2.08%   |
| 4.01-8.0    | 1         | 1.04%   |
| 32.01-64.0  | 1         | 1.04%   |
| 64.01-256.0 | 1         | 1.04%   |
| 16.01-24.0  | 1         | 1.04%   |
| 8.01-16.0   | 1         | 1.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 48        | 48%     |
| 2      | 26        | 26%     |
| 0      | 11        | 11%     |
| 6      | 5         | 5%      |
| 3      | 5         | 5%      |
| 4      | 2         | 2%      |
| 15     | 1         | 1%      |
| 7      | 1         | 1%      |
| 5      | 1         | 1%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 83        | 85.57%  |
| Yes       | 14        | 14.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 77.89%  |
| No        | 21        | 22.11%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 66        | 69.47%  |
| No        | 29        | 30.53%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 49        | 51.04%  |
| No        | 47        | 48.96%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 17        | 17.89%  |
| UK           | 10        | 10.53%  |
| Russia       | 10        | 10.53%  |
| Germany      | 9         | 9.47%   |
| Brazil       | 6         | 6.32%   |
| Ukraine      | 4         | 4.21%   |
| Japan        | 4         | 4.21%   |
| China        | 4         | 4.21%   |
| Austria      | 4         | 4.21%   |
| Portugal     | 3         | 3.16%   |
| Poland       | 3         | 3.16%   |
| Switzerland  | 2         | 2.11%   |
| Sweden       | 2         | 2.11%   |
| Netherlands  | 2         | 2.11%   |
| Turkey       | 1         | 1.05%   |
| Spain        | 1         | 1.05%   |
| Singapore    | 1         | 1.05%   |
| Saudi Arabia | 1         | 1.05%   |
| Romania      | 1         | 1.05%   |
| Peru         | 1         | 1.05%   |
| Jamaica      | 1         | 1.05%   |
| Italy        | 1         | 1.05%   |
| India        | 1         | 1.05%   |
| France       | 1         | 1.05%   |
| Denmark      | 1         | 1.05%   |
| Croatia      | 1         | 1.05%   |
| Colombia     | 1         | 1.05%   |
| Belarus      | 1         | 1.05%   |
| Bangladesh   | 1         | 1.05%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Moscow                      | 5         | 4.72%   |
| Brighton                    | 5         | 4.72%   |
| ЕЊta-ku                   | 3         | 2.83%   |
| St Petersburg               | 3         | 2.83%   |
| London                      | 3         | 2.83%   |
| Kyiv                        | 3         | 2.83%   |
| Zurich                      | 2         | 1.89%   |
| Vienna                      | 2         | 1.89%   |
| Seattle                     | 2         | 1.89%   |
| Rio de Janeiro              | 2         | 1.89%   |
| Rietberg                    | 2         | 1.89%   |
| Graz                        | 2         | 1.89%   |
| Fuchu                       | 2         | 1.89%   |
| Egham                       | 2         | 1.89%   |
| Chicago                     | 2         | 1.89%   |
| Berlin                      | 2         | 1.89%   |
| Zaporizhzhya                | 1         | 0.94%   |
| Wuhan                       | 1         | 0.94%   |
| Worthing                    | 1         | 0.94%   |
| Woodburn                    | 1         | 0.94%   |
| Wieliczka                   | 1         | 0.94%   |
| Washington                  | 1         | 0.94%   |
| Vila Real de Santo António | 1         | 0.94%   |
| Vancouver                   | 1         | 0.94%   |
| Trosa                       | 1         | 0.94%   |
| Thrissur                    | 1         | 0.94%   |
| Teaneck                     | 1         | 0.94%   |
| Stuttgart                   | 1         | 0.94%   |
| Sollentuna                  | 1         | 0.94%   |
| Slavonski Brod              | 1         | 0.94%   |
| Singapore                   | 1         | 0.94%   |
| Shanghai                    | 1         | 0.94%   |
| Setagaya-ku                 | 1         | 0.94%   |
| Santa Monica                | 1         | 0.94%   |
| San Francisco               | 1         | 0.94%   |
| Ruthin                      | 1         | 0.94%   |
| Rostov-on-Don               | 1         | 0.94%   |
| Riyadh                      | 1         | 0.94%   |
| Resana                      | 1         | 0.94%   |
| Poulsbo                     | 1         | 0.94%   |
| Pobiedziska                 | 1         | 0.94%   |
| Omaha                       | 1         | 0.94%   |
| Northeim                    | 1         | 0.94%   |
| New York                    | 1         | 0.94%   |
| Montclair                   | 1         | 0.94%   |
| Minsk                       | 1         | 0.94%   |
| Milan                       | 1         | 0.94%   |
| Medellín                   | 1         | 0.94%   |
| Manchester                  | 1         | 0.94%   |
| Maia                        | 1         | 0.94%   |
| Madrid                      | 1         | 0.94%   |
| Lubin                       | 1         | 0.94%   |
| Lima                        | 1         | 0.94%   |
| Lake Forest                 | 1         | 0.94%   |
| Kunitachi                   | 1         | 0.94%   |
| Kislovodsk                  | 1         | 0.94%   |
| Kingston                    | 1         | 0.94%   |
| Khabarovsk                  | 1         | 0.94%   |
| JoГЈo Pessoa              | 1         | 0.94%   |
| Jaboatao dos Guararapes     | 1         | 0.94%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 26        | 41     | 21.31%  |
| Samsung Electronics | 24        | 35     | 19.67%  |
| Toshiba             | 12        | 25     | 9.84%   |
| Crucial             | 8         | 17     | 6.56%   |
| Seagate             | 7         | 22     | 5.74%   |
| Kingston            | 7         | 10     | 5.74%   |
| HGST                | 7         | 22     | 5.74%   |
| A-DATA Technology   | 5         | 5      | 4.1%    |
| SK Hynix            | 4         | 4      | 3.28%   |
| Intel               | 4         | 5      | 3.28%   |
| Micron Technology   | 2         | 3      | 1.64%   |
| Apple               | 2         | 2      | 1.64%   |
| SSSTC               | 1         | 1      | 0.82%   |
| SPCC                | 1         | 1      | 0.82%   |
| Solid State Storage | 1         | 1      | 0.82%   |
| Silicon Motion      | 1         | 1      | 0.82%   |
| SanDisk             | 1         | 2      | 0.82%   |
| PNY                 | 1         | 1      | 0.82%   |
| Mushkin             | 1         | 1      | 0.82%   |
| LSI                 | 1         | 4      | 0.82%   |
| LITEON              | 1         | 1      | 0.82%   |
| KIOXIA              | 1         | 1      | 0.82%   |
| Hitachi             | 1         | 2      | 0.82%   |
| GOODRAM             | 1         | 1      | 0.82%   |
| Fujitsu             | 1         | 2      | 0.82%   |
| Apacer              | 1         | 1      | 0.82%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB                           | 5         | 3.68%   |
| HGST HTS725050A7E630 500GB                         | 4         | 2.94%   |
| WDC WDS100T3X0C-00SJG0 1TB                         | 3         | 2.21%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB               | 3         | 2.21%   |
| Toshiba MQ04ABF100 1TB                             | 3         | 2.21%   |
| Samsung HM251JX 250GB                              | 3         | 2.21%   |
| HGST HTS721010A9E630 1TB                           | 3         | 2.21%   |
| WDC WDS100T1X0E-00AFY0 1TB                         | 2         | 1.47%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB                 | 2         | 1.47%   |
| WDC PC SN730 NVMe 1024GB                           | 2         | 1.47%   |
| Samsung SSD 870 EVO 1TB                            | 2         | 1.47%   |
| Samsung SSD 850 EVO 250GB                          | 2         | 1.47%   |
| Samsung MZVLB512HBJQ-000L7 512GB                   | 2         | 1.47%   |
| Kingston SA2000M81000G 1TB                         | 2         | 1.47%   |
| WDC WDS500G1X0E-00AFY0 500GB                       | 1         | 0.74%   |
| WDC WDS250G2B0C-00PXH0 250GB                       | 1         | 0.74%   |
| WDC WDS100T2B0A-00SM50 1TB                         | 1         | 0.74%   |
| WDC WD60EFRX-68TGBN1 6TB                           | 1         | 0.74%   |
| WDC WD5002ABYS-18B1B0 500GB                        | 1         | 0.74%   |
| WDC WD40EZRZ-75GXCB0 4TB                           | 1         | 0.74%   |
| WDC WD30EFRX-68EUZN0 3TB                           | 1         | 0.74%   |
| WDC WD20EFRX-68AX9N0 2TB                           | 1         | 0.74%   |
| WDC WD120EFAX-68UNTN0 12TB                         | 1         | 0.74%   |
| WDC WD10SPZX-60Z10T0 1TB                           | 1         | 0.74%   |
| WDC WD10SPZX-21Z10T0 1TB                           | 1         | 0.74%   |
| WDC WD10JPVX-00JC3T0 1TB                           | 1         | 0.74%   |
| WDC WD10JMVW-11AJGS3 1TB                           | 1         | 0.74%   |
| WDC WD10EZEX-60WN4A0 1TB                           | 1         | 0.74%   |
| WDC WD10EZEX-00RKKA0 1TB                           | 1         | 0.74%   |
| WDC WD10EARX-00N0YB0 1TB                           | 1         | 0.74%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB               | 1         | 0.74%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB               | 1         | 0.74%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB               | 1         | 0.74%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB               | 1         | 0.74%   |
| Toshiba MQ01ABD100 1TB                             | 1         | 0.74%   |
| Toshiba MG09ACA18TE 18TB                           | 1         | 0.74%   |
| Toshiba MG06ACA800E 8TB                            | 1         | 0.74%   |
| Toshiba KXG6APNV2T04 2TB                           | 1         | 0.74%   |
| SSSTC CL1-3D256-Q11 NVMe 256GB                     | 1         | 0.74%   |
| SPCC M.2 PCIe SSD 1TB                              | 1         | 0.74%   |
| Solid State Storage CL1-3D128-Q11 NVMe SSSTC 128GB | 1         | 0.74%   |
| SK Hynix PC300 HFS512GD9MND-5510A 512GB            | 1         | 0.74%   |
| SK Hynix HFS128G39TND-N210A 128GB                  | 1         | 0.74%   |
| SK Hynix BC511 NVMe 256GB                          | 1         | 0.74%   |
| SK Hynix BC511 HFM256GDJTNI-82A0A 256GB            | 1         | 0.74%   |
| Silicon Motion NE-256 256GB                        | 1         | 0.74%   |
| Seagate ST5000LM000-2U8170 5TB                     | 1         | 0.74%   |
| Seagate ST5000LM000-2AN170 5TB                     | 1         | 0.74%   |
| Seagate ST4000DM000-1F2168 4TB                     | 1         | 0.74%   |
| Seagate ST3750640AS 752GB                          | 1         | 0.74%   |
| Seagate ST32000641AS 2TB                           | 1         | 0.74%   |
| Seagate ST3000DM007-1WY10G 3TB                     | 1         | 0.74%   |
| Seagate ST3000DM001-1ER166 3TB                     | 1         | 0.74%   |
| Seagate ST1000LM035-1RK172 1TB                     | 1         | 0.74%   |
| SanDisk SDSSDH3500G 500GB                          | 1         | 0.74%   |
| Samsung SSD 970 EVO Plus 1TB                       | 1         | 0.74%   |
| Samsung SSD 970 EVO 1TB                            | 1         | 0.74%   |
| Samsung SSD 870 QVO 1TB                            | 1         | 0.74%   |
| Samsung SSD 860 EVO M.2 250GB                      | 1         | 0.74%   |
| Samsung SSD 860 EVO 500GB                          | 1         | 0.74%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 11        | 24     | 26.83%  |
| WDC                 | 9         | 15     | 21.95%  |
| Seagate             | 7         | 22     | 17.07%  |
| HGST                | 7         | 22     | 17.07%  |
| Samsung Electronics | 4         | 7      | 9.76%   |
| LSI                 | 1         | 4      | 2.44%   |
| Hitachi             | 1         | 2      | 2.44%   |
| Fujitsu             | 1         | 2      | 2.44%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 14     | 29.03%  |
| Crucial             | 5         | 10     | 16.13%  |
| Kingston            | 3         | 5      | 9.68%   |
| A-DATA Technology   | 3         | 3      | 9.68%   |
| Intel               | 2         | 3      | 6.45%   |
| Apple               | 2         | 2      | 6.45%   |
| WDC                 | 1         | 2      | 3.23%   |
| SK Hynix            | 1         | 1      | 3.23%   |
| SanDisk             | 1         | 2      | 3.23%   |
| Micron Technology   | 1         | 1      | 3.23%   |
| LITEON              | 1         | 1      | 3.23%   |
| GOODRAM             | 1         | 1      | 3.23%   |
| Apacer              | 1         | 1      | 3.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 49        | 67     | 45.37%  |
| SSD  | 30        | 46     | 27.78%  |
| HDD  | 29        | 98     | 26.85%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 49        | 67     | 50%     |
| SATA | 49        | 144    | 50%     |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 31        | 67     | 46.27%  |
| 0.51-1.0   | 20        | 35     | 29.85%  |
| 1.01-2.0   | 4         | 5      | 5.97%   |
| 4.01-10.0  | 4         | 23     | 5.97%   |
| 3.01-4.0   | 3         | 4      | 4.48%   |
| 2.01-3.0   | 2         | 3      | 2.99%   |
| 10.01-20.0 | 2         | 3      | 2.99%   |
| 20.01-50.0 | 1         | 4      | 1.49%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 24        | 24%     |
| 101-250        | 24        | 24%     |
| 501-1000       | 17        | 17%     |
| 1-20           | 11        | 11%     |
| 21-50          | 8         | 8%      |
| 51-100         | 7         | 7%      |
| 1001-2000      | 4         | 4%      |
| More than 3000 | 3         | 3%      |
| 2001-3000      | 2         | 2%      |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 62        | 62%     |
| 21-50          | 24        | 24%     |
| 101-250        | 7         | 7%      |
| 51-100         | 2         | 2%      |
| More than 3000 | 1         | 1%      |
| 251-500        | 1         | 1%      |
| 1001-2000      | 1         | 1%      |
| 501-1000       | 1         | 1%      |
| 0              | 1         | 1%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


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
| HGST HTS721010A9E630 1TB            | 1         | 8      | 7.14%   |
| Fujitsu MHS2040AT D 40GB            | 1         | 2      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 4         | 17     | 30.77%  |
| WDC                 | 3         | 5      | 23.08%  |
| Samsung Electronics | 3         | 5      | 23.08%  |
| Kingston            | 1         | 1      | 7.69%   |
| Hitachi             | 1         | 2      | 7.69%   |
| Fujitsu             | 1         | 2      | 7.69%   |

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
| HDD  | 9         | 27     | 81.82%  |
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

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 80        | 172    | 84.21%  |
| Malfunc  | 11        | 32     | 11.58%  |
| Detected | 4         | 7      | 4.21%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 37        | 30.08%  |
| AMD                            | 26        | 21.14%  |
| Sandisk                        | 18        | 14.63%  |
| Samsung Electronics            | 15        | 12.2%   |
| Silicon Motion                 | 4         | 3.25%   |
| Kingston Technology Company    | 4         | 3.25%   |
| SK Hynix                       | 3         | 2.44%   |
| Micron/Crucial Technology      | 3         | 2.44%   |
| Solid State Storage Technology | 2         | 1.63%   |
| Micron Technology              | 2         | 1.63%   |
| ASMedia Technology             | 2         | 1.63%   |
| ADATA Technology               | 2         | 1.63%   |
| Toshiba                        | 1         | 0.81%   |
| Phison Electronics             | 1         | 0.81%   |
| Marvell Technology Group       | 1         | 0.81%   |
| KIOXIA                         | 1         | 0.81%   |
| Broadcom / LSI                 | 1         | 0.81%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 19        | 14.07%  |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 11        | 8.15%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 10        | 7.41%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 4.44%   |
| AMD 400 Series Chipset SATA Controller                                         | 6         | 4.44%   |
| Unknown                                                                        | 6         | 4.44%   |
| Intel Comet Lake SATA AHCI Controller                                          | 5         | 3.7%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 4         | 2.96%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 4         | 2.96%   |
| AMD 500 Series Chipset SATA Controller                                         | 4         | 2.96%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                     | 3         | 2.22%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 3         | 2.22%   |
| SK Hynix BC511                                                                 | 2         | 1.48%   |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 2         | 1.48%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 1.48%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 1.48%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 1.48%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2         | 1.48%   |
| Kingston Company A2000 NVMe SSD                                                | 2         | 1.48%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 1.48%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.48%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 2         | 1.48%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 2         | 1.48%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 1.48%   |
| Toshiba XG6 NVMe SSD Controller                                                | 1         | 0.74%   |
| SK Hynix PC300 NVMe Solid State Drive 512GB                                    | 1         | 0.74%   |
| Sandisk PC SN530                                                               | 1         | 0.74%   |
| Samsung SM951 AHCI                                                             | 1         | 0.74%   |
| Phison E12 NVMe Controller                                                     | 1         | 0.74%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 1         | 0.74%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                          | 1         | 0.74%   |
| KIOXIA unknown                                                                 | 1         | 0.74%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 1         | 0.74%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 0.74%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1         | 0.74%   |
| Intel SSD 660P Series                                                          | 1         | 0.74%   |
| Intel NVMe Optane Memory Series                                                | 1         | 0.74%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 1         | 0.74%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 0.74%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 0.74%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1         | 0.74%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 0.74%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 1         | 0.74%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 1         | 0.74%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 0.74%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 1         | 0.74%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 1         | 0.74%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]    | 1         | 0.74%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]    | 1         | 0.74%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                 | 1         | 0.74%   |
| ASMedia ASM1166 Serial ATA Controller                                          | 1         | 0.74%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 1         | 0.74%   |
| AMD X399 Series Chipset SATA Controller                                        | 1         | 0.74%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 1         | 0.74%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 57        | 47.9%   |
| NVMe | 56        | 47.06%  |
| IDE  | 4         | 3.36%   |
| RAID | 2         | 1.68%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 47        | 48.96%  |
| AMD     | 33        | 34.38%  |
| ARM     | 8         | 8.33%   |
| Unknown | 8         | 8.33%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
|                                                 | 8         | 8.33%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 6         | 6.25%   |
| Intel Core i7-3520M CPU @ 2.90GHz               | 4         | 4.17%   |
| ARM Cortex-A72 r0p3                             | 4         | 4.17%   |
| AMD Ryzen 5 5600G with Radeon Graphics          | 4         | 4.17%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 3         | 3.13%   |
| Intel Core i5-10210U CPU @ 1.60GHz              | 3         | 3.13%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 2         | 2.08%   |
| Intel Core i7-7600U CPU @ 2.80GHz               | 2         | 2.08%   |
| Intel Core i5-10500T CPU @ 2.30GHz              | 2         | 2.08%   |
| Intel Core i5-10300H CPU @ 2.50GHz              | 2         | 2.08%   |
| ARM Cortex-A72 r0p2                             | 2         | 2.08%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 2         | 2.08%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 2         | 2.08%   |
| AMD Ryzen 7 4700U with Radeon Graphics          | 2         | 2.08%   |
| AMD Ryzen 5 PRO 3500U w/ Radeon Vega Mobile Gfx | 2         | 2.08%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 2         | 2.08%   |
| Intel Xeon W-10885M CPU @ 2.40GHz               | 1         | 1.04%   |
| Intel Xeon E-2334 CPU @ 3.40GHz                 | 1         | 1.04%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz             | 1         | 1.04%   |
| Intel Pentium M processor 1000MHz               | 1         | 1.04%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 1         | 1.04%   |
| Intel Core i7-8700 CPU @ 3.20GHz                | 1         | 1.04%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 1.04%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 1.04%   |
| Intel Core i7-5600U CPU @ 2.60GHz               | 1         | 1.04%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz              | 1         | 1.04%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz              | 1         | 1.04%   |
| Intel Core i7-3770 CPU @ 3.40GHz                | 1         | 1.04%   |
| Intel Core i7-3687U CPU @ 2.10GHz               | 1         | 1.04%   |
| Intel Core i7-3615QM CPU @ 2.30GHz              | 1         | 1.04%   |
| Intel Core i7-10870H CPU @ 2.20GHz              | 1         | 1.04%   |
| Intel Core i7-10700 CPU @ 2.90GHz               | 1         | 1.04%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz              | 1         | 1.04%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 1         | 1.04%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 1         | 1.04%   |
| Intel Core i5-5257U CPU @ 2.70GHz               | 1         | 1.04%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 1         | 1.04%   |
| Intel Core i5-10400 CPU @ 2.90GHz               | 1         | 1.04%   |
| Intel Atom CPU E3827 @ 1.74GHz                  | 1         | 1.04%   |
| ARM Cortex-A53 r0p4                             | 1         | 1.04%   |
| ARM ARM1176 r0p7 (ECO: 0x00000000)              | 1         | 1.04%   |
| AMD Ryzen Threadripper 1950X 16-Core Processor  | 1         | 1.04%   |
| AMD Ryzen Embedded V1202B with Radeon Vega Gfx  | 1         | 1.04%   |
| AMD Ryzen 9 5950X 16-Core Processor             | 1         | 1.04%   |
| AMD Ryzen 9 5900X 12-Core Processor             | 1         | 1.04%   |
| AMD Ryzen 9 3950X 16-Core Processor             | 1         | 1.04%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics      | 1         | 1.04%   |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx | 1         | 1.04%   |
| AMD Ryzen 7 5800X 8-Core Processor              | 1         | 1.04%   |
| AMD Ryzen 7 5700U with Radeon Graphics          | 1         | 1.04%   |
| AMD Ryzen 7 4800U with Radeon Graphics          | 1         | 1.04%   |
| AMD Ryzen 7 2700X Eight-Core Processor          | 1         | 1.04%   |
| AMD Ryzen 5 5500U with Radeon Graphics          | 1         | 1.04%   |
| AMD Ryzen 5 4600H with Radeon Graphics          | 1         | 1.04%   |
| AMD Ryzen 5 2600X Six-Core Processor            | 1         | 1.04%   |
| AMD Ryzen 5 2600 Six-Core Processor             | 1         | 1.04%   |
| AMD Ryzen 5 2400GE with Radeon Vega Graphics    | 1         | 1.04%   |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx   | 1         | 1.04%   |
| AMD FX-8320E Eight-Core Processor               | 1         | 1.04%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 25        | 26.04%  |
| Other                  | 15        | 15.63%  |
| Intel Core i5          | 11        | 11.46%  |
| AMD Ryzen 5            | 11        | 11.46%  |
| AMD Ryzen 7            | 8         | 8.33%   |
| ARM Cortex             | 7         | 7.29%   |
| AMD Ryzen 9            | 5         | 5.21%   |
| Intel Xeon             | 3         | 3.13%   |
| AMD Ryzen 7 PRO        | 2         | 2.08%   |
| AMD Ryzen 5 PRO        | 2         | 2.08%   |
| Intel Pentium M        | 1         | 1.04%   |
| Intel Atom             | 1         | 1.04%   |
| AMD Ryzen Threadripper | 1         | 1.04%   |
| AMD Ryzen Embedded     | 1         | 1.04%   |
| AMD Ryzen 3            | 1         | 1.04%   |
| AMD FX                 | 1         | 1.04%   |
| AMD E                  | 1         | 1.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 21        | 22.11%  |
| Unknown | 15        | 15.79%  |
| 2       | 14        | 14.74%  |
| 8       | 12        | 12.63%  |
| 6       | 10        | 10.53%  |
| 16      | 8         | 8.42%   |
| 12      | 8         | 8.42%   |
| 32      | 3         | 3.16%   |
| 24      | 3         | 3.16%   |
| 1       | 1         | 1.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 84        | 87.5%   |
| Unknown | 11        | 11.46%  |
| 2       | 1         | 1.04%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 45        | 47.37%  |
| 1       | 34        | 35.79%  |
| Unknown | 16        | 16.84%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 18        | 18.95%  |
| KabyLake   | 12        | 12.63%  |
| CometLake  | 11        | 11.58%  |
| Zen 2      | 10        | 10.53%  |
| Zen+       | 8         | 8.42%   |
| IvyBridge  | 8         | 8.42%   |
| Zen 3      | 7         | 7.37%   |
| TigerLake  | 6         | 6.32%   |
| Zen        | 4         | 4.21%   |
| Broadwell  | 3         | 3.16%   |
| Haswell    | 2         | 2.11%   |
| Skylake    | 1         | 1.05%   |
| Silvermont | 1         | 1.05%   |
| Piledriver | 1         | 1.05%   |
| P6         | 1         | 1.05%   |
| IceLake    | 1         | 1.05%   |
| Bobcat     | 1         | 1.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 40        | 39.6%   |
| AMD                        | 30        | 29.7%   |
| Nvidia                     | 28        | 27.72%  |
| Matrox Electronics Systems | 2         | 1.98%   |
| ASPEED Technology          | 1         | 0.99%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                               | 7         | 6.8%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                | 6         | 5.83%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]     | 5         | 4.85%   |
| Intel CometLake-U GT2 [UHD Graphics]                                     | 4         | 3.88%   |
| Intel CometLake-H GT2 [UHD Graphics]                                     | 4         | 3.88%   |
| Intel 3rd Gen Core processor Graphics Controller                         | 4         | 3.88%   |
| AMD Cezanne                                                              | 4         | 3.88%   |
| Nvidia TU117M                                                            | 3         | 2.91%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                 | 3         | 2.91%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                | 3         | 2.91%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                 | 3         | 2.91%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]         | 3         | 2.91%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                               | 2         | 1.94%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                               | 2         | 1.94%   |
| Nvidia GP108M [GeForce MX230]                                            | 2         | 1.94%   |
| Nvidia GK208B [GeForce GT 710]                                           | 2         | 1.94%   |
| Intel HD Graphics 620                                                    | 2         | 1.94%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller              | 2         | 1.94%   |
| AMD Lucienne                                                             | 2         | 1.94%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                  | 1         | 0.97%   |
| Nvidia TU104GLM [Quadro RTX 5000 Mobile / Max-Q]                         | 1         | 0.97%   |
| Nvidia GT218 [GeForce 210]                                               | 1         | 0.97%   |
| Nvidia GP108 [GeForce GT 1030]                                           | 1         | 0.97%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                               | 1         | 0.97%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                  | 1         | 0.97%   |
| Nvidia GP107GL [Quadro P620]                                             | 1         | 0.97%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                       | 1         | 0.97%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                      | 1         | 0.97%   |
| Nvidia GM206 [GeForce GTX 960]                                           | 1         | 0.97%   |
| Nvidia GM108M [GeForce MX130]                                            | 1         | 0.97%   |
| Nvidia GM108M [GeForce 940MX]                                            | 1         | 0.97%   |
| Nvidia GM107M [GeForce GTX 860M]                                         | 1         | 0.97%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                        | 1         | 0.97%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                              | 1         | 0.97%   |
| Nvidia GK107GLM [Quadro K1100M]                                          | 1         | 0.97%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                          | 1         | 0.97%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)        | 1         | 0.97%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller | 1         | 0.97%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                               | 1         | 0.97%   |
| Intel Skylake GT2 [HD Graphics 520]                                      | 1         | 0.97%   |
| Intel JasperLake [UHD Graphics]                                          | 1         | 0.97%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                   | 1         | 0.97%   |
| Intel Iris Plus Graphics G7                                              | 1         | 0.97%   |
| Intel Iris Graphics 6100                                                 | 1         | 0.97%   |
| Intel HD Graphics 630                                                    | 1         | 0.97%   |
| Intel HD Graphics 5500                                                   | 1         | 0.97%   |
| Intel Comet Lake-H WS GT2 Integrated UHD Graphics Controller             | 1         | 0.97%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                | 1         | 0.97%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display             | 1         | 0.97%   |
| Intel 82852/855GM Integrated Graphics Device                             | 1         | 0.97%   |
| ASPEED Technology ASPEED Graphics Family                                 | 1         | 0.97%   |
| AMD Wrestler [Radeon HD 6320]                                            | 1         | 0.97%   |
| AMD RV630 XT [Radeon HD 2600 XT]                                         | 1         | 0.97%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]    | 1         | 0.97%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                           | 1         | 0.97%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                  | 1         | 0.97%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                  | 1         | 0.97%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                       | 1         | 0.97%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]      | 1         | 0.97%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 25        | 26.04%  |
| 1 x Intel      | 22        | 22.92%  |
| Intel + Nvidia | 16        | 16.67%  |
| Other          | 14        | 14.58%  |
| 1 x Nvidia     | 12        | 12.5%   |
| 2 x AMD        | 2         | 2.08%   |
| 1 x Matrox     | 2         | 2.08%   |
| Intel + AMD    | 1         | 1.04%   |
| 1 x ASPEED     | 1         | 1.04%   |
| AMD + Nvidia   | 1         | 1.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 62        | 65.26%  |
| Proprietary | 19        | 20%     |
| Unknown     | 14        | 14.74%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 70        | 72.16%  |
| 1.01-2.0   | 9         | 9.28%   |
| 0.51-1.0   | 6         | 6.19%   |
| 0.01-0.5   | 5         | 5.15%   |
| 3.01-4.0   | 4         | 4.12%   |
| 7.01-8.0   | 1         | 1.03%   |
| 5.01-6.0   | 1         | 1.03%   |
| 2.01-3.0   | 1         | 1.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| LG Display          | 10        | 13.51%  |
| BOE                 | 10        | 13.51%  |
| AU Optronics        | 9         | 12.16%  |
| Philips             | 4         | 5.41%   |
| Hewlett-Packard     | 4         | 5.41%   |
| Goldstar            | 4         | 5.41%   |
| Dell                | 4         | 5.41%   |
| Chimei Innolux      | 4         | 5.41%   |
| Samsung Electronics | 3         | 4.05%   |
| RTK                 | 2         | 2.7%    |
| LG Electronics      | 2         | 2.7%    |
| Lenovo              | 2         | 2.7%    |
| Apple               | 2         | 2.7%    |
| ViewSonic           | 1         | 1.35%   |
| Sony                | 1         | 1.35%   |
| Sharp               | 1         | 1.35%   |
| SDC                 | 1         | 1.35%   |
| PANDA               | 1         | 1.35%   |
| LGD                 | 1         | 1.35%   |
| InfoVision          | 1         | 1.35%   |
| Iiyama              | 1         | 1.35%   |
| HJW                 | 1         | 1.35%   |
| Eizo                | 1         | 1.35%   |
| CSO                 | 1         | 1.35%   |
| BenQ                | 1         | 1.35%   |
| AOC                 | 1         | 1.35%   |
| Unknown             | 1         | 1.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0258 1600x900 350x190mm 15.7-inch            | 3         | 3.95%   |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                  | 3         | 3.95%   |
| RTK WCS Display RTK1A1B 1920x1080 344x195mm 15.6-inch                  | 2         | 2.63%   |
| Philips LCD Monitor PHL08C3 1920x1080 600x340mm 27.2-inch              | 2         | 2.63%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch           | 2         | 2.63%   |
| ViewSonic LCD Monitor VSCD22B 1920x1080 520x290mm 23.4-inch            | 1         | 1.32%   |
| Sony TV SNY4B03 1920x1080 930x520mm 41.9-inch                          | 1         | 1.32%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 380x210mm 17.1-inch                | 1         | 1.32%   |
| SDC LCD Monitor 3520x1080                                              | 1         | 1.32%   |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                       | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SDC3754 1600x900 380x210mm 17.1-inch   | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1020x570mm 46.0-inch | 1         | 1.32%   |
| Philips PHL 273V7 PHLC156 1920x1080 600x340mm 27.2-inch                | 1         | 1.32%   |
| Philips LCD Monitor 271P4 3520x1080                                    | 1         | 1.32%   |
| Philips LCD Monitor 271P4                                              | 1         | 1.32%   |
| PANDA LCD Monitor NCP004F 1920x1080 310x170mm 13.9-inch                | 1         | 1.32%   |
| LGD LCD Monitor 1920x1080                                              | 1         | 1.32%   |
| LG Electronics LCD Monitor LX20D 1600x1200                             | 1         | 1.32%   |
| LG Electronics LCD Monitor LG Ultra HD 11520x2160                      | 1         | 1.32%   |
| LG Electronics LCD Monitor LG Ultra HD                                 | 1         | 1.32%   |
| LG Display LCD Monitor LGD062E 1920x1080 340x190mm 15.3-inch           | 1         | 1.32%   |
| LG Display LCD Monitor LGD060A 1920x1080 290x170mm 13.2-inch           | 1         | 1.32%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch           | 1         | 1.32%   |
| LG Display LCD Monitor LGD05F1 1920x1080 310x170mm 13.9-inch           | 1         | 1.32%   |
| LG Display LCD Monitor LGD033E 1366x768 310x170mm 13.9-inch            | 1         | 1.32%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                  | 1         | 1.32%   |
| Lenovo LEN P44w-10 LEN61D5 3840x1200 1050x330mm 43.3-inch              | 1         | 1.32%   |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch           | 1         | 1.32%   |
| Iiyama PL2474H IVM6146 1920x1080 520x290mm 23.4-inch                   | 1         | 1.32%   |
| HJW HDMI TO USB HJW0001 1920x1080 700x390mm 31.5-inch                  | 1         | 1.32%   |
| Hewlett-Packard LCD Monitor LA2306 3520x1080                           | 1         | 1.32%   |
| Hewlett-Packard LA2306 HWP2949 1920x1080 510x290mm 23.1-inch           | 1         | 1.32%   |
| Hewlett-Packard E242 HWP326E 1920x1200 520x320mm 24.0-inch             | 1         | 1.32%   |
| Hewlett-Packard E233 HPN345F 1920x1080 510x290mm 23.1-inch             | 1         | 1.32%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch             | 1         | 1.32%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch             | 1         | 1.32%   |
| Goldstar 27GK750F GSM770F 1920x1080 600x340mm 27.2-inch                | 1         | 1.32%   |
| Goldstar 23EA53 GSM59A8 1920x1080 510x290mm 23.1-inch                  | 1         | 1.32%   |
| Eizo FX2431 ENC2036 1920x1200 520x330mm 24.2-inch                      | 1         | 1.32%   |
| Dell U2718Q DELA0EC 3840x2160 610x350mm 27.7-inch                      | 1         | 1.32%   |
| Dell U2518D DEL413C 2560x1440 550x310mm 24.9-inch                      | 1         | 1.32%   |
| Dell LCD Monitor U2715H 2560x1440                                      | 1         | 1.32%   |
| Dell LCD Monitor DEL9408 1920x1080 520x290mm 23.4-inch                 | 1         | 1.32%   |
| CSO LCD Monitor CSO1500 3840x2160 340x190mm 15.3-inch                  | 1         | 1.32%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 280x180mm 13.1-inch       | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 340x190mm 15.3-inch       | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN1484 1600x900 310x170mm 13.9-inch        | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN13A2 1920x1080 290x170mm 13.2-inch       | 1         | 1.32%   |
| BOE LCD Monitor BOE0982 3840x2160 310x170mm 13.9-inch                  | 1         | 1.32%   |
| BOE LCD Monitor BOE08D7 1920x1080 310x170mm 13.9-inch                  | 1         | 1.32%   |
| BOE LCD Monitor BOE084D 1920x1080 340x190mm 15.3-inch                  | 1         | 1.32%   |
| BOE LCD Monitor BOE07F1 1920x1080 340x190mm 15.3-inch                  | 1         | 1.32%   |
| BOE LCD Monitor BOE0792 1920x1080 340x190mm 15.3-inch                  | 1         | 1.32%   |
| BOE LCD Monitor BOE075A 1366x768 310x170mm 13.9-inch                   | 1         | 1.32%   |
| BOE LCD Monitor BOE0747 1920x1080 340x190mm 15.3-inch                  | 1         | 1.32%   |
| BenQ GW2280 BNQ78E8 1920x1080 480x270mm 21.7-inch                      | 1         | 1.32%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 340x190mm 15.3-inch         | 1         | 1.32%   |
| AU Optronics LCD Monitor AUOD0ED 1920x1080 340x190mm 15.3-inch         | 1         | 1.32%   |
| AU Optronics LCD Monitor AUO5A2D 1920x1080 290x170mm 13.2-inch         | 1         | 1.32%   |
| AU Optronics LCD Monitor AUO5699 1920x1080 340x190mm 15.3-inch         | 1         | 1.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 41        | 56.16%  |
| 3840x2160 (4K)    | 6         | 8.22%   |
| 1600x900 (HD+)    | 6         | 8.22%   |
| 2560x1440 (QHD)   | 3         | 4.11%   |
| 2256x1504         | 3         | 4.11%   |
| 1920x1200 (WUXGA) | 3         | 4.11%   |
| 2560x1600         | 2         | 2.74%   |
| 1366x768 (WXGA)   | 2         | 2.74%   |
| Unknown           | 2         | 2.74%   |
| 3840x1200         | 1         | 1.37%   |
| 3520x1080         | 1         | 1.37%   |
| 2160x1440         | 1         | 1.37%   |
| 1600x1200         | 1         | 1.37%   |
| 11520x2160        | 1         | 1.37%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 21        | 29.17%  |
| 15      | 15        | 20.83%  |
| 27      | 7         | 9.72%   |
| Unknown | 7         | 9.72%   |
| 23      | 6         | 8.33%   |
| 24      | 4         | 5.56%   |
| 17      | 3         | 4.17%   |
| 12      | 2         | 2.78%   |
| 46      | 1         | 1.39%   |
| 43      | 1         | 1.39%   |
| 41      | 1         | 1.39%   |
| 32      | 1         | 1.39%   |
| 31      | 1         | 1.39%   |
| 22      | 1         | 1.39%   |
| 21      | 1         | 1.39%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 27        | 38.03%  |
| 501-600     | 15        | 21.13%  |
| 201-300     | 11        | 15.49%  |
| Unknown     | 7         | 9.86%   |
| 351-400     | 3         | 4.23%   |
| 601-700     | 2         | 2.82%   |
| 401-500     | 2         | 2.82%   |
| 1001-1500   | 2         | 2.82%   |
| 701-800     | 1         | 1.41%   |
| 901-1000    | 1         | 1.41%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 49        | 75.38%  |
| 16/10   | 6         | 9.23%   |
| Unknown | 6         | 9.23%   |
| 3/2     | 3         | 4.62%   |
| 3.18    | 1         | 1.54%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 17        | 23.61%  |
| 91-100         | 10        | 13.89%  |
| 201-250        | 9         | 12.5%   |
| 301-350        | 7         | 9.72%   |
| Unknown        | 7         | 9.72%   |
| 101-110        | 5         | 6.94%   |
| 71-80          | 4         | 5.56%   |
| 251-300        | 3         | 4.17%   |
| 121-130        | 3         | 4.17%   |
| 501-1000       | 3         | 4.17%   |
| 61-70          | 2         | 2.78%   |
| 351-500        | 2         | 2.78%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 23        | 32.86%  |
| 51-100        | 17        | 24.29%  |
| 161-240       | 13        | 18.57%  |
| 101-120       | 7         | 10%     |
| Unknown       | 7         | 10%     |
| More than 240 | 2         | 2.86%   |
| 1-50          | 1         | 1.43%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 51        | 52.58%  |
| 0     | 36        | 37.11%  |
| 2     | 9         | 9.28%   |
| 3     | 1         | 1.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 65        | 45.77%  |
| Realtek Semiconductor           | 42        | 29.58%  |
| TP-Link                         | 5         | 3.52%   |
| Broadcom                        | 5         | 3.52%   |
| Ralink Technology               | 4         | 2.82%   |
| Qualcomm Atheros                | 4         | 2.82%   |
| Hewlett-Packard                 | 4         | 2.82%   |
| Edimax Technology               | 2         | 1.41%   |
| D-Link System                   | 2         | 1.41%   |
| Qualcomm Atheros Communications | 1         | 0.7%    |
| Mellanox Technologies           | 1         | 0.7%    |
| Lenovo                          | 1         | 0.7%    |
| Google                          | 1         | 0.7%    |
| Emulex                          | 1         | 0.7%    |
| BUFFALO                         | 1         | 0.7%    |
| ASUSTek Computer                | 1         | 0.7%    |
| Arduino SA                      | 1         | 0.7%    |
| Aquantia                        | 1         | 0.7%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 35        | 19.89%  |
| Intel Wi-Fi 6 AX200                                                           | 10        | 5.68%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 6         | 3.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6         | 3.41%   |
| Intel Wireless-AC 9260                                                        | 5         | 2.84%   |
| Intel Wireless 8265 / 8275                                                    | 5         | 2.84%   |
| Intel I211 Gigabit Network Connection                                         | 5         | 2.84%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 5         | 2.84%   |
| Intel Wi-Fi 6 AX201                                                           | 4         | 2.27%   |
| Intel I210 Gigabit Network Connection                                         | 4         | 2.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 4         | 2.27%   |
| HP hs2350 HSPA+ Mobile Broadband Module Network Adapter                       | 4         | 2.27%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 3         | 1.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 3         | 1.7%    |
| Realtek RTL8125 2.5GbE Controller                                             | 3         | 1.7%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 3         | 1.7%    |
| Intel Ethernet Controller I225-V                                              | 3         | 1.7%    |
| Intel 82574L Gigabit Network Connection                                       | 3         | 1.7%    |
| Ralink MT7601U Wireless Adapter                                               | 2         | 1.14%   |
| Intel Wireless 7265                                                           | 2         | 1.14%   |
| Intel Wireless 7260                                                           | 2         | 1.14%   |
| Intel Ethernet Connection (4) I219-LM                                         | 2         | 1.14%   |
| Intel Ethernet Connection (11) I219-LM                                        | 2         | 1.14%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2         | 1.14%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]    | 2         | 1.14%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1         | 0.57%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]           | 1         | 0.57%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                      | 1         | 0.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.57%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                        | 1         | 0.57%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1         | 0.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 0.57%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 0.57%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1         | 0.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1         | 0.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 1         | 0.57%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 1         | 0.57%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1         | 0.57%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1         | 0.57%   |
| Mellanox MT27710 Family [ConnectX-4 Lx]                                       | 1         | 0.57%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                              | 1         | 0.57%   |
| Intel Wireless 8260                                                           | 1         | 0.57%   |
| Intel Wi-Fi 6 AX201 160MHz                                                    | 1         | 0.57%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 0.57%   |
| Intel I350 Gigabit Network Connection                                         | 1         | 0.57%   |
| Intel Ethernet Controller I225-LM                                             | 1         | 0.57%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 1         | 0.57%   |
| Intel Ethernet Connection I219-LM                                             | 1         | 0.57%   |
| Intel Ethernet Connection I217-LM                                             | 1         | 0.57%   |
| Intel Ethernet Connection (7) I219-V                                          | 1         | 0.57%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1         | 0.57%   |
| Intel Ethernet Connection (5) I219-V                                          | 1         | 0.57%   |
| Intel Ethernet Connection (3) I218-LM                                         | 1         | 0.57%   |
| Intel Ethernet Connection (14) I219-LM                                        | 1         | 0.57%   |
| Intel Ethernet Connection (13) I219-V                                         | 1         | 0.57%   |
| Intel Ethernet Connection (11) I219-V                                         | 1         | 0.57%   |
| Intel Ethernet Connection (10) I219-V                                         | 1         | 0.57%   |
| Intel Centrino Advanced-N 6235                                                | 1         | 0.57%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller             | 1         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 52        | 63.41%  |
| Realtek Semiconductor           | 7         | 8.54%   |
| TP-Link                         | 5         | 6.1%    |
| Ralink Technology               | 4         | 4.88%   |
| Broadcom                        | 4         | 4.88%   |
| Qualcomm Atheros                | 3         | 3.66%   |
| Edimax Technology               | 2         | 2.44%   |
| D-Link System                   | 2         | 2.44%   |
| Qualcomm Atheros Communications | 1         | 1.22%   |
| BUFFALO                         | 1         | 1.22%   |
| ASUSTek Computer                | 1         | 1.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                           | 10        | 12.2%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 6         | 7.32%   |
| Intel Wireless-AC 9260                                                        | 5         | 6.1%    |
| Intel Wireless 8265 / 8275                                                    | 5         | 6.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 5         | 6.1%    |
| Intel Wi-Fi 6 AX201                                                           | 4         | 4.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 4         | 4.88%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 3         | 3.66%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 3         | 3.66%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 3         | 3.66%   |
| Ralink MT7601U Wireless Adapter                                               | 2         | 2.44%   |
| Intel Wireless 7265                                                           | 2         | 2.44%   |
| Intel Wireless 7260                                                           | 2         | 2.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2         | 2.44%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]    | 2         | 2.44%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1         | 1.22%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]           | 1         | 1.22%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                      | 1         | 1.22%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.22%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                        | 1         | 1.22%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 1.22%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1         | 1.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1         | 1.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 1         | 1.22%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 1         | 1.22%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1         | 1.22%   |
| Intel Wireless 8260                                                           | 1         | 1.22%   |
| Intel Wi-Fi 6 AX201 160MHz                                                    | 1         | 1.22%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 1.22%   |
| Intel Centrino Advanced-N 6235                                                | 1         | 1.22%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                | 1         | 1.22%   |
| Edimax EW-7711MAC 802.11ac Wireless Adapter                                   | 1         | 1.22%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]                      | 1         | 1.22%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                   | 1         | 1.22%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 1         | 1.22%   |
| Broadcom BCM4331 802.11a/b/g/n                                                | 1         | 1.22%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 1         | 1.22%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                                           | 1         | 1.22%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 39        | 46.99%  |
| Intel                 | 37        | 44.58%  |
| Broadcom              | 2         | 2.41%   |
| Qualcomm Atheros      | 1         | 1.2%    |
| Lenovo                | 1         | 1.2%    |
| Google                | 1         | 1.2%    |
| Emulex                | 1         | 1.2%    |
| Aquantia              | 1         | 1.2%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 35        | 40.23%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6         | 6.9%    |
| Intel I211 Gigabit Network Connection                                         | 5         | 5.75%   |
| Intel I210 Gigabit Network Connection                                         | 4         | 4.6%    |
| Realtek RTL8125 2.5GbE Controller                                             | 3         | 3.45%   |
| Intel Ethernet Controller I225-V                                              | 3         | 3.45%   |
| Intel 82574L Gigabit Network Connection                                       | 3         | 3.45%   |
| Intel Ethernet Connection (4) I219-LM                                         | 2         | 2.3%    |
| Intel Ethernet Connection (11) I219-LM                                        | 2         | 2.3%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1         | 1.15%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 1.15%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1         | 1.15%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                              | 1         | 1.15%   |
| Intel I350 Gigabit Network Connection                                         | 1         | 1.15%   |
| Intel Ethernet Controller I225-LM                                             | 1         | 1.15%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 1         | 1.15%   |
| Intel Ethernet Connection I219-LM                                             | 1         | 1.15%   |
| Intel Ethernet Connection I217-LM                                             | 1         | 1.15%   |
| Intel Ethernet Connection (7) I219-V                                          | 1         | 1.15%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1         | 1.15%   |
| Intel Ethernet Connection (5) I219-V                                          | 1         | 1.15%   |
| Intel Ethernet Connection (3) I218-LM                                         | 1         | 1.15%   |
| Intel Ethernet Connection (14) I219-LM                                        | 1         | 1.15%   |
| Intel Ethernet Connection (13) I219-V                                         | 1         | 1.15%   |
| Intel Ethernet Connection (11) I219-V                                         | 1         | 1.15%   |
| Intel Ethernet Connection (10) I219-V                                         | 1         | 1.15%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 1.15%   |
| Google Nexus/Pixel Device (charging + debug)                                  | 1         | 1.15%   |
| Emulex OneConnect 10Gb NIC (be3)                                              | 1         | 1.15%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                             | 1         | 1.15%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 1         | 1.15%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 1         | 1.15%   |
| Unknown                                                                       | 1         | 1.15%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 75        | 50.34%  |
| WiFi     | 67        | 44.97%  |
| Modem    | 6         | 4.03%   |
| Unknown  | 1         | 0.67%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 66        | 61.68%  |
| WiFi     | 38        | 35.51%  |
| Modem    | 3         | 2.8%    |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 54        | 56.84%  |
| 1     | 19        | 20%     |
| 0     | 13        | 13.68%  |
| 3     | 6         | 6.32%   |
| 4     | 2         | 2.11%   |
| 7     | 1         | 1.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 79        | 79%     |
| Yes  | 21        | 21%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 39        | 79.59%  |
| Apple                           | 3         | 6.12%   |
| Realtek Semiconductor           | 2         | 4.08%   |
| Realtek                         | 1         | 2.04%   |
| Qualcomm Atheros Communications | 1         | 2.04%   |
| IMC Networks                    | 1         | 2.04%   |
| Cambridge Silicon Radio         | 1         | 2.04%   |
| Broadcom                        | 1         | 2.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 11        | 22.45%  |
| Intel AX200 Bluetooth                               | 9         | 18.37%  |
| Intel Bluetooth wireless interface                  | 7         | 14.29%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4         | 8.16%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 8.16%   |
| Intel AX210 Bluetooth                               | 3         | 6.12%   |
| Apple Bluetooth Host Controller                     | 2         | 4.08%   |
| Realtek  Bluetooth Adapter                          | 1         | 2.04%   |
| Realtek Bluetooth Radio                             | 1         | 2.04%   |
| Realtek Bluetooth Radio                             | 1         | 2.04%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 2.04%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2.04%   |
| IMC Networks Bluetooth module                       | 1         | 2.04%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.04%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 2.04%   |
| Apple Apple Broadcom Built-in Bluetooth             | 1         | 2.04%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 45        | 38.46%  |
| AMD                     | 37        | 31.62%  |
| Nvidia                  | 23        | 19.66%  |
| Lenovo                  | 3         | 2.56%   |
| Yamaha                  | 1         | 0.85%   |
| SteelSeries ApS         | 1         | 0.85%   |
| Logitech                | 1         | 0.85%   |
| GN Netcom               | 1         | 0.85%   |
| Generalplus Technology  | 1         | 0.85%   |
| CMX Systems             | 1         | 0.85%   |
| C-Media Electronics     | 1         | 0.85%   |
| AudioQuest              | 1         | 0.85%   |
| AKAI  Professional M.I. | 1         | 0.85%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 20        | 13.79%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 11        | 7.59%   |
| Intel Comet Lake PCH cAVS                                                  | 9         | 6.21%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 5.52%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8         | 5.52%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 4.14%   |
| AMD Starship/Matisse HD Audio Controller                                   | 6         | 4.14%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5         | 3.45%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4         | 2.76%   |
| Intel Comet Lake PCH-LP cAVS                                               | 4         | 2.76%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 2.76%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4         | 2.76%   |
| Intel Sunrise Point-LP HD Audio                                            | 3         | 2.07%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 3         | 2.07%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 1.38%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 1.38%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 1.38%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 1.38%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 1.38%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 1.38%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 1.38%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2         | 1.38%   |
| AMD Navi 10 HDMI Audio                                                     | 2         | 1.38%   |
| Yamaha Steinberg UR12                                                      | 1         | 0.69%   |
| SteelSeries ApS SteelSeries Siberia 350                                    | 1         | 0.69%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.69%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 0.69%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.69%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 0.69%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.69%   |
| Nvidia GM206 High Definition Audio Controller                              | 1         | 0.69%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.69%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 0.69%   |
| Logitech H390 headset with microphone                                      | 1         | 0.69%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                   | 1         | 0.69%   |
| Lenovo ThinkPad Dock Audio                                                 | 1         | 0.69%   |
| Lenovo Realtek USB Audio                                                   | 1         | 0.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 0.69%   |
| Intel Jasper Lake HD Audio                                                 | 1         | 0.69%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 0.69%   |
| Intel CM238 HD Audio Controller                                            | 1         | 0.69%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 0.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 0.69%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 1         | 0.69%   |
| GN Netcom Jabra SPEAK 410 USB                                              | 1         | 0.69%   |
| Generalplus Technology USB Audio Device                                    | 1         | 0.69%   |
| CMX Systems USB PnP Audio Device                                           | 1         | 0.69%   |
| C-Media Electronics Anua Mic CM 900                                        | 1         | 0.69%   |
| AudioQuest DragonFly                                                       | 1         | 0.69%   |
| AMD Wrestler HDMI Audio                                                    | 1         | 0.69%   |
| AMD RV630 HDMI Audio [Radeon HD 2600 PRO/XT / HD 3610]                     | 1         | 0.69%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1         | 0.69%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1         | 0.69%   |
| AKAI  Professional M.I. LPK25 MIDI Keyboard                                | 1         | 0.69%   |
| Unknown                                                                    | 1         | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 19        | 20.65%  |
| Micron Technology      | 14        | 15.22%  |
| SK Hynix               | 13        | 14.13%  |
| Kingston               | 11        | 11.96%  |
| Crucial                | 8         | 8.7%    |
| Corsair                | 5         | 5.43%   |
| Unknown                | 4         | 4.35%   |
| Smart                  | 3         | 3.26%   |
| Team                   | 2         | 2.17%   |
| Ramaxel Technology     | 2         | 2.17%   |
| GOODRAM                | 2         | 2.17%   |
| Unknown (000000000C01) | 1         | 1.09%   |
| Transcend              | 1         | 1.09%   |
| PNY                    | 1         | 1.09%   |
| Klevv                  | 1         | 1.09%   |
| Gold Key               | 1         | 1.09%   |
| G.Skill                | 1         | 1.09%   |
| A-DATA Technology      | 1         | 1.09%   |
| 06F100000C01           | 1         | 1.09%   |
| Unknown                | 1         | 1.09%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s        | 4         | 4.26%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 2.13%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 2         | 2.13%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s       | 2         | 2.13%   |
| SK Hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 2         | 2.13%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s        | 2         | 2.13%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s         | 2         | 2.13%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s         | 2         | 2.13%   |
| Crucial RAM BL32G32C16S4B.M16FB1 32GB SODIMM DDR4 2667MT/s   | 2         | 2.13%   |
| Corsair RAM CMK32GX4M2D3200C16 16GB DIMM DDR4 3200MT/s       | 2         | 2.13%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                    | 1         | 1.06%   |
| Unknown RAM Module 1GB SODIMM DDR                            | 1         | 1.06%   |
| Unknown RAM 3000 C16 Series 4096MB DIMM DDR4 2933MT/s        | 1         | 1.06%   |
| Unknown RAM 2G-08-10-12-1333 2GB DIMM DDR3 1333MT/s          | 1         | 1.06%   |
| Unknown (000000000C01) RAM Module 32GB DIMM DDR4 3200MT/s    | 1         | 1.06%   |
| Transcend RAM JM2666HLE-32G 32GB DIMM DDR4 2666MT/s          | 1         | 1.06%   |
| Team RAM TEAMGROUP-UD4-4133 8GB DIMM DDR4 4133MT/s           | 1         | 1.06%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s        | 1         | 1.06%   |
| Smart RAM SF4641G8CK8IWGKSEG 8GB SODIMM DDR4 2133MT/s        | 1         | 1.06%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s        | 1         | 1.06%   |
| SMART RAM Module 8GB DIMM DDR4 2667MT/s                      | 1         | 1.06%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1867MT/s                 | 1         | 1.06%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                 | 1         | 1.06%   |
| SK Hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s      | 1         | 1.06%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 1.06%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 1.06%   |
| Samsung RAM M474A4G43AB1-CVF 32GB SODIMM DDR4 2933MT/s       | 1         | 1.06%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s        | 1         | 1.06%   |
| Samsung RAM M471B5674-M0-YK0 4GB Chip DDR3 1600MT/s          | 1         | 1.06%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 1         | 1.06%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s        | 1         | 1.06%   |
| Samsung RAM M471A5244BB0-CWE 4GB SODIMM DDR4 3200MT/s        | 1         | 1.06%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s       | 1         | 1.06%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s       | 1         | 1.06%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 1         | 1.06%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s  | 1         | 1.06%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 1.06%   |
| Samsung RAM M378A4G43MB1-CTD 32GB DIMM DDR4 2666MT/s         | 1         | 1.06%   |
| Samsung RAM K4EBE304EB-EGCF 8GB Row Of Chips LPDDR3 1867MT/s | 1         | 1.06%   |
| Ramaxel RAM RMSA3320MJ78HAF-3200 8GB SODIMM DDR4 3200MT/s    | 1         | 1.06%   |
| Ramaxel RAM RMSA3300MH78HBF-2666 16GB SODIMM DDR4 2400MT/s   | 1         | 1.06%   |
| PNY RAM 16GU2X16LIII43-12-K 16GB SODIMM DDR4 2667MT/s        | 1         | 1.06%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                   | 1         | 1.06%   |
| Micron RAM Module 16GB DIMM DDR4 2400MT/s                    | 1         | 1.06%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s  | 1         | 1.06%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s        | 1         | 1.06%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s   | 1         | 1.06%   |
| Micron RAM 4ATF1G64HZ-3G2B2 8GB SODIMM DDR4 3200MT/s         | 1         | 1.06%   |
| Micron RAM 18ASF4G72AZ-3G2B1 32GB DIMM DDR4 3200MT/s         | 1         | 1.06%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s        | 1         | 1.06%   |
| Micron RAM 16ATF2G64HZ-2G6J1 16GB SODIMM DDR4 2667MT/s       | 1         | 1.06%   |
| Micron RAM 16ATF2G64AZ-3G2J1 16GB DIMM DDR4 3200MT/s         | 1         | 1.06%   |
| Klevv RAM KD4AGSA8M-32N220A 16GB SODIMM DDR4 3200MT/s        | 1         | 1.06%   |
| Kingston RAM Module 8GB SODIMM DDR4 2667MT/s                 | 1         | 1.06%   |
| Kingston RAM Module 16GB SODIMM DDR4 2667MT/s                | 1         | 1.06%   |
| Kingston RAM Module 16GB SODIMM DDR4 2400MT/s                | 1         | 1.06%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 2933MT/s         | 1         | 1.06%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s       | 1         | 1.06%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 2666MT/s          | 1         | 1.06%   |
| Kingston RAM KHX2400C14S4/4G 4GB SODIMM DDR4 2400MT/s        | 1         | 1.06%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 63        | 77.78%  |
| DDR3   | 15        | 18.52%  |
| LPDDR4 | 1         | 1.23%   |
| LPDDR3 | 1         | 1.23%   |
| DDR    | 1         | 1.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 54        | 65.85%  |
| DIMM         | 23        | 28.05%  |
| Row Of Chips | 4         | 4.88%   |
| Chip         | 1         | 1.22%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 33        | 39.29%  |
| 16384 | 26        | 30.95%  |
| 32768 | 12        | 14.29%  |
| 4096  | 10        | 11.9%   |
| 2048  | 2         | 2.38%   |
| 1024  | 1         | 1.19%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 29        | 34.12%  |
| 2667    | 18        | 21.18%  |
| 1600    | 8         | 9.41%   |
| 1867    | 6         | 7.06%   |
| 2400    | 5         | 5.88%   |
| 2666    | 4         | 4.71%   |
| 2133    | 4         | 4.71%   |
| 2933    | 3         | 3.53%   |
| 1333    | 2         | 2.35%   |
| 4267    | 1         | 1.18%   |
| 4133    | 1         | 1.18%   |
| 3600    | 1         | 1.18%   |
| 3000    | 1         | 1.18%   |
| 1334    | 1         | 1.18%   |
| Unknown | 1         | 1.18%   |

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
| Chicony Electronics                    | 14        | 24.56%  |
| IMC Networks                           | 10        | 17.54%  |
| Logitech                               | 6         | 10.53%  |
| Realtek Semiconductor                  | 5         | 8.77%   |
| Lite-On Technology                     | 5         | 8.77%   |
| Acer                                   | 5         | 8.77%   |
| Sunplus Innovation Technology          | 3         | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 5.26%   |
| Microdia                               | 2         | 3.51%   |
| Syntek                                 | 1         | 1.75%   |
| GEMBIRD                                | 1         | 1.75%   |
| Aveo Technology                        | 1         | 1.75%   |
| Apple                                  | 1         | 1.75%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                             | 7         | 12.07%  |
| Chicony Integrated Camera                                                  | 6         | 10.34%  |
| Logitech Webcam C270                                                       | 3         | 5.17%   |
| Lite-On Integrated Camera                                                  | 3         | 5.17%   |
| Chicony Integrated HP HD Webcam                                            | 3         | 5.17%   |
| Acer Integrated Camera                                                     | 3         | 5.17%   |
| Sunplus Integrated_Webcam_HD                                               | 2         | 3.45%   |
| Realtek Laptop Camera                                                      | 2         | 3.45%   |
| Lite-On HP HD Camera                                                       | 2         | 3.45%   |
| Acer HD Webcam                                                             | 2         | 3.45%   |
| Syntek Lenovo EasyCamera                                                   | 1         | 1.72%   |
| Sunplus Integrated_Webcam_FHD                                              | 1         | 1.72%   |
| Realtek USB 2 Webcam                                                       | 1         | 1.72%   |
| Realtek Realtek USB2.0 PC Camera                                           | 1         | 1.72%   |
| Realtek Integrated_Webcam_HD                                               | 1         | 1.72%   |
| Microdia HP Integrated Webcam                                              | 1         | 1.72%   |
| Microdia Dell Integrated HD Webcam                                         | 1         | 1.72%   |
| Logitech Webcam C170                                                       | 1         | 1.72%   |
| Logitech HD Pro Webcam C920                                                | 1         | 1.72%   |
| Logitech C920 PRO HD Webcam                                                | 1         | 1.72%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 1         | 1.72%   |
| IMC Networks HD Camera                                                     | 1         | 1.72%   |
| IMC Networks EasyCamera                                                    | 1         | 1.72%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]                          | 1         | 1.72%   |
| Chicony USB2.0 0.3M UVC WebCam                                             | 1         | 1.72%   |
| Chicony ThinkPad T490 Webcam                                               | 1         | 1.72%   |
| Chicony Ltd., Integrated Camera                                            | 1         | 1.72%   |
| Chicony Integrated IR Camera                                               | 1         | 1.72%   |
| Chicony HD Webcam                                                          | 1         | 1.72%   |
| Chicony Chicony USB2.0 Camera                                              | 1         | 1.72%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 1.72%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed]                | 1         | 1.72%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam   | 1         | 1.72%   |
| Aveo USB2.0 Camera                                                         | 1         | 1.72%   |
| Apple FaceTime HD Camera (Built-in)                                        | 1         | 1.72%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 8         | 44.44%  |
| Validity Sensors           | 5         | 27.78%  |
| Shenzhen Goodix Technology | 4         | 22.22%  |
| AuthenTec                  | 1         | 5.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


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

![Unsupported Devices](./All/images/pie_chart_bsd/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 28        | 28.87%  |
| 2     | 25        | 25.77%  |
| 4     | 15        | 15.46%  |
| 1     | 15        | 15.46%  |
| 3     | 10        | 10.31%  |
| 5     | 3         | 3.09%   |
| 9     | 1         | 1.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 51        | 34.93%  |
| Bluetooth                | 30        | 20.55%  |
| Net/wireless             | 27        | 18.49%  |
| Fingerprint reader       | 18        | 12.33%  |
| Card reader              | 8         | 5.48%   |
| Sound                    | 5         | 3.42%   |
| Net/ethernet             | 3         | 2.05%   |
| Firewire controller      | 2         | 1.37%   |
| Network                  | 1         | 0.68%   |
| Modem                    | 1         | 0.68%   |

