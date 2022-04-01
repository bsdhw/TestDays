FreeBSD 14.0-CURRENT - Tested Hardware & Statistics
---------------------------------------------------

A project to collect tested hardware configurations for FreeBSD 14.0-CURRENT.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/FreeBSD_14.0-CURRENT/Desktop/README.md) and [notebooks](/Dist/FreeBSD_14.0-CURRENT/Notebook/README.md).

Full-feature report is available here: https://bsd-hardware.info/?view=trends

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

Total: 165

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
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
| Unknown       | Unknown                     | Desktop     | [d05fb15725](https://bsd-hardware.info/?probe=d05fb15725) | Nov 22, 2021 |
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
| amd64 | 70        | 81.4%   |
| arm64 | 13        | 15.12%  |
| riscv | 1         | 1.16%   |
| i386  | 1         | 1.16%   |
| arm   | 1         | 1.16%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KDE5          | 24        | 26.09%  |
| Console       | 19        | 20.65%  |
| XFCE          | 11        | 11.96%  |
| MATE          | 8         | 8.7%    |
| i3            | 5         | 5.43%   |
| GNOME         | 5         | 5.43%   |
| TWM           | 4         | 4.35%   |
| Cinnamon      | 3         | 3.26%   |
| Openbox       | 2         | 2.17%   |
| Lumina        | 2         | 2.17%   |
| Xfwm4         | 1         | 1.09%   |
| Picom         | 1         | 1.09%   |
| LXQt          | 1         | 1.09%   |
| LXDE          | 1         | 1.09%   |
| GNUstep       | 1         | 1.09%   |
| Fluxbox       | 1         | 1.09%   |
| Enlightenment | 1         | 1.09%   |
| ctwm          | 1         | 1.09%   |
| akonadi_newm  | 1         | 1.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 64        | 71.91%  |
| Console | 24        | 26.97%  |
| Wayland | 1         | 1.12%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 38        | 42.7%   |
| SDDM    | 23        | 25.84%  |
| SLiM    | 10        | 11.24%  |
| GDM     | 9         | 10.11%  |
| XDM     | 6         | 6.74%   |
| LightDM | 3         | 3.37%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang             | Computers | Percent |
|------------------|-----------|---------|
| C                | 55        | 62.5%   |
| en_US            | 11        | 12.5%   |
| Unknown          | 5         | 5.68%   |
| uk_UA            | 3         | 3.41%   |
| de_DE            | 3         | 3.41%   |
| zh_CN            | 2         | 2.27%   |
| en_GB            | 2         | 2.27%   |
| sv_SE            | 1         | 1.14%   |
| ru_RU            | 1         | 1.14%   |
| pt_PT            | 1         | 1.14%   |
| pl_PL            | 1         | 1.14%   |
| it_IT.ISO8859-15 | 1         | 1.14%   |
| fr_FR            | 1         | 1.14%   |
| de_CH            | 1         | 1.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 77        | 89.53%  |
| BIOS | 9         | 10.47%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 62        | 72.09%  |
| Ufs  | 24        | 27.91%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 78        | 90.7%   |
| MBR  | 8         | 9.3%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 23        | 26.74%  |
| ASUSTek Computer               | 10        | 11.63%  |
| Hewlett-Packard                | 9         | 10.47%  |
| Unknown                        | 9         | 10.47%  |
| Dell                           | 7         | 8.14%   |
| Gigabyte Technology            | 6         | 6.98%   |
| Raspberry Pi Foundation        | 4         | 4.65%   |
| MSI                            | 2         | 2.33%   |
| Framework                      | 2         | 2.33%   |
| Beckhoff Automation            | 2         | 2.33%   |
| Apple                          | 2         | 2.33%   |
| pine64                         | 1         | 1.16%   |
| Notebook                       | 1         | 1.16%   |
| Matsushita Electric Industrial | 1         | 1.16%   |
| khadas                         | 1         | 1.16%   |
| Intel                          | 1         | 1.16%   |
| HUAWEI                         | 1         | 1.16%   |
| friendlyelec                   | 1         | 1.16%   |
| Avell High Performance         | 1         | 1.16%   |
| ASRock                         | 1         | 1.16%   |
| A-DATA Technology              | 1         | 1.16%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 10        | 11.63%  |
| RPi Raspberry Pi                            | 3         | 3.49%   |
| HP EliteBook 8570p                          | 3         | 3.49%   |
| Framework Laptop                            | 2         | 2.33%   |
| RPi rpi                                     | 1         | 1.16%   |
| pine64 pinebook-pro-rk3399                  | 1         | 1.16%   |
| Notebook NS50_70MU                          | 1         | 1.16%   |
| MSI MS-7B86                                 | 1         | 1.16%   |
| MSI GE76 Raider 10UG                        | 1         | 1.16%   |
| Matsushita Electric Industrial CF-T2BW1AXR  | 1         | 1.16%   |
| Lenovo XiaoXinPro-13ARE 2020 82DM           | 1         | 1.16%   |
| Lenovo ThinkPad X395 20NL001SMX             | 1         | 1.16%   |
| Lenovo ThinkPad X395 20NL000GPG             | 1         | 1.16%   |
| Lenovo ThinkPad X270 20HM004JBR             | 1         | 1.16%   |
| Lenovo ThinkPad X260 20F5A28AUK             | 1         | 1.16%   |
| Lenovo ThinkPad X13 Gen 1 20T2003PRT        | 1         | 1.16%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TLA055CD | 1         | 1.16%   |
| Lenovo ThinkPad X1 Extreme 20MF000BUS       | 1         | 1.16%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS1QC00    | 1         | 1.16%   |
| Lenovo ThinkPad T495s 20QKS1812F            | 1         | 1.16%   |
| Lenovo ThinkPad T470p 20J7S0PM00            | 1         | 1.16%   |
| Lenovo ThinkPad T430 2349H2G                | 1         | 1.16%   |
| Lenovo ThinkPad T14s Gen 2i 20WM00B7MX      | 1         | 1.16%   |
| Lenovo ThinkPad P15 Gen 1 20ST005VRT        | 1         | 1.16%   |
| Lenovo ThinkPad P14s Gen 1 20Y1CTO1WW       | 1         | 1.16%   |
| Lenovo ThinkPad E14 Gen 3 20Y7003SGE        | 1         | 1.16%   |
| Lenovo ThinkPad E14 20RBCTO1WW              | 1         | 1.16%   |
| Lenovo ThinkBook 14 G3 ACL 21A2             | 1         | 1.16%   |
| Lenovo Legion 5P 15IMH05H 82AW              | 1         | 1.16%   |
| Lenovo Legion 5 15IMH05 82AU                | 1         | 1.16%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY        | 1         | 1.16%   |
| Lenovo IdeaPad 330-15ARR 81D2               | 1         | 1.16%   |
| khadas edge-v                               | 1         | 1.16%   |
| Intel S2600WTTR                             | 1         | 1.16%   |
| HUAWEI HN-WX9X                              | 1         | 1.16%   |
| HP ZBook 17 G2                              | 1         | 1.16%   |
| HP ProBook 455 G7                           | 1         | 1.16%   |
| HP ProBook 440 G7                           | 1         | 1.16%   |
| HP ProBook 440 G6                           | 1         | 1.16%   |
| HP EliteDesk 800 G4 SFF                     | 1         | 1.16%   |
| HP EliteBook Folio 9470m                    | 1         | 1.16%   |
| Gigabyte X570 AORUS MASTER                  | 1         | 1.16%   |
| Gigabyte X570 AORUS ELITE                   | 1         | 1.16%   |
| Gigabyte X399 DESIGNARE EX                  | 1         | 1.16%   |
| Gigabyte B550I AORUS PRO AX                 | 1         | 1.16%   |
| Gigabyte B450M DS3H                         | 1         | 1.16%   |
| Gigabyte 970A-UD3P                          | 1         | 1.16%   |
| friendlyelec nanopi-m4                      | 1         | 1.16%   |
| Dell Vostro 5490                            | 1         | 1.16%   |
| Dell OptiPlex 5490 AIO                      | 1         | 1.16%   |
| Dell OptiPlex 5080                          | 1         | 1.16%   |
| Dell Latitude E5430 vPro                    | 1         | 1.16%   |
| Dell Inspiron 3793                          | 1         | 1.16%   |
| Dell G5 5505                                | 1         | 1.16%   |
| Dell G3 3500                                | 1         | 1.16%   |
| Beckhoff Automation CX2033-0185             | 1         | 1.16%   |
| Beckhoff Automation CBxx63                  | 1         | 1.16%   |
| Avell High Performance A62 LIV              | 1         | 1.16%   |
| ASUS VivoBook_ASUSLaptop X512DA_F512DA      | 1         | 1.16%   |
| ASUS TUF GAMING B550-PLUS                   | 1         | 1.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo ThinkPad                            | 16        | 18.6%   |
| Unknown                                    | 10        | 11.63%  |
| HP EliteBook                               | 4         | 4.65%   |
| ASUS PRIME                                 | 4         | 4.65%   |
| RPi Raspberry                              | 3         | 3.49%   |
| HP ProBook                                 | 3         | 3.49%   |
| Lenovo Legion                              | 2         | 2.33%   |
| Lenovo IdeaPad                             | 2         | 2.33%   |
| Gigabyte X570                              | 2         | 2.33%   |
| Framework Laptop                           | 2         | 2.33%   |
| Dell OptiPlex                              | 2         | 2.33%   |
| RPi rpi                                    | 1         | 1.16%   |
| pine64 pinebook-pro-rk3399                 | 1         | 1.16%   |
| Notebook NS50                              | 1         | 1.16%   |
| MSI MS-7B86                                | 1         | 1.16%   |
| MSI GE76                                   | 1         | 1.16%   |
| Matsushita Electric Industrial CF-T2BW1AXR | 1         | 1.16%   |
| Lenovo XiaoXinPro-13ARE                    | 1         | 1.16%   |
| Lenovo ThinkBook                           | 1         | 1.16%   |
| khadas edge-v                              | 1         | 1.16%   |
| Intel S2600WTTR                            | 1         | 1.16%   |
| HUAWEI HN-WX9X                             | 1         | 1.16%   |
| HP ZBook                                   | 1         | 1.16%   |
| HP EliteDesk                               | 1         | 1.16%   |
| Gigabyte X399                              | 1         | 1.16%   |
| Gigabyte B550I                             | 1         | 1.16%   |
| Gigabyte B450M                             | 1         | 1.16%   |
| Gigabyte 970A-UD3P                         | 1         | 1.16%   |
| friendlyelec nanopi-m4                     | 1         | 1.16%   |
| Dell Vostro                                | 1         | 1.16%   |
| Dell Latitude                              | 1         | 1.16%   |
| Dell Inspiron                              | 1         | 1.16%   |
| Dell G5                                    | 1         | 1.16%   |
| Dell G3                                    | 1         | 1.16%   |
| Beckhoff Automation CX2033-0185            | 1         | 1.16%   |
| Beckhoff Automation CBxx63                 | 1         | 1.16%   |
| Avell High Performance A62                 | 1         | 1.16%   |
| ASUS VivoBook                              | 1         | 1.16%   |
| ASUS TUF                                   | 1         | 1.16%   |
| ASUS ROG                                   | 1         | 1.16%   |
| ASUS P8H77-M                               | 1         | 1.16%   |
| ASUS MINIPC                                | 1         | 1.16%   |
| ASUS 1215B                                 | 1         | 1.16%   |
| ASRock B450                                | 1         | 1.16%   |
| Apple MacBookPro12                         | 1         | 1.16%   |
| Apple MacBookPro10                         | 1         | 1.16%   |
| A-DATA XENIA159GENI72060                   | 1         | 1.16%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 23        | 26.74%  |
| 2020    | 21        | 24.42%  |
| 2019    | 11        | 12.79%  |
| Unknown | 9         | 10.47%  |
| 2018    | 6         | 6.98%   |
| 2017    | 4         | 4.65%   |
| 2013    | 4         | 4.65%   |
| 2016    | 2         | 2.33%   |
| 2015    | 2         | 2.33%   |
| 2022    | 1         | 1.16%   |
| 2012    | 1         | 1.16%   |
| 2011    | 1         | 1.16%   |
| 2003    | 1         | 1.16%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 48        | 55.81%  |
| Desktop        | 28        | 32.56%  |
| System on chip | 7         | 8.14%   |
| Mini pc        | 1         | 1.16%   |
| All in one     | 1         | 1.16%   |
| Server         | 1         | 1.16%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 86        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 35        | 40.23%  |
| 8.01-16.0       | 16        | 18.39%  |
| 32.01-64.0      | 13        | 14.94%  |
| 64.01-256.0     | 9         | 10.34%  |
| 4.01-8.0        | 7         | 8.05%   |
| 0.51-1.0        | 2         | 2.3%    |
| More than 256.0 | 1         | 1.15%   |
| 3.01-4.0        | 1         | 1.15%   |
| 24.01-32.0      | 1         | 1.15%   |
| 2.01-3.0        | 1         | 1.15%   |
| 1.01-2.0        | 1         | 1.15%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.51-1.0    | 31        | 36.05%  |
| 1.01-2.0    | 23        | 26.74%  |
| 0.01-0.5    | 16        | 18.6%   |
| 2.01-3.0    | 6         | 6.98%   |
| 3.01-4.0    | 3         | 3.49%   |
| 4.01-8.0    | 1         | 1.16%   |
| 32.01-64.0  | 1         | 1.16%   |
| 24.01-32.0  | 1         | 1.16%   |
| 64.01-256.0 | 1         | 1.16%   |
| 16.01-24.0  | 1         | 1.16%   |
| 8.01-16.0   | 1         | 1.16%   |
| 0           | 1         | 1.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 45        | 50%     |
| 2      | 22        | 24.44%  |
| 0      | 11        | 12.22%  |
| 3      | 5         | 5.56%   |
| 6      | 4         | 4.44%   |
| 4      | 2         | 2.22%   |
| 5      | 1         | 1.11%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 74        | 84.09%  |
| Yes       | 14        | 15.91%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 67        | 77.91%  |
| No        | 19        | 22.09%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 59        | 68.6%   |
| No        | 27        | 31.4%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 44        | 50.57%  |
| No        | 43        | 49.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 14        | 16.28%  |
| UK           | 11        | 12.79%  |
| Germany      | 9         | 10.47%  |
| Russia       | 8         | 9.3%    |
| Brazil       | 6         | 6.98%   |
| Ukraine      | 4         | 4.65%   |
| China        | 4         | 4.65%   |
| Austria      | 4         | 4.65%   |
| Poland       | 3         | 3.49%   |
| Japan        | 3         | 3.49%   |
| Switzerland  | 2         | 2.33%   |
| Sweden       | 2         | 2.33%   |
| Portugal     | 2         | 2.33%   |
| Turkey       | 1         | 1.16%   |
| Spain        | 1         | 1.16%   |
| Singapore    | 1         | 1.16%   |
| Saudi Arabia | 1         | 1.16%   |
| Peru         | 1         | 1.16%   |
| Netherlands  | 1         | 1.16%   |
| Jamaica      | 1         | 1.16%   |
| Italy        | 1         | 1.16%   |
| India        | 1         | 1.16%   |
| France       | 1         | 1.16%   |
| Denmark      | 1         | 1.16%   |
| Croatia      | 1         | 1.16%   |
| Belarus      | 1         | 1.16%   |
| Bangladesh   | 1         | 1.16%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Moscow                  | 5         | 5.21%   |
| Brighton                | 5         | 5.21%   |
| ЕЊta-ku               | 3         | 3.13%   |
| London                  | 3         | 3.13%   |
| Kyiv                    | 3         | 3.13%   |
| Zurich                  | 2         | 2.08%   |
| Vienna                  | 2         | 2.08%   |
| Seattle                 | 2         | 2.08%   |
| Rio de Janeiro          | 2         | 2.08%   |
| Rietberg                | 2         | 2.08%   |
| Graz                    | 2         | 2.08%   |
| Fuchu                   | 2         | 2.08%   |
| Egham                   | 2         | 2.08%   |
| Chicago                 | 2         | 2.08%   |
| Berlin                  | 2         | 2.08%   |
| Zaporizhzhya            | 1         | 1.04%   |
| Wuhan                   | 1         | 1.04%   |
| Worthing                | 1         | 1.04%   |
| Woodburn                | 1         | 1.04%   |
| Wieliczka               | 1         | 1.04%   |
| Washington              | 1         | 1.04%   |
| Vancouver               | 1         | 1.04%   |
| Trosa                   | 1         | 1.04%   |
| Thrissur                | 1         | 1.04%   |
| Teaneck                 | 1         | 1.04%   |
| Stuttgart               | 1         | 1.04%   |
| St Petersburg           | 1         | 1.04%   |
| Sollentuna              | 1         | 1.04%   |
| Slavonski Brod          | 1         | 1.04%   |
| Singapore               | 1         | 1.04%   |
| Shanghai                | 1         | 1.04%   |
| Santa Monica            | 1         | 1.04%   |
| San Francisco           | 1         | 1.04%   |
| Ruthin                  | 1         | 1.04%   |
| Rostov-on-Don           | 1         | 1.04%   |
| Riyadh                  | 1         | 1.04%   |
| Resana                  | 1         | 1.04%   |
| Poulsbo                 | 1         | 1.04%   |
| Pobiedziska             | 1         | 1.04%   |
| Omaha                   | 1         | 1.04%   |
| Northeim                | 1         | 1.04%   |
| New York                | 1         | 1.04%   |
| Montclair               | 1         | 1.04%   |
| Minsk                   | 1         | 1.04%   |
| Milan                   | 1         | 1.04%   |
| Maia                    | 1         | 1.04%   |
| Madrid                  | 1         | 1.04%   |
| Lubin                   | 1         | 1.04%   |
| Lima                    | 1         | 1.04%   |
| Lake Forest             | 1         | 1.04%   |
| Kunitachi               | 1         | 1.04%   |
| Kingston                | 1         | 1.04%   |
| Khabarovsk              | 1         | 1.04%   |
| JoГЈo Pessoa          | 1         | 1.04%   |
| Jaboatao dos Guararapes | 1         | 1.04%   |
| Istanbul                | 1         | 1.04%   |
| Ilhavo                  | 1         | 1.04%   |
| Hoogeveen               | 1         | 1.04%   |
| Hangzhou                | 1         | 1.04%   |
| Guangzhou Shi           | 1         | 1.04%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 24        | 37     | 22.43%  |
| Samsung Electronics | 22        | 31     | 20.56%  |
| Toshiba             | 11        | 20     | 10.28%  |
| HGST                | 7         | 20     | 6.54%   |
| Seagate             | 6         | 10     | 5.61%   |
| Crucial             | 6         | 13     | 5.61%   |
| Kingston            | 5         | 8      | 4.67%   |
| SK Hynix            | 4         | 4      | 3.74%   |
| Intel               | 4         | 5      | 3.74%   |
| A-DATA Technology   | 4         | 4      | 3.74%   |
| Micron Technology   | 2         | 3      | 1.87%   |
| Apple               | 2         | 2      | 1.87%   |
| SSSTC               | 1         | 1      | 0.93%   |
| Solid State Storage | 1         | 1      | 0.93%   |
| Silicon Motion      | 1         | 1      | 0.93%   |
| SanDisk             | 1         | 1      | 0.93%   |
| PNY                 | 1         | 1      | 0.93%   |
| LITEON              | 1         | 1      | 0.93%   |
| KIOXIA              | 1         | 1      | 0.93%   |
| GOODRAM             | 1         | 1      | 0.93%   |
| Fujitsu             | 1         | 2      | 0.93%   |
| Apacer              | 1         | 1      | 0.93%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB                           | 5         | 4.2%    |
| HGST HTS725050A7E630 500GB                         | 4         | 3.36%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB               | 3         | 2.52%   |
| Toshiba MQ04ABF100 1TB                             | 3         | 2.52%   |
| Samsung HM251JX 250GB                              | 3         | 2.52%   |
| HGST HTS721010A9E630 1TB                           | 3         | 2.52%   |
| WDC WDS100T3X0C-00SJG0 1TB                         | 2         | 1.68%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB                 | 2         | 1.68%   |
| WDC PC SN730 NVMe 1024GB                           | 2         | 1.68%   |
| Samsung SSD 850 EVO 250GB                          | 2         | 1.68%   |
| Samsung MZVLB512HBJQ-000L7 512GB                   | 2         | 1.68%   |
| WDC WDS500G1X0E-00AFY0 500GB                       | 1         | 0.84%   |
| WDC WDS250G2B0C-00PXH0 250GB                       | 1         | 0.84%   |
| WDC WDS100T2B0A-00SM50 1TB                         | 1         | 0.84%   |
| WDC WD60EFRX-68TGBN1 6TB                           | 1         | 0.84%   |
| WDC WD5002ABYS-18B1B0 500GB                        | 1         | 0.84%   |
| WDC WD40EZRZ-75GXCB0 4TB                           | 1         | 0.84%   |
| WDC WD30EFRX-68EUZN0 3TB                           | 1         | 0.84%   |
| WDC WD20EFRX-68AX9N0 2TB                           | 1         | 0.84%   |
| WDC WD120EFAX-68UNTN0 12TB                         | 1         | 0.84%   |
| WDC WD10SPZX-60Z10T0 1TB                           | 1         | 0.84%   |
| WDC WD10SPZX-21Z10T0 1TB                           | 1         | 0.84%   |
| WDC WD10JPVX-00JC3T0 1TB                           | 1         | 0.84%   |
| WDC WD10JMVW-11AJGS3 1TB                           | 1         | 0.84%   |
| WDC WD10EZEX-60WN4A0 1TB                           | 1         | 0.84%   |
| WDC WD10EZEX-00RKKA0 1TB                           | 1         | 0.84%   |
| WDC WD10EARX-00N0YB0 1TB                           | 1         | 0.84%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB               | 1         | 0.84%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB               | 1         | 0.84%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB               | 1         | 0.84%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB               | 1         | 0.84%   |
| Toshiba MQ01ABD100 1TB                             | 1         | 0.84%   |
| Toshiba MG09ACA18TE 18TB                           | 1         | 0.84%   |
| Toshiba KXG6APNV2T04 2TB                           | 1         | 0.84%   |
| SSSTC CL1-3D256-Q11 NVMe 256GB                     | 1         | 0.84%   |
| Solid State Storage CL1-3D128-Q11 NVMe SSSTC 128GB | 1         | 0.84%   |
| SK Hynix PC300 HFS512GD9MND-5510A 512GB            | 1         | 0.84%   |
| SK Hynix HFS128G39TND-N210A 128GB                  | 1         | 0.84%   |
| SK Hynix BC511 NVMe 256GB                          | 1         | 0.84%   |
| SK Hynix BC511 HFM256GDJTNI-82A0A 256GB            | 1         | 0.84%   |
| Silicon Motion NE-256 256GB                        | 1         | 0.84%   |
| Seagate ST5000LM000-2AN170 5TB                     | 1         | 0.84%   |
| Seagate ST4000DM000-1F2168 4TB                     | 1         | 0.84%   |
| Seagate ST3750640AS 752GB                          | 1         | 0.84%   |
| Seagate ST32000641AS 2TB                           | 1         | 0.84%   |
| Seagate ST3000DM007-1WY10G 3TB                     | 1         | 0.84%   |
| Seagate ST3000DM001-1ER166 3TB                     | 1         | 0.84%   |
| Seagate ST1000LM035-1RK172 1TB                     | 1         | 0.84%   |
| SanDisk SDSSDH3500G 500GB                          | 1         | 0.84%   |
| Samsung SSD 970 EVO Plus 1TB                       | 1         | 0.84%   |
| Samsung SSD 970 EVO 1TB                            | 1         | 0.84%   |
| Samsung SSD 870 QVO 1TB                            | 1         | 0.84%   |
| Samsung SSD 860 EVO M.2 250GB                      | 1         | 0.84%   |
| Samsung SSD 860 EVO 500GB                          | 1         | 0.84%   |
| Samsung SSD 860 EVO 4TB                            | 1         | 0.84%   |
| Samsung SSD 860 EVO 250GB                          | 1         | 0.84%   |
| Samsung SSD 850 EVO 500GB                          | 1         | 0.84%   |
| Samsung SSD 840 PRO Series 128GB                   | 1         | 0.84%   |
| Samsung MZVLW256HEHP-000L7 256GB                   | 1         | 0.84%   |
| Samsung MZVLB512HBJQ-000L2 512GB                   | 1         | 0.84%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 10        | 19     | 27.03%  |
| WDC                 | 9         | 15     | 24.32%  |
| HGST                | 7         | 20     | 18.92%  |
| Seagate             | 6         | 10     | 16.22%  |
| Samsung Electronics | 4         | 7      | 10.81%  |
| Fujitsu             | 1         | 2      | 2.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 10     | 28%     |
| Crucial             | 3         | 8      | 12%     |
| Kingston            | 2         | 4      | 8%      |
| Intel               | 2         | 3      | 8%      |
| Apple               | 2         | 2      | 8%      |
| A-DATA Technology   | 2         | 2      | 8%      |
| WDC                 | 1         | 2      | 4%      |
| SK Hynix            | 1         | 1      | 4%      |
| SanDisk             | 1         | 1      | 4%      |
| Micron Technology   | 1         | 1      | 4%      |
| LITEON              | 1         | 1      | 4%      |
| GOODRAM             | 1         | 1      | 4%      |
| Apacer              | 1         | 1      | 4%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 44        | 58     | 46.32%  |
| HDD  | 26        | 73     | 27.37%  |
| SSD  | 25        | 37     | 26.32%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 44        | 58     | 50.57%  |
| SATA | 43        | 110    | 49.43%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 29        | 63     | 50.88%  |
| 0.51-1.0   | 16        | 27     | 28.07%  |
| 3.01-4.0   | 3         | 4      | 5.26%   |
| 1.01-2.0   | 3         | 3      | 5.26%   |
| 2.01-3.0   | 2         | 3      | 3.51%   |
| 10.01-20.0 | 2         | 3      | 3.51%   |
| 4.01-10.0  | 2         | 7      | 3.51%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 23        | 25.56%  |
| 251-500        | 22        | 24.44%  |
| 501-1000       | 13        | 14.44%  |
| 1-20           | 10        | 11.11%  |
| 21-50          | 8         | 8.89%   |
| 51-100         | 7         | 7.78%   |
| 1001-2000      | 3         | 3.33%   |
| More than 3000 | 2         | 2.22%   |
| 2001-3000      | 2         | 2.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 57        | 63.33%  |
| 21-50     | 23        | 25.56%  |
| 101-250   | 5         | 5.56%   |
| 251-500   | 1         | 1.11%   |
| 1001-2000 | 1         | 1.11%   |
| 501-1000  | 1         | 1.11%   |
| 51-100    | 1         | 1.11%   |
| 0         | 1         | 1.11%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| HGST HTS725050A7E630 500GB        | 4         | 9      | 40%     |
| WDC WD60EFRX-68TGBN1 6TB          | 1         | 3      | 10%     |
| WDC WD5002ABYS-18B1B0 500GB       | 1         | 1      | 10%     |
| WDC WD10SPZX-60Z10T0 1TB          | 1         | 1      | 10%     |
| Samsung Electronics HM251JX 250GB | 1         | 1      | 10%     |
| HGST HTS721010A9E630 1TB          | 1         | 6      | 10%     |
| Fujitsu MHS2040AT D 40GB          | 1         | 2      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 4         | 15     | 44.44%  |
| WDC                 | 3         | 5      | 33.33%  |
| Samsung Electronics | 1         | 1      | 11.11%  |
| Fujitsu             | 1         | 2      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 4         | 15     | 44.44%  |
| WDC                 | 3         | 5      | 33.33%  |
| Samsung Electronics | 1         | 1      | 11.11%  |
| Fujitsu             | 1         | 2      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 23     | 100%    |

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
| Works    | 73        | 142    | 86.9%   |
| Malfunc  | 8         | 23     | 9.52%   |
| Detected | 3         | 3      | 3.57%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 34        | 30.91%  |
| AMD                            | 22        | 20%     |
| Sandisk                        | 16        | 14.55%  |
| Samsung Electronics            | 15        | 13.64%  |
| SK Hynix                       | 3         | 2.73%   |
| Silicon Motion                 | 3         | 2.73%   |
| Kingston Technology Company    | 3         | 2.73%   |
| Solid State Storage Technology | 2         | 1.82%   |
| Micron/Crucial Technology      | 2         | 1.82%   |
| Micron Technology              | 2         | 1.82%   |
| ADATA Technology               | 2         | 1.82%   |
| VMware                         | 1         | 0.91%   |
| Toshiba                        | 1         | 0.91%   |
| Phison Electronics             | 1         | 0.91%   |
| Marvell Technology Group       | 1         | 0.91%   |
| KIOXIA                         | 1         | 0.91%   |
| ASMedia Technology             | 1         | 0.91%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 17        | 14.05%  |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 11        | 9.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 10        | 8.26%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 4.96%   |
| Unknown                                                                        | 6         | 4.96%   |
| AMD 400 Series Chipset SATA Controller                                         | 5         | 4.13%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 3.31%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 4         | 3.31%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 3         | 2.48%   |
| AMD 500 Series Chipset SATA Controller                                         | 3         | 2.48%   |
| SK Hynix BC511                                                                 | 2         | 1.65%   |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 2         | 1.65%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 1.65%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 1.65%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 1.65%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.65%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 2         | 1.65%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 2         | 1.65%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2         | 1.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 1.65%   |
| VMware SATA AHCI controller                                                    | 1         | 0.83%   |
| VMware NVMe SSD Controller                                                     | 1         | 0.83%   |
| Toshiba XG6 NVMe SSD Controller                                                | 1         | 0.83%   |
| SK Hynix PC300 NVMe Solid State Drive 512GB                                    | 1         | 0.83%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 0.83%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1         | 0.83%   |
| Samsung SM951 AHCI                                                             | 1         | 0.83%   |
| Phison E12 NVMe Controller                                                     | 1         | 0.83%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1         | 0.83%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 1         | 0.83%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                          | 1         | 0.83%   |
| KIOXIA unknown                                                                 | 1         | 0.83%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 1         | 0.83%   |
| Kingston Company A2000 NVMe SSD                                                | 1         | 0.83%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1         | 0.83%   |
| Intel SSD 660P Series                                                          | 1         | 0.83%   |
| Intel NVMe Optane Memory Series                                                | 1         | 0.83%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 1         | 0.83%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 0.83%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 0.83%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1         | 0.83%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 0.83%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 1         | 0.83%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 1         | 0.83%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 0.83%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 1         | 0.83%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 1         | 0.83%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]    | 1         | 0.83%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]    | 1         | 0.83%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 1         | 0.83%   |
| AMD X399 Series Chipset SATA Controller                                        | 1         | 0.83%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 1         | 0.83%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 52        | 48.15%  |
| SATA | 51        | 47.22%  |
| IDE  | 4         | 3.7%    |
| RAID | 1         | 0.93%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 42        | 48.28%  |
| AMD     | 29        | 33.33%  |
| Unknown | 9         | 10.34%  |
| ARM     | 7         | 8.05%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
|                                                 | 9         | 10.34%  |
| Intel Core i7-3520M CPU @ 2.90GHz               | 4         | 4.6%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 4         | 4.6%    |
| ARM Cortex-A72 r0p3                             | 4         | 4.6%    |
| Intel Core i7-10750H CPU @ 2.60GHz              | 3         | 3.45%   |
| Intel Core i5-10210U CPU @ 1.60GHz              | 3         | 3.45%   |
| AMD Ryzen 5 5600G with Radeon Graphics          | 3         | 3.45%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 2         | 2.3%    |
| Intel Core i7-7600U CPU @ 2.80GHz               | 2         | 2.3%    |
| Intel Core i5-10500T CPU @ 2.30GHz              | 2         | 2.3%    |
| Intel Core i5-10300H CPU @ 2.50GHz              | 2         | 2.3%    |
| ARM Cortex-A72 r0p2                             | 2         | 2.3%    |
| AMD Ryzen 7 4700U with Radeon Graphics          | 2         | 2.3%    |
| AMD Ryzen 5 PRO 3500U w/ Radeon Vega Mobile Gfx | 2         | 2.3%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 2         | 2.3%    |
| Intel Xeon W-10885M CPU @ 2.40GHz               | 1         | 1.15%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz             | 1         | 1.15%   |
| Intel Pentium M processor 1000MHz               | 1         | 1.15%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 1         | 1.15%   |
| Intel Core i7-8700 CPU @ 3.20GHz                | 1         | 1.15%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 1.15%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 1.15%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz              | 1         | 1.15%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz              | 1         | 1.15%   |
| Intel Core i7-3770 CPU @ 3.40GHz                | 1         | 1.15%   |
| Intel Core i7-3687U CPU @ 2.10GHz               | 1         | 1.15%   |
| Intel Core i7-3615QM CPU @ 2.30GHz              | 1         | 1.15%   |
| Intel Core i7-10870H CPU @ 2.20GHz              | 1         | 1.15%   |
| Intel Core i7-10700 CPU @ 2.90GHz               | 1         | 1.15%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz              | 1         | 1.15%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 1         | 1.15%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 1         | 1.15%   |
| Intel Core i5-5257U CPU @ 2.70GHz               | 1         | 1.15%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 1         | 1.15%   |
| Intel Atom CPU E3827 @ 1.74GHz                  | 1         | 1.15%   |
| ARM Cortex-A53 r0p4                             | 1         | 1.15%   |
| AMD Ryzen Threadripper 1950X 16-Core Processor  | 1         | 1.15%   |
| AMD Ryzen Embedded V1202B with Radeon Vega Gfx  | 1         | 1.15%   |
| AMD Ryzen 9 5950X 16-Core Processor             | 1         | 1.15%   |
| AMD Ryzen 9 5900X 12-Core Processor             | 1         | 1.15%   |
| AMD Ryzen 9 3950X 16-Core Processor             | 1         | 1.15%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 1         | 1.15%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics      | 1         | 1.15%   |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx | 1         | 1.15%   |
| AMD Ryzen 7 5800X 8-Core Processor              | 1         | 1.15%   |
| AMD Ryzen 7 5700U with Radeon Graphics          | 1         | 1.15%   |
| AMD Ryzen 7 4800U with Radeon Graphics          | 1         | 1.15%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 1         | 1.15%   |
| AMD Ryzen 7 2700X Eight-Core Processor          | 1         | 1.15%   |
| AMD Ryzen 5 5500U with Radeon Graphics          | 1         | 1.15%   |
| AMD Ryzen 5 4600H with Radeon Graphics          | 1         | 1.15%   |
| AMD Ryzen 5 2600X Six-Core Processor            | 1         | 1.15%   |
| AMD Ryzen 5 2600 Six-Core Processor             | 1         | 1.15%   |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx   | 1         | 1.15%   |
| AMD FX-8320E Eight-Core Processor               | 1         | 1.15%   |
| AMD E-450 APU with Radeon HD Graphics           | 1         | 1.15%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 24        | 27.59%  |
| Other                  | 13        | 14.94%  |
| Intel Core i5          | 10        | 11.49%  |
| AMD Ryzen 5            | 9         | 10.34%  |
| ARM Cortex             | 7         | 8.05%   |
| AMD Ryzen 7            | 7         | 8.05%   |
| AMD Ryzen 9            | 4         | 4.6%    |
| Intel Xeon             | 2         | 2.3%    |
| AMD Ryzen 7 PRO        | 2         | 2.3%    |
| AMD Ryzen 5 PRO        | 2         | 2.3%    |
| Intel Pentium M        | 1         | 1.15%   |
| Intel Atom             | 1         | 1.15%   |
| AMD Ryzen Threadripper | 1         | 1.15%   |
| AMD Ryzen Embedded     | 1         | 1.15%   |
| AMD Ryzen 3            | 1         | 1.15%   |
| AMD FX                 | 1         | 1.15%   |
| AMD E                  | 1         | 1.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 18        | 20.93%  |
| Unknown | 15        | 17.44%  |
| 2       | 13        | 15.12%  |
| 8       | 11        | 12.79%  |
| 6       | 9         | 10.47%  |
| 16      | 7         | 8.14%   |
| 12      | 7         | 8.14%   |
| 32      | 3         | 3.49%   |
| 24      | 2         | 2.33%   |
| 1       | 1         | 1.16%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 75        | 86.21%  |
| Unknown | 11        | 12.64%  |
| 2       | 1         | 1.15%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 40        | 46.51%  |
| 1       | 30        | 34.88%  |
| Unknown | 16        | 18.6%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 17        | 19.77%  |
| KabyLake   | 12        | 13.95%  |
| CometLake  | 10        | 11.63%  |
| Zen+       | 8         | 9.3%    |
| Zen 2      | 8         | 9.3%    |
| IvyBridge  | 8         | 9.3%    |
| Zen 3      | 6         | 6.98%   |
| TigerLake  | 4         | 4.65%   |
| Zen        | 3         | 3.49%   |
| Haswell    | 2         | 2.33%   |
| Broadwell  | 2         | 2.33%   |
| Skylake    | 1         | 1.16%   |
| Silvermont | 1         | 1.16%   |
| Piledriver | 1         | 1.16%   |
| P6         | 1         | 1.16%   |
| IceLake    | 1         | 1.16%   |
| Bobcat     | 1         | 1.16%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 36        | 39.13%  |
| AMD                        | 27        | 29.35%  |
| Nvidia                     | 26        | 28.26%  |
| VMware                     | 1         | 1.09%   |
| Matrox Electronics Systems | 1         | 1.09%   |
| ASPEED Technology          | 1         | 1.09%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                            | 6         | 6.45%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]  | 5         | 5.38%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                             | 4         | 4.3%    |
| Intel CometLake-U GT2 [UHD Graphics]                                  | 4         | 4.3%    |
| Intel CometLake-H GT2 [UHD Graphics]                                  | 4         | 4.3%    |
| Intel 3rd Gen Core processor Graphics Controller                      | 4         | 4.3%    |
| Nvidia TU117M                                                         | 3         | 3.23%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                             | 3         | 3.23%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                              | 3         | 3.23%   |
| AMD Cezanne                                                           | 3         | 3.23%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                            | 2         | 2.15%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                            | 2         | 2.15%   |
| Nvidia GP108M [GeForce MX230]                                         | 2         | 2.15%   |
| Nvidia GK208B [GeForce GT 710]                                        | 2         | 2.15%   |
| Intel HD Graphics 620                                                 | 2         | 2.15%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                              | 2         | 2.15%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller           | 2         | 2.15%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]      | 2         | 2.15%   |
| AMD Lucienne                                                          | 2         | 2.15%   |
| Nvidia TU104GLM [Quadro RTX 5000 Mobile / Max-Q]                      | 1         | 1.08%   |
| Nvidia GT218 [GeForce 210]                                            | 1         | 1.08%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                            | 1         | 1.08%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                               | 1         | 1.08%   |
| Nvidia GP107GL [Quadro P620]                                          | 1         | 1.08%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                    | 1         | 1.08%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                   | 1         | 1.08%   |
| Nvidia GM206 [GeForce GTX 960]                                        | 1         | 1.08%   |
| Nvidia GM108M [GeForce MX130]                                         | 1         | 1.08%   |
| Nvidia GM108M [GeForce 940MX]                                         | 1         | 1.08%   |
| Nvidia GM107M [GeForce GTX 860M]                                      | 1         | 1.08%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                     | 1         | 1.08%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                           | 1         | 1.08%   |
| Nvidia GK107GLM [Quadro K1100M]                                       | 1         | 1.08%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                       | 1         | 1.08%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)     | 1         | 1.08%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                            | 1         | 1.08%   |
| Intel Skylake GT2 [HD Graphics 520]                                   | 1         | 1.08%   |
| Intel JasperLake [UHD Graphics]                                       | 1         | 1.08%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                | 1         | 1.08%   |
| Intel Iris Plus Graphics G7                                           | 1         | 1.08%   |
| Intel Iris Graphics 6100                                              | 1         | 1.08%   |
| Intel HD Graphics 630                                                 | 1         | 1.08%   |
| Intel Comet Lake-H WS GT2 Integrated UHD Graphics Controller          | 1         | 1.08%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                             | 1         | 1.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display          | 1         | 1.08%   |
| Intel 82852/855GM Integrated Graphics Device                          | 1         | 1.08%   |
| ASPEED Technology ASPEED Graphics Family                              | 1         | 1.08%   |
| AMD Wrestler [Radeon HD 6320]                                         | 1         | 1.08%   |
| AMD RV630 XT [Radeon HD 2600 XT]                                      | 1         | 1.08%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM] | 1         | 1.08%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]               | 1         | 1.08%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]               | 1         | 1.08%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                    | 1         | 1.08%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]   | 1         | 1.08%   |
| Unknown                                                               | 1         | 1.08%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 23        | 26.44%  |
| 1 x Intel      | 19        | 21.84%  |
| Intel + Nvidia | 15        | 17.24%  |
| Other          | 13        | 14.94%  |
| 1 x Nvidia     | 11        | 12.64%  |
| 2 x AMD        | 1         | 1.15%   |
| 1 x VMware     | 1         | 1.15%   |
| 1 x Matrox     | 1         | 1.15%   |
| Intel + AMD    | 1         | 1.15%   |
| 1 x ASPEED     | 1         | 1.15%   |
| AMD + Nvidia   | 1         | 1.15%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 56        | 65.12%  |
| Proprietary | 17        | 19.77%  |
| Unknown     | 13        | 15.12%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 64        | 72.73%  |
| 1.01-2.0   | 7         | 7.95%   |
| 0.51-1.0   | 6         | 6.82%   |
| 0.01-0.5   | 5         | 5.68%   |
| 3.01-4.0   | 4         | 4.55%   |
| 7.01-8.0   | 1         | 1.14%   |
| 2.01-3.0   | 1         | 1.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| LG Display          | 10        | 14.71%  |
| BOE                 | 9         | 13.24%  |
| AU Optronics        | 7         | 10.29%  |
| Philips             | 4         | 5.88%   |
| Hewlett-Packard     | 4         | 5.88%   |
| Goldstar            | 4         | 5.88%   |
| Chimei Innolux      | 4         | 5.88%   |
| Dell                | 3         | 4.41%   |
| Samsung Electronics | 2         | 2.94%   |
| RTK                 | 2         | 2.94%   |
| LG Electronics      | 2         | 2.94%   |
| Lenovo              | 2         | 2.94%   |
| Apple               | 2         | 2.94%   |
| ViewSonic           | 1         | 1.47%   |
| Sony                | 1         | 1.47%   |
| Sharp               | 1         | 1.47%   |
| SDC                 | 1         | 1.47%   |
| PANDA               | 1         | 1.47%   |
| LGD                 | 1         | 1.47%   |
| InfoVision          | 1         | 1.47%   |
| Iiyama              | 1         | 1.47%   |
| HJW                 | 1         | 1.47%   |
| Eizo                | 1         | 1.47%   |
| CSO                 | 1         | 1.47%   |
| BenQ                | 1         | 1.47%   |
| AOC                 | 1         | 1.47%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0258 1600x900 350x190mm 15.7-inch          | 3         | 4.29%   |
| RTK WCS Display RTK1A1B 1920x1080 344x195mm 15.6-inch                | 2         | 2.86%   |
| Philips LCD Monitor PHL08C3 1920x1080 600x340mm 27.2-inch            | 2         | 2.86%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch         | 2         | 2.86%   |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                | 2         | 2.86%   |
| ViewSonic LCD Monitor VSCD22B 1920x1080 520x290mm 23.4-inch          | 1         | 1.43%   |
| Sony TV SNY4B03 1920x1080 930x520mm 41.9-inch                        | 1         | 1.43%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 380x210mm 17.1-inch              | 1         | 1.43%   |
| SDC LCD Monitor 3520x1080                                            | 1         | 1.43%   |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                     | 1         | 1.43%   |
| Samsung Electronics LCD Monitor SDC3754 1600x900 380x210mm 17.1-inch | 1         | 1.43%   |
| Philips PHL 273V7 PHLC156 1920x1080 600x340mm 27.2-inch              | 1         | 1.43%   |
| Philips LCD Monitor 271P4 3520x1080                                  | 1         | 1.43%   |
| Philips LCD Monitor 271P4                                            | 1         | 1.43%   |
| PANDA LCD Monitor NCP004F 1920x1080 310x170mm 13.9-inch              | 1         | 1.43%   |
| LGD LCD Monitor 1920x1080                                            | 1         | 1.43%   |
| LG Electronics LCD Monitor LX20D 1600x1200                           | 1         | 1.43%   |
| LG Electronics LCD Monitor LG Ultra HD 11520x2160                    | 1         | 1.43%   |
| LG Electronics LCD Monitor LG Ultra HD                               | 1         | 1.43%   |
| LG Display LCD Monitor LGD062E 1920x1080 340x190mm 15.3-inch         | 1         | 1.43%   |
| LG Display LCD Monitor LGD060A 1920x1080 290x170mm 13.2-inch         | 1         | 1.43%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch         | 1         | 1.43%   |
| LG Display LCD Monitor LGD05F1 1920x1080 310x170mm 13.9-inch         | 1         | 1.43%   |
| LG Display LCD Monitor LGD033E 1366x768 310x170mm 13.9-inch          | 1         | 1.43%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                | 1         | 1.43%   |
| Lenovo LEN P44w-10 LEN61D5 3840x1200 1050x330mm 43.3-inch            | 1         | 1.43%   |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch         | 1         | 1.43%   |
| Iiyama PL2474H IVM6146 1920x1080 520x290mm 23.4-inch                 | 1         | 1.43%   |
| HJW HDMI TO USB HJW0001 1920x1080 700x390mm 31.5-inch                | 1         | 1.43%   |
| Hewlett-Packard LCD Monitor LA2306 3520x1080                         | 1         | 1.43%   |
| Hewlett-Packard LA2306 HWP2949 1920x1080 510x290mm 23.1-inch         | 1         | 1.43%   |
| Hewlett-Packard E242 HWP326E 1920x1200 520x320mm 24.0-inch           | 1         | 1.43%   |
| Hewlett-Packard E233 HPN345F 1920x1080 510x290mm 23.1-inch           | 1         | 1.43%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch           | 1         | 1.43%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch           | 1         | 1.43%   |
| Goldstar 27GK750F GSM770F 1920x1080 600x340mm 27.2-inch              | 1         | 1.43%   |
| Goldstar 23EA53 GSM59A8 1920x1080 510x290mm 23.1-inch                | 1         | 1.43%   |
| Eizo FX2431 ENC2036 1920x1200 520x330mm 24.2-inch                    | 1         | 1.43%   |
| Dell U2718Q DELA0EC 3840x2160 610x350mm 27.7-inch                    | 1         | 1.43%   |
| Dell U2518D DEL413C 2560x1440 550x310mm 24.9-inch                    | 1         | 1.43%   |
| Dell LCD Monitor DEL9408 1920x1080 520x290mm 23.4-inch               | 1         | 1.43%   |
| CSO LCD Monitor CSO1500 3840x2160 340x190mm 15.3-inch                | 1         | 1.43%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 280x180mm 13.1-inch     | 1         | 1.43%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 340x190mm 15.3-inch     | 1         | 1.43%   |
| Chimei Innolux LCD Monitor CMN1484 1600x900 310x170mm 13.9-inch      | 1         | 1.43%   |
| Chimei Innolux LCD Monitor CMN13A2 1920x1080 290x170mm 13.2-inch     | 1         | 1.43%   |
| BOE LCD Monitor BOE0982 3840x2160 310x170mm 13.9-inch                | 1         | 1.43%   |
| BOE LCD Monitor BOE08D7 1920x1080 310x170mm 13.9-inch                | 1         | 1.43%   |
| BOE LCD Monitor BOE084D 1920x1080 340x190mm 15.3-inch                | 1         | 1.43%   |
| BOE LCD Monitor BOE07F1 1920x1080 340x190mm 15.3-inch                | 1         | 1.43%   |
| BOE LCD Monitor BOE0792 1920x1080 340x190mm 15.3-inch                | 1         | 1.43%   |
| BOE LCD Monitor BOE075A 1366x768 310x170mm 13.9-inch                 | 1         | 1.43%   |
| BOE LCD Monitor BOE0747 1920x1080 340x190mm 15.3-inch                | 1         | 1.43%   |
| BenQ GW2280 BNQ78E8 1920x1080 480x270mm 21.7-inch                    | 1         | 1.43%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 340x190mm 15.3-inch       | 1         | 1.43%   |
| AU Optronics LCD Monitor AUO5A2D 1920x1080 290x170mm 13.2-inch       | 1         | 1.43%   |
| AU Optronics LCD Monitor AUO5699 1920x1080 340x190mm 15.3-inch       | 1         | 1.43%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch       | 1         | 1.43%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch        | 1         | 1.43%   |
| AU Optronics LCD Monitor AUO2026 2560x1600 290x180mm 13.4-inch       | 1         | 1.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 38        | 56.72%  |
| 3840x2160 (4K)    | 6         | 8.96%   |
| 1600x900 (HD+)    | 6         | 8.96%   |
| 1920x1200 (WUXGA) | 3         | 4.48%   |
| 2560x1600         | 2         | 2.99%   |
| 2256x1504         | 2         | 2.99%   |
| 1366x768 (WXGA)   | 2         | 2.99%   |
| Unknown           | 2         | 2.99%   |
| 3840x1200         | 1         | 1.49%   |
| 3520x1080         | 1         | 1.49%   |
| 2560x1440 (QHD)   | 1         | 1.49%   |
| 2160x1440         | 1         | 1.49%   |
| 1600x1200         | 1         | 1.49%   |
| 11520x2160        | 1         | 1.49%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 19        | 28.79%  |
| 15      | 14        | 21.21%  |
| 27      | 7         | 10.61%  |
| 23      | 6         | 9.09%   |
| Unknown | 5         | 7.58%   |
| 24      | 4         | 6.06%   |
| 17      | 3         | 4.55%   |
| 12      | 2         | 3.03%   |
| 43      | 1         | 1.52%   |
| 41      | 1         | 1.52%   |
| 32      | 1         | 1.52%   |
| 31      | 1         | 1.52%   |
| 22      | 1         | 1.52%   |
| 21      | 1         | 1.52%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 25        | 38.46%  |
| 501-600     | 15        | 23.08%  |
| 201-300     | 10        | 15.38%  |
| Unknown     | 5         | 7.69%   |
| 351-400     | 3         | 4.62%   |
| 601-700     | 2         | 3.08%   |
| 401-500     | 2         | 3.08%   |
| 701-800     | 1         | 1.54%   |
| 1001-1500   | 1         | 1.54%   |
| 901-1000    | 1         | 1.54%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 46        | 77.97%  |
| 16/10   | 6         | 10.17%  |
| Unknown | 4         | 6.78%   |
| 3/2     | 2         | 3.39%   |
| 3.18    | 1         | 1.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 15        | 22.73%  |
| 201-250        | 9         | 13.64%  |
| 91-100         | 9         | 13.64%  |
| 301-350        | 7         | 10.61%  |
| 101-110        | 5         | 7.58%   |
| Unknown        | 5         | 7.58%   |
| 71-80          | 4         | 6.06%   |
| 251-300        | 3         | 4.55%   |
| 121-130        | 3         | 4.55%   |
| 61-70          | 2         | 3.03%   |
| 351-500        | 2         | 3.03%   |
| 501-1000       | 2         | 3.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 21        | 32.81%  |
| 51-100        | 17        | 26.56%  |
| 161-240       | 12        | 18.75%  |
| 101-120       | 7         | 10.94%  |
| Unknown       | 5         | 7.81%   |
| More than 240 | 2         | 3.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 45        | 51.14%  |
| 0     | 33        | 37.5%   |
| 2     | 9         | 10.23%  |
| 3     | 1         | 1.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 58        | 44.96%  |
| Realtek Semiconductor | 40        | 31.01%  |
| TP-Link               | 5         | 3.88%   |
| Ralink Technology     | 4         | 3.1%    |
| Hewlett-Packard       | 4         | 3.1%    |
| Broadcom              | 4         | 3.1%    |
| Qualcomm Atheros      | 3         | 2.33%   |
| Edimax Technology     | 2         | 1.55%   |
| D-Link System         | 2         | 1.55%   |
| Mellanox Technologies | 1         | 0.78%   |
| Lenovo                | 1         | 0.78%   |
| Google                | 1         | 0.78%   |
| Emulex                | 1         | 0.78%   |
| BUFFALO               | 1         | 0.78%   |
| ASUSTek Computer      | 1         | 0.78%   |
| Arduino SA            | 1         | 0.78%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 33        | 20.89%  |
| Intel Wi-Fi 6 AX200                                                        | 8         | 5.06%   |
| Intel Comet Lake PCH CNVi WiFi                                             | 6         | 3.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 6         | 3.8%    |
| Intel Wireless-AC 9260                                                     | 5         | 3.16%   |
| Intel Wireless 8265 / 8275                                                 | 5         | 3.16%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 5         | 3.16%   |
| Intel I211 Gigabit Network Connection                                      | 4         | 2.53%   |
| Intel I210 Gigabit Network Connection                                      | 4         | 2.53%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                          | 4         | 2.53%   |
| HP hs2350 HSPA+ Mobile Broadband Module Network Adapter                    | 4         | 2.53%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 3         | 1.9%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 3         | 1.9%    |
| Realtek RTL8125 2.5GbE Controller                                          | 3         | 1.9%    |
| Intel Wi-Fi 6 AX201                                                        | 3         | 1.9%    |
| Intel 82574L Gigabit Network Connection                                    | 3         | 1.9%    |
| Ralink MT7601U Wireless Adapter                                            | 2         | 1.27%   |
| Intel Wireless 7260                                                        | 2         | 1.27%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                     | 2         | 1.27%   |
| Intel Ethernet Controller I225-V                                           | 2         | 1.27%   |
| Intel Ethernet Connection (4) I219-LM                                      | 2         | 1.27%   |
| Intel Ethernet Connection (11) I219-LM                                     | 2         | 1.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 2         | 1.27%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 2         | 1.27%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                     | 1         | 0.63%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]        | 1         | 0.63%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                   | 1         | 0.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 0.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 0.63%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                     | 1         | 0.63%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 1         | 0.63%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 1         | 0.63%   |
| Ralink RT5370 Wireless Adapter                                             | 1         | 0.63%   |
| Ralink RT2870/RT3070 Wireless Adapter                                      | 1         | 0.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 1         | 0.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 1         | 0.63%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 1         | 0.63%   |
| Mellanox MT27710 Family [ConnectX-4 Lx]                                    | 1         | 0.63%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                           | 1         | 0.63%   |
| Intel Wireless 8260                                                        | 1         | 0.63%   |
| Intel Wireless 7265                                                        | 1         | 0.63%   |
| Intel Wi-Fi 6 AX201 160MHz                                                 | 1         | 0.63%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                  | 1         | 0.63%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                              | 1         | 0.63%   |
| Intel Ethernet Connection I219-LM                                          | 1         | 0.63%   |
| Intel Ethernet Connection I217-LM                                          | 1         | 0.63%   |
| Intel Ethernet Connection (7) I219-V                                       | 1         | 0.63%   |
| Intel Ethernet Connection (7) I219-LM                                      | 1         | 0.63%   |
| Intel Ethernet Connection (5) I219-V                                       | 1         | 0.63%   |
| Intel Ethernet Connection (14) I219-LM                                     | 1         | 0.63%   |
| Intel Ethernet Connection (13) I219-V                                      | 1         | 0.63%   |
| Intel Ethernet Connection (10) I219-V                                      | 1         | 0.63%   |
| Intel Centrino Advanced-N 6235                                             | 1         | 0.63%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller          | 1         | 0.63%   |
| Google Nexus/Pixel Device (charging + debug)                               | 1         | 0.63%   |
| Emulex OneConnect 10Gb NIC (be3)                                           | 1         | 0.63%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]             | 1         | 0.63%   |
| Edimax EW-7711MAC 802.11ac Wireless Adapter                                | 1         | 0.63%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]                   | 1         | 0.63%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                          | 1         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 47        | 62.67%  |
| Realtek Semiconductor | 7         | 9.33%   |
| TP-Link               | 5         | 6.67%   |
| Ralink Technology     | 4         | 5.33%   |
| Broadcom              | 4         | 5.33%   |
| Qualcomm Atheros      | 2         | 2.67%   |
| Edimax Technology     | 2         | 2.67%   |
| D-Link System         | 2         | 2.67%   |
| BUFFALO               | 1         | 1.33%   |
| ASUSTek Computer      | 1         | 1.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                        | 8         | 10.67%  |
| Intel Comet Lake PCH CNVi WiFi                                             | 6         | 8%      |
| Intel Wireless-AC 9260                                                     | 5         | 6.67%   |
| Intel Wireless 8265 / 8275                                                 | 5         | 6.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 5         | 6.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                          | 4         | 5.33%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 3         | 4%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 3         | 4%      |
| Intel Wi-Fi 6 AX201                                                        | 3         | 4%      |
| Ralink MT7601U Wireless Adapter                                            | 2         | 2.67%   |
| Intel Wireless 7260                                                        | 2         | 2.67%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                     | 2         | 2.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 2         | 2.67%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 2         | 2.67%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                     | 1         | 1.33%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]        | 1         | 1.33%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                   | 1         | 1.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 1.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 1.33%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                     | 1         | 1.33%   |
| Ralink RT5370 Wireless Adapter                                             | 1         | 1.33%   |
| Ralink RT2870/RT3070 Wireless Adapter                                      | 1         | 1.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 1         | 1.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 1         | 1.33%   |
| Intel Wireless 8260                                                        | 1         | 1.33%   |
| Intel Wireless 7265                                                        | 1         | 1.33%   |
| Intel Wi-Fi 6 AX201 160MHz                                                 | 1         | 1.33%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                  | 1         | 1.33%   |
| Intel Centrino Advanced-N 6235                                             | 1         | 1.33%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]             | 1         | 1.33%   |
| Edimax EW-7711MAC 802.11ac Wireless Adapter                                | 1         | 1.33%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]                   | 1         | 1.33%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                | 1         | 1.33%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                         | 1         | 1.33%   |
| Broadcom BCM4331 802.11a/b/g/n                                             | 1         | 1.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                        | 1         | 1.33%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                                        | 1         | 1.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 37        | 50%     |
| Intel                 | 32        | 43.24%  |
| Qualcomm Atheros      | 1         | 1.35%   |
| Lenovo                | 1         | 1.35%   |
| Google                | 1         | 1.35%   |
| Emulex                | 1         | 1.35%   |
| Broadcom              | 1         | 1.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 33        | 43.42%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 7.89%   |
| Intel I211 Gigabit Network Connection                             | 4         | 5.26%   |
| Intel I210 Gigabit Network Connection                             | 4         | 5.26%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 3.95%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 3.95%   |
| Intel Ethernet Controller I225-V                                  | 2         | 2.63%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.63%   |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 2.63%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.32%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.32%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.32%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                  | 1         | 1.32%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1         | 1.32%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.32%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.32%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.32%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.32%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 1.32%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 1.32%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.32%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.32%   |
| Google Nexus/Pixel Device (charging + debug)                      | 1         | 1.32%   |
| Emulex OneConnect 10Gb NIC (be3)                                  | 1         | 1.32%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.32%   |
| Unknown                                                           | 1         | 1.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 68        | 50.37%  |
| WiFi     | 60        | 44.44%  |
| Modem    | 6         | 4.44%   |
| Unknown  | 1         | 0.74%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 61        | 61.62%  |
| WiFi     | 35        | 35.35%  |
| Modem    | 3         | 3.03%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 49        | 56.98%  |
| 1     | 19        | 22.09%  |
| 0     | 12        | 13.95%  |
| 3     | 4         | 4.65%   |
| 7     | 1         | 1.16%   |
| 4     | 1         | 1.16%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 75        | 83.33%  |
| Yes  | 15        | 16.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 35        | 79.55%  |
| Apple                           | 3         | 6.82%   |
| Realtek Semiconductor           | 2         | 4.55%   |
| Realtek                         | 1         | 2.27%   |
| Qualcomm Atheros Communications | 1         | 2.27%   |
| IMC Networks                    | 1         | 2.27%   |
| Broadcom                        | 1         | 2.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                          | 10        | 22.73%  |
| Intel Bluetooth wireless interface             | 7         | 15.91%  |
| Intel AX200 Bluetooth                          | 7         | 15.91%  |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 4         | 9.09%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 4         | 9.09%   |
| Intel AX210 Bluetooth                          | 2         | 4.55%   |
| Apple Bluetooth Host Controller                | 2         | 4.55%   |
| Realtek  Bluetooth Adapter                     | 1         | 2.27%   |
| Realtek Bluetooth Radio                        | 1         | 2.27%   |
| Realtek Bluetooth Radio                        | 1         | 2.27%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0         | 1         | 2.27%   |
| Intel Centrino Bluetooth Wireless Transceiver  | 1         | 2.27%   |
| IMC Networks Bluetooth module                  | 1         | 2.27%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 1         | 2.27%   |
| Apple Apple Broadcom Built-in Bluetooth        | 1         | 2.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 41        | 38.32%  |
| AMD                     | 33        | 30.84%  |
| Nvidia                  | 21        | 19.63%  |
| Lenovo                  | 3         | 2.8%    |
| Yamaha                  | 1         | 0.93%   |
| VMware                  | 1         | 0.93%   |
| SteelSeries ApS         | 1         | 0.93%   |
| Logitech                | 1         | 0.93%   |
| GN Netcom               | 1         | 0.93%   |
| CMX Systems             | 1         | 0.93%   |
| C-Media Electronics     | 1         | 0.93%   |
| AudioQuest              | 1         | 0.93%   |
| AKAI  Professional M.I. | 1         | 0.93%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 18        | 13.64%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 10        | 7.58%   |
| Intel Comet Lake PCH cAVS                                                  | 8         | 6.06%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 6.06%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7         | 5.3%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5         | 3.79%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5         | 3.79%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4         | 3.03%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 3.03%   |
| Intel Comet Lake PCH-LP cAVS                                               | 4         | 3.03%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 3.03%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4         | 3.03%   |
| Intel Sunrise Point-LP HD Audio                                            | 3         | 2.27%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 3         | 2.27%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 1.52%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 1.52%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 1.52%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 1.52%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 1.52%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2         | 1.52%   |
| Yamaha Steinberg UR12                                                      | 1         | 0.76%   |
| VMware HD Audio Controller                                                 | 1         | 0.76%   |
| SteelSeries ApS SteelSeries Siberia 350                                    | 1         | 0.76%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 0.76%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.76%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.76%   |
| Nvidia GM206 High Definition Audio Controller                              | 1         | 0.76%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.76%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 0.76%   |
| Logitech H390 headset with microphone                                      | 1         | 0.76%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                   | 1         | 0.76%   |
| Lenovo ThinkPad Dock Audio                                                 | 1         | 0.76%   |
| Lenovo Realtek USB Audio                                                   | 1         | 0.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 0.76%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 0.76%   |
| Intel Jasper Lake HD Audio                                                 | 1         | 0.76%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 0.76%   |
| Intel CM238 HD Audio Controller                                            | 1         | 0.76%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 0.76%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 0.76%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 0.76%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 1         | 0.76%   |
| GN Netcom Jabra SPEAK 410 USB                                              | 1         | 0.76%   |
| CMX Systems USB PnP Audio Device                                           | 1         | 0.76%   |
| C-Media Electronics BIRD UM1                                               | 1         | 0.76%   |
| AudioQuest DragonFly                                                       | 1         | 0.76%   |
| AMD Wrestler HDMI Audio                                                    | 1         | 0.76%   |
| AMD RV630 HDMI Audio [Radeon HD 2600 PRO/XT / HD 3610]                     | 1         | 0.76%   |
| AMD Navi 10 HDMI Audio                                                     | 1         | 0.76%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1         | 0.76%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1         | 0.76%   |
| AKAI  Professional M.I. LPK25 MIDI Keyboard                                | 1         | 0.76%   |
| Unknown                                                                    | 1         | 0.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 18        | 22.22%  |
| Micron Technology   | 14        | 17.28%  |
| SK Hynix            | 13        | 16.05%  |
| Kingston            | 10        | 12.35%  |
| Crucial             | 5         | 6.17%   |
| Corsair             | 4         | 4.94%   |
| Unknown             | 3         | 3.7%    |
| Smart               | 3         | 3.7%    |
| Ramaxel Technology  | 2         | 2.47%   |
| GOODRAM             | 2         | 2.47%   |
| Team                | 1         | 1.23%   |
| PNY                 | 1         | 1.23%   |
| Klevv               | 1         | 1.23%   |
| Gold Key            | 1         | 1.23%   |
| G.Skill             | 1         | 1.23%   |
| A-DATA Technology   | 1         | 1.23%   |
| Unknown             | 1         | 1.23%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s        | 4         | 4.82%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 2.41%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 2         | 2.41%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s       | 2         | 2.41%   |
| SK Hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 2         | 2.41%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s        | 2         | 2.41%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s         | 2         | 2.41%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s         | 2         | 2.41%   |
| Crucial RAM BL32G32C16S4B.M16FB1 32GB SODIMM DDR4 2667MT/s   | 2         | 2.41%   |
| Corsair RAM CMK32GX4M2D3200C16 16GB DIMM DDR4 3200MT/s       | 2         | 2.41%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                    | 1         | 1.2%    |
| Unknown RAM Module 1GB SODIMM DDR                            | 1         | 1.2%    |
| Unknown RAM 2G-08-10-12-1333 2GB DIMM DDR3 1333MT/s          | 1         | 1.2%    |
| Team RAM TEAMGROUP-UD4-4133 8GB DIMM DDR4 4133MT/s           | 1         | 1.2%    |
| Smart RAM SF4641G8CK8IWGKSEG 8GB SODIMM DDR4 2133MT/s        | 1         | 1.2%    |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s        | 1         | 1.2%    |
| SMART RAM Module 8GB DIMM DDR4 2667MT/s                      | 1         | 1.2%    |
| SK Hynix RAM Module 4GB SODIMM DDR3 1867MT/s                 | 1         | 1.2%    |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                 | 1         | 1.2%    |
| SK Hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s      | 1         | 1.2%    |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 1.2%    |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 1.2%    |
| Samsung RAM M474A4G43AB1-CVF 32GB SODIMM DDR4 2933MT/s       | 1         | 1.2%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s        | 1         | 1.2%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 1         | 1.2%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s        | 1         | 1.2%    |
| Samsung RAM M471A5244BB0-CWE 4GB SODIMM DDR4 3200MT/s        | 1         | 1.2%    |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s       | 1         | 1.2%    |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s       | 1         | 1.2%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 1         | 1.2%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s  | 1         | 1.2%    |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 1.2%    |
| Samsung RAM M378A4G43MB1-CTD 32GB DIMM DDR4 2666MT/s         | 1         | 1.2%    |
| Samsung RAM K4EBE304EB-EGCF 8GB Row Of Chips LPDDR3 1867MT/s | 1         | 1.2%    |
| Ramaxel RAM RMSA3320MJ78HAF-3200 8GB SODIMM DDR4 3200MT/s    | 1         | 1.2%    |
| Ramaxel RAM RMSA3300MH78HBF-2666 16GB SODIMM DDR4 2400MT/s   | 1         | 1.2%    |
| PNY RAM 16GU2X16LIII43-12-K 16GB SODIMM DDR4 2667MT/s        | 1         | 1.2%    |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                   | 1         | 1.2%    |
| Micron RAM Module 16GB DIMM DDR4 2400MT/s                    | 1         | 1.2%    |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s  | 1         | 1.2%    |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s        | 1         | 1.2%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s   | 1         | 1.2%    |
| Micron RAM 4ATF1G64HZ-3G2B2 8GB SODIMM DDR4 3200MT/s         | 1         | 1.2%    |
| Micron RAM 18ASF4G72AZ-3G2B1 32GB DIMM DDR4 3200MT/s         | 1         | 1.2%    |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s        | 1         | 1.2%    |
| Micron RAM 16ATF2G64HZ-2G6J1 16GB SODIMM DDR4 2667MT/s       | 1         | 1.2%    |
| Micron RAM 16ATF2G64AZ-3G2J1 16GB DIMM DDR4 3200MT/s         | 1         | 1.2%    |
| Klevv RAM KD4AGSA8M-32N220A 16GB SODIMM DDR4 3200MT/s        | 1         | 1.2%    |
| Kingston RAM Module 8GB SODIMM DDR4 2667MT/s                 | 1         | 1.2%    |
| Kingston RAM Module 16GB SODIMM DDR4 2667MT/s                | 1         | 1.2%    |
| Kingston RAM Module 16GB SODIMM DDR4 2400MT/s                | 1         | 1.2%    |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 2933MT/s         | 1         | 1.2%    |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 2666MT/s          | 1         | 1.2%    |
| Kingston RAM KHX2400C14S4/4G 4GB SODIMM DDR4 2400MT/s        | 1         | 1.2%    |
| Kingston RAM KHX1600C10D3/ 8GB DIMM DDR3 1600MT/s            | 1         | 1.2%    |
| Kingston RAM 99U5428-063.A00LF 8GB SODIMM DDR3 1600MT/s      | 1         | 1.2%    |
| Kingston RAM 9965745-020.A00G 32GB DIMM DDR4 3200MT/s        | 1         | 1.2%    |
| Kingston RAM 9965745-017.A00G 16GB DIMM DDR4 3200MT/s        | 1         | 1.2%    |
| Kingston RAM 9905713-030.A00G 8GB DIMM DDR4 2666MT/s         | 1         | 1.2%    |
| Kingston RAM 9905428-196.A00LF 8GB SODIMM DDR3 1333MT/s      | 1         | 1.2%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 55        | 76.39%  |
| DDR3   | 14        | 19.44%  |
| LPDDR4 | 1         | 1.39%   |
| LPDDR3 | 1         | 1.39%   |
| DDR    | 1         | 1.39%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 51        | 69.86%  |
| DIMM         | 18        | 24.66%  |
| Row Of Chips | 4         | 5.48%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 32        | 43.24%  |
| 16384 | 23        | 31.08%  |
| 4096  | 9         | 12.16%  |
| 32768 | 7         | 9.46%   |
| 2048  | 2         | 2.7%    |
| 1024  | 1         | 1.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 24        | 32%     |
| 2667    | 18        | 24%     |
| 1600    | 10        | 13.33%  |
| 2400    | 5         | 6.67%   |
| 2933    | 3         | 4%      |
| 2666    | 3         | 4%      |
| 2133    | 3         | 4%      |
| 1867    | 2         | 2.67%   |
| 1333    | 2         | 2.67%   |
| 4267    | 1         | 1.33%   |
| 4133    | 1         | 1.33%   |
| 3600    | 1         | 1.33%   |
| 1334    | 1         | 1.33%   |
| Unknown | 1         | 1.33%   |

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
| Chicony Electronics                    | 14        | 25.45%  |
| IMC Networks                           | 10        | 18.18%  |
| Logitech                               | 6         | 10.91%  |
| Realtek Semiconductor                  | 5         | 9.09%   |
| Lite-On Technology                     | 4         | 7.27%   |
| Acer                                   | 4         | 7.27%   |
| Sunplus Innovation Technology          | 3         | 5.45%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 5.45%   |
| Microdia                               | 2         | 3.64%   |
| Syntek                                 | 1         | 1.82%   |
| GEMBIRD                                | 1         | 1.82%   |
| Aveo Technology                        | 1         | 1.82%   |
| Apple                                  | 1         | 1.82%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                             | 7         | 12.5%   |
| Chicony Integrated Camera                                                  | 7         | 12.5%   |
| Logitech Webcam C270                                                       | 3         | 5.36%   |
| Chicony Integrated HP HD Webcam                                            | 3         | 5.36%   |
| Acer Integrated Camera                                                     | 3         | 5.36%   |
| Sunplus Integrated_Webcam_HD                                               | 2         | 3.57%   |
| Realtek Laptop Camera                                                      | 2         | 3.57%   |
| Lite-On Integrated Camera                                                  | 2         | 3.57%   |
| Lite-On HP HD Camera                                                       | 2         | 3.57%   |
| Syntek Lenovo EasyCamera                                                   | 1         | 1.79%   |
| Sunplus Integrated_Webcam_FHD                                              | 1         | 1.79%   |
| Realtek USB 2 Webcam                                                       | 1         | 1.79%   |
| Realtek Realtek USB2.0 PC Camera                                           | 1         | 1.79%   |
| Realtek Integrated_Webcam_HD                                               | 1         | 1.79%   |
| Microdia HP Integrated Webcam                                              | 1         | 1.79%   |
| Microdia Dell Integrated HD Webcam                                         | 1         | 1.79%   |
| Logitech Webcam C170                                                       | 1         | 1.79%   |
| Logitech HD Pro Webcam C920                                                | 1         | 1.79%   |
| Logitech C920 PRO HD Webcam                                                | 1         | 1.79%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 1         | 1.79%   |
| IMC Networks HD Camera                                                     | 1         | 1.79%   |
| IMC Networks EasyCamera                                                    | 1         | 1.79%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]                          | 1         | 1.79%   |
| Chicony USB2.0 0.3M UVC WebCam                                             | 1         | 1.79%   |
| Chicony ThinkPad T490 Webcam                                               | 1         | 1.79%   |
| Chicony Integrated IR Camera                                               | 1         | 1.79%   |
| Chicony HD Webcam                                                          | 1         | 1.79%   |
| Chicony Chicony USB2.0 Camera                                              | 1         | 1.79%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 1.79%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed]                | 1         | 1.79%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam   | 1         | 1.79%   |
| Aveo USB2.0 Camera                                                         | 1         | 1.79%   |
| Apple FaceTime HD Camera (Built-in)                                        | 1         | 1.79%   |
| Acer HD Webcam                                                             | 1         | 1.79%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 8         | 47.06%  |
| Validity Sensors           | 4         | 23.53%  |
| Shenzhen Goodix Technology | 4         | 23.53%  |
| AuthenTec                  | 1         | 5.88%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 29.41%  |
| Validity Sensors Synaptics WBDI                                            | 2         | 11.76%  |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 11.76%  |
| Shenzhen Goodix  FingerPrint Device                                        | 2         | 11.76%  |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 11.76%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 5.88%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 5.88%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 5.88%   |
| AuthenTec AES2810                                                          | 1         | 5.88%   |

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
| 0     | 26        | 29.89%  |
| 2     | 20        | 22.99%  |
| 4     | 15        | 17.24%  |
| 1     | 13        | 14.94%  |
| 3     | 9         | 10.34%  |
| 5     | 3         | 3.45%   |
| 9     | 1         | 1.15%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 46        | 34.07%  |
| Bluetooth                | 26        | 19.26%  |
| Net/wireless             | 25        | 18.52%  |
| Fingerprint reader       | 17        | 12.59%  |
| Card reader              | 8         | 5.93%   |
| Sound                    | 6         | 4.44%   |
| Net/ethernet             | 3         | 2.22%   |
| Firewire controller      | 2         | 1.48%   |
| Network                  | 1         | 0.74%   |
| Modem                    | 1         | 0.74%   |

