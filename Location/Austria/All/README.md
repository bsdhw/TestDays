BSD in Austria - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for BSD in Austria.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Austria/Desktop/README.md) and [notebooks](/Location/Austria/Notebook/README.md).

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

Total: 205

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| AAEON         | UP-APL01 V0.4               | Desktop     | [a8d73a9156](https://bsd-hardware.info/?probe=a8d73a9156) | Sep 01, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [63587e2fca](https://bsd-hardware.info/?probe=63587e2fca) | Aug 31, 2022 |
| Deciso        | NetBoard-A10                | Notebook    | [aefb2f4660](https://bsd-hardware.info/?probe=aefb2f4660) | Aug 24, 2022 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [45043e0e42](https://bsd-hardware.info/?probe=45043e0e42) | Aug 18, 2022 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | Desktop     | [4e056b6f77](https://bsd-hardware.info/?probe=4e056b6f77) | Aug 11, 2022 |
| Deciso        | Netboard A10 GEN2 Model ... | Desktop     | [1cd64c78d5](https://bsd-hardware.info/?probe=1cd64c78d5) | Aug 10, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [f603e648c7](https://bsd-hardware.info/?probe=f603e648c7) | Aug 01, 2022 |
| IP3 Tech      | IB2                         | Mini pc     | [9e304de7ad](https://bsd-hardware.info/?probe=9e304de7ad) | Jul 31, 2022 |
| Deciso        | Netboard A10 GEN2 Model ... | Desktop     | [5c00da486d](https://bsd-hardware.info/?probe=5c00da486d) | Jul 29, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [bd2f6f8596](https://bsd-hardware.info/?probe=bd2f6f8596) | Jul 29, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [69c0b0d218](https://bsd-hardware.info/?probe=69c0b0d218) | Jul 29, 2022 |
| Biostar       | A10N-8800E                  | Desktop     | [fe4d305991](https://bsd-hardware.info/?probe=fe4d305991) | Jul 27, 2022 |
| Gigabyte      | H87-HD3                     | Desktop     | [e6a9b0dd8b](https://bsd-hardware.info/?probe=e6a9b0dd8b) | Jul 25, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [57da61c80c](https://bsd-hardware.info/?probe=57da61c80c) | Jul 17, 2022 |
| PC Engines    | apu4                        | Desktop     | [4e24f7aa5b](https://bsd-hardware.info/?probe=4e24f7aa5b) | Jul 15, 2022 |
| Deciso        | Netboard A10 GEN2 Model ... | Desktop     | [bfbac4efa5](https://bsd-hardware.info/?probe=bfbac4efa5) | Jul 05, 2022 |
| Secudos       | Unknown                     | Desktop     | [beaf8ea459](https://bsd-hardware.info/?probe=beaf8ea459) | Jul 04, 2022 |
| Secudos       | Unknown                     | Desktop     | [e54c622459](https://bsd-hardware.info/?probe=e54c622459) | Jul 04, 2022 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | Desktop     | [e68d7a5dff](https://bsd-hardware.info/?probe=e68d7a5dff) | Jun 29, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [f573327012](https://bsd-hardware.info/?probe=f573327012) | Jun 29, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [f68b48b102](https://bsd-hardware.info/?probe=f68b48b102) | Jun 28, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [86bac086b3](https://bsd-hardware.info/?probe=86bac086b3) | Jun 27, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [153c93c827](https://bsd-hardware.info/?probe=153c93c827) | Jun 20, 2022 |
| Fujitsu       | LIFEBOOK A555               | Notebook    | [23d96bc669](https://bsd-hardware.info/?probe=23d96bc669) | Jun 11, 2022 |
| PC Engines    | APU2                        | Desktop     | [b296296b84](https://bsd-hardware.info/?probe=b296296b84) | Jun 10, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [bfe11a7156](https://bsd-hardware.info/?probe=bfe11a7156) | Jun 01, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [9c86650e6a](https://bsd-hardware.info/?probe=9c86650e6a) | Jun 01, 2022 |
| MSI           | MS-6788                     | Desktop     | [f750cb83e3](https://bsd-hardware.info/?probe=f750cb83e3) | May 31, 2022 |
| Dell          | 055H3G A01                  | Desktop     | [cc1c76afc0](https://bsd-hardware.info/?probe=cc1c76afc0) | May 24, 2022 |
| Shuttle       | DS10U                       | Desktop     | [573358361a](https://bsd-hardware.info/?probe=573358361a) | May 22, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [02f79b14cb](https://bsd-hardware.info/?probe=02f79b14cb) | May 20, 2022 |
| PC Engines    | APU2                        | Desktop     | [7132ae8216](https://bsd-hardware.info/?probe=7132ae8216) | May 19, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [f658f57d9a](https://bsd-hardware.info/?probe=f658f57d9a) | May 12, 2022 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [d97560d02b](https://bsd-hardware.info/?probe=d97560d02b) | May 08, 2022 |
| BESSTAR Te... | U820                        | Notebook    | [6f2aa2d02a](https://bsd-hardware.info/?probe=6f2aa2d02a) | May 07, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [7a43bfada9](https://bsd-hardware.info/?probe=7a43bfada9) | Apr 23, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [4ad1c07aa5](https://bsd-hardware.info/?probe=4ad1c07aa5) | Apr 19, 2022 |
| PC Engines    | apu4                        | Desktop     | [beb62ed999](https://bsd-hardware.info/?probe=beb62ed999) | Apr 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [4d52408404](https://bsd-hardware.info/?probe=4d52408404) | Apr 04, 2022 |
| Dell          | 096JG8 A01                  | Desktop     | [7ee68eb371](https://bsd-hardware.info/?probe=7ee68eb371) | Apr 02, 2022 |
| Dell          | 096JG8 A01                  | Desktop     | [657c893958](https://bsd-hardware.info/?probe=657c893958) | Apr 02, 2022 |
| PC Engines    | APU2                        | Desktop     | [5aef21bfc3](https://bsd-hardware.info/?probe=5aef21bfc3) | Mar 26, 2022 |
| Secudos       | Unknown                     | Desktop     | [970e9962ff](https://bsd-hardware.info/?probe=970e9962ff) | Mar 24, 2022 |
| ZOTAC         | ZBOX-CI341                  | Mini pc     | [fc5d42c3b7](https://bsd-hardware.info/?probe=fc5d42c3b7) | Mar 21, 2022 |
| PC Engines    | apu4                        | Desktop     | [395eb04c69](https://bsd-hardware.info/?probe=395eb04c69) | Mar 14, 2022 |
| Lenovo        | ThinkPad T410 2537WEE       | Notebook    | [973ade9e4a](https://bsd-hardware.info/?probe=973ade9e4a) | Mar 07, 2022 |
| PC Engines    | APU2                        | Desktop     | [c5ed9017c3](https://bsd-hardware.info/?probe=c5ed9017c3) | Mar 05, 2022 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [59cee41440](https://bsd-hardware.info/?probe=59cee41440) | Mar 01, 2022 |
| Shuttle       | DS10U                       | Desktop     | [1300217458](https://bsd-hardware.info/?probe=1300217458) | Feb 28, 2022 |
| HP            | 805D                        | Desktop     | [4c07559a11](https://bsd-hardware.info/?probe=4c07559a11) | Feb 28, 2022 |
| PC Engines    | apu4                        | Desktop     | [606d9c838c](https://bsd-hardware.info/?probe=606d9c838c) | Feb 26, 2022 |
| PC Engines    | apu4                        | Desktop     | [8b42751f17](https://bsd-hardware.info/?probe=8b42751f17) | Feb 25, 2022 |
| Unknown       | Unknown                     | Desktop     | [96bae6432b](https://bsd-hardware.info/?probe=96bae6432b) | Feb 24, 2022 |
| Supermicro    | X11SBA-LN4F                 | Server      | [b64aeb3448](https://bsd-hardware.info/?probe=b64aeb3448) | Feb 23, 2022 |
| Shuttle       | FH170                       | Desktop     | [5fd212645c](https://bsd-hardware.info/?probe=5fd212645c) | Feb 18, 2022 |
| Dell          | 096JG8 A01                  | Desktop     | [6baeaf5d48](https://bsd-hardware.info/?probe=6baeaf5d48) | Feb 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [f172be6fb0](https://bsd-hardware.info/?probe=f172be6fb0) | Feb 17, 2022 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [f1dd03cdcb](https://bsd-hardware.info/?probe=f1dd03cdcb) | Feb 16, 2022 |
| Lenovo        | ThinkPad T400 2768W3A       | Desktop     | [4691fdb146](https://bsd-hardware.info/?probe=4691fdb146) | Feb 13, 2022 |
| Lenovo        | ThinkPad T400 2768W3A       | Desktop     | [97788dfb1a](https://bsd-hardware.info/?probe=97788dfb1a) | Feb 13, 2022 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | Desktop     | [0117d61d81](https://bsd-hardware.info/?probe=0117d61d81) | Feb 07, 2022 |
| Lenovo        | ThinkPad T510 4384AJ6       | Notebook    | [70a56029e7](https://bsd-hardware.info/?probe=70a56029e7) | Jan 31, 2022 |
| Dell          | 0NKW6Y A00                  | Desktop     | [1ea6d60d70](https://bsd-hardware.info/?probe=1ea6d60d70) | Jan 30, 2022 |
| HP            | 805D                        | Desktop     | [d7e312307f](https://bsd-hardware.info/?probe=d7e312307f) | Jan 30, 2022 |
| HP            | ProLiant DL360e Gen8        | Server      | [f97e208e22](https://bsd-hardware.info/?probe=f97e208e22) | Jan 30, 2022 |
| HP            | ProLiant DL360e Gen8        | Server      | [c2431ee491](https://bsd-hardware.info/?probe=c2431ee491) | Jan 30, 2022 |
| Unknown       | YL-J3160L4                  | Desktop     | [763dc53716](https://bsd-hardware.info/?probe=763dc53716) | Jan 28, 2022 |
| Lenovo        | Y50-70 20378                | Notebook    | [1feb455e8c](https://bsd-hardware.info/?probe=1feb455e8c) | Jan 25, 2022 |
| Lenovo        | 0B98401 WIN                 | Desktop     | [c5430f00cf](https://bsd-hardware.info/?probe=c5430f00cf) | Jan 22, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [d2d10a1ffc](https://bsd-hardware.info/?probe=d2d10a1ffc) | Jan 21, 2022 |
| Dell          | Precision 7530              | Notebook    | [498bfe852c](https://bsd-hardware.info/?probe=498bfe852c) | Jan 07, 2022 |
| Biostar       | N3050NH                     | Desktop     | [31e33326fa](https://bsd-hardware.info/?probe=31e33326fa) | Jan 06, 2022 |
| Gigabyte      | B150-HD3P-CF                | Desktop     | [9752eae10b](https://bsd-hardware.info/?probe=9752eae10b) | Jan 06, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [6c208c85a5](https://bsd-hardware.info/?probe=6c208c85a5) | Jan 06, 2022 |
| ZOTAC         | ZBOXNANO-ID63/ID64/ID65     | Mini pc     | [d8d2cea545](https://bsd-hardware.info/?probe=d8d2cea545) | Jan 05, 2022 |
| Fujitsu       | D3164-C2 S26361-D3164-C2    | Desktop     | [765210be77](https://bsd-hardware.info/?probe=765210be77) | Dec 28, 2021 |
| Unknown       | Unknown                     | Notebook    | [db4d12babd](https://bsd-hardware.info/?probe=db4d12babd) | Dec 23, 2021 |
| Purism        | Librem Mini v2              | Desktop     | [528ef01c87](https://bsd-hardware.info/?probe=528ef01c87) | Dec 20, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [b872e9b044](https://bsd-hardware.info/?probe=b872e9b044) | Dec 18, 2021 |
| Unknown       | Unknown                     | Notebook    | [eab0d6c6d3](https://bsd-hardware.info/?probe=eab0d6c6d3) | Dec 12, 2021 |
| HP            | 805D                        | Desktop     | [324b4670b6](https://bsd-hardware.info/?probe=324b4670b6) | Dec 12, 2021 |
| Unknown       | Unknown                     | Desktop     | [943365b2f1](https://bsd-hardware.info/?probe=943365b2f1) | Dec 11, 2021 |
| BESSTAR Te... | IB9                         | Desktop     | [26717d3708](https://bsd-hardware.info/?probe=26717d3708) | Dec 10, 2021 |
| HP            | 3397                        | Desktop     | [ac295c89b0](https://bsd-hardware.info/?probe=ac295c89b0) | Dec 05, 2021 |
| Protectli     | FW6E                        | Desktop     | [3ddd9d297c](https://bsd-hardware.info/?probe=3ddd9d297c) | Dec 02, 2021 |
| Unknown       | Unknown                     | Notebook    | [6d1fb7b4bb](https://bsd-hardware.info/?probe=6d1fb7b4bb) | Nov 27, 2021 |
| Gigabyte      | B365M DS3H                  | Desktop     | [69194e4ead](https://bsd-hardware.info/?probe=69194e4ead) | Nov 23, 2021 |
| HP            | ProLiant DL360e Gen8        | Server      | [d12db83eb6](https://bsd-hardware.info/?probe=d12db83eb6) | Nov 13, 2021 |
| PC Engines    | APU2                        | Desktop     | [9a262221d5](https://bsd-hardware.info/?probe=9a262221d5) | Nov 03, 2021 |
| Winston Ma... | PICO PC  PICOPC             | Desktop     | [55a9e67b4c](https://bsd-hardware.info/?probe=55a9e67b4c) | Oct 26, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [087d40ba7c](https://bsd-hardware.info/?probe=087d40ba7c) | Oct 19, 2021 |
| BESSTAR Te... | UM270 V1.0                  | Desktop     | [aa7ee48846](https://bsd-hardware.info/?probe=aa7ee48846) | Oct 19, 2021 |
| PC Engines    | APU2                        | Desktop     | [6580ee2c23](https://bsd-hardware.info/?probe=6580ee2c23) | Oct 19, 2021 |
| HP            | 805D                        | Desktop     | [b61f6f9d52](https://bsd-hardware.info/?probe=b61f6f9d52) | Oct 16, 2021 |
| ASRock        | B460M Pro4                  | Desktop     | [e0fbe78c7e](https://bsd-hardware.info/?probe=e0fbe78c7e) | Oct 14, 2021 |
| ASRock        | H510M-HDV/M.2               | Desktop     | [39c65baf01](https://bsd-hardware.info/?probe=39c65baf01) | Oct 14, 2021 |
| Silicom       | MinnowBoard Turbot          | Desktop     | [0c6c98cbd3](https://bsd-hardware.info/?probe=0c6c98cbd3) | Oct 09, 2021 |
| ASUSTek       | P11C-I Series               | Desktop     | [2690a544a5](https://bsd-hardware.info/?probe=2690a544a5) | Sep 29, 2021 |
| Shuttle       | DS10U                       | Desktop     | [6f5d8afb4b](https://bsd-hardware.info/?probe=6f5d8afb4b) | Sep 29, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [ad178dbed0](https://bsd-hardware.info/?probe=ad178dbed0) | Sep 13, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [bf9b083102](https://bsd-hardware.info/?probe=bf9b083102) | Sep 08, 2021 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | Notebook    | [62f9376847](https://bsd-hardware.info/?probe=62f9376847) | Sep 04, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [5147f5734d](https://bsd-hardware.info/?probe=5147f5734d) | Sep 04, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [2e8b641cc4](https://bsd-hardware.info/?probe=2e8b641cc4) | Sep 04, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [d6fb115604](https://bsd-hardware.info/?probe=d6fb115604) | Aug 21, 2021 |
| Shuttle       | DS10U                       | Desktop     | [7e11cc28f5](https://bsd-hardware.info/?probe=7e11cc28f5) | Aug 19, 2021 |
| HP            | 1495                        | Desktop     | [d7e136e07f](https://bsd-hardware.info/?probe=d7e136e07f) | Aug 11, 2021 |
| PC Engines    | apu4                        | Desktop     | [f6d199de58](https://bsd-hardware.info/?probe=f6d199de58) | Aug 08, 2021 |
| HP            | 1495                        | Desktop     | [4dfe9896c4](https://bsd-hardware.info/?probe=4dfe9896c4) | Aug 04, 2021 |
| Silicom       | MinnowBoard Turbot          | Desktop     | [6defda405f](https://bsd-hardware.info/?probe=6defda405f) | Aug 02, 2021 |
| Shuttle       | FH170                       | Desktop     | [0c381808eb](https://bsd-hardware.info/?probe=0c381808eb) | Aug 02, 2021 |
| Supermicro    | X11SBA-LN4F                 | Server      | [2030131cb8](https://bsd-hardware.info/?probe=2030131cb8) | Jul 31, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [eb75d5e2a3](https://bsd-hardware.info/?probe=eb75d5e2a3) | Jul 29, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [1d117c1c21](https://bsd-hardware.info/?probe=1d117c1c21) | Jul 28, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [e91c7fa2c8](https://bsd-hardware.info/?probe=e91c7fa2c8) | Jul 26, 2021 |
| NEXCOM        | NSA3110 B                   | Desktop     | [4f532bbd9e](https://bsd-hardware.info/?probe=4f532bbd9e) | Jul 25, 2021 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [d26a6c8990](https://bsd-hardware.info/?probe=d26a6c8990) | Jul 24, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [c1c721ac0b](https://bsd-hardware.info/?probe=c1c721ac0b) | Jul 16, 2021 |
| Shuttle       | DS10U                       | Desktop     | [746d0761cc](https://bsd-hardware.info/?probe=746d0761cc) | Jul 16, 2021 |
| Supermicro    | X11SDV-4C-TP8F              | Server      | [0b9c25527f](https://bsd-hardware.info/?probe=0b9c25527f) | Jul 09, 2021 |
| Dell          | 0T7D40 A01                  | Desktop     | [f67d589e29](https://bsd-hardware.info/?probe=f67d589e29) | Jul 08, 2021 |
| Dell          | 0T7D40 A01                  | Desktop     | [d39de0c0dc](https://bsd-hardware.info/?probe=d39de0c0dc) | Jun 30, 2021 |
| BESSTAR Te... | IB9                         | Desktop     | [1c8c267ce2](https://bsd-hardware.info/?probe=1c8c267ce2) | Jun 20, 2021 |
| HP            | 1495                        | Desktop     | [572b748256](https://bsd-hardware.info/?probe=572b748256) | Jun 10, 2021 |
| BESSTAR Te... | IB9                         | Desktop     | [f152e4b3e7](https://bsd-hardware.info/?probe=f152e4b3e7) | Jun 10, 2021 |
| HPE           | ProLiant MicroServer Gen... | Server      | [c42933f9fd](https://bsd-hardware.info/?probe=c42933f9fd) | Jun 01, 2021 |
| HP            | 3397                        | Desktop     | [ab3fc66a9e](https://bsd-hardware.info/?probe=ab3fc66a9e) | May 20, 2021 |
| HP            | 1495                        | Desktop     | [3d2d524163](https://bsd-hardware.info/?probe=3d2d524163) | May 19, 2021 |
| HP            | 3397                        | Desktop     | [5d2d602907](https://bsd-hardware.info/?probe=5d2d602907) | May 19, 2021 |
| Protectli     | FW4B                        | Desktop     | [1a8296fffd](https://bsd-hardware.info/?probe=1a8296fffd) | May 15, 2021 |
| Protectli     | FW4B                        | Desktop     | [47aa4d946c](https://bsd-hardware.info/?probe=47aa4d946c) | May 14, 2021 |
| Gigabyte      | B365M DS3H                  | Desktop     | [b77ceeed88](https://bsd-hardware.info/?probe=b77ceeed88) | May 14, 2021 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [b3acafeb1a](https://bsd-hardware.info/?probe=b3acafeb1a) | May 09, 2021 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [86cec3b874](https://bsd-hardware.info/?probe=86cec3b874) | May 09, 2021 |
| Unknown       | Unknown                     | Desktop     | [2d8cb88aa7](https://bsd-hardware.info/?probe=2d8cb88aa7) | May 03, 2021 |
| Unknown       | SKYBAY                      | Desktop     | [34073c7322](https://bsd-hardware.info/?probe=34073c7322) | Apr 21, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [e1837571df](https://bsd-hardware.info/?probe=e1837571df) | Apr 15, 2021 |
| Shuttle       | DS10U                       | Desktop     | [491a0135a0](https://bsd-hardware.info/?probe=491a0135a0) | Apr 14, 2021 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | Desktop     | [478a874db2](https://bsd-hardware.info/?probe=478a874db2) | Apr 09, 2021 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [fd03138dfc](https://bsd-hardware.info/?probe=fd03138dfc) | Apr 08, 2021 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [f8d08a1ec0](https://bsd-hardware.info/?probe=f8d08a1ec0) | Apr 08, 2021 |
| Sophos        | SG                          | Firewall    | [31f0629346](https://bsd-hardware.info/?probe=31f0629346) | Apr 07, 2021 |
| HP            | 8054                        | Desktop     | [ab00142638](https://bsd-hardware.info/?probe=ab00142638) | Apr 07, 2021 |
| BESSTAR Te... | UM250 V1.0                  | Desktop     | [ec9c1e37db](https://bsd-hardware.info/?probe=ec9c1e37db) | Apr 07, 2021 |
| Shuttle       | DS10U                       | Desktop     | [bd2ea41c3d](https://bsd-hardware.info/?probe=bd2ea41c3d) | Apr 05, 2021 |
| BESSTAR Te... | IB9                         | Desktop     | [202b90b7bf](https://bsd-hardware.info/?probe=202b90b7bf) | Apr 02, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [57de8a523c](https://bsd-hardware.info/?probe=57de8a523c) | Mar 29, 2021 |
| Intel         | S5000PSL                    | Server      | [411f470773](https://bsd-hardware.info/?probe=411f470773) | Mar 18, 2021 |
| PC Engines    | APU2                        | Desktop     | [e578d2eadd](https://bsd-hardware.info/?probe=e578d2eadd) | Mar 17, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [e3f20f8770](https://bsd-hardware.info/?probe=e3f20f8770) | Mar 17, 2021 |
| Supermicro    | X10SRA-F                    | Server      | [14a919ab3f](https://bsd-hardware.info/?probe=14a919ab3f) | Mar 17, 2021 |
| HP            | 3397                        | Desktop     | [4e4f84fe7e](https://bsd-hardware.info/?probe=4e4f84fe7e) | Mar 17, 2021 |
| PC Engines    | APU2                        | Desktop     | [70050ec377](https://bsd-hardware.info/?probe=70050ec377) | Mar 16, 2021 |
| Unknown       | SKYBAY                      | Desktop     | [e44d5add26](https://bsd-hardware.info/?probe=e44d5add26) | Mar 16, 2021 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [50caf95a09](https://bsd-hardware.info/?probe=50caf95a09) | Mar 15, 2021 |
| Shuttle       | DS10U                       | Desktop     | [8e895a4efd](https://bsd-hardware.info/?probe=8e895a4efd) | Mar 15, 2021 |
| Shuttle       | DS10U                       | Desktop     | [8fe918937b](https://bsd-hardware.info/?probe=8fe918937b) | Mar 15, 2021 |
| Unknown       | SKYBAY                      | Desktop     | [0cae097db1](https://bsd-hardware.info/?probe=0cae097db1) | Mar 14, 2021 |
| Panasonic     | CF-30KTP48NL                | Notebook    | [119b4875e9](https://bsd-hardware.info/?probe=119b4875e9) | Mar 12, 2021 |
| HP            | ProLiant DL360 G6           | Server      | [a8b43ed394](https://bsd-hardware.info/?probe=a8b43ed394) | Mar 10, 2021 |
| Unknown       | Unknown                     | Desktop     | [155c42b4b5](https://bsd-hardware.info/?probe=155c42b4b5) | Mar 08, 2021 |
| Intel         | S5000PSL                    | Server      | [ccf8f22e7c](https://bsd-hardware.info/?probe=ccf8f22e7c) | Mar 08, 2021 |
| Unknown       | J3160-4L                    | Desktop     | [0390ce8498](https://bsd-hardware.info/?probe=0390ce8498) | Mar 06, 2021 |
| ZOTAC         | ZBOX-CI527/CI547NANO        | Mini pc     | [6ca50f8007](https://bsd-hardware.info/?probe=6ca50f8007) | Mar 06, 2021 |
| Supermicro    | X11SBA-LN4F                 | Server      | [9479fdf6dd](https://bsd-hardware.info/?probe=9479fdf6dd) | Mar 06, 2021 |
| HP            | 3397                        | Desktop     | [f53c2d8ded](https://bsd-hardware.info/?probe=f53c2d8ded) | Mar 01, 2021 |
| HP            | 3397                        | Desktop     | [901050fb80](https://bsd-hardware.info/?probe=901050fb80) | Feb 26, 2021 |
| ZOTAC         | ZBOX-CI341                  | Mini pc     | [e7a255c3aa](https://bsd-hardware.info/?probe=e7a255c3aa) | Feb 20, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [1439878133](https://bsd-hardware.info/?probe=1439878133) | Feb 12, 2021 |
| ZOTAC         | ZBOX-CI341                  | Mini pc     | [ae36e30e53](https://bsd-hardware.info/?probe=ae36e30e53) | Feb 08, 2021 |
| AAEON         | UP-APL01 V0.4               | Desktop     | [8fc8c1d27e](https://bsd-hardware.info/?probe=8fc8c1d27e) | Jan 31, 2021 |
| Dell          | Vostro V131                 | Notebook    | [897616d9c8](https://bsd-hardware.info/?probe=897616d9c8) | Jan 31, 2021 |
| Supermicro    | X11SBA-FA                   | Server      | [53c6203cec](https://bsd-hardware.info/?probe=53c6203cec) | Jan 27, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [93e276fc9b](https://bsd-hardware.info/?probe=93e276fc9b) | Jan 26, 2021 |
| HP            | ProLiant DL360p Gen8        | Server      | [1e629d4c5a](https://bsd-hardware.info/?probe=1e629d4c5a) | Jan 26, 2021 |
| Dell          | Vostro V131                 | Notebook    | [630822a6a1](https://bsd-hardware.info/?probe=630822a6a1) | Jan 25, 2021 |
| Protectli     | FW4B                        | Desktop     | [0a02b075ac](https://bsd-hardware.info/?probe=0a02b075ac) | Jan 24, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [1a07b34622](https://bsd-hardware.info/?probe=1a07b34622) | Jan 22, 2021 |
| PC Engines    | apu4                        | Desktop     | [e7fcefa741](https://bsd-hardware.info/?probe=e7fcefa741) | Jan 21, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [64254af8aa](https://bsd-hardware.info/?probe=64254af8aa) | Jan 20, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [3bd99c74b9](https://bsd-hardware.info/?probe=3bd99c74b9) | Jan 20, 2021 |
| HP            | ZBook 17 G4                 | Notebook    | [40ad0612de](https://bsd-hardware.info/?probe=40ad0612de) | Jan 02, 2021 |
| Acer          | TravelMate Spin B118-RN     | Convertible | [c3acc4d372](https://bsd-hardware.info/?probe=c3acc4d372) | Dec 21, 2020 |
| Supermicro    | X10SDV-TLN4F                | Server      | [8ab697e7dd](https://bsd-hardware.info/?probe=8ab697e7dd) | Dec 15, 2020 |
| HUAWEI        | BC11HGSA0 V100R003          | Server      | [ac2c7107d3](https://bsd-hardware.info/?probe=ac2c7107d3) | Nov 19, 2020 |
| Acer          | TravelMate Spin B118-RN     | Convertible | [41c071ead3](https://bsd-hardware.info/?probe=41c071ead3) | Nov 03, 2020 |
| HP            | ProLiant SE326M1R2          | Server      | [e59d5d41a5](https://bsd-hardware.info/?probe=e59d5d41a5) | Oct 29, 2020 |
| HP            | ProLiant DL360 G6           | Server      | [e523287429](https://bsd-hardware.info/?probe=e523287429) | Oct 29, 2020 |
| Unknown       | Unknown                     | Desktop     | [e69210e453](https://bsd-hardware.info/?probe=e69210e453) | Oct 29, 2020 |
| Lenovo        | ThinkPad T410 2537AT1       | Notebook    | [4e693bfcb2](https://bsd-hardware.info/?probe=4e693bfcb2) | Oct 29, 2020 |
| ASRock        | TRX40 Taichi                | Desktop     | [dda9a512ac](https://bsd-hardware.info/?probe=dda9a512ac) | Oct 29, 2020 |
| Dell          | PowerEdge 1950              | Desktop     | [3cfcdfce6d](https://bsd-hardware.info/?probe=3cfcdfce6d) | Oct 19, 2020 |
| Dell          | PowerEdge 1950              | Desktop     | [0865193e7e](https://bsd-hardware.info/?probe=0865193e7e) | Oct 19, 2020 |
| Dell          | PowerEdge R610              | Desktop     | [2ea539bbd3](https://bsd-hardware.info/?probe=2ea539bbd3) | Oct 19, 2020 |
| PC Engines    | APU2                        | Desktop     | [2ab3051cb8](https://bsd-hardware.info/?probe=2ab3051cb8) | Oct 19, 2020 |
| PC Engines    | apu4                        | Desktop     | [f0116986e0](https://bsd-hardware.info/?probe=f0116986e0) | Oct 19, 2020 |
| Dell          | Latitude E7440              | Notebook    | [acd2735dc4](https://bsd-hardware.info/?probe=acd2735dc4) | Aug 07, 2020 |
| HP            | EliteBook 840 G3            | Notebook    | [71c35a9cc2](https://bsd-hardware.info/?probe=71c35a9cc2) | Aug 06, 2020 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [be9c9d6b01](https://bsd-hardware.info/?probe=be9c9d6b01) | Aug 01, 2020 |
| HP            | EliteBook 840 G3            | Notebook    | [6c7374d0ab](https://bsd-hardware.info/?probe=6c7374d0ab) | May 29, 2020 |
| Lenovo        | ThinkPad T60 2007J3G        | Notebook    | [ee60eb3dc8](https://bsd-hardware.info/?probe=ee60eb3dc8) | May 25, 2020 |
| Dell          | XPS 13 9360                 | Notebook    | [152f5cda4c](https://bsd-hardware.info/?probe=152f5cda4c) | May 23, 2020 |
| Fujitsu       | D3049-A1 S26361-D3049-A1... | Server      | [6cf7f9ea4b](https://bsd-hardware.info/?probe=6cf7f9ea4b) | May 23, 2020 |
| Dell          | XPS 13 9360                 | Notebook    | [d350b44569](https://bsd-hardware.info/?probe=d350b44569) | May 23, 2020 |
| Dell          | XPS 13 9360                 | Notebook    | [4199e37b56](https://bsd-hardware.info/?probe=4199e37b56) | May 23, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| OPNsense 21.7.3      | 9         | 5.33%   |
| OPNsense 22.1.1      | 8         | 4.73%   |
| OPNsense 21.7.7      | 7         | 4.14%   |
| OPNsense 21.1.4      | 6         | 3.55%   |
| OPNsense 20.7.8      | 6         | 3.55%   |
| OPNsense 22.1        | 5         | 2.96%   |
| OPNsense 21.7.6      | 5         | 2.96%   |
| OPNsense 21.1.5      | 5         | 2.96%   |
| OPNsense 21.1.3      | 5         | 2.96%   |
| OPNsense 21.1.2      | 5         | 2.96%   |
| OPNsense 21.1        | 5         | 2.96%   |
| OpenBSD 6.8          | 5         | 2.96%   |
| FreeBSD 13.1         | 5         | 2.96%   |
| OPNsense 22.1.9      | 4         | 2.37%   |
| OPNsense 22.1.7      | 4         | 2.37%   |
| OPNsense 22.1.4      | 4         | 2.37%   |
| OPNsense 21.7        | 4         | 2.37%   |
| OPNsense 21.1.8      | 4         | 2.37%   |
| FreeBSD 14.0-CURRENT | 4         | 2.37%   |
| OPNsense 22.7.2      | 3         | 1.78%   |
| OPNsense 22.1.10     | 3         | 1.78%   |
| OPNsense 21.7.8      | 3         | 1.78%   |
| OPNsense 21.1.1      | 3         | 1.78%   |
| FreeBSD 12.2         | 3         | 1.78%   |
| FreeBSD 12.1-p10     | 3         | 1.78%   |
| OPNsense 22.7        | 2         | 1.18%   |
| OPNsense 22.4.3      | 2         | 1.18%   |
| OPNsense 22.4.1      | 2         | 1.18%   |
| OPNsense 22.1.6      | 2         | 1.18%   |
| OPNsense 22.1.2      | 2         | 1.18%   |
| OPNsense 21.7.5      | 2         | 1.18%   |
| OPNsense 21.7.1      | 2         | 1.18%   |
| OPNsense 21.1.9      | 2         | 1.18%   |
| OpenBSD 7.1          | 2         | 1.18%   |
| FreeNAS 11.3-p7      | 2         | 1.18%   |
| FreeBSD 13.0-p5      | 2         | 1.18%   |
| FreeBSD 13.0-p4      | 2         | 1.18%   |
| FreeBSD 13.0-p3      | 2         | 1.18%   |
| FreeBSD 12.1-p8      | 2         | 1.18%   |
| FreeBSD 12.1-p5      | 2         | 1.18%   |
| OPNsense 22.4.2      | 1         | 0.59%   |
| OPNsense 22.1.8      | 1         | 0.59%   |
| OPNsense 22.1.3      | 1         | 0.59%   |
| OPNsense 21.7.4      | 1         | 0.59%   |
| OPNsense 21.7.2      | 1         | 0.59%   |
| OPNsense 21.1.7      | 1         | 0.59%   |
| OPNsense 21.1.6      | 1         | 0.59%   |
| OpenBSD 7.0          | 1         | 0.59%   |
| helloSystem 0.7.0    | 1         | 0.59%   |
| helloSystem 0.5.0    | 1         | 0.59%   |
| FreeNAS 11.3-p8      | 1         | 0.59%   |
| FreeBSD 13.0-RC2     | 1         | 0.59%   |
| FreeBSD 13.0-p11     | 1         | 0.59%   |
| FreeBSD 13.0-p1      | 1         | 0.59%   |
| FreeBSD 13.0-CURRENT | 1         | 0.59%   |
| FreeBSD 13.0         | 1         | 0.59%   |
| FreeBSD 12.3         | 1         | 0.59%   |
| FreeBSD 12.2-p5      | 1         | 0.59%   |
| FreeBSD 12.1-p7      | 1         | 0.59%   |
| FreeBSD 12.1-p4      | 1         | 0.59%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 92        | 67.65%  |
| FreeBSD     | 31        | 22.79%  |
| OpenBSD     | 8         | 5.88%   |
| FreeNAS     | 3         | 2.21%   |
| helloSystem | 2         | 1.47%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 134       | 98.53%  |
| i386  | 1         | 0.74%   |
| arm64 | 1         | 0.74%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 105       | 76.09%  |
| KDE5         | 10        | 7.25%   |
| XFCE         | 4         | 2.9%    |
| helloDesktop | 4         | 2.9%    |
| Cinnamon     | 3         | 2.17%   |
| MATE         | 2         | 1.45%   |
| LXQt         | 2         | 1.45%   |
| fvwm         | 2         | 1.45%   |
| xinitrc      | 1         | 0.72%   |
| TWM          | 1         | 0.72%   |
| Openbox      | 1         | 0.72%   |
| Lumina       | 1         | 0.72%   |
| i3           | 1         | 0.72%   |
| GNOME        | 1         | 0.72%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 107       | 78.68%  |
| X11     | 28        | 20.59%  |
| Wayland | 1         | 0.74%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 116       | 84.67%  |
| SDDM    | 13        | 9.49%   |
| SLiM    | 3         | 2.19%   |
| LightDM | 3         | 2.19%   |
| XDM     | 1         | 0.73%   |
| GDM     | 1         | 0.73%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 107       | 76.43%  |
| C       | 14        | 10%     |
| en_US   | 13        | 9.29%   |
| de_DE   | 4         | 2.86%   |
| de_AT   | 1         | 0.71%   |
| cs_CZ   | 1         | 0.71%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 114       | 83.82%  |
| BIOS | 22        | 16.18%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ufs     | 81        | 59.12%  |
| Zfs     | 47        | 34.31%  |
| Ffs     | 8         | 5.84%   |
| Unknown | 1         | 0.73%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 123       | 90.44%  |
| MBR     | 9         | 6.62%   |
| Unknown | 4         | 2.94%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 16        | 11.76%  |
| Hewlett-Packard     | 14        | 10.29%  |
| Unknown             | 13        | 9.56%   |
| PC Engines          | 12        | 8.82%   |
| Dell                | 10        | 7.35%   |
| ZOTAC               | 6         | 4.41%   |
| Supermicro          | 5         | 3.68%   |
| Fujitsu             | 5         | 3.68%   |
| Protectli           | 4         | 2.94%   |
| Gigabyte Technology | 4         | 2.94%   |
| Deciso              | 4         | 2.94%   |
| BESSTAR Tech        | 4         | 2.94%   |
| AMI                 | 4         | 2.94%   |
| Shuttle             | 3         | 2.21%   |
| Intel               | 3         | 2.21%   |
| ASUSTek Computer    | 3         | 2.21%   |
| ASRock              | 3         | 2.21%   |
| Secudos             | 2         | 1.47%   |
| MW                  | 2         | 1.47%   |
| Biostar             | 2         | 1.47%   |
| AAEON               | 2         | 1.47%   |
| Winston Marriot     | 1         | 0.74%   |
| Sophos              | 1         | 0.74%   |
| Silicom             | 1         | 0.74%   |
| SeeedStudio         | 1         | 0.74%   |
| Seeed Studio        | 1         | 0.74%   |
| Purism              | 1         | 0.74%   |
| Panasonic           | 1         | 0.74%   |
| NEXCOM              | 1         | 0.74%   |
| MSI                 | 1         | 0.74%   |
| IP3 Tech            | 1         | 0.74%   |
| HUAWEI              | 1         | 0.74%   |
| HPE                 | 1         | 0.74%   |
| AWOW                | 1         | 0.74%   |
| Apple               | 1         | 0.74%   |
| Acer                | 1         | 0.74%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                             | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Unknown                                          | 15        | 11.03%  |
| PC Engines apu4                                  | 6         | 4.41%   |
| PC Engines APU2                                  | 6         | 4.41%   |
| Supermicro Super Server                          | 3         | 2.21%   |
| Protectli FW4B                                   | 3         | 2.21%   |
| Deciso Netboard A10 GEN2 Model G                 | 3         | 2.21%   |
| ZOTAC ZBOX-CI341                                 | 2         | 1.47%   |
| ZOTAC ZBOX-CI323NANO                             | 2         | 1.47%   |
| Shuttle DS10U                                    | 2         | 1.47%   |
| MW GMLK-2_5G4L                                   | 2         | 1.47%   |
| Lenovo ThinkPad T490 20N2CTO1WW                  | 2         | 1.47%   |
| Intel Q3XXG4-P V1.0                              | 2         | 1.47%   |
| HP ProLiant DL360 G6                             | 2         | 1.47%   |
| HP EliteBook 850 G7 Notebook PC                  | 2         | 1.47%   |
| Fujitsu ESPRIMO C720                             | 2         | 1.47%   |
| AMI LES compact 4L                               | 2         | 1.47%   |
| AMI Aptio CRB                                    | 2         | 1.47%   |
| AAEON UP-APL01                                   | 2         | 1.47%   |
| ZOTAC ZBOXNANO-ID63/ID64/ID65                    | 1         | 0.74%   |
| ZOTAC ZBOX-CI527/CI547NANO                       | 1         | 0.74%   |
| Winston Marriot PICO PC  PICOPC                  | 1         | 0.74%   |
| Supermicro IXWS-733TQ-665B-IXN                   | 1         | 0.74%   |
| Supermicro 1HE Intel Single-CPU RI1102D-F Server | 1         | 0.74%   |
| Sophos SG                                        | 1         | 0.74%   |
| Silicom Minnowboard Turbot D0/D1 PLATFORM        | 1         | 0.74%   |
| Shuttle DH170                                    | 1         | 0.74%   |
| SeeedStudio ODYSSEY-X86J4125                     | 1         | 0.74%   |
| Seeed Studio ODYSSEY-X86J4105                    | 1         | 0.74%   |
| Purism Librem Mini v2                            | 1         | 0.74%   |
| Protectli FW6E                                   | 1         | 0.74%   |
| Panasonic CF-30KTP48NL                           | 1         | 0.74%   |
| NEXCOM ASG                                       | 1         | 0.74%   |
| MSI MS-6788                                      | 1         | 0.74%   |
| Lenovo Y50-70 20378                              | 1         | 0.74%   |
| Lenovo ThinkPad T60 2007J3G                      | 1         | 0.74%   |
| Lenovo ThinkPad T510 4384AJ6                     | 1         | 0.74%   |
| Lenovo ThinkPad T410 2537WEE                     | 1         | 0.74%   |
| Lenovo ThinkPad T410 2537AT1                     | 1         | 0.74%   |
| Lenovo ThinkPad T400 2768W3A                     | 1         | 0.74%   |
| Lenovo ThinkPad E15 Gen 3 20YG006GGE             | 1         | 0.74%   |
| Lenovo ThinkPad E14 Gen 3 20Y7003SGE             | 1         | 0.74%   |
| Lenovo ThinkCentre M93p 10AB003CGE               | 1         | 0.74%   |
| Lenovo ThinkCentre M92P 3237CK4                  | 1         | 0.74%   |
| Lenovo ThinkCentre M73 10B4S03V05                | 1         | 0.74%   |
| Lenovo IdeaPad 110S-11IBR 80WG                   | 1         | 0.74%   |
| Lenovo IdeaCentre 310S-08ASR 90G9002PGE          | 1         | 0.74%   |
| Lenovo IdeaCentre 3 07ADA05 90MV007UGE           | 1         | 0.74%   |
| IP3 Tech CoreBox Pro                             | 1         | 0.74%   |
| Intel S5000PSL                                   | 1         | 0.74%   |
| HUAWEI RH2288H V3                                | 1         | 0.74%   |
| HPE ProLiant MicroServer Gen10                   | 1         | 0.74%   |
| HP ZBook 17 G4                                   | 1         | 0.74%   |
| HP ProLiant SE326M1R2                            | 1         | 0.74%   |
| HP ProLiant DL360p Gen8                          | 1         | 0.74%   |
| HP ProLiant DL360e Gen8                          | 1         | 0.74%   |
| HP ProDesk 600 G2 SFF                            | 1         | 0.74%   |
| HP EliteDesk 800 G2 SFF                          | 1         | 0.74%   |
| HP EliteBook Folio 9470m                         | 1         | 0.74%   |
| HP EliteBook 840 G3                              | 1         | 0.74%   |
| HP Compaq Elite 8300 SFF                         | 1         | 0.74%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Unknown                        | 15        | 11.03%  |
| Lenovo ThinkPad                | 9         | 6.62%   |
| PC Engines apu4                | 6         | 4.41%   |
| PC Engines APU2                | 6         | 4.41%   |
| HP ProLiant                    | 5         | 3.68%   |
| HP EliteBook                   | 4         | 2.94%   |
| Dell OptiPlex                  | 4         | 2.94%   |
| Supermicro Super               | 3         | 2.21%   |
| Protectli FW4B                 | 3         | 2.21%   |
| Lenovo ThinkCentre             | 3         | 2.21%   |
| Fujitsu ESPRIMO                | 3         | 2.21%   |
| Deciso Netboard                | 3         | 2.21%   |
| ZOTAC ZBOX-CI341               | 2         | 1.47%   |
| ZOTAC ZBOX-CI323NANO           | 2         | 1.47%   |
| Shuttle DS10U                  | 2         | 1.47%   |
| MW GMLK-2                      | 2         | 1.47%   |
| Lenovo IdeaCentre              | 2         | 1.47%   |
| Intel Q3XXG4-P                 | 2         | 1.47%   |
| HP Compaq                      | 2         | 1.47%   |
| Dell PowerEdge                 | 2         | 1.47%   |
| AMI LES                        | 2         | 1.47%   |
| AMI Aptio                      | 2         | 1.47%   |
| AAEON UP-APL01                 | 2         | 1.47%   |
| ZOTAC ZBOXNANO-ID63            | 1         | 0.74%   |
| ZOTAC ZBOX-CI527               | 1         | 0.74%   |
| Winston Marriot PICO           | 1         | 0.74%   |
| Supermicro IXWS-733TQ-665B-IXN | 1         | 0.74%   |
| Supermicro 1HE                 | 1         | 0.74%   |
| Sophos SG                      | 1         | 0.74%   |
| Silicom Minnowboard            | 1         | 0.74%   |
| Shuttle DH170                  | 1         | 0.74%   |
| SeeedStudio ODYSSEY-X86J4125   | 1         | 0.74%   |
| Seeed Studio ODYSSEY-X86J4105  | 1         | 0.74%   |
| Purism Librem                  | 1         | 0.74%   |
| Protectli FW6E                 | 1         | 0.74%   |
| Panasonic CF-30KTP48NL         | 1         | 0.74%   |
| NEXCOM ASG                     | 1         | 0.74%   |
| MSI MS-6788                    | 1         | 0.74%   |
| Lenovo Y50-70                  | 1         | 0.74%   |
| Lenovo IdeaPad                 | 1         | 0.74%   |
| IP3 Tech CoreBox               | 1         | 0.74%   |
| Intel S5000PSL                 | 1         | 0.74%   |
| HUAWEI RH2288H                 | 1         | 0.74%   |
| HPE ProLiant                   | 1         | 0.74%   |
| HP ZBook                       | 1         | 0.74%   |
| HP ProDesk                     | 1         | 0.74%   |
| HP EliteDesk                   | 1         | 0.74%   |
| Gigabyte H87-HD3               | 1         | 0.74%   |
| Gigabyte H81M-S2PV             | 1         | 0.74%   |
| Gigabyte B365M                 | 1         | 0.74%   |
| Gigabyte B150-HD3P-CF          | 1         | 0.74%   |
| Fujitsu PRIMERGY               | 1         | 0.74%   |
| Fujitsu LIFEBOOK               | 1         | 0.74%   |
| Dell XPS                       | 1         | 0.74%   |
| Dell Vostro                    | 1         | 0.74%   |
| Dell Precision                 | 1         | 0.74%   |
| Dell Latitude                  | 1         | 0.74%   |
| Deciso NetBoard-A10            | 1         | 0.74%   |
| Biostar N3050NH                | 1         | 0.74%   |
| Biostar A10N-8800E             | 1         | 0.74%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 19        | 13.97%  |
| 2020    | 18        | 13.24%  |
| 2021    | 17        | 12.5%   |
| 2019    | 15        | 11.03%  |
| 2016    | 15        | 11.03%  |
| 2017    | 13        | 9.56%   |
| 2015    | 8         | 5.88%   |
| 2013    | 6         | 4.41%   |
| 2010    | 6         | 4.41%   |
| 2011    | 5         | 3.68%   |
| 2022    | 3         | 2.21%   |
| 2012    | 3         | 2.21%   |
| Unknown | 3         | 2.21%   |
| 2009    | 2         | 1.47%   |
| 2014    | 1         | 0.74%   |
| 2007    | 1         | 0.74%   |
| 2006    | 1         | 0.74%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 82        | 60.29%  |
| Notebook       | 24        | 17.65%  |
| Server         | 14        | 10.29%  |
| Mini pc        | 12        | 8.82%   |
| System on chip | 1         | 0.74%   |
| Firewall       | 1         | 0.74%   |
| Convertible    | 1         | 0.74%   |
| All in one     | 1         | 0.74%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 118       | 86.76%  |
| Yes  | 18        | 13.24%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 53        | 38.69%  |
| 16.01-24.0      | 28        | 20.44%  |
| 4.01-8.0        | 27        | 19.71%  |
| 32.01-64.0      | 10        | 7.3%    |
| 2.01-3.0        | 7         | 5.11%   |
| 64.01-256.0     | 4         | 2.92%   |
| More than 256.0 | 3         | 2.19%   |
| 3.01-4.0        | 3         | 2.19%   |
| 24.01-32.0      | 1         | 0.73%   |
| 1.01-2.0        | 1         | 0.73%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 74        | 53.24%  |
| 0.51-1.0    | 38        | 27.34%  |
| 1.01-2.0    | 13        | 9.35%   |
| 2.01-3.0    | 4         | 2.88%   |
| 4.01-8.0    | 3         | 2.16%   |
| 32.01-64.0  | 3         | 2.16%   |
| 3.01-4.0    | 1         | 0.72%   |
| 64.01-256.0 | 1         | 0.72%   |
| 16.01-24.0  | 1         | 0.72%   |
| 0           | 1         | 0.72%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 107       | 76.98%  |
| 2      | 14        | 10.07%  |
| 0      | 8         | 5.76%   |
| 4      | 3         | 2.16%   |
| 3      | 3         | 2.16%   |
| 17     | 1         | 0.72%   |
| 15     | 1         | 0.72%   |
| 13     | 1         | 0.72%   |
| 7      | 1         | 0.72%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 122       | 89.05%  |
| Yes       | 15        | 10.95%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 131       | 96.32%  |
| No        | 5         | 3.68%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 87        | 63.5%   |
| Yes       | 50        | 36.5%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 100       | 72.99%  |
| Yes       | 37        | 27.01%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Austria | 136       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                            | Computers | Percent |
|---------------------------------|-----------|---------|
| Vienna                          | 69        | 47.92%  |
| Graz                            | 13        | 9.03%   |
| Linz                            | 4         | 2.78%   |
| Innsbruck                       | 4         | 2.78%   |
| Salzburg                        | 3         | 2.08%   |
| Sankt Veit an der Glan          | 2         | 1.39%   |
| Bruck an der Mur                | 2         | 1.39%   |
| Atzenbrugg                      | 2         | 1.39%   |
| Zwettl Stadt                    | 1         | 0.69%   |
| Wels                            | 1         | 0.69%   |
| Weidlingbach                    | 1         | 0.69%   |
| Voggenberg                      | 1         | 0.69%   |
| Tulln                           | 1         | 0.69%   |
| Stockerau                       | 1         | 0.69%   |
| Steyr                           | 1         | 0.69%   |
| Spittal an der Drau             | 1         | 0.69%   |
| Siegendorf im Burgenland        | 1         | 0.69%   |
| Schwechat                       | 1         | 0.69%   |
| Schluesslberg                   | 1         | 0.69%   |
| Sankt PГ¶lten                 | 1         | 0.69%   |
| Sankt PÃ¶lten                 | 1         | 0.69%   |
| Sankt Margarethen im Burgenland | 1         | 0.69%   |
| Pusarnitz                       | 1         | 0.69%   |
| Purkersdorf                     | 1         | 0.69%   |
| Poelfing                        | 1         | 0.69%   |
| Pinsdorf                        | 1         | 0.69%   |
| Pichl bei Wels                  | 1         | 0.69%   |
| Parndorf                        | 1         | 0.69%   |
| Ottensheim                      | 1         | 0.69%   |
| Oberpullendorf                  | 1         | 0.69%   |
| Neumarkt am Wallersee           | 1         | 0.69%   |
| Neulengbach                     | 1         | 0.69%   |
| Maria-Anzbach                   | 1         | 0.69%   |
| Maria Enzersdorf                | 1         | 0.69%   |
| Margarethen am Moos             | 1         | 0.69%   |
| Leogang                         | 1         | 0.69%   |
| Leobersdorf                     | 1         | 0.69%   |
| Leoben                          | 1         | 0.69%   |
| Kirchberg in Tirol              | 1         | 0.69%   |
| Hoerndl                         | 1         | 0.69%   |
| Hintersdorf                     | 1         | 0.69%   |
| Grosspertholz                   | 1         | 0.69%   |
| Gmunden                         | 1         | 0.69%   |
| Gaweinstal                      | 1         | 0.69%   |
| Gallneukirchen                  | 1         | 0.69%   |
| Gablitz                         | 1         | 0.69%   |
| Ferndorf                        | 1         | 0.69%   |
| Euratsfeld                      | 1         | 0.69%   |
| Enzenreith                      | 1         | 0.69%   |
| Eisenstadt                      | 1         | 0.69%   |
| Breitenfurt bei Wien            | 1         | 0.69%   |
| Birkfeld                        | 1         | 0.69%   |
| Ansfelden                       | 1         | 0.69%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 26        | 39     | 16.56%  |
| Transcend           | 21        | 23     | 13.38%  |
| WDC                 | 16        | 37     | 10.19%  |
| Crucial             | 11        | 14     | 7.01%   |
| Kingston            | 10        | 19     | 6.37%   |
| Seagate             | 9         | 29     | 5.73%   |
| Intel               | 9         | 12     | 5.73%   |
| SanDisk             | 6         | 11     | 3.82%   |
| Phison              | 4         | 5      | 2.55%   |
| Hoodisk             | 4         | 5      | 2.55%   |
| SK hynix            | 3         | 4      | 1.91%   |
| Micron Technology   | 3         | 7      | 1.91%   |
| HGST                | 3         | 9      | 1.91%   |
| China               | 3         | 3      | 1.91%   |
| Toshiba             | 2         | 2      | 1.27%   |
| OCZ                 | 2         | 2      | 1.27%   |
| Hitachi             | 2         | 2      | 1.27%   |
| Hewlett-Packard     | 2         | 2      | 1.27%   |
| FORESEE             | 2         | 3      | 1.27%   |
| Dell                | 2         | 2      | 1.27%   |
| Corsair             | 2         | 3      | 1.27%   |
| ATP                 | 2         | 2      | 1.27%   |
| A-DATA Technology   | 2         | 5      | 1.27%   |
| SYNOLOGY            | 1         | 1      | 0.64%   |
| Kston               | 1         | 1      | 0.64%   |
| KingSpec            | 1         | 1      | 0.64%   |
| Intenso             | 1         | 1      | 0.64%   |
| Goodram             | 1         | 1      | 0.64%   |
| Dogfish             | 1         | 1      | 0.64%   |
| BR                  | 1         | 1      | 0.64%   |
| BORY                | 1         | 1      | 0.64%   |
| BIWIN               | 1         | 1      | 0.64%   |
| Apple               | 1         | 1      | 0.64%   |
| AirDisk             | 1         | 1      | 0.64%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung SSD 840 EVO 250GB               | 6         | 3.49%   |
| Transcend TS128GMSA230S 128GB           | 5         | 2.91%   |
| Transcend TS128GMSA370 128GB            | 3         | 1.74%   |
| Kingston SUV500MS120G 120GB             | 3         | 1.74%   |
| Kingston SA400S37240G 240GB             | 3         | 1.74%   |
| Crucial CT240BX500SSD1 240GB            | 3         | 1.74%   |
| WDC WD60EFRX-68L0BN1 6TB                | 2         | 1.16%   |
| WDC WD40EFRX-68N32N0 4TB                | 2         | 1.16%   |
| Transcend TS64GMSA230S 64GB             | 2         | 1.16%   |
| Transcend TS240GSSD220S 240GB           | 2         | 1.16%   |
| Transcend TS16GMSA370 16GB              | 2         | 1.16%   |
| SK hynix BC511 HFM512GDJTNI-82A0A 512GB | 2         | 1.16%   |
| SanDisk SSD PLUS 120GB                  | 2         | 1.16%   |
| Samsung SSD 860 EVO 250GB               | 2         | 1.16%   |
| Samsung MZALQ512HBLU-00BL1 512GB        | 2         | 1.16%   |
| Phison SATA SSD 16GB                    | 2         | 1.16%   |
| Intel SSDPEKKF512G8L 512GB              | 2         | 1.16%   |
| Hoodisk SSD 64GB                        | 2         | 1.16%   |
| HP RAID 1(1+0) 1TB                      | 2         | 1.16%   |
| FORESEE 128GB SSD                       | 2         | 1.16%   |
| Crucial CT250MX500SSD1 250GB            | 2         | 1.16%   |
| Crucial CT120BX500SSD1 120GB            | 2         | 1.16%   |
| China SATA SSD 64GB                     | 2         | 1.16%   |
| WDC WDS500G2B0A-00SM50 500GB            | 1         | 0.58%   |
| WDC WDS240G2G0B-00EPW0 240GB            | 1         | 0.58%   |
| WDC WD80PURZ-85YNPY0 8TB                | 1         | 0.58%   |
| WDC WD80EFAX-68KNBN0 8TB                | 1         | 0.58%   |
| WDC WD800JD-60LSA5 80GB                 | 1         | 0.58%   |
| WDC WD3200BEVT-22ZCT0 320GB             | 1         | 0.58%   |
| WDC WD2500AAKX-001CA0 250GB             | 1         | 0.58%   |
| WDC WD2500AAJS-00L7A0 250GB             | 1         | 0.58%   |
| WDC WD20SPZX-22CRAT0 2TB                | 1         | 0.58%   |
| WDC WD1600BEVS-00UST0 160GB             | 1         | 0.58%   |
| WDC WD1600BEKT-08PVMT1 160GB            | 1         | 0.58%   |
| WDC WD120EFBX-68B0EN0 12TB              | 1         | 0.58%   |
| WDC WD10JPVT-75A1YT0 1TB                | 1         | 0.58%   |
| WDC WD10JPLX-00MBPT0 1TB                | 1         | 0.58%   |
| WDC WD10EZEX-08WN4A0 1TB                | 1         | 0.58%   |
| WDC WD10EARS-00Y5B1 1TB                 | 1         | 0.58%   |
| WDC WD Elements 25A1 4TB                | 1         | 0.58%   |
| WDC PC SN530 SDBPMPZ-256G-1001 256GB    | 1         | 0.58%   |
| Transcend TS64GMSA370 64GB              | 1         | 0.58%   |
| Transcend TS32GSSD370S 32GB             | 1         | 0.58%   |
| Transcend TS2TMTE220S 2TB               | 1         | 0.58%   |
| Transcend TS256GMTS430S 256GB           | 1         | 0.58%   |
| Transcend TS256GMTE652T2 256GB          | 1         | 0.58%   |
| Transcend TS256GMSA370 256GB            | 1         | 0.58%   |
| Transcend TS256GMSA230S 256GB           | 1         | 0.58%   |
| Toshiba MQ04ABF100 1TB                  | 1         | 0.58%   |
| Toshiba MK3276GSX -63 320GB             | 1         | 0.58%   |
| SYNOLOGY iSCSI Storage 10.9TB           | 1         | 0.58%   |
| SK hynix SC308 SATA 128GB               | 1         | 0.58%   |
| Seagate ST9500325AS 500GB               | 1         | 0.58%   |
| Seagate ST8000VN0022-2EL112 8TB         | 1         | 0.58%   |
| Seagate ST8000DM004-2CX188 8TB          | 1         | 0.58%   |
| Seagate ST4000VX007-2DT166 4TB          | 1         | 0.58%   |
| Seagate ST4000VN008-2DR166 4TB          | 1         | 0.58%   |
| Seagate ST3500413AS 500GB               | 1         | 0.58%   |
| Seagate ST3250318AS 250GB               | 1         | 0.58%   |
| Seagate ST3160318AS 160GB               | 1         | 0.58%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 14        | 34     | 40%     |
| Seagate             | 8         | 23     | 22.86%  |
| HGST                | 3         | 9      | 8.57%   |
| Toshiba             | 2         | 2      | 5.71%   |
| Hitachi             | 2         | 2      | 5.71%   |
| Hewlett-Packard     | 2         | 2      | 5.71%   |
| Dell                | 2         | 2      | 5.71%   |
| SYNOLOGY            | 1         | 1      | 2.86%   |
| Samsung Electronics | 1         | 1      | 2.86%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Transcend           | 19        | 20     | 18.63%  |
| Samsung Electronics | 18        | 25     | 17.65%  |
| Crucial             | 11        | 14     | 10.78%  |
| Kingston            | 9         | 18     | 8.82%   |
| SanDisk             | 6         | 11     | 5.88%   |
| Intel               | 6         | 9      | 5.88%   |
| Hoodisk             | 4         | 5      | 3.92%   |
| Phison              | 3         | 4      | 2.94%   |
| Micron Technology   | 3         | 7      | 2.94%   |
| China               | 3         | 3      | 2.94%   |
| WDC                 | 2         | 2      | 1.96%   |
| OCZ                 | 2         | 2      | 1.96%   |
| FORESEE             | 2         | 3      | 1.96%   |
| SK hynix            | 1         | 2      | 0.98%   |
| Seagate             | 1         | 6      | 0.98%   |
| Kston               | 1         | 1      | 0.98%   |
| KingSpec            | 1         | 1      | 0.98%   |
| Intenso             | 1         | 1      | 0.98%   |
| Goodram             | 1         | 1      | 0.98%   |
| Dogfish             | 1         | 1      | 0.98%   |
| BR                  | 1         | 1      | 0.98%   |
| BORY                | 1         | 1      | 0.98%   |
| BIWIN               | 1         | 1      | 0.98%   |
| ATP                 | 1         | 1      | 0.98%   |
| Apple               | 1         | 1      | 0.98%   |
| AirDisk             | 1         | 1      | 0.98%   |
| A-DATA Technology   | 1         | 2      | 0.98%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 97        | 144    | 65.54%  |
| HDD  | 30        | 76     | 20.27%  |
| NVMe | 21        | 31     | 14.19%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 113       | 220    | 84.33%  |
| NVMe | 21        | 31     | 15.67%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 102       | 159    | 79.07%  |
| 0.51-1.0   | 12        | 12     | 9.3%    |
| 4.01-10.0  | 5         | 22     | 3.88%   |
| 3.01-4.0   | 4         | 13     | 3.1%    |
| 1.01-2.0   | 4         | 11     | 3.1%    |
| 10.01-20.0 | 2         | 3      | 1.55%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 70        | 50.36%  |
| 251-500    | 26        | 18.71%  |
| 21-50      | 15        | 10.79%  |
| 51-100     | 13        | 9.35%   |
| 1-20       | 9         | 6.47%   |
| 501-1000   | 5         | 3.6%    |
| 1001-2000  | 1         | 0.72%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 128       | 92.09%  |
| 21-50    | 6         | 4.32%   |
| 101-250  | 2         | 1.44%   |
| 251-500  | 1         | 0.72%   |
| 501-1000 | 1         | 0.72%   |
| 51-100   | 1         | 0.72%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                      | Computers | Drives | Percent |
|--------------------------------------------|-----------|--------|---------|
| WDC WD60EFRX-68L0BN1 6TB                   | 1         | 1      | 7.69%   |
| WDC WD3200BEVT-22ZCT0 320GB                | 1         | 1      | 7.69%   |
| WDC WD1600BEVS-00UST0 160GB                | 1         | 1      | 7.69%   |
| WDC WD1600BEKT-08PVMT1 160GB               | 1         | 2      | 7.69%   |
| SK hynix SC308 SATA 128GB                  | 1         | 2      | 7.69%   |
| Seagate ST9500325AS 500GB                  | 1         | 1      | 7.69%   |
| OCZ AGILITY3 120GB                         | 1         | 1      | 7.69%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB | 1         | 2      | 7.69%   |
| Intel SSDSCKKF256G8H 256GB                 | 1         | 2      | 7.69%   |
| Hitachi HTS541040G9SA00 40GB               | 1         | 1      | 7.69%   |
| Hitachi HDS721050CLA660 500GB              | 1         | 1      | 7.69%   |
| HGST HTS725050A7E630 500GB                 | 1         | 4      | 7.69%   |
| A-DATA Technology SU630 240GB              | 1         | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 4         | 5      | 30.77%  |
| Hitachi           | 2         | 2      | 15.38%  |
| SK hynix          | 1         | 2      | 7.69%   |
| Seagate           | 1         | 1      | 7.69%   |
| OCZ               | 1         | 1      | 7.69%   |
| Micron Technology | 1         | 2      | 7.69%   |
| Intel             | 1         | 2      | 7.69%   |
| HGST              | 1         | 4      | 7.69%   |
| A-DATA Technology | 1         | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 5      | 50%     |
| Hitachi | 2         | 2      | 25%     |
| Seagate | 1         | 1      | 12.5%   |
| HGST    | 1         | 4      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 12     | 61.54%  |
| SSD  | 5         | 8      | 38.46%  |

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
| Works    | 119       | 225    | 88.15%  |
| Malfunc  | 11        | 20     | 8.15%   |
| Detected | 5         | 6      | 3.7%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 105       | 64.81%  |
| AMD                         | 23        | 14.2%   |
| Samsung Electronics         | 8         | 4.94%   |
| Broadcom / LSI              | 5         | 3.09%   |
| Hewlett-Packard             | 4         | 2.47%   |
| Phison Electronics          | 3         | 1.85%   |
| SK hynix                    | 2         | 1.23%   |
| Marvell Technology Group    | 2         | 1.23%   |
| Toshiba                     | 1         | 0.62%   |
| Silicon Motion              | 1         | 0.62%   |
| SanDisk                     | 1         | 0.62%   |
| Realtek Semiconductor       | 1         | 0.62%   |
| Lite-On Technology          | 1         | 0.62%   |
| Kingston Technology Company | 1         | 0.62%   |
| Dell                        | 1         | 0.62%   |
| ATP ELECTRONICS             | 1         | 0.62%   |
| ASMedia Technology          | 1         | 0.62%   |
| Unknown                     | 1         | 0.62%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 18        | 10.23%  |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 15        | 8.52%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 10        | 5.68%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 8         | 4.55%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 6         | 3.41%   |
| AMD FCH SATA Controller [IDE mode]                                               | 6         | 3.41%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 5         | 2.84%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 4         | 2.27%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 4         | 2.27%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 4         | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 4         | 2.27%   |
| Samsung NVMe SSD Controller 980                                                  | 3         | 1.7%    |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.7%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3         | 1.7%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 3         | 1.7%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 3         | 1.7%    |
| HP Smart Array G6 controllers                                                    | 3         | 1.7%    |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                              | 3         | 1.7%    |
| Unknown                                                                          | 3         | 1.7%    |
| SK hynix BC511                                                                   | 2         | 1.14%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 1.14%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 2         | 1.14%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 2         | 1.14%   |
| Intel Atom Processor C3000 Series SATA Controller 0                              | 2         | 1.14%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 2         | 1.14%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 1.14%   |
| Intel 631xESB/632xESB IDE Controller                                             | 2         | 1.14%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 1.14%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 2         | 1.14%   |
| Broadcom / LSI SAS1068E PCI-Express Fusion-MPT SAS                               | 2         | 1.14%   |
| Toshiba XG4 NVMe SSD Controller                                                  | 1         | 0.57%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 1         | 0.57%   |
| SanDisk PC SN530                                                                 | 1         | 0.57%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.57%   |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 0.57%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 0.57%   |
| Phison E12 NVMe Controller                                                       | 1         | 0.57%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller            | 1         | 0.57%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                            | 1         | 0.57%   |
| Lite-On M8Pe Series NVMe SSD                                                     | 1         | 0.57%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.57%   |
| Intel SSD 660P Series                                                            | 1         | 0.57%   |
| Intel SSD 600P Series                                                            | 1         | 0.57%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 1         | 0.57%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 1         | 0.57%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1         | 0.57%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 0.57%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                    | 1         | 0.57%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                     | 1         | 0.57%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 1         | 0.57%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 1         | 0.57%   |
| Intel C600/X79 series chipset 4-Port SATA IDE Controller                         | 1         | 0.57%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 1         | 0.57%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 1         | 0.57%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 1         | 0.57%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                           | 1         | 0.57%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 1         | 0.57%   |
| Intel 82801EB (ICH5) SATA Controller                                             | 1         | 0.57%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 1         | 0.57%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]      | 1         | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 111       | 66.87%  |
| NVMe | 24        | 14.46%  |
| IDE  | 18        | 10.84%  |
| RAID | 7         | 4.22%   |
| SAS  | 4         | 2.41%   |
| SCSI | 2         | 1.2%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 109       | 80.15%  |
| AMD     | 26        | 19.12%  |
| Unknown | 1         | 0.74%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| AMD GX-412TC SOC                                       | 12        | 8.82%   |
| Intel Celeron CPU J3160 @ 1.60GHz                      | 9         | 6.62%   |
| Intel Xeon CPU E5620 @ 2.40GHz                         | 3         | 2.21%   |
| Intel Celeron J4125 CPU @ 2.00GHz                      | 3         | 2.21%   |
| AMD GX-420MC SOC                                       | 3         | 2.21%   |
| Intel Pentium CPU N4200 @ 1.10GHz                      | 2         | 1.47%   |
| Intel Pentium CPU G3220 @ 3.00GHz                      | 2         | 1.47%   |
| Intel Core i7-8665U CPU @ 1.90GHz                      | 2         | 1.47%   |
| Intel Core i7-8565U CPU @ 1.80GHz                      | 2         | 1.47%   |
| Intel Core i5-7200U CPU @ 2.50GHz                      | 2         | 1.47%   |
| Intel Core i5-6500 CPU @ 3.20GHz                       | 2         | 1.47%   |
| Intel Core i5-6400 CPU @ 2.70GHz                       | 2         | 1.47%   |
| Intel Core i5-2400 CPU @ 3.10GHz                       | 2         | 1.47%   |
| Intel Core i5-10310U CPU @ 1.70GHz                     | 2         | 1.47%   |
| Intel Core i5-10210U CPU @ 1.60GHz                     | 2         | 1.47%   |
| Intel Core i5 CPU M 520 @ 2.40GHz                      | 2         | 1.47%   |
| Intel Core i3-4130 CPU @ 3.40GHz                       | 2         | 1.47%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz                     | 2         | 1.47%   |
| Intel Celeron N4100 CPU @ 1.10GHz                      | 2         | 1.47%   |
| Intel Celeron CPU N3150 @ 1.60GHz                      | 2         | 1.47%   |
| Intel Celeron CPU J1900 @ 1.99GHz                      | 2         | 1.47%   |
| Intel Atom CPU C3558 @ 2.20GHz                         | 2         | 1.47%   |
| AMD Ryzen 5 5500U with Radeon Graphics                 | 2         | 1.47%   |
| Intel Xeon D-2123IT CPU @ 2.20GHz                      | 1         | 0.74%   |
| Intel Xeon CPU L5640 @ 2.27GHz                         | 1         | 0.74%   |
| Intel Xeon CPU E5540 @ 2.53GHz                         | 1         | 0.74%   |
| Intel Xeon CPU E5420 @ 2.50GHz                         | 1         | 0.74%   |
| Intel Xeon CPU E5320 @ 1.86GHz                         | 1         | 0.74%   |
| Intel Xeon CPU E5-2690 v4 @ 2.60GHz                    | 1         | 0.74%   |
| Intel Xeon CPU E5-2667 v4 @ 3.20GHz                    | 1         | 0.74%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz                    | 1         | 0.74%   |
| Intel Xeon CPU E5-2430L 0 @ 2.00GHz                    | 1         | 0.74%   |
| Intel Xeon CPU E31220 @ 3.10GHz                        | 1         | 0.74%   |
| Intel Xeon CPU D-1540 @ 2.00GHz                        | 1         | 0.74%   |
| Intel Pentium CPU N3710 @ 1.60GHz                      | 1         | 0.74%   |
| Intel Pentium CPU N3700 @ 1.60GHz                      | 1         | 0.74%   |
| Intel Pentium CPU G4400 @ 3.30GHz                      | 1         | 0.74%   |
| Intel Pentium 4 CPU 2.40GHz ("GenuineIntel" 686-class) | 1         | 0.74%   |
| Intel Genuine CPU 0000 @ 2.40GHz                       | 1         | 0.74%   |
| Intel Core i7-8850H CPU @ 2.60GHz                      | 1         | 0.74%   |
| Intel Core i7-8550U CPU @ 1.80GHz                      | 1         | 0.74%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz                     | 1         | 0.74%   |
| Intel Core i7-5550U CPU @ 2.00GHz                      | 1         | 0.74%   |
| Intel Core i7-4790 CPU @ 3.60GHz                       | 1         | 0.74%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz                     | 1         | 0.74%   |
| Intel Core i7-3770 CPU @ 3.40GHz                       | 1         | 0.74%   |
| Intel Core i7-3687U CPU @ 2.10GHz                      | 1         | 0.74%   |
| Intel Core i7-10510U CPU @ 1.80GHz                     | 1         | 0.74%   |
| Intel Core i5-8365U CPU @ 1.60GHz                      | 1         | 0.74%   |
| Intel Core i5-8279U CPU @ 2.40GHz                      | 1         | 0.74%   |
| Intel Core i5-7500 CPU @ 3.40GHz                       | 1         | 0.74%   |
| Intel Core i5-6600 CPU @ 3.30GHz                       | 1         | 0.74%   |
| Intel Core i5-6500T CPU @ 2.50GHz                      | 1         | 0.74%   |
| Intel Core i5-6200U CPU @ 2.30GHz                      | 1         | 0.74%   |
| Intel Core i5-4590T CPU @ 2.00GHz                      | 1         | 0.74%   |
| Intel Core i5-4310U CPU @ 2.00GHz                      | 1         | 0.74%   |
| Intel Core i5-4200U CPU @ 1.60GHz                      | 1         | 0.74%   |
| Intel Core i5-3570 CPU @ 3.40GHz                       | 1         | 0.74%   |
| Intel Core i5-3470T CPU @ 2.90GHz                      | 1         | 0.74%   |
| Intel Core i5-3470 CPU @ 3.20GHz                       | 1         | 0.74%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 29        | 21.32%  |
| Intel Celeron          | 26        | 19.12%  |
| AMD GX                 | 15        | 11.03%  |
| Intel Xeon             | 14        | 10.29%  |
| Intel Core i7          | 13        | 9.56%   |
| Intel Core i3          | 11        | 8.09%   |
| Intel Pentium          | 7         | 5.15%   |
| Intel Core 2 Duo       | 3         | 2.21%   |
| Intel Atom             | 3         | 2.21%   |
| Other                  | 2         | 1.47%   |
| AMD Ryzen 7            | 2         | 1.47%   |
| AMD Ryzen 5            | 2         | 1.47%   |
| Intel Pentium 4        | 1         | 0.74%   |
| Intel Genuine          | 1         | 0.74%   |
| Intel Core 2           | 1         | 0.74%   |
| AMD Ryzen Threadripper | 1         | 0.74%   |
| AMD Ryzen Embedded     | 1         | 0.74%   |
| AMD Ryzen 5 PRO        | 1         | 0.74%   |
| AMD Opteron            | 1         | 0.74%   |
| AMD FX                 | 1         | 0.74%   |
| AMD Athlon             | 1         | 0.74%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 79        | 58.09%  |
| 2       | 32        | 23.53%  |
| 8       | 10        | 7.35%   |
| Unknown | 5         | 3.68%   |
| 12      | 4         | 2.94%   |
| 6       | 2         | 1.47%   |
| 64      | 1         | 0.74%   |
| 16      | 1         | 0.74%   |
| 14      | 1         | 0.74%   |
| 1       | 1         | 0.74%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 124       | 91.18%  |
| 2       | 7         | 5.15%   |
| Unknown | 5         | 3.68%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 80        | 58.82%  |
| 2       | 50        | 36.76%  |
| Unknown | 6         | 4.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 21        | 15.44%  |
| Silvermont    | 18        | 13.24%  |
| Puma          | 15        | 11.03%  |
| Skylake       | 11        | 8.09%   |
| Haswell       | 10        | 7.35%   |
| Westmere      | 7         | 5.15%   |
| IvyBridge     | 7         | 5.15%   |
| SandyBridge   | 6         | 4.41%   |
| Goldmont plus | 6         | 4.41%   |
| Goldmont      | 6         | 4.41%   |
| Broadwell     | 5         | 3.68%   |
| Zen           | 4         | 2.94%   |
| Penryn        | 4         | 2.94%   |
| Excavator     | 3         | 2.21%   |
| Unknown       | 3         | 2.21%   |
| IceLake       | 2         | 1.47%   |
| Core          | 2         | 1.47%   |
| CometLake     | 2         | 1.47%   |
| Zen+          | 1         | 0.74%   |
| Zen 2         | 1         | 0.74%   |
| NetBurst      | 1         | 0.74%   |
| Nehalem       | 1         | 0.74%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 87        | 70.73%  |
| AMD                        | 16        | 13.01%  |
| Nvidia                     | 8         | 6.5%    |
| ASPEED Technology          | 7         | 5.69%   |
| Matrox Electronics Systems | 4         | 3.25%   |
| Huawei Technologies        | 1         | 0.81%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                     | Computers | Percent |
|-------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller  | 15        | 12.2%   |
| Intel HD Graphics 530                                                                     | 7         | 5.69%   |
| ASPEED Technology ASPEED Graphics Family                                                  | 7         | 5.69%   |
| Intel GeminiLake [UHD Graphics 600]                                                       | 6         | 4.88%   |
| AMD ES1000                                                                                | 6         | 4.88%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                                | 5         | 4.07%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                      | 5         | 4.07%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller               | 4         | 3.25%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                 | 4         | 3.25%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                          | 3         | 2.44%   |
| Intel HD Graphics 620                                                                     | 3         | 2.44%   |
| Intel Haswell-ULT Integrated Graphics Controller                                          | 3         | 2.44%   |
| Intel Core Processor Integrated Graphics Controller                                       | 3         | 2.44%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                              | 3         | 2.44%   |
| Matrox Electronics Systems MGA G200EH                                                     | 2         | 1.63%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                              | 2         | 1.63%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                    | 2         | 1.63%   |
| Intel HD Graphics 630                                                                     | 2         | 1.63%   |
| Intel HD Graphics 500                                                                     | 2         | 1.63%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller        | 2         | 1.63%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                 | 2         | 1.63%   |
| Intel 3rd Gen Core processor Graphics Controller                                          | 2         | 1.63%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                       | 2         | 1.63%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                          | 2         | 1.63%   |
| AMD Lucienne                                                                              | 2         | 1.63%   |
| Nvidia NV28 [GeForce4 Ti 4200 AGP 8x]                                                     | 1         | 0.81%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                     | 1         | 0.81%   |
| Nvidia GP107 [GeForce GTX 1050]                                                           | 1         | 0.81%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                        | 1         | 0.81%   |
| Nvidia GP104GLM [Quadro P4000 Mobile]                                                     | 1         | 0.81%   |
| Nvidia GP104GL [Tesla P4]                                                                 | 1         | 0.81%   |
| Nvidia GM107M [GeForce GTX 860M]                                                          | 1         | 0.81%   |
| Nvidia GK208B [GeForce GT 710]                                                            | 1         | 0.81%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                             | 1         | 0.81%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                         | 1         | 0.81%   |
| Intel UHD Graphics 620                                                                    | 1         | 0.81%   |
| Intel Skylake GT2 [HD Graphics 520]                                                       | 1         | 0.81%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                    | 1         | 0.81%   |
| Intel HD Graphics 6000                                                                    | 1         | 0.81%   |
| Intel HD Graphics 5500                                                                    | 1         | 0.81%   |
| Intel HD Graphics 510                                                                     | 1         | 0.81%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                  | 1         | 0.81%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                          | 1         | 0.81%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                 | 1         | 0.81%   |
| Intel Coffee Lake UHD 610 Graphics Controller                                             | 1         | 0.81%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                               | 1         | 0.81%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                     | 1         | 0.81%   |
| Huawei Technologies Hi171x Series [iBMC Intelligent Management system chip w/VGA support] | 1         | 0.81%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                  | 1         | 0.81%   |
| AMD RV515/M52 [Mobility Radeon X1300]                                                     | 1         | 0.81%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                      | 1         | 0.81%   |
| AMD Blackcomb [Radeon HD 6970M/6990M]                                                     | 1         | 0.81%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| 1 x Intel                    | 80        | 58.82%  |
| Other                        | 19        | 13.97%  |
| 1 x AMD                      | 15        | 11.03%  |
| 1 x Nvidia                   | 5         | 3.68%   |
| 1 x Matrox                   | 4         | 2.94%   |
| 1 x ASPEED                   | 4         | 2.94%   |
| 2 x Intel                    | 3         | 2.21%   |
| Intel + ASPEED               | 2         | 1.47%   |
| Nvidia + Huawei Technologies | 1         | 0.74%   |
| Nvidia + ASPEED              | 1         | 0.74%   |
| Intel + Nvidia               | 1         | 0.74%   |
| Intel + AMD                  | 1         | 0.74%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 113       | 83.09%  |
| Unknown     | 19        | 13.97%  |
| Proprietary | 4         | 2.94%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 130       | 94.89%  |
| 3.01-4.0   | 2         | 1.46%   |
| 1.01-2.0   | 2         | 1.46%   |
| 0.51-1.0   | 2         | 1.46%   |
| 7.01-8.0   | 1         | 0.73%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 4         | 14.29%  |
| Lenovo              | 4         | 14.29%  |
| AU Optronics        | 4         | 14.29%  |
| LG Display          | 3         | 10.71%  |
| Dell                | 3         | 10.71%  |
| Philips             | 2         | 7.14%   |
| Chimei Innolux      | 2         | 7.14%   |
| BOE                 | 2         | 7.14%   |
| Unknown             | 1         | 3.57%   |
| PANDA               | 1         | 3.57%   |
| Medion              | 1         | 3.57%   |
| Apple               | 1         | 3.57%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics C34J79x SAM0F1E 3440x1440 800x330mm 34.1-inch    | 2         | 6.9%    |
| LG Display LCD Monitor LGD064C 1920x1080 340x190mm 15.3-inch         | 2         | 6.9%    |
| AU Optronics LCD Monitor AUO2036 2560x1440 310x170mm 13.9-inch       | 2         | 6.9%    |
| Unknown LCD Monitor Sharp 3840x2160                                  | 1         | 3.45%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 430x270mm 20.0-inch | 1         | 3.45%   |
| Samsung Electronics CJG9S SAM9596 3840x1080                          | 1         | 3.45%   |
| Philips PHL BDM4037U PHLC142 3840x2160 890x500mm 40.2-inch           | 1         | 3.45%   |
| Philips PHL 273V7 PHLC156 1920x1080 600x340mm 27.2-inch              | 1         | 3.45%   |
| PANDA LM116LF3L02 NCP000A 1920x1080 260x150mm 11.8-inch              | 1         | 3.45%   |
| Medion MD22321 MEA8302 1920x1080 700x390mm 31.5-inch                 | 1         | 3.45%   |
| LG Display LCD Monitor LGD0353 1366x768 350x190mm 15.7-inch          | 1         | 3.45%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch              | 1         | 3.45%   |
| Lenovo LCD Monitor LEN4043 1400x1050 300x230mm 14.9-inch             | 1         | 3.45%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch              | 1         | 3.45%   |
| Lenovo LCD Monitor LEN4033 1440x900 300x190mm 14.0-inch              | 1         | 3.45%   |
| Dell U2715H DELD069 2560x1440 600x340mm 27.2-inch                    | 1         | 3.45%   |
| Dell U2715H DELD066 2560x1440 600x340mm 27.2-inch                    | 1         | 3.45%   |
| Dell P2719H DEL4185 1920x1080 600x340mm 27.2-inch                    | 1         | 3.45%   |
| Dell 2001FP DELA007 1600x1200 410x310mm 20.2-inch                    | 1         | 3.45%   |
| Chimei Innolux LCD Monitor CMN1484 1600x900 310x170mm 13.9-inch      | 1         | 3.45%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch      | 1         | 3.45%   |
| BOE LCD Monitor BOE08D7 1920x1080 310x170mm 13.9-inch                | 1         | 3.45%   |
| BOE LCD Monitor BOE0714 1920x1080 310x170mm 13.9-inch                | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch       | 1         | 3.45%   |
| AU Optronics LCD Monitor 1920x1080                                   | 1         | 3.45%   |
| Apple iMac APPA007 2560x1440 600x340mm 27.2-inch                     | 1         | 3.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 9         | 33.33%  |
| 2560x1440 (QHD)    | 4         | 14.81%  |
| 1366x768 (WXGA)    | 3         | 11.11%  |
| 3840x2160 (4K)     | 2         | 7.41%   |
| 3440x1440          | 2         | 7.41%   |
| 1440x900 (WXGA+)   | 2         | 7.41%   |
| 3840x1080          | 1         | 3.7%    |
| 1680x1050 (WSXGA+) | 1         | 3.7%    |
| 1600x900 (HD+)     | 1         | 3.7%    |
| 1600x1200          | 1         | 3.7%    |
| 1400x1050          | 1         | 3.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 6         | 21.43%  |
| 27      | 4         | 14.29%  |
| 15      | 4         | 14.29%  |
| 14      | 3         | 10.71%  |
| Unknown | 3         | 10.71%  |
| 34      | 2         | 7.14%   |
| 20      | 2         | 7.14%   |
| 11      | 2         | 7.14%   |
| 40      | 1         | 3.57%   |
| 31      | 1         | 3.57%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 10        | 35.71%  |
| 201-300     | 5         | 17.86%  |
| 501-600     | 4         | 14.29%  |
| Unknown     | 3         | 10.71%  |
| 701-800     | 2         | 7.14%   |
| 401-500     | 2         | 7.14%   |
| 801-900     | 1         | 3.57%   |
| 601-700     | 1         | 3.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 17        | 62.96%  |
| 16/10   | 3         | 11.11%  |
| 4/3     | 2         | 7.41%   |
| 21/9    | 2         | 7.41%   |
| Unknown | 2         | 7.41%   |
| 32/9    | 1         | 3.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 8         | 28.57%  |
| 301-350        | 4         | 14.29%  |
| 351-500        | 3         | 10.71%  |
| 91-100         | 3         | 10.71%  |
| Unknown        | 3         | 10.71%  |
| 51-60          | 2         | 7.14%   |
| 151-200        | 2         | 7.14%   |
| 101-110        | 2         | 7.14%   |
| 501-1000       | 1         | 3.57%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 9         | 32.14%  |
| 101-120 | 7         | 25%     |
| 51-100  | 6         | 21.43%  |
| 161-240 | 3         | 10.71%  |
| Unknown | 3         | 10.71%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 110       | 80.88%  |
| 1     | 21        | 15.44%  |
| 2     | 5         | 3.68%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 112       | 63.64%  |
| Realtek Semiconductor | 40        | 22.73%  |
| Broadcom              | 8         | 4.55%   |
| Qualcomm Atheros      | 3         | 1.7%    |
| LG Electronics        | 2         | 1.14%   |
| TP-Link               | 1         | 0.57%   |
| Seeed Technology      | 1         | 0.57%   |
| QLogic                | 1         | 0.57%   |
| Mellanox Technologies | 1         | 0.57%   |
| Hewlett-Packard       | 1         | 0.57%   |
| Edimax Technology     | 1         | 0.57%   |
| Dresden Elektronik    | 1         | 0.57%   |
| Dell                  | 1         | 0.57%   |
| AVM                   | 1         | 0.57%   |
| Arduino SA            | 1         | 0.57%   |
| AMD                   | 1         | 0.57%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 34        | 15.18%  |
| Intel I211 Gigabit Network Connection                             | 30        | 13.39%  |
| Intel I210 Gigabit Network Connection                             | 23        | 10.27%  |
| Intel I350 Gigabit Network Connection                             | 7         | 3.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 3.13%   |
| Intel Ethernet Connection (2) I219-LM                             | 6         | 2.68%   |
| Intel Wireless 7265                                               | 5         | 2.23%   |
| Intel 82576 Gigabit Network Connection                            | 5         | 2.23%   |
| Intel Wireless 3165                                               | 4         | 1.79%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 4         | 1.79%   |
| Intel Wireless 7260                                               | 3         | 1.34%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 1.34%   |
| Intel Ethernet Controller I225-V                                  | 3         | 1.34%   |
| Intel Ethernet Connection (6) I219-LM                             | 3         | 1.34%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.34%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.89%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2         | 0.89%   |
| LG Optimus Android Phone [USB tethering mode]                     | 2         | 0.89%   |
| Intel Wireless 8265 / 8275                                        | 2         | 0.89%   |
| Intel Wireless 3160                                               | 2         | 0.89%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 2         | 0.89%   |
| Intel Ethernet Connection X553 1GbE                               | 2         | 0.89%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.89%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 0.89%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 0.89%   |
| Intel Centrino Ultimate-N 6300                                    | 2         | 0.89%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 0.89%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 2         | 0.89%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 0.89%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 0.89%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1         | 0.45%   |
| Seeed Seeeduino_Cortex_M0+                                        | 1         | 0.45%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 0.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.45%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.45%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1         | 0.45%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 0.45%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.45%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.45%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 0.45%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1         | 0.45%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 0.45%   |
| QLogic cLOM8214 1/10GbE Controller                                | 1         | 0.45%   |
| Mellanox MT27710 Family [ConnectX-4 Lx]                           | 1         | 0.45%   |
| Intel Wireless-AC 9260                                            | 1         | 0.45%   |
| Intel Wireless 8260                                               | 1         | 0.45%   |
| Intel WiFi Link 5100                                              | 1         | 0.45%   |
| Intel Ultimate N WiFi Link 5300                                   | 1         | 0.45%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 1         | 0.45%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 1         | 0.45%   |
| Intel I210 Gigabit Fiber Network Connection                       | 1         | 0.45%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                     | 1         | 0.45%   |
| Intel Ethernet Connection X722 for 10GBASE-T                      | 1         | 0.45%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                  | 1         | 0.45%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.45%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.45%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.45%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.45%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.45%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 37        | 72.55%  |
| Realtek Semiconductor | 8         | 15.69%  |
| Qualcomm Atheros      | 3         | 5.88%   |
| TP-Link               | 1         | 1.96%   |
| Edimax Technology     | 1         | 1.96%   |
| Dell                  | 1         | 1.96%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                            | 5         | 9.62%   |
| Intel Wireless 3165                                            | 4         | 7.69%   |
| Intel Wireless 7260                                            | 3         | 5.77%   |
| Intel Wi-Fi 6 AX200                                            | 3         | 5.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 3.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 3.85%   |
| Intel Wireless 8265 / 8275                                     | 2         | 3.85%   |
| Intel Wireless 3160                                            | 2         | 3.85%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 2         | 3.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 3.85%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 3.85%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 1         | 1.92%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 1.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.92%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.92%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1         | 1.92%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 1.92%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 1.92%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 1         | 1.92%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 1.92%   |
| Intel Wireless-AC 9260                                         | 1         | 1.92%   |
| Intel Wireless 8260                                            | 1         | 1.92%   |
| Intel WiFi Link 5100                                           | 1         | 1.92%   |
| Intel Ultimate N WiFi Link 5300                                | 1         | 1.92%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 1.92%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1         | 1.92%   |
| Intel Centrino Wireless-N 2230                                 | 1         | 1.92%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 1         | 1.92%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 1         | 1.92%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 1.92%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 1.92%   |
| Intel Centrino Advanced-N 6200                                 | 1         | 1.92%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 1         | 1.92%   |
| Dell Dell Wireless 5550 HSPA+ Mini-Card Network Adapter        | 1         | 1.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 93        | 66.91%  |
| Realtek Semiconductor | 36        | 25.9%   |
| Broadcom              | 8         | 5.76%   |
| QLogic                | 1         | 0.72%   |
| AMD                   | 1         | 0.72%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 34        | 20.86%  |
| Intel I211 Gigabit Network Connection                                         | 30        | 18.4%   |
| Intel I210 Gigabit Network Connection                                         | 23        | 14.11%  |
| Intel I350 Gigabit Network Connection                                         | 7         | 4.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 7         | 4.29%   |
| Intel Ethernet Connection (2) I219-LM                                         | 6         | 3.68%   |
| Intel 82576 Gigabit Network Connection                                        | 5         | 3.07%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 4         | 2.45%   |
| Intel Ethernet Controller I225-V                                              | 3         | 1.84%   |
| Intel Ethernet Connection (6) I219-LM                                         | 3         | 1.84%   |
| Intel 82577LM Gigabit Network Connection                                      | 3         | 1.84%   |
| Intel Ethernet Connection X553 1GbE                                           | 2         | 1.23%   |
| Intel Ethernet Connection I217-V                                              | 2         | 1.23%   |
| Intel Ethernet Connection (2) I219-V                                          | 2         | 1.23%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 2         | 1.23%   |
| Intel 82574L Gigabit Network Connection                                       | 2         | 1.23%   |
| Intel 82567LM Gigabit Network Connection                                      | 2         | 1.23%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 0.61%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 0.61%   |
| QLogic cLOM8214 1/10GbE Controller                                            | 1         | 0.61%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 1         | 0.61%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 1         | 0.61%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 1         | 0.61%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                              | 1         | 0.61%   |
| Intel Ethernet Connection I219-V                                              | 1         | 0.61%   |
| Intel Ethernet Connection I219-LM                                             | 1         | 0.61%   |
| Intel Ethernet Connection I218-LM                                             | 1         | 0.61%   |
| Intel Ethernet Connection I217-LM                                             | 1         | 0.61%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1         | 0.61%   |
| Intel Ethernet Connection (5) I219-LM                                         | 1         | 0.61%   |
| Intel Ethernet Connection (14) I219-V                                         | 1         | 0.61%   |
| Intel Ethernet Connection (12) I219-V                                         | 1         | 0.61%   |
| Intel 82580 Gigabit Network Connection                                        | 1         | 0.61%   |
| Intel 82576NS Gigabit Network Connection                                      | 1         | 0.61%   |
| Intel 82573L Gigabit Ethernet Controller                                      | 1         | 0.61%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 0.61%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 1         | 0.61%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)                        | 1         | 0.61%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                | 1         | 0.61%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                             | 1         | 0.61%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 1         | 0.61%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 1         | 0.61%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0                     | 1         | 0.61%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 131       | 68.95%  |
| WiFi     | 50        | 26.32%  |
| Modem    | 6         | 3.16%   |
| Unknown  | 3         | 1.58%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 126       | 86.9%   |
| WiFi     | 18        | 12.41%  |
| Modem    | 1         | 0.69%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 41        | 30.15%  |
| 4     | 29        | 21.32%  |
| 3     | 28        | 20.59%  |
| 1     | 13        | 9.56%   |
| 6     | 9         | 6.62%   |
| 8     | 7         | 5.15%   |
| 5     | 4         | 2.94%   |
| 7     | 3         | 2.21%   |
| 10    | 1         | 0.74%   |
| 0     | 1         | 0.74%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 132       | 96.35%  |
| Yes  | 5         | 3.65%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 27        | 72.97%  |
| Realtek Semiconductor | 3         | 8.11%   |
| IMC Networks          | 2         | 5.41%   |
| Broadcom              | 2         | 5.41%   |
| Lite-On Technology    | 1         | 2.7%    |
| Apple                 | 1         | 2.7%    |
| Alps Electric         | 1         | 2.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface               | 13        | 35.14%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 4         | 10.81%  |
| Intel AX201 Bluetooth                            | 3         | 8.11%   |
| Intel AX200 Bluetooth                            | 3         | 8.11%   |
| Intel Centrino Bluetooth Wireless Transceiver    | 2         | 5.41%   |
| IMC Networks Realtek Bluetooth Adapter           | 2         | 5.41%   |
| Broadcom BCM2045B (BDC-2.1)                      | 2         | 5.41%   |
| Realtek RTL8821A Bluetooth                       | 1         | 2.7%    |
| Realtek  Bluetooth Adapter                       | 1         | 2.7%    |
| Realtek Bluetooth Radio                          | 1         | 2.7%    |
| Lite-On Atheros AR3012 Bluetooth                 | 1         | 2.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter         | 1         | 2.7%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter | 1         | 2.7%    |
| Apple Built-in Bluetooth 2.0+EDR HCI             | 1         | 2.7%    |
| Alps Electric UGTZ4 Bluetooth                    | 1         | 2.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor        | Computers | Percent |
|---------------|-----------|---------|
| Intel         | 82        | 81.19%  |
| AMD           | 11        | 10.89%  |
| Nvidia        | 4         | 3.96%   |
| Plantronics   | 3         | 2.97%   |
| Creative Labs | 1         | 0.99%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 14        | 11.97%  |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7         | 5.98%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 5.13%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 5.13%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 5.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 4.27%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 4.27%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 4.27%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 4.27%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 4         | 3.42%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 3.42%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 3.42%   |
| Plantronics Plantronics Blackwire 315.1                                                           | 3         | 2.56%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 2.56%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 2.56%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 2.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 2.56%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 2.56%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.71%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 1.71%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 1.71%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.71%   |
| Intel 200 Series PCH HD Audio                                                                     | 2         | 1.71%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1.71%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.71%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.85%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 0.85%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1         | 0.85%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.85%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 0.85%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 1         | 0.85%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 0.85%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                                                | 1         | 0.85%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 1         | 0.85%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 0.85%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.85%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 1         | 0.85%   |
| AMD Barts HDMI Audio [Radeon HD 6790/6850/6870 / 7720 OEM]                                        | 1         | 0.85%   |
| Unknown                                                                                           | 1         | 0.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 23        | 17.56%  |
| Unknown             | 20        | 15.27%  |
| Crucial             | 17        | 12.98%  |
| Kingston            | 16        | 12.21%  |
| SK hynix            | 14        | 10.69%  |
| Micron Technology   | 13        | 9.92%   |
| Corsair             | 7         | 5.34%   |
| Unknown (ABCD)      | 4         | 3.05%   |
| Unknown             | 3         | 2.29%   |
| Transcend           | 2         | 1.53%   |
| Ramaxel Technology  | 2         | 1.53%   |
| Nanya Technology    | 2         | 1.53%   |
| G.Skill             | 2         | 1.53%   |
| Tigo                | 1         | 0.76%   |
| Miron               | 1         | 0.76%   |
| Kingmax             | 1         | 0.76%   |
| Kimtigo             | 1         | 0.76%   |
| Elpida              | 1         | 0.76%   |
| ATP                 | 1         | 0.76%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                       | 5         | 3.68%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR3 2400MT/s | 4         | 2.94%   |
| Unknown                                                           | 3         | 2.21%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                         | 2         | 1.47%   |
| Unknown RAM AW24P64F8BLK0S 8GB DIMM DDR3 1600MT/s                 | 2         | 1.47%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                     | 2         | 1.47%   |
| SK hynix RAM HMT125U6BFR8C-G7 2GB DIMM DDR3 1067MT/s              | 2         | 1.47%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                    | 2         | 1.47%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s            | 2         | 1.47%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s            | 2         | 1.47%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1333MT/s               | 2         | 1.47%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s              | 2         | 1.47%   |
| Kingston RAM CBD26D4S9S8K1C-8 8GB SODIMM DDR4 2667MT/s            | 2         | 1.47%   |
| Crucial RAM CT8G4SFS824A.M8FRS 8GB DIMM DDR4 2400MT/s             | 2         | 1.47%   |
| Unknown RAM X4B08QD8BNVFSO-7-TO1 8GB DIMM DDR4 2933MT/s           | 1         | 0.74%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                         | 1         | 0.74%   |
| Unknown RAM Module 8GB 1600MT/s                                   | 1         | 0.74%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                      | 1         | 0.74%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s                        | 1         | 0.74%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                         | 1         | 0.74%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                         | 1         | 0.74%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                      | 1         | 0.74%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                         | 1         | 0.74%   |
| Unknown RAM Module 2048MB SODIMM DDR2                             | 1         | 0.74%   |
| Unknown RAM Module 1GB DIMM DDR2 1033MT/s                         | 1         | 0.74%   |
| Unknown RAM Module 1024MB SODIMM DDR2                             | 1         | 0.74%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s               | 1         | 0.74%   |
| Transcend RAM JM3200HSE-16G 16GB SODIMM DDR4 3200MT/s             | 1         | 0.74%   |
| Tigo RAM 1600MHz-4G 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.74%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                        | 1         | 0.74%   |
| SK hynix RAM HMT451U6DFR8A-PB 4GB DIMM DDR3 1600MT/s              | 1         | 0.74%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB DIMM DDR3 1600MT/s              | 1         | 0.74%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 1         | 0.74%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB DIMM DDR3 1600MT/s              | 1         | 0.74%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM 1333MT/s                 | 1         | 0.74%   |
| SK hynix RAM HMT112U6TFR8C-H9 1GB DIMM DDR3 1333MT/s              | 1         | 0.74%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s            | 1         | 0.74%   |
| SK hynix RAM HMA84GR7MFR4N-UH 32GB DIMM DDR4 2400MT/s             | 1         | 0.74%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2133MT/s            | 1         | 0.74%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s                         | 1         | 0.74%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                       | 1         | 0.74%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s             | 1         | 0.74%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 1600MT/s             | 1         | 0.74%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s             | 1         | 0.74%   |
| Samsung RAM M471B5273CH0-YK0 4GB SODIMM DDR3 1600MT/s             | 1         | 0.74%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s             | 1         | 0.74%   |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s               | 1         | 0.74%   |
| Samsung RAM M471B1G73QH0-YK0 8GB DIMM DDR3 1600MT/s               | 1         | 0.74%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s             | 1         | 0.74%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s             | 1         | 0.74%   |
| Samsung RAM M471A4G43MB1-CTD 0kB SODIMM DDR4 2667MT/s             | 1         | 0.74%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s             | 1         | 0.74%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s             | 1         | 0.74%   |
| Samsung RAM M393A4K40CB2-CTD 32GB DIMM DDR4 2667MT/s              | 1         | 0.74%   |
| Samsung RAM M391B5273DH0-YH9 4GB DIMM DDR3 1333MT/s               | 1         | 0.74%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 2400MT/s               | 1         | 0.74%   |
| Samsung RAM K4F6E304HB-MGCJ 2GB Chip LPDDR4                       | 1         | 0.74%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s           | 1         | 0.74%   |
| Ramaxel RAM RMR5030MN68F9F1600 4GB DIMM DDR3 1600MT/s             | 1         | 0.74%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM 1334MT/s                   | 1         | 0.74%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 58        | 49.57%  |
| DDR4    | 47        | 40.17%  |
| LPDDR4  | 7         | 5.98%   |
| DDR2    | 2         | 1.71%   |
| LPDDR3  | 1         | 0.85%   |
| DRAM    | 1         | 0.85%   |
| Unknown | 1         | 0.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 57        | 48.72%  |
| DIMM         | 54        | 46.15%  |
| Row Of Chips | 3         | 2.56%   |
| Unknown      | 2         | 1.71%   |
| Chip         | 1         | 0.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 47        | 38.84%  |
| 4096  | 35        | 28.93%  |
| 16384 | 15        | 12.4%   |
| 2048  | 14        | 11.57%  |
| 32768 | 6         | 4.96%   |
| 1024  | 3         | 2.48%   |
| 6144  | 1         | 0.83%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 32        | 26.45%  |
| 1333    | 23        | 19.01%  |
| 2400    | 20        | 16.53%  |
| 2667    | 15        | 12.4%   |
| 3200    | 10        | 8.26%   |
| 2133    | 7         | 5.79%   |
| 1334    | 2         | 1.65%   |
| 1067    | 2         | 1.65%   |
| Unknown | 2         | 1.65%   |
| 65535   | 1         | 0.83%   |
| 4000    | 1         | 0.83%   |
| 2933    | 1         | 0.83%   |
| 2666    | 1         | 0.83%   |
| 1867    | 1         | 0.83%   |
| 1066    | 1         | 0.83%   |
| 1033    | 1         | 0.83%   |
| 667     | 1         | 0.83%   |

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
| Chicony Electronics                    | 7         | 35%     |
| Microdia                               | 3         | 15%     |
| Realtek Semiconductor                  | 2         | 10%     |
| Logitech                               | 2         | 10%     |
| Lite-On Technology                     | 1         | 5%      |
| Lenovo                                 | 1         | 5%      |
| IMC Networks                           | 1         | 5%      |
| Cheng Uei Precision Industry (Foxlink) | 1         | 5%      |
| Apple                                  | 1         | 5%      |
| Acer                                   | 1         | 5%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Realtek Realtek USB2.0 PC Camera                            | 2         | 10%     |
| Chicony ThinkPad T490 Webcam                                | 2         | 10%     |
| Chicony HP HD Camera                                        | 2         | 10%     |
| Microdia Laptop_Integrated_Webcam_HD                        | 1         | 5%      |
| Microdia Integrated Webcam HD                               | 1         | 5%      |
| Microdia Integrated Webcam                                  | 1         | 5%      |
| Logitech Webcam C170                                        | 1         | 5%      |
| Logitech HD Pro Webcam C920                                 | 1         | 5%      |
| Lite-On HP HD Camera                                        | 1         | 5%      |
| Lenovo Integrated Webcam [R5U877]                           | 1         | 5%      |
| IMC Networks Integrated Camera                              | 1         | 5%      |
| Chicony Integrated Camera                                   | 1         | 5%      |
| Chicony HP Universal Camera                                 | 1         | 5%      |
| Chicony HD WebCam                                           | 1         | 5%      |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed] | 1         | 5%      |
| Apple FaceTime HD camera                                    | 1         | 5%      |
| Acer Lenovo EasyCamera                                      | 1         | 5%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 36.36%  |
| Synaptics                  | 3         | 27.27%  |
| Upek                       | 2         | 18.18%  |
| STMicroelectronics         | 1         | 9.09%   |
| Shenzhen Goodix Technology | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                | 2         | 18.18%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor    | 2         | 18.18%  |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 18.18%  |
| Validity Sensors VFS5011 Fingerprint Reader               | 1         | 9.09%   |
| Validity Sensors VFS491                                   | 1         | 9.09%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 9.09%   |
| STMicroelectronics Fingerprint Reader                     | 1         | 9.09%   |
| Shenzhen Goodix  FingerPrint Device                       | 1         | 9.09%   |

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
| 0     | 51        | 36.43%  |
| 1     | 45        | 32.14%  |
| 2     | 27        | 19.29%  |
| 3     | 14        | 10%     |
| 4     | 2         | 1.43%   |
| 5     | 1         | 0.71%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 74        | 54.01%  |
| Card reader              | 15        | 10.95%  |
| Bluetooth                | 15        | 10.95%  |
| Net/wireless             | 12        | 8.76%   |
| Fingerprint reader       | 11        | 8.03%   |
| Firewire controller      | 4         | 2.92%   |
| Network                  | 2         | 1.46%   |
| Graphics card            | 2         | 1.46%   |
| Sound                    | 1         | 0.73%   |
| Net/ethernet             | 1         | 0.73%   |

