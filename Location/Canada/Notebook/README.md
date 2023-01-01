BSD in Canada - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for BSD in Canada.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
  - [ OS                       ](#os)
  - [ OS Family                ](#os-family)
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

Total: 112

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| HP            | 2000                        | [5414b7c943](https://bsd-hardware.info/?probe=5414b7c943) | Dec 09, 2022 |
| Acer          | Swift SF114-34              | [2c560bad00](https://bsd-hardware.info/?probe=2c560bad00) | Dec 05, 2022 |
| Panasonic     | CF-54-1                     | [0c5820ea0d](https://bsd-hardware.info/?probe=0c5820ea0d) | Dec 01, 2022 |
| Lenovo        | ThinkPad X230 2325T4T       | [f0cc17c7eb](https://bsd-hardware.info/?probe=f0cc17c7eb) | Nov 21, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [8257d11669](https://bsd-hardware.info/?probe=8257d11669) | Nov 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [4044f32351](https://bsd-hardware.info/?probe=4044f32351) | Nov 12, 2022 |
| Lenovo        | ThinkPad X260 20F5S2GM00    | [b8874a6df3](https://bsd-hardware.info/?probe=b8874a6df3) | Nov 10, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [e8aea441aa](https://bsd-hardware.info/?probe=e8aea441aa) | Nov 06, 2022 |
| Lenovo        | ThinkPad X220 429043U       | [e5716f886a](https://bsd-hardware.info/?probe=e5716f886a) | Oct 30, 2022 |
| Lenovo        | ThinkPad T420s 41742BU      | [34f0a2bc03](https://bsd-hardware.info/?probe=34f0a2bc03) | Oct 30, 2022 |
| Lenovo        | ThinkPad T460 20FMS10N00    | [04ce25bd7f](https://bsd-hardware.info/?probe=04ce25bd7f) | Oct 29, 2022 |
| Fujitsu       | LIFEBOOK E752               | [e3c5057898](https://bsd-hardware.info/?probe=e3c5057898) | Oct 29, 2022 |
| Unknown       | Unknown                     | [2df5c5b434](https://bsd-hardware.info/?probe=2df5c5b434) | Oct 28, 2022 |
| Panasonic     | CF-53AAGHYDM                | [f2fafaa9e3](https://bsd-hardware.info/?probe=f2fafaa9e3) | Oct 27, 2022 |
| Matsushita... | CF-48V4KNDQM                | [d96fbc17b5](https://bsd-hardware.info/?probe=d96fbc17b5) | Oct 27, 2022 |
| Panasonic     | CF-52PFPBSFQ                | [088e0245af](https://bsd-hardware.info/?probe=088e0245af) | Oct 27, 2022 |
| Matsushita... | CF-51RCVDNLM                | [6e8067d4d8](https://bsd-hardware.info/?probe=6e8067d4d8) | Oct 26, 2022 |
| Lenovo        | ThinkPad T410 2537N24       | [b7a4ee06a6](https://bsd-hardware.info/?probe=b7a4ee06a6) | Oct 26, 2022 |
| Lenovo        | ThinkPad T430 2347GZU       | [f2236f17ee](https://bsd-hardware.info/?probe=f2236f17ee) | Oct 25, 2022 |
| ASUSTek       | 1000HE                      | [c4bbcf9537](https://bsd-hardware.info/?probe=c4bbcf9537) | Oct 24, 2022 |
| MSI           | GL65 Leopard 10SFSK         | [2ea7c7f9a2](https://bsd-hardware.info/?probe=2ea7c7f9a2) | Oct 10, 2022 |
| MSI           | GL65 Leopard 10SFSK         | [489567748e](https://bsd-hardware.info/?probe=489567748e) | Oct 01, 2022 |
| Intel         | H81U                        | [fa8c32528a](https://bsd-hardware.info/?probe=fa8c32528a) | Sep 28, 2022 |
| Acer          | Swift SF313-52              | [83516dabac](https://bsd-hardware.info/?probe=83516dabac) | Sep 28, 2022 |
| Acer          | Swift SF313-52              | [6339e6b468](https://bsd-hardware.info/?probe=6339e6b468) | Sep 25, 2022 |
| Lenovo        | ThinkPad X250 20CL001GUS    | [2f1f82558e](https://bsd-hardware.info/?probe=2f1f82558e) | Sep 18, 2022 |
| Google        | Peppy                       | [80ffa77224](https://bsd-hardware.info/?probe=80ffa77224) | Sep 15, 2022 |
| Intel         | H81U                        | [b5e2598580](https://bsd-hardware.info/?probe=b5e2598580) | Aug 03, 2022 |
| Intel         | H81U                        | [8f50dbe259](https://bsd-hardware.info/?probe=8f50dbe259) | Aug 01, 2022 |
| Dell          | Latitude E7440              | [03497b7b2a](https://bsd-hardware.info/?probe=03497b7b2a) | Jul 27, 2022 |
| Lenovo        | IdeaPad Y580 20132          | [3df3bd2f62](https://bsd-hardware.info/?probe=3df3bd2f62) | Jul 22, 2022 |
| Dell          | Studio 1747                 | [7ae292b282](https://bsd-hardware.info/?probe=7ae292b282) | May 21, 2022 |
| Dell          | Inspiron 5559               | [a7111b84cb](https://bsd-hardware.info/?probe=a7111b84cb) | May 08, 2022 |
| Fujitsu       | LIFEBOOK E752               | [3e60a82218](https://bsd-hardware.info/?probe=3e60a82218) | May 06, 2022 |
| ASUSTek       | 1000HE                      | [a6393754b4](https://bsd-hardware.info/?probe=a6393754b4) | May 05, 2022 |
| Matsushita... | CF-48V4KNDQM                | [774cab5326](https://bsd-hardware.info/?probe=774cab5326) | May 03, 2022 |
| Matsushita... | CF-51RCVDNLM                | [4b1abdd507](https://bsd-hardware.info/?probe=4b1abdd507) | May 03, 2022 |
| Lenovo        | ThinkPad T410 2537N24       | [2884106c6b](https://bsd-hardware.info/?probe=2884106c6b) | May 03, 2022 |
| Lenovo        | ThinkPad T430 2347GZU       | [00ba6ca9f8](https://bsd-hardware.info/?probe=00ba6ca9f8) | May 03, 2022 |
| Lenovo        | ThinkPad T420s 41742BU      | [6b77fe651f](https://bsd-hardware.info/?probe=6b77fe651f) | May 03, 2022 |
| Lenovo        | ThinkPad X220 429043U       | [f3c30a6190](https://bsd-hardware.info/?probe=f3c30a6190) | May 02, 2022 |
| Panasonic     | CF-53AAGHYDM                | [abd8754907](https://bsd-hardware.info/?probe=abd8754907) | May 01, 2022 |
| Panasonic     | CF-52PFPBSFQ                | [1ce63e2214](https://bsd-hardware.info/?probe=1ce63e2214) | Apr 29, 2022 |
| Toshiba       | Satellite Pro T130          | [62dd51afcf](https://bsd-hardware.info/?probe=62dd51afcf) | Apr 11, 2022 |
| Intel         | H81U                        | [71068a0577](https://bsd-hardware.info/?probe=71068a0577) | Mar 01, 2022 |
| Lenovo        | ThinkPad X250 20CL001GUS    | [4ae2360503](https://bsd-hardware.info/?probe=4ae2360503) | Jan 11, 2022 |
| Toshiba       | TECRA Z40-B                 | [d498fcd3f8](https://bsd-hardware.info/?probe=d498fcd3f8) | Jan 02, 2022 |
| ASUSTek       | U31SD                       | [a07366611d](https://bsd-hardware.info/?probe=a07366611d) | Jan 02, 2022 |
| ASUSTek       | TUF GAMING FX504GD_FX80G... | [259b5cc7b2](https://bsd-hardware.info/?probe=259b5cc7b2) | Dec 28, 2021 |
| Lenovo        | ThinkPad X280 20KF001UUS    | [5b9001009e](https://bsd-hardware.info/?probe=5b9001009e) | Dec 20, 2021 |
| Lenovo        | ThinkPad T420s 41742BU      | [a86326d049](https://bsd-hardware.info/?probe=a86326d049) | Dec 11, 2021 |
| Lenovo        | ThinkPad X220 429043U       | [339779baad](https://bsd-hardware.info/?probe=339779baad) | Nov 26, 2021 |
| Dell          | Studio 1747                 | [b0a51ac0af](https://bsd-hardware.info/?probe=b0a51ac0af) | Nov 11, 2021 |
| Dell          | Studio 1747                 | [7ab6b58d69](https://bsd-hardware.info/?probe=7ab6b58d69) | Nov 11, 2021 |
| Panasonic     | CF-53AAGHYDM                | [721ef0235c](https://bsd-hardware.info/?probe=721ef0235c) | Oct 30, 2021 |
| Matsushita... | CF-48V4KNDQM                | [9e254ab443](https://bsd-hardware.info/?probe=9e254ab443) | Oct 23, 2021 |
| ASUSTek       | 1000HE                      | [1d5e3e5bc3](https://bsd-hardware.info/?probe=1d5e3e5bc3) | Oct 22, 2021 |
| Lenovo        | ThinkPad T430 2347GZU       | [3337c00433](https://bsd-hardware.info/?probe=3337c00433) | Oct 22, 2021 |
| Dell          | Studio 1747                 | [ca939fbe2f](https://bsd-hardware.info/?probe=ca939fbe2f) | Oct 19, 2021 |
| Matsushita... | CF-51RCVDNLM                | [b20953f2f4](https://bsd-hardware.info/?probe=b20953f2f4) | Oct 18, 2021 |
| Panasonic     | CF-52PFPBSFQ                | [bbdfde368b](https://bsd-hardware.info/?probe=bbdfde368b) | Oct 18, 2021 |
| Lenovo        | ThinkPad T410 2537N24       | [1a5bae2227](https://bsd-hardware.info/?probe=1a5bae2227) | Oct 15, 2021 |
| HP            | Notebook                    | [a3c3297cd2](https://bsd-hardware.info/?probe=a3c3297cd2) | Aug 08, 2021 |
| HP            | Notebook                    | [0c316107a4](https://bsd-hardware.info/?probe=0c316107a4) | Aug 08, 2021 |
| Gigabyte      | MMLP3AP-00                  | [168e674b55](https://bsd-hardware.info/?probe=168e674b55) | Jul 03, 2021 |
| Dell          | Inspiron 15-7579            | [4b8b5f7918](https://bsd-hardware.info/?probe=4b8b5f7918) | Jun 19, 2021 |
| LG Electro... | E500-GP01A9                 | [7db1345e97](https://bsd-hardware.info/?probe=7db1345e97) | Jun 17, 2021 |
| LG Electro... | E500-GP01A9                 | [cbade775b6](https://bsd-hardware.info/?probe=cbade775b6) | Jun 17, 2021 |
| LG Electro... | E500-GP01A9                 | [80052d6cdc](https://bsd-hardware.info/?probe=80052d6cdc) | Jun 15, 2021 |
| Dell          | Inspiron 15-3567            | [d239ee4916](https://bsd-hardware.info/?probe=d239ee4916) | Jun 12, 2021 |
| Apple         | PowerBook5,2                | [8cc0aab53c](https://bsd-hardware.info/?probe=8cc0aab53c) | May 31, 2021 |
| Panasonic     | CF-53AAGHYDM                | [ef5e9ec095](https://bsd-hardware.info/?probe=ef5e9ec095) | May 18, 2021 |
| Panasonic     | CF-52PFPBSFQ                | [65f5931910](https://bsd-hardware.info/?probe=65f5931910) | May 18, 2021 |
| Lenovo        | ThinkPad T430 2347GZU       | [1e9f399d73](https://bsd-hardware.info/?probe=1e9f399d73) | May 17, 2021 |
| Lenovo        | ThinkPad T410 2537N24       | [109f3afa21](https://bsd-hardware.info/?probe=109f3afa21) | May 17, 2021 |
| ASUSTek       | 1000HE                      | [f92f43bc54](https://bsd-hardware.info/?probe=f92f43bc54) | May 17, 2021 |
| Matsushita... | CF-51RCVDNLM                | [33bc82e701](https://bsd-hardware.info/?probe=33bc82e701) | May 17, 2021 |
| Matsushita... | CF-48V4KNDQM                | [bf76401b74](https://bsd-hardware.info/?probe=bf76401b74) | May 17, 2021 |
| Dell          | Latitude 3440               | [3c8d21772a](https://bsd-hardware.info/?probe=3c8d21772a) | May 01, 2021 |
| Dell          | Latitude 3440               | [7e85a38390](https://bsd-hardware.info/?probe=7e85a38390) | Apr 04, 2021 |
| ASUSTek       | G75VW                       | [9b84d1e7e6](https://bsd-hardware.info/?probe=9b84d1e7e6) | Mar 24, 2021 |
| ASUSTek       | G75VW                       | [cf4b3e0c6f](https://bsd-hardware.info/?probe=cf4b3e0c6f) | Mar 23, 2021 |
| ASUSTek       | G75VW                       | [4a59793120](https://bsd-hardware.info/?probe=4a59793120) | Mar 23, 2021 |
| Dell          | Inspiron 7370               | [7e2328dda3](https://bsd-hardware.info/?probe=7e2328dda3) | Mar 20, 2021 |
| Apple         | MacBookPro5,5               | [f46146b79e](https://bsd-hardware.info/?probe=f46146b79e) | Mar 11, 2021 |
| Apple         | MacBookPro5,5               | [c1ed4c02b8](https://bsd-hardware.info/?probe=c1ed4c02b8) | Mar 11, 2021 |
| Alienware     | 14                          | [0e0cdf952a](https://bsd-hardware.info/?probe=0e0cdf952a) | Mar 06, 2021 |
| Toshiba       | Satellite U500              | [feae098542](https://bsd-hardware.info/?probe=feae098542) | Feb 20, 2021 |
| Lenovo        | ThinkPad T410 253722U       | [219e9cb1d7](https://bsd-hardware.info/?probe=219e9cb1d7) | Feb 10, 2021 |
| Intel         | H81U                        | [efb1f9d207](https://bsd-hardware.info/?probe=efb1f9d207) | Feb 07, 2021 |
| Alienware     | 14                          | [dd2cc000a7](https://bsd-hardware.info/?probe=dd2cc000a7) | Jan 07, 2021 |
| Alienware     | 14                          | [48f61623f2](https://bsd-hardware.info/?probe=48f61623f2) | Jan 07, 2021 |
| HP            | EliteBook 840 G3            | [11011ecee1](https://bsd-hardware.info/?probe=11011ecee1) | Jan 02, 2021 |
| Lenovo        | ThinkPad T440 20B7S0A800    | [d3474f1ca3](https://bsd-hardware.info/?probe=d3474f1ca3) | Nov 18, 2020 |
| Lenovo        | ThinkPad T490 20N3S8PB00    | [6a0f910601](https://bsd-hardware.info/?probe=6a0f910601) | Nov 10, 2020 |
| Lenovo        | ThinkPad T490 20N3S8PB00    | [6dca4cdd18](https://bsd-hardware.info/?probe=6dca4cdd18) | Nov 10, 2020 |
| Lenovo        | ThinkPad T430 2347GZU       | [f287de215c](https://bsd-hardware.info/?probe=f287de215c) | Oct 20, 2020 |
| Lenovo        | ThinkPad T410 2537N24       | [f846609c80](https://bsd-hardware.info/?probe=f846609c80) | Oct 20, 2020 |
| Panasonic     | CF-52PFPBSFQ                | [feb1da0406](https://bsd-hardware.info/?probe=feb1da0406) | Oct 20, 2020 |
| Matsushita... | CF-51RCVDNLM                | [efece2abf7](https://bsd-hardware.info/?probe=efece2abf7) | Oct 20, 2020 |
| ASUSTek       | 1000HE                      | [621df26e0c](https://bsd-hardware.info/?probe=621df26e0c) | Oct 19, 2020 |
| Lenovo        | ThinkPad T460 20FMS1BC01    | [bf6d6d155b](https://bsd-hardware.info/?probe=bf6d6d155b) | Oct 19, 2020 |
| Lenovo        | ThinkPad E495 20NE0001US    | [a1fc75a9b7](https://bsd-hardware.info/?probe=a1fc75a9b7) | Oct 09, 2020 |
| HP            | Pavilion dv6500             | [316ffb0740](https://bsd-hardware.info/?probe=316ffb0740) | Sep 04, 2020 |
| Acer          | AOD270                      | [41d2974f13](https://bsd-hardware.info/?probe=41d2974f13) | Aug 20, 2020 |
| HP            | Compaq Mini 110c-1100       | [515042ff2d](https://bsd-hardware.info/?probe=515042ff2d) | Aug 20, 2020 |
| Lenovo        | ThinkPad T510 4313CTO       | [7f6095b266](https://bsd-hardware.info/?probe=7f6095b266) | Aug 20, 2020 |
| HP            | EliteBook 840 G3            | [e568f0f32e](https://bsd-hardware.info/?probe=e568f0f32e) | Aug 04, 2020 |
| ASUSTek       | K52JK                       | [d5d32f1334](https://bsd-hardware.info/?probe=d5d32f1334) | Jun 29, 2020 |
| Lenovo        | ThinkPad T420 4180B39       | [05ed5eb1e4](https://bsd-hardware.info/?probe=05ed5eb1e4) | May 25, 2020 |
| Lenovo        | ThinkPad X270 20HNCTO1WW    | [7def094afb](https://bsd-hardware.info/?probe=7def094afb) | May 23, 2020 |
| ASUSTek       | K52JK                       | [6a6b06fc67](https://bsd-hardware.info/?probe=6a6b06fc67) | May 23, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| OpenBSD 7.2         | 15        | 15.31%  |
| OpenBSD 7.1         | 10        | 10.2%   |
| OpenBSD 7.0         | 9         | 9.18%   |
| OpenBSD 6.9         | 9         | 9.18%   |
| OpenBSD 6.8         | 7         | 7.14%   |
| helloSystem 0.4.0   | 4         | 4.08%   |
| FreeBSD 13.0-p5     | 3         | 3.06%   |
| helloSystem 0.8.0   | 2         | 2.04%   |
| helloSystem 0.7.0   | 2         | 2.04%   |
| helloSystem 0.5.0   | 2         | 2.04%   |
| FreeBSD 13.1-p2     | 2         | 2.04%   |
| FreeBSD 13.1        | 2         | 2.04%   |
| FreeBSD 13.0        | 2         | 2.04%   |
| FreeBSD 12.2        | 2         | 2.04%   |
| OPNsense 22.7.6     | 1         | 1.02%   |
| OPNsense 22.7.5     | 1         | 1.02%   |
| OPNsense 22.7.4     | 1         | 1.02%   |
| OPNsense 22.7       | 1         | 1.02%   |
| OPNsense 22.1.1     | 1         | 1.02%   |
| OPNsense 21.1.5     | 1         | 1.02%   |
| OPNsense 21.1.4     | 1         | 1.02%   |
| OPNsense 21.1       | 1         | 1.02%   |
| NetBSD 8.99.51      | 1         | 1.02%   |
| helloSystem 0.6.0   | 1         | 1.02%   |
| GhostBSD 22.06.18   | 1         | 1.02%   |
| GhostBSD 21.08.27   | 1         | 1.02%   |
| FreeBSD 13.1-STABLE | 1         | 1.02%   |
| FreeBSD 13.1-p4     | 1         | 1.02%   |
| FreeBSD 13.0-p3     | 1         | 1.02%   |
| FreeBSD 13.0-p2     | 1         | 1.02%   |
| FreeBSD 12.1-STABLE | 1         | 1.02%   |
| FreeBSD 12.1-p8     | 1         | 1.02%   |
| FreeBSD 12.1-p5     | 1         | 1.02%   |
| FreeBSD 12.1-p10    | 1         | 1.02%   |
| FreeBSD 12.1        | 1         | 1.02%   |
| FreeBSD 12.0-p3     | 1         | 1.02%   |
| FreeBSD 12.0-p13    | 1         | 1.02%   |
| FreeBSD 11.4-p8     | 1         | 1.02%   |
| FreeBSD 11.4-p7     | 1         | 1.02%   |
| FreeBSD 11.4-p6     | 1         | 1.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 23        | 37.7%   |
| OpenBSD     | 19        | 31.15%  |
| helloSystem | 10        | 16.39%  |
| OPNsense    | 6         | 9.84%   |
| GhostBSD    | 2         | 3.28%   |
| NetBSD      | 1         | 1.64%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| amd64  | 56        | 91.8%   |
| i386   | 4         | 6.56%   |
| macppc | 1         | 1.64%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 24        | 34.29%  |
| fvwm         | 12        | 17.14%  |
| XFCE         | 9         | 12.86%  |
| Console      | 9         | 12.86%  |
| TWM          | 3         | 4.29%   |
| Openbox      | 2         | 2.86%   |
| KDE5         | 2         | 2.86%   |
| i3           | 2         | 2.86%   |
| GNOME        | 2         | 2.86%   |
| MATE         | 1         | 1.43%   |
| LXQt         | 1         | 1.43%   |
| Lumina       | 1         | 1.43%   |
| Fluxbox      | 1         | 1.43%   |
| Cinnamon     | 1         | 1.43%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 52        | 85.25%  |
| Console | 9         | 14.75%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 35        | 56.45%  |
| SLiM    | 11        | 17.74%  |
| XDM     | 7         | 11.29%  |
| LightDM | 4         | 6.45%   |
| SDDM    | 3         | 4.84%   |
| GDM     | 2         | 3.23%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 35        | 57.38%  |
| en_US   | 12        | 19.67%  |
| C       | 6         | 9.84%   |
| en_CA   | 4         | 6.56%   |
| fr_FR   | 2         | 3.28%   |
| fr_CA   | 1         | 1.64%   |
| en_NL   | 1         | 1.64%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 39        | 62.9%   |
| BIOS | 23        | 37.1%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 23        | 37.7%   |
| Ffs    | 19        | 31.15%  |
| Ufs    | 18        | 29.51%  |
| Cd9660 | 1         | 1.64%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 46        | 75.41%  |
| MBR     | 13        | 21.31%  |
| Unknown | 2         | 3.28%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 21        | 34.43%  |
| Dell                           | 7         | 11.48%  |
| Hewlett-Packard                | 5         | 8.2%    |
| ASUSTek Computer               | 5         | 8.2%    |
| Toshiba                        | 3         | 4.92%   |
| Panasonic                      | 3         | 4.92%   |
| Intel                          | 3         | 4.92%   |
| Acer                           | 3         | 4.92%   |
| Matsushita Electric Industrial | 2         | 3.28%   |
| Apple                          | 2         | 3.28%   |
| MSI                            | 1         | 1.64%   |
| LG Electronics                 | 1         | 1.64%   |
| Google                         | 1         | 1.64%   |
| Gigabyte Technology            | 1         | 1.64%   |
| Fujitsu                        | 1         | 1.64%   |
| Alienware                      | 1         | 1.64%   |
| Unknown                        | 1         | 1.64%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel H81U                                  | 3         | 4.92%   |
| Toshiba TECRA Z40-B                         | 1         | 1.64%   |
| Toshiba Satellite U500                      | 1         | 1.64%   |
| Toshiba Satellite Pro T130                  | 1         | 1.64%   |
| Panasonic CF-54-1                           | 1         | 1.64%   |
| Panasonic CF-53AAGHYDM                      | 1         | 1.64%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 1.64%   |
| MSI GL65 Leopard 10SFSK                     | 1         | 1.64%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 1.64%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 1.64%   |
| LG E500-GP01A9                              | 1         | 1.64%   |
| Lenovo ThinkPad X280 20KF001UUS             | 1         | 1.64%   |
| Lenovo ThinkPad X270 W10DG 20K5S0TT1N       | 1         | 1.64%   |
| Lenovo ThinkPad X270 W10DG 20K5S0PY04       | 1         | 1.64%   |
| Lenovo ThinkPad X270 20HNCTO1WW             | 1         | 1.64%   |
| Lenovo ThinkPad X260 20F5S2GM00             | 1         | 1.64%   |
| Lenovo ThinkPad X250 20CL001GUS             | 1         | 1.64%   |
| Lenovo ThinkPad X230 2325T4T                | 1         | 1.64%   |
| Lenovo ThinkPad X220 429043U                | 1         | 1.64%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS13H00    | 1         | 1.64%   |
| Lenovo ThinkPad T510 4313CTO                | 1         | 1.64%   |
| Lenovo ThinkPad T490 20N3S8PB00             | 1         | 1.64%   |
| Lenovo ThinkPad T460 20FMS1BC01             | 1         | 1.64%   |
| Lenovo ThinkPad T460 20FMS10N00             | 1         | 1.64%   |
| Lenovo ThinkPad T440 20B7S0A800             | 1         | 1.64%   |
| Lenovo ThinkPad T430 2347GZU                | 1         | 1.64%   |
| Lenovo ThinkPad T420s 41742BU               | 1         | 1.64%   |
| Lenovo ThinkPad T420 4180B39                | 1         | 1.64%   |
| Lenovo ThinkPad T410 2537N24                | 1         | 1.64%   |
| Lenovo ThinkPad T410 253722U                | 1         | 1.64%   |
| Lenovo ThinkPad E495 20NE0001US             | 1         | 1.64%   |
| Lenovo IdeaPad Y580 20132                   | 1         | 1.64%   |
| HP Pavilion dv6500                          | 1         | 1.64%   |
| HP Notebook                                 | 1         | 1.64%   |
| HP EliteBook 840 G3                         | 1         | 1.64%   |
| HP Compaq Mini 110c-1100                    | 1         | 1.64%   |
| HP 2000                                     | 1         | 1.64%   |
| Google Peppy                                | 1         | 1.64%   |
| Gigabyte MMLP3AP-00                         | 1         | 1.64%   |
| Fujitsu LIFEBOOK E752                       | 1         | 1.64%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad                             | 20        | 32.79%  |
| Dell Inspiron                               | 4         | 6.56%   |
| Intel H81U                                  | 3         | 4.92%   |
| Toshiba Satellite                           | 2         | 3.28%   |
| Dell Latitude                               | 2         | 3.28%   |
| Acer Swift                                  | 2         | 3.28%   |
| Toshiba TECRA                               | 1         | 1.64%   |
| Panasonic CF-54-1                           | 1         | 1.64%   |
| Panasonic CF-53AAGHYDM                      | 1         | 1.64%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 1.64%   |
| MSI GL65                                    | 1         | 1.64%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 1.64%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 1.64%   |
| LG E500-GP01A9                              | 1         | 1.64%   |
| Lenovo IdeaPad                              | 1         | 1.64%   |
| HP Pavilion                                 | 1         | 1.64%   |
| HP Notebook                                 | 1         | 1.64%   |
| HP EliteBook                                | 1         | 1.64%   |
| HP Compaq                                   | 1         | 1.64%   |
| HP 2000                                     | 1         | 1.64%   |
| Google Peppy                                | 1         | 1.64%   |
| Gigabyte MMLP3AP-00                         | 1         | 1.64%   |
| Fujitsu LIFEBOOK                            | 1         | 1.64%   |
| Dell Studio                                 | 1         | 1.64%   |
| ASUS U31SD                                  | 1         | 1.64%   |
| ASUS TUF                                    | 1         | 1.64%   |
| ASUS K52JK                                  | 1         | 1.64%   |
| ASUS G75VW                                  | 1         | 1.64%   |
| ASUS 1000HE                                 | 1         | 1.64%   |
| Apple PowerBook5                            | 1         | 1.64%   |
| Apple MacBookPro5                           | 1         | 1.64%   |
| Alienware 14                                | 1         | 1.64%   |
| Acer AOD270                                 | 1         | 1.64%   |
| Unknown                                     | 1         | 1.64%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 8         | 13.11%  |
| 2010    | 8         | 13.11%  |
| 2011    | 7         | 11.48%  |
| 2016    | 5         | 8.2%    |
| 2015    | 5         | 8.2%    |
| 2018    | 4         | 6.56%   |
| 2012    | 4         | 6.56%   |
| 2021    | 3         | 4.92%   |
| 2014    | 3         | 4.92%   |
| 2009    | 3         | 4.92%   |
| 2020    | 2         | 3.28%   |
| 2017    | 2         | 3.28%   |
| 2013    | 2         | 3.28%   |
| 2022    | 1         | 1.64%   |
| 2008    | 1         | 1.64%   |
| 2006    | 1         | 1.64%   |
| 2002    | 1         | 1.64%   |
| Unknown | 1         | 1.64%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 61        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 60        | 98.36%  |
| Yes  | 1         | 1.64%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 27        | 44.26%  |
| 4.01-8.0   | 12        | 19.67%  |
| 16.01-24.0 | 9         | 14.75%  |
| 3.01-4.0   | 5         | 8.2%    |
| 2.01-3.0   | 4         | 6.56%   |
| 32.01-64.0 | 2         | 3.28%   |
| 1.01-2.0   | 1         | 1.64%   |
| 0.51-1.0   | 1         | 1.64%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 43        | 69.35%  |
| 0.51-1.0 | 13        | 20.97%  |
| 1.01-2.0 | 2         | 3.23%   |
| 0        | 2         | 3.23%   |
| 3.01-4.0 | 1         | 1.61%   |
| Unknown  | 1         | 1.61%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 50        | 80.65%  |
| 2      | 8         | 12.9%   |
| 0      | 4         | 6.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 47        | 77.05%  |
| Yes       | 14        | 22.95%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 56        | 91.8%   |
| No        | 5         | 8.2%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 57        | 93.44%  |
| No        | 4         | 6.56%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 63.93%  |
| No        | 22        | 36.07%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Canada  | 61        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Montreal         | 18        | 23.08%  |
| Saint-Laurent    | 9         | 11.54%  |
| Vancouver        | 6         | 7.69%   |
| QuГ©bec        | 5         | 6.41%   |
| Ottawa           | 3         | 3.85%   |
| Kingsburg        | 3         | 3.85%   |
| Calgary          | 3         | 3.85%   |
| Victoria         | 2         | 2.56%   |
| Toronto          | 2         | 2.56%   |
| Stratford        | 2         | 2.56%   |
| Sainte-Julie     | 2         | 2.56%   |
| Peterborough     | 2         | 2.56%   |
| Winnipeg         | 1         | 1.28%   |
| Vaudreuil-Dorion | 1         | 1.28%   |
| Surrey           | 1         | 1.28%   |
| Sechelt          | 1         | 1.28%   |
| Saint-Zotique    | 1         | 1.28%   |
| Québec          | 1         | 1.28%   |
| North York       | 1         | 1.28%   |
| Niagara Falls    | 1         | 1.28%   |
| Nepean           | 1         | 1.28%   |
| Mississauga      | 1         | 1.28%   |
| Mission          | 1         | 1.28%   |
| Maple Ridge      | 1         | 1.28%   |
| Lloydminster     | 1         | 1.28%   |
| Laval            | 1         | 1.28%   |
| Langley          | 1         | 1.28%   |
| Lamont           | 1         | 1.28%   |
| Hamilton         | 1         | 1.28%   |
| Halifax          | 1         | 1.28%   |
| Guelph           | 1         | 1.28%   |
| Gatineau         | 1         | 1.28%   |
| Beloeil          | 1         | 1.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 16        | 39     | 25.4%   |
| Samsung Electronics | 7         | 10     | 11.11%  |
| Toshiba             | 6         | 7      | 9.52%   |
| Seagate             | 5         | 9      | 7.94%   |
| Kingston            | 4         | 4      | 6.35%   |
| Hitachi             | 4         | 7      | 6.35%   |
| A-DATA Technology   | 3         | 6      | 4.76%   |
| NVMe                | 2         | 2      | 3.17%   |
| Lexar               | 2         | 3      | 3.17%   |
| Intel               | 2         | 2      | 3.17%   |
| Crucial             | 2         | 2      | 3.17%   |
| Transcend           | 1         | 1      | 1.59%   |
| SK hynix            | 1         | 1      | 1.59%   |
| SanDisk             | 1         | 1      | 1.59%   |
| Phison              | 1         | 1      | 1.59%   |
| OCZ                 | 1         | 1      | 1.59%   |
| Micron Technology   | 1         | 1      | 1.59%   |
| Kston               | 1         | 2      | 1.59%   |
| KingDian            | 1         | 1      | 1.59%   |
| Hewlett-Packard     | 1         | 1      | 1.59%   |
| Fujitsu             | 1         | 1      | 1.59%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| WDC WDS500G2B0A-00SM50 500GB         | 2         | 3.13%   |
| Kingston SA400S37240G 240GB          | 2         | 3.13%   |
| WDC WDS500G2B0A 500GB                | 1         | 1.56%   |
| WDC WDS200T2B0A 2TB                  | 1         | 1.56%   |
| WDC WD7500BPKX-75HPJT0 752GB         | 1         | 1.56%   |
| WDC WD7500BPKX-00HPJT0 752GB         | 1         | 1.56%   |
| WDC WD7500BPKT-75PK4T0 752GB         | 1         | 1.56%   |
| WDC WD7500BPKT-00PK4T0 752GB         | 1         | 1.56%   |
| WDC WD6400BEVT-22A0RT0 640GB         | 1         | 1.56%   |
| WDC WD5000LPLX-00ZNTT0 500GB         | 1         | 1.56%   |
| WDC WD3200LPVX-60V0TT0 320GB         | 1         | 1.56%   |
| WDC WD3200BEVE-00A0HT0 320GB         | 1         | 1.56%   |
| WDC WD10JPVX-75JC3T0 1TB             | 1         | 1.56%   |
| WDC WD10JPVT-00A1YT0 1TB             | 1         | 1.56%   |
| WDC WD10JPLX-00MBPT0 1TB             | 1         | 1.56%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB   | 1         | 1.56%   |
| WDC PC SN530 SDBPNPZ-256G-1014 256GB | 1         | 1.56%   |
| Transcend TSA 240GB                  | 1         | 1.56%   |
| Toshiba THNSNJ128GCSU 128GB          | 1         | 1.56%   |
| Toshiba MQ04ABF100 1TB               | 1         | 1.56%   |
| Toshiba MQ01ABF032 320GB             | 1         | 1.56%   |
| Toshiba MK8025GAS 80GB               | 1         | 1.56%   |
| Toshiba MK5061GSYN 500GB             | 1         | 1.56%   |
| Toshiba MK3259GSXP 320GB             | 1         | 1.56%   |
| SK hynix SC308 SATA 256GB            | 1         | 1.56%   |
| Seagate ST9500420AS 500GB            | 1         | 1.56%   |
| Seagate ST9160821A 160GB             | 1         | 1.56%   |
| Seagate ST500LT032-1E9142 500GB      | 1         | 1.56%   |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 1         | 1.56%   |
| Seagate ST1000LM035-1RK172 1TB       | 1         | 1.56%   |
| SanDisk SSD U100 16GB                | 1         | 1.56%   |
| Samsung SSD 860 EVO M.2 1TB          | 1         | 1.56%   |
| Samsung SSD 860 EVO 500GB            | 1         | 1.56%   |
| Samsung SSD 860 EVO 1TB              | 1         | 1.56%   |
| Samsung SSD 850 PRO 256GB            | 1         | 1.56%   |
| Samsung MZ7TE128HMGR-000L1 128GB     | 1         | 1.56%   |
| Samsung MZ7TD128HAFV-000L1 128GB     | 1         | 1.56%   |
| Samsung MZ7PC128HAFU-000L1 128GB     | 1         | 1.56%   |
| Phison PCIe SSD 512GB                | 1         | 1.56%   |
| OCZ VERTEX3 120GB                    | 1         | 1.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 11        | 33     | 37.93%  |
| Toshiba | 5         | 6      | 17.24%  |
| Seagate | 5         | 9      | 17.24%  |
| Hitachi | 4         | 7      | 13.79%  |
| NVMe    | 2         | 2      | 6.9%    |
| Lexar   | 1         | 1      | 3.45%   |
| Fujitsu | 1         | 1      | 3.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 10     | 22.58%  |
| WDC                 | 4         | 4      | 12.9%   |
| Kingston            | 4         | 4      | 12.9%   |
| Intel               | 2         | 2      | 6.45%   |
| Crucial             | 2         | 2      | 6.45%   |
| A-DATA Technology   | 2         | 5      | 6.45%   |
| Transcend           | 1         | 1      | 3.23%   |
| Toshiba             | 1         | 1      | 3.23%   |
| SK hynix            | 1         | 1      | 3.23%   |
| SanDisk             | 1         | 1      | 3.23%   |
| OCZ                 | 1         | 1      | 3.23%   |
| Micron Technology   | 1         | 1      | 3.23%   |
| Lexar               | 1         | 2      | 3.23%   |
| Kston               | 1         | 2      | 3.23%   |
| KingDian            | 1         | 1      | 3.23%   |
| Hewlett-Packard     | 1         | 1      | 3.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 28        | 39     | 46.67%  |
| HDD  | 28        | 59     | 46.67%  |
| NVMe | 4         | 4      | 6.67%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 54        | 98     | 93.1%   |
| NVMe | 4         | 4      | 6.9%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 42        | 70     | 75%     |
| 0.51-1.0   | 12        | 26     | 21.43%  |
| 1.01-2.0   | 2         | 2      | 3.57%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 21-50      | 17        | 26.15%  |
| 101-250    | 17        | 26.15%  |
| 251-500    | 9         | 13.85%  |
| 51-100     | 9         | 13.85%  |
| 1-20       | 8         | 12.31%  |
| 501-1000   | 4         | 6.15%   |
| 1001-2000  | 1         | 1.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 49        | 79.03%  |
| 21-50   | 8         | 12.9%   |
| 51-100  | 4         | 6.45%   |
| 251-500 | 1         | 1.61%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| WDC WDS200T2B0A 2TB           | 1         | 1      | 14.29%  |
| WDC WD6400BEVT-22A0RT0 640GB  | 1         | 1      | 14.29%  |
| Seagate ST9500420AS 500GB     | 1         | 2      | 14.29%  |
| Kingston SNS4151S316GD 16GB   | 1         | 1      | 14.29%  |
| Intel SSDSC2CW120A3 120GB     | 1         | 1      | 14.29%  |
| Hitachi HTS541612J9SA00 120GB | 1         | 1      | 14.29%  |
| A-DATA Technology SP550 480GB | 1         | 4      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 2         | 2      | 28.57%  |
| Seagate           | 1         | 2      | 14.29%  |
| Kingston          | 1         | 1      | 14.29%  |
| Intel             | 1         | 1      | 14.29%  |
| Hitachi           | 1         | 1      | 14.29%  |
| A-DATA Technology | 1         | 4      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 33.33%  |
| Seagate | 1         | 2      | 33.33%  |
| Hitachi | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 4         | 7      | 57.14%  |
| HDD  | 3         | 4      | 42.86%  |

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
| Works    | 50        | 87     | 81.97%  |
| Malfunc  | 7         | 11     | 11.48%  |
| Detected | 4         | 4      | 6.56%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 51        | 83.61%  |
| SanDisk               | 3         | 4.92%   |
| Samsung Electronics   | 2         | 3.28%   |
| AMD                   | 2         | 3.28%   |
| Realtek Semiconductor | 1         | 1.64%   |
| Phison Electronics    | 1         | 1.64%   |
| Nvidia                | 1         | 1.64%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 10        | 15.63%  |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 7         | 10.94%  |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 5         | 7.81%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 5         | 7.81%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 5         | 7.81%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 4         | 6.25%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 2         | 3.13%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 2         | 3.13%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 2         | 3.13%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 2         | 3.13%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 2         | 3.13%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 2         | 3.13%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 2         | 3.13%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 1         | 1.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 1         | 1.56%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 1.56%   |
| Phison E12 NVMe Controller                                                             | 1         | 1.56%   |
| Nvidia MCP79 AHCI Controller                                                           | 1         | 1.56%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 1         | 1.56%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 1         | 1.56%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 1         | 1.56%   |
| Intel 82801CAM IDE U100 Controller                                                     | 1         | 1.56%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.56%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.56%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 1         | 1.56%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 1         | 1.56%   |
| Unknown                                                                                | 1         | 1.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 48        | 76.19%  |
| NVMe | 7         | 11.11%  |
| IDE  | 6         | 9.52%   |
| RAID | 2         | 3.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 58        | 95.08%  |
| AMD     | 2         | 3.28%   |
| Unknown | 1         | 1.64%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz                             | 6         | 9.38%   |
| Intel Core i5-2520M CPU @ 2.50GHz                             | 4         | 6.25%   |
| Intel Core i5 CPU M 520 @ 2.40GHz                             | 3         | 4.69%   |
| Intel CPU Version                                             | 2         | 3.13%   |
| Intel Core i7-3630QM CPU @ 2.40GHz                            | 2         | 3.13%   |
| Intel Core i5-5300U CPU @ 2.30GHz                             | 2         | 3.13%   |
| Intel Core i5-3320M CPU @ 2.60GHz                             | 2         | 3.13%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz                   | 1         | 1.56%   |
| Intel Pentium 4 Mobile CPU 1.60GHz ("GenuineIntel" 686-class) | 1         | 1.56%   |
| Intel Pentium 4 Mobile CPU 1.60GHz                            | 1         | 1.56%   |
| Intel Genuine CPU T2300 @ 1.66GHz                             | 1         | 1.56%   |
| Intel CPU T2300 @ 1.66GHz ("GenuineIntel" 686-class)          | 1         | 1.56%   |
| Intel Core i7-8750H CPU @ 2.20GHz                             | 1         | 1.56%   |
| Intel Core i7-8650U CPU @ 1.90GHz                             | 1         | 1.56%   |
| Intel Core i7-7600U CPU @ 2.80GHz                             | 1         | 1.56%   |
| Intel Core i7-6600U CPU @ 2.60GHz                             | 1         | 1.56%   |
| Intel Core i7-5500U CPU @ 2.40GHz                             | 1         | 1.56%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz                            | 1         | 1.56%   |
| Intel Core i7-3520M CPU @ 2.90GHz                             | 1         | 1.56%   |
| Intel Core i7-10750H CPU @ 2.60GHz                            | 1         | 1.56%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz                            | 1         | 1.56%   |
| Intel Core i5-8265U CPU @ 1.60GHz                             | 1         | 1.56%   |
| Intel Core i5-8250U CPU @ 1.60GHz                             | 1         | 1.56%   |
| Intel Core i5-7200U CPU @ 2.50GHz                             | 1         | 1.56%   |
| Intel Core i5-6200U CPU @ 2.30GHz                             | 1         | 1.56%   |
| Intel Core i5-5200U CPU @ 2.20GHz                             | 1         | 1.56%   |
| Intel Core i5-4310U CPU @ 2.00GHz                             | 1         | 1.56%   |
| Intel Core i5-4300U CPU @ 1.90GHz                             | 1         | 1.56%   |
| Intel Core i5-4210U CPU @ 1.70GHz                             | 1         | 1.56%   |
| Intel Core i5 CPU M 540 @ 2.53GHz                             | 1         | 1.56%   |
| Intel Core i5 CPU M 430 @ 2.27GH                              | 1         | 1.56%   |
| Intel Core i3-7100U CPU @ 2.40GHz                             | 1         | 1.56%   |
| Intel Core i3-5020U CPU @ 2.20GHz                             | 1         | 1.56%   |
| Intel Core i3-5010U CPU @ 2.10GHz                             | 1         | 1.56%   |
| Intel Core i3-5005U CPU @ 2.00GHz                             | 1         | 1.56%   |
| Intel Core i3-4010U CPU @ 1.70GHz                             | 1         | 1.56%   |
| Intel Core i3-2310M CPU @ 2.10GHz                             | 1         | 1.56%   |
| Intel Core 2 Duo CPU T8100                                    | 1         | 1.56%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz                          | 1         | 1.56%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz                          | 1         | 1.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 27        | 43.55%  |
| Intel Core i7           | 11        | 17.74%  |
| Intel Core i3           | 6         | 9.68%   |
| Other                   | 4         | 6.45%   |
| Intel Core 2 Duo        | 3         | 4.84%   |
| Intel Celeron           | 3         | 4.84%   |
| Intel Atom              | 3         | 4.84%   |
| Intel Pentium Dual-Core | 1         | 1.61%   |
| Intel Pentium 4         | 1         | 1.61%   |
| Intel Genuine           | 1         | 1.61%   |
| AMD Ryzen 7             | 1         | 1.61%   |
| AMD E1                  | 1         | 1.61%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 42        | 68.85%  |
| 4       | 8         | 13.11%  |
| Unknown | 7         | 11.48%  |
| 6       | 2         | 3.28%   |
| 8       | 1         | 1.64%   |
| 1       | 1         | 1.64%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 59        | 92.19%  |
| Unknown | 4         | 6.25%   |
| 2       | 1         | 1.56%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 46        | 75.41%  |
| Unknown | 8         | 13.11%  |
| 1       | 7         | 11.48%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Skylake     | 8         | 12.7%   |
| KabyLake    | 7         | 11.11%  |
| Broadwell   | 7         | 11.11%  |
| IvyBridge   | 6         | 9.52%   |
| Haswell     | 6         | 9.52%   |
| SandyBridge | 5         | 7.94%   |
| Unknown     | 5         | 7.94%   |
| Westmere    | 4         | 6.35%   |
| Penryn      | 4         | 6.35%   |
| Bonnell     | 3         | 4.76%   |
| Zen+        | 1         | 1.59%   |
| P6          | 1         | 1.59%   |
| NetBurst    | 1         | 1.59%   |
| Nehalem     | 1         | 1.59%   |
| Jaguar      | 1         | 1.59%   |
| IceLake     | 1         | 1.59%   |
| Core        | 1         | 1.59%   |
| CometLake   | 1         | 1.59%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 51        | 78.46%  |
| Nvidia | 8         | 12.31%  |
| AMD    | 6         | 9.23%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                           | 8         | 11.59%  |
| Intel HD Graphics 5500                                                        | 7         | 10.14%  |
| Intel Haswell-ULT Integrated Graphics Controller                              | 5         | 7.25%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 5         | 7.25%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 5         | 7.25%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 3         | 4.35%   |
| Intel HD Graphics 620                                                         | 3         | 4.35%   |
| Intel Core Processor Integrated Graphics Controller                           | 3         | 4.35%   |
| Nvidia GK107M [GeForce GTX 660M]                                              | 2         | 2.9%    |
| Intel UHD Graphics 620                                                        | 2         | 2.9%    |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 2         | 2.9%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 2         | 2.9%    |
| Nvidia GT218M [NVS 3100M]                                                     | 1         | 1.45%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 1         | 1.45%   |
| Nvidia GK106M [GeForce GTX 765M]                                              | 1         | 1.45%   |
| Nvidia GF119M [GeForce GT 520M]                                               | 1         | 1.45%   |
| Nvidia G86M [GeForce 8400M GS]                                                | 1         | 1.45%   |
| Nvidia C79 [GeForce 9400M]                                                    | 1         | 1.45%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 1         | 1.45%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 1.45%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 1.45%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 1         | 1.45%   |
| Intel JasperLake [UHD Graphics]                                               | 1         | 1.45%   |
| Intel Iris Plus Graphics G7                                                   | 1         | 1.45%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 1         | 1.45%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 1         | 1.45%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller               | 1         | 1.45%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 1         | 1.45%   |
| AMD RV730/M96 [Mobility Radeon HD 4650/5165]                                  | 1         | 1.45%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                             | 1         | 1.45%   |
| AMD RV350/M10 / RV360/M11 [Mobility Radeon 9600 (PRO) / 9700]                 | 1         | 1.45%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 1         | 1.45%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 1         | 1.45%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                       | 1         | 1.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 41        | 67.21%  |
| 2 x Intel      | 6         | 9.84%   |
| 1 x AMD        | 6         | 9.84%   |
| 1 x Nvidia     | 4         | 6.56%   |
| Intel + Nvidia | 4         | 6.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 57        | 93.44%  |
| Proprietary | 3         | 4.92%   |
| Unknown     | 1         | 1.64%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 53        | 85.48%  |
| 0.01-0.5   | 3         | 4.84%   |
| 3.01-4.0   | 2         | 3.23%   |
| 1.01-2.0   | 2         | 3.23%   |
| 0.51-1.0   | 2         | 3.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 9         | 20.93%  |
| Chimei Innolux          | 9         | 20.93%  |
| AU Optronics            | 6         | 13.95%  |
| Samsung Electronics     | 5         | 11.63%  |
| BOE                     | 5         | 11.63%  |
| Chi Mei Optoelectronics | 3         | 6.98%   |
| Lenovo                  | 2         | 4.65%   |
| Goldstar                | 2         | 4.65%   |
| Toshiba                 | 1         | 2.33%   |
| Apple                   | 1         | 2.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch               | 2         | 4.65%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 310x170mm 13.9-inch          | 2         | 4.65%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch            | 2         | 4.65%   |
| Toshiba LCD Monitor LCD0905 1366x768 290x170mm 13.2-inch                  | 1         | 2.33%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 470x300mm 22.0-inch      | 1         | 2.33%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch      | 1         | 2.33%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 330x210mm 15.4-inch      | 1         | 2.33%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch      | 1         | 2.33%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 310x170mm 13.9-inch      | 1         | 2.33%   |
| LG Display LCD Monitor LGD0484 1366x768 340x190mm 15.3-inch               | 1         | 2.33%   |
| LG Display LCD Monitor LGD045E 1366x768 310x170mm 13.9-inch               | 1         | 2.33%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x170mm 13.9-inch               | 1         | 2.33%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch               | 1         | 2.33%   |
| LG Display LCD Monitor LGD021D 1600x900 380x210mm 17.1-inch               | 1         | 2.33%   |
| LG Display LCD Monitor LGD0215 1920x1080 350x190mm 15.7-inch              | 1         | 2.33%   |
| LG Display LCD Monitor LGD01E9 1920x1080 350x190mm 15.7-inch              | 1         | 2.33%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch                   | 1         | 2.33%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch                   | 1         | 2.33%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch                | 1         | 2.33%   |
| Goldstar L1920P GSM4A7B 1280x1024 380x300mm 19.1-inch                     | 1         | 2.33%   |
| Chimei Innolux LCD Monitor CMN15F4 1920x1080 340x190mm 15.3-inch          | 1         | 2.33%   |
| Chimei Innolux LCD Monitor CMN14B7 1366x768 310x170mm 13.9-inch           | 1         | 2.33%   |
| Chimei Innolux LCD Monitor CMN1492 1366x768 310x170mm 13.9-inch           | 1         | 2.33%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 310x170mm 13.9-inch           | 1         | 2.33%   |
| Chimei Innolux LCD Monitor CMN1367 1920x1080 290x170mm 13.2-inch          | 1         | 2.33%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 280x160mm 12.7-inch          | 1         | 2.33%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch           | 1         | 2.33%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 380x210mm 17.1-inch | 1         | 2.33%   |
| Chi Mei Optoelectronics LCD Monitor CMO1333 1366x768 290x160mm 13.0-inch  | 1         | 2.33%   |
| Chi Mei Optoelectronics LCD Monitor CMO1312 1280x800 290x180mm 13.4-inch  | 1         | 2.33%   |
| BOE LCD Monitor BOE08BC 2256x1504 280x190mm 13.3-inch                     | 1         | 2.33%   |
| BOE LCD Monitor BOE0817 1366x768 340x190mm 15.3-inch                      | 1         | 2.33%   |
| BOE LCD Monitor BOE07C9 1920x1080 300x170mm 13.6-inch                     | 1         | 2.33%   |
| BOE LCD Monitor BOE0742 1920x1080 310x170mm 13.9-inch                     | 1         | 2.33%   |
| BOE LCD Monitor BOE06C2 1366x768 340x190mm 15.3-inch                      | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO173D 1920x1080 310x170mm 13.9-inch            | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 310x170mm 13.9-inch            | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO10ED 1920x1080 340x190mm 15.3-inch            | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch             | 1         | 2.33%   |
| Apple Color LCD APP9C20 1280x854 320x220mm 15.3-inch                      | 1         | 2.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 15        | 34.88%  |
| 1366x768 (WXGA)    | 15        | 34.88%  |
| 1600x900 (HD+)     | 5         | 11.63%  |
| 1280x800 (WXGA)    | 3         | 6.98%   |
| 2560x1080          | 1         | 2.33%   |
| 2256x1504          | 1         | 2.33%   |
| 1680x1050 (WSXGA+) | 1         | 2.33%   |
| 1280x854           | 1         | 2.33%   |
| 1280x1024 (SXGA)   | 1         | 2.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 17        | 39.53%  |
| 15     | 12        | 27.91%  |
| 12     | 7         | 16.28%  |
| 17     | 2         | 4.65%   |
| 34     | 1         | 2.33%   |
| 22     | 1         | 2.33%   |
| 19     | 1         | 2.33%   |
| 14     | 1         | 2.33%   |
| 11     | 1         | 2.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 23        | 53.49%  |
| 201-300     | 15        | 34.88%  |
| 351-400     | 3         | 6.98%   |
| 701-800     | 1         | 2.33%   |
| 401-500     | 1         | 2.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 34        | 79.07%  |
| 16/10 | 5         | 11.63%  |
| 3/2   | 2         | 4.65%   |
| 5/4   | 1         | 2.33%   |
| 21/9  | 1         | 2.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 14        | 32.56%  |
| 61-70          | 7         | 16.28%  |
| 101-110        | 7         | 16.28%  |
| 91-100         | 5         | 11.63%  |
| 71-80          | 4         | 9.3%    |
| 121-130        | 2         | 4.65%   |
| 51-60          | 1         | 2.33%   |
| 351-500        | 1         | 2.33%   |
| 201-250        | 1         | 2.33%   |
| 151-200        | 1         | 2.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 19        | 44.19%  |
| 101-120 | 12        | 27.91%  |
| 161-240 | 6         | 13.95%  |
| 51-100  | 6         | 13.95%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 47        | 75.81%  |
| 0     | 14        | 22.58%  |
| 2     | 1         | 1.61%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 42        | 48.28%  |
| Realtek Semiconductor             | 17        | 19.54%  |
| Qualcomm Atheros                  | 15        | 17.24%  |
| Broadcom                          | 4         | 4.6%    |
| Sierra Wireless                   | 2         | 2.3%    |
| Ericsson Business Mobile Networks | 2         | 2.3%    |
| Ralink Technology                 | 1         | 1.15%   |
| Nvidia                            | 1         | 1.15%   |
| Marvell Technology Group          | 1         | 1.15%   |
| JMicron Technology                | 1         | 1.15%   |
| Apple                             | 1         | 1.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 8         | 6.67%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 8         | 6.67%   |
| Intel Wireless 8260                                                     | 7         | 5.83%   |
| Intel Ethernet Connection I219-LM                                       | 7         | 5.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 5.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 7         | 5.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 3.33%   |
| Intel 82577LM Gigabit Network Connection                                | 4         | 3.33%   |
| Intel Wireless 8265 / 8275                                              | 3         | 2.5%    |
| Intel Wireless 7265                                                     | 3         | 2.5%    |
| Intel Wireless 7260                                                     | 3         | 2.5%    |
| Intel Centrino Advanced-N 6200                                          | 3         | 2.5%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 1.67%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 1.67%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 2         | 1.67%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 2         | 1.67%   |
| Intel Ethernet Connection I218-LM                                       | 2         | 1.67%   |
| Intel Ethernet Connection (4) I219-LM                                   | 2         | 1.67%   |
| Intel Ethernet Connection (3) I218-LM                                   | 2         | 1.67%   |
| Sierra Wireless EM7455                                                  | 1         | 0.83%   |
| Sierra Wireless EM7305 Modem                                            | 1         | 0.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.83%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.83%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 1         | 0.83%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 0.83%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller               | 1         | 0.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 0.83%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 1         | 0.83%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 1         | 0.83%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 1         | 0.83%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.83%   |
| Nvidia MCP79 Ethernet                                                   | 1         | 0.83%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                 | 1         | 0.83%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 1         | 0.83%   |
| Intel Wireless-AC 9260                                                  | 1         | 0.83%   |
| Intel Wireless 3165                                                     | 1         | 0.83%   |
| Intel Wireless 3160                                                     | 1         | 0.83%   |
| Intel WiMAX Connection 2400m                                            | 1         | 0.83%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 1         | 0.83%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 40        | 67.8%   |
| Qualcomm Atheros      | 11        | 18.64%  |
| Broadcom              | 4         | 6.78%   |
| Realtek Semiconductor | 2         | 3.39%   |
| Sierra Wireless       | 1         | 1.69%   |
| Ralink Technology     | 1         | 1.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                                     | 7         | 11.67%  |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 11.67%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 6.67%   |
| Intel Wireless 8265 / 8275                                              | 3         | 5%      |
| Intel Wireless 7265                                                     | 3         | 5%      |
| Intel Wireless 7260                                                     | 3         | 5%      |
| Intel Centrino Advanced-N 6200                                          | 3         | 5%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 3.33%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 3.33%   |
| Sierra Wireless EM7455                                                  | 1         | 1.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.67%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 1.67%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 1.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 1.67%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 1         | 1.67%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.67%   |
| Intel Wireless-AC 9260                                                  | 1         | 1.67%   |
| Intel Wireless 3165                                                     | 1         | 1.67%   |
| Intel Wireless 3160                                                     | 1         | 1.67%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 1         | 1.67%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 1.67%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 1.67%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 1.67%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 1.67%   |
| Intel Centrino Wireless-N 2200                                          | 1         | 1.67%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 1.67%   |
| Intel Centrino Wireless-N 100                                           | 1         | 1.67%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                    | 1         | 1.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 1.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1         | 1.67%   |
| Broadcom BCM43225 802.11b/g/n                                           | 1         | 1.67%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 1         | 1.67%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 1         | 1.67%   |
| Broadcom BCM4306 802.11b/g Wireless LAN Controller                      | 1         | 1.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 28        | 50%     |
| Realtek Semiconductor    | 17        | 30.36%  |
| Qualcomm Atheros         | 7         | 12.5%   |
| Nvidia                   | 1         | 1.79%   |
| Marvell Technology Group | 1         | 1.79%   |
| JMicron Technology       | 1         | 1.79%   |
| Apple                    | 1         | 1.79%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8         | 14.29%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 14.29%  |
| Intel Ethernet Connection I219-LM                                 | 7         | 12.5%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 12.5%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 7.14%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 3.57%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 3.57%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 3.57%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 3.57%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 3.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.79%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.79%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.79%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 1.79%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.79%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 1.79%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.79%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.79%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 1.79%   |
| Intel 82580 Gigabit Network Connection                            | 1         | 1.79%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.79%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                   | 1         | 1.79%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 57        | 48.72%  |
| Ethernet | 56        | 47.86%  |
| Unknown  | 3         | 2.56%   |
| Modem    | 1         | 0.85%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 51        | 57.3%   |
| Ethernet | 38        | 42.7%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 52        | 85.25%  |
| 1     | 6         | 9.84%   |
| 3     | 2         | 3.28%   |
| 4     | 1         | 1.64%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 56        | 88.89%  |
| Yes  | 7         | 11.11%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 19        | 48.72%  |
| Broadcom                        | 4         | 10.26%  |
| Qualcomm Atheros Communications | 2         | 5.13%   |
| IMC Networks                    | 2         | 5.13%   |
| Foxconn / Hon Hai               | 2         | 5.13%   |
| Cambridge Silicon Radio         | 2         | 5.13%   |
| Alps Electric                   | 2         | 5.13%   |
| Toshiba                         | 1         | 2.56%   |
| Realtek Semiconductor           | 1         | 2.56%   |
| Lite-On Technology              | 1         | 2.56%   |
| Hewlett-Packard                 | 1         | 2.56%   |
| ASUSTek Computer                | 1         | 2.56%   |
| Apple                           | 1         | 2.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 14        | 35.9%   |
| Intel AX201 Bluetooth                                       | 3         | 7.69%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 3         | 7.69%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2         | 5.13%   |
| Alps Electric UGTZ4 Bluetooth                               | 2         | 5.13%   |
| Toshiba ASKEY Bluetooth Controller BTU1030                  | 1         | 2.56%   |
| Realtek  Bluetooth 4.0 Adapter                              | 1         | 2.56%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 2.56%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 2.56%   |
| Lite-On Broadcom Bluetooth 4.0 USB                          | 1         | 2.56%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 2.56%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 1         | 2.56%   |
| IMC Networks Bluetooth                                      | 1         | 2.56%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 1         | 2.56%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 2.56%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device    | 1         | 2.56%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 1         | 2.56%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 1         | 2.56%   |
| ASUS Broadcom Bluetooth 2.1                                 | 1         | 2.56%   |
| Apple Bluetooth Host Controller                             | 1         | 2.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 57        | 87.69%  |
| AMD    | 4         | 6.15%   |
| Nvidia | 3         | 4.62%   |
| XMOS   | 1         | 1.54%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 13        | 16.25%  |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 7         | 8.75%   |
| Intel Broadwell-U Audio Controller                                         | 7         | 8.75%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6         | 7.5%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 7.5%    |
| Intel 8 Series HD Audio Controller                                         | 5         | 6.25%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 6.25%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 5%      |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 5%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 2.5%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 2.5%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 2         | 2.5%    |
| XMOS retrieving string failed                                              | 1         | 1.25%   |
| XMOS iFi (by AMR) HD USB Audio                                             | 1         | 1.25%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 1.25%   |
| Nvidia High Definition Audio Controller                                    | 1         | 1.25%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 1.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.25%   |
| Intel Jasper Lake HD Audio                                                 | 1         | 1.25%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1.25%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.25%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.25%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.25%   |
| Intel 82801CA/CAM AC'97 Audio Controller                                   | 1         | 1.25%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 1.25%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 1.25%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.25%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.25%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1         | 1.25%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 17        | 28.81%  |
| SK hynix            | 16        | 27.12%  |
| Unknown             | 9         | 15.25%  |
| Kingston            | 6         | 10.17%  |
| Micron Technology   | 3         | 5.08%   |
| Corsair             | 3         | 5.08%   |
| A-DATA Technology   | 2         | 3.39%   |
| Ramaxel Technology  | 1         | 1.69%   |
| Nanya Technology    | 1         | 1.69%   |
| Unknown             | 1         | 1.69%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s           | 3         | 4.92%   |
| Unknown RAM Module 1GB SODIMM DDR2                              | 2         | 3.28%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 2         | 3.28%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s         | 2         | 3.28%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s           | 2         | 3.28%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s           | 2         | 3.28%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                     | 1         | 1.64%   |
| Unknown RAM Module 512MB SODIMM SDRAM                           | 1         | 1.64%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                     | 1         | 1.64%   |
| Unknown RAM Module 4096MB SODIMM DDR2                           | 1         | 1.64%   |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s                     | 1         | 1.64%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                          | 1         | 1.64%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                   | 1         | 1.64%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.64%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s          | 1         | 1.64%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 1         | 1.64%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s       | 1         | 1.64%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.64%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.64%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s          | 1         | 1.64%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s          | 1         | 1.64%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s          | 1         | 1.64%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB Row Of Chips DDR4 2400MT/s | 1         | 1.64%   |
| SK hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s  | 1         | 1.64%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB SODIMM LPDDR3 1867MT/s          | 1         | 1.64%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB Chip LPDDR3 1867MT/s            | 1         | 1.64%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s           | 1         | 1.64%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM 1067MT/s                | 1         | 1.64%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.64%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.64%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.64%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.64%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s           | 1         | 1.64%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s           | 1         | 1.64%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s           | 1         | 1.64%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s           | 1         | 1.64%   |
| Samsung RAM K4UBE3D4AA-MGCH 8GB Row Of Chips LPDDR4 3200MT/s    | 1         | 1.64%   |
| Ramaxel RAM RMT3020EF48E8W1333 2GB SODIMM DDR3 1334MT/s         | 1         | 1.64%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s            | 1         | 1.64%   |
| Micron RAM MT36KSF2G72PZ-1G6E 8GB SODIMM DDR3 1600MT/s          | 1         | 1.64%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 33        | 60%     |
| DDR4   | 12        | 21.82%  |
| DDR2   | 4         | 7.27%   |
| SDRAM  | 3         | 5.45%   |
| LPDDR4 | 2         | 3.64%   |
| LPDDR3 | 1         | 1.82%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 51        | 91.07%  |
| Row Of Chips | 3         | 5.36%   |
| Chip         | 2         | 3.57%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 24        | 42.86%  |
| 8192  | 14        | 25%     |
| 2048  | 10        | 17.86%  |
| 16384 | 5         | 8.93%   |
| 1024  | 2         | 3.57%   |
| 512   | 1         | 1.79%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 17        | 30.91%  |
| 2400    | 6         | 10.91%  |
| 1333    | 6         | 10.91%  |
| Unknown | 6         | 10.91%  |
| 2667    | 4         | 7.27%   |
| 1334    | 4         | 7.27%   |
| 1067    | 4         | 7.27%   |
| 3200    | 2         | 3.64%   |
| 2133    | 2         | 3.64%   |
| 4267    | 1         | 1.82%   |
| 1867    | 1         | 1.82%   |
| 667     | 1         | 1.82%   |
| 533     | 1         | 1.82%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Samsung ML-1610 Mono Laser Printer | 1         | 100%    |

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


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 15        | 38.46%  |
| Acer                          | 6         | 15.38%  |
| Microdia                      | 4         | 10.26%  |
| Realtek Semiconductor         | 3         | 7.69%   |
| Lite-On Technology            | 3         | 7.69%   |
| IMC Networks                  | 3         | 7.69%   |
| Sunplus Innovation Technology | 2         | 5.13%   |
| Syntek                        | 1         | 2.56%   |
| Quanta                        | 1         | 2.56%   |
| Lenovo                        | 1         | 2.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Acer Integrated Camera                   | 4         | 10.26%  |
| Lite-On Integrated Camera                | 3         | 7.69%   |
| Chicony integrated camera                | 3         | 7.69%   |
| Chicony HD Webcam                        | 3         | 7.69%   |
| Syntek Lenovo EasyCamera                 | 1         | 2.56%   |
| Sunplus Laptop_Integrated_Webcam_FHD     | 1         | 2.56%   |
| Sunplus ASUS Webcam                      | 1         | 2.56%   |
| Realtek Realtek USB2.0 PC Camera         | 1         | 2.56%   |
| Realtek Integrated Webcam HD             | 1         | 2.56%   |
| Realtek Integrated Webcam                | 1         | 2.56%   |
| Quanta USB2.0 HD UVC WebCam              | 1         | 2.56%   |
| Microdia Sonix USB 2.0 Camera            | 1         | 2.56%   |
| Microdia Laptop_Integrated_Webcam_2M     | 1         | 2.56%   |
| Microdia Integrated Webcam HD            | 1         | 2.56%   |
| Microdia Integrated Webcam               | 1         | 2.56%   |
| Lenovo Integrated Webcam [R5U877]        | 1         | 2.56%   |
| IMC Networks UVC VGA Webcam              | 1         | 2.56%   |
| IMC Networks Integrated Webcam           | 1         | 2.56%   |
| IMC Networks Integrated Camera           | 1         | 2.56%   |
| Chicony WebCam                           | 1         | 2.56%   |
| Chicony VGA 24fps UVC Webcam             | 1         | 2.56%   |
| Chicony TOSHIBA Web Camera - FHD         | 1         | 2.56%   |
| Chicony Sonix ST50220 USB Video Camera   | 1         | 2.56%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 1         | 2.56%   |
| Chicony Integrated Camera [ThinkPad]     | 1         | 2.56%   |
| Chicony HP HD Camera                     | 1         | 2.56%   |
| Chicony FJ Camera                        | 1         | 2.56%   |
| Chicony 2.0M UVC Webcam / CNF7129        | 1         | 2.56%   |
| Acer ThinkPad P50 Integrated Camera      | 1         | 2.56%   |
| Acer SunplusIT Integrated Camera         | 1         | 2.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 6         | 46.15%  |
| Upek                  | 2         | 15.38%  |
| LighTuning Technology | 2         | 15.38%  |
| AuthenTec             | 2         | 15.38%  |
| Synaptics             | 1         | 7.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 3         | 23.08%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 15.38%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 7.69%   |
| Validity Sensors VFS Fingerprint sensor                | 1         | 7.69%   |
| Validity Sensors Synaptics WBDI                        | 1         | 7.69%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 7.69%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 7.69%   |
| LighTuning EgisTec EH575                               | 1         | 7.69%   |
| AuthenTec AuthenTec Inc. AES2660                       | 1         | 7.69%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 7.69%   |

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
| 1     | 31        | 49.21%  |
| 2     | 13        | 20.63%  |
| 3     | 11        | 17.46%  |
| 0     | 4         | 6.35%   |
| 4     | 3         | 4.76%   |
| 5     | 1         | 1.59%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 47        | 47.47%  |
| Bluetooth                | 14        | 14.14%  |
| Fingerprint reader       | 9         | 9.09%   |
| Card reader              | 9         | 9.09%   |
| Firewire controller      | 8         | 8.08%   |
| Net/wireless             | 4         | 4.04%   |
| Storage                  | 2         | 2.02%   |
| Graphics card            | 2         | 2.02%   |
| Storage/ata              | 1         | 1.01%   |
| Sound                    | 1         | 1.01%   |
| Network                  | 1         | 1.01%   |
| Net/ethernet             | 1         | 1.01%   |

