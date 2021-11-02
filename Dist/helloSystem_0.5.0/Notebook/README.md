helloSystem 0.5.0 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for helloSystem 0.5.0.

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
| HP            | ProBook 470 G4              | [5f026ff3a2](https://bsd-hardware.info/?probe=5f026ff3a2) | Oct 17, 2021 |
| HP            | ProBook 470 G4              | [40c180238f](https://bsd-hardware.info/?probe=40c180238f) | Oct 17, 2021 |
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
| amd64 | 111       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 110       | 99.1%   |
| KDE5         | 1         | 0.9%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 111       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SLiM | 111       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 111       | 100%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 88        | 79.28%  |
| BIOS | 23        | 20.72%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Zfs  | 111       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 111       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 32        | 28.83%  |
| Dell                | 19        | 17.12%  |
| Hewlett-Packard     | 18        | 16.22%  |
| ASUSTek Computer    | 10        | 9.01%   |
| Toshiba             | 8         | 7.21%   |
| Apple               | 5         | 4.5%    |
| Acer                | 3         | 2.7%    |
| Samsung Electronics | 2         | 1.8%    |
| Gateway             | 2         | 1.8%    |
| WYSE                | 1         | 0.9%    |
| TUXEDO              | 1         | 0.9%    |
| Sony                | 1         | 0.9%    |
| Packard Bell        | 1         | 0.9%    |
| NEC Computers       | 1         | 0.9%    |
| MSI                 | 1         | 0.9%    |
| MouseComputer       | 1         | 0.9%    |
| LG Electronics      | 1         | 0.9%    |
| Hampoo              | 1         | 0.9%    |
| Fujitsu             | 1         | 0.9%    |
| eMachines           | 1         | 0.9%    |
| Alienware           | 1         | 0.9%    |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Dell Inspiron 15-3567                       | 3         | 2.7%    |
| Gateway NE56R                               | 2         | 1.8%    |
| Dell Inspiron 7520                          | 2         | 1.8%    |
| Apple MacBookPro9,2                         | 2         | 1.8%    |
| WYSE Z CLASS                                | 1         | 0.9%    |
| TUXEDO Aura 15 Gen1                         | 1         | 0.9%    |
| Toshiba Satellite Pro U400                  | 1         | 0.9%    |
| Toshiba Satellite P300                      | 1         | 0.9%    |
| Toshiba Satellite L855                      | 1         | 0.9%    |
| Toshiba Satellite L500                      | 1         | 0.9%    |
| Toshiba Satellite C640                      | 1         | 0.9%    |
| Toshiba PORTEGE Z10t-A                      | 1         | 0.9%    |
| Toshiba PORTEGE R930                        | 1         | 0.9%    |
| Toshiba dynabook Satellite B453/L           | 1         | 0.9%    |
| Sony VPCEJ1E1E                              | 1         | 0.9%    |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 1         | 0.9%    |
| Samsung 530U3C/530U4C/532U3C                | 1         | 0.9%    |
| Packard Bell EasyNote MH36                  | 1         | 0.9%    |
| NEC Computers PC-VK17HBBCD                  | 1         | 0.9%    |
| MSI GF65 Thin 10SDR                         | 1         | 0.9%    |
| MouseComputer W331AU                        | 1         | 0.9%    |
| LG 14Z980-G.BH51P1                          | 1         | 0.9%    |
| Lenovo ZIUS6                                | 1         | 0.9%    |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS          | 1         | 0.9%    |
| Lenovo ThinkPad X260 20F5S82N00             | 1         | 0.9%    |
| Lenovo ThinkPad X250 20CLS4JH00             | 1         | 0.9%    |
| Lenovo ThinkPad X240 20AMS39F0K             | 1         | 0.9%    |
| Lenovo ThinkPad X230 Tablet 343522U         | 1         | 0.9%    |
| Lenovo ThinkPad X230 2330A48                | 1         | 0.9%    |
| Lenovo ThinkPad X230 2325WWB                | 1         | 0.9%    |
| Lenovo ThinkPad X230 2325O76                | 1         | 0.9%    |
| Lenovo ThinkPad X230 23255Y4                | 1         | 0.9%    |
| Lenovo ThinkPad X230 23254G7                | 1         | 0.9%    |
| Lenovo ThinkPad X200 7458VP4                | 1         | 0.9%    |
| Lenovo ThinkPad T61 64607EU                 | 1         | 0.9%    |
| Lenovo ThinkPad T490s 20NYS3TU00            | 1         | 0.9%    |
| Lenovo ThinkPad T490 20RYS06R00             | 1         | 0.9%    |
| Lenovo ThinkPad T470p 20J6A012CD            | 1         | 0.9%    |
| Lenovo ThinkPad T440s 20ARS1B704            | 1         | 0.9%    |
| Lenovo ThinkPad T420 4236FJ1                | 1         | 0.9%    |
| Lenovo ThinkPad T410 2537E82                | 1         | 0.9%    |
| Lenovo ThinkPad T14s Gen 1 20T1S0Q200       | 1         | 0.9%    |
| Lenovo ThinkPad L520 78594KM                | 1         | 0.9%    |
| Lenovo ThinkPad L450 20DTCTO1WW             | 1         | 0.9%    |
| Lenovo ThinkPad Edge E530 62724FU           | 1         | 0.9%    |
| Lenovo ThinkPad E420 1141A83                | 1         | 0.9%    |
| Lenovo Legion Y530-15ICH 81FV               | 1         | 0.9%    |
| Lenovo IdeaPad S145-15IWL 81S9              | 1         | 0.9%    |
| Lenovo IdeaPad 110S-11IBR 80WG              | 1         | 0.9%    |
| Lenovo G550 2958                            | 1         | 0.9%    |
| Lenovo G500s 20245                          | 1         | 0.9%    |
| Lenovo G500 20236                           | 1         | 0.9%    |
| Lenovo G470 20078                           | 1         | 0.9%    |
| Lenovo B41-80 80LG                          | 1         | 0.9%    |
| HP Stream 11 Pro G4 EE                      | 1         | 0.9%    |
| HP ProBook 470 G4                           | 1         | 0.9%    |
| HP ProBook 4440s                            | 1         | 0.9%    |
| HP ProBook 440 G2                           | 1         | 0.9%    |
| HP Pavilion Notebook                        | 1         | 0.9%    |
| HP Pavilion Laptop 14-ce2xxx                | 1         | 0.9%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 22        | 19.82%  |
| Dell Latitude              | 8         | 7.21%   |
| HP Pavilion                | 6         | 5.41%   |
| Dell Inspiron              | 6         | 5.41%   |
| Toshiba Satellite          | 5         | 4.5%    |
| HP ProBook                 | 3         | 2.7%    |
| Acer Aspire                | 3         | 2.7%    |
| Toshiba PORTEGE            | 2         | 1.8%    |
| Lenovo IdeaPad             | 2         | 1.8%    |
| HP EliteBook               | 2         | 1.8%    |
| Gateway NE56R              | 2         | 1.8%    |
| Dell Vostro                | 2         | 1.8%    |
| ASUS VivoBook              | 2         | 1.8%    |
| Apple MacBookPro9          | 2         | 1.8%    |
| WYSE Z                     | 1         | 0.9%    |
| TUXEDO Aura                | 1         | 0.9%    |
| Toshiba dynabook           | 1         | 0.9%    |
| Sony VPCEJ1E1E             | 1         | 0.9%    |
| Samsung RV411              | 1         | 0.9%    |
| Samsung 530U3C             | 1         | 0.9%    |
| Packard Bell EasyNote      | 1         | 0.9%    |
| NEC Computers PC-VK17HBBCD | 1         | 0.9%    |
| MSI GF65                   | 1         | 0.9%    |
| MouseComputer W331AU       | 1         | 0.9%    |
| LG 14Z980-G.BH51P1         | 1         | 0.9%    |
| Lenovo ZIUS6               | 1         | 0.9%    |
| Lenovo Yoga                | 1         | 0.9%    |
| Lenovo Legion              | 1         | 0.9%    |
| Lenovo G550                | 1         | 0.9%    |
| Lenovo G500s               | 1         | 0.9%    |
| Lenovo G500                | 1         | 0.9%    |
| Lenovo G470                | 1         | 0.9%    |
| Lenovo B41-80              | 1         | 0.9%    |
| HP Stream                  | 1         | 0.9%    |
| HP OMEN                    | 1         | 0.9%    |
| HP G42                     | 1         | 0.9%    |
| HP 625                     | 1         | 0.9%    |
| HP 255                     | 1         | 0.9%    |
| HP 250                     | 1         | 0.9%    |
| HP 15                      | 1         | 0.9%    |
| Hampoo NA123               | 1         | 0.9%    |
| Fujitsu LIFEBOOK           | 1         | 0.9%    |
| eMachines eME732ZG         | 1         | 0.9%    |
| Dell XPS                   | 1         | 0.9%    |
| Dell Precision             | 1         | 0.9%    |
| Dell G3                    | 1         | 0.9%    |
| ASUS X55CR                 | 1         | 0.9%    |
| ASUS X556UA                | 1         | 0.9%    |
| ASUS X555LD                | 1         | 0.9%    |
| ASUS X441BA                | 1         | 0.9%    |
| ASUS UX330UAK              | 1         | 0.9%    |
| ASUS Strix                 | 1         | 0.9%    |
| ASUS K55VD                 | 1         | 0.9%    |
| ASUS G75VW                 | 1         | 0.9%    |
| Apple MacBookPro6          | 1         | 0.9%    |
| Apple MacBookPro3          | 1         | 0.9%    |
| Apple MacBookAir7          | 1         | 0.9%    |
| Alienware 17               | 1         | 0.9%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 22        | 19.82%  |
| 2013 | 18        | 16.22%  |
| 2019 | 16        | 14.41%  |
| 2011 | 8         | 7.21%   |
| 2009 | 8         | 7.21%   |
| 2018 | 7         | 6.31%   |
| 2014 | 7         | 6.31%   |
| 2015 | 6         | 5.41%   |
| 2021 | 5         | 4.5%    |
| 2012 | 5         | 4.5%    |
| 2017 | 3         | 2.7%    |
| 2016 | 2         | 1.8%    |
| 2010 | 2         | 1.8%    |
| 2008 | 2         | 1.8%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 111       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 110       | 99.1%   |
| Yes  | 1         | 0.9%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 48        | 43.24%  |
| 8.01-16.0  | 43        | 38.74%  |
| 16.01-24.0 | 15        | 13.51%  |
| 32.01-64.0 | 3         | 2.7%    |
| 24.01-32.0 | 1         | 0.9%    |
| 2.01-3.0   | 1         | 0.9%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 77        | 69.37%  |
| 0.51-1.0  | 28        | 25.23%  |
| 1.01-2.0  | 3         | 2.7%    |
| 2.01-3.0  | 2         | 1.8%    |
| 8.01-16.0 | 1         | 0.9%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 88        | 78.57%  |
| 2      | 15        | 13.39%  |
| 0      | 7         | 6.25%   |
| 3      | 2         | 1.79%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 58        | 52.25%  |
| No        | 53        | 47.75%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 97        | 87.39%  |
| No        | 14        | 12.61%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 109       | 98.2%   |
| No        | 2         | 1.8%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 71        | 63.96%  |
| No        | 40        | 36.04%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| USA                | 19        | 16.96%  |
| Germany            | 12        | 10.71%  |
| Brazil             | 8         | 7.14%   |
| Netherlands        | 6         | 5.36%   |
| China              | 5         | 4.46%   |
| UK                 | 4         | 3.57%   |
| Sweden             | 4         | 3.57%   |
| Spain              | 4         | 3.57%   |
| Italy              | 4         | 3.57%   |
| Switzerland        | 3         | 2.68%   |
| Poland             | 3         | 2.68%   |
| Indonesia          | 3         | 2.68%   |
| India              | 3         | 2.68%   |
| Ukraine            | 2         | 1.79%   |
| Portugal           | 2         | 1.79%   |
| Mexico             | 2         | 1.79%   |
| Lithuania          | 2         | 1.79%   |
| Japan              | 2         | 1.79%   |
| Canada             | 2         | 1.79%   |
| South Africa       | 1         | 0.89%   |
| Slovakia           | 1         | 0.89%   |
| Puerto Rico        | 1         | 0.89%   |
| Oman               | 1         | 0.89%   |
| New Zealand        | 1         | 0.89%   |
| Morocco            | 1         | 0.89%   |
| Montenegro         | 1         | 0.89%   |
| Malta              | 1         | 0.89%   |
| Malaysia           | 1         | 0.89%   |
| Latvia             | 1         | 0.89%   |
| Hungary            | 1         | 0.89%   |
| Greece             | 1         | 0.89%   |
| France             | 1         | 0.89%   |
| Dominican Republic | 1         | 0.89%   |
| Cyprus             | 1         | 0.89%   |
| Croatia            | 1         | 0.89%   |
| Bulgaria           | 1         | 0.89%   |
| Belgium            | 1         | 0.89%   |
| Belarus            | 1         | 0.89%   |
| Austria            | 1         | 0.89%   |
| Australia          | 1         | 0.89%   |
| Argentina          | 1         | 0.89%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Zurich               | 2         | 1.75%   |
| Wroclaw              | 2         | 1.75%   |
| Surabaya             | 2         | 1.75%   |
| Berlin               | 2         | 1.75%   |
| Zhengzhou            | 1         | 0.88%   |
| Zagreb               | 1         | 0.88%   |
| Wuhan                | 1         | 0.88%   |
| Washington           | 1         | 0.88%   |
| Warmond              | 1         | 0.88%   |
| Wandur               | 1         | 0.88%   |
| Vilnius              | 1         | 0.88%   |
| Vigonovo             | 1         | 0.88%   |
| Vienna               | 1         | 0.88%   |
| V?�ster??s           | 1         | 0.88%   |
| Vancouver            | 1         | 0.88%   |
| Utrecht              | 1         | 0.88%   |
| Tula de Allende      | 1         | 0.88%   |
| Traverse City        | 1         | 0.88%   |
| The Bronx            | 1         | 0.88%   |
| Tangara              | 1         | 0.88%   |
| Sungai Buloh         | 1         | 0.88%   |
| Solarino             | 1         | 0.88%   |
| Sofia                | 1         | 0.88%   |
| Shibakoen            | 1         | 0.88%   |
| Shasta               | 1         | 0.88%   |
| Santo Domingo Este   | 1         | 0.88%   |
| Sankt Augustin       | 1         | 0.88%   |
| Roosendaal           | 1         | 0.88%   |
| Riga                 | 1         | 0.88%   |
| Redondela            | 1         | 0.88%   |
| Pleidelsheim         | 1         | 0.88%   |
| Plav                 | 1         | 0.88%   |
| Plattsburgh          | 1         | 0.88%   |
| Perwez               | 1         | 0.88%   |
| Osasco               | 1         | 0.88%   |
| Oosterhout           | 1         | 0.88%   |
| Oklahoma City        | 1         | 0.88%   |
| Notting Hill Gate    | 1         | 0.88%   |
| Nizwa                | 1         | 0.88%   |
| New Braunfels        | 1         | 0.88%   |
| Munich               | 1         | 0.88%   |
| Morden               | 1         | 0.88%   |
| Montreuil            | 1         | 0.88%   |
| Miskolc              | 1         | 0.88%   |
| Mar del Plata        | 1         | 0.88%   |
| Macerata             | 1         | 0.88%   |
| Lusk                 | 1         | 0.88%   |
| Lule??               | 1         | 0.88%   |
| Lisbon               | 1         | 0.88%   |
| Liptovský Mikuláš | 1         | 0.88%   |
| Limassol             | 1         | 0.88%   |
| Leipzig              | 1         | 0.88%   |
| Leesville            | 1         | 0.88%   |
| Las Vegas            | 1         | 0.88%   |
| Langnau am Albis     | 1         | 0.88%   |
| Lake Forest          | 1         | 0.88%   |
| Lajeado              | 1         | 0.88%   |
| Krakow               | 1         | 0.88%   |
| Klaipėda            | 1         | 0.88%   |
| Klagshamn            | 1         | 0.88%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 17        | 17     | 14.29%  |
| Seagate             | 16        | 17     | 13.45%  |
| Samsung Electronics | 16        | 21     | 13.45%  |
| Toshiba             | 11        | 11     | 9.24%   |
| Crucial             | 11        | 11     | 9.24%   |
| SanDisk             | 6         | 6      | 5.04%   |
| Intel               | 6         | 6      | 5.04%   |
| Hitachi             | 6         | 7      | 5.04%   |
| Kingston            | 5         | 6      | 4.2%    |
| A-DATA Technology   | 4         | 5      | 3.36%   |
| SPCC                | 2         | 2      | 1.68%   |
| OCZ                 | 2         | 2      | 1.68%   |
| HGST                | 2         | 2      | 1.68%   |
| Apple               | 2         | 2      | 1.68%   |
| Transcend           | 1         | 2      | 0.84%   |
| SMART               | 1         | 1      | 0.84%   |
| SK Hynix            | 1         | 1      | 0.84%   |
| PNY                 | 1         | 1      | 0.84%   |
| Patriot             | 1         | 1      | 0.84%   |
| MyDigitalSSD        | 1         | 1      | 0.84%   |
| Micron Technology   | 1         | 1      | 0.84%   |
| LITEONIT            | 1         | 1      | 0.84%   |
| LITEON              | 1         | 1      | 0.84%   |
| KingSpec            | 1         | 1      | 0.84%   |
| HPE                 | 1         | 1      | 0.84%   |
| Hewlett-Packard     | 1         | 2      | 0.84%   |
| Fujitsu             | 1         | 1      | 0.84%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 3         | 2.46%   |
| Seagate ST9500325AS 500GB            | 2         | 1.64%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 2         | 1.64%   |
| Samsung SSD 850 EVO 250GB            | 2         | 1.64%   |
| Kingston SA400S37120G 120GB          | 2         | 1.64%   |
| Crucial CT1000MX500SSD1 1TB          | 2         | 1.64%   |
| A-DATA SU650 120GB                   | 2         | 1.64%   |
| WDC WDS240G2G0A-00JH30 240GB         | 1         | 0.82%   |
| WDC WDS120G1G0A-00SS50 120GB         | 1         | 0.82%   |
| WDC WDBNCE2500PNC 250GB              | 1         | 0.82%   |
| WDC WD800BEVS-00RST0 80GB            | 1         | 0.82%   |
| WDC WD7500BPVX-60JC3T0 752GB         | 1         | 0.82%   |
| WDC WD5000LPVX-60V0TT0 500GB         | 1         | 0.82%   |
| WDC WD5000LPVX-00V0TT0 500GB         | 1         | 0.82%   |
| WDC WD3200BEVT-60ZCT1 320GB          | 1         | 0.82%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 0.82%   |
| WDC WD3200BEKT-75PVMT1 320GB         | 1         | 0.82%   |
| WDC WD2500BEVT-75ZCT2 250GB          | 1         | 0.82%   |
| WDC WD1600BEVT-75ZCT2 160GB          | 1         | 0.82%   |
| WDC WD10SPZX-24Z10 1TB               | 1         | 0.82%   |
| WDC WD10JPVX-00JC3T0 1TB             | 1         | 0.82%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB   | 1         | 0.82%   |
| WDC PC SN530 SDBPNPZ-512G-1032 512GB | 1         | 0.82%   |
| WDC PC SN530 SDBPNPZ-256G-1002 256GB | 1         | 0.82%   |
| Transcend TS512GMTS430S 512GB        | 1         | 0.82%   |
| Toshiba THNSNF128GCSS 128GB          | 1         | 0.82%   |
| Toshiba THNSNC128GMLJ 128GB          | 1         | 0.82%   |
| Toshiba MQ01ABF050 500GB             | 1         | 0.82%   |
| Toshiba MQ01ABD100 1TB               | 1         | 0.82%   |
| Toshiba MQ01ABD075 752GB             | 1         | 0.82%   |
| Toshiba MQ01ABD032 320GB             | 1         | 0.82%   |
| Toshiba MK3265GSXN 320GB             | 1         | 0.82%   |
| Toshiba MK3261GSYN 320GB             | 1         | 0.82%   |
| Toshiba MK3261GSY 320GB              | 1         | 0.82%   |
| Toshiba KXG50PNV2T04 NVMe 2048GB     | 1         | 0.82%   |
| Toshiba KBG40ZNS256G NVMe 256GB      | 1         | 0.82%   |
| SPCC Solid State Disk 256GB          | 1         | 0.82%   |
| SPCC Solid State Disk 1TB            | 1         | 0.82%   |
| SMART SSD XceedValue2 mSATA 32GB     | 1         | 0.82%   |
| SK Hynix SHGP31-1000GM-2 1TB         | 1         | 0.82%   |
| Seagate ST9320423AS 320GB            | 1         | 0.82%   |
| Seagate ST9250315AS 250GB            | 1         | 0.82%   |
| Seagate ST9160412ASG 160GB           | 1         | 0.82%   |
| Seagate ST9160412AS 160GB            | 1         | 0.82%   |
| Seagate ST500LM000-SSHD-8GB          | 1         | 0.82%   |
| Seagate ST320LT012-9WS14C 320GB      | 1         | 0.82%   |
| Seagate ST1000LM049-2GH172 1TB       | 1         | 0.82%   |
| Seagate ST1000LM048-2E7172 1TB       | 1         | 0.82%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 1         | 0.82%   |
| SanDisk Ultra II 480GB               | 1         | 0.82%   |
| SanDisk SSD i100 24GB                | 1         | 0.82%   |
| SanDisk SDSSDP128G 128GB             | 1         | 0.82%   |
| SanDisk SDSSDHP256G 256GB            | 1         | 0.82%   |
| SanDisk SD8SBAT256G1002 256GB        | 1         | 0.82%   |
| SanDisk SD7SN6S-256G-1006 256GB      | 1         | 0.82%   |
| Samsung SSD RBX Series 64GB M        | 1         | 0.82%   |
| Samsung SSD PM871b M.2 2280 128GB    | 1         | 0.82%   |
| Samsung SSD PM851 mSATA 256GB        | 1         | 0.82%   |
| Samsung SSD 980 PRO 500GB            | 1         | 0.82%   |
| Samsung SSD 970 EVO 250GB            | 1         | 0.82%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 17     | 34.04%  |
| WDC                 | 11        | 11     | 23.4%   |
| Toshiba             | 7         | 7      | 14.89%  |
| Hitachi             | 6         | 7      | 12.77%  |
| Samsung Electronics | 3         | 3      | 6.38%   |
| HGST                | 2         | 2      | 4.26%   |
| Fujitsu             | 1         | 1      | 2.13%   |
| Apple               | 1         | 1      | 2.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 15     | 19.67%  |
| Crucial             | 10        | 10     | 16.39%  |
| SanDisk             | 6         | 6      | 9.84%   |
| Kingston            | 5         | 6      | 8.2%    |
| Intel               | 4         | 4      | 6.56%   |
| WDC                 | 3         | 3      | 4.92%   |
| A-DATA Technology   | 3         | 4      | 4.92%   |
| Toshiba             | 2         | 2      | 3.28%   |
| SPCC                | 2         | 2      | 3.28%   |
| OCZ                 | 2         | 2      | 3.28%   |
| Transcend           | 1         | 2      | 1.64%   |
| SMART               | 1         | 1      | 1.64%   |
| PNY                 | 1         | 1      | 1.64%   |
| Patriot             | 1         | 1      | 1.64%   |
| MyDigitalSSD        | 1         | 1      | 1.64%   |
| Micron Technology   | 1         | 1      | 1.64%   |
| LITEONIT            | 1         | 1      | 1.64%   |
| LITEON              | 1         | 1      | 1.64%   |
| KingSpec            | 1         | 1      | 1.64%   |
| HPE                 | 1         | 1      | 1.64%   |
| Hewlett-Packard     | 1         | 2      | 1.64%   |
| Apple               | 1         | 1      | 1.64%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 56        | 68     | 48.7%   |
| HDD  | 47        | 49     | 40.87%  |
| NVMe | 12        | 13     | 10.43%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 96        | 117    | 88.89%  |
| NVMe | 12        | 13     | 11.11%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 78        | 92     | 78%     |
| 0.51-1.0   | 20        | 23     | 20%     |
| 1.01-2.0   | 2         | 2      | 2%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 65        | 58.56%  |
| 101-250    | 17        | 15.32%  |
| 251-500    | 16        | 14.41%  |
| 501-1000   | 6         | 5.41%   |
| 51-100     | 4         | 3.6%    |
| 21-50      | 2         | 1.8%    |
| 1001-2000  | 1         | 0.9%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 111       | 100%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                    | Notebooks | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB           | 2         | 2      | 7.69%   |
| WDC WD5000LPVX-60V0TT0 500GB             | 1         | 1      | 3.85%   |
| WDC WD3200BEVT-22ZCT0 320GB              | 1         | 1      | 3.85%   |
| Toshiba MQ01ABD075 752GB                 | 1         | 1      | 3.85%   |
| Toshiba MQ01ABD032 320GB                 | 1         | 1      | 3.85%   |
| Toshiba MK3265GSXN 320GB                 | 1         | 1      | 3.85%   |
| Toshiba MK3261GSYN 320GB                 | 1         | 1      | 3.85%   |
| Seagate ST9500325AS 500GB                | 1         | 1      | 3.85%   |
| Seagate ST9320423AS 320GB                | 1         | 1      | 3.85%   |
| Seagate ST9160412AS 160GB                | 1         | 1      | 3.85%   |
| Seagate ST500LM012 HN-M500MBB 500GB      | 1         | 1      | 3.85%   |
| Seagate ST320LT012-9WS14C 320GB          | 1         | 2      | 3.85%   |
| Seagate ST1000LM049-2GH172 1TB           | 1         | 1      | 3.85%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 1         | 1      | 3.85%   |
| Samsung Electronics SSD 840 Series 500GB | 1         | 1      | 3.85%   |
| Kingston RBU-SNS8350DES3128GP 128GB      | 1         | 1      | 3.85%   |
| Hitachi HTS545050B9A300 500GB            | 1         | 1      | 3.85%   |
| Hitachi HTS545050A7E380 500GB            | 1         | 1      | 3.85%   |
| Hitachi HTS545032B9A300 320GB            | 1         | 1      | 3.85%   |
| Hitachi HTS545025B9SA02 250GB            | 1         | 1      | 3.85%   |
| HGST HTS721010A9E630 1TB                 | 1         | 1      | 3.85%   |
| Hewlett-Packard SSD S700 1TB             | 1         | 1      | 3.85%   |
| Fujitsu MHW2160BH 160GB                  | 1         | 1      | 3.85%   |
| Crucial CT525MX300SSD1 528GB             | 1         | 1      | 3.85%   |
| Apple HDD HTS545050A7E362 500GB          | 1         | 1      | 3.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 10     | 34.62%  |
| Toshiba             | 4         | 4      | 15.38%  |
| Hitachi             | 4         | 4      | 15.38%  |
| WDC                 | 2         | 2      | 7.69%   |
| Samsung Electronics | 1         | 1      | 3.85%   |
| Kingston            | 1         | 1      | 3.85%   |
| HGST                | 1         | 1      | 3.85%   |
| Hewlett-Packard     | 1         | 1      | 3.85%   |
| Fujitsu             | 1         | 1      | 3.85%   |
| Crucial             | 1         | 1      | 3.85%   |
| Apple               | 1         | 1      | 3.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 9         | 10     | 40.91%  |
| Toshiba | 4         | 4      | 18.18%  |
| Hitachi | 4         | 4      | 18.18%  |
| WDC     | 2         | 2      | 9.09%   |
| HGST    | 1         | 1      | 4.55%   |
| Fujitsu | 1         | 1      | 4.55%   |
| Apple   | 1         | 1      | 4.55%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 22        | 23     | 84.62%  |
| SSD  | 4         | 4      | 15.38%  |

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
| Works   | 84        | 102    | 75.68%  |
| Malfunc | 26        | 27     | 23.42%  |
| Failed  | 1         | 1      | 0.9%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 97        | 83.62%  |
| AMD                       | 8         | 6.9%    |
| Sandisk                   | 3         | 2.59%   |
| Samsung Electronics       | 3         | 2.59%   |
| Toshiba                   | 1         | 0.86%   |
| SK Hynix                  | 1         | 0.86%   |
| Realtek Semiconductor     | 1         | 0.86%   |
| Micron/Crucial Technology | 1         | 0.86%   |
| KIOXIA                    | 1         | 0.86%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 23        | 18.55%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 12        | 9.68%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 9         | 7.26%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 8         | 6.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 8         | 6.45%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 7         | 5.65%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 5         | 4.03%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 5         | 4.03%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 2.42%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 3         | 2.42%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 2.42%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 2.42%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 2         | 1.61%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 1.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.61%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 1.61%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 1.61%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 1.61%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 2         | 1.61%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 2         | 1.61%   |
| Unknown                                                                          | 2         | 1.61%   |
| Toshiba unknown                                                                  | 1         | 0.81%   |
| SK Hynix Gold P31 SSD                                                            | 1         | 0.81%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.81%   |
| Samsung SM951 AHCI                                                               | 1         | 0.81%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 0.81%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.81%   |
| KIOXIA unknown                                                                   | 1         | 0.81%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 1         | 0.81%   |
| Intel SSD 660P Series                                                            | 1         | 0.81%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 0.81%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 0.81%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 0.81%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 0.81%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 1         | 0.81%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 1         | 0.81%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 1         | 0.81%   |
| AMD FCH IDE Controller                                                           | 1         | 0.81%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 94        | 77.69%  |
| NVMe | 12        | 9.92%   |
| IDE  | 8         | 6.61%   |
| RAID | 7         | 5.79%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 101       | 90.99%  |
| AMD    | 10        | 9.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel CPU Version                     | 6         | 5.41%   |
| Intel Core i5-3320M CPU @ 2.60GHz     | 5         | 4.5%    |
| Intel Core i5-3210M CPU @ 2.50GHz     | 4         | 3.6%    |
| Intel Core i7-8750H CPU @ 2.20GHz     | 3         | 2.7%    |
| Intel Core i5-6200U CPU @ 2.30GHz     | 3         | 2.7%    |
| Intel Core i5-4210U CPU @ 1.70GHz     | 3         | 2.7%    |
| Intel Core i7-7500U CPU @ 2.70GHz     | 2         | 1.8%    |
| Intel Core i7-4510U CPU @ 2.00GHz     | 2         | 1.8%    |
| Intel Core i7-3630QM CPU @ 2.40GHz    | 2         | 1.8%    |
| Intel Core i7 CPU M 620 @ 2.67GHz     | 2         | 1.8%    |
| Intel Core i5-6300U CPU @ 2.40GHz     | 2         | 1.8%    |
| Intel Core i5-5200U CPU @ 2.20GHz     | 2         | 1.8%    |
| Intel Core i5-3340M CPU @ 2.70GHz     | 2         | 1.8%    |
| Intel Core i5-3230M CPU @ 2.60GHz     | 2         | 1.8%    |
| Intel Core i5-2520M CPU @ 2.50GHz     | 2         | 1.8%    |
| Intel Core i3-6006U CPU @ 2.00GHz     | 2         | 1.8%    |
| Intel Core i3-5005U CPU @ 2.00GHz     | 2         | 1.8%    |
| Intel Core i3-2370M CPU @ 2.40GHz     | 2         | 1.8%    |
| Intel Core i3-2350M CPU @ 2.30GHz     | 2         | 1.8%    |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz  | 2         | 1.8%    |
| Intel Core 2 Duo                      | 2         | 1.8%    |
| Intel Celeron CPU N3450 @ 1.10GHz     | 2         | 1.8%    |
| Intel Celeron CPU 1005M @ 1.90GHz     | 2         | 1.8%    |
| Intel Pentium CPU P6200 @ 2.13GHz     | 1         | 0.9%    |
| Intel Pentium CPU B940 @ 2.00GHz      | 1         | 0.9%    |
| Intel Genuine CPU                     | 1         | 0.9%    |
| Intel Core i7-8665U CPU @ 1.90GHz     | 1         | 0.9%    |
| Intel Core i7-8565U CPU @ 1.80GHz     | 1         | 0.9%    |
| Intel Core i7-6820HQ CPU @ 2.70GHz    | 1         | 0.9%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz    | 1         | 0.9%    |
| Intel Core i7-4700MQ CPU @ 2.40GHz    | 1         | 0.9%    |
| Intel Core i7-4600U CPU @ 2.10GHz     | 1         | 0.9%    |
| Intel Core i7-3632QM CPU @ 2.20GHz    | 1         | 0.9%    |
| Intel Core i7-2637M CPU               | 1         | 0.9%    |
| Intel Core i7-10750H CPU @ 2.60GHz    | 1         | 0.9%    |
| Intel Core i7-10610U CPU @ 1.80GHz    | 1         | 0.9%    |
| Intel Core i7-10510U CPU @ 1.80GHz    | 1         | 0.9%    |
| Intel Core i5-8365U CPU @ 1.60GHz     | 1         | 0.9%    |
| Intel Core i5-8265U CPU @ 1.60GHz     | 1         | 0.9%    |
| Intel Core i5-8250U CPU @ 1.60GHz     | 1         | 0.9%    |
| Intel Core i5-7300HQ CPU @ 2.50GHz    | 1         | 0.9%    |
| Intel Core i5-7200U CPU @ 2.50GHz     | 1         | 0.9%    |
| Intel Core i5-6300HQ CPU @ 2.30GHz    | 1         | 0.9%    |
| Intel Core i5-5250U CPU @ 1.60GHz     | 1         | 0.9%    |
| Intel Core i5-4300U CPU @ 1.90GHz     | 1         | 0.9%    |
| Intel Core i5-4210Y CPU @ 1.50GHz     | 1         | 0.9%    |
| Intel Core i5-4200U CPU @ 1.60GHz     | 1         | 0.9%    |
| Intel Core i5-2537M CPU @ 1.40GHz     | 1         | 0.9%    |
| Intel Core i5 CPU M 560 @ 2.67GH      | 1         | 0.9%    |
| Intel Core i5 CPU M 540 @ 2.53GHz     | 1         | 0.9%    |
| Intel Core i3-8145U CPU @ 2.10GHz     | 1         | 0.9%    |
| Intel Core i3-7100U CPU @ 2.40GHz     | 1         | 0.9%    |
| Intel Core i3-3120M CPU @ 2.50GHz     | 1         | 0.9%    |
| Intel Core i3-3110M CPU @ 2.40GHz     | 1         | 0.9%    |
| Intel Core i3-2330M CPU @ 2.20GHz     | 1         | 0.9%    |
| Intel Core i3-2310M CPU @ 2.10GH      | 1         | 0.9%    |
| Intel Core i3 CPU M 390 @ 2.67GHz     | 1         | 0.9%    |
| Intel Core 2 Solo CPU U3500 @ 1.40GHz | 1         | 0.9%    |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz  | 1         | 0.9%    |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz  | 1         | 0.9%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model             | Notebooks | Percent |
|-------------------|-----------|---------|
| Intel Core i5     | 38        | 34.23%  |
| Intel Core i7     | 22        | 19.82%  |
| Intel Core i3     | 15        | 13.51%  |
| Intel Celeron     | 9         | 8.11%   |
| Intel Core 2 Duo  | 7         | 6.31%   |
| Other             | 6         | 5.41%   |
| Intel Pentium     | 2         | 1.8%    |
| AMD Ryzen 7       | 2         | 1.8%    |
| AMD A6            | 2         | 1.8%    |
| Intel Genuine     | 1         | 0.9%    |
| Intel Core 2 Solo | 1         | 0.9%    |
| AMD Ryzen 3       | 1         | 0.9%    |
| AMD Phenom II     | 1         | 0.9%    |
| AMD G             | 1         | 0.9%    |
| AMD E1            | 1         | 0.9%    |
| AMD Athlon II     | 1         | 0.9%    |
| AMD A10           | 1         | 0.9%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 79        | 71.17%  |
| 4       | 20        | 18.02%  |
| Unknown | 5         | 4.5%    |
| 6       | 4         | 3.6%    |
| 16      | 1         | 0.9%    |
| 8       | 1         | 0.9%    |
| 1       | 1         | 0.9%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 110       | 99.1%   |
| 2      | 1         | 0.9%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 73        | 65.77%  |
| 1       | 32        | 28.83%  |
| Unknown | 6         | 5.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| IvyBridge   | 20        | 18.02%  |
| KabyLake    | 16        | 14.41%  |
| SandyBridge | 13        | 11.71%  |
| Penryn      | 11        | 9.91%   |
| Skylake     | 10        | 9.01%   |
| Haswell     | 10        | 9.01%   |
| Westmere    | 7         | 6.31%   |
| Broadwell   | 6         | 5.41%   |
| Core        | 3         | 2.7%    |
| Silvermont  | 2         | 1.8%    |
| K10         | 2         | 1.8%    |
| Jaguar      | 2         | 1.8%    |
| Goldmont    | 2         | 1.8%    |
| Zen+        | 1         | 0.9%    |
| Zen 3       | 1         | 0.9%    |
| Zen 2       | 1         | 0.9%    |
| Piledriver  | 1         | 0.9%    |
| Excavator   | 1         | 0.9%    |
| CometLake   | 1         | 0.9%    |
| Bobcat      | 1         | 0.9%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 91        | 70%     |
| Nvidia | 21        | 16.15%  |
| AMD    | 18        | 13.85%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 18        | 13.85%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 12        | 9.23%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 9         | 6.92%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 6.15%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 5.38%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 3.85%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 3.85%   |
| Intel HD Graphics 620                                                                    | 4         | 3.08%   |
| Intel HD Graphics 5500                                                                   | 4         | 3.08%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 2.31%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 2.31%   |
| Intel HD Graphics 530                                                                    | 3         | 2.31%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 2.31%   |
| Intel HD Graphics 500                                                                    | 2         | 1.54%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.54%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.54%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 2         | 1.54%   |
| AMD Chelsea LP [Radeon HD 7730M]                                                         | 2         | 1.54%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.77%   |
| Nvidia GT216M [NVS 5100M]                                                                | 1         | 0.77%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.77%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.77%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 0.77%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.77%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.77%   |
| Nvidia GK107M [GeForce GTX 660M]                                                         | 1         | 0.77%   |
| Nvidia GK106M [GeForce GTX 770M]                                                         | 1         | 0.77%   |
| Nvidia GF119M [GeForce 610M]                                                             | 1         | 0.77%   |
| Nvidia GF119M [GeForce 410M]                                                             | 1         | 0.77%   |
| Nvidia G98M [Quadro NVS 160M]                                                            | 1         | 0.77%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 0.77%   |
| Nvidia G86M [Quadro NVS 140M]                                                            | 1         | 0.77%   |
| Nvidia G84M [GeForce 8600M GT]                                                           | 1         | 0.77%   |
| Intel UHD Graphics 620                                                                   | 1         | 0.77%   |
| Intel HD Graphics 630                                                                    | 1         | 0.77%   |
| Intel HD Graphics 6000                                                                   | 1         | 0.77%   |
| Intel HD Graphics                                                                        | 1         | 0.77%   |
| Intel Haswell-ULT High Definition Audio Controller [HD Graphics]                         | 1         | 0.77%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 0.77%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 0.77%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 0.77%   |
| AMD Venus XTX [Radeon HD 8890M / R9 M275X/M375X]                                         | 1         | 0.77%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 0.77%   |
| AMD Temash [Radeon HD 8250/8280G]                                                        | 1         | 0.77%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 0.77%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 0.77%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 0.77%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 1         | 0.77%   |
| AMD Richland [Radeon HD 8610G]                                                           | 1         | 0.77%   |
| AMD Renoir                                                                               | 1         | 0.77%   |
| AMD Picasso                                                                              | 1         | 0.77%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 1         | 0.77%   |
| AMD Kabini [Radeon HD 8210]                                                              | 1         | 0.77%   |
| AMD Cezanne                                                                              | 1         | 0.77%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 63        | 56.76%  |
| Intel + Nvidia | 14        | 12.61%  |
| 1 x AMD        | 13        | 11.71%  |
| 2 x Intel      | 9         | 8.11%   |
| 1 x Nvidia     | 7         | 6.31%   |
| Intel + AMD    | 5         | 4.5%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 90        | 81.08%  |
| Unknown     | 19        | 17.12%  |
| Proprietary | 2         | 1.8%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 100       | 90.09%  |
| 0.01-0.5   | 8         | 7.21%   |
| 0.51-1.0   | 2         | 1.8%    |
| 1.01-2.0   | 1         | 0.9%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 24        | 27.59%  |
| AU Optronics            | 18        | 20.69%  |
| Chimei Innolux          | 13        | 14.94%  |
| Samsung Electronics     | 9         | 10.34%  |
| Chi Mei Optoelectronics | 5         | 5.75%   |
| BOE                     | 5         | 5.75%   |
| InfoVision              | 3         | 3.45%   |
| Lenovo                  | 2         | 2.3%    |
| Apple                   | 2         | 2.3%    |
| AOC                     | 2         | 2.3%    |
| Sony                    | 1         | 1.15%   |
| LG Philips              | 1         | 1.15%   |
| Goldstar                | 1         | 1.15%   |
| Dell                    | 1         | 1.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch             | 3         | 3.45%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch      | 2         | 2.3%    |
| LG Display LCD Monitor LGD0532 1920x1080 340x190mm 15.3-inch              | 2         | 2.3%    |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch               | 2         | 2.3%    |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch               | 2         | 2.3%    |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 310x170mm 13.9-inch          | 2         | 2.3%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 340x190mm 15.3-inch             | 2         | 2.3%    |
| Sony SDM-HS95P SNY2500 1280x1024 380x300mm 19.1-inch                      | 1         | 1.15%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 470x300mm 22.0-inch      | 1         | 1.15%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 330x210mm 15.4-inch      | 1         | 1.15%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 370x230mm 17.2-inch      | 1         | 1.15%   |
| Samsung Electronics LCD Monitor SEC354C 1366x768 350x200mm 15.9-inch      | 1         | 1.15%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 340x190mm 15.3-inch      | 1         | 1.15%   |
| Samsung Electronics LCD Monitor SDC324D 1366x768 310x170mm 13.9-inch      | 1         | 1.15%   |
| Samsung Electronics LCD Monitor SDC324A 1366x768 290x170mm 13.2-inch      | 1         | 1.15%   |
| LG Philips LCD Monitor LPL3B01 1280x800 330x210mm 15.4-inch               | 1         | 1.15%   |
| LG Display LCD Monitor LGD11F9 1280x800 290x180mm 13.4-inch               | 1         | 1.15%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch              | 1         | 1.15%   |
| LG Display LCD Monitor LGD05B1 1920x1080 310x170mm 13.9-inch              | 1         | 1.15%   |
| LG Display LCD Monitor LGD0545 3200x1800 290x170mm 13.2-inch              | 1         | 1.15%   |
| LG Display LCD Monitor LGD053F 1920x1080 340x190mm 15.3-inch              | 1         | 1.15%   |
| LG Display LCD Monitor LGD0527 1366x768 310x170mm 13.9-inch               | 1         | 1.15%   |
| LG Display LCD Monitor LGD0525 1366x768 340x190mm 15.3-inch               | 1         | 1.15%   |
| LG Display LCD Monitor LGD045C 1366x768 350x190mm 15.7-inch               | 1         | 1.15%   |
| LG Display LCD Monitor LGD0459 1920x1080 380x210mm 17.1-inch              | 1         | 1.15%   |
| LG Display LCD Monitor LGD0446 1920x1080 310x170mm 13.9-inch              | 1         | 1.15%   |
| LG Display LCD Monitor LGD03A3 1366x768 280x160mm 12.7-inch               | 1         | 1.15%   |
| LG Display LCD Monitor LGD0372 1600x900 380x210mm 17.1-inch               | 1         | 1.15%   |
| LG Display LCD Monitor LGD0360 1600x900 290x170mm 13.2-inch               | 1         | 1.15%   |
| LG Display LCD Monitor LGD02E9 1366x768 310x170mm 13.9-inch               | 1         | 1.15%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x170mm 13.9-inch               | 1         | 1.15%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch               | 1         | 1.15%   |
| LG Display LCD Monitor LGD02DA 1920x1080 380x210mm 17.1-inch              | 1         | 1.15%   |
| LG Display LCD Monitor LGD02AD 1366x768 340x190mm 15.3-inch               | 1         | 1.15%   |
| LG Display LCD Monitor LGD029B 1366x768 310x170mm 13.9-inch               | 1         | 1.15%   |
| LG Display LCD Monitor LGD0230 1366x768 340x190mm 15.3-inch               | 1         | 1.15%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch                   | 1         | 1.15%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch                   | 1         | 1.15%   |
| InfoVision LCD Monitor IVO0579 1366x768 310x170mm 13.9-inch               | 1         | 1.15%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 1         | 1.15%   |
| Dell E2013H DELD05C 1600x900 440x250mm 19.9-inch                          | 1         | 1.15%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 380x210mm 17.1-inch          | 1         | 1.15%   |
| Chimei Innolux LCD Monitor CMN15B1 1920x1080 340x190mm 15.3-inch          | 1         | 1.15%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch           | 1         | 1.15%   |
| Chimei Innolux LCD Monitor CMN15A9 1366x768 340x190mm 15.3-inch           | 1         | 1.15%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 310x170mm 13.9-inch          | 1         | 1.15%   |
| Chimei Innolux LCD Monitor CMN14E0 1920x1080 310x170mm 13.9-inch          | 1         | 1.15%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch          | 1         | 1.15%   |
| Chimei Innolux LCD Monitor CMN14A1 1366x768 310x170mm 13.9-inch           | 1         | 1.15%   |
| Chimei Innolux LCD Monitor CMN1469 1366x768 310x170mm 13.9-inch           | 1         | 1.15%   |
| Chimei Innolux LCD Monitor CMN1404 1920x1080 310x170mm 13.9-inch          | 1         | 1.15%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch           | 1         | 1.15%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 380x210mm 17.1-inch | 1         | 1.15%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch  | 1         | 1.15%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 350x190mm 15.7-inch  | 1         | 1.15%   |
| Chi Mei Optoelectronics LCD Monitor CMO1318 1366x768 290x160mm 13.0-inch  | 1         | 1.15%   |
| Chi Mei Optoelectronics LCD Monitor CMO1312 1280x800 290x180mm 13.4-inch  | 1         | 1.15%   |
| BOE LCD Monitor BOE0715 1366x768 250x140mm 11.3-inch                      | 1         | 1.15%   |
| BOE LCD Monitor BOE06C2 1366x768 340x190mm 15.3-inch                      | 1         | 1.15%   |
| BOE LCD Monitor BOE0691 1920x1080 280x160mm 12.7-inch                     | 1         | 1.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 45        | 52.33%  |
| 1920x1080 (FHD)    | 24        | 27.91%  |
| 1280x800 (WXGA)    | 6         | 6.98%   |
| 1600x900 (HD+)     | 5         | 5.81%   |
| 1440x900 (WXGA+)   | 2         | 2.33%   |
| 3840x2160 (4K)     | 1         | 1.16%   |
| 3200x1800 (QHD+)   | 1         | 1.16%   |
| 1680x1050 (WSXGA+) | 1         | 1.16%   |
| 1280x1024 (SXGA)   | 1         | 1.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 32        | 36.78%  |
| 13     | 28        | 32.18%  |
| 12     | 10        | 11.49%  |
| 17     | 7         | 8.05%   |
| 11     | 3         | 3.45%   |
| 21     | 2         | 2.3%    |
| 19     | 2         | 2.3%    |
| 27     | 1         | 1.15%   |
| 22     | 1         | 1.15%   |
| 14     | 1         | 1.15%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 52        | 59.77%  |
| 201-300     | 22        | 25.29%  |
| 351-400     | 8         | 9.2%    |
| 401-500     | 4         | 4.6%    |
| 601-700     | 1         | 1.15%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 73        | 86.9%   |
| 16/10 | 10        | 11.9%   |
| 5/4   | 1         | 1.19%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 25        | 28.74%  |
| 91-100         | 25        | 28.74%  |
| 61-70          | 10        | 11.49%  |
| 101-110        | 7         | 8.05%   |
| 121-130        | 6         | 6.9%    |
| 71-80          | 4         | 4.6%    |
| 51-60          | 3         | 3.45%   |
| 201-250        | 3         | 3.45%   |
| 151-200        | 2         | 2.3%    |
| 301-350        | 1         | 1.15%   |
| 131-140        | 1         | 1.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 37        | 43.02%  |
| 101-120       | 35        | 40.7%   |
| 51-100        | 11        | 12.79%  |
| 161-240       | 2         | 2.33%   |
| More than 240 | 1         | 1.16%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 83        | 74.77%  |
| 0     | 23        | 20.72%  |
| 2     | 5         | 4.5%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 65        | 37.79%  |
| Realtek Semiconductor             | 47        | 27.33%  |
| Qualcomm Atheros                  | 30        | 17.44%  |
| Broadcom                          | 15        | 8.72%   |
| Ralink                            | 3         | 1.74%   |
| Marvell Technology Group          | 3         | 1.74%   |
| Ralink Technology                 | 2         | 1.16%   |
| TP-Link                           | 1         | 0.58%   |
| Toshiba                           | 1         | 0.58%   |
| Sierra Wireless                   | 1         | 0.58%   |
| Hewlett-Packard                   | 1         | 0.58%   |
| Ericsson Business Mobile Networks | 1         | 0.58%   |
| D-Link                            | 1         | 0.58%   |
| AboCom Systems                    | 1         | 0.58%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 27        | 12.39%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 17        | 7.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 9         | 4.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 8         | 3.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 7         | 3.21%   |
| Intel Wireless 7265                                                                   | 6         | 2.75%   |
| Intel Wireless 7260                                                                   | 6         | 2.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 6         | 2.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 5         | 2.29%   |
| Intel Wireless 8260                                                                   | 5         | 2.29%   |
| Intel WiFi Link 5100                                                                  | 5         | 2.29%   |
| Intel Wireless 8265 / 8275                                                            | 4         | 1.83%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 4         | 1.83%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 3         | 1.38%   |
| Intel Ethernet Connection I218-LM                                                     | 3         | 1.38%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 3         | 1.38%   |
| Intel Centrino Wireless-N 2230                                                        | 3         | 1.38%   |
| Intel Centrino Advanced-N 6200                                                        | 3         | 1.38%   |
| Intel 82577LM Gigabit Network Connection                                              | 3         | 1.38%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                             | 2         | 0.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 2         | 0.92%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                                | 2         | 0.92%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 2         | 0.92%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                              | 2         | 0.92%   |
| Intel Wireless 3165                                                                   | 2         | 0.92%   |
| Intel Ultimate N WiFi Link 5300                                                       | 2         | 0.92%   |
| Intel Ethernet Connection I219-LM                                                     | 2         | 0.92%   |
| Intel Ethernet Connection (6) I219-LM                                                 | 2         | 0.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 2         | 0.92%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                          | 2         | 0.92%   |
| Intel Centrino Advanced-N 6235                                                        | 2         | 0.92%   |
| Intel 82567LM Gigabit Network Connection                                              | 2         | 0.92%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                                     | 2         | 0.92%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                                     | 2         | 0.92%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                       | 2         | 0.92%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 2         | 0.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 2         | 0.92%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                            | 1         | 0.46%   |
| Toshiba Ericsson H5321gw for TOSHIBA Mobile Broadband Network Adapter                 | 1         | 0.46%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                                         | 1         | 0.46%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 1         | 0.46%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.46%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 1         | 0.46%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                | 1         | 0.46%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                           | 1         | 0.46%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 0.46%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 1         | 0.46%   |
| Ralink RT5370 Wireless Adapter                                                        | 1         | 0.46%   |
| Ralink RT2501/RT2573 Wireless Adapter                                                 | 1         | 0.46%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 1         | 0.46%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                             | 1         | 0.46%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 1         | 0.46%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 1         | 0.46%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                            | 1         | 0.46%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                            | 1         | 0.46%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                         | 1         | 0.46%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                              | 1         | 0.46%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.46%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                               | 1         | 0.46%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                               | 1         | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 61        | 51.69%  |
| Qualcomm Atheros      | 27        | 22.88%  |
| Broadcom              | 11        | 9.32%   |
| Realtek Semiconductor | 10        | 8.47%   |
| Ralink                | 3         | 2.54%   |
| Ralink Technology     | 2         | 1.69%   |
| TP-Link               | 1         | 0.85%   |
| Sierra Wireless       | 1         | 0.85%   |
| D-Link                | 1         | 0.85%   |
| AboCom Systems        | 1         | 0.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 8         | 6.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 7         | 5.93%   |
| Intel Wireless 7265                                                                   | 6         | 5.08%   |
| Intel Wireless 7260                                                                   | 6         | 5.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 6         | 5.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 5         | 4.24%   |
| Intel Wireless 8260                                                                   | 5         | 4.24%   |
| Intel WiFi Link 5100                                                                  | 5         | 4.24%   |
| Intel Wireless 8265 / 8275                                                            | 4         | 3.39%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 4         | 3.39%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 3         | 2.54%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 3         | 2.54%   |
| Intel Centrino Wireless-N 2230                                                        | 3         | 2.54%   |
| Intel Centrino Advanced-N 6200                                                        | 3         | 2.54%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                             | 2         | 1.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 2         | 1.69%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 2         | 1.69%   |
| Intel Wireless 3165                                                                   | 2         | 1.69%   |
| Intel Ultimate N WiFi Link 5300                                                       | 2         | 1.69%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 2         | 1.69%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                          | 2         | 1.69%   |
| Intel Centrino Advanced-N 6235                                                        | 2         | 1.69%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 2         | 1.69%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 2         | 1.69%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                            | 1         | 0.85%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                                         | 1         | 0.85%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 1         | 0.85%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.85%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 1         | 0.85%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                | 1         | 0.85%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                           | 1         | 0.85%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 0.85%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 1         | 0.85%   |
| Ralink RT5370 Wireless Adapter                                                        | 1         | 0.85%   |
| Ralink RT2501/RT2573 Wireless Adapter                                                 | 1         | 0.85%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 1         | 0.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 1         | 0.85%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 1         | 0.85%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.85%   |
| Intel Wi-Fi 6 AX200                                                                   | 1         | 0.85%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                               | 1         | 0.85%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                         | 1         | 0.85%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 1         | 0.85%   |
| Intel Centrino Wireless-N 135                                                         | 1         | 0.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 1         | 0.85%   |
| D-Link DWA-171 AC600 DB Wireless Adapter(rev.A1) [Realtek RTL8811AU]                  | 1         | 0.85%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                    | 1         | 0.85%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                    | 1         | 0.85%   |
| Broadcom BCM43225 802.11b/g/n                                                         | 1         | 0.85%   |
| Broadcom BCM43224 802.11a/b/g/n                                                       | 1         | 0.85%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 1         | 0.85%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 1         | 0.85%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                     | 1         | 0.85%   |
| AboCom Systems 802.11n/b/g Mini Wireless LAN USB2.0 Adapter                           | 1         | 0.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 44        | 45.36%  |
| Intel                    | 32        | 32.99%  |
| Qualcomm Atheros         | 9         | 9.28%   |
| Broadcom                 | 9         | 9.28%   |
| Marvell Technology Group | 3         | 3.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 27        | 27.84%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 17.53%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 9.28%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 3.09%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 3.09%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 2.06%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 2.06%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 2.06%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 2.06%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 2.06%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 2.06%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 2.06%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 2.06%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.03%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.03%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 1.03%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.03%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.03%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 1.03%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.03%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 1.03%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.03%   |
| Intel Ethernet Connection I218-V                                  | 1         | 1.03%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.03%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 1.03%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 1.03%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.03%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.03%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 1.03%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.03%   |
| Intel 82567LF Gigabit Network Connection                          | 1         | 1.03%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.03%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 1.03%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 1.03%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.03%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 109       | 52.15%  |
| Ethernet | 97        | 46.41%  |
| Modem    | 3         | 1.44%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 96        | 49.48%  |
| Ethernet | 96        | 49.48%  |
| Modem    | 2         | 1.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 94        | 84.68%  |
| 1     | 17        | 15.32%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 104       | 92.86%  |
| Yes  | 8         | 7.14%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 35        | 48.61%  |
| Broadcom                        | 8         | 11.11%  |
| Qualcomm Atheros Communications | 6         | 8.33%   |
| Realtek Semiconductor           | 4         | 5.56%   |
| IMC Networks                    | 4         | 5.56%   |
| Apple                           | 4         | 5.56%   |
| Cambridge Silicon Radio         | 3         | 4.17%   |
| Ralink                          | 2         | 2.78%   |
| Lite-On Technology              | 2         | 2.78%   |
| Dell                            | 2         | 2.78%   |
| Hewlett-Packard                 | 1         | 1.39%   |
| Foxconn / Hon Hai               | 1         | 1.39%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 23        | 31.94%  |
| Intel Centrino Bluetooth Wireless Transceiver               | 4         | 5.56%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 4         | 5.56%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 4         | 5.56%   |
| Intel AX201 Bluetooth                                       | 3         | 4.17%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 3         | 4.17%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 3         | 4.17%   |
| Ralink RT3290 Bluetooth                                     | 2         | 2.78%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 2         | 2.78%   |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS                 | 2         | 2.78%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 2         | 2.78%   |
| Realtek RTL8821A Bluetooth                                  | 1         | 1.39%   |
| Realtek  Bluetooth 4.0 + High Speed Chip                    | 1         | 1.39%   |
| Realtek CSR Bluetooth Chip                                  | 1         | 1.39%   |
| Realtek Bluetooth Radio                                     | 1         | 1.39%   |
| Qualcomm Atheros  QCA9565 Bluetooth 4.0 + HS Adapter        | 1         | 1.39%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 1.39%   |
| Qualcomm Atheros Atheros AR9462 Bluetooth 3.0 + HS Adapter  | 1         | 1.39%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 1.39%   |
| Intel AX200 Bluetooth                                       | 1         | 1.39%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0                 | 1         | 1.39%   |
| IMC Networks Broadcom BCM20702 Bluetooth 4.0 +HS USB Device | 1         | 1.39%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 1.39%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 1.39%   |
| Dell DW375 Bluetooth Module                                 | 1         | 1.39%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 1         | 1.39%   |
| Broadcom BCM43142A0 Bluetooth 4.0                           | 1         | 1.39%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                        | 1         | 1.39%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 1         | 1.39%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 1         | 1.39%   |
| Apple Bluetooth Host Controller                             | 1         | 1.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 101       | 84.17%  |
| AMD    | 14        | 11.67%  |
| Nvidia | 5         | 4.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 25        | 17.12%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 12        | 8.22%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 12        | 8.22%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 6.16%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 6.16%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 5.48%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 4.79%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 4.11%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 4.11%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 3.42%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 2.05%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 2.05%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 2.05%   |
| AMD FCH Azalia Controller                                                                         | 3         | 2.05%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 3         | 2.05%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 1.37%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.37%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 1.37%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.37%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.37%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 2         | 1.37%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1.37%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.37%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.68%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.68%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 0.68%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.68%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.68%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 0.68%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 0.68%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 0.68%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.68%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 0.68%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 0.68%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 0.68%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.68%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 0.68%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 33        | 23.91%  |
| SK Hynix            | 26        | 18.84%  |
| Micron Technology   | 16        | 11.59%  |
| Kingston            | 12        | 8.7%    |
| Elpida              | 10        | 7.25%   |
| Unknown             | 9         | 6.52%   |
| Smart               | 4         | 2.9%    |
| Ramaxel Technology  | 4         | 2.9%    |
| Crucial             | 4         | 2.9%    |
| Nanya Technology    | 3         | 2.17%   |
| Teikon              | 2         | 1.45%   |
| High Bridge         | 2         | 1.45%   |
| Apacer              | 2         | 1.45%   |
| A-DATA Technology   | 2         | 1.45%   |
| Unknown (ABCD)      | 1         | 0.72%   |
| Transcend           | 1         | 0.72%   |
| Toshiba             | 1         | 0.72%   |
| Smart Brazil        | 1         | 0.72%   |
| SHARETRONIC         | 1         | 0.72%   |
| G.Skill             | 1         | 0.72%   |
| Corsair             | 1         | 0.72%   |
| Axiom               | 1         | 0.72%   |
| Unknown             | 1         | 0.72%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 4         | 2.74%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s                     | 3         | 2.05%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 3         | 2.05%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s                     | 3         | 2.05%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1333MT/s                     | 3         | 2.05%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 3         | 2.05%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                               | 2         | 1.37%   |
| SK Hynix RAM Module 2GB SODIMM DDR3 1600MT/s                              | 2         | 1.37%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s                    | 2         | 1.37%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 2         | 1.37%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 2         | 1.37%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s                     | 2         | 1.37%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s                    | 2         | 1.37%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s                     | 2         | 1.37%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s                     | 2         | 1.37%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                               | 1         | 0.68%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                               | 1         | 0.68%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                               | 1         | 0.68%   |
| Unknown RAM Module 4GB SODIMM DDR3                                        | 1         | 0.68%   |
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                                | 1         | 0.68%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 1         | 0.68%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                                  | 1         | 0.68%   |
| Unknown RAM Module 2048MB SODIMM 667MT/s                                  | 1         | 0.68%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s              | 1         | 0.68%   |
| Transcend RAM JM1600KSH-8G 8192MB SODIMM DDR3 1333MT/s                    | 1         | 0.68%   |
| Toshiba RAM 8HTF12864HDY-800G1 2048MB SODIMM 800MT/s                      | 1         | 0.68%   |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 800MT/s                       | 1         | 0.68%   |
| Teikon RAM TMT451S6BFR8A-PBSC 4096MB SODIMM DDR3 1600MT/s                 | 1         | 0.68%   |
| Teikon RAM TML251S6EFR8A-PBHC 4096MB SODIMM DDR3 1600MT/s                 | 1         | 0.68%   |
| Smart RAM SH564568FH8NWPHSFR 2GB SODIMM DDR3 1333MT/s                     | 1         | 0.68%   |
| Smart RAM SH564128FJ8NZRNSDR 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.68%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4096MB SODIMM DDR4 2400MT/s           | 1         | 0.68%   |
| SK Hynix RAM Module 2GB DDR3 1600MT/s                                     | 1         | 0.68%   |
| SK Hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s                      | 1         | 0.68%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 0.68%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 0.68%   |
| SK Hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1333MT/s                    | 1         | 0.68%   |
| SK Hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s                    | 1         | 0.68%   |
| SK Hynix RAM HMT325S6CFR8C-H9 2048MB SODIMM DDR3 1333MT/s                 | 1         | 0.68%   |
| SK Hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s                    | 1         | 0.68%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16384MB SODIMM DDR4 3200MT/s                | 1         | 0.68%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s                    | 1         | 0.68%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s                    | 1         | 0.68%   |
| SK Hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 1         | 0.68%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 1         | 0.68%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB Chip DDR4 2133MT/s                   | 1         | 0.68%   |
| SK Hynix RAM 9A9A9A9A9A9A9A9A9A9A9A9A9A9A9A9A9A9A 2GB SODIMM DDR2 800MT/s | 1         | 0.68%   |
| SK Hynix RAM 313131313131313131313131313131313131 2GB SODIMM DDR2 800MT/s | 1         | 0.68%   |
| SHARETRONIC RAM Module 2GB SODIMM DDR3 1600MT/s                           | 1         | 0.68%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                               | 1         | 0.68%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s                     | 1         | 0.68%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1333MT/s                     | 1         | 0.68%   |
| Samsung RAM M471B5674EB0-YMA 2GB Row Of Chips DDR3 1600MT/s               | 1         | 0.68%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.68%   |
| Samsung RAM M471B5273BH1-CH9 4096MB SODIMM DDR3 1333MT/s                  | 1         | 0.68%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.68%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.68%   |
| Samsung RAM M471B1G73AH0-CH9 8GB SODIMM DDR3 1333MT/s                     | 1         | 0.68%   |
| Samsung RAM M471A5644EB0-CPB 2048MB SODIMM DDR4 2133MT/s                  | 1         | 0.68%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s                     | 1         | 0.68%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 69        | 62.73%  |
| DDR4    | 27        | 24.55%  |
| DDR2    | 6         | 5.45%   |
| Unknown | 5         | 4.55%   |
| LPDDR3  | 2         | 1.82%   |
| LPDDR4  | 1         | 0.91%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 103       | 92.79%  |
| Row Of Chips | 4         | 3.6%    |
| Chip         | 2         | 1.8%    |
| DIMM         | 1         | 0.9%    |
| Unknown      | 1         | 0.9%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 54        | 43.2%   |
| 2048  | 37        | 29.6%   |
| 8192  | 26        | 20.8%   |
| 16384 | 7         | 5.6%    |
| 32768 | 1         | 0.8%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 43        | 34.4%   |
| 1333    | 24        | 19.2%   |
| 2400    | 11        | 8.8%    |
| 2667    | 9         | 7.2%    |
| 1334    | 9         | 7.2%    |
| 2133    | 7         | 5.6%    |
| 800     | 7         | 5.6%    |
| 3200    | 3         | 2.4%    |
| 1067    | 3         | 2.4%    |
| 667     | 3         | 2.4%    |
| 1867    | 2         | 1.6%    |
| 1777    | 1         | 0.8%    |
| 1066    | 1         | 0.8%    |
| 975     | 1         | 0.8%    |
| Unknown | 1         | 0.8%    |

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
| Chicony Electronics                    | 21        | 25.93%  |
| Realtek Semiconductor                  | 10        | 12.35%  |
| Sunplus Innovation Technology          | 6         | 7.41%   |
| Microdia                               | 6         | 7.41%   |
| IMC Networks                           | 6         | 7.41%   |
| Acer                                   | 6         | 7.41%   |
| Suyin                                  | 5         | 6.17%   |
| Syntek                                 | 3         | 3.7%    |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.7%    |
| Silicon Motion                         | 2         | 2.47%   |
| Lite-On Technology                     | 2         | 2.47%   |
| Importek                               | 2         | 2.47%   |
| Apple                                  | 2         | 2.47%   |
| Alcor Micro                            | 2         | 2.47%   |
| Ricoh                                  | 1         | 1.23%   |
| Quanta                                 | 1         | 1.23%   |
| Logitech                               | 1         | 1.23%   |
| Lenovo                                 | 1         | 1.23%   |
| Holitech                               | 1         | 1.23%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                  | 5         | 6.1%    |
| Realtek Integrated_Webcam_HD                               | 4         | 4.88%   |
| Realtek Realtek USB2.0 PC Camera                           | 3         | 3.66%   |
| Chicony Integrated Camera [ThinkPad]                       | 3         | 3.66%   |
| Chicony HP HD Webcam [Fixed]                               | 3         | 3.66%   |
| Syntek Lenovo EasyCamera                                   | 2         | 2.44%   |
| Sunplus Integrated_Webcam_HD                               | 2         | 2.44%   |
| Sunplus Asus Webcam                                        | 2         | 2.44%   |
| Realtek Integrated Webcam                                  | 2         | 2.44%   |
| Microdia Laptop_Integrated_Webcam_HD                       | 2         | 2.44%   |
| Microdia Integrated Webcam                                 | 2         | 2.44%   |
| IMC Networks USB2.0 HD UVC WebCam                          | 2         | 2.44%   |
| IMC Networks Integrated Camera                             | 2         | 2.44%   |
| Apple FaceTime HD Camera                                   | 2         | 2.44%   |
| Acer Integrated Camera                                     | 2         | 2.44%   |
| Syntek EasyCamera                                          | 1         | 1.22%   |
| Suyin USB 2.0 Camera                                       | 1         | 1.22%   |
| Suyin Sony Visual Communication Camera                     | 1         | 1.22%   |
| Suyin HP Webcam-101                                        | 1         | 1.22%   |
| Suyin HP Integrated Webcam                                 | 1         | 1.22%   |
| Suyin Acer/Lenovo Webcam [CN0316]                          | 1         | 1.22%   |
| Sunplus Integrated Camera                                  | 1         | 1.22%   |
| Sunplus Dell E5570 integrated webcam                       | 1         | 1.22%   |
| Silicon Motion WebCam SCX Series                           | 1         | 1.22%   |
| Silicon Motion Realtek USB2.0 PC Camera                    | 1         | 1.22%   |
| Ricoh Integrated Camera                                    | 1         | 1.22%   |
| Realtek LG Camera                                          | 1         | 1.22%   |
| Quanta HP Webcam                                           | 1         | 1.22%   |
| Microdia Laptop_Integrated_Webcam_FHD                      | 1         | 1.22%   |
| Microdia HP Webcam                                         | 1         | 1.22%   |
| Logitech Webcam C270                                       | 1         | 1.22%   |
| Lite-On Integrated Camera                                  | 1         | 1.22%   |
| Lite-On HP IR Camera                                       | 1         | 1.22%   |
| Lenovo Integrated Webcam [R5U877]                          | 1         | 1.22%   |
| Importek TOSHIBA Web Camera - HD                           | 1         | 1.22%   |
| Importek TOSHIBA Web Camera                                | 1         | 1.22%   |
| IMC Networks USB2.0 VGA UVC WebCam                         | 1         | 1.22%   |
| IMC Networks EasyCamera                                    | 1         | 1.22%   |
| Holitech USB2.0 HD UVC WebCam                              | 1         | 1.22%   |
| Chicony UVC 1.00 device HD UVC WebCam                      | 1         | 1.22%   |
| Chicony USB2.0 VGA UVC WebCam                              | 1         | 1.22%   |
| Chicony USB 2.0 Camera                                     | 1         | 1.22%   |
| Chicony TOSHIBA Web Camera - HD                            | 1         | 1.22%   |
| Chicony TOSHIBA Web Camera - 3M                            | 1         | 1.22%   |
| Chicony Lenovo EasyCamera                                  | 1         | 1.22%   |
| Chicony HP Webcam [2 MP Macro]                             | 1         | 1.22%   |
| Chicony HP HD Camera                                       | 1         | 1.22%   |
| Chicony HD WebCam                                          | 1         | 1.22%   |
| Chicony Chicony USB2.0 Camera                              | 1         | 1.22%   |
| Chicony 1.3M Webcam                                        | 1         | 1.22%   |
| Cheng Uei Precision Industry (Foxlink) Webcam              | 1         | 1.22%   |
| Cheng Uei Precision Industry (Foxlink) Realtek DMFT - RGB  | 1         | 1.22%   |
| Cheng Uei Precision Industry (Foxlink) HP Universal Camera | 1         | 1.22%   |
| Alcor Micro USB 2.0 Camera                                 | 1         | 1.22%   |
| Alcor Micro Acer Integrated Webcam                         | 1         | 1.22%   |
| Acer ThinkPad Integrated Camera                            | 1         | 1.22%   |
| Acer Lenovo Integrated Webcam                              | 1         | 1.22%   |
| Acer Lenovo EasyCamera                                     | 1         | 1.22%   |
| Acer HD Webcam                                             | 1         | 1.22%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Validity Sensors   | 8         | 66.67%  |
| Synaptics          | 1         | 8.33%   |
| STMicroelectronics | 1         | 8.33%   |
| Broadcom           | 1         | 8.33%   |
| AuthenTec          | 1         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                                  | 3         | 25%     |
| Validity Sensors VFS495 Fingerprint Reader                                   | 2         | 16.67%  |
| Validity Sensors VFS451 Fingerprint Reader                                   | 1         | 8.33%   |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 1         | 8.33%   |
| Validity Sensors Synaptics WBDI                                              | 1         | 8.33%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 1         | 8.33%   |
| STMicroelectronics Fingerprint Reader                                        | 1         | 8.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 8.33%   |
| AuthenTec AES2810                                                            | 1         | 8.33%   |

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
| 2     | 40        | 35.4%   |
| 1     | 35        | 30.97%  |
| 3     | 22        | 19.47%  |
| 0     | 9         | 7.96%   |
| 4     | 6         | 5.31%   |
| 6     | 1         | 0.88%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 86        | 43.22%  |
| Card reader              | 51        | 25.63%  |
| Net/wireless             | 18        | 9.05%   |
| Bluetooth                | 18        | 9.05%   |
| Fingerprint reader       | 12        | 6.03%   |
| Firewire controller      | 8         | 4.02%   |
| Storage                  | 3         | 1.51%   |
| Sound                    | 2         | 1.01%   |
| Dvb card                 | 1         | 0.5%    |

