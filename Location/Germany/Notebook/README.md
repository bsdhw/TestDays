BSD in Germany - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for BSD in Germany.

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

Total: 416

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Unknown       | Unknown                     | [7cfd3d40eb](https://bsd-hardware.info/?probe=7cfd3d40eb) | Sep 30, 2023 |
| Dell          | Latitude 5591               | [c30943def8](https://bsd-hardware.info/?probe=c30943def8) | Sep 28, 2023 |
| TUXEDO        | Aura 15 Gen1                | [b31f8c12f8](https://bsd-hardware.info/?probe=b31f8c12f8) | Sep 24, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [de1bdf0601](https://bsd-hardware.info/?probe=de1bdf0601) | Sep 21, 2023 |
| Alienware     | m15                         | [609d2ce1ce](https://bsd-hardware.info/?probe=609d2ce1ce) | Sep 14, 2023 |
| Deciso        | NetBoard-A10                | [0068732d33](https://bsd-hardware.info/?probe=0068732d33) | Sep 13, 2023 |
| HP            | ProBook 4530s               | [0b47c15c42](https://bsd-hardware.info/?probe=0b47c15c42) | Sep 12, 2023 |
| HP            | ProBook 4530s               | [4b6daa1f1c](https://bsd-hardware.info/?probe=4b6daa1f1c) | Sep 12, 2023 |
| Lenovo        | ThinkPad SL 2746N8G         | [07eda65608](https://bsd-hardware.info/?probe=07eda65608) | Sep 09, 2023 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [1d5aff2e2a](https://bsd-hardware.info/?probe=1d5aff2e2a) | Sep 08, 2023 |
| Deciso        | NetBoard-A10                | [f95d1da00c](https://bsd-hardware.info/?probe=f95d1da00c) | Sep 01, 2023 |
| Dell          | Latitude 5591               | [972da999fb](https://bsd-hardware.info/?probe=972da999fb) | Aug 18, 2023 |
| Dell          | Latitude 5591               | [a599361016](https://bsd-hardware.info/?probe=a599361016) | Aug 13, 2023 |
| Unknown       | Unknown                     | [09d17597cf](https://bsd-hardware.info/?probe=09d17597cf) | Aug 01, 2023 |
| Unknown       | Unknown                     | [2a2e7a98e3](https://bsd-hardware.info/?probe=2a2e7a98e3) | Aug 01, 2023 |
| Deciso        | NetBoard-A10                | [65667b2f29](https://bsd-hardware.info/?probe=65667b2f29) | Aug 01, 2023 |
| Deciso        | NetBoard-A20                | [9bd5d8fd54](https://bsd-hardware.info/?probe=9bd5d8fd54) | Jul 31, 2023 |
| Deciso        | NetBoard-A10                | [42fcdacbf7](https://bsd-hardware.info/?probe=42fcdacbf7) | Jul 31, 2023 |
| Lenovo        | ThinkPad X230 23202DG       | [f8ade878ce](https://bsd-hardware.info/?probe=f8ade878ce) | Jul 30, 2023 |
| HP            | Notebook                    | [360790274a](https://bsd-hardware.info/?probe=360790274a) | Jul 29, 2023 |
| Lenovo        | ThinkPad T520 42435GG       | [f3aa06579e](https://bsd-hardware.info/?probe=f3aa06579e) | Jul 20, 2023 |
| Samsung       | RC530/RC730                 | [b76e5e8a87](https://bsd-hardware.info/?probe=b76e5e8a87) | Jul 17, 2023 |
| Deciso        | NetBoard-A10                | [535720220a](https://bsd-hardware.info/?probe=535720220a) | Jul 13, 2023 |
| Tactus        | GeoBook 140                 | [4b7383c876](https://bsd-hardware.info/?probe=4b7383c876) | Jul 11, 2023 |
| Lenovo        | ThinkPad X250 20CLS13Q06    | [c318ab3cc7](https://bsd-hardware.info/?probe=c318ab3cc7) | Jul 09, 2023 |
| Unknown       | Unknown                     | [3725d44c33](https://bsd-hardware.info/?probe=3725d44c33) | Jul 01, 2023 |
| Deciso        | NetBoard-A10                | [2eff359d8f](https://bsd-hardware.info/?probe=2eff359d8f) | Jun 28, 2023 |
| Lenovo        | ThinkPad T430 2347A45       | [6969cd9e1a](https://bsd-hardware.info/?probe=6969cd9e1a) | Jun 20, 2023 |
| Lenovo        | ThinkPad T430 2347A45       | [461a92a1a2](https://bsd-hardware.info/?probe=461a92a1a2) | Jun 20, 2023 |
| Dell          | Latitude E6520              | [98868960d5](https://bsd-hardware.info/?probe=98868960d5) | Jun 18, 2023 |
| Samsung       | NC210/NC110                 | [06f5a9210b](https://bsd-hardware.info/?probe=06f5a9210b) | Jun 17, 2023 |
| Apple         | MacBook7,1                  | [6412e6fb23](https://bsd-hardware.info/?probe=6412e6fb23) | Jun 16, 2023 |
| Lenovo        | ThinkPad T530 2429AP0       | [ddf37e7b17](https://bsd-hardware.info/?probe=ddf37e7b17) | Jun 13, 2023 |
| Samsung       | NC210/NC110                 | [dad27d6099](https://bsd-hardware.info/?probe=dad27d6099) | Jun 13, 2023 |
| HP            | 15                          | [4664b4c93f](https://bsd-hardware.info/?probe=4664b4c93f) | Jun 11, 2023 |
| Toshiba       | Satellite C70-B             | [cf9ed85e65](https://bsd-hardware.info/?probe=cf9ed85e65) | Jun 05, 2023 |
| Toshiba       | Satellite C70-B             | [fc66ebba25](https://bsd-hardware.info/?probe=fc66ebba25) | Jun 05, 2023 |
| Deciso        | NetBoard-A10                | [ab3919bc32](https://bsd-hardware.info/?probe=ab3919bc32) | Jun 04, 2023 |
| Tactus        | GeoFlex 110                 | [df93ad7e83](https://bsd-hardware.info/?probe=df93ad7e83) | May 27, 2023 |
| Lenovo        | ThinkPad T560 20FJS03Q00    | [a2110471aa](https://bsd-hardware.info/?probe=a2110471aa) | May 18, 2023 |
| Deciso        | NetBoard-A10                | [37ee98e0b6](https://bsd-hardware.info/?probe=37ee98e0b6) | May 09, 2023 |
| Apple         | MacBook5,1                  | [da07885adb](https://bsd-hardware.info/?probe=da07885adb) | May 09, 2023 |
| Apple         | MacBook5,1                  | [a5a1ca2ee6](https://bsd-hardware.info/?probe=a5a1ca2ee6) | May 02, 2023 |
| Deciso        | NetBoard-A10                | [79c36f752c](https://bsd-hardware.info/?probe=79c36f752c) | Apr 28, 2023 |
| Apple         | MacBook5,1                  | [52174cc0ba](https://bsd-hardware.info/?probe=52174cc0ba) | Apr 27, 2023 |
| Apple         | MacBook5,1                  | [4c7f33d6a9](https://bsd-hardware.info/?probe=4c7f33d6a9) | Apr 25, 2023 |
| Dell          | Latitude 7280               | [254acb5df8](https://bsd-hardware.info/?probe=254acb5df8) | Apr 20, 2023 |
| Lenovo        | ThinkPad X201 3626WNP       | [d642970071](https://bsd-hardware.info/?probe=d642970071) | Apr 19, 2023 |
| Unknown       | Unknown                     | [c221bccd5d](https://bsd-hardware.info/?probe=c221bccd5d) | Apr 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 34487... | [cec90ddd1b](https://bsd-hardware.info/?probe=cec90ddd1b) | Apr 08, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [f3ac765863](https://bsd-hardware.info/?probe=f3ac765863) | Apr 08, 2023 |
| IGEL Techn... | M340C                       | [6c8b2b7af7](https://bsd-hardware.info/?probe=6c8b2b7af7) | Apr 05, 2023 |
| Lenovo        | ThinkPad X220 4291AN9       | [1646bb53ab](https://bsd-hardware.info/?probe=1646bb53ab) | Mar 25, 2023 |
| Lenovo        | ThinkPad X230 232578G       | [edf47cb2d4](https://bsd-hardware.info/?probe=edf47cb2d4) | Mar 21, 2023 |
| Lenovo        | ThinkPad T61 7659CA1        | [bba228ddc9](https://bsd-hardware.info/?probe=bba228ddc9) | Mar 20, 2023 |
| ASUSTek       | G750JS                      | [bb6117addd](https://bsd-hardware.info/?probe=bb6117addd) | Mar 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [6d9c564a33](https://bsd-hardware.info/?probe=6d9c564a33) | Mar 17, 2023 |
| Lenovo        | ThinkPad X61s 7667WQS       | [f1351003d1](https://bsd-hardware.info/?probe=f1351003d1) | Mar 17, 2023 |
| Acer          | Aspire V3-112P              | [104c10f9b0](https://bsd-hardware.info/?probe=104c10f9b0) | Mar 14, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | [d9d7368322](https://bsd-hardware.info/?probe=d9d7368322) | Mar 13, 2023 |
| Lenovo        | ZIUS6                       | [d387825f01](https://bsd-hardware.info/?probe=d387825f01) | Mar 12, 2023 |
| Dell          | Latitude E6330              | [5c60cd3d04](https://bsd-hardware.info/?probe=5c60cd3d04) | Mar 12, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2BR0... | [56fa0d4656](https://bsd-hardware.info/?probe=56fa0d4656) | Mar 11, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [1a2543f92f](https://bsd-hardware.info/?probe=1a2543f92f) | Mar 06, 2023 |
| Deciso        | NetBoard-A10                | [ca59a5e6f4](https://bsd-hardware.info/?probe=ca59a5e6f4) | Feb 28, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | [59e609fbb2](https://bsd-hardware.info/?probe=59e609fbb2) | Feb 26, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | [d8ba5b3157](https://bsd-hardware.info/?probe=d8ba5b3157) | Feb 19, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | [820596f359](https://bsd-hardware.info/?probe=820596f359) | Feb 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [63b73012e6](https://bsd-hardware.info/?probe=63b73012e6) | Feb 18, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | [9137c7933c](https://bsd-hardware.info/?probe=9137c7933c) | Feb 13, 2023 |
| Shuttle       | DS437T                      | [9a16ad9fec](https://bsd-hardware.info/?probe=9a16ad9fec) | Feb 12, 2023 |
| Alienware     | m15                         | [3ab3e4b671](https://bsd-hardware.info/?probe=3ab3e4b671) | Feb 12, 2023 |
| MSI           | GF76 12UE                   | [371f734e07](https://bsd-hardware.info/?probe=371f734e07) | Feb 10, 2023 |
| Notebook      | NV4XMB,ME,MZ                | [8a2bba8635](https://bsd-hardware.info/?probe=8a2bba8635) | Feb 05, 2023 |
| Lenovo        | ThinkPad P50 20EN0008GE     | [8cb09e34ec](https://bsd-hardware.info/?probe=8cb09e34ec) | Feb 04, 2023 |
| Lenovo        | G70-70 80HW006AGE           | [a52e13cf4e](https://bsd-hardware.info/?probe=a52e13cf4e) | Feb 04, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | [c0a6490fc8](https://bsd-hardware.info/?probe=c0a6490fc8) | Feb 03, 2023 |
| Lenovo        | ThinkPad T460 20FMS04200    | [3178015cd3](https://bsd-hardware.info/?probe=3178015cd3) | Feb 02, 2023 |
| Apple         | MacBookAir5,1               | [eeed92ab62](https://bsd-hardware.info/?probe=eeed92ab62) | Jan 29, 2023 |
| HP            | Laptop 14s-fq1xxx           | [1603f38c4c](https://bsd-hardware.info/?probe=1603f38c4c) | Jan 28, 2023 |
| Fujitsu       | LIFEBOOK S935               | [5c07c1a47e](https://bsd-hardware.info/?probe=5c07c1a47e) | Jan 24, 2023 |
| Dell          | XPS 13 9310                 | [7319560506](https://bsd-hardware.info/?probe=7319560506) | Jan 24, 2023 |
| Medion        | S14409                      | [9a44efb64c](https://bsd-hardware.info/?probe=9a44efb64c) | Jan 23, 2023 |
| Lenovo        | ThinkPad T440p 20AN007FG... | [0883806434](https://bsd-hardware.info/?probe=0883806434) | Jan 22, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | [ab38c51298](https://bsd-hardware.info/?probe=ab38c51298) | Jan 22, 2023 |
| Deciso        | NetBoard-A10                | [624bfd62b5](https://bsd-hardware.info/?probe=624bfd62b5) | Jan 15, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [ced6c29193](https://bsd-hardware.info/?probe=ced6c29193) | Jan 14, 2023 |
| Apple         | MacBookAir5,1               | [0d398d5c59](https://bsd-hardware.info/?probe=0d398d5c59) | Dec 27, 2022 |
| Deciso        | NetBoard-A10                | [b09ff8826c](https://bsd-hardware.info/?probe=b09ff8826c) | Dec 26, 2022 |
| Tactus        | GeoFlex 110                 | [955c355b47](https://bsd-hardware.info/?probe=955c355b47) | Dec 23, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [b38d32b139](https://bsd-hardware.info/?probe=b38d32b139) | Dec 23, 2022 |
| Acer          | Aspire ES1-533              | [570b96d0f7](https://bsd-hardware.info/?probe=570b96d0f7) | Dec 23, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [af2a9d1a42](https://bsd-hardware.info/?probe=af2a9d1a42) | Dec 20, 2022 |
| Unknown       | Unknown                     | [364b3758b6](https://bsd-hardware.info/?probe=364b3758b6) | Dec 20, 2022 |
| Acer          | Swift SF114-34              | [0be43b76d1](https://bsd-hardware.info/?probe=0be43b76d1) | Dec 11, 2022 |
| Dell          | Latitude D610               | [6ef8d8137b](https://bsd-hardware.info/?probe=6ef8d8137b) | Nov 24, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [4c83122cc0](https://bsd-hardware.info/?probe=4c83122cc0) | Nov 14, 2022 |
| Google        | Akemi                       | [2d8e99f0c2](https://bsd-hardware.info/?probe=2d8e99f0c2) | Nov 12, 2022 |
| Deciso        | NetBoard-A20                | [61157ac2b6](https://bsd-hardware.info/?probe=61157ac2b6) | Nov 10, 2022 |
| Deciso        | NetBoard-A10                | [1fc6403341](https://bsd-hardware.info/?probe=1fc6403341) | Nov 08, 2022 |
| Acer          | JM11-MS                     | [3ff8b20107](https://bsd-hardware.info/?probe=3ff8b20107) | Oct 29, 2022 |
| Fujitsu       | LIFEBOOK E752               | [06e6c07e90](https://bsd-hardware.info/?probe=06e6c07e90) | Oct 25, 2022 |
| Dell          | Latitude 5591               | [58b577382a](https://bsd-hardware.info/?probe=58b577382a) | Oct 23, 2022 |
| Alienware     | m15                         | [3304a767ba](https://bsd-hardware.info/?probe=3304a767ba) | Oct 22, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | [17d766d55a](https://bsd-hardware.info/?probe=17d766d55a) | Oct 08, 2022 |
| HP            | 255 G8 Notebook PC          | [f9851a3257](https://bsd-hardware.info/?probe=f9851a3257) | Oct 01, 2022 |
| Tactus        | GeoFlex 110                 | [0b93b5f915](https://bsd-hardware.info/?probe=0b93b5f915) | Sep 28, 2022 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | [b2024820d1](https://bsd-hardware.info/?probe=b2024820d1) | Sep 26, 2022 |
| Gigabyte      | GB-BSi5A-6200               | [c947635b8f](https://bsd-hardware.info/?probe=c947635b8f) | Sep 25, 2022 |
| Gigabyte      | GB-BSi5A-6200               | [533c7f35f1](https://bsd-hardware.info/?probe=533c7f35f1) | Sep 25, 2022 |
| IBM           | ThinkPad T40 23737CG        | [dfc9b64da2](https://bsd-hardware.info/?probe=dfc9b64da2) | Sep 25, 2022 |
| Fujitsu       | LIFEBOOK A532               | [91e0f723ea](https://bsd-hardware.info/?probe=91e0f723ea) | Sep 18, 2022 |
| Deciso        | DEC2700 - OPNsense Appli... | [eee7bdda02](https://bsd-hardware.info/?probe=eee7bdda02) | Sep 15, 2022 |
| Lenovo        | ThinkPad X270 20HMS2LL00    | [12f6a8866f](https://bsd-hardware.info/?probe=12f6a8866f) | Sep 14, 2022 |
| Deciso        | DEC2700 - OPNsense Appli... | [9e6bd1263d](https://bsd-hardware.info/?probe=9e6bd1263d) | Sep 13, 2022 |
| Deciso        | Netboard A20                | [164274c6b4](https://bsd-hardware.info/?probe=164274c6b4) | Aug 22, 2022 |
| Lenovo        | ThinkPad T480 20L50000GE    | [cd7d7d83ba](https://bsd-hardware.info/?probe=cd7d7d83ba) | Aug 20, 2022 |
| Samsung       | NC210/NC110                 | [6c697b3312](https://bsd-hardware.info/?probe=6c697b3312) | Aug 13, 2022 |
| TUXEDO        | Pulse 14 Gen1               | [5edf8a1bef](https://bsd-hardware.info/?probe=5edf8a1bef) | Aug 09, 2022 |
| ASUSTek       | F6A                         | [6626d18284](https://bsd-hardware.info/?probe=6626d18284) | Aug 08, 2022 |
| Apple         | MacBook6,1                  | [55ab4bc8d6](https://bsd-hardware.info/?probe=55ab4bc8d6) | Jul 29, 2022 |
| Shuttle       | DS437                       | [d7b076918a](https://bsd-hardware.info/?probe=d7b076918a) | Jul 07, 2022 |
| Shuttle       | DS437                       | [9fe84a8c9d](https://bsd-hardware.info/?probe=9fe84a8c9d) | Jul 07, 2022 |
| Lenovo        | IdeaPad S12 20021,2959      | [c1bf998d6a](https://bsd-hardware.info/?probe=c1bf998d6a) | Jul 07, 2022 |
| Deciso        | NetBoard-A10                | [681bb27fbc](https://bsd-hardware.info/?probe=681bb27fbc) | Jul 04, 2022 |
| Apple         | MacBook6,1                  | [a6d3cf9a30](https://bsd-hardware.info/?probe=a6d3cf9a30) | Jun 20, 2022 |
| Dell          | Latitude 5521               | [2c9d24a69e](https://bsd-hardware.info/?probe=2c9d24a69e) | Jun 19, 2022 |
| Lenovo        | ThinkPad T420 4236MY0       | [94095d4c11](https://bsd-hardware.info/?probe=94095d4c11) | Jun 06, 2022 |
| TUXEDO        | Aura 15 Gen1                | [727f9708b4](https://bsd-hardware.info/?probe=727f9708b4) | May 24, 2022 |
| HP            | 255 G8 Notebook PC          | [004e039a23](https://bsd-hardware.info/?probe=004e039a23) | May 19, 2022 |
| HP            | 255 G8 Notebook PC          | [555a7733b7](https://bsd-hardware.info/?probe=555a7733b7) | May 19, 2022 |
| TUXEDO        | Aura 15 Gen1                | [1c84f0f722](https://bsd-hardware.info/?probe=1c84f0f722) | May 19, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [86866ce217](https://bsd-hardware.info/?probe=86866ce217) | May 17, 2022 |
| Deciso        | OPNsense Appliance          | [70c9fd07ac](https://bsd-hardware.info/?probe=70c9fd07ac) | May 09, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [5259bc1933](https://bsd-hardware.info/?probe=5259bc1933) | May 08, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [a69f0fefca](https://bsd-hardware.info/?probe=a69f0fefca) | May 07, 2022 |
| Acer          | Aspire E1-570G              | [7fd31252a2](https://bsd-hardware.info/?probe=7fd31252a2) | May 04, 2022 |
| HP            | EliteBook 820 G2            | [3997ff79e4](https://bsd-hardware.info/?probe=3997ff79e4) | May 03, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [f02e4345ff](https://bsd-hardware.info/?probe=f02e4345ff) | Apr 30, 2022 |
| Deciso        | DEC2700 - OPNsense Appli... | [22b192afca](https://bsd-hardware.info/?probe=22b192afca) | Apr 28, 2022 |
| Apple         | MacBookPro3,1               | [912d02aec2](https://bsd-hardware.info/?probe=912d02aec2) | Apr 28, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [30e267dd51](https://bsd-hardware.info/?probe=30e267dd51) | Apr 27, 2022 |
| Lenovo        | B570 1068FQG                | [a0d1f01226](https://bsd-hardware.info/?probe=a0d1f01226) | Apr 22, 2022 |
| AMI           | Intel                       | [db87d63d35](https://bsd-hardware.info/?probe=db87d63d35) | Apr 15, 2022 |
| AMI           | Intel                       | [8dc710d126](https://bsd-hardware.info/?probe=8dc710d126) | Apr 14, 2022 |
| Dell          | Latitude E6440              | [eea29a3895](https://bsd-hardware.info/?probe=eea29a3895) | Apr 12, 2022 |
| Apple         | MacBook5,1                  | [41d62dde7d](https://bsd-hardware.info/?probe=41d62dde7d) | Apr 10, 2022 |
| Apple         | MacBook5,1                  | [c5f7b5499a](https://bsd-hardware.info/?probe=c5f7b5499a) | Apr 10, 2022 |
| Acer          | Swift SF114-32              | [7bc748ce7c](https://bsd-hardware.info/?probe=7bc748ce7c) | Apr 08, 2022 |
| Dell          | Precision M4800             | [7a7968204a](https://bsd-hardware.info/?probe=7a7968204a) | Apr 06, 2022 |
| TUXEDO        | Aura 15 Gen1                | [e72b47b6de](https://bsd-hardware.info/?probe=e72b47b6de) | Apr 04, 2022 |
| Lenovo        | ThinkPad X260 20F5A28AUK    | [f53c625efd](https://bsd-hardware.info/?probe=f53c625efd) | Mar 30, 2022 |
| Fujitsu       | LIFEBOOK A544               | [e363c95c1c](https://bsd-hardware.info/?probe=e363c95c1c) | Mar 29, 2022 |
| Dell          | Latitude E6540              | [41e5f63a69](https://bsd-hardware.info/?probe=41e5f63a69) | Mar 26, 2022 |
| Dell          | Latitude E6540              | [0ac0f8f1d8](https://bsd-hardware.info/?probe=0ac0f8f1d8) | Mar 26, 2022 |
| Notebook      | N13xWU                      | [8986953acd](https://bsd-hardware.info/?probe=8986953acd) | Mar 22, 2022 |
| Notebook      | N7x0WU                      | [b80f84aef1](https://bsd-hardware.info/?probe=b80f84aef1) | Mar 22, 2022 |
| Notebook      | N8xEJEK                     | [9a62677ea8](https://bsd-hardware.info/?probe=9a62677ea8) | Mar 22, 2022 |
| Dell          | Latitude E6500              | [5fad69bbf0](https://bsd-hardware.info/?probe=5fad69bbf0) | Mar 22, 2022 |
| Dell          | Latitude E6510              | [a040a1a04b](https://bsd-hardware.info/?probe=a040a1a04b) | Mar 22, 2022 |
| Dell          | Latitude E6530              | [9bc5fc70a7](https://bsd-hardware.info/?probe=9bc5fc70a7) | Mar 22, 2022 |
| Deciso        | Netboard A20                | [8ded6d9af6](https://bsd-hardware.info/?probe=8ded6d9af6) | Mar 21, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [0dbac1ca61](https://bsd-hardware.info/?probe=0dbac1ca61) | Mar 19, 2022 |
| Toshiba       | Satellite Pro L40           | [5ff92a5bb3](https://bsd-hardware.info/?probe=5ff92a5bb3) | Mar 19, 2022 |
| Toshiba       | Satellite Pro L40           | [71a7b43ec6](https://bsd-hardware.info/?probe=71a7b43ec6) | Mar 19, 2022 |
| Dell          | Latitude E6540              | [e0576dd008](https://bsd-hardware.info/?probe=e0576dd008) | Mar 13, 2022 |
| AEWIN         | CB-7979                     | [ec1e865bbd](https://bsd-hardware.info/?probe=ec1e865bbd) | Mar 07, 2022 |
| Dell          | Latitude 5591               | [d4d653fba8](https://bsd-hardware.info/?probe=d4d653fba8) | Feb 22, 2022 |
| Lenovo        | ThinkPad X240 20AMS2QD0C    | [ae597455a4](https://bsd-hardware.info/?probe=ae597455a4) | Feb 13, 2022 |
| MiTAC         | 5033                        | [54df5c9e9e](https://bsd-hardware.info/?probe=54df5c9e9e) | Feb 10, 2022 |
| ASUSTek       | X555LA                      | [28b3002182](https://bsd-hardware.info/?probe=28b3002182) | Feb 10, 2022 |
| ASUSTek       | X555LA                      | [9aa18b2e33](https://bsd-hardware.info/?probe=9aa18b2e33) | Feb 09, 2022 |
| Apple         | MacBookPro4,1               | [d852363467](https://bsd-hardware.info/?probe=d852363467) | Feb 08, 2022 |
| Apple         | MacBookPro4,1               | [f05ce66a9a](https://bsd-hardware.info/?probe=f05ce66a9a) | Feb 08, 2022 |
| Lenovo        | ThinkPad T440p 20AWS3RH0... | [a6c02e440b](https://bsd-hardware.info/?probe=a6c02e440b) | Feb 05, 2022 |
| GPD           | G1621-02                    | [1970f517fd](https://bsd-hardware.info/?probe=1970f517fd) | Jan 30, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [b1d702812e](https://bsd-hardware.info/?probe=b1d702812e) | Jan 26, 2022 |
| MSI           | GT75VR 7RF                  | [db276eaa53](https://bsd-hardware.info/?probe=db276eaa53) | Jan 25, 2022 |
| Apple         | MacBookPro11,4              | [6d580e8270](https://bsd-hardware.info/?probe=6d580e8270) | Jan 21, 2022 |
| Dell          | Latitude E6540              | [f13972c935](https://bsd-hardware.info/?probe=f13972c935) | Jan 21, 2022 |
| Fujitsu       | CELSIUS H780                | [a173366c78](https://bsd-hardware.info/?probe=a173366c78) | Jan 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [c36023a724](https://bsd-hardware.info/?probe=c36023a724) | Jan 17, 2022 |
| Acer          | TravelMate 8481TG           | [fae71f7e35](https://bsd-hardware.info/?probe=fae71f7e35) | Jan 15, 2022 |
| MSI           | GT75VR 7RF                  | [cca6cc3c0b](https://bsd-hardware.info/?probe=cca6cc3c0b) | Jan 07, 2022 |
| Apple         | MacBook5,1                  | [f0aeeb7f3c](https://bsd-hardware.info/?probe=f0aeeb7f3c) | Jan 05, 2022 |
| Dell          | Latitude 3400               | [41bf32aff1](https://bsd-hardware.info/?probe=41bf32aff1) | Jan 02, 2022 |
| Lenovo        | ThinkPad X220 4293AF4       | [8c7992e557](https://bsd-hardware.info/?probe=8c7992e557) | Jan 01, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [42b4bcbcc2](https://bsd-hardware.info/?probe=42b4bcbcc2) | Dec 27, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [695d7201d4](https://bsd-hardware.info/?probe=695d7201d4) | Dec 27, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [2e1c585715](https://bsd-hardware.info/?probe=2e1c585715) | Dec 21, 2021 |
| Unknown       | Unknown                     | [aa872042e3](https://bsd-hardware.info/?probe=aa872042e3) | Dec 15, 2021 |
| ASUSTek       | 1005P                       | [4c43bd561f](https://bsd-hardware.info/?probe=4c43bd561f) | Dec 14, 2021 |
| Intel         | SharkBay Platform           | [383d1e31c9](https://bsd-hardware.info/?probe=383d1e31c9) | Dec 14, 2021 |
| Unknown       | Unknown                     | [8c3ba89ddd](https://bsd-hardware.info/?probe=8c3ba89ddd) | Dec 12, 2021 |
| Lenovo        | ThinkPad T430s 2356JH4      | [0b6ab3ba1b](https://bsd-hardware.info/?probe=0b6ab3ba1b) | Dec 09, 2021 |
| Dell          | Precision M4300             | [08fe78379d](https://bsd-hardware.info/?probe=08fe78379d) | Dec 08, 2021 |
| Deciso        | Netboard A20                | [593d123f0c](https://bsd-hardware.info/?probe=593d123f0c) | Dec 07, 2021 |
| Lenovo        | ThinkPad T430s 2356JH4      | [b1377872cd](https://bsd-hardware.info/?probe=b1377872cd) | Dec 03, 2021 |
| Unknown       | Unknown                     | [5d1a3bbfe3](https://bsd-hardware.info/?probe=5d1a3bbfe3) | Nov 30, 2021 |
| Shuttle       | DS437                       | [b5d1bcffdb](https://bsd-hardware.info/?probe=b5d1bcffdb) | Nov 29, 2021 |
| Lenovo        | ThinkPad X240 20AMS2QDOC    | [66cfdd2419](https://bsd-hardware.info/?probe=66cfdd2419) | Nov 27, 2021 |
| Shuttle       | DS437                       | [687fc514ba](https://bsd-hardware.info/?probe=687fc514ba) | Nov 27, 2021 |
| Shuttle       | DS437                       | [e65a62f5a5](https://bsd-hardware.info/?probe=e65a62f5a5) | Nov 27, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [8b178d13c7](https://bsd-hardware.info/?probe=8b178d13c7) | Nov 22, 2021 |
| Alienware     | m15                         | [20afd3904b](https://bsd-hardware.info/?probe=20afd3904b) | Nov 21, 2021 |
| Lenovo        | ThinkPad X220 42915CG       | [d8628f80c0](https://bsd-hardware.info/?probe=d8628f80c0) | Nov 19, 2021 |
| Shuttle       | DS437                       | [0dc3d4619e](https://bsd-hardware.info/?probe=0dc3d4619e) | Nov 17, 2021 |
| Acer          | TravelMate B117-M           | [4f02660d9c](https://bsd-hardware.info/?probe=4f02660d9c) | Nov 14, 2021 |
| Lenovo        | ThinkPad W520 4276CTO       | [9082353a69](https://bsd-hardware.info/?probe=9082353a69) | Nov 06, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [1d261120d3](https://bsd-hardware.info/?probe=1d261120d3) | Nov 06, 2021 |
| Lenovo        | ThinkPad T420 4180EE8       | [5303c12fe5](https://bsd-hardware.info/?probe=5303c12fe5) | Nov 05, 2021 |
| Apple         | MacBookAir5,1               | [10d629e1a0](https://bsd-hardware.info/?probe=10d629e1a0) | Nov 04, 2021 |
| BESSTAR Te... | U820                        | [3bd9cd5b98](https://bsd-hardware.info/?probe=3bd9cd5b98) | Nov 03, 2021 |
| Lenovo        | IdeaPad Z360                | [796bd6482f](https://bsd-hardware.info/?probe=796bd6482f) | Nov 02, 2021 |
| BESSTAR Te... | U820                        | [1a39d8a6e3](https://bsd-hardware.info/?probe=1a39d8a6e3) | Nov 02, 2021 |
| Apple         | MacBookAir5,1               | [b354b2bd4e](https://bsd-hardware.info/?probe=b354b2bd4e) | Oct 31, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [d910c79d75](https://bsd-hardware.info/?probe=d910c79d75) | Oct 24, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [d8a6d0daf3](https://bsd-hardware.info/?probe=d8a6d0daf3) | Oct 18, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | [b4ba704356](https://bsd-hardware.info/?probe=b4ba704356) | Oct 17, 2021 |
| Lenovo        | ThinkPad X230 23254G7       | [06c6a282ca](https://bsd-hardware.info/?probe=06c6a282ca) | Oct 16, 2021 |
| Dell          | Inspiron 3493               | [ed41c18cfc](https://bsd-hardware.info/?probe=ed41c18cfc) | Oct 16, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [be42957ecd](https://bsd-hardware.info/?probe=be42957ecd) | Oct 10, 2021 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | [5b08c1de3d](https://bsd-hardware.info/?probe=5b08c1de3d) | Oct 06, 2021 |
| ASUSTek       | UX305FA                     | [decf219ff2](https://bsd-hardware.info/?probe=decf219ff2) | Sep 30, 2021 |
| Lenovo        | ThinkPad X230 2325O76       | [b8729e39e1](https://bsd-hardware.info/?probe=b8729e39e1) | Sep 29, 2021 |
| Unknown       | Unknown                     | [27f807ae11](https://bsd-hardware.info/?probe=27f807ae11) | Sep 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [d9762d6c2d](https://bsd-hardware.info/?probe=d9762d6c2d) | Sep 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [0d00ce5de9](https://bsd-hardware.info/?probe=0d00ce5de9) | Sep 22, 2021 |
| Lenovo        | ThinkPad T400 6474E18       | [2dd5b5869f](https://bsd-hardware.info/?probe=2dd5b5869f) | Sep 13, 2021 |
| Dell          | XPS 15 9570                 | [ee8980fec1](https://bsd-hardware.info/?probe=ee8980fec1) | Sep 07, 2021 |
| Dell          | Latitude 3540               | [2583b22e8d](https://bsd-hardware.info/?probe=2583b22e8d) | Aug 29, 2021 |
| Dell          | Latitude 3540               | [de97e0b2fc](https://bsd-hardware.info/?probe=de97e0b2fc) | Aug 29, 2021 |
| Apple         | MacBookAir7,2               | [6eada6e49e](https://bsd-hardware.info/?probe=6eada6e49e) | Aug 28, 2021 |
| Dell          | Latitude 5591               | [f0ee8a7da0](https://bsd-hardware.info/?probe=f0ee8a7da0) | Aug 25, 2021 |
| Acer          | Aspire ES1-132              | [43c82b1b16](https://bsd-hardware.info/?probe=43c82b1b16) | Aug 22, 2021 |
| Insyde        | Braswell                    | [6c8e94b016](https://bsd-hardware.info/?probe=6c8e94b016) | Aug 19, 2021 |
| Dell          | Latitude 5591               | [c21b6fde68](https://bsd-hardware.info/?probe=c21b6fde68) | Aug 12, 2021 |
| Deciso        | Netboard A20                | [5be914e123](https://bsd-hardware.info/?probe=5be914e123) | Aug 03, 2021 |
| Lenovo        | ThinkPad L512 44444XG       | [a6c8fbcb20](https://bsd-hardware.info/?probe=a6c8fbcb20) | Aug 01, 2021 |
| Sony          | VPCEJ1E1E                   | [c471fb3f82](https://bsd-hardware.info/?probe=c471fb3f82) | Aug 01, 2021 |
| Lenovo        | G550 2958                   | [86880c29cf](https://bsd-hardware.info/?probe=86880c29cf) | Jul 31, 2021 |
| Lenovo        | G550 2958                   | [4fe522eaf3](https://bsd-hardware.info/?probe=4fe522eaf3) | Jul 31, 2021 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [38910aa754](https://bsd-hardware.info/?probe=38910aa754) | Jul 25, 2021 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [3348992bef](https://bsd-hardware.info/?probe=3348992bef) | Jul 23, 2021 |
| Fujitsu       | LIFEBOOK E780               | [71b543094c](https://bsd-hardware.info/?probe=71b543094c) | Jul 22, 2021 |
| MSI           | MS-1613                     | [795e61c1a3](https://bsd-hardware.info/?probe=795e61c1a3) | Jul 21, 2021 |
| Unknown       | Unknown                     | [a37195bcb8](https://bsd-hardware.info/?probe=a37195bcb8) | Jul 15, 2021 |
| Lenovo        | ThinkPad X230 2325A95       | [94d66a0677](https://bsd-hardware.info/?probe=94d66a0677) | Jul 10, 2021 |
| Lenovo        | ThinkPad X230 232578G       | [a8c497b58b](https://bsd-hardware.info/?probe=a8c497b58b) | Jul 09, 2021 |
| Lenovo        | ThinkPad T510 4384FF3       | [25e208721d](https://bsd-hardware.info/?probe=25e208721d) | Jul 02, 2021 |
| Fujitsu       | LIFEBOOK E780               | [2e8c2afe50](https://bsd-hardware.info/?probe=2e8c2afe50) | Jun 20, 2021 |
| Apple         | MacBookAir6,1               | [46bf9edc63](https://bsd-hardware.info/?probe=46bf9edc63) | Jun 17, 2021 |
| Apple         | MacBookAir6,1               | [dbda48cff7](https://bsd-hardware.info/?probe=dbda48cff7) | Jun 17, 2021 |
| HP            | ProBook 640 G1              | [937ed102d1](https://bsd-hardware.info/?probe=937ed102d1) | Jun 12, 2021 |
| ASUSTek       | UX330UAK                    | [430c90b88d](https://bsd-hardware.info/?probe=430c90b88d) | Jun 12, 2021 |
| Unknown       | Unknown                     | [1f2d078d2e](https://bsd-hardware.info/?probe=1f2d078d2e) | Jun 01, 2021 |
| Deciso        | Netboard A20                | [f4a0f0941b](https://bsd-hardware.info/?probe=f4a0f0941b) | May 26, 2021 |
| Unknown       | Unknown                     | [b4b6cfff1f](https://bsd-hardware.info/?probe=b4b6cfff1f) | May 24, 2021 |
| Lenovo        | ThinkPad SL510 28477MG      | [bdbd2d0a05](https://bsd-hardware.info/?probe=bdbd2d0a05) | May 20, 2021 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | [2be8cf963c](https://bsd-hardware.info/?probe=2be8cf963c) | May 02, 2021 |
| HP            | Compaq Presario CQ71        | [258ef16ace](https://bsd-hardware.info/?probe=258ef16ace) | Apr 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [6e8891f184](https://bsd-hardware.info/?probe=6e8891f184) | Apr 24, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [7ec73fe36d](https://bsd-hardware.info/?probe=7ec73fe36d) | Apr 23, 2021 |
| Lenovo        | ThinkPad W541 20EGS04800    | [91d2cd471c](https://bsd-hardware.info/?probe=91d2cd471c) | Apr 16, 2021 |
| Clevo         | W55xEU                      | [229587fbd5](https://bsd-hardware.info/?probe=229587fbd5) | Apr 16, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [403a237513](https://bsd-hardware.info/?probe=403a237513) | Apr 14, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [270bd22b8d](https://bsd-hardware.info/?probe=270bd22b8d) | Apr 14, 2021 |
| Apple         | MacBookPro8,1               | [5d3d014284](https://bsd-hardware.info/?probe=5d3d014284) | Apr 12, 2021 |
| Apple         | MacBookPro8,1               | [ffcc46ea0b](https://bsd-hardware.info/?probe=ffcc46ea0b) | Apr 12, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [bd88655975](https://bsd-hardware.info/?probe=bd88655975) | Apr 10, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [2376cf30b2](https://bsd-hardware.info/?probe=2376cf30b2) | Apr 03, 2021 |
| Dell          | Latitude 5591               | [dadf2c296f](https://bsd-hardware.info/?probe=dadf2c296f) | Mar 30, 2021 |
| TUXEDO        | Unknown                     | [35aa6590c6](https://bsd-hardware.info/?probe=35aa6590c6) | Mar 29, 2021 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [c5e824b558](https://bsd-hardware.info/?probe=c5e824b558) | Mar 29, 2021 |
| Lenovo        | ThinkPad X220 4291IR6       | [3e9aab9818](https://bsd-hardware.info/?probe=3e9aab9818) | Mar 25, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [dc40b42864](https://bsd-hardware.info/?probe=dc40b42864) | Mar 22, 2021 |
| Packard Be... | EasyNote MH36               | [2a98cae4e8](https://bsd-hardware.info/?probe=2a98cae4e8) | Mar 13, 2021 |
| Fujitsu       | LIFEBOOK A555               | [bcb99d0f09](https://bsd-hardware.info/?probe=bcb99d0f09) | Mar 13, 2021 |
| Fujitsu       | LIFEBOOK A555               | [ee894449af](https://bsd-hardware.info/?probe=ee894449af) | Mar 13, 2021 |
| Acer          | Aspire 4810T                | [14af887195](https://bsd-hardware.info/?probe=14af887195) | Mar 11, 2021 |
| HP            | EliteBook 2760p             | [5707fc27ce](https://bsd-hardware.info/?probe=5707fc27ce) | Mar 11, 2021 |
| Clevo         | W55xEU                      | [e51ee3b14c](https://bsd-hardware.info/?probe=e51ee3b14c) | Mar 08, 2021 |
| Dell          | Latitude E6500              | [d25dacc162](https://bsd-hardware.info/?probe=d25dacc162) | Mar 07, 2021 |
| Clevo         | W55xEU                      | [d874753fe2](https://bsd-hardware.info/?probe=d874753fe2) | Mar 07, 2021 |
| Lenovo        | 3000 N200 0769AP2           | [6b81593de9](https://bsd-hardware.info/?probe=6b81593de9) | Mar 06, 2021 |
| Dell          | Latitude 5591               | [e570513187](https://bsd-hardware.info/?probe=e570513187) | Mar 05, 2021 |
| Dell          | Latitude 5400               | [b9d1f08bcf](https://bsd-hardware.info/?probe=b9d1f08bcf) | Mar 04, 2021 |
| Fujitsu       | LIFEBOOK E754               | [d3d033f879](https://bsd-hardware.info/?probe=d3d033f879) | Mar 03, 2021 |
| Fujitsu       | LIFEBOOK E736               | [845c584693](https://bsd-hardware.info/?probe=845c584693) | Mar 03, 2021 |
| Acer          | Extensa 5630                | [6a1b523efb](https://bsd-hardware.info/?probe=6a1b523efb) | Mar 03, 2021 |
| Hampoo        | B3W6_NA123C Reserved        | [bc138c0580](https://bsd-hardware.info/?probe=bc138c0580) | Feb 27, 2021 |
| Fujitsu       | LIFEBOOK E780               | [57506cbdcf](https://bsd-hardware.info/?probe=57506cbdcf) | Feb 26, 2021 |
| Dell          | Latitude 5591               | [0424bf31ca](https://bsd-hardware.info/?probe=0424bf31ca) | Feb 25, 2021 |
| Lenovo        | ThinkPad T520 4242A16       | [49dacee7d0](https://bsd-hardware.info/?probe=49dacee7d0) | Feb 23, 2021 |
| Lenovo        | Z50-70 20354                | [d3d9dc620f](https://bsd-hardware.info/?probe=d3d9dc620f) | Feb 23, 2021 |
| Unknown       | Unknown                     | [eaa6a36e6e](https://bsd-hardware.info/?probe=eaa6a36e6e) | Feb 22, 2021 |
| Lenovo        | ThinkPad T450 20BUS08800    | [d783b3b4dd](https://bsd-hardware.info/?probe=d783b3b4dd) | Feb 22, 2021 |
| Dell          | Latitude 5424 Rugged        | [b94ae57278](https://bsd-hardware.info/?probe=b94ae57278) | Feb 22, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [7f8c483af1](https://bsd-hardware.info/?probe=7f8c483af1) | Feb 21, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [a9604cfdb8](https://bsd-hardware.info/?probe=a9604cfdb8) | Feb 19, 2021 |
| Lenovo        | V130-15IKB 81HN             | [893c17f73a](https://bsd-hardware.info/?probe=893c17f73a) | Feb 19, 2021 |
| Lenovo        | V130-15IKB 81HN             | [d0f504fad2](https://bsd-hardware.info/?probe=d0f504fad2) | Feb 19, 2021 |
| Lenovo        | ZIUS6                       | [1c239bac92](https://bsd-hardware.info/?probe=1c239bac92) | Feb 18, 2021 |
| Clevo         | W55xEU                      | [a66041bae0](https://bsd-hardware.info/?probe=a66041bae0) | Feb 17, 2021 |
| Dell          | Latitude E6330              | [abe1869a95](https://bsd-hardware.info/?probe=abe1869a95) | Feb 17, 2021 |
| Lenovo        | U310                        | [ccec69b736](https://bsd-hardware.info/?probe=ccec69b736) | Feb 16, 2021 |
| Lenovo        | U310                        | [83805a17c5](https://bsd-hardware.info/?probe=83805a17c5) | Feb 16, 2021 |
| Lenovo        | U310                        | [111385095d](https://bsd-hardware.info/?probe=111385095d) | Feb 16, 2021 |
| Apple         | MacBookAir4,2               | [7d8419c918](https://bsd-hardware.info/?probe=7d8419c918) | Feb 16, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | [19f307ff6d](https://bsd-hardware.info/?probe=19f307ff6d) | Feb 16, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [5a393bc680](https://bsd-hardware.info/?probe=5a393bc680) | Feb 15, 2021 |
| Medion        | P6812                       | [c2c592bca8](https://bsd-hardware.info/?probe=c2c592bca8) | Feb 15, 2021 |
| Medion        | P6812                       | [afa43a6aab](https://bsd-hardware.info/?probe=afa43a6aab) | Feb 15, 2021 |
| Fujitsu       | LIFEBOOK E780               | [0f5e891a5d](https://bsd-hardware.info/?probe=0f5e891a5d) | Feb 14, 2021 |
| Lenovo        | ThinkPad T430 2349GCG       | [6da4116499](https://bsd-hardware.info/?probe=6da4116499) | Feb 13, 2021 |
| Lenovo        | ThinkPad T430 2349GCG       | [d212f58dd2](https://bsd-hardware.info/?probe=d212f58dd2) | Feb 13, 2021 |
| Dell          | Latitude 7380               | [1aa2a3a541](https://bsd-hardware.info/?probe=1aa2a3a541) | Feb 12, 2021 |
| Dell          | Latitude 7380               | [4814701c0e](https://bsd-hardware.info/?probe=4814701c0e) | Feb 12, 2021 |
| Clevo         | W55xEU                      | [796ad51947](https://bsd-hardware.info/?probe=796ad51947) | Feb 11, 2021 |
| Clevo         | W55xEU                      | [c28a6397b5](https://bsd-hardware.info/?probe=c28a6397b5) | Feb 11, 2021 |
| Lenovo        | ThinkPad X260 20F5S1H800    | [ca369843a9](https://bsd-hardware.info/?probe=ca369843a9) | Feb 09, 2021 |
| Lenovo        | ThinkPad X220 42915CG       | [0bc3ba767e](https://bsd-hardware.info/?probe=0bc3ba767e) | Feb 06, 2021 |
| Acer          | Extensa 5220                | [5d6a8a51d0](https://bsd-hardware.info/?probe=5d6a8a51d0) | Feb 06, 2021 |
| Acer          | Extensa 5220                | [c443decee1](https://bsd-hardware.info/?probe=c443decee1) | Feb 06, 2021 |
| Fujitsu       | LIFEBOOK E753               | [37245aca21](https://bsd-hardware.info/?probe=37245aca21) | Feb 03, 2021 |
| Unknown       | Unknown                     | [95e264ef56](https://bsd-hardware.info/?probe=95e264ef56) | Feb 02, 2021 |
| Lenovo        | ThinkPad SL510 2847Q9G      | [12e9632d4b](https://bsd-hardware.info/?probe=12e9632d4b) | Jan 31, 2021 |
| Clevo         | W55xEU                      | [ecacada83f](https://bsd-hardware.info/?probe=ecacada83f) | Jan 29, 2021 |
| Clevo         | W55xEU                      | [e17285783e](https://bsd-hardware.info/?probe=e17285783e) | Jan 29, 2021 |
| Fujitsu       | LIFEBOOK E753               | [9a615ebaf8](https://bsd-hardware.info/?probe=9a615ebaf8) | Jan 24, 2021 |
| HP            | Laptop 17-ca1xxx            | [ecf07ad5fe](https://bsd-hardware.info/?probe=ecf07ad5fe) | Jan 24, 2021 |
| HP            | Laptop 17-ca1xxx            | [fb318623f3](https://bsd-hardware.info/?probe=fb318623f3) | Jan 23, 2021 |
| HP            | Laptop 17-ca1xxx            | [97a89d4eb0](https://bsd-hardware.info/?probe=97a89d4eb0) | Jan 23, 2021 |
| HP            | Laptop 17-ca1xxx            | [806c954739](https://bsd-hardware.info/?probe=806c954739) | Jan 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [5f469ceeb9](https://bsd-hardware.info/?probe=5f469ceeb9) | Jan 20, 2021 |
| TUXEDO        | Pulse 14 Gen1               | [5359b4dee9](https://bsd-hardware.info/?probe=5359b4dee9) | Jan 18, 2021 |
| Dell          | Inspiron 3542               | [3c41c474ad](https://bsd-hardware.info/?probe=3c41c474ad) | Jan 16, 2021 |
| Lenovo        | ThinkPad X201 3626HMG       | [a0b1fd0ca5](https://bsd-hardware.info/?probe=a0b1fd0ca5) | Jan 12, 2021 |
| Lenovo        | ThinkPad X201 3626HMG       | [f384858fd6](https://bsd-hardware.info/?probe=f384858fd6) | Jan 12, 2021 |
| Dell          | XPS 15 7590                 | [6cd195aa69](https://bsd-hardware.info/?probe=6cd195aa69) | Jan 05, 2021 |
| Dell          | XPS 15 7590                 | [50ca36db01](https://bsd-hardware.info/?probe=50ca36db01) | Jan 05, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [1ffaf5420c](https://bsd-hardware.info/?probe=1ffaf5420c) | Jan 03, 2021 |
| Apple         | MacBookPro10,2              | [1b0cc7506e](https://bsd-hardware.info/?probe=1b0cc7506e) | Jan 03, 2021 |
| Apple         | MacBookPro10,2              | [e43a26be8d](https://bsd-hardware.info/?probe=e43a26be8d) | Jan 01, 2021 |
| HP            | Laptop 14-dk0xxx            | [5cd8e23152](https://bsd-hardware.info/?probe=5cd8e23152) | Dec 26, 2020 |
| HP            | Laptop 14-dk0xxx            | [fdbd71db5e](https://bsd-hardware.info/?probe=fdbd71db5e) | Dec 26, 2020 |
| HP            | 655                         | [ae2de01d19](https://bsd-hardware.info/?probe=ae2de01d19) | Dec 26, 2020 |
| Lenovo        | ThinkPad X240 20AMS0RR00    | [0f9b8d2e3b](https://bsd-hardware.info/?probe=0f9b8d2e3b) | Dec 22, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [7e80ced15e](https://bsd-hardware.info/?probe=7e80ced15e) | Dec 16, 2020 |
| Lenovo        | ThinkPad X230 23244A9       | [d2e3890c19](https://bsd-hardware.info/?probe=d2e3890c19) | Dec 16, 2020 |
| Lenovo        | ThinkPad X230 23244A9       | [7aaf6835e2](https://bsd-hardware.info/?probe=7aaf6835e2) | Dec 16, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [1952513db8](https://bsd-hardware.info/?probe=1952513db8) | Dec 15, 2020 |
| Lenovo        | ThinkPad T420 4180AJ3       | [683eca8c23](https://bsd-hardware.info/?probe=683eca8c23) | Dec 11, 2020 |
| Lenovo        | ThinkPad X250 20CLS02000    | [cbd9f8a13c](https://bsd-hardware.info/?probe=cbd9f8a13c) | Dec 09, 2020 |
| Dell          | Latitude 2100               | [899ce6ffe4](https://bsd-hardware.info/?probe=899ce6ffe4) | Dec 08, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [16206c4970](https://bsd-hardware.info/?probe=16206c4970) | Dec 07, 2020 |
| Lenovo        | ThinkPad T460 20FMS78014    | [c811e29e6c](https://bsd-hardware.info/?probe=c811e29e6c) | Nov 30, 2020 |
| Dell          | Latitude E6440              | [f9278127a1](https://bsd-hardware.info/?probe=f9278127a1) | Nov 27, 2020 |
| Lenovo        | ThinkPad T420 4236N2G       | [1565d5d570](https://bsd-hardware.info/?probe=1565d5d570) | Nov 24, 2020 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [0738824c51](https://bsd-hardware.info/?probe=0738824c51) | Nov 22, 2020 |
| Lenovo        | ThinkPad T460 20FN003LGE    | [1b7b105e5c](https://bsd-hardware.info/?probe=1b7b105e5c) | Nov 08, 2020 |
| Lenovo        | V130-15IKB 81HN             | [d20a8be7d4](https://bsd-hardware.info/?probe=d20a8be7d4) | Nov 03, 2020 |
| Lenovo        | ThinkPad T520 4243FS9       | [242cd8a6e7](https://bsd-hardware.info/?probe=242cd8a6e7) | Nov 02, 2020 |
| Dell          | Precision M4800             | [8afb8e7443](https://bsd-hardware.info/?probe=8afb8e7443) | Oct 29, 2020 |
| Schenker      | N13xWU                      | [c23a22a72d](https://bsd-hardware.info/?probe=c23a22a72d) | Oct 29, 2020 |
| HUAWEI        | MACH-WX9                    | [2a1b806f39](https://bsd-hardware.info/?probe=2a1b806f39) | Oct 29, 2020 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [26c750117f](https://bsd-hardware.info/?probe=26c750117f) | Oct 28, 2020 |
| IBM           | ThinkPad X41 2525F8G        | [c58f946d2a](https://bsd-hardware.info/?probe=c58f946d2a) | Oct 22, 2020 |
| Lenovo        | ThinkPad Edge E531 68852... | [e6b45d36e5](https://bsd-hardware.info/?probe=e6b45d36e5) | Oct 20, 2020 |
| Lenovo        | ThinkPad X240 20AMS2QD0C    | [fdc7310ca7](https://bsd-hardware.info/?probe=fdc7310ca7) | Oct 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [857f9809b7](https://bsd-hardware.info/?probe=857f9809b7) | Oct 19, 2020 |
| Lenovo        | ThinkPad X270 20HNA004CD    | [79160b17c4](https://bsd-hardware.info/?probe=79160b17c4) | Oct 19, 2020 |
| Apple         | PowerBook6,7                | [7ac5f5530a](https://bsd-hardware.info/?probe=7ac5f5530a) | Oct 19, 2020 |
| Alienware     | m15                         | [8f8cf7d956](https://bsd-hardware.info/?probe=8f8cf7d956) | Oct 19, 2020 |
| Unknown       | Unknown                     | [fd77b4658f](https://bsd-hardware.info/?probe=fd77b4658f) | Oct 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [ee1f866775](https://bsd-hardware.info/?probe=ee1f866775) | Oct 13, 2020 |
| Lenovo        | ThinkPad X220 4291OQ6       | [ed0340e006](https://bsd-hardware.info/?probe=ed0340e006) | Oct 04, 2020 |
| ASUSTek       | N56VJ                       | [9fb23e0394](https://bsd-hardware.info/?probe=9fb23e0394) | Sep 22, 2020 |
| Lenovo        | ThinkPad T460 20FMS78014    | [53e545fcb9](https://bsd-hardware.info/?probe=53e545fcb9) | Sep 17, 2020 |
| Acer          | TravelMate 270              | [56a5581907](https://bsd-hardware.info/?probe=56a5581907) | Sep 17, 2020 |
| HP            | nx9010 (DN775T)             | [b7c0cb252f](https://bsd-hardware.info/?probe=b7c0cb252f) | Sep 16, 2020 |
| Lenovo        | ThinkPad X61 7673AG4        | [650e00a14a](https://bsd-hardware.info/?probe=650e00a14a) | Sep 14, 2020 |
| Panasonic     | CF-C1BD06EFG                | [3e876bada1](https://bsd-hardware.info/?probe=3e876bada1) | Sep 02, 2020 |
| Lenovo        | ThinkPad T460 20FMS78014    | [d78837860f](https://bsd-hardware.info/?probe=d78837860f) | Aug 23, 2020 |
| HKC           | NT11T                       | [1988c603c9](https://bsd-hardware.info/?probe=1988c603c9) | Aug 22, 2020 |
| Acer          | E1-510                      | [c65d08aa57](https://bsd-hardware.info/?probe=c65d08aa57) | Aug 20, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [3032cd9409](https://bsd-hardware.info/?probe=3032cd9409) | Aug 20, 2020 |
| HP            | Compaq Presario CQ71        | [b34e70d7d4](https://bsd-hardware.info/?probe=b34e70d7d4) | Aug 20, 2020 |
| Lenovo        | ThinkPad T450 20BUS08800    | [359cd8cf1b](https://bsd-hardware.info/?probe=359cd8cf1b) | Aug 11, 2020 |
| Sony          | VGN-SZ3VWP_X                | [ace534d784](https://bsd-hardware.info/?probe=ace534d784) | Aug 10, 2020 |
| HP            | ZBook 15 G4                 | [a8953b4964](https://bsd-hardware.info/?probe=a8953b4964) | Aug 03, 2020 |
| HP            | ZBook 15 G4                 | [a97053c5d4](https://bsd-hardware.info/?probe=a97053c5d4) | Aug 03, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [20f3e760eb](https://bsd-hardware.info/?probe=20f3e760eb) | Aug 03, 2020 |
| Lenovo        | ThinkPad T480 20L5000BMD    | [6259248178](https://bsd-hardware.info/?probe=6259248178) | Jul 31, 2020 |
| Dell          | Precision M4800             | [adbaced1b1](https://bsd-hardware.info/?probe=adbaced1b1) | Jul 30, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [ac13b0591f](https://bsd-hardware.info/?probe=ac13b0591f) | Jul 27, 2020 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [2e8c0ef401](https://bsd-hardware.info/?probe=2e8c0ef401) | Jul 21, 2020 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [ff2a0edd8a](https://bsd-hardware.info/?probe=ff2a0edd8a) | Jul 21, 2020 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [de1425a34c](https://bsd-hardware.info/?probe=de1425a34c) | Jul 19, 2020 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [5b8fe1f4f7](https://bsd-hardware.info/?probe=5b8fe1f4f7) | Jul 19, 2020 |
| Schenker      | N13xWU                      | [225afaa47f](https://bsd-hardware.info/?probe=225afaa47f) | Jul 15, 2020 |
| Dell          | Latitude E6440              | [a59bcf04fe](https://bsd-hardware.info/?probe=a59bcf04fe) | Jul 13, 2020 |
| Dell          | Inspiron 7773               | [0b335f5918](https://bsd-hardware.info/?probe=0b335f5918) | Jul 12, 2020 |
| Schenker      | SCHENKER_COMPACT15_17_SC... | [95434cbf80](https://bsd-hardware.info/?probe=95434cbf80) | Jul 07, 2020 |
| Lenovo        | G50-45 80E3                 | [56d1b97dc1](https://bsd-hardware.info/?probe=56d1b97dc1) | Jun 11, 2020 |
| Lenovo        | ThinkPad T450s 20BWS16X0... | [f83f765ab3](https://bsd-hardware.info/?probe=f83f765ab3) | Jun 06, 2020 |
| Schenker      | SCHENKER_COMPACT15_17_SC... | [96fcd8fc28](https://bsd-hardware.info/?probe=96fcd8fc28) | May 28, 2020 |
| Fujitsu       | LIFEBOOK A357               | [b02640458b](https://bsd-hardware.info/?probe=b02640458b) | May 26, 2020 |
| Lenovo        | ThinkPad T410 2537H21       | [0087b62853](https://bsd-hardware.info/?probe=0087b62853) | May 25, 2020 |
| HP            | EliteBook 8560w             | [c240e3a1ea](https://bsd-hardware.info/?probe=c240e3a1ea) | May 25, 2020 |
| TUXEDO        | N13xWU                      | [9649f2d700](https://bsd-hardware.info/?probe=9649f2d700) | May 25, 2020 |
| TUXEDO        | N13xWU                      | [7230dca5a8](https://bsd-hardware.info/?probe=7230dca5a8) | May 25, 2020 |
| Sony          | VPCM12M1E                   | [1e5d0a4d7a](https://bsd-hardware.info/?probe=1e5d0a4d7a) | May 25, 2020 |
| Lenovo        | ThinkPad T410s 291245G      | [6394ae37a8](https://bsd-hardware.info/?probe=6394ae37a8) | May 25, 2020 |
| Lenovo        | ThinkPad T410s 291245G      | [b453d7ac18](https://bsd-hardware.info/?probe=b453d7ac18) | May 25, 2020 |
| Lenovo        | ThinkPad X260 20F5S1H800    | [85567202a8](https://bsd-hardware.info/?probe=85567202a8) | May 23, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| helloSystem 0.8.1    | 17        | 5%      |
| helloSystem 0.4.0    | 14        | 4.12%   |
| helloSystem 0.7.0    | 13        | 3.82%   |
| OpenBSD 6.8          | 12        | 3.53%   |
| helloSystem 0.5.0    | 12        | 3.53%   |
| helloSystem 0.8.0    | 11        | 3.24%   |
| FreeBSD 12.2         | 10        | 2.94%   |
| OpenBSD 7.0          | 8         | 2.35%   |
| FreeBSD 14.0-CURRENT | 7         | 2.06%   |
| FreeBSD 13.2         | 7         | 2.06%   |
| FreeBSD 13.0-p4      | 7         | 2.06%   |
| OpenBSD 7.2          | 6         | 1.76%   |
| OpenBSD 6.9          | 6         | 1.76%   |
| helloSystem 0.6.0    | 6         | 1.76%   |
| GhostBSD 22.01.12    | 6         | 1.76%   |
| FreeBSD 12.1-p10     | 6         | 1.76%   |
| OPNsense 21.7.6      | 5         | 1.47%   |
| OpenBSD 6.7          | 5         | 1.47%   |
| NomadBSD 5806f915    | 5         | 1.47%   |
| GhostBSD 21.08.27    | 5         | 1.47%   |
| FreeBSD 13.0-CURRENT | 5         | 1.47%   |
| FreeBSD 13.0         | 5         | 1.47%   |
| FreeBSD 12.2-p2      | 5         | 1.47%   |
| FreeBSD 12.1-STABLE  | 5         | 1.47%   |
| OPNsense 23.1.11     | 4         | 1.18%   |
| OPNsense 21.1.2      | 4         | 1.18%   |
| NomadBSD 1.4         | 4         | 1.18%   |
| GhostBSD 20.04.02    | 4         | 1.18%   |
| FreeBSD 13.1-p5      | 4         | 1.18%   |
| FreeBSD 12.1-p5      | 4         | 1.18%   |
| FreeBSD 12.1         | 4         | 1.18%   |
| OPNsense 22.1.6      | 3         | 0.88%   |
| NomadBSD 1.4-RC1     | 3         | 0.88%   |
| FreeBSD 13.1-p2      | 3         | 0.88%   |
| FreeBSD 13.1         | 3         | 0.88%   |
| FreeBSD 12.2-p3      | 3         | 0.88%   |
| FreeBSD 12.1-p7      | 3         | 0.88%   |
| OPNsense 23.7.5      | 2         | 0.59%   |
| OPNsense 23.7.3      | 2         | 0.59%   |
| OPNsense 23.4.1      | 2         | 0.59%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 92        | 31.29%  |
| helloSystem | 72        | 24.49%  |
| OPNsense    | 59        | 20.07%  |
| OpenBSD     | 34        | 11.56%  |
| GhostBSD    | 18        | 6.12%   |
| NomadBSD    | 14        | 4.76%   |
| NetBSD      | 2         | 0.68%   |
| MidnightBSD | 1         | 0.34%   |
| HardenedBSD | 1         | 0.34%   |
| FuryBSD     | 1         | 0.34%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| amd64  | 275       | 96.49%  |
| i386   | 9         | 3.16%   |
| macppc | 1         | 0.35%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Console       | 78        | 26%     |
| helloDesktop  | 76        | 25.33%  |
| XFCE          | 25        | 8.33%   |
| fvwm          | 25        | 8.33%   |
| MATE          | 24        | 8%      |
| KDE5          | 17        | 5.67%   |
| GNOME         | 16        | 5.33%   |
| Openbox       | 12        | 4%      |
| TWM           | 10        | 3.33%   |
| i3            | 4         | 1.33%   |
| AwesomeWM     | 4         | 1.33%   |
| Cinnamon      | 2         | 0.67%   |
| Picom         | 1         | 0.33%   |
| LXQt          | 1         | 0.33%   |
| LXDE          | 1         | 0.33%   |
| JWM           | 1         | 0.33%   |
| iwm           | 1         | 0.33%   |
| IceWM         | 1         | 0.33%   |
| Enlightenment | 1         | 0.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 204       | 70.83%  |
| Console | 82        | 28.47%  |
| Wayland | 2         | 0.69%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 128       | 42.52%  |
| SLiM    | 99        | 32.89%  |
| LightDM | 27        | 8.97%   |
| SDDM    | 21        | 6.98%   |
| XDM     | 12        | 3.99%   |
| GDM     | 11        | 3.65%   |
| Ly      | 3         | 1%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Notebooks | Percent |
|------------------|-----------|---------|
| Unknown          | 122       | 40.4%   |
| en_US            | 63        | 20.86%  |
| de_DE            | 51        | 16.89%  |
| C                | 45        | 14.9%   |
| de               | 7         | 2.32%   |
| en_GB            | 5         | 1.66%   |
| fr_FR            | 2         | 0.66%   |
| de_DE.ISO8859-1  | 2         | 0.66%   |
| pl_PL            | 1         | 0.33%   |
| en_IE            | 1         | 0.33%   |
| en_CA            | 1         | 0.33%   |
| en               | 1         | 0.33%   |
| de_DE.ISO8859-15 | 1         | 0.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 232       | 80%     |
| BIOS | 58        | 20%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 149       | 50.68%  |
| Ufs    | 88        | 29.93%  |
| Ffs    | 34        | 11.56%  |
| Cd9660 | 23        | 7.82%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 263       | 91%     |
| MBR     | 24        | 8.3%    |
| Unknown | 2         | 0.69%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 104       | 36.49%  |
| Dell                | 29        | 10.18%  |
| Deciso              | 22        | 7.72%   |
| Hewlett-Packard     | 17        | 5.96%   |
| Apple               | 17        | 5.96%   |
| Acer                | 14        | 4.91%   |
| Fujitsu             | 11        | 3.86%   |
| Unknown             | 11        | 3.86%   |
| ASUSTek Computer    | 9         | 3.16%   |
| TUXEDO              | 8         | 2.81%   |
| Notebook            | 4         | 1.4%    |
| Sony                | 3         | 1.05%   |
| Shuttle             | 3         | 1.05%   |
| MSI                 | 3         | 1.05%   |
| Toshiba             | 2         | 0.7%    |
| Tactus              | 2         | 0.7%    |
| Schenker            | 2         | 0.7%    |
| Samsung Electronics | 2         | 0.7%    |
| Medion              | 2         | 0.7%    |
| IBM                 | 2         | 0.7%    |
| Gigabyte Technology | 2         | 0.7%    |
| Panasonic           | 1         | 0.35%   |
| Packard Bell        | 1         | 0.35%   |
| MiTAC               | 1         | 0.35%   |
| Intel               | 1         | 0.35%   |
| Insyde              | 1         | 0.35%   |
| IGEL Technology     | 1         | 0.35%   |
| HUAWEI              | 1         | 0.35%   |
| HKC                 | 1         | 0.35%   |
| Hampoo              | 1         | 0.35%   |
| GPD                 | 1         | 0.35%   |
| Google              | 1         | 0.35%   |
| Clevo               | 1         | 0.35%   |
| BESSTAR Tech        | 1         | 0.35%   |
| AMI                 | 1         | 0.35%   |
| Alienware           | 1         | 0.35%   |
| AEWIN               | 1         | 0.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Deciso NetBoard-A10                        | 12        | 4.21%   |
| Unknown                                    | 12        | 4.21%   |
| Deciso Netboard A20                        | 5         | 1.75%   |
| Apple MacBookAir5,1                        | 4         | 1.4%    |
| TUXEDO Pulse 14 Gen1                       | 2         | 0.7%    |
| Shuttle DS437                              | 2         | 0.7%    |
| Lenovo ThinkPad X260 20F5S1H800            | 2         | 0.7%    |
| Lenovo ThinkPad X230 232578G               | 2         | 0.7%    |
| Lenovo ThinkPad T410s 291245G              | 2         | 0.7%    |
| Lenovo ThinkPad E490 20N8CTO1WW            | 2         | 0.7%    |
| HP ZBook 15 G4                             | 2         | 0.7%    |
| Gigabyte GB-BSi5A-6200                     | 2         | 0.7%    |
| Dell Latitude E6540                        | 2         | 0.7%    |
| Dell Latitude E6500                        | 2         | 0.7%    |
| Dell Latitude E6330                        | 2         | 0.7%    |
| Dell Latitude 5591                         | 2         | 0.7%    |
| Deciso NetBoard-A20                        | 2         | 0.7%    |
| Deciso DEC2700 - OPNsense Appliance        | 2         | 0.7%    |
| ASUS TUF Gaming FX505DT_FX505DT            | 2         | 0.7%    |
| Apple MacBook5,1                           | 2         | 0.7%    |
| TUXEDO Pulse 15 Gen1                       | 1         | 0.35%   |
| TUXEDO N13xWU                              | 1         | 0.35%   |
| TUXEDO InfinityBook S 15 Gen6              | 1         | 0.35%   |
| TUXEDO InfinityBook Pro 14 Gen6            | 1         | 0.35%   |
| TUXEDO Aura 15 Gen1                        | 1         | 0.35%   |
| Toshiba Satellite Pro L40                  | 1         | 0.35%   |
| Toshiba Satellite C70-B                    | 1         | 0.35%   |
| Tactus GeoFlex 110                         | 1         | 0.35%   |
| Tactus GeoBook 140                         | 1         | 0.35%   |
| Sony VPCM12M1E                             | 1         | 0.35%   |
| Sony VPCEJ1E1E                             | 1         | 0.35%   |
| Sony VGN-SZ3VWP_X                          | 1         | 0.35%   |
| Shuttle DS437T                             | 1         | 0.35%   |
| Schenker SCHENKER_COMPACT15_17_SCO15_17M19 | 1         | 0.35%   |
| Schenker N13xWU                            | 1         | 0.35%   |
| Samsung RC530/RC730                        | 1         | 0.35%   |
| Samsung NC210/NC110                        | 1         | 0.35%   |
| Panasonic CF-C1BD06EFG                     | 1         | 0.35%   |
| Packard Bell EasyNote MH36                 | 1         | 0.35%   |
| Notebook NV4XMB,ME,MZ                      | 1         | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 85        | 29.82%  |
| Dell Latitude          | 21        | 7.37%   |
| Deciso NetBoard-A10    | 12        | 4.21%   |
| Unknown                | 12        | 4.21%   |
| Fujitsu LIFEBOOK       | 10        | 3.51%   |
| Lenovo IdeaPad         | 5         | 1.75%   |
| Deciso Netboard        | 5         | 1.75%   |
| Acer Aspire            | 5         | 1.75%   |
| Apple MacBookAir5      | 4         | 1.4%    |
| TUXEDO Pulse           | 3         | 1.05%   |
| HP Laptop              | 3         | 1.05%   |
| HP EliteBook           | 3         | 1.05%   |
| Dell XPS               | 3         | 1.05%   |
| Dell Inspiron          | 3         | 1.05%   |
| Acer TravelMate        | 3         | 1.05%   |
| TUXEDO InfinityBook    | 2         | 0.7%    |
| Toshiba Satellite      | 2         | 0.7%    |
| Shuttle DS437          | 2         | 0.7%    |
| Lenovo ThinkBook       | 2         | 0.7%    |
| Lenovo Legion          | 2         | 0.7%    |
| IBM ThinkPad           | 2         | 0.7%    |
| HP ZBook               | 2         | 0.7%    |
| HP ProBook             | 2         | 0.7%    |
| Gigabyte GB-BSi5A-6200 | 2         | 0.7%    |
| Dell Precision         | 2         | 0.7%    |
| Deciso NetBoard-A20    | 2         | 0.7%    |
| Deciso DEC2700         | 2         | 0.7%    |
| ASUS TUF               | 2         | 0.7%    |
| Apple MacBook5         | 2         | 0.7%    |
| Acer Swift             | 2         | 0.7%    |
| Acer Extensa           | 2         | 0.7%    |
| TUXEDO N13xWU          | 1         | 0.35%   |
| TUXEDO Aura            | 1         | 0.35%   |
| Tactus GeoFlex         | 1         | 0.35%   |
| Tactus GeoBook         | 1         | 0.35%   |
| Sony VPCM12M1E         | 1         | 0.35%   |
| Sony VPCEJ1E1E         | 1         | 0.35%   |
| Sony VGN-SZ3VWP        | 1         | 0.35%   |
| Shuttle DS437T         | 1         | 0.35%   |
| Schenker SCHENKER      | 1         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 27        | 9.47%   |
| 2020    | 26        | 9.12%   |
| 2018    | 23        | 8.07%   |
| 2022    | 22        | 7.72%   |
| 2011    | 22        | 7.72%   |
| 2017    | 20        | 7.02%   |
| 2016    | 20        | 7.02%   |
| 2019    | 19        | 6.67%   |
| 2013    | 18        | 6.32%   |
| 2012    | 16        | 5.61%   |
| 2010    | 16        | 5.61%   |
| 2014    | 15        | 5.26%   |
| 2015    | 12        | 4.21%   |
| 2008    | 10        | 3.51%   |
| 2009    | 6         | 2.11%   |
| 2007    | 4         | 1.4%    |
| Unknown | 3         | 1.05%   |
| 2003    | 2         | 0.7%    |
| 2023    | 1         | 0.35%   |
| 2006    | 1         | 0.35%   |
| 2005    | 1         | 0.35%   |
| 2002    | 1         | 0.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 285       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 283       | 99.3%   |
| Yes  | 2         | 0.7%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 104       | 36.24%  |
| 16.01-24.0  | 78        | 27.18%  |
| 4.01-8.0    | 58        | 20.21%  |
| 32.01-64.0  | 18        | 6.27%   |
| 2.01-3.0    | 14        | 4.88%   |
| 3.01-4.0    | 4         | 1.39%   |
| 1.01-2.0    | 3         | 1.05%   |
| 0.51-1.0    | 3         | 1.05%   |
| 0.01-0.5    | 2         | 0.7%    |
| 24.01-32.0  | 1         | 0.35%   |
| 64.01-256.0 | 1         | 0.35%   |
| 0           | 1         | 0.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 169       | 57.88%  |
| 0.51-1.0   | 81        | 27.74%  |
| 1.01-2.0   | 25        | 8.56%   |
| 2.01-3.0   | 5         | 1.71%   |
| 4.01-8.0   | 4         | 1.37%   |
| Unknown    | 4         | 1.37%   |
| 0          | 2         | 0.68%   |
| 24.01-32.0 | 1         | 0.34%   |
| 16.01-24.0 | 1         | 0.34%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 211       | 72.26%  |
| 2      | 60        | 20.55%  |
| 0      | 12        | 4.11%   |
| 3      | 9         | 3.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 207       | 72.13%  |
| Yes       | 80        | 27.87%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 258       | 90.53%  |
| No        | 27        | 9.47%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 241       | 84.27%  |
| No        | 45        | 15.73%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 161       | 56.1%   |
| No        | 126       | 43.9%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Germany | 285       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Berlin            | 29        | 9.57%   |
| Munich            | 11        | 3.63%   |
| Frankfurt am Main | 10        | 3.3%    |
| Hamburg           | 9         | 2.97%   |
| Bedburg           | 6         | 1.98%   |
| Halle             | 5         | 1.65%   |
| Aachen            | 5         | 1.65%   |
| Lübeck           | 4         | 1.32%   |
| Leipzig           | 4         | 1.32%   |
| Cologne           | 4         | 1.32%   |
| Wuppertal         | 3         | 0.99%   |
| Wernigerode       | 3         | 0.99%   |
| Stuttgart         | 3         | 0.99%   |
| Neuss             | 3         | 0.99%   |
| Markt Indersdorf  | 3         | 0.99%   |
| Ludwigsburg       | 3         | 0.99%   |
| Giessen           | 3         | 0.99%   |
| Essen             | 3         | 0.99%   |
| Darmstadt         | 3         | 0.99%   |
| Bonn              | 3         | 0.99%   |
| Blomberg          | 3         | 0.99%   |
| Bielefeld         | 3         | 0.99%   |
| Zwingenberg       | 2         | 0.66%   |
| Wissen            | 2         | 0.66%   |
| Reutlingen        | 2         | 0.66%   |
| Regensburg        | 2         | 0.66%   |
| Potsdam           | 2         | 0.66%   |
| Pleidelsheim      | 2         | 0.66%   |
| Nuremberg         | 2         | 0.66%   |
| Münster          | 2         | 0.66%   |
| Mainz             | 2         | 0.66%   |
| Lüneburg         | 2         | 0.66%   |
| Kornwestheim      | 2         | 0.66%   |
| Karlsruhe         | 2         | 0.66%   |
| Habichtswald      | 2         | 0.66%   |
| Gummersbach       | 2         | 0.66%   |
| Gifhorn           | 2         | 0.66%   |
| Erlangen          | 2         | 0.66%   |
| Dresden           | 2         | 0.66%   |
| Dortmund          | 2         | 0.66%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 69        | 89     | 21.36%  |
| Transcend           | 31        | 36     | 9.6%    |
| WDC                 | 25        | 29     | 7.74%   |
| SanDisk             | 22        | 24     | 6.81%   |
| Crucial             | 20        | 25     | 6.19%   |
| Seagate             | 19        | 21     | 5.88%   |
| Toshiba             | 14        | 33     | 4.33%   |
| NVMe                | 14        | 25     | 4.33%   |
| Kingston            | 14        | 16     | 4.33%   |
| Intel               | 11        | 11     | 3.41%   |
| Intenso             | 10        | 11     | 3.1%    |
| Apple               | 10        | 10     | 3.1%    |
| Micron Technology   | 9         | 9      | 2.79%   |
| Hitachi             | 8         | 11     | 2.48%   |
| HGST                | 5         | 10     | 1.55%   |
| SPCC                | 4         | 5      | 1.24%   |
| OCZ                 | 4         | 7      | 1.24%   |
| KIOXIA              | 4         | 4      | 1.24%   |
| Fujitsu             | 4         | 4      | 1.24%   |
| SK hynix            | 3         | 4      | 0.93%   |
| Hoodisk             | 3         | 3      | 0.93%   |
| A-DATA Technology   | 3         | 4      | 0.93%   |
| LITEON              | 2         | 2      | 0.62%   |
| Kston               | 2         | 2      | 0.62%   |
| Verbatim            | 1         | 3      | 0.31%   |
| PNY                 | 1         | 1      | 0.31%   |
| Phison              | 1         | 1      | 0.31%   |
| Netac               | 1         | 1      | 0.31%   |
| MyDigitalSSD        | 1         | 1      | 0.31%   |
| Mushkin             | 1         | 1      | 0.31%   |
| Lenovo              | 1         | 1      | 0.31%   |
| Gigabyte Technology | 1         | 1      | 0.31%   |
| FORESEE             | 1         | 1      | 0.31%   |
| Dogfish             | 1         | 1      | 0.31%   |
| Corsair             | 1         | 1      | 0.31%   |
| BIWIN               | 1         | 1      | 0.31%   |
| 2-Power             | 1         | 1      | 0.31%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Transcend TS256GMTE652T2 256GB       | 7         | 2.09%   |
| Transcend TS256GMTS952T2 256GB       | 5         | 1.49%   |
| Transcend TS256GMTE710T 256GB        | 5         | 1.49%   |
| Transcend TS128GMTE110S 128GB        | 4         | 1.19%   |
| Samsung SSD 860 EVO 500GB            | 4         | 1.19%   |
| Apple SSD TS128E 121GB               | 4         | 1.19%   |
| SanDisk SSD PLUS 120GB               | 3         | 0.9%    |
| Samsung SSD 850 EVO 500GB            | 3         | 0.9%    |
| Samsung SSD 850 EVO 250GB            | 3         | 0.9%    |
| Samsung SSD 840 EVO 250GB            | 3         | 0.9%    |
| NVMe Samsung SSD 980 500GB           | 3         | 0.9%    |
| Hoodisk SSD 128GB                    | 3         | 0.9%    |
| Transcend TS64GSSD370S 64GB          | 2         | 0.6%    |
| Transcend TS512GMTS952T2 512GB       | 2         | 0.6%    |
| Transcend TS240GMTS420S 240GB        | 2         | 0.6%    |
| Toshiba THNSNK256GVN8 M.2 2280 256GB | 2         | 0.6%    |
| SPCC Solid State Disk 1TB            | 2         | 0.6%    |
| Seagate ST500LT012-1DG142 500GB      | 2         | 0.6%    |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 0.6%    |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 0.6%    |
| SanDisk SDSSDP064G 64GB              | 2         | 0.6%    |
| Samsung SSD 970 EVO Plus 250GB       | 2         | 0.6%    |
| Samsung SSD 970 EVO Plus 1TB         | 2         | 0.6%    |
| Samsung SSD 970 EVO 500GB            | 2         | 0.6%    |
| Samsung SSD 870 EVO 250GB            | 2         | 0.6%    |
| Samsung SSD 840 PRO Series 256GB     | 2         | 0.6%    |
| Samsung SSD 840 EVO 120GB            | 2         | 0.6%    |
| Samsung PM9A1 NVMe 512GB             | 2         | 0.6%    |
| Samsung MZYLF128HCHP-000L2 128GB     | 2         | 0.6%    |
| Samsung MZVLB512HAJQ-000L7 512GB     | 2         | 0.6%    |
| Samsung MZALQ512HALU-000L2 512GB     | 2         | 0.6%    |
| Samsung MZ7LN256HCHP-000L7 256GB     | 2         | 0.6%    |
| NVMe WDC PC SN730 SDB 512GB          | 2         | 0.6%    |
| NVMe SAMSUNG MZVLW256 256GB          | 2         | 0.6%    |
| Micron 2200V_MTFDHBA512TCK 512GB     | 2         | 0.6%    |
| LITEON LCH-128V2S 128GB              | 2         | 0.6%    |
| Kingston SV300S37A240G 240GB         | 2         | 0.6%    |
| Kingston SA400S37480G 480GB          | 2         | 0.6%    |
| Kingston SA400S37120G 120GB          | 2         | 0.6%    |
| Intenso SSD Sata III 256GB           | 2         | 0.6%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 21     | 26.76%  |
| WDC                 | 16        | 19     | 22.54%  |
| NVMe                | 10        | 20     | 14.08%  |
| Hitachi             | 8         | 11     | 11.27%  |
| Toshiba             | 6         | 7      | 8.45%   |
| HGST                | 5         | 10     | 7.04%   |
| Fujitsu             | 4         | 4      | 5.63%   |
| Samsung Electronics | 2         | 2      | 2.82%   |
| Apple               | 1         | 1      | 1.41%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 45        | 54     | 24.73%  |
| SanDisk             | 22        | 24     | 12.09%  |
| Crucial             | 17        | 22     | 9.34%   |
| Transcend           | 15        | 18     | 8.24%   |
| Kingston            | 11        | 13     | 6.04%   |
| Intel               | 11        | 11     | 6.04%   |
| Intenso             | 10        | 11     | 5.49%   |
| Apple               | 9         | 9      | 4.95%   |
| WDC                 | 4         | 4      | 2.2%    |
| Toshiba             | 4         | 9      | 2.2%    |
| OCZ                 | 4         | 7      | 2.2%    |
| Micron Technology   | 4         | 4      | 2.2%    |
| SPCC                | 3         | 3      | 1.65%   |
| NVMe                | 3         | 3      | 1.65%   |
| Hoodisk             | 3         | 3      | 1.65%   |
| SK hynix            | 2         | 3      | 1.1%    |
| LITEON              | 2         | 2      | 1.1%    |
| Kston               | 2         | 2      | 1.1%    |
| A-DATA Technology   | 2         | 2      | 1.1%    |
| Verbatim            | 1         | 3      | 0.55%   |
| PNY                 | 1         | 1      | 0.55%   |
| Netac               | 1         | 1      | 0.55%   |
| MyDigitalSSD        | 1         | 1      | 0.55%   |
| Mushkin             | 1         | 1      | 0.55%   |
| FORESEE             | 1         | 1      | 0.55%   |
| Dogfish             | 1         | 1      | 0.55%   |
| Corsair             | 1         | 1      | 0.55%   |
| 2-Power             | 1         | 1      | 0.55%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 165       | 215    | 54.82%  |
| NVMe | 69        | 100    | 22.92%  |
| HDD  | 67        | 95     | 22.26%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 219       | 310    | 76.04%  |
| NVMe | 69        | 100    | 23.96%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 187       | 244    | 79.91%  |
| 0.51-1.0   | 30        | 39     | 12.82%  |
| 1.01-2.0   | 15        | 25     | 6.41%   |
| 3.01-4.0   | 1         | 1      | 0.43%   |
| 4.01-10.0  | 1         | 1      | 0.43%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 105       | 35.12%  |
| 1-20           | 71        | 23.75%  |
| 251-500        | 59        | 19.73%  |
| 51-100         | 26        | 8.7%    |
| 501-1000       | 19        | 6.35%   |
| 21-50          | 12        | 4.01%   |
| 1001-2000      | 4         | 1.34%   |
| Unknown        | 2         | 0.67%   |
| More than 3000 | 1         | 0.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 241       | 80.6%   |
| 21-50          | 25        | 8.36%   |
| 101-250        | 13        | 4.35%   |
| 51-100         | 12        | 4.01%   |
| 251-500        | 4         | 1.34%   |
| Unknown        | 2         | 0.67%   |
| More than 3000 | 1         | 0.33%   |
| 501-1000       | 1         | 0.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Toshiba THNSNK256GVN8 M.2 2280 256GB         | 2         | 7      | 6.67%   |
| Hitachi HTS545032B9A300 320GB                | 2         | 4      | 6.67%   |
| Hitachi HTS543225L9A300 250GB                | 2         | 2      | 6.67%   |
| HGST HTS541010A9E680 1TB                     | 2         | 3      | 6.67%   |
| WDC WD3200BEVT-22ZCT0 320GB                  | 1         | 1      | 3.33%   |
| WDC WD1600BEVS-07RST0 160GB                  | 1         | 1      | 3.33%   |
| WDC WD10SPZX-21Z10T0 1TB                     | 1         | 1      | 3.33%   |
| Toshiba MK2018GAP 20GB                       | 1         | 1      | 3.33%   |
| Seagate ST9500420AS 500GB                    | 1         | 1      | 3.33%   |
| Seagate ST9320325AS 320GB                    | 1         | 1      | 3.33%   |
| Seagate ST9250410AS 250GB                    | 1         | 1      | 3.33%   |
| Seagate ST500LT012-1DG142 500GB              | 1         | 1      | 3.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 1      | 3.33%   |
| SanDisk SSD PLUS 480GB                       | 1         | 1      | 3.33%   |
| SanDisk SSD P4 64GB                          | 1         | 1      | 3.33%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 1      | 3.33%   |
| Micron Technology 1100 SATA 256GB            | 1         | 1      | 3.33%   |
| Kingston SV300S37A240G 240GB                 | 1         | 1      | 3.33%   |
| Kingston SNV425S264GB                        | 1         | 1      | 3.33%   |
| Intel SSDSC2KF256H6L 256GB                   | 1         | 1      | 3.33%   |
| Intel SSDSC2BF180A4L 180GB                   | 1         | 1      | 3.33%   |
| Hitachi HTS548040M9AT00 37GB                 | 1         | 1      | 3.33%   |
| Hitachi HTS545025B9SA02 250GB                | 1         | 2      | 3.33%   |
| Fujitsu MHW2160BH 160GB                      | 1         | 1      | 3.33%   |
| Crucial CT1000P1SSD8 1TB                     | 1         | 1      | 3.33%   |
| Corsair Force GT 120GB                       | 1         | 1      | 3.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 6         | 9      | 20%     |
| Seagate             | 5         | 5      | 16.67%  |
| WDC                 | 3         | 3      | 10%     |
| Toshiba             | 3         | 8      | 10%     |
| SanDisk             | 2         | 2      | 6.67%   |
| Kingston            | 2         | 2      | 6.67%   |
| Intel               | 2         | 2      | 6.67%   |
| HGST                | 2         | 3      | 6.67%   |
| Samsung Electronics | 1         | 1      | 3.33%   |
| Micron Technology   | 1         | 1      | 3.33%   |
| Fujitsu             | 1         | 1      | 3.33%   |
| Crucial             | 1         | 1      | 3.33%   |
| Corsair             | 1         | 1      | 3.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 6         | 9      | 33.33%  |
| Seagate | 5         | 5      | 27.78%  |
| WDC     | 3         | 3      | 16.67%  |
| HGST    | 2         | 3      | 11.11%  |
| Toshiba | 1         | 1      | 5.56%   |
| Fujitsu | 1         | 1      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 18        | 22     | 60%     |
| SSD  | 11        | 16     | 36.67%  |
| NVMe | 1         | 1      | 3.33%   |

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
| Works    | 243       | 346    | 84.38%  |
| Malfunc  | 30        | 39     | 10.42%  |
| Detected | 15        | 25     | 5.21%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 204       | 62.96%  |
| Samsung Electronics              | 38        | 11.73%  |
| AMD                              | 21        | 6.48%   |
| Transcend                        | 15        | 4.63%   |
| SanDisk                          | 10        | 3.09%   |
| Micron Technology                | 6         | 1.85%   |
| Toshiba                          | 5         | 1.54%   |
| Nvidia                           | 4         | 1.23%   |
| Phison Electronics               | 3         | 0.93%   |
| Micron/Crucial Technology        | 3         | 0.93%   |
| KIOXIA                           | 3         | 0.93%   |
| Kingston Technology Company      | 3         | 0.93%   |
| SK hynix                         | 2         | 0.62%   |
| Silicon Motion                   | 2         | 0.62%   |
| ADATA Technology                 | 2         | 0.62%   |
| ULi Electronics                  | 1         | 0.31%   |
| Silicon Integrated Systems [SiS] | 1         | 0.31%   |
| Lenovo                           | 1         | 0.31%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 28        | 8.16%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 24        | 7%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 23        | 6.71%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 21        | 6.12%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 19        | 5.54%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 16        | 4.66%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 12        | 3.5%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 11        | 3.21%   |
| Transcend NVMe PCIe SSD 120S/112S (DRAM-less)                                          | 10        | 2.92%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 10        | 2.92%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 9         | 2.62%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 8         | 2.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 8         | 2.33%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 7         | 2.04%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 7         | 2.04%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 6         | 1.75%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 5         | 1.46%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 5         | 1.46%   |
| Samsung NVMe SSD Controller 980                                                        | 5         | 1.46%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 5         | 1.46%   |
| Unknown                                                                                | 5         | 1.46%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 4         | 1.17%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                             | 3         | 0.87%   |
| Nvidia MCP79 AHCI Controller                                                           | 3         | 0.87%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                            | 3         | 0.87%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                             | 3         | 0.87%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 3         | 0.87%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 3         | 0.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 3         | 0.87%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 3         | 0.87%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 3         | 0.87%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 3         | 0.87%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 3         | 0.87%   |
| Toshiba XG6 NVMe SSD Controller                                                        | 2         | 0.58%   |
| Toshiba XG5 NVMe SSD Controller                                                        | 2         | 0.58%   |
| Phison E12 NVMe Controller                                                             | 2         | 0.58%   |
| Micron 2200S NVMe SSD [Cassandra]                                                      | 2         | 0.58%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 2         | 0.58%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 2         | 0.58%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 2         | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 213       | 64.94%  |
| NVMe | 80        | 24.39%  |
| IDE  | 28        | 8.54%   |
| RAID | 7         | 2.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 240       | 84.21%  |
| AMD     | 44        | 15.44%  |
| PowerPC | 1         | 0.35%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| AMD Ryzen Embedded V1500B              | 15        | 5.24%   |
| Intel Core i5-2520M CPU @ 2.50GHz      | 10        | 3.5%    |
| Intel Core i5-6300U CPU @ 2.40GHz      | 9         | 3.15%   |
| Intel CPU Version                      | 7         | 2.45%   |
| Intel Core i5-3320M CPU @ 2.60GHz      | 7         | 2.45%   |
| Intel Core i7-8550U CPU @ 1.80GHz      | 6         | 2.1%    |
| Intel Core i7-3520M CPU @ 2.90GHz      | 6         | 2.1%    |
| Intel Core i5-5300U CPU @ 2.30GHz      | 6         | 2.1%    |
| AMD EPYC 3201 8-Core Processor         | 6         | 2.1%    |
| Intel Core i5-3317U CPU @ 1.70GHz      | 5         | 1.75%   |
| Intel Core i5-3230M CPU @ 2.60GHz      | 5         | 1.75%   |
| Intel Core i3-4005U CPU @ 1.70GHz      | 5         | 1.75%   |
| Intel Core i5-6200U CPU @ 2.30GHz      | 4         | 1.4%    |
| Intel Core i5 CPU M 560 @ 2.67GHz      | 4         | 1.4%    |
| AMD Ryzen 7 4800H with Radeon Graphics | 4         | 1.4%    |
| Intel Core i7-9750H CPU @ 2.60GHz      | 3         | 1.05%   |
| Intel Core i7-8565U CPU @ 1.80GHz      | 3         | 1.05%   |
| Intel Core i7-7500U CPU @ 2.70GHz      | 3         | 1.05%   |
| Intel Core i5-8250U CPU @ 1.60GHz      | 3         | 1.05%   |
| Intel Core i5-5200U CPU @ 2.20GHz      | 3         | 1.05%   |
| Intel Core i5-4250U CPU @ 1.30GHz      | 3         | 1.05%   |
| Intel Core i5-4210U CPU @ 1.70GHz      | 3         | 1.05%   |
| Intel Core 2 Duo                       | 3         | 1.05%   |
| Intel Celeron CPU 1037U @ 1.80GHz      | 3         | 1.05%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz   | 2         | 0.7%    |
| Intel Pentium 3558U @ 1.70GHz          | 2         | 0.7%    |
| Intel Genuine CPU                      | 2         | 0.7%    |
| Intel Core i7-8750H CPU @ 2.20GHz      | 2         | 0.7%    |
| Intel Core i7-8650U CPU @ 1.90GHz      | 2         | 0.7%    |
| Intel Core i7-6600U CPU @ 2.60GHz      | 2         | 0.7%    |
| Intel Core i7-4810MQ CPU @ 2.80GHz     | 2         | 0.7%    |
| Intel Core i7-4610M CPU @ 3.00GHz      | 2         | 0.7%    |
| Intel Core i7-2860QM CPU @ 2.50GHz     | 2         | 0.7%    |
| Intel Core i7-2677M CPU @ 1.80GHz      | 2         | 0.7%    |
| Intel Core i7-10510U CPU @ 1.80GHz     | 2         | 0.7%    |
| Intel Core i5-8400H CPU @ 2.50GHz      | 2         | 0.7%    |
| Intel Core i5-8265U CPU @ 1.60GHz      | 2         | 0.7%    |
| Intel Core i5-7300U CPU @ 2.60GHz      | 2         | 0.7%    |
| Intel Core i5-7200U CPU @ 2.50GHz      | 2         | 0.7%    |
| Intel Core i5-4300U CPU @ 1.90GHz      | 2         | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 93        | 32.63%  |
| Intel Core i7        | 55        | 19.3%   |
| Other                | 21        | 7.37%   |
| Intel Core 2 Duo     | 16        | 5.61%   |
| AMD Ryzen Embedded   | 15        | 5.26%   |
| Intel Core i3        | 14        | 4.91%   |
| Intel Celeron        | 14        | 4.91%   |
| AMD Ryzen 7          | 9         | 3.16%   |
| Intel Pentium        | 7         | 2.46%   |
| AMD Ryzen 5          | 7         | 2.46%   |
| AMD EPYC             | 7         | 2.46%   |
| Intel Atom           | 5         | 1.75%   |
| Intel Xeon           | 3         | 1.05%   |
| Intel Pentium M      | 3         | 1.05%   |
| Intel Genuine        | 3         | 1.05%   |
| Intel Pentium Silver | 2         | 0.7%    |
| Intel Pentium Dual   | 1         | 0.35%   |
| Intel Pentium 4      | 1         | 0.35%   |
| Intel Core m3        | 1         | 0.35%   |
| Intel Core M         | 1         | 0.35%   |
| Intel Core 2 Solo    | 1         | 0.35%   |
| Intel Core 2         | 1         | 0.35%   |
| Intel Celeron M      | 1         | 0.35%   |
| AMD Ryzen 7 PRO      | 1         | 0.35%   |
| AMD GX               | 1         | 0.35%   |
| AMD E2               | 1         | 0.35%   |
| AMD A6               | 1         | 0.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 141       | 49.3%   |
| 4       | 66        | 23.08%  |
| 8       | 27        | 9.44%   |
| Unknown | 21        | 7.34%   |
| 1       | 10        | 3.5%    |
| 16      | 9         | 3.15%   |
| 6       | 7         | 2.45%   |
| 12      | 4         | 1.4%    |
| 10      | 1         | 0.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 274       | 95.8%   |
| 2       | 6         | 2.1%    |
| Unknown | 6         | 2.1%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 181       | 63.51%  |
| 1       | 75        | 26.32%  |
| Unknown | 29        | 10.18%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 43        | 15.09%  |
| Haswell       | 32        | 11.23%  |
| IvyBridge     | 30        | 10.53%  |
| SandyBridge   | 28        | 9.82%   |
| Zen           | 22        | 7.72%   |
| Penryn        | 20        | 7.02%   |
| Skylake       | 17        | 5.96%   |
| Broadwell     | 14        | 4.91%   |
| Unknown       | 12        | 4.21%   |
| Westmere      | 8         | 2.81%   |
| TigerLake     | 8         | 2.81%   |
| Silvermont    | 7         | 2.46%   |
| Core          | 7         | 2.46%   |
| Zen 2         | 6         | 2.11%   |
| Bonnell       | 5         | 1.75%   |
| Zen+          | 4         | 1.4%    |
| P6            | 4         | 1.4%    |
| Zen 3         | 3         | 1.05%   |
| Goldmont plus | 3         | 1.05%   |
| Goldmont      | 3         | 1.05%   |
| Puma          | 2         | 0.7%    |
| NetBurst      | 2         | 0.7%    |
| Piledriver    | 1         | 0.35%   |
| IceLake       | 1         | 0.35%   |
| Geode         | 1         | 0.35%   |
| CometLake     | 1         | 0.35%   |
| Bobcat        | 1         | 0.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 216       | 72.24%  |
| Nvidia                           | 52        | 17.39%  |
| AMD                              | 29        | 9.7%    |
| Trident Microsystems             | 1         | 0.33%   |
| Silicon Integrated Systems [SiS] | 1         | 0.33%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 30        | 9.74%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 26        | 8.44%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 20        | 6.49%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 16        | 5.19%   |
| Intel UHD Graphics 620                                                                   | 11        | 3.57%   |
| Intel HD Graphics 5500                                                                   | 11        | 3.57%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 10        | 3.25%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 10        | 3.25%   |
| Intel Core Processor Integrated Graphics Controller                                      | 9         | 2.92%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 9         | 2.92%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 8         | 2.6%    |
| Intel HD Graphics 620                                                                    | 7         | 2.27%   |
| AMD Renoir                                                                               | 6         | 1.95%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 1.62%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 1.62%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 1.62%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 1.3%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 1.3%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 1.3%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 1.3%    |
| AMD Lucienne                                                                             | 4         | 1.3%    |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 0.97%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                    | 3         | 0.97%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 0.97%   |
| Nvidia C79 [GeForce 9400M]                                                               | 3         | 0.97%   |
| Intel HD Graphics 500                                                                    | 3         | 0.97%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 0.97%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 0.97%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 0.97%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.65%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.65%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 2         | 0.65%   |
| Nvidia G98M [Quadro NVS 160M]                                                            | 2         | 0.65%   |
| Nvidia G84M [GeForce 8600M GT]                                                           | 2         | 0.65%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 0.65%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.65%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 0.65%   |
| Intel HD Graphics P630                                                                   | 2         | 0.65%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 0.65%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 158       | 55.24%  |
| Intel + Nvidia           | 29        | 10.14%  |
| Other                    | 24        | 8.39%   |
| 2 x Intel                | 23        | 8.04%   |
| 1 x Nvidia               | 21        | 7.34%   |
| 1 x AMD                  | 20        | 6.99%   |
| Intel + AMD              | 6         | 2.1%    |
| AMD + Nvidia             | 3         | 1.05%   |
| 1 x Trident Microsystems | 1         | 0.35%   |
| 1 x SiS                  | 1         | 0.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 235       | 81.03%  |
| Unknown     | 38        | 13.1%   |
| Proprietary | 17        | 5.86%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 268       | 92.73%  |
| 0.01-0.5   | 10        | 3.46%   |
| 7.01-8.0   | 4         | 1.38%   |
| 1.01-2.0   | 4         | 1.38%   |
| 3.01-4.0   | 3         | 1.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 34        | 19.21%  |
| LG Display           | 32        | 18.08%  |
| Chimei Innolux       | 17        | 9.6%    |
| Apple                | 14        | 7.91%   |
| Samsung Electronics  | 13        | 7.34%   |
| BOE                  | 13        | 7.34%   |
| Lenovo               | 12        | 6.78%   |
| Sharp                | 6         | 3.39%   |
| Dell                 | 6         | 3.39%   |
| InfoVision           | 4         | 2.26%   |
| PANDA                | 3         | 1.69%   |
| Goldstar             | 3         | 1.69%   |
| AOC                  | 3         | 1.69%   |
| Iiyama               | 2         | 1.13%   |
| BenQ                 | 2         | 1.13%   |
| Ancor Communications | 2         | 1.13%   |
| Unknown              | 2         | 1.13%   |
| TRU                  | 1         | 0.56%   |
| Toshiba              | 1         | 0.56%   |
| Panasonic            | 1         | 0.56%   |
| LTM                  | 1         | 0.56%   |
| LG Philips           | 1         | 0.56%   |
| JDI                  | 1         | 0.56%   |
| Hewlett-Packard      | 1         | 0.56%   |
| Eizo                 | 1         | 0.56%   |
| CSO                  | 1         | 0.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                  | 5         | 2.81%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch  | 3         | 1.69%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch               | 3         | 1.69%   |
| BOE LCD Monitor BOE05E0 1366x768 280x160mm 12.7-inch                  | 3         | 1.69%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch        | 3         | 1.69%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch         | 3         | 1.69%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch         | 3         | 1.69%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 290x170mm 13.2-inch               | 2         | 1.12%   |
| PANDA LCD Monitor NCP002D 1920x1080 340x190mm 15.3-inch               | 2         | 1.12%   |
| LG Display LCD Monitor LGD057E 1920x1080 340x190mm 15.3-inch          | 2         | 1.12%   |
| LG Display LCD Monitor LGD04A3 1366x768 280x160mm 12.7-inch           | 2         | 1.12%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch          | 2         | 1.12%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch           | 2         | 1.12%   |
| LG Display LCD Monitor LGD0353 1366x768 350x190mm 15.7-inch           | 2         | 1.12%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch           | 2         | 1.12%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch              | 2         | 1.12%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch               | 2         | 1.12%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch      | 2         | 1.12%   |
| AU Optronics LCD Monitor AUO8074 1280x800 330x210mm 15.4-inch         | 2         | 1.12%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch        | 2         | 1.12%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 340x190mm 15.3-inch        | 2         | 1.12%   |
| Unknown                                                               | 2         | 1.12%   |
| TRU LCD Monitor TRU235C 1366x768 260x140mm 11.6-inch                  | 1         | 0.56%   |
| Toshiba TV TSB0108 1360x768 700x390mm 31.5-inch                       | 1         | 0.56%   |
| Sharp LCD Monitor SHP14F9 1920x1200 290x180mm 13.4-inch               | 1         | 0.56%   |
| Sharp LCD Monitor SHP14BA 1920x1080 340x190mm 15.3-inch               | 1         | 0.56%   |
| Sharp LCD Monitor SHP143A 3840x2160 350x190mm 15.7-inch               | 1         | 0.56%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch               | 1         | 0.56%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch     | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC504B 1600x900 380x210mm 17.1-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 340x190mm 15.3-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC3143 1366x768 310x180mm 14.1-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 340x190mm 15.3-inch | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 340x190mm 15.3-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC374A 3200x1800 290x170mm 13.2-inch | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC324A 1366x768 290x170mm 13.2-inch  | 1         | 0.56%   |
| PANDA LM133LF5L01 NCP0020 1920x1080 290x170mm 13.2-inch               | 1         | 0.56%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch          | 1         | 0.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 57        | 32.57%  |
| 1366x768 (WXGA)    | 53        | 30.29%  |
| 1280x800 (WXGA)    | 11        | 6.29%   |
| 3840x2160 (4K)     | 10        | 5.71%   |
| 1600x900 (HD+)     | 10        | 5.71%   |
| 2560x1440 (QHD)    | 7         | 4%      |
| 1920x1200 (WUXGA)  | 6         | 3.43%   |
| 1440x900 (WXGA+)   | 5         | 2.86%   |
| 3200x1800 (QHD+)   | 2         | 1.14%   |
| 2880x1800          | 2         | 1.14%   |
| 2560x1600          | 2         | 1.14%   |
| 1024x768 (XGA)     | 2         | 1.14%   |
| 9600x2160          | 1         | 0.57%   |
| 720x1280           | 1         | 0.57%   |
| 3000x2000          | 1         | 0.57%   |
| 2880x1620          | 1         | 0.57%   |
| 2560x1080          | 1         | 0.57%   |
| 1920x540           | 1         | 0.57%   |
| 1680x1050 (WSXGA+) | 1         | 0.57%   |
| 1280x1024 (SXGA)   | 1         | 0.57%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 54        | 30.68%  |
| 15      | 49        | 27.84%  |
| 12      | 25        | 14.2%   |
| 11      | 8         | 4.55%   |
| 24      | 7         | 3.98%   |
| 17      | 7         | 3.98%   |
| 14      | 7         | 3.98%   |
| 27      | 5         | 2.84%   |
| Unknown | 5         | 2.84%   |
| 23      | 3         | 1.7%    |
| 39      | 1         | 0.57%   |
| 34      | 1         | 0.57%   |
| 32      | 1         | 0.57%   |
| 31      | 1         | 0.57%   |
| 26      | 1         | 0.57%   |
| 6       | 1         | 0.57%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 83        | 47.16%  |
| 201-300     | 61        | 34.66%  |
| 501-600     | 14        | 7.95%   |
| 351-400     | 6         | 3.41%   |
| Unknown     | 5         | 2.84%   |
| 701-800     | 2         | 1.14%   |
| 601-700     | 2         | 1.14%   |
| 801-900     | 1         | 0.57%   |
| 401-500     | 1         | 0.57%   |
| 101-200     | 1         | 0.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 132       | 78.11%  |
| 16/10   | 25        | 14.79%  |
| Unknown | 5         | 2.96%   |
| 4/3     | 3         | 1.78%   |
| 3/2     | 2         | 1.18%   |
| 5/4     | 1         | 0.59%   |
| 21/9    | 1         | 0.59%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 48        | 27.12%  |
| 91-100         | 35        | 19.77%  |
| 61-70          | 25        | 14.12%  |
| 101-110        | 15        | 8.47%   |
| 71-80          | 12        | 6.78%   |
| 51-60          | 8         | 4.52%   |
| 201-250        | 7         | 3.95%   |
| 301-350        | 6         | 3.39%   |
| 121-130        | 6         | 3.39%   |
| Unknown        | 5         | 2.82%   |
| 251-300        | 4         | 2.26%   |
| 351-500        | 3         | 1.69%   |
| 1-40           | 1         | 0.56%   |
| 141-150        | 1         | 0.56%   |
| 501-1000       | 1         | 0.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 79        | 45.93%  |
| 101-120       | 36        | 20.93%  |
| 51-100        | 22        | 12.79%  |
| 161-240       | 20        | 11.63%  |
| More than 240 | 10        | 5.81%   |
| Unknown       | 5         | 2.91%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 165       | 56.7%   |
| 0     | 109       | 37.46%  |
| 2     | 16        | 5.5%    |
| 3     | 1         | 0.34%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 209       | 46.76%  |
| Realtek Semiconductor             | 88        | 19.69%  |
| Qualcomm Atheros                  | 33        | 7.38%   |
| Broadcom                          | 32        | 7.16%   |
| AMD                               | 22        | 4.92%   |
| Ericsson Business Mobile Networks | 12        | 2.68%   |
| Ralink Technology                 | 7         | 1.57%   |
| Sierra Wireless                   | 5         | 1.12%   |
| Google                            | 5         | 1.12%   |
| Edimax Technology                 | 5         | 1.12%   |
| Nvidia                            | 4         | 0.89%   |
| Marvell Technology Group          | 3         | 0.67%   |
| ASUSTek Computer                  | 3         | 0.67%   |
| TP-Link                           | 2         | 0.45%   |
| Ralink                            | 2         | 0.45%   |
| MediaTek                          | 2         | 0.45%   |
| Dell                              | 2         | 0.45%   |
| ULi Electronics                   | 1         | 0.22%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.22%   |
| Samsung Electronics               | 1         | 0.22%   |
| National Semiconductor            | 1         | 0.22%   |
| Micro Star International          | 1         | 0.22%   |
| JMicron Technology                | 1         | 0.22%   |
| Huawei Technologies               | 1         | 0.22%   |
| Hewlett-Packard                   | 1         | 0.22%   |
| D-Link System                     | 1         | 0.22%   |
| Aquantia                          | 1         | 0.22%   |
| Apple                             | 1         | 0.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 68        | 11.83%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 33        | 5.74%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 22        | 3.83%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0                   | 22        | 3.83%   |
| Intel I210 Gigabit Network Connection                                       | 19        | 3.3%    |
| Intel Centrino Ultimate-N 6300                                              | 15        | 2.61%   |
| Intel Wireless 8265 / 8275                                                  | 14        | 2.43%   |
| Intel Wireless 8260                                                         | 14        | 2.43%   |
| Intel Wireless 7265                                                         | 14        | 2.43%   |
| Intel I211 Gigabit Network Connection                                       | 13        | 2.26%   |
| Intel Wi-Fi 6 AX200                                                         | 12        | 2.09%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 11        | 1.91%   |
| Intel Wireless 7260                                                         | 11        | 1.91%   |
| Intel Ethernet Connection I219-LM                                           | 11        | 1.91%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 8         | 1.39%   |
| Intel Ethernet Connection I217-LM                                           | 8         | 1.39%   |
| Intel 82577LM Gigabit Network Connection                                    | 8         | 1.39%   |
| Intel Wi-Fi 6 AX201                                                         | 7         | 1.22%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III | 7         | 1.22%   |
| Broadcom BCM43224 802.11a/b/g/n                                             | 7         | 1.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 6         | 1.04%   |
| Intel Ethernet Connection (3) I218-LM                                       | 6         | 1.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 5         | 0.87%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                      | 5         | 0.87%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 5         | 0.87%   |
| Intel Ethernet Connection (4) I219-V                                        | 5         | 0.87%   |
| Intel Ethernet Connection (4) I219-LM                                       | 5         | 0.87%   |
| Google Nexus/Pixel Device (tether)                                          | 5         | 0.87%   |
| Sierra Wireless EM7455                                                      | 4         | 0.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 4         | 0.7%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 4         | 0.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 4         | 0.7%    |
| Intel Wireless-AC 9260                                                      | 4         | 0.7%    |
| Intel Wireless 3165                                                         | 4         | 0.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                            | 4         | 0.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                             | 4         | 0.7%    |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]              | 4         | 0.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                  | 3         | 0.52%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                            | 3         | 0.52%   |
| Nvidia MCP79 Ethernet                                                       | 3         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 167       | 62.31%  |
| Qualcomm Atheros         | 28        | 10.45%  |
| Broadcom                 | 24        | 8.96%   |
| Realtek Semiconductor    | 22        | 8.21%   |
| Ralink Technology        | 7         | 2.61%   |
| Sierra Wireless          | 5         | 1.87%   |
| Edimax Technology        | 5         | 1.87%   |
| ASUSTek Computer         | 3         | 1.12%   |
| TP-Link                  | 2         | 0.75%   |
| Ralink                   | 2         | 0.75%   |
| MediaTek                 | 2         | 0.75%   |
| Micro Star International | 1         | 0.37%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 22        | 8.18%   |
| Intel Centrino Ultimate-N 6300                                 | 15        | 5.58%   |
| Intel Wireless 8265 / 8275                                     | 14        | 5.2%    |
| Intel Wireless 8260                                            | 14        | 5.2%    |
| Intel Wireless 7265                                            | 14        | 5.2%    |
| Intel Wi-Fi 6 AX200                                            | 12        | 4.46%   |
| Intel Wireless 7260                                            | 11        | 4.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 8         | 2.97%   |
| Intel Wi-Fi 6 AX201                                            | 7         | 2.6%    |
| Broadcom BCM43224 802.11a/b/g/n                                | 7         | 2.6%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6         | 2.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 5         | 1.86%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 5         | 1.86%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 5         | 1.86%   |
| Sierra Wireless EM7455                                         | 4         | 1.49%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 4         | 1.49%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 4         | 1.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4         | 1.49%   |
| Intel Wireless-AC 9260                                         | 4         | 1.49%   |
| Intel Wireless 3165                                            | 4         | 1.49%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 4         | 1.49%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 4         | 1.49%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 4         | 1.49%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 1.12%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 1.12%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 3         | 1.12%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 3         | 1.12%   |
| Intel Centrino Advanced-N 6200                                 | 3         | 1.12%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 3         | 1.12%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2         | 0.74%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 0.74%   |
| Ralink RT5572 Wireless Adapter                                 | 2         | 0.74%   |
| Ralink RT5370 Wireless Adapter                                 | 2         | 0.74%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 2         | 0.74%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 0.74%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 0.74%   |
| Intel WiFi Link 5100                                           | 2         | 0.74%   |
| Intel Ultimate N WiFi Link 5300                                | 2         | 0.74%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 2         | 0.74%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 140       | 49.47%  |
| Realtek Semiconductor    | 82        | 28.98%  |
| AMD                      | 22        | 7.77%   |
| Broadcom                 | 14        | 4.95%   |
| Qualcomm Atheros         | 8         | 2.83%   |
| Google                   | 5         | 1.77%   |
| Nvidia                   | 4         | 1.41%   |
| Marvell Technology Group | 3         | 1.06%   |
| Samsung Electronics      | 1         | 0.35%   |
| National Semiconductor   | 1         | 0.35%   |
| JMicron Technology       | 1         | 0.35%   |
| Aquantia                 | 1         | 0.35%   |
| Apple                    | 1         | 0.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 68        | 23.86%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 33        | 11.58%  |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0         | 22        | 7.72%   |
| Intel I210 Gigabit Network Connection                             | 19        | 6.67%   |
| Intel I211 Gigabit Network Connection                             | 13        | 4.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 3.86%   |
| Intel Ethernet Connection I219-LM                                 | 11        | 3.86%   |
| Intel Ethernet Connection I217-LM                                 | 8         | 2.81%   |
| Intel 82577LM Gigabit Network Connection                          | 8         | 2.81%   |
| Intel Ethernet Connection (3) I218-LM                             | 6         | 2.11%   |
| Intel Ethernet Connection (4) I219-V                              | 5         | 1.75%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 1.75%   |
| Google Nexus/Pixel Device (tether)                                | 5         | 1.75%   |
| Nvidia MCP79 Ethernet                                             | 3         | 1.05%   |
| Intel Ethernet Connection I219-V                                  | 3         | 1.05%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.05%   |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 1.05%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.05%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 1.05%   |
| Intel 82566MM Gigabit Network Connection                          | 3         | 1.05%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 3         | 1.05%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.7%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.7%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 0.7%    |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.7%    |
| Intel Ethernet Connection (10) I219-V                             | 2         | 0.7%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 0.7%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 0.7%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.35%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.35%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.35%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.35%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.35%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.35%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.35%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.35%   |
| Nvidia MCP89 Ethernet                                             | 1         | 0.35%   |
| National DP83815 (MacPhyter) Ethernet Controller                  | 1         | 0.35%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.35%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 258       | 49.52%  |
| WiFi     | 241       | 46.26%  |
| Modem    | 11        | 2.11%   |
| Unknown  | 11        | 2.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 205       | 56.47%  |
| WiFi     | 150       | 41.32%  |
| Unknown  | 7         | 1.93%   |
| Modem    | 1         | 0.28%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 201       | 70.28%  |
| 1     | 44        | 15.38%  |
| 5     | 15        | 5.24%   |
| 6     | 14        | 4.9%    |
| 3     | 7         | 2.45%   |
| 0     | 2         | 0.7%    |
| 8     | 1         | 0.35%   |
| 7     | 1         | 0.35%   |
| 4     | 1         | 0.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 251       | 87.15%  |
| Yes  | 37        | 12.85%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 84        | 51.85%  |
| Broadcom                        | 20        | 12.35%  |
| Apple                           | 15        | 9.26%   |
| Qualcomm Atheros Communications | 13        | 8.02%   |
| Realtek Semiconductor           | 8         | 4.94%   |
| Foxconn / Hon Hai               | 6         | 3.7%    |
| Lite-On Technology              | 3         | 1.85%   |
| Dell                            | 3         | 1.85%   |
| IMC Networks                    | 2         | 1.23%   |
| Hewlett-Packard                 | 2         | 1.23%   |
| Cambridge Silicon Radio         | 2         | 1.23%   |
| ASUSTek Computer                | 2         | 1.23%   |
| Alps Electric                   | 2         | 1.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 40        | 24.69%  |
| Intel AX200 Bluetooth                                       | 13        | 8.02%   |
| Intel AX201 Bluetooth                                       | 10        | 6.17%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 9         | 5.56%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 7         | 4.32%   |
| Apple Bluetooth Host Controller                             | 7         | 4.32%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 6         | 3.7%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 5         | 3.09%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 4         | 2.47%   |
| Intel Wireless-AC 3168 Bluetooth                            | 4         | 2.47%   |
| Intel AX210 Bluetooth                                       | 4         | 2.47%   |
| Lite-On Atheros AR3012 Bluetooth                            | 3         | 1.85%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 3         | 1.85%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 3         | 1.85%   |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 1.23%   |
| Realtek Bluetooth 4.2 Adapter                               | 2         | 1.23%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 2         | 1.23%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 2         | 1.23%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 2         | 1.23%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 2         | 1.23%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2         | 1.23%   |
| Apple Broadcom Built-in Bluetooth                           | 2         | 1.23%   |
| Realtek RTL8821A Bluetooth                                  | 1         | 0.62%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 0.62%   |
| Realtek Bluetooth Adapter                                   | 1         | 0.62%   |
| Realtek Bluetooth 4.0 + High Speed Chip                     | 1         | 0.62%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 1         | 0.62%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 0.62%   |
| Qualcomm Atheros Dell Wireless 1802 Bluetooth 4.0 LE        | 1         | 0.62%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 0.62%   |
| Qualcomm Atheros Bluetooth                                  | 1         | 0.62%   |
| Intel Wireless Bluetooth                                    | 1         | 0.62%   |
| IMC Networks Bluetooth Module                               | 1         | 0.62%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 1         | 0.62%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 0.62%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter                  | 1         | 0.62%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 0.62%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device             | 1         | 0.62%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device    | 1         | 0.62%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 1         | 0.62%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 230       | 75.91%  |
| AMD                                          | 42        | 13.86%  |
| Nvidia                                       | 20        | 6.6%    |
| Realtek Semiconductor                        | 2         | 0.66%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.33%   |
| ULi Electronics                              | 1         | 0.33%   |
| Texas Instruments                            | 1         | 0.33%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.33%   |
| Phison Electronics                           | 1         | 0.33%   |
| Logitech                                     | 1         | 0.33%   |
| Lenovo                                       | 1         | 0.33%   |
| Hewlett-Packard                              | 1         | 0.33%   |
| GN Netcom                                    | 1         | 0.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 34        | 9.42%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 32        | 8.86%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 31        | 8.59%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 26        | 7.2%    |
| Intel 8 Series HD Audio Controller                                                                | 20        | 5.54%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 19        | 5.26%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 14        | 3.88%   |
| Intel Broadwell-U Audio Controller                                                                | 14        | 3.88%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 13        | 3.6%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 11        | 3.05%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 11        | 3.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 10        | 2.77%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 10        | 2.77%   |
| Intel Cannon Lake PCH cAVS                                                                        | 9         | 2.49%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 9         | 2.49%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 8         | 2.22%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 1.94%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 7         | 1.94%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 1.66%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.11%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1.11%   |
| Intel CM238 HD Audio Controller                                                                   | 4         | 1.11%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 0.83%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 0.83%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 0.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.83%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 0.83%   |
| AMD FCH Azalia Controller                                                                         | 3         | 0.83%   |
| Realtek Semiconductor USB Audio                                                                   | 2         | 0.55%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.55%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.55%   |
| Intel Jasper Lake HD Audio                                                                        | 2         | 0.55%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 0.55%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 2         | 0.55%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 0.55%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 1         | 0.28%   |
| ULi Electronics M5451 PCI AC-Link Controller Audio Device                                         | 1         | 0.28%   |
| Texas Instruments PCM2900 Audio Codec                                                             | 1         | 0.28%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 1         | 0.28%   |
| Phison Electronics SoundYouSoundYouSoundYouSoundYouSoundYouSoundYouSoundYouSoun                   | 1         | 0.28%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 81        | 27.55%  |
| SK hynix                     | 53        | 18.03%  |
| Kingston                     | 34        | 11.56%  |
| Micron Technology            | 27        | 9.18%   |
| Unknown                      | 24        | 8.16%   |
| Transcend                    | 21        | 7.14%   |
| Crucial                      | 13        | 4.42%   |
| Unknown                      | 9         | 3.06%   |
| Corsair                      | 8         | 2.72%   |
| Ramaxel Technology           | 7         | 2.38%   |
| Elpida                       | 5         | 1.7%    |
| Nanya Technology             | 4         | 1.36%   |
| Unknown (ABCD)               | 1         | 0.34%   |
| Unknown (0x7F7F7F94FFFFFFFF) | 1         | 0.34%   |
| Team                         | 1         | 0.34%   |
| Patriot                      | 1         | 0.34%   |
| G.Skill                      | 1         | 0.34%   |
| ASint Technology             | 1         | 0.34%   |
| A-DATA Technology            | 1         | 0.34%   |
| 48spaces                     | 1         | 0.34%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s           | 13        | 4.26%   |
| Unknown                                                       | 9         | 2.95%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s         | 7         | 2.3%    |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                  | 6         | 1.97%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 6         | 1.97%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s        | 6         | 1.97%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s         | 6         | 1.97%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s         | 5         | 1.64%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s         | 5         | 1.64%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s         | 4         | 1.31%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s         | 4         | 1.31%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s         | 4         | 1.31%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s       | 4         | 1.31%   |
| Transcend RAM TS512MLH64V6HL 4GB SODIMM DDR4 2667MT/s         | 3         | 0.98%   |
| Transcend RAM TS1GLH64V6B3 8GB SODIMM DDR4 1333MT/s           | 3         | 0.98%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 3         | 0.98%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 3         | 0.98%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s         | 3         | 0.98%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s         | 3         | 0.98%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s         | 3         | 0.98%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s         | 3         | 0.98%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s       | 3         | 0.98%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                    | 2         | 0.66%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s        | 2         | 0.66%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 2         | 0.66%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s        | 2         | 0.66%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s        | 2         | 0.66%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2400MT/s        | 2         | 0.66%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s         | 2         | 0.66%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s         | 2         | 0.66%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s         | 2         | 0.66%   |
| Ramaxel RAM RMT3020EC58E9F1333 4GB SODIMM DDR3 1333MT/s       | 2         | 0.66%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 0.66%   |
| Micron RAM 16KTF1G64HZ-1G6P1 8GB SODIMM DDR3 1600MT/s         | 2         | 0.66%   |
| Kingston RAM CBD26D4S9S8K1C-8 8GB SODIMM DDR4 2667MT/s        | 2         | 0.66%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s        | 2         | 0.66%   |
| Kingston RAM 99U5428-042.A00G 4096MB SODIMM DDR3 1334MT/s     | 2         | 0.66%   |
| Corsair RAM CMSX8GX3M1A1600C10 8GB SODIMM DDR3 1333MT/s       | 2         | 0.66%   |
| Unknown SODIMM 2048MB SODIMM DDR2 533MT/s                     | 1         | 0.33%   |
| Unknown SODIMM 1GB SODIMM DDR2 667MT/s                        | 1         | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 128       | 50%     |
| DDR4    | 89        | 34.77%  |
| DDR2    | 18        | 7.03%   |
| LPDDR4  | 6         | 2.34%   |
| LPDDR3  | 4         | 1.56%   |
| DDR     | 4         | 1.56%   |
| Unknown | 4         | 1.56%   |
| SDRAM   | 1         | 0.39%   |
| RAM     | 1         | 0.39%   |
| DRAM    | 1         | 0.39%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 240       | 93.75%  |
| Row Of Chips | 11        | 4.3%    |
| Chip         | 4         | 1.56%   |
| DIMM         | 1         | 0.39%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 110       | 40.59%  |
| 4096  | 72        | 26.57%  |
| 2048  | 46        | 16.97%  |
| 16384 | 29        | 10.7%   |
| 1024  | 9         | 3.32%   |
| 512   | 2         | 0.74%   |
| 256   | 2         | 0.74%   |
| 32768 | 1         | 0.37%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 81        | 30.22%  |
| 2667    | 40        | 14.93%  |
| 1333    | 26        | 9.7%    |
| 3200    | 21        | 7.84%   |
| 2400    | 17        | 6.34%   |
| 1334    | 16        | 5.97%   |
| 667     | 14        | 5.22%   |
| 2133    | 13        | 4.85%   |
| 1867    | 9         | 3.36%   |
| Unknown | 8         | 2.99%   |
| 800     | 7         | 2.61%   |
| 4267    | 5         | 1.87%   |
| 1067    | 5         | 1.87%   |
| 1066    | 2         | 0.75%   |
| 533     | 2         | 0.75%   |
| 2933    | 1         | 0.37%   |
| 975     | 1         | 0.37%   |

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

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 120 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 59        | 35.33%  |
| Bison Electronics                      | 18        | 10.78%  |
| Microdia                               | 12        | 7.19%   |
| Realtek Semiconductor                  | 11        | 6.59%   |
| Suyin                                  | 9         | 5.39%   |
| Lite-On Technology                     | 9         | 5.39%   |
| IMC Networks                           | 9         | 5.39%   |
| Sunplus Innovation Technology          | 7         | 4.19%   |
| Apple                                  | 6         | 3.59%   |
| Syntek                                 | 5         | 2.99%   |
| Lenovo                                 | 5         | 2.99%   |
| Alcor Micro                            | 4         | 2.4%    |
| Silicon Motion                         | 2         | 1.2%    |
| Quanta                                 | 2         | 1.2%    |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.2%    |
| Tripath Technology                     | 1         | 0.6%    |
| SunplusIT                              | 1         | 0.6%    |
| Ricoh                                  | 1         | 0.6%    |
| Pixart Imaging                         | 1         | 0.6%    |
| Luxvisions Innotech Limited            | 1         | 0.6%    |
| Logitech                               | 1         | 0.6%    |
| Cubeternet                             | 1         | 0.6%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 26        | 15.48%  |
| Chicony Lenovo Integrated Camera (0.3MP) | 7         | 4.17%   |
| Bison Integrated Camera                  | 7         | 4.17%   |
| Lite-On Integrated Camera                | 6         | 3.57%   |
| Microdia Integrated Webcam               | 5         | 2.98%   |
| Chicony FJ Camera                        | 5         | 2.98%   |
| IMC Networks Integrated Camera           | 4         | 2.38%   |
| Chicony HD Webcam                        | 4         | 2.38%   |
| Apple FaceTime HD Camera (Built-in)      | 4         | 2.38%   |
| Syntek Integrated Camera                 | 3         | 1.79%   |
| Suyin RGBIR Camera                       | 3         | 1.79%   |
| Realtek USB 2.0 PC Camera                | 3         | 1.79%   |
| Chicony Integrated Camera [ThinkPad]     | 3         | 1.79%   |
| Alcor Micro USB 2.0 Camera               | 3         | 1.79%   |
| Syntek Lenovo EasyCamera                 | 2         | 1.19%   |
| Realtek Integrated_Webcam_HD             | 2         | 1.19%   |
| Quanta HP TrueVision HD Camera           | 2         | 1.19%   |
| Microdia Integrated_Webcam_HD            | 2         | 1.19%   |
| Lite-On Realtek PC Camera                | 2         | 1.19%   |
| Lenovo Integrated Webcam [R5U877]        | 2         | 1.19%   |
| Lenovo Integrated Camera                 | 2         | 1.19%   |
| IMC Networks Realtek PC Camera           | 2         | 1.19%   |
| Chicony HD WebCam (Acer)                 | 2         | 1.19%   |
| Chicony Chicony USB2.0 Camera            | 2         | 1.19%   |
| Bison ThinkPad Integrated Camera         | 2         | 1.19%   |
| Bison SunplusIT Integrated Camera        | 2         | 1.19%   |
| Bison SunplusIT INC. Integrated Camera   | 2         | 1.19%   |
| Bison Lenovo EasyCamera                  | 2         | 1.19%   |
| Tripath USB Camera                       | 1         | 0.6%    |
| Suyin Sony Visual Communication Camera   | 1         | 0.6%    |
| Suyin Integrated Webcam                  | 1         | 0.6%    |
| Suyin HP Webcam-101                      | 1         | 0.6%    |
| Suyin HP Integrated Webcam               | 1         | 0.6%    |
| Suyin Asus Integrated Webcam             | 1         | 0.6%    |
| Suyin Acer/Lenovo Webcam [CN0316]        | 1         | 0.6%    |
| SunplusIT USB camera                     | 1         | 0.6%    |
| Sunplus SPCA2650 AV Camera               | 1         | 0.6%    |
| Sunplus Laptop_Integrated_Webcam_FHD     | 1         | 0.6%    |
| Sunplus Integrated_Webcam_HD             | 1         | 0.6%    |
| Sunplus Integrated_Webcam_FHD            | 1         | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 21        | 33.87%  |
| Upek                       | 11        | 17.74%  |
| Synaptics                  | 9         | 14.52%  |
| AuthenTec                  | 5         | 8.06%   |
| Shenzhen Goodix Technology | 4         | 6.45%   |
| LighTuning Technology      | 4         | 6.45%   |
| Broadcom                   | 3         | 4.84%   |
| STMicroelectronics         | 2         | 3.23%   |
| Elan Microelectronics      | 2         | 3.23%   |
| Next Biometrics            | 1         | 1.61%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 10        | 16.13%  |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 8         | 12.9%   |
| Validity Sensors Synaptics WBDI                                              | 5         | 8.06%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 3         | 4.84%   |
| Shenzhen Goodix Fingerprint Reader                                           | 3         | 4.84%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 4.84%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 2         | 3.23%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 2         | 3.23%   |
| Validity Sensors Swipe Fingerprint Sensor                                    | 2         | 3.23%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 2         | 3.23%   |
| STMicroelectronics Fingerprint Reader                                        | 2         | 3.23%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 2         | 3.23%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 2         | 3.23%   |
| Elan Fingerprint Sensor                                                      | 2         | 3.23%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 1         | 1.61%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 1         | 1.61%   |
| Upek TCS5B Fingerprint sensor                                                | 1         | 1.61%   |
| Synaptics WBDI                                                               | 1         | 1.61%   |
| Synaptics UWP WBDI                                                           | 1         | 1.61%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 1         | 1.61%   |
| Shenzhen Goodix Fingerprint Reader SGX                                       | 1         | 1.61%   |
| Next Biometrics NB-2020-U Fingerprint Reader                                 | 1         | 1.61%   |
| AuthenTec AES2660                                                            | 1         | 1.61%   |
| AuthenTec AES2550 Fingerprint Sensor                                         | 1         | 1.61%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 1         | 1.61%   |
| AuthenTec AES1660                                                            | 1         | 1.61%   |
| AuthenTec AES1600                                                            | 1         | 1.61%   |
| Unknown                                                                      | 1         | 1.61%   |

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
| 1     | 89        | 30.17%  |
| 2     | 75        | 25.42%  |
| 0     | 56        | 18.98%  |
| 3     | 50        | 16.95%  |
| 4     | 17        | 5.76%   |
| 5     | 6         | 2.03%   |
| 7     | 1         | 0.34%   |
| 6     | 1         | 0.34%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 194       | 42.54%  |
| Bluetooth                | 58        | 12.72%  |
| Fingerprint reader       | 53        | 11.62%  |
| Card reader              | 50        | 10.96%  |
| Net/wireless             | 43        | 9.43%   |
| Firewire controller      | 19        | 4.17%   |
| Network                  | 9         | 1.97%   |
| Graphics card            | 9         | 1.97%   |
| Net/ethernet             | 6         | 1.32%   |
| Sound                    | 5         | 1.1%    |
| Modem                    | 4         | 0.88%   |
| Storage                  | 3         | 0.66%   |
| Storage/nvme             | 1         | 0.22%   |
| Storage/ide              | 1         | 0.22%   |
| Storage/ata              | 1         | 0.22%   |

