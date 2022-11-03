helloSystem 0.5.0 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for helloSystem 0.5.0.

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

Total: 137

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Fujitsu Si... | ESPRIMO Mobile V5535        | [f4c9b911fe](https://bsd-hardware.info/?probe=f4c9b911fe) | Jan 16, 2022 |
| Packard Be... | EasyNote_MX61-B-038         | [235d60060d](https://bsd-hardware.info/?probe=235d60060d) | Dec 12, 2021 |
| HP            | Laptop 15-dw0xxx            | [4903f23b62](https://bsd-hardware.info/?probe=4903f23b62) | Dec 05, 2021 |
| HP            | EliteBook 840 G3            | [03be88ded4](https://bsd-hardware.info/?probe=03be88ded4) | Nov 02, 2021 |
| HP            | ProBook 470 G4              | [5f026ff3a2](https://bsd-hardware.info/?probe=5f026ff3a2) | Oct 17, 2021 |
| Lenovo        | G500s 20245                 | [e6141c9ab3](https://bsd-hardware.info/?probe=e6141c9ab3) | Oct 16, 2021 |
| Lenovo        | ThinkPad X230 23254G7       | [06c6a282ca](https://bsd-hardware.info/?probe=06c6a282ca) | Oct 16, 2021 |
| HP            | Pavilion dv3                | [7f0b7f520f](https://bsd-hardware.info/?probe=7f0b7f520f) | Oct 14, 2021 |
| HP            | ProBook 470 G4              | [a9c135bf27](https://bsd-hardware.info/?probe=a9c135bf27) | Oct 10, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [fc1eda0998](https://bsd-hardware.info/?probe=fc1eda0998) | Oct 08, 2021 |
| Toshiba       | dynabook Satellite B453/... | [e621531452](https://bsd-hardware.info/?probe=e621531452) | Oct 05, 2021 |
| ASUSTek       | X441BA                      | [2fcb818b78](https://bsd-hardware.info/?probe=2fcb818b78) | Oct 04, 2021 |
| Lenovo        | ThinkPad T490s 20NYS3TU0... | [d377309110](https://bsd-hardware.info/?probe=d377309110) | Oct 02, 2021 |
| Lenovo        | ThinkPad X230 Tablet 343... | [efdfee9023](https://bsd-hardware.info/?probe=efdfee9023) | Oct 01, 2021 |
| Lenovo        | ThinkPad X230 2325O76       | [b8729e39e1](https://bsd-hardware.info/?probe=b8729e39e1) | Sep 29, 2021 |
| Toshiba       | Satellite P300              | [13e4aa7026](https://bsd-hardware.info/?probe=13e4aa7026) | Sep 29, 2021 |
| Lenovo        | ThinkPad L520 78594KM       | [7905093412](https://bsd-hardware.info/?probe=7905093412) | Sep 26, 2021 |
| Lenovo        | ThinkPad T410 2537E82       | [4ccdde7b89](https://bsd-hardware.info/?probe=4ccdde7b89) | Sep 20, 2021 |
| Lenovo        | ThinkPad T61 64607EU        | [34e48b691d](https://bsd-hardware.info/?probe=34e48b691d) | Sep 17, 2021 |
| HP            | G42                         | [738ccd1adf](https://bsd-hardware.info/?probe=738ccd1adf) | Sep 15, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [7979c87340](https://bsd-hardware.info/?probe=7979c87340) | Sep 14, 2021 |
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
| HP            | OMEN by Laptop              | [abc94e9198](https://bsd-hardware.info/?probe=abc94e9198) | Jun 13, 2021 |
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
| Lenovo        | ThinkPad E420 1141A83       | [a48872901d](https://bsd-hardware.info/?probe=a48872901d) | Feb 20, 2021 |
| HP            | ProBook 440 G2              | [63038d613f](https://bsd-hardware.info/?probe=63038d613f) | Feb 19, 2021 |
| Lenovo        | ZIUS6                       | [1c239bac92](https://bsd-hardware.info/?probe=1c239bac92) | Feb 18, 2021 |
| Lenovo        | ThinkPad T490 20RYS06R00    | [12c985b708](https://bsd-hardware.info/?probe=12c985b708) | Feb 17, 2021 |
| HP            | Pavilion Laptop 14-ce2xx... | [c355a6280b](https://bsd-hardware.info/?probe=c355a6280b) | Feb 17, 2021 |
| HP            | OMEN by Laptop              | [bb8beb97be](https://bsd-hardware.info/?probe=bb8beb97be) | Feb 17, 2021 |
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
| amd64 | 115       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 114       | 99.13%  |
| KDE5         | 1         | 0.87%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 115       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SLiM | 115       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 115       | 100%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 92        | 80%     |
| BIOS | 23        | 20%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Zfs  | 115       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 115       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 32        | 27.83%  |
| Hewlett-Packard     | 20        | 17.39%  |
| Dell                | 19        | 16.52%  |
| ASUSTek Computer    | 10        | 8.7%    |
| Toshiba             | 8         | 6.96%   |
| Apple               | 5         | 4.35%   |
| Acer                | 3         | 2.61%   |
| Samsung Electronics | 2         | 1.74%   |
| Packard Bell        | 2         | 1.74%   |
| Gateway             | 2         | 1.74%   |
| WYSE                | 1         | 0.87%   |
| TUXEDO              | 1         | 0.87%   |
| Sony                | 1         | 0.87%   |
| NEC Computers       | 1         | 0.87%   |
| MSI                 | 1         | 0.87%   |
| MouseComputer       | 1         | 0.87%   |
| LG Electronics      | 1         | 0.87%   |
| Hampoo              | 1         | 0.87%   |
| Fujitsu Siemens     | 1         | 0.87%   |
| Fujitsu             | 1         | 0.87%   |
| eMachines           | 1         | 0.87%   |
| Alienware           | 1         | 0.87%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Dell Inspiron 15-3567                       | 3         | 2.61%   |
| HP EliteBook 840 G3                         | 2         | 1.74%   |
| Gateway NE56R                               | 2         | 1.74%   |
| Dell Inspiron 7520                          | 2         | 1.74%   |
| Apple MacBookPro9,2                         | 2         | 1.74%   |
| WYSE Z CLASS                                | 1         | 0.87%   |
| TUXEDO Aura 15 Gen1                         | 1         | 0.87%   |
| Toshiba Satellite Pro U400                  | 1         | 0.87%   |
| Toshiba Satellite P300                      | 1         | 0.87%   |
| Toshiba Satellite L855                      | 1         | 0.87%   |
| Toshiba Satellite L500                      | 1         | 0.87%   |
| Toshiba Satellite C640                      | 1         | 0.87%   |
| Toshiba PORTEGE Z10t-A                      | 1         | 0.87%   |
| Toshiba PORTEGE R930                        | 1         | 0.87%   |
| Toshiba dynabook Satellite B453/L           | 1         | 0.87%   |
| Sony VPCEJ1E1E                              | 1         | 0.87%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 1         | 0.87%   |
| Samsung 530U3C/530U4C/532U3C                | 1         | 0.87%   |
| Packard Bell EasyNote_MX61-B-038            | 1         | 0.87%   |
| Packard Bell EasyNote MH36                  | 1         | 0.87%   |
| NEC Computers PC-VK17HBBCD                  | 1         | 0.87%   |
| MSI GF65 Thin 10SDR                         | 1         | 0.87%   |
| MouseComputer W331AU                        | 1         | 0.87%   |
| LG 14Z980-G.BH51P1                          | 1         | 0.87%   |
| Lenovo ZIUS6                                | 1         | 0.87%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS          | 1         | 0.87%   |
| Lenovo ThinkPad X260 20F5S82N00             | 1         | 0.87%   |
| Lenovo ThinkPad X250 20CLS4JH00             | 1         | 0.87%   |
| Lenovo ThinkPad X240 20AMS39F0K             | 1         | 0.87%   |
| Lenovo ThinkPad X230 Tablet 343522U         | 1         | 0.87%   |
| Lenovo ThinkPad X230 2330A48                | 1         | 0.87%   |
| Lenovo ThinkPad X230 2325WWB                | 1         | 0.87%   |
| Lenovo ThinkPad X230 2325O76                | 1         | 0.87%   |
| Lenovo ThinkPad X230 23255Y4                | 1         | 0.87%   |
| Lenovo ThinkPad X230 23254G7                | 1         | 0.87%   |
| Lenovo ThinkPad X200 7458VP4                | 1         | 0.87%   |
| Lenovo ThinkPad T61 64607EU                 | 1         | 0.87%   |
| Lenovo ThinkPad T490s 20NYS3TU00            | 1         | 0.87%   |
| Lenovo ThinkPad T490 20RYS06R00             | 1         | 0.87%   |
| Lenovo ThinkPad T470p 20J6A012CD            | 1         | 0.87%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 22        | 19.13%  |
| Dell Latitude              | 8         | 6.96%   |
| HP Pavilion                | 6         | 5.22%   |
| Dell Inspiron              | 6         | 5.22%   |
| Toshiba Satellite          | 5         | 4.35%   |
| HP ProBook                 | 3         | 2.61%   |
| HP EliteBook               | 3         | 2.61%   |
| Acer Aspire                | 3         | 2.61%   |
| Toshiba PORTEGE            | 2         | 1.74%   |
| Packard Bell EasyNote      | 2         | 1.74%   |
| Lenovo IdeaPad             | 2         | 1.74%   |
| Gateway NE56R              | 2         | 1.74%   |
| Dell Vostro                | 2         | 1.74%   |
| ASUS VivoBook              | 2         | 1.74%   |
| Apple MacBookPro9          | 2         | 1.74%   |
| WYSE Z                     | 1         | 0.87%   |
| TUXEDO Aura                | 1         | 0.87%   |
| Toshiba dynabook           | 1         | 0.87%   |
| Sony VPCEJ1E1E             | 1         | 0.87%   |
| Samsung RV411              | 1         | 0.87%   |
| Samsung 530U3C             | 1         | 0.87%   |
| NEC Computers PC-VK17HBBCD | 1         | 0.87%   |
| MSI GF65                   | 1         | 0.87%   |
| MouseComputer W331AU       | 1         | 0.87%   |
| LG 14Z980-G.BH51P1         | 1         | 0.87%   |
| Lenovo ZIUS6               | 1         | 0.87%   |
| Lenovo Yoga                | 1         | 0.87%   |
| Lenovo Legion              | 1         | 0.87%   |
| Lenovo G550                | 1         | 0.87%   |
| Lenovo G500s               | 1         | 0.87%   |
| Lenovo G500                | 1         | 0.87%   |
| Lenovo G470                | 1         | 0.87%   |
| Lenovo B41-80              | 1         | 0.87%   |
| HP Stream                  | 1         | 0.87%   |
| HP OMEN                    | 1         | 0.87%   |
| HP Laptop                  | 1         | 0.87%   |
| HP G42                     | 1         | 0.87%   |
| HP 625                     | 1         | 0.87%   |
| HP 255                     | 1         | 0.87%   |
| HP 250                     | 1         | 0.87%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2013 | 16        | 13.91%  |
| 2020 | 14        | 12.17%  |
| 2019 | 12        | 10.43%  |
| 2012 | 10        | 8.7%    |
| 2009 | 10        | 8.7%    |
| 2015 | 9         | 7.83%   |
| 2011 | 9         | 7.83%   |
| 2018 | 8         | 6.96%   |
| 2014 | 8         | 6.96%   |
| 2016 | 7         | 6.09%   |
| 2010 | 3         | 2.61%   |
| 2007 | 3         | 2.61%   |
| 2021 | 2         | 1.74%   |
| 2017 | 2         | 1.74%   |
| 2008 | 2         | 1.74%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 115       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 114       | 99.13%  |
| Yes  | 1         | 0.87%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 50        | 43.48%  |
| 8.01-16.0  | 44        | 38.26%  |
| 16.01-24.0 | 15        | 13.04%  |
| 32.01-64.0 | 3         | 2.61%   |
| 3.01-4.0   | 1         | 0.87%   |
| 24.01-32.0 | 1         | 0.87%   |
| 2.01-3.0   | 1         | 0.87%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 79        | 68.7%   |
| 0.51-1.0  | 29        | 25.22%  |
| 2.01-3.0  | 3         | 2.61%   |
| 1.01-2.0  | 3         | 2.61%   |
| 8.01-16.0 | 1         | 0.87%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 92        | 79.31%  |
| 2      | 15        | 12.93%  |
| 0      | 7         | 6.03%   |
| 3      | 2         | 1.72%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 59        | 51.3%   |
| No        | 56        | 48.7%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 101       | 87.83%  |
| No        | 14        | 12.17%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 113       | 98.26%  |
| No        | 2         | 1.74%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 73        | 63.48%  |
| No        | 42        | 36.52%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| USA                | 20        | 17.24%  |
| Germany            | 12        | 10.34%  |
| Brazil             | 9         | 7.76%   |
| Netherlands        | 6         | 5.17%   |
| Italy              | 5         | 4.31%   |
| China              | 5         | 4.31%   |
| UK                 | 4         | 3.45%   |
| Sweden             | 4         | 3.45%   |
| Spain              | 4         | 3.45%   |
| Switzerland        | 3         | 2.59%   |
| Poland             | 3         | 2.59%   |
| Indonesia          | 3         | 2.59%   |
| India              | 3         | 2.59%   |
| Ukraine            | 2         | 1.72%   |
| Portugal           | 2         | 1.72%   |
| Mexico             | 2         | 1.72%   |
| Lithuania          | 2         | 1.72%   |
| Japan              | 2         | 1.72%   |
| Canada             | 2         | 1.72%   |
| South Africa       | 1         | 0.86%   |
| Slovakia           | 1         | 0.86%   |
| Puerto Rico        | 1         | 0.86%   |
| Oman               | 1         | 0.86%   |
| New Zealand        | 1         | 0.86%   |
| Morocco            | 1         | 0.86%   |
| Montenegro         | 1         | 0.86%   |
| Malta              | 1         | 0.86%   |
| Malaysia           | 1         | 0.86%   |
| Latvia             | 1         | 0.86%   |
| Hungary            | 1         | 0.86%   |
| Greece             | 1         | 0.86%   |
| France             | 1         | 0.86%   |
| Finland            | 1         | 0.86%   |
| Dominican Republic | 1         | 0.86%   |
| Cyprus             | 1         | 0.86%   |
| Croatia            | 1         | 0.86%   |
| Bulgaria           | 1         | 0.86%   |
| Belgium            | 1         | 0.86%   |
| Belarus            | 1         | 0.86%   |
| Austria            | 1         | 0.86%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Zurich             | 2         | 1.69%   |
| Wroclaw            | 2         | 1.69%   |
| Surabaya           | 2         | 1.69%   |
| Berlin             | 2         | 1.69%   |
| Zhengzhou          | 1         | 0.85%   |
| Zagreb             | 1         | 0.85%   |
| Wuhan              | 1         | 0.85%   |
| Washington         | 1         | 0.85%   |
| Warmond            | 1         | 0.85%   |
| Wandur             | 1         | 0.85%   |
| Vilnius            | 1         | 0.85%   |
| Vigonovo           | 1         | 0.85%   |
| Vienna             | 1         | 0.85%   |
| VÃ¤sterÃ¥s     | 1         | 0.85%   |
| Vancouver          | 1         | 0.85%   |
| Utrecht            | 1         | 0.85%   |
| Tula de Allende    | 1         | 0.85%   |
| Traverse City      | 1         | 0.85%   |
| The Bronx          | 1         | 0.85%   |
| Tangara            | 1         | 0.85%   |
| Sungai Buloh       | 1         | 0.85%   |
| Solarino           | 1         | 0.85%   |
| Sofia              | 1         | 0.85%   |
| Shibakoen          | 1         | 0.85%   |
| Shasta             | 1         | 0.85%   |
| SÃ£o Paulo       | 1         | 0.85%   |
| Santo Domingo Este | 1         | 0.85%   |
| Sankt Augustin     | 1         | 0.85%   |
| Roosendaal         | 1         | 0.85%   |
| Riga               | 1         | 0.85%   |
| Redondela          | 1         | 0.85%   |
| Pleidelsheim       | 1         | 0.85%   |
| Plav               | 1         | 0.85%   |
| Plattsburgh        | 1         | 0.85%   |
| Perwez             | 1         | 0.85%   |
| Padova             | 1         | 0.85%   |
| Osasco             | 1         | 0.85%   |
| Oosterhout         | 1         | 0.85%   |
| Oklahoma City      | 1         | 0.85%   |
| Notting Hill Gate  | 1         | 0.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 19     | 14.63%  |
| WDC                 | 17        | 17     | 13.82%  |
| Samsung Electronics | 16        | 21     | 13.01%  |
| Toshiba             | 12        | 12     | 9.76%   |
| Crucial             | 11        | 11     | 8.94%   |
| SanDisk             | 6         | 6      | 4.88%   |
| Intel               | 6         | 6      | 4.88%   |
| Hitachi             | 6         | 7      | 4.88%   |
| Kingston            | 5         | 6      | 4.07%   |
| A-DATA Technology   | 4         | 5      | 3.25%   |
| SPCC                | 2         | 2      | 1.63%   |
| OCZ                 | 2         | 2      | 1.63%   |
| HGST                | 2         | 2      | 1.63%   |
| Apple               | 2         | 2      | 1.63%   |
| Transcend           | 1         | 2      | 0.81%   |
| SSSTC               | 1         | 1      | 0.81%   |
| Smart               | 1         | 1      | 0.81%   |
| SK hynix            | 1         | 1      | 0.81%   |
| PNY                 | 1         | 1      | 0.81%   |
| Patriot             | 1         | 1      | 0.81%   |
| MyDigitalSSD        | 1         | 1      | 0.81%   |
| Micron Technology   | 1         | 1      | 0.81%   |
| LITEONIT            | 1         | 1      | 0.81%   |
| LITEON              | 1         | 1      | 0.81%   |
| KingSpec            | 1         | 1      | 0.81%   |
| HPE                 | 1         | 1      | 0.81%   |
| Hewlett-Packard     | 1         | 2      | 0.81%   |
| Fujitsu             | 1         | 1      | 0.81%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 3         | 2.38%   |
| Seagate ST9500325AS 500GB            | 2         | 1.59%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 2         | 1.59%   |
| Samsung SSD 850 EVO 250GB            | 2         | 1.59%   |
| Kingston SA400S37120G 120GB          | 2         | 1.59%   |
| Crucial CT1000MX500SSD1 1TB          | 2         | 1.59%   |
| A-DATA SU650 120GB                   | 2         | 1.59%   |
| WDC WDS240G2G0A-00JH30 240GB         | 1         | 0.79%   |
| WDC WDS120G1G0A-00SS50 120GB         | 1         | 0.79%   |
| WDC WDBNCE2500PNC 250GB              | 1         | 0.79%   |
| WDC WD800BEVS-00RST0 80GB            | 1         | 0.79%   |
| WDC WD7500BPVX-60JC3T0 752GB         | 1         | 0.79%   |
| WDC WD5000LPVX-60V0TT0 500GB         | 1         | 0.79%   |
| WDC WD5000LPVX-00V0TT0 500GB         | 1         | 0.79%   |
| WDC WD3200BEVT-60ZCT1 320GB          | 1         | 0.79%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 0.79%   |
| WDC WD3200BEKT-75PVMT1 320GB         | 1         | 0.79%   |
| WDC WD2500BEVT-75ZCT2 250GB          | 1         | 0.79%   |
| WDC WD1600BEVT-75ZCT2 160GB          | 1         | 0.79%   |
| WDC WD10SPZX-24Z10 1TB               | 1         | 0.79%   |
| WDC WD10JPVX-00JC3T0 1TB             | 1         | 0.79%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB   | 1         | 0.79%   |
| WDC PC SN530 SDBPNPZ-512G-1032 512GB | 1         | 0.79%   |
| WDC PC SN530 SDBPNPZ-256G-1002 256GB | 1         | 0.79%   |
| Transcend TS512GMTS430S 512GB        | 1         | 0.79%   |
| Toshiba THNSNF128GCSS 128GB          | 1         | 0.79%   |
| Toshiba THNSNC128GMLJ 128GB          | 1         | 0.79%   |
| Toshiba MQ01ABF050 500GB             | 1         | 0.79%   |
| Toshiba MQ01ABD100 1TB               | 1         | 0.79%   |
| Toshiba MQ01ABD075 752GB             | 1         | 0.79%   |
| Toshiba MQ01ABD032 320GB             | 1         | 0.79%   |
| Toshiba MK3265GSXN 320GB             | 1         | 0.79%   |
| Toshiba MK3261GSYN 320GB             | 1         | 0.79%   |
| Toshiba MK3261GSY 320GB              | 1         | 0.79%   |
| Toshiba KXG50PNV2T04 NVMe 2048GB     | 1         | 0.79%   |
| Toshiba KBG40ZNS256G NVMe 256GB      | 1         | 0.79%   |
| Toshiba KBG30ZMV256G 256GB           | 1         | 0.79%   |
| SSSTC CVB-8D128-HP 128GB             | 1         | 0.79%   |
| SPCC Solid State Disk 256GB          | 1         | 0.79%   |
| SPCC Solid State Disk 1TB            | 1         | 0.79%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 19     | 36.73%  |
| WDC                 | 11        | 11     | 22.45%  |
| Toshiba             | 7         | 7      | 14.29%  |
| Hitachi             | 6         | 7      | 12.24%  |
| Samsung Electronics | 3         | 3      | 6.12%   |
| HGST                | 2         | 2      | 4.08%   |
| Fujitsu             | 1         | 1      | 2.04%   |
| Apple               | 1         | 1      | 2.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 15     | 19.35%  |
| Crucial             | 10        | 10     | 16.13%  |
| SanDisk             | 6         | 6      | 9.68%   |
| Kingston            | 5         | 6      | 8.06%   |
| Intel               | 4         | 4      | 6.45%   |
| WDC                 | 3         | 3      | 4.84%   |
| A-DATA Technology   | 3         | 4      | 4.84%   |
| Toshiba             | 2         | 2      | 3.23%   |
| SPCC                | 2         | 2      | 3.23%   |
| OCZ                 | 2         | 2      | 3.23%   |
| Transcend           | 1         | 2      | 1.61%   |
| SSSTC               | 1         | 1      | 1.61%   |
| Smart               | 1         | 1      | 1.61%   |
| PNY                 | 1         | 1      | 1.61%   |
| Patriot             | 1         | 1      | 1.61%   |
| MyDigitalSSD        | 1         | 1      | 1.61%   |
| Micron Technology   | 1         | 1      | 1.61%   |
| LITEONIT            | 1         | 1      | 1.61%   |
| LITEON              | 1         | 1      | 1.61%   |
| KingSpec            | 1         | 1      | 1.61%   |
| HPE                 | 1         | 1      | 1.61%   |
| Hewlett-Packard     | 1         | 2      | 1.61%   |
| Apple               | 1         | 1      | 1.61%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 57        | 69     | 47.9%   |
| HDD  | 49        | 51     | 41.18%  |
| NVMe | 13        | 14     | 10.92%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 99        | 120    | 88.39%  |
| NVMe | 13        | 14     | 11.61%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 81        | 95     | 78.64%  |
| 0.51-1.0   | 20        | 23     | 19.42%  |
| 1.01-2.0   | 2         | 2      | 1.94%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 67        | 58.26%  |
| 101-250    | 19        | 16.52%  |
| 251-500    | 16        | 13.91%  |
| 501-1000   | 6         | 5.22%   |
| 51-100     | 4         | 3.48%   |
| 21-50      | 2         | 1.74%   |
| 1001-2000  | 1         | 0.87%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 115       | 100%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                    | Notebooks | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB           | 2         | 2      | 7.14%   |
| WDC WD5000LPVX-60V0TT0 500GB             | 1         | 1      | 3.57%   |
| WDC WD3200BEVT-22ZCT0 320GB              | 1         | 1      | 3.57%   |
| Toshiba MQ01ABD075 752GB                 | 1         | 1      | 3.57%   |
| Toshiba MQ01ABD032 320GB                 | 1         | 1      | 3.57%   |
| Toshiba MK3265GSXN 320GB                 | 1         | 1      | 3.57%   |
| Toshiba MK3261GSYN 320GB                 | 1         | 1      | 3.57%   |
| SSSTC CVB-8D128-HP 128GB                 | 1         | 1      | 3.57%   |
| Seagate ST9500325AS 500GB                | 1         | 1      | 3.57%   |
| Seagate ST9320423AS 320GB                | 1         | 1      | 3.57%   |
| Seagate ST9160821AS 160GB                | 1         | 1      | 3.57%   |
| Seagate ST9160412AS 160GB                | 1         | 1      | 3.57%   |
| Seagate ST500LM012 HN-M500MBB 500GB      | 1         | 1      | 3.57%   |
| Seagate ST320LT012-9WS14C 320GB          | 1         | 2      | 3.57%   |
| Seagate ST1000LM049-2GH172 1TB           | 1         | 1      | 3.57%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 1         | 1      | 3.57%   |
| Samsung Electronics SSD 840 Series 500GB | 1         | 1      | 3.57%   |
| Kingston RBU-SNS8350DES3128GP 128GB      | 1         | 1      | 3.57%   |
| Hitachi HTS545050B9A300 500GB            | 1         | 1      | 3.57%   |
| Hitachi HTS545050A7E380 500GB            | 1         | 1      | 3.57%   |
| Hitachi HTS545032B9A300 320GB            | 1         | 1      | 3.57%   |
| Hitachi HTS545025B9SA02 250GB            | 1         | 1      | 3.57%   |
| HGST HTS721010A9E630 1TB                 | 1         | 1      | 3.57%   |
| Hewlett-Packard SSD S700 1TB             | 1         | 1      | 3.57%   |
| Fujitsu MHW2160BH 160GB                  | 1         | 1      | 3.57%   |
| Crucial CT525MX300SSD1 528GB             | 1         | 1      | 3.57%   |
| Apple HDD HTS545050A7E362 500GB          | 1         | 1      | 3.57%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 11     | 35.71%  |
| Toshiba             | 4         | 4      | 14.29%  |
| Hitachi             | 4         | 4      | 14.29%  |
| WDC                 | 2         | 2      | 7.14%   |
| SSSTC               | 1         | 1      | 3.57%   |
| Samsung Electronics | 1         | 1      | 3.57%   |
| Kingston            | 1         | 1      | 3.57%   |
| HGST                | 1         | 1      | 3.57%   |
| Hewlett-Packard     | 1         | 1      | 3.57%   |
| Fujitsu             | 1         | 1      | 3.57%   |
| Crucial             | 1         | 1      | 3.57%   |
| Apple               | 1         | 1      | 3.57%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 10        | 11     | 43.48%  |
| Toshiba | 4         | 4      | 17.39%  |
| Hitachi | 4         | 4      | 17.39%  |
| WDC     | 2         | 2      | 8.7%    |
| HGST    | 1         | 1      | 4.35%   |
| Fujitsu | 1         | 1      | 4.35%   |
| Apple   | 1         | 1      | 4.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 23        | 24     | 82.14%  |
| SSD  | 5         | 5      | 17.86%  |

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
| Works   | 86        | 104    | 74.78%  |
| Malfunc | 28        | 29     | 24.35%  |
| Failed  | 1         | 1      | 0.87%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 99        | 81.82%  |
| AMD                              | 9         | 7.44%   |
| SanDisk                          | 3         | 2.48%   |
| Samsung Electronics              | 3         | 2.48%   |
| Toshiba                          | 2         | 1.65%   |
| SK hynix                         | 1         | 0.83%   |
| Silicon Integrated Systems [SiS] | 1         | 0.83%   |
| Realtek Semiconductor            | 1         | 0.83%   |
| Micron/Crucial Technology        | 1         | 0.83%   |
| KIOXIA                           | 1         | 0.83%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 23        | 17.56%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 13        | 9.92%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 9         | 6.87%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 8         | 6.11%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 8         | 6.11%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 7         | 5.34%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 5         | 3.82%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 5         | 3.82%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 2.29%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 3         | 2.29%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 2.29%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 2.29%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 1.53%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 1.53%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.53%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 1.53%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 1.53%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 1.53%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 2         | 1.53%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 2         | 1.53%   |
| Unknown                                                                          | 2         | 1.53%   |
| Toshiba unknown                                                                  | 1         | 0.76%   |
| Toshiba BG3 NVMe SSD Controller                                                  | 1         | 0.76%   |
| SK hynix Gold P31 SSD                                                            | 1         | 0.76%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.76%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.76%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.76%   |
| Samsung SM951 AHCI                                                               | 1         | 0.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 0.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.76%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 1         | 0.76%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 1         | 0.76%   |
| Intel SSD 660P Series                                                            | 1         | 0.76%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 0.76%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 0.76%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 0.76%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 0.76%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 0.76%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 1         | 0.76%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 1         | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 96        | 76.19%  |
| NVMe | 13        | 10.32%  |
| IDE  | 10        | 7.94%   |
| RAID | 7         | 5.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 104       | 90.43%  |
| AMD    | 11        | 9.57%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel CPU Version                        | 6         | 5.22%   |
| Intel Core i5-3320M CPU @ 2.60GHz        | 5         | 4.35%   |
| Intel Core i5-3210M CPU @ 2.50GHz        | 4         | 3.48%   |
| Intel Core i7-8750H CPU @ 2.20GHz        | 3         | 2.61%   |
| Intel Core i5-6300U CPU @ 2.40GHz        | 3         | 2.61%   |
| Intel Core i5-6200U CPU @ 2.30GHz        | 3         | 2.61%   |
| Intel Core i5-4210U CPU @ 1.70GHz        | 3         | 2.61%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 2         | 1.74%   |
| Intel Core i7-4510U CPU @ 2.00GHz        | 2         | 1.74%   |
| Intel Core i7-3630QM CPU @ 2.40GHz       | 2         | 1.74%   |
| Intel Core i7 CPU M 620 @ 2.67GHz        | 2         | 1.74%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 2         | 1.74%   |
| Intel Core i5-3340M CPU @ 2.70GHz        | 2         | 1.74%   |
| Intel Core i5-3230M CPU @ 2.60GHz        | 2         | 1.74%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 2         | 1.74%   |
| Intel Core i3-6006U CPU @ 2.00GHz        | 2         | 1.74%   |
| Intel Core i3-5005U CPU @ 2.00GHz        | 2         | 1.74%   |
| Intel Core i3-2370M CPU @ 2.40GHz        | 2         | 1.74%   |
| Intel Core i3-2350M CPU @ 2.30GHz        | 2         | 1.74%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz     | 2         | 1.74%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz     | 2         | 1.74%   |
| Intel Core 2 Duo                         | 2         | 1.74%   |
| Intel Celeron CPU N3450 @ 1.10GHz        | 2         | 1.74%   |
| Intel Celeron CPU 1005M @ 1.90GHz        | 2         | 1.74%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz | 1         | 0.87%   |
| Intel Pentium CPU P6200 @ 2.13GHz        | 1         | 0.87%   |
| Intel Pentium CPU B940 @ 2.00GHz         | 1         | 0.87%   |
| Intel Genuine CPU                        | 1         | 0.87%   |
| Intel Core i7-8665U CPU @ 1.90GHz        | 1         | 0.87%   |
| Intel Core i7-8565U CPU @ 1.80GHz        | 1         | 0.87%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz       | 1         | 0.87%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz       | 1         | 0.87%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz       | 1         | 0.87%   |
| Intel Core i7-4600U CPU @ 2.10GHz        | 1         | 0.87%   |
| Intel Core i7-3632QM CPU @ 2.20GHz       | 1         | 0.87%   |
| Intel Core i7-2637M CPU                  | 1         | 0.87%   |
| Intel Core i7-10750H CPU @ 2.60GHz       | 1         | 0.87%   |
| Intel Core i7-10610U CPU @ 1.80GHz       | 1         | 0.87%   |
| Intel Core i7-10510U CPU @ 1.80GHz       | 1         | 0.87%   |
| Intel Core i5-8365U CPU @ 1.60GHz        | 1         | 0.87%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 39        | 33.91%  |
| Intel Core i7           | 22        | 19.13%  |
| Intel Core i3           | 15        | 13.04%  |
| Intel Celeron           | 9         | 7.83%   |
| Intel Core 2 Duo        | 8         | 6.96%   |
| Other                   | 6         | 5.22%   |
| Intel Pentium           | 2         | 1.74%   |
| AMD Ryzen 7             | 2         | 1.74%   |
| AMD A6                  | 2         | 1.74%   |
| Intel Pentium Silver    | 1         | 0.87%   |
| Intel Genuine           | 1         | 0.87%   |
| Intel Core 2 Solo       | 1         | 0.87%   |
| AMD Turion 64 X2 Mobile | 1         | 0.87%   |
| AMD Ryzen 3             | 1         | 0.87%   |
| AMD Phenom II           | 1         | 0.87%   |
| AMD G                   | 1         | 0.87%   |
| AMD E1                  | 1         | 0.87%   |
| AMD Athlon II           | 1         | 0.87%   |
| AMD A10                 | 1         | 0.87%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 81        | 70.43%  |
| 4       | 21        | 18.26%  |
| Unknown | 6         | 5.22%   |
| 6       | 4         | 3.48%   |
| 16      | 1         | 0.87%   |
| 8       | 1         | 0.87%   |
| 1       | 1         | 0.87%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 114       | 99.13%  |
| 2      | 1         | 0.87%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 74        | 64.35%  |
| 1       | 34        | 29.57%  |
| Unknown | 7         | 6.09%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| IvyBridge     | 20        | 17.39%  |
| KabyLake      | 16        | 13.91%  |
| SandyBridge   | 13        | 11.3%   |
| Skylake       | 11        | 9.57%   |
| Penryn        | 11        | 9.57%   |
| Haswell       | 10        | 8.7%    |
| Westmere      | 7         | 6.09%   |
| Broadwell     | 6         | 5.22%   |
| Core          | 4         | 3.48%   |
| Silvermont    | 2         | 1.74%   |
| K10           | 2         | 1.74%   |
| Jaguar        | 2         | 1.74%   |
| Goldmont      | 2         | 1.74%   |
| Zen+          | 1         | 0.87%   |
| Zen 3         | 1         | 0.87%   |
| Zen 2         | 1         | 0.87%   |
| Piledriver    | 1         | 0.87%   |
| K8 Hammer     | 1         | 0.87%   |
| Goldmont plus | 1         | 0.87%   |
| Excavator     | 1         | 0.87%   |
| CometLake     | 1         | 0.87%   |
| Bobcat        | 1         | 0.87%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 93        | 69.4%   |
| Nvidia                           | 21        | 15.67%  |
| AMD                              | 19        | 14.18%  |
| Silicon Integrated Systems [SiS] | 1         | 0.75%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 18        | 13.43%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 12        | 8.96%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 9         | 6.72%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 5.97%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 5.97%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 3.73%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 3.73%   |
| Intel HD Graphics 620                                                                    | 4         | 2.99%   |
| Intel HD Graphics 5500                                                                   | 4         | 2.99%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 2.24%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 2.24%   |
| Intel HD Graphics 530                                                                    | 3         | 2.24%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 2.24%   |
| Intel HD Graphics 500                                                                    | 2         | 1.49%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.49%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 2         | 1.49%   |
| AMD Chelsea LP [Radeon HD 7730M]                                                         | 2         | 1.49%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.75%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.75%   |
| Nvidia GT216M [NVS 5100M]                                                                | 1         | 0.75%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.75%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.75%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 0.75%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.75%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.75%   |
| Nvidia GK107M [GeForce GTX 660M]                                                         | 1         | 0.75%   |
| Nvidia GK106M [GeForce GTX 770M]                                                         | 1         | 0.75%   |
| Nvidia GF119M [GeForce 610M]                                                             | 1         | 0.75%   |
| Nvidia GF119M [GeForce 410M]                                                             | 1         | 0.75%   |
| Nvidia G98M [Quadro NVS 160M]                                                            | 1         | 0.75%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 0.75%   |
| Nvidia G86M [Quadro NVS 140M]                                                            | 1         | 0.75%   |
| Nvidia G84M [GeForce 8600M GT]                                                           | 1         | 0.75%   |
| Intel UHD Graphics 620                                                                   | 1         | 0.75%   |
| Intel HD Graphics 630                                                                    | 1         | 0.75%   |
| Intel HD Graphics 6000                                                                   | 1         | 0.75%   |
| Intel HD Graphics                                                                        | 1         | 0.75%   |
| Intel Haswell-ULT High Definition Audio Controller [HD Graphics]                         | 1         | 0.75%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 65        | 56.52%  |
| Intel + Nvidia | 14        | 12.17%  |
| 1 x AMD        | 14        | 12.17%  |
| 2 x Intel      | 9         | 7.83%   |
| 1 x Nvidia     | 7         | 6.09%   |
| Intel + AMD    | 5         | 4.35%   |
| 1 x SiS        | 1         | 0.87%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 94        | 81.74%  |
| Unknown     | 19        | 16.52%  |
| Proprietary | 2         | 1.74%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 103       | 89.57%  |
| 0.01-0.5   | 9         | 7.83%   |
| 0.51-1.0   | 2         | 1.74%   |
| 1.01-2.0   | 1         | 0.87%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 24        | 26.67%  |
| AU Optronics            | 19        | 21.11%  |
| Chimei Innolux          | 14        | 15.56%  |
| Samsung Electronics     | 9         | 10%     |
| Chi Mei Optoelectronics | 5         | 5.56%   |
| BOE                     | 5         | 5.56%   |
| InfoVision              | 3         | 3.33%   |
| LG Philips              | 2         | 2.22%   |
| Lenovo                  | 2         | 2.22%   |
| Apple                   | 2         | 2.22%   |
| AOC                     | 2         | 2.22%   |
| Sony                    | 1         | 1.11%   |
| Goldstar                | 1         | 1.11%   |
| Dell                    | 1         | 1.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch        | 3         | 3.33%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch | 2         | 2.22%   |
| LG Display LCD Monitor LGD0532 1920x1080 340x190mm 15.3-inch         | 2         | 2.22%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch          | 2         | 2.22%   |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch          | 2         | 2.22%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 310x170mm 13.9-inch     | 2         | 2.22%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 340x190mm 15.3-inch        | 2         | 2.22%   |
| Sony SDM-HS95P SNY2500 1280x1024 380x300mm 19.1-inch                 | 1         | 1.11%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 470x300mm 22.0-inch | 1         | 1.11%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 300x170mm 13.6-inch | 1         | 1.11%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 370x230mm 17.2-inch | 1         | 1.11%   |
| Samsung Electronics LCD Monitor SEC354C 1366x768 350x200mm 15.9-inch | 1         | 1.11%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 340x190mm 15.3-inch | 1         | 1.11%   |
| Samsung Electronics LCD Monitor SDC324D 1366x768 310x170mm 13.9-inch | 1         | 1.11%   |
| Samsung Electronics LCD Monitor SDC324A 1366x768 290x170mm 13.2-inch | 1         | 1.11%   |
| LG Philips LCD Monitor LPLE300 1280x800 330x210mm 15.4-inch          | 1         | 1.11%   |
| LG Philips LCD Monitor LPL3B01 1280x800 330x210mm 15.4-inch          | 1         | 1.11%   |
| LG Display LCD Monitor LGD11F9 1280x800 290x180mm 13.4-inch          | 1         | 1.11%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch         | 1         | 1.11%   |
| LG Display LCD Monitor LGD05B1 1920x1080 310x170mm 13.9-inch         | 1         | 1.11%   |
| LG Display LCD Monitor LGD0545 3200x1800 290x170mm 13.2-inch         | 1         | 1.11%   |
| LG Display LCD Monitor LGD053F 1920x1080 340x190mm 15.3-inch         | 1         | 1.11%   |
| LG Display LCD Monitor LGD0527 1366x768 310x170mm 13.9-inch          | 1         | 1.11%   |
| LG Display LCD Monitor LGD0525 1366x768 340x190mm 15.3-inch          | 1         | 1.11%   |
| LG Display LCD Monitor LGD045C 1366x768 350x190mm 15.7-inch          | 1         | 1.11%   |
| LG Display LCD Monitor LGD0459 1920x1080 380x210mm 17.1-inch         | 1         | 1.11%   |
| LG Display LCD Monitor LGD0446 1920x1080 310x170mm 13.9-inch         | 1         | 1.11%   |
| LG Display LCD Monitor LGD03A3 1366x768 280x160mm 12.7-inch          | 1         | 1.11%   |
| LG Display LCD Monitor LGD0372 1600x900 380x210mm 17.1-inch          | 1         | 1.11%   |
| LG Display LCD Monitor LGD0360 1600x900 290x170mm 13.2-inch          | 1         | 1.11%   |
| LG Display LCD Monitor LGD02E9 1366x768 310x170mm 13.9-inch          | 1         | 1.11%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x170mm 13.9-inch          | 1         | 1.11%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch          | 1         | 1.11%   |
| LG Display LCD Monitor LGD02DA 1920x1080 380x210mm 17.1-inch         | 1         | 1.11%   |
| LG Display LCD Monitor LGD02AD 1366x768 340x190mm 15.3-inch          | 1         | 1.11%   |
| LG Display LCD Monitor LGD029B 1366x768 310x170mm 13.9-inch          | 1         | 1.11%   |
| LG Display LCD Monitor LGD0230 1366x768 340x190mm 15.3-inch          | 1         | 1.11%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch              | 1         | 1.11%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x170mm 12.2-inch              | 1         | 1.11%   |
| InfoVision LCD Monitor IVO0579 1366x768 310x170mm 13.9-inch          | 1         | 1.11%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 47        | 52.81%  |
| 1920x1080 (FHD)    | 24        | 26.97%  |
| 1280x800 (WXGA)    | 7         | 7.87%   |
| 1600x900 (HD+)     | 5         | 5.62%   |
| 1440x900 (WXGA+)   | 2         | 2.25%   |
| 3840x2160 (4K)     | 1         | 1.12%   |
| 3200x1800 (QHD+)   | 1         | 1.12%   |
| 1680x1050 (WSXGA+) | 1         | 1.12%   |
| 1280x1024 (SXGA)   | 1         | 1.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 34        | 37.78%  |
| 13     | 29        | 32.22%  |
| 12     | 10        | 11.11%  |
| 17     | 7         | 7.78%   |
| 11     | 3         | 3.33%   |
| 21     | 2         | 2.22%   |
| 19     | 2         | 2.22%   |
| 27     | 1         | 1.11%   |
| 22     | 1         | 1.11%   |
| 14     | 1         | 1.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 55        | 61.11%  |
| 201-300     | 22        | 24.44%  |
| 351-400     | 8         | 8.89%   |
| 401-500     | 4         | 4.44%   |
| 601-700     | 1         | 1.11%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 75        | 86.21%  |
| 16/10 | 10        | 11.49%  |
| 5/4   | 1         | 1.15%   |
| 3/2   | 1         | 1.15%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 26        | 28.89%  |
| 91-100         | 26        | 28.89%  |
| 61-70          | 10        | 11.11%  |
| 101-110        | 8         | 8.89%   |
| 121-130        | 6         | 6.67%   |
| 71-80          | 4         | 4.44%   |
| 51-60          | 3         | 3.33%   |
| 201-250        | 3         | 3.33%   |
| 151-200        | 2         | 2.22%   |
| 301-350        | 1         | 1.11%   |
| 131-140        | 1         | 1.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 37        | 41.57%  |
| 101-120       | 37        | 41.57%  |
| 51-100        | 12        | 13.48%  |
| 161-240       | 2         | 2.25%   |
| More than 240 | 1         | 1.12%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 86        | 74.78%  |
| 0     | 24        | 20.87%  |
| 2     | 5         | 4.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 66        | 36.67%  |
| Realtek Semiconductor             | 49        | 27.22%  |
| Qualcomm Atheros                  | 32        | 17.78%  |
| Broadcom                          | 15        | 8.33%   |
| Ralink                            | 3         | 1.67%   |
| Marvell Technology Group          | 3         | 1.67%   |
| Ralink Technology                 | 2         | 1.11%   |
| TP-Link                           | 1         | 0.56%   |
| Toshiba                           | 1         | 0.56%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.56%   |
| Sierra Wireless                   | 1         | 0.56%   |
| Samsung Electronics               | 1         | 0.56%   |
| Huawei Technologies               | 1         | 0.56%   |
| Hewlett-Packard                   | 1         | 0.56%   |
| Ericsson Business Mobile Networks | 1         | 0.56%   |
| D-Link                            | 1         | 0.56%   |
| AboCom Systems                    | 1         | 0.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 28        | 12.28%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 17        | 7.46%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 9         | 3.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 3.51%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 3.07%   |
| Intel Wireless 8260                                                     | 6         | 2.63%   |
| Intel Wireless 7265                                                     | 6         | 2.63%   |
| Intel Wireless 7260                                                     | 6         | 2.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 2.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 2.19%   |
| Intel WiFi Link 5100                                                    | 5         | 2.19%   |
| Intel Wireless 8265 / 8275                                              | 4         | 1.75%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 1.75%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 1.32%   |
| Intel Ethernet Connection I219-LM                                       | 3         | 1.32%   |
| Intel Ethernet Connection I218-LM                                       | 3         | 1.32%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 1.32%   |
| Intel Centrino Wireless-N 2230                                          | 3         | 1.32%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 1.32%   |
| Intel 82577LM Gigabit Network Connection                                | 3         | 1.32%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 0.88%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 2         | 0.88%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 0.88%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 2         | 0.88%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.88%   |
| Intel Wireless 3165                                                     | 2         | 0.88%   |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 0.88%   |
| Intel Ethernet Connection (6) I219-LM                                   | 2         | 0.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 0.88%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 0.88%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 0.88%   |
| Intel 82567LM Gigabit Network Connection                                | 2         | 0.88%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                       | 2         | 0.88%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                       | 2         | 0.88%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 2         | 0.88%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 0.88%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 0.88%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 1         | 0.44%   |
| Toshiba Ericsson H5321gw for TOSHIBA Mobile Broadband Network Adapter   | 1         | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 62        | 50.82%  |
| Qualcomm Atheros      | 29        | 23.77%  |
| Realtek Semiconductor | 11        | 9.02%   |
| Broadcom              | 11        | 9.02%   |
| Ralink                | 3         | 2.46%   |
| Ralink Technology     | 2         | 1.64%   |
| TP-Link               | 1         | 0.82%   |
| Sierra Wireless       | 1         | 0.82%   |
| D-Link                | 1         | 0.82%   |
| AboCom Systems        | 1         | 0.82%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 6.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 5.74%   |
| Intel Wireless 8260                                                     | 6         | 4.92%   |
| Intel Wireless 7265                                                     | 6         | 4.92%   |
| Intel Wireless 7260                                                     | 6         | 4.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 4.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 4.1%    |
| Intel WiFi Link 5100                                                    | 5         | 4.1%    |
| Intel Wireless 8265 / 8275                                              | 4         | 3.28%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 3.28%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 2.46%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 2.46%   |
| Intel Centrino Wireless-N 2230                                          | 3         | 2.46%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 2.46%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 1.64%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 1.64%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 1.64%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.64%   |
| Intel Wireless 3165                                                     | 2         | 1.64%   |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 1.64%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.64%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 1.64%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 1.64%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 1.64%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 1.64%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 1         | 0.82%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                           | 1         | 0.82%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.82%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.82%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 1         | 0.82%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1         | 0.82%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.82%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.82%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.82%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.82%   |
| Ralink RT2501/RT2573 Wireless Adapter                                   | 1         | 0.82%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                               | 1         | 0.82%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.82%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.82%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 46        | 44.66%  |
| Intel                            | 33        | 32.04%  |
| Qualcomm Atheros                 | 9         | 8.74%   |
| Broadcom                         | 9         | 8.74%   |
| Marvell Technology Group         | 3         | 2.91%   |
| Silicon Integrated Systems [SiS] | 1         | 0.97%   |
| Samsung Electronics              | 1         | 0.97%   |
| Huawei Technologies              | 1         | 0.97%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 28        | 27.18%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 16.5%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 8.74%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 2.91%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 2.91%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 2.91%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 1.94%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 1.94%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 1.94%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 1.94%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 1.94%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 1.94%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 1.94%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.97%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.97%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.97%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.97%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.97%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.97%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.97%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.97%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.97%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.97%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 0.97%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.97%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.97%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.97%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 0.97%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.97%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.97%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.97%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 0.97%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.97%   |
| Intel 82567LF Gigabit Network Connection                          | 1         | 0.97%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 0.97%   |
| Huawei USB Composite Device                                       | 1         | 0.97%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 0.97%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 0.97%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.97%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 113       | 52.07%  |
| Ethernet | 101       | 46.54%  |
| Modem    | 3         | 1.38%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 99        | 49.75%  |
| WiFi     | 98        | 49.25%  |
| Modem    | 2         | 1.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 98        | 85.22%  |
| 1     | 17        | 14.78%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 107       | 92.24%  |
| Yes  | 9         | 7.76%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 36        | 48.65%  |
| Broadcom                        | 8         | 10.81%  |
| Qualcomm Atheros Communications | 6         | 8.11%   |
| Realtek Semiconductor           | 5         | 6.76%   |
| IMC Networks                    | 4         | 5.41%   |
| Apple                           | 4         | 5.41%   |
| Cambridge Silicon Radio         | 3         | 4.05%   |
| Ralink                          | 2         | 2.7%    |
| Lite-On Technology              | 2         | 2.7%    |
| Dell                            | 2         | 2.7%    |
| Hewlett-Packard                 | 1         | 1.35%   |
| Foxconn / Hon Hai               | 1         | 1.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 24        | 32.43%  |
| Intel Centrino Bluetooth Wireless Transceiver               | 4         | 5.41%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 4         | 5.41%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 4         | 5.41%   |
| Intel AX201 Bluetooth                                       | 3         | 4.05%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 3         | 4.05%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 3         | 4.05%   |
| Ralink RT3290 Bluetooth                                     | 2         | 2.7%    |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 2         | 2.7%    |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS                 | 2         | 2.7%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 2         | 2.7%    |
| Realtek RTL8821A Bluetooth                                  | 1         | 1.35%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 1.35%   |
| Realtek  Bluetooth 4.0 + High Speed Chip                    | 1         | 1.35%   |
| Realtek CSR Bluetooth Chip                                  | 1         | 1.35%   |
| Realtek Bluetooth Radio                                     | 1         | 1.35%   |
| Qualcomm Atheros  QCA9565 Bluetooth 4.0 + HS Adapter        | 1         | 1.35%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 1.35%   |
| Qualcomm Atheros Atheros AR9462 Bluetooth 3.0 + HS Adapter  | 1         | 1.35%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 1.35%   |
| Intel AX200 Bluetooth                                       | 1         | 1.35%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0                 | 1         | 1.35%   |
| IMC Networks Broadcom BCM20702 Bluetooth 4.0 +HS USB Device | 1         | 1.35%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 1.35%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 1.35%   |
| Dell DW375 Bluetooth Module                                 | 1         | 1.35%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 1         | 1.35%   |
| Broadcom BCM43142A0 Bluetooth 4.0                           | 1         | 1.35%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                        | 1         | 1.35%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 1         | 1.35%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 1         | 1.35%   |
| Apple Bluetooth Host Controller                             | 1         | 1.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 103       | 83.06%  |
| AMD                              | 15        | 12.1%   |
| Nvidia                           | 5         | 4.03%   |
| Silicon Integrated Systems [SiS] | 1         | 0.81%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 25        | 16.56%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 13        | 8.61%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 12        | 7.95%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 5.96%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 5.96%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 5.3%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 4.64%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 3.97%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 3.97%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 3.31%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 2.65%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 1.99%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.99%   |
| AMD FCH Azalia Controller                                                                         | 3         | 1.99%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 1.99%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 1.32%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.32%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 1.32%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.32%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.32%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 2         | 1.32%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1.32%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.32%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.66%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.66%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.66%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.66%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 0.66%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.66%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.66%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.66%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 0.66%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 0.66%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 0.66%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.66%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 0.66%   |
| AMD RV610 HDMI Audio [Radeon HD 2350 PRO / 2400 PRO/XT / HD 3410]                                 | 1         | 0.66%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 0.66%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 0.66%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 33        | 23.4%   |
| SK hynix            | 27        | 19.15%  |
| Micron Technology   | 16        | 11.35%  |
| Kingston            | 12        | 8.51%   |
| Elpida              | 10        | 7.09%   |
| Unknown             | 9         | 6.38%   |
| Smart               | 4         | 2.84%   |
| Ramaxel Technology  | 4         | 2.84%   |
| Crucial             | 4         | 2.84%   |
| Nanya Technology    | 3         | 2.13%   |
| Unknown             | 3         | 2.13%   |
| Teikon              | 2         | 1.42%   |
| High Bridge         | 2         | 1.42%   |
| Apacer              | 2         | 1.42%   |
| A-DATA Technology   | 2         | 1.42%   |
| Unknown (ABCD)      | 1         | 0.71%   |
| Transcend           | 1         | 0.71%   |
| Toshiba             | 1         | 0.71%   |
| Smart Brazil        | 1         | 0.71%   |
| SHARETRONIC         | 1         | 0.71%   |
| G.Skill             | 1         | 0.71%   |
| Corsair             | 1         | 0.71%   |
| Axiom               | 1         | 0.71%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 4         | 2.68%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s             | 3         | 2.01%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 3         | 2.01%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s             | 3         | 2.01%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s             | 3         | 2.01%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s             | 3         | 2.01%   |
| Unknown                                                           | 3         | 2.01%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                       | 2         | 1.34%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                      | 2         | 1.34%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.34%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s             | 2         | 1.34%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s             | 2         | 1.34%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s             | 2         | 1.34%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s            | 2         | 1.34%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s             | 2         | 1.34%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s             | 2         | 1.34%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                       | 1         | 0.67%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                       | 1         | 0.67%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                       | 1         | 0.67%   |
| Unknown RAM Module 4GB SODIMM DDR3                                | 1         | 0.67%   |
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                        | 1         | 0.67%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                        | 1         | 0.67%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                          | 1         | 0.67%   |
| Unknown RAM Module 2048MB SODIMM 667MT/s                          | 1         | 0.67%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 1         | 0.67%   |
| Transcend RAM JM1600KSH-8G 8192MB SODIMM DDR3 1333MT/s            | 1         | 0.67%   |
| Toshiba RAM 8HTF12864HDY-800G1 2048MB SODIMM 800MT/s              | 1         | 0.67%   |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 800MT/s               | 1         | 0.67%   |
| Teikon RAM TMT451S6BFR8A-PBSC 4096MB SODIMM DDR3 1600MT/s         | 1         | 0.67%   |
| Teikon RAM TML251S6EFR8A-PBHC 4096MB SODIMM DDR3 1600MT/s         | 1         | 0.67%   |
| Smart RAM SH564568FH8NWPHSFR 2GB SODIMM DDR3 1333MT/s             | 1         | 0.67%   |
| Smart RAM SH564128FJ8NZRNSDR 4GB SODIMM DDR3 1600MT/s             | 1         | 0.67%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2400MT/s      | 1         | 0.67%   |
| SK hynix RAM Module 2GB DDR3 1600MT/s                             | 1         | 0.67%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s             | 1         | 0.67%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 1         | 0.67%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 1         | 0.67%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1333MT/s            | 1         | 0.67%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s            | 1         | 0.67%   |
| SK hynix RAM HMT325S6CFR8C-H9 2048MB SODIMM DDR3 1333MT/s         | 1         | 0.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 69        | 61.06%  |
| DDR4    | 28        | 24.78%  |
| DDR2    | 7         | 6.19%   |
| Unknown | 5         | 4.42%   |
| LPDDR3  | 2         | 1.77%   |
| LPDDR4  | 1         | 0.88%   |
| DRAM    | 1         | 0.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 105       | 92.11%  |
| Row Of Chips | 4         | 3.51%   |
| DIMM         | 2         | 1.75%   |
| Chip         | 2         | 1.75%   |
| Unknown      | 1         | 0.88%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 55        | 42.97%  |
| 2048  | 39        | 30.47%  |
| 8192  | 26        | 20.31%  |
| 16384 | 7         | 5.47%   |
| 32768 | 1         | 0.78%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 42        | 33.07%  |
| 1333    | 20        | 15.75%  |
| 1334    | 12        | 9.45%   |
| 2667    | 10        | 7.87%   |
| 2400    | 10        | 7.87%   |
| 2133    | 7         | 5.51%   |
| 800     | 7         | 5.51%   |
| 3200    | 4         | 3.15%   |
| 1067    | 4         | 3.15%   |
| 1867    | 3         | 2.36%   |
| 667     | 3         | 2.36%   |
| Unknown | 2         | 1.57%   |
| 1866    | 1         | 0.79%   |
| 975     | 1         | 0.79%   |
| 333     | 1         | 0.79%   |

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
| Chicony Electronics                    | 22        | 26.19%  |
| Realtek Semiconductor                  | 10        | 11.9%   |
| Sunplus Innovation Technology          | 6         | 7.14%   |
| Microdia                               | 6         | 7.14%   |
| IMC Networks                           | 6         | 7.14%   |
| Acer                                   | 6         | 7.14%   |
| Suyin                                  | 5         | 5.95%   |
| Syntek                                 | 3         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.57%   |
| Silicon Motion                         | 2         | 2.38%   |
| Lite-On Technology                     | 2         | 2.38%   |
| Importek                               | 2         | 2.38%   |
| Apple                                  | 2         | 2.38%   |
| Alcor Micro                            | 2         | 2.38%   |
| Ricoh                                  | 1         | 1.19%   |
| Quanta                                 | 1         | 1.19%   |
| Luxvisions Innotech Limited            | 1         | 1.19%   |
| Logitech                               | 1         | 1.19%   |
| Lenovo                                 | 1         | 1.19%   |
| Holitech                               | 1         | 1.19%   |
| ALi                                    | 1         | 1.19%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 5         | 5.88%   |
| Realtek Integrated_Webcam_HD                        | 4         | 4.71%   |
| Realtek Realtek USB2.0 PC Camera                    | 3         | 3.53%   |
| Chicony Integrated Camera [ThinkPad]                | 3         | 3.53%   |
| Chicony HP HD Webcam [Fixed]                        | 3         | 3.53%   |
| Syntek Lenovo EasyCamera                            | 2         | 2.35%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 2.35%   |
| Sunplus Asus Webcam                                 | 2         | 2.35%   |
| Realtek Integrated Webcam                           | 2         | 2.35%   |
| Microdia Laptop_Integrated_Webcam_HD                | 2         | 2.35%   |
| Microdia Integrated Webcam                          | 2         | 2.35%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 2         | 2.35%   |
| IMC Networks Integrated Camera                      | 2         | 2.35%   |
| Chicony HP HD Camera                                | 2         | 2.35%   |
| Apple FaceTime HD Camera                            | 2         | 2.35%   |
| Acer Integrated Camera                              | 2         | 2.35%   |
| Syntek EasyCamera                                   | 1         | 1.18%   |
| Suyin USB 2.0 Camera                                | 1         | 1.18%   |
| Suyin Sony Visual Communication Camera              | 1         | 1.18%   |
| Suyin HP Webcam-101                                 | 1         | 1.18%   |
| Suyin HP Integrated Webcam                          | 1         | 1.18%   |
| Suyin Acer/Lenovo Webcam [CN0316]                   | 1         | 1.18%   |
| Sunplus Integrated Camera                           | 1         | 1.18%   |
| Sunplus Dell E5570 integrated webcam                | 1         | 1.18%   |
| Silicon Motion WebCam SCX Series                    | 1         | 1.18%   |
| Silicon Motion Realtek USB2.0 PC Camera             | 1         | 1.18%   |
| Ricoh Integrated Camera                             | 1         | 1.18%   |
| Realtek LG Camera                                   | 1         | 1.18%   |
| Quanta HP Webcam                                    | 1         | 1.18%   |
| Microdia Laptop_Integrated_Webcam_FHD               | 1         | 1.18%   |
| Microdia HP Webcam                                  | 1         | 1.18%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 1.18%   |
| Logitech Webcam C270                                | 1         | 1.18%   |
| Lite-On Integrated Camera                           | 1         | 1.18%   |
| Lite-On HP IR Camera                                | 1         | 1.18%   |
| Lenovo Integrated Webcam [R5U877]                   | 1         | 1.18%   |
| Importek TOSHIBA Web Camera - HD                    | 1         | 1.18%   |
| Importek TOSHIBA Web Camera                         | 1         | 1.18%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 1.18%   |
| IMC Networks EasyCamera                             | 1         | 1.18%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Validity Sensors   | 9         | 69.23%  |
| Synaptics          | 1         | 7.69%   |
| STMicroelectronics | 1         | 7.69%   |
| Broadcom           | 1         | 7.69%   |
| AuthenTec          | 1         | 7.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                                  | 3         | 23.08%  |
| Validity Sensors VFS495 Fingerprint Reader                                   | 3         | 23.08%  |
| Validity Sensors VFS451 Fingerprint Reader                                   | 1         | 7.69%   |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 1         | 7.69%   |
| Validity Sensors Synaptics WBDI                                              | 1         | 7.69%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 1         | 7.69%   |
| STMicroelectronics Fingerprint Reader                                        | 1         | 7.69%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 7.69%   |
| AuthenTec AES2810                                                            | 1         | 7.69%   |

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
| 2     | 41        | 35.04%  |
| 1     | 35        | 29.91%  |
| 3     | 22        | 18.8%   |
| 0     | 11        | 9.4%    |
| 4     | 6         | 5.13%   |
| 6     | 1         | 0.85%   |
| 5     | 1         | 0.85%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 88        | 42.93%  |
| Card reader              | 52        | 25.37%  |
| Net/wireless             | 19        | 9.27%   |
| Bluetooth                | 19        | 9.27%   |
| Fingerprint reader       | 13        | 6.34%   |
| Firewire controller      | 8         | 3.9%    |
| Storage                  | 3         | 1.46%   |
| Sound                    | 2         | 0.98%   |
| Dvb card                 | 1         | 0.49%   |

