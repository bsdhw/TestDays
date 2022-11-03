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

Total: 164

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
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

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 87        | 82.86%  |
| arm64 | 14        | 13.33%  |
| arm   | 2         | 1.9%    |
| riscv | 1         | 0.95%   |
| i386  | 1         | 0.95%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KDE5          | 28        | 25.45%  |
| Console       | 25        | 22.73%  |
| XFCE          | 13        | 11.82%  |
| MATE          | 8         | 7.27%   |
| TWM           | 6         | 5.45%   |
| GNOME         | 6         | 5.45%   |
| i3            | 5         | 4.55%   |
| Openbox       | 3         | 2.73%   |
| Cinnamon      | 3         | 2.73%   |
| LXQt          | 2         | 1.82%   |
| LXDE          | 2         | 1.82%   |
| Lumina        | 2         | 1.82%   |
| Xfwm4         | 1         | 0.91%   |
| spectrwm      | 1         | 0.91%   |
| Picom         | 1         | 0.91%   |
| GNUstep       | 1         | 0.91%   |
| Fluxbox       | 1         | 0.91%   |
| Enlightenment | 1         | 0.91%   |
| ctwm          | 1         | 0.91%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 77        | 70.64%  |
| Console | 30        | 27.52%  |
| Wayland | 2         | 1.83%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 49        | 45.37%  |
| SDDM    | 25        | 23.15%  |
| SLiM    | 13        | 12.04%  |
| GDM     | 11        | 10.19%  |
| XDM     | 6         | 5.56%   |
| LightDM | 3         | 2.78%   |
| Ly      | 1         | 0.93%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Computers | Percent |
|------------------|-----------|---------|
| C                | 70        | 65.42%  |
| en_US            | 12        | 11.21%  |
| de_DE            | 5         | 4.67%   |
| Unknown          | 5         | 4.67%   |
| uk_UA            | 3         | 2.8%    |
| zh_CN            | 2         | 1.87%   |
| ru_RU            | 2         | 1.87%   |
| en_GB            | 2         | 1.87%   |
| sv_SE            | 1         | 0.93%   |
| pt_PT            | 1         | 0.93%   |
| pl_PL            | 1         | 0.93%   |
| it_IT.ISO8859-15 | 1         | 0.93%   |
| fr_FR            | 1         | 0.93%   |
| de_CH            | 1         | 0.93%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 93        | 88.57%  |
| BIOS | 12        | 11.43%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 75        | 71.43%  |
| Ufs  | 30        | 28.57%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 96        | 91.43%  |
| MBR  | 9         | 8.57%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 25        | 23.81%  |
| Dell                           | 11        | 10.48%  |
| ASUSTek Computer               | 11        | 10.48%  |
| Unknown                        | 11        | 10.48%  |
| Hewlett-Packard                | 9         | 8.57%   |
| Gigabyte Technology            | 7         | 6.67%   |
| MSI                            | 5         | 4.76%   |
| Raspberry Pi Foundation        | 4         | 3.81%   |
| ASRock                         | 3         | 2.86%   |
| Apple                          | 3         | 2.86%   |
| Intel                          | 2         | 1.9%    |
| Framework                      | 2         | 1.9%    |
| Beckhoff Automation            | 2         | 1.9%    |
| Valve                          | 1         | 0.95%   |
| System76                       | 1         | 0.95%   |
| pine64                         | 1         | 0.95%   |
| Notebook                       | 1         | 0.95%   |
| Matsushita Electric Industrial | 1         | 0.95%   |
| khadas                         | 1         | 0.95%   |
| HUAWEI                         | 1         | 0.95%   |
| friendlyelec                   | 1         | 0.95%   |
| Avell High Performance         | 1         | 0.95%   |
| A-DATA Technology              | 1         | 0.95%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 12        | 11.43%  |
| RPi Raspberry Pi                            | 3         | 2.86%   |
| HP EliteBook 8570p                          | 3         | 2.86%   |
| Framework Laptop                            | 2         | 1.9%    |
| Valve Jupiter                               | 1         | 0.95%   |
| System76 Gazelle                            | 1         | 0.95%   |
| RPi rpi                                     | 1         | 0.95%   |
| pine64 pinebook-pro-rk3399                  | 1         | 0.95%   |
| Notebook NS50_70MU                          | 1         | 0.95%   |
| MSI MS-7C79                                 | 1         | 0.95%   |
| MSI MS-7C75                                 | 1         | 0.95%   |
| MSI MS-7B86                                 | 1         | 0.95%   |
| MSI GE76 Raider 10UG                        | 1         | 0.95%   |
| MSI Bravo 15 A4DDR                          | 1         | 0.95%   |
| Matsushita Electric Industrial CF-T2BW1AXR  | 1         | 0.95%   |
| Lenovo XiaoXinPro-13ARE 2020 82DM           | 1         | 0.95%   |
| Lenovo ThinkPad X395 20NL001SMX             | 1         | 0.95%   |
| Lenovo ThinkPad X395 20NL000GPG             | 1         | 0.95%   |
| Lenovo ThinkPad X270 20HM004JBR             | 1         | 0.95%   |
| Lenovo ThinkPad X260 20F5A28AUK             | 1         | 0.95%   |
| Lenovo ThinkPad X13 Gen 1 20T2003PRT        | 1         | 0.95%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TLA055CD | 1         | 0.95%   |
| Lenovo ThinkPad X1 Extreme 20MF000BUS       | 1         | 0.95%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS1QC00    | 1         | 0.95%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS0BT00    | 1         | 0.95%   |
| Lenovo ThinkPad T495s 20QKS1812F            | 1         | 0.95%   |
| Lenovo ThinkPad T495 20NJ0010PB             | 1         | 0.95%   |
| Lenovo ThinkPad T470p 20J7S0PM00            | 1         | 0.95%   |
| Lenovo ThinkPad T430 2349H2G                | 1         | 0.95%   |
| Lenovo ThinkPad T14s Gen 2i 20WM00B7MX      | 1         | 0.95%   |
| Lenovo ThinkPad P15 Gen 1 20ST005VRT        | 1         | 0.95%   |
| Lenovo ThinkPad P14s Gen 1 20Y1CTO1WW       | 1         | 0.95%   |
| Lenovo ThinkPad E14 Gen 3 20Y7003SGE        | 1         | 0.95%   |
| Lenovo ThinkPad E14 20RBCTO1WW              | 1         | 0.95%   |
| Lenovo ThinkBook 14 G3 ACL 21A2             | 1         | 0.95%   |
| Lenovo Legion 5P 15IMH05H 82AW              | 1         | 0.95%   |
| Lenovo Legion 5 15IMH05 82AU                | 1         | 0.95%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY        | 1         | 0.95%   |
| Lenovo IdeaPad 330-15ARR 81D2               | 1         | 0.95%   |
| khadas edge-v                               | 1         | 0.95%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo ThinkPad                            | 18        | 17.14%  |
| Unknown                                    | 12        | 11.43%  |
| ASUS PRIME                                 | 5         | 4.76%   |
| HP EliteBook                               | 4         | 3.81%   |
| RPi Raspberry                              | 3         | 2.86%   |
| HP ProBook                                 | 3         | 2.86%   |
| Dell OptiPlex                              | 3         | 2.86%   |
| Dell Latitude                              | 3         | 2.86%   |
| Lenovo Legion                              | 2         | 1.9%    |
| Lenovo IdeaPad                             | 2         | 1.9%    |
| Gigabyte X570                              | 2         | 1.9%    |
| Gigabyte B450M                             | 2         | 1.9%    |
| Framework Laptop                           | 2         | 1.9%    |
| Valve Jupiter                              | 1         | 0.95%   |
| System76 Gazelle                           | 1         | 0.95%   |
| RPi rpi                                    | 1         | 0.95%   |
| pine64 pinebook-pro-rk3399                 | 1         | 0.95%   |
| Notebook NS50                              | 1         | 0.95%   |
| MSI MS-7C79                                | 1         | 0.95%   |
| MSI MS-7C75                                | 1         | 0.95%   |
| MSI MS-7B86                                | 1         | 0.95%   |
| MSI GE76                                   | 1         | 0.95%   |
| MSI Bravo                                  | 1         | 0.95%   |
| Matsushita Electric Industrial CF-T2BW1AXR | 1         | 0.95%   |
| Lenovo XiaoXinPro-13ARE                    | 1         | 0.95%   |
| Lenovo ThinkBook                           | 1         | 0.95%   |
| khadas edge-v                              | 1         | 0.95%   |
| Intel S2600WTTR                            | 1         | 0.95%   |
| Intel NUC11PHi7                            | 1         | 0.95%   |
| HUAWEI HN-WX9X                             | 1         | 0.95%   |
| HP ZBook                                   | 1         | 0.95%   |
| HP EliteDesk                               | 1         | 0.95%   |
| Gigabyte X399                              | 1         | 0.95%   |
| Gigabyte B550I                             | 1         | 0.95%   |
| Gigabyte 970A-UD3P                         | 1         | 0.95%   |
| friendlyelec nanopi-m4                     | 1         | 0.95%   |
| Dell Vostro                                | 1         | 0.95%   |
| Dell PowerEdge                             | 1         | 0.95%   |
| Dell Inspiron                              | 1         | 0.95%   |
| Dell G5                                    | 1         | 0.95%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 27        | 25.71%  |
| 2020    | 26        | 24.76%  |
| 2019    | 13        | 12.38%  |
| Unknown | 11        | 10.48%  |
| 2018    | 7         | 6.67%   |
| 2022    | 5         | 4.76%   |
| 2017    | 4         | 3.81%   |
| 2013    | 4         | 3.81%   |
| 2015    | 3         | 2.86%   |
| 2016    | 2         | 1.9%    |
| 2012    | 1         | 0.95%   |
| 2011    | 1         | 0.95%   |
| 2003    | 1         | 0.95%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 56        | 53.33%  |
| Desktop        | 37        | 35.24%  |
| System on chip | 7         | 6.67%   |
| Mini pc        | 2         | 1.9%    |
| Server         | 2         | 1.9%    |
| All in one     | 1         | 0.95%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 104       | 99.05%  |
| Yes  | 1         | 0.95%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 39        | 36.45%  |
| 8.01-16.0       | 20        | 18.69%  |
| 32.01-64.0      | 17        | 15.89%  |
| 64.01-256.0     | 15        | 14.02%  |
| 4.01-8.0        | 9         | 8.41%   |
| 0.51-1.0        | 2         | 1.87%   |
| More than 256.0 | 1         | 0.93%   |
| 3.01-4.0        | 1         | 0.93%   |
| 24.01-32.0      | 1         | 0.93%   |
| 1.01-2.0        | 1         | 0.93%   |
| 0.01-0.5        | 1         | 0.93%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.51-1.0    | 34        | 31.48%  |
| 1.01-2.0    | 29        | 26.85%  |
| 0.01-0.5    | 19        | 17.59%  |
| 2.01-3.0    | 12        | 11.11%  |
| 3.01-4.0    | 5         | 4.63%   |
| 24.01-32.0  | 2         | 1.85%   |
| 0           | 2         | 1.85%   |
| 4.01-8.0    | 1         | 0.93%   |
| 32.01-64.0  | 1         | 0.93%   |
| 64.01-256.0 | 1         | 0.93%   |
| 16.01-24.0  | 1         | 0.93%   |
| 8.01-16.0   | 1         | 0.93%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 52        | 46.43%  |
| 2      | 29        | 25.89%  |
| 0      | 13        | 11.61%  |
| 3      | 7         | 6.25%   |
| 6      | 5         | 4.46%   |
| 4      | 3         | 2.68%   |
| 15     | 1         | 0.89%   |
| 7      | 1         | 0.89%   |
| 5      | 1         | 0.89%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 92        | 85.98%  |
| Yes       | 15        | 14.02%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 82        | 78.1%   |
| No        | 23        | 21.9%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 72        | 68.57%  |
| No        | 33        | 31.43%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 54        | 50.94%  |
| No        | 52        | 49.06%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 19        | 18.1%   |
| UK           | 11        | 10.48%  |
| Russia       | 11        | 10.48%  |
| Germany      | 11        | 10.48%  |
| Brazil       | 6         | 5.71%   |
| Poland       | 5         | 4.76%   |
| Ukraine      | 4         | 3.81%   |
| Japan        | 4         | 3.81%   |
| China        | 4         | 3.81%   |
| Austria      | 4         | 3.81%   |
| Portugal     | 3         | 2.86%   |
| Switzerland  | 2         | 1.9%    |
| Sweden       | 2         | 1.9%    |
| Romania      | 2         | 1.9%    |
| Netherlands  | 2         | 1.9%    |
| Denmark      | 2         | 1.9%    |
| Turkey       | 1         | 0.95%   |
| Spain        | 1         | 0.95%   |
| Singapore    | 1         | 0.95%   |
| Saudi Arabia | 1         | 0.95%   |
| Peru         | 1         | 0.95%   |
| Jamaica      | 1         | 0.95%   |
| Italy        | 1         | 0.95%   |
| India        | 1         | 0.95%   |
| France       | 1         | 0.95%   |
| Croatia      | 1         | 0.95%   |
| Colombia     | 1         | 0.95%   |
| Belarus      | 1         | 0.95%   |
| Bangladesh   | 1         | 0.95%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Moscow                      | 5         | 4.27%   |
| Brighton                    | 5         | 4.27%   |
| St Petersburg               | 3         | 2.56%   |
| Seattle                     | 3         | 2.56%   |
| London                      | 3         | 2.56%   |
| Kyiv                        | 3         | 2.56%   |
| ЕЊta-ku                   | 2         | 1.71%   |
| Zurich                      | 2         | 1.71%   |
| Vienna                      | 2         | 1.71%   |
| Rio de Janeiro              | 2         | 1.71%   |
| Rietberg                    | 2         | 1.71%   |
| Northeim                    | 2         | 1.71%   |
| Graz                        | 2         | 1.71%   |
| Fuchu                       | 2         | 1.71%   |
| Egham                       | 2         | 1.71%   |
| Chicago                     | 2         | 1.71%   |
| Cambridge                   | 2         | 1.71%   |
| Berlin                      | 2         | 1.71%   |
| Zaporizhzhya                | 1         | 0.85%   |
| Wuhan                       | 1         | 0.85%   |
| Woodburn                    | 1         | 0.85%   |
| Wieliczka                   | 1         | 0.85%   |
| Washington                  | 1         | 0.85%   |
| Warsaw                      | 1         | 0.85%   |
| Vila Real de Santo António | 1         | 0.85%   |
| Vancouver                   | 1         | 0.85%   |
| Tynda                       | 1         | 0.85%   |
| Trosa                       | 1         | 0.85%   |
| Thrissur                    | 1         | 0.85%   |
| Teaneck                     | 1         | 0.85%   |
| Stuttgart                   | 1         | 0.85%   |
| Sollentuna                  | 1         | 0.85%   |
| Slavonski Brod              | 1         | 0.85%   |
| Singapore                   | 1         | 0.85%   |
| Shanghai                    | 1         | 0.85%   |
| Setagaya-ku                 | 1         | 0.85%   |
| Satu Mare                   | 1         | 0.85%   |
| Santa Monica                | 1         | 0.85%   |
| San Francisco               | 1         | 0.85%   |
| Ruthin                      | 1         | 0.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 28        | 43     | 20.59%  |
| WDC                 | 27        | 44     | 19.85%  |
| Toshiba             | 12        | 22     | 8.82%   |
| Seagate             | 10        | 26     | 7.35%   |
| Crucial             | 8         | 17     | 5.88%   |
| Kingston            | 7         | 10     | 5.15%   |
| HGST                | 7         | 21     | 5.15%   |
| A-DATA Technology   | 6         | 6      | 4.41%   |
| SK hynix            | 5         | 5      | 3.68%   |
| KIOXIA              | 4         | 4      | 2.94%   |
| Intel               | 4         | 7      | 2.94%   |
| Apple               | 3         | 3      | 2.21%   |
| Micron Technology   | 2         | 3      | 1.47%   |
| SSSTC               | 1         | 1      | 0.74%   |
| SPCC                | 1         | 1      | 0.74%   |
| Solid State Storage | 1         | 1      | 0.74%   |
| Silicon Motion      | 1         | 1      | 0.74%   |
| SanDisk             | 1         | 2      | 0.74%   |
| PNY                 | 1         | 1      | 0.74%   |
| Mushkin             | 1         | 1      | 0.74%   |
| LSI                 | 1         | 4      | 0.74%   |
| LITEON              | 1         | 1      | 0.74%   |
| Hitachi             | 1         | 2      | 0.74%   |
| Goodram             | 1         | 1      | 0.74%   |
| Fujitsu             | 1         | 2      | 0.74%   |
| Apacer              | 1         | 1      | 0.74%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB             | 5         | 3.29%   |
| HGST HTS725050A7E630 500GB           | 4         | 2.63%   |
| WDC WDS100T3X0C-00SJG0 1TB           | 3         | 1.97%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 3         | 1.97%   |
| Toshiba MQ04ABF100 1TB               | 3         | 1.97%   |
| Samsung HM251JX 250GB                | 3         | 1.97%   |
| HGST HTS721010A9E630 1TB             | 3         | 1.97%   |
| WDC WDS100T1X0E-00AFY0 1TB           | 2         | 1.32%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB   | 2         | 1.32%   |
| WDC PC SN730 NVMe 1024GB             | 2         | 1.32%   |
| Seagate ST1000LM049-2GH172 1TB       | 2         | 1.32%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 1.32%   |
| Samsung SSD 970 EVO Plus 1TB         | 2         | 1.32%   |
| Samsung SSD 870 EVO 1TB              | 2         | 1.32%   |
| Samsung SSD 860 EVO 250GB            | 2         | 1.32%   |
| Samsung SSD 850 EVO 250GB            | 2         | 1.32%   |
| Samsung MZVLB512HBJQ-000L7 512GB     | 2         | 1.32%   |
| KIOXIA KBG40ZNS256G NVMe 256GB       | 2         | 1.32%   |
| Kingston SA2000M81000G 1TB           | 2         | 1.32%   |
| Apple SSD SM256E 256GB               | 2         | 1.32%   |
| WDC WDS500G1X0E-00AFY0 500GB         | 1         | 0.66%   |
| WDC WDS250G2B0C-00PXH0 250GB         | 1         | 0.66%   |
| WDC WDS100T2B0A-00SM50 1TB           | 1         | 0.66%   |
| WDC WD60EFRX-68TGBN1 6TB             | 1         | 0.66%   |
| WDC WD5002ABYS-18B1B0 500GB          | 1         | 0.66%   |
| WDC WD40EZRZ-75GXCB0 4TB             | 1         | 0.66%   |
| WDC WD30EFRX-68EUZN0 3TB             | 1         | 0.66%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 1         | 0.66%   |
| WDC WD20EFRX-68AX9N0 2TB             | 1         | 0.66%   |
| WDC WD120EFAX-68UNTN0 12TB           | 1         | 0.66%   |
| WDC WD10SPZX-60Z10T0 1TB             | 1         | 0.66%   |
| WDC WD10SPZX-21Z10T0 1TB             | 1         | 0.66%   |
| WDC WD10JPVX-00JC3T0 1TB             | 1         | 0.66%   |
| WDC WD10JMVW-11AJGS3 1TB             | 1         | 0.66%   |
| WDC WD10EZEX-60WN4A0 1TB             | 1         | 0.66%   |
| WDC WD10EZEX-00RKKA0 1TB             | 1         | 0.66%   |
| WDC WD10EARX-00N0YB0 1TB             | 1         | 0.66%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB | 1         | 0.66%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB | 1         | 0.66%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB | 1         | 0.66%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 11        | 21     | 24.44%  |
| WDC                 | 10        | 16     | 22.22%  |
| Seagate             | 10        | 26     | 22.22%  |
| HGST                | 7         | 21     | 15.56%  |
| Samsung Electronics | 4         | 7      | 8.89%   |
| LSI                 | 1         | 4      | 2.22%   |
| Hitachi             | 1         | 2      | 2.22%   |
| Fujitsu             | 1         | 2      | 2.22%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 15     | 29.41%  |
| Crucial             | 5         | 10     | 14.71%  |
| A-DATA Technology   | 4         | 4      | 11.76%  |
| Kingston            | 3         | 5      | 8.82%   |
| Apple               | 3         | 3      | 8.82%   |
| Intel               | 2         | 5      | 5.88%   |
| WDC                 | 1         | 2      | 2.94%   |
| SK hynix            | 1         | 1      | 2.94%   |
| SanDisk             | 1         | 2      | 2.94%   |
| Micron Technology   | 1         | 1      | 2.94%   |
| LITEON              | 1         | 1      | 2.94%   |
| Goodram             | 1         | 1      | 2.94%   |
| Apacer              | 1         | 1      | 2.94%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 55        | 80     | 45.83%  |
| SSD  | 33        | 51     | 27.5%   |
| HDD  | 32        | 99     | 26.67%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 55        | 80     | 50%     |
| SATA | 55        | 150    | 50%     |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 34        | 67     | 45.95%  |
| 0.51-1.0   | 23        | 40     | 31.08%  |
| 1.01-2.0   | 5         | 6      | 6.76%   |
| 4.01-10.0  | 4         | 23     | 5.41%   |
| 3.01-4.0   | 3         | 4      | 4.05%   |
| 2.01-3.0   | 2         | 3      | 2.7%    |
| 10.01-20.0 | 2         | 3      | 2.7%    |
| 20.01-50.0 | 1         | 4      | 1.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 29        | 26.13%  |
| 251-500        | 25        | 22.52%  |
| 501-1000       | 18        | 16.22%  |
| 1-20           | 11        | 9.91%   |
| 21-50          | 8         | 7.21%   |
| 51-100         | 8         | 7.21%   |
| 1001-2000      | 5         | 4.5%    |
| 2001-3000      | 4         | 3.6%    |
| More than 3000 | 3         | 2.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 68        | 60.71%  |
| 21-50          | 27        | 24.11%  |
| 101-250        | 8         | 7.14%   |
| 1001-2000      | 2         | 1.79%   |
| 501-1000       | 2         | 1.79%   |
| 51-100         | 2         | 1.79%   |
| More than 3000 | 1         | 0.89%   |
| 251-500        | 1         | 0.89%   |
| 0              | 1         | 0.89%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| HGST HTS725050A7E630 500GB          | 4         | 7      | 28.57%  |
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
| HGST                | 4         | 16     | 30.77%  |
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
| HGST                | 4         | 16     | 40%     |
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
| HDD  | 9         | 26     | 81.82%  |
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
| Works    | 88        | 192    | 85.44%  |
| Malfunc  | 11        | 31     | 10.68%  |
| Detected | 4         | 7      | 3.88%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 44        | 31.43%  |
| AMD                            | 26        | 18.57%  |
| Samsung Electronics            | 19        | 13.57%  |
| SanDisk                        | 18        | 12.86%  |
| Kingston Technology Company    | 5         | 3.57%   |
| SK hynix                       | 4         | 2.86%   |
| Silicon Motion                 | 4         | 2.86%   |
| Micron/Crucial Technology      | 3         | 2.14%   |
| KIOXIA                         | 3         | 2.14%   |
| Toshiba                        | 2         | 1.43%   |
| Solid State Storage Technology | 2         | 1.43%   |
| Micron Technology              | 2         | 1.43%   |
| Marvell Technology Group       | 2         | 1.43%   |
| ASMedia Technology             | 2         | 1.43%   |
| ADATA Technology               | 2         | 1.43%   |
| Phison Electronics             | 1         | 0.71%   |
| Broadcom / LSI                 | 1         | 0.71%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 19        | 12.42%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 13        | 8.5%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 11        | 7.19%   |
| Intel Comet Lake SATA AHCI Controller                                          | 8         | 5.23%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 4.58%   |
| Unknown                                                                        | 7         | 4.58%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 6         | 3.92%   |
| AMD 400 Series Chipset SATA Controller                                         | 6         | 3.92%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 4         | 2.61%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 4         | 2.61%   |
| AMD 500 Series Chipset SATA Controller                                         | 4         | 2.61%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 3         | 1.96%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 3         | 1.96%   |
| Kingston Company A2000 NVMe SSD                                                | 3         | 1.96%   |
| Toshiba XG6 NVMe SSD Controller                                                | 2         | 1.31%   |
| SK hynix BC511                                                                 | 2         | 1.31%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 1.31%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 1.31%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 1.31%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 1.31%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 1.31%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2         | 1.31%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 1.31%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.31%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 2         | 1.31%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 2         | 1.31%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 1.31%   |
| SK hynix PC300 NVMe Solid State Drive 512GB                                    | 1         | 0.65%   |
| SanDisk PC SN530                                                               | 1         | 0.65%   |
| Samsung SM951 AHCI                                                             | 1         | 0.65%   |
| Phison E12 NVMe Controller                                                     | 1         | 0.65%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 1         | 0.65%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                          | 1         | 0.65%   |
| Marvell Group 88SE9170 PCIe 2.0 x1 2-port SATA 6 Gb/s Controller               | 1         | 0.65%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 1         | 0.65%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 0.65%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1         | 0.65%   |
| Intel SSD 660P Series                                                          | 1         | 0.65%   |
| Intel NVMe Optane Memory Series                                                | 1         | 0.65%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 1         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 65        | 48.51%  |
| NVMe | 63        | 47.01%  |
| IDE  | 4         | 2.99%   |
| RAID | 2         | 1.49%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 54        | 50.47%  |
| AMD      | 35        | 32.71%  |
| ARM      | 9         | 8.41%   |
| Unknown  | 8         | 7.48%   |
| Research | 1         | 0.93%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
|                                                 | 8         | 7.48%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 6         | 5.61%   |
| Intel Core i7-3520M CPU @ 2.90GHz               | 4         | 3.74%   |
| Intel Core i5-10210U CPU @ 1.60GHz              | 4         | 3.74%   |
| ARM Cortex-A72 r0p3                             | 4         | 3.74%   |
| AMD Ryzen 5 5600G with Radeon Graphics          | 4         | 3.74%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 3         | 2.8%    |
| Intel Core i7-8750H CPU @ 2.20GHz               | 2         | 1.87%   |
| Intel Core i7-7600U CPU @ 2.80GHz               | 2         | 1.87%   |
| Intel Core i5-10500T CPU @ 2.30GHz              | 2         | 1.87%   |
| Intel Core i5-10300H CPU @ 2.50GHz              | 2         | 1.87%   |
| ARM Cortex-A72 r0p2                             | 2         | 1.87%   |
| ARM Cortex-A53 r0p4                             | 2         | 1.87%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 2         | 1.87%   |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx | 2         | 1.87%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 2         | 1.87%   |
| AMD Ryzen 7 4700U with Radeon Graphics          | 2         | 1.87%   |
| AMD Ryzen 5 PRO 3500U w/ Radeon Vega Mobile Gfx | 2         | 1.87%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 2         | 1.87%   |
| Research Morello SoC r0p0                       | 1         | 0.93%   |
| Intel Xeon W-10885M CPU @ 2.40GHz               | 1         | 0.93%   |
| Intel Xeon E-2334 CPU @ 3.40GHz                 | 1         | 0.93%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz             | 1         | 0.93%   |
| Intel Pentium M processor 1000MHz               | 1         | 0.93%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 1         | 0.93%   |
| Intel Core i7-8700 CPU @ 3.20GHz                | 1         | 0.93%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 0.93%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 0.93%   |
| Intel Core i7-5600U CPU @ 2.60GHz               | 1         | 0.93%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz              | 1         | 0.93%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz              | 1         | 0.93%   |
| Intel Core i7-3770 CPU @ 3.40GHz                | 1         | 0.93%   |
| Intel Core i7-3687U CPU @ 2.10GHz               | 1         | 0.93%   |
| Intel Core i7-3615QM CPU @ 2.30GHz              | 1         | 0.93%   |
| Intel Core i7-10870H CPU @ 2.20GHz              | 1         | 0.93%   |
| Intel Core i7-10700K CPU @ 3.80GHz              | 1         | 0.93%   |
| Intel Core i7-10700 CPU @ 2.90GHz               | 1         | 0.93%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz              | 1         | 0.93%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 1         | 0.93%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 1         | 0.93%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 26        | 24.53%  |
| Other                  | 20        | 18.87%  |
| Intel Core i5          | 13        | 12.26%  |
| AMD Ryzen 5            | 11        | 10.38%  |
| ARM Cortex             | 8         | 7.55%   |
| AMD Ryzen 7            | 8         | 7.55%   |
| AMD Ryzen 9            | 5         | 4.72%   |
| Intel Xeon             | 3         | 2.83%   |
| AMD Ryzen 7 PRO        | 3         | 2.83%   |
| AMD Ryzen 5 PRO        | 2         | 1.89%   |
| Intel Pentium M        | 1         | 0.94%   |
| Intel Atom             | 1         | 0.94%   |
| AMD Ryzen Threadripper | 1         | 0.94%   |
| AMD Ryzen Embedded     | 1         | 0.94%   |
| AMD Ryzen 3            | 1         | 0.94%   |
| AMD FX                 | 1         | 0.94%   |
| AMD E                  | 1         | 0.94%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 22        | 20.75%  |
| 8       | 18        | 16.98%  |
| Unknown | 17        | 16.04%  |
| 2       | 15        | 14.15%  |
| 6       | 11        | 10.38%  |
| 16      | 8         | 7.55%   |
| 12      | 8         | 7.55%   |
| 32      | 3         | 2.83%   |
| 24      | 3         | 2.83%   |
| 1       | 1         | 0.94%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 92        | 86.79%  |
| Unknown | 13        | 12.26%  |
| 2       | 1         | 0.94%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 52        | 49.06%  |
| 1       | 36        | 33.96%  |
| Unknown | 18        | 16.98%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 23.58%  |
| KabyLake   | 13        | 12.26%  |
| CometLake  | 12        | 11.32%  |
| Zen 2      | 10        | 9.43%   |
| Zen+       | 9         | 8.49%   |
| IvyBridge  | 9         | 8.49%   |
| Zen 3      | 7         | 6.6%    |
| TigerLake  | 6         | 5.66%   |
| Zen        | 4         | 3.77%   |
| Broadwell  | 3         | 2.83%   |
| Haswell    | 2         | 1.89%   |
| Skylake    | 1         | 0.94%   |
| Silvermont | 1         | 0.94%   |
| Piledriver | 1         | 0.94%   |
| P6         | 1         | 0.94%   |
| IceLake    | 1         | 0.94%   |
| Bobcat     | 1         | 0.94%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 45        | 39.82%  |
| Nvidia                     | 33        | 29.2%   |
| AMD                        | 32        | 28.32%  |
| Matrox Electronics Systems | 2         | 1.77%   |
| ASPEED Technology          | 1         | 0.88%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                           | 7         | 6.09%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                            | 6         | 5.22%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series] | 6         | 5.22%   |
| Intel CometLake-U GT2 [UHD Graphics]                                 | 5         | 4.35%   |
| Intel 3rd Gen Core processor Graphics Controller                     | 5         | 4.35%   |
| Intel CometLake-H GT2 [UHD Graphics]                                 | 4         | 3.48%   |
| AMD Cezanne                                                          | 4         | 3.48%   |
| Nvidia TU117M                                                        | 3         | 2.61%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                             | 3         | 2.61%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                            | 3         | 2.61%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                             | 3         | 2.61%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]     | 3         | 2.61%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                           | 2         | 1.74%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                           | 2         | 1.74%   |
| Nvidia GP108M [GeForce MX230]                                        | 2         | 1.74%   |
| Nvidia GP108 [GeForce GT 1030]                                       | 2         | 1.74%   |
| Nvidia GK208B [GeForce GT 710]                                       | 2         | 1.74%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                 | 2         | 1.74%   |
| Intel HD Graphics 620                                                | 2         | 1.74%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller          | 2         | 1.74%   |
| AMD Lucienne                                                         | 2         | 1.74%   |
| Nvidia TU117M [GeForce MX450]                                        | 1         | 0.87%   |
| Nvidia TU116 [GeForce GTX 1660]                                      | 1         | 0.87%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                              | 1         | 0.87%   |
| Nvidia TU104GLM [Quadro RTX 5000 Mobile / Max-Q]                     | 1         | 0.87%   |
| Nvidia GT218 [GeForce 210]                                           | 1         | 0.87%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                           | 1         | 0.87%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                              | 1         | 0.87%   |
| Nvidia GP107GL [Quadro P620]                                         | 1         | 0.87%   |
| Nvidia GP107 [GeForce GTX 1050]                                      | 1         | 0.87%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                   | 1         | 0.87%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                  | 1         | 0.87%   |
| Nvidia GM206 [GeForce GTX 960]                                       | 1         | 0.87%   |
| Nvidia GM108M [GeForce MX130]                                        | 1         | 0.87%   |
| Nvidia GM108M [GeForce 940MX]                                        | 1         | 0.87%   |
| Nvidia GM107M [GeForce GTX 860M]                                     | 1         | 0.87%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                    | 1         | 0.87%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                          | 1         | 0.87%   |
| Nvidia GK107GLM [Quadro K1100M]                                      | 1         | 0.87%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                           | 1         | 0.87%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 27        | 25.23%  |
| 1 x Intel      | 24        | 22.43%  |
| Intel + Nvidia | 19        | 17.76%  |
| Other          | 16        | 14.95%  |
| 1 x Nvidia     | 14        | 13.08%  |
| 2 x AMD        | 2         | 1.87%   |
| 1 x Matrox     | 2         | 1.87%   |
| Intel + AMD    | 1         | 0.93%   |
| 1 x ASPEED     | 1         | 0.93%   |
| AMD + Nvidia   | 1         | 0.93%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 67        | 63.81%  |
| Proprietary | 22        | 20.95%  |
| Unknown     | 16        | 15.24%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 77        | 71.96%  |
| 1.01-2.0   | 11        | 10.28%  |
| 0.51-1.0   | 6         | 5.61%   |
| 0.01-0.5   | 5         | 4.67%   |
| 3.01-4.0   | 4         | 3.74%   |
| 5.01-6.0   | 2         | 1.87%   |
| 7.01-8.0   | 1         | 0.93%   |
| 2.01-3.0   | 1         | 0.93%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| BOE                 | 13        | 16.25%  |
| LG Display          | 10        | 12.5%   |
| AU Optronics        | 9         | 11.25%  |
| Dell                | 6         | 7.5%    |
| Goldstar            | 5         | 6.25%   |
| Philips             | 4         | 5%      |
| Hewlett-Packard     | 4         | 5%      |
| Chimei Innolux      | 4         | 5%      |
| Samsung Electronics | 3         | 3.75%   |
| RTK                 | 2         | 2.5%    |
| LG Electronics      | 2         | 2.5%    |
| Lenovo              | 2         | 2.5%    |
| Apple               | 2         | 2.5%    |
| ViewSonic           | 1         | 1.25%   |
| Sony                | 1         | 1.25%   |
| Sharp               | 1         | 1.25%   |
| SDC                 | 1         | 1.25%   |
| PANDA               | 1         | 1.25%   |
| LGD                 | 1         | 1.25%   |
| InfoVision          | 1         | 1.25%   |
| Iiyama              | 1         | 1.25%   |
| HJW                 | 1         | 1.25%   |
| Eizo                | 1         | 1.25%   |
| CSO                 | 1         | 1.25%   |
| BenQ                | 1         | 1.25%   |
| AOC                 | 1         | 1.25%   |
| Unknown             | 1         | 1.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0258 1600x900 350x190mm 15.7-inch            | 3         | 3.66%   |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                  | 3         | 3.66%   |
| RTK WCS Display RTK1A1B 1920x1080 344x195mm 15.6-inch                  | 2         | 2.44%   |
| Philips LCD Monitor PHL08C3 1920x1080 600x340mm 27.2-inch              | 2         | 2.44%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch           | 2         | 2.44%   |
| ViewSonic LCD Monitor VSCD22B 1920x1080 520x290mm 23.4-inch            | 1         | 1.22%   |
| Sony TV SNY4B03 1920x1080 930x520mm 41.9-inch                          | 1         | 1.22%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 380x210mm 17.1-inch                | 1         | 1.22%   |
| SDC LCD Monitor 3520x1080                                              | 1         | 1.22%   |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                       | 1         | 1.22%   |
| Samsung Electronics LCD Monitor SDC3754 1600x900 380x210mm 17.1-inch   | 1         | 1.22%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1020x570mm 46.0-inch | 1         | 1.22%   |
| Philips PHL 273V7 PHLC156 1920x1080 600x340mm 27.2-inch                | 1         | 1.22%   |
| Philips LCD Monitor 271P4 3520x1080                                    | 1         | 1.22%   |
| Philips LCD Monitor 271P4                                              | 1         | 1.22%   |
| PANDA LCD Monitor NCP004F 1920x1080 310x170mm 13.9-inch                | 1         | 1.22%   |
| LGD LCD Monitor 1920x1080                                              | 1         | 1.22%   |
| LG Electronics LCD Monitor LX20D 1600x1200                             | 1         | 1.22%   |
| LG Electronics LCD Monitor LG Ultra HD 11520x2160                      | 1         | 1.22%   |
| LG Electronics LCD Monitor LG Ultra HD                                 | 1         | 1.22%   |
| LG Display LCD Monitor LGD062E 1920x1080 340x190mm 15.3-inch           | 1         | 1.22%   |
| LG Display LCD Monitor LGD060A 1920x1080 290x170mm 13.2-inch           | 1         | 1.22%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch           | 1         | 1.22%   |
| LG Display LCD Monitor LGD05F1 1920x1080 310x170mm 13.9-inch           | 1         | 1.22%   |
| LG Display LCD Monitor LGD033E 1366x768 310x170mm 13.9-inch            | 1         | 1.22%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                  | 1         | 1.22%   |
| Lenovo LEN P44w-10 LEN61D5 3840x1200 1050x330mm 43.3-inch              | 1         | 1.22%   |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch           | 1         | 1.22%   |
| Iiyama PL2474H IVM6146 1920x1080 520x290mm 23.4-inch                   | 1         | 1.22%   |
| HJW HDMI TO USB HJW0001 1920x1080 700x390mm 31.5-inch                  | 1         | 1.22%   |
| Hewlett-Packard LCD Monitor LA2306 3520x1080                           | 1         | 1.22%   |
| Hewlett-Packard LA2306 HWP2949 1920x1080 510x290mm 23.1-inch           | 1         | 1.22%   |
| Hewlett-Packard E242 HWP326E 1920x1200 520x320mm 24.0-inch             | 1         | 1.22%   |
| Hewlett-Packard E233 HPN345F 1920x1080 510x290mm 23.1-inch             | 1         | 1.22%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch             | 1         | 1.22%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch             | 1         | 1.22%   |
| Goldstar 27GL650F GSM5B71 1920x1080 530x300mm 24.0-inch                | 1         | 1.22%   |
| Goldstar 27GK750F GSM770F 1920x1080 600x340mm 27.2-inch                | 1         | 1.22%   |
| Goldstar 23EA53 GSM59A8 1920x1080 510x290mm 23.1-inch                  | 1         | 1.22%   |
| Eizo FX2431 ENC2036 1920x1200 520x330mm 24.2-inch                      | 1         | 1.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 46        | 58.23%  |
| 3840x2160 (4K)    | 6         | 7.59%   |
| 1600x900 (HD+)    | 6         | 7.59%   |
| 1920x1200 (WUXGA) | 4         | 5.06%   |
| 2560x1440 (QHD)   | 3         | 3.8%    |
| 2256x1504         | 3         | 3.8%    |
| 2560x1600         | 2         | 2.53%   |
| 1366x768 (WXGA)   | 2         | 2.53%   |
| Unknown           | 2         | 2.53%   |
| 3840x1200         | 1         | 1.27%   |
| 3520x1080         | 1         | 1.27%   |
| 2160x1440         | 1         | 1.27%   |
| 1600x1200         | 1         | 1.27%   |
| 11520x2160        | 1         | 1.27%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 23        | 29.49%  |
| 15      | 16        | 20.51%  |
| Unknown | 8         | 10.26%  |
| 27      | 7         | 8.97%   |
| 24      | 6         | 7.69%   |
| 23      | 6         | 7.69%   |
| 17      | 3         | 3.85%   |
| 12      | 2         | 2.56%   |
| 46      | 1         | 1.28%   |
| 43      | 1         | 1.28%   |
| 41      | 1         | 1.28%   |
| 32      | 1         | 1.28%   |
| 31      | 1         | 1.28%   |
| 22      | 1         | 1.28%   |
| 21      | 1         | 1.28%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 30        | 38.96%  |
| 501-600     | 17        | 22.08%  |
| 201-300     | 11        | 14.29%  |
| Unknown     | 8         | 10.39%  |
| 351-400     | 3         | 3.9%    |
| 601-700     | 2         | 2.6%    |
| 401-500     | 2         | 2.6%    |
| 1001-1500   | 2         | 2.6%    |
| 701-800     | 1         | 1.3%    |
| 901-1000    | 1         | 1.3%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 53        | 74.65%  |
| 16/10   | 7         | 9.86%   |
| Unknown | 7         | 9.86%   |
| 3/2     | 3         | 4.23%   |
| 3.18    | 1         | 1.41%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 19        | 24.36%  |
| 91-100         | 11        | 14.1%   |
| 201-250        | 10        | 12.82%  |
| Unknown        | 8         | 10.26%  |
| 301-350        | 7         | 8.97%   |
| 101-110        | 5         | 6.41%   |
| 71-80          | 4         | 5.13%   |
| 251-300        | 4         | 5.13%   |
| 121-130        | 3         | 3.85%   |
| 501-1000       | 3         | 3.85%   |
| 61-70          | 2         | 2.56%   |
| 351-500        | 2         | 2.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 26        | 34.21%  |
| 51-100        | 19        | 25%     |
| 161-240       | 13        | 17.11%  |
| Unknown       | 8         | 10.53%  |
| 101-120       | 7         | 9.21%   |
| More than 240 | 2         | 2.63%   |
| 1-50          | 1         | 1.32%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 58        | 53.7%   |
| 0     | 40        | 37.04%  |
| 2     | 9         | 8.33%   |
| 3     | 1         | 0.93%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 71        | 45.51%  |
| Realtek Semiconductor           | 47        | 30.13%  |
| TP-Link                         | 6         | 3.85%   |
| Broadcom                        | 6         | 3.85%   |
| Ralink Technology               | 4         | 2.56%   |
| Qualcomm Atheros                | 4         | 2.56%   |
| Hewlett-Packard                 | 4         | 2.56%   |
| Edimax Technology               | 2         | 1.28%   |
| D-Link System                   | 2         | 1.28%   |
| Xiaomi                          | 1         | 0.64%   |
| Qualcomm Atheros Communications | 1         | 0.64%   |
| Mellanox Technologies           | 1         | 0.64%   |
| Lenovo                          | 1         | 0.64%   |
| Google                          | 1         | 0.64%   |
| Emulex                          | 1         | 0.64%   |
| BUFFALO                         | 1         | 0.64%   |
| ASUSTek Computer                | 1         | 0.64%   |
| Arduino SA                      | 1         | 0.64%   |
| Aquantia                        | 1         | 0.64%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 38        | 19.69%  |
| Intel Wi-Fi 6 AX200                                                        | 10        | 5.18%   |
| Intel Comet Lake PCH CNVi WiFi                                             | 7         | 3.63%   |
| Intel Wireless-AC 9260                                                     | 6         | 3.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 6         | 3.11%   |
| Intel Wireless 8265 / 8275                                                 | 5         | 2.59%   |
| Intel I211 Gigabit Network Connection                                      | 5         | 2.59%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                          | 5         | 2.59%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 5         | 2.59%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 4         | 2.07%   |
| Realtek RTL8125 2.5GbE Controller                                          | 4         | 2.07%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                     | 4         | 2.07%   |
| Intel Wi-Fi 6 AX201                                                        | 4         | 2.07%   |
| Intel I210 Gigabit Network Connection                                      | 4         | 2.07%   |
| Intel 82574L Gigabit Network Connection                                    | 4         | 2.07%   |
| HP hs2350 HSPA+ Mobile Broadband Module Network Adapter                    | 4         | 2.07%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 3         | 1.55%   |
| Intel Ethernet Controller I225-V                                           | 3         | 1.55%   |
| Intel Ethernet Connection (14) I219-LM                                     | 3         | 1.55%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 2         | 1.04%   |
| Ralink MT7601U Wireless Adapter                                            | 2         | 1.04%   |
| Intel Wireless 7265                                                        | 2         | 1.04%   |
| Intel Wireless 7260                                                        | 2         | 1.04%   |
| Intel Ethernet Connection (4) I219-LM                                      | 2         | 1.04%   |
| Intel Ethernet Connection (11) I219-LM                                     | 2         | 1.04%   |
| Intel Ethernet Connection (10) I219-V                                      | 2         | 1.04%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 2         | 1.04%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 2         | 1.04%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                       | 1         | 0.52%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                     | 1         | 0.52%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]        | 1         | 0.52%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                   | 1         | 0.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 0.52%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                     | 1         | 0.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 1         | 0.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 1         | 0.52%   |
| Ralink RT5370 Wireless Adapter                                             | 1         | 0.52%   |
| Ralink RT2870/RT3070 Wireless Adapter                                      | 1         | 0.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 1         | 0.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 1         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 57        | 63.33%  |
| Realtek Semiconductor           | 8         | 8.89%   |
| TP-Link                         | 6         | 6.67%   |
| Broadcom                        | 5         | 5.56%   |
| Ralink Technology               | 4         | 4.44%   |
| Qualcomm Atheros                | 3         | 3.33%   |
| Edimax Technology               | 2         | 2.22%   |
| D-Link System                   | 2         | 2.22%   |
| Qualcomm Atheros Communications | 1         | 1.11%   |
| BUFFALO                         | 1         | 1.11%   |
| ASUSTek Computer                | 1         | 1.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                           | 10        | 11.11%  |
| Intel Comet Lake PCH CNVi WiFi                                                | 7         | 7.78%   |
| Intel Wireless-AC 9260                                                        | 6         | 6.67%   |
| Intel Wireless 8265 / 8275                                                    | 5         | 5.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 5         | 5.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 5         | 5.56%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 4         | 4.44%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 4         | 4.44%   |
| Intel Wi-Fi 6 AX201                                                           | 4         | 4.44%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 3         | 3.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 2.22%   |
| Ralink MT7601U Wireless Adapter                                               | 2         | 2.22%   |
| Intel Wireless 7265                                                           | 2         | 2.22%   |
| Intel Wireless 7260                                                           | 2         | 2.22%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2         | 2.22%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]    | 2         | 2.22%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1         | 1.11%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]           | 1         | 1.11%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                      | 1         | 1.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.11%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                        | 1         | 1.11%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 1.11%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1         | 1.11%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1         | 1.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 1         | 1.11%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 1         | 1.11%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1         | 1.11%   |
| Intel Wireless 8260                                                           | 1         | 1.11%   |
| Intel Wi-Fi 6 AX201 160MHz                                                    | 1         | 1.11%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 1         | 1.11%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 1.11%   |
| Intel Centrino Advanced-N 6235                                                | 1         | 1.11%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                | 1         | 1.11%   |
| Edimax EW-7711MAC 802.11ac Wireless Adapter                                   | 1         | 1.11%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]                      | 1         | 1.11%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                   | 1         | 1.11%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 1         | 1.11%   |
| Broadcom BCM4331 802.11a/b/g/n                                                | 1         | 1.11%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 1         | 1.11%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 1         | 1.11%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 42        | 46.15%  |
| Intel                 | 41        | 45.05%  |
| Broadcom              | 2         | 2.2%    |
| Xiaomi                | 1         | 1.1%    |
| Qualcomm Atheros      | 1         | 1.1%    |
| Lenovo                | 1         | 1.1%    |
| Google                | 1         | 1.1%    |
| Emulex                | 1         | 1.1%    |
| Aquantia              | 1         | 1.1%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 38        | 40%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6         | 6.32%   |
| Intel I211 Gigabit Network Connection                                         | 5         | 5.26%   |
| Intel I210 Gigabit Network Connection                                         | 4         | 4.21%   |
| Intel 82574L Gigabit Network Connection                                       | 4         | 4.21%   |
| Realtek RTL8125 2.5GbE Controller                                             | 3         | 3.16%   |
| Intel Ethernet Controller I225-V                                              | 3         | 3.16%   |
| Intel Ethernet Connection (14) I219-LM                                        | 3         | 3.16%   |
| Intel Ethernet Connection (4) I219-LM                                         | 2         | 2.11%   |
| Intel Ethernet Connection (11) I219-LM                                        | 2         | 2.11%   |
| Intel Ethernet Connection (10) I219-V                                         | 2         | 2.11%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                          | 1         | 1.05%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1         | 1.05%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 1.05%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1         | 1.05%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                              | 1         | 1.05%   |
| Intel I350 Gigabit Network Connection                                         | 1         | 1.05%   |
| Intel Ethernet Controller I225-LM                                             | 1         | 1.05%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 1         | 1.05%   |
| Intel Ethernet Connection I219-LM                                             | 1         | 1.05%   |
| Intel Ethernet Connection I217-LM                                             | 1         | 1.05%   |
| Intel Ethernet Connection (7) I219-V                                          | 1         | 1.05%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1         | 1.05%   |
| Intel Ethernet Connection (5) I219-V                                          | 1         | 1.05%   |
| Intel Ethernet Connection (3) I218-LM                                         | 1         | 1.05%   |
| Intel Ethernet Connection (13) I219-V                                         | 1         | 1.05%   |
| Intel Ethernet Connection (11) I219-V                                         | 1         | 1.05%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 1.05%   |
| Google Nexus/Pixel Device (charging + debug)                                  | 1         | 1.05%   |
| Emulex OneConnect 10Gb NIC (be3)                                              | 1         | 1.05%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                             | 1         | 1.05%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 1         | 1.05%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 1         | 1.05%   |
| Unknown                                                                       | 1         | 1.05%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 83        | 50.61%  |
| WiFi     | 73        | 44.51%  |
| Modem    | 6         | 3.66%   |
| Unknown  | 2         | 1.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 70        | 60.34%  |
| WiFi     | 43        | 37.07%  |
| Modem    | 3         | 2.59%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 58        | 55.24%  |
| 1     | 23        | 21.9%   |
| 0     | 14        | 13.33%  |
| 3     | 7         | 6.67%   |
| 4     | 2         | 1.9%    |
| 7     | 1         | 0.95%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 89        | 80.18%  |
| Yes  | 22        | 19.82%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 43        | 78.18%  |
| Apple                           | 4         | 7.27%   |
| Realtek Semiconductor           | 2         | 3.64%   |
| IMC Networks                    | 2         | 3.64%   |
| Realtek                         | 1         | 1.82%   |
| Qualcomm Atheros Communications | 1         | 1.82%   |
| Cambridge Silicon Radio         | 1         | 1.82%   |
| Broadcom                        | 1         | 1.82%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 14        | 25.45%  |
| Intel AX200 Bluetooth                               | 9         | 16.36%  |
| Intel Bluetooth wireless interface                  | 7         | 12.73%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 5         | 9.09%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 7.27%   |
| Intel AX210 Bluetooth                               | 3         | 5.45%   |
| Apple Bluetooth Host Controller                     | 2         | 3.64%   |
| Realtek  Bluetooth Adapter                          | 1         | 1.82%   |
| Realtek Bluetooth Radio                             | 1         | 1.82%   |
| Realtek Bluetooth Radio                             | 1         | 1.82%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.82%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.82%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.82%   |
| IMC Networks Bluetooth module                       | 1         | 1.82%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.82%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.82%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 1.82%   |
| Apple Apple Broadcom Built-in Bluetooth             | 1         | 1.82%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 52        | 40%     |
| AMD                     | 39        | 30%     |
| Nvidia                  | 27        | 20.77%  |
| Lenovo                  | 3         | 2.31%   |
| Yamaha                  | 1         | 0.77%   |
| SteelSeries ApS         | 1         | 0.77%   |
| Logitech                | 1         | 0.77%   |
| GN Netcom               | 1         | 0.77%   |
| Generalplus Technology  | 1         | 0.77%   |
| CMX Systems             | 1         | 0.77%   |
| C-Media Electronics     | 1         | 0.77%   |
| AudioQuest              | 1         | 0.77%   |
| AKAI  Professional M.I. | 1         | 0.77%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                  | 21        | 13.21%  |
| AMD Renoir Radeon High Definition Audio Controller                      | 11        | 6.92%   |
| Intel Comet Lake PCH cAVS                                               | 10        | 6.29%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller     | 9         | 5.66%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                     | 9         | 5.66%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller             | 6         | 3.77%   |
| AMD Starship/Matisse HD Audio Controller                                | 6         | 3.77%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller          | 5         | 3.14%   |
| Nvidia GP107GL High Definition Audio Controller                         | 5         | 3.14%   |
| Intel Comet Lake PCH-LP cAVS                                            | 5         | 3.14%   |
| Intel Cannon Lake PCH cAVS                                              | 4         | 2.52%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                     | 4         | 2.52%   |
| Nvidia TU116 High Definition Audio Controller                           | 3         | 1.89%   |
| Intel Tiger Lake-H HD Audio Controller                                  | 3         | 1.89%   |
| Intel Sunrise Point-LP HD Audio                                         | 3         | 1.89%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]               | 3         | 1.89%   |
| Unknown                                                                 | 3         | 1.89%   |
| Nvidia GP108 High Definition Audio Controller                           | 2         | 1.26%   |
| Nvidia GK208 HDMI/DP Audio Controller                                   | 2         | 1.26%   |
| Nvidia GK107 HDMI Audio Controller                                      | 2         | 1.26%   |
| Intel Wildcat Point-LP High Definition Audio Controller                 | 2         | 1.26%   |
| Intel Broadwell-U Audio Controller                                      | 2         | 1.26%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller     | 2         | 1.26%   |
| AMD SBx00 Azalia (Intel HDA)                                            | 2         | 1.26%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 2         | 1.26%   |
| AMD Navi 10 HDMI Audio                                                  | 2         | 1.26%   |
| Yamaha Steinberg UR12                                                   | 1         | 0.63%   |
| SteelSeries ApS SteelSeries Siberia 350                                 | 1         | 0.63%   |
| Nvidia TU106 High Definition Audio Controller                           | 1         | 0.63%   |
| Nvidia TU104 HD Audio Controller                                        | 1         | 0.63%   |
| Nvidia High Definition Audio Controller                                 | 1         | 0.63%   |
| Nvidia GP106 High Definition Audio Controller                           | 1         | 0.63%   |
| Nvidia GM206 High Definition Audio Controller                           | 1         | 0.63%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]           | 1         | 0.63%   |
| Nvidia GA104 High Definition Audio Controller                           | 1         | 0.63%   |
| Logitech H390 headset with microphone                                   | 1         | 0.63%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                | 1         | 0.63%   |
| Lenovo ThinkPad Dock Audio                                              | 1         | 0.63%   |
| Lenovo Realtek USB Audio                                                | 1         | 0.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller        | 1         | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 21        | 20.59%  |
| SK hynix               | 15        | 14.71%  |
| Micron Technology      | 15        | 14.71%  |
| Kingston               | 11        | 10.78%  |
| Crucial                | 9         | 8.82%   |
| Corsair                | 5         | 4.9%    |
| Unknown                | 4         | 3.92%   |
| Smart                  | 3         | 2.94%   |
| Ramaxel Technology     | 3         | 2.94%   |
| Team                   | 2         | 1.96%   |
| Goodram                | 2         | 1.96%   |
| A-DATA Technology      | 2         | 1.96%   |
| Unknown                | 2         | 1.96%   |
| Unknown (000000000C01) | 1         | 0.98%   |
| Transcend              | 1         | 0.98%   |
| PNY                    | 1         | 0.98%   |
| Neo Forza              | 1         | 0.98%   |
| KLEVV                  | 1         | 0.98%   |
| Gold Key               | 1         | 0.98%   |
| G.Skill                | 1         | 0.98%   |
| 06F100000C01           | 1         | 0.98%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s      | 4         | 3.85%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s     | 2         | 1.92%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s     | 2         | 1.92%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s     | 2         | 1.92%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s    | 2         | 1.92%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s      | 2         | 1.92%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s      | 2         | 1.92%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s       | 2         | 1.92%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s       | 2         | 1.92%   |
| Crucial RAM BL32G32C16S4B.M16FB1 32GB SODIMM DDR4 2667MT/s | 2         | 1.92%   |
| Corsair RAM CMK32GX4M2D3200C16 16GB DIMM DDR4 3200MT/s     | 2         | 1.92%   |
| Unknown                                                    | 2         | 1.92%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                  | 1         | 0.96%   |
| Unknown RAM Module 1GB SODIMM DDR                          | 1         | 0.96%   |
| Unknown RAM 3000 C16 Series 4096MB DIMM DDR4 2933MT/s      | 1         | 0.96%   |
| Unknown RAM 2G-08-10-12-1333 2GB DIMM DDR3 1333MT/s        | 1         | 0.96%   |
| Unknown (000000000C01) RAM Module 32GB DIMM DDR4 3200MT/s  | 1         | 0.96%   |
| Transcend RAM JM2666HLE-32G 32GB DIMM DDR4 2666MT/s        | 1         | 0.96%   |
| Team RAM TEAMGROUP-UD4-4133 8GB DIMM DDR4 4133MT/s         | 1         | 0.96%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s      | 1         | 0.96%   |
| Smart RAM SF4641G8CK8IWGKSEG 8GB SODIMM DDR4 2133MT/s      | 1         | 0.96%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s      | 1         | 0.96%   |
| Smart RAM Module 8GB DIMM DDR4 2667MT/s                    | 1         | 0.96%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1867MT/s               | 1         | 0.96%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s               | 1         | 0.96%   |
| SK hynix RAM HMAA4GU6CJR8N-XN 32GB DIMM DDR4 3200MT/s      | 1         | 0.96%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s    | 1         | 0.96%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s     | 1         | 0.96%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s     | 1         | 0.96%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s     | 1         | 0.96%   |
| Samsung RAM M474A4G43AB1-CVF 32GB SODIMM DDR4 2933MT/s     | 1         | 0.96%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s      | 1         | 0.96%   |
| Samsung RAM M471B5674-M0-YK0 4GB Chip DDR3 1600MT/s        | 1         | 0.96%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s      | 1         | 0.96%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s      | 1         | 0.96%   |
| Samsung RAM M471A5244BB0-CWE 4GB SODIMM DDR4 3200MT/s      | 1         | 0.96%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s     | 1         | 0.96%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s     | 1         | 0.96%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s     | 1         | 0.96%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s      | 1         | 0.96%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 70        | 77.78%  |
| DDR3   | 16        | 17.78%  |
| LPDDR5 | 1         | 1.11%   |
| LPDDR4 | 1         | 1.11%   |
| LPDDR3 | 1         | 1.11%   |
| DDR    | 1         | 1.11%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 59        | 65.56%  |
| DIMM         | 26        | 28.89%  |
| Row Of Chips | 4         | 4.44%   |
| Chip         | 1         | 1.11%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 36        | 38.71%  |
| 16384 | 28        | 30.11%  |
| 32768 | 14        | 15.05%  |
| 4096  | 11        | 11.83%  |
| 2048  | 3         | 3.23%   |
| 1024  | 1         | 1.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 34        | 36.17%  |
| 2667    | 20        | 21.28%  |
| 1600    | 8         | 8.51%   |
| 1867    | 6         | 6.38%   |
| 2400    | 5         | 5.32%   |
| 2666    | 4         | 4.26%   |
| 2933    | 3         | 3.19%   |
| 2133    | 3         | 3.19%   |
| 3600    | 2         | 2.13%   |
| 1333    | 2         | 2.13%   |
| 4267    | 1         | 1.06%   |
| 4266    | 1         | 1.06%   |
| 4133    | 1         | 1.06%   |
| 3000    | 1         | 1.06%   |
| 1866    | 1         | 1.06%   |
| 1334    | 1         | 1.06%   |
| Unknown | 1         | 1.06%   |

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
| Chicony Electronics                    | 15        | 24.19%  |
| IMC Networks                           | 10        | 16.13%  |
| Realtek Semiconductor                  | 6         | 9.68%   |
| Logitech                               | 6         | 9.68%   |
| Lite-On Technology                     | 5         | 8.06%   |
| Acer                                   | 5         | 8.06%   |
| Sunplus Innovation Technology          | 4         | 6.45%   |
| Microdia                               | 3         | 4.84%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 4.84%   |
| Apple                                  | 2         | 3.23%   |
| Syntek                                 | 1         | 1.61%   |
| GEMBIRD                                | 1         | 1.61%   |
| Aveo Technology                        | 1         | 1.61%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                             | 7         | 11.11%  |
| Chicony Integrated Camera                                                  | 7         | 11.11%  |
| Sunplus Integrated_Webcam_HD                                               | 3         | 4.76%   |
| Logitech Webcam C270                                                       | 3         | 4.76%   |
| Lite-On Integrated Camera                                                  | 3         | 4.76%   |
| Chicony Integrated HP HD Webcam                                            | 3         | 4.76%   |
| Acer Integrated Camera                                                     | 3         | 4.76%   |
| Realtek Laptop Camera                                                      | 2         | 3.17%   |
| Realtek Integrated_Webcam_HD                                               | 2         | 3.17%   |
| Microdia HP Integrated Webcam                                              | 2         | 3.17%   |
| Lite-On HP HD Camera                                                       | 2         | 3.17%   |
| Chicony ThinkPad T490 Webcam                                               | 2         | 3.17%   |
| Apple FaceTime HD Camera (Built-in)                                        | 2         | 3.17%   |
| Acer HD Webcam                                                             | 2         | 3.17%   |
| Syntek Lenovo EasyCamera                                                   | 1         | 1.59%   |
| Sunplus Integrated_Webcam_FHD                                              | 1         | 1.59%   |
| Realtek USB 2 Webcam                                                       | 1         | 1.59%   |
| Realtek Realtek USB2.0 PC Camera                                           | 1         | 1.59%   |
| Microdia Dell Integrated HD Webcam                                         | 1         | 1.59%   |
| Logitech Webcam C170                                                       | 1         | 1.59%   |
| Logitech HD Pro Webcam C920                                                | 1         | 1.59%   |
| Logitech C920 PRO HD Webcam                                                | 1         | 1.59%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 1         | 1.59%   |
| IMC Networks HD Camera                                                     | 1         | 1.59%   |
| IMC Networks EasyCamera                                                    | 1         | 1.59%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]                          | 1         | 1.59%   |
| Chicony USB2.0 0.3M UVC WebCam                                             | 1         | 1.59%   |
| Chicony Integrated IR Camera                                               | 1         | 1.59%   |
| Chicony HD Webcam                                                          | 1         | 1.59%   |
| Chicony Chicony USB2.0 Camera                                              | 1         | 1.59%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 1.59%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed]                | 1         | 1.59%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam   | 1         | 1.59%   |
| Aveo USB2.0 Camera                                                         | 1         | 1.59%   |

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
| 0     | 31        | 28.44%  |
| 2     | 30        | 27.52%  |
| 1     | 18        | 16.51%  |
| 4     | 15        | 13.76%  |
| 3     | 10        | 9.17%   |
| 5     | 4         | 3.67%   |
| 9     | 1         | 0.92%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 59        | 36.88%  |
| Bluetooth                | 33        | 20.63%  |
| Net/wireless             | 27        | 16.88%  |
| Fingerprint reader       | 19        | 11.88%  |
| Card reader              | 9         | 5.63%   |
| Sound                    | 5         | 3.13%   |
| Net/ethernet             | 3         | 1.88%   |
| Network                  | 2         | 1.25%   |
| Firewire controller      | 2         | 1.25%   |
| Modem                    | 1         | 0.63%   |

