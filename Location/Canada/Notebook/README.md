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

Total: 162

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Apple         | MacBookPro7,1               | [91d07ef080](https://bsd-hardware.info/?probe=91d07ef080) | Nov 01, 2023 |
| Datto         | Unknown                     | [8b59510085](https://bsd-hardware.info/?probe=8b59510085) | Oct 27, 2023 |
| Panasonic     | CF-52PFPBSFQ                | [4a97ab307a](https://bsd-hardware.info/?probe=4a97ab307a) | Oct 22, 2023 |
| Lenovo        | ThinkPad T430 2347GZU       | [88ae89f787](https://bsd-hardware.info/?probe=88ae89f787) | Oct 22, 2023 |
| Panasonic     | CF-53AAGHYDM                | [6f29731875](https://bsd-hardware.info/?probe=6f29731875) | Oct 22, 2023 |
| ASUSTek       | 1000HE                      | [249959fd2c](https://bsd-hardware.info/?probe=249959fd2c) | Oct 21, 2023 |
| Matsushita... | CF-51RCVDNLM                | [ec5aff8b6b](https://bsd-hardware.info/?probe=ec5aff8b6b) | Oct 21, 2023 |
| Matsushita... | CF-48V4KNDQM                | [625f272fcd](https://bsd-hardware.info/?probe=625f272fcd) | Oct 21, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [965e71ac80](https://bsd-hardware.info/?probe=965e71ac80) | Oct 21, 2023 |
| Lenovo        | ThinkPad T410 2537N24       | [fd75aab1c6](https://bsd-hardware.info/?probe=fd75aab1c6) | Oct 20, 2023 |
| Lenovo        | ThinkPad T470 20HES0HU00    | [a64fe205a9](https://bsd-hardware.info/?probe=a64fe205a9) | Sep 17, 2023 |
| Shuttle       | DS67U                       | [55c2922a25](https://bsd-hardware.info/?probe=55c2922a25) | Sep 04, 2023 |
| Datto         | Unknown                     | [418eab5eaa](https://bsd-hardware.info/?probe=418eab5eaa) | Aug 23, 2023 |
| Star Labs     | Lite                        | [eabab74d7b](https://bsd-hardware.info/?probe=eabab74d7b) | Aug 18, 2023 |
| ASUSTek       | ROG Strix G513QC_G513QC     | [b90e62e27d](https://bsd-hardware.info/?probe=b90e62e27d) | Aug 04, 2023 |
| Acer          | Aspire 4736Z                | [bccf97f694](https://bsd-hardware.info/?probe=bccf97f694) | Jul 20, 2023 |
| Deciso        | NetBoard-A20                | [0754642fe6](https://bsd-hardware.info/?probe=0754642fe6) | Jun 07, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | [8cc6299ba9](https://bsd-hardware.info/?probe=8cc6299ba9) | May 31, 2023 |
| Acer          | Aspire E5-573               | [7bcb7c96be](https://bsd-hardware.info/?probe=7bcb7c96be) | May 23, 2023 |
| Lenovo        | ThinkPad T410 2537N24       | [6cd0f02045](https://bsd-hardware.info/?probe=6cd0f02045) | May 08, 2023 |
| Matsushita... | CF-48V4KNDQM                | [79f10d24d6](https://bsd-hardware.info/?probe=79f10d24d6) | May 07, 2023 |
| ASUSTek       | 1000HE                      | [36214f8bed](https://bsd-hardware.info/?probe=36214f8bed) | May 07, 2023 |
| Matsushita... | CF-51RCVDNLM                | [105a885451](https://bsd-hardware.info/?probe=105a885451) | May 05, 2023 |
| Lenovo        | ThinkPad T420s 41742BU      | [161fe49de4](https://bsd-hardware.info/?probe=161fe49de4) | May 05, 2023 |
| Lenovo        | ThinkPad X230 2325T4T       | [00303b7a59](https://bsd-hardware.info/?probe=00303b7a59) | May 05, 2023 |
| Lenovo        | ThinkPad X220 429043U       | [bb714a4350](https://bsd-hardware.info/?probe=bb714a4350) | May 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [28e76d5531](https://bsd-hardware.info/?probe=28e76d5531) | May 04, 2023 |
| Lenovo        | ThinkPad T430 2347GZU       | [8c3f486dbc](https://bsd-hardware.info/?probe=8c3f486dbc) | May 03, 2023 |
| Panasonic     | CF-52PFPBSFQ                | [e2c3df29b5](https://bsd-hardware.info/?probe=e2c3df29b5) | May 03, 2023 |
| Panasonic     | CF-53AAGHYDM                | [c7daf17edb](https://bsd-hardware.info/?probe=c7daf17edb) | May 02, 2023 |
| Lenovo        | ThinkPad X260 20F5S2GM00    | [c4af168c4a](https://bsd-hardware.info/?probe=c4af168c4a) | May 01, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [cf504f51df](https://bsd-hardware.info/?probe=cf504f51df) | May 01, 2023 |
| Fujitsu       | LIFEBOOK E752               | [44ea9fb6ae](https://bsd-hardware.info/?probe=44ea9fb6ae) | Apr 30, 2023 |
| Google        | Terra                       | [ef1619f65f](https://bsd-hardware.info/?probe=ef1619f65f) | Apr 13, 2023 |
| Google        | Terra                       | [bf598bc5bf](https://bsd-hardware.info/?probe=bf598bc5bf) | Apr 13, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X3C... | [0249b4e73f](https://bsd-hardware.info/?probe=0249b4e73f) | Apr 11, 2023 |
| HP            | Pavilion dv6                | [ce2cc6852d](https://bsd-hardware.info/?probe=ce2cc6852d) | Mar 27, 2023 |
| Dell          | Latitude 5420               | [4e22bbc131](https://bsd-hardware.info/?probe=4e22bbc131) | Mar 26, 2023 |
| eMachines     | eM350                       | [bb900ace2d](https://bsd-hardware.info/?probe=bb900ace2d) | Mar 25, 2023 |
| Alienware     | 14                          | [742d648570](https://bsd-hardware.info/?probe=742d648570) | Mar 25, 2023 |
| Acer          | AOD270                      | [73877008e9](https://bsd-hardware.info/?probe=73877008e9) | Mar 25, 2023 |
| Intel         | SandyBridge Platform        | [954a21f7de](https://bsd-hardware.info/?probe=954a21f7de) | Mar 23, 2023 |
| HP            | ProBook 640 G3              | [860471150b](https://bsd-hardware.info/?probe=860471150b) | Mar 18, 2023 |
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


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| OpenBSD 7.2          | 15        | 10.42%  |
| OpenBSD 7.3          | 14        | 9.72%   |
| OpenBSD 7.1          | 10        | 6.94%   |
| OpenBSD 7.0          | 9         | 6.25%   |
| OpenBSD 6.9          | 9         | 6.25%   |
| OpenBSD 7.4          | 7         | 4.86%   |
| OpenBSD 6.8          | 7         | 4.86%   |
| helloSystem 0.8.1    | 5         | 3.47%   |
| helloSystem 0.4.0    | 4         | 2.78%   |
| helloSystem 0.8.0    | 3         | 2.08%   |
| helloSystem 0.7.0    | 3         | 2.08%   |
| FreeBSD 13.1-p7      | 3         | 2.08%   |
| FreeBSD 13.1-p5      | 3         | 2.08%   |
| FreeBSD 13.0-p5      | 3         | 2.08%   |
| OPNsense 23.7.3      | 2         | 1.39%   |
| helloSystem 0.5.0    | 2         | 1.39%   |
| FreeBSD 14.0-CURRENT | 2         | 1.39%   |
| FreeBSD 13.1-p2      | 2         | 1.39%   |
| FreeBSD 13.1         | 2         | 1.39%   |
| FreeBSD 13.0         | 2         | 1.39%   |
| FreeBSD 12.2         | 2         | 1.39%   |
| OPNsense 23.7.1      | 1         | 0.69%   |
| OPNsense 23.4        | 1         | 0.69%   |
| OPNsense 23.1.3      | 1         | 0.69%   |
| OPNsense 23.1        | 1         | 0.69%   |
| OPNsense 22.7.6      | 1         | 0.69%   |
| OPNsense 22.7.5      | 1         | 0.69%   |
| OPNsense 22.7.4      | 1         | 0.69%   |
| OPNsense 22.7        | 1         | 0.69%   |
| OPNsense 22.1.1      | 1         | 0.69%   |
| OPNsense 21.1.5      | 1         | 0.69%   |
| OPNsense 21.1.4      | 1         | 0.69%   |
| OPNsense 21.1        | 1         | 0.69%   |
| NetBSD 8.99.51       | 1         | 0.69%   |
| helloSystem 0.8.2    | 1         | 0.69%   |
| helloSystem 0.6.0    | 1         | 0.69%   |
| GhostBSD 23.10.09    | 1         | 0.69%   |
| GhostBSD 23.09.06    | 1         | 0.69%   |
| GhostBSD 22.06.18    | 1         | 0.69%   |
| GhostBSD 21.08.27    | 1         | 0.69%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 30        | 36.14%  |
| OpenBSD     | 19        | 22.89%  |
| helloSystem | 18        | 21.69%  |
| OPNsense    | 11        | 13.25%  |
| GhostBSD    | 4         | 4.82%   |
| NetBSD      | 1         | 1.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| amd64  | 78        | 93.98%  |
| i386   | 4         | 4.82%   |
| macppc | 1         | 1.2%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 32        | 34.78%  |
| Console      | 18        | 19.57%  |
| fvwm         | 12        | 13.04%  |
| XFCE         | 10        | 10.87%  |
| TWM          | 4         | 4.35%   |
| MATE         | 3         | 3.26%   |
| GNOME        | 3         | 3.26%   |
| Openbox      | 2         | 2.17%   |
| KDE5         | 2         | 2.17%   |
| i3           | 2         | 2.17%   |
| LXQt         | 1         | 1.09%   |
| Lumina       | 1         | 1.09%   |
| Fluxbox      | 1         | 1.09%   |
| Cinnamon     | 1         | 1.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 66        | 78.57%  |
| Console | 18        | 21.43%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 46        | 54.76%  |
| SLiM    | 19        | 22.62%  |
| XDM     | 7         | 8.33%   |
| LightDM | 6         | 7.14%   |
| SDDM    | 3         | 3.57%   |
| GDM     | 3         | 3.57%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 42        | 49.41%  |
| en_US   | 19        | 22.35%  |
| C       | 14        | 16.47%  |
| en_CA   | 4         | 4.71%   |
| fr_FR   | 3         | 3.53%   |
| fr_CA   | 1         | 1.18%   |
| en_NL   | 1         | 1.18%   |
| en      | 1         | 1.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 59        | 70.24%  |
| BIOS | 25        | 29.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 37        | 44.05%  |
| Ufs    | 22        | 26.19%  |
| Ffs    | 19        | 22.62%  |
| Cd9660 | 6         | 7.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 67        | 80.72%  |
| MBR     | 14        | 16.87%  |
| Unknown | 2         | 2.41%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 26        | 31.33%  |
| Dell                           | 9         | 10.84%  |
| Hewlett-Packard                | 7         | 8.43%   |
| ASUSTek Computer               | 6         | 7.23%   |
| Acer                           | 5         | 6.02%   |
| Intel                          | 4         | 4.82%   |
| Toshiba                        | 3         | 3.61%   |
| Panasonic                      | 3         | 3.61%   |
| Apple                          | 3         | 3.61%   |
| Matsushita Electric Industrial | 2         | 2.41%   |
| Google                         | 2         | 2.41%   |
| Gigabyte Technology            | 2         | 2.41%   |
| Unknown                        | 2         | 2.41%   |
| Star Labs                      | 1         | 1.2%    |
| Shuttle                        | 1         | 1.2%    |
| MSI                            | 1         | 1.2%    |
| LG Electronics                 | 1         | 1.2%    |
| Fujitsu                        | 1         | 1.2%    |
| eMachines                      | 1         | 1.2%    |
| Deciso                         | 1         | 1.2%    |
| Datto                          | 1         | 1.2%    |
| Alienware                      | 1         | 1.2%    |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel H81U                                  | 3         | 3.61%   |
| Unknown                                     | 3         | 3.61%   |
| Toshiba TECRA Z40-B                         | 1         | 1.2%    |
| Toshiba Satellite U500                      | 1         | 1.2%    |
| Toshiba Satellite Pro T130                  | 1         | 1.2%    |
| Star Labs Lite                              | 1         | 1.2%    |
| Shuttle DS67U                               | 1         | 1.2%    |
| Panasonic CF-54-1                           | 1         | 1.2%    |
| Panasonic CF-53AAGHYDM                      | 1         | 1.2%    |
| Panasonic CF-52PFPBSFQ                      | 1         | 1.2%    |
| MSI GL65 Leopard 10SFSK                     | 1         | 1.2%    |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 1.2%    |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 1.2%    |
| LG E500-GP01A9                              | 1         | 1.2%    |
| Lenovo ThinkPad X280 20KF001UUS             | 1         | 1.2%    |
| Lenovo ThinkPad X270 W10DG 20K5S0TT1N       | 1         | 1.2%    |
| Lenovo ThinkPad X270 W10DG 20K5S0PY04       | 1         | 1.2%    |
| Lenovo ThinkPad X270 20HNCTO1WW             | 1         | 1.2%    |
| Lenovo ThinkPad X260 20F5S2GM00             | 1         | 1.2%    |
| Lenovo ThinkPad X250 20CL001GUS             | 1         | 1.2%    |
| Lenovo ThinkPad X230 2325T4T                | 1         | 1.2%    |
| Lenovo ThinkPad X220 429043U                | 1         | 1.2%    |
| Lenovo ThinkPad X1 Carbon 4th 20FCS13H00    | 1         | 1.2%    |
| Lenovo ThinkPad T510 4313CTO                | 1         | 1.2%    |
| Lenovo ThinkPad T490 20N3S8PB00             | 1         | 1.2%    |
| Lenovo ThinkPad T470 20HES0HU00             | 1         | 1.2%    |
| Lenovo ThinkPad T460 20FMS1BC01             | 1         | 1.2%    |
| Lenovo ThinkPad T460 20FMS10N00             | 1         | 1.2%    |
| Lenovo ThinkPad T440 20B7S0A800             | 1         | 1.2%    |
| Lenovo ThinkPad T430 2347GZU                | 1         | 1.2%    |
| Lenovo ThinkPad T420s 41742BU               | 1         | 1.2%    |
| Lenovo ThinkPad T420 4180B39                | 1         | 1.2%    |
| Lenovo ThinkPad T410 2537N24                | 1         | 1.2%    |
| Lenovo ThinkPad T410 253722U                | 1         | 1.2%    |
| Lenovo ThinkPad T400 2764CTO                | 1         | 1.2%    |
| Lenovo ThinkPad T15p Gen 3 21DA000QUS       | 1         | 1.2%    |
| Lenovo ThinkPad L15 Gen 2 20X3CTO1WW        | 1         | 1.2%    |
| Lenovo ThinkPad E495 20NE0001US             | 1         | 1.2%    |
| Lenovo Legion 5 15ARH05 82B5                | 1         | 1.2%    |
| Lenovo IdeaPad Y580 20132                   | 1         | 1.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad                             | 24        | 28.92%  |
| Dell Inspiron                               | 4         | 4.82%   |
| Intel H81U                                  | 3         | 3.61%   |
| Dell Latitude                               | 3         | 3.61%   |
| Unknown                                     | 3         | 3.61%   |
| Toshiba Satellite                           | 2         | 2.41%   |
| HP Pavilion                                 | 2         | 2.41%   |
| Acer Swift                                  | 2         | 2.41%   |
| Acer Aspire                                 | 2         | 2.41%   |
| Toshiba TECRA                               | 1         | 1.2%    |
| Star Labs Lite                              | 1         | 1.2%    |
| Shuttle DS67U                               | 1         | 1.2%    |
| Panasonic CF-54-1                           | 1         | 1.2%    |
| Panasonic CF-53AAGHYDM                      | 1         | 1.2%    |
| Panasonic CF-52PFPBSFQ                      | 1         | 1.2%    |
| MSI GL65                                    | 1         | 1.2%    |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 1.2%    |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 1.2%    |
| LG E500-GP01A9                              | 1         | 1.2%    |
| Lenovo Legion                               | 1         | 1.2%    |
| Lenovo IdeaPad                              | 1         | 1.2%    |
| Intel SandyBridge                           | 1         | 1.2%    |
| HP ProBook                                  | 1         | 1.2%    |
| HP Notebook                                 | 1         | 1.2%    |
| HP EliteBook                                | 1         | 1.2%    |
| HP Compaq                                   | 1         | 1.2%    |
| HP 2000                                     | 1         | 1.2%    |
| Google Terra                                | 1         | 1.2%    |
| Google Peppy                                | 1         | 1.2%    |
| Gigabyte MMLP3AP-00                         | 1         | 1.2%    |
| Gigabyte GB-BSi3A-6100                      | 1         | 1.2%    |
| Fujitsu LIFEBOOK                            | 1         | 1.2%    |
| eMachines eM350                             | 1         | 1.2%    |
| Dell XPS                                    | 1         | 1.2%    |
| Dell Studio                                 | 1         | 1.2%    |
| Deciso NetBoard-A20                         | 1         | 1.2%    |
| ASUS U31SD                                  | 1         | 1.2%    |
| ASUS TUF                                    | 1         | 1.2%    |
| ASUS ROG                                    | 1         | 1.2%    |
| ASUS K52JK                                  | 1         | 1.2%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 10        | 12.05%  |
| 2010    | 9         | 10.84%  |
| 2011    | 7         | 8.43%   |
| 2021    | 6         | 7.23%   |
| 2018    | 6         | 7.23%   |
| 2015    | 6         | 7.23%   |
| 2009    | 6         | 7.23%   |
| 2022    | 5         | 6.02%   |
| 2016    | 5         | 6.02%   |
| 2014    | 5         | 6.02%   |
| 2017    | 4         | 4.82%   |
| 2012    | 4         | 4.82%   |
| 2023    | 2         | 2.41%   |
| 2020    | 2         | 2.41%   |
| 2013    | 2         | 2.41%   |
| 2008    | 1         | 1.2%    |
| 2006    | 1         | 1.2%    |
| 2002    | 1         | 1.2%    |
| Unknown | 1         | 1.2%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 83        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 81        | 97.59%  |
| Yes  | 2         | 2.41%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 33        | 39.76%  |
| 4.01-8.0   | 17        | 20.48%  |
| 16.01-24.0 | 15        | 18.07%  |
| 3.01-4.0   | 6         | 7.23%   |
| 32.01-64.0 | 5         | 6.02%   |
| 2.01-3.0   | 5         | 6.02%   |
| 1.01-2.0   | 1         | 1.2%    |
| 0.51-1.0   | 1         | 1.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 54        | 64.29%  |
| 0.51-1.0 | 20        | 23.81%  |
| 1.01-2.0 | 6         | 7.14%   |
| 0        | 2         | 2.38%   |
| 3.01-4.0 | 1         | 1.19%   |
| Unknown  | 1         | 1.19%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 67        | 79.76%  |
| 2      | 10        | 11.9%   |
| 0      | 5         | 5.95%   |
| 58     | 1         | 1.19%   |
| 3      | 1         | 1.19%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 67        | 78.82%  |
| Yes       | 18        | 21.18%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 75        | 90.36%  |
| No        | 8         | 9.64%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 89.16%  |
| No        | 9         | 10.84%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 55        | 65.48%  |
| No        | 29        | 34.52%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Canada  | 83        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Montreal          | 24        | 22.22%  |
| Saint-Laurent     | 14        | 12.96%  |
| Vancouver         | 7         | 6.48%   |
| Toronto           | 6         | 5.56%   |
| QuГ©bec         | 5         | 4.63%   |
| Calgary           | 5         | 4.63%   |
| Ottawa            | 4         | 3.7%    |
| Victoria          | 3         | 2.78%   |
| Kingsburg         | 3         | 2.78%   |
| Stratford         | 2         | 1.85%   |
| Sainte-Julie      | 2         | 1.85%   |
| Peterborough      | 2         | 1.85%   |
| Langley           | 2         | 1.85%   |
| Winnipeg          | 1         | 0.93%   |
| Whitby            | 1         | 0.93%   |
| Vaudreuil-Dorion  | 1         | 0.93%   |
| Surrey            | 1         | 0.93%   |
| St. Jean Baptiste | 1         | 0.93%   |
| Sechelt           | 1         | 0.93%   |
| Scarborough       | 1         | 0.93%   |
| Saskatoon         | 1         | 0.93%   |
| Saint-Zotique     | 1         | 0.93%   |
| Québec           | 1         | 0.93%   |
| Pierrefonds       | 1         | 0.93%   |
| North York        | 1         | 0.93%   |
| North Vancouver   | 1         | 0.93%   |
| Niagara Falls     | 1         | 0.93%   |
| Nepean            | 1         | 0.93%   |
| Mississauga       | 1         | 0.93%   |
| Mission           | 1         | 0.93%   |
| Maple Ridge       | 1         | 0.93%   |
| Lloydminster      | 1         | 0.93%   |
| Laval             | 1         | 0.93%   |
| Lamont            | 1         | 0.93%   |
| Kelowna           | 1         | 0.93%   |
| Hamilton          | 1         | 0.93%   |
| Halifax           | 1         | 0.93%   |
| Guelph            | 1         | 0.93%   |
| Gatineau          | 1         | 0.93%   |
| Brampton          | 1         | 0.93%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 19        | 55     | 20.88%  |
| Toshiba             | 9         | 19     | 9.89%   |
| Kingston            | 9         | 12     | 9.89%   |
| Samsung Electronics | 8         | 14     | 8.79%   |
| Hitachi             | 7         | 11     | 7.69%   |
| Seagate             | 6         | 12     | 6.59%   |
| Intel               | 5         | 12     | 5.49%   |
| Crucial             | 3         | 3      | 3.3%    |
| A-DATA Technology   | 3         | 8      | 3.3%    |
| Transcend           | 2         | 2      | 2.2%    |
| SanDisk             | 2         | 2      | 2.2%    |
| NVMe                | 2         | 3      | 2.2%    |
| Lexar               | 2         | 3      | 2.2%    |
| UMIS                | 1         | 1      | 1.1%    |
| Star Drive          | 1         | 1      | 1.1%    |
| SK hynix            | 1         | 1      | 1.1%    |
| Phison              | 1         | 1      | 1.1%    |
| OCZ                 | 1         | 1      | 1.1%    |
| Micron Technology   | 1         | 1      | 1.1%    |
| LITEON              | 1         | 2      | 1.1%    |
| Kston               | 1         | 2      | 1.1%    |
| KIOXIA              | 1         | 1      | 1.1%    |
| KingDian            | 1         | 1      | 1.1%    |
| HPE                 | 1         | 5      | 1.1%    |
| HGST                | 1         | 34     | 1.1%    |
| Hewlett-Packard     | 1         | 1      | 1.1%    |
| Fujitsu             | 1         | 1      | 1.1%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB          | 3         | 3.19%   |
| WDC WDS500G2B0A-00SM50 500GB         | 2         | 2.13%   |
| WDC WDS500G2B0A 500GB                | 1         | 1.06%   |
| WDC WDS200T2B0A 2TB                  | 1         | 1.06%   |
| WDC WDBNCE0010PNC 1TB                | 1         | 1.06%   |
| WDC WD7500BPKX-75HPJT0 752GB         | 1         | 1.06%   |
| WDC WD7500BPKX-00HPJT0 752GB         | 1         | 1.06%   |
| WDC WD7500BPKT-75PK4T0 752GB         | 1         | 1.06%   |
| WDC WD7500BPKT-00PK4T0 752GB         | 1         | 1.06%   |
| WDC WD6400BEVT-22A0RT0 640GB         | 1         | 1.06%   |
| WDC WD5000LPLX-00ZNTT0 500GB         | 1         | 1.06%   |
| WDC WD3200LPVX-60V0TT0 320GB         | 1         | 1.06%   |
| WDC WD3200BEVE-00A0HT0 320GB         | 1         | 1.06%   |
| WDC WD10JPVX-75JC3T0 1TB             | 1         | 1.06%   |
| WDC WD10JPVT-00A1YT0 1TB             | 1         | 1.06%   |
| WDC WD10JPLX-00MBPT0 1TB             | 1         | 1.06%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 1         | 1.06%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB   | 1         | 1.06%   |
| WDC PC SN530 SDBPNPZ-256G-1014 256GB | 1         | 1.06%   |
| WDC PC SN530 NVMe 256GB              | 1         | 1.06%   |
| UMIS RPETJ1T24MGE2QDQ 1TB            | 1         | 1.06%   |
| Transcend TSA 240GB                  | 1         | 1.06%   |
| Transcend TS256GMTS952T2 256GB       | 1         | 1.06%   |
| Toshiba THNSNJ128GCSU 128GB          | 1         | 1.06%   |
| Toshiba MQ04ABF100 1TB               | 1         | 1.06%   |
| Toshiba MQ01ABF032 320GB             | 1         | 1.06%   |
| Toshiba MK8025GAS 80GB               | 1         | 1.06%   |
| Toshiba MK5061GSYN 500GB             | 1         | 1.06%   |
| Toshiba MK3259GSXP 320GB             | 1         | 1.06%   |
| Toshiba MK1665GSX 160GB              | 1         | 1.06%   |
| Toshiba KXG6AZNV256G 256GB           | 1         | 1.06%   |
| Toshiba HDWQ140 4TB                  | 1         | 1.06%   |
| Star Drive SATA SSD 240GB            | 1         | 1.06%   |
| SK hynix SC308 SATA 256GB            | 1         | 1.06%   |
| Seagate ST9500420AS 500GB            | 1         | 1.06%   |
| Seagate ST9160821A 160GB             | 1         | 1.06%   |
| Seagate ST500LT032-1E9142 500GB      | 1         | 1.06%   |
| Seagate ST2000LM007-1R8174 2TB       | 1         | 1.06%   |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 1         | 1.06%   |
| Seagate ST1000LM035-1RK172 1TB       | 1         | 1.06%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 11        | 46     | 29.73%  |
| Toshiba | 7         | 17     | 18.92%  |
| Hitachi | 7         | 11     | 18.92%  |
| Seagate | 6         | 12     | 16.22%  |
| NVMe    | 2         | 3      | 5.41%   |
| Lexar   | 1         | 1      | 2.7%    |
| HPE     | 1         | 5      | 2.7%    |
| HGST    | 1         | 34     | 2.7%    |
| Fujitsu | 1         | 1      | 2.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 9         | 11     | 20.93%  |
| Samsung Electronics | 7         | 13     | 16.28%  |
| WDC                 | 5         | 5      | 11.63%  |
| Intel               | 4         | 11     | 9.3%    |
| Transcend           | 2         | 2      | 4.65%   |
| SanDisk             | 2         | 2      | 4.65%   |
| Crucial             | 2         | 2      | 4.65%   |
| A-DATA Technology   | 2         | 7      | 4.65%   |
| Toshiba             | 1         | 1      | 2.33%   |
| Star Drive          | 1         | 1      | 2.33%   |
| SK hynix            | 1         | 1      | 2.33%   |
| OCZ                 | 1         | 1      | 2.33%   |
| Micron Technology   | 1         | 1      | 2.33%   |
| LITEON              | 1         | 2      | 2.33%   |
| Lexar               | 1         | 2      | 2.33%   |
| Kston               | 1         | 2      | 2.33%   |
| KingDian            | 1         | 1      | 2.33%   |
| Hewlett-Packard     | 1         | 1      | 2.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 39        | 66     | 46.99%  |
| HDD  | 34        | 130    | 40.96%  |
| NVMe | 10        | 13     | 12.05%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 70        | 196    | 87.5%   |
| NVMe | 10        | 13     | 12.5%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 54        | 107    | 73.97%  |
| 0.51-1.0   | 15        | 38     | 20.55%  |
| 1.01-2.0   | 3         | 3      | 4.11%   |
| 3.01-4.0   | 1         | 48     | 1.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 23        | 26.14%  |
| 21-50      | 17        | 19.32%  |
| 1-20       | 16        | 18.18%  |
| 251-500    | 13        | 14.77%  |
| 51-100     | 12        | 13.64%  |
| 501-1000   | 6         | 6.82%   |
| 1001-2000  | 1         | 1.14%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 70        | 83.33%  |
| 21-50   | 9         | 10.71%  |
| 51-100  | 4         | 4.76%   |
| 251-500 | 1         | 1.19%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| WDC WDS200T2B0A 2TB           | 1         | 1      | 8.33%   |
| WDC WD6400BEVT-22A0RT0 640GB  | 1         | 1      | 8.33%   |
| Toshiba MK1665GSX 160GB       | 1         | 1      | 8.33%   |
| Seagate ST9500420AS 500GB     | 1         | 2      | 8.33%   |
| Kingston SV300S37A60G 64GB    | 1         | 2      | 8.33%   |
| Kingston SUV400S37240G 240GB  | 1         | 1      | 8.33%   |
| Kingston SNS4151S316GD 16GB   | 1         | 1      | 8.33%   |
| Kingston SNS4151S316G 16GB    | 1         | 1      | 8.33%   |
| Intel SSDSC2CW120A3 120GB     | 1         | 1      | 8.33%   |
| Hitachi HTS547575A9E384 752GB | 1         | 1      | 8.33%   |
| Hitachi HTS541612J9SA00 120GB | 1         | 1      | 8.33%   |
| A-DATA Technology SP550 480GB | 1         | 6      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Kingston          | 4         | 5      | 33.33%  |
| WDC               | 2         | 2      | 16.67%  |
| Hitachi           | 2         | 2      | 16.67%  |
| Toshiba           | 1         | 1      | 8.33%   |
| Seagate           | 1         | 2      | 8.33%   |
| Intel             | 1         | 1      | 8.33%   |
| A-DATA Technology | 1         | 6      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 2         | 2      | 40%     |
| WDC     | 1         | 1      | 20%     |
| Toshiba | 1         | 1      | 20%     |
| Seagate | 1         | 2      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 7         | 13     | 58.33%  |
| HDD  | 5         | 6      | 41.67%  |

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
| Works    | 68        | 185    | 80.95%  |
| Malfunc  | 12        | 19     | 14.29%  |
| Detected | 4         | 5      | 4.76%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 65        | 73.86%  |
| SanDisk                                 | 5         | 5.68%   |
| AMD                                     | 4         | 4.55%   |
| Samsung Electronics                     | 3         | 3.41%   |
| Toshiba                                 | 2         | 2.27%   |
| Nvidia                                  | 2         | 2.27%   |
| Shenzhen Unionmemory Information System | 1         | 1.14%   |
| Realtek Semiconductor                   | 1         | 1.14%   |
| Phison Electronics                      | 1         | 1.14%   |
| Micron/Crucial Technology               | 1         | 1.14%   |
| MAXIO Technology (Hangzhou)             | 1         | 1.14%   |
| Kingston Technology Company             | 1         | 1.14%   |
| Broadcom / LSI                          | 1         | 1.14%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 15        | 16.3%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 7         | 7.61%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 6         | 6.52%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 5         | 5.43%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 5         | 5.43%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 5         | 5.43%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 4         | 4.35%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 4         | 4.35%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                   | 3         | 3.26%   |
| Toshiba XG6 NVMe SSD Controller                                                        | 2         | 2.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 2         | 2.17%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 2         | 2.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 2         | 2.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 2         | 2.17%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 2         | 2.17%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 2         | 2.17%   |
| Shenzhen Unionmemory Information System AM630 PCIe 4.0 NVMe SSD 1024GB                 | 1         | 1.09%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                              | 1         | 1.09%   |
| SanDisk IX SN530 NVMe SSD (DRAM-less)                                                  | 1         | 1.09%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 1.09%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                      | 1         | 1.09%   |
| Phison E12 NVMe Controller                                                             | 1         | 1.09%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                               | 1         | 1.09%   |
| Nvidia MCP79 AHCI Controller                                                           | 1         | 1.09%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                   | 1         | 1.09%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                           | 1         | 1.09%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                               | 1         | 1.09%   |
| Intel SSD 670p Series [Keystone Harbor]                                                | 1         | 1.09%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 1         | 1.09%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 1         | 1.09%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 1         | 1.09%   |
| Intel 82801CAM IDE U100 Controller                                                     | 1         | 1.09%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 1         | 1.09%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 1         | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller          | 1         | 1.09%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 1         | 1.09%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 1         | 1.09%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                           | 1         | 1.09%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 63        | 72.41%  |
| NVMe | 14        | 16.09%  |
| IDE  | 7         | 8.05%   |
| RAID | 2         | 2.3%    |
| SAS  | 1         | 1.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 77        | 92.77%  |
| AMD     | 5         | 6.02%   |
| Unknown | 1         | 1.2%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz                             | 6         | 6.98%   |
| Intel Core i5-2520M CPU @ 2.50GHz                             | 4         | 4.65%   |
| Intel Core i5 CPU M 520 @ 2.40GHz                             | 3         | 3.49%   |
| Intel CPU Version                                             | 2         | 2.33%   |
| Intel Core i7-3630QM CPU @ 2.40GHz                            | 2         | 2.33%   |
| Intel Core i5-7200U CPU @ 2.50GHz                             | 2         | 2.33%   |
| Intel Core i5-5300U CPU @ 2.30GHz                             | 2         | 2.33%   |
| Intel Core i5-4210U CPU @ 1.70GHz                             | 2         | 2.33%   |
| Intel Core i5-3320M CPU @ 2.60GHz                             | 2         | 2.33%   |
| Intel Core i3-7100U CPU @ 2.40GHz                             | 2         | 2.33%   |
| Intel Celeron CPU 1037U @ 1.80GHz                             | 2         | 2.33%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GH                            | 1         | 1.16%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz                   | 1         | 1.16%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz                   | 1         | 1.16%   |
| Intel Pentium CPU N4200 @ 1.10GHz                             | 1         | 1.16%   |
| Intel Pentium 4 Mobile CPU 1.60GHz ("GenuineIntel" 686-class) | 1         | 1.16%   |
| Intel Pentium 4 Mobile CPU 1.60GHz                            | 1         | 1.16%   |
| Intel Genuine CPU T2300 @ 1.66GHz                             | 1         | 1.16%   |
| Intel CPU T2300 @ 1.66GHz ("GenuineIntel" 686-class)          | 1         | 1.16%   |
| Intel Core i7-8750H CPU @ 2.20GHz                             | 1         | 1.16%   |
| Intel Core i7-8650U CPU @ 1.90GHz                             | 1         | 1.16%   |
| Intel Core i7-7600U CPU @ 2.80GHz                             | 1         | 1.16%   |
| Intel Core i7-6600U CPU @ 2.60GHz                             | 1         | 1.16%   |
| Intel Core i7-5500U CPU @ 2.40GHz                             | 1         | 1.16%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz                            | 1         | 1.16%   |
| Intel Core i7-3520M CPU @ 2.90GHz                             | 1         | 1.16%   |
| Intel Core i7-10750H CPU @ 2.60GHz                            | 1         | 1.16%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz                            | 1         | 1.16%   |
| Intel Core i5-8265U CPU @ 1.60GHz                             | 1         | 1.16%   |
| Intel Core i5-8250U CPU @ 1.60GHz                             | 1         | 1.16%   |
| Intel Core i5-7300U CPU @ 2.60GHz                             | 1         | 1.16%   |
| Intel Core i5-6200U CPU @ 2.30GHz                             | 1         | 1.16%   |
| Intel Core i5-5200U CPU @ 2.20GHz                             | 1         | 1.16%   |
| Intel Core i5-4310U CPU @ 2.00GHz                             | 1         | 1.16%   |
| Intel Core i5-4300U CPU @ 1.90GHz                             | 1         | 1.16%   |
| Intel Core i5-2410M CPU @ 2.30GHz                             | 1         | 1.16%   |
| Intel Core i5 CPU M 540 @ 2.53GHz                             | 1         | 1.16%   |
| Intel Core i5 CPU M 430 @ 2.27GH                              | 1         | 1.16%   |
| Intel Core i3-6100U CPU @ 2.30GHz                             | 1         | 1.16%   |
| Intel Core i3-5020U CPU @ 2.20GHz                             | 1         | 1.16%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 31        | 36.9%   |
| Intel Core i7           | 11        | 13.1%   |
| Other                   | 8         | 9.52%   |
| Intel Core i3           | 8         | 9.52%   |
| Intel Celeron           | 6         | 7.14%   |
| Intel Core 2 Duo        | 5         | 5.95%   |
| Intel Atom              | 4         | 4.76%   |
| Intel Pentium Dual-Core | 2         | 2.38%   |
| Intel Xeon              | 1         | 1.19%   |
| Intel Pentium 4         | 1         | 1.19%   |
| Intel Pentium           | 1         | 1.19%   |
| Intel Genuine           | 1         | 1.19%   |
| AMD Ryzen 9             | 1         | 1.19%   |
| AMD Ryzen 7             | 1         | 1.19%   |
| AMD Ryzen 5             | 1         | 1.19%   |
| AMD EPYC                | 1         | 1.19%   |
| AMD E1                  | 1         | 1.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 52        | 62.65%  |
| 4       | 12        | 14.46%  |
| Unknown | 10        | 12.05%  |
| 8       | 2         | 2.41%   |
| 6       | 2         | 2.41%   |
| 1       | 2         | 2.41%   |
| 16      | 1         | 1.2%    |
| 12      | 1         | 1.2%    |
| 10      | 1         | 1.2%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 80        | 93.02%  |
| Unknown | 4         | 4.65%   |
| 2       | 2         | 2.33%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 58        | 69.88%  |
| 1       | 14        | 16.87%  |
| Unknown | 11        | 13.25%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Skylake     | 10        | 11.76%  |
| KabyLake    | 10        | 11.76%  |
| IvyBridge   | 8         | 9.41%   |
| Penryn      | 7         | 8.24%   |
| Haswell     | 7         | 8.24%   |
| Broadwell   | 7         | 8.24%   |
| SandyBridge | 6         | 7.06%   |
| Unknown     | 6         | 7.06%   |
| Westmere    | 4         | 4.71%   |
| Bonnell     | 4         | 4.71%   |
| TigerLake   | 3         | 3.53%   |
| Zen+        | 1         | 1.18%   |
| Zen 3       | 1         | 1.18%   |
| Zen 2       | 1         | 1.18%   |
| Zen         | 1         | 1.18%   |
| Silvermont  | 1         | 1.18%   |
| P6          | 1         | 1.18%   |
| NetBurst    | 1         | 1.18%   |
| Nehalem     | 1         | 1.18%   |
| Jaguar      | 1         | 1.18%   |
| IceLake     | 1         | 1.18%   |
| Goldmont    | 1         | 1.18%   |
| Core        | 1         | 1.18%   |
| CometLake   | 1         | 1.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor         | Notebooks | Percent |
|----------------|-----------|---------|
| Intel          | 68        | 76.4%   |
| Nvidia         | 12        | 13.48%  |
| AMD            | 8         | 8.99%   |
| Silicon Motion | 1         | 1.12%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 9.68%   |
| Intel HD Graphics 5500                                                                   | 7         | 7.53%   |
| Intel HD Graphics 620                                                                    | 6         | 6.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 6.45%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 6.45%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 6.45%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 4.3%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 3.23%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 3.23%   |
| Nvidia GK107M [GeForce GTX 660M]                                                         | 2         | 2.15%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 2         | 2.15%   |
| Intel UHD Graphics 620                                                                   | 2         | 2.15%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 2.15%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 2.15%   |
| Silicon Motion SM712 LynxEM+                                                             | 1         | 1.08%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 1.08%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 1.08%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 1.08%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 1.08%   |
| Nvidia GK106M [GeForce GTX 765M]                                                         | 1         | 1.08%   |
| Nvidia GF119M [GeForce GT 520M]                                                          | 1         | 1.08%   |
| Nvidia G86M [GeForce 8400M GS]                                                           | 1         | 1.08%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 1.08%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.08%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 1         | 1.08%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.08%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.08%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 1.08%   |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 1.08%   |
| Intel Iris Plus Graphics G7                                                              | 1         | 1.08%   |
| Intel HD Graphics 510                                                                    | 1         | 1.08%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.08%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.08%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 1.08%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1         | 1.08%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 1         | 1.08%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 1         | 1.08%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.08%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 1.08%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 53        | 63.86%  |
| 2 x Intel          | 9         | 10.84%  |
| 1 x Nvidia         | 6         | 7.23%   |
| 1 x AMD            | 6         | 7.23%   |
| Intel + Nvidia     | 5         | 6.02%   |
| Other              | 1         | 1.2%    |
| 1 x Silicon Motion | 1         | 1.2%    |
| Intel + AMD        | 1         | 1.2%    |
| AMD + Nvidia       | 1         | 1.2%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 78        | 92.86%  |
| Proprietary | 4         | 4.76%   |
| Unknown     | 2         | 2.38%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 75        | 88.24%  |
| 3.01-4.0   | 3         | 3.53%   |
| 0.01-0.5   | 3         | 3.53%   |
| 1.01-2.0   | 2         | 2.35%   |
| 0.51-1.0   | 2         | 2.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 10        | 20.41%  |
| Chimei Innolux          | 9         | 18.37%  |
| BOE                     | 7         | 14.29%  |
| Samsung Electronics     | 6         | 12.24%  |
| AU Optronics            | 6         | 12.24%  |
| Lenovo                  | 3         | 6.12%   |
| Chi Mei Optoelectronics | 3         | 6.12%   |
| Goldstar                | 2         | 4.08%   |
| Toshiba                 | 1         | 2.04%   |
| Apple                   | 1         | 2.04%   |
| Acer                    | 1         | 2.04%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch               | 2         | 4.08%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 310x170mm 13.9-inch          | 2         | 4.08%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch            | 2         | 4.08%   |
| Toshiba LCD Monitor LCD0905 1366x768 290x170mm 13.2-inch                  | 1         | 2.04%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 470x300mm 22.0-inch      | 1         | 2.04%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch      | 1         | 2.04%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 330x210mm 15.4-inch      | 1         | 2.04%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch      | 1         | 2.04%   |
| Samsung Electronics LCD Monitor SEC3050 1366x768 320x190mm 14.7-inch      | 1         | 2.04%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 310x170mm 13.9-inch      | 1         | 2.04%   |
| LG Display LCD Monitor LGD0484 1366x768 340x190mm 15.3-inch               | 1         | 2.04%   |
| LG Display LCD Monitor LGD045E 1366x768 310x170mm 13.9-inch               | 1         | 2.04%   |
| LG Display LCD Monitor LGD0456 1366x768 340x190mm 15.3-inch               | 1         | 2.04%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x170mm 13.9-inch               | 1         | 2.04%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch               | 1         | 2.04%   |
| LG Display LCD Monitor LGD021D 1600x900 380x210mm 17.1-inch               | 1         | 2.04%   |
| LG Display LCD Monitor LGD0215 1920x1080 350x190mm 15.7-inch              | 1         | 2.04%   |
| LG Display LCD Monitor LGD01E9 1920x1080 350x190mm 15.7-inch              | 1         | 2.04%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch                   | 1         | 2.04%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch                   | 1         | 2.04%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch                   | 1         | 2.04%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch                | 1         | 2.04%   |
| Goldstar L1920P GSM4A7B 1280x1024 380x300mm 19.1-inch                     | 1         | 2.04%   |
| Chimei Innolux LCD Monitor CMN15F4 1920x1080 340x190mm 15.3-inch          | 1         | 2.04%   |
| Chimei Innolux LCD Monitor CMN14B7 1366x768 310x170mm 13.9-inch           | 1         | 2.04%   |
| Chimei Innolux LCD Monitor CMN1492 1366x768 310x170mm 13.9-inch           | 1         | 2.04%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 310x170mm 13.9-inch           | 1         | 2.04%   |
| Chimei Innolux LCD Monitor CMN1367 1920x1080 290x170mm 13.2-inch          | 1         | 2.04%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 280x160mm 12.7-inch          | 1         | 2.04%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch           | 1         | 2.04%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 380x210mm 17.1-inch | 1         | 2.04%   |
| Chi Mei Optoelectronics LCD Monitor CMO1333 1366x768 290x160mm 13.0-inch  | 1         | 2.04%   |
| Chi Mei Optoelectronics LCD Monitor CMO1312 1280x800 290x180mm 13.4-inch  | 1         | 2.04%   |
| BOE LCD Monitor BOE08E8 1920x1080 340x190mm 15.3-inch                     | 1         | 2.04%   |
| BOE LCD Monitor BOE08BC 2256x1504 280x190mm 13.3-inch                     | 1         | 2.04%   |
| BOE LCD Monitor BOE0817 1366x768 340x190mm 15.3-inch                      | 1         | 2.04%   |
| BOE LCD Monitor BOE07C9 1920x1080 300x170mm 13.6-inch                     | 1         | 2.04%   |
| BOE LCD Monitor BOE0742 1920x1080 310x170mm 13.9-inch                     | 1         | 2.04%   |
| BOE LCD Monitor BOE06C2 1366x768 340x190mm 15.3-inch                      | 1         | 2.04%   |
| BOE LCD Monitor BOE06B3 1366x768 310x170mm 13.9-inch                      | 1         | 2.04%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 18        | 36.73%  |
| 1366x768 (WXGA)    | 17        | 34.69%  |
| 1600x900 (HD+)     | 5         | 10.2%   |
| 1280x800 (WXGA)    | 4         | 8.16%   |
| 2560x1080          | 1         | 2.04%   |
| 2256x1504          | 1         | 2.04%   |
| 1680x1050 (WSXGA+) | 1         | 2.04%   |
| 1280x854           | 1         | 2.04%   |
| 1280x1024 (SXGA)   | 1         | 2.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 18        | 36.73%  |
| 15     | 14        | 28.57%  |
| 12     | 7         | 14.29%  |
| 14     | 3         | 6.12%   |
| 17     | 2         | 4.08%   |
| 34     | 1         | 2.04%   |
| 27     | 1         | 2.04%   |
| 22     | 1         | 2.04%   |
| 19     | 1         | 2.04%   |
| 11     | 1         | 2.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 27        | 55.1%   |
| 201-300     | 16        | 32.65%  |
| 351-400     | 3         | 6.12%   |
| 701-800     | 1         | 2.04%   |
| 501-600     | 1         | 2.04%   |
| 401-500     | 1         | 2.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 38        | 79.17%  |
| 16/10 | 6         | 12.5%   |
| 3/2   | 2         | 4.17%   |
| 5/4   | 1         | 2.08%   |
| 21/9  | 1         | 2.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 16        | 32.65%  |
| 91-100         | 8         | 16.33%  |
| 61-70          | 7         | 14.29%  |
| 101-110        | 7         | 14.29%  |
| 71-80          | 4         | 8.16%   |
| 121-130        | 2         | 4.08%   |
| 51-60          | 1         | 2.04%   |
| 351-500        | 1         | 2.04%   |
| 301-350        | 1         | 2.04%   |
| 201-250        | 1         | 2.04%   |
| 151-200        | 1         | 2.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 20        | 40.82%  |
| 101-120 | 16        | 32.65%  |
| 51-100  | 7         | 14.29%  |
| 161-240 | 6         | 12.24%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 58        | 67.44%  |
| 0     | 26        | 30.23%  |
| 2     | 2         | 2.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 57        | 48.72%  |
| Realtek Semiconductor             | 23        | 19.66%  |
| Qualcomm Atheros                  | 18        | 15.38%  |
| Broadcom                          | 6         | 5.13%   |
| Sierra Wireless                   | 2         | 1.71%   |
| Ericsson Business Mobile Networks | 2         | 1.71%   |
| Ralink Technology                 | 1         | 0.85%   |
| Ralink                            | 1         | 0.85%   |
| Nvidia                            | 1         | 0.85%   |
| NetGear                           | 1         | 0.85%   |
| MediaTek                          | 1         | 0.85%   |
| Marvell Technology Group          | 1         | 0.85%   |
| JMicron Technology                | 1         | 0.85%   |
| Apple                             | 1         | 0.85%   |
| AMD                               | 1         | 0.85%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 8.02%   |
| Intel Ethernet Connection I219-LM                                 | 9         | 5.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 4.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 4.94%   |
| Intel Wireless 8260                                               | 7         | 4.32%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 7         | 4.32%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 2.47%   |
| Intel Wireless 8265 / 8275                                        | 4         | 2.47%   |
| Intel Wireless 7265                                               | 4         | 2.47%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 2.47%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 3         | 1.85%   |
| Intel Wireless 7260                                               | 3         | 1.85%   |
| Intel Wireless 3165                                               | 3         | 1.85%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.85%   |
| Intel Centrino Advanced-N 6200                                    | 3         | 1.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 1.23%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 2         | 1.23%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.23%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 1.23%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.23%   |
| Intel I210 Gigabit Network Connection                             | 2         | 1.23%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.23%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.23%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 1.23%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 2         | 1.23%   |
| Sierra Wireless EM7455                                            | 1         | 0.62%   |
| Sierra Wireless EM7305 Modem                                      | 1         | 0.62%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.62%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 0.62%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.62%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 0.62%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.62%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1         | 0.62%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 1         | 0.62%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 0.62%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 0.62%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.62%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.62%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.62%   |
| Qualcomm Atheros AR5212 802.11abg NIC                             | 1         | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 50        | 64.94%  |
| Qualcomm Atheros      | 12        | 15.58%  |
| Broadcom              | 6         | 7.79%   |
| Realtek Semiconductor | 4         | 5.19%   |
| Sierra Wireless       | 1         | 1.3%    |
| Ralink Technology     | 1         | 1.3%    |
| Ralink                | 1         | 1.3%    |
| NetGear               | 1         | 1.3%    |
| MediaTek              | 1         | 1.3%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                                     | 7         | 8.97%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 8.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 5.13%   |
| Intel Wireless 8265 / 8275                                              | 4         | 5.13%   |
| Intel Wireless 7265                                                     | 4         | 5.13%   |
| Intel Wireless 7260                                                     | 3         | 3.85%   |
| Intel Wireless 3165                                                     | 3         | 3.85%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 3.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 2.56%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 2.56%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 2.56%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 2         | 2.56%   |
| Sierra Wireless EM7455                                                  | 1         | 1.28%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 1.28%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 1.28%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.28%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 1.28%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 1.28%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                               | 1         | 1.28%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.28%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 1.28%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 1.28%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 1         | 1.28%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.28%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]             | 1         | 1.28%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 1.28%   |
| Intel Wireless-AC 9260                                                  | 1         | 1.28%   |
| Intel Wireless 3160                                                     | 1         | 1.28%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 1         | 1.28%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 1.28%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 1.28%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 1.28%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 1.28%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 1.28%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 1.28%   |
| Intel Centrino Wireless-N 2200                                          | 1         | 1.28%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 1         | 1.28%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 1.28%   |
| Intel Centrino Wireless-N 100                                           | 1         | 1.28%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                    | 1         | 1.28%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 39        | 51.32%  |
| Realtek Semiconductor    | 22        | 28.95%  |
| Qualcomm Atheros         | 9         | 11.84%  |
| Nvidia                   | 1         | 1.32%   |
| Marvell Technology Group | 1         | 1.32%   |
| JMicron Technology       | 1         | 1.32%   |
| Broadcom                 | 1         | 1.32%   |
| Apple                    | 1         | 1.32%   |
| AMD                      | 1         | 1.32%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 16.25%  |
| Intel Ethernet Connection I219-LM                                 | 9         | 11.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 10%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 10%     |
| Intel 82577LM Gigabit Network Connection                          | 4         | 5%      |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 3         | 3.75%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 3.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 2.5%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 2.5%    |
| Intel I210 Gigabit Network Connection                             | 2         | 2.5%    |
| Intel Ethernet Connection I218-LM                                 | 2         | 2.5%    |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 2.5%    |
| Intel 82574L Gigabit Network Connection                           | 2         | 2.5%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.25%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.25%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.25%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.25%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 1.25%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.25%   |
| Intel I350 Gigabit Fiber Network Connection                       | 1         | 1.25%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.25%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.25%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.25%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 1.25%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 1.25%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.25%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 1.25%   |
| Intel 82583V Gigabit Network Connection                           | 1         | 1.25%   |
| Intel 82580 Gigabit Network Connection                            | 1         | 1.25%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.25%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 1.25%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                   | 1         | 1.25%   |
| AMD XGMAC 10GbE Controller                                        | 1         | 1.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 75        | 49.02%  |
| WiFi     | 74        | 48.37%  |
| Unknown  | 3         | 1.96%   |
| Modem    | 1         | 0.65%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 58        | 51.79%  |
| Ethernet | 54        | 48.21%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 67        | 80.72%  |
| 1     | 10        | 12.05%  |
| 3     | 3         | 3.61%   |
| 10    | 1         | 1.2%    |
| 6     | 1         | 1.2%    |
| 4     | 1         | 1.2%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 75        | 87.21%  |
| Yes  | 11        | 12.79%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 28        | 50.91%  |
| Broadcom                        | 5         | 9.09%   |
| IMC Networks                    | 3         | 5.45%   |
| Cambridge Silicon Radio         | 3         | 5.45%   |
| Realtek Semiconductor           | 2         | 3.64%   |
| Qualcomm Atheros Communications | 2         | 3.64%   |
| Lite-On Technology              | 2         | 3.64%   |
| Foxconn / Hon Hai               | 2         | 3.64%   |
| ASUSTek Computer                | 2         | 3.64%   |
| Apple                           | 2         | 3.64%   |
| Alps Electric                   | 2         | 3.64%   |
| Toshiba                         | 1         | 1.82%   |
| Hewlett-Packard                 | 1         | 1.82%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 18        | 32.73%  |
| Intel AX201 Bluetooth                                       | 5         | 9.09%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 3         | 5.45%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 3         | 5.45%   |
| Apple Bluetooth Host Controller                             | 2         | 3.64%   |
| Alps Electric UGTZ4 Bluetooth                               | 2         | 3.64%   |
| Toshiba ASKEY Bluetooth Controller BTU1030                  | 1         | 1.82%   |
| Realtek Bluetooth Adapter                                   | 1         | 1.82%   |
| Realtek Bluetooth 4.0 Adapter                               | 1         | 1.82%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 1.82%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 1.82%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 1.82%   |
| Lite-On Broadcom Bluetooth 4.0 USB                          | 1         | 1.82%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 1.82%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 1.82%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 1         | 1.82%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 1         | 1.82%   |
| Intel AX211 Bluetooth                                       | 1         | 1.82%   |
| IMC Networks MediaTek Bluetooth Adapter                     | 1         | 1.82%   |
| IMC Networks Bluetooth                                      | 1         | 1.82%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 1         | 1.82%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 1.82%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device    | 1         | 1.82%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 1         | 1.82%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 1         | 1.82%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 1         | 1.82%   |
| ASUS Broadcom Bluetooth 2.1                                 | 1         | 1.82%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 1         | 1.82%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 72        | 82.76%  |
| AMD                    | 7         | 8.05%   |
| Nvidia                 | 6         | 6.9%    |
| XMOS                   | 1         | 1.15%   |
| Generalplus Technology | 1         | 1.15%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 17        | 16.35%  |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 6.73%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 6.73%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 5.77%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 5.77%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 5.77%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 5.77%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 4.81%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 4.81%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 3.85%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 2.88%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 2.88%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.92%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 1.92%   |
| XMOS USB Audio                                                                                    | 1         | 0.96%   |
| XMOS iFi (by AMR) HD USB Audio                                                                    | 1         | 0.96%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.96%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.96%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.96%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.96%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 0.96%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 0.96%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.96%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.96%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.96%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 0.96%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 0.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.96%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 0.96%   |
| Intel 82801CA/CAM AC'97 Audio Controller                                                          | 1         | 0.96%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 0.96%   |
| Generalplus Technology USB Audio Device                                                           | 1         | 0.96%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 0.96%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 0.96%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 0.96%   |
| AMD FCH Azalia Controller                                                                         | 1         | 0.96%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 1         | 0.96%   |
| Unknown                                                                                           | 1         | 0.96%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 24        | 28.24%  |
| Samsung Electronics | 19        | 22.35%  |
| Kingston            | 10        | 11.76%  |
| Unknown             | 9         | 10.59%  |
| Micron Technology   | 7         | 8.24%   |
| Unknown             | 4         | 4.71%   |
| Corsair             | 3         | 3.53%   |
| A-DATA Technology   | 2         | 2.35%   |
| Unknown (ABCD)      | 1         | 1.18%   |
| Transcend           | 1         | 1.18%   |
| Ramaxel Technology  | 1         | 1.18%   |
| Nanya Technology    | 1         | 1.18%   |
| G.Skill             | 1         | 1.18%   |
| Elpida              | 1         | 1.18%   |
| Crucial             | 1         | 1.18%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 4         | 4.55%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 3.41%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 3.41%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 2         | 2.27%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 2         | 2.27%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 2.27%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 2         | 2.27%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 1067MT/s            | 2         | 2.27%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 2.27%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                      | 1         | 1.14%   |
| Unknown RAM Module 512MB SODIMM SDRAM                            | 1         | 1.14%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 1.14%   |
| Unknown RAM Module 4096MB SODIMM DDR2                            | 1         | 1.14%   |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s                      | 1         | 1.14%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                           | 1         | 1.14%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 1.14%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 1.14%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s              | 1         | 1.14%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1         | 1.14%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.14%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 1         | 1.14%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.14%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.14%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.14%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.14%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.14%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 1.14%   |
| SK hynix RAM HMT112S6AFP6C-G7 1GB SODIMM 800MT/s                 | 1         | 1.14%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s           | 1         | 1.14%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.14%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.14%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB Row Of Chips DDR4 2400MT/s  | 1         | 1.14%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 1.14%   |
| SK hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 1         | 1.14%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB SODIMM LPDDR3 1867MT/s           | 1         | 1.14%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB Chip LPDDR3 1867MT/s             | 1         | 1.14%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s            | 1         | 1.14%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM 1600MT/s                 | 1         | 1.14%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.14%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.14%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 41        | 52.56%  |
| DDR4    | 21        | 26.92%  |
| DDR2    | 5         | 6.41%   |
| LPDDR4  | 4         | 5.13%   |
| SDRAM   | 3         | 3.85%   |
| LPDDR3  | 2         | 2.56%   |
| DDR5    | 1         | 1.28%   |
| Unknown | 1         | 1.28%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 71        | 91.03%  |
| Row Of Chips | 4         | 5.13%   |
| Chip         | 2         | 2.56%   |
| Unknown      | 1         | 1.28%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 28        | 34.15%  |
| 8192  | 25        | 30.49%  |
| 2048  | 17        | 20.73%  |
| 16384 | 7         | 8.54%   |
| 1024  | 3         | 3.66%   |
| 32768 | 1         | 1.22%   |
| 512   | 1         | 1.22%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 21        | 25.93%  |
| 1333    | 9         | 11.11%  |
| 2667    | 8         | 9.88%   |
| 1067    | 8         | 9.88%   |
| 2400    | 7         | 8.64%   |
| 3200    | 6         | 7.41%   |
| Unknown | 6         | 7.41%   |
| 1334    | 5         | 6.17%   |
| 2133    | 4         | 4.94%   |
| 4267    | 2         | 2.47%   |
| 667     | 2         | 2.47%   |
| 4800    | 1         | 1.23%   |
| 1867    | 1         | 1.23%   |
| 800     | 1         | 1.23%   |

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
| Chicony Electronics           | 18        | 36.73%  |
| Bison Electronics             | 6         | 12.24%  |
| Microdia                      | 5         | 10.2%   |
| Realtek Semiconductor         | 4         | 8.16%   |
| Lite-On Technology            | 3         | 6.12%   |
| IMC Networks                  | 3         | 6.12%   |
| Syntek                        | 2         | 4.08%   |
| Sunplus Innovation Technology | 2         | 4.08%   |
| Suyin                         | 1         | 2.04%   |
| Quanta                        | 1         | 2.04%   |
| Luxvisions Innotech Limited   | 1         | 2.04%   |
| Lenovo                        | 1         | 2.04%   |
| ALi                           | 1         | 2.04%   |
| Alcor Micro                   | 1         | 2.04%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 5         | 10.2%   |
| Bison Integrated Camera                       | 4         | 8.16%   |
| Lite-On Integrated Camera                     | 3         | 6.12%   |
| Chicony HD Webcam                             | 3         | 6.12%   |
| Syntek Lenovo EasyCamera                      | 1         | 2.04%   |
| Syntek Integrated Camera                      | 1         | 2.04%   |
| Suyin Acer/HP Integrated Webcam [CN0314]      | 1         | 2.04%   |
| Sunplus Laptop_Integrated_Webcam_FHD          | 1         | 2.04%   |
| Sunplus ASUS Webcam                           | 1         | 2.04%   |
| Realtek USB 2.0 PC Camera                     | 1         | 2.04%   |
| Realtek Integrated Webcam HD                  | 1         | 2.04%   |
| Realtek Integrated Webcam                     | 1         | 2.04%   |
| Realtek HD Webcam - Realtek                   | 1         | 2.04%   |
| Quanta Realtek PC Camera                      | 1         | 2.04%   |
| Microdia Sonix USB 2.0 Camera                 | 1         | 2.04%   |
| Microdia Laptop_Integrated_Webcam_2M          | 1         | 2.04%   |
| Microdia Integrated_Webcam_HD                 | 1         | 2.04%   |
| Microdia Integrated Webcam HD                 | 1         | 2.04%   |
| Microdia Integrated Webcam                    | 1         | 2.04%   |
| Luxvisions Innotech Limited Integrated Camera | 1         | 2.04%   |
| Lenovo Integrated Webcam [R5U877]             | 1         | 2.04%   |
| IMC Networks UVC VGA Webcam                   | 1         | 2.04%   |
| IMC Networks Integrated Webcam                | 1         | 2.04%   |
| IMC Networks Integrated Camera                | 1         | 2.04%   |
| Chicony WebCam                                | 1         | 2.04%   |
| Chicony VGA 24fps UVC Webcam                  | 1         | 2.04%   |
| Chicony USB2.0 HD UVC WebCam                  | 1         | 2.04%   |
| Chicony TOSHIBA Web Camera - FHD              | 1         | 2.04%   |
| Chicony Sonix ST50220 USB Video Camera        | 1         | 2.04%   |
| Chicony Lenovo Integrated Camera (0.3MP)      | 1         | 2.04%   |
| Chicony Integrated Camera [ThinkPad]          | 1         | 2.04%   |
| Chicony HP HD Camera                          | 1         | 2.04%   |
| Chicony FJ Camera                             | 1         | 2.04%   |
| Chicony 2.0M UVC Webcam / CNF7129             | 1         | 2.04%   |
| Bison ThinkPad P50 Integrated Camera          | 1         | 2.04%   |
| Bison SunplusIT Integrated Camera             | 1         | 2.04%   |
| ALi WebCam                                    | 1         | 2.04%   |
| Alcor Micro USB2.0 Camera                     | 1         | 2.04%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 47.06%  |
| Upek                       | 2         | 11.76%  |
| Synaptics                  | 2         | 11.76%  |
| LighTuning Technology      | 2         | 11.76%  |
| AuthenTec                  | 2         | 11.76%  |
| Shenzhen Goodix Technology | 1         | 5.88%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 3         | 17.65%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 11.76%  |
| LighTuning EgisTec Touch Fingerprint Sensor            | 2         | 11.76%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 5.88%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 5.88%   |
| Validity Sensors VFS Fingerprint sensor                | 1         | 5.88%   |
| Validity Sensors Synaptics WBDI                        | 1         | 5.88%   |
| Validity Sensors Fingerprint scanner                   | 1         | 5.88%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 5.88%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 5.88%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 5.88%   |
| AuthenTec AES2660                                      | 1         | 5.88%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 5.88%   |

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
| 1     | 37        | 43.02%  |
| 2     | 18        | 20.93%  |
| 3     | 14        | 16.28%  |
| 0     | 11        | 12.79%  |
| 4     | 5         | 5.81%   |
| 5     | 1         | 1.16%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 59        | 46.46%  |
| Bluetooth                | 18        | 14.17%  |
| Fingerprint reader       | 13        | 10.24%  |
| Card reader              | 12        | 9.45%   |
| Firewire controller      | 9         | 7.09%   |
| Net/wireless             | 8         | 6.3%    |
| Storage                  | 2         | 1.57%   |
| Graphics card            | 2         | 1.57%   |
| Storage/ata              | 1         | 0.79%   |
| Sound                    | 1         | 0.79%   |
| Network                  | 1         | 0.79%   |
| Net/ethernet             | 1         | 0.79%   |

