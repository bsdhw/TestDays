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

Total: 115

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| amd64 | 59        | 98.33%  |
| i386  | 1         | 1.67%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KDE5          | 15        | 23.44%  |
| XFCE          | 10        | 15.63%  |
| TWM           | 6         | 9.38%   |
| MATE          | 5         | 7.81%   |
| GNOME         | 5         | 7.81%   |
| Console       | 5         | 7.81%   |
| i3            | 3         | 4.69%   |
| Cinnamon      | 3         | 4.69%   |
| LXDE          | 2         | 3.13%   |
| Lumina        | 2         | 3.13%   |
| Xfwm4         | 1         | 1.56%   |
| sway          | 1         | 1.56%   |
| Picom         | 1         | 1.56%   |
| LXQt          | 1         | 1.56%   |
| GNUstep       | 1         | 1.56%   |
| Fluxbox       | 1         | 1.56%   |
| Enlightenment | 1         | 1.56%   |
| ctwm          | 1         | 1.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 52        | 82.54%  |
| Console | 9         | 14.29%  |
| Wayland | 2         | 3.17%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 22        | 35.48%  |
| SDDM    | 15        | 24.19%  |
| SLiM    | 9         | 14.52%  |
| GDM     | 7         | 11.29%  |
| XDM     | 5         | 8.06%   |
| LightDM | 3         | 4.84%   |
| Ly      | 1         | 1.61%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Notebooks | Percent |
|------------------|-----------|---------|
| C                | 45        | 72.58%  |
| en_US            | 7         | 11.29%  |
| zh_CN            | 2         | 3.23%   |
| en_GB            | 2         | 3.23%   |
| pt_PT            | 1         | 1.61%   |
| pl_PL            | 1         | 1.61%   |
| it_IT.ISO8859-15 | 1         | 1.61%   |
| fr_FR            | 1         | 1.61%   |
| de_DE            | 1         | 1.61%   |
| Unknown          | 1         | 1.61%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 56        | 93.33%  |
| BIOS | 4         | 6.67%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Zfs  | 47        | 78.33%  |
| Ufs  | 13        | 21.67%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 58        | 96.67%  |
| MBR  | 2         | 3.33%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 25        | 41.67%  |
| Dell                           | 9         | 15%     |
| Hewlett-Packard                | 8         | 13.33%  |
| Apple                          | 3         | 5%      |
| MSI                            | 2         | 3.33%   |
| Framework                      | 2         | 3.33%   |
| ASUSTek Computer               | 2         | 3.33%   |
| Valve                          | 1         | 1.67%   |
| Timi                           | 1         | 1.67%   |
| System76                       | 1         | 1.67%   |
| Notebook                       | 1         | 1.67%   |
| Matsushita Electric Industrial | 1         | 1.67%   |
| HUAWEI                         | 1         | 1.67%   |
| Google                         | 1         | 1.67%   |
| Avell High Performance         | 1         | 1.67%   |
| A-DATA Technology              | 1         | 1.67%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| HP EliteBook 8570p                          | 3         | 5%      |
| Framework Laptop                            | 2         | 3.33%   |
| Valve Jupiter                               | 1         | 1.67%   |
| Timi Redmi Book Pro 14 2022                 | 1         | 1.67%   |
| System76 Gazelle                            | 1         | 1.67%   |
| Notebook NS50_70MU                          | 1         | 1.67%   |
| MSI GE76 Raider 10UG                        | 1         | 1.67%   |
| MSI Bravo 15 A4DDR                          | 1         | 1.67%   |
| Matsushita Electric Industrial CF-T2BW1AXR  | 1         | 1.67%   |
| Lenovo XiaoXinPro-13ARE 2020 82DM           | 1         | 1.67%   |
| Lenovo ThinkPad X395 20NL001SMX             | 1         | 1.67%   |
| Lenovo ThinkPad X395 20NL000GPG             | 1         | 1.67%   |
| Lenovo ThinkPad X270 20HM004JBR             | 1         | 1.67%   |
| Lenovo ThinkPad X260 20F5A28AUK             | 1         | 1.67%   |
| Lenovo ThinkPad X13 Gen 1 20T2003PRT        | 1         | 1.67%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TLA055CD | 1         | 1.67%   |
| Lenovo ThinkPad X1 Extreme 20MF000BUS       | 1         | 1.67%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS1QC00    | 1         | 1.67%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS0BT00    | 1         | 1.67%   |
| Lenovo ThinkPad T495s 20QKS1812F            | 1         | 1.67%   |
| Lenovo ThinkPad T495 20NJ0010PB             | 1         | 1.67%   |
| Lenovo ThinkPad T470p 20J7S0PM00            | 1         | 1.67%   |
| Lenovo ThinkPad T430 2349H2G                | 1         | 1.67%   |
| Lenovo ThinkPad T14s Gen 2i 20WM00B7MX      | 1         | 1.67%   |
| Lenovo ThinkPad P15 Gen 1 20ST005VRT        | 1         | 1.67%   |
| Lenovo ThinkPad P14s Gen 1 20Y1CTO1WW       | 1         | 1.67%   |
| Lenovo ThinkPad E14 Gen 3 20Y7003SGE        | 1         | 1.67%   |
| Lenovo ThinkPad E14 20RBCTO1WW              | 1         | 1.67%   |
| Lenovo ThinkBook 14 G3 ACL 21A2             | 1         | 1.67%   |
| Lenovo Legion 5P 15IMH05H 82AW              | 1         | 1.67%   |
| Lenovo Legion 5 15IMH05 82AU                | 1         | 1.67%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY        | 1         | 1.67%   |
| Lenovo IdeaPad 330-15ARR 81D2               | 1         | 1.67%   |
| HUAWEI HN-WX9X                              | 1         | 1.67%   |
| HP ZBook 17 G2                              | 1         | 1.67%   |
| HP ProBook 455 G7                           | 1         | 1.67%   |
| HP ProBook 440 G7                           | 1         | 1.67%   |
| HP ProBook 440 G6                           | 1         | 1.67%   |
| HP EliteBook Folio 9470m                    | 1         | 1.67%   |
| Google Akemi                                | 1         | 1.67%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo ThinkPad                            | 18        | 30%     |
| HP EliteBook                               | 4         | 6.67%   |
| Dell Latitude                              | 4         | 6.67%   |
| HP ProBook                                 | 3         | 5%      |
| Lenovo Legion                              | 2         | 3.33%   |
| Lenovo IdeaPad                             | 2         | 3.33%   |
| Framework Laptop                           | 2         | 3.33%   |
| Valve Jupiter                              | 1         | 1.67%   |
| Timi Redmi                                 | 1         | 1.67%   |
| System76 Gazelle                           | 1         | 1.67%   |
| Notebook NS50                              | 1         | 1.67%   |
| MSI GE76                                   | 1         | 1.67%   |
| MSI Bravo                                  | 1         | 1.67%   |
| Matsushita Electric Industrial CF-T2BW1AXR | 1         | 1.67%   |
| Lenovo XiaoXinPro-13ARE                    | 1         | 1.67%   |
| Lenovo ThinkBook                           | 1         | 1.67%   |
| HUAWEI HN-WX9X                             | 1         | 1.67%   |
| HP ZBook                                   | 1         | 1.67%   |
| Google Akemi                               | 1         | 1.67%   |
| Dell Vostro                                | 1         | 1.67%   |
| Dell Precision                             | 1         | 1.67%   |
| Dell Inspiron                              | 1         | 1.67%   |
| Dell G5                                    | 1         | 1.67%   |
| Dell G3                                    | 1         | 1.67%   |
| Avell High Performance A62                 | 1         | 1.67%   |
| ASUS VivoBook                              | 1         | 1.67%   |
| ASUS 1215B                                 | 1         | 1.67%   |
| Apple MacBookPro12                         | 1         | 1.67%   |
| Apple MacBookPro10                         | 1         | 1.67%   |
| Apple MacBookAir5                          | 1         | 1.67%   |
| A-DATA XENIA159GENI72060                   | 1         | 1.67%   |
| Unknown                                    | 1         | 1.67%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 17        | 28.33%  |
| 2021 | 13        | 21.67%  |
| 2019 | 7         | 11.67%  |
| 2022 | 6         | 10%     |
| 2017 | 4         | 6.67%   |
| 2013 | 4         | 6.67%   |
| 2015 | 3         | 5%      |
| 2018 | 2         | 3.33%   |
| 2016 | 1         | 1.67%   |
| 2014 | 1         | 1.67%   |
| 2011 | 1         | 1.67%   |
| 2003 | 1         | 1.67%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 60        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 58        | 96.67%  |
| Yes  | 2         | 3.33%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 26        | 41.94%  |
| 8.01-16.0   | 15        | 24.19%  |
| 32.01-64.0  | 12        | 19.35%  |
| 64.01-256.0 | 4         | 6.45%   |
| 4.01-8.0    | 3         | 4.84%   |
| 24.01-32.0  | 1         | 1.61%   |
| 1.01-2.0    | 1         | 1.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.51-1.0   | 24        | 38.71%  |
| 1.01-2.0   | 18        | 29.03%  |
| 2.01-3.0   | 8         | 12.9%   |
| 0.01-0.5   | 7         | 11.29%  |
| 3.01-4.0   | 2         | 3.23%   |
| 24.01-32.0 | 2         | 3.23%   |
| 8.01-16.0  | 1         | 1.61%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 43        | 65.15%  |
| 2      | 21        | 31.82%  |
| 3      | 2         | 3.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 56        | 90.32%  |
| Yes       | 6         | 9.68%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 48        | 80%     |
| No        | 12        | 20%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 59        | 98.33%  |
| No        | 1         | 1.67%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 47        | 77.05%  |
| No        | 14        | 22.95%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 12        | 20%     |
| UK          | 6         | 10%     |
| Russia      | 6         | 10%     |
| Germany     | 6         | 10%     |
| Poland      | 4         | 6.67%   |
| China       | 4         | 6.67%   |
| Brazil      | 3         | 5%      |
| Portugal    | 2         | 3.33%   |
| Austria     | 2         | 3.33%   |
| Turkey      | 1         | 1.67%   |
| Switzerland | 1         | 1.67%   |
| Sweden      | 1         | 1.67%   |
| Spain       | 1         | 1.67%   |
| Peru        | 1         | 1.67%   |
| Netherlands | 1         | 1.67%   |
| Japan       | 1         | 1.67%   |
| Italy       | 1         | 1.67%   |
| India       | 1         | 1.67%   |
| France      | 1         | 1.67%   |
| Denmark     | 1         | 1.67%   |
| Croatia     | 1         | 1.67%   |
| Colombia    | 1         | 1.67%   |
| Belarus     | 1         | 1.67%   |
| Bangladesh  | 1         | 1.67%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Brighton       | 5         | 7.04%   |
| Moscow         | 3         | 4.23%   |
| London         | 3         | 4.23%   |
| Seattle        | 2         | 2.82%   |
| ЕЊta-ku      | 1         | 1.41%   |
| Zurich         | 1         | 1.41%   |
| Wuhan          | 1         | 1.41%   |
| Wieliczka      | 1         | 1.41%   |
| Washington     | 1         | 1.41%   |
| Warsaw         | 1         | 1.41%   |
| Vienna         | 1         | 1.41%   |
| Vancouver      | 1         | 1.41%   |
| Trosa          | 1         | 1.41%   |
| Thrissur       | 1         | 1.41%   |
| Stuttgart      | 1         | 1.41%   |
| St Petersburg  | 1         | 1.41%   |
| Slavonski Brod | 1         | 1.41%   |
| Shanghai       | 1         | 1.41%   |
| Rostov-on-Don  | 1         | 1.41%   |
| Riverside      | 1         | 1.41%   |
| Resana         | 1         | 1.41%   |
| Poulsbo        | 1         | 1.41%   |
| Pobiedziska    | 1         | 1.41%   |
| Paris          | 1         | 1.41%   |
| Omaha          | 1         | 1.41%   |
| Olympia        | 1         | 1.41%   |
| Northeim       | 1         | 1.41%   |
| New York       | 1         | 1.41%   |
| Neumünster    | 1         | 1.41%   |
| Montclair      | 1         | 1.41%   |
| Minsk          | 1         | 1.41%   |
| Milan          | 1         | 1.41%   |
| Medellín      | 1         | 1.41%   |
| Manchester     | 1         | 1.41%   |
| Maia           | 1         | 1.41%   |
| Madrid         | 1         | 1.41%   |
| Lima           | 1         | 1.41%   |
| Kislovodsk     | 1         | 1.41%   |
| Khabarovsk     | 1         | 1.41%   |
| Katowice       | 1         | 1.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 22        | 28     | 27.85%  |
| WDC                 | 13        | 20     | 16.46%  |
| Toshiba             | 7         | 15     | 8.86%   |
| KIOXIA              | 5         | 5      | 6.33%   |
| HGST                | 5         | 21     | 6.33%   |
| SK hynix            | 3         | 3      | 3.8%    |
| Seagate             | 3         | 3      | 3.8%    |
| Kingston            | 3         | 5      | 3.8%    |
| Apple               | 3         | 3      | 3.8%    |
| A-DATA Technology   | 3         | 3      | 3.8%    |
| Intel               | 2         | 2      | 2.53%   |
| Crucial             | 2         | 4      | 2.53%   |
| SPCC                | 1         | 1      | 1.27%   |
| Solid State Storage | 1         | 1      | 1.27%   |
| Silicon Motion      | 1         | 1      | 1.27%   |
| SanDisk             | 1         | 2      | 1.27%   |
| Mushkin             | 1         | 1      | 1.27%   |
| Micron Technology   | 1         | 1      | 1.27%   |
| LITEON              | 1         | 1      | 1.27%   |
| Fujitsu             | 1         | 2      | 1.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB                           | 5         | 5.88%   |
| HGST HTS725050A7E630 500GB                         | 4         | 4.71%   |
| Samsung HM251JX 250GB                              | 3         | 3.53%   |
| WDC WDS100T3X0C-00SJG0 1TB                         | 2         | 2.35%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB                 | 2         | 2.35%   |
| WDC PC SN730 NVMe 1024GB                           | 2         | 2.35%   |
| Seagate ST1000LM035-1RK172 1TB                     | 2         | 2.35%   |
| Samsung SSD 970 EVO Plus 1TB                       | 2         | 2.35%   |
| Samsung MZVLB512HBJQ-000L7 512GB                   | 2         | 2.35%   |
| KIOXIA KBG40ZNS256G NVMe 256GB                     | 2         | 2.35%   |
| HGST HTS721010A9E630 1TB                           | 2         | 2.35%   |
| Apple SSD SM256E 256GB                             | 2         | 2.35%   |
| WDC WDS500G1X0E-00AFY0 500GB                       | 1         | 1.18%   |
| WDC WDS100T1X0E-00AFY0 1TB                         | 1         | 1.18%   |
| WDC WD10SPZX-60Z10T0 1TB                           | 1         | 1.18%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB               | 1         | 1.18%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB               | 1         | 1.18%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB               | 1         | 1.18%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB               | 1         | 1.18%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB               | 1         | 1.18%   |
| Toshiba MQ04ABF100 1TB                             | 1         | 1.18%   |
| Toshiba KXG6APNV2T04 2TB                           | 1         | 1.18%   |
| SPCC M.2 PCIe SSD 1TB                              | 1         | 1.18%   |
| Solid State Storage CL1-3D128-Q11 NVMe SSSTC 128GB | 1         | 1.18%   |
| SK hynix PC300 HFS512GD9MND-5510A 512GB            | 1         | 1.18%   |
| SK hynix BC511 NVMe 256GB                          | 1         | 1.18%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB            | 1         | 1.18%   |
| Silicon Motion NE-256 256GB                        | 1         | 1.18%   |
| Seagate ST1000LM049-2GH172 1TB                     | 1         | 1.18%   |
| SanDisk SDSSDH3500G 500GB                          | 1         | 1.18%   |
| Samsung SSD PM851 mSATA 256GB                      | 1         | 1.18%   |
| Samsung SSD 980 PRO 1TB                            | 1         | 1.18%   |
| Samsung SSD 970 PRO 1TB                            | 1         | 1.18%   |
| Samsung SSD 970 EVO 1TB                            | 1         | 1.18%   |
| Samsung SSD 860 EVO 500GB                          | 1         | 1.18%   |
| Samsung SSD 850 EVO 250GB                          | 1         | 1.18%   |
| Samsung SSD 840 PRO Series 128GB                   | 1         | 1.18%   |
| Samsung PM9A1 NVMe 512GB                           | 1         | 1.18%   |
| Samsung MZVLW256HEHP-000L7 256GB                   | 1         | 1.18%   |
| Samsung MZVLB512HBJQ-000L2 512GB                   | 1         | 1.18%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 6         | 14     | 31.58%  |
| HGST                | 5         | 21     | 26.32%  |
| Seagate             | 3         | 3      | 15.79%  |
| Samsung Electronics | 3         | 3      | 15.79%  |
| WDC                 | 1         | 1      | 5.26%   |
| Fujitsu             | 1         | 2      | 5.26%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 5      | 30.77%  |
| Apple               | 3         | 3      | 23.08%  |
| SanDisk             | 1         | 2      | 7.69%   |
| LITEON              | 1         | 1      | 7.69%   |
| Kingston            | 1         | 2      | 7.69%   |
| Intel               | 1         | 1      | 7.69%   |
| Crucial             | 1         | 1      | 7.69%   |
| A-DATA Technology   | 1         | 1      | 7.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 43        | 62     | 62.32%  |
| SSD  | 13        | 16     | 18.84%  |
| HDD  | 13        | 44     | 18.84%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 43        | 62     | 62.32%  |
| SATA | 26        | 60     | 37.68%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 20        | 41     | 74.07%  |
| 0.51-1.0   | 7         | 19     | 25.93%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 18        | 27.69%  |
| 251-500    | 17        | 26.15%  |
| 501-1000   | 11        | 16.92%  |
| 51-100     | 7         | 10.77%  |
| 21-50      | 5         | 7.69%   |
| 1001-2000  | 4         | 6.15%   |
| 1-20       | 2         | 3.08%   |
| 2001-3000  | 1         | 1.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 39        | 59.09%  |
| 21-50    | 20        | 30.3%   |
| 101-250  | 5         | 7.58%   |
| 501-1000 | 1         | 1.52%   |
| 51-100   | 1         | 1.52%   |

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
| HGST HTS721010A9E630 1TB                  | 1         | 12     | 11.11%  |
| Fujitsu MHS2040AT D 40GB                  | 1         | 2      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 4         | 19     | 50%     |
| Samsung Electronics | 2         | 2      | 25%     |
| WDC                 | 1         | 1      | 12.5%   |
| Fujitsu             | 1         | 2      | 12.5%   |

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
| HDD  | 6         | 23     | 85.71%  |
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
| Works    | 57        | 95     | 85.07%  |
| Malfunc  | 7         | 24     | 10.45%  |
| Detected | 3         | 3      | 4.48%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 32        | 36.78%  |
| Samsung Electronics            | 16        | 18.39%  |
| SanDisk                        | 13        | 14.94%  |
| AMD                            | 8         | 9.2%    |
| KIOXIA                         | 4         | 4.6%    |
| SK hynix                       | 3         | 3.45%   |
| Toshiba                        | 2         | 2.3%    |
| Silicon Motion                 | 2         | 2.3%    |
| Micron Technology              | 2         | 2.3%    |
| Kingston Technology Company    | 2         | 2.3%    |
| ADATA Technology               | 2         | 2.3%    |
| Solid State Storage Technology | 1         | 1.15%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 10        | 10.99%  |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 9         | 9.89%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 7.69%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 7         | 7.69%   |
| Intel Comet Lake SATA AHCI Controller                                          | 5         | 5.49%   |
| Unknown                                                                        | 5         | 5.49%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 4         | 4.4%    |
| Samsung NVMe SSD Controller 980                                                | 3         | 3.3%    |
| KIOXIA NVMe SSD Controller BG4                                                 | 3         | 3.3%    |
| Toshiba XG6 NVMe SSD Controller                                                | 2         | 2.2%    |
| SK hynix BC511                                                                 | 2         | 2.2%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 2         | 2.2%    |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 2.2%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 2.2%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 2.2%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 2.2%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 2.2%    |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 2         | 2.2%    |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 2         | 2.2%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2         | 2.2%    |
| SK hynix PC300 NVMe Solid State Drive 512GB                                    | 1         | 1.1%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1         | 1.1%    |
| SanDisk PC SN530                                                               | 1         | 1.1%    |
| Samsung SM951 AHCI                                                             | 1         | 1.1%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 1.1%    |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 1         | 1.1%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 1.1%    |
| Intel SSD 660P Series                                                          | 1         | 1.1%    |
| Intel Jasper Lake SATA AHCI Controller                                         | 1         | 1.1%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 1.1%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 1.1%    |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 1         | 1.1%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1         | 1.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 1.1%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 1         | 1.1%    |
| ADATA IM2P33F8ABR1 NVMe SSD                                                    | 1         | 1.1%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 43        | 51.19%  |
| SATA | 38        | 45.24%  |
| IDE  | 3         | 3.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 43        | 70.49%  |
| AMD    | 18        | 29.51%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-10210U CPU @ 1.60GHz              | 5         | 8.2%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 5         | 8.2%    |
| Intel Core i7-3520M CPU @ 2.90GHz               | 4         | 6.56%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 3         | 4.92%   |
| Intel Core i7-7600U CPU @ 2.80GHz               | 2         | 3.28%   |
| Intel Core i5-10300H CPU @ 2.50GHz              | 2         | 3.28%   |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx | 2         | 3.28%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 2         | 3.28%   |
| AMD Ryzen 5 PRO 3500U w/ Radeon Vega Mobile Gfx | 2         | 3.28%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 2         | 3.28%   |
| Intel Xeon W-10885M CPU @ 2.40GHz               | 1         | 1.64%   |
| Intel Pentium M processor 1000MHz               | 1         | 1.64%   |
| Intel Core i7-9850H CPU @ 2.60GHz               | 1         | 1.64%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 1         | 1.64%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 1         | 1.64%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 1.64%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 1.64%   |
| Intel Core i7-5600U CPU @ 2.60GHz               | 1         | 1.64%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz              | 1         | 1.64%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz              | 1         | 1.64%   |
| Intel Core i7-4600U CPU @ 2.10GHz               | 1         | 1.64%   |
| Intel Core i7-3687U CPU @ 2.10GHz               | 1         | 1.64%   |
| Intel Core i7-3615QM CPU @ 2.30GHz              | 1         | 1.64%   |
| Intel Core i7-10870H CPU @ 2.20GHz              | 1         | 1.64%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz              | 1         | 1.64%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 1         | 1.64%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 1         | 1.64%   |
| Intel Core i5-5257U CPU @ 2.70GHz               | 1         | 1.64%   |
| Intel Core i5-3427U CPU @ 1.80GHz               | 1         | 1.64%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 1         | 1.64%   |
| Intel 11th Gen Core i7-11850H @ 2.50GHz         | 1         | 1.64%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz         | 1         | 1.64%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics      | 1         | 1.64%   |
| AMD Ryzen 7 6800H with Radeon Graphics          | 1         | 1.64%   |
| AMD Ryzen 7 5700U with Radeon Graphics          | 1         | 1.64%   |
| AMD Ryzen 7 4800U with Radeon Graphics          | 1         | 1.64%   |
| AMD Ryzen 7 4700U with Radeon Graphics          | 1         | 1.64%   |
| AMD Ryzen 5 5500U with Radeon Graphics          | 1         | 1.64%   |
| AMD Ryzen 5 4600H with Radeon Graphics          | 1         | 1.64%   |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx   | 1         | 1.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel Core i7   | 23        | 38.33%  |
| Intel Core i5   | 11        | 18.33%  |
| Other           | 7         | 11.67%  |
| AMD Ryzen 7     | 6         | 10%     |
| AMD Ryzen 5     | 4         | 6.67%   |
| AMD Ryzen 7 PRO | 3         | 5%      |
| AMD Ryzen 5 PRO | 2         | 3.33%   |
| Intel Xeon      | 1         | 1.67%   |
| Intel Pentium M | 1         | 1.67%   |
| AMD Ryzen 3     | 1         | 1.67%   |
| AMD E           | 1         | 1.67%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 20        | 32.79%  |
| 2      | 14        | 22.95%  |
| 8      | 12        | 19.67%  |
| 16     | 6         | 9.84%   |
| 6      | 6         | 9.84%   |
| 12     | 2         | 3.28%   |
| 1      | 1         | 1.64%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 60        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 42        | 68.85%  |
| 1       | 18        | 29.51%  |
| Unknown | 1         | 1.64%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| KabyLake  | 13        | 21.31%  |
| IvyBridge | 8         | 13.11%  |
| CometLake | 7         | 11.48%  |
| Zen+      | 6         | 9.84%   |
| Zen 2     | 6         | 9.84%   |
| Unknown   | 6         | 9.84%   |
| TigerLake | 5         | 8.2%    |
| Haswell   | 3         | 4.92%   |
| Broadwell | 2         | 3.28%   |
| Zen       | 1         | 1.64%   |
| Skylake   | 1         | 1.64%   |
| P6        | 1         | 1.64%   |
| IceLake   | 1         | 1.64%   |
| Bobcat    | 1         | 1.64%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 39        | 48.15%  |
| AMD    | 22        | 27.16%  |
| Nvidia | 20        | 24.69%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel CometLake-U GT2 [UHD Graphics]                                 | 6         | 7.23%   |
| AMD Renoir                                                           | 6         | 7.23%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series] | 6         | 7.23%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                            | 5         | 6.02%   |
| Intel 3rd Gen Core processor Graphics Controller                     | 5         | 6.02%   |
| Intel CometLake-H GT2 [UHD Graphics]                                 | 4         | 4.82%   |
| Nvidia TU117M                                                        | 3         | 3.61%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                            | 3         | 3.61%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                             | 3         | 3.61%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                           | 2         | 2.41%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                           | 2         | 2.41%   |
| Nvidia GP108M [GeForce MX230]                                        | 2         | 2.41%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                 | 2         | 2.41%   |
| Intel HD Graphics 620                                                | 2         | 2.41%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller          | 2         | 2.41%   |
| AMD Lucienne                                                         | 2         | 2.41%   |
| Nvidia TU117M [GeForce MX450]                                        | 1         | 1.2%    |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                | 1         | 1.2%    |
| Nvidia TU104GLM [Quadro RTX 5000 Mobile / Max-Q]                     | 1         | 1.2%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                           | 1         | 1.2%    |
| Nvidia GM108M [GeForce MX130]                                        | 1         | 1.2%    |
| Nvidia GM108M [GeForce 940MX]                                        | 1         | 1.2%    |
| Nvidia GM107M [GeForce GTX 860M]                                     | 1         | 1.2%    |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                          | 1         | 1.2%    |
| Nvidia GK107GLM [Quadro K1100M]                                      | 1         | 1.2%    |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                           | 1         | 1.2%    |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                      | 1         | 1.2%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                           | 1         | 1.2%    |
| Intel Skylake GT2 [HD Graphics 520]                                  | 1         | 1.2%    |
| Intel JasperLake [UHD Graphics]                                      | 1         | 1.2%    |
| Intel Iris Plus Graphics G7                                          | 1         | 1.2%    |
| Intel Iris Graphics 6100                                             | 1         | 1.2%    |
| Intel HD Graphics 630                                                | 1         | 1.2%    |
| Intel HD Graphics 5500                                               | 1         | 1.2%    |
| Intel Haswell-ULT Integrated Graphics Controller                     | 1         | 1.2%    |
| Intel Coffee Lake-S GT2 [UHD Graphics P630]                          | 1         | 1.2%    |
| Intel 82852/855GM Integrated Graphics Device                         | 1         | 1.2%    |
| AMD Wrestler [Radeon HD 6320]                                        | 1         | 1.2%    |
| AMD VanGogh [AMD Custom GPU 0405]                                    | 1         | 1.2%    |
| AMD Rembrandt [Radeon 680M]                                          | 1         | 1.2%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 21        | 33.87%  |
| 1 x AMD                  | 18        | 29.03%  |
| Intel + Nvidia           | 16        | 25.81%  |
| 1 x Nvidia               | 3         | 4.84%   |
| 2 x AMD                  | 2         | 3.23%   |
| Intel + AMD + 1 x Nvidia | 1         | 1.61%   |
| AMD + Nvidia             | 1         | 1.61%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 50        | 83.33%  |
| Proprietary | 10        | 16.67%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 48        | 77.42%  |
| 1.01-2.0   | 4         | 6.45%   |
| 0.51-1.0   | 4         | 6.45%   |
| 0.01-0.5   | 4         | 6.45%   |
| 3.01-4.0   | 1         | 1.61%   |
| 8.01-16.0  | 1         | 1.61%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| BOE                 | 13        | 22.41%  |
| LG Display          | 10        | 17.24%  |
| AU Optronics        | 9         | 15.52%  |
| Chimei Innolux      | 4         | 6.9%    |
| Philips             | 3         | 5.17%   |
| Hewlett-Packard     | 3         | 5.17%   |
| Sharp               | 2         | 3.45%   |
| InfoVision          | 2         | 3.45%   |
| Apple               | 2         | 3.45%   |
| ViewSonic           | 1         | 1.72%   |
| SDC                 | 1         | 1.72%   |
| Samsung Electronics | 1         | 1.72%   |
| PANDA               | 1         | 1.72%   |
| LGD                 | 1         | 1.72%   |
| Lenovo              | 1         | 1.72%   |
| Iiyama              | 1         | 1.72%   |
| HJW                 | 1         | 1.72%   |
| Dell                | 1         | 1.72%   |
| CSO                 | 1         | 1.72%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0258 1600x900 350x190mm 15.7-inch          | 3         | 5.08%   |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                | 3         | 5.08%   |
| Philips LCD Monitor PHL08C3 1920x1080 600x340mm 27.2-inch            | 2         | 3.39%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch         | 2         | 3.39%   |
| ViewSonic LCD Monitor VSCD22B 1920x1080 520x290mm 23.4-inch          | 1         | 1.69%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 380x210mm 17.1-inch              | 1         | 1.69%   |
| Sharp LCD Monitor SHP14B9 3840x2160 340x190mm 15.3-inch              | 1         | 1.69%   |
| SDC LCD Monitor 3520x1080                                            | 1         | 1.69%   |
| Samsung Electronics LCD Monitor SDC3754 1600x900 380x210mm 17.1-inch | 1         | 1.69%   |
| Philips LCD Monitor 271P4 3520x1080                                  | 1         | 1.69%   |
| Philips LCD Monitor 271P4                                            | 1         | 1.69%   |
| PANDA LCD Monitor NCP004F 1920x1080 310x170mm 13.9-inch              | 1         | 1.69%   |
| LGD LCD Monitor 1920x1080                                            | 1         | 1.69%   |
| LG Display LCD Monitor LGD062E 1920x1080 340x190mm 15.3-inch         | 1         | 1.69%   |
| LG Display LCD Monitor LGD060A 1920x1080 290x170mm 13.2-inch         | 1         | 1.69%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch         | 1         | 1.69%   |
| LG Display LCD Monitor LGD05F1 1920x1080 310x170mm 13.9-inch         | 1         | 1.69%   |
| LG Display LCD Monitor LGD033E 1366x768 310x170mm 13.9-inch          | 1         | 1.69%   |
| Lenovo LEN P44w-10 LEN61D5 3840x1200 1050x330mm 43.3-inch            | 1         | 1.69%   |
| InfoVision LCD Monitor IVO8544 1920x1080 290x170mm 13.2-inch         | 1         | 1.69%   |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch         | 1         | 1.69%   |
| Iiyama PL2474H IVM6146 1920x1080 520x290mm 23.4-inch                 | 1         | 1.69%   |
| HJW HDMI TO USB HJW0001 1920x1080 700x390mm 31.5-inch                | 1         | 1.69%   |
| Hewlett-Packard LCD Monitor LA2306 3520x1080                         | 1         | 1.69%   |
| Hewlett-Packard LA2306 HWP2949 1920x1080 510x290mm 23.1-inch         | 1         | 1.69%   |
| Hewlett-Packard E242 HWP326E 1920x1200 520x320mm 24.0-inch           | 1         | 1.69%   |
| Dell U2718Q DELA0EC 3840x2160 610x350mm 27.7-inch                    | 1         | 1.69%   |
| CSO LCD Monitor CSO1500 3840x2160 340x190mm 15.3-inch                | 1         | 1.69%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 280x180mm 13.1-inch     | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 340x190mm 15.3-inch     | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN1484 1600x900 310x170mm 13.9-inch      | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN13A2 1920x1080 290x170mm 13.2-inch     | 1         | 1.69%   |
| BOE LCD Monitor BOE0982 3840x2160 310x170mm 13.9-inch                | 1         | 1.69%   |
| BOE LCD Monitor BOE0928 1920x1080 340x190mm 15.3-inch                | 1         | 1.69%   |
| BOE LCD Monitor BOE08D7 1920x1080 310x170mm 13.9-inch                | 1         | 1.69%   |
| BOE LCD Monitor BOE084D 1920x1080 340x190mm 15.3-inch                | 1         | 1.69%   |
| BOE LCD Monitor BOE07F1 1920x1080 340x190mm 15.3-inch                | 1         | 1.69%   |
| BOE LCD Monitor BOE07BB 1920x1080 310x170mm 13.9-inch                | 1         | 1.69%   |
| BOE LCD Monitor BOE0792 1920x1080 340x190mm 15.3-inch                | 1         | 1.69%   |
| BOE LCD Monitor BOE075A 1366x768 310x170mm 13.9-inch                 | 1         | 1.69%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 32        | 57.14%  |
| 1600x900 (HD+)    | 6         | 10.71%  |
| 3840x2160 (4K)    | 4         | 7.14%   |
| 2256x1504         | 3         | 5.36%   |
| 1366x768 (WXGA)   | 3         | 5.36%   |
| 2560x1600         | 2         | 3.57%   |
| 1920x1200 (WUXGA) | 2         | 3.57%   |
| 3840x1200         | 1         | 1.79%   |
| 3520x1080         | 1         | 1.79%   |
| 2160x1440         | 1         | 1.79%   |
| Unknown           | 1         | 1.79%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 23        | 41.07%  |
| 15      | 15        | 26.79%  |
| 27      | 3         | 5.36%   |
| 23      | 3         | 5.36%   |
| 17      | 3         | 5.36%   |
| 12      | 3         | 5.36%   |
| Unknown | 2         | 3.57%   |
| 43      | 1         | 1.79%   |
| 31      | 1         | 1.79%   |
| 24      | 1         | 1.79%   |
| 22      | 1         | 1.79%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 28        | 50.91%  |
| 201-300     | 13        | 23.64%  |
| 501-600     | 5         | 9.09%   |
| 351-400     | 3         | 5.45%   |
| 601-700     | 2         | 3.64%   |
| Unknown     | 2         | 3.64%   |
| 401-500     | 1         | 1.82%   |
| 1001-1500   | 1         | 1.82%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 39        | 78%     |
| 16/10   | 5         | 10%     |
| 3/2     | 3         | 6%      |
| Unknown | 2         | 4%      |
| 3.18    | 1         | 2%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 18        | 32.14%  |
| 91-100         | 12        | 21.43%  |
| 71-80          | 5         | 8.93%   |
| 201-250        | 4         | 7.14%   |
| 61-70          | 3         | 5.36%   |
| 301-350        | 3         | 5.36%   |
| 121-130        | 3         | 5.36%   |
| 101-110        | 3         | 5.36%   |
| Unknown        | 2         | 3.57%   |
| 351-500        | 1         | 1.79%   |
| 251-300        | 1         | 1.79%   |
| 501-1000       | 1         | 1.79%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 24        | 43.64%  |
| 161-240       | 12        | 21.82%  |
| 51-100        | 8         | 14.55%  |
| 101-120       | 6         | 10.91%  |
| More than 240 | 3         | 5.45%   |
| Unknown       | 2         | 3.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 39        | 61.9%   |
| 0     | 16        | 25.4%   |
| 2     | 7         | 11.11%  |
| 3     | 1         | 1.59%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 50        | 46.73%  |
| Realtek Semiconductor | 31        | 28.97%  |
| TP-Link               | 5         | 4.67%   |
| Broadcom              | 5         | 4.67%   |
| Hewlett-Packard       | 4         | 3.74%   |
| Qualcomm Atheros      | 3         | 2.8%    |
| Ralink Technology     | 2         | 1.87%   |
| Edimax Technology     | 2         | 1.87%   |
| D-Link System         | 2         | 1.87%   |
| Lenovo                | 1         | 0.93%   |
| Google                | 1         | 0.93%   |
| BUFFALO               | 1         | 0.93%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 25        | 18.8%   |
| Intel Wireless-AC 9260                                                     | 6         | 4.51%   |
| Intel Wi-Fi 6 AX200                                                        | 6         | 4.51%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                          | 6         | 4.51%   |
| Intel Comet Lake PCH CNVi WiFi                                             | 6         | 4.51%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 6         | 4.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 6         | 4.51%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 4         | 3.01%   |
| Intel Wireless 8265 / 8275                                                 | 4         | 3.01%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                     | 4         | 3.01%   |
| HP hs2350 HSPA+ Mobile Broadband Module Network Adapter                    | 4         | 3.01%   |
| Intel Wi-Fi 6 AX201                                                        | 3         | 2.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 2         | 1.5%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 2         | 1.5%    |
| Ralink MT7601U Wireless Adapter                                            | 2         | 1.5%    |
| Intel Wireless 7260                                                        | 2         | 1.5%    |
| Intel Ethernet Connection (4) I219-LM                                      | 2         | 1.5%    |
| Intel Ethernet Connection (10) I219-V                                      | 2         | 1.5%    |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 2         | 1.5%    |
| Unknown                                                                    | 2         | 1.5%    |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]        | 1         | 0.75%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                   | 1         | 0.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 0.75%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                     | 1         | 0.75%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 1         | 0.75%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 1         | 0.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 1         | 0.75%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 1         | 0.75%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 1         | 0.75%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                           | 1         | 0.75%   |
| Intel Wireless 8260                                                        | 1         | 0.75%   |
| Intel Wireless 7265                                                        | 1         | 0.75%   |
| Intel Wi-Fi 6 AX201 160MHz                                                 | 1         | 0.75%   |
| Intel Tiger Lake PCH CNVi WiFi                                             | 1         | 0.75%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                  | 1         | 0.75%   |
| Intel Ethernet Connection I219-LM                                          | 1         | 0.75%   |
| Intel Ethernet Connection I218-LM                                          | 1         | 0.75%   |
| Intel Ethernet Connection I217-LM                                          | 1         | 0.75%   |
| Intel Ethernet Connection (7) I219-V                                       | 1         | 0.75%   |
| Intel Ethernet Connection (5) I219-V                                       | 1         | 0.75%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 50        | 65.79%  |
| Realtek Semiconductor | 7         | 9.21%   |
| TP-Link               | 5         | 6.58%   |
| Broadcom              | 5         | 6.58%   |
| Ralink Technology     | 2         | 2.63%   |
| Qualcomm Atheros      | 2         | 2.63%   |
| Edimax Technology     | 2         | 2.63%   |
| D-Link System         | 2         | 2.63%   |
| BUFFALO               | 1         | 1.32%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Wireless-AC 9260                                                     | 6         | 7.89%   |
| Intel Wi-Fi 6 AX200                                                        | 6         | 7.89%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                          | 6         | 7.89%   |
| Intel Comet Lake PCH CNVi WiFi                                             | 6         | 7.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 6         | 7.89%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 4         | 5.26%   |
| Intel Wireless 8265 / 8275                                                 | 4         | 5.26%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                     | 4         | 5.26%   |
| Intel Wi-Fi 6 AX201                                                        | 3         | 3.95%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 2         | 2.63%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 2         | 2.63%   |
| Ralink MT7601U Wireless Adapter                                            | 2         | 2.63%   |
| Intel Wireless 7260                                                        | 2         | 2.63%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 2         | 2.63%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]        | 1         | 1.32%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                   | 1         | 1.32%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 1.32%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                     | 1         | 1.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 1         | 1.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 1         | 1.32%   |
| Intel Wireless 8260                                                        | 1         | 1.32%   |
| Intel Wireless 7265                                                        | 1         | 1.32%   |
| Intel Wi-Fi 6 AX201 160MHz                                                 | 1         | 1.32%   |
| Intel Tiger Lake PCH CNVi WiFi                                             | 1         | 1.32%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                  | 1         | 1.32%   |
| Intel Centrino Advanced-N 6235                                             | 1         | 1.32%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 1         | 1.32%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]             | 1         | 1.32%   |
| Edimax EW-7711MAC 802.11ac Wireless Adapter                                | 1         | 1.32%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]                   | 1         | 1.32%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                | 1         | 1.32%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                         | 1         | 1.32%   |
| Broadcom BCM4331 802.11a/b/g/n                                             | 1         | 1.32%   |
| Broadcom BCM43224 802.11a/b/g/n                                            | 1         | 1.32%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                        | 1         | 1.32%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 27        | 52.94%  |
| Intel                 | 20        | 39.22%  |
| Qualcomm Atheros      | 1         | 1.96%   |
| Lenovo                | 1         | 1.96%   |
| Google                | 1         | 1.96%   |
| Broadcom              | 1         | 1.96%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 25        | 49.02%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 11.76%  |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 3.92%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 3.92%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.96%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.96%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.96%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                  | 1         | 1.96%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.96%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.96%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.96%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.96%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 1.96%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.96%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 1.96%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.96%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 1.96%   |
| Google Nexus/Pixel Device (charging + debug)                      | 1         | 1.96%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.96%   |
| Unknown                                                           | 1         | 1.96%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 60        | 52.17%  |
| Ethernet | 49        | 42.61%  |
| Modem    | 5         | 4.35%   |
| Unknown  | 1         | 0.87%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 39        | 49.37%  |
| Ethernet | 37        | 46.84%  |
| Modem    | 3         | 3.8%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 46        | 76.67%  |
| 1     | 12        | 20%     |
| 3     | 2         | 3.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 52        | 78.79%  |
| Yes  | 14        | 21.21%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 36        | 75%     |
| Apple                           | 4         | 8.33%   |
| Realtek Semiconductor           | 2         | 4.17%   |
| IMC Networks                    | 2         | 4.17%   |
| Realtek                         | 1         | 2.08%   |
| Qualcomm Atheros Communications | 1         | 2.08%   |
| Opticis                         | 1         | 2.08%   |
| Broadcom                        | 1         | 2.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                          | 13        | 27.08%  |
| Intel AX200 Bluetooth                          | 6         | 12.5%   |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 5         | 10.42%  |
| Intel Bluetooth wireless interface             | 5         | 10.42%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 3         | 6.25%   |
| Intel AX210 Bluetooth                          | 3         | 6.25%   |
| Apple Bluetooth Host Controller                | 2         | 4.17%   |
| Realtek  Bluetooth Adapter                     | 1         | 2.08%   |
| Realtek Bluetooth Radio                        | 1         | 2.08%   |
| Realtek Bluetooth Radio                        | 1         | 2.08%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0         | 1         | 2.08%   |
| Opticis Bluetooth Radio                        | 1         | 2.08%   |
| Intel Centrino Bluetooth Wireless Transceiver  | 1         | 2.08%   |
| IMC Networks Bluetooth Radio                   | 1         | 2.08%   |
| IMC Networks Bluetooth module                  | 1         | 2.08%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 1         | 2.08%   |
| Apple Built-in Bluetooth 2.0+EDR HCI           | 1         | 2.08%   |
| Apple Apple Broadcom Built-in Bluetooth        | 1         | 2.08%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor            | Notebooks | Percent |
|-------------------|-----------|---------|
| Intel             | 44        | 51.76%  |
| AMD               | 22        | 25.88%  |
| Nvidia            | 13        | 15.29%  |
| Lenovo            | 3         | 3.53%   |
| Texas Instruments | 1         | 1.18%   |
| SteelSeries ApS   | 1         | 1.18%   |
| CMX Systems       | 1         | 1.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                              | 16        | 15.09%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 8         | 7.55%   |
| Intel Comet Lake PCH cAVS                                           | 7         | 6.6%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 7         | 6.6%    |
| Intel Comet Lake PCH-LP cAVS                                        | 6         | 5.66%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 6         | 5.66%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller      | 5         | 4.72%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 5         | 4.72%   |
| Intel Sunrise Point-LP HD Audio                                     | 3         | 2.83%   |
| Intel Cannon Lake PCH cAVS                                          | 3         | 2.83%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]           | 3         | 2.83%   |
| Nvidia TU116 High Definition Audio Controller                       | 2         | 1.89%   |
| Nvidia GK107 HDMI Audio Controller                                  | 2         | 1.89%   |
| Intel Wildcat Point-LP High Definition Audio Controller             | 2         | 1.89%   |
| Intel Tiger Lake-H HD Audio Controller                              | 2         | 1.89%   |
| Intel Broadwell-U Audio Controller                                  | 2         | 1.89%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 2         | 1.89%   |
| AMD Rembrandt Radeon High Definition Audio Controller               | 2         | 1.89%   |
| AMD Navi 10 HDMI Audio                                              | 2         | 1.89%   |
| Texas Instruments PCM2706 stereo audio DAC                          | 1         | 0.94%   |
| SteelSeries ApS SteelSeries Siberia 350                             | 1         | 0.94%   |
| Nvidia TU104 HD Audio Controller                                    | 1         | 0.94%   |
| Nvidia GP107GL High Definition Audio Controller                     | 1         | 0.94%   |
| Nvidia GA104 High Definition Audio Controller                       | 1         | 0.94%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                            | 1         | 0.94%   |
| Lenovo ThinkPad Dock Audio                                          | 1         | 0.94%   |
| Lenovo Realtek USB Audio                                            | 1         | 0.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 1         | 0.94%   |
| Intel Jasper Lake HD Audio                                          | 1         | 0.94%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller           | 1         | 0.94%   |
| Intel Haswell-ULT HD Audio Controller                               | 1         | 0.94%   |
| Intel CM238 HD Audio Controller                                     | 1         | 0.94%   |
| Intel Cannon Point-LP High Definition Audio Controller              | 1         | 0.94%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller   | 1         | 0.94%   |
| Intel 8 Series HD Audio Controller                                  | 1         | 0.94%   |
| CMX Systems USB PnP Audio Device                                    | 1         | 0.94%   |
| AMD Wrestler HDMI Audio                                             | 1         | 0.94%   |
| AMD SBx00 Azalia (Intel HDA)                                        | 1         | 0.94%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                             | 1         | 0.94%   |
| Unknown                                                             | 1         | 0.94%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 20        | 28.17%  |
| SK hynix            | 12        | 16.9%   |
| Micron Technology   | 10        | 14.08%  |
| Kingston            | 6         | 8.45%   |
| Crucial             | 6         | 8.45%   |
| Ramaxel Technology  | 3         | 4.23%   |
| Unknown             | 2         | 2.82%   |
| Smart               | 2         | 2.82%   |
| Unknown             | 2         | 2.82%   |
| Team                | 1         | 1.41%   |
| PNY                 | 1         | 1.41%   |
| Neo Forza           | 1         | 1.41%   |
| Goodram             | 1         | 1.41%   |
| Gold Key            | 1         | 1.41%   |
| G.Skill             | 1         | 1.41%   |
| Elpida              | 1         | 1.41%   |
| A-DATA Technology   | 1         | 1.41%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s        | 4         | 5.56%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 2.78%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 2         | 2.78%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s       | 2         | 2.78%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s        | 2         | 2.78%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s        | 2         | 2.78%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s         | 2         | 2.78%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s         | 2         | 2.78%   |
| Crucial RAM BL32G32C16S4B.M16FB1 32GB SODIMM DDR4 2667MT/s   | 2         | 2.78%   |
| Unknown                                                      | 2         | 2.78%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                  | 1         | 1.39%   |
| Unknown RAM Module 1GB SODIMM DDR                            | 1         | 1.39%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s         | 1         | 1.39%   |
| Smart RAM SF4641G8CK8IWGKSEG 8GB SODIMM DDR4 2133MT/s        | 1         | 1.39%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s        | 1         | 1.39%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1867MT/s                 | 1         | 1.39%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                 | 1         | 1.39%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 1.39%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s      | 1         | 1.39%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 1.39%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 1         | 1.39%   |
| Samsung RAM M474A4G43AB1-CVF 32GB SODIMM DDR4 2933MT/s       | 1         | 1.39%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s        | 1         | 1.39%   |
| Samsung RAM M471B5674-M0-YK0 4GB Chip DDR3 1600MT/s          | 1         | 1.39%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 1         | 1.39%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s        | 1         | 1.39%   |
| Samsung RAM M471A5244BB0-CWE 4GB SODIMM DDR4 3200MT/s        | 1         | 1.39%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s       | 1         | 1.39%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s       | 1         | 1.39%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s       | 1         | 1.39%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 1         | 1.39%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s  | 1         | 1.39%   |
| Samsung RAM K4EBE304EB-EGCF 8GB Row Of Chips LPDDR3 1867MT/s | 1         | 1.39%   |
| Ramaxel RAM RMSA3320MJ78HAF-3200 8GB SODIMM DDR4 3200MT/s    | 1         | 1.39%   |
| Ramaxel RAM RMSA3300MH78HBF-2666 16GB SODIMM DDR4 2400MT/s   | 1         | 1.39%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s    | 1         | 1.39%   |
| PNY RAM 16GU2X16LIII43-12-K 16GB SODIMM DDR4 2667MT/s        | 1         | 1.39%   |
| Neo Forza RAM NMSO432F82-3200E 32GB SODIMM DDR4 3200MT/s     | 1         | 1.39%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                   | 1         | 1.39%   |
| Micron RAM Module 2GB SODIMM DDR3 1600MT/s                   | 1         | 1.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 44        | 70.97%  |
| DDR3   | 13        | 20.97%  |
| LPDDR5 | 2         | 3.23%   |
| LPDDR4 | 1         | 1.61%   |
| LPDDR3 | 1         | 1.61%   |
| DDR    | 1         | 1.61%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 56        | 90.32%  |
| Row Of Chips | 5         | 8.06%   |
| Chip         | 1         | 1.61%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 27        | 42.19%  |
| 16384 | 16        | 25%     |
| 4096  | 12        | 18.75%  |
| 32768 | 6         | 9.38%   |
| 2048  | 2         | 3.13%   |
| 1024  | 1         | 1.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 20        | 30.77%  |
| 2667    | 17        | 26.15%  |
| 1600    | 7         | 10.77%  |
| 1867    | 6         | 9.23%   |
| 2400    | 5         | 7.69%   |
| 2933    | 2         | 3.08%   |
| 2133    | 2         | 3.08%   |
| 6400    | 1         | 1.54%   |
| 4267    | 1         | 1.54%   |
| 4266    | 1         | 1.54%   |
| 1334    | 1         | 1.54%   |
| 1333    | 1         | 1.54%   |
| Unknown | 1         | 1.54%   |

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
| Chicony Electronics                    | 15        | 25.86%  |
| IMC Networks                           | 10        | 17.24%  |
| Realtek Semiconductor                  | 6         | 10.34%  |
| Lite-On Technology                     | 5         | 8.62%   |
| Acer                                   | 5         | 8.62%   |
| Sunplus Innovation Technology          | 3         | 5.17%   |
| Microdia                               | 3         | 5.17%   |
| Logitech                               | 3         | 5.17%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 5.17%   |
| Syntek                                 | 2         | 3.45%   |
| Apple                                  | 2         | 3.45%   |
| SunplusIT                              | 1         | 1.72%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                             | 7         | 11.86%  |
| Chicony Integrated Camera                                                  | 7         | 11.86%  |
| Sunplus Integrated_Webcam_HD                                               | 3         | 5.08%   |
| Lite-On Integrated Camera                                                  | 3         | 5.08%   |
| Chicony Integrated HP HD Webcam                                            | 3         | 5.08%   |
| Acer Integrated Camera                                                     | 3         | 5.08%   |
| Realtek Laptop Camera                                                      | 2         | 3.39%   |
| Realtek Integrated_Webcam_HD                                               | 2         | 3.39%   |
| Microdia Integrated Webcam                                                 | 2         | 3.39%   |
| Logitech Webcam C270                                                       | 2         | 3.39%   |
| Lite-On HP HD Camera                                                       | 2         | 3.39%   |
| Chicony ThinkPad T490 Webcam                                               | 2         | 3.39%   |
| Apple FaceTime HD Camera (Built-in)                                        | 2         | 3.39%   |
| Acer HD Webcam                                                             | 2         | 3.39%   |
| Syntek Lenovo EasyCamera                                                   | 1         | 1.69%   |
| Syntek Integrated Camera                                                   | 1         | 1.69%   |
| SunplusIT XiaoMi USB 2.0 Webcam                                            | 1         | 1.69%   |
| Realtek USB 2 Webcam                                                       | 1         | 1.69%   |
| Realtek Realtek USB2.0 PC Camera                                           | 1         | 1.69%   |
| Microdia Dell Integrated HD Webcam                                         | 1         | 1.69%   |
| Logitech HD Pro Webcam C920                                                | 1         | 1.69%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 1         | 1.69%   |
| IMC Networks HD Camera                                                     | 1         | 1.69%   |
| IMC Networks EasyCamera                                                    | 1         | 1.69%   |
| Chicony USB2.0 0.3M UVC WebCam                                             | 1         | 1.69%   |
| Chicony Integrated IR Camera                                               | 1         | 1.69%   |
| Chicony HD Webcam                                                          | 1         | 1.69%   |
| Chicony Chicony USB2.0 Camera                                              | 1         | 1.69%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 1.69%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed]                | 1         | 1.69%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam   | 1         | 1.69%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 9         | 45%     |
| Validity Sensors           | 5         | 25%     |
| Shenzhen Goodix Technology | 5         | 25%     |
| AuthenTec                  | 1         | 5%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 6         | 30%     |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 15%     |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 10%     |
| Validity Sensors Synaptics WBDI                                            | 2         | 10%     |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 10%     |
| Shenzhen Goodix  FingerPrint Device                                        | 2         | 10%     |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 5%      |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 5%      |
| AuthenTec AES2810                                                          | 1         | 5%      |

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
| 2     | 24        | 37.5%   |
| 4     | 12        | 18.75%  |
| 1     | 12        | 18.75%  |
| 3     | 9         | 14.06%  |
| 5     | 4         | 6.25%   |
| 0     | 2         | 3.13%   |
| 9     | 1         | 1.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 48        | 35.82%  |
| Bluetooth                | 29        | 21.64%  |
| Net/wireless             | 22        | 16.42%  |
| Fingerprint reader       | 19        | 14.18%  |
| Card reader              | 8         | 5.97%   |
| Sound                    | 2         | 1.49%   |
| Net/ethernet             | 2         | 1.49%   |
| Firewire controller      | 2         | 1.49%   |
| Network                  | 1         | 0.75%   |
| Modem                    | 1         | 0.75%   |

