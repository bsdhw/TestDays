helloSystem 0.5.0 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for helloSystem 0.5.0 (Beta test).

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://bsd-hardware.info/?view=trends&rel=hellosystem-0.5.0

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

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [62f9376847](https://bsd-hardware.info/?probe=62f9376847) | Sep 04, 2021 |
| Apple         | MacBookAir7,2               | [6eada6e49e](https://bsd-hardware.info/?probe=6eada6e49e) | Aug 28, 2021 |
| Itautec       | Infoway w7530               | [fe69db32c8](https://bsd-hardware.info/?probe=fe69db32c8) | Aug 27, 2021 |
| HP            | Pavilion dv6                | [8054d6310f](https://bsd-hardware.info/?probe=8054d6310f) | Aug 19, 2021 |
| MSI           | GF65 Thin 10SDR             | [7e5ebc9c82](https://bsd-hardware.info/?probe=7e5ebc9c82) | Aug 18, 2021 |
| Toshiba       | Satellite L855              | [116ce6af18](https://bsd-hardware.info/?probe=116ce6af18) | Aug 18, 2021 |
| Dell          | Latitude E5530 non-vPro     | [bd4b0f0700](https://bsd-hardware.info/?probe=bd4b0f0700) | Aug 17, 2021 |
| ASUSTek       | X55CR                       | [c7c812c2c9](https://bsd-hardware.info/?probe=c7c812c2c9) | Aug 15, 2021 |
| HP            | 250 G4                      | [24e8c3de59](https://bsd-hardware.info/?probe=24e8c3de59) | Aug 13, 2021 |
| HP            | 625                         | [606d75e6a1](https://bsd-hardware.info/?probe=606d75e6a1) | Aug 11, 2021 |
| HP            | 250 G4                      | [43a7b112ba](https://bsd-hardware.info/?probe=43a7b112ba) | Aug 11, 2021 |
| Lenovo        | ThinkPad X230 2330A48       | [791c826f7d](https://bsd-hardware.info/?probe=791c826f7d) | Aug 11, 2021 |
| HP            | Pavilion 11                 | [5300a49632](https://bsd-hardware.info/?probe=5300a49632) | Aug 10, 2021 |
| Dell          | G3 3579                     | [91c803fdf2](https://bsd-hardware.info/?probe=91c803fdf2) | Aug 09, 2021 |
| NEC Comput... | PC-VK17HBBCD                | [1e23da04c0](https://bsd-hardware.info/?probe=1e23da04c0) | Aug 08, 2021 |
| Dell          | Inspiron 15-3567            | [9073f1975d](https://bsd-hardware.info/?probe=9073f1975d) | Aug 07, 2021 |
| ASUSTek       | K55VD                       | [6896c37580](https://bsd-hardware.info/?probe=6896c37580) | Aug 06, 2021 |
| Apple         | MacBookPro3,1               | [3566222830](https://bsd-hardware.info/?probe=3566222830) | Aug 04, 2021 |
| Lenovo        | ThinkPad X250 20CLS4JH00    | [89a74889ae](https://bsd-hardware.info/?probe=89a74889ae) | Aug 02, 2021 |
| Sony          | VPCEJ1E1E                   | [c471fb3f82](https://bsd-hardware.info/?probe=c471fb3f82) | Aug 01, 2021 |
| Lenovo        | G550 2958                   | [86880c29cf](https://bsd-hardware.info/?probe=86880c29cf) | Jul 31, 2021 |
| Lenovo        | G550 2958                   | [4fe522eaf3](https://bsd-hardware.info/?probe=4fe522eaf3) | Jul 31, 2021 |
| HP            | 15                          | [c2da1dd654](https://bsd-hardware.info/?probe=c2da1dd654) | Jul 30, 2021 |
| Apple         | MacBookPro6,2               | [7f25ab7c67](https://bsd-hardware.info/?probe=7f25ab7c67) | Jul 26, 2021 |
| Lenovo        | G500 20236                  | [d15eff8bcc](https://bsd-hardware.info/?probe=d15eff8bcc) | Jul 21, 2021 |
| HP            | Stream 11 Pro G4 EE         | [bd2bf6b0a0](https://bsd-hardware.info/?probe=bd2bf6b0a0) | Jul 20, 2021 |
| Apple         | MacBookPro9,2               | [6cca4dee6f](https://bsd-hardware.info/?probe=6cca4dee6f) | Jul 15, 2021 |
| Alienware     | 17                          | [aff2be63cd](https://bsd-hardware.info/?probe=aff2be63cd) | Jul 10, 2021 |
| MouseCompu... | W331AU                      | [f9a4733911](https://bsd-hardware.info/?probe=f9a4733911) | Jul 06, 2021 |
| MouseCompu... | W331AU                      | [4adfeaa072](https://bsd-hardware.info/?probe=4adfeaa072) | Jul 06, 2021 |
| HP            | ProBook 4440s               | [4aac49bc1e](https://bsd-hardware.info/?probe=4aac49bc1e) | Jul 01, 2021 |
| Lenovo        | ThinkPad X200 7458VP4       | [42100d8ea1](https://bsd-hardware.info/?probe=42100d8ea1) | Jun 30, 2021 |
| HP            | Pavilion 17                 | [9929e0c39b](https://bsd-hardware.info/?probe=9929e0c39b) | Jun 30, 2021 |
| Dell          | Latitude E6410              | [8c904d84e0](https://bsd-hardware.info/?probe=8c904d84e0) | Jun 28, 2021 |
| Lenovo        | G500 20236                  | [6e96d4c26f](https://bsd-hardware.info/?probe=6e96d4c26f) | Jun 28, 2021 |
| Lenovo        | G500 20236                  | [7ae63d4c6c](https://bsd-hardware.info/?probe=7ae63d4c6c) | Jun 27, 2021 |
| Lenovo        | ThinkPad L450 20DTCTO1WW    | [aba7b76575](https://bsd-hardware.info/?probe=aba7b76575) | Jun 27, 2021 |
| ASUSTek       | Strix 17 GL703GE            | [1697ebb0a5](https://bsd-hardware.info/?probe=1697ebb0a5) | Jun 25, 2021 |
| Acer          | Aspire 5750                 | [d59f20f88a](https://bsd-hardware.info/?probe=d59f20f88a) | Jun 22, 2021 |
| Dell          | Precision 7710              | [33653d0c28](https://bsd-hardware.info/?probe=33653d0c28) | Jun 22, 2021 |
| Lenovo        | ThinkPad X230 2325WWB       | [786669cc9c](https://bsd-hardware.info/?probe=786669cc9c) | Jun 21, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | [46dca136f6](https://bsd-hardware.info/?probe=46dca136f6) | Jun 21, 2021 |
| Lenovo        | ThinkPad T470p 20J6A012C... | [d5e4c49986](https://bsd-hardware.info/?probe=d5e4c49986) | Jun 21, 2021 |
| Acer          | Aspire 5750                 | [cc6dc71d37](https://bsd-hardware.info/?probe=cc6dc71d37) | Jun 21, 2021 |
| Toshiba       | PORTEGE Z10t-A              | [cb7cbd17d0](https://bsd-hardware.info/?probe=cb7cbd17d0) | Jun 20, 2021 |
| Gateway       | NE56R                       | [cc65e24aea](https://bsd-hardware.info/?probe=cc65e24aea) | Jun 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [0fe1337b93](https://bsd-hardware.info/?probe=0fe1337b93) | Jun 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [902b4298d4](https://bsd-hardware.info/?probe=902b4298d4) | Jun 19, 2021 |
| WYSE          | Z CLASS                     | [571fdbf390](https://bsd-hardware.info/?probe=571fdbf390) | Jun 19, 2021 |
| Dell          | Latitude E5420              | [1ed3ff35f6](https://bsd-hardware.info/?probe=1ed3ff35f6) | Jun 19, 2021 |
| Dell          | Vostro 3560                 | [ce9d5f9a46](https://bsd-hardware.info/?probe=ce9d5f9a46) | Jun 18, 2021 |
| Lenovo        | ThinkPad Edge E530 62724... | [78abd376db](https://bsd-hardware.info/?probe=78abd376db) | Jun 18, 2021 |
| Lenovo        | ThinkPad T420 4236FJ1       | [808f58228e](https://bsd-hardware.info/?probe=808f58228e) | Jun 17, 2021 |
| Toshiba       | PORTEGE R930                | [db520e9382](https://bsd-hardware.info/?probe=db520e9382) | Jun 15, 2021 |
| Toshiba       | Satellite C640              | [ec0d93d08c](https://bsd-hardware.info/?probe=ec0d93d08c) | Jun 15, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | [9ae8146589](https://bsd-hardware.info/?probe=9ae8146589) | Jun 15, 2021 |
| Dell          | Latitude 5400               | [1bb6c1f63f](https://bsd-hardware.info/?probe=1bb6c1f63f) | Jun 15, 2021 |
| Dell          | Inspiron 15-3567            | [53049dff12](https://bsd-hardware.info/?probe=53049dff12) | Jun 14, 2021 |
| HP            | OMEN by HP Laptop           | [abc94e9198](https://bsd-hardware.info/?probe=abc94e9198) | Jun 13, 2021 |
| HP            | 255 G2                      | [31177d9e0f](https://bsd-hardware.info/?probe=31177d9e0f) | Jun 13, 2021 |
| Lenovo        | ThinkPad T430 2349GCU       | [ca15c7d742](https://bsd-hardware.info/?probe=ca15c7d742) | Jun 13, 2021 |
| Gateway       | NE56R                       | [932f5d03f3](https://bsd-hardware.info/?probe=932f5d03f3) | Jun 13, 2021 |
| Dell          | Latitude E4300              | [7855973957](https://bsd-hardware.info/?probe=7855973957) | Jun 12, 2021 |
| Dell          | Inspiron 15-3567            | [d239ee4916](https://bsd-hardware.info/?probe=d239ee4916) | Jun 12, 2021 |
| Lenovo        | ThinkPad X240 20AMS39F0K    | [65564434a9](https://bsd-hardware.info/?probe=65564434a9) | Jun 12, 2021 |
| ASUSTek       | UX330UAK                    | [430c90b88d](https://bsd-hardware.info/?probe=430c90b88d) | Jun 12, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | [b644ed3914](https://bsd-hardware.info/?probe=b644ed3914) | Mar 31, 2021 |
| Dell          | Vostro 14-3468              | [219133fc53](https://bsd-hardware.info/?probe=219133fc53) | Mar 30, 2021 |
| Dell          | Vostro 14-3468              | [2c61fcee12](https://bsd-hardware.info/?probe=2c61fcee12) | Mar 30, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | [a5b9f5e79d](https://bsd-hardware.info/?probe=a5b9f5e79d) | Mar 27, 2021 |
| Lenovo        | ThinkPad X230 23255Y4       | [ab871769f0](https://bsd-hardware.info/?probe=ab871769f0) | Mar 27, 2021 |
| Toshiba       | Satellite L500              | [e07fd4edd9](https://bsd-hardware.info/?probe=e07fd4edd9) | Mar 25, 2021 |
| HP            | Pavilion Notebook           | [42ecf97502](https://bsd-hardware.info/?probe=42ecf97502) | Mar 25, 2021 |
| HP            | Pavilion Notebook           | [88e98e18a5](https://bsd-hardware.info/?probe=88e98e18a5) | Mar 25, 2021 |
| ASUSTek       | G75VW                       | [9b84d1e7e6](https://bsd-hardware.info/?probe=9b84d1e7e6) | Mar 24, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | [d856b5bf95](https://bsd-hardware.info/?probe=d856b5bf95) | Mar 23, 2021 |
| Samsung       | 530U3C/530U4C/532U3C        | [10c79ea427](https://bsd-hardware.info/?probe=10c79ea427) | Mar 22, 2021 |
| Lenovo        | ThinkPad X260 20F5S82N00    | [aa3deadedd](https://bsd-hardware.info/?probe=aa3deadedd) | Mar 19, 2021 |
| Dell          | Inspiron 7520               | [599d3e84d7](https://bsd-hardware.info/?probe=599d3e84d7) | Mar 16, 2021 |
| TUXEDO        | Aura 15 Gen1                | [860b1cd65b](https://bsd-hardware.info/?probe=860b1cd65b) | Mar 15, 2021 |
| Packard Be... | EasyNote MH36               | [2a98cae4e8](https://bsd-hardware.info/?probe=2a98cae4e8) | Mar 13, 2021 |
| Fujitsu       | LIFEBOOK A555               | [bcb99d0f09](https://bsd-hardware.info/?probe=bcb99d0f09) | Mar 13, 2021 |
| Fujitsu       | LIFEBOOK A555               | [ee894449af](https://bsd-hardware.info/?probe=ee894449af) | Mar 13, 2021 |
| Dell          | Inspiron 7520               | [0054ef2511](https://bsd-hardware.info/?probe=0054ef2511) | Mar 13, 2021 |
| Dell          | Inspiron 3543               | [525eeec663](https://bsd-hardware.info/?probe=525eeec663) | Mar 12, 2021 |
| Acer          | Aspire 4810T                | [14af887195](https://bsd-hardware.info/?probe=14af887195) | Mar 11, 2021 |
| Lenovo        | B41-80 80LG                 | [d598cc6240](https://bsd-hardware.info/?probe=d598cc6240) | Mar 11, 2021 |
| TUXEDO        | Aura 15 Gen1                | [9a7f08f8c1](https://bsd-hardware.info/?probe=9a7f08f8c1) | Mar 11, 2021 |
| TUXEDO        | Aura 15 Gen1                | [d9661207d7](https://bsd-hardware.info/?probe=d9661207d7) | Mar 11, 2021 |
| Toshiba       | Satellite Pro U400          | [71fd81df30](https://bsd-hardware.info/?probe=71fd81df30) | Mar 07, 2021 |
| ASUSTek       | X556UA                      | [57018edd10](https://bsd-hardware.info/?probe=57018edd10) | Mar 07, 2021 |
| Dell          | Latitude E6500              | [d25dacc162](https://bsd-hardware.info/?probe=d25dacc162) | Mar 07, 2021 |
| Dell          | Latitude E5570              | [12eae7a62e](https://bsd-hardware.info/?probe=12eae7a62e) | Mar 05, 2021 |
| HP            | EliteBook 820 G1            | [de98cd5952](https://bsd-hardware.info/?probe=de98cd5952) | Mar 04, 2021 |
| HP            | EliteBook 820 G1            | [03c5808adf](https://bsd-hardware.info/?probe=03c5808adf) | Mar 04, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [d129752b43](https://bsd-hardware.info/?probe=d129752b43) | Mar 04, 2021 |
| Acer          | Aspire 8730                 | [33e7d80b63](https://bsd-hardware.info/?probe=33e7d80b63) | Mar 01, 2021 |
| Hampoo        | B3W6_NA123C Reserved        | [bc138c0580](https://bsd-hardware.info/?probe=bc138c0580) | Feb 27, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [5211d36066](https://bsd-hardware.info/?probe=5211d36066) | Feb 25, 2021 |
| Lenovo        | ThinkPad T470p 20J6A012C... | [cbaa19611e](https://bsd-hardware.info/?probe=cbaa19611e) | Feb 24, 2021 |
| Dell          | XPS 13 9333                 | [7c78b3d42a](https://bsd-hardware.info/?probe=7c78b3d42a) | Feb 24, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [467a915fc7](https://bsd-hardware.info/?probe=467a915fc7) | Feb 23, 2021 |
| LG Electro... | 14Z980-G.BH51P1             | [d8ee6bc4e3](https://bsd-hardware.info/?probe=d8ee6bc4e3) | Feb 22, 2021 |
| Dell          | Latitude E7240              | [e42e579971](https://bsd-hardware.info/?probe=e42e579971) | Feb 22, 2021 |
| Lenovo        | G470 20078                  | [b8e35aacdb](https://bsd-hardware.info/?probe=b8e35aacdb) | Feb 22, 2021 |
| Apple         | MacBookPro9,2               | [a7d9aeda81](https://bsd-hardware.info/?probe=a7d9aeda81) | Feb 22, 2021 |
| HP            | EliteBook 8540p             | [78d9a31074](https://bsd-hardware.info/?probe=78d9a31074) | Feb 21, 2021 |
| Lenovo        | ThinkPad E420 1141A83       | [aa98e655f3](https://bsd-hardware.info/?probe=aa98e655f3) | Feb 20, 2021 |
| Lenovo        | ThinkPad E420 1141A83       | [9731048099](https://bsd-hardware.info/?probe=9731048099) | Feb 20, 2021 |
| Lenovo        | ThinkPad E420 1141A83       | [03d4d9a468](https://bsd-hardware.info/?probe=03d4d9a468) | Feb 20, 2021 |
| Lenovo        | ThinkPad E420 1141A83       | [a48872901d](https://bsd-hardware.info/?probe=a48872901d) | Feb 20, 2021 |
| HP            | ProBook 440 G2              | [63038d613f](https://bsd-hardware.info/?probe=63038d613f) | Feb 19, 2021 |
| Lenovo        | ZIUS6                       | [1c239bac92](https://bsd-hardware.info/?probe=1c239bac92) | Feb 18, 2021 |
| Lenovo        | ThinkPad T490 20RYS06R00    | [12c985b708](https://bsd-hardware.info/?probe=12c985b708) | Feb 17, 2021 |
| HP            | Pavilion Laptop 14-ce2xx... | [c355a6280b](https://bsd-hardware.info/?probe=c355a6280b) | Feb 17, 2021 |
| HP            | OMEN by HP Laptop           | [bb8beb97be](https://bsd-hardware.info/?probe=bb8beb97be) | Feb 17, 2021 |
| eMachines     | eME732ZG                    | [d0c0433452](https://bsd-hardware.info/?probe=d0c0433452) | Feb 16, 2021 |
| ASUSTek       | X555LD                      | [74d43ccd10](https://bsd-hardware.info/?probe=74d43ccd10) | Feb 16, 2021 |
| HP            | EliteBook 840 G3            | [0d35b2f5d8](https://bsd-hardware.info/?probe=0d35b2f5d8) | Feb 15, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [f8bdec0105](https://bsd-hardware.info/?probe=f8bdec0105) | Feb 14, 2021 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 95        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 94        | 98.95%  |
| KDE5         | 1         | 1.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 95        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SLiM | 95        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 95        | 100%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 76        | 80%     |
| BIOS | 19        | 20%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Zfs  | 95        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 95        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 22        | 23.16%  |
| Dell                | 19        | 20%     |
| Hewlett-Packard     | 15        | 15.79%  |
| ASUSTek Computer    | 9         | 9.47%   |
| Toshiba             | 6         | 6.32%   |
| Apple               | 5         | 5.26%   |
| Acer                | 3         | 3.16%   |
| Samsung Electronics | 2         | 2.11%   |
| Gateway             | 2         | 2.11%   |
| WYSE                | 1         | 1.05%   |
| TUXEDO              | 1         | 1.05%   |
| Sony                | 1         | 1.05%   |
| Packard Bell        | 1         | 1.05%   |
| NEC Computers       | 1         | 1.05%   |
| MSI                 | 1         | 1.05%   |
| MouseComputer       | 1         | 1.05%   |
| LG Electronics      | 1         | 1.05%   |
| Hampoo              | 1         | 1.05%   |
| Fujitsu             | 1         | 1.05%   |
| eMachines           | 1         | 1.05%   |
| Alienware           | 1         | 1.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Dell Inspiron 15-3567                       | 3         | 3.16%   |
| Gateway NE56R                               | 2         | 2.11%   |
| Dell Inspiron 7520                          | 2         | 2.11%   |
| Apple MacBookPro9,2                         | 2         | 2.11%   |
| WYSE Z CLASS                                | 1         | 1.05%   |
| TUXEDO Aura 15 Gen1                         | 1         | 1.05%   |
| Toshiba Satellite Pro U400                  | 1         | 1.05%   |
| Toshiba Satellite L855                      | 1         | 1.05%   |
| Toshiba Satellite L500                      | 1         | 1.05%   |
| Toshiba Satellite C640                      | 1         | 1.05%   |
| Toshiba PORTEGE Z10t-A                      | 1         | 1.05%   |
| Toshiba PORTEGE R930                        | 1         | 1.05%   |
| Sony VPCEJ1E1E                              | 1         | 1.05%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 1         | 1.05%   |
| Samsung 530U3C/530U4C/532U3C                | 1         | 1.05%   |
| Packard Bell EasyNote MH36                  | 1         | 1.05%   |
| NEC Computers PC-VK17HBBCD                  | 1         | 1.05%   |
| MSI GF65 Thin 10SDR                         | 1         | 1.05%   |
| MouseComputer W331AU                        | 1         | 1.05%   |
| LG 14Z980-G.BH51P1                          | 1         | 1.05%   |
| Lenovo ZIUS6                                | 1         | 1.05%   |
| Lenovo ThinkPad X260 20F5S82N00             | 1         | 1.05%   |
| Lenovo ThinkPad X250 20CLS4JH00             | 1         | 1.05%   |
| Lenovo ThinkPad X240 20AMS39F0K             | 1         | 1.05%   |
| Lenovo ThinkPad X230 2330A48                | 1         | 1.05%   |
| Lenovo ThinkPad X230 2325WWB                | 1         | 1.05%   |
| Lenovo ThinkPad X230 23255Y4                | 1         | 1.05%   |
| Lenovo ThinkPad X200 7458VP4                | 1         | 1.05%   |
| Lenovo ThinkPad T490 20RYS06R00             | 1         | 1.05%   |
| Lenovo ThinkPad T470p 20J6A012CD            | 1         | 1.05%   |
| Lenovo ThinkPad T440s 20ARS1B704            | 1         | 1.05%   |
| Lenovo ThinkPad T420 4236FJ1                | 1         | 1.05%   |
| Lenovo ThinkPad L450 20DTCTO1WW             | 1         | 1.05%   |
| Lenovo ThinkPad Edge E530 62724FU           | 1         | 1.05%   |
| Lenovo ThinkPad E420 1141A83                | 1         | 1.05%   |
| Lenovo Legion Y530-15ICH 81FV               | 1         | 1.05%   |
| Lenovo IdeaPad S145-15IWL 81S9              | 1         | 1.05%   |
| Lenovo IdeaPad 110S-11IBR 80WG              | 1         | 1.05%   |
| Lenovo G550 2958                            | 1         | 1.05%   |
| Lenovo G500 20236                           | 1         | 1.05%   |
| Lenovo G470 20078                           | 1         | 1.05%   |
| Lenovo B41-80 80LG                          | 1         | 1.05%   |
| HP Stream 11 Pro G4 EE                      | 1         | 1.05%   |
| HP ProBook 4440s                            | 1         | 1.05%   |
| HP ProBook 440 G2                           | 1         | 1.05%   |
| HP Pavilion Notebook                        | 1         | 1.05%   |
| HP Pavilion Laptop 14-ce2xxx                | 1         | 1.05%   |
| HP Pavilion dv6                             | 1         | 1.05%   |
| HP Pavilion 17                              | 1         | 1.05%   |
| HP Pavilion 11                              | 1         | 1.05%   |
| HP OMEN by HP Laptop                        | 1         | 1.05%   |
| HP EliteBook 8540p                          | 1         | 1.05%   |
| HP EliteBook 840 G3                         | 1         | 1.05%   |
| HP 625                                      | 1         | 1.05%   |
| HP 255 G2                                   | 1         | 1.05%   |
| HP 250 G4                                   | 1         | 1.05%   |
| HP 15                                       | 1         | 1.05%   |
| Hampoo NA123                                | 1         | 1.05%   |
| Fujitsu LIFEBOOK A555                       | 1         | 1.05%   |
| eMachines eME732ZG                          | 1         | 1.05%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 14        | 14.74%  |
| Dell Latitude              | 8         | 8.42%   |
| Dell Inspiron              | 6         | 6.32%   |
| HP Pavilion                | 5         | 5.26%   |
| Toshiba Satellite          | 4         | 4.21%   |
| Acer Aspire                | 3         | 3.16%   |
| Toshiba PORTEGE            | 2         | 2.11%   |
| Lenovo IdeaPad             | 2         | 2.11%   |
| HP ProBook                 | 2         | 2.11%   |
| HP EliteBook               | 2         | 2.11%   |
| Gateway NE56R              | 2         | 2.11%   |
| Dell Vostro                | 2         | 2.11%   |
| ASUS VivoBook              | 2         | 2.11%   |
| Apple MacBookPro9          | 2         | 2.11%   |
| WYSE Z                     | 1         | 1.05%   |
| TUXEDO Aura                | 1         | 1.05%   |
| Sony VPCEJ1E1E             | 1         | 1.05%   |
| Samsung RV411              | 1         | 1.05%   |
| Samsung 530U3C             | 1         | 1.05%   |
| Packard Bell EasyNote      | 1         | 1.05%   |
| NEC Computers PC-VK17HBBCD | 1         | 1.05%   |
| MSI GF65                   | 1         | 1.05%   |
| MouseComputer W331AU       | 1         | 1.05%   |
| LG 14Z980-G.BH51P1         | 1         | 1.05%   |
| Lenovo ZIUS6               | 1         | 1.05%   |
| Lenovo Legion              | 1         | 1.05%   |
| Lenovo G550                | 1         | 1.05%   |
| Lenovo G500                | 1         | 1.05%   |
| Lenovo G470                | 1         | 1.05%   |
| Lenovo B41-80              | 1         | 1.05%   |
| HP Stream                  | 1         | 1.05%   |
| HP OMEN                    | 1         | 1.05%   |
| HP 625                     | 1         | 1.05%   |
| HP 255                     | 1         | 1.05%   |
| HP 250                     | 1         | 1.05%   |
| HP 15                      | 1         | 1.05%   |
| Hampoo NA123               | 1         | 1.05%   |
| Fujitsu LIFEBOOK           | 1         | 1.05%   |
| eMachines eME732ZG         | 1         | 1.05%   |
| Dell XPS                   | 1         | 1.05%   |
| Dell Precision             | 1         | 1.05%   |
| Dell G3                    | 1         | 1.05%   |
| ASUS X55CR                 | 1         | 1.05%   |
| ASUS X556UA                | 1         | 1.05%   |
| ASUS X555LD                | 1         | 1.05%   |
| ASUS UX330UAK              | 1         | 1.05%   |
| ASUS Strix                 | 1         | 1.05%   |
| ASUS K55VD                 | 1         | 1.05%   |
| ASUS G75VW                 | 1         | 1.05%   |
| Apple MacBookPro6          | 1         | 1.05%   |
| Apple MacBookPro3          | 1         | 1.05%   |
| Apple MacBookAir7          | 1         | 1.05%   |
| Alienware 17               | 1         | 1.05%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 20        | 21.05%  |
| 2013 | 14        | 14.74%  |
| 2019 | 13        | 13.68%  |
| 2018 | 7         | 7.37%   |
| 2015 | 6         | 6.32%   |
| 2014 | 6         | 6.32%   |
| 2011 | 6         | 6.32%   |
| 2009 | 6         | 6.32%   |
| 2012 | 5         | 5.26%   |
| 2021 | 3         | 3.16%   |
| 2017 | 3         | 3.16%   |
| 2016 | 2         | 2.11%   |
| 2010 | 2         | 2.11%   |
| 2008 | 2         | 2.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 95        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 94        | 98.95%  |
| Yes  | 1         | 1.05%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 43        | 45.26%  |
| 8.01-16.0  | 35        | 36.84%  |
| 16.01-24.0 | 12        | 12.63%  |
| 32.01-64.0 | 3         | 3.16%   |
| 24.01-32.0 | 1         | 1.05%   |
| 2.01-3.0   | 1         | 1.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 67        | 70.53%  |
| 0.51-1.0  | 23        | 24.21%  |
| 1.01-2.0  | 3         | 3.16%   |
| 2.01-3.0  | 1         | 1.05%   |
| 8.01-16.0 | 1         | 1.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 76        | 79.17%  |
| 2      | 14        | 14.58%  |
| 0      | 5         | 5.21%   |
| 3      | 1         | 1.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 50        | 52.63%  |
| No        | 45        | 47.37%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 82        | 86.32%  |
| No        | 13        | 13.68%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 94        | 98.95%  |
| No        | 1         | 1.05%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 62        | 65.26%  |
| No        | 33        | 34.74%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| USA                | 16        | 16.67%  |
| Germany            | 10        | 10.42%  |
| Brazil             | 8         | 8.33%   |
| Netherlands        | 6         | 6.25%   |
| China              | 5         | 5.21%   |
| UK                 | 4         | 4.17%   |
| Sweden             | 4         | 4.17%   |
| Spain              | 4         | 4.17%   |
| Italy              | 3         | 3.13%   |
| India              | 3         | 3.13%   |
| Ukraine            | 2         | 2.08%   |
| Poland             | 2         | 2.08%   |
| Mexico             | 2         | 2.08%   |
| Indonesia          | 2         | 2.08%   |
| Canada             | 2         | 2.08%   |
| Switzerland        | 1         | 1.04%   |
| South Africa       | 1         | 1.04%   |
| Slovakia           | 1         | 1.04%   |
| Puerto Rico        | 1         | 1.04%   |
| Portugal           | 1         | 1.04%   |
| Oman               | 1         | 1.04%   |
| Morocco            | 1         | 1.04%   |
| Malaysia           | 1         | 1.04%   |
| Lithuania          | 1         | 1.04%   |
| Latvia             | 1         | 1.04%   |
| Japan              | 1         | 1.04%   |
| Hungary            | 1         | 1.04%   |
| Greece             | 1         | 1.04%   |
| France             | 1         | 1.04%   |
| Dominican Republic | 1         | 1.04%   |
| Cyprus             | 1         | 1.04%   |
| Croatia            | 1         | 1.04%   |
| Bulgaria           | 1         | 1.04%   |
| Belgium            | 1         | 1.04%   |
| Belarus            | 1         | 1.04%   |
| Austria            | 1         | 1.04%   |
| Australia          | 1         | 1.04%   |
| Argentina          | 1         | 1.04%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Berlin               | 2         | 2.04%   |
| Zurich               | 1         | 1.02%   |
| Zhengzhou            | 1         | 1.02%   |
| Zagreb               | 1         | 1.02%   |
| Wuhan                | 1         | 1.02%   |
| Wroclaw              | 1         | 1.02%   |
| Washington           | 1         | 1.02%   |
| Warmond              | 1         | 1.02%   |
| Wandur               | 1         | 1.02%   |
| Vigonovo             | 1         | 1.02%   |
| Vienna               | 1         | 1.02%   |
| V?�ster??s           | 1         | 1.02%   |
| Vancouver            | 1         | 1.02%   |
| Utrecht              | 1         | 1.02%   |
| Tula de Allende      | 1         | 1.02%   |
| The Bronx            | 1         | 1.02%   |
| Tangara              | 1         | 1.02%   |
| Surabaya             | 1         | 1.02%   |
| Sungai Buloh         | 1         | 1.02%   |
| Solarino             | 1         | 1.02%   |
| Sofia                | 1         | 1.02%   |
| Shibakoen            | 1         | 1.02%   |
| Shasta               | 1         | 1.02%   |
| Santo Domingo Este   | 1         | 1.02%   |
| Sankt Augustin       | 1         | 1.02%   |
| Roosendaal           | 1         | 1.02%   |
| Riga                 | 1         | 1.02%   |
| Redondela            | 1         | 1.02%   |
| Pleidelsheim         | 1         | 1.02%   |
| Perwez               | 1         | 1.02%   |
| Osasco               | 1         | 1.02%   |
| Oosterhout           | 1         | 1.02%   |
| Oklahoma City        | 1         | 1.02%   |
| Notting Hill Gate    | 1         | 1.02%   |
| Nizwa                | 1         | 1.02%   |
| New Braunfels        | 1         | 1.02%   |
| Morden               | 1         | 1.02%   |
| Montreuil            | 1         | 1.02%   |
| Miskolc              | 1         | 1.02%   |
| Mar del Plata        | 1         | 1.02%   |
| Lusk                 | 1         | 1.02%   |
| Lule??               | 1         | 1.02%   |
| Liptovský Mikuláš | 1         | 1.02%   |
| Limassol             | 1         | 1.02%   |
| Leipzig              | 1         | 1.02%   |
| Leesville            | 1         | 1.02%   |
| Las Vegas            | 1         | 1.02%   |
| Lake Forest          | 1         | 1.02%   |
| Lajeado              | 1         | 1.02%   |
| Krakow               | 1         | 1.02%   |
| Klaipėda            | 1         | 1.02%   |
| Klagshamn            | 1         | 1.02%   |
| Kherson              | 1         | 1.02%   |
| Johannesburg         | 1         | 1.02%   |
| Jakarta              | 1         | 1.02%   |
| Jaipur               | 1         | 1.02%   |
| Huangpu              | 1         | 1.02%   |
| Horishni Plavni      | 1         | 1.02%   |
| Henderson            | 1         | 1.02%   |
| Hayes                | 1         | 1.02%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 14        | 14     | 13.59%  |
| Samsung Electronics | 14        | 19     | 13.59%  |
| Seagate             | 13        | 14     | 12.62%  |
| Toshiba             | 10        | 10     | 9.71%   |
| Crucial             | 8         | 8      | 7.77%   |
| SanDisk             | 6         | 6      | 5.83%   |
| Hitachi             | 6         | 7      | 5.83%   |
| Intel               | 5         | 5      | 4.85%   |
| Kingston            | 3         | 3      | 2.91%   |
| A-DATA Technology   | 3         | 4      | 2.91%   |
| SPCC                | 2         | 2      | 1.94%   |
| OCZ                 | 2         | 2      | 1.94%   |
| HGST                | 2         | 2      | 1.94%   |
| Apple               | 2         | 2      | 1.94%   |
| Transcend           | 1         | 2      | 0.97%   |
| SMART               | 1         | 1      | 0.97%   |
| SK Hynix            | 1         | 1      | 0.97%   |
| PNY                 | 1         | 1      | 0.97%   |
| Patriot             | 1         | 1      | 0.97%   |
| MyDigitalSSD        | 1         | 1      | 0.97%   |
| Micron Technology   | 1         | 1      | 0.97%   |
| LITEONIT            | 1         | 1      | 0.97%   |
| LITEON              | 1         | 1      | 0.97%   |
| KingSpec            | 1         | 1      | 0.97%   |
| HPE                 | 1         | 1      | 0.97%   |
| Hewlett-Packard     | 1         | 2      | 0.97%   |
| Fujitsu             | 1         | 1      | 0.97%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST500LM012 HN-M500MBB 500GB  | 2         | 1.89%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 1.89%   |
| Samsung SSD 850 EVO 250GB            | 2         | 1.89%   |
| Crucial CT1000MX500SSD1 1TB          | 2         | 1.89%   |
| WDC WDS240G2G0A-00JH30 240GB         | 1         | 0.94%   |
| WDC WDBNCE2500PNC 250GB              | 1         | 0.94%   |
| WDC WD800BEVS-00RST0 80GB            | 1         | 0.94%   |
| WDC WD7500BPVX-60JC3T0 752GB         | 1         | 0.94%   |
| WDC WD5000LPVX-60V0TT0 500GB         | 1         | 0.94%   |
| WDC WD5000LPVX-00V0TT0 500GB         | 1         | 0.94%   |
| WDC WD3200BEVT-60ZCT1 320GB          | 1         | 0.94%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 0.94%   |
| WDC WD3200BEKT-75PVMT1 320GB         | 1         | 0.94%   |
| WDC WD2500BEVT-75ZCT2 250GB          | 1         | 0.94%   |
| WDC WD10SPZX-24Z10 1TB               | 1         | 0.94%   |
| WDC WD10JPVX-00JC3T0 1TB             | 1         | 0.94%   |
| WDC PC SN530 SDBPNPZ-512G-1032 512GB | 1         | 0.94%   |
| WDC PC SN530 SDBPNPZ-256G-1002 256GB | 1         | 0.94%   |
| Transcend TS512GMTS430S 512GB        | 1         | 0.94%   |
| Toshiba THNSNF128GCSS 128GB          | 1         | 0.94%   |
| Toshiba THNSNC128GMLJ 128GB          | 1         | 0.94%   |
| Toshiba MQ01ABF050 500GB             | 1         | 0.94%   |
| Toshiba MQ01ABD100 1TB               | 1         | 0.94%   |
| Toshiba MQ01ABD075 752GB             | 1         | 0.94%   |
| Toshiba MQ01ABD032 320GB             | 1         | 0.94%   |
| Toshiba MK3265GSXN 320GB             | 1         | 0.94%   |
| Toshiba MK3261GSYN 320GB             | 1         | 0.94%   |
| Toshiba KXG50PNV2T04 NVMe 2048GB     | 1         | 0.94%   |
| Toshiba KBG40ZNS256G NVMe 256GB      | 1         | 0.94%   |
| SPCC Solid State Disk 256GB          | 1         | 0.94%   |
| SPCC Solid State Disk 1TB            | 1         | 0.94%   |
| SMART SSD XceedValue2 mSATA 32GB     | 1         | 0.94%   |
| SK Hynix SHGP31-1000GM-2 1TB         | 1         | 0.94%   |
| Seagate ST9500325AS 500GB            | 1         | 0.94%   |
| Seagate ST9320423AS 320GB            | 1         | 0.94%   |
| Seagate ST9250315AS 250GB            | 1         | 0.94%   |
| Seagate ST9160412ASG 160GB           | 1         | 0.94%   |
| Seagate ST9160412AS 160GB            | 1         | 0.94%   |
| Seagate ST500LM000-SSHD-8GB          | 1         | 0.94%   |
| Seagate ST320LT012-9WS14C 320GB      | 1         | 0.94%   |
| Seagate ST1000LM049-2GH172 1TB       | 1         | 0.94%   |
| Seagate ST1000LM048-2E7172 1TB       | 1         | 0.94%   |
| SanDisk Ultra II 480GB               | 1         | 0.94%   |
| SanDisk SSD i100 24GB                | 1         | 0.94%   |
| SanDisk SDSSDP128G 128GB             | 1         | 0.94%   |
| SanDisk SDSSDHP256G 256GB            | 1         | 0.94%   |
| SanDisk SD8SBAT256G1002 256GB        | 1         | 0.94%   |
| SanDisk SD7SN6S-256G-1006 256GB      | 1         | 0.94%   |
| Samsung SSD RBX Series 64GB M        | 1         | 0.94%   |
| Samsung SSD PM851 mSATA 256GB        | 1         | 0.94%   |
| Samsung SSD 980 PRO 500GB            | 1         | 0.94%   |
| Samsung SSD 970 EVO 250GB            | 1         | 0.94%   |
| Samsung SSD 870 QVO 1TB              | 1         | 0.94%   |
| Samsung SSD 860 EVO 500GB            | 1         | 0.94%   |
| Samsung SSD 860 EVO 1TB              | 1         | 0.94%   |
| Samsung SSD 840 Series 500GB         | 1         | 0.94%   |
| Samsung SSD 840 EVO 250GB            | 1         | 0.94%   |
| Samsung SG9XCS1F50GMIBM 43W7729 50GB | 1         | 0.94%   |
| Samsung MZMTE128HMGR-00000 128GB     | 1         | 0.94%   |
| Samsung MZ7LN256HCHP-000F0 256GB     | 1         | 0.94%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 14     | 31.71%  |
| WDC                 | 10        | 10     | 24.39%  |
| Toshiba             | 6         | 6      | 14.63%  |
| Hitachi             | 6         | 7      | 14.63%  |
| Samsung Electronics | 2         | 2      | 4.88%   |
| HGST                | 2         | 2      | 4.88%   |
| Fujitsu             | 1         | 1      | 2.44%   |
| Apple               | 1         | 1      | 2.44%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 14     | 20.75%  |
| Crucial             | 7         | 7      | 13.21%  |
| SanDisk             | 6         | 6      | 11.32%  |
| Intel               | 4         | 4      | 7.55%   |
| Kingston            | 3         | 3      | 5.66%   |
| WDC                 | 2         | 2      | 3.77%   |
| Toshiba             | 2         | 2      | 3.77%   |
| SPCC                | 2         | 2      | 3.77%   |
| OCZ                 | 2         | 2      | 3.77%   |
| A-DATA Technology   | 2         | 3      | 3.77%   |
| Transcend           | 1         | 2      | 1.89%   |
| SMART               | 1         | 1      | 1.89%   |
| PNY                 | 1         | 1      | 1.89%   |
| Patriot             | 1         | 1      | 1.89%   |
| MyDigitalSSD        | 1         | 1      | 1.89%   |
| Micron Technology   | 1         | 1      | 1.89%   |
| LITEONIT            | 1         | 1      | 1.89%   |
| LITEON              | 1         | 1      | 1.89%   |
| KingSpec            | 1         | 1      | 1.89%   |
| HPE                 | 1         | 1      | 1.89%   |
| Hewlett-Packard     | 1         | 2      | 1.89%   |
| Apple               | 1         | 1      | 1.89%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 48        | 59     | 48.48%  |
| HDD  | 41        | 43     | 41.41%  |
| NVMe | 10        | 11     | 10.1%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 84        | 102    | 89.36%  |
| NVMe | 10        | 11     | 10.64%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 68        | 80     | 78.16%  |
| 0.51-1.0   | 17        | 20     | 19.54%  |
| 1.01-2.0   | 2         | 2      | 2.3%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 55        | 57.89%  |
| 251-500    | 15        | 15.79%  |
| 101-250    | 14        | 14.74%  |
| 501-1000   | 5         | 5.26%   |
| 51-100     | 3         | 3.16%   |
| 21-50      | 2         | 2.11%   |
| 1001-2000  | 1         | 1.05%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 95        | 100%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                    | Notebooks | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-60V0TT0 500GB             | 1         | 1      | 4.55%   |
| WDC WD3200BEVT-22ZCT0 320GB              | 1         | 1      | 4.55%   |
| Toshiba MQ01ABD075 752GB                 | 1         | 1      | 4.55%   |
| Toshiba MQ01ABD032 320GB                 | 1         | 1      | 4.55%   |
| Toshiba MK3265GSXN 320GB                 | 1         | 1      | 4.55%   |
| Toshiba MK3261GSYN 320GB                 | 1         | 1      | 4.55%   |
| Seagate ST9320423AS 320GB                | 1         | 1      | 4.55%   |
| Seagate ST9160412AS 160GB                | 1         | 1      | 4.55%   |
| Seagate ST500LM012 HN-M500MBB 500GB      | 1         | 1      | 4.55%   |
| Seagate ST320LT012-9WS14C 320GB          | 1         | 2      | 4.55%   |
| Seagate ST1000LM049-2GH172 1TB           | 1         | 1      | 4.55%   |
| Seagate ST1000LM035-1RK172 1TB           | 1         | 1      | 4.55%   |
| Samsung Electronics SSD 840 Series 500GB | 1         | 1      | 4.55%   |
| Kingston RBU-SNS8350DES3128GP 128GB      | 1         | 1      | 4.55%   |
| Hitachi HTS545050B9A300 500GB            | 1         | 1      | 4.55%   |
| Hitachi HTS545050A7E380 500GB            | 1         | 1      | 4.55%   |
| Hitachi HTS545032B9A300 320GB            | 1         | 1      | 4.55%   |
| Hitachi HTS545025B9SA02 250GB            | 1         | 1      | 4.55%   |
| HGST HTS721010A9E630 1TB                 | 1         | 1      | 4.55%   |
| Hewlett-Packard SSD S700 1TB             | 1         | 1      | 4.55%   |
| Fujitsu MHW2160BH 160GB                  | 1         | 1      | 4.55%   |
| Apple HDD HTS545050A7E362 500GB          | 1         | 1      | 4.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 7      | 27.27%  |
| Toshiba             | 4         | 4      | 18.18%  |
| Hitachi             | 4         | 4      | 18.18%  |
| WDC                 | 2         | 2      | 9.09%   |
| Samsung Electronics | 1         | 1      | 4.55%   |
| Kingston            | 1         | 1      | 4.55%   |
| HGST                | 1         | 1      | 4.55%   |
| Hewlett-Packard     | 1         | 1      | 4.55%   |
| Fujitsu             | 1         | 1      | 4.55%   |
| Apple               | 1         | 1      | 4.55%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 7      | 31.58%  |
| Toshiba | 4         | 4      | 21.05%  |
| Hitachi | 4         | 4      | 21.05%  |
| WDC     | 2         | 2      | 10.53%  |
| HGST    | 1         | 1      | 5.26%   |
| Fujitsu | 1         | 1      | 5.26%   |
| Apple   | 1         | 1      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 19        | 20     | 86.36%  |
| SSD  | 3         | 3      | 13.64%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                   | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| HPE MK000480GWUGF 480GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| HPE    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Works   | 73        | 89     | 76.04%  |
| Malfunc | 22        | 23     | 22.92%  |
| Failed  | 1         | 1      | 1.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 84        | 84%     |
| AMD                       | 6         | 6%      |
| Samsung Electronics       | 3         | 3%      |
| Sandisk                   | 2         | 2%      |
| Toshiba                   | 1         | 1%      |
| SK Hynix                  | 1         | 1%      |
| Realtek Semiconductor     | 1         | 1%      |
| Micron/Crucial Technology | 1         | 1%      |
| KIOXIA                    | 1         | 1%      |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 18        | 16.82%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 11        | 10.28%  |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 8         | 7.48%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 7         | 6.54%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 7         | 6.54%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 7         | 6.54%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 5         | 4.67%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 4         | 3.74%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 2.8%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 3         | 2.8%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 2.8%    |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 2         | 1.87%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 1.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.87%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 2         | 1.87%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 2         | 1.87%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 1.87%   |
| Unknown                                                                          | 2         | 1.87%   |
| Toshiba unknown                                                                  | 1         | 0.93%   |
| SK Hynix NVMe SSD Controller                                                     | 1         | 0.93%   |
| Samsung SM951 AHCI                                                               | 1         | 0.93%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 0.93%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.93%   |
| KIOXIA unknown                                                                   | 1         | 0.93%   |
| Intel SSD 660P Series                                                            | 1         | 0.93%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 0.93%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 0.93%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 0.93%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 1         | 0.93%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 0.93%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 0.93%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 1         | 0.93%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 1         | 0.93%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 0.93%   |
| AMD FCH IDE Controller                                                           | 1         | 0.93%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 80        | 76.92%  |
| NVMe | 10        | 9.62%   |
| RAID | 7         | 6.73%   |
| IDE  | 7         | 6.73%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 88        | 92.63%  |
| AMD    | 7         | 7.37%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel CPU Version                     | 5         | 5.26%   |
| Intel Core i5-3210M CPU @ 2.50GHz     | 4         | 4.21%   |
| Intel Core i7-8750H CPU @ 2.20GHz     | 3         | 3.16%   |
| Intel Core i5-6200U CPU @ 2.30GHz     | 3         | 3.16%   |
| Intel Core i5-4210U CPU @ 1.70GHz     | 3         | 3.16%   |
| Intel Core i7-4510U CPU @ 2.00GHz     | 2         | 2.11%   |
| Intel Core i7-3630QM CPU @ 2.40GHz    | 2         | 2.11%   |
| Intel Core i7 CPU M 620 @ 2.67GHz     | 2         | 2.11%   |
| Intel Core i5-6300U CPU @ 2.40GHz     | 2         | 2.11%   |
| Intel Core i5-5200U CPU @ 2.20GHz     | 2         | 2.11%   |
| Intel Core i5-3340M CPU @ 2.70GHz     | 2         | 2.11%   |
| Intel Core i5-3320M CPU @ 2.60GHz     | 2         | 2.11%   |
| Intel Core i5-3230M CPU @ 2.60GHz     | 2         | 2.11%   |
| Intel Core i3-6006U CPU @ 2.00GHz     | 2         | 2.11%   |
| Intel Core i3-5005U CPU @ 2.00GHz     | 2         | 2.11%   |
| Intel Core i3-2370M CPU @ 2.40GHz     | 2         | 2.11%   |
| Intel Core i3-2350M CPU @ 2.30GHz     | 2         | 2.11%   |
| Intel Core 2 Duo                      | 2         | 2.11%   |
| Intel Celeron CPU N3450 @ 1.10GHz     | 2         | 2.11%   |
| Intel Pentium CPU P6200 @ 2.13GHz     | 1         | 1.05%   |
| Intel Pentium CPU B940 @ 2.00GHz      | 1         | 1.05%   |
| Intel Genuine CPU                     | 1         | 1.05%   |
| Intel Core i7-8565U CPU @ 1.80GHz     | 1         | 1.05%   |
| Intel Core i7-7500U CPU @ 2.70GHz     | 1         | 1.05%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz    | 1         | 1.05%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz    | 1         | 1.05%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz    | 1         | 1.05%   |
| Intel Core i7-4600U CPU @ 2.10GHz     | 1         | 1.05%   |
| Intel Core i7-3632QM CPU @ 2.20GHz    | 1         | 1.05%   |
| Intel Core i7-2637M CPU               | 1         | 1.05%   |
| Intel Core i7-10750H CPU @ 2.60GHz    | 1         | 1.05%   |
| Intel Core i7-10510U CPU @ 1.80GHz    | 1         | 1.05%   |
| Intel Core i5-8365U CPU @ 1.60GHz     | 1         | 1.05%   |
| Intel Core i5-8265U CPU @ 1.60GHz     | 1         | 1.05%   |
| Intel Core i5-8250U CPU @ 1.60GHz     | 1         | 1.05%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz    | 1         | 1.05%   |
| Intel Core i5-7200U CPU @ 2.50GHz     | 1         | 1.05%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz    | 1         | 1.05%   |
| Intel Core i5-5250U CPU @ 1.60GHz     | 1         | 1.05%   |
| Intel Core i5-4300U CPU @ 1.90GHz     | 1         | 1.05%   |
| Intel Core i5-4210Y CPU @ 1.50GHz     | 1         | 1.05%   |
| Intel Core i5-4200U CPU @ 1.60GHz     | 1         | 1.05%   |
| Intel Core i5-2537M CPU @ 1.40GHz     | 1         | 1.05%   |
| Intel Core i5-2520M CPU @ 2.50GHz     | 1         | 1.05%   |
| Intel Core i5 CPU M 560 @ 2.67GH      | 1         | 1.05%   |
| Intel Core i3-8145U CPU @ 2.10GHz     | 1         | 1.05%   |
| Intel Core i3-7100U CPU @ 2.40GHz     | 1         | 1.05%   |
| Intel Core i3-3120M CPU @ 2.50GHz     | 1         | 1.05%   |
| Intel Core i3-2330M CPU @ 2.20GHz     | 1         | 1.05%   |
| Intel Core i3-2310M CPU @ 2.10GH      | 1         | 1.05%   |
| Intel Core i3 CPU M 390 @ 2.67GHz     | 1         | 1.05%   |
| Intel Core 2 Solo CPU U3500 @ 1.40GHz | 1         | 1.05%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz  | 1         | 1.05%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz  | 1         | 1.05%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz  | 1         | 1.05%   |
| Intel Celeron CPU N3060 @ 1.60GHz     | 1         | 1.05%   |
| Intel Celeron CPU N3050 @ 1.60GHz     | 1         | 1.05%   |
| Intel Celeron CPU B840 @ 1.90GHz      | 1         | 1.05%   |
| Intel Celeron CPU B830 @ 1.80GHz      | 1         | 1.05%   |
| Intel Celeron CPU 3215U @ 1.70GHz     | 1         | 1.05%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model             | Notebooks | Percent |
|-------------------|-----------|---------|
| Intel Core i5     | 33        | 34.74%  |
| Intel Core i7     | 19        | 20%     |
| Intel Core i3     | 14        | 14.74%  |
| Intel Celeron     | 8         | 8.42%   |
| Other             | 5         | 5.26%   |
| Intel Core 2 Duo  | 5         | 5.26%   |
| Intel Pentium     | 2         | 2.11%   |
| Intel Genuine     | 1         | 1.05%   |
| Intel Core 2 Solo | 1         | 1.05%   |
| AMD Ryzen 7       | 1         | 1.05%   |
| AMD Ryzen 3       | 1         | 1.05%   |
| AMD G             | 1         | 1.05%   |
| AMD E1            | 1         | 1.05%   |
| AMD Athlon II     | 1         | 1.05%   |
| AMD A6            | 1         | 1.05%   |
| AMD A10           | 1         | 1.05%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 68        | 71.58%  |
| 4       | 18        | 18.95%  |
| 6       | 4         | 4.21%   |
| Unknown | 3         | 3.16%   |
| 8       | 1         | 1.05%   |
| 1       | 1         | 1.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 94        | 98.95%  |
| 2      | 1         | 1.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 64        | 67.37%  |
| 1       | 27        | 28.42%  |
| Unknown | 4         | 4.21%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| IvyBridge   | 15        | 15.79%  |
| KabyLake    | 13        | 13.68%  |
| SandyBridge | 12        | 12.63%  |
| Skylake     | 10        | 10.53%  |
| Haswell     | 10        | 10.53%  |
| Penryn      | 9         | 9.47%   |
| Westmere    | 6         | 6.32%   |
| Broadwell   | 6         | 6.32%   |
| Silvermont  | 2         | 2.11%   |
| Jaguar      | 2         | 2.11%   |
| Goldmont    | 2         | 2.11%   |
| Core        | 2         | 2.11%   |
| Zen+        | 1         | 1.05%   |
| Zen 2       | 1         | 1.05%   |
| Piledriver  | 1         | 1.05%   |
| K10         | 1         | 1.05%   |
| CometLake   | 1         | 1.05%   |
| Bobcat      | 1         | 1.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 80        | 71.43%  |
| Nvidia | 18        | 16.07%  |
| AMD    | 14        | 12.5%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 13        | 11.61%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11        | 9.82%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 7.14%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 7.14%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 6.25%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 3.57%   |
| Intel HD Graphics 5500                                                                   | 4         | 3.57%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 3.57%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 2.68%   |
| Intel HD Graphics 620                                                                    | 3         | 2.68%   |
| Intel HD Graphics 530                                                                    | 3         | 2.68%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 2.68%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 1.79%   |
| Intel HD Graphics 500                                                                    | 2         | 1.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.79%   |
| AMD Chelsea LP [Radeon HD 7730M]                                                         | 2         | 1.79%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.89%   |
| Nvidia GT216M [NVS 5100M]                                                                | 1         | 0.89%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.89%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.89%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.89%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.89%   |
| Nvidia GK107M [GeForce GTX 660M]                                                         | 1         | 0.89%   |
| Nvidia GK106M [GeForce GTX 770M]                                                         | 1         | 0.89%   |
| Nvidia GF119M [GeForce 610M]                                                             | 1         | 0.89%   |
| Nvidia GF119M [GeForce 410M]                                                             | 1         | 0.89%   |
| Nvidia G98M [Quadro NVS 160M]                                                            | 1         | 0.89%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 0.89%   |
| Nvidia G84M [GeForce 8600M GT]                                                           | 1         | 0.89%   |
| Intel UHD Graphics 620                                                                   | 1         | 0.89%   |
| Intel HD Graphics 630                                                                    | 1         | 0.89%   |
| Intel HD Graphics 6000                                                                   | 1         | 0.89%   |
| Intel HD Graphics                                                                        | 1         | 0.89%   |
| Intel Haswell-ULT High Definition Audio Controller [HD Graphics]                         | 1         | 0.89%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 0.89%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 0.89%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 0.89%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 0.89%   |
| AMD Venus XTX [Radeon HD 8890M / R9 M275X/M375X]                                         | 1         | 0.89%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 0.89%   |
| AMD Temash [Radeon HD 8250/8280G]                                                        | 1         | 0.89%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 0.89%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 0.89%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 1         | 0.89%   |
| AMD Richland [Radeon HD 8610G]                                                           | 1         | 0.89%   |
| AMD Renoir                                                                               | 1         | 0.89%   |
| AMD Picasso                                                                              | 1         | 0.89%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 1         | 0.89%   |
| AMD Kabini [Radeon HD 8210]                                                              | 1         | 0.89%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 55        | 57.89%  |
| Intel + Nvidia | 12        | 12.63%  |
| 1 x AMD        | 9         | 9.47%   |
| 2 x Intel      | 8         | 8.42%   |
| 1 x Nvidia     | 6         | 6.32%   |
| Intel + AMD    | 5         | 5.26%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 78        | 82.11%  |
| Unknown     | 16        | 16.84%  |
| Proprietary | 1         | 1.05%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 87        | 91.58%  |
| 0.01-0.5   | 5         | 5.26%   |
| 0.51-1.0   | 2         | 2.11%   |
| 1.01-2.0   | 1         | 1.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 23        | 30.26%  |
| AU Optronics            | 13        | 17.11%  |
| Chimei Innolux          | 12        | 15.79%  |
| Samsung Electronics     | 7         | 9.21%   |
| BOE                     | 5         | 6.58%   |
| Chi Mei Optoelectronics | 4         | 5.26%   |
| InfoVision              | 3         | 3.95%   |
| Apple                   | 2         | 2.63%   |
| AOC                     | 2         | 2.63%   |
| Sony                    | 1         | 1.32%   |
| LG Philips              | 1         | 1.32%   |
| Lenovo                  | 1         | 1.32%   |
| Goldstar                | 1         | 1.32%   |
| Dell                    | 1         | 1.32%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch             | 3         | 3.95%   |
| LG Display LCD Monitor LGD0532 1920x1080 340x190mm 15.3-inch              | 2         | 2.63%   |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch               | 2         | 2.63%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 310x170mm 13.9-inch          | 2         | 2.63%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 340x190mm 15.3-inch             | 2         | 2.63%   |
| Sony SDM-HS95P SNY2500 1280x1024 380x300mm 19.1-inch                      | 1         | 1.32%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 470x300mm 22.0-inch      | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 330x210mm 15.4-inch      | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SEC354C 1366x768 350x200mm 15.9-inch      | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch      | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 340x190mm 15.3-inch      | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SDC324D 1366x768 310x170mm 13.9-inch      | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SDC324A 1366x768 290x170mm 13.2-inch      | 1         | 1.32%   |
| LG Philips LCD Monitor LPL3B01 1280x800 330x210mm 15.4-inch               | 1         | 1.32%   |
| LG Display LCD Monitor LGD11F9 1280x800 290x180mm 13.4-inch               | 1         | 1.32%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch              | 1         | 1.32%   |
| LG Display LCD Monitor LGD05B1 1920x1080 310x170mm 13.9-inch              | 1         | 1.32%   |
| LG Display LCD Monitor LGD0545 3200x1800 290x170mm 13.2-inch              | 1         | 1.32%   |
| LG Display LCD Monitor LGD053F 1920x1080 340x190mm 15.3-inch              | 1         | 1.32%   |
| LG Display LCD Monitor LGD0527 1366x768 310x170mm 13.9-inch               | 1         | 1.32%   |
| LG Display LCD Monitor LGD0525 1366x768 340x190mm 15.3-inch               | 1         | 1.32%   |
| LG Display LCD Monitor LGD045C 1366x768 350x190mm 15.7-inch               | 1         | 1.32%   |
| LG Display LCD Monitor LGD0459 1920x1080 380x210mm 17.1-inch              | 1         | 1.32%   |
| LG Display LCD Monitor LGD0446 1920x1080 310x170mm 13.9-inch              | 1         | 1.32%   |
| LG Display LCD Monitor LGD03A3 1366x768 280x160mm 12.7-inch               | 1         | 1.32%   |
| LG Display LCD Monitor LGD0372 1600x900 380x210mm 17.1-inch               | 1         | 1.32%   |
| LG Display LCD Monitor LGD0360 1600x900 290x170mm 13.2-inch               | 1         | 1.32%   |
| LG Display LCD Monitor LGD02E9 1366x768 310x170mm 13.9-inch               | 1         | 1.32%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x170mm 13.9-inch               | 1         | 1.32%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch               | 1         | 1.32%   |
| LG Display LCD Monitor LGD02DA 1920x1080 380x210mm 17.1-inch              | 1         | 1.32%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch               | 1         | 1.32%   |
| LG Display LCD Monitor LGD02AD 1366x768 340x190mm 15.3-inch               | 1         | 1.32%   |
| LG Display LCD Monitor LGD029B 1366x768 310x170mm 13.9-inch               | 1         | 1.32%   |
| LG Display LCD Monitor LGD0230 1366x768 340x190mm 15.3-inch               | 1         | 1.32%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch                   | 1         | 1.32%   |
| InfoVision LCD Monitor IVO0579 1366x768 310x170mm 13.9-inch               | 1         | 1.32%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 1         | 1.32%   |
| Dell E2013H DELD05C 1600x900 440x250mm 19.9-inch                          | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 380x210mm 17.1-inch          | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN15B1 1920x1080 340x190mm 15.3-inch          | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch           | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN15A9 1366x768 340x190mm 15.3-inch           | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN14E0 1920x1080 310x170mm 13.9-inch          | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch          | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN14A1 1366x768 310x170mm 13.9-inch           | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN1469 1366x768 310x170mm 13.9-inch           | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN1404 1920x1080 310x170mm 13.9-inch          | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch           | 1         | 1.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 380x210mm 17.1-inch | 1         | 1.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch  | 1         | 1.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 350x190mm 15.7-inch  | 1         | 1.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO1312 1280x800 290x180mm 13.4-inch  | 1         | 1.32%   |
| BOE LCD Monitor BOE0715 1366x768 250x140mm 11.3-inch                      | 1         | 1.32%   |
| BOE LCD Monitor BOE06C2 1366x768 340x190mm 15.3-inch                      | 1         | 1.32%   |
| BOE LCD Monitor BOE0691 1920x1080 280x160mm 12.7-inch                     | 1         | 1.32%   |
| BOE LCD Monitor BOE0674 1366x768 340x190mm 15.3-inch                      | 1         | 1.32%   |
| BOE LCD Monitor BOE062C 1366x768 340x190mm 15.3-inch                      | 1         | 1.32%   |
| AU Optronics LCD Monitor AUO463D 1920x1080 310x170mm 13.9-inch            | 1         | 1.32%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 340x190mm 15.3-inch             | 1         | 1.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 38        | 50.67%  |
| 1920x1080 (FHD)    | 23        | 30.67%  |
| 1280x800 (WXGA)    | 5         | 6.67%   |
| 1600x900 (HD+)     | 4         | 5.33%   |
| 3840x2160 (4K)     | 1         | 1.33%   |
| 3200x1800 (QHD+)   | 1         | 1.33%   |
| 1680x1050 (WSXGA+) | 1         | 1.33%   |
| 1440x900 (WXGA+)   | 1         | 1.33%   |
| 1280x1024 (SXGA)   | 1         | 1.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 30        | 39.47%  |
| 13     | 25        | 32.89%  |
| 12     | 7         | 9.21%   |
| 17     | 5         | 6.58%   |
| 11     | 3         | 3.95%   |
| 21     | 2         | 2.63%   |
| 19     | 2         | 2.63%   |
| 27     | 1         | 1.32%   |
| 22     | 1         | 1.32%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 48        | 63.16%  |
| 201-300     | 17        | 22.37%  |
| 351-400     | 6         | 7.89%   |
| 401-500     | 4         | 5.26%   |
| 601-700     | 1         | 1.32%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 64        | 87.67%  |
| 16/10 | 8         | 10.96%  |
| 5/4   | 1         | 1.37%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 23        | 30.26%  |
| 81-90          | 22        | 28.95%  |
| 61-70          | 7         | 9.21%   |
| 101-110        | 7         | 9.21%   |
| 121-130        | 5         | 6.58%   |
| 71-80          | 3         | 3.95%   |
| 51-60          | 3         | 3.95%   |
| 201-250        | 3         | 3.95%   |
| 151-200        | 2         | 2.63%   |
| 301-350        | 1         | 1.32%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 32        | 42.67%  |
| 101-120       | 30        | 40%     |
| 51-100        | 10        | 13.33%  |
| 161-240       | 2         | 2.67%   |
| More than 240 | 1         | 1.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 71        | 74.74%  |
| 0     | 19        | 20%     |
| 2     | 5         | 5.26%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 53        | 35.81%  |
| Realtek Semiconductor             | 41        | 27.7%   |
| Qualcomm Atheros                  | 28        | 18.92%  |
| Broadcom                          | 13        | 8.78%   |
| Ralink                            | 3         | 2.03%   |
| Marvell Technology Group          | 2         | 1.35%   |
| TP-Link                           | 1         | 0.68%   |
| Toshiba                           | 1         | 0.68%   |
| Sierra Wireless                   | 1         | 0.68%   |
| Ralink Technology                 | 1         | 0.68%   |
| Hewlett-Packard                   | 1         | 0.68%   |
| Ericsson Business Mobile Networks | 1         | 0.68%   |
| D-Link                            | 1         | 0.68%   |
| AboCom Systems                    | 1         | 0.68%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 25        | 13.37%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 14        | 7.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 8         | 4.28%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 6         | 3.21%   |
| Intel Wireless 7260                                                                   | 6         | 3.21%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 6         | 3.21%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 5         | 2.67%   |
| Intel Wireless 8260                                                                   | 5         | 2.67%   |
| Intel Wireless 7265                                                                   | 5         | 2.67%   |
| Intel Wireless 8265 / 8275                                                            | 4         | 2.14%   |
| Intel WiFi Link 5100                                                                  | 4         | 2.14%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 3         | 1.6%    |
| Intel Ethernet Connection I218-LM                                                     | 3         | 1.6%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 3         | 1.6%    |
| Intel Centrino Wireless-N 2230                                                        | 3         | 1.6%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 3         | 1.6%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                             | 2         | 1.07%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 2         | 1.07%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 2         | 1.07%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                              | 2         | 1.07%   |
| Intel Wireless 3165                                                                   | 2         | 1.07%   |
| Intel Ultimate N WiFi Link 5300                                                       | 2         | 1.07%   |
| Intel Ethernet Connection I219-LM                                                     | 2         | 1.07%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                          | 2         | 1.07%   |
| Intel Centrino Advanced-N 6235                                                        | 2         | 1.07%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 2         | 1.07%   |
| Intel Centrino Advanced-N 6200                                                        | 2         | 1.07%   |
| Intel 82577LM Gigabit Network Connection                                              | 2         | 1.07%   |
| Intel 82567LM Gigabit Network Connection                                              | 2         | 1.07%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                                     | 2         | 1.07%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                                     | 2         | 1.07%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                       | 2         | 1.07%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 2         | 1.07%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                            | 1         | 0.53%   |
| Toshiba Ericsson H5321gw for TOSHIBA Mobile Broadband Network Adapter                 | 1         | 0.53%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                                         | 1         | 0.53%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.53%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 1         | 0.53%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                | 1         | 0.53%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                           | 1         | 0.53%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 0.53%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 1         | 0.53%   |
| Ralink RT5370 Wireless Adapter                                                        | 1         | 0.53%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 1         | 0.53%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                                | 1         | 0.53%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                             | 1         | 0.53%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 1         | 0.53%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 1         | 0.53%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                            | 1         | 0.53%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                            | 1         | 0.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                         | 1         | 0.53%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                              | 1         | 0.53%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.53%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                               | 1         | 0.53%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                               | 1         | 0.53%   |
| Intel Wi-Fi 6 AX200                                                                   | 1         | 0.53%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                               | 1         | 0.53%   |
| Intel Ethernet Connection I219-V                                                      | 1         | 0.53%   |
| Intel Ethernet Connection I218-V                                                      | 1         | 0.53%   |
| Intel Ethernet Connection (6) I219-V                                                  | 1         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 50        | 49.02%  |
| Qualcomm Atheros      | 26        | 25.49%  |
| Realtek Semiconductor | 9         | 8.82%   |
| Broadcom              | 9         | 8.82%   |
| Ralink                | 3         | 2.94%   |
| TP-Link               | 1         | 0.98%   |
| Sierra Wireless       | 1         | 0.98%   |
| Ralink Technology     | 1         | 0.98%   |
| D-Link                | 1         | 0.98%   |
| AboCom Systems        | 1         | 0.98%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 8         | 7.84%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 6         | 5.88%   |
| Intel Wireless 7260                                                                   | 6         | 5.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 5         | 4.9%    |
| Intel Wireless 8260                                                                   | 5         | 4.9%    |
| Intel Wireless 7265                                                                   | 5         | 4.9%    |
| Intel Wireless 8265 / 8275                                                            | 4         | 3.92%   |
| Intel WiFi Link 5100                                                                  | 4         | 3.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 3         | 2.94%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 3         | 2.94%   |
| Intel Centrino Wireless-N 2230                                                        | 3         | 2.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 3         | 2.94%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                             | 2         | 1.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 2         | 1.96%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 2         | 1.96%   |
| Intel Wireless 3165                                                                   | 2         | 1.96%   |
| Intel Ultimate N WiFi Link 5300                                                       | 2         | 1.96%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                          | 2         | 1.96%   |
| Intel Centrino Advanced-N 6235                                                        | 2         | 1.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 2         | 1.96%   |
| Intel Centrino Advanced-N 6200                                                        | 2         | 1.96%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 2         | 1.96%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                            | 1         | 0.98%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                                         | 1         | 0.98%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.98%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 1         | 0.98%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                | 1         | 0.98%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                           | 1         | 0.98%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 0.98%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 1         | 0.98%   |
| Ralink RT5370 Wireless Adapter                                                        | 1         | 0.98%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 1         | 0.98%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 1         | 0.98%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 1         | 0.98%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.98%   |
| Intel Wi-Fi 6 AX200                                                                   | 1         | 0.98%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                               | 1         | 0.98%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 1         | 0.98%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 1         | 0.98%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 1         | 0.98%   |
| D-Link DWA-171 AC600 DB Wireless Adapter(rev.A1) [Realtek RTL8811AU]                  | 1         | 0.98%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                    | 1         | 0.98%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                    | 1         | 0.98%   |
| Broadcom BCM43225 802.11b/g/n                                                         | 1         | 0.98%   |
| Broadcom BCM43224 802.11a/b/g/n                                                       | 1         | 0.98%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 1         | 0.98%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 1         | 0.98%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                     | 1         | 0.98%   |
| AboCom Systems 802.11n/b/g Mini Wireless LAN USB2.0 Adapter                           | 1         | 0.98%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 39        | 47.56%  |
| Intel                    | 24        | 29.27%  |
| Broadcom                 | 9         | 10.98%  |
| Qualcomm Atheros         | 8         | 9.76%   |
| Marvell Technology Group | 2         | 2.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 25        | 30.49%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 17.07%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 7.32%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 3.66%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 2.44%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 2.44%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 2.44%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 2.44%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 2.44%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 2.44%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 2.44%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.22%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.22%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.22%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 1.22%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.22%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.22%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 1.22%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.22%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.22%   |
| Intel Ethernet Connection I218-V                                  | 1         | 1.22%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.22%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.22%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 1.22%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 1.22%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.22%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.22%   |
| Intel 82567LF Gigabit Network Connection                          | 1         | 1.22%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 1.22%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 1.22%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 94        | 52.51%  |
| Ethernet | 82        | 45.81%  |
| Modem    | 3         | 1.68%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 83        | 50%     |
| Ethernet | 81        | 48.8%   |
| Modem    | 2         | 1.2%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 80        | 84.21%  |
| 1     | 15        | 15.79%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 89        | 92.71%  |
| Yes  | 7         | 7.29%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 33        | 52.38%  |
| Qualcomm Atheros Communications | 6         | 9.52%   |
| IMC Networks                    | 4         | 6.35%   |
| Broadcom                        | 4         | 6.35%   |
| Apple                           | 4         | 6.35%   |
| Realtek Semiconductor           | 3         | 4.76%   |
| Ralink                          | 2         | 3.17%   |
| Dell                            | 2         | 3.17%   |
| Cambridge Silicon Radio         | 2         | 3.17%   |
| Lite-On Technology              | 1         | 1.59%   |
| Hewlett-Packard                 | 1         | 1.59%   |
| Foxconn / Hon Hai               | 1         | 1.59%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 22        | 34.92%  |
| Intel Centrino Bluetooth Wireless Transceiver               | 4         | 6.35%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 4         | 6.35%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 3         | 4.76%   |
| Ralink RT3290 Bluetooth                                     | 2         | 3.17%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 2         | 3.17%   |
| Intel AX201 Bluetooth                                       | 2         | 3.17%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 2         | 3.17%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2         | 3.17%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 3.17%   |
| Realtek RTL8821A Bluetooth                                  | 1         | 1.59%   |
| Realtek  Bluetooth 4.0 + High Speed Chip                    | 1         | 1.59%   |
| Realtek CSR Bluetooth Chip                                  | 1         | 1.59%   |
| Qualcomm Atheros  QCA9565 Bluetooth 4.0 + HS Adapter        | 1         | 1.59%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 1.59%   |
| Qualcomm Atheros Atheros AR9462 Bluetooth 3.0 + HS Adapter  | 1         | 1.59%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 1.59%   |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS                 | 1         | 1.59%   |
| Intel AX200 Bluetooth                                       | 1         | 1.59%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0                 | 1         | 1.59%   |
| IMC Networks Broadcom BCM20702 Bluetooth 4.0 +HS USB Device | 1         | 1.59%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 1.59%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 1.59%   |
| Dell DW375 Bluetooth Module                                 | 1         | 1.59%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 1         | 1.59%   |
| Broadcom BCM43142A0 Bluetooth 4.0                           | 1         | 1.59%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                        | 1         | 1.59%   |
| Apple Bluetooth Host Controller                             | 1         | 1.59%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 88        | 85.44%  |
| AMD    | 10        | 9.71%   |
| Nvidia | 5         | 4.85%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 20        | 15.87%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 11        | 8.73%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 10        | 7.94%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 7.14%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 7.14%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7         | 5.56%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 4.76%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 4.76%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 4.76%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 3.17%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 2.38%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 2.38%   |
| AMD FCH Azalia Controller                                                                         | 3         | 2.38%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 1.59%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 1.59%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.59%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.59%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.59%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 2         | 1.59%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.79%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.79%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 0.79%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.79%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.79%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.79%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 0.79%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 0.79%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 0.79%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 0.79%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.79%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 0.79%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 0.79%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 0.79%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 0.79%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 0.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 27        | 22.88%  |
| SK Hynix            | 22        | 18.64%  |
| Micron Technology   | 14        | 11.86%  |
| Kingston            | 10        | 8.47%   |
| Elpida              | 10        | 8.47%   |
| Unknown             | 7         | 5.93%   |
| Smart               | 4         | 3.39%   |
| Ramaxel Technology  | 4         | 3.39%   |
| Crucial             | 4         | 3.39%   |
| Nanya Technology    | 3         | 2.54%   |
| Teikon              | 2         | 1.69%   |
| High Bridge         | 2         | 1.69%   |
| Apacer              | 2         | 1.69%   |
| Unknown (ABCD)      | 1         | 0.85%   |
| Transcend           | 1         | 0.85%   |
| Toshiba             | 1         | 0.85%   |
| Smart Brazil        | 1         | 0.85%   |
| SHARETRONIC         | 1         | 0.85%   |
| Corsair             | 1         | 0.85%   |
| A-DATA Technology   | 1         | 0.85%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 4         | 3.2%    |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s                     | 3         | 2.4%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1333MT/s                     | 3         | 2.4%    |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                               | 2         | 1.6%    |
| SK Hynix RAM Module 2GB SODIMM DDR3 1600MT/s                              | 2         | 1.6%    |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 2         | 1.6%    |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s                     | 2         | 1.6%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 2         | 1.6%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 2         | 1.6%    |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s                    | 2         | 1.6%    |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s                     | 2         | 1.6%    |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s                     | 2         | 1.6%    |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                               | 1         | 0.8%    |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                               | 1         | 0.8%    |
| Unknown RAM Module 4GB SODIMM DDR3                                        | 1         | 0.8%    |
| Unknown RAM Module 2048MB SODIMM 800MT/s                                  | 1         | 0.8%    |
| Unknown RAM Module 2048MB SODIMM 667MT/s                                  | 1         | 0.8%    |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s            | 1         | 0.8%    |
| Transcend RAM JM1600KSH-8G 8192MB SODIMM DDR3 1333MT/s                    | 1         | 0.8%    |
| Toshiba RAM 8HTF12864HDY-800G1 2048MB SODIMM 800MT/s                      | 1         | 0.8%    |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 800MT/s                       | 1         | 0.8%    |
| Teikon RAM TMT451S6BFR8A-PBSC 4096MB SODIMM DDR3 1600MT/s                 | 1         | 0.8%    |
| Teikon RAM TML251S6EFR8A-PBHC 4096MB SODIMM DDR3 1600MT/s                 | 1         | 0.8%    |
| Smart RAM SH564568FH8NWPHSFR 2GB SODIMM DDR3 1333MT/s                     | 1         | 0.8%    |
| Smart RAM SH564128FJ8NZRNSDR 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.8%    |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4096MB SODIMM DDR4 2400MT/s           | 1         | 0.8%    |
| SK Hynix RAM Module 2GB DDR3 1600MT/s                                     | 1         | 0.8%    |
| SK Hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s                      | 1         | 0.8%    |
| SK Hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1333MT/s                    | 1         | 0.8%    |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s                    | 1         | 0.8%    |
| SK Hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s                    | 1         | 0.8%    |
| SK Hynix RAM HMT325S6CFR8C-H9 2048MB SODIMM DDR3 1333MT/s                 | 1         | 0.8%    |
| SK Hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s                    | 1         | 0.8%    |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16384MB SODIMM DDR4 3200MT/s                | 1         | 0.8%    |
| SK Hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s                    | 1         | 0.8%    |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s                    | 1         | 0.8%    |
| SK Hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 1         | 0.8%    |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 1         | 0.8%    |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB Chip DDR4 2133MT/s                   | 1         | 0.8%    |
| SK Hynix RAM 9A9A9A9A9A9A9A9A9A9A9A9A9A9A9A9A9A9A 2GB SODIMM DDR2 800MT/s | 1         | 0.8%    |
| SK Hynix RAM 313131313131313131313131313131313131 2GB SODIMM DDR2 800MT/s | 1         | 0.8%    |
| SHARETRONIC RAM Module 2GB SODIMM DDR3 1600MT/s                           | 1         | 0.8%    |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                               | 1         | 0.8%    |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s                     | 1         | 0.8%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1333MT/s                     | 1         | 0.8%    |
| Samsung RAM M471B5674EB0-YMA 2GB Row Of Chips DDR3 1600MT/s               | 1         | 0.8%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.8%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 1         | 0.8%    |
| Samsung RAM M471B5273BH1-CH9 4096MB SODIMM DDR3 1333MT/s                  | 1         | 0.8%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.8%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.8%    |
| Samsung RAM M471B1G73AH0-CH9 8GB SODIMM DDR3 1333MT/s                     | 1         | 0.8%    |
| Samsung RAM M471A5644EB0-CPB 2048MB SODIMM DDR4 2133MT/s                  | 1         | 0.8%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s                     | 1         | 0.8%    |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s                     | 1         | 0.8%    |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s                    | 1         | 0.8%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 1         | 0.8%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s                     | 1         | 0.8%    |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2133MT/s                     | 1         | 0.8%    |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s              | 1         | 0.8%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 61        | 64.89%  |
| DDR4    | 22        | 23.4%   |
| DDR2    | 4         | 4.26%   |
| Unknown | 4         | 4.26%   |
| LPDDR3  | 2         | 2.13%   |
| LPDDR4  | 1         | 1.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 88        | 92.63%  |
| Row Of Chips | 3         | 3.16%   |
| Chip         | 2         | 2.11%   |
| DIMM         | 1         | 1.05%   |
| Unknown      | 1         | 1.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 44        | 41.12%  |
| 2048  | 33        | 30.84%  |
| 8192  | 22        | 20.56%  |
| 16384 | 7         | 6.54%   |
| 32768 | 1         | 0.93%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 39        | 36.45%  |
| 1333    | 22        | 20.56%  |
| 2400    | 11        | 10.28%  |
| 2667    | 8         | 7.48%   |
| 2133    | 5         | 4.67%   |
| 1334    | 5         | 4.67%   |
| 800     | 5         | 4.67%   |
| 1067    | 3         | 2.8%    |
| 1867    | 2         | 1.87%   |
| 667     | 2         | 1.87%   |
| 3200    | 1         | 0.93%   |
| 1777    | 1         | 0.93%   |
| 1066    | 1         | 0.93%   |
| 975     | 1         | 0.93%   |
| Unknown | 1         | 0.93%   |

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
| Chicony Electronics                    | 17        | 25.37%  |
| Realtek Semiconductor                  | 10        | 14.93%  |
| Sunplus Innovation Technology          | 6         | 8.96%   |
| Microdia                               | 6         | 8.96%   |
| Acer                                   | 4         | 5.97%   |
| Suyin                                  | 3         | 4.48%   |
| IMC Networks                           | 3         | 4.48%   |
| Syntek                                 | 2         | 2.99%   |
| Silicon Motion                         | 2         | 2.99%   |
| Lite-On Technology                     | 2         | 2.99%   |
| Importek                               | 2         | 2.99%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.99%   |
| Apple                                  | 2         | 2.99%   |
| Alcor Micro                            | 2         | 2.99%   |
| Ricoh                                  | 1         | 1.49%   |
| Quanta                                 | 1         | 1.49%   |
| Logitech                               | 1         | 1.49%   |
| Holitech                               | 1         | 1.49%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                              | 4         | 5.88%   |
| Realtek Realtek USB2.0 PC Camera                          | 3         | 4.41%   |
| Chicony integrated camera                                 | 3         | 4.41%   |
| Chicony HP HD Webcam [Fixed]                              | 3         | 4.41%   |
| Sunplus Integrated_Webcam_HD                              | 2         | 2.94%   |
| Sunplus Asus Webcam                                       | 2         | 2.94%   |
| Realtek Integrated Webcam                                 | 2         | 2.94%   |
| Microdia Laptop_Integrated_Webcam_HD                      | 2         | 2.94%   |
| Microdia Integrated Webcam                                | 2         | 2.94%   |
| IMC Networks USB2.0 HD UVC WebCam                         | 2         | 2.94%   |
| Chicony Integrated Camera [ThinkPad]                      | 2         | 2.94%   |
| Apple FaceTime HD Camera                                  | 2         | 2.94%   |
| Syntek Lenovo EasyCamera                                  | 1         | 1.47%   |
| Syntek EasyCamera                                         | 1         | 1.47%   |
| Suyin USB 2.0 Camera                                      | 1         | 1.47%   |
| Suyin Sony Visual Communication Camera                    | 1         | 1.47%   |
| Suyin HP Integrated Webcam                                | 1         | 1.47%   |
| Sunplus Integrated Camera                                 | 1         | 1.47%   |
| Sunplus Dell E5570 integrated webcam                      | 1         | 1.47%   |
| Silicon Motion WebCam SCX Series                          | 1         | 1.47%   |
| Silicon Motion Realtek USB2.0 PC Camera                   | 1         | 1.47%   |
| Ricoh Integrated Camera                                   | 1         | 1.47%   |
| Realtek LG Camera                                         | 1         | 1.47%   |
| Quanta HP Webcam                                          | 1         | 1.47%   |
| Microdia Laptop_Integrated_Webcam_FHD                     | 1         | 1.47%   |
| Microdia HP Webcam                                        | 1         | 1.47%   |
| Logitech Webcam C270                                      | 1         | 1.47%   |
| Lite-On Integrated Camera                                 | 1         | 1.47%   |
| Lite-On HP IR Camera                                      | 1         | 1.47%   |
| Importek TOSHIBA Web Camera - HD                          | 1         | 1.47%   |
| Importek TOSHIBA Web Camera                               | 1         | 1.47%   |
| IMC Networks EasyCamera                                   | 1         | 1.47%   |
| Holitech USB2.0 HD UVC WebCam                             | 1         | 1.47%   |
| Chicony UVC 1.00 device HD UVC WebCam                     | 1         | 1.47%   |
| Chicony USB2.0 VGA UVC WebCam                             | 1         | 1.47%   |
| Chicony TOSHIBA Web Camera - HD                           | 1         | 1.47%   |
| Chicony TOSHIBA Web Camera - 3M                           | 1         | 1.47%   |
| Chicony Lenovo EasyCamera                                 | 1         | 1.47%   |
| Chicony HP Webcam [2 MP Macro]                            | 1         | 1.47%   |
| Chicony HP HD Camera                                      | 1         | 1.47%   |
| Chicony HD WebCam                                         | 1         | 1.47%   |
| Chicony Chicony USB2.0 Camera                             | 1         | 1.47%   |
| Chicony 1.3M Webcam                                       | 1         | 1.47%   |
| Cheng Uei Precision Industry (Foxlink) Webcam             | 1         | 1.47%   |
| Cheng Uei Precision Industry (Foxlink) Realtek DMFT - RGB | 1         | 1.47%   |
| Alcor Micro USB 2.0 Camera                                | 1         | 1.47%   |
| Alcor Micro Acer Integrated Webcam                        | 1         | 1.47%   |
| Acer Lenovo Integrated Webcam                             | 1         | 1.47%   |
| Acer Lenovo EasyCamera                                    | 1         | 1.47%   |
| Acer Integrated Camera                                    | 1         | 1.47%   |
| Acer HD Webcam                                            | 1         | 1.47%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 7         | 77.78%  |
| Broadcom         | 1         | 11.11%  |
| AuthenTec        | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                                  | 3         | 33.33%  |
| Validity Sensors VFS495 Fingerprint Reader                                   | 1         | 11.11%  |
| Validity Sensors VFS451 Fingerprint Reader                                   | 1         | 11.11%  |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 1         | 11.11%  |
| Validity Sensors Synaptics WBDI                                              | 1         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 11.11%  |
| AuthenTec AES2810                                                            | 1         | 11.11%  |

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
| 2     | 37        | 38.14%  |
| 1     | 26        | 26.8%   |
| 3     | 21        | 21.65%  |
| 0     | 7         | 7.22%   |
| 4     | 6         | 6.19%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 76        | 43.18%  |
| Card reader              | 47        | 26.7%   |
| Bluetooth                | 17        | 9.66%   |
| Net/wireless             | 15        | 8.52%   |
| Fingerprint reader       | 9         | 5.11%   |
| Firewire controller      | 7         | 3.98%   |
| Storage                  | 2         | 1.14%   |
| Sound                    | 2         | 1.14%   |
| Dvb card                 | 1         | 0.57%   |

