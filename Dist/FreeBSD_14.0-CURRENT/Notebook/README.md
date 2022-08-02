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

Total: 129

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| HP            | EliteBook 8570p             | [978f01c546](https://bsd-hardware.info/?probe=978f01c546) | Jul 16, 2022 |
| HP            | EliteBook 8570p             | [68c4af67b5](https://bsd-hardware.info/?probe=68c4af67b5) | Jul 14, 2022 |
| Lenovo        | ThinkPad T495 20NJ0010PB    | [078888676a](https://bsd-hardware.info/?probe=078888676a) | Jul 13, 2022 |
| Apple         | MacBookAir5,2               | [894b6f82cf](https://bsd-hardware.info/?probe=894b6f82cf) | Jul 13, 2022 |
| Toshiba       | Satellite L305D             | [ed950787b0](https://bsd-hardware.info/?probe=ed950787b0) | Jul 10, 2022 |
| Dell          | Latitude 5521               | [2c9d24a69e](https://bsd-hardware.info/?probe=2c9d24a69e) | Jun 19, 2022 |
| Dell          | Latitude 5410               | [3334ff3727](https://bsd-hardware.info/?probe=3334ff3727) | Jun 06, 2022 |
| HP            | EliteBook 8570p             | [1067f6ab27](https://bsd-hardware.info/?probe=1067f6ab27) | Jun 03, 2022 |
| HP            | EliteBook 8570p             | [3d0fdb11ff](https://bsd-hardware.info/?probe=3d0fdb11ff) | May 27, 2022 |
| HP            | ProBook 455 G7              | [c6944afe69](https://bsd-hardware.info/?probe=c6944afe69) | May 19, 2022 |
| Lenovo        | ThinkPad T495s 20QKS1812... | [89db84f7ec](https://bsd-hardware.info/?probe=89db84f7ec) | May 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [015bf0fea4](https://bsd-hardware.info/?probe=015bf0fea4) | May 06, 2022 |
| Framework     | Laptop                      | [5d6cb039ea](https://bsd-hardware.info/?probe=5d6cb039ea) | Apr 25, 2022 |
| HP            | EliteBook 8570p             | [c4dee3f070](https://bsd-hardware.info/?probe=c4dee3f070) | Apr 21, 2022 |
| HP            | EliteBook 8570p             | [d9acb17caf](https://bsd-hardware.info/?probe=d9acb17caf) | Apr 20, 2022 |
| HP            | EliteBook 8570p             | [0c73871c49](https://bsd-hardware.info/?probe=0c73871c49) | Apr 04, 2022 |
| MSI           | Bravo 15 A4DDR              | [1868573e9a](https://bsd-hardware.info/?probe=1868573e9a) | Apr 02, 2022 |
| Lenovo        | ThinkPad X260 20F5A28AUK    | [f53c625efd](https://bsd-hardware.info/?probe=f53c625efd) | Mar 30, 2022 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | [859a429ad0](https://bsd-hardware.info/?probe=859a429ad0) | Mar 24, 2022 |
| HP            | EliteBook 8570p             | [e9f59e748e](https://bsd-hardware.info/?probe=e9f59e748e) | Mar 24, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [6858ad2b12](https://bsd-hardware.info/?probe=6858ad2b12) | Mar 22, 2022 |
| HP            | EliteBook 8570p             | [7e1e137c8f](https://bsd-hardware.info/?probe=7e1e137c8f) | Mar 20, 2022 |
| HP            | EliteBook 8570p             | [dafb1bbb92](https://bsd-hardware.info/?probe=dafb1bbb92) | Mar 20, 2022 |
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
| HP            | EliteBook 8570p             | [1520fece28](https://bsd-hardware.info/?probe=1520fece28) | Jan 17, 2022 |
| HP            | EliteBook 8570p             | [5f106ee686](https://bsd-hardware.info/?probe=5f106ee686) | Jan 15, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20T20... | [6836fc60f6](https://bsd-hardware.info/?probe=6836fc60f6) | Jan 09, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [6c208c85a5](https://bsd-hardware.info/?probe=6c208c85a5) | Jan 06, 2022 |
| HP            | EliteBook 8570p             | [1bbb37d4c6](https://bsd-hardware.info/?probe=1bbb37d4c6) | Jan 03, 2022 |
| HP            | EliteBook 8570p             | [0a180d834c](https://bsd-hardware.info/?probe=0a180d834c) | Jan 03, 2022 |
| HP            | EliteBook 8570p             | [b956c2a933](https://bsd-hardware.info/?probe=b956c2a933) | Dec 28, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [42b4bcbcc2](https://bsd-hardware.info/?probe=42b4bcbcc2) | Dec 27, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [695d7201d4](https://bsd-hardware.info/?probe=695d7201d4) | Dec 27, 2021 |
| HP            | EliteBook 8570p             | [44d3e7366c](https://bsd-hardware.info/?probe=44d3e7366c) | Dec 20, 2021 |
| HP            | EliteBook Folio 9470m       | [b872e9b044](https://bsd-hardware.info/?probe=b872e9b044) | Dec 18, 2021 |
| HP            | ProBook 440 G6              | [7a8a66430a](https://bsd-hardware.info/?probe=7a8a66430a) | Dec 13, 2021 |
| HP            | ProBook 440 G6              | [f3c014b120](https://bsd-hardware.info/?probe=f3c014b120) | Dec 12, 2021 |
| HP            | EliteBook 8570p             | [045ffeb9b3](https://bsd-hardware.info/?probe=045ffeb9b3) | Dec 12, 2021 |
| ASUSTek       | 1215B                       | [6dbcac684f](https://bsd-hardware.info/?probe=6dbcac684f) | Dec 04, 2021 |
| HP            | EliteBook 8570p             | [92fc69392b](https://bsd-hardware.info/?probe=92fc69392b) | Nov 27, 2021 |
| HP            | EliteBook 8570p             | [d3888a4c7d](https://bsd-hardware.info/?probe=d3888a4c7d) | Nov 21, 2021 |
| HP            | EliteBook 8570p             | [822a2481bb](https://bsd-hardware.info/?probe=822a2481bb) | Nov 17, 2021 |
| HP            | EliteBook 8570p             | [ea51e03be6](https://bsd-hardware.info/?probe=ea51e03be6) | Nov 13, 2021 |
| HP            | EliteBook 8570p             | [28a264a128](https://bsd-hardware.info/?probe=28a264a128) | Nov 09, 2021 |
| HP            | EliteBook 8570p             | [d0b487888a](https://bsd-hardware.info/?probe=d0b487888a) | Nov 08, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [e54d79065e](https://bsd-hardware.info/?probe=e54d79065e) | Nov 02, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [a71d3392eb](https://bsd-hardware.info/?probe=a71d3392eb) | Nov 02, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0PM0... | [7a61d90a55](https://bsd-hardware.info/?probe=7a61d90a55) | Oct 28, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [d910c79d75](https://bsd-hardware.info/?probe=d910c79d75) | Oct 24, 2021 |
| HP            | EliteBook 8570p             | [86613b04d3](https://bsd-hardware.info/?probe=86613b04d3) | Oct 17, 2021 |
| HP            | EliteBook 8570p             | [1b48acadd5](https://bsd-hardware.info/?probe=1b48acadd5) | Oct 10, 2021 |
| Framework     | Laptop                      | [e5aca4b7d0](https://bsd-hardware.info/?probe=e5aca4b7d0) | Oct 02, 2021 |
| HP            | EliteBook 8570p             | [646148fc25](https://bsd-hardware.info/?probe=646148fc25) | Sep 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [0b73df29bf](https://bsd-hardware.info/?probe=0b73df29bf) | Sep 15, 2021 |
| HP            | EliteBook 8570p             | [5a4e53da56](https://bsd-hardware.info/?probe=5a4e53da56) | Sep 12, 2021 |
| Lenovo        | ThinkPad X395 20NL000GPG    | [d7812a2905](https://bsd-hardware.info/?probe=d7812a2905) | Sep 10, 2021 |
| Lenovo        | ThinkPad X395 20NL000GPG    | [cdde22fb04](https://bsd-hardware.info/?probe=cdde22fb04) | Sep 10, 2021 |
| HP            | EliteBook 8570p             | [7a289e8d1b](https://bsd-hardware.info/?probe=7a289e8d1b) | Sep 06, 2021 |
| HP            | EliteBook 8570p             | [fae9e84f60](https://bsd-hardware.info/?probe=fae9e84f60) | Aug 27, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [76f004bd26](https://bsd-hardware.info/?probe=76f004bd26) | Aug 26, 2021 |
| HP            | EliteBook 8570p             | [a98c6adb40](https://bsd-hardware.info/?probe=a98c6adb40) | Aug 22, 2021 |
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
| Lenovo        | XiaoXinPro-13ARE 2020 82... | [e0e6f62814](https://bsd-hardware.info/?probe=e0e6f62814) | Jul 19, 2021 |
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
| HP            | EliteBook 8570p             | [062fe5ec40](https://bsd-hardware.info/?probe=062fe5ec40) | May 09, 2021 |
| Dell          | G5 5505                     | [ba74d8eee0](https://bsd-hardware.info/?probe=ba74d8eee0) | May 08, 2021 |
| Dell          | G5 5505                     | [23ae99e489](https://bsd-hardware.info/?probe=23ae99e489) | May 08, 2021 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | [2be8cf963c](https://bsd-hardware.info/?probe=2be8cf963c) | May 02, 2021 |
| Dell          | Inspiron 3793               | [c2d56fc369](https://bsd-hardware.info/?probe=c2d56fc369) | Apr 29, 2021 |
| HP            | EliteBook 8570p             | [e90abb54c9](https://bsd-hardware.info/?probe=e90abb54c9) | Apr 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [4993ad0feb](https://bsd-hardware.info/?probe=4993ad0feb) | Apr 25, 2021 |
| HUAWEI        | HN-WX9X                     | [d776625073](https://bsd-hardware.info/?probe=d776625073) | Apr 11, 2021 |
| HP            | EliteBook 8570p             | [d9ec051372](https://bsd-hardware.info/?probe=d9ec051372) | Apr 06, 2021 |
| HP            | EliteBook 8570p             | [cdeafa0952](https://bsd-hardware.info/?probe=cdeafa0952) | Apr 02, 2021 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [342e914968](https://bsd-hardware.info/?probe=342e914968) | Mar 29, 2021 |
| HP            | EliteBook 8570p             | [ed80dc9019](https://bsd-hardware.info/?probe=ed80dc9019) | Mar 27, 2021 |
| HP            | ProBook 455 G7              | [dd877e6c6c](https://bsd-hardware.info/?probe=dd877e6c6c) | Mar 27, 2021 |
| Lenovo        | ThinkPad X395 20NL001SMX    | [cd016e96ee](https://bsd-hardware.info/?probe=cd016e96ee) | Mar 17, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [9fed35d792](https://bsd-hardware.info/?probe=9fed35d792) | Mar 10, 2021 |
| HP            | ProBook 455 G7              | [1fcde7c0e1](https://bsd-hardware.info/?probe=1fcde7c0e1) | Mar 09, 2021 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | [f2c2e5345a](https://bsd-hardware.info/?probe=f2c2e5345a) | Feb 27, 2021 |
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
| amd64 | 54        | 98.18%  |
| i386  | 1         | 1.82%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KDE5          | 16        | 26.67%  |
| XFCE          | 8         | 13.33%  |
| TWM           | 5         | 8.33%   |
| Console       | 5         | 8.33%   |
| MATE          | 4         | 6.67%   |
| GNOME         | 4         | 6.67%   |
| i3            | 3         | 5%      |
| Cinnamon      | 3         | 5%      |
| LXDE          | 2         | 3.33%   |
| Lumina        | 2         | 3.33%   |
| Xfwm4         | 1         | 1.67%   |
| Picom         | 1         | 1.67%   |
| LXQt          | 1         | 1.67%   |
| GNUstep       | 1         | 1.67%   |
| Fluxbox       | 1         | 1.67%   |
| Enlightenment | 1         | 1.67%   |
| ctwm          | 1         | 1.67%   |
| akonadi_newm  | 1         | 1.67%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 47        | 81.03%  |
| Console | 9         | 15.52%  |
| Wayland | 2         | 3.45%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 19        | 33.33%  |
| SDDM    | 15        | 26.32%  |
| SLiM    | 8         | 14.04%  |
| GDM     | 7         | 12.28%  |
| XDM     | 4         | 7.02%   |
| LightDM | 3         | 5.26%   |
| Ly      | 1         | 1.75%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Notebooks | Percent |
|------------------|-----------|---------|
| C                | 41        | 70.69%  |
| en_US            | 6         | 10.34%  |
| en_GB            | 3         | 5.17%   |
| zh_CN            | 2         | 3.45%   |
| pt_PT            | 1         | 1.72%   |
| pl_PL            | 1         | 1.72%   |
| it_IT.ISO8859-15 | 1         | 1.72%   |
| fr_FR            | 1         | 1.72%   |
| de_DE            | 1         | 1.72%   |
| Unknown          | 1         | 1.72%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 51        | 92.73%  |
| BIOS | 4         | 7.27%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Zfs  | 42        | 76.36%  |
| Ufs  | 13        | 23.64%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 53        | 96.36%  |
| MBR  | 2         | 3.64%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 25        | 45.45%  |
| Hewlett-Packard                | 8         | 14.55%  |
| Dell                           | 7         | 12.73%  |
| Framework                      | 3         | 5.45%   |
| Apple                          | 3         | 5.45%   |
| MSI                            | 2         | 3.64%   |
| ASUSTek Computer               | 2         | 3.64%   |
| Notebook                       | 1         | 1.82%   |
| Matsushita Electric Industrial | 1         | 1.82%   |
| HUAWEI                         | 1         | 1.82%   |
| Avell High Performance         | 1         | 1.82%   |
| A-DATA Technology              | 1         | 1.82%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| HP EliteBook 8570p                          | 3         | 5.45%   |
| Framework Laptop                            | 3         | 5.45%   |
| Notebook NS50_70MU                          | 1         | 1.82%   |
| MSI GE76 Raider 10UG                        | 1         | 1.82%   |
| MSI Bravo 15 A4DDR                          | 1         | 1.82%   |
| Matsushita Electric Industrial CF-T2BW1AXR  | 1         | 1.82%   |
| Lenovo XiaoXinPro-13ARE 2020 82DM           | 1         | 1.82%   |
| Lenovo ThinkPad X395 20NL001SMX             | 1         | 1.82%   |
| Lenovo ThinkPad X395 20NL000GPG             | 1         | 1.82%   |
| Lenovo ThinkPad X270 20HM004JBR             | 1         | 1.82%   |
| Lenovo ThinkPad X260 20F5A28AUK             | 1         | 1.82%   |
| Lenovo ThinkPad X13 Gen 1 20T2003PRT        | 1         | 1.82%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TLA055CD | 1         | 1.82%   |
| Lenovo ThinkPad X1 Extreme 20MF000BUS       | 1         | 1.82%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS1QC00    | 1         | 1.82%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS0BT00    | 1         | 1.82%   |
| Lenovo ThinkPad T495s 20QKS1812F            | 1         | 1.82%   |
| Lenovo ThinkPad T495 20NJ0010PB             | 1         | 1.82%   |
| Lenovo ThinkPad T470p 20J7S0PM00            | 1         | 1.82%   |
| Lenovo ThinkPad T430 2349H2G                | 1         | 1.82%   |
| Lenovo ThinkPad T14s Gen 2i 20WM00B7MX      | 1         | 1.82%   |
| Lenovo ThinkPad P15 Gen 1 20ST005VRT        | 1         | 1.82%   |
| Lenovo ThinkPad P14s Gen 1 20Y1CTO1WW       | 1         | 1.82%   |
| Lenovo ThinkPad E14 Gen 3 20Y7003SGE        | 1         | 1.82%   |
| Lenovo ThinkPad E14 20RBCTO1WW              | 1         | 1.82%   |
| Lenovo ThinkBook 14 G3 ACL 21A2             | 1         | 1.82%   |
| Lenovo Legion 5P 15IMH05H 82AW              | 1         | 1.82%   |
| Lenovo Legion 5 15IMH05 82AU                | 1         | 1.82%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY        | 1         | 1.82%   |
| Lenovo IdeaPad 330-15ARR 81D2               | 1         | 1.82%   |
| HUAWEI HN-WX9X                              | 1         | 1.82%   |
| HP ZBook 17 G2                              | 1         | 1.82%   |
| HP ProBook 455 G7                           | 1         | 1.82%   |
| HP ProBook 440 G7                           | 1         | 1.82%   |
| HP ProBook 440 G6                           | 1         | 1.82%   |
| HP EliteBook Folio 9470m                    | 1         | 1.82%   |
| Dell Vostro 5490                            | 1         | 1.82%   |
| Dell Latitude E5430 vPro                    | 1         | 1.82%   |
| Dell Latitude 5521                          | 1         | 1.82%   |
| Dell Latitude 5410                          | 1         | 1.82%   |
| Dell Inspiron 3793                          | 1         | 1.82%   |
| Dell G5 5505                                | 1         | 1.82%   |
| Dell G3 3500                                | 1         | 1.82%   |
| Avell High Performance A62 LIV              | 1         | 1.82%   |
| ASUS VivoBook_ASUSLaptop X512DA_F512DA      | 1         | 1.82%   |
| ASUS 1215B                                  | 1         | 1.82%   |
| Apple MacBookPro12,1                        | 1         | 1.82%   |
| Apple MacBookPro10,1                        | 1         | 1.82%   |
| Apple MacBookAir5,2                         | 1         | 1.82%   |
| A-DATA XENIA159GENI72060                    | 1         | 1.82%   |
| Unknown                                     | 1         | 1.82%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo ThinkPad                            | 18        | 32.73%  |
| HP EliteBook                               | 4         | 7.27%   |
| HP ProBook                                 | 3         | 5.45%   |
| Framework Laptop                           | 3         | 5.45%   |
| Dell Latitude                              | 3         | 5.45%   |
| Lenovo Legion                              | 2         | 3.64%   |
| Lenovo IdeaPad                             | 2         | 3.64%   |
| Notebook NS50                              | 1         | 1.82%   |
| MSI GE76                                   | 1         | 1.82%   |
| MSI Bravo                                  | 1         | 1.82%   |
| Matsushita Electric Industrial CF-T2BW1AXR | 1         | 1.82%   |
| Lenovo XiaoXinPro-13ARE                    | 1         | 1.82%   |
| Lenovo ThinkBook                           | 1         | 1.82%   |
| HUAWEI HN-WX9X                             | 1         | 1.82%   |
| HP ZBook                                   | 1         | 1.82%   |
| Dell Vostro                                | 1         | 1.82%   |
| Dell Inspiron                              | 1         | 1.82%   |
| Dell G5                                    | 1         | 1.82%   |
| Dell G3                                    | 1         | 1.82%   |
| Avell High Performance A62                 | 1         | 1.82%   |
| ASUS VivoBook                              | 1         | 1.82%   |
| ASUS 1215B                                 | 1         | 1.82%   |
| Apple MacBookPro12                         | 1         | 1.82%   |
| Apple MacBookPro10                         | 1         | 1.82%   |
| Apple MacBookAir5                          | 1         | 1.82%   |
| A-DATA XENIA159GENI72060                   | 1         | 1.82%   |
| Unknown                                    | 1         | 1.82%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 17        | 30.91%  |
| 2021 | 13        | 23.64%  |
| 2019 | 7         | 12.73%  |
| 2017 | 4         | 7.27%   |
| 2013 | 4         | 7.27%   |
| 2015 | 3         | 5.45%   |
| 2022 | 2         | 3.64%   |
| 2018 | 2         | 3.64%   |
| 2016 | 1         | 1.82%   |
| 2011 | 1         | 1.82%   |
| 2003 | 1         | 1.82%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 55        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 55        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 24        | 42.86%  |
| 8.01-16.0   | 13        | 23.21%  |
| 32.01-64.0  | 11        | 19.64%  |
| 4.01-8.0    | 3         | 5.36%   |
| 64.01-256.0 | 3         | 5.36%   |
| 24.01-32.0  | 1         | 1.79%   |
| 1.01-2.0    | 1         | 1.79%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.51-1.0   | 24        | 42.86%  |
| 1.01-2.0   | 15        | 26.79%  |
| 2.01-3.0   | 7         | 12.5%   |
| 0.01-0.5   | 5         | 8.93%   |
| 3.01-4.0   | 2         | 3.57%   |
| 24.01-32.0 | 2         | 3.57%   |
| 8.01-16.0  | 1         | 1.79%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 39        | 65%     |
| 2      | 20        | 33.33%  |
| 3      | 1         | 1.67%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 51        | 89.47%  |
| Yes       | 6         | 10.53%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 46        | 83.64%  |
| No        | 9         | 16.36%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 55        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 76.79%  |
| No        | 13        | 23.21%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 10        | 18.18%  |
| UK          | 6         | 10.91%  |
| Russia      | 5         | 9.09%   |
| Germany     | 5         | 9.09%   |
| Poland      | 4         | 7.27%   |
| China       | 4         | 7.27%   |
| Brazil      | 3         | 5.45%   |
| Portugal    | 2         | 3.64%   |
| Austria     | 2         | 3.64%   |
| Turkey      | 1         | 1.82%   |
| Switzerland | 1         | 1.82%   |
| Sweden      | 1         | 1.82%   |
| Spain       | 1         | 1.82%   |
| Peru        | 1         | 1.82%   |
| Netherlands | 1         | 1.82%   |
| Japan       | 1         | 1.82%   |
| Italy       | 1         | 1.82%   |
| India       | 1         | 1.82%   |
| Denmark     | 1         | 1.82%   |
| Croatia     | 1         | 1.82%   |
| Colombia    | 1         | 1.82%   |
| Belarus     | 1         | 1.82%   |
| Bangladesh  | 1         | 1.82%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Brighton       | 5         | 7.81%   |
| London         | 3         | 4.69%   |
| Moscow         | 2         | 3.13%   |
| ЕЊta-ku      | 1         | 1.56%   |
| Zurich         | 1         | 1.56%   |
| Wuhan          | 1         | 1.56%   |
| Worthing       | 1         | 1.56%   |
| Wieliczka      | 1         | 1.56%   |
| Washington     | 1         | 1.56%   |
| Warsaw         | 1         | 1.56%   |
| Vienna         | 1         | 1.56%   |
| Vancouver      | 1         | 1.56%   |
| Trosa          | 1         | 1.56%   |
| Thrissur       | 1         | 1.56%   |
| Stuttgart      | 1         | 1.56%   |
| St Petersburg  | 1         | 1.56%   |
| Slavonski Brod | 1         | 1.56%   |
| Shanghai       | 1         | 1.56%   |
| Seattle        | 1         | 1.56%   |
| Rostov-on-Don  | 1         | 1.56%   |
| Riverside      | 1         | 1.56%   |
| Resana         | 1         | 1.56%   |
| Poulsbo        | 1         | 1.56%   |
| Pobiedziska    | 1         | 1.56%   |
| Omaha          | 1         | 1.56%   |
| Northeim       | 1         | 1.56%   |
| New York       | 1         | 1.56%   |
| Montclair      | 1         | 1.56%   |
| Minsk          | 1         | 1.56%   |
| Milan          | 1         | 1.56%   |
| Medellín      | 1         | 1.56%   |
| Manchester     | 1         | 1.56%   |
| Maia           | 1         | 1.56%   |
| Madrid         | 1         | 1.56%   |
| Lima           | 1         | 1.56%   |
| Kislovodsk     | 1         | 1.56%   |
| Khabarovsk     | 1         | 1.56%   |
| Katowice       | 1         | 1.56%   |
| JoГЈo Pessoa | 1         | 1.56%   |
| Istanbul       | 1         | 1.56%   |
| Ilhavo         | 1         | 1.56%   |
| Hoogeveen      | 1         | 1.56%   |
| Hangzhou       | 1         | 1.56%   |
| Guangzhou Shi  | 1         | 1.56%   |
| Graz           | 1         | 1.56%   |
| Fuchu          | 1         | 1.56%   |
| Fjenneslev     | 1         | 1.56%   |
| Farnham        | 1         | 1.56%   |
| Eilenburg      | 1         | 1.56%   |
| Dormagen       | 1         | 1.56%   |
| Dhaka          | 1         | 1.56%   |
| Chicago        | 1         | 1.56%   |
| Brooklyn       | 1         | 1.56%   |
| BrasГ­lia    | 1         | 1.56%   |
| Berlin         | 1         | 1.56%   |
| Beijing        | 1         | 1.56%   |
| Araruama       | 1         | 1.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 19        | 23     | 26.76%  |
| WDC                 | 13        | 20     | 18.31%  |
| Toshiba             | 7         | 16     | 9.86%   |
| HGST                | 5         | 21     | 7.04%   |
| SK hynix            | 3         | 3      | 4.23%   |
| KIOXIA              | 3         | 3      | 4.23%   |
| Kingston            | 3         | 5      | 4.23%   |
| Apple               | 3         | 3      | 4.23%   |
| A-DATA Technology   | 3         | 3      | 4.23%   |
| Intel               | 2         | 2      | 2.82%   |
| Crucial             | 2         | 4      | 2.82%   |
| SPCC                | 1         | 1      | 1.41%   |
| Solid State Storage | 1         | 1      | 1.41%   |
| Silicon Motion      | 1         | 1      | 1.41%   |
| Seagate             | 1         | 1      | 1.41%   |
| SanDisk             | 1         | 2      | 1.41%   |
| Mushkin             | 1         | 1      | 1.41%   |
| LITEON              | 1         | 1      | 1.41%   |
| Fujitsu             | 1         | 2      | 1.41%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB                           | 5         | 6.58%   |
| HGST HTS725050A7E630 500GB                         | 4         | 5.26%   |
| Samsung HM251JX 250GB                              | 3         | 3.95%   |
| WDC WDS100T3X0C-00SJG0 1TB                         | 2         | 2.63%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB                 | 2         | 2.63%   |
| WDC PC SN730 NVMe 1024GB                           | 2         | 2.63%   |
| Samsung MZVLB512HBJQ-000L7 512GB                   | 2         | 2.63%   |
| KIOXIA KBG40ZNS256G NVMe 256GB                     | 2         | 2.63%   |
| HGST HTS721010A9E630 1TB                           | 2         | 2.63%   |
| Apple SSD SM256E 256GB                             | 2         | 2.63%   |
| WDC WDS500G1X0E-00AFY0 500GB                       | 1         | 1.32%   |
| WDC WDS100T1X0E-00AFY0 1TB                         | 1         | 1.32%   |
| WDC WD10SPZX-60Z10T0 1TB                           | 1         | 1.32%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB               | 1         | 1.32%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB               | 1         | 1.32%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB               | 1         | 1.32%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB               | 1         | 1.32%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB               | 1         | 1.32%   |
| Toshiba MQ04ABF100 1TB                             | 1         | 1.32%   |
| Toshiba KXG6APNV2T04 2TB                           | 1         | 1.32%   |
| SPCC M.2 PCIe SSD 1TB                              | 1         | 1.32%   |
| Solid State Storage CL1-3D128-Q11 NVMe SSSTC 128GB | 1         | 1.32%   |
| SK hynix PC300 HFS512GD9MND-5510A 512GB            | 1         | 1.32%   |
| SK hynix BC511 NVMe 256GB                          | 1         | 1.32%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB            | 1         | 1.32%   |
| Silicon Motion NE-256 256GB                        | 1         | 1.32%   |
| Seagate ST1000LM035-1RK172 1TB                     | 1         | 1.32%   |
| SanDisk SDSSDH3500G 500GB                          | 1         | 1.32%   |
| Samsung SSD 970 PRO 1TB                            | 1         | 1.32%   |
| Samsung SSD 970 EVO Plus 1TB                       | 1         | 1.32%   |
| Samsung SSD 970 EVO 1TB                            | 1         | 1.32%   |
| Samsung SSD 860 EVO 500GB                          | 1         | 1.32%   |
| Samsung SSD 850 EVO 250GB                          | 1         | 1.32%   |
| Samsung SSD 840 PRO Series 128GB                   | 1         | 1.32%   |
| Samsung PM9A1 NVMe 512GB                           | 1         | 1.32%   |
| Samsung MZVLW256HEHP-000L7 256GB                   | 1         | 1.32%   |
| Samsung MZVLB512HBJQ-000L2 512GB                   | 1         | 1.32%   |
| Samsung MZVLB2T0HMLB-00000 2TB                     | 1         | 1.32%   |
| Samsung MZVLB256HBHQ-000L7 256GB                   | 1         | 1.32%   |
| Samsung MZVLB256HAHQ-00000 256GB                   | 1         | 1.32%   |
| Samsung MZVLB1T0HBLR-000L2 1TB                     | 1         | 1.32%   |
| Samsung MZMTD128HAFV-000L1 128GB                   | 1         | 1.32%   |
| Samsung MZALQ512HBLU-00BL1 512GB                   | 1         | 1.32%   |
| Samsung MZALQ256HAJD-000L2 256GB                   | 1         | 1.32%   |
| Mushkin MKNSSDHL1TB-D8                             | 1         | 1.32%   |
| LITEON LCH-256V2S 256GB                            | 1         | 1.32%   |
| KIOXIA KXG60PNV2T04 NVMe 2048GB                    | 1         | 1.32%   |
| Kingston SUV500MS480G 480GB                        | 1         | 1.32%   |
| Kingston SUV500MS120G 120GB                        | 1         | 1.32%   |
| Kingston RBUSNS8154P3256GJ3 256GB                  | 1         | 1.32%   |
| Kingston OM8PCP3512F-AA 512GB                      | 1         | 1.32%   |
| Intel SSDSC2BF240A5L 240GB                         | 1         | 1.32%   |
| Intel SSDPEKNW512G8H 512GB                         | 1         | 1.32%   |
| Fujitsu MHS2040AT D 40GB                           | 1         | 1.32%   |
| Crucial CT480BX500SSD1 480GB                       | 1         | 1.32%   |
| Crucial CT2000P5SSD8 2TB                           | 1         | 1.32%   |
| Apple SSD SM0128G 121GB                            | 1         | 1.32%   |
| A-DATA SX8200PNP 1TB                               | 1         | 1.32%   |
| A-DATA SU650NS38 240GB                             | 1         | 1.32%   |
| A-DATA IM2P33F8BR2-512GB                           | 1         | 1.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 6         | 15     | 35.29%  |
| HGST                | 5         | 21     | 29.41%  |
| Samsung Electronics | 3         | 3      | 17.65%  |
| WDC                 | 1         | 1      | 5.88%   |
| Seagate             | 1         | 1      | 5.88%   |
| Fujitsu             | 1         | 2      | 5.88%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 4      | 25%     |
| Apple               | 3         | 3      | 25%     |
| SanDisk             | 1         | 2      | 8.33%   |
| LITEON              | 1         | 1      | 8.33%   |
| Kingston            | 1         | 2      | 8.33%   |
| Intel               | 1         | 1      | 8.33%   |
| Crucial             | 1         | 1      | 8.33%   |
| A-DATA Technology   | 1         | 1      | 8.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 39        | 55     | 62.9%   |
| SSD  | 12        | 15     | 19.35%  |
| HDD  | 11        | 43     | 17.74%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 39        | 55     | 62.9%   |
| SATA | 23        | 58     | 37.1%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 19        | 43     | 79.17%  |
| 0.51-1.0   | 5         | 15     | 20.83%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 16        | 26.67%  |
| 101-250    | 16        | 26.67%  |
| 501-1000   | 11        | 18.33%  |
| 51-100     | 6         | 10%     |
| 21-50      | 5         | 8.33%   |
| 1001-2000  | 4         | 6.67%   |
| 1-20       | 2         | 3.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 35        | 59.32%  |
| 21-50    | 18        | 30.51%  |
| 101-250  | 4         | 6.78%   |
| 501-1000 | 1         | 1.69%   |
| 51-100   | 1         | 1.69%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| HGST HTS725050A7E630 500GB        | 4         | 9      | 50%     |
| WDC WD10SPZX-60Z10T0 1TB          | 1         | 1      | 12.5%   |
| Samsung Electronics HM251JX 250GB | 1         | 1      | 12.5%   |
| HGST HTS721010A9E630 1TB          | 1         | 10     | 12.5%   |
| Fujitsu MHS2040AT D 40GB          | 1         | 2      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 4         | 19     | 57.14%  |
| WDC                 | 1         | 1      | 14.29%  |
| Samsung Electronics | 1         | 1      | 14.29%  |
| Fujitsu             | 1         | 2      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 4         | 19     | 57.14%  |
| WDC                 | 1         | 1      | 14.29%  |
| Samsung Electronics | 1         | 1      | 14.29%  |
| Fujitsu             | 1         | 2      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 23     | 100%    |

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
| Works    | 53        | 87     | 85.48%  |
| Malfunc  | 6         | 23     | 9.68%   |
| Detected | 3         | 3      | 4.84%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 28        | 35.9%   |
| Samsung Electronics            | 14        | 17.95%  |
| SanDisk                        | 13        | 16.67%  |
| AMD                            | 8         | 10.26%  |
| SK hynix                       | 3         | 3.85%   |
| Toshiba                        | 2         | 2.56%   |
| Silicon Motion                 | 2         | 2.56%   |
| KIOXIA                         | 2         | 2.56%   |
| Kingston Technology Company    | 2         | 2.56%   |
| ADATA Technology               | 2         | 2.56%   |
| Solid State Storage Technology | 1         | 1.28%   |
| Micron Technology              | 1         | 1.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 9         | 11.11%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 9         | 11.11%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 8.64%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 7         | 8.64%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 4.94%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 4         | 4.94%   |
| Unknown                                                                        | 4         | 4.94%   |
| Toshiba XG6 NVMe SSD Controller                                                | 2         | 2.47%   |
| SK hynix BC511                                                                 | 2         | 2.47%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 2         | 2.47%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 2.47%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 2.47%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 2         | 2.47%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 2.47%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 2.47%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 2         | 2.47%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 2         | 2.47%   |
| SK hynix PC300 NVMe Solid State Drive 512GB                                    | 1         | 1.23%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1         | 1.23%   |
| SanDisk PC SN530                                                               | 1         | 1.23%   |
| Samsung SM951 AHCI                                                             | 1         | 1.23%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 1.23%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 1.23%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 1         | 1.23%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 1.23%   |
| Intel SSD 660P Series                                                          | 1         | 1.23%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 1         | 1.23%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 1.23%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 1.23%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.23%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 1         | 1.23%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1         | 1.23%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 1.23%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 1         | 1.23%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 39        | 51.32%  |
| SATA | 34        | 44.74%  |
| IDE  | 3         | 3.95%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 39        | 70.91%  |
| AMD    | 16        | 29.09%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 5         | 9.09%   |
| Intel Core i7-3520M CPU @ 2.90GHz               | 4         | 7.27%   |
| Intel Core i5-10210U CPU @ 1.60GHz              | 4         | 7.27%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 3         | 5.45%   |
| Intel Core i7-7600U CPU @ 2.80GHz               | 2         | 3.64%   |
| Intel Core i5-10300H CPU @ 2.50GHz              | 2         | 3.64%   |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx | 2         | 3.64%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 2         | 3.64%   |
| AMD Ryzen 5 PRO 3500U w/ Radeon Vega Mobile Gfx | 2         | 3.64%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 2         | 3.64%   |
| Intel Xeon W-10885M CPU @ 2.40GHz               | 1         | 1.82%   |
| Intel Pentium M processor 1000MHz               | 1         | 1.82%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 1         | 1.82%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 1         | 1.82%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 1.82%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 1.82%   |
| Intel Core i7-5600U CPU @ 2.60GHz               | 1         | 1.82%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz              | 1         | 1.82%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz              | 1         | 1.82%   |
| Intel Core i7-3687U CPU @ 2.10GHz               | 1         | 1.82%   |
| Intel Core i7-3615QM CPU @ 2.30GHz              | 1         | 1.82%   |
| Intel Core i7-10870H CPU @ 2.20GHz              | 1         | 1.82%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz              | 1         | 1.82%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 1         | 1.82%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 1         | 1.82%   |
| Intel Core i5-5257U CPU @ 2.70GHz               | 1         | 1.82%   |
| Intel Core i5-3427U CPU @ 1.80GHz               | 1         | 1.82%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 1         | 1.82%   |
| Intel 11th Gen Core i7-11850H @ 2.50GHz         | 1         | 1.82%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics      | 1         | 1.82%   |
| AMD Ryzen 7 5700U with Radeon Graphics          | 1         | 1.82%   |
| AMD Ryzen 7 4800U with Radeon Graphics          | 1         | 1.82%   |
| AMD Ryzen 7 4700U with Radeon Graphics          | 1         | 1.82%   |
| AMD Ryzen 5 5500U with Radeon Graphics          | 1         | 1.82%   |
| AMD Ryzen 5 4600H with Radeon Graphics          | 1         | 1.82%   |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx   | 1         | 1.82%   |
| AMD E-450 APU with Radeon HD Graphics           | 1         | 1.82%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel Core i7   | 21        | 38.18%  |
| Intel Core i5   | 10        | 18.18%  |
| Other           | 6         | 10.91%  |
| AMD Ryzen 7     | 5         | 9.09%   |
| AMD Ryzen 5     | 4         | 7.27%   |
| AMD Ryzen 7 PRO | 3         | 5.45%   |
| AMD Ryzen 5 PRO | 2         | 3.64%   |
| Intel Xeon      | 1         | 1.82%   |
| Intel Pentium M | 1         | 1.82%   |
| AMD Ryzen 3     | 1         | 1.82%   |
| AMD E           | 1         | 1.82%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 19        | 34.55%  |
| 2      | 13        | 23.64%  |
| 8      | 10        | 18.18%  |
| 16     | 5         | 9.09%   |
| 6      | 5         | 9.09%   |
| 12     | 2         | 3.64%   |
| 1      | 1         | 1.82%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 55        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 38        | 69.09%  |
| 1       | 16        | 29.09%  |
| Unknown | 1         | 1.82%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| KabyLake  | 11        | 20%     |
| IvyBridge | 8         | 14.55%  |
| CometLake | 7         | 12.73%  |
| Zen+      | 6         | 10.91%  |
| Zen 2     | 6         | 10.91%  |
| TigerLake | 5         | 9.09%   |
| Unknown   | 3         | 5.45%   |
| Haswell   | 2         | 3.64%   |
| Broadwell | 2         | 3.64%   |
| Zen       | 1         | 1.82%   |
| Skylake   | 1         | 1.82%   |
| P6        | 1         | 1.82%   |
| IceLake   | 1         | 1.82%   |
| Bobcat    | 1         | 1.82%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 35        | 48.61%  |
| AMD    | 19        | 26.39%  |
| Nvidia | 18        | 25%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                           | 6         | 8.11%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series] | 6         | 8.11%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                            | 5         | 6.76%   |
| Intel CometLake-U GT2 [UHD Graphics]                                 | 5         | 6.76%   |
| Intel 3rd Gen Core processor Graphics Controller                     | 5         | 6.76%   |
| Intel CometLake-H GT2 [UHD Graphics]                                 | 4         | 5.41%   |
| Nvidia TU117M                                                        | 3         | 4.05%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                             | 3         | 4.05%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                           | 2         | 2.7%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                           | 2         | 2.7%    |
| Nvidia GP108M [GeForce MX230]                                        | 2         | 2.7%    |
| Intel HD Graphics 620                                                | 2         | 2.7%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                            | 2         | 2.7%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller          | 2         | 2.7%    |
| AMD Lucienne                                                         | 2         | 2.7%    |
| Nvidia TU117M [GeForce MX450]                                        | 1         | 1.35%   |
| Nvidia TU104GLM [Quadro RTX 5000 Mobile / Max-Q]                     | 1         | 1.35%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                           | 1         | 1.35%   |
| Nvidia GM108M [GeForce MX130]                                        | 1         | 1.35%   |
| Nvidia GM108M [GeForce 940MX]                                        | 1         | 1.35%   |
| Nvidia GM107M [GeForce GTX 860M]                                     | 1         | 1.35%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                          | 1         | 1.35%   |
| Nvidia GK107GLM [Quadro K1100M]                                      | 1         | 1.35%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                      | 1         | 1.35%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                           | 1         | 1.35%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                 | 1         | 1.35%   |
| Intel Skylake GT2 [HD Graphics 520]                                  | 1         | 1.35%   |
| Intel JasperLake [UHD Graphics]                                      | 1         | 1.35%   |
| Intel Iris Plus Graphics G7                                          | 1         | 1.35%   |
| Intel Iris Graphics 6100                                             | 1         | 1.35%   |
| Intel HD Graphics 630                                                | 1         | 1.35%   |
| Intel HD Graphics 5500                                               | 1         | 1.35%   |
| Intel Comet Lake-H WS GT2 Integrated UHD Graphics Controller         | 1         | 1.35%   |
| Intel 82852/855GM Integrated Graphics Device                         | 1         | 1.35%   |
| AMD Wrestler [Radeon HD 6320]                                        | 1         | 1.35%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]     | 1         | 1.35%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                       | 1         | 1.35%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]              | 1         | 1.35%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 19        | 33.93%  |
| 1 x AMD        | 16        | 28.57%  |
| Intel + Nvidia | 15        | 26.79%  |
| 1 x Nvidia     | 3         | 5.36%   |
| 2 x AMD        | 2         | 3.57%   |
| AMD + Nvidia   | 1         | 1.79%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 45        | 81.82%  |
| Proprietary | 10        | 18.18%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 44        | 77.19%  |
| 1.01-2.0   | 4         | 7.02%   |
| 0.51-1.0   | 4         | 7.02%   |
| 0.01-0.5   | 4         | 7.02%   |
| 3.01-4.0   | 1         | 1.75%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| BOE                 | 12        | 21.82%  |
| LG Display          | 10        | 18.18%  |
| AU Optronics        | 9         | 16.36%  |
| Chimei Innolux      | 4         | 7.27%   |
| Philips             | 3         | 5.45%   |
| Hewlett-Packard     | 3         | 5.45%   |
| Apple               | 2         | 3.64%   |
| ViewSonic           | 1         | 1.82%   |
| Sharp               | 1         | 1.82%   |
| SDC                 | 1         | 1.82%   |
| Samsung Electronics | 1         | 1.82%   |
| PANDA               | 1         | 1.82%   |
| LGD                 | 1         | 1.82%   |
| Lenovo              | 1         | 1.82%   |
| InfoVision          | 1         | 1.82%   |
| Iiyama              | 1         | 1.82%   |
| HJW                 | 1         | 1.82%   |
| Dell                | 1         | 1.82%   |
| CSO                 | 1         | 1.82%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0258 1600x900 350x190mm 15.7-inch          | 3         | 5.36%   |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                | 3         | 5.36%   |
| Philips LCD Monitor PHL08C3 1920x1080 600x340mm 27.2-inch            | 2         | 3.57%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch         | 2         | 3.57%   |
| ViewSonic LCD Monitor VSCD22B 1920x1080 520x290mm 23.4-inch          | 1         | 1.79%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 380x210mm 17.1-inch              | 1         | 1.79%   |
| SDC LCD Monitor 3520x1080                                            | 1         | 1.79%   |
| Samsung Electronics LCD Monitor SDC3754 1600x900 380x210mm 17.1-inch | 1         | 1.79%   |
| Philips LCD Monitor 271P4 3520x1080                                  | 1         | 1.79%   |
| Philips LCD Monitor 271P4                                            | 1         | 1.79%   |
| PANDA LCD Monitor NCP004F 1920x1080 310x170mm 13.9-inch              | 1         | 1.79%   |
| LGD LCD Monitor 1920x1080                                            | 1         | 1.79%   |
| LG Display LCD Monitor LGD062E 1920x1080 340x190mm 15.3-inch         | 1         | 1.79%   |
| LG Display LCD Monitor LGD060A 1920x1080 290x170mm 13.2-inch         | 1         | 1.79%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch         | 1         | 1.79%   |
| LG Display LCD Monitor LGD05F1 1920x1080 310x170mm 13.9-inch         | 1         | 1.79%   |
| LG Display LCD Monitor LGD033E 1366x768 310x170mm 13.9-inch          | 1         | 1.79%   |
| Lenovo LEN P44w-10 LEN61D5 3840x1200 1050x330mm 43.3-inch            | 1         | 1.79%   |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch         | 1         | 1.79%   |
| Iiyama PL2474H IVM6146 1920x1080 520x290mm 23.4-inch                 | 1         | 1.79%   |
| HJW HDMI TO USB HJW0001 1920x1080 700x390mm 31.5-inch                | 1         | 1.79%   |
| Hewlett-Packard LCD Monitor LA2306 3520x1080                         | 1         | 1.79%   |
| Hewlett-Packard LA2306 HWP2949 1920x1080 510x290mm 23.1-inch         | 1         | 1.79%   |
| Hewlett-Packard E242 HWP326E 1920x1200 520x320mm 24.0-inch           | 1         | 1.79%   |
| Dell U2718Q DELA0EC 3840x2160 610x350mm 27.7-inch                    | 1         | 1.79%   |
| CSO LCD Monitor CSO1500 3840x2160 340x190mm 15.3-inch                | 1         | 1.79%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 280x180mm 13.1-inch     | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 340x190mm 15.3-inch     | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN1484 1600x900 310x170mm 13.9-inch      | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN13A2 1920x1080 290x170mm 13.2-inch     | 1         | 1.79%   |
| BOE LCD Monitor BOE0982 3840x2160 310x170mm 13.9-inch                | 1         | 1.79%   |
| BOE LCD Monitor BOE0928 1920x1080 340x190mm 15.3-inch                | 1         | 1.79%   |
| BOE LCD Monitor BOE08D7 1920x1080 310x170mm 13.9-inch                | 1         | 1.79%   |
| BOE LCD Monitor BOE084D 1920x1080 340x190mm 15.3-inch                | 1         | 1.79%   |
| BOE LCD Monitor BOE07F1 1920x1080 340x190mm 15.3-inch                | 1         | 1.79%   |
| BOE LCD Monitor BOE07BB 1920x1080 310x170mm 13.9-inch                | 1         | 1.79%   |
| BOE LCD Monitor BOE0792 1920x1080 340x190mm 15.3-inch                | 1         | 1.79%   |
| BOE LCD Monitor BOE075A 1366x768 310x170mm 13.9-inch                 | 1         | 1.79%   |
| BOE LCD Monitor BOE0747 1920x1080 340x190mm 15.3-inch                | 1         | 1.79%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 340x190mm 15.3-inch       | 1         | 1.79%   |
| AU Optronics LCD Monitor AUOD0ED 1920x1080 340x190mm 15.3-inch       | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO5A2D 1920x1080 290x170mm 13.2-inch       | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO5699 1920x1080 340x190mm 15.3-inch       | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch       | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch        | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO2026 2560x1600 290x180mm 13.4-inch       | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO139D 1920x1080 380x210mm 17.1-inch       | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 310x170mm 13.9-inch       | 1         | 1.79%   |
| Apple Color LCD APPA029 2560x1600 290x180mm 13.4-inch                | 1         | 1.79%   |
| Apple Cinema HD APP9223 1920x1200 490x310mm 22.8-inch                | 1         | 1.79%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 31        | 58.49%  |
| 1600x900 (HD+)    | 6         | 11.32%  |
| 3840x2160 (4K)    | 3         | 5.66%   |
| 2256x1504         | 3         | 5.66%   |
| 2560x1600         | 2         | 3.77%   |
| 1920x1200 (WUXGA) | 2         | 3.77%   |
| 1366x768 (WXGA)   | 2         | 3.77%   |
| 3840x1200         | 1         | 1.89%   |
| 3520x1080         | 1         | 1.89%   |
| 2160x1440         | 1         | 1.89%   |
| Unknown           | 1         | 1.89%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 22        | 41.51%  |
| 15      | 14        | 26.42%  |
| 27      | 3         | 5.66%   |
| 23      | 3         | 5.66%   |
| 17      | 3         | 5.66%   |
| 12      | 2         | 3.77%   |
| Unknown | 2         | 3.77%   |
| 43      | 1         | 1.89%   |
| 31      | 1         | 1.89%   |
| 24      | 1         | 1.89%   |
| 22      | 1         | 1.89%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 27        | 51.92%  |
| 201-300     | 11        | 21.15%  |
| 501-600     | 5         | 9.62%   |
| 351-400     | 3         | 5.77%   |
| 601-700     | 2         | 3.85%   |
| Unknown     | 2         | 3.85%   |
| 401-500     | 1         | 1.92%   |
| 1001-1500   | 1         | 1.92%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 36        | 76.6%   |
| 16/10   | 5         | 10.64%  |
| 3/2     | 3         | 6.38%   |
| Unknown | 2         | 4.26%   |
| 3.18    | 1         | 2.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 18        | 33.96%  |
| 91-100         | 11        | 20.75%  |
| 71-80          | 4         | 7.55%   |
| 201-250        | 4         | 7.55%   |
| 301-350        | 3         | 5.66%   |
| 121-130        | 3         | 5.66%   |
| 101-110        | 3         | 5.66%   |
| 61-70          | 2         | 3.77%   |
| Unknown        | 2         | 3.77%   |
| 351-500        | 1         | 1.89%   |
| 251-300        | 1         | 1.89%   |
| 501-1000       | 1         | 1.89%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 23        | 44.23%  |
| 161-240       | 11        | 21.15%  |
| 51-100        | 8         | 15.38%  |
| 101-120       | 6         | 11.54%  |
| More than 240 | 2         | 3.85%   |
| Unknown       | 2         | 3.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 35        | 61.4%   |
| 0     | 14        | 24.56%  |
| 2     | 7         | 12.28%  |
| 3     | 1         | 1.75%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 46        | 46%     |
| Realtek Semiconductor | 28        | 28%     |
| TP-Link               | 5         | 5%      |
| Broadcom              | 5         | 5%      |
| Hewlett-Packard       | 4         | 4%      |
| Qualcomm Atheros      | 3         | 3%      |
| Ralink Technology     | 2         | 2%      |
| Edimax Technology     | 2         | 2%      |
| D-Link System         | 2         | 2%      |
| Lenovo                | 1         | 1%      |
| Google                | 1         | 1%      |
| BUFFALO               | 1         | 1%      |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 24        | 19.2%   |
| Intel Wi-Fi 6 AX200                                                        | 6         | 4.8%    |
| Intel Comet Lake PCH CNVi WiFi                                             | 6         | 4.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 6         | 4.8%    |
| Intel Wireless-AC 9260                                                     | 5         | 4%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                          | 5         | 4%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 5         | 4%      |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 4         | 3.2%    |
| Intel Wireless 8265 / 8275                                                 | 4         | 3.2%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                     | 4         | 3.2%    |
| HP hs2350 HSPA+ Mobile Broadband Module Network Adapter                    | 4         | 3.2%    |
| Intel Wi-Fi 6 AX201                                                        | 3         | 2.4%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 2         | 1.6%    |
| Ralink MT7601U Wireless Adapter                                            | 2         | 1.6%    |
| Intel Wireless 7260                                                        | 2         | 1.6%    |
| Intel Ethernet Connection (4) I219-LM                                      | 2         | 1.6%    |
| Intel Ethernet Connection (10) I219-V                                      | 2         | 1.6%    |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 2         | 1.6%    |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]        | 1         | 0.8%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                   | 1         | 0.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 0.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 0.8%    |
| Realtek RTL8188SU 802.11n WLAN Adapter                                     | 1         | 0.8%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 1         | 0.8%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 1         | 0.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 1         | 0.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 1         | 0.8%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 1         | 0.8%    |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                           | 1         | 0.8%    |
| Intel Wireless 8260                                                        | 1         | 0.8%    |
| Intel Wireless 7265                                                        | 1         | 0.8%    |
| Intel Wi-Fi 6 AX201 160MHz                                                 | 1         | 0.8%    |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                  | 1         | 0.8%    |
| Intel Ethernet Connection I219-LM                                          | 1         | 0.8%    |
| Intel Ethernet Connection I217-LM                                          | 1         | 0.8%    |
| Intel Ethernet Connection (7) I219-V                                       | 1         | 0.8%    |
| Intel Ethernet Connection (5) I219-V                                       | 1         | 0.8%    |
| Intel Ethernet Connection (3) I218-LM                                      | 1         | 0.8%    |
| Intel Ethernet Connection (14) I219-LM                                     | 1         | 0.8%    |
| Intel Ethernet Connection (13) I219-V                                      | 1         | 0.8%    |
| Intel Ethernet Connection (11) I219-LM                                     | 1         | 0.8%    |
| Intel Centrino Advanced-N 6235                                             | 1         | 0.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                            | 1         | 0.8%    |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller          | 1         | 0.8%    |
| Google Nexus/Pixel Device (charging + debug)                               | 1         | 0.8%    |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]             | 1         | 0.8%    |
| Edimax EW-7711MAC 802.11ac Wireless Adapter                                | 1         | 0.8%    |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]                   | 1         | 0.8%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                          | 1         | 0.8%    |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                | 1         | 0.8%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                         | 1         | 0.8%    |
| Broadcom BCM4331 802.11a/b/g/n                                             | 1         | 0.8%    |
| Broadcom BCM43224 802.11a/b/g/n                                            | 1         | 0.8%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                        | 1         | 0.8%    |
| Unknown                                                                    | 1         | 0.8%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 46        | 64.79%  |
| Realtek Semiconductor | 6         | 8.45%   |
| TP-Link               | 5         | 7.04%   |
| Broadcom              | 5         | 7.04%   |
| Ralink Technology     | 2         | 2.82%   |
| Qualcomm Atheros      | 2         | 2.82%   |
| Edimax Technology     | 2         | 2.82%   |
| D-Link System         | 2         | 2.82%   |
| BUFFALO               | 1         | 1.41%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                        | 6         | 8.45%   |
| Intel Comet Lake PCH CNVi WiFi                                             | 6         | 8.45%   |
| Intel Wireless-AC 9260                                                     | 5         | 7.04%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                          | 5         | 7.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 5         | 7.04%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 4         | 5.63%   |
| Intel Wireless 8265 / 8275                                                 | 4         | 5.63%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                     | 4         | 5.63%   |
| Intel Wi-Fi 6 AX201                                                        | 3         | 4.23%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 2         | 2.82%   |
| Ralink MT7601U Wireless Adapter                                            | 2         | 2.82%   |
| Intel Wireless 7260                                                        | 2         | 2.82%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 2         | 2.82%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]        | 1         | 1.41%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                   | 1         | 1.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 1.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 1.41%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                     | 1         | 1.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 1         | 1.41%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 1         | 1.41%   |
| Intel Wireless 8260                                                        | 1         | 1.41%   |
| Intel Wireless 7265                                                        | 1         | 1.41%   |
| Intel Wi-Fi 6 AX201 160MHz                                                 | 1         | 1.41%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                  | 1         | 1.41%   |
| Intel Centrino Advanced-N 6235                                             | 1         | 1.41%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 1         | 1.41%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]             | 1         | 1.41%   |
| Edimax EW-7711MAC 802.11ac Wireless Adapter                                | 1         | 1.41%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]                   | 1         | 1.41%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                | 1         | 1.41%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                         | 1         | 1.41%   |
| Broadcom BCM4331 802.11a/b/g/n                                             | 1         | 1.41%   |
| Broadcom BCM43224 802.11a/b/g/n                                            | 1         | 1.41%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                        | 1         | 1.41%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 26        | 53.06%  |
| Intel                 | 19        | 38.78%  |
| Qualcomm Atheros      | 1         | 2.04%   |
| Lenovo                | 1         | 2.04%   |
| Google                | 1         | 2.04%   |
| Broadcom              | 1         | 2.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 24        | 48.98%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 12.24%  |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 4.08%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 4.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 2.04%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 2.04%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 2.04%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                  | 1         | 2.04%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 2.04%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 2.04%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 2.04%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 2.04%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 2.04%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 2.04%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 2.04%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 2.04%   |
| Google Nexus/Pixel Device (charging + debug)                      | 1         | 2.04%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 2.04%   |
| Unknown                                                           | 1         | 2.04%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 56        | 51.85%  |
| Ethernet | 47        | 43.52%  |
| Modem    | 5         | 4.63%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 37        | 50%     |
| WiFi     | 34        | 45.95%  |
| Modem    | 3         | 4.05%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 44        | 80%     |
| 1     | 9         | 16.36%  |
| 3     | 2         | 3.64%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 47        | 78.33%  |
| Yes  | 13        | 21.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 33        | 76.74%  |
| Apple                           | 4         | 9.3%    |
| Realtek Semiconductor           | 2         | 4.65%   |
| Realtek                         | 1         | 2.33%   |
| Qualcomm Atheros Communications | 1         | 2.33%   |
| IMC Networks                    | 1         | 2.33%   |
| Broadcom                        | 1         | 2.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                          | 11        | 25.58%  |
| Intel AX200 Bluetooth                          | 6         | 13.95%  |
| Intel Bluetooth wireless interface             | 5         | 11.63%  |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 4         | 9.3%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 3         | 6.98%   |
| Intel AX210 Bluetooth                          | 3         | 6.98%   |
| Apple Bluetooth Host Controller                | 2         | 4.65%   |
| Realtek  Bluetooth Adapter                     | 1         | 2.33%   |
| Realtek Bluetooth Radio                        | 1         | 2.33%   |
| Realtek Bluetooth Radio                        | 1         | 2.33%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0         | 1         | 2.33%   |
| Intel Centrino Bluetooth Wireless Transceiver  | 1         | 2.33%   |
| IMC Networks Bluetooth module                  | 1         | 2.33%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 1         | 2.33%   |
| Apple Built-in Bluetooth 2.0+EDR HCI           | 1         | 2.33%   |
| Apple Apple Broadcom Built-in Bluetooth        | 1         | 2.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel           | 40        | 52.63%  |
| AMD             | 19        | 25%     |
| Nvidia          | 12        | 15.79%  |
| Lenovo          | 3         | 3.95%   |
| SteelSeries ApS | 1         | 1.32%   |
| CMX Systems     | 1         | 1.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                              | 15        | 15.79%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 8         | 8.42%   |
| Intel Comet Lake PCH cAVS                                           | 7         | 7.37%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 7         | 7.37%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 6         | 6.32%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller      | 5         | 5.26%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 5         | 5.26%   |
| Intel Comet Lake PCH-LP cAVS                                        | 5         | 5.26%   |
| Intel Sunrise Point-LP HD Audio                                     | 3         | 3.16%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]           | 3         | 3.16%   |
| Nvidia TU116 High Definition Audio Controller                       | 2         | 2.11%   |
| Nvidia GK107 HDMI Audio Controller                                  | 2         | 2.11%   |
| Intel Wildcat Point-LP High Definition Audio Controller             | 2         | 2.11%   |
| Intel Cannon Lake PCH cAVS                                          | 2         | 2.11%   |
| Intel Broadwell-U Audio Controller                                  | 2         | 2.11%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 2         | 2.11%   |
| AMD Navi 10 HDMI Audio                                              | 2         | 2.11%   |
| SteelSeries ApS SteelSeries Siberia 350                             | 1         | 1.05%   |
| Nvidia TU104 HD Audio Controller                                    | 1         | 1.05%   |
| Nvidia GP107GL High Definition Audio Controller                     | 1         | 1.05%   |
| Nvidia GA104 High Definition Audio Controller                       | 1         | 1.05%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                            | 1         | 1.05%   |
| Lenovo ThinkPad Dock Audio                                          | 1         | 1.05%   |
| Lenovo Realtek USB Audio                                            | 1         | 1.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 1         | 1.05%   |
| Intel Tiger Lake-H HD Audio Controller                              | 1         | 1.05%   |
| Intel Jasper Lake HD Audio                                          | 1         | 1.05%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller           | 1         | 1.05%   |
| Intel CM238 HD Audio Controller                                     | 1         | 1.05%   |
| Intel Cannon Point-LP High Definition Audio Controller              | 1         | 1.05%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller   | 1         | 1.05%   |
| CMX Systems USB PnP Audio Device                                    | 1         | 1.05%   |
| AMD Wrestler HDMI Audio                                             | 1         | 1.05%   |
| AMD SBx00 Azalia (Intel HDA)                                        | 1         | 1.05%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 20        | 30.77%  |
| SK hynix            | 12        | 18.46%  |
| Micron Technology   | 10        | 15.38%  |
| Kingston            | 6         | 9.23%   |
| Crucial             | 5         | 7.69%   |
| Ramaxel Technology  | 3         | 4.62%   |
| Smart               | 2         | 3.08%   |
| Unknown             | 1         | 1.54%   |
| Team                | 1         | 1.54%   |
| PNY                 | 1         | 1.54%   |
| Goodram             | 1         | 1.54%   |
| Gold Key            | 1         | 1.54%   |
| G.Skill             | 1         | 1.54%   |
| A-DATA Technology   | 1         | 1.54%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s        | 4         | 6.06%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 3.03%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 2         | 3.03%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s       | 2         | 3.03%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s        | 2         | 3.03%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s        | 2         | 3.03%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s         | 2         | 3.03%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s         | 2         | 3.03%   |
| Crucial RAM BL32G32C16S4B.M16FB1 32GB SODIMM DDR4 2667MT/s   | 2         | 3.03%   |
| Unknown RAM Module 1GB SODIMM DDR                            | 1         | 1.52%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s        | 1         | 1.52%   |
| Smart RAM SF4641G8CK8IWGKSEG 8GB SODIMM DDR4 2133MT/s        | 1         | 1.52%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s        | 1         | 1.52%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1867MT/s                 | 1         | 1.52%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                 | 1         | 1.52%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 1.52%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s      | 1         | 1.52%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 1.52%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 1         | 1.52%   |
| Samsung RAM M474A4G43AB1-CVF 32GB SODIMM DDR4 2933MT/s       | 1         | 1.52%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s        | 1         | 1.52%   |
| Samsung RAM M471B5674-M0-YK0 4GB Chip DDR3 1600MT/s          | 1         | 1.52%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 1         | 1.52%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s        | 1         | 1.52%   |
| Samsung RAM M471A5244BB0-CWE 4GB SODIMM DDR4 3200MT/s        | 1         | 1.52%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s       | 1         | 1.52%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s       | 1         | 1.52%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s       | 1         | 1.52%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 1         | 1.52%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s  | 1         | 1.52%   |
| Samsung RAM K4EBE304EB-EGCF 8GB Row Of Chips LPDDR3 1867MT/s | 1         | 1.52%   |
| Ramaxel RAM RMSA3320MJ78HAF-3200 8GB SODIMM DDR4 3200MT/s    | 1         | 1.52%   |
| Ramaxel RAM RMSA3300MH78HBF-2666 16GB SODIMM DDR4 2400MT/s   | 1         | 1.52%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s    | 1         | 1.52%   |
| PNY RAM 16GU2X16LIII43-12-K 16GB SODIMM DDR4 2667MT/s        | 1         | 1.52%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                   | 1         | 1.52%   |
| Micron RAM Module 2GB SODIMM DDR3 1600MT/s                   | 1         | 1.52%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s  | 1         | 1.52%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s        | 1         | 1.52%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s   | 1         | 1.52%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s        | 1         | 1.52%   |
| Kingston RAM Module 8GB SODIMM DDR4 2667MT/s                 | 1         | 1.52%   |
| Kingston RAM Module 16GB SODIMM DDR4 2667MT/s                | 1         | 1.52%   |
| Kingston RAM Module 16GB SODIMM DDR4 2400MT/s                | 1         | 1.52%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 2933MT/s         | 1         | 1.52%   |
| Kingston RAM KHX2400C14S4/4G 4GB SODIMM DDR4 2400MT/s        | 1         | 1.52%   |
| Kingston RAM 99U5428-063.A00LF 8GB SODIMM DDR3 1600MT/s      | 1         | 1.52%   |
| Kingston RAM 9905428-196.A00LF 8GB SODIMM DDR3 1333MT/s      | 1         | 1.52%   |
| Goodram RAM GR1600S364L11/8G 8GB SODIMM DDR3 1600MT/s        | 1         | 1.52%   |
| Gold Key RAM NMSO416E82-3200E 16GB SODIMM DDR4 3200MT/s      | 1         | 1.52%   |
| G.Skill RAM F4-2133C15-16GRS 16GB SODIMM DDR4 2133MT/s       | 1         | 1.52%   |
| Crucial RAM CT32G4SFD832A.C16FE 32GB SODIMM DDR4 3200MT/s    | 1         | 1.52%   |
| Crucial RAM CT16G4SFRA32A.M16FR 16GB SODIMM DDR4 3200MT/s    | 1         | 1.52%   |
| Crucial RAM CT16G4SFD832A.M16FJ 16GB SODIMM DDR4 3200MT/s    | 1         | 1.52%   |
| A-DATA RAM DDR4 3200 16GB SODIMM DDR4 2667MT/s               | 1         | 1.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 40        | 71.43%  |
| DDR3   | 13        | 23.21%  |
| LPDDR4 | 1         | 1.79%   |
| LPDDR3 | 1         | 1.79%   |
| DDR    | 1         | 1.79%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 52        | 91.23%  |
| Row Of Chips | 4         | 7.02%   |
| Chip         | 1         | 1.75%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 26        | 44.83%  |
| 16384 | 15        | 25.86%  |
| 4096  | 9         | 15.52%  |
| 32768 | 5         | 8.62%   |
| 2048  | 2         | 3.45%   |
| 1024  | 1         | 1.72%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 18        | 30.51%  |
| 2667    | 16        | 27.12%  |
| 1600    | 7         | 11.86%  |
| 1867    | 6         | 10.17%  |
| 2400    | 4         | 6.78%   |
| 2933    | 2         | 3.39%   |
| 2133    | 2         | 3.39%   |
| 4267    | 1         | 1.69%   |
| 1334    | 1         | 1.69%   |
| 1333    | 1         | 1.69%   |
| Unknown | 1         | 1.69%   |

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
| Chicony Electronics                    | 15        | 27.78%  |
| IMC Networks                           | 10        | 18.52%  |
| Realtek Semiconductor                  | 6         | 11.11%  |
| Lite-On Technology                     | 5         | 9.26%   |
| Acer                                   | 5         | 9.26%   |
| Sunplus Innovation Technology          | 3         | 5.56%   |
| Logitech                               | 3         | 5.56%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 5.56%   |
| Apple                                  | 2         | 3.7%    |
| Syntek                                 | 1         | 1.85%   |
| Microdia                               | 1         | 1.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                             | 7         | 12.73%  |
| Chicony Integrated Camera                                                  | 7         | 12.73%  |
| Sunplus Integrated_Webcam_HD                                               | 3         | 5.45%   |
| Lite-On Integrated Camera                                                  | 3         | 5.45%   |
| Chicony Integrated HP HD Webcam                                            | 3         | 5.45%   |
| Acer Integrated Camera                                                     | 3         | 5.45%   |
| Realtek Laptop Camera                                                      | 2         | 3.64%   |
| Realtek Integrated_Webcam_HD                                               | 2         | 3.64%   |
| Logitech Webcam C270                                                       | 2         | 3.64%   |
| Lite-On HP HD Camera                                                       | 2         | 3.64%   |
| Chicony ThinkPad T490 Webcam                                               | 2         | 3.64%   |
| Apple FaceTime HD Camera (Built-in)                                        | 2         | 3.64%   |
| Acer HD Webcam                                                             | 2         | 3.64%   |
| Syntek Lenovo EasyCamera                                                   | 1         | 1.82%   |
| Realtek USB 2 Webcam                                                       | 1         | 1.82%   |
| Realtek Realtek USB2.0 PC Camera                                           | 1         | 1.82%   |
| Microdia Dell Integrated HD Webcam                                         | 1         | 1.82%   |
| Logitech HD Pro Webcam C920                                                | 1         | 1.82%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 1         | 1.82%   |
| IMC Networks HD Camera                                                     | 1         | 1.82%   |
| IMC Networks EasyCamera                                                    | 1         | 1.82%   |
| Chicony USB2.0 0.3M UVC WebCam                                             | 1         | 1.82%   |
| Chicony Integrated IR Camera                                               | 1         | 1.82%   |
| Chicony HD Webcam                                                          | 1         | 1.82%   |
| Chicony Chicony USB2.0 Camera                                              | 1         | 1.82%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 1.82%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed]                | 1         | 1.82%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam   | 1         | 1.82%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 9         | 47.37%  |
| Validity Sensors           | 5         | 26.32%  |
| Shenzhen Goodix Technology | 4         | 21.05%  |
| AuthenTec                  | 1         | 5.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 20        | 35.09%  |
| 4     | 12        | 21.05%  |
| 1     | 10        | 17.54%  |
| 3     | 9         | 15.79%  |
| 5     | 4         | 7.02%   |
| 9     | 1         | 1.75%   |
| 0     | 1         | 1.75%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 44        | 34.65%  |
| Bluetooth                | 27        | 21.26%  |
| Net/wireless             | 22        | 17.32%  |
| Fingerprint reader       | 19        | 14.96%  |
| Card reader              | 8         | 6.3%    |
| Sound                    | 2         | 1.57%   |
| Net/ethernet             | 2         | 1.57%   |
| Firewire controller      | 2         | 1.57%   |
| Modem                    | 1         | 0.79%   |

