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

Total: 119

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Gigabyte      | GB-BSi3A-6100               | [e7ef795b9b](https://bsd-hardware.info/?probe=e7ef795b9b) | Feb 19, 2023 |
| Gigabyte      | GB-BSi3A-6100               | [cd2273037f](https://bsd-hardware.info/?probe=cd2273037f) | Feb 19, 2023 |
| Unknown       | Unknown                     | [4cae5c6bb7](https://bsd-hardware.info/?probe=4cae5c6bb7) | Feb 01, 2023 |
| HP            | 2000                        | [7f29899321](https://bsd-hardware.info/?probe=7f29899321) | Jan 09, 2023 |
| Dell          | XPS 13 9310                 | [e56cfbdedc](https://bsd-hardware.info/?probe=e56cfbdedc) | Jan 08, 2023 |
| Dell          | XPS 13 9310                 | [db483e3d46](https://bsd-hardware.info/?probe=db483e3d46) | Jan 08, 2023 |
| Lenovo        | ThinkPad T400 2764CTO       | [26f8459193](https://bsd-hardware.info/?probe=26f8459193) | Jan 06, 2023 |
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
| OpenBSD 7.2         | 15        | 14.71%  |
| OpenBSD 7.1         | 10        | 9.8%    |
| OpenBSD 7.0         | 9         | 8.82%   |
| OpenBSD 6.9         | 9         | 8.82%   |
| OpenBSD 6.8         | 7         | 6.86%   |
| helloSystem 0.4.0   | 4         | 3.92%   |
| helloSystem 0.8.0   | 3         | 2.94%   |
| helloSystem 0.7.0   | 3         | 2.94%   |
| FreeBSD 13.0-p5     | 3         | 2.94%   |
| helloSystem 0.5.0   | 2         | 1.96%   |
| FreeBSD 13.1-p2     | 2         | 1.96%   |
| FreeBSD 13.1        | 2         | 1.96%   |
| FreeBSD 13.0        | 2         | 1.96%   |
| FreeBSD 12.2        | 2         | 1.96%   |
| OPNsense 23.1       | 1         | 0.98%   |
| OPNsense 22.7.6     | 1         | 0.98%   |
| OPNsense 22.7.5     | 1         | 0.98%   |
| OPNsense 22.7.4     | 1         | 0.98%   |
| OPNsense 22.7       | 1         | 0.98%   |
| OPNsense 22.1.1     | 1         | 0.98%   |
| OPNsense 21.1.5     | 1         | 0.98%   |
| OPNsense 21.1.4     | 1         | 0.98%   |
| OPNsense 21.1       | 1         | 0.98%   |
| NetBSD 8.99.51      | 1         | 0.98%   |
| helloSystem 0.6.0   | 1         | 0.98%   |
| GhostBSD 22.06.18   | 1         | 0.98%   |
| GhostBSD 21.08.27   | 1         | 0.98%   |
| FreeBSD 13.1-STABLE | 1         | 0.98%   |
| FreeBSD 13.1-p5     | 1         | 0.98%   |
| FreeBSD 13.1-p4     | 1         | 0.98%   |
| FreeBSD 13.0-p3     | 1         | 0.98%   |
| FreeBSD 13.0-p2     | 1         | 0.98%   |
| FreeBSD 12.1-STABLE | 1         | 0.98%   |
| FreeBSD 12.1-p8     | 1         | 0.98%   |
| FreeBSD 12.1-p5     | 1         | 0.98%   |
| FreeBSD 12.1-p10    | 1         | 0.98%   |
| FreeBSD 12.1        | 1         | 0.98%   |
| FreeBSD 12.0-p3     | 1         | 0.98%   |
| FreeBSD 12.0-p13    | 1         | 0.98%   |
| FreeBSD 11.4-p8     | 1         | 0.98%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 24        | 36.92%  |
| OpenBSD     | 19        | 29.23%  |
| helloSystem | 12        | 18.46%  |
| OPNsense    | 7         | 10.77%  |
| GhostBSD    | 2         | 3.08%   |
| NetBSD      | 1         | 1.54%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| amd64  | 60        | 92.31%  |
| i386   | 4         | 6.15%   |
| macppc | 1         | 1.54%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 26        | 35.14%  |
| fvwm         | 12        | 16.22%  |
| Console      | 10        | 13.51%  |
| XFCE         | 9         | 12.16%  |
| TWM          | 4         | 5.41%   |
| Openbox      | 2         | 2.7%    |
| KDE5         | 2         | 2.7%    |
| i3           | 2         | 2.7%    |
| GNOME        | 2         | 2.7%    |
| MATE         | 1         | 1.35%   |
| LXQt         | 1         | 1.35%   |
| Lumina       | 1         | 1.35%   |
| Fluxbox      | 1         | 1.35%   |
| Cinnamon     | 1         | 1.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 55        | 84.62%  |
| Console | 10        | 15.38%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 37        | 56.06%  |
| SLiM    | 13        | 19.7%   |
| XDM     | 7         | 10.61%  |
| LightDM | 4         | 6.06%   |
| SDDM    | 3         | 4.55%   |
| GDM     | 2         | 3.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 36        | 55.38%  |
| en_US   | 13        | 20%     |
| C       | 7         | 10.77%  |
| en_CA   | 4         | 6.15%   |
| fr_FR   | 2         | 3.08%   |
| fr_CA   | 1         | 1.54%   |
| en_NL   | 1         | 1.54%   |
| en      | 1         | 1.54%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 43        | 65.15%  |
| BIOS | 23        | 34.85%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 25        | 37.88%  |
| Ufs    | 19        | 28.79%  |
| Ffs    | 19        | 28.79%  |
| Cd9660 | 3         | 4.55%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 50        | 76.92%  |
| MBR     | 13        | 20%     |
| Unknown | 2         | 3.08%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 22        | 33.85%  |
| Dell                           | 8         | 12.31%  |
| Hewlett-Packard                | 5         | 7.69%   |
| ASUSTek Computer               | 5         | 7.69%   |
| Toshiba                        | 3         | 4.62%   |
| Panasonic                      | 3         | 4.62%   |
| Intel                          | 3         | 4.62%   |
| Acer                           | 3         | 4.62%   |
| Matsushita Electric Industrial | 2         | 3.08%   |
| Gigabyte Technology            | 2         | 3.08%   |
| Apple                          | 2         | 3.08%   |
| Unknown                        | 2         | 3.08%   |
| MSI                            | 1         | 1.54%   |
| LG Electronics                 | 1         | 1.54%   |
| Google                         | 1         | 1.54%   |
| Fujitsu                        | 1         | 1.54%   |
| Alienware                      | 1         | 1.54%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel H81U                                  | 3         | 4.62%   |
| Unknown                                     | 2         | 3.08%   |
| Toshiba TECRA Z40-B                         | 1         | 1.54%   |
| Toshiba Satellite U500                      | 1         | 1.54%   |
| Toshiba Satellite Pro T130                  | 1         | 1.54%   |
| Panasonic CF-54-1                           | 1         | 1.54%   |
| Panasonic CF-53AAGHYDM                      | 1         | 1.54%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 1.54%   |
| MSI GL65 Leopard 10SFSK                     | 1         | 1.54%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 1.54%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 1.54%   |
| LG E500-GP01A9                              | 1         | 1.54%   |
| Lenovo ThinkPad X280 20KF001UUS             | 1         | 1.54%   |
| Lenovo ThinkPad X270 W10DG 20K5S0TT1N       | 1         | 1.54%   |
| Lenovo ThinkPad X270 W10DG 20K5S0PY04       | 1         | 1.54%   |
| Lenovo ThinkPad X270 20HNCTO1WW             | 1         | 1.54%   |
| Lenovo ThinkPad X260 20F5S2GM00             | 1         | 1.54%   |
| Lenovo ThinkPad X250 20CL001GUS             | 1         | 1.54%   |
| Lenovo ThinkPad X230 2325T4T                | 1         | 1.54%   |
| Lenovo ThinkPad X220 429043U                | 1         | 1.54%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS13H00    | 1         | 1.54%   |
| Lenovo ThinkPad T510 4313CTO                | 1         | 1.54%   |
| Lenovo ThinkPad T490 20N3S8PB00             | 1         | 1.54%   |
| Lenovo ThinkPad T460 20FMS1BC01             | 1         | 1.54%   |
| Lenovo ThinkPad T460 20FMS10N00             | 1         | 1.54%   |
| Lenovo ThinkPad T440 20B7S0A800             | 1         | 1.54%   |
| Lenovo ThinkPad T430 2347GZU                | 1         | 1.54%   |
| Lenovo ThinkPad T420s 41742BU               | 1         | 1.54%   |
| Lenovo ThinkPad T420 4180B39                | 1         | 1.54%   |
| Lenovo ThinkPad T410 2537N24                | 1         | 1.54%   |
| Lenovo ThinkPad T410 253722U                | 1         | 1.54%   |
| Lenovo ThinkPad T400 2764CTO                | 1         | 1.54%   |
| Lenovo ThinkPad E495 20NE0001US             | 1         | 1.54%   |
| Lenovo IdeaPad Y580 20132                   | 1         | 1.54%   |
| HP Pavilion dv6500                          | 1         | 1.54%   |
| HP Notebook                                 | 1         | 1.54%   |
| HP EliteBook 840 G3                         | 1         | 1.54%   |
| HP Compaq Mini 110c-1100                    | 1         | 1.54%   |
| HP 2000                                     | 1         | 1.54%   |
| Google Peppy                                | 1         | 1.54%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad                             | 21        | 32.31%  |
| Dell Inspiron                               | 4         | 6.15%   |
| Intel H81U                                  | 3         | 4.62%   |
| Toshiba Satellite                           | 2         | 3.08%   |
| Dell Latitude                               | 2         | 3.08%   |
| Acer Swift                                  | 2         | 3.08%   |
| Unknown                                     | 2         | 3.08%   |
| Toshiba TECRA                               | 1         | 1.54%   |
| Panasonic CF-54-1                           | 1         | 1.54%   |
| Panasonic CF-53AAGHYDM                      | 1         | 1.54%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 1.54%   |
| MSI GL65                                    | 1         | 1.54%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 1.54%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 1.54%   |
| LG E500-GP01A9                              | 1         | 1.54%   |
| Lenovo IdeaPad                              | 1         | 1.54%   |
| HP Pavilion                                 | 1         | 1.54%   |
| HP Notebook                                 | 1         | 1.54%   |
| HP EliteBook                                | 1         | 1.54%   |
| HP Compaq                                   | 1         | 1.54%   |
| HP 2000                                     | 1         | 1.54%   |
| Google Peppy                                | 1         | 1.54%   |
| Gigabyte MMLP3AP-00                         | 1         | 1.54%   |
| Gigabyte GB-BSi3A-6100                      | 1         | 1.54%   |
| Fujitsu LIFEBOOK                            | 1         | 1.54%   |
| Dell XPS                                    | 1         | 1.54%   |
| Dell Studio                                 | 1         | 1.54%   |
| ASUS U31SD                                  | 1         | 1.54%   |
| ASUS TUF                                    | 1         | 1.54%   |
| ASUS K52JK                                  | 1         | 1.54%   |
| ASUS G75VW                                  | 1         | 1.54%   |
| ASUS 1000HE                                 | 1         | 1.54%   |
| Apple PowerBook5                            | 1         | 1.54%   |
| Apple MacBookPro5                           | 1         | 1.54%   |
| Alienware 14                                | 1         | 1.54%   |
| Acer AOD270                                 | 1         | 1.54%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 8         | 12.31%  |
| 2010    | 8         | 12.31%  |
| 2011    | 7         | 10.77%  |
| 2016    | 5         | 7.69%   |
| 2015    | 5         | 7.69%   |
| 2018    | 4         | 6.15%   |
| 2014    | 4         | 6.15%   |
| 2012    | 4         | 6.15%   |
| 2009    | 4         | 6.15%   |
| 2021    | 3         | 4.62%   |
| 2017    | 3         | 4.62%   |
| 2022    | 2         | 3.08%   |
| 2020    | 2         | 3.08%   |
| 2013    | 2         | 3.08%   |
| 2008    | 1         | 1.54%   |
| 2006    | 1         | 1.54%   |
| 2002    | 1         | 1.54%   |
| Unknown | 1         | 1.54%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 65        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 64        | 98.46%  |
| Yes  | 1         | 1.54%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 27        | 41.54%  |
| 4.01-8.0   | 14        | 21.54%  |
| 16.01-24.0 | 11        | 16.92%  |
| 3.01-4.0   | 5         | 7.69%   |
| 2.01-3.0   | 4         | 6.15%   |
| 32.01-64.0 | 2         | 3.08%   |
| 1.01-2.0   | 1         | 1.54%   |
| 0.51-1.0   | 1         | 1.54%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 45        | 68.18%  |
| 0.51-1.0 | 15        | 22.73%  |
| 1.01-2.0 | 2         | 3.03%   |
| 0        | 2         | 3.03%   |
| 3.01-4.0 | 1         | 1.52%   |
| Unknown  | 1         | 1.52%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 53        | 80.3%   |
| 2      | 9         | 13.64%  |
| 0      | 4         | 6.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 51        | 78.46%  |
| Yes       | 14        | 21.54%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 59        | 90.77%  |
| No        | 6         | 9.23%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 60        | 92.31%  |
| No        | 5         | 7.69%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 65.15%  |
| No        | 23        | 34.85%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Canada  | 65        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Montreal         | 18        | 21.95%  |
| Saint-Laurent    | 9         | 10.98%  |
| Vancouver        | 6         | 7.32%   |
| QuГ©bec        | 5         | 6.1%    |
| Toronto          | 4         | 4.88%   |
| Ottawa           | 3         | 3.66%   |
| Kingsburg        | 3         | 3.66%   |
| Calgary          | 3         | 3.66%   |
| Victoria         | 2         | 2.44%   |
| Stratford        | 2         | 2.44%   |
| Sainte-Julie     | 2         | 2.44%   |
| Peterborough     | 2         | 2.44%   |
| Langley          | 2         | 2.44%   |
| Winnipeg         | 1         | 1.22%   |
| Vaudreuil-Dorion | 1         | 1.22%   |
| Surrey           | 1         | 1.22%   |
| Sechelt          | 1         | 1.22%   |
| Saskatoon        | 1         | 1.22%   |
| Saint-Zotique    | 1         | 1.22%   |
| Québec          | 1         | 1.22%   |
| North York       | 1         | 1.22%   |
| Niagara Falls    | 1         | 1.22%   |
| Nepean           | 1         | 1.22%   |
| Mississauga      | 1         | 1.22%   |
| Mission          | 1         | 1.22%   |
| Maple Ridge      | 1         | 1.22%   |
| Lloydminster     | 1         | 1.22%   |
| Laval            | 1         | 1.22%   |
| Lamont           | 1         | 1.22%   |
| Hamilton         | 1         | 1.22%   |
| Halifax          | 1         | 1.22%   |
| Guelph           | 1         | 1.22%   |
| Gatineau         | 1         | 1.22%   |
| Beloeil          | 1         | 1.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 16        | 40     | 23.88%  |
| Samsung Electronics | 7         | 10     | 10.45%  |
| Kingston            | 7         | 8      | 10.45%  |
| Toshiba             | 6         | 7      | 8.96%   |
| Seagate             | 5         | 9      | 7.46%   |
| Hitachi             | 4         | 7      | 5.97%   |
| A-DATA Technology   | 3         | 6      | 4.48%   |
| NVMe                | 2         | 2      | 2.99%   |
| Lexar               | 2         | 3      | 2.99%   |
| Intel               | 2         | 2      | 2.99%   |
| Crucial             | 2         | 2      | 2.99%   |
| Transcend           | 1         | 1      | 1.49%   |
| SK hynix            | 1         | 1      | 1.49%   |
| SanDisk             | 1         | 1      | 1.49%   |
| Phison              | 1         | 1      | 1.49%   |
| OCZ                 | 1         | 1      | 1.49%   |
| Micron Technology   | 1         | 1      | 1.49%   |
| Kston               | 1         | 2      | 1.49%   |
| KIOXIA              | 1         | 1      | 1.49%   |
| KingDian            | 1         | 1      | 1.49%   |
| Hewlett-Packard     | 1         | 1      | 1.49%   |
| Fujitsu             | 1         | 1      | 1.49%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB          | 3         | 4.35%   |
| WDC WDS500G2B0A-00SM50 500GB         | 2         | 2.9%    |
| WDC WDS500G2B0A 500GB                | 1         | 1.45%   |
| WDC WDS200T2B0A 2TB                  | 1         | 1.45%   |
| WDC WD7500BPKX-75HPJT0 752GB         | 1         | 1.45%   |
| WDC WD7500BPKX-00HPJT0 752GB         | 1         | 1.45%   |
| WDC WD7500BPKT-75PK4T0 752GB         | 1         | 1.45%   |
| WDC WD7500BPKT-00PK4T0 752GB         | 1         | 1.45%   |
| WDC WD6400BEVT-22A0RT0 640GB         | 1         | 1.45%   |
| WDC WD5000LPLX-00ZNTT0 500GB         | 1         | 1.45%   |
| WDC WD3200LPVX-60V0TT0 320GB         | 1         | 1.45%   |
| WDC WD3200BEVE-00A0HT0 320GB         | 1         | 1.45%   |
| WDC WD10JPVX-75JC3T0 1TB             | 1         | 1.45%   |
| WDC WD10JPVT-00A1YT0 1TB             | 1         | 1.45%   |
| WDC WD10JPLX-00MBPT0 1TB             | 1         | 1.45%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB   | 1         | 1.45%   |
| WDC PC SN530 SDBPNPZ-256G-1014 256GB | 1         | 1.45%   |
| Transcend TSA 240GB                  | 1         | 1.45%   |
| Toshiba THNSNJ128GCSU 128GB          | 1         | 1.45%   |
| Toshiba MQ04ABF100 1TB               | 1         | 1.45%   |
| Toshiba MQ01ABF032 320GB             | 1         | 1.45%   |
| Toshiba MK8025GAS 80GB               | 1         | 1.45%   |
| Toshiba MK5061GSYN 500GB             | 1         | 1.45%   |
| Toshiba MK3259GSXP 320GB             | 1         | 1.45%   |
| SK hynix SC308 SATA 256GB            | 1         | 1.45%   |
| Seagate ST9500420AS 500GB            | 1         | 1.45%   |
| Seagate ST9160821A 160GB             | 1         | 1.45%   |
| Seagate ST500LT032-1E9142 500GB      | 1         | 1.45%   |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 1         | 1.45%   |
| Seagate ST1000LM035-1RK172 1TB       | 1         | 1.45%   |
| SanDisk SSD U100 16GB                | 1         | 1.45%   |
| Samsung SSD 860 EVO M.2 1TB          | 1         | 1.45%   |
| Samsung SSD 860 EVO 500GB            | 1         | 1.45%   |
| Samsung SSD 860 EVO 1TB              | 1         | 1.45%   |
| Samsung SSD 850 PRO 256GB            | 1         | 1.45%   |
| Samsung MZ7TE128HMGR-000L1 128GB     | 1         | 1.45%   |
| Samsung MZ7TD128HAFV-000L1 128GB     | 1         | 1.45%   |
| Samsung MZ7PC128HAFU-000L1 128GB     | 1         | 1.45%   |
| Phison PCIe SSD 512GB                | 1         | 1.45%   |
| OCZ VERTEX3 120GB                    | 1         | 1.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 11        | 34     | 37.93%  |
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
| Samsung Electronics | 7         | 10     | 20.59%  |
| Kingston            | 7         | 7      | 20.59%  |
| WDC                 | 4         | 4      | 11.76%  |
| Intel               | 2         | 2      | 5.88%   |
| Crucial             | 2         | 2      | 5.88%   |
| A-DATA Technology   | 2         | 5      | 5.88%   |
| Transcend           | 1         | 1      | 2.94%   |
| Toshiba             | 1         | 1      | 2.94%   |
| SK hynix            | 1         | 1      | 2.94%   |
| SanDisk             | 1         | 1      | 2.94%   |
| OCZ                 | 1         | 1      | 2.94%   |
| Micron Technology   | 1         | 1      | 2.94%   |
| Lexar               | 1         | 2      | 2.94%   |
| Kston               | 1         | 2      | 2.94%   |
| KingDian            | 1         | 1      | 2.94%   |
| Hewlett-Packard     | 1         | 1      | 2.94%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 31        | 42     | 47.69%  |
| HDD  | 28        | 60     | 43.08%  |
| NVMe | 6         | 6      | 9.23%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 57        | 102    | 90.48%  |
| NVMe | 6         | 6      | 9.52%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 45        | 74     | 76.27%  |
| 0.51-1.0   | 12        | 26     | 20.34%  |
| 1.01-2.0   | 2         | 2      | 3.39%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 18        | 25.71%  |
| 21-50      | 17        | 24.29%  |
| 251-500    | 10        | 14.29%  |
| 1-20       | 10        | 14.29%  |
| 51-100     | 10        | 14.29%  |
| 501-1000   | 4         | 5.71%   |
| 1001-2000  | 1         | 1.43%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 53        | 80.3%   |
| 21-50   | 8         | 12.12%  |
| 51-100  | 4         | 6.06%   |
| 251-500 | 1         | 1.52%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| WDC WDS200T2B0A 2TB           | 1         | 1      | 12.5%   |
| WDC WD6400BEVT-22A0RT0 640GB  | 1         | 1      | 12.5%   |
| Seagate ST9500420AS 500GB     | 1         | 2      | 12.5%   |
| Kingston SUV400S37240G 240GB  | 1         | 1      | 12.5%   |
| Kingston SNS4151S316GD 16GB   | 1         | 1      | 12.5%   |
| Intel SSDSC2CW120A3 120GB     | 1         | 1      | 12.5%   |
| Hitachi HTS541612J9SA00 120GB | 1         | 1      | 12.5%   |
| A-DATA Technology SP550 480GB | 1         | 4      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 2         | 2      | 25%     |
| Kingston          | 2         | 2      | 25%     |
| Seagate           | 1         | 2      | 12.5%   |
| Intel             | 1         | 1      | 12.5%   |
| Hitachi           | 1         | 1      | 12.5%   |
| A-DATA Technology | 1         | 4      | 12.5%   |

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
| SSD  | 5         | 8      | 62.5%   |
| HDD  | 3         | 4      | 37.5%   |

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
| Works    | 54        | 92     | 81.82%  |
| Malfunc  | 8         | 12     | 12.12%  |
| Detected | 4         | 4      | 6.06%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 54        | 81.82%  |
| SanDisk                     | 3         | 4.55%   |
| Samsung Electronics         | 2         | 3.03%   |
| AMD                         | 2         | 3.03%   |
| Toshiba                     | 1         | 1.52%   |
| Realtek Semiconductor       | 1         | 1.52%   |
| Phison Electronics          | 1         | 1.52%   |
| Nvidia                      | 1         | 1.52%   |
| Kingston Technology Company | 1         | 1.52%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 11        | 15.71%  |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 7         | 10%     |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 5         | 7.14%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 5         | 7.14%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 5         | 7.14%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 4         | 5.71%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 4.29%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 2         | 2.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 2         | 2.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 2         | 2.86%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 2         | 2.86%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 2         | 2.86%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 2         | 2.86%   |
| Toshiba XG6 NVMe SSD Controller                                                        | 1         | 1.43%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 1         | 1.43%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 1         | 1.43%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 1.43%   |
| Phison E12 NVMe Controller                                                             | 1         | 1.43%   |
| Nvidia MCP79 AHCI Controller                                                           | 1         | 1.43%   |
| Kingston Company A2000 NVMe SSD                                                        | 1         | 1.43%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 1         | 1.43%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 1         | 1.43%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 1         | 1.43%   |
| Intel 82801CAM IDE U100 Controller                                                     | 1         | 1.43%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 1         | 1.43%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 1         | 1.43%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.43%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.43%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 1         | 1.43%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 1         | 1.43%   |
| Unknown                                                                                | 1         | 1.43%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 50        | 73.53%  |
| NVMe | 9         | 13.24%  |
| IDE  | 7         | 10.29%  |
| RAID | 2         | 2.94%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 62        | 95.38%  |
| AMD     | 2         | 3.08%   |
| Unknown | 1         | 1.54%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz                             | 6         | 8.82%   |
| Intel Core i5-2520M CPU @ 2.50GHz                             | 4         | 5.88%   |
| Intel Core i5 CPU M 520 @ 2.40GHz                             | 3         | 4.41%   |
| Intel CPU Version                                             | 2         | 2.94%   |
| Intel Core i7-3630QM CPU @ 2.40GHz                            | 2         | 2.94%   |
| Intel Core i5-5300U CPU @ 2.30GHz                             | 2         | 2.94%   |
| Intel Core i5-3320M CPU @ 2.60GHz                             | 2         | 2.94%   |
| Intel Celeron CPU 1037U @ 1.80GHz                             | 2         | 2.94%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz                   | 1         | 1.47%   |
| Intel Pentium 4 Mobile CPU 1.60GHz ("GenuineIntel" 686-class) | 1         | 1.47%   |
| Intel Pentium 4 Mobile CPU 1.60GHz                            | 1         | 1.47%   |
| Intel Genuine CPU T2300 @ 1.66GHz                             | 1         | 1.47%   |
| Intel CPU T2300 @ 1.66GHz ("GenuineIntel" 686-class)          | 1         | 1.47%   |
| Intel Core i7-8750H CPU @ 2.20GHz                             | 1         | 1.47%   |
| Intel Core i7-8650U CPU @ 1.90GHz                             | 1         | 1.47%   |
| Intel Core i7-7600U CPU @ 2.80GHz                             | 1         | 1.47%   |
| Intel Core i7-6600U CPU @ 2.60GHz                             | 1         | 1.47%   |
| Intel Core i7-5500U CPU @ 2.40GHz                             | 1         | 1.47%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz                            | 1         | 1.47%   |
| Intel Core i7-3520M CPU @ 2.90GHz                             | 1         | 1.47%   |
| Intel Core i7-10750H CPU @ 2.60GHz                            | 1         | 1.47%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz                            | 1         | 1.47%   |
| Intel Core i5-8265U CPU @ 1.60GHz                             | 1         | 1.47%   |
| Intel Core i5-8250U CPU @ 1.60GHz                             | 1         | 1.47%   |
| Intel Core i5-7200U CPU @ 2.50GHz                             | 1         | 1.47%   |
| Intel Core i5-6200U CPU @ 2.30GHz                             | 1         | 1.47%   |
| Intel Core i5-5200U CPU @ 2.20GHz                             | 1         | 1.47%   |
| Intel Core i5-4310U CPU @ 2.00GHz                             | 1         | 1.47%   |
| Intel Core i5-4300U CPU @ 1.90GHz                             | 1         | 1.47%   |
| Intel Core i5-4210U CPU @ 1.70GHz                             | 1         | 1.47%   |
| Intel Core i5 CPU M 540 @ 2.53GHz                             | 1         | 1.47%   |
| Intel Core i5 CPU M 430 @ 2.27GH                              | 1         | 1.47%   |
| Intel Core i3-7100U CPU @ 2.40GHz                             | 1         | 1.47%   |
| Intel Core i3-6100U CPU @ 2.30GHz                             | 1         | 1.47%   |
| Intel Core i3-5020U CPU @ 2.20GHz                             | 1         | 1.47%   |
| Intel Core i3-5010U CPU @ 2.10GHz                             | 1         | 1.47%   |
| Intel Core i3-5005U CPU @ 2.00GHz                             | 1         | 1.47%   |
| Intel Core i3-4010U CPU @ 1.70GHz                             | 1         | 1.47%   |
| Intel Core i3-2310M CPU @ 2.10GHz                             | 1         | 1.47%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz                          | 1         | 1.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 27        | 40.91%  |
| Intel Core i7           | 11        | 16.67%  |
| Intel Core i3           | 7         | 10.61%  |
| Other                   | 5         | 7.58%   |
| Intel Core 2 Duo        | 4         | 6.06%   |
| Intel Celeron           | 4         | 6.06%   |
| Intel Atom              | 3         | 4.55%   |
| Intel Pentium Dual-Core | 1         | 1.52%   |
| Intel Pentium 4         | 1         | 1.52%   |
| Intel Genuine           | 1         | 1.52%   |
| AMD Ryzen 7             | 1         | 1.52%   |
| AMD E1                  | 1         | 1.52%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 44        | 67.69%  |
| 4       | 9         | 13.85%  |
| Unknown | 8         | 12.31%  |
| 6       | 2         | 3.08%   |
| 8       | 1         | 1.54%   |
| 1       | 1         | 1.54%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 63        | 92.65%  |
| Unknown | 4         | 5.88%   |
| 2       | 1         | 1.47%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 48        | 73.85%  |
| Unknown | 9         | 13.85%  |
| 1       | 8         | 12.31%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Skylake     | 9         | 13.43%  |
| KabyLake    | 7         | 10.45%  |
| IvyBridge   | 7         | 10.45%  |
| Broadwell   | 7         | 10.45%  |
| Haswell     | 6         | 8.96%   |
| SandyBridge | 5         | 7.46%   |
| Penryn      | 5         | 7.46%   |
| Unknown     | 5         | 7.46%   |
| Westmere    | 4         | 5.97%   |
| Bonnell     | 3         | 4.48%   |
| Zen+        | 1         | 1.49%   |
| TigerLake   | 1         | 1.49%   |
| P6          | 1         | 1.49%   |
| NetBurst    | 1         | 1.49%   |
| Nehalem     | 1         | 1.49%   |
| Jaguar      | 1         | 1.49%   |
| IceLake     | 1         | 1.49%   |
| Core        | 1         | 1.49%   |
| CometLake   | 1         | 1.49%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 55        | 79.71%  |
| Nvidia | 8         | 11.59%  |
| AMD    | 6         | 8.7%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                           | 9         | 12.33%  |
| Intel HD Graphics 5500                                                        | 7         | 9.59%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 6         | 8.22%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 5         | 6.85%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 5         | 6.85%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 3         | 4.11%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 3         | 4.11%   |
| Intel HD Graphics 620                                                         | 3         | 4.11%   |
| Intel Core Processor Integrated Graphics Controller                           | 3         | 4.11%   |
| Nvidia GK107M [GeForce GTX 660M]                                              | 2         | 2.74%   |
| Intel UHD Graphics 620                                                        | 2         | 2.74%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 2         | 2.74%   |
| Nvidia GT218M [NVS 3100M]                                                     | 1         | 1.37%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 1         | 1.37%   |
| Nvidia GK106M [GeForce GTX 765M]                                              | 1         | 1.37%   |
| Nvidia GF119M [GeForce GT 520M]                                               | 1         | 1.37%   |
| Nvidia G86M [GeForce 8400M GS]                                                | 1         | 1.37%   |
| Nvidia C79 [GeForce 9400M]                                                    | 1         | 1.37%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 1         | 1.37%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 1         | 1.37%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 1.37%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 1.37%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 1         | 1.37%   |
| Intel JasperLake [UHD Graphics]                                               | 1         | 1.37%   |
| Intel Iris Plus Graphics G7                                                   | 1         | 1.37%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 1         | 1.37%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 1         | 1.37%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller               | 1         | 1.37%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 1         | 1.37%   |
| AMD RV730/M96 [Mobility Radeon HD 4650/5165]                                  | 1         | 1.37%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/5145/530v/540v/545v]              | 1         | 1.37%   |
| AMD RV350/M10 / RV360/M11 [Mobility Radeon 9600 (PRO) / 9700]                 | 1         | 1.37%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 1         | 1.37%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 1         | 1.37%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                       | 1         | 1.37%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 44        | 67.69%  |
| 2 x Intel      | 7         | 10.77%  |
| 1 x AMD        | 6         | 9.23%   |
| 1 x Nvidia     | 4         | 6.15%   |
| Intel + Nvidia | 4         | 6.15%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 61        | 93.85%  |
| Proprietary | 3         | 4.62%   |
| Unknown     | 1         | 1.54%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 57        | 86.36%  |
| 0.01-0.5   | 3         | 4.55%   |
| 3.01-4.0   | 2         | 3.03%   |
| 1.01-2.0   | 2         | 3.03%   |
| 0.51-1.0   | 2         | 3.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 9         | 20.45%  |
| Chimei Innolux          | 9         | 20.45%  |
| AU Optronics            | 6         | 13.64%  |
| Samsung Electronics     | 5         | 11.36%  |
| BOE                     | 5         | 11.36%  |
| Lenovo                  | 3         | 6.82%   |
| Chi Mei Optoelectronics | 3         | 6.82%   |
| Goldstar                | 2         | 4.55%   |
| Toshiba                 | 1         | 2.27%   |
| Apple                   | 1         | 2.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch               | 2         | 4.55%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 310x170mm 13.9-inch          | 2         | 4.55%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch            | 2         | 4.55%   |
| Toshiba LCD Monitor LCD0905 1366x768 290x170mm 13.2-inch                  | 1         | 2.27%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 470x300mm 22.0-inch      | 1         | 2.27%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch      | 1         | 2.27%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 330x210mm 15.4-inch      | 1         | 2.27%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch      | 1         | 2.27%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 310x170mm 13.9-inch      | 1         | 2.27%   |
| LG Display LCD Monitor LGD0484 1366x768 340x190mm 15.3-inch               | 1         | 2.27%   |
| LG Display LCD Monitor LGD045E 1366x768 310x170mm 13.9-inch               | 1         | 2.27%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x170mm 13.9-inch               | 1         | 2.27%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch               | 1         | 2.27%   |
| LG Display LCD Monitor LGD021D 1600x900 380x210mm 17.1-inch               | 1         | 2.27%   |
| LG Display LCD Monitor LGD0215 1920x1080 350x190mm 15.7-inch              | 1         | 2.27%   |
| LG Display LCD Monitor LGD01E9 1920x1080 350x190mm 15.7-inch              | 1         | 2.27%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch                   | 1         | 2.27%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch                   | 1         | 2.27%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch                   | 1         | 2.27%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch                | 1         | 2.27%   |
| Goldstar L1920P GSM4A7B 1280x1024 380x300mm 19.1-inch                     | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN15F4 1920x1080 340x190mm 15.3-inch          | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN14B7 1366x768 310x170mm 13.9-inch           | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN1492 1366x768 310x170mm 13.9-inch           | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 310x170mm 13.9-inch           | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN1367 1920x1080 290x170mm 13.2-inch          | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 280x160mm 12.7-inch          | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch           | 1         | 2.27%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 380x210mm 17.1-inch | 1         | 2.27%   |
| Chi Mei Optoelectronics LCD Monitor CMO1333 1366x768 290x160mm 13.0-inch  | 1         | 2.27%   |
| Chi Mei Optoelectronics LCD Monitor CMO1312 1280x800 290x180mm 13.4-inch  | 1         | 2.27%   |
| BOE LCD Monitor BOE08BC 2256x1504 280x190mm 13.3-inch                     | 1         | 2.27%   |
| BOE LCD Monitor BOE0817 1366x768 340x190mm 15.3-inch                      | 1         | 2.27%   |
| BOE LCD Monitor BOE07C9 1920x1080 300x170mm 13.6-inch                     | 1         | 2.27%   |
| BOE LCD Monitor BOE0742 1920x1080 310x170mm 13.9-inch                     | 1         | 2.27%   |
| BOE LCD Monitor BOE06C2 1366x768 340x190mm 15.3-inch                      | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO173D 1920x1080 310x170mm 13.9-inch            | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 310x170mm 13.9-inch            | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO10ED 1920x1080 340x190mm 15.3-inch            | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch             | 1         | 2.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 15        | 34.09%  |
| 1366x768 (WXGA)    | 15        | 34.09%  |
| 1600x900 (HD+)     | 5         | 11.36%  |
| 1280x800 (WXGA)    | 4         | 9.09%   |
| 2560x1080          | 1         | 2.27%   |
| 2256x1504          | 1         | 2.27%   |
| 1680x1050 (WSXGA+) | 1         | 2.27%   |
| 1280x854           | 1         | 2.27%   |
| 1280x1024 (SXGA)   | 1         | 2.27%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 17        | 38.64%  |
| 15     | 12        | 27.27%  |
| 12     | 7         | 15.91%  |
| 17     | 2         | 4.55%   |
| 14     | 2         | 4.55%   |
| 34     | 1         | 2.27%   |
| 22     | 1         | 2.27%   |
| 19     | 1         | 2.27%   |
| 11     | 1         | 2.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 23        | 52.27%  |
| 201-300     | 16        | 36.36%  |
| 351-400     | 3         | 6.82%   |
| 701-800     | 1         | 2.27%   |
| 401-500     | 1         | 2.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 34        | 77.27%  |
| 16/10 | 6         | 13.64%  |
| 3/2   | 2         | 4.55%   |
| 5/4   | 1         | 2.27%   |
| 21/9  | 1         | 2.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 15        | 34.09%  |
| 61-70          | 7         | 15.91%  |
| 101-110        | 7         | 15.91%  |
| 91-100         | 5         | 11.36%  |
| 71-80          | 4         | 9.09%   |
| 121-130        | 2         | 4.55%   |
| 51-60          | 1         | 2.27%   |
| 351-500        | 1         | 2.27%   |
| 201-250        | 1         | 2.27%   |
| 151-200        | 1         | 2.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 19        | 43.18%  |
| 101-120 | 13        | 29.55%  |
| 161-240 | 6         | 13.64%  |
| 51-100  | 6         | 13.64%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 49        | 74.24%  |
| 0     | 16        | 24.24%  |
| 2     | 1         | 1.52%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 46        | 50.55%  |
| Realtek Semiconductor             | 17        | 18.68%  |
| Qualcomm Atheros                  | 15        | 16.48%  |
| Broadcom                          | 4         | 4.4%    |
| Sierra Wireless                   | 2         | 2.2%    |
| Ericsson Business Mobile Networks | 2         | 2.2%    |
| Ralink Technology                 | 1         | 1.1%    |
| Nvidia                            | 1         | 1.1%    |
| Marvell Technology Group          | 1         | 1.1%    |
| JMicron Technology                | 1         | 1.1%    |
| Apple                             | 1         | 1.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 8         | 6.3%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 8         | 6.3%    |
| Intel Ethernet Connection I219-LM                                       | 8         | 6.3%    |
| Intel Wireless 8260                                                     | 7         | 5.51%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 5.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 7         | 5.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 3.15%   |
| Intel 82577LM Gigabit Network Connection                                | 4         | 3.15%   |
| Intel Wireless 8265 / 8275                                              | 3         | 2.36%   |
| Intel Wireless 7265                                                     | 3         | 2.36%   |
| Intel Wireless 7260                                                     | 3         | 2.36%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 2.36%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 1.57%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 1.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 2         | 1.57%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 2         | 1.57%   |
| Intel Wireless 3165                                                     | 2         | 1.57%   |
| Intel Ethernet Connection I218-LM                                       | 2         | 1.57%   |
| Intel Ethernet Connection (4) I219-LM                                   | 2         | 1.57%   |
| Intel Ethernet Connection (3) I218-LM                                   | 2         | 1.57%   |
| Sierra Wireless EM7455                                                  | 1         | 0.79%   |
| Sierra Wireless EM7305 Modem                                            | 1         | 0.79%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.79%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.79%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 1         | 0.79%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 0.79%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller               | 1         | 0.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 0.79%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 1         | 0.79%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 1         | 0.79%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 1         | 0.79%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.79%   |
| Nvidia MCP79 Ethernet                                                   | 1         | 0.79%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                 | 1         | 0.79%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 1         | 0.79%   |
| Intel Wireless-AC 9260                                                  | 1         | 0.79%   |
| Intel Wireless 3160                                                     | 1         | 0.79%   |
| Intel WiMAX Connection 2400m                                            | 1         | 0.79%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 1         | 0.79%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 43        | 69.35%  |
| Qualcomm Atheros      | 11        | 17.74%  |
| Broadcom              | 4         | 6.45%   |
| Realtek Semiconductor | 2         | 3.23%   |
| Sierra Wireless       | 1         | 1.61%   |
| Ralink Technology     | 1         | 1.61%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                                     | 7         | 11.11%  |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 11.11%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 6.35%   |
| Intel Wireless 8265 / 8275                                              | 3         | 4.76%   |
| Intel Wireless 7265                                                     | 3         | 4.76%   |
| Intel Wireless 7260                                                     | 3         | 4.76%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 4.76%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 3.17%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 3.17%   |
| Intel Wireless 3165                                                     | 2         | 3.17%   |
| Sierra Wireless EM7455                                                  | 1         | 1.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.59%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 1.59%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 1.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 1.59%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 1         | 1.59%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.59%   |
| Intel Wireless-AC 9260                                                  | 1         | 1.59%   |
| Intel Wireless 3160                                                     | 1         | 1.59%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 1         | 1.59%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 1.59%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 1.59%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 1.59%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 1.59%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 1.59%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 1.59%   |
| Intel Centrino Wireless-N 2200                                          | 1         | 1.59%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 1.59%   |
| Intel Centrino Wireless-N 100                                           | 1         | 1.59%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                    | 1         | 1.59%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 1.59%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1         | 1.59%   |
| Broadcom BCM43225 802.11b/g/n                                           | 1         | 1.59%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 1         | 1.59%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 1         | 1.59%   |
| Broadcom BCM4306 802.11b/g Wireless LAN Controller                      | 1         | 1.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 31        | 52.54%  |
| Realtek Semiconductor    | 17        | 28.81%  |
| Qualcomm Atheros         | 7         | 11.86%  |
| Nvidia                   | 1         | 1.69%   |
| Marvell Technology Group | 1         | 1.69%   |
| JMicron Technology       | 1         | 1.69%   |
| Apple                    | 1         | 1.69%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8         | 13.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 13.33%  |
| Intel Ethernet Connection I219-LM                                 | 8         | 13.33%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 11.67%  |
| Intel 82577LM Gigabit Network Connection                          | 4         | 6.67%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 3.33%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 3.33%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 3.33%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 3.33%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 3.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.67%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.67%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.67%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 1.67%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.67%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 1.67%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.67%   |
| Intel I350 Gigabit Fiber Network Connection                       | 1         | 1.67%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.67%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 1.67%   |
| Intel 82583V Gigabit Network Connection                           | 1         | 1.67%   |
| Intel 82580 Gigabit Network Connection                            | 1         | 1.67%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.67%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.67%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                   | 1         | 1.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 60        | 48.78%  |
| Ethernet | 59        | 47.97%  |
| Unknown  | 3         | 2.44%   |
| Modem    | 1         | 0.81%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 53        | 56.99%  |
| Ethernet | 40        | 43.01%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 54        | 83.08%  |
| 1     | 7         | 10.77%  |
| 3     | 2         | 3.08%   |
| 10    | 1         | 1.54%   |
| 4     | 1         | 1.54%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 59        | 88.06%  |
| Yes  | 8         | 11.94%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 21        | 48.84%  |
| Broadcom                        | 5         | 11.63%  |
| Cambridge Silicon Radio         | 3         | 6.98%   |
| Qualcomm Atheros Communications | 2         | 4.65%   |
| IMC Networks                    | 2         | 4.65%   |
| Foxconn / Hon Hai               | 2         | 4.65%   |
| Alps Electric                   | 2         | 4.65%   |
| Toshiba                         | 1         | 2.33%   |
| Realtek Semiconductor           | 1         | 2.33%   |
| Lite-On Technology              | 1         | 2.33%   |
| Hewlett-Packard                 | 1         | 2.33%   |
| ASUSTek Computer                | 1         | 2.33%   |
| Apple                           | 1         | 2.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 15        | 34.88%  |
| Intel AX201 Bluetooth                                       | 4         | 9.3%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 3         | 6.98%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 3         | 6.98%   |
| Alps Electric UGTZ4 Bluetooth                               | 2         | 4.65%   |
| Toshiba ASKEY Bluetooth Controller BTU1030                  | 1         | 2.33%   |
| Realtek  Bluetooth 4.0 Adapter                              | 1         | 2.33%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 2.33%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 2.33%   |
| Lite-On Broadcom Bluetooth 4.0 USB                          | 1         | 2.33%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 2.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 1         | 2.33%   |
| IMC Networks Bluetooth                                      | 1         | 2.33%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 1         | 2.33%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 2.33%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device    | 1         | 2.33%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 1         | 2.33%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 1         | 2.33%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 1         | 2.33%   |
| ASUS Broadcom Bluetooth 2.1                                 | 1         | 2.33%   |
| Apple Bluetooth Host Controller                             | 1         | 2.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 60        | 88.24%  |
| AMD    | 4         | 5.88%   |
| Nvidia | 3         | 4.41%   |
| XMOS   | 1         | 1.47%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 14        | 16.87%  |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 7         | 8.43%   |
| Intel Broadwell-U Audio Controller                                         | 7         | 8.43%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6         | 7.23%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 7.23%   |
| Intel 8 Series HD Audio Controller                                         | 5         | 6.02%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 6.02%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 4.82%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 4.82%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 3.61%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 2.41%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 2         | 2.41%   |
| XMOS retrieving string failed                                              | 1         | 1.2%    |
| XMOS iFi (by AMR) HD USB Audio                                             | 1         | 1.2%    |
| Nvidia MCP79 High Definition Audio                                         | 1         | 1.2%    |
| Nvidia High Definition Audio Controller                                    | 1         | 1.2%    |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 1.2%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.2%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 1.2%    |
| Intel Jasper Lake HD Audio                                                 | 1         | 1.2%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1.2%    |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.2%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.2%    |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.2%    |
| Intel 82801CA/CAM AC'97 Audio Controller                                   | 1         | 1.2%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 1.2%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 1.2%    |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.2%    |
| AMD FCH Azalia Controller                                                  | 1         | 1.2%    |
| AMD Family 17h/19h HD Audio Controller                                     | 1         | 1.2%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 17        | 26.56%  |
| Samsung Electronics | 17        | 26.56%  |
| Unknown             | 9         | 14.06%  |
| Kingston            | 7         | 10.94%  |
| Micron Technology   | 4         | 6.25%   |
| Corsair             | 3         | 4.69%   |
| A-DATA Technology   | 2         | 3.13%   |
| Unknown             | 2         | 3.13%   |
| Ramaxel Technology  | 1         | 1.56%   |
| Nanya Technology    | 1         | 1.56%   |
| G.Skill             | 1         | 1.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s           | 3         | 4.48%   |
| Unknown RAM Module 1GB SODIMM DDR2                              | 2         | 2.99%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 2         | 2.99%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s         | 2         | 2.99%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s           | 2         | 2.99%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s           | 2         | 2.99%   |
| Unknown                                                         | 2         | 2.99%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                     | 1         | 1.49%   |
| Unknown RAM Module 512MB SODIMM SDRAM                           | 1         | 1.49%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                     | 1         | 1.49%   |
| Unknown RAM Module 4096MB SODIMM DDR2                           | 1         | 1.49%   |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s                     | 1         | 1.49%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                          | 1         | 1.49%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                   | 1         | 1.49%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.49%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s          | 1         | 1.49%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 1         | 1.49%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s       | 1         | 1.49%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.49%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.49%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s          | 1         | 1.49%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1333MT/s          | 1         | 1.49%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s          | 1         | 1.49%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s          | 1         | 1.49%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB Row Of Chips DDR4 2400MT/s | 1         | 1.49%   |
| SK hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s  | 1         | 1.49%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB SODIMM LPDDR3 1867MT/s          | 1         | 1.49%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB Chip LPDDR3 1867MT/s            | 1         | 1.49%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s           | 1         | 1.49%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM 1067MT/s                | 1         | 1.49%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.49%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.49%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.49%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.49%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s           | 1         | 1.49%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s           | 1         | 1.49%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s           | 1         | 1.49%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s           | 1         | 1.49%   |
| Samsung RAM K4UBE3D4AA-MGCH 8GB Row Of Chips LPDDR4 3200MT/s    | 1         | 1.49%   |
| Ramaxel RAM RMT3020EF48E8W1333 2GB SODIMM DDR3 1334MT/s         | 1         | 1.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 35        | 59.32%  |
| DDR4   | 13        | 22.03%  |
| DDR2   | 4         | 6.78%   |
| SDRAM  | 3         | 5.08%   |
| LPDDR4 | 3         | 5.08%   |
| LPDDR3 | 1         | 1.69%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 54        | 90%     |
| Row Of Chips | 4         | 6.67%   |
| Chip         | 2         | 3.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 25        | 41.67%  |
| 8192  | 15        | 25%     |
| 2048  | 12        | 20%     |
| 16384 | 5         | 8.33%   |
| 1024  | 2         | 3.33%   |
| 512   | 1         | 1.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 18        | 29.51%  |
| 1333    | 7         | 11.48%  |
| 2400    | 6         | 9.84%   |
| Unknown | 6         | 9.84%   |
| 2667    | 5         | 8.2%    |
| 1067    | 5         | 8.2%    |
| 1334    | 4         | 6.56%   |
| 2133    | 3         | 4.92%   |
| 4267    | 2         | 3.28%   |
| 3200    | 2         | 3.28%   |
| 1867    | 1         | 1.64%   |
| 667     | 1         | 1.64%   |
| 533     | 1         | 1.64%   |

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
| Chicony Electronics           | 15        | 37.5%   |
| Bison Electronics             | 6         | 15%     |
| Microdia                      | 5         | 12.5%   |
| Realtek Semiconductor         | 3         | 7.5%    |
| Lite-On Technology            | 3         | 7.5%    |
| IMC Networks                  | 3         | 7.5%    |
| Sunplus Innovation Technology | 2         | 5%      |
| Syntek                        | 1         | 2.5%    |
| Quanta                        | 1         | 2.5%    |
| Lenovo                        | 1         | 2.5%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Bison Integrated Camera                  | 4         | 10%     |
| Lite-On Integrated Camera                | 3         | 7.5%    |
| Chicony integrated camera                | 3         | 7.5%    |
| Chicony HD Webcam                        | 3         | 7.5%    |
| Syntek Lenovo EasyCamera                 | 1         | 2.5%    |
| Sunplus Laptop_Integrated_Webcam_FHD     | 1         | 2.5%    |
| Sunplus ASUS Webcam                      | 1         | 2.5%    |
| Realtek Realtek USB2.0 PC Camera         | 1         | 2.5%    |
| Realtek Integrated Webcam HD             | 1         | 2.5%    |
| Realtek Integrated Webcam                | 1         | 2.5%    |
| Quanta USB2.0 HD UVC WebCam              | 1         | 2.5%    |
| Microdia Sonix USB 2.0 Camera            | 1         | 2.5%    |
| Microdia Laptop_Integrated_Webcam_2M     | 1         | 2.5%    |
| Microdia Integrated_Webcam_HD            | 1         | 2.5%    |
| Microdia Integrated Webcam HD            | 1         | 2.5%    |
| Microdia Integrated Webcam               | 1         | 2.5%    |
| Lenovo Integrated Webcam [R5U877]        | 1         | 2.5%    |
| IMC Networks UVC VGA Webcam              | 1         | 2.5%    |
| IMC Networks Integrated Webcam           | 1         | 2.5%    |
| IMC Networks Integrated Camera           | 1         | 2.5%    |
| Chicony WebCam                           | 1         | 2.5%    |
| Chicony VGA 24fps UVC Webcam             | 1         | 2.5%    |
| Chicony TOSHIBA Web Camera - FHD         | 1         | 2.5%    |
| Chicony Sonix ST50220 USB Video Camera   | 1         | 2.5%    |
| Chicony Lenovo Integrated Camera (0.3MP) | 1         | 2.5%    |
| Chicony Integrated Camera [ThinkPad]     | 1         | 2.5%    |
| Chicony HP HD Camera                     | 1         | 2.5%    |
| Chicony FJ Camera                        | 1         | 2.5%    |
| Chicony 2.0M UVC Webcam / CNF7129        | 1         | 2.5%    |
| Bison ThinkPad P50 Integrated Camera     | 1         | 2.5%    |
| Bison SunplusIT Integrated Camera        | 1         | 2.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 42.86%  |
| Upek                       | 2         | 14.29%  |
| LighTuning Technology      | 2         | 14.29%  |
| AuthenTec                  | 2         | 14.29%  |
| Synaptics                  | 1         | 7.14%   |
| Shenzhen Goodix Technology | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 3         | 21.43%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 14.29%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 7.14%   |
| Validity Sensors VFS Fingerprint sensor                | 1         | 7.14%   |
| Validity Sensors Synaptics WBDI                        | 1         | 7.14%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 7.14%   |
| Shenzhen Goodix FingerPrint                            | 1         | 7.14%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 7.14%   |
| LighTuning EgisTec EH575                               | 1         | 7.14%   |
| AuthenTec AuthenTec Inc. AES2660                       | 1         | 7.14%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 7.14%   |

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
| 1     | 33        | 49.25%  |
| 2     | 13        | 19.4%   |
| 3     | 11        | 16.42%  |
| 0     | 5         | 7.46%   |
| 4     | 4         | 5.97%   |
| 5     | 1         | 1.49%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 50        | 48.08%  |
| Bluetooth                | 15        | 14.42%  |
| Fingerprint reader       | 10        | 9.62%   |
| Card reader              | 9         | 8.65%   |
| Firewire controller      | 8         | 7.69%   |
| Net/wireless             | 4         | 3.85%   |
| Storage                  | 2         | 1.92%   |
| Graphics card            | 2         | 1.92%   |
| Storage/ata              | 1         | 0.96%   |
| Sound                    | 1         | 0.96%   |
| Network                  | 1         | 0.96%   |
| Net/ethernet             | 1         | 0.96%   |

