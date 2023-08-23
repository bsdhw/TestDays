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

Total: 138

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [2294352c5a](https://bsd-hardware.info/?probe=2294352c5a) | Nov 08, 2022 |
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
| amd64 | 116       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 115       | 99.14%  |
| KDE5         | 1         | 0.86%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 116       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SLiM | 116       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 116       | 100%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 93        | 80.17%  |
| BIOS | 23        | 19.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Zfs  | 116       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 116       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 32        | 27.59%  |
| Hewlett-Packard     | 20        | 17.24%  |
| Dell                | 19        | 16.38%  |
| ASUSTek Computer    | 11        | 9.48%   |
| Toshiba             | 8         | 6.9%    |
| Apple               | 5         | 4.31%   |
| Acer                | 3         | 2.59%   |
| Samsung Electronics | 2         | 1.72%   |
| Packard Bell        | 2         | 1.72%   |
| Gateway             | 2         | 1.72%   |
| WYSE                | 1         | 0.86%   |
| TUXEDO              | 1         | 0.86%   |
| Sony                | 1         | 0.86%   |
| NEC Computers       | 1         | 0.86%   |
| MSI                 | 1         | 0.86%   |
| MouseComputer       | 1         | 0.86%   |
| LG Electronics      | 1         | 0.86%   |
| Hampoo              | 1         | 0.86%   |
| Fujitsu Siemens     | 1         | 0.86%   |
| Fujitsu             | 1         | 0.86%   |
| eMachines           | 1         | 0.86%   |
| Alienware           | 1         | 0.86%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Dell Inspiron 15-3567                       | 3         | 2.59%   |
| HP EliteBook 840 G3                         | 2         | 1.72%   |
| Gateway NE56R                               | 2         | 1.72%   |
| Dell Inspiron 7520                          | 2         | 1.72%   |
| Apple MacBookPro9,2                         | 2         | 1.72%   |
| WYSE Z CLASS                                | 1         | 0.86%   |
| TUXEDO Aura 15 Gen1                         | 1         | 0.86%   |
| Toshiba Satellite Pro U400                  | 1         | 0.86%   |
| Toshiba Satellite P300                      | 1         | 0.86%   |
| Toshiba Satellite L855                      | 1         | 0.86%   |
| Toshiba Satellite L500                      | 1         | 0.86%   |
| Toshiba Satellite C640                      | 1         | 0.86%   |
| Toshiba PORTEGE Z10t-A                      | 1         | 0.86%   |
| Toshiba PORTEGE R930                        | 1         | 0.86%   |
| Toshiba dynabook Satellite B453/L           | 1         | 0.86%   |
| Sony VPCEJ1E1E                              | 1         | 0.86%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 1         | 0.86%   |
| Samsung 530U3C/530U4C/532U3C                | 1         | 0.86%   |
| Packard Bell EasyNote_MX61-B-038            | 1         | 0.86%   |
| Packard Bell EasyNote MH36                  | 1         | 0.86%   |
| NEC Computers PC-VK17HBBCD                  | 1         | 0.86%   |
| MSI GF65 Thin 10SDR                         | 1         | 0.86%   |
| MouseComputer W331AU                        | 1         | 0.86%   |
| LG 14Z980-G.BH51P1                          | 1         | 0.86%   |
| Lenovo ZIUS6                                | 1         | 0.86%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS          | 1         | 0.86%   |
| Lenovo ThinkPad X260 20F5S82N00             | 1         | 0.86%   |
| Lenovo ThinkPad X250 20CLS4JH00             | 1         | 0.86%   |
| Lenovo ThinkPad X240 20AMS39F0K             | 1         | 0.86%   |
| Lenovo ThinkPad X230 Tablet 343522U         | 1         | 0.86%   |
| Lenovo ThinkPad X230 2330A48                | 1         | 0.86%   |
| Lenovo ThinkPad X230 2325WWB                | 1         | 0.86%   |
| Lenovo ThinkPad X230 2325O76                | 1         | 0.86%   |
| Lenovo ThinkPad X230 23255Y4                | 1         | 0.86%   |
| Lenovo ThinkPad X230 23254G7                | 1         | 0.86%   |
| Lenovo ThinkPad X200 7458VP4                | 1         | 0.86%   |
| Lenovo ThinkPad T61 64607EU                 | 1         | 0.86%   |
| Lenovo ThinkPad T490s 20NYS3TU00            | 1         | 0.86%   |
| Lenovo ThinkPad T490 20RYS06R00             | 1         | 0.86%   |
| Lenovo ThinkPad T470p 20J6A012CD            | 1         | 0.86%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 22        | 18.97%  |
| Dell Latitude              | 8         | 6.9%    |
| HP Pavilion                | 6         | 5.17%   |
| Dell Inspiron              | 6         | 5.17%   |
| Toshiba Satellite          | 5         | 4.31%   |
| HP ProBook                 | 3         | 2.59%   |
| HP EliteBook               | 3         | 2.59%   |
| Acer Aspire                | 3         | 2.59%   |
| Toshiba PORTEGE            | 2         | 1.72%   |
| Packard Bell EasyNote      | 2         | 1.72%   |
| Lenovo IdeaPad             | 2         | 1.72%   |
| Gateway NE56R              | 2         | 1.72%   |
| Dell Vostro                | 2         | 1.72%   |
| ASUS VivoBook              | 2         | 1.72%   |
| Apple MacBookPro9          | 2         | 1.72%   |
| WYSE Z                     | 1         | 0.86%   |
| TUXEDO Aura                | 1         | 0.86%   |
| Toshiba dynabook           | 1         | 0.86%   |
| Sony VPCEJ1E1E             | 1         | 0.86%   |
| Samsung RV411              | 1         | 0.86%   |
| Samsung 530U3C             | 1         | 0.86%   |
| NEC Computers PC-VK17HBBCD | 1         | 0.86%   |
| MSI GF65                   | 1         | 0.86%   |
| MouseComputer W331AU       | 1         | 0.86%   |
| LG 14Z980-G.BH51P1         | 1         | 0.86%   |
| Lenovo ZIUS6               | 1         | 0.86%   |
| Lenovo Yoga                | 1         | 0.86%   |
| Lenovo Legion              | 1         | 0.86%   |
| Lenovo G550                | 1         | 0.86%   |
| Lenovo G500s               | 1         | 0.86%   |
| Lenovo G500                | 1         | 0.86%   |
| Lenovo G470                | 1         | 0.86%   |
| Lenovo B41-80              | 1         | 0.86%   |
| HP Stream                  | 1         | 0.86%   |
| HP OMEN                    | 1         | 0.86%   |
| HP Laptop                  | 1         | 0.86%   |
| HP G42                     | 1         | 0.86%   |
| HP 625                     | 1         | 0.86%   |
| HP 255                     | 1         | 0.86%   |
| HP 250                     | 1         | 0.86%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2013 | 15        | 12.93%  |
| 2020 | 13        | 11.21%  |
| 2019 | 13        | 11.21%  |
| 2012 | 11        | 9.48%   |
| 2009 | 10        | 8.62%   |
| 2015 | 9         | 7.76%   |
| 2011 | 9         | 7.76%   |
| 2018 | 8         | 6.9%    |
| 2014 | 8         | 6.9%    |
| 2016 | 7         | 6.03%   |
| 2021 | 3         | 2.59%   |
| 2010 | 3         | 2.59%   |
| 2007 | 3         | 2.59%   |
| 2017 | 2         | 1.72%   |
| 2008 | 2         | 1.72%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 116       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 115       | 99.14%  |
| Yes  | 1         | 0.86%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 50        | 43.1%   |
| 8.01-16.0  | 44        | 37.93%  |
| 16.01-24.0 | 15        | 12.93%  |
| 32.01-64.0 | 3         | 2.59%   |
| 24.01-32.0 | 2         | 1.72%   |
| 3.01-4.0   | 1         | 0.86%   |
| 2.01-3.0   | 1         | 0.86%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 79        | 68.1%   |
| 0.51-1.0  | 30        | 25.86%  |
| 2.01-3.0  | 3         | 2.59%   |
| 1.01-2.0  | 3         | 2.59%   |
| 8.01-16.0 | 1         | 0.86%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 93        | 79.49%  |
| 2      | 15        | 12.82%  |
| 0      | 7         | 5.98%   |
| 3      | 2         | 1.71%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 59        | 50.86%  |
| No        | 57        | 49.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 102       | 87.93%  |
| No        | 14        | 12.07%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 114       | 98.28%  |
| No        | 2         | 1.72%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 63.79%  |
| No        | 42        | 36.21%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| USA                | 20        | 17.09%  |
| Germany            | 12        | 10.26%  |
| Brazil             | 9         | 7.69%   |
| Netherlands        | 6         | 5.13%   |
| Italy              | 5         | 4.27%   |
| China              | 5         | 4.27%   |
| UK                 | 4         | 3.42%   |
| Sweden             | 4         | 3.42%   |
| Spain              | 4         | 3.42%   |
| Switzerland        | 3         | 2.56%   |
| Poland             | 3         | 2.56%   |
| Indonesia          | 3         | 2.56%   |
| India              | 3         | 2.56%   |
| Ukraine            | 2         | 1.71%   |
| Portugal           | 2         | 1.71%   |
| Mexico             | 2         | 1.71%   |
| Lithuania          | 2         | 1.71%   |
| Japan              | 2         | 1.71%   |
| Canada             | 2         | 1.71%   |
| South Africa       | 1         | 0.85%   |
| Slovakia           | 1         | 0.85%   |
| Puerto Rico        | 1         | 0.85%   |
| Oman               | 1         | 0.85%   |
| New Zealand        | 1         | 0.85%   |
| Morocco            | 1         | 0.85%   |
| Montenegro         | 1         | 0.85%   |
| Malta              | 1         | 0.85%   |
| Malaysia           | 1         | 0.85%   |
| Latvia             | 1         | 0.85%   |
| Hungary            | 1         | 0.85%   |
| Greece             | 1         | 0.85%   |
| France             | 1         | 0.85%   |
| Finland            | 1         | 0.85%   |
| Dominican Republic | 1         | 0.85%   |
| Cyprus             | 1         | 0.85%   |
| Croatia            | 1         | 0.85%   |
| Chile              | 1         | 0.85%   |
| Bulgaria           | 1         | 0.85%   |
| Belgium            | 1         | 0.85%   |
| Belarus            | 1         | 0.85%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Zurich             | 2         | 1.68%   |
| Wroclaw            | 2         | 1.68%   |
| Surabaya           | 2         | 1.68%   |
| Berlin             | 2         | 1.68%   |
| Zhengzhou          | 1         | 0.84%   |
| Zagreb             | 1         | 0.84%   |
| Wuhan              | 1         | 0.84%   |
| Washington         | 1         | 0.84%   |
| Warmond            | 1         | 0.84%   |
| Wandur             | 1         | 0.84%   |
| Vilnius            | 1         | 0.84%   |
| Vigonovo           | 1         | 0.84%   |
| Vienna             | 1         | 0.84%   |
| VÃ¤sterÃ¥s     | 1         | 0.84%   |
| Vancouver          | 1         | 0.84%   |
| Utrecht            | 1         | 0.84%   |
| Tula de Allende    | 1         | 0.84%   |
| Traverse City      | 1         | 0.84%   |
| The Bronx          | 1         | 0.84%   |
| Temuco             | 1         | 0.84%   |
| Tangara            | 1         | 0.84%   |
| Sungai Buloh       | 1         | 0.84%   |
| Solarino           | 1         | 0.84%   |
| Sofia              | 1         | 0.84%   |
| Shibakoen          | 1         | 0.84%   |
| Shasta             | 1         | 0.84%   |
| SÃ£o Paulo       | 1         | 0.84%   |
| Santo Domingo Este | 1         | 0.84%   |
| Sankt Augustin     | 1         | 0.84%   |
| Roosendaal         | 1         | 0.84%   |
| Riga               | 1         | 0.84%   |
| Redondela          | 1         | 0.84%   |
| Pleidelsheim       | 1         | 0.84%   |
| Plav               | 1         | 0.84%   |
| Plattsburgh        | 1         | 0.84%   |
| Perwez             | 1         | 0.84%   |
| Padova             | 1         | 0.84%   |
| Osasco             | 1         | 0.84%   |
| Oosterhout         | 1         | 0.84%   |
| Oklahoma City      | 1         | 0.84%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 18        | 18     | 14.52%  |
| Seagate             | 18        | 19     | 14.52%  |
| Samsung Electronics | 16        | 21     | 12.9%   |
| Toshiba             | 12        | 12     | 9.68%   |
| Crucial             | 11        | 11     | 8.87%   |
| SanDisk             | 6         | 6      | 4.84%   |
| Intel               | 6         | 6      | 4.84%   |
| Hitachi             | 6         | 7      | 4.84%   |
| Kingston            | 5         | 6      | 4.03%   |
| A-DATA Technology   | 4         | 5      | 3.23%   |
| SPCC                | 2         | 2      | 1.61%   |
| OCZ                 | 2         | 2      | 1.61%   |
| HGST                | 2         | 2      | 1.61%   |
| Apple               | 2         | 2      | 1.61%   |
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
| Seagate ST1000LM035-1RK172 1TB       | 3         | 2.36%   |
| Seagate ST9500325AS 500GB            | 2         | 1.57%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 2         | 1.57%   |
| Samsung SSD 850 EVO 250GB            | 2         | 1.57%   |
| Kingston SA400S37120G 120GB          | 2         | 1.57%   |
| Crucial CT1000MX500SSD1 1TB          | 2         | 1.57%   |
| A-DATA SU650 120GB                   | 2         | 1.57%   |
| WDC WDS500G2B0A-00SM50 500GB         | 1         | 0.79%   |
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
| Samsung Electronics | 12        | 15     | 19.05%  |
| Crucial             | 10        | 10     | 15.87%  |
| SanDisk             | 6         | 6      | 9.52%   |
| Kingston            | 5         | 6      | 7.94%   |
| WDC                 | 4         | 4      | 6.35%   |
| Intel               | 4         | 4      | 6.35%   |
| A-DATA Technology   | 3         | 4      | 4.76%   |
| Toshiba             | 2         | 2      | 3.17%   |
| SPCC                | 2         | 2      | 3.17%   |
| OCZ                 | 2         | 2      | 3.17%   |
| Transcend           | 1         | 2      | 1.59%   |
| SSSTC               | 1         | 1      | 1.59%   |
| Smart               | 1         | 1      | 1.59%   |
| PNY                 | 1         | 1      | 1.59%   |
| Patriot             | 1         | 1      | 1.59%   |
| MyDigitalSSD        | 1         | 1      | 1.59%   |
| Micron Technology   | 1         | 1      | 1.59%   |
| LITEONIT            | 1         | 1      | 1.59%   |
| LITEON              | 1         | 1      | 1.59%   |
| KingSpec            | 1         | 1      | 1.59%   |
| HPE                 | 1         | 1      | 1.59%   |
| Hewlett-Packard     | 1         | 2      | 1.59%   |
| Apple               | 1         | 1      | 1.59%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 58        | 70     | 48.33%  |
| HDD  | 49        | 51     | 40.83%  |
| NVMe | 13        | 14     | 10.83%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 100       | 121    | 88.5%   |
| NVMe | 13        | 14     | 11.5%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 82        | 96     | 78.85%  |
| 0.51-1.0   | 20        | 23     | 19.23%  |
| 1.01-2.0   | 2         | 2      | 1.92%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 67        | 57.76%  |
| 101-250    | 19        | 16.38%  |
| 251-500    | 17        | 14.66%  |
| 501-1000   | 6         | 5.17%   |
| 51-100     | 4         | 3.45%   |
| 21-50      | 2         | 1.72%   |
| 1001-2000  | 1         | 0.86%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 116       | 100%    |

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
| Works   | 87        | 105    | 75%     |
| Malfunc | 28        | 29     | 24.14%  |
| Failed  | 1         | 1      | 0.86%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 100       | 81.97%  |
| AMD                              | 9         | 7.38%   |
| SanDisk                          | 3         | 2.46%   |
| Samsung Electronics              | 3         | 2.46%   |
| Toshiba                          | 2         | 1.64%   |
| SK hynix                         | 1         | 0.82%   |
| Silicon Integrated Systems [SiS] | 1         | 0.82%   |
| Realtek Semiconductor            | 1         | 0.82%   |
| Micron/Crucial Technology        | 1         | 0.82%   |
| KIOXIA                           | 1         | 0.82%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 23        | 17.42%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 13        | 9.85%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 9         | 6.82%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 8         | 6.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 8         | 6.06%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 7         | 5.3%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 5         | 3.79%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 5         | 3.79%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 3.03%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 2.27%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 2.27%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 2.27%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 1.52%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 1.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.52%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 1.52%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 1.52%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 1.52%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 2         | 1.52%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 2         | 1.52%   |
| Toshiba XG5 NVMe SSD Controller                                                  | 1         | 0.76%   |
| Toshiba BG3 NVMe SSD Controller                                                  | 1         | 0.76%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 1         | 0.76%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.76%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.76%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.76%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                       | 1         | 0.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 0.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.76%   |
| Realtek RTS5763DL x2 NVMe SSD Controller                                         | 1         | 0.76%   |
| Micron/Crucial P5 NVMe PCIe SSD[SlashP5]                                         | 1         | 0.76%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 1         | 0.76%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                 | 1         | 0.76%   |
| Intel SSD 660P Series                                                            | 1         | 0.76%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 0.76%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 0.76%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 0.76%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 0.76%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 0.76%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 1         | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 97        | 76.38%  |
| NVMe | 13        | 10.24%  |
| IDE  | 10        | 7.87%   |
| RAID | 7         | 5.51%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 105       | 90.52%  |
| AMD    | 11        | 9.48%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel CPU Version                        | 6         | 5.17%   |
| Intel Core i5-3320M CPU @ 2.60GHz        | 5         | 4.31%   |
| Intel Core i5-3210M CPU @ 2.50GHz        | 4         | 3.45%   |
| Intel Core i7-8750H CPU @ 2.20GHz        | 3         | 2.59%   |
| Intel Core i5-6300U CPU @ 2.40GHz        | 3         | 2.59%   |
| Intel Core i5-6200U CPU @ 2.30GHz        | 3         | 2.59%   |
| Intel Core i5-4210U CPU @ 1.70GHz        | 3         | 2.59%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 2         | 1.72%   |
| Intel Core i7-4510U CPU @ 2.00GHz        | 2         | 1.72%   |
| Intel Core i7-3630QM CPU @ 2.40GHz       | 2         | 1.72%   |
| Intel Core i7 CPU M 620 @ 2.67GHz        | 2         | 1.72%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 2         | 1.72%   |
| Intel Core i5-3340M CPU @ 2.70GHz        | 2         | 1.72%   |
| Intel Core i5-3230M CPU @ 2.60GHz        | 2         | 1.72%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 2         | 1.72%   |
| Intel Core i3-6006U CPU @ 2.00GHz        | 2         | 1.72%   |
| Intel Core i3-5005U CPU @ 2.00GHz        | 2         | 1.72%   |
| Intel Core i3-2370M CPU @ 2.40GHz        | 2         | 1.72%   |
| Intel Core i3-2350M CPU @ 2.30GHz        | 2         | 1.72%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz     | 2         | 1.72%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz     | 2         | 1.72%   |
| Intel Core 2 Duo                         | 2         | 1.72%   |
| Intel Celeron CPU N3450 @ 1.10GHz        | 2         | 1.72%   |
| Intel Celeron CPU 1005M @ 1.90GHz        | 2         | 1.72%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz | 1         | 0.86%   |
| Intel Pentium CPU P6200 @ 2.13GHz        | 1         | 0.86%   |
| Intel Pentium CPU B940 @ 2.00GHz         | 1         | 0.86%   |
| Intel Genuine CPU                        | 1         | 0.86%   |
| Intel Core i7-8665U CPU @ 1.90GHz        | 1         | 0.86%   |
| Intel Core i7-8565U CPU @ 1.80GHz        | 1         | 0.86%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz       | 1         | 0.86%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz       | 1         | 0.86%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz       | 1         | 0.86%   |
| Intel Core i7-4600U CPU @ 2.10GHz        | 1         | 0.86%   |
| Intel Core i7-3632QM CPU @ 2.20GHz       | 1         | 0.86%   |
| Intel Core i7-2637M CPU                  | 1         | 0.86%   |
| Intel Core i7-10750H CPU @ 2.60GHz       | 1         | 0.86%   |
| Intel Core i7-10610U CPU @ 1.80GHz       | 1         | 0.86%   |
| Intel Core i7-10510U CPU @ 1.80GHz       | 1         | 0.86%   |
| Intel Core i5-8365U CPU @ 1.60GHz        | 1         | 0.86%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 40        | 34.48%  |
| Intel Core i7           | 22        | 18.97%  |
| Intel Core i3           | 15        | 12.93%  |
| Intel Celeron           | 9         | 7.76%   |
| Intel Core 2 Duo        | 8         | 6.9%    |
| Other                   | 6         | 5.17%   |
| Intel Pentium           | 2         | 1.72%   |
| AMD Ryzen 7             | 2         | 1.72%   |
| AMD A6                  | 2         | 1.72%   |
| Intel Pentium Silver    | 1         | 0.86%   |
| Intel Genuine           | 1         | 0.86%   |
| Intel Core 2 Solo       | 1         | 0.86%   |
| AMD Turion 64 X2 Mobile | 1         | 0.86%   |
| AMD Ryzen 3             | 1         | 0.86%   |
| AMD Phenom II           | 1         | 0.86%   |
| AMD G                   | 1         | 0.86%   |
| AMD E1                  | 1         | 0.86%   |
| AMD Athlon II           | 1         | 0.86%   |
| AMD A10                 | 1         | 0.86%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 81        | 69.83%  |
| 4       | 22        | 18.97%  |
| Unknown | 6         | 5.17%   |
| 6       | 4         | 3.45%   |
| 16      | 1         | 0.86%   |
| 8       | 1         | 0.86%   |
| 1       | 1         | 0.86%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 115       | 99.14%  |
| 2      | 1         | 0.86%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 75        | 64.66%  |
| 1       | 34        | 29.31%  |
| Unknown | 7         | 6.03%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| IvyBridge     | 20        | 17.24%  |
| KabyLake      | 17        | 14.66%  |
| SandyBridge   | 13        | 11.21%  |
| Skylake       | 11        | 9.48%   |
| Penryn        | 11        | 9.48%   |
| Haswell       | 10        | 8.62%   |
| Westmere      | 7         | 6.03%   |
| Broadwell     | 6         | 5.17%   |
| Core          | 4         | 3.45%   |
| Silvermont    | 2         | 1.72%   |
| K10           | 2         | 1.72%   |
| Jaguar        | 2         | 1.72%   |
| Goldmont      | 2         | 1.72%   |
| Zen+          | 1         | 0.86%   |
| Zen 3         | 1         | 0.86%   |
| Zen 2         | 1         | 0.86%   |
| Piledriver    | 1         | 0.86%   |
| K8 Hammer     | 1         | 0.86%   |
| Goldmont plus | 1         | 0.86%   |
| Excavator     | 1         | 0.86%   |
| CometLake     | 1         | 0.86%   |
| Bobcat        | 1         | 0.86%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 94        | 69.12%  |
| Nvidia                           | 22        | 16.18%  |
| AMD                              | 19        | 13.97%  |
| Silicon Integrated Systems [SiS] | 1         | 0.74%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 18        | 13.24%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 12        | 8.82%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 9         | 6.62%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 5.88%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 5.88%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 3.68%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 3.68%   |
| Intel HD Graphics 620                                                                    | 4         | 2.94%   |
| Intel HD Graphics 5500                                                                   | 4         | 2.94%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 2.94%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 2.21%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 2.21%   |
| Intel HD Graphics 530                                                                    | 3         | 2.21%   |
| Intel HD Graphics 500                                                                    | 2         | 1.47%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.47%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.47%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 2         | 1.47%   |
| AMD Chelsea LP [Radeon HD 7730M]                                                         | 2         | 1.47%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.74%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.74%   |
| Nvidia GT216M [NVS 5100M]                                                                | 1         | 0.74%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.74%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.74%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.74%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 0.74%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.74%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.74%   |
| Nvidia GK107M [GeForce GTX 660M]                                                         | 1         | 0.74%   |
| Nvidia GK106M [GeForce GTX 770M]                                                         | 1         | 0.74%   |
| Nvidia GF119M [GeForce 610M]                                                             | 1         | 0.74%   |
| Nvidia GF119M [GeForce 410M]                                                             | 1         | 0.74%   |
| Nvidia G98M [Quadro NVS 160M]                                                            | 1         | 0.74%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 0.74%   |
| Nvidia G86M [Quadro NVS 140M]                                                            | 1         | 0.74%   |
| Nvidia G84M [GeForce 8600M GT]                                                           | 1         | 0.74%   |
| Intel UHD Graphics 620                                                                   | 1         | 0.74%   |
| Intel HD Graphics 630                                                                    | 1         | 0.74%   |
| Intel HD Graphics 6000                                                                   | 1         | 0.74%   |
| Intel HD Graphics                                                                        | 1         | 0.74%   |
| Intel Haswell-ULT Integrated Graphics Controller [HD Graphics]                           | 1         | 0.74%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 65        | 56.03%  |
| Intel + Nvidia | 15        | 12.93%  |
| 1 x AMD        | 14        | 12.07%  |
| 2 x Intel      | 9         | 7.76%   |
| 1 x Nvidia     | 7         | 6.03%   |
| Intel + AMD    | 5         | 4.31%   |
| 1 x SiS        | 1         | 0.86%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 95        | 81.9%   |
| Unknown     | 19        | 16.38%  |
| Proprietary | 2         | 1.72%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 104       | 89.66%  |
| 0.01-0.5   | 9         | 7.76%   |
| 0.51-1.0   | 2         | 1.72%   |
| 1.01-2.0   | 1         | 0.86%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 24        | 26.09%  |
| AU Optronics            | 19        | 20.65%  |
| Chimei Innolux          | 14        | 15.22%  |
| Samsung Electronics     | 9         | 9.78%   |
| Chi Mei Optoelectronics | 5         | 5.43%   |
| BOE                     | 5         | 5.43%   |
| InfoVision              | 3         | 3.26%   |
| LG Philips              | 2         | 2.17%   |
| Lenovo                  | 2         | 2.17%   |
| Apple                   | 2         | 2.17%   |
| AOC                     | 2         | 2.17%   |
| Sony                    | 1         | 1.09%   |
| PANDA                   | 1         | 1.09%   |
| Goldstar                | 1         | 1.09%   |
| Dell                    | 1         | 1.09%   |
| Ancor Communications    | 1         | 1.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch        | 3         | 3.26%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch | 2         | 2.17%   |
| LG Display LCD Monitor LGD0532 1920x1080 340x190mm 15.3-inch         | 2         | 2.17%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch          | 2         | 2.17%   |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch          | 2         | 2.17%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 310x170mm 13.9-inch     | 2         | 2.17%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 340x190mm 15.3-inch        | 2         | 2.17%   |
| Sony SDM-HS95P SNY2500 1280x1024 380x300mm 19.1-inch                 | 1         | 1.09%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 470x300mm 22.0-inch | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 370x230mm 17.2-inch | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC354C 1366x768 350x200mm 15.9-inch | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 340x190mm 15.3-inch | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SDC324D 1366x768 310x170mm 13.9-inch | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SDC324A 1366x768 290x170mm 13.2-inch | 1         | 1.09%   |
| PANDA LCD Monitor NCP0029 1920x1080 340x190mm 15.3-inch              | 1         | 1.09%   |
| LG Philips LCD Monitor LPLE300 1280x800 330x210mm 15.4-inch          | 1         | 1.09%   |
| LG Philips LCD Monitor LPL3B01 1280x800 330x210mm 15.4-inch          | 1         | 1.09%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 340x190mm 15.3-inch        | 1         | 1.09%   |
| LG Display LCD Monitor LGD11F9 1280x800 290x180mm 13.4-inch          | 1         | 1.09%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch         | 1         | 1.09%   |
| LG Display LCD Monitor LGD05B1 1920x1080 310x170mm 13.9-inch         | 1         | 1.09%   |
| LG Display LCD Monitor LGD0545 3200x1800 290x170mm 13.2-inch         | 1         | 1.09%   |
| LG Display LCD Monitor LGD053F 1920x1080 340x190mm 15.3-inch         | 1         | 1.09%   |
| LG Display LCD Monitor LGD0527 1366x768 310x170mm 13.9-inch          | 1         | 1.09%   |
| LG Display LCD Monitor LGD0525 1366x768 340x190mm 15.3-inch          | 1         | 1.09%   |
| LG Display LCD Monitor LGD045C 1366x768 350x190mm 15.7-inch          | 1         | 1.09%   |
| LG Display LCD Monitor LGD0459 1920x1080 380x210mm 17.1-inch         | 1         | 1.09%   |
| LG Display LCD Monitor LGD0446 1920x1080 310x170mm 13.9-inch         | 1         | 1.09%   |
| LG Display LCD Monitor LGD03A3 1366x768 280x160mm 12.7-inch          | 1         | 1.09%   |
| LG Display LCD Monitor LGD0372 1600x900 380x210mm 17.1-inch          | 1         | 1.09%   |
| LG Display LCD Monitor LGD0360 1600x900 290x170mm 13.2-inch          | 1         | 1.09%   |
| LG Display LCD Monitor LGD02E9 1366x768 310x170mm 13.9-inch          | 1         | 1.09%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x170mm 13.9-inch          | 1         | 1.09%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch          | 1         | 1.09%   |
| LG Display LCD Monitor LGD02DA 1920x1080 380x210mm 17.1-inch         | 1         | 1.09%   |
| LG Display LCD Monitor LGD02AD 1366x768 340x190mm 15.3-inch          | 1         | 1.09%   |
| LG Display LCD Monitor LGD029B 1366x768 310x170mm 13.9-inch          | 1         | 1.09%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch              | 1         | 1.09%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch              | 1         | 1.09%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 47        | 52.22%  |
| 1920x1080 (FHD)    | 25        | 27.78%  |
| 1280x800 (WXGA)    | 7         | 7.78%   |
| 1600x900 (HD+)     | 5         | 5.56%   |
| 1440x900 (WXGA+)   | 2         | 2.22%   |
| 3840x2160 (4K)     | 1         | 1.11%   |
| 3200x1800 (QHD+)   | 1         | 1.11%   |
| 1680x1050 (WSXGA+) | 1         | 1.11%   |
| 1280x1024 (SXGA)   | 1         | 1.11%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 35        | 38.04%  |
| 13     | 29        | 31.52%  |
| 12     | 10        | 10.87%  |
| 17     | 7         | 7.61%   |
| 11     | 3         | 3.26%   |
| 21     | 2         | 2.17%   |
| 19     | 2         | 2.17%   |
| 27     | 1         | 1.09%   |
| 24     | 1         | 1.09%   |
| 22     | 1         | 1.09%   |
| 14     | 1         | 1.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 56        | 60.87%  |
| 201-300     | 22        | 23.91%  |
| 351-400     | 8         | 8.7%    |
| 401-500     | 4         | 4.35%   |
| 601-700     | 1         | 1.09%   |
| 501-600     | 1         | 1.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 76        | 86.36%  |
| 16/10 | 10        | 11.36%  |
| 5/4   | 1         | 1.14%   |
| 3/2   | 1         | 1.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 27        | 29.35%  |
| 81-90          | 26        | 28.26%  |
| 61-70          | 10        | 10.87%  |
| 101-110        | 8         | 8.7%    |
| 121-130        | 6         | 6.52%   |
| 71-80          | 4         | 4.35%   |
| 201-250        | 4         | 4.35%   |
| 51-60          | 3         | 3.26%   |
| 151-200        | 2         | 2.17%   |
| 301-350        | 1         | 1.09%   |
| 131-140        | 1         | 1.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 38        | 41.76%  |
| 101-120       | 37        | 40.66%  |
| 51-100        | 13        | 14.29%  |
| 161-240       | 2         | 2.2%    |
| More than 240 | 1         | 1.1%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 86        | 74.14%  |
| 0     | 24        | 20.69%  |
| 2     | 6         | 5.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 67        | 36.61%  |
| Realtek Semiconductor             | 50        | 27.32%  |
| Qualcomm Atheros                  | 32        | 17.49%  |
| Broadcom                          | 15        | 8.2%    |
| Ralink                            | 3         | 1.64%   |
| Marvell Technology Group          | 3         | 1.64%   |
| Ralink Technology                 | 2         | 1.09%   |
| TP-Link                           | 1         | 0.55%   |
| Toshiba                           | 1         | 0.55%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.55%   |
| Sierra Wireless                   | 1         | 0.55%   |
| Samsung Electronics               | 1         | 0.55%   |
| Huawei Technologies               | 1         | 0.55%   |
| Hewlett-Packard                   | 1         | 0.55%   |
| Ericsson Business Mobile Networks | 1         | 0.55%   |
| Dell                              | 1         | 0.55%   |
| D-Link                            | 1         | 0.55%   |
| AboCom Systems                    | 1         | 0.55%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 29        | 12.55%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 17        | 7.36%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 9         | 3.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 3.46%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 3.03%   |
| Intel Wireless 8260                                                     | 6         | 2.6%    |
| Intel Wireless 7265                                                     | 6         | 2.6%    |
| Intel Wireless 7260                                                     | 6         | 2.6%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 2.6%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 2.16%   |
| Intel WiFi Link 5100                                                    | 5         | 2.16%   |
| Intel Wireless 8265 / 8275                                              | 4         | 1.73%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 1.73%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 1.3%    |
| Intel Ethernet Connection I219-LM                                       | 3         | 1.3%    |
| Intel Ethernet Connection I218-LM                                       | 3         | 1.3%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 1.3%    |
| Intel Centrino Wireless-N 2230                                          | 3         | 1.3%    |
| Intel Centrino Advanced-N 6200                                          | 3         | 1.3%    |
| Intel 82577LM Gigabit Network Connection                                | 3         | 1.3%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.87%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 0.87%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 2         | 0.87%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 0.87%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 2         | 0.87%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.87%   |
| Intel Wireless 3165                                                     | 2         | 0.87%   |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 0.87%   |
| Intel Ethernet Connection (6) I219-LM                                   | 2         | 0.87%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 0.87%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 0.87%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 0.87%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 0.87%   |
| Intel 82567LM Gigabit Network Connection                                | 2         | 0.87%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                       | 2         | 0.87%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                       | 2         | 0.87%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 2         | 0.87%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 0.87%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 0.87%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 1         | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 63        | 51.22%  |
| Qualcomm Atheros      | 29        | 23.58%  |
| Realtek Semiconductor | 11        | 8.94%   |
| Broadcom              | 11        | 8.94%   |
| Ralink                | 3         | 2.44%   |
| Ralink Technology     | 2         | 1.63%   |
| TP-Link               | 1         | 0.81%   |
| Sierra Wireless       | 1         | 0.81%   |
| D-Link                | 1         | 0.81%   |
| AboCom Systems        | 1         | 0.81%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 6.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 5.69%   |
| Intel Wireless 8260                                                     | 6         | 4.88%   |
| Intel Wireless 7265                                                     | 6         | 4.88%   |
| Intel Wireless 7260                                                     | 6         | 4.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 4.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 4.07%   |
| Intel WiFi Link 5100                                                    | 5         | 4.07%   |
| Intel Wireless 8265 / 8275                                              | 4         | 3.25%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 3.25%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 2.44%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 2.44%   |
| Intel Centrino Wireless-N 2230                                          | 3         | 2.44%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 2.44%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 1.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 1.63%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 1.63%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.63%   |
| Intel Wireless 3165                                                     | 2         | 1.63%   |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 1.63%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.63%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 1.63%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 1.63%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 1.63%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 1.63%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 1.63%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 1         | 0.81%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 0.81%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.81%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.81%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 1         | 0.81%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1         | 0.81%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.81%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.81%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.81%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.81%   |
| Ralink RT2501/RT2573 Wireless Adapter                                   | 1         | 0.81%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                               | 1         | 0.81%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.81%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 47        | 45.19%  |
| Intel                            | 33        | 31.73%  |
| Qualcomm Atheros                 | 9         | 8.65%   |
| Broadcom                         | 9         | 8.65%   |
| Marvell Technology Group         | 3         | 2.88%   |
| Silicon Integrated Systems [SiS] | 1         | 0.96%   |
| Samsung Electronics              | 1         | 0.96%   |
| Huawei Technologies              | 1         | 0.96%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 29        | 27.88%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 16.35%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 8.65%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 2.88%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 2.88%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 2.88%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 1.92%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 1.92%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 1.92%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 1.92%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 1.92%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 1.92%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 1.92%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.96%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.96%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.96%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.96%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.96%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.96%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.96%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.96%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.96%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.96%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 0.96%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.96%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.96%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.96%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 0.96%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.96%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.96%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.96%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 0.96%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.96%   |
| Intel 82567LF Gigabit Network Connection                          | 1         | 0.96%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 0.96%   |
| Huawei USB Device                                                 | 1         | 0.96%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 0.96%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 0.96%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.96%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 114       | 51.82%  |
| Ethernet | 102       | 46.36%  |
| Modem    | 3         | 1.36%   |
| Unknown  | 1         | 0.45%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 100       | 50%     |
| WiFi     | 98        | 49%     |
| Modem    | 2         | 1%      |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 99        | 85.34%  |
| 1     | 17        | 14.66%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 108       | 92.31%  |
| Yes  | 9         | 7.69%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 37        | 49.33%  |
| Broadcom                        | 8         | 10.67%  |
| Qualcomm Atheros Communications | 6         | 8%      |
| Realtek Semiconductor           | 5         | 6.67%   |
| IMC Networks                    | 4         | 5.33%   |
| Apple                           | 4         | 5.33%   |
| Cambridge Silicon Radio         | 3         | 4%      |
| Ralink                          | 2         | 2.67%   |
| Lite-On Technology              | 2         | 2.67%   |
| Dell                            | 2         | 2.67%   |
| Hewlett-Packard                 | 1         | 1.33%   |
| Foxconn / Hon Hai               | 1         | 1.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 24        | 32%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 5         | 6.67%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 4         | 5.33%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 4         | 5.33%   |
| Intel AX201 Bluetooth                                       | 3         | 4%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 3         | 4%      |
| Apple Broadcom Built-in Bluetooth                           | 3         | 4%      |
| Ralink RT3290 Bluetooth                                     | 2         | 2.67%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 2         | 2.67%   |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS                 | 2         | 2.67%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 2         | 2.67%   |
| Realtek RTL8821A Bluetooth                                  | 1         | 1.33%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 1.33%   |
| Realtek CSR Bluetooth Chip                                  | 1         | 1.33%   |
| Realtek Bluetooth Adapter                                   | 1         | 1.33%   |
| Realtek Bluetooth 4.0 + High Speed Chip                     | 1         | 1.33%   |
| Qualcomm Atheros QCA9565 Bluetooth 4.0 + HS Adapter         | 1         | 1.33%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 1.33%   |
| Qualcomm Atheros AR9462 Bluetooth 3.0 + HS Adapter          | 1         | 1.33%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 1.33%   |
| Intel AX200 Bluetooth                                       | 1         | 1.33%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0                 | 1         | 1.33%   |
| IMC Networks Broadcom BCM20702 Bluetooth 4.0 +HS USB Device | 1         | 1.33%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 1.33%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 1.33%   |
| Dell DW375 Bluetooth Module                                 | 1         | 1.33%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 1         | 1.33%   |
| Broadcom BCM43142A0 Bluetooth 4.0                           | 1         | 1.33%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                        | 1         | 1.33%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 1         | 1.33%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 1         | 1.33%   |
| Apple Bluetooth Host Controller                             | 1         | 1.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 104       | 83.2%   |
| AMD                              | 15        | 12%     |
| Nvidia                           | 5         | 4%      |
| Silicon Integrated Systems [SiS] | 1         | 0.8%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 25        | 16.45%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 13        | 8.55%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 12        | 7.89%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 5.92%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 5.92%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 5.26%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 4.61%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 3.95%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 3.95%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 3.29%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 2.63%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 2.63%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.97%   |
| AMD FCH Azalia Controller                                                                         | 3         | 1.97%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 1.97%   |
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
| Samsung Electronics | 33        | 23.08%  |
| SK hynix            | 28        | 19.58%  |
| Micron Technology   | 16        | 11.19%  |
| Kingston            | 13        | 9.09%   |
| Elpida              | 10        | 6.99%   |
| Unknown             | 9         | 6.29%   |
| Smart               | 4         | 2.8%    |
| Ramaxel Technology  | 4         | 2.8%    |
| Crucial             | 4         | 2.8%    |
| Nanya Technology    | 3         | 2.1%    |
| Unknown             | 3         | 2.1%    |
| Teikon              | 2         | 1.4%    |
| High Bridge         | 2         | 1.4%    |
| Apacer              | 2         | 1.4%    |
| A-DATA Technology   | 2         | 1.4%    |
| Unknown (ABCD)      | 1         | 0.7%    |
| Transcend           | 1         | 0.7%    |
| Toshiba             | 1         | 0.7%    |
| Smart Brazil        | 1         | 0.7%    |
| SHARETRONIC         | 1         | 0.7%    |
| G.Skill             | 1         | 0.7%    |
| Corsair             | 1         | 0.7%    |
| Axiom               | 1         | 0.7%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 4         | 2.65%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s          | 3         | 1.99%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 3         | 1.99%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM 1333MT/s               | 3         | 1.99%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s          | 3         | 1.99%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 3         | 1.99%   |
| Unknown                                                        | 3         | 1.99%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                    | 2         | 1.32%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                   | 2         | 1.32%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s         | 2         | 1.32%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 2         | 1.32%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 2         | 1.32%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 1.32%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s          | 2         | 1.32%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s         | 2         | 1.32%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s          | 2         | 1.32%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s          | 2         | 1.32%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                    | 1         | 0.66%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                    | 1         | 0.66%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                    | 1         | 0.66%   |
| Unknown RAM Module 4GB SODIMM DDR3                             | 1         | 0.66%   |
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                     | 1         | 0.66%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 1         | 0.66%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                       | 1         | 0.66%   |
| Unknown RAM Module 2048MB SODIMM 667MT/s                       | 1         | 0.66%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1         | 0.66%   |
| Transcend RAM JM1600KSH-8G 8192MB SODIMM DDR3 1333MT/s         | 1         | 0.66%   |
| Toshiba RAM 8HTF12864HDY-800G1 2048MB SODIMM 800MT/s           | 1         | 0.66%   |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 800MT/s            | 1         | 0.66%   |
| Teikon RAM TMT451S6BFR8A-PBSC 4096MB SODIMM DDR3 1600MT/s      | 1         | 0.66%   |
| Teikon RAM TML251S6EFR8A-PBHC 4GB SODIMM DDR3 1600MT/s         | 1         | 0.66%   |
| Smart RAM SH564568FH8NWPHSFR 2GB SODIMM DDR3 1333MT/s          | 1         | 0.66%   |
| Smart RAM SH564128FJ8NZRNSDR 4GB SODIMM DDR3 1600MT/s          | 1         | 0.66%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2400MT/s   | 1         | 0.66%   |
| SK hynix RAM Module 2GB DDR3 1600MT/s                          | 1         | 0.66%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s          | 1         | 0.66%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 0.66%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 0.66%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1333MT/s         | 1         | 0.66%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s         | 1         | 0.66%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 69        | 60.53%  |
| DDR4    | 29        | 25.44%  |
| DDR2    | 7         | 6.14%   |
| Unknown | 5         | 4.39%   |
| LPDDR3  | 2         | 1.75%   |
| LPDDR4  | 1         | 0.88%   |
| DRAM    | 1         | 0.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 106       | 92.17%  |
| Row Of Chips | 4         | 3.48%   |
| DIMM         | 2         | 1.74%   |
| Chip         | 2         | 1.74%   |
| Unknown      | 1         | 0.87%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 54        | 41.54%  |
| 2048  | 39        | 30%     |
| 8192  | 28        | 21.54%  |
| 16384 | 8         | 6.15%   |
| 32768 | 1         | 0.77%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 42        | 33.07%  |
| 1333    | 19        | 14.96%  |
| 2667    | 12        | 9.45%   |
| 1334    | 12        | 9.45%   |
| 2400    | 9         | 7.09%   |
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
| Chicony Electronics                    | 22        | 25.88%  |
| Realtek Semiconductor                  | 10        | 11.76%  |
| IMC Networks                           | 7         | 8.24%   |
| Sunplus Innovation Technology          | 6         | 7.06%   |
| Microdia                               | 6         | 7.06%   |
| Bison Electronics                      | 6         | 7.06%   |
| Suyin                                  | 5         | 5.88%   |
| Syntek                                 | 3         | 3.53%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.53%   |
| Silicon Motion                         | 2         | 2.35%   |
| Lite-On Technology                     | 2         | 2.35%   |
| Importek                               | 2         | 2.35%   |
| Apple                                  | 2         | 2.35%   |
| Alcor Micro                            | 2         | 2.35%   |
| Ricoh                                  | 1         | 1.18%   |
| Quanta                                 | 1         | 1.18%   |
| Nanchang BYD Electronics               | 1         | 1.18%   |
| Luxvisions Innotech Limited            | 1         | 1.18%   |
| Logitech                               | 1         | 1.18%   |
| Lenovo                                 | 1         | 1.18%   |
| ALi                                    | 1         | 1.18%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 5         | 5.81%   |
| Realtek USB 2.0 PC Camera                           | 3         | 3.49%   |
| Realtek Integrated_Webcam_HD                        | 3         | 3.49%   |
| Chicony Integrated Camera [ThinkPad]                | 3         | 3.49%   |
| Chicony HP HD Webcam [Fixed]                        | 3         | 3.49%   |
| Syntek Lenovo EasyCamera                            | 2         | 2.33%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 2.33%   |
| Sunplus Asus Webcam                                 | 2         | 2.33%   |
| Realtek Integrated Webcam                           | 2         | 2.33%   |
| Microdia Laptop_Integrated_Webcam_HD                | 2         | 2.33%   |
| Microdia Integrated Webcam                          | 2         | 2.33%   |
| IMC Networks Realtek PC Camera                      | 2         | 2.33%   |
| IMC Networks Integrated Camera                      | 2         | 2.33%   |
| Chicony HP HD Camera                                | 2         | 2.33%   |
| Bison Integrated Camera                             | 2         | 2.33%   |
| Apple FaceTime HD Camera                            | 2         | 2.33%   |
| Syntek EasyCamera                                   | 1         | 1.16%   |
| Suyin USB 2.0 Camera                                | 1         | 1.16%   |
| Suyin Sony Visual Communication Camera              | 1         | 1.16%   |
| Suyin HP Webcam-101                                 | 1         | 1.16%   |
| Suyin HP Integrated Webcam                          | 1         | 1.16%   |
| Suyin Acer/Lenovo Webcam [CN0316]                   | 1         | 1.16%   |
| Sunplus Integrated Camera                           | 1         | 1.16%   |
| Sunplus Dell E5570 integrated webcam                | 1         | 1.16%   |
| Silicon Motion WebCam SCX Series                    | 1         | 1.16%   |
| Silicon Motion Realtek USB 2.0 PC Camera            | 1         | 1.16%   |
| Ricoh Integrated Camera                             | 1         | 1.16%   |
| Realtek LG Camera                                   | 1         | 1.16%   |
| Realtek Dell EasyCamera                             | 1         | 1.16%   |
| Quanta HP Webcam                                    | 1         | 1.16%   |
| Nanchang BYD USB2.0 HD UVC WebCam                   | 1         | 1.16%   |
| Microdia Laptop_Integrated_Webcam_FHD               | 1         | 1.16%   |
| Microdia HP Webcam                                  | 1         | 1.16%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 1.16%   |
| Logitech Webcam C270                                | 1         | 1.16%   |
| Lite-On Integrated Camera                           | 1         | 1.16%   |
| Lite-On HP IR Camera                                | 1         | 1.16%   |
| Lenovo Integrated Webcam [R5U877]                   | 1         | 1.16%   |
| Importek TOSHIBA Web Camera - HD                    | 1         | 1.16%   |
| Importek TOSHIBA Web Camera                         | 1         | 1.16%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 9         | 64.29%  |
| Synaptics             | 1         | 7.14%   |
| STMicroelectronics    | 1         | 7.14%   |
| Elan Microelectronics | 1         | 7.14%   |
| Broadcom              | 1         | 7.14%   |
| AuthenTec             | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                                  | 3         | 21.43%  |
| Validity Sensors VFS495 Fingerprint Reader                                   | 3         | 21.43%  |
| Validity Sensors VFS451 Fingerprint Reader                                   | 1         | 7.14%   |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 1         | 7.14%   |
| Validity Sensors Synaptics WBDI                                              | 1         | 7.14%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 1         | 7.14%   |
| STMicroelectronics Fingerprint Reader                                        | 1         | 7.14%   |
| Elan Fingerprint Sensor                                                      | 1         | 7.14%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 7.14%   |
| AuthenTec AES2810                                                            | 1         | 7.14%   |

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
| 2     | 42        | 35.59%  |
| 1     | 35        | 29.66%  |
| 3     | 21        | 17.8%   |
| 0     | 11        | 9.32%   |
| 4     | 6         | 5.08%   |
| 5     | 2         | 1.69%   |
| 6     | 1         | 0.85%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 89        | 42.58%  |
| Card reader              | 52        | 24.88%  |
| Bluetooth                | 20        | 9.57%   |
| Net/wireless             | 19        | 9.09%   |
| Fingerprint reader       | 14        | 6.7%    |
| Firewire controller      | 8         | 3.83%   |
| Storage                  | 3         | 1.44%   |
| Sound                    | 2         | 0.96%   |
| Network                  | 1         | 0.48%   |
| Dvb card                 | 1         | 0.48%   |

