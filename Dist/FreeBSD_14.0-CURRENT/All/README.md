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

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
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

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 52        | 77.61%  |
| arm64 | 12        | 17.91%  |
| riscv | 1         | 1.49%   |
| i386  | 1         | 1.49%   |
| arm   | 1         | 1.49%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KDE5          | 19        | 26.76%  |
| Console       | 16        | 22.54%  |
| XFCE          | 9         | 12.68%  |
| MATE          | 6         | 8.45%   |
| TWM           | 4         | 5.63%   |
| i3            | 4         | 5.63%   |
| GNOME         | 3         | 4.23%   |
| Cinnamon      | 3         | 4.23%   |
| Openbox       | 2         | 2.82%   |
| LXQt          | 1         | 1.41%   |
| LXDE          | 1         | 1.41%   |
| Lumina        | 1         | 1.41%   |
| Fluxbox       | 1         | 1.41%   |
| Enlightenment | 1         | 1.41%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 48        | 68.57%  |
| Console | 21        | 30%     |
| Wayland | 1         | 1.43%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 32        | 46.38%  |
| SDDM    | 16        | 23.19%  |
| SLiM    | 8         | 11.59%  |
| GDM     | 7         | 10.14%  |
| XDM     | 5         | 7.25%   |
| LightDM | 1         | 1.45%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Computers | Percent |
|------------------|-----------|---------|
| C                | 40        | 57.97%  |
| en_US            | 8         | 11.59%  |
| Unknown          | 4         | 5.8%    |
| uk_UA            | 3         | 4.35%   |
| de_DE            | 3         | 4.35%   |
| zh_CN            | 2         | 2.9%    |
| en_GB            | 2         | 2.9%    |
| sv_SE            | 1         | 1.45%   |
| ru_RU            | 1         | 1.45%   |
| pt_PT            | 1         | 1.45%   |
| pl_PL            | 1         | 1.45%   |
| it_IT.ISO8859-15 | 1         | 1.45%   |
| fr_FR            | 1         | 1.45%   |
| de_CH            | 1         | 1.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 59        | 88.06%  |
| BIOS | 8         | 11.94%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 52        | 77.61%  |
| Ufs  | 15        | 22.39%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 60        | 89.55%  |
| MBR  | 7         | 10.45%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 18        | 26.87%  |
| Unknown                        | 9         | 13.43%  |
| Hewlett-Packard                | 8         | 11.94%  |
| ASUSTek Computer               | 7         | 10.45%  |
| Gigabyte Technology            | 5         | 7.46%   |
| Dell                           | 5         | 7.46%   |
| Raspberry Pi Foundation        | 3         | 4.48%   |
| Beckhoff Automation            | 2         | 2.99%   |
| pine64                         | 1         | 1.49%   |
| MSI                            | 1         | 1.49%   |
| Matsushita Electric Industrial | 1         | 1.49%   |
| khadas                         | 1         | 1.49%   |
| Intel                          | 1         | 1.49%   |
| HUAWEI                         | 1         | 1.49%   |
| friendlyelec                   | 1         | 1.49%   |
| Framework                      | 1         | 1.49%   |
| Avell High Performance         | 1         | 1.49%   |
| A-DATA Technology              | 1         | 1.49%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 10        | 14.93%  |
| HP EliteBook 8570p                          | 3         | 4.48%   |
| RPi Raspberry Pi                            | 2         | 2.99%   |
| RPi rpi                                     | 1         | 1.49%   |
| pine64 pinebook-pro-rk3399                  | 1         | 1.49%   |
| MSI MS-7B86                                 | 1         | 1.49%   |
| Matsushita Electric Industrial CF-T2BW1AXR  | 1         | 1.49%   |
| Lenovo XiaoXinPro-13ARE 2020 82DM           | 1         | 1.49%   |
| Lenovo ThinkPad X395 20NL001SMX             | 1         | 1.49%   |
| Lenovo ThinkPad X395 20NL000GPG             | 1         | 1.49%   |
| Lenovo ThinkPad X270 20HM004JBR             | 1         | 1.49%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TLA055CD | 1         | 1.49%   |
| Lenovo ThinkPad X1 Extreme 20MF000BUS       | 1         | 1.49%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS1QC00    | 1         | 1.49%   |
| Lenovo ThinkPad T495s 20QKS1812F            | 1         | 1.49%   |
| Lenovo ThinkPad T470p 20J7S0PM00            | 1         | 1.49%   |
| Lenovo ThinkPad T430 2349H2G                | 1         | 1.49%   |
| Lenovo ThinkPad P15 Gen 1 20ST005VRT        | 1         | 1.49%   |
| Lenovo ThinkPad P14s Gen 1 20Y1CTO1WW       | 1         | 1.49%   |
| Lenovo ThinkPad E14 20RBCTO1WW              | 1         | 1.49%   |
| Lenovo ThinkBook 14 G3 ACL 21A2             | 1         | 1.49%   |
| Lenovo Legion 5P 15IMH05H 82AW              | 1         | 1.49%   |
| Lenovo Legion 5 15IMH05 82AU                | 1         | 1.49%   |
| Lenovo IdeaPad 330-15ARR 81D2               | 1         | 1.49%   |
| khadas edge-v                               | 1         | 1.49%   |
| Intel S2600WTTR                             | 1         | 1.49%   |
| HUAWEI HN-WX9X                              | 1         | 1.49%   |
| HP ZBook 17 G2                              | 1         | 1.49%   |
| HP ProBook 455 G7                           | 1         | 1.49%   |
| HP ProBook 440 G7                           | 1         | 1.49%   |
| HP ProBook 440 G6                           | 1         | 1.49%   |
| HP EliteBook Folio 9470m                    | 1         | 1.49%   |
| Gigabyte X570 AORUS MASTER                  | 1         | 1.49%   |
| Gigabyte X570 AORUS ELITE                   | 1         | 1.49%   |
| Gigabyte X399 DESIGNARE EX                  | 1         | 1.49%   |
| Gigabyte B550I AORUS PRO AX                 | 1         | 1.49%   |
| Gigabyte 970A-UD3P                          | 1         | 1.49%   |
| friendlyelec nanopi-m4                      | 1         | 1.49%   |
| Framework Laptop                            | 1         | 1.49%   |
| Dell Vostro 5490                            | 1         | 1.49%   |
| Dell OptiPlex 5080                          | 1         | 1.49%   |
| Dell Latitude E5430 vPro                    | 1         | 1.49%   |
| Dell Inspiron 3793                          | 1         | 1.49%   |
| Dell G5 5505                                | 1         | 1.49%   |
| Beckhoff Automation CX2033-0185             | 1         | 1.49%   |
| Beckhoff Automation CBxx63                  | 1         | 1.49%   |
| Avell High Performance A62 LIV              | 1         | 1.49%   |
| ASUS VivoBook_ASUSLaptop X512DA_F512DA      | 1         | 1.49%   |
| ASUS PRIME Z590-A                           | 1         | 1.49%   |
| ASUS PRIME X570-PRO                         | 1         | 1.49%   |
| ASUS PRIME B450M-GAMING/BR                  | 1         | 1.49%   |
| ASUS PRIME B450M-A                          | 1         | 1.49%   |
| ASUS P8H77-M PRO                            | 1         | 1.49%   |
| ASUS 1215B                                  | 1         | 1.49%   |
| A-DATA XENIA159GENI72060                    | 1         | 1.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo ThinkPad                            | 12        | 17.91%  |
| Unknown                                    | 10        | 14.93%  |
| HP EliteBook                               | 4         | 5.97%   |
| ASUS PRIME                                 | 4         | 5.97%   |
| HP ProBook                                 | 3         | 4.48%   |
| RPi Raspberry                              | 2         | 2.99%   |
| Lenovo Legion                              | 2         | 2.99%   |
| Gigabyte X570                              | 2         | 2.99%   |
| RPi rpi                                    | 1         | 1.49%   |
| pine64 pinebook-pro-rk3399                 | 1         | 1.49%   |
| MSI MS-7B86                                | 1         | 1.49%   |
| Matsushita Electric Industrial CF-T2BW1AXR | 1         | 1.49%   |
| Lenovo XiaoXinPro-13ARE                    | 1         | 1.49%   |
| Lenovo ThinkBook                           | 1         | 1.49%   |
| Lenovo IdeaPad                             | 1         | 1.49%   |
| khadas edge-v                              | 1         | 1.49%   |
| Intel S2600WTTR                            | 1         | 1.49%   |
| HUAWEI HN-WX9X                             | 1         | 1.49%   |
| HP ZBook                                   | 1         | 1.49%   |
| Gigabyte X399                              | 1         | 1.49%   |
| Gigabyte B550I                             | 1         | 1.49%   |
| Gigabyte 970A-UD3P                         | 1         | 1.49%   |
| friendlyelec nanopi-m4                     | 1         | 1.49%   |
| Framework Laptop                           | 1         | 1.49%   |
| Dell Vostro                                | 1         | 1.49%   |
| Dell OptiPlex                              | 1         | 1.49%   |
| Dell Latitude                              | 1         | 1.49%   |
| Dell Inspiron                              | 1         | 1.49%   |
| Dell G5                                    | 1         | 1.49%   |
| Beckhoff Automation CX2033-0185            | 1         | 1.49%   |
| Beckhoff Automation CBxx63                 | 1         | 1.49%   |
| Avell High Performance A62                 | 1         | 1.49%   |
| ASUS VivoBook                              | 1         | 1.49%   |
| ASUS P8H77-M                               | 1         | 1.49%   |
| ASUS 1215B                                 | 1         | 1.49%   |
| A-DATA XENIA159GENI72060                   | 1         | 1.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 22        | 32.84%  |
| 2021    | 15        | 22.39%  |
| Unknown | 9         | 13.43%  |
| 2019    | 6         | 8.96%   |
| 2018    | 6         | 8.96%   |
| 2017    | 3         | 4.48%   |
| 2016    | 1         | 1.49%   |
| 2015    | 1         | 1.49%   |
| 2014    | 1         | 1.49%   |
| 2013    | 1         | 1.49%   |
| 2011    | 1         | 1.49%   |
| 2003    | 1         | 1.49%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 37        | 55.22%  |
| Desktop        | 23        | 34.33%  |
| System on chip | 6         | 8.96%   |
| Server         | 1         | 1.49%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 67        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 26        | 38.24%  |
| 8.01-16.0       | 11        | 16.18%  |
| 32.01-64.0      | 9         | 13.24%  |
| 64.01-256.0     | 8         | 11.76%  |
| 4.01-8.0        | 7         | 10.29%  |
| 0.51-1.0        | 2         | 2.94%   |
| More than 256.0 | 1         | 1.47%   |
| 3.01-4.0        | 1         | 1.47%   |
| 24.01-32.0      | 1         | 1.47%   |
| 2.01-3.0        | 1         | 1.47%   |
| 1.01-2.0        | 1         | 1.47%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.51-1.0   | 24        | 35.82%  |
| 1.01-2.0   | 15        | 22.39%  |
| 0.01-0.5   | 13        | 19.4%   |
| 2.01-3.0   | 6         | 8.96%   |
| 3.01-4.0   | 3         | 4.48%   |
| 4.01-8.0   | 1         | 1.49%   |
| 32.01-64.0 | 1         | 1.49%   |
| 24.01-32.0 | 1         | 1.49%   |
| 16.01-24.0 | 1         | 1.49%   |
| 8.01-16.0  | 1         | 1.49%   |
| 0          | 1         | 1.49%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 30        | 42.86%  |
| 2      | 19        | 27.14%  |
| 0      | 11        | 15.71%  |
| 3      | 5         | 7.14%   |
| 6      | 3         | 4.29%   |
| 5      | 1         | 1.43%   |
| 4      | 1         | 1.43%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 56        | 82.35%  |
| Yes       | 12        | 17.65%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 51        | 76.12%  |
| No        | 16        | 23.88%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 46        | 68.66%  |
| No        | 21        | 31.34%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 35        | 51.47%  |
| Yes       | 33        | 48.53%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| UK           | 9         | 13.43%  |
| USA          | 7         | 10.45%  |
| Russia       | 7         | 10.45%  |
| Germany      | 7         | 10.45%  |
| Brazil       | 5         | 7.46%   |
| Ukraine      | 4         | 5.97%   |
| China        | 4         | 5.97%   |
| Japan        | 3         | 4.48%   |
| Austria      | 3         | 4.48%   |
| Switzerland  | 2         | 2.99%   |
| Sweden       | 2         | 2.99%   |
| Portugal     | 2         | 2.99%   |
| Poland       | 2         | 2.99%   |
| Spain        | 1         | 1.49%   |
| Saudi Arabia | 1         | 1.49%   |
| Peru         | 1         | 1.49%   |
| Jamaica      | 1         | 1.49%   |
| Italy        | 1         | 1.49%   |
| India        | 1         | 1.49%   |
| France       | 1         | 1.49%   |
| Croatia      | 1         | 1.49%   |
| Belarus      | 1         | 1.49%   |
| Bangladesh   | 1         | 1.49%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Moscow                  | 5         | 6.58%   |
| Brighton                | 5         | 6.58%   |
| Ōta-ku                 | 3         | 3.95%   |
| London                  | 3         | 3.95%   |
| Kyiv                    | 3         | 3.95%   |
| Zurich                  | 2         | 2.63%   |
| Vienna                  | 2         | 2.63%   |
| Seattle                 | 2         | 2.63%   |
| Rietberg                | 2         | 2.63%   |
| Fuchu                   | 2         | 2.63%   |
| Berlin                  | 2         | 2.63%   |
| Zaporizhzhya            | 1         | 1.32%   |
| Wuhan                   | 1         | 1.32%   |
| Worthing                | 1         | 1.32%   |
| Woodburn                | 1         | 1.32%   |
| Wieliczka               | 1         | 1.32%   |
| Vancouver               | 1         | 1.32%   |
| Trosa                   | 1         | 1.32%   |
| Thrissur                | 1         | 1.32%   |
| Stuttgart               | 1         | 1.32%   |
| St Petersburg           | 1         | 1.32%   |
| Sollentuna              | 1         | 1.32%   |
| Slavonski Brod          | 1         | 1.32%   |
| Santa Monica            | 1         | 1.32%   |
| San Francisco           | 1         | 1.32%   |
| Ruthin                  | 1         | 1.32%   |
| Riyadh                  | 1         | 1.32%   |
| Rio de Janeiro          | 1         | 1.32%   |
| Resana                  | 1         | 1.32%   |
| Poulsbo                 | 1         | 1.32%   |
| Pobiedziska             | 1         | 1.32%   |
| Northeim                | 1         | 1.32%   |
| Minsk                   | 1         | 1.32%   |
| Milan                   | 1         | 1.32%   |
| Maia                    | 1         | 1.32%   |
| Madrid                  | 1         | 1.32%   |
| Lima                    | 1         | 1.32%   |
| Lake Forest             | 1         | 1.32%   |
| Kunitachi               | 1         | 1.32%   |
| Kingston                | 1         | 1.32%   |
| Khabarovsk              | 1         | 1.32%   |
| João Pessoa            | 1         | 1.32%   |
| Jaboatao dos Guararapes | 1         | 1.32%   |
| Ilhavo                  | 1         | 1.32%   |
| Hangzhou                | 1         | 1.32%   |
| Guangzhou Shi           | 1         | 1.32%   |
| Graz                    | 1         | 1.32%   |
| Farnham                 | 1         | 1.32%   |
| Eilenburg               | 1         | 1.32%   |
| Dhaka                   | 1         | 1.32%   |
| Claix                   | 1         | 1.32%   |
| Cambridge               | 1         | 1.32%   |
| Brasília               | 1         | 1.32%   |
| Beijing                 | 1         | 1.32%   |
| Beckton                 | 1         | 1.32%   |
| Araruama                | 1         | 1.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 17        | 25     | 20.73%  |
| WDC                 | 16        | 25     | 19.51%  |
| Toshiba             | 9         | 15     | 10.98%  |
| Seagate             | 6         | 10     | 7.32%   |
| HGST                | 6         | 17     | 7.32%   |
| Kingston            | 5         | 8      | 6.1%    |
| Crucial             | 5         | 12     | 6.1%    |
| SK Hynix            | 4         | 4      | 4.88%   |
| A-DATA Technology   | 3         | 3      | 3.66%   |
| Micron Technology   | 2         | 3      | 2.44%   |
| Intel               | 2         | 3      | 2.44%   |
| Solid State Storage | 1         | 1      | 1.22%   |
| Silicon Motion      | 1         | 1      | 1.22%   |
| SanDisk             | 1         | 1      | 1.22%   |
| LITEON              | 1         | 1      | 1.22%   |
| GOODRAM             | 1         | 1      | 1.22%   |
| Fujitsu             | 1         | 2      | 1.22%   |
| Apacer              | 1         | 1      | 1.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB                           | 5         | 5.38%   |
| HGST HTS725050A7E630 500GB                         | 4         | 4.3%    |
| Samsung HM251JX 250GB                              | 3         | 3.23%   |
| HGST HTS721010A9E630 1TB                           | 3         | 3.23%   |
| WDC WDS100T3X0C-00SJG0 1TB                         | 2         | 2.15%   |
| WDC PC SN730 NVMe 1024GB                           | 2         | 2.15%   |
| Toshiba MQ04ABF100 1TB                             | 2         | 2.15%   |
| Samsung SSD 850 EVO 250GB                          | 2         | 2.15%   |
| Samsung MZVLB512HBJQ-000L7 512GB                   | 2         | 2.15%   |
| WDC WDS250G2B0C-00PXH0 250GB                       | 1         | 1.08%   |
| WDC WDS100T2B0A-00SM50 1TB                         | 1         | 1.08%   |
| WDC WD5002ABYS-18B1B0 500GB                        | 1         | 1.08%   |
| WDC WD40EZRZ-75GXCB0 4TB                           | 1         | 1.08%   |
| WDC WD30EFRX-68EUZN0 3TB                           | 1         | 1.08%   |
| WDC WD120EFAX-68UNTN0 12TB                         | 1         | 1.08%   |
| WDC WD10SPZX-60Z10T0 1TB                           | 1         | 1.08%   |
| WDC WD10SPZX-21Z10T0 1TB                           | 1         | 1.08%   |
| WDC WD10JMVW-11AJGS3 1TB                           | 1         | 1.08%   |
| WDC WD10EZEX-00RKKA0 1TB                           | 1         | 1.08%   |
| WDC WD10EARX-00N0YB0 1TB                           | 1         | 1.08%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB               | 1         | 1.08%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB               | 1         | 1.08%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB               | 1         | 1.08%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB               | 1         | 1.08%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB               | 1         | 1.08%   |
| Toshiba MQ01ABD100 1TB                             | 1         | 1.08%   |
| Toshiba KXG6APNV2T04 2TB                           | 1         | 1.08%   |
| Solid State Storage CL1-3D128-Q11 NVMe SSSTC 128GB | 1         | 1.08%   |
| SK Hynix PC300 HFS512GD9MND-5510A 512GB            | 1         | 1.08%   |
| SK Hynix HFS128G39TND-N210A 128GB                  | 1         | 1.08%   |
| SK Hynix BC511 NVMe 256GB                          | 1         | 1.08%   |
| SK Hynix BC511 HFM256GDJTNI-82A0A 256GB            | 1         | 1.08%   |
| Silicon Motion NE-256 256GB                        | 1         | 1.08%   |
| Seagate ST5000LM000-2AN170 5TB                     | 1         | 1.08%   |
| Seagate ST4000DM000-1F2168 4TB                     | 1         | 1.08%   |
| Seagate ST3750640AS 752GB                          | 1         | 1.08%   |
| Seagate ST32000641AS 2TB                           | 1         | 1.08%   |
| Seagate ST3000DM007-1WY10G 3TB                     | 1         | 1.08%   |
| Seagate ST3000DM001-1ER166 3TB                     | 1         | 1.08%   |
| Seagate ST1000LM035-1RK172 1TB                     | 1         | 1.08%   |
| SanDisk SDSSDH3500G 500GB                          | 1         | 1.08%   |
| Samsung SSD 970 EVO 1TB                            | 1         | 1.08%   |
| Samsung SSD 870 QVO 1TB                            | 1         | 1.08%   |
| Samsung SSD 860 EVO 500GB                          | 1         | 1.08%   |
| Samsung SSD 860 EVO 4TB                            | 1         | 1.08%   |
| Samsung SSD 860 EVO 250GB                          | 1         | 1.08%   |
| Samsung SSD 850 EVO 500GB                          | 1         | 1.08%   |
| Samsung SSD 840 PRO Series 128GB                   | 1         | 1.08%   |
| Samsung MZVLW256HEHP-000L7 256GB                   | 1         | 1.08%   |
| Samsung MZVLB512HBJQ-000L2 512GB                   | 1         | 1.08%   |
| Samsung MZVLB256HBHQ-000L7 256GB                   | 1         | 1.08%   |
| Samsung MZVLB256HAHQ-00000 256GB                   | 1         | 1.08%   |
| Samsung MZVLB1T0HBLR-000L2 1TB                     | 1         | 1.08%   |
| Samsung MZMTD128HAFV-000L1 128GB                   | 1         | 1.08%   |
| Samsung HM250HI 250GB                              | 1         | 1.08%   |
| Micron 5200_MTFDDAK480TDC 480GB                    | 1         | 1.08%   |
| Micron 2300_MTFDHBA512TDV 512GB                    | 1         | 1.08%   |
| LITEON LCH-256V2S 256GB                            | 1         | 1.08%   |
| Kingston SUV500MS480G 480GB                        | 1         | 1.08%   |
| Kingston SUV500MS120G 120GB                        | 1         | 1.08%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 8         | 14     | 25.81%  |
| WDC                 | 6         | 9      | 19.35%  |
| Seagate             | 6         | 10     | 19.35%  |
| HGST                | 6         | 17     | 19.35%  |
| Samsung Electronics | 4         | 7      | 12.9%   |
| Fujitsu             | 1         | 2      | 3.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 9      | 30%     |
| Crucial             | 3         | 8      | 15%     |
| Kingston            | 2         | 4      | 10%     |
| WDC                 | 1         | 2      | 5%      |
| SK Hynix            | 1         | 1      | 5%      |
| SanDisk             | 1         | 1      | 5%      |
| Micron Technology   | 1         | 1      | 5%      |
| LITEON              | 1         | 1      | 5%      |
| Intel               | 1         | 2      | 5%      |
| GOODRAM             | 1         | 1      | 5%      |
| Apacer              | 1         | 1      | 5%      |
| A-DATA Technology   | 1         | 1      | 5%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 30        | 42     | 41.67%  |
| HDD  | 22        | 59     | 30.56%  |
| SSD  | 20        | 32     | 27.78%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 34        | 91     | 53.13%  |
| NVMe | 30        | 42     | 46.88%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 25        | 57     | 55.56%  |
| 0.51-1.0   | 13        | 22     | 28.89%  |
| 3.01-4.0   | 2         | 3      | 4.44%   |
| 2.01-3.0   | 2         | 3      | 4.44%   |
| 10.01-20.0 | 1         | 1      | 2.22%   |
| 1.01-2.0   | 1         | 1      | 2.22%   |
| 4.01-10.0  | 1         | 4      | 2.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 17        | 24.64%  |
| 101-250        | 15        | 21.74%  |
| 501-1000       | 12        | 17.39%  |
| 1-20           | 9         | 13.04%  |
| 21-50          | 6         | 8.7%    |
| 51-100         | 5         | 7.25%   |
| 2001-3000      | 2         | 2.9%    |
| 1001-2000      | 2         | 2.9%    |
| More than 3000 | 1         | 1.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 43        | 62.32%  |
| 21-50     | 19        | 27.54%  |
| 101-250   | 4         | 5.8%    |
| 251-500   | 1         | 1.45%   |
| 1001-2000 | 1         | 1.45%   |
| 501-1000  | 1         | 1.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| HGST HTS725050A7E630 500GB        | 4         | 9      | 44.44%  |
| WDC WD5002ABYS-18B1B0 500GB       | 1         | 1      | 11.11%  |
| WDC WD10SPZX-60Z10T0 1TB          | 1         | 1      | 11.11%  |
| Samsung Electronics HM251JX 250GB | 1         | 1      | 11.11%  |
| HGST HTS721010A9E630 1TB          | 1         | 4      | 11.11%  |
| Fujitsu MHS2040AT D 40GB          | 1         | 2      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 4         | 13     | 50%     |
| WDC                 | 2         | 2      | 25%     |
| Samsung Electronics | 1         | 1      | 12.5%   |
| Fujitsu             | 1         | 2      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 4         | 13     | 50%     |
| WDC                 | 2         | 2      | 25%     |
| Samsung Electronics | 1         | 1      | 12.5%   |
| Fujitsu             | 1         | 2      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 7         | 18     | 100%    |

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
| Works    | 55        | 113    | 85.94%  |
| Malfunc  | 7         | 18     | 10.94%  |
| Detected | 2         | 2      | 3.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 27        | 32.93%  |
| AMD                            | 16        | 19.51%  |
| Sandisk                        | 11        | 13.41%  |
| Samsung Electronics            | 10        | 12.2%   |
| SK Hynix                       | 3         | 3.66%   |
| Silicon Motion                 | 3         | 3.66%   |
| Kingston Technology Company    | 3         | 3.66%   |
| Micron Technology              | 2         | 2.44%   |
| ADATA Technology               | 2         | 2.44%   |
| VMware                         | 1         | 1.22%   |
| Toshiba                        | 1         | 1.22%   |
| Solid State Storage Technology | 1         | 1.22%   |
| Micron/Crucial Technology      | 1         | 1.22%   |
| Marvell Technology Group       | 1         | 1.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 13        | 14.61%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 8         | 8.99%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 7         | 7.87%   |
| Unknown                                                                        | 6         | 6.74%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 5         | 5.62%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 4.49%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 3         | 3.37%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3         | 3.37%   |
| AMD 400 Series Chipset SATA Controller                                         | 3         | 3.37%   |
| SK Hynix BC511                                                                 | 2         | 2.25%   |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 2         | 2.25%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 2.25%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 2.25%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 2.25%   |
| VMware SATA AHCI controller                                                    | 1         | 1.12%   |
| Toshiba XG6 NVMe SSD Controller                                                | 1         | 1.12%   |
| SK Hynix PC300 NVMe Solid State Drive 512GB                                    | 1         | 1.12%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1         | 1.12%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 1         | 1.12%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                          | 1         | 1.12%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 1         | 1.12%   |
| Kingston Company A2000 NVMe SSD                                                | 1         | 1.12%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 1         | 1.12%   |
| Intel SSD 660P Series                                                          | 1         | 1.12%   |
| Intel NVMe Optane Memory Series                                                | 1         | 1.12%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 1.12%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 1.12%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.12%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 1         | 1.12%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 1         | 1.12%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 1.12%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 1         | 1.12%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 1         | 1.12%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]    | 1         | 1.12%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]    | 1         | 1.12%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 1         | 1.12%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 1         | 1.12%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1         | 1.12%   |
| AMD X399 Series Chipset SATA Controller                                        | 1         | 1.12%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                       | 1         | 1.12%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 1         | 1.12%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 38        | 47.5%   |
| SATA | 38        | 47.5%   |
| IDE  | 3         | 3.75%   |
| RAID | 1         | 1.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 31        | 45.59%  |
| AMD     | 22        | 32.35%  |
| Unknown | 9         | 13.24%  |
| ARM     | 6         | 8.82%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
|                                                 | 9         | 13.24%  |
| Intel Core i7-3520M CPU @ 2.90GHz               | 4         | 5.88%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 3         | 4.41%   |
| Intel Core i5-10210U CPU @ 1.60GHz              | 3         | 4.41%   |
| ARM Cortex-A72 r0p3                             | 3         | 4.41%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 2         | 2.94%   |
| Intel Core i7-7600U CPU @ 2.80GHz               | 2         | 2.94%   |
| ARM Cortex-A72 r0p2                             | 2         | 2.94%   |
| AMD Ryzen 5 PRO 3500U w/ Radeon Vega Mobile Gfx | 2         | 2.94%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 2         | 2.94%   |
| Intel Xeon W-10885M CPU @ 2.40GHz               | 1         | 1.47%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz             | 1         | 1.47%   |
| Intel Pentium M processor 1000MHz               | 1         | 1.47%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 1         | 1.47%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 1.47%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 1.47%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz              | 1         | 1.47%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz              | 1         | 1.47%   |
| Intel Core i7-3770 CPU @ 3.40GHz                | 1         | 1.47%   |
| Intel Core i7-3687U CPU @ 2.10GHz               | 1         | 1.47%   |
| Intel Core i7-10700 CPU @ 2.90GHz               | 1         | 1.47%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz              | 1         | 1.47%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 1         | 1.47%   |
| Intel Core i5-10500T CPU @ 2.30GHz              | 1         | 1.47%   |
| Intel Core i5-10300H CPU @ 2.50GHz              | 1         | 1.47%   |
| Intel Atom CPU E3827 @ 1.74GHz                  | 1         | 1.47%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 1         | 1.47%   |
| ARM Cortex-A53 r0p4                             | 1         | 1.47%   |
| AMD Ryzen Threadripper 1950X 16-Core Processor  | 1         | 1.47%   |
| AMD Ryzen Embedded V1202B with Radeon Vega Gfx  | 1         | 1.47%   |
| AMD Ryzen 9 5900X 12-Core Processor             | 1         | 1.47%   |
| AMD Ryzen 9 3950X 16-Core Processor             | 1         | 1.47%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 1         | 1.47%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics      | 1         | 1.47%   |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx | 1         | 1.47%   |
| AMD Ryzen 7 5800X 8-Core Processor              | 1         | 1.47%   |
| AMD Ryzen 7 5700U with Radeon Graphics          | 1         | 1.47%   |
| AMD Ryzen 7 4800U with Radeon Graphics          | 1         | 1.47%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 1         | 1.47%   |
| AMD Ryzen 7 4700U with Radeon Graphics          | 1         | 1.47%   |
| AMD Ryzen 7 2700X Eight-Core Processor          | 1         | 1.47%   |
| AMD Ryzen 5 2600X Six-Core Processor            | 1         | 1.47%   |
| AMD Ryzen 5 2600 Six-Core Processor             | 1         | 1.47%   |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx   | 1         | 1.47%   |
| AMD FX-8320E Eight-Core Processor               | 1         | 1.47%   |
| AMD E-450 APU with Radeon HD Graphics           | 1         | 1.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 20        | 29.41%  |
| Other                  | 10        | 14.71%  |
| Intel Core i5          | 6         | 8.82%   |
| ARM Cortex             | 6         | 8.82%   |
| AMD Ryzen 7            | 6         | 8.82%   |
| AMD Ryzen 5            | 4         | 5.88%   |
| AMD Ryzen 9            | 3         | 4.41%   |
| Intel Xeon             | 2         | 2.94%   |
| AMD Ryzen 7 PRO        | 2         | 2.94%   |
| AMD Ryzen 5 PRO        | 2         | 2.94%   |
| Intel Pentium M        | 1         | 1.47%   |
| Intel Atom             | 1         | 1.47%   |
| AMD Ryzen Threadripper | 1         | 1.47%   |
| AMD Ryzen Embedded     | 1         | 1.47%   |
| AMD Ryzen 3            | 1         | 1.47%   |
| AMD FX                 | 1         | 1.47%   |
| AMD E                  | 1         | 1.47%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 14        | 20.9%   |
| 4       | 12        | 17.91%  |
| 2       | 11        | 16.42%  |
| 8       | 9         | 13.43%  |
| 16      | 7         | 10.45%  |
| 6       | 7         | 10.45%  |
| 32      | 2         | 2.99%   |
| 24      | 2         | 2.99%   |
| 12      | 2         | 2.99%   |
| 1       | 1         | 1.49%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 57        | 83.82%  |
| Unknown | 10        | 14.71%  |
| 2       | 1         | 1.47%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 29        | 43.28%  |
| 1       | 23        | 34.33%  |
| Unknown | 15        | 22.39%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 15        | 22.39%  |
| KabyLake   | 10        | 14.93%  |
| Zen+       | 8         | 11.94%  |
| IvyBridge  | 7         | 10.45%  |
| CometLake  | 7         | 10.45%  |
| Zen 2      | 6         | 8.96%   |
| Zen        | 3         | 4.48%   |
| Zen 3      | 2         | 2.99%   |
| Haswell    | 2         | 2.99%   |
| TigerLake  | 1         | 1.49%   |
| Silvermont | 1         | 1.49%   |
| Piledriver | 1         | 1.49%   |
| P6         | 1         | 1.49%   |
| IceLake    | 1         | 1.49%   |
| Broadwell  | 1         | 1.49%   |
| Bobcat     | 1         | 1.49%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 24        | 35.82%  |
| Nvidia                     | 21        | 31.34%  |
| AMD                        | 19        | 28.36%  |
| VMware                     | 1         | 1.49%   |
| Matrox Electronics Systems | 1         | 1.49%   |
| ASPEED Technology          | 1         | 1.49%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series] | 5         | 7.35%   |
| AMD Renoir                                                           | 4         | 5.88%   |
| Intel CometLake-U GT2 [UHD Graphics]                                 | 3         | 4.41%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                            | 3         | 4.41%   |
| Intel 3rd Gen Core processor Graphics Controller                     | 3         | 4.41%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                             | 3         | 4.41%   |
| Nvidia TU117M                                                        | 2         | 2.94%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                           | 2         | 2.94%   |
| Nvidia GP108M [GeForce MX230]                                        | 2         | 2.94%   |
| Nvidia GK208B [GeForce GT 710]                                       | 2         | 2.94%   |
| Intel HD Graphics 620                                                | 2         | 2.94%   |
| Intel CometLake-H GT2 [UHD Graphics]                                 | 2         | 2.94%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller          | 2         | 2.94%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]     | 2         | 2.94%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                           | 1         | 1.47%   |
| Nvidia TU104GLM [Quadro RTX 5000 Mobile / Max-Q]                     | 1         | 1.47%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                           | 1         | 1.47%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                              | 1         | 1.47%   |
| Nvidia GP107GL [Quadro P620]                                         | 1         | 1.47%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                   | 1         | 1.47%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                  | 1         | 1.47%   |
| Nvidia GM206 [GeForce GTX 960]                                       | 1         | 1.47%   |
| Nvidia GM108M [GeForce MX130]                                        | 1         | 1.47%   |
| Nvidia GM108M [GeForce 940MX]                                        | 1         | 1.47%   |
| Nvidia GM107M [GeForce GTX 860M]                                     | 1         | 1.47%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                    | 1         | 1.47%   |
| Nvidia GK107GLM [Quadro K1100M]                                      | 1         | 1.47%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)    | 1         | 1.47%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                           | 1         | 1.47%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                            | 1         | 1.47%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                               | 1         | 1.47%   |
| Intel Iris Plus Graphics G7                                          | 1         | 1.47%   |
| Intel HD Graphics 630                                                | 1         | 1.47%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                             | 1         | 1.47%   |
| Intel Comet Lake-H WS GT2 Integrated UHD Graphics Controller         | 1         | 1.47%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display         | 1         | 1.47%   |
| Intel 82852/855GM Integrated Graphics Device                         | 1         | 1.47%   |
| ASPEED Technology ASPEED Graphics Family                             | 1         | 1.47%   |
| AMD Wrestler [Radeon HD 6320]                                        | 1         | 1.47%   |
| AMD RV630 XT [Radeon HD 2600 XT]                                     | 1         | 1.47%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]              | 1         | 1.47%   |
| AMD Lucienne                                                         | 1         | 1.47%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]              | 1         | 1.47%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]  | 1         | 1.47%   |
| Unknown                                                              | 1         | 1.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 18        | 26.47%  |
| Other          | 12        | 17.65%  |
| Intel + Nvidia | 12        | 17.65%  |
| 1 x Intel      | 12        | 17.65%  |
| 1 x Nvidia     | 10        | 14.71%  |
| 2 x AMD        | 1         | 1.47%   |
| 1 x VMware     | 1         | 1.47%   |
| 1 x Matrox     | 1         | 1.47%   |
| 1 x ASPEED     | 1         | 1.47%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 40        | 59.7%   |
| Proprietary | 15        | 22.39%  |
| Unknown     | 12        | 17.91%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 49        | 71.01%  |
| 1.01-2.0   | 6         | 8.7%    |
| 0.51-1.0   | 5         | 7.25%   |
| 3.01-4.0   | 4         | 5.8%    |
| 0.01-0.5   | 3         | 4.35%   |
| 7.01-8.0   | 1         | 1.45%   |
| 2.01-3.0   | 1         | 1.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| LG Display          | 9         | 16.98%  |
| BOE                 | 5         | 9.43%   |
| Philips             | 4         | 7.55%   |
| Chimei Innolux      | 4         | 7.55%   |
| AU Optronics        | 4         | 7.55%   |
| Hewlett-Packard     | 3         | 5.66%   |
| Goldstar            | 3         | 5.66%   |
| Samsung Electronics | 2         | 3.77%   |
| RTK                 | 2         | 3.77%   |
| LG Electronics      | 2         | 3.77%   |
| Dell                | 2         | 3.77%   |
| Sony                | 1         | 1.89%   |
| SDC                 | 1         | 1.89%   |
| PANDA               | 1         | 1.89%   |
| LGD                 | 1         | 1.89%   |
| Lenovo              | 1         | 1.89%   |
| InfoVision          | 1         | 1.89%   |
| Iiyama              | 1         | 1.89%   |
| HJW                 | 1         | 1.89%   |
| Eizo                | 1         | 1.89%   |
| CSO                 | 1         | 1.89%   |
| BenQ                | 1         | 1.89%   |
| Apple               | 1         | 1.89%   |
| AOC                 | 1         | 1.89%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0258 1600x900 350x190mm 15.7-inch          | 3         | 5.45%   |
| RTK WCS Display RTK1A1B 1920x1080 344x195mm 15.6-inch                | 2         | 3.64%   |
| Philips LCD Monitor PHL08C3 1920x1080 600x340mm 27.2-inch            | 2         | 3.64%   |
| Sony TV SNY4B03 1920x1080 930x520mm 41.9-inch                        | 1         | 1.82%   |
| SDC LCD Monitor 3520x1080                                            | 1         | 1.82%   |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                     | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SDC3754 1600x900 380x210mm 17.1-inch | 1         | 1.82%   |
| Philips PHL 273V7 PHLC156 1920x1080 600x340mm 27.2-inch              | 1         | 1.82%   |
| Philips LCD Monitor 271P4 3520x1080                                  | 1         | 1.82%   |
| Philips LCD Monitor 271P4                                            | 1         | 1.82%   |
| PANDA LCD Monitor NCP004F 1920x1080 310x170mm 13.9-inch              | 1         | 1.82%   |
| LGD LCD Monitor 1920x1080                                            | 1         | 1.82%   |
| LG Electronics LCD Monitor LX20D 1600x1200                           | 1         | 1.82%   |
| LG Electronics LCD Monitor LG Ultra HD 11520x2160                    | 1         | 1.82%   |
| LG Electronics LCD Monitor LG Ultra HD                               | 1         | 1.82%   |
| LG Display LCD Monitor LGD062E 1920x1080 340x190mm 15.3-inch         | 1         | 1.82%   |
| LG Display LCD Monitor LGD060A 1920x1080 290x170mm 13.2-inch         | 1         | 1.82%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch         | 1         | 1.82%   |
| LG Display LCD Monitor LGD05F1 1920x1080 310x170mm 13.9-inch         | 1         | 1.82%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch         | 1         | 1.82%   |
| LG Display LCD Monitor LGD033E 1366x768 310x170mm 13.9-inch          | 1         | 1.82%   |
| Lenovo LEN P44w-10 LEN61D5 3840x1200 1050x330mm 43.3-inch            | 1         | 1.82%   |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch         | 1         | 1.82%   |
| Iiyama PL2474H IVM6146 1920x1080 520x290mm 23.4-inch                 | 1         | 1.82%   |
| HJW HDMI TO USB HJW0001 1920x1080 700x390mm 31.5-inch                | 1         | 1.82%   |
| Hewlett-Packard LCD Monitor LA2306 3520x1080                         | 1         | 1.82%   |
| Hewlett-Packard LA2306 HWP2949 1920x1080 510x290mm 23.1-inch         | 1         | 1.82%   |
| Hewlett-Packard E242 HWP326E 1920x1200 520x320mm 24.0-inch           | 1         | 1.82%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch           | 1         | 1.82%   |
| Goldstar 27GK750F GSM770F 1920x1080 600x340mm 27.2-inch              | 1         | 1.82%   |
| Goldstar 23EA53 GSM59A8 1920x1080 510x290mm 23.1-inch                | 1         | 1.82%   |
| Eizo FX2431 ENC2036 1920x1200 520x330mm 24.2-inch                    | 1         | 1.82%   |
| Dell U2718Q DELA0EC 3840x2160 610x350mm 27.7-inch                    | 1         | 1.82%   |
| Dell U2518D DEL413C 2560x1440 550x310mm 24.9-inch                    | 1         | 1.82%   |
| CSO LCD Monitor CSO1500 3840x2160 340x190mm 15.3-inch                | 1         | 1.82%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 280x180mm 13.1-inch     | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 340x190mm 15.3-inch     | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN1484 1600x900 310x170mm 13.9-inch      | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN13A2 1920x1080 290x170mm 13.2-inch     | 1         | 1.82%   |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                | 1         | 1.82%   |
| BOE LCD Monitor BOE084D 1920x1080 340x190mm 15.3-inch                | 1         | 1.82%   |
| BOE LCD Monitor BOE07F1 1920x1080 340x190mm 15.3-inch                | 1         | 1.82%   |
| BOE LCD Monitor BOE0792 1920x1080 340x190mm 15.3-inch                | 1         | 1.82%   |
| BOE LCD Monitor BOE0747 1920x1080 340x190mm 15.3-inch                | 1         | 1.82%   |
| BenQ GW2280 BNQ78E8 1920x1080 480x270mm 21.7-inch                    | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch       | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch        | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO2026 2560x1600 290x180mm 13.4-inch       | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO139D 1920x1080 380x210mm 17.1-inch       | 1         | 1.82%   |
| Apple Cinema HD APP9223 1920x1200 490x310mm 22.8-inch                | 1         | 1.82%   |
| AOC Q3277 AOC3277 2560x1440 710x400mm 32.1-inch                      | 1         | 1.82%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 28        | 53.85%  |
| 1600x900 (HD+)    | 6         | 11.54%  |
| 3840x2160 (4K)    | 4         | 7.69%   |
| 1920x1200 (WUXGA) | 3         | 5.77%   |
| Unknown           | 2         | 3.85%   |
| 3840x1200         | 1         | 1.92%   |
| 3520x1080         | 1         | 1.92%   |
| 2560x1600         | 1         | 1.92%   |
| 2560x1440 (QHD)   | 1         | 1.92%   |
| 2256x1504         | 1         | 1.92%   |
| 2160x1440         | 1         | 1.92%   |
| 1600x1200         | 1         | 1.92%   |
| 1366x768 (WXGA)   | 1         | 1.92%   |
| 11520x2160        | 1         | 1.92%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 13        | 25.49%  |
| 15      | 12        | 23.53%  |
| 27      | 6         | 11.76%  |
| Unknown | 5         | 9.8%    |
| 24      | 3         | 5.88%   |
| 23      | 3         | 5.88%   |
| 17      | 2         | 3.92%   |
| 43      | 1         | 1.96%   |
| 41      | 1         | 1.96%   |
| 32      | 1         | 1.96%   |
| 31      | 1         | 1.96%   |
| 22      | 1         | 1.96%   |
| 21      | 1         | 1.96%   |
| 12      | 1         | 1.96%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 20        | 40%     |
| 501-600     | 10        | 20%     |
| 201-300     | 6         | 12%     |
| Unknown     | 5         | 10%     |
| 601-700     | 2         | 4%      |
| 401-500     | 2         | 4%      |
| 351-400     | 2         | 4%      |
| 701-800     | 1         | 2%      |
| 1001-1500   | 1         | 2%      |
| 901-1000    | 1         | 2%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 34        | 75.56%  |
| 16/10   | 5         | 11.11%  |
| Unknown | 4         | 8.89%   |
| 3/2     | 1         | 2.22%   |
| 3.18    | 1         | 2.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 10        | 19.61%  |
| 91-100         | 7         | 13.73%  |
| 301-350        | 6         | 11.76%  |
| 201-250        | 5         | 9.8%    |
| 101-110        | 5         | 9.8%    |
| Unknown        | 5         | 9.8%    |
| 71-80          | 3         | 5.88%   |
| 251-300        | 3         | 5.88%   |
| 351-500        | 2         | 3.92%   |
| 121-130        | 2         | 3.92%   |
| 501-1000       | 2         | 3.92%   |
| 61-70          | 1         | 1.96%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 17        | 34.69%  |
| 51-100        | 13        | 26.53%  |
| 161-240       | 7         | 14.29%  |
| 101-120       | 6         | 12.24%  |
| Unknown       | 5         | 10.2%   |
| More than 240 | 1         | 2.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 31        | 45.59%  |
| 0     | 27        | 39.71%  |
| 2     | 9         | 13.24%  |
| 3     | 1         | 1.47%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 46        | 45.54%  |
| Realtek Semiconductor | 30        | 29.7%   |
| TP-Link               | 4         | 3.96%   |
| Ralink Technology     | 4         | 3.96%   |
| Hewlett-Packard       | 4         | 3.96%   |
| Qualcomm Atheros      | 2         | 1.98%   |
| D-Link System         | 2         | 1.98%   |
| Broadcom              | 2         | 1.98%   |
| Mellanox Technologies | 1         | 0.99%   |
| Lenovo                | 1         | 0.99%   |
| Emulex                | 1         | 0.99%   |
| Edimax Technology     | 1         | 0.99%   |
| BUFFALO               | 1         | 0.99%   |
| ASUSTek Computer      | 1         | 0.99%   |
| Arduino SA            | 1         | 0.99%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 24        | 19.83%  |
| Intel Wi-Fi 6 AX200                                                        | 7         | 5.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 6         | 4.96%   |
| Intel Wireless-AC 9260                                                     | 5         | 4.13%   |
| Intel Wireless 8265 / 8275                                                 | 5         | 4.13%   |
| Intel Comet Lake PCH CNVi WiFi                                             | 5         | 4.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 5         | 4.13%   |
| Intel I211 Gigabit Network Connection                                      | 4         | 3.31%   |
| HP hs2350 HSPA+ Mobile Broadband Module Network Adapter                    | 4         | 3.31%   |
| Intel I210 Gigabit Network Connection                                      | 3         | 2.48%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                          | 3         | 2.48%   |
| Intel 82574L Gigabit Network Connection                                    | 3         | 2.48%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 2         | 1.65%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 2         | 1.65%   |
| Realtek RTL8125 2.5GbE Controller                                          | 2         | 1.65%   |
| Ralink MT7601U Wireless Adapter                                            | 2         | 1.65%   |
| Intel Wireless 7260                                                        | 2         | 1.65%   |
| Intel Ethernet Connection (4) I219-LM                                      | 2         | 1.65%   |
| Intel Ethernet Connection (11) I219-LM                                     | 2         | 1.65%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 2         | 1.65%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 2         | 1.65%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                     | 1         | 0.83%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]        | 1         | 0.83%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 0.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 0.83%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                     | 1         | 0.83%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 1         | 0.83%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 1         | 0.83%   |
| Ralink RT5370 Wireless Adapter                                             | 1         | 0.83%   |
| Ralink RT2870/RT3070 Wireless Adapter                                      | 1         | 0.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 1         | 0.83%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 1         | 0.83%   |
| Mellanox MT27710 Family [ConnectX-4 Lx]                                    | 1         | 0.83%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                           | 1         | 0.83%   |
| Intel Wi-Fi 6 AX201                                                        | 1         | 0.83%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                  | 1         | 0.83%   |
| Intel Ethernet Controller I225-V                                           | 1         | 0.83%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                              | 1         | 0.83%   |
| Intel Ethernet Connection I217-LM                                          | 1         | 0.83%   |
| Intel Ethernet Connection (7) I219-V                                       | 1         | 0.83%   |
| Intel Ethernet Connection (5) I219-V                                       | 1         | 0.83%   |
| Intel Centrino Advanced-N 6235                                             | 1         | 0.83%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller          | 1         | 0.83%   |
| Emulex OneConnect 10Gb NIC (be3)                                           | 1         | 0.83%   |
| Edimax EW-7711MAC 802.11ac Wireless Adapter                                | 1         | 0.83%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]                   | 1         | 0.83%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                         | 1         | 0.83%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                        | 1         | 0.83%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                                        | 1         | 0.83%   |
| Arduino SA Uno R3 (CDC ACM)                                                | 1         | 0.83%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 37        | 63.79%  |
| Realtek Semiconductor | 5         | 8.62%   |
| TP-Link               | 4         | 6.9%    |
| Ralink Technology     | 4         | 6.9%    |
| D-Link System         | 2         | 3.45%   |
| Broadcom              | 2         | 3.45%   |
| Qualcomm Atheros      | 1         | 1.72%   |
| Edimax Technology     | 1         | 1.72%   |
| BUFFALO               | 1         | 1.72%   |
| ASUSTek Computer      | 1         | 1.72%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                        | 7         | 12.07%  |
| Intel Wireless-AC 9260                                                     | 5         | 8.62%   |
| Intel Wireless 8265 / 8275                                                 | 5         | 8.62%   |
| Intel Comet Lake PCH CNVi WiFi                                             | 5         | 8.62%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 5         | 8.62%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                          | 3         | 5.17%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 2         | 3.45%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 2         | 3.45%   |
| Ralink MT7601U Wireless Adapter                                            | 2         | 3.45%   |
| Intel Wireless 7260                                                        | 2         | 3.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 2         | 3.45%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 2         | 3.45%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                     | 1         | 1.72%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]        | 1         | 1.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 1.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 1.72%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                     | 1         | 1.72%   |
| Ralink RT5370 Wireless Adapter                                             | 1         | 1.72%   |
| Ralink RT2870/RT3070 Wireless Adapter                                      | 1         | 1.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 1         | 1.72%   |
| Intel Wi-Fi 6 AX201                                                        | 1         | 1.72%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                  | 1         | 1.72%   |
| Intel Centrino Advanced-N 6235                                             | 1         | 1.72%   |
| Edimax EW-7711MAC 802.11ac Wireless Adapter                                | 1         | 1.72%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]                   | 1         | 1.72%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                         | 1         | 1.72%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                        | 1         | 1.72%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                                        | 1         | 1.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 28        | 50.91%  |
| Intel                 | 24        | 43.64%  |
| Qualcomm Atheros      | 1         | 1.82%   |
| Lenovo                | 1         | 1.82%   |
| Emulex                | 1         | 1.82%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 24        | 42.86%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 10.71%  |
| Intel I211 Gigabit Network Connection                             | 4         | 7.14%   |
| Intel I210 Gigabit Network Connection                             | 3         | 5.36%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 5.36%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 3.57%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 3.57%   |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 3.57%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.79%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.79%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.79%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                  | 1         | 1.79%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.79%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1         | 1.79%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.79%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.79%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 1.79%   |
| Emulex OneConnect 10Gb NIC (be3)                                  | 1         | 1.79%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 51        | 49.04%  |
| WiFi     | 46        | 44.23%  |
| Modem    | 6         | 5.77%   |
| Unknown  | 1         | 0.96%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 48        | 64%     |
| WiFi     | 24        | 32%     |
| Modem    | 3         | 4%      |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 38        | 56.72%  |
| 1     | 13        | 19.4%   |
| 0     | 11        | 16.42%  |
| 3     | 3         | 4.48%   |
| 7     | 1         | 1.49%   |
| 4     | 1         | 1.49%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 59        | 83.1%   |
| Yes  | 12        | 16.9%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 28        | 84.85%  |
| Realtek Semiconductor | 1         | 3.03%   |
| Realtek               | 1         | 3.03%   |
| IMC Networks          | 1         | 3.03%   |
| Broadcom              | 1         | 3.03%   |
| Apple                 | 1         | 3.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                          | 7         | 21.21%  |
| Intel Bluetooth wireless interface             | 6         | 18.18%  |
| Intel AX200 Bluetooth                          | 6         | 18.18%  |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 4         | 12.12%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 4         | 12.12%  |
| Realtek  Bluetooth Adapter                     | 1         | 3.03%   |
| Realtek Bluetooth Radio                        | 1         | 3.03%   |
| Intel Centrino Bluetooth Wireless Transceiver  | 1         | 3.03%   |
| IMC Networks Bluetooth module                  | 1         | 3.03%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 1         | 3.03%   |
| Apple Apple Broadcom Built-in Bluetooth        | 1         | 3.03%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 29        | 36.25%  |
| AMD                     | 25        | 31.25%  |
| Nvidia                  | 16        | 20%     |
| Lenovo                  | 2         | 2.5%    |
| Yamaha                  | 1         | 1.25%   |
| VMware                  | 1         | 1.25%   |
| Logitech                | 1         | 1.25%   |
| GN Netcom               | 1         | 1.25%   |
| CMX Systems             | 1         | 1.25%   |
| C-Media Electronics     | 1         | 1.25%   |
| AudioQuest              | 1         | 1.25%   |
| AKAI  Professional M.I. | 1         | 1.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 12        | 12.24%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 7.14%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7         | 7.14%   |
| Intel Comet Lake PCH cAVS                                                  | 6         | 6.12%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 5         | 5.1%    |
| Nvidia GP107GL High Definition Audio Controller                            | 4         | 4.08%   |
| AMD Starship/Matisse HD Audio Controller                                   | 4         | 4.08%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4         | 4.08%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 3.06%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 3.06%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 3.06%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 3         | 3.06%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 2.04%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 2.04%   |
| Intel Sunrise Point-LP HD Audio                                            | 2         | 2.04%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 2.04%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 2.04%   |
| Yamaha Steinberg UR12                                                      | 1         | 1.02%   |
| VMware HD Audio Controller                                                 | 1         | 1.02%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 1.02%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 1.02%   |
| Nvidia GM206 High Definition Audio Controller                              | 1         | 1.02%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 1.02%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 1.02%   |
| Logitech H390 headset with microphone                                      | 1         | 1.02%   |
| Lenovo ThinkPad Dock Audio                                                 | 1         | 1.02%   |
| Lenovo Realtek USB Audio                                                   | 1         | 1.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.02%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 1.02%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1.02%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.02%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.02%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 1.02%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 1         | 1.02%   |
| GN Netcom Jabra SPEAK 410 USB                                              | 1         | 1.02%   |
| CMX Systems USB PnP Audio Device                                           | 1         | 1.02%   |
| C-Media Electronics BIRD UM1                                               | 1         | 1.02%   |
| AudioQuest DragonFly                                                       | 1         | 1.02%   |
| AMD Wrestler HDMI Audio                                                    | 1         | 1.02%   |
| AMD RV630 HDMI Audio [Radeon HD 2600 PRO/XT / HD 3610]                     | 1         | 1.02%   |
| AMD Navi 10 HDMI Audio                                                     | 1         | 1.02%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1         | 1.02%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1         | 1.02%   |
| AKAI  Professional M.I. LPK25 MIDI Keyboard                                | 1         | 1.02%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 14        | 23.33%  |
| SK Hynix            | 10        | 16.67%  |
| Micron Technology   | 10        | 16.67%  |
| Kingston            | 9         | 15%     |
| Crucial             | 4         | 6.67%   |
| Unknown             | 3         | 5%      |
| Smart               | 2         | 3.33%   |
| Ramaxel Technology  | 2         | 3.33%   |
| Corsair             | 2         | 3.33%   |
| PNY                 | 1         | 1.67%   |
| GOODRAM             | 1         | 1.67%   |
| A-DATA Technology   | 1         | 1.67%   |
| Unknown             | 1         | 1.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s        | 4         | 6.56%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 3.28%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s       | 2         | 3.28%   |
| SK Hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 2         | 3.28%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s        | 2         | 3.28%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s         | 2         | 3.28%   |
| Crucial RAM BL32G32C16S4B.M16FB1 32GB SODIMM DDR4 2667MT/s   | 2         | 3.28%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                    | 1         | 1.64%   |
| Unknown RAM Module 1GB SODIMM DDR                            | 1         | 1.64%   |
| Unknown RAM 2G-08-10-12-1333 2GB DIMM DDR3 1333MT/s          | 1         | 1.64%   |
| Smart RAM SF4641G8CK8IWGKSEG 8GB SODIMM DDR4 2133MT/s        | 1         | 1.64%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s        | 1         | 1.64%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 1         | 1.64%   |
| SK Hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s      | 1         | 1.64%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 1.64%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 1.64%   |
| Samsung RAM M474A4G43AB1-CVF 32GB SODIMM DDR4 2933MT/s       | 1         | 1.64%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM 1334MT/s             | 1         | 1.64%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 1         | 1.64%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s       | 1         | 1.64%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s  | 1         | 1.64%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 1.64%   |
| Samsung RAM M378A4G43MB1-CTD 32GB DIMM DDR4 2666MT/s         | 1         | 1.64%   |
| Samsung RAM K4EBE304EB-EGCF 8GB Row Of Chips LPDDR3 1867MT/s | 1         | 1.64%   |
| Ramaxel RAM RMSA3320MJ78HAF-3200 8GB SODIMM DDR4 3200MT/s    | 1         | 1.64%   |
| Ramaxel RAM RMSA3300MH78HBF-2666 16GB SODIMM DDR4 2400MT/s   | 1         | 1.64%   |
| PNY RAM 16GU2X16LIII43-12-K 16GB SODIMM DDR4 2667MT/s        | 1         | 1.64%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                   | 1         | 1.64%   |
| Micron RAM Module 16GB DIMM DDR4 2400MT/s                    | 1         | 1.64%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s        | 1         | 1.64%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s   | 1         | 1.64%   |
| Micron RAM 18ASF4G72AZ-3G2B1 32GB DIMM DDR4 3200MT/s         | 1         | 1.64%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s        | 1         | 1.64%   |
| Micron RAM 16ATF2G64HZ-2G6J1 16GB SODIMM DDR4 2667MT/s       | 1         | 1.64%   |
| Micron RAM 16ATF2G64AZ-3G2J1 16GB DIMM DDR4 3200MT/s         | 1         | 1.64%   |
| Kingston RAM Module 8GB SODIMM DDR4 2667MT/s                 | 1         | 1.64%   |
| Kingston RAM Module 16GB SODIMM DDR4 2667MT/s                | 1         | 1.64%   |
| Kingston RAM Module 16GB SODIMM DDR4 2400MT/s                | 1         | 1.64%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 2933MT/s         | 1         | 1.64%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 2666MT/s          | 1         | 1.64%   |
| Kingston RAM KHX2400C14S4/4G 4GB SODIMM DDR4 2400MT/s        | 1         | 1.64%   |
| Kingston RAM KHX1600C10D3/ 8GB DIMM DDR3 1600MT/s            | 1         | 1.64%   |
| Kingston RAM 99U5428-063.A00LF 8GB SODIMM DDR3 1600MT/s      | 1         | 1.64%   |
| Kingston RAM 9905713-030.A00G 8GB DIMM DDR4 2666MT/s         | 1         | 1.64%   |
| Kingston RAM 9905428-196.A00LF 8GB SODIMM DDR3 1333MT/s      | 1         | 1.64%   |
| GOODRAM RAM GR1600S364L11/8G 8GB SODIMM DDR3 1600MT/s        | 1         | 1.64%   |
| Crucial RAM CT16G4DFD832A.C16FP 16GB DIMM DDR4 3200MT/s      | 1         | 1.64%   |
| Crucial RAM BL16G36C16U4B.M8FB1 16GB DIMM DDR4 3600MT/s      | 1         | 1.64%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s        | 1         | 1.64%   |
| Corsair RAM CMD128GX4M8A2400C14 16GB DIMM DDR4 2133MT/s      | 1         | 1.64%   |
| A-DATA RAM DDR4 3200 16GB SODIMM DDR4 2667MT/s               | 1         | 1.64%   |
| Unknown                                                      | 1         | 1.64%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 39        | 73.58%  |
| DDR3   | 12        | 22.64%  |
| LPDDR3 | 1         | 1.89%   |
| DDR    | 1         | 1.89%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 38        | 70.37%  |
| DIMM         | 13        | 24.07%  |
| Row Of Chips | 3         | 5.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 26        | 48.15%  |
| 16384 | 16        | 29.63%  |
| 32768 | 5         | 9.26%   |
| 4096  | 4         | 7.41%   |
| 2048  | 2         | 3.7%    |
| 1024  | 1         | 1.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 17        | 30.36%  |
| 3200    | 11        | 19.64%  |
| 1600    | 9         | 16.07%  |
| 2400    | 5         | 8.93%   |
| 2933    | 3         | 5.36%   |
| 2666    | 3         | 5.36%   |
| 2133    | 2         | 3.57%   |
| 1333    | 2         | 3.57%   |
| 3600    | 1         | 1.79%   |
| 1867    | 1         | 1.79%   |
| 1334    | 1         | 1.79%   |
| Unknown | 1         | 1.79%   |

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
| Chicony Electronics                    | 11        | 25%     |
| IMC Networks                           | 9         | 20.45%  |
| Logitech                               | 6         | 13.64%  |
| Lite-On Technology                     | 4         | 9.09%   |
| Realtek Semiconductor                  | 3         | 6.82%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 6.82%   |
| Microdia                               | 2         | 4.55%   |
| Acer                                   | 2         | 4.55%   |
| Syntek                                 | 1         | 2.27%   |
| Sunplus Innovation Technology          | 1         | 2.27%   |
| GEMBIRD                                | 1         | 2.27%   |
| Aveo Technology                        | 1         | 2.27%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                             | 6         | 13.33%  |
| Chicony Integrated Camera                                                  | 5         | 11.11%  |
| Logitech Webcam C270                                                       | 3         | 6.67%   |
| Chicony Integrated HP HD Webcam                                            | 3         | 6.67%   |
| Lite-On Integrated Camera                                                  | 2         | 4.44%   |
| Lite-On HP HD Camera                                                       | 2         | 4.44%   |
| Syntek Lenovo EasyCamera                                                   | 1         | 2.22%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 2.22%   |
| Realtek USB 2 Webcam                                                       | 1         | 2.22%   |
| Realtek Laptop Camera                                                      | 1         | 2.22%   |
| Realtek Integrated_Webcam_HD                                               | 1         | 2.22%   |
| Microdia HP Integrated Webcam                                              | 1         | 2.22%   |
| Microdia Dell Integrated HD Webcam                                         | 1         | 2.22%   |
| Logitech Webcam C170                                                       | 1         | 2.22%   |
| Logitech HD Pro Webcam C920                                                | 1         | 2.22%   |
| Logitech C920 PRO HD Webcam                                                | 1         | 2.22%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 1         | 2.22%   |
| IMC Networks HD Camera                                                     | 1         | 2.22%   |
| IMC Networks EasyCamera                                                    | 1         | 2.22%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]                          | 1         | 2.22%   |
| Chicony USB2.0 0.3M UVC WebCam                                             | 1         | 2.22%   |
| Chicony ThinkPad T490 Webcam                                               | 1         | 2.22%   |
| Chicony Integrated IR Camera                                               | 1         | 2.22%   |
| Chicony HD Webcam                                                          | 1         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed]                | 1         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam   | 1         | 2.22%   |
| Aveo USB2.0 Camera                                                         | 1         | 2.22%   |
| Acer Integrated Camera                                                     | 1         | 2.22%   |
| Acer HD Webcam                                                             | 1         | 2.22%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 7         | 50%     |
| Validity Sensors           | 3         | 21.43%  |
| Shenzhen Goodix Technology | 3         | 21.43%  |
| AuthenTec                  | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 4         | 28.57%  |
| Validity Sensors Synaptics WBDI                                            | 2         | 14.29%  |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 14.29%  |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 14.29%  |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 7.14%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 7.14%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 7.14%   |
| AuthenTec AES2810                                                          | 1         | 7.14%   |

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
| 0     | 22        | 32.35%  |
| 4     | 13        | 19.12%  |
| 2     | 12        | 17.65%  |
| 1     | 11        | 16.18%  |
| 3     | 6         | 8.82%   |
| 5     | 3         | 4.41%   |
| 9     | 1         | 1.47%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 33        | 32.04%  |
| Net/wireless             | 22        | 21.36%  |
| Bluetooth                | 19        | 18.45%  |
| Fingerprint reader       | 14        | 13.59%  |
| Card reader              | 6         | 5.83%   |
| Sound                    | 4         | 3.88%   |
| Firewire controller      | 2         | 1.94%   |
| Network                  | 1         | 0.97%   |
| Net/ethernet             | 1         | 0.97%   |
| Modem                    | 1         | 0.97%   |

