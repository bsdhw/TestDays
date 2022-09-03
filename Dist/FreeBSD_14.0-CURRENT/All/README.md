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

Total: 194

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Valve         | Jupiter                     | Notebook    | [4e58d828cc](https://bsd-hardware.info/?probe=4e58d828cc) | Sep 01, 2022 |
| Dell          | 0VG93V A00                  | Desktop     | [8de9fa2319](https://bsd-hardware.info/?probe=8de9fa2319) | Aug 18, 2022 |
| Intel         | S2600WTTR G92187-372        | Server      | [ce1988c8ff](https://bsd-hardware.info/?probe=ce1988c8ff) | Aug 18, 2022 |
| Unknown       | Unknown                     | Desktop     | [3208aefb72](https://bsd-hardware.info/?probe=3208aefb72) | Aug 17, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [978f01c546](https://bsd-hardware.info/?probe=978f01c546) | Jul 16, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [68c4af67b5](https://bsd-hardware.info/?probe=68c4af67b5) | Jul 14, 2022 |
| Lenovo        | ThinkPad T495 20NJ0010PB    | Notebook    | [078888676a](https://bsd-hardware.info/?probe=078888676a) | Jul 13, 2022 |
| Apple         | MacBookAir5,2               | Notebook    | [894b6f82cf](https://bsd-hardware.info/?probe=894b6f82cf) | Jul 13, 2022 |
| Toshiba       | Satellite L305D             | Notebook    | [ed950787b0](https://bsd-hardware.info/?probe=ed950787b0) | Jul 10, 2022 |
| Intel         | NUC11PHBi7 M26151-402       | Mini pc     | [7c34be7c2e](https://bsd-hardware.info/?probe=7c34be7c2e) | Jul 06, 2022 |
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
| Valve         | Jupiter                     | Notebook    | [e5aca4b7d0](https://bsd-hardware.info/?probe=e5aca4b7d0) | Oct 02, 2021 |
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
| amd64 | 84        | 83.17%  |
| arm64 | 13        | 12.87%  |
| arm   | 2         | 1.98%   |
| riscv | 1         | 0.99%   |
| i386  | 1         | 0.99%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KDE5          | 28        | 26.17%  |
| Console       | 25        | 23.36%  |
| XFCE          | 12        | 11.21%  |
| MATE          | 8         | 7.48%   |
| TWM           | 6         | 5.61%   |
| i3            | 5         | 4.67%   |
| GNOME         | 5         | 4.67%   |
| Openbox       | 3         | 2.8%    |
| Cinnamon      | 3         | 2.8%    |
| LXDE          | 2         | 1.87%   |
| Lumina        | 2         | 1.87%   |
| Xfwm4         | 1         | 0.93%   |
| Picom         | 1         | 0.93%   |
| LXQt          | 1         | 0.93%   |
| GNUstep       | 1         | 0.93%   |
| Fluxbox       | 1         | 0.93%   |
| Enlightenment | 1         | 0.93%   |
| ctwm          | 1         | 0.93%   |
| akonadi_newm  | 1         | 0.93%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 73        | 69.52%  |
| Console | 30        | 28.57%  |
| Wayland | 2         | 1.9%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 46        | 44.23%  |
| SDDM    | 24        | 23.08%  |
| SLiM    | 13        | 12.5%   |
| GDM     | 11        | 10.58%  |
| XDM     | 6         | 5.77%   |
| LightDM | 3         | 2.88%   |
| Ly      | 1         | 0.96%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Computers | Percent |
|------------------|-----------|---------|
| C                | 67        | 64.42%  |
| en_US            | 12        | 11.54%  |
| de_DE            | 5         | 4.81%   |
| Unknown          | 5         | 4.81%   |
| uk_UA            | 3         | 2.88%   |
| en_GB            | 3         | 2.88%   |
| zh_CN            | 2         | 1.92%   |
| sv_SE            | 1         | 0.96%   |
| ru_RU            | 1         | 0.96%   |
| pt_PT            | 1         | 0.96%   |
| pl_PL            | 1         | 0.96%   |
| it_IT.ISO8859-15 | 1         | 0.96%   |
| fr_FR            | 1         | 0.96%   |
| de_CH            | 1         | 0.96%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 89        | 88.12%  |
| BIOS | 12        | 11.88%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 71        | 70.3%   |
| Ufs  | 30        | 29.7%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 92        | 91.09%  |
| MBR  | 9         | 8.91%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 25        | 24.75%  |
| Dell                           | 11        | 10.89%  |
| ASUSTek Computer               | 11        | 10.89%  |
| Unknown                        | 10        | 9.9%    |
| Hewlett-Packard                | 9         | 8.91%   |
| Gigabyte Technology            | 7         | 6.93%   |
| Raspberry Pi Foundation        | 4         | 3.96%   |
| MSI                            | 3         | 2.97%   |
| ASRock                         | 3         | 2.97%   |
| Apple                          | 3         | 2.97%   |
| Intel                          | 2         | 1.98%   |
| Framework                      | 2         | 1.98%   |
| Beckhoff Automation            | 2         | 1.98%   |
| Valve                          | 1         | 0.99%   |
| pine64                         | 1         | 0.99%   |
| Notebook                       | 1         | 0.99%   |
| Matsushita Electric Industrial | 1         | 0.99%   |
| khadas                         | 1         | 0.99%   |
| HUAWEI                         | 1         | 0.99%   |
| friendlyelec                   | 1         | 0.99%   |
| Avell High Performance         | 1         | 0.99%   |
| A-DATA Technology              | 1         | 0.99%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 11        | 10.89%  |
| RPi Raspberry Pi                            | 3         | 2.97%   |
| HP EliteBook 8570p                          | 3         | 2.97%   |
| Framework Laptop                            | 2         | 1.98%   |
| Valve Jupiter                               | 1         | 0.99%   |
| RPi rpi                                     | 1         | 0.99%   |
| pine64 pinebook-pro-rk3399                  | 1         | 0.99%   |
| Notebook NS50_70MU                          | 1         | 0.99%   |
| MSI MS-7B86                                 | 1         | 0.99%   |
| MSI GE76 Raider 10UG                        | 1         | 0.99%   |
| MSI Bravo 15 A4DDR                          | 1         | 0.99%   |
| Matsushita Electric Industrial CF-T2BW1AXR  | 1         | 0.99%   |
| Lenovo XiaoXinPro-13ARE 2020 82DM           | 1         | 0.99%   |
| Lenovo ThinkPad X395 20NL001SMX             | 1         | 0.99%   |
| Lenovo ThinkPad X395 20NL000GPG             | 1         | 0.99%   |
| Lenovo ThinkPad X270 20HM004JBR             | 1         | 0.99%   |
| Lenovo ThinkPad X260 20F5A28AUK             | 1         | 0.99%   |
| Lenovo ThinkPad X13 Gen 1 20T2003PRT        | 1         | 0.99%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TLA055CD | 1         | 0.99%   |
| Lenovo ThinkPad X1 Extreme 20MF000BUS       | 1         | 0.99%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS1QC00    | 1         | 0.99%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS0BT00    | 1         | 0.99%   |
| Lenovo ThinkPad T495s 20QKS1812F            | 1         | 0.99%   |
| Lenovo ThinkPad T495 20NJ0010PB             | 1         | 0.99%   |
| Lenovo ThinkPad T470p 20J7S0PM00            | 1         | 0.99%   |
| Lenovo ThinkPad T430 2349H2G                | 1         | 0.99%   |
| Lenovo ThinkPad T14s Gen 2i 20WM00B7MX      | 1         | 0.99%   |
| Lenovo ThinkPad P15 Gen 1 20ST005VRT        | 1         | 0.99%   |
| Lenovo ThinkPad P14s Gen 1 20Y1CTO1WW       | 1         | 0.99%   |
| Lenovo ThinkPad E14 Gen 3 20Y7003SGE        | 1         | 0.99%   |
| Lenovo ThinkPad E14 20RBCTO1WW              | 1         | 0.99%   |
| Lenovo ThinkBook 14 G3 ACL 21A2             | 1         | 0.99%   |
| Lenovo Legion 5P 15IMH05H 82AW              | 1         | 0.99%   |
| Lenovo Legion 5 15IMH05 82AU                | 1         | 0.99%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY        | 1         | 0.99%   |
| Lenovo IdeaPad 330-15ARR 81D2               | 1         | 0.99%   |
| khadas edge-v                               | 1         | 0.99%   |
| Intel S2600WTTR                             | 1         | 0.99%   |
| Intel NUC11PHi7                             | 1         | 0.99%   |
| HUAWEI HN-WX9X                              | 1         | 0.99%   |
| HP ZBook 17 G2                              | 1         | 0.99%   |
| HP ProBook 455 G7                           | 1         | 0.99%   |
| HP ProBook 440 G7                           | 1         | 0.99%   |
| HP ProBook 440 G6                           | 1         | 0.99%   |
| HP EliteDesk 800 G4 SFF                     | 1         | 0.99%   |
| HP EliteBook Folio 9470m                    | 1         | 0.99%   |
| Gigabyte X570 AORUS MASTER                  | 1         | 0.99%   |
| Gigabyte X570 AORUS ELITE                   | 1         | 0.99%   |
| Gigabyte X399 DESIGNARE EX                  | 1         | 0.99%   |
| Gigabyte B550I AORUS PRO AX                 | 1         | 0.99%   |
| Gigabyte B450M S2H                          | 1         | 0.99%   |
| Gigabyte B450M DS3H                         | 1         | 0.99%   |
| Gigabyte 970A-UD3P                          | 1         | 0.99%   |
| friendlyelec nanopi-m4                      | 1         | 0.99%   |
| Dell Vostro 5490                            | 1         | 0.99%   |
| Dell PowerEdge T150                         | 1         | 0.99%   |
| Dell OptiPlex 5490 AIO                      | 1         | 0.99%   |
| Dell OptiPlex 5090                          | 1         | 0.99%   |
| Dell OptiPlex 5080                          | 1         | 0.99%   |
| Dell Latitude E5430 vPro                    | 1         | 0.99%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo ThinkPad                            | 18        | 17.82%  |
| Unknown                                    | 11        | 10.89%  |
| ASUS PRIME                                 | 5         | 4.95%   |
| HP EliteBook                               | 4         | 3.96%   |
| RPi Raspberry                              | 3         | 2.97%   |
| HP ProBook                                 | 3         | 2.97%   |
| Dell OptiPlex                              | 3         | 2.97%   |
| Dell Latitude                              | 3         | 2.97%   |
| Lenovo Legion                              | 2         | 1.98%   |
| Lenovo IdeaPad                             | 2         | 1.98%   |
| Gigabyte X570                              | 2         | 1.98%   |
| Gigabyte B450M                             | 2         | 1.98%   |
| Framework Laptop                           | 2         | 1.98%   |
| Valve Jupiter                              | 1         | 0.99%   |
| RPi rpi                                    | 1         | 0.99%   |
| pine64 pinebook-pro-rk3399                 | 1         | 0.99%   |
| Notebook NS50                              | 1         | 0.99%   |
| MSI MS-7B86                                | 1         | 0.99%   |
| MSI GE76                                   | 1         | 0.99%   |
| MSI Bravo                                  | 1         | 0.99%   |
| Matsushita Electric Industrial CF-T2BW1AXR | 1         | 0.99%   |
| Lenovo XiaoXinPro-13ARE                    | 1         | 0.99%   |
| Lenovo ThinkBook                           | 1         | 0.99%   |
| khadas edge-v                              | 1         | 0.99%   |
| Intel S2600WTTR                            | 1         | 0.99%   |
| Intel NUC11PHi7                            | 1         | 0.99%   |
| HUAWEI HN-WX9X                             | 1         | 0.99%   |
| HP ZBook                                   | 1         | 0.99%   |
| HP EliteDesk                               | 1         | 0.99%   |
| Gigabyte X399                              | 1         | 0.99%   |
| Gigabyte B550I                             | 1         | 0.99%   |
| Gigabyte 970A-UD3P                         | 1         | 0.99%   |
| friendlyelec nanopi-m4                     | 1         | 0.99%   |
| Dell Vostro                                | 1         | 0.99%   |
| Dell PowerEdge                             | 1         | 0.99%   |
| Dell Inspiron                              | 1         | 0.99%   |
| Dell G5                                    | 1         | 0.99%   |
| Dell G3                                    | 1         | 0.99%   |
| Beckhoff Automation CX2033-0185            | 1         | 0.99%   |
| Beckhoff Automation CBxx63                 | 1         | 0.99%   |
| Avell High Performance A62                 | 1         | 0.99%   |
| ASUS VivoBook                              | 1         | 0.99%   |
| ASUS TUF                                   | 1         | 0.99%   |
| ASUS ROG                                   | 1         | 0.99%   |
| ASUS P8H77-M                               | 1         | 0.99%   |
| ASUS MINIPC                                | 1         | 0.99%   |
| ASUS 1215B                                 | 1         | 0.99%   |
| ASRock X570                                | 1         | 0.99%   |
| ASRock B550                                | 1         | 0.99%   |
| ASRock B450                                | 1         | 0.99%   |
| Apple MacBookPro12                         | 1         | 0.99%   |
| Apple MacBookPro10                         | 1         | 0.99%   |
| Apple MacBookAir5                          | 1         | 0.99%   |
| A-DATA XENIA159GENI72060                   | 1         | 0.99%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 26        | 25.74%  |
| 2021    | 25        | 24.75%  |
| 2019    | 13        | 12.87%  |
| Unknown | 10        | 9.9%    |
| 2018    | 7         | 6.93%   |
| 2022    | 4         | 3.96%   |
| 2017    | 4         | 3.96%   |
| 2013    | 4         | 3.96%   |
| 2015    | 3         | 2.97%   |
| 2016    | 2         | 1.98%   |
| 2012    | 1         | 0.99%   |
| 2011    | 1         | 0.99%   |
| 2003    | 1         | 0.99%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 55        | 54.46%  |
| Desktop        | 34        | 33.66%  |
| System on chip | 7         | 6.93%   |
| Mini pc        | 2         | 1.98%   |
| Server         | 2         | 1.98%   |
| All in one     | 1         | 0.99%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 101       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 39        | 37.86%  |
| 8.01-16.0       | 19        | 18.45%  |
| 32.01-64.0      | 16        | 15.53%  |
| 64.01-256.0     | 14        | 13.59%  |
| 4.01-8.0        | 8         | 7.77%   |
| 0.51-1.0        | 2         | 1.94%   |
| More than 256.0 | 1         | 0.97%   |
| 3.01-4.0        | 1         | 0.97%   |
| 24.01-32.0      | 1         | 0.97%   |
| 1.01-2.0        | 1         | 0.97%   |
| 0.01-0.5        | 1         | 0.97%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.51-1.0    | 34        | 32.69%  |
| 1.01-2.0    | 28        | 26.92%  |
| 0.01-0.5    | 17        | 16.35%  |
| 2.01-3.0    | 11        | 10.58%  |
| 3.01-4.0    | 5         | 4.81%   |
| 24.01-32.0  | 2         | 1.92%   |
| 0           | 2         | 1.92%   |
| 4.01-8.0    | 1         | 0.96%   |
| 32.01-64.0  | 1         | 0.96%   |
| 64.01-256.0 | 1         | 0.96%   |
| 16.01-24.0  | 1         | 0.96%   |
| 8.01-16.0   | 1         | 0.96%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 51        | 47.66%  |
| 2      | 28        | 26.17%  |
| 0      | 12        | 11.21%  |
| 6      | 5         | 4.67%   |
| 3      | 5         | 4.67%   |
| 4      | 3         | 2.8%    |
| 15     | 1         | 0.93%   |
| 7      | 1         | 0.93%   |
| 5      | 1         | 0.93%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 88        | 85.44%  |
| Yes       | 15        | 14.56%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 79        | 78.22%  |
| No        | 22        | 21.78%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 70        | 69.31%  |
| No        | 31        | 30.69%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 52        | 50.98%  |
| No        | 50        | 49.02%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 18        | 17.82%  |
| UK           | 11        | 10.89%  |
| Germany      | 11        | 10.89%  |
| Russia       | 10        | 9.9%    |
| Brazil       | 6         | 5.94%   |
| Poland       | 5         | 4.95%   |
| Ukraine      | 4         | 3.96%   |
| Japan        | 4         | 3.96%   |
| China        | 4         | 3.96%   |
| Austria      | 4         | 3.96%   |
| Portugal     | 3         | 2.97%   |
| Switzerland  | 2         | 1.98%   |
| Sweden       | 2         | 1.98%   |
| Netherlands  | 2         | 1.98%   |
| Turkey       | 1         | 0.99%   |
| Spain        | 1         | 0.99%   |
| Singapore    | 1         | 0.99%   |
| Saudi Arabia | 1         | 0.99%   |
| Romania      | 1         | 0.99%   |
| Peru         | 1         | 0.99%   |
| Jamaica      | 1         | 0.99%   |
| Italy        | 1         | 0.99%   |
| India        | 1         | 0.99%   |
| France       | 1         | 0.99%   |
| Denmark      | 1         | 0.99%   |
| Croatia      | 1         | 0.99%   |
| Colombia     | 1         | 0.99%   |
| Belarus      | 1         | 0.99%   |
| Bangladesh   | 1         | 0.99%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Moscow                      | 5         | 4.39%   |
| Brighton                    | 5         | 4.39%   |
| ЕЊta-ku                   | 3         | 2.63%   |
| St Petersburg               | 3         | 2.63%   |
| Seattle                     | 3         | 2.63%   |
| London                      | 3         | 2.63%   |
| Kyiv                        | 3         | 2.63%   |
| Zurich                      | 2         | 1.75%   |
| Vienna                      | 2         | 1.75%   |
| Rio de Janeiro              | 2         | 1.75%   |
| Rietberg                    | 2         | 1.75%   |
| Northeim                    | 2         | 1.75%   |
| Graz                        | 2         | 1.75%   |
| Fuchu                       | 2         | 1.75%   |
| Egham                       | 2         | 1.75%   |
| Chicago                     | 2         | 1.75%   |
| Cambridge                   | 2         | 1.75%   |
| Berlin                      | 2         | 1.75%   |
| Zaporizhzhya                | 1         | 0.88%   |
| Wuhan                       | 1         | 0.88%   |
| Worthing                    | 1         | 0.88%   |
| Woodburn                    | 1         | 0.88%   |
| Wieliczka                   | 1         | 0.88%   |
| Washington                  | 1         | 0.88%   |
| Warsaw                      | 1         | 0.88%   |
| Vila Real de Santo António | 1         | 0.88%   |
| Vancouver                   | 1         | 0.88%   |
| Tynda                       | 1         | 0.88%   |
| Trosa                       | 1         | 0.88%   |
| Thrissur                    | 1         | 0.88%   |
| Teaneck                     | 1         | 0.88%   |
| Stuttgart                   | 1         | 0.88%   |
| Sollentuna                  | 1         | 0.88%   |
| Slavonski Brod              | 1         | 0.88%   |
| Singapore                   | 1         | 0.88%   |
| Shanghai                    | 1         | 0.88%   |
| Setagaya-ku                 | 1         | 0.88%   |
| Santa Monica                | 1         | 0.88%   |
| San Francisco               | 1         | 0.88%   |
| Ruthin                      | 1         | 0.88%   |
| Rostov-on-Don               | 1         | 0.88%   |
| Riyadh                      | 1         | 0.88%   |
| Riverside                   | 1         | 0.88%   |
| Resana                      | 1         | 0.88%   |
| Poulsbo                     | 1         | 0.88%   |
| Pobiedziska                 | 1         | 0.88%   |
| Omaha                       | 1         | 0.88%   |
| New York                    | 1         | 0.88%   |
| Montclair                   | 1         | 0.88%   |
| Minsk                       | 1         | 0.88%   |
| Milan                       | 1         | 0.88%   |
| Medellín                   | 1         | 0.88%   |
| Manchester                  | 1         | 0.88%   |
| Maia                        | 1         | 0.88%   |
| Madrid                      | 1         | 0.88%   |
| Lubin                       | 1         | 0.88%   |
| Lima                        | 1         | 0.88%   |
| Lake Forest                 | 1         | 0.88%   |
| Kunitachi                   | 1         | 0.88%   |
| Kislovodsk                  | 1         | 0.88%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 27        | 44     | 20.61%  |
| Samsung Electronics | 26        | 37     | 19.85%  |
| Toshiba             | 12        | 25     | 9.16%   |
| Seagate             | 8         | 24     | 6.11%   |
| Crucial             | 8         | 17     | 6.11%   |
| Kingston            | 7         | 10     | 5.34%   |
| HGST                | 7         | 24     | 5.34%   |
| SK hynix            | 5         | 5      | 3.82%   |
| A-DATA Technology   | 5         | 5      | 3.82%   |
| KIOXIA              | 4         | 4      | 3.05%   |
| Intel               | 4         | 7      | 3.05%   |
| Apple               | 3         | 3      | 2.29%   |
| Micron Technology   | 2         | 3      | 1.53%   |
| SSSTC               | 1         | 1      | 0.76%   |
| SPCC                | 1         | 1      | 0.76%   |
| Solid State Storage | 1         | 1      | 0.76%   |
| Silicon Motion      | 1         | 1      | 0.76%   |
| SanDisk             | 1         | 2      | 0.76%   |
| PNY                 | 1         | 1      | 0.76%   |
| Mushkin             | 1         | 1      | 0.76%   |
| LSI                 | 1         | 4      | 0.76%   |
| LITEON              | 1         | 1      | 0.76%   |
| Hitachi             | 1         | 2      | 0.76%   |
| Goodram             | 1         | 1      | 0.76%   |
| Fujitsu             | 1         | 2      | 0.76%   |
| Apacer              | 1         | 1      | 0.76%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB                           | 5         | 3.45%   |
| HGST HTS725050A7E630 500GB                         | 4         | 2.76%   |
| WDC WDS100T3X0C-00SJG0 1TB                         | 3         | 2.07%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB               | 3         | 2.07%   |
| Toshiba MQ04ABF100 1TB                             | 3         | 2.07%   |
| Samsung HM251JX 250GB                              | 3         | 2.07%   |
| HGST HTS721010A9E630 1TB                           | 3         | 2.07%   |
| WDC WDS100T1X0E-00AFY0 1TB                         | 2         | 1.38%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB                 | 2         | 1.38%   |
| WDC PC SN730 NVMe 1024GB                           | 2         | 1.38%   |
| Samsung SSD 870 EVO 1TB                            | 2         | 1.38%   |
| Samsung SSD 850 EVO 250GB                          | 2         | 1.38%   |
| Samsung MZVLB512HBJQ-000L7 512GB                   | 2         | 1.38%   |
| KIOXIA KBG40ZNS256G NVMe 256GB                     | 2         | 1.38%   |
| Kingston SA2000M81000G 1TB                         | 2         | 1.38%   |
| Apple SSD SM256E 256GB                             | 2         | 1.38%   |
| WDC WDS500G1X0E-00AFY0 500GB                       | 1         | 0.69%   |
| WDC WDS250G2B0C-00PXH0 250GB                       | 1         | 0.69%   |
| WDC WDS100T2B0A-00SM50 1TB                         | 1         | 0.69%   |
| WDC WD60EFRX-68TGBN1 6TB                           | 1         | 0.69%   |
| WDC WD5002ABYS-18B1B0 500GB                        | 1         | 0.69%   |
| WDC WD40EZRZ-75GXCB0 4TB                           | 1         | 0.69%   |
| WDC WD30EFRX-68EUZN0 3TB                           | 1         | 0.69%   |
| WDC WD20EZRZ-00Z5HB0 2TB                           | 1         | 0.69%   |
| WDC WD20EFRX-68AX9N0 2TB                           | 1         | 0.69%   |
| WDC WD120EFAX-68UNTN0 12TB                         | 1         | 0.69%   |
| WDC WD10SPZX-60Z10T0 1TB                           | 1         | 0.69%   |
| WDC WD10SPZX-21Z10T0 1TB                           | 1         | 0.69%   |
| WDC WD10JPVX-00JC3T0 1TB                           | 1         | 0.69%   |
| WDC WD10JMVW-11AJGS3 1TB                           | 1         | 0.69%   |
| WDC WD10EZEX-60WN4A0 1TB                           | 1         | 0.69%   |
| WDC WD10EZEX-00RKKA0 1TB                           | 1         | 0.69%   |
| WDC WD10EARX-00N0YB0 1TB                           | 1         | 0.69%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB               | 1         | 0.69%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB               | 1         | 0.69%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB               | 1         | 0.69%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB               | 1         | 0.69%   |
| Toshiba MQ01ABD100 1TB                             | 1         | 0.69%   |
| Toshiba MG09ACA18TE 18TB                           | 1         | 0.69%   |
| Toshiba MG06ACA800E 8TB                            | 1         | 0.69%   |
| Toshiba KXG6APNV2T04 2TB                           | 1         | 0.69%   |
| SSSTC CL1-3D256-Q11 NVMe 256GB                     | 1         | 0.69%   |
| SPCC M.2 PCIe SSD 1TB                              | 1         | 0.69%   |
| Solid State Storage CL1-3D128-Q11 NVMe SSSTC 128GB | 1         | 0.69%   |
| SK hynix PC801 NVMe 2TB                            | 1         | 0.69%   |
| SK hynix PC300 HFS512GD9MND-5510A 512GB            | 1         | 0.69%   |
| SK hynix HFS128G39TND-N210A 128GB                  | 1         | 0.69%   |
| SK hynix BC511 NVMe 256GB                          | 1         | 0.69%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB            | 1         | 0.69%   |
| Silicon Motion NE-256 256GB                        | 1         | 0.69%   |
| Seagate ST5000LM000-2U8170 5TB                     | 1         | 0.69%   |
| Seagate ST5000LM000-2AN170 5TB                     | 1         | 0.69%   |
| Seagate ST4000DM000-1F2168 4TB                     | 1         | 0.69%   |
| Seagate ST3750640AS 752GB                          | 1         | 0.69%   |
| Seagate ST32000641AS 2TB                           | 1         | 0.69%   |
| Seagate ST3000DM007-1WY10G 3TB                     | 1         | 0.69%   |
| Seagate ST3000DM001-1ER166 3TB                     | 1         | 0.69%   |
| Seagate ST1000LM049-2GH172 1TB                     | 1         | 0.69%   |
| Seagate ST1000LM035-1RK172 1TB                     | 1         | 0.69%   |
| SanDisk SDSSDH3500G 500GB                          | 1         | 0.69%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 11        | 24     | 25.58%  |
| WDC                 | 10        | 16     | 23.26%  |
| Seagate             | 8         | 24     | 18.6%   |
| HGST                | 7         | 24     | 16.28%  |
| Samsung Electronics | 4         | 7      | 9.3%    |
| LSI                 | 1         | 4      | 2.33%   |
| Hitachi             | 1         | 2      | 2.33%   |
| Fujitsu             | 1         | 2      | 2.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 14     | 28.13%  |
| Crucial             | 5         | 10     | 15.63%  |
| Kingston            | 3         | 5      | 9.38%   |
| Apple               | 3         | 3      | 9.38%   |
| A-DATA Technology   | 3         | 3      | 9.38%   |
| Intel               | 2         | 5      | 6.25%   |
| WDC                 | 1         | 2      | 3.13%   |
| SK hynix            | 1         | 1      | 3.13%   |
| SanDisk             | 1         | 2      | 3.13%   |
| Micron Technology   | 1         | 1      | 3.13%   |
| LITEON              | 1         | 1      | 3.13%   |
| Goodram             | 1         | 1      | 3.13%   |
| Apacer              | 1         | 1      | 3.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 53        | 75     | 46.49%  |
| SSD  | 31        | 49     | 27.19%  |
| HDD  | 30        | 103    | 26.32%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 53        | 75     | 50.96%  |
| SATA | 51        | 152    | 49.04%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 32        | 70     | 45.71%  |
| 0.51-1.0   | 21        | 39     | 30%     |
| 1.01-2.0   | 5         | 6      | 7.14%   |
| 4.01-10.0  | 4         | 23     | 5.71%   |
| 3.01-4.0   | 3         | 4      | 4.29%   |
| 2.01-3.0   | 2         | 3      | 2.86%   |
| 10.01-20.0 | 2         | 3      | 2.86%   |
| 20.01-50.0 | 1         | 4      | 1.43%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 26        | 24.3%   |
| 251-500        | 25        | 23.36%  |
| 501-1000       | 18        | 16.82%  |
| 1-20           | 11        | 10.28%  |
| 21-50          | 8         | 7.48%   |
| 51-100         | 8         | 7.48%   |
| 1001-2000      | 5         | 4.67%   |
| More than 3000 | 3         | 2.8%    |
| 2001-3000      | 3         | 2.8%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 64        | 59.81%  |
| 21-50          | 27        | 25.23%  |
| 101-250        | 7         | 6.54%   |
| 1001-2000      | 2         | 1.87%   |
| 501-1000       | 2         | 1.87%   |
| 51-100         | 2         | 1.87%   |
| More than 3000 | 1         | 0.93%   |
| 251-500        | 1         | 0.93%   |
| 0              | 1         | 0.93%   |

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
| HGST HTS721010A9E630 1TB            | 1         | 10     | 7.14%   |
| Fujitsu MHS2040AT D 40GB            | 1         | 2      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 4         | 19     | 30.77%  |
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
| HGST                | 4         | 19     | 40%     |
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
| HDD  | 9         | 29     | 81.82%  |
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
| Works    | 85        | 186    | 85%     |
| Malfunc  | 11        | 34     | 11%     |
| Detected | 4         | 7      | 4%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 41        | 30.6%   |
| AMD                            | 26        | 19.4%   |
| SanDisk                        | 18        | 13.43%  |
| Samsung Electronics            | 17        | 12.69%  |
| SK hynix                       | 4         | 2.99%   |
| Silicon Motion                 | 4         | 2.99%   |
| Kingston Technology Company    | 4         | 2.99%   |
| Micron/Crucial Technology      | 3         | 2.24%   |
| KIOXIA                         | 3         | 2.24%   |
| Toshiba                        | 2         | 1.49%   |
| Solid State Storage Technology | 2         | 1.49%   |
| Micron Technology              | 2         | 1.49%   |
| Marvell Technology Group       | 2         | 1.49%   |
| ASMedia Technology             | 2         | 1.49%   |
| ADATA Technology               | 2         | 1.49%   |
| Phison Electronics             | 1         | 0.75%   |
| Broadcom / LSI                 | 1         | 0.75%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 19        | 13.01%  |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 11        | 7.53%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 11        | 7.53%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 4.79%   |
| Unknown                                                                        | 7         | 4.79%   |
| Intel Comet Lake SATA AHCI Controller                                          | 6         | 4.11%   |
| AMD 400 Series Chipset SATA Controller                                         | 6         | 4.11%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 5         | 3.42%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 4         | 2.74%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 4         | 2.74%   |
| AMD 500 Series Chipset SATA Controller                                         | 4         | 2.74%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 3         | 2.05%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 3         | 2.05%   |
| Toshiba XG6 NVMe SSD Controller                                                | 2         | 1.37%   |
| SK hynix BC511                                                                 | 2         | 1.37%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 1.37%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 1.37%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 1.37%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 1.37%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2         | 1.37%   |
| Kingston Company A2000 NVMe SSD                                                | 2         | 1.37%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 1.37%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.37%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 2         | 1.37%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 2         | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 1.37%   |
| SK hynix PC300 NVMe Solid State Drive 512GB                                    | 1         | 0.68%   |
| SanDisk PC SN530                                                               | 1         | 0.68%   |
| Samsung SM951 AHCI                                                             | 1         | 0.68%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 0.68%   |
| Phison E12 NVMe Controller                                                     | 1         | 0.68%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 1         | 0.68%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                          | 1         | 0.68%   |
| Marvell Group 88SE9170 PCIe 2.0 x1 2-port SATA 6 Gb/s Controller               | 1         | 0.68%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 1         | 0.68%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 0.68%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1         | 0.68%   |
| Intel SSD 660P Series                                                          | 1         | 0.68%   |
| Intel NVMe Optane Memory Series                                                | 1         | 0.68%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 1         | 0.68%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 0.68%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 0.68%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1         | 0.68%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 0.68%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 1         | 0.68%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 1         | 0.68%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 0.68%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 1         | 0.68%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 1         | 0.68%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]    | 1         | 0.68%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]    | 1         | 0.68%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                 | 1         | 0.68%   |
| ASMedia ASM1166 Serial ATA Controller                                          | 1         | 0.68%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 1         | 0.68%   |
| AMD X399 Series Chipset SATA Controller                                        | 1         | 0.68%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 1         | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 62        | 48.44%  |
| NVMe | 60        | 46.88%  |
| IDE  | 4         | 3.13%   |
| RAID | 2         | 1.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 51        | 49.51%  |
| AMD      | 35        | 33.98%  |
| ARM      | 8         | 7.77%   |
| Unknown  | 8         | 7.77%   |
| Research | 1         | 0.97%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
|                                                 | 8         | 7.77%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 6         | 5.83%   |
| Intel Core i7-3520M CPU @ 2.90GHz               | 4         | 3.88%   |
| Intel Core i5-10210U CPU @ 1.60GHz              | 4         | 3.88%   |
| ARM Cortex-A72 r0p3                             | 4         | 3.88%   |
| AMD Ryzen 5 5600G with Radeon Graphics          | 4         | 3.88%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 3         | 2.91%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 2         | 1.94%   |
| Intel Core i7-7600U CPU @ 2.80GHz               | 2         | 1.94%   |
| Intel Core i5-10500T CPU @ 2.30GHz              | 2         | 1.94%   |
| Intel Core i5-10300H CPU @ 2.50GHz              | 2         | 1.94%   |
| ARM Cortex-A72 r0p2                             | 2         | 1.94%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 2         | 1.94%   |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx | 2         | 1.94%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 2         | 1.94%   |
| AMD Ryzen 7 4700U with Radeon Graphics          | 2         | 1.94%   |
| AMD Ryzen 5 PRO 3500U w/ Radeon Vega Mobile Gfx | 2         | 1.94%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 2         | 1.94%   |
| Research Morello SoC r0p0                       | 1         | 0.97%   |
| Intel Xeon W-10885M CPU @ 2.40GHz               | 1         | 0.97%   |
| Intel Xeon E-2334 CPU @ 3.40GHz                 | 1         | 0.97%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz             | 1         | 0.97%   |
| Intel Pentium M processor 1000MHz               | 1         | 0.97%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 1         | 0.97%   |
| Intel Core i7-8700 CPU @ 3.20GHz                | 1         | 0.97%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 0.97%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 0.97%   |
| Intel Core i7-5600U CPU @ 2.60GHz               | 1         | 0.97%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz              | 1         | 0.97%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz              | 1         | 0.97%   |
| Intel Core i7-3770 CPU @ 3.40GHz                | 1         | 0.97%   |
| Intel Core i7-3687U CPU @ 2.10GHz               | 1         | 0.97%   |
| Intel Core i7-3615QM CPU @ 2.30GHz              | 1         | 0.97%   |
| Intel Core i7-10870H CPU @ 2.20GHz              | 1         | 0.97%   |
| Intel Core i7-10700 CPU @ 2.90GHz               | 1         | 0.97%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz              | 1         | 0.97%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 1         | 0.97%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 1         | 0.97%   |
| Intel Core i5-5257U CPU @ 2.70GHz               | 1         | 0.97%   |
| Intel Core i5-3427U CPU @ 1.80GHz               | 1         | 0.97%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 1         | 0.97%   |
| Intel Core i5-10400 CPU @ 2.90GHz               | 1         | 0.97%   |
| Intel Atom CPU E3827 @ 1.74GHz                  | 1         | 0.97%   |
| Intel 11th Gen Core i7-11850H @ 2.50GHz         | 1         | 0.97%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz          | 1         | 0.97%   |
| ARM Cortex-A53 r0p4                             | 1         | 0.97%   |
| ARM ARM1176 r0p7 (ECO: 0x00000000)              | 1         | 0.97%   |
| AMD Ryzen Threadripper 1950X 16-Core Processor  | 1         | 0.97%   |
| AMD Ryzen Embedded V1202B with Radeon Vega Gfx  | 1         | 0.97%   |
| AMD Ryzen 9 5950X 16-Core Processor             | 1         | 0.97%   |
| AMD Ryzen 9 5900X 12-Core Processor             | 1         | 0.97%   |
| AMD Ryzen 9 3950X 16-Core Processor             | 1         | 0.97%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics      | 1         | 0.97%   |
| AMD Ryzen 7 5800X 8-Core Processor              | 1         | 0.97%   |
| AMD Ryzen 7 5700U with Radeon Graphics          | 1         | 0.97%   |
| AMD Ryzen 7 4800U with Radeon Graphics          | 1         | 0.97%   |
| AMD Ryzen 7 2700X Eight-Core Processor          | 1         | 0.97%   |
| AMD Ryzen 5 5500U with Radeon Graphics          | 1         | 0.97%   |
| AMD Ryzen 5 4600H with Radeon Graphics          | 1         | 0.97%   |
| AMD Ryzen 5 2600X Six-Core Processor            | 1         | 0.97%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 25        | 24.51%  |
| Other                  | 18        | 17.65%  |
| Intel Core i5          | 13        | 12.75%  |
| AMD Ryzen 5            | 11        | 10.78%  |
| AMD Ryzen 7            | 8         | 7.84%   |
| ARM Cortex             | 7         | 6.86%   |
| AMD Ryzen 9            | 5         | 4.9%    |
| Intel Xeon             | 3         | 2.94%   |
| AMD Ryzen 7 PRO        | 3         | 2.94%   |
| AMD Ryzen 5 PRO        | 2         | 1.96%   |
| Intel Pentium M        | 1         | 0.98%   |
| Intel Atom             | 1         | 0.98%   |
| AMD Ryzen Threadripper | 1         | 0.98%   |
| AMD Ryzen Embedded     | 1         | 0.98%   |
| AMD Ryzen 3            | 1         | 0.98%   |
| AMD FX                 | 1         | 0.98%   |
| AMD E                  | 1         | 0.98%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 22        | 21.57%  |
| 8       | 16        | 15.69%  |
| Unknown | 16        | 15.69%  |
| 2       | 15        | 14.71%  |
| 6       | 10        | 9.8%    |
| 16      | 8         | 7.84%   |
| 12      | 8         | 7.84%   |
| 32      | 3         | 2.94%   |
| 24      | 3         | 2.94%   |
| 1       | 1         | 0.98%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 89        | 87.25%  |
| Unknown | 12        | 11.76%  |
| 2       | 1         | 0.98%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 49        | 48.04%  |
| 1       | 36        | 35.29%  |
| Unknown | 17        | 16.67%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 21.57%  |
| KabyLake   | 13        | 12.75%  |
| CometLake  | 11        | 10.78%  |
| Zen 2      | 10        | 9.8%    |
| Zen+       | 9         | 8.82%   |
| IvyBridge  | 9         | 8.82%   |
| Zen 3      | 7         | 6.86%   |
| TigerLake  | 6         | 5.88%   |
| Zen        | 4         | 3.92%   |
| Broadwell  | 3         | 2.94%   |
| Haswell    | 2         | 1.96%   |
| Skylake    | 1         | 0.98%   |
| Silvermont | 1         | 0.98%   |
| Piledriver | 1         | 0.98%   |
| P6         | 1         | 0.98%   |
| IceLake    | 1         | 0.98%   |
| Bobcat     | 1         | 0.98%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 44        | 40.37%  |
| AMD                        | 32        | 29.36%  |
| Nvidia                     | 30        | 27.52%  |
| Matrox Electronics Systems | 2         | 1.83%   |
| ASPEED Technology          | 1         | 0.92%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                               | 7         | 6.31%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                | 6         | 5.41%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]     | 6         | 5.41%   |
| Intel CometLake-U GT2 [UHD Graphics]                                     | 5         | 4.5%    |
| Intel 3rd Gen Core processor Graphics Controller                         | 5         | 4.5%    |
| Intel CometLake-H GT2 [UHD Graphics]                                     | 4         | 3.6%    |
| AMD Cezanne                                                              | 4         | 3.6%    |
| Nvidia TU117M                                                            | 3         | 2.7%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                 | 3         | 2.7%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                | 3         | 2.7%    |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                 | 3         | 2.7%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]         | 3         | 2.7%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                               | 2         | 1.8%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                               | 2         | 1.8%    |
| Nvidia GP108M [GeForce MX230]                                            | 2         | 1.8%    |
| Nvidia GP108 [GeForce GT 1030]                                           | 2         | 1.8%    |
| Nvidia GK208B [GeForce GT 710]                                           | 2         | 1.8%    |
| Intel HD Graphics 620                                                    | 2         | 1.8%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller              | 2         | 1.8%    |
| AMD Lucienne                                                             | 2         | 1.8%    |
| Nvidia TU117M [GeForce MX450]                                            | 1         | 0.9%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                  | 1         | 0.9%    |
| Nvidia TU104GLM [Quadro RTX 5000 Mobile / Max-Q]                         | 1         | 0.9%    |
| Nvidia GT218 [GeForce 210]                                               | 1         | 0.9%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                               | 1         | 0.9%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                  | 1         | 0.9%    |
| Nvidia GP107GL [Quadro P620]                                             | 1         | 0.9%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                       | 1         | 0.9%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                      | 1         | 0.9%    |
| Nvidia GM206 [GeForce GTX 960]                                           | 1         | 0.9%    |
| Nvidia GM108M [GeForce MX130]                                            | 1         | 0.9%    |
| Nvidia GM108M [GeForce 940MX]                                            | 1         | 0.9%    |
| Nvidia GM107M [GeForce GTX 860M]                                         | 1         | 0.9%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                        | 1         | 0.9%    |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                              | 1         | 0.9%    |
| Nvidia GK107GLM [Quadro K1100M]                                          | 1         | 0.9%    |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                          | 1         | 0.9%    |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)        | 1         | 0.9%    |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller | 1         | 0.9%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                               | 1         | 0.9%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                     | 1         | 0.9%    |
| Intel Skylake GT2 [HD Graphics 520]                                      | 1         | 0.9%    |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                | 1         | 0.9%    |
| Intel JasperLake [UHD Graphics]                                          | 1         | 0.9%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                   | 1         | 0.9%    |
| Intel Iris Plus Graphics G7                                              | 1         | 0.9%    |
| Intel Iris Graphics 6100                                                 | 1         | 0.9%    |
| Intel HD Graphics 630                                                    | 1         | 0.9%    |
| Intel HD Graphics 5500                                                   | 1         | 0.9%    |
| Intel Comet Lake-H WS GT2 Integrated UHD Graphics Controller             | 1         | 0.9%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                | 1         | 0.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display             | 1         | 0.9%    |
| Intel 82852/855GM Integrated Graphics Device                             | 1         | 0.9%    |
| ASPEED Technology ASPEED Graphics Family                                 | 1         | 0.9%    |
| AMD Wrestler [Radeon HD 6320]                                            | 1         | 0.9%    |
| AMD VanGogh [AMD Custom GPU 0405]                                        | 1         | 0.9%    |
| AMD RV630 XT [Radeon HD 2600 XT]                                         | 1         | 0.9%    |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]    | 1         | 0.9%    |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                           | 1         | 0.9%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                  | 1         | 0.9%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 27        | 26.21%  |
| 1 x Intel      | 24        | 23.3%   |
| Intel + Nvidia | 18        | 17.48%  |
| Other          | 15        | 14.56%  |
| 1 x Nvidia     | 12        | 11.65%  |
| 2 x AMD        | 2         | 1.94%   |
| 1 x Matrox     | 2         | 1.94%   |
| Intel + AMD    | 1         | 0.97%   |
| 1 x ASPEED     | 1         | 0.97%   |
| AMD + Nvidia   | 1         | 0.97%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 66        | 65.35%  |
| Proprietary | 20        | 19.8%   |
| Unknown     | 15        | 14.85%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 75        | 72.82%  |
| 1.01-2.0   | 10        | 9.71%   |
| 0.51-1.0   | 6         | 5.83%   |
| 0.01-0.5   | 5         | 4.85%   |
| 3.01-4.0   | 4         | 3.88%   |
| 7.01-8.0   | 1         | 0.97%   |
| 5.01-6.0   | 1         | 0.97%   |
| 2.01-3.0   | 1         | 0.97%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| BOE                 | 12        | 15.58%  |
| LG Display          | 10        | 12.99%  |
| AU Optronics        | 9         | 11.69%  |
| Dell                | 5         | 6.49%   |
| Philips             | 4         | 5.19%   |
| Hewlett-Packard     | 4         | 5.19%   |
| Goldstar            | 4         | 5.19%   |
| Chimei Innolux      | 4         | 5.19%   |
| Samsung Electronics | 3         | 3.9%    |
| RTK                 | 2         | 2.6%    |
| LG Electronics      | 2         | 2.6%    |
| Lenovo              | 2         | 2.6%    |
| Apple               | 2         | 2.6%    |
| ViewSonic           | 1         | 1.3%    |
| Sony                | 1         | 1.3%    |
| Sharp               | 1         | 1.3%    |
| SDC                 | 1         | 1.3%    |
| PANDA               | 1         | 1.3%    |
| LGD                 | 1         | 1.3%    |
| InfoVision          | 1         | 1.3%    |
| Iiyama              | 1         | 1.3%    |
| HJW                 | 1         | 1.3%    |
| Eizo                | 1         | 1.3%    |
| CSO                 | 1         | 1.3%    |
| BenQ                | 1         | 1.3%    |
| AOC                 | 1         | 1.3%    |
| Unknown             | 1         | 1.3%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0258 1600x900 350x190mm 15.7-inch            | 3         | 3.8%    |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                  | 3         | 3.8%    |
| RTK WCS Display RTK1A1B 1920x1080 344x195mm 15.6-inch                  | 2         | 2.53%   |
| Philips LCD Monitor PHL08C3 1920x1080 600x340mm 27.2-inch              | 2         | 2.53%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch           | 2         | 2.53%   |
| ViewSonic LCD Monitor VSCD22B 1920x1080 520x290mm 23.4-inch            | 1         | 1.27%   |
| Sony TV SNY4B03 1920x1080 930x520mm 41.9-inch                          | 1         | 1.27%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 380x210mm 17.1-inch                | 1         | 1.27%   |
| SDC LCD Monitor 3520x1080                                              | 1         | 1.27%   |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                       | 1         | 1.27%   |
| Samsung Electronics LCD Monitor SDC3754 1600x900 380x210mm 17.1-inch   | 1         | 1.27%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1020x570mm 46.0-inch | 1         | 1.27%   |
| Philips PHL 273V7 PHLC156 1920x1080 600x340mm 27.2-inch                | 1         | 1.27%   |
| Philips LCD Monitor 271P4 3520x1080                                    | 1         | 1.27%   |
| Philips LCD Monitor 271P4                                              | 1         | 1.27%   |
| PANDA LCD Monitor NCP004F 1920x1080 310x170mm 13.9-inch                | 1         | 1.27%   |
| LGD LCD Monitor 1920x1080                                              | 1         | 1.27%   |
| LG Electronics LCD Monitor LX20D 1600x1200                             | 1         | 1.27%   |
| LG Electronics LCD Monitor LG Ultra HD 11520x2160                      | 1         | 1.27%   |
| LG Electronics LCD Monitor LG Ultra HD                                 | 1         | 1.27%   |
| LG Display LCD Monitor LGD062E 1920x1080 340x190mm 15.3-inch           | 1         | 1.27%   |
| LG Display LCD Monitor LGD060A 1920x1080 290x170mm 13.2-inch           | 1         | 1.27%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch           | 1         | 1.27%   |
| LG Display LCD Monitor LGD05F1 1920x1080 310x170mm 13.9-inch           | 1         | 1.27%   |
| LG Display LCD Monitor LGD033E 1366x768 310x170mm 13.9-inch            | 1         | 1.27%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                  | 1         | 1.27%   |
| Lenovo LEN P44w-10 LEN61D5 3840x1200 1050x330mm 43.3-inch              | 1         | 1.27%   |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch           | 1         | 1.27%   |
| Iiyama PL2474H IVM6146 1920x1080 520x290mm 23.4-inch                   | 1         | 1.27%   |
| HJW HDMI TO USB HJW0001 1920x1080 700x390mm 31.5-inch                  | 1         | 1.27%   |
| Hewlett-Packard LCD Monitor LA2306 3520x1080                           | 1         | 1.27%   |
| Hewlett-Packard LA2306 HWP2949 1920x1080 510x290mm 23.1-inch           | 1         | 1.27%   |
| Hewlett-Packard E242 HWP326E 1920x1200 520x320mm 24.0-inch             | 1         | 1.27%   |
| Hewlett-Packard E233 HPN345F 1920x1080 510x290mm 23.1-inch             | 1         | 1.27%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch             | 1         | 1.27%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch             | 1         | 1.27%   |
| Goldstar 27GK750F GSM770F 1920x1080 600x340mm 27.2-inch                | 1         | 1.27%   |
| Goldstar 23EA53 GSM59A8 1920x1080 510x290mm 23.1-inch                  | 1         | 1.27%   |
| Eizo FX2431 ENC2036 1920x1200 520x330mm 24.2-inch                      | 1         | 1.27%   |
| Dell U2718Q DELA0EC 3840x2160 610x350mm 27.7-inch                      | 1         | 1.27%   |
| Dell U2518D DEL413C 2560x1440 550x310mm 24.9-inch                      | 1         | 1.27%   |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                      | 1         | 1.27%   |
| Dell LCD Monitor U2715H 2560x1440                                      | 1         | 1.27%   |
| Dell LCD Monitor DEL9408 1920x1080 520x290mm 23.4-inch                 | 1         | 1.27%   |
| CSO LCD Monitor CSO1500 3840x2160 340x190mm 15.3-inch                  | 1         | 1.27%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 280x180mm 13.1-inch       | 1         | 1.27%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 340x190mm 15.3-inch       | 1         | 1.27%   |
| Chimei Innolux LCD Monitor CMN1484 1600x900 310x170mm 13.9-inch        | 1         | 1.27%   |
| Chimei Innolux LCD Monitor CMN13A2 1920x1080 290x170mm 13.2-inch       | 1         | 1.27%   |
| BOE LCD Monitor BOE0982 3840x2160 310x170mm 13.9-inch                  | 1         | 1.27%   |
| BOE LCD Monitor BOE0928 1920x1080 340x190mm 15.3-inch                  | 1         | 1.27%   |
| BOE LCD Monitor BOE08D7 1920x1080 310x170mm 13.9-inch                  | 1         | 1.27%   |
| BOE LCD Monitor BOE084D 1920x1080 340x190mm 15.3-inch                  | 1         | 1.27%   |
| BOE LCD Monitor BOE07F1 1920x1080 340x190mm 15.3-inch                  | 1         | 1.27%   |
| BOE LCD Monitor BOE07BB 1920x1080 310x170mm 13.9-inch                  | 1         | 1.27%   |
| BOE LCD Monitor BOE0792 1920x1080 340x190mm 15.3-inch                  | 1         | 1.27%   |
| BOE LCD Monitor BOE075A 1366x768 310x170mm 13.9-inch                   | 1         | 1.27%   |
| BOE LCD Monitor BOE0747 1920x1080 340x190mm 15.3-inch                  | 1         | 1.27%   |
| BenQ GW2280 BNQ78E8 1920x1080 480x270mm 21.7-inch                      | 1         | 1.27%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 340x190mm 15.3-inch         | 1         | 1.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 43        | 56.58%  |
| 3840x2160 (4K)    | 6         | 7.89%   |
| 1600x900 (HD+)    | 6         | 7.89%   |
| 1920x1200 (WUXGA) | 4         | 5.26%   |
| 2560x1440 (QHD)   | 3         | 3.95%   |
| 2256x1504         | 3         | 3.95%   |
| 2560x1600         | 2         | 2.63%   |
| 1366x768 (WXGA)   | 2         | 2.63%   |
| Unknown           | 2         | 2.63%   |
| 3840x1200         | 1         | 1.32%   |
| 3520x1080         | 1         | 1.32%   |
| 2160x1440         | 1         | 1.32%   |
| 1600x1200         | 1         | 1.32%   |
| 11520x2160        | 1         | 1.32%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 22        | 29.33%  |
| 15      | 16        | 21.33%  |
| 27      | 7         | 9.33%   |
| Unknown | 7         | 9.33%   |
| 23      | 6         | 8%      |
| 24      | 5         | 6.67%   |
| 17      | 3         | 4%      |
| 12      | 2         | 2.67%   |
| 46      | 1         | 1.33%   |
| 43      | 1         | 1.33%   |
| 41      | 1         | 1.33%   |
| 32      | 1         | 1.33%   |
| 31      | 1         | 1.33%   |
| 22      | 1         | 1.33%   |
| 21      | 1         | 1.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 29        | 39.19%  |
| 501-600     | 16        | 21.62%  |
| 201-300     | 11        | 14.86%  |
| Unknown     | 7         | 9.46%   |
| 351-400     | 3         | 4.05%   |
| 601-700     | 2         | 2.7%    |
| 401-500     | 2         | 2.7%    |
| 1001-1500   | 2         | 2.7%    |
| 701-800     | 1         | 1.35%   |
| 901-1000    | 1         | 1.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 51        | 75%     |
| 16/10   | 7         | 10.29%  |
| Unknown | 6         | 8.82%   |
| 3/2     | 3         | 4.41%   |
| 3.18    | 1         | 1.47%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 18        | 24%     |
| 91-100         | 11        | 14.67%  |
| 201-250        | 9         | 12%     |
| 301-350        | 7         | 9.33%   |
| Unknown        | 7         | 9.33%   |
| 101-110        | 5         | 6.67%   |
| 71-80          | 4         | 5.33%   |
| 251-300        | 4         | 5.33%   |
| 121-130        | 3         | 4%      |
| 501-1000       | 3         | 4%      |
| 61-70          | 2         | 2.67%   |
| 351-500        | 2         | 2.67%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 25        | 34.25%  |
| 51-100        | 18        | 24.66%  |
| 161-240       | 13        | 17.81%  |
| 101-120       | 7         | 9.59%   |
| Unknown       | 7         | 9.59%   |
| More than 240 | 2         | 2.74%   |
| 1-50          | 1         | 1.37%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 55        | 52.88%  |
| 0     | 39        | 37.5%   |
| 2     | 9         | 8.65%   |
| 3     | 1         | 0.96%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 69        | 45.7%   |
| Realtek Semiconductor           | 45        | 29.8%   |
| TP-Link                         | 6         | 3.97%   |
| Broadcom                        | 6         | 3.97%   |
| Ralink Technology               | 4         | 2.65%   |
| Qualcomm Atheros                | 4         | 2.65%   |
| Hewlett-Packard                 | 4         | 2.65%   |
| Edimax Technology               | 2         | 1.32%   |
| D-Link System                   | 2         | 1.32%   |
| Qualcomm Atheros Communications | 1         | 0.66%   |
| Mellanox Technologies           | 1         | 0.66%   |
| Lenovo                          | 1         | 0.66%   |
| Google                          | 1         | 0.66%   |
| Emulex                          | 1         | 0.66%   |
| BUFFALO                         | 1         | 0.66%   |
| ASUSTek Computer                | 1         | 0.66%   |
| Arduino SA                      | 1         | 0.66%   |
| Aquantia                        | 1         | 0.66%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 37        | 19.79%  |
| Intel Wi-Fi 6 AX200                                                           | 10        | 5.35%   |
| Intel Wireless-AC 9260                                                        | 6         | 3.21%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 6         | 3.21%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6         | 3.21%   |
| Intel Wireless 8265 / 8275                                                    | 5         | 2.67%   |
| Intel I211 Gigabit Network Connection                                         | 5         | 2.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 5         | 2.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 5         | 2.67%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 4         | 2.14%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 4         | 2.14%   |
| Intel Wi-Fi 6 AX201                                                           | 4         | 2.14%   |
| Intel I210 Gigabit Network Connection                                         | 4         | 2.14%   |
| HP hs2350 HSPA+ Mobile Broadband Module Network Adapter                       | 4         | 2.14%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 3         | 1.6%    |
| Realtek RTL8125 2.5GbE Controller                                             | 3         | 1.6%    |
| Intel Ethernet Controller I225-V                                              | 3         | 1.6%    |
| Intel Ethernet Connection (14) I219-LM                                        | 3         | 1.6%    |
| Intel 82574L Gigabit Network Connection                                       | 3         | 1.6%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 1.07%   |
| Ralink MT7601U Wireless Adapter                                               | 2         | 1.07%   |
| Intel Wireless 7265                                                           | 2         | 1.07%   |
| Intel Wireless 7260                                                           | 2         | 1.07%   |
| Intel Ethernet Connection (4) I219-LM                                         | 2         | 1.07%   |
| Intel Ethernet Connection (11) I219-LM                                        | 2         | 1.07%   |
| Intel Ethernet Connection (10) I219-V                                         | 2         | 1.07%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2         | 1.07%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]    | 2         | 1.07%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1         | 0.53%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]           | 1         | 0.53%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                      | 1         | 0.53%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.53%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                        | 1         | 0.53%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1         | 0.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 0.53%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 0.53%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1         | 0.53%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1         | 0.53%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 1         | 0.53%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 1         | 0.53%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1         | 0.53%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1         | 0.53%   |
| Mellanox MT27710 Family [ConnectX-4 Lx]                                       | 1         | 0.53%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                              | 1         | 0.53%   |
| Intel Wireless 8260                                                           | 1         | 0.53%   |
| Intel Wi-Fi 6 AX201 160MHz                                                    | 1         | 0.53%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 0.53%   |
| Intel I350 Gigabit Network Connection                                         | 1         | 0.53%   |
| Intel Ethernet Controller I225-LM                                             | 1         | 0.53%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 1         | 0.53%   |
| Intel Ethernet Connection I219-LM                                             | 1         | 0.53%   |
| Intel Ethernet Connection I217-LM                                             | 1         | 0.53%   |
| Intel Ethernet Connection (7) I219-V                                          | 1         | 0.53%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1         | 0.53%   |
| Intel Ethernet Connection (5) I219-V                                          | 1         | 0.53%   |
| Intel Ethernet Connection (3) I218-LM                                         | 1         | 0.53%   |
| Intel Ethernet Connection (13) I219-V                                         | 1         | 0.53%   |
| Intel Ethernet Connection (11) I219-V                                         | 1         | 0.53%   |
| Intel Centrino Advanced-N 6235                                                | 1         | 0.53%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller             | 1         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 55        | 62.5%   |
| Realtek Semiconductor           | 8         | 9.09%   |
| TP-Link                         | 6         | 6.82%   |
| Broadcom                        | 5         | 5.68%   |
| Ralink Technology               | 4         | 4.55%   |
| Qualcomm Atheros                | 3         | 3.41%   |
| Edimax Technology               | 2         | 2.27%   |
| D-Link System                   | 2         | 2.27%   |
| Qualcomm Atheros Communications | 1         | 1.14%   |
| BUFFALO                         | 1         | 1.14%   |
| ASUSTek Computer                | 1         | 1.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                           | 10        | 11.36%  |
| Intel Wireless-AC 9260                                                        | 6         | 6.82%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 6         | 6.82%   |
| Intel Wireless 8265 / 8275                                                    | 5         | 5.68%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 5         | 5.68%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 5         | 5.68%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 4         | 4.55%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 4         | 4.55%   |
| Intel Wi-Fi 6 AX201                                                           | 4         | 4.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 3         | 3.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 2.27%   |
| Ralink MT7601U Wireless Adapter                                               | 2         | 2.27%   |
| Intel Wireless 7265                                                           | 2         | 2.27%   |
| Intel Wireless 7260                                                           | 2         | 2.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2         | 2.27%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]    | 2         | 2.27%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1         | 1.14%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]           | 1         | 1.14%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                      | 1         | 1.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.14%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                        | 1         | 1.14%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 1.14%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1         | 1.14%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1         | 1.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 1         | 1.14%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 1         | 1.14%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1         | 1.14%   |
| Intel Wireless 8260                                                           | 1         | 1.14%   |
| Intel Wi-Fi 6 AX201 160MHz                                                    | 1         | 1.14%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 1.14%   |
| Intel Centrino Advanced-N 6235                                                | 1         | 1.14%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                | 1         | 1.14%   |
| Edimax EW-7711MAC 802.11ac Wireless Adapter                                   | 1         | 1.14%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]                      | 1         | 1.14%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                   | 1         | 1.14%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 1         | 1.14%   |
| Broadcom BCM4331 802.11a/b/g/n                                                | 1         | 1.14%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 1         | 1.14%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 1         | 1.14%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                                           | 1         | 1.14%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 41        | 46.59%  |
| Intel                 | 40        | 45.45%  |
| Broadcom              | 2         | 2.27%   |
| Qualcomm Atheros      | 1         | 1.14%   |
| Lenovo                | 1         | 1.14%   |
| Google                | 1         | 1.14%   |
| Emulex                | 1         | 1.14%   |
| Aquantia              | 1         | 1.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 37        | 40.22%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6         | 6.52%   |
| Intel I211 Gigabit Network Connection                                         | 5         | 5.43%   |
| Intel I210 Gigabit Network Connection                                         | 4         | 4.35%   |
| Realtek RTL8125 2.5GbE Controller                                             | 3         | 3.26%   |
| Intel Ethernet Controller I225-V                                              | 3         | 3.26%   |
| Intel Ethernet Connection (14) I219-LM                                        | 3         | 3.26%   |
| Intel 82574L Gigabit Network Connection                                       | 3         | 3.26%   |
| Intel Ethernet Connection (4) I219-LM                                         | 2         | 2.17%   |
| Intel Ethernet Connection (11) I219-LM                                        | 2         | 2.17%   |
| Intel Ethernet Connection (10) I219-V                                         | 2         | 2.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1         | 1.09%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 1.09%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1         | 1.09%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                              | 1         | 1.09%   |
| Intel I350 Gigabit Network Connection                                         | 1         | 1.09%   |
| Intel Ethernet Controller I225-LM                                             | 1         | 1.09%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 1         | 1.09%   |
| Intel Ethernet Connection I219-LM                                             | 1         | 1.09%   |
| Intel Ethernet Connection I217-LM                                             | 1         | 1.09%   |
| Intel Ethernet Connection (7) I219-V                                          | 1         | 1.09%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1         | 1.09%   |
| Intel Ethernet Connection (5) I219-V                                          | 1         | 1.09%   |
| Intel Ethernet Connection (3) I218-LM                                         | 1         | 1.09%   |
| Intel Ethernet Connection (13) I219-V                                         | 1         | 1.09%   |
| Intel Ethernet Connection (11) I219-V                                         | 1         | 1.09%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 1.09%   |
| Google Nexus/Pixel Device (charging + debug)                                  | 1         | 1.09%   |
| Emulex OneConnect 10Gb NIC (be3)                                              | 1         | 1.09%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                             | 1         | 1.09%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 1         | 1.09%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 1         | 1.09%   |
| Unknown                                                                       | 1         | 1.09%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 80        | 50.63%  |
| WiFi     | 71        | 44.94%  |
| Modem    | 6         | 3.8%    |
| Unknown  | 1         | 0.63%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 69        | 60.53%  |
| WiFi     | 42        | 36.84%  |
| Modem    | 3         | 2.63%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 56        | 55.45%  |
| 1     | 22        | 21.78%  |
| 0     | 13        | 12.87%  |
| 3     | 7         | 6.93%   |
| 4     | 2         | 1.98%   |
| 7     | 1         | 0.99%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 85        | 80.19%  |
| Yes  | 21        | 19.81%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 41        | 77.36%  |
| Apple                           | 4         | 7.55%   |
| Realtek Semiconductor           | 2         | 3.77%   |
| IMC Networks                    | 2         | 3.77%   |
| Realtek                         | 1         | 1.89%   |
| Qualcomm Atheros Communications | 1         | 1.89%   |
| Cambridge Silicon Radio         | 1         | 1.89%   |
| Broadcom                        | 1         | 1.89%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 12        | 22.64%  |
| Intel AX200 Bluetooth                               | 9         | 16.98%  |
| Intel Bluetooth wireless interface                  | 7         | 13.21%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 5         | 9.43%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 7.55%   |
| Intel AX210 Bluetooth                               | 3         | 5.66%   |
| Apple Bluetooth Host Controller                     | 2         | 3.77%   |
| Realtek  Bluetooth Adapter                          | 1         | 1.89%   |
| Realtek Bluetooth Radio                             | 1         | 1.89%   |
| Realtek Bluetooth Radio                             | 1         | 1.89%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.89%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.89%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.89%   |
| IMC Networks Bluetooth module                       | 1         | 1.89%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.89%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.89%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 1.89%   |
| Apple Apple Broadcom Built-in Bluetooth             | 1         | 1.89%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 49        | 39.52%  |
| AMD                     | 39        | 31.45%  |
| Nvidia                  | 24        | 19.35%  |
| Lenovo                  | 3         | 2.42%   |
| Yamaha                  | 1         | 0.81%   |
| SteelSeries ApS         | 1         | 0.81%   |
| Logitech                | 1         | 0.81%   |
| GN Netcom               | 1         | 0.81%   |
| Generalplus Technology  | 1         | 0.81%   |
| CMX Systems             | 1         | 0.81%   |
| C-Media Electronics     | 1         | 0.81%   |
| AudioQuest              | 1         | 0.81%   |
| AKAI  Professional M.I. | 1         | 0.81%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 21        | 13.73%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 11        | 7.19%   |
| Intel Comet Lake PCH cAVS                                                  | 9         | 5.88%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9         | 5.88%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 9         | 5.88%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 3.92%   |
| AMD Starship/Matisse HD Audio Controller                                   | 6         | 3.92%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5         | 3.27%   |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 3.27%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4         | 2.61%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 2.61%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4         | 2.61%   |
| Intel Sunrise Point-LP HD Audio                                            | 3         | 1.96%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 3         | 1.96%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 1.31%   |
| Nvidia GP108 High Definition Audio Controller                              | 2         | 1.31%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 1.31%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 1.31%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 1.31%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 1.31%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 1.31%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 1.31%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 1.31%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2         | 1.31%   |
| AMD Navi 10 HDMI Audio                                                     | 2         | 1.31%   |
| Yamaha Steinberg UR12                                                      | 1         | 0.65%   |
| SteelSeries ApS SteelSeries Siberia 350                                    | 1         | 0.65%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.65%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 0.65%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.65%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.65%   |
| Nvidia GM206 High Definition Audio Controller                              | 1         | 0.65%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.65%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 0.65%   |
| Logitech H390 headset with microphone                                      | 1         | 0.65%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                   | 1         | 0.65%   |
| Lenovo ThinkPad Dock Audio                                                 | 1         | 0.65%   |
| Lenovo Realtek USB Audio                                                   | 1         | 0.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 0.65%   |
| Intel Jasper Lake HD Audio                                                 | 1         | 0.65%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 0.65%   |
| Intel CM238 HD Audio Controller                                            | 1         | 0.65%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 0.65%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 0.65%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 1         | 0.65%   |
| GN Netcom Jabra SPEAK 410 USB                                              | 1         | 0.65%   |
| Generalplus Technology USB Audio Device                                    | 1         | 0.65%   |
| CMX Systems USB PnP Audio Device                                           | 1         | 0.65%   |
| C-Media Electronics Anua Mic CM 900                                        | 1         | 0.65%   |
| AudioQuest DragonFly                                                       | 1         | 0.65%   |
| AMD Wrestler HDMI Audio                                                    | 1         | 0.65%   |
| AMD RV630 HDMI Audio [Radeon HD 2600 PRO/XT / HD 3610]                     | 1         | 0.65%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 1         | 0.65%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1         | 0.65%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1         | 0.65%   |
| AKAI  Professional M.I. LPK25 MIDI Keyboard                                | 1         | 0.65%   |
| Unknown                                                                    | 1         | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 21        | 21.21%  |
| SK hynix               | 15        | 15.15%  |
| Micron Technology      | 15        | 15.15%  |
| Kingston               | 11        | 11.11%  |
| Crucial                | 8         | 8.08%   |
| Corsair                | 5         | 5.05%   |
| Unknown                | 4         | 4.04%   |
| Smart                  | 3         | 3.03%   |
| Ramaxel Technology     | 3         | 3.03%   |
| Team                   | 2         | 2.02%   |
| Goodram                | 2         | 2.02%   |
| Unknown                | 2         | 2.02%   |
| Unknown (000000000C01) | 1         | 1.01%   |
| Transcend              | 1         | 1.01%   |
| PNY                    | 1         | 1.01%   |
| KLEVV                  | 1         | 1.01%   |
| Gold Key               | 1         | 1.01%   |
| G.Skill                | 1         | 1.01%   |
| A-DATA Technology      | 1         | 1.01%   |
| 06F100000C01           | 1         | 1.01%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s        | 4         | 3.96%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 1.98%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 2         | 1.98%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s       | 2         | 1.98%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 2         | 1.98%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s        | 2         | 1.98%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s        | 2         | 1.98%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s         | 2         | 1.98%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s         | 2         | 1.98%   |
| Crucial RAM BL32G32C16S4B.M16FB1 32GB SODIMM DDR4 2667MT/s   | 2         | 1.98%   |
| Corsair RAM CMK32GX4M2D3200C16 16GB DIMM DDR4 3200MT/s       | 2         | 1.98%   |
| Unknown                                                      | 2         | 1.98%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                    | 1         | 0.99%   |
| Unknown RAM Module 1GB SODIMM DDR                            | 1         | 0.99%   |
| Unknown RAM 3000 C16 Series 4096MB DIMM DDR4 2933MT/s        | 1         | 0.99%   |
| Unknown RAM 2G-08-10-12-1333 2GB DIMM DDR3 1333MT/s          | 1         | 0.99%   |
| Unknown (000000000C01) RAM Module 32GB DIMM DDR4 3200MT/s    | 1         | 0.99%   |
| Transcend RAM JM2666HLE-32G 32GB DIMM DDR4 2666MT/s          | 1         | 0.99%   |
| Team RAM TEAMGROUP-UD4-4133 8GB DIMM DDR4 4133MT/s           | 1         | 0.99%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s        | 1         | 0.99%   |
| Smart RAM SF4641G8CK8IWGKSEG 8GB SODIMM DDR4 2133MT/s        | 1         | 0.99%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s        | 1         | 0.99%   |
| Smart RAM Module 8GB DIMM DDR4 2667MT/s                      | 1         | 0.99%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1867MT/s                 | 1         | 0.99%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                 | 1         | 0.99%   |
| SK hynix RAM HMAA4GU6CJR8N-XN 32GB DIMM DDR4 3200MT/s        | 1         | 0.99%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s      | 1         | 0.99%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 0.99%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 1         | 0.99%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 0.99%   |
| Samsung RAM M474A4G43AB1-CVF 32GB SODIMM DDR4 2933MT/s       | 1         | 0.99%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s        | 1         | 0.99%   |
| Samsung RAM M471B5674-M0-YK0 4GB Chip DDR3 1600MT/s          | 1         | 0.99%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 1         | 0.99%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s        | 1         | 0.99%   |
| Samsung RAM M471A5244BB0-CWE 4GB SODIMM DDR4 3200MT/s        | 1         | 0.99%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s       | 1         | 0.99%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s       | 1         | 0.99%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s       | 1         | 0.99%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 1         | 0.99%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s  | 1         | 0.99%   |
| Samsung RAM M378A4G43MB1-CTD 32GB DIMM DDR4 2666MT/s         | 1         | 0.99%   |
| Samsung RAM K4EBE304EB-EGCF 8GB Row Of Chips LPDDR3 1867MT/s | 1         | 0.99%   |
| Ramaxel RAM RMSA3320MJ78HAF-3200 8GB SODIMM DDR4 3200MT/s    | 1         | 0.99%   |
| Ramaxel RAM RMSA3300MH78HBF-2666 16GB SODIMM DDR4 2400MT/s   | 1         | 0.99%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s    | 1         | 0.99%   |
| PNY RAM 16GU2X16LIII43-12-K 16GB SODIMM DDR4 2667MT/s        | 1         | 0.99%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                   | 1         | 0.99%   |
| Micron RAM Module 2GB SODIMM DDR3 1600MT/s                   | 1         | 0.99%   |
| Micron RAM Module 16GB DIMM DDR4 2400MT/s                    | 1         | 0.99%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s  | 1         | 0.99%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s        | 1         | 0.99%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s   | 1         | 0.99%   |
| Micron RAM 4ATF1G64HZ-3G2B2 8GB SODIMM DDR4 3200MT/s         | 1         | 0.99%   |
| Micron RAM 18ASF4G72AZ-3G2B1 32GB DIMM DDR4 3200MT/s         | 1         | 0.99%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s        | 1         | 0.99%   |
| Micron RAM 16ATF2G64HZ-2G6J1 16GB SODIMM DDR4 2667MT/s       | 1         | 0.99%   |
| Micron RAM 16ATF2G64AZ-3G2J1 16GB DIMM DDR4 3200MT/s         | 1         | 0.99%   |
| KLEVV RAM KD4AGSA8M-32N220A 16GB SODIMM DDR4 3200MT/s        | 1         | 0.99%   |
| Kingston RAM Module 8GB SODIMM DDR4 2667MT/s                 | 1         | 0.99%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 67        | 77.01%  |
| DDR3   | 16        | 18.39%  |
| LPDDR5 | 1         | 1.15%   |
| LPDDR4 | 1         | 1.15%   |
| LPDDR3 | 1         | 1.15%   |
| DDR    | 1         | 1.15%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 58        | 66.67%  |
| DIMM         | 24        | 27.59%  |
| Row Of Chips | 4         | 4.6%    |
| Chip         | 1         | 1.15%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 35        | 38.89%  |
| 16384 | 27        | 30%     |
| 32768 | 13        | 14.44%  |
| 4096  | 11        | 12.22%  |
| 2048  | 3         | 3.33%   |
| 1024  | 1         | 1.11%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 33        | 36.26%  |
| 2667    | 19        | 20.88%  |
| 1600    | 8         | 8.79%   |
| 1867    | 6         | 6.59%   |
| 2400    | 5         | 5.49%   |
| 2666    | 4         | 4.4%    |
| 2933    | 3         | 3.3%    |
| 2133    | 3         | 3.3%    |
| 1333    | 2         | 2.2%    |
| 4267    | 1         | 1.1%    |
| 4266    | 1         | 1.1%    |
| 4133    | 1         | 1.1%    |
| 3600    | 1         | 1.1%    |
| 3000    | 1         | 1.1%    |
| 1866    | 1         | 1.1%    |
| 1334    | 1         | 1.1%    |
| Unknown | 1         | 1.1%    |

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
| Chicony Electronics                    | 15        | 24.59%  |
| IMC Networks                           | 10        | 16.39%  |
| Realtek Semiconductor                  | 6         | 9.84%   |
| Logitech                               | 6         | 9.84%   |
| Lite-On Technology                     | 5         | 8.2%    |
| Acer                                   | 5         | 8.2%    |
| Sunplus Innovation Technology          | 4         | 6.56%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 4.92%   |
| Microdia                               | 2         | 3.28%   |
| Apple                                  | 2         | 3.28%   |
| Syntek                                 | 1         | 1.64%   |
| GEMBIRD                                | 1         | 1.64%   |
| Aveo Technology                        | 1         | 1.64%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                             | 7         | 11.29%  |
| Chicony Integrated Camera                                                  | 7         | 11.29%  |
| Sunplus Integrated_Webcam_HD                                               | 3         | 4.84%   |
| Logitech Webcam C270                                                       | 3         | 4.84%   |
| Lite-On Integrated Camera                                                  | 3         | 4.84%   |
| Chicony Integrated HP HD Webcam                                            | 3         | 4.84%   |
| Acer Integrated Camera                                                     | 3         | 4.84%   |
| Realtek Laptop Camera                                                      | 2         | 3.23%   |
| Realtek Integrated_Webcam_HD                                               | 2         | 3.23%   |
| Lite-On HP HD Camera                                                       | 2         | 3.23%   |
| Chicony ThinkPad T490 Webcam                                               | 2         | 3.23%   |
| Apple FaceTime HD Camera (Built-in)                                        | 2         | 3.23%   |
| Acer HD Webcam                                                             | 2         | 3.23%   |
| Syntek Lenovo EasyCamera                                                   | 1         | 1.61%   |
| Sunplus Integrated_Webcam_FHD                                              | 1         | 1.61%   |
| Realtek USB 2 Webcam                                                       | 1         | 1.61%   |
| Realtek Realtek USB2.0 PC Camera                                           | 1         | 1.61%   |
| Microdia HP Integrated Webcam                                              | 1         | 1.61%   |
| Microdia Dell Integrated HD Webcam                                         | 1         | 1.61%   |
| Logitech Webcam C170                                                       | 1         | 1.61%   |
| Logitech HD Pro Webcam C920                                                | 1         | 1.61%   |
| Logitech C920 PRO HD Webcam                                                | 1         | 1.61%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 1         | 1.61%   |
| IMC Networks HD Camera                                                     | 1         | 1.61%   |
| IMC Networks EasyCamera                                                    | 1         | 1.61%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]                          | 1         | 1.61%   |
| Chicony USB2.0 0.3M UVC WebCam                                             | 1         | 1.61%   |
| Chicony Integrated IR Camera                                               | 1         | 1.61%   |
| Chicony HD Webcam                                                          | 1         | 1.61%   |
| Chicony Chicony USB2.0 Camera                                              | 1         | 1.61%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 1.61%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed]                | 1         | 1.61%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam   | 1         | 1.61%   |
| Aveo USB2.0 Camera                                                         | 1         | 1.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 9         | 47.37%  |
| Validity Sensors           | 5         | 26.32%  |
| Shenzhen Goodix Technology | 4         | 21.05%  |
| AuthenTec                  | 1         | 5.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


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

![Unsupported Devices](./images/pie_chart_bsd/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 30        | 28.85%  |
| 2     | 27        | 25.96%  |
| 1     | 17        | 16.35%  |
| 4     | 15        | 14.42%  |
| 3     | 10        | 9.62%   |
| 5     | 4         | 3.85%   |
| 9     | 1         | 0.96%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 56        | 36.13%  |
| Bluetooth                | 32        | 20.65%  |
| Net/wireless             | 27        | 17.42%  |
| Fingerprint reader       | 19        | 12.26%  |
| Card reader              | 9         | 5.81%   |
| Sound                    | 5         | 3.23%   |
| Net/ethernet             | 3         | 1.94%   |
| Firewire controller      | 2         | 1.29%   |
| Network                  | 1         | 0.65%   |
| Modem                    | 1         | 0.65%   |

