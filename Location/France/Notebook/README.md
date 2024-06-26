BSD in France - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for BSD in France.

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

Total: 261

| Vendor    | Model                       | Probe                                                     | Date         |
|-----------|-----------------------------|-----------------------------------------------------------|--------------|
| Apple     | MacBookAir6,2               | [a9ec0cba48](https://bsd-hardware.info/?probe=a9ec0cba48) | May 02, 2024 |
| Dell      | Latitude 7490               | [e55889ef1e](https://bsd-hardware.info/?probe=e55889ef1e) | May 02, 2024 |
| Apple     | MacBookAir6,2               | [26a2dbed23](https://bsd-hardware.info/?probe=26a2dbed23) | Apr 28, 2024 |
| Apple     | MacBookAir6,2               | [126d9918f3](https://bsd-hardware.info/?probe=126d9918f3) | Apr 28, 2024 |
| Apple     | MacBookAir6,2               | [5bb2644b89](https://bsd-hardware.info/?probe=5bb2644b89) | Apr 28, 2024 |
| Apple     | MacBookAir6,2               | [2b066c44b9](https://bsd-hardware.info/?probe=2b066c44b9) | Apr 26, 2024 |
| Apple     | MacBookAir6,2               | [a206641c60](https://bsd-hardware.info/?probe=a206641c60) | Apr 26, 2024 |
| Lenovo    | ThinkPad X280 20KFCTO1WW    | [d76cb40918](https://bsd-hardware.info/?probe=d76cb40918) | Apr 23, 2024 |
| Lenovo    | ThinkPad X220 429135G       | [b681d0b406](https://bsd-hardware.info/?probe=b681d0b406) | Apr 23, 2024 |
| Apple     | MacBookAir6,2               | [fc810b38b1](https://bsd-hardware.info/?probe=fc810b38b1) | Apr 16, 2024 |
| ASUSTek   | VivoBook S14 X430UA         | [12764b3dba](https://bsd-hardware.info/?probe=12764b3dba) | Apr 14, 2024 |
| Dell      | Latitude 7490               | [38f6023f20](https://bsd-hardware.info/?probe=38f6023f20) | Apr 14, 2024 |
| Deciso    | NetBoard-A20                | [0b84a8b2a6](https://bsd-hardware.info/?probe=0b84a8b2a6) | Mar 31, 2024 |
| Apple     | MacBookPro11,1              | [58369a2ff3](https://bsd-hardware.info/?probe=58369a2ff3) | Mar 16, 2024 |
| Lenovo    | ThinkPad X220 429147U       | [0644799933](https://bsd-hardware.info/?probe=0644799933) | Mar 15, 2024 |
| Lenovo    | ThinkPad T420 4236JY2       | [0111e4442e](https://bsd-hardware.info/?probe=0111e4442e) | Mar 11, 2024 |
| Dell      | Precision 7520              | [bd40dd5305](https://bsd-hardware.info/?probe=bd40dd5305) | Feb 19, 2024 |
| Intel     | Jasper Lake Client Platf... | [6a041adf7a](https://bsd-hardware.info/?probe=6a041adf7a) | Feb 19, 2024 |
| Dell      | Latitude E6430              | [1f9f417c2f](https://bsd-hardware.info/?probe=1f9f417c2f) | Feb 18, 2024 |
| Lenovo    | ThinkPad T470 20HES0EV0A    | [05ecc99fe8](https://bsd-hardware.info/?probe=05ecc99fe8) | Feb 13, 2024 |
| Apple     | MacBookPro14,1              | [c8d68d0eec](https://bsd-hardware.info/?probe=c8d68d0eec) | Feb 01, 2024 |
| Acer      | TravelMate P645-SG          | [5765a3732f](https://bsd-hardware.info/?probe=5765a3732f) | Jan 31, 2024 |
| Acer      | TravelMate P645-SG          | [32dc9a4b1b](https://bsd-hardware.info/?probe=32dc9a4b1b) | Jan 31, 2024 |
| Lenovo    | ThinkBook 14 G6 IRL 21KG    | [a1fc491614](https://bsd-hardware.info/?probe=a1fc491614) | Jan 31, 2024 |
| Dell      | Precision 7510              | [b5d52d8750](https://bsd-hardware.info/?probe=b5d52d8750) | Jan 16, 2024 |
| Razer     | Blade 16 - RZ09-0483        | [d81973c8bc](https://bsd-hardware.info/?probe=d81973c8bc) | Jan 16, 2024 |
| Samsung   | N150/N210/N220              | [92c052e0d7](https://bsd-hardware.info/?probe=92c052e0d7) | Jan 14, 2024 |
| HP        | Pavilion g7                 | [25ccdb00f6](https://bsd-hardware.info/?probe=25ccdb00f6) | Jan 09, 2024 |
| ASUSTek   | VivoBook_ASUSLaptop X160... | [77d8cc2e7c](https://bsd-hardware.info/?probe=77d8cc2e7c) | Jan 02, 2024 |
| Dell      | Vostro V130                 | [44e78243c2](https://bsd-hardware.info/?probe=44e78243c2) | Dec 30, 2023 |
| Dell      | Latitude 7414               | [2d57c22982](https://bsd-hardware.info/?probe=2d57c22982) | Dec 08, 2023 |
| HP        | Pavilion g7                 | [4c1bc19902](https://bsd-hardware.info/?probe=4c1bc19902) | Dec 03, 2023 |
| Lenovo    | ThinkPad T470 20HES0EV0A    | [96562d6513](https://bsd-hardware.info/?probe=96562d6513) | Nov 20, 2023 |
| Lenovo    | ThinkPad T470 20HES0EV0A    | [5caaad73bd](https://bsd-hardware.info/?probe=5caaad73bd) | Nov 19, 2023 |
| Dell      | Latitude 5440               | [9daa44aacf](https://bsd-hardware.info/?probe=9daa44aacf) | Nov 18, 2023 |
| Lenovo    | ThinkPad X260 20F6006XUK    | [823bdd1b43](https://bsd-hardware.info/?probe=823bdd1b43) | Nov 10, 2023 |
| Dell      | Precision 7560              | [a0e5297849](https://bsd-hardware.info/?probe=a0e5297849) | Nov 09, 2023 |
| ASUSTek   | N73SV                       | [31fff3e92b](https://bsd-hardware.info/?probe=31fff3e92b) | Oct 21, 2023 |
| ASUSTek   | N73SV                       | [30726f25a0](https://bsd-hardware.info/?probe=30726f25a0) | Oct 21, 2023 |
| Lenovo    | ThinkPad X1 Carbon 3rd 2... | [0f3cd5aa25](https://bsd-hardware.info/?probe=0f3cd5aa25) | Oct 13, 2023 |
| Lenovo    | ThinkPad X260 20F6006XUK    | [25fecdaad5](https://bsd-hardware.info/?probe=25fecdaad5) | Oct 03, 2023 |
| ASUSTek   | ZenBook UX333FA_UX333FA     | [d331bd9a11](https://bsd-hardware.info/?probe=d331bd9a11) | Sep 08, 2023 |
| ASUSTek   | ASUS TUF Dash F15 FX517Z... | [cbde759aa2](https://bsd-hardware.info/?probe=cbde759aa2) | Sep 07, 2023 |
| ASUSTek   | ASUS TUF Dash F15 FX517Z... | [22ec8197cc](https://bsd-hardware.info/?probe=22ec8197cc) | Sep 07, 2023 |
| Unknown   | Unknown                     | [516b89740b](https://bsd-hardware.info/?probe=516b89740b) | Sep 06, 2023 |
| Unknown   | Unknown                     | [084127fd8b](https://bsd-hardware.info/?probe=084127fd8b) | Sep 06, 2023 |
| Lenovo    | ThinkPad X260 20F6006XUK    | [e4f0ac6bb9](https://bsd-hardware.info/?probe=e4f0ac6bb9) | Sep 03, 2023 |
| Lenovo    | ThinkPad X260 20F6006XUK    | [4bce25bd89](https://bsd-hardware.info/?probe=4bce25bd89) | Sep 03, 2023 |
| Deciso    | NetBoard-A20                | [bf4ed827a5](https://bsd-hardware.info/?probe=bf4ed827a5) | Aug 31, 2023 |
| Getac     | V110G2                      | [884803a6bd](https://bsd-hardware.info/?probe=884803a6bd) | Aug 25, 2023 |
| Lenovo    | ThinkPad T460p 20FXS06A1... | [378d093019](https://bsd-hardware.info/?probe=378d093019) | Aug 15, 2023 |
| Unknown   | Unknown                     | [4176afcb0d](https://bsd-hardware.info/?probe=4176afcb0d) | Aug 13, 2023 |
| Lenovo    | ThinkPad T60 1951CZ1        | [46766bc381](https://bsd-hardware.info/?probe=46766bc381) | Aug 11, 2023 |
| Notebook  | N7x0WU                      | [418b98798e](https://bsd-hardware.info/?probe=418b98798e) | Aug 09, 2023 |
| Notebook  | N7x0WU                      | [60d49b408a](https://bsd-hardware.info/?probe=60d49b408a) | Aug 09, 2023 |
| Chuwi     | CoreBook X                  | [2854f97c81](https://bsd-hardware.info/?probe=2854f97c81) | Aug 01, 2023 |
| Deciso    | NetBoard-A20                | [c4a85b9853](https://bsd-hardware.info/?probe=c4a85b9853) | Jul 18, 2023 |
| HP        | Stream Laptop 14-ds0xxx     | [81bbc73e72](https://bsd-hardware.info/?probe=81bbc73e72) | Jun 18, 2023 |
| Unknown   | Unknown                     | [422b9d51a7](https://bsd-hardware.info/?probe=422b9d51a7) | Jun 06, 2023 |
| Dell      | System XPS L702X            | [f56d7090f9](https://bsd-hardware.info/?probe=f56d7090f9) | May 28, 2023 |
| Deciso    | NetBoard-A20                | [0c5fd49340](https://bsd-hardware.info/?probe=0c5fd49340) | May 25, 2023 |
| Dell      | System XPS L702X            | [857016be75](https://bsd-hardware.info/?probe=857016be75) | May 24, 2023 |
| HP        | EliteBook 8570p             | [b5f17b6bf8](https://bsd-hardware.info/?probe=b5f17b6bf8) | May 23, 2023 |
| Deciso    | NetBoard-A20                | [313796fd3e](https://bsd-hardware.info/?probe=313796fd3e) | May 18, 2023 |
| Alienware | 17 R4                       | [df734c8e64](https://bsd-hardware.info/?probe=df734c8e64) | May 14, 2023 |
| Notebook  | N7x0WU                      | [7a646e185a](https://bsd-hardware.info/?probe=7a646e185a) | May 09, 2023 |
| Lenovo    | G500 20236                  | [e7387bfd6e](https://bsd-hardware.info/?probe=e7387bfd6e) | Apr 23, 2023 |
| Dell      | Latitude 7410               | [d5c047907d](https://bsd-hardware.info/?probe=d5c047907d) | Apr 19, 2023 |
| Deciso    | NetBoard-A20                | [33ca458105](https://bsd-hardware.info/?probe=33ca458105) | Mar 30, 2023 |
| Intel     | H81U                        | [af9a6469c9](https://bsd-hardware.info/?probe=af9a6469c9) | Mar 24, 2023 |
| Lenovo    | G500 20236                  | [55dc82af1c](https://bsd-hardware.info/?probe=55dc82af1c) | Mar 20, 2023 |
| Acer      | Swift SF314-56              | [94c7da1b3f](https://bsd-hardware.info/?probe=94c7da1b3f) | Mar 13, 2023 |
| Sony      | VGN-FZ19VN                  | [73809d943a](https://bsd-hardware.info/?probe=73809d943a) | Mar 13, 2023 |
| Dell      | Precision 7720              | [01f5f21b76](https://bsd-hardware.info/?probe=01f5f21b76) | Mar 12, 2023 |
| Intel     | Jasper Lake Client Platf... | [88de48013c](https://bsd-hardware.info/?probe=88de48013c) | Mar 10, 2023 |
| Intel     | Jasper Lake Client Platf... | [de93a79b7d](https://bsd-hardware.info/?probe=de93a79b7d) | Mar 10, 2023 |
| Lenovo    | ThinkPad T495 20NKS0HN1N    | [af190c38e9](https://bsd-hardware.info/?probe=af190c38e9) | Mar 10, 2023 |
| Lenovo    | ThinkPad T470 20HES0EV0A    | [dd6c3fa0f7](https://bsd-hardware.info/?probe=dd6c3fa0f7) | Mar 10, 2023 |
| Fujitsu   | CELSIUS H730                | [d2292bbcda](https://bsd-hardware.info/?probe=d2292bbcda) | Mar 10, 2023 |
| Fujitsu   | CELSIUS H730                | [223879138d](https://bsd-hardware.info/?probe=223879138d) | Mar 10, 2023 |
| HP        | EliteBook 2530p             | [e70d97f7d6](https://bsd-hardware.info/?probe=e70d97f7d6) | Mar 09, 2023 |
| Dell      | Latitude D620               | [8b3ad4e8b9](https://bsd-hardware.info/?probe=8b3ad4e8b9) | Mar 09, 2023 |
| Dell      | Latitude D620               | [d42a8ee079](https://bsd-hardware.info/?probe=d42a8ee079) | Mar 09, 2023 |
| Lenovo    | ThinkPad L14 Gen 3 21C5C... | [2ab690000c](https://bsd-hardware.info/?probe=2ab690000c) | Feb 25, 2023 |
| Lenovo    | ThinkPad L14 Gen 3 21C5C... | [ae0dc68ba6](https://bsd-hardware.info/?probe=ae0dc68ba6) | Feb 25, 2023 |
| Lenovo    | ThinkPad L14 Gen 3 21C5C... | [aef791947c](https://bsd-hardware.info/?probe=aef791947c) | Feb 23, 2023 |
| Lenovo    | ThinkPad X280 20KFCTO1WW    | [3dae7e3ebb](https://bsd-hardware.info/?probe=3dae7e3ebb) | Feb 23, 2023 |
| Lenovo    | ThinkPad L14 Gen 3 21C5C... | [6669622646](https://bsd-hardware.info/?probe=6669622646) | Feb 23, 2023 |
| Deciso    | NetBoard-A20                | [d23ae47425](https://bsd-hardware.info/?probe=d23ae47425) | Feb 23, 2023 |
| Deciso    | NetBoard-A20                | [ffc9e123b4](https://bsd-hardware.info/?probe=ffc9e123b4) | Feb 14, 2023 |
| Lenovo    | ThinkPad P15 Gen 2i 20YQ... | [78a978a8d4](https://bsd-hardware.info/?probe=78a978a8d4) | Feb 06, 2023 |
| Toshiba   | PORTEGE Z930                | [5462140da0](https://bsd-hardware.info/?probe=5462140da0) | Feb 05, 2023 |
| Lenovo    | G500 20236                  | [081d22fbe2](https://bsd-hardware.info/?probe=081d22fbe2) | Jan 24, 2023 |
| Lenovo    | G500 20236                  | [a35053ad38](https://bsd-hardware.info/?probe=a35053ad38) | Jan 24, 2023 |
| Toshiba   | PORTEGE Z930                | [476203ee86](https://bsd-hardware.info/?probe=476203ee86) | Jan 23, 2023 |
| Toshiba   | PORTEGE Z930                | [4af2cc1909](https://bsd-hardware.info/?probe=4af2cc1909) | Jan 23, 2023 |
| Dell      | Latitude E6400              | [dcc804a61f](https://bsd-hardware.info/?probe=dcc804a61f) | Jan 22, 2023 |
| Dell      | Latitude E6400              | [9dd8d0184f](https://bsd-hardware.info/?probe=9dd8d0184f) | Jan 22, 2023 |
| Dell      | Precision 5540              | [683769b797](https://bsd-hardware.info/?probe=683769b797) | Jan 19, 2023 |
| Lenovo    | ThinkPad T480 20L5CTO1WW    | [4014cc42ed](https://bsd-hardware.info/?probe=4014cc42ed) | Jan 08, 2023 |
| Deciso    | Netboard A20                | [3ff47d2ce0](https://bsd-hardware.info/?probe=3ff47d2ce0) | Jan 06, 2023 |
| Lenovo    | ThinkPad X280 20KFCTO1WW    | [a9b3805c0b](https://bsd-hardware.info/?probe=a9b3805c0b) | Jan 01, 2023 |
| Lenovo    | ThinkPad T440p 20AWS0Y40... | [ce2b20b3a9](https://bsd-hardware.info/?probe=ce2b20b3a9) | Dec 13, 2022 |
| Lenovo    | ThinkPad T440p 20AWS0Y40... | [7463e05c88](https://bsd-hardware.info/?probe=7463e05c88) | Dec 12, 2022 |
| Apple     | MacBookPro14,1              | [5234a39100](https://bsd-hardware.info/?probe=5234a39100) | Dec 10, 2022 |
| Apple     | MacBookPro14,1              | [ddeb9befdf](https://bsd-hardware.info/?probe=ddeb9befdf) | Dec 03, 2022 |
| Panasonic | CF-31-5                     | [7047afaaf4](https://bsd-hardware.info/?probe=7047afaaf4) | Nov 30, 2022 |
| Medion    | E15415                      | [e467080570](https://bsd-hardware.info/?probe=e467080570) | Nov 13, 2022 |
| Dell      | Precision M4500             | [ab63467f38](https://bsd-hardware.info/?probe=ab63467f38) | Nov 03, 2022 |
| Deciso    | NetBoard-A20                | [9c133326c9](https://bsd-hardware.info/?probe=9c133326c9) | Nov 03, 2022 |
| Intel     | H81U                        | [b0e1f80338](https://bsd-hardware.info/?probe=b0e1f80338) | Oct 24, 2022 |
| Dell      | Precision M4500             | [66ded228ea](https://bsd-hardware.info/?probe=66ded228ea) | Oct 20, 2022 |
| Intel     | H81U                        | [9b212d2264](https://bsd-hardware.info/?probe=9b212d2264) | Oct 13, 2022 |
| Lenovo    | ThinkPad T590 20N4CTO1WW    | [442a743538](https://bsd-hardware.info/?probe=442a743538) | Oct 08, 2022 |
| Toshiba   | NB300                       | [c18ae50101](https://bsd-hardware.info/?probe=c18ae50101) | Oct 03, 2022 |
| TUXEDO    | Aura 15 Gen1                | [e83d522905](https://bsd-hardware.info/?probe=e83d522905) | Oct 03, 2022 |
| Dell      | Precision M4500             | [6b987b43b1](https://bsd-hardware.info/?probe=6b987b43b1) | Oct 03, 2022 |
| Dell      | Inspiron 5515               | [dca437b993](https://bsd-hardware.info/?probe=dca437b993) | Jul 01, 2022 |
| ASUSTek   | K53TA                       | [6ce39c5e61](https://bsd-hardware.info/?probe=6ce39c5e61) | Jun 27, 2022 |
| HP        | EliteBook 8440p             | [25d5a77b59](https://bsd-hardware.info/?probe=25d5a77b59) | Jun 17, 2022 |
| Alienware | M18xR2                      | [6d55881f6a](https://bsd-hardware.info/?probe=6d55881f6a) | Jun 15, 2022 |
| Apple     | MacBook5,1                  | [8ba77d7208](https://bsd-hardware.info/?probe=8ba77d7208) | Jun 13, 2022 |
| Acer      | Aspire E5-571               | [4be2393c8d](https://bsd-hardware.info/?probe=4be2393c8d) | Jun 11, 2022 |
| Lenovo    | ThinkPad T14 Gen 1 20S0C... | [56111732fd](https://bsd-hardware.info/?probe=56111732fd) | Jun 07, 2022 |
| Lenovo    | ThinkPad T14 Gen 1 20S0C... | [aeec87e07f](https://bsd-hardware.info/?probe=aeec87e07f) | Jun 06, 2022 |
| Dell      | Latitude 7490               | [18215740d1](https://bsd-hardware.info/?probe=18215740d1) | Jun 05, 2022 |
| Lenovo    | ThinkPad T590 20N4CTO1WW    | [f3ad761457](https://bsd-hardware.info/?probe=f3ad761457) | Jun 04, 2022 |
| Dell      | Latitude 7490               | [22224f46f4](https://bsd-hardware.info/?probe=22224f46f4) | Jun 02, 2022 |
| Acer      | Aspire E5-576               | [138e9fdeb4](https://bsd-hardware.info/?probe=138e9fdeb4) | May 31, 2022 |
| TUXEDO    | Aura 15 Gen1                | [20814a930a](https://bsd-hardware.info/?probe=20814a930a) | May 18, 2022 |
| TUXEDO    | Aura 15 Gen1                | [115de395dd](https://bsd-hardware.info/?probe=115de395dd) | May 17, 2022 |
| TUXEDO    | InfinityBook13V3            | [fd081a3636](https://bsd-hardware.info/?probe=fd081a3636) | May 17, 2022 |
| Lenovo    | ThinkPad X250 20CLS4WV08    | [0419c52079](https://bsd-hardware.info/?probe=0419c52079) | May 11, 2022 |
| Intel     | H81U                        | [550699602e](https://bsd-hardware.info/?probe=550699602e) | May 11, 2022 |
| Intel     | H81U                        | [04646d1cc7](https://bsd-hardware.info/?probe=04646d1cc7) | May 05, 2022 |
| Dell      | Latitude 7490               | [0d5b872ec1](https://bsd-hardware.info/?probe=0d5b872ec1) | May 02, 2022 |
| Dell      | Latitude 7490               | [03c97fe4d9](https://bsd-hardware.info/?probe=03c97fe4d9) | May 02, 2022 |
| Dell      | Precision 7730              | [bdb3e3d4ce](https://bsd-hardware.info/?probe=bdb3e3d4ce) | Apr 30, 2022 |
| Dell      | Latitude 7490               | [1586880dd7](https://bsd-hardware.info/?probe=1586880dd7) | Apr 30, 2022 |
| Dell      | Studio 1555                 | [6da8f97bcd](https://bsd-hardware.info/?probe=6da8f97bcd) | Apr 22, 2022 |
| Dell      | Latitude E5450              | [ca5eb083f9](https://bsd-hardware.info/?probe=ca5eb083f9) | Apr 16, 2022 |
| Deciso    | Netboard A20                | [0829d5a85d](https://bsd-hardware.info/?probe=0829d5a85d) | Apr 06, 2022 |
| HP        | EliteBook 2530p             | [e5c8017afb](https://bsd-hardware.info/?probe=e5c8017afb) | Mar 12, 2022 |
| Lenovo    | Flex 2-15 20405             | [3b77055bd4](https://bsd-hardware.info/?probe=3b77055bd4) | Mar 07, 2022 |
| Dell      | Latitude E5440              | [b0314f9200](https://bsd-hardware.info/?probe=b0314f9200) | Feb 26, 2022 |
| Lenovo    | Legion 5 15ARH05 82B5       | [1a13b7bfd1](https://bsd-hardware.info/?probe=1a13b7bfd1) | Feb 16, 2022 |
| Lenovo    | Flex 2-15 20405             | [1e8904f4fc](https://bsd-hardware.info/?probe=1e8904f4fc) | Feb 15, 2022 |
| Lenovo    | Flex 2-15 20405             | [b77b926f9b](https://bsd-hardware.info/?probe=b77b926f9b) | Feb 13, 2022 |
| Deciso    | NetBoard-A20                | [4d8f19ba12](https://bsd-hardware.info/?probe=4d8f19ba12) | Feb 11, 2022 |
| Deciso    | NetBoard-A20                | [a6b7d2d5e8](https://bsd-hardware.info/?probe=a6b7d2d5e8) | Feb 06, 2022 |
| Deciso    | Netboard A20                | [8cd43fcfd1](https://bsd-hardware.info/?probe=8cd43fcfd1) | Feb 03, 2022 |
| ASUSTek   | 1015PEM                     | [efea0efb2b](https://bsd-hardware.info/?probe=efea0efb2b) | Jan 31, 2022 |
| Apple     | MacBook4,1                  | [e89404ebed](https://bsd-hardware.info/?probe=e89404ebed) | Jan 29, 2022 |
| Lenovo    | Legion Y540-15IRH 81SX      | [384d2f888b](https://bsd-hardware.info/?probe=384d2f888b) | Jan 18, 2022 |
| HP        | EliteBook 2530p             | [42eb986a58](https://bsd-hardware.info/?probe=42eb986a58) | Jan 11, 2022 |
| Dell      | Latitude E5450              | [a05fbe1c26](https://bsd-hardware.info/?probe=a05fbe1c26) | Jan 05, 2022 |
| Dell      | Latitude E5450              | [c2ef231757](https://bsd-hardware.info/?probe=c2ef231757) | Jan 04, 2022 |
| ASUSTek   | S550CA                      | [1263a5fb37](https://bsd-hardware.info/?probe=1263a5fb37) | Dec 29, 2021 |
| Samsung   | R720                        | [620195d4aa](https://bsd-hardware.info/?probe=620195d4aa) | Dec 20, 2021 |
| HP        | Compaq 15                   | [1e8b1ce39b](https://bsd-hardware.info/?probe=1e8b1ce39b) | Dec 20, 2021 |
| Lenovo    | G500 20236                  | [350def9eca](https://bsd-hardware.info/?probe=350def9eca) | Dec 19, 2021 |
| Lenovo    | ThinkPad T590 20N4CTO1WW    | [4147a5824d](https://bsd-hardware.info/?probe=4147a5824d) | Dec 16, 2021 |
| HP        | ProBook 650 G5              | [d4ffc24c6f](https://bsd-hardware.info/?probe=d4ffc24c6f) | Dec 15, 2021 |
| Lenovo    | ThinkPad T590 20N4CTO1WW    | [eb69e83fbf](https://bsd-hardware.info/?probe=eb69e83fbf) | Dec 09, 2021 |
| Google    | Terra                       | [9ba239a4a3](https://bsd-hardware.info/?probe=9ba239a4a3) | Oct 10, 2021 |
| Lenovo    | ThinkPad X220 4290W42       | [8be5183e21](https://bsd-hardware.info/?probe=8be5183e21) | Sep 25, 2021 |
| Lenovo    | ThinkPad T500 2056Y2Z       | [88b86ecf8b](https://bsd-hardware.info/?probe=88b86ecf8b) | Sep 25, 2021 |
| MSI       | P65 Creator 8RE             | [2684b5021c](https://bsd-hardware.info/?probe=2684b5021c) | Sep 18, 2021 |
| Lenovo    | ThinkPad E14 Gen 3 20Y7C... | [8611fbfd97](https://bsd-hardware.info/?probe=8611fbfd97) | Sep 14, 2021 |
| Apple     | MacBookPro8,2               | [5f78c3411f](https://bsd-hardware.info/?probe=5f78c3411f) | Sep 13, 2021 |
| Lenovo    | ThinkPad P14s Gen 1 20Y1... | [d028fc63d4](https://bsd-hardware.info/?probe=d028fc63d4) | Aug 29, 2021 |
| Lenovo    | ThinkPad P14s Gen 1 20Y1... | [76f004bd26](https://bsd-hardware.info/?probe=76f004bd26) | Aug 26, 2021 |
| Fujitsu   | LIFEBOOK NH570              | [51b5325c85](https://bsd-hardware.info/?probe=51b5325c85) | Aug 13, 2021 |
| Lenovo    | G500 20236                  | [d15eff8bcc](https://bsd-hardware.info/?probe=d15eff8bcc) | Jul 21, 2021 |
| Lenovo    | ThinkPad T420 42368A3       | [0a3b5c9c27](https://bsd-hardware.info/?probe=0a3b5c9c27) | Jul 12, 2021 |
| Notebook  | W510LU                      | [3d6de69bda](https://bsd-hardware.info/?probe=3d6de69bda) | Jul 02, 2021 |
| Lenovo    | G500 20236                  | [7ae63d4c6c](https://bsd-hardware.info/?probe=7ae63d4c6c) | Jun 27, 2021 |
| Dell      | Vostro 5481                 | [bb318fbc50](https://bsd-hardware.info/?probe=bb318fbc50) | Jun 26, 2021 |
| Lenovo    | ThinkPad T450s 20BWS0L60... | [6ea6f6ffe7](https://bsd-hardware.info/?probe=6ea6f6ffe7) | Jun 20, 2021 |
| Lenovo    | ThinkPad X250 20CLS7WY04    | [b60f4a19ee](https://bsd-hardware.info/?probe=b60f4a19ee) | Jun 06, 2021 |
| Apple     | MacBookPro8,2               | [193936b5ca](https://bsd-hardware.info/?probe=193936b5ca) | May 30, 2021 |
| Lenovo    | ThinkPad T450s 20BWS0L60... | [ac567bd12d](https://bsd-hardware.info/?probe=ac567bd12d) | May 28, 2021 |
| Lenovo    | ThinkPad A485 20MVS0FD00    | [2f1ba02130](https://bsd-hardware.info/?probe=2f1ba02130) | May 28, 2021 |
| Acer      | Aspire E5-571P              | [7c8c842fa7](https://bsd-hardware.info/?probe=7c8c842fa7) | May 24, 2021 |
| Lenovo    | ThinkPad T590 20N4CTO1WW    | [7c642e5e7d](https://bsd-hardware.info/?probe=7c642e5e7d) | Apr 30, 2021 |
| Lenovo    | ThinkPad T590 20N4CTO1WW    | [2e2e69cb9e](https://bsd-hardware.info/?probe=2e2e69cb9e) | Apr 29, 2021 |
| Lenovo    | ThinkPad T430 23495P8       | [2c985c22ef](https://bsd-hardware.info/?probe=2c985c22ef) | Apr 10, 2021 |
| Lenovo    | ThinkPad T420 4236NUG       | [4ff3fa22ff](https://bsd-hardware.info/?probe=4ff3fa22ff) | Apr 07, 2021 |
| Lenovo    | ThinkPad X220 4290EE8       | [f46976d85d](https://bsd-hardware.info/?probe=f46976d85d) | Mar 29, 2021 |
| Lenovo    | ThinkPad T490 20N20009FR    | [e1f691ac78](https://bsd-hardware.info/?probe=e1f691ac78) | Mar 29, 2021 |
| Lenovo    | ThinkPad T590 20N4CTO1WW    | [dec8aa97f5](https://bsd-hardware.info/?probe=dec8aa97f5) | Mar 26, 2021 |
| Lenovo    | ThinkPad T590 20N4CTO1WW    | [83ed58b4d0](https://bsd-hardware.info/?probe=83ed58b4d0) | Mar 26, 2021 |
| HP        | Pavilion Gaming Laptop 1... | [3cb0e979f8](https://bsd-hardware.info/?probe=3cb0e979f8) | Mar 26, 2021 |
| MSI       | MS-N033                     | [650f6a1b70](https://bsd-hardware.info/?probe=650f6a1b70) | Mar 21, 2021 |
| Dell      | Inspiron 7566               | [183ac9b791](https://bsd-hardware.info/?probe=183ac9b791) | Mar 17, 2021 |
| Dell      | Inspiron 7566               | [b4a35aa7b0](https://bsd-hardware.info/?probe=b4a35aa7b0) | Mar 17, 2021 |
| SECO      | UDOO x86                    | [f8310915b6](https://bsd-hardware.info/?probe=f8310915b6) | Mar 13, 2021 |
| HP        | EliteBook 820 G1            | [565343b334](https://bsd-hardware.info/?probe=565343b334) | Mar 13, 2021 |
| Lenovo    | ThinkPad T400 6475P1G       | [6a0907b5e8](https://bsd-hardware.info/?probe=6a0907b5e8) | Mar 06, 2021 |
| Clevo     | W240EU/W250EUQ/W270EUQ      | [17ed006376](https://bsd-hardware.info/?probe=17ed006376) | Mar 05, 2021 |
| HP        | EliteBook 820 G1            | [de98cd5952](https://bsd-hardware.info/?probe=de98cd5952) | Mar 04, 2021 |
| HP        | EliteBook 820 G1            | [03c5808adf](https://bsd-hardware.info/?probe=03c5808adf) | Mar 04, 2021 |
| Dell      | Latitude 5280               | [b84364959d](https://bsd-hardware.info/?probe=b84364959d) | Mar 04, 2021 |
| Lenovo    | IdeaPad S145-15API 81UT     | [1f226262cc](https://bsd-hardware.info/?probe=1f226262cc) | Mar 04, 2021 |
| ASUSTek   | X550LC                      | [e056f1c77c](https://bsd-hardware.info/?probe=e056f1c77c) | Mar 03, 2021 |
| Lenovo    | ThinkPad X280 20KFCTO1WW    | [9bdf9ecec8](https://bsd-hardware.info/?probe=9bdf9ecec8) | Feb 25, 2021 |
| Lenovo    | IdeaPad S145-15API 81UT     | [7def696a61](https://bsd-hardware.info/?probe=7def696a61) | Feb 22, 2021 |
| Lenovo    | IdeaPad S145-15API 81UT     | [0dc468c860](https://bsd-hardware.info/?probe=0dc468c860) | Feb 22, 2021 |
| ASUSTek   | X751LN                      | [fe7d72b06a](https://bsd-hardware.info/?probe=fe7d72b06a) | Feb 21, 2021 |
| ASUSTek   | X751LN                      | [a88cfd7fdd](https://bsd-hardware.info/?probe=a88cfd7fdd) | Feb 21, 2021 |
| Gigabyte  | P15FR7                      | [c65b4d297a](https://bsd-hardware.info/?probe=c65b4d297a) | Feb 21, 2021 |
| Lenovo    | ThinkPad X1 Carbon 4th 2... | [71cfece3a7](https://bsd-hardware.info/?probe=71cfece3a7) | Feb 18, 2021 |
| ASUSTek   | X75VC                       | [4a0982db2b](https://bsd-hardware.info/?probe=4a0982db2b) | Feb 15, 2021 |
| Clevo     | W240EU/W250EUQ/W270EUQ      | [4f646f53e9](https://bsd-hardware.info/?probe=4f646f53e9) | Feb 14, 2021 |
| Lenovo    | ThinkPad T580 20LAS2TG00    | [d5a1c088b3](https://bsd-hardware.info/?probe=d5a1c088b3) | Feb 13, 2021 |
| ASUSTek   | E200HA                      | [5781a8b561](https://bsd-hardware.info/?probe=5781a8b561) | Feb 12, 2021 |
| Lenovo    | G500 20236                  | [9b149fcd68](https://bsd-hardware.info/?probe=9b149fcd68) | Feb 12, 2021 |
| Dell      | Latitude 3410               | [465dd01c0d](https://bsd-hardware.info/?probe=465dd01c0d) | Feb 11, 2021 |
| Dell      | Latitude E6230              | [696e95fc08](https://bsd-hardware.info/?probe=696e95fc08) | Feb 10, 2021 |
| ASUSTek   | X550LC                      | [b3cf6f9142](https://bsd-hardware.info/?probe=b3cf6f9142) | Feb 09, 2021 |
| Lenovo    | IdeaPad S145-15API 81UT     | [7e5ce355e7](https://bsd-hardware.info/?probe=7e5ce355e7) | Feb 08, 2021 |
| Dell      | Latitude 5280               | [73fca8b178](https://bsd-hardware.info/?probe=73fca8b178) | Feb 08, 2021 |
| Lenovo    | ThinkPad T420 42368A3       | [5d7840d28e](https://bsd-hardware.info/?probe=5d7840d28e) | Feb 07, 2021 |
| Dell      | Latitude 3410               | [f81c1e338f](https://bsd-hardware.info/?probe=f81c1e338f) | Feb 07, 2021 |
| Lenovo    | ThinkPad P50 20EQS0U60C     | [d8cf9e878e](https://bsd-hardware.info/?probe=d8cf9e878e) | Jan 19, 2021 |
| ASUSTek   | X550LC                      | [f7c32488e9](https://bsd-hardware.info/?probe=f7c32488e9) | Jan 15, 2021 |
| Lenovo    | IdeaPad S145-15API 81UT     | [06cbb5cd5f](https://bsd-hardware.info/?probe=06cbb5cd5f) | Jan 15, 2021 |
| Dell      | Latitude 5280               | [c9bfb73262](https://bsd-hardware.info/?probe=c9bfb73262) | Jan 15, 2021 |
| Dell      | Latitude 5400               | [f242897c33](https://bsd-hardware.info/?probe=f242897c33) | Jan 13, 2021 |
| Dell      | Latitude 5490               | [3fba47b07f](https://bsd-hardware.info/?probe=3fba47b07f) | Jan 12, 2021 |
| ASUSTek   | N75SF                       | [7efb6557a2](https://bsd-hardware.info/?probe=7efb6557a2) | Jan 10, 2021 |
| Lenovo    | IdeaPad S145-15API 81UT     | [9ccf63e228](https://bsd-hardware.info/?probe=9ccf63e228) | Jan 09, 2021 |
| Lenovo    | IdeaPad S145-15API 81UT     | [e18df4623a](https://bsd-hardware.info/?probe=e18df4623a) | Jan 09, 2021 |
| Dell      | Latitude 5280               | [1ae6e6ee2d](https://bsd-hardware.info/?probe=1ae6e6ee2d) | Jan 05, 2021 |
| ASUSTek   | X102BA                      | [893b9111c6](https://bsd-hardware.info/?probe=893b9111c6) | Dec 27, 2020 |
| Apple     | PowerBook5,8                | [96f550a537](https://bsd-hardware.info/?probe=96f550a537) | Dec 24, 2020 |
| Clevo     | W240EU/W250EUQ/W270EUQ      | [2544123f79](https://bsd-hardware.info/?probe=2544123f79) | Dec 06, 2020 |
| Dell      | Latitude 5280               | [d1be72cc7e](https://bsd-hardware.info/?probe=d1be72cc7e) | Nov 21, 2020 |
| Dell      | Latitude 5280               | [fd4e8756b4](https://bsd-hardware.info/?probe=fd4e8756b4) | Nov 21, 2020 |
| Lenovo    | ThinkPad X1 Carbon 6th 2... | [9b6b24708e](https://bsd-hardware.info/?probe=9b6b24708e) | Nov 03, 2020 |
| Lenovo    | ThinkPad X1 Carbon 5th 2... | [7c8972f650](https://bsd-hardware.info/?probe=7c8972f650) | Oct 29, 2020 |
| Lenovo    | ThinkPad X230 2325AJ9       | [176044b6b8](https://bsd-hardware.info/?probe=176044b6b8) | Oct 21, 2020 |
| Lenovo    | ThinkPad S5-S540 20B3001... | [7e6cb69989](https://bsd-hardware.info/?probe=7e6cb69989) | Oct 21, 2020 |
| Lenovo    | ThinkPad W540 20BG001KUK    | [1b1327ac93](https://bsd-hardware.info/?probe=1b1327ac93) | Oct 21, 2020 |
| ASUSTek   | X102BA                      | [47e04c9378](https://bsd-hardware.info/?probe=47e04c9378) | Oct 19, 2020 |
| ASUSTek   | UX305FA                     | [4ecb1e9cd3](https://bsd-hardware.info/?probe=4ecb1e9cd3) | Sep 25, 2020 |
| Lenovo    | ThinkPad W540 20BG001KUK    | [986575086d](https://bsd-hardware.info/?probe=986575086d) | Sep 05, 2020 |
| Lenovo    | ThinkPad W540 20BG001KUK    | [f95de56bcd](https://bsd-hardware.info/?probe=f95de56bcd) | Sep 03, 2020 |
| TUXEDO    | InfinityBook13V3            | [d508fb472b](https://bsd-hardware.info/?probe=d508fb472b) | Aug 10, 2020 |
| Sony      | VGN-AR630E                  | [b417df513f](https://bsd-hardware.info/?probe=b417df513f) | Aug 07, 2020 |
| MSI       | P65 Creator 8RE             | [4031d186c2](https://bsd-hardware.info/?probe=4031d186c2) | Aug 06, 2020 |
| Lenovo    | ThinkPad X280 20KFCTO1WW    | [82de136ad3](https://bsd-hardware.info/?probe=82de136ad3) | Aug 06, 2020 |
| Lenovo    | ThinkPad W540 20BG001KUK    | [f3e2acbb66](https://bsd-hardware.info/?probe=f3e2acbb66) | Jul 31, 2020 |
| Lenovo    | ThinkPad W540 20BG001KUK    | [7ae8c247e9](https://bsd-hardware.info/?probe=7ae8c247e9) | Jul 31, 2020 |
| Lenovo    | ThinkPad T590 20N4CTO1WW    | [90e2b57f16](https://bsd-hardware.info/?probe=90e2b57f16) | Jun 14, 2020 |
| Lenovo    | ThinkPad T590 20N4CTO1WW    | [9ad34ffa59](https://bsd-hardware.info/?probe=9ad34ffa59) | Jun 14, 2020 |
| Dell      | Latitude E6420              | [7c8a68918a](https://bsd-hardware.info/?probe=7c8a68918a) | May 27, 2020 |
| Lenovo    | ThinkPad X1 Carbon 5th 2... | [bb2fcf8d92](https://bsd-hardware.info/?probe=bb2fcf8d92) | May 25, 2020 |
| HP        | ZBook 15                    | [3e9076f244](https://bsd-hardware.info/?probe=3e9076f244) | May 23, 2020 |
| HP        | ZBook 15                    | [23ec663f87](https://bsd-hardware.info/?probe=23ec663f87) | May 23, 2020 |
| Lenovo    | ThinkPad T495 20NJCTO1WW    | [fa71e5839a](https://bsd-hardware.info/?probe=fa71e5839a) | May 23, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| OpenBSD 6.8          | 7         | 3.48%   |
| helloSystem 0.8.1    | 7         | 3.48%   |
| helloSystem 0.4.0    | 7         | 3.48%   |
| FreeBSD 13.1         | 7         | 3.48%   |
| OpenBSD 7.0          | 6         | 2.99%   |
| NomadBSD 1.3.2       | 6         | 2.99%   |
| helloSystem 0.7.0    | 6         | 2.99%   |
| FreeBSD 14.0-p6      | 6         | 2.99%   |
| NomadBSD 20221130    | 5         | 2.49%   |
| GhostBSD 20.04.02    | 5         | 2.49%   |
| FreeBSD 13.1-p7      | 5         | 2.49%   |
| FreeBSD 13.0         | 5         | 2.49%   |
| OpenBSD 7.1          | 4         | 1.99%   |
| NomadBSD 1.4         | 4         | 1.99%   |
| helloSystem 0.8.0    | 4         | 1.99%   |
| FreeBSD 12.2-p2      | 4         | 1.99%   |
| OpenBSD 6.9          | 3         | 1.49%   |
| FreeBSD 13.2         | 3         | 1.49%   |
| FreeBSD 13.1-p3      | 3         | 1.49%   |
| FreeBSD 13.0-STABLE  | 3         | 1.49%   |
| FreeBSD 12.2-p4      | 3         | 1.49%   |
| FreeBSD 12.2         | 3         | 1.49%   |
| OPNsense 23.1.11     | 2         | 1%      |
| OPNsense 22.7.6      | 2         | 1%      |
| OPNsense 22.10       | 2         | 1%      |
| OPNsense 22.1        | 2         | 1%      |
| OpenBSD 7.2          | 2         | 1%      |
| OpenBSD 6.7          | 2         | 1%      |
| NetBSD 10.0_RC3      | 2         | 1%      |
| helloSystem 0.9.0    | 2         | 1%      |
| GhostBSD 24.01.1     | 2         | 1%      |
| GhostBSD 22.01.12    | 2         | 1%      |
| FreeBSD 14.0-RC4     | 2         | 1%      |
| FreeBSD 14.0-CURRENT | 2         | 1%      |
| FreeBSD 13.2-p3      | 2         | 1%      |
| FreeBSD 13.2-p2      | 2         | 1%      |
| FreeBSD 13.1-STABLE  | 2         | 1%      |
| FreeBSD 13.0-RC5     | 2         | 1%      |
| FreeBSD 13.0-p6      | 2         | 1%      |
| FreeBSD 13.0-p3      | 2         | 1%      |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 77        | 45.03%  |
| helloSystem | 24        | 14.04%  |
| OpenBSD     | 23        | 13.45%  |
| NomadBSD    | 16        | 9.36%   |
| OPNsense    | 15        | 8.77%   |
| GhostBSD    | 10        | 5.85%   |
| NetBSD      | 5         | 2.92%   |
| FuryBSD     | 1         | 0.58%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| amd64  | 152       | 96.82%  |
| i386   | 4         | 2.55%   |
| macppc | 1         | 0.64%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 32        | 18.08%  |
| XFCE         | 30        | 16.95%  |
| Console      | 23        | 12.99%  |
| KDE5         | 19        | 10.73%  |
| fvwm         | 16        | 9.04%   |
| Openbox      | 15        | 8.47%   |
| MATE         | 11        | 6.21%   |
| GNOME        | 10        | 5.65%   |
| TWM          | 7         | 3.95%   |
| i3           | 5         | 2.82%   |
| xinitrc      | 3         | 1.69%   |
| AwesomeWM    | 3         | 1.69%   |
| X-Cinnamon   | 1         | 0.56%   |
| sway         | 1         | 0.56%   |
| LXDE         | 1         | 0.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 134       | 83.75%  |
| Console | 25        | 15.63%  |
| Wayland | 1         | 0.63%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 63        | 37.28%  |
| SLiM    | 56        | 33.14%  |
| SDDM    | 20        | 11.83%  |
| LightDM | 14        | 8.28%   |
| XDM     | 11        | 6.51%   |
| GDM     | 5         | 2.96%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| Unknown         | 51        | 30%     |
| fr_FR           | 43        | 25.29%  |
| en_US           | 34        | 20%     |
| C               | 32        | 18.82%  |
| de_DE           | 3         | 1.76%   |
| fr              | 2         | 1.18%   |
| en_US.ISO8859-1 | 2         | 1.18%   |
| en_GB           | 2         | 1.18%   |
| en              | 1         | 0.59%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 124       | 77.5%   |
| BIOS | 36        | 22.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 86        | 52.12%  |
| Ufs    | 46        | 27.88%  |
| Ffs    | 23        | 13.94%  |
| Cd9660 | 10        | 6.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 131       | 81.88%  |
| MBR     | 26        | 16.25%  |
| Unknown | 2         | 1.25%   |
| BSD     | 1         | 0.63%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 45        | 28.66%  |
| Dell                | 31        | 19.75%  |
| ASUSTek Computer    | 15        | 9.55%   |
| Apple               | 11        | 7.01%   |
| Hewlett-Packard     | 10        | 6.37%   |
| Deciso              | 6         | 3.82%   |
| Intel               | 5         | 3.18%   |
| Acer                | 5         | 3.18%   |
| TUXEDO              | 3         | 1.91%   |
| Toshiba             | 3         | 1.91%   |
| Sony                | 2         | 1.27%   |
| Samsung Electronics | 2         | 1.27%   |
| Notebook            | 2         | 1.27%   |
| MSI                 | 2         | 1.27%   |
| Fujitsu             | 2         | 1.27%   |
| Alienware           | 2         | 1.27%   |
| Unknown             | 2         | 1.27%   |
| SECO                | 1         | 0.64%   |
| Razer               | 1         | 0.64%   |
| Panasonic           | 1         | 0.64%   |
| Medion              | 1         | 0.64%   |
| Google              | 1         | 0.64%   |
| Gigabyte Technology | 1         | 0.64%   |
| Getac               | 1         | 0.64%   |
| Clevo               | 1         | 0.64%   |
| Chuwi               | 1         | 0.64%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel H81U                               | 4         | 2.55%   |
| Apple MacBookAir6,2                      | 4         | 2.55%   |
| Dell Precision M4500                     | 3         | 1.91%   |
| Deciso NetBoard-A20                      | 3         | 1.91%   |
| Deciso Netboard A20                      | 3         | 1.91%   |
| TUXEDO InfinityBook13V3                  | 2         | 1.27%   |
| Toshiba PORTEGE Z930                     | 2         | 1.27%   |
| Dell Latitude 3410                       | 2         | 1.27%   |
| Apple MacBookPro14,1                     | 2         | 1.27%   |
| Unknown                                  | 2         | 1.27%   |
| TUXEDO Aura 15 Gen1                      | 1         | 0.64%   |
| Toshiba NB300                            | 1         | 0.64%   |
| Sony VGN-FZ19VN                          | 1         | 0.64%   |
| Sony VGN-AR630E                          | 1         | 0.64%   |
| SECO UDOO x86                            | 1         | 0.64%   |
| Samsung R720                             | 1         | 0.64%   |
| Samsung N150/N210/N220                   | 1         | 0.64%   |
| Razer Blade 16 - RZ09-0483               | 1         | 0.64%   |
| Panasonic CF-31-5                        | 1         | 0.64%   |
| Notebook W510LU                          | 1         | 0.64%   |
| Notebook N7x0WU                          | 1         | 0.64%   |
| MSI P65 Creator 8RE                      | 1         | 0.64%   |
| MSI MS-N033                              | 1         | 0.64%   |
| Medion E15415                            | 1         | 0.64%   |
| Lenovo ThinkPad X280 20KFCTO1WW          | 1         | 0.64%   |
| Lenovo ThinkPad X260 20F6006XUK          | 1         | 0.64%   |
| Lenovo ThinkPad X250 20CLS7WY04          | 1         | 0.64%   |
| Lenovo ThinkPad X250 20CLS4WV08          | 1         | 0.64%   |
| Lenovo ThinkPad X230 2325AJ9             | 1         | 0.64%   |
| Lenovo ThinkPad X220 429147U             | 1         | 0.64%   |
| Lenovo ThinkPad X220 429135G             | 1         | 0.64%   |
| Lenovo ThinkPad X220 4290W42             | 1         | 0.64%   |
| Lenovo ThinkPad X220 4290EE8             | 1         | 0.64%   |
| Lenovo ThinkPad X1 Carbon 6th 20KHS1TG00 | 1         | 0.64%   |
| Lenovo ThinkPad X1 Carbon 5th 20HRCTO1WW | 1         | 0.64%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS2K000 | 1         | 0.64%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BS003LFR | 1         | 0.64%   |
| Lenovo ThinkPad W540 20BG001KUK          | 1         | 0.64%   |
| Lenovo ThinkPad T60 1951CZ1              | 1         | 0.64%   |
| Lenovo ThinkPad T590 20N4CTO1WW          | 1         | 0.64%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 39        | 24.84%  |
| Dell Latitude           | 16        | 10.19%  |
| Dell Precision          | 9         | 5.73%   |
| Intel H81U              | 4         | 2.55%   |
| HP EliteBook            | 4         | 2.55%   |
| Apple MacBookAir6       | 4         | 2.55%   |
| Deciso NetBoard-A20     | 3         | 1.91%   |
| Deciso Netboard         | 3         | 1.91%   |
| Acer Aspire             | 3         | 1.91%   |
| TUXEDO InfinityBook13V3 | 2         | 1.27%   |
| Toshiba PORTEGE         | 2         | 1.27%   |
| Lenovo Legion           | 2         | 1.27%   |
| HP Pavilion             | 2         | 1.27%   |
| Dell Vostro             | 2         | 1.27%   |
| Dell Inspiron           | 2         | 1.27%   |
| ASUS VivoBook           | 2         | 1.27%   |
| Apple MacBookPro14      | 2         | 1.27%   |
| Unknown                 | 2         | 1.27%   |
| TUXEDO Aura             | 1         | 0.64%   |
| Toshiba NB300           | 1         | 0.64%   |
| Sony VGN-FZ19VN         | 1         | 0.64%   |
| Sony VGN-AR630E         | 1         | 0.64%   |
| SECO UDOO               | 1         | 0.64%   |
| Samsung R720            | 1         | 0.64%   |
| Samsung N150            | 1         | 0.64%   |
| Razer Blade             | 1         | 0.64%   |
| Panasonic CF-31-5       | 1         | 0.64%   |
| Notebook W510LU         | 1         | 0.64%   |
| Notebook N7x0WU         | 1         | 0.64%   |
| MSI P65                 | 1         | 0.64%   |
| MSI MS-N033             | 1         | 0.64%   |
| Medion E15415           | 1         | 0.64%   |
| Lenovo ThinkBook        | 1         | 0.64%   |
| Lenovo IdeaPad          | 1         | 0.64%   |
| Lenovo G500             | 1         | 0.64%   |
| Lenovo Flex             | 1         | 0.64%   |
| Intel Jasper            | 1         | 0.64%   |
| HP ZBook                | 1         | 0.64%   |
| HP Stream               | 1         | 0.64%   |
| HP ProBook              | 1         | 0.64%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 22        | 14.01%  |
| 2020    | 16        | 10.19%  |
| 2021    | 13        | 8.28%   |
| 2013    | 13        | 8.28%   |
| 2011    | 13        | 8.28%   |
| 2022    | 12        | 7.64%   |
| 2018    | 11        | 7.01%   |
| 2015    | 10        | 6.37%   |
| 2010    | 9         | 5.73%   |
| 2016    | 8         | 5.1%    |
| 2014    | 7         | 4.46%   |
| 2023    | 6         | 3.82%   |
| 2017    | 4         | 2.55%   |
| 2012    | 3         | 1.91%   |
| 2009    | 3         | 1.91%   |
| 2008    | 3         | 1.91%   |
| 2007    | 2         | 1.27%   |
| 2006    | 1         | 0.64%   |
| Unknown | 1         | 0.64%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 157       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 155       | 98.73%  |
| Yes  | 2         | 1.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 55        | 34.38%  |
| 16.01-24.0  | 40        | 25%     |
| 4.01-8.0    | 26        | 16.25%  |
| 32.01-64.0  | 14        | 8.75%   |
| 2.01-3.0    | 9         | 5.63%   |
| 64.01-256.0 | 6         | 3.75%   |
| 3.01-4.0    | 4         | 2.5%    |
| 24.01-32.0  | 3         | 1.88%   |
| 1.01-2.0    | 2         | 1.25%   |
| 0.51-1.0    | 1         | 0.63%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 86        | 51.81%  |
| 0.51-1.0   | 46        | 27.71%  |
| 1.01-2.0   | 17        | 10.24%  |
| 2.01-3.0   | 7         | 4.22%   |
| Unknown    | 5         | 3.01%   |
| 8.01-16.0  | 4         | 2.41%   |
| 32.01-64.0 | 1         | 0.6%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 104       | 64.2%   |
| 2      | 30        | 18.52%  |
| 0      | 21        | 12.96%  |
| 3      | 5         | 3.09%   |
| 4      | 2         | 1.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 121       | 75.63%  |
| Yes       | 39        | 24.38%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 133       | 84.18%  |
| No        | 25        | 15.82%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 143       | 91.08%  |
| No        | 14        | 8.92%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 98        | 61.25%  |
| No        | 62        | 38.75%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| France  | 157       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Paris                    | 29        | 16.11%  |
| Franconville             | 7         | 3.89%   |
| Colombes                 | 7         | 3.89%   |
| Bordeaux                 | 6         | 3.33%   |
| Urcuit                   | 4         | 2.22%   |
| Melun                    | 4         | 2.22%   |
| Noyon                    | 3         | 1.67%   |
| Marcq-en-Baroeul         | 3         | 1.67%   |
| Mâcon                   | 3         | 1.67%   |
| Fontenay-sous-Bois       | 3         | 1.67%   |
| Carry-le-Rouet           | 3         | 1.67%   |
| Stiring-Wendel           | 2         | 1.11%   |
| Saint-Raphaël           | 2         | 1.11%   |
| Saint-Germain-en-Laye    | 2         | 1.11%   |
| Saint-Denis              | 2         | 1.11%   |
| Rosny-sous-Bois          | 2         | 1.11%   |
| Rennes                   | 2         | 1.11%   |
| Noisy-le-Grand           | 2         | 1.11%   |
| Dijon                    | 2         | 1.11%   |
| Courbevoie               | 2         | 1.11%   |
| Colmar                   | 2         | 1.11%   |
| Asnieres-sur-Seine       | 2         | 1.11%   |
| Villeneuve-Saint-Georges | 1         | 0.56%   |
| Villemomble              | 1         | 0.56%   |
| Villejuif                | 1         | 0.56%   |
| Villefontaine            | 1         | 0.56%   |
| Vertou                   | 1         | 0.56%   |
| Tulle                    | 1         | 0.56%   |
| Tournon-sur-RhÃ´ne     | 1         | 0.56%   |
| Toulouse                 | 1         | 0.56%   |
| St-Malo                  | 1         | 0.56%   |
| Soisy-sur-Seine          | 1         | 0.56%   |
| Sartrouville             | 1         | 0.56%   |
| Sarcelles                | 1         | 0.56%   |
| Samatan                  | 1         | 0.56%   |
| Sallanches               | 1         | 0.56%   |
| Saint-Saulge             | 1         | 0.56%   |
| Saint-Martin-d'Hères    | 1         | 0.56%   |
| Saint-Herblain           | 1         | 0.56%   |
| Saint-Genest-Lerpt       | 1         | 0.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 31        | 43     | 18.24%  |
| Crucial             | 17        | 21     | 10%     |
| Toshiba             | 15        | 24     | 8.82%   |
| Seagate             | 15        | 27     | 8.82%   |
| Kingston            | 11        | 13     | 6.47%   |
| WDC                 | 10        | 15     | 5.88%   |
| Transcend           | 10        | 16     | 5.88%   |
| SanDisk             | 9         | 12     | 5.29%   |
| China               | 7         | 7      | 4.12%   |
| Micron Technology   | 6         | 11     | 3.53%   |
| Intel               | 6         | 9      | 3.53%   |
| NVMe                | 5         | 5      | 2.94%   |
| HGST                | 5         | 8      | 2.94%   |
| Apple               | 5         | 6      | 2.94%   |
| SK hynix            | 3         | 3      | 1.76%   |
| Fujitsu             | 3         | 3      | 1.76%   |
| Phison              | 2         | 2      | 1.18%   |
| Hitachi             | 2         | 2      | 1.18%   |
| SPCC                | 1         | 1      | 0.59%   |
| Lexar               | 1         | 2      | 0.59%   |
| LDLC F6+            | 1         | 1      | 0.59%   |
| Integral            | 1         | 1      | 0.59%   |
| Generic             | 1         | 1      | 0.59%   |
| EMTEC               | 1         | 1      | 0.59%   |
| BHT                 | 1         | 1      | 0.59%   |
| AirDisk             | 1         | 1      | 0.59%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Transcend TS256GMTS952T2 256GB       | 5         | 2.84%   |
| China MSATA 32GB SSD                 | 4         | 2.27%   |
| Apple SSD SD0128F 121GB              | 4         | 2.27%   |
| Seagate ST1000LM035-1RK172 1TB       | 3         | 1.7%    |
| Kingston SA400S37240G 240GB          | 3         | 1.7%    |
| Crucial CT1000P1SSD8 1TB             | 3         | 1.7%    |
| WDC WD3200BPVT-80JJ5T0 320GB         | 2         | 1.14%   |
| Transcend TS256GMTS430S 256GB        | 2         | 1.14%   |
| Toshiba MK2556GSY 250GB              | 2         | 1.14%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB  | 2         | 1.14%   |
| Samsung SSD 970 EVO Plus 2TB         | 2         | 1.14%   |
| Samsung SSD 950 PRO 512GB            | 2         | 1.14%   |
| Samsung SSD 860 EVO M.2 1TB          | 2         | 1.14%   |
| Samsung SSD 860 EVO 250GB            | 2         | 1.14%   |
| Samsung SSD 850 EVO 250GB            | 2         | 1.14%   |
| NVMe WDC PC SN720 SDA 512GB          | 2         | 1.14%   |
| Intel SSDPEKKF256G8L 256GB           | 2         | 1.14%   |
| HGST HTS725050A7E630 500GB           | 2         | 1.14%   |
| HGST HTS721010A9E630 1TB             | 2         | 1.14%   |
| Crucial CT960M500SSD1 960GB          | 2         | 1.14%   |
| Crucial CT250MX500SSD1 250GB         | 2         | 1.14%   |
| Crucial CT1050MX300SSD1 1TB          | 2         | 1.14%   |
| Crucial CT1000MX500SSD1 1TB          | 2         | 1.14%   |
| China SH00M240GB                     | 2         | 1.14%   |
| WDC WDS240G2G0B-00EPW0 240GB         | 1         | 0.57%   |
| WDC WDS120G2G0B-00EPW0 120GB         | 1         | 0.57%   |
| WDC WD3200BEVT-75ZCT2 320GB          | 1         | 0.57%   |
| WDC WD20SMZW-11JW8S1 2TB             | 1         | 0.57%   |
| WDC WD20SDRW-11VUUS0 2TB             | 1         | 0.57%   |
| WDC WD10SPZX-21Z10T0 1TB             | 1         | 0.57%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.57%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 1         | 0.57%   |
| WDC PC SN520 SDAPMUW-128G-1101 128GB | 1         | 0.57%   |
| Transcend TS256GMTS800 256GB         | 1         | 0.57%   |
| Transcend TS256GMTE710T 256GB        | 1         | 0.57%   |
| Transcend TS128GMTS400 128GB         | 1         | 0.57%   |
| Toshiba THNSNJ256GCSY 256GB          | 1         | 0.57%   |
| Toshiba THNSNF128GMCS 128GB          | 1         | 0.57%   |
| Toshiba THNSN51T02DUK NVMe 1024GB    | 1         | 0.57%   |
| Toshiba MQ04ABF100 1TB               | 1         | 0.57%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 27     | 30%     |
| Toshiba             | 10        | 14     | 20%     |
| WDC                 | 6         | 8      | 12%     |
| NVMe                | 5         | 5      | 10%     |
| HGST                | 5         | 8      | 10%     |
| Fujitsu             | 3         | 3      | 6%      |
| Hitachi             | 2         | 2      | 4%      |
| Samsung Electronics | 1         | 1      | 2%      |
| Lexar               | 1         | 2      | 2%      |
| LDLC F6+            | 1         | 1      | 2%      |
| Generic             | 1         | 1      | 2%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 19        | 25     | 22.89%  |
| Crucial             | 12        | 12     | 14.46%  |
| Transcend           | 9         | 15     | 10.84%  |
| SanDisk             | 9         | 12     | 10.84%  |
| Kingston            | 9         | 10     | 10.84%  |
| China               | 7         | 7      | 8.43%   |
| Apple               | 5         | 6      | 6.02%   |
| Toshiba             | 4         | 8      | 4.82%   |
| WDC                 | 2         | 3      | 2.41%   |
| Micron Technology   | 2         | 7      | 2.41%   |
| SPCC                | 1         | 1      | 1.2%    |
| Intel               | 1         | 1      | 1.2%    |
| Integral            | 1         | 1      | 1.2%    |
| EMTEC               | 1         | 1      | 1.2%    |
| BHT                 | 1         | 1      | 1.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 75        | 110    | 47.77%  |
| HDD  | 47        | 72     | 29.94%  |
| NVMe | 35        | 54     | 22.29%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 115       | 182    | 76.67%  |
| NVMe | 35        | 54     | 23.33%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 89        | 132    | 70.08%  |
| 0.51-1.0   | 32        | 42     | 25.2%   |
| 1.01-2.0   | 6         | 8      | 4.72%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 57        | 34.13%  |
| 1-20       | 31        | 18.56%  |
| 251-500    | 27        | 16.17%  |
| 21-50      | 18        | 10.78%  |
| 501-1000   | 18        | 10.78%  |
| 51-100     | 9         | 5.39%   |
| 1001-2000  | 6         | 3.59%   |
| Unknown    | 1         | 0.6%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 127       | 79.38%  |
| 21-50    | 15        | 9.38%   |
| 101-250  | 12        | 7.5%    |
| 51-100   | 3         | 1.88%   |
| 501-1000 | 2         | 1.25%   |
| Unknown  | 1         | 0.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD3200BPVT-80JJ5T0 320GB          | 2         | 2      | 11.11%  |
| WDC WD10JPVX-22JC3T0 1TB              | 1         | 1      | 5.56%   |
| Toshiba MQ01ABD075 752GB              | 1         | 1      | 5.56%   |
| Toshiba MK3261GSY 320GB               | 1         | 1      | 5.56%   |
| Toshiba MK1629GSGF 160GB              | 1         | 3      | 5.56%   |
| Seagate ST9320423AS 320GB             | 1         | 1      | 5.56%   |
| Seagate ST9320325AS 320GB             | 1         | 1      | 5.56%   |
| Seagate ST320LT012-9WS14C 320GB       | 1         | 7      | 5.56%   |
| Seagate ST320LT007-9ZV142 320GB       | 1         | 1      | 5.56%   |
| Seagate ST3160212AS 160GB             | 1         | 1      | 5.56%   |
| Seagate ST1000LM014-1EJ164 1TB        | 1         | 1      | 5.56%   |
| SanDisk SD7UB3Q256G1001 256GB         | 1         | 1      | 5.56%   |
| Samsung Electronics SSD 840 EVO 500GB | 1         | 2      | 5.56%   |
| Kingston SUV500MS480G 480GB           | 1         | 1      | 5.56%   |
| HGST HTS725050A7E630 500GB            | 1         | 1      | 5.56%   |
| HGST HTS545050A7E660 500GB            | 1         | 2      | 5.56%   |
| Crucial CT525MX300SSD1 528GB          | 1         | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 12     | 33.33%  |
| WDC                 | 3         | 3      | 16.67%  |
| Toshiba             | 3         | 5      | 16.67%  |
| HGST                | 2         | 3      | 11.11%  |
| SanDisk             | 1         | 1      | 5.56%   |
| Samsung Electronics | 1         | 2      | 5.56%   |
| Kingston            | 1         | 1      | 5.56%   |
| Crucial             | 1         | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 12     | 42.86%  |
| WDC     | 3         | 3      | 21.43%  |
| Toshiba | 3         | 5      | 21.43%  |
| HGST    | 2         | 3      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 23     | 76.47%  |
| SSD  | 4         | 5      | 23.53%  |

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
| Works    | 121       | 201    | 84.03%  |
| Malfunc  | 17        | 28     | 11.81%  |
| Detected | 6         | 7      | 4.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 111       | 63.07%  |
| Samsung Electronics            | 16        | 9.09%   |
| AMD                            | 14        | 7.95%   |
| Micron/Crucial Technology      | 6         | 3.41%   |
| SanDisk                        | 5         | 2.84%   |
| Micron Technology              | 4         | 2.27%   |
| Marvell Technology Group       | 4         | 2.27%   |
| SK hynix                       | 3         | 1.7%    |
| Phison Electronics             | 3         | 1.7%    |
| KIOXIA                         | 2         | 1.14%   |
| Kingston Technology Company    | 2         | 1.14%   |
| Transcend                      | 1         | 0.57%   |
| Toshiba                        | 1         | 0.57%   |
| Solid State Storage Technology | 1         | 0.57%   |
| Realtek Semiconductor          | 1         | 0.57%   |
| Nvidia                         | 1         | 0.57%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.57%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 14        | 7.41%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 12        | 6.35%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 12        | 6.35%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 10        | 5.29%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 9         | 4.76%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 9         | 4.76%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 9         | 4.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 7         | 3.7%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 6         | 3.17%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 5         | 2.65%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 5         | 2.65%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                       | 4         | 2.12%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 2.12%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 3         | 1.59%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                        | 3         | 1.59%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                 | 3         | 1.59%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 1.59%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 1.59%   |
| Intel Comet Lake RAID Controller                                                 | 3         | 1.59%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 1.59%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 1.59%   |
| SK hynix BC511 NVMe SSD                                                          | 2         | 1.06%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                      | 2         | 1.06%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 2         | 1.06%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 1.06%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 2         | 1.06%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                             | 2         | 1.06%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 2         | 1.06%   |
| Micron 2200S NVMe SSD [Cassandra]                                                | 2         | 1.06%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 2         | 1.06%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 1.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.06%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 1.06%   |
| Transcend NVMe PCIe SSD 240S/MTE710T                                             | 1         | 0.53%   |
| Toshiba XG4 NVMe SSD Controller                                                  | 1         | 0.53%   |
| Solid State Storage CA6-8D512 NVMe SSD M.2                                       | 1         | 0.53%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 1         | 0.53%   |
| Sandisk WD PC SN740 NVMe SSD 512GB (DRAM-less)                                   | 1         | 0.53%   |
| SanDisk PC SN520 x2 M.2 2242 NVMe SSD                                            | 1         | 0.53%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 1         | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 111       | 62.01%  |
| NVMe | 46        | 25.7%   |
| RAID | 13        | 7.26%   |
| IDE  | 9         | 5.03%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 136       | 86.08%  |
| AMD     | 21        | 13.29%  |
| PowerPC | 1         | 0.63%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5-5300U CPU @ 2.30GHz    | 5         | 3.16%   |
| Intel Core i5-2520M CPU @ 2.50GHz    | 5         | 3.16%   |
| Intel Core i5-8265U CPU @ 1.60GHz    | 4         | 2.53%   |
| Intel Core i5-4250U CPU @ 1.30GHz    | 4         | 2.53%   |
| Intel Core i7-6500U CPU @ 2.50GHz    | 3         | 1.9%    |
| Intel Core i5-10210U CPU @ 1.60GHz   | 3         | 1.9%    |
| Intel Core i5 CPU M 560 @ 2.67GH     | 3         | 1.9%    |
| Intel Core i3-4010U CPU @ 1.70GHz    | 3         | 1.9%    |
| AMD EPYC 3201 8-Core Processor       | 3         | 1.9%    |
| AMD EPYC 3101 4-Core Processor       | 3         | 1.9%    |
| Intel Core i7-8565U CPU @ 1.80GHz    | 2         | 1.27%   |
| Intel Core i7-8550U CPU @ 1.80GHz    | 2         | 1.27%   |
| Intel Core i7-7500U CPU @ 2.70GHz    | 2         | 1.27%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz   | 2         | 1.27%   |
| Intel Core i7-6600U CPU @ 2.60GHz    | 2         | 1.27%   |
| Intel Core i7-2620M CPU @ 2.70GHz    | 2         | 1.27%   |
| Intel Core i5-9300H CPU @ 2.40GHz    | 2         | 1.27%   |
| Intel Core i5-8250U CPU @ 1.60GHz    | 2         | 1.27%   |
| Intel Core i5-7360U CPU @ 2.30GHz    | 2         | 1.27%   |
| Intel Core i5-7300U CPU @ 2.60GHz    | 2         | 1.27%   |
| Intel Core i5-7200U CPU @ 2.50GHz    | 2         | 1.27%   |
| Intel Core i5-4200U CPU @ 1.60GHz    | 2         | 1.27%   |
| Intel Core i5-3437U CPU @ 1.90GHz    | 2         | 1.27%   |
| Intel Core i5-3320M CPU @ 2.60GHz    | 2         | 1.27%   |
| Intel Core i3-8130U CPU @ 2.20GHz    | 2         | 1.27%   |
| Intel Core i3-4025U CPU @ 1.90GHz    | 2         | 1.27%   |
| Intel Core i3-4005U CPU @ 1.70GHz    | 2         | 1.27%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz | 2         | 1.27%   |
| Intel Celeron CPU N3160 @ 1.60GHz    | 2         | 1.27%   |
| PowerPC 7447A (Revision 0x105)       | 1         | 0.63%   |
| Intel Xeon W-11855M CPU @ 3.20GHz    | 1         | 0.63%   |
| Intel Pentium M                      | 1         | 0.63%   |
| Intel CPU Version                    | 1         | 0.63%   |
| Intel Core M-5Y10c CPU @ 0.80GHz     | 1         | 0.63%   |
| Intel Core i7-9850H CPU @ 2.60GHz    | 1         | 0.63%   |
| Intel Core i7-8750H CPU @ 2.20GHz    | 1         | 0.63%   |
| Intel Core i7-8665U CPU @ 1.90GHz    | 1         | 0.63%   |
| Intel Core i7-7920HQ CPU @ 3.10GHz   | 1         | 0.63%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz   | 1         | 0.63%   |
| Intel Core i7-7820HK CPU @ 2.90GHz   | 1         | 0.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 50        | 31.65%  |
| Intel Core i7    | 39        | 24.68%  |
| Intel Core i3    | 13        | 8.23%   |
| Other            | 10        | 6.33%   |
| Intel Core 2 Duo | 9         | 5.7%    |
| Intel Celeron    | 8         | 5.06%   |
| AMD EPYC         | 6         | 3.8%    |
| Intel Atom       | 4         | 2.53%   |
| AMD Ryzen 7 PRO  | 4         | 2.53%   |
| AMD Ryzen 7      | 4         | 2.53%   |
| AMD A4           | 2         | 1.27%   |
| Intel Xeon       | 1         | 0.63%   |
| Intel Pentium M  | 1         | 0.63%   |
| Intel Core M     | 1         | 0.63%   |
| Intel Core 2     | 1         | 0.63%   |
| AMD Ryzen 5 PRO  | 1         | 0.63%   |
| AMD Ryzen 5      | 1         | 0.63%   |
| AMD E2           | 1         | 0.63%   |
| AMD E1           | 1         | 0.63%   |
| AMD A6           | 1         | 0.63%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 74        | 46.84%  |
| 4       | 49        | 31.01%  |
| Unknown | 11        | 6.96%   |
| 8       | 10        | 6.33%   |
| 16      | 4         | 2.53%   |
| 6       | 4         | 2.53%   |
| 12      | 2         | 1.27%   |
| 1       | 2         | 1.27%   |
| 32      | 1         | 0.63%   |
| 10      | 1         | 0.63%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 150       | 95.54%  |
| Unknown | 5         | 3.18%   |
| 2       | 2         | 1.27%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 109       | 68.99%  |
| 1       | 37        | 23.42%  |
| Unknown | 12        | 7.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 36        | 22.78%  |
| Haswell       | 21        | 13.29%  |
| IvyBridge     | 13        | 8.23%   |
| SandyBridge   | 12        | 7.59%   |
| Unknown       | 12        | 7.59%   |
| Skylake       | 9         | 5.7%    |
| Broadwell     | 9         | 5.7%    |
| Penryn        | 8         | 5.06%   |
| Zen           | 7         | 4.43%   |
| Westmere      | 6         | 3.8%    |
| Silvermont    | 4         | 2.53%   |
| Zen+          | 3         | 1.9%    |
| Zen 2         | 3         | 1.9%    |
| Core          | 3         | 1.9%    |
| Bonnell       | 3         | 1.9%    |
| K10 Llano     | 2         | 1.27%   |
| Jaguar        | 2         | 1.27%   |
| Zen 3         | 1         | 0.63%   |
| TigerLake     | 1         | 0.63%   |
| P6            | 1         | 0.63%   |
| Goldmont plus | 1         | 0.63%   |
| Excavator     | 1         | 0.63%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 120       | 67.8%   |
| Nvidia | 35        | 19.77%  |
| AMD    | 22        | 12.43%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 17        | 9.24%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 11        | 5.98%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11        | 5.98%   |
| Intel HD Graphics 5500                                                                   | 8         | 4.35%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 3.8%    |
| Intel UHD Graphics 620                                                                   | 6         | 3.26%   |
| Intel HD Graphics 620                                                                    | 6         | 3.26%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 3.26%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 2.72%   |
| Intel HD Graphics 630                                                                    | 4         | 2.17%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 2.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 2.17%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 2.17%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 3         | 1.63%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 1.63%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 1.63%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.63%   |
| Intel HD Graphics 530                                                                    | 3         | 1.63%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 1.63%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 3         | 1.63%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 1.63%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 1.09%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 1.09%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 2         | 1.09%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.09%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.09%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 1.09%   |
| Intel Iris Plus Graphics 640                                                             | 2         | 1.09%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 2         | 1.09%   |
| AMD Lucienne                                                                             | 2         | 1.09%   |
| Nvidia TU117GLM [T1200 Laptop GPU]                                                       | 1         | 0.54%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 0.54%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.54%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.54%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.54%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.54%   |
| Nvidia GP104GLM [Quadro P3000 Mobile]                                                    | 1         | 0.54%   |
| Nvidia GP104BM [GeForce GTX 1080 Mobile]                                                 | 1         | 0.54%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                    | 1         | 0.54%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 86        | 54.43%  |
| Intel + Nvidia           | 21        | 13.29%  |
| 1 x AMD                  | 17        | 10.76%  |
| 1 x Nvidia               | 12        | 7.59%   |
| 2 x Intel                | 11        | 6.96%   |
| Other                    | 6         | 3.8%    |
| 2 x AMD                  | 2         | 1.27%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.63%   |
| Intel + AMD              | 1         | 0.63%   |
| AMD + Nvidia             | 1         | 0.63%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 138       | 86.25%  |
| Proprietary | 12        | 7.5%    |
| Unknown     | 10        | 6.25%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 140       | 88.61%  |
| 0.51-1.0   | 5         | 3.16%   |
| 0.01-0.5   | 4         | 2.53%   |
| 3.01-4.0   | 3         | 1.9%    |
| 7.01-8.0   | 2         | 1.27%   |
| 5.01-6.0   | 2         | 1.27%   |
| 1.01-2.0   | 1         | 0.63%   |
| 8.01-16.0  | 1         | 0.63%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 23        | 17.97%  |
| LG Display              | 17        | 13.28%  |
| Chimei Innolux          | 16        | 12.5%   |
| BOE                     | 12        | 9.38%   |
| Apple                   | 11        | 8.59%   |
| Samsung Electronics     | 10        | 7.81%   |
| Chi Mei Optoelectronics | 5         | 3.91%   |
| Goldstar                | 4         | 3.13%   |
| Dell                    | 4         | 3.13%   |
| Philips                 | 3         | 2.34%   |
| Lenovo                  | 3         | 2.34%   |
| Iiyama                  | 3         | 2.34%   |
| ViewSonic               | 2         | 1.56%   |
| Sharp                   | 2         | 1.56%   |
| LGD                     | 2         | 1.56%   |
| HUAWEI                  | 2         | 1.56%   |
| CSO                     | 2         | 1.56%   |
| Nvidia                  | 1         | 0.78%   |
| IBM                     | 1         | 0.78%   |
| Hewlett-Packard         | 1         | 0.78%   |
| CPT                     | 1         | 0.78%   |
| BOE Technology Group    | 1         | 0.78%   |
| ASUSTek Computer        | 1         | 0.78%   |
| Acer                    | 1         | 0.78%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                     | 4         | 3.13%   |
| Goldstar 24GM77 GSM5A91 1920x1080 530x300mm 24.0-inch                    | 3         | 2.34%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 3         | 2.34%   |
| Philips PHL 241B8Q PHL0929 1920x1080 530x300mm 24.0-inch                 | 2         | 1.56%   |
| LGD LCD Monitor 1600x900                                                 | 2         | 1.56%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 2         | 1.56%   |
| Iiyama PL2474H IVM6146 1920x1080 520x290mm 23.4-inch                     | 2         | 1.56%   |
| HUAWEI AD80HW HWV2402 1920x1080 530x300mm 24.0-inch                      | 2         | 1.56%   |
| Dell SE2417HGX DELD0F7 1920x1080 520x290mm 23.4-inch                     | 2         | 1.56%   |
| Chimei Innolux LCD Monitor CMN1343 1920x1080 280x160mm 12.7-inch         | 2         | 1.56%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 2         | 1.56%   |
| BOE LCD Monitor BOE0700 1920x1080 340x190mm 15.3-inch                    | 2         | 1.56%   |
| AU Optronics LCD Monitor AUO34ED 1920x1080 340x190mm 15.3-inch           | 2         | 1.56%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch            | 2         | 1.56%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch           | 2         | 1.56%   |
| Apple Color LCD APPA034 2880x1800 290x180mm 13.4-inch                    | 2         | 1.56%   |
| ViewSonic VA2223-FHD VSC9239 1920x1080 480x270mm 21.7-inch               | 1         | 0.78%   |
| ViewSonic TD2420 SERIES VSC452D 1920x1080 520x290mm 23.4-inch            | 1         | 0.78%   |
| Sharp LCD Monitor SHP14B9 3840x2160 340x190mm 15.3-inch                  | 1         | 0.78%   |
| Sharp LCD Monitor SHP1416 1366x768 310x170mm 13.9-inch                   | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC544E 1024x600 220x130mm 10.1-inch     | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x170mm 13.9-inch     | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch    | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 300x190mm 14.0-inch     | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC3659 1600x900 340x190mm 15.3-inch     | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 340x190mm 15.3-inch     | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch     | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 340x190mm 15.3-inch     | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch     | 1         | 0.78%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch        | 1         | 0.78%   |
| Philips PHL 439P1 PHL0973 3840x2160 940x530mm 42.5-inch                  | 1         | 0.78%   |
| Nvidia LCD Monitor Default Flat Panel 1440x900                           | 1         | 0.78%   |
| LG Display LCD Monitor LGD7001 1366x768 340x190mm 15.3-inch              | 1         | 0.78%   |
| LG Display LCD Monitor LGD063F 1920x1080 380x210mm 17.1-inch             | 1         | 0.78%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch             | 1         | 0.78%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch             | 1         | 0.78%   |
| LG Display LCD Monitor LGD04F9 1920x1080 310x170mm 13.9-inch             | 1         | 0.78%   |
| LG Display LCD Monitor LGD0438 1366x768 340x190mm 15.3-inch              | 1         | 0.78%   |
| LG Display LCD Monitor LGD03EE 1366x768 280x160mm 12.7-inch              | 1         | 0.78%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch              | 1         | 0.78%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 47        | 40.17%  |
| 1366x768 (WXGA)    | 34        | 29.06%  |
| 1600x900 (HD+)     | 8         | 6.84%   |
| 1440x900 (WXGA+)   | 6         | 5.13%   |
| 3840x2160 (4K)     | 4         | 3.42%   |
| 1280x800 (WXGA)    | 4         | 3.42%   |
| 2560x1440 (QHD)    | 3         | 2.56%   |
| 1024x600           | 3         | 2.56%   |
| 2880x1800          | 2         | 1.71%   |
| 1920x1200 (WUXGA)  | 2         | 1.71%   |
| 2560x1600          | 1         | 0.85%   |
| 1680x1050 (WSXGA+) | 1         | 0.85%   |
| 1440x960           | 1         | 0.85%   |
| 1400x1050          | 1         | 0.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 38        | 30.4%   |
| 15      | 31        | 24.8%   |
| 12      | 15        | 12%     |
| 24      | 6         | 4.8%    |
| 23      | 6         | 4.8%    |
| 17      | 6         | 4.8%    |
| Unknown | 5         | 4%      |
| 14      | 4         | 3.2%    |
| 27      | 3         | 2.4%    |
| 21      | 3         | 2.4%    |
| 10      | 3         | 2.4%    |
| 11      | 2         | 1.6%    |
| 42      | 1         | 0.8%    |
| 18      | 1         | 0.8%    |
| 9       | 1         | 0.8%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 58        | 46.77%  |
| 201-300     | 36        | 29.03%  |
| 501-600     | 13        | 10.48%  |
| 351-400     | 6         | 4.84%   |
| Unknown     | 5         | 4.03%   |
| 401-500     | 4         | 3.23%   |
| 601-700     | 1         | 0.81%   |
| 901-1000    | 1         | 0.81%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 87        | 79.09%  |
| 16/10   | 14        | 12.73%  |
| Unknown | 5         | 4.55%   |
| 3/2     | 3         | 2.73%   |
| 4/3     | 1         | 0.91%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 39        | 31.45%  |
| 91-100         | 27        | 21.77%  |
| 61-70          | 15        | 12.1%   |
| 201-250        | 14        | 11.29%  |
| 121-130        | 6         | 4.84%   |
| Unknown        | 5         | 4.03%   |
| 41-50          | 4         | 3.23%   |
| 101-110        | 4         | 3.23%   |
| 301-350        | 3         | 2.42%   |
| 71-80          | 2         | 1.61%   |
| 51-60          | 2         | 1.61%   |
| 141-150        | 1         | 0.81%   |
| 111-120        | 1         | 0.81%   |
| 501-1000       | 1         | 0.81%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 57        | 46.72%  |
| 101-120       | 34        | 27.87%  |
| 51-100        | 14        | 11.48%  |
| 161-240       | 8         | 6.56%   |
| Unknown       | 5         | 4.1%    |
| More than 240 | 4         | 3.28%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 109       | 65.66%  |
| 0     | 40        | 24.1%   |
| 2     | 14        | 8.43%   |
| 3     | 3         | 1.81%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 110       | 45.45%  |
| Realtek Semiconductor             | 52        | 21.49%  |
| Qualcomm Atheros                  | 26        | 10.74%  |
| Broadcom                          | 17        | 7.02%   |
| AMD                               | 6         | 2.48%   |
| Marvell Technology Group          | 5         | 2.07%   |
| Xiaomi                            | 3         | 1.24%   |
| TP-Link                           | 3         | 1.24%   |
| Sierra Wireless                   | 3         | 1.24%   |
| Dell                              | 3         | 1.24%   |
| Edimax Technology                 | 2         | 0.83%   |
| Apple                             | 2         | 0.83%   |
| Samsung Electronics               | 1         | 0.41%   |
| Sagem                             | 1         | 0.41%   |
| Ralink Technology                 | 1         | 0.41%   |
| Ralink                            | 1         | 0.41%   |
| Qualcomm                          | 1         | 0.41%   |
| Nvidia                            | 1         | 0.41%   |
| MediaTek                          | 1         | 0.41%   |
| Huawei Technologies               | 1         | 0.41%   |
| Hewlett-Packard                   | 1         | 0.41%   |
| Ericsson Business Mobile Networks | 1         | 0.41%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 36        | 11.46%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 15        | 4.78%   |
| Intel Wireless 8265 / 8275                                             | 12        | 3.82%   |
| Intel Wireless 7265                                                    | 11        | 3.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 10        | 3.18%   |
| Intel Wireless 8260                                                    | 8         | 2.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 7         | 2.23%   |
| Intel Ethernet Connection (3) I218-LM                                  | 7         | 2.23%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 6         | 1.91%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 6         | 1.91%   |
| Intel Wireless 7260                                                    | 6         | 1.91%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 6         | 1.91%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 6         | 1.91%   |
| AMD XGMAC 10GbE Controller                                             | 6         | 1.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 5         | 1.59%   |
| Intel Wi-Fi 6 AX200                                                    | 5         | 1.59%   |
| Intel I210 Gigabit Network Connection                                  | 5         | 1.59%   |
| Intel Ethernet Connection (4) I219-V                                   | 5         | 1.59%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 5         | 1.59%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 4         | 1.27%   |
| Intel Ethernet Connection I217-LM                                      | 4         | 1.27%   |
| Intel Ethernet Connection (4) I219-LM                                  | 4         | 1.27%   |
| Intel 82567LM Gigabit Network Connection                               | 4         | 1.27%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 3         | 0.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 3         | 0.96%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 3         | 0.96%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 3         | 0.96%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                | 3         | 0.96%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 3         | 0.96%   |
| Intel Ethernet Connection (6) I219-V                                   | 3         | 0.96%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3         | 0.96%   |
| Intel Centrino Advanced-N 6235                                         | 3         | 0.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 3         | 0.96%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 2         | 0.64%   |
| Sierra Wireless EM7305 Modem                                           | 2         | 0.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2         | 0.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 2         | 0.64%   |
| Intel Wireless 3165                                                    | 2         | 0.64%   |
| Intel WiFi Link 5100                                                   | 2         | 0.64%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 2         | 0.64%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 101       | 62.73%  |
| Qualcomm Atheros      | 23        | 14.29%  |
| Broadcom              | 14        | 8.7%    |
| Realtek Semiconductor | 11        | 6.83%   |
| TP-Link               | 3         | 1.86%   |
| Edimax Technology     | 2         | 1.24%   |
| Dell                  | 2         | 1.24%   |
| Sierra Wireless       | 1         | 0.62%   |
| Sagem                 | 1         | 0.62%   |
| Ralink Technology     | 1         | 0.62%   |
| Ralink                | 1         | 0.62%   |
| MediaTek              | 1         | 0.62%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 12        | 7.41%   |
| Intel Wireless 7265                                            | 11        | 6.79%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 10        | 6.17%   |
| Intel Wireless 8260                                            | 8         | 4.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 7         | 4.32%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 6         | 3.7%    |
| Intel Wireless 7260                                            | 6         | 3.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 6         | 3.7%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 6         | 3.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 5         | 3.09%   |
| Intel Wi-Fi 6 AX200                                            | 5         | 3.09%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 5         | 3.09%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 4         | 2.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 3         | 1.85%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 3         | 1.85%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 3         | 1.85%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 3         | 1.85%   |
| Intel Centrino Advanced-N 6235                                 | 3         | 1.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 1.85%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 2         | 1.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 1.23%   |
| Intel Wireless 3165                                            | 2         | 1.23%   |
| Intel WiFi Link 5100                                           | 2         | 1.23%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 2         | 1.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 1.23%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 2         | 1.23%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 1.23%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 2         | 1.23%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 2         | 1.23%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter             | 2         | 1.23%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 2         | 1.23%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 0.62%   |
| Sierra Wireless EM7345 4G LTE                                  | 1         | 0.62%   |
| Sagem XG-76NA 802.11bg                                         | 1         | 0.62%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.62%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                   | 1         | 0.62%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 0.62%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 0.62%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 71        | 49.65%  |
| Realtek Semiconductor    | 43        | 30.07%  |
| Qualcomm Atheros         | 7         | 4.9%    |
| AMD                      | 6         | 4.2%    |
| Marvell Technology Group | 5         | 3.5%    |
| Broadcom                 | 4         | 2.8%    |
| Xiaomi                   | 3         | 2.1%    |
| Samsung Electronics      | 1         | 0.7%    |
| Qualcomm                 | 1         | 0.7%    |
| Nvidia                   | 1         | 0.7%    |
| Apple                    | 1         | 0.7%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 36        | 25%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 15        | 10.42%  |
| Intel Ethernet Connection (3) I218-LM                                  | 7         | 4.86%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 6         | 4.17%   |
| AMD XGMAC 10GbE Controller                                             | 6         | 4.17%   |
| Intel I210 Gigabit Network Connection                                  | 5         | 3.47%   |
| Intel Ethernet Connection (4) I219-V                                   | 5         | 3.47%   |
| Intel Ethernet Connection I217-LM                                      | 4         | 2.78%   |
| Intel Ethernet Connection (4) I219-LM                                  | 4         | 2.78%   |
| Intel 82567LM Gigabit Network Connection                               | 4         | 2.78%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 3         | 2.08%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 3         | 2.08%   |
| Intel Ethernet Connection (6) I219-V                                   | 3         | 2.08%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3         | 2.08%   |
| Intel Ethernet Controller I225-V                                       | 2         | 1.39%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 1.39%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 1.39%   |
| Intel Ethernet Connection (5) I219-LM                                  | 2         | 1.39%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 0.69%   |
| Realtek USB 2.5GbE Controller                                          | 1         | 0.69%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 0.69%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.69%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.69%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.69%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.69%   |
| Qualcomm ALCATEL RNDIS Interface                                       | 1         | 0.69%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 0.69%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 1         | 0.69%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                | 1         | 0.69%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 0.69%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 1         | 0.69%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                   | 1         | 0.69%   |
| Intel Ethernet Connection I219-V                                       | 1         | 0.69%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1         | 0.69%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 0.69%   |
| Intel Ethernet Connection (3) I218-V                                   | 1         | 0.69%   |
| Intel Ethernet Connection (23) I219-V                                  | 1         | 0.69%   |
| Intel Ethernet Connection (23) I219-LM                                 | 1         | 0.69%   |
| Intel Ethernet Connection (16) I219-LM                                 | 1         | 0.69%   |
| Intel Ethernet Connection (14) I219-LM                                 | 1         | 0.69%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 143       | 50.35%  |
| Ethernet | 133       | 46.83%  |
| Unknown  | 5         | 1.76%   |
| Modem    | 3         | 1.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 100       | 52.08%  |
| WiFi     | 92        | 47.92%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 116       | 73.42%  |
| 1     | 28        | 17.72%  |
| 6     | 7         | 4.43%   |
| 3     | 6         | 3.8%    |
| 0     | 1         | 0.63%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 138       | 84.66%  |
| Yes  | 25        | 15.34%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 66        | 65.35%  |
| Broadcom                        | 8         | 7.92%   |
| Apple                           | 8         | 7.92%   |
| Qualcomm Atheros Communications | 4         | 3.96%   |
| Realtek Semiconductor           | 3         | 2.97%   |
| IMC Networks                    | 3         | 2.97%   |
| Foxconn / Hon Hai               | 3         | 2.97%   |
| Dell                            | 3         | 2.97%   |
| TP-Link                         | 1         | 0.99%   |
| Hewlett-Packard                 | 1         | 0.99%   |
| Creative Technology             | 1         | 0.99%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                        | 30        | 29.7%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)            | 11        | 10.89%  |
| Intel AX201 Bluetooth                                     | 8         | 7.92%   |
| Intel AX200 Bluetooth                                     | 5         | 4.95%   |
| Apple Broadcom Built-in Bluetooth                         | 4         | 3.96%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                  | 3         | 2.97%   |
| Intel AX210 Bluetooth                                     | 3         | 2.97%   |
| Broadcom BCM2045B (BDC-2.1)                               | 3         | 2.97%   |
| Apple Bluetooth Host Controller                           | 3         | 2.97%   |
| Realtek Bluetooth Adapter                                 | 2         | 1.98%   |
| Intel Wireless-AC 3168 Bluetooth                          | 2         | 1.98%   |
| Intel Centrino Bluetooth Wireless Transceiver             | 2         | 1.98%   |
| Intel AX211 Bluetooth                                     | 2         | 1.98%   |
| Foxconn / Hon Hai Bluetooth USB Module                    | 2         | 1.98%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module               | 2         | 1.98%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                | 2         | 1.98%   |
| TP-Link Bluetooth 5.0 USB Adapter                         | 1         | 0.99%   |
| Realtek  Bluetooth 4.2 Adapter                            | 1         | 0.99%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                    | 1         | 0.99%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                    | 1         | 0.99%   |
| Qualcomm Atheros Bluetooth                                | 1         | 0.99%   |
| Qualcomm Atheros AR3011 Bluetooth                         | 1         | 0.99%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1               | 1         | 0.99%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS          | 1         | 0.99%   |
| IMC Networks Bluetooth Radio                              | 1         | 0.99%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]             | 1         | 0.99%   |
| Foxconn / Hon Hai Bluetooth 5.2 Adapter [MediaTek MT7922] | 1         | 0.99%   |
| Dell DW375 Bluetooth Module                               | 1         | 0.99%   |
| Creative Creative Bluetooth Audio W2                      | 1         | 0.99%   |
| Broadcom BCM43142A0 Bluetooth Module                      | 1         | 0.99%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]        | 1         | 0.99%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]          | 1         | 0.99%   |
| Apple Built-in iSight (no firmware loaded)                | 1         | 0.99%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 133       | 71.51%  |
| AMD                 | 25        | 13.44%  |
| Nvidia              | 16        | 8.6%    |
| Logitech            | 3         | 1.61%   |
| Lenovo              | 2         | 1.08%   |
| GN Netcom           | 2         | 1.08%   |
| ASUSTek Computer    | 2         | 1.08%   |
| Texas Instruments   | 1         | 0.54%   |
| Kingston Technology | 1         | 0.54%   |
| DSEA A/S            | 1         | 0.54%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 19        | 8.26%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 17        | 7.39%   |
| Intel 8 Series HD Audio Controller                                                                | 17        | 7.39%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 12        | 5.22%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 12        | 5.22%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 10        | 4.35%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9         | 3.91%   |
| Intel Broadwell-U Audio Controller                                                                | 9         | 3.91%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 3.04%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 2.61%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 2.61%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 2.61%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 2.61%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 2.17%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 2.17%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 5         | 2.17%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 4         | 1.74%   |
| Intel CM238 HD Audio Controller                                                                   | 4         | 1.74%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 1.74%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 1.74%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 1.74%   |
| AMD FCH Azalia Controller                                                                         | 4         | 1.74%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1.3%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.3%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 1.3%    |
| Logitech H600 [Wireless Headset]                                                                  | 2         | 0.87%   |
| Lenovo Realtek USB Audio                                                                          | 2         | 0.87%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.87%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 2         | 0.87%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 0.87%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 0.87%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.87%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 0.87%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 2         | 0.87%   |
| Unknown                                                                                           | 2         | 0.87%   |
| Texas Instruments PCM2706 stereo audio DAC                                                        | 1         | 0.43%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.43%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.43%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.43%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 46        | 27.71%  |
| SK hynix            | 35        | 21.08%  |
| Micron Technology   | 17        | 10.24%  |
| Unknown             | 13        | 7.83%   |
| Crucial             | 10        | 6.02%   |
| Kingston            | 9         | 5.42%   |
| Elpida              | 8         | 4.82%   |
| Transcend           | 5         | 3.01%   |
| Corsair             | 4         | 2.41%   |
| Nanya Technology    | 3         | 1.81%   |
| Unknown             | 3         | 1.81%   |
| G.Skill             | 2         | 1.2%    |
| A-DATA Technology   | 2         | 1.2%    |
| V-Color             | 1         | 0.6%    |
| Unknown (ABCD)      | 1         | 0.6%    |
| SHARETRONIC         | 1         | 0.6%    |
| Ramaxel Technology  | 1         | 0.6%    |
| Patriot             | 1         | 0.6%    |
| CSX                 | 1         | 0.6%    |
| Avant               | 1         | 0.6%    |
| 48spaces            | 1         | 0.6%    |
| 2B0B00000000        | 1         | 0.6%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                 | 5         | 2.75%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s     | 4         | 2.2%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s      | 4         | 2.2%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s      | 4         | 2.2%    |
| Transcend RAM TS1GLH64V6B3 8GB SODIMM DDR4 1333MT/s        | 3         | 1.65%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 3         | 1.65%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s     | 3         | 1.65%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s     | 3         | 1.65%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s     | 3         | 1.65%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s      | 3         | 1.65%   |
| Unknown                                                    | 3         | 1.65%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                 | 2         | 1.1%    |
| Unknown RAM Module 2GB SODIMM DDR2                         | 2         | 1.1%    |
| Unknown RAM Module 1GB SODIMM DDR2                         | 2         | 1.1%    |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s        | 2         | 1.1%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s     | 2         | 1.1%    |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s    | 2         | 1.1%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s     | 2         | 1.1%    |
| Samsung RAM M471B5773CHS-CK0 2GB DDR3 1600MT/s             | 2         | 1.1%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s      | 2         | 1.1%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s      | 2         | 1.1%    |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s     | 2         | 1.1%    |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2400MT/s     | 2         | 1.1%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s      | 2         | 1.1%    |
| Micron RAM Module 4GB SODIMM LPDDR3 2133MT/s               | 2         | 1.1%    |
| Elpida RAM Module 4096MB SODIMM DDR3 1600MT/s              | 2         | 1.1%    |
| Crucial RAM CT204864BF160B.C16 16GB SODIMM DDR3 1600MT/s   | 2         | 1.1%    |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s    | 2         | 1.1%    |
| Corsair RAM CMSX8GX4M1A2400C16 8GB SODIMM DDR4 2400MT/s    | 2         | 1.1%    |
| A-DATA RAM AO1P32NCST2-BZ6SHD 16384MB SODIMM DDR4 3200MT/s | 2         | 1.1%    |
| V-Color RAM TN48G24S817-VHA/R 8GB SODIMM DDR4 2400MT/s     | 1         | 0.55%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                | 1         | 0.55%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                | 1         | 0.55%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2400MT/s             | 1         | 0.55%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                | 1         | 0.55%   |
| Unknown RAM Module 4GB SODIMM 533MT/s                      | 1         | 0.55%   |
| Unknown RAM Module 4096MB SODIMM LPDDR3 1600MT/s           | 1         | 0.55%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                | 1         | 0.55%   |
| Unknown RAM Module 2GB SODIMM 667MT/s                      | 1         | 0.55%   |
| Unknown RAM Module 1024MB SODIMM DDR2                      | 1         | 0.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 58        | 42.65%  |
| DDR4    | 54        | 39.71%  |
| DDR2    | 10        | 7.35%   |
| LPDDR3  | 7         | 5.15%   |
| DDR5    | 3         | 2.21%   |
| Unknown | 2         | 1.47%   |
| LPDDR5  | 1         | 0.74%   |
| LPDDR4  | 1         | 0.74%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 130       | 92.86%  |
| Row Of Chips | 4         | 2.86%   |
| Chip         | 3         | 2.14%   |
| Unknown      | 3         | 2.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 52        | 34.21%  |
| 8192  | 49        | 32.24%  |
| 16384 | 23        | 15.13%  |
| 2048  | 20        | 13.16%  |
| 32768 | 5         | 3.29%   |
| 1024  | 3         | 1.97%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 42        | 28.77%  |
| 2667    | 20        | 13.7%   |
| 3200    | 15        | 10.27%  |
| 2400    | 14        | 9.59%   |
| 1333    | 13        | 8.9%    |
| 2133    | 10        | 6.85%   |
| 1334    | 10        | 6.85%   |
| 1867    | 4         | 2.74%   |
| Unknown | 4         | 2.74%   |
| 800     | 3         | 2.05%   |
| 667     | 3         | 2.05%   |
| 5600    | 2         | 1.37%   |
| 6400    | 1         | 0.68%   |
| 4800    | 1         | 0.68%   |
| 1200    | 1         | 0.68%   |
| 1067    | 1         | 0.68%   |
| 975     | 1         | 0.68%   |
| 533     | 1         | 0.68%   |

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
| Chicony Electronics                    | 35        | 32.71%  |
| Sunplus Innovation Technology          | 11        | 10.28%  |
| Bison Electronics                      | 10        | 9.35%   |
| Realtek Semiconductor                  | 9         | 8.41%   |
| Microdia                               | 9         | 8.41%   |
| IMC Networks                           | 9         | 8.41%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 4.67%   |
| Syntek                                 | 4         | 3.74%   |
| Lite-On Technology                     | 4         | 3.74%   |
| Quanta                                 | 3         | 2.8%    |
| Suyin                                  | 2         | 1.87%   |
| Alcor Micro                            | 2         | 1.87%   |
| Z-Star Microelectronics                | 1         | 0.93%   |
| SIMPLO Technology                      | 1         | 0.93%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.93%   |
| Apple                                  | 1         | 0.93%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                             | 11        | 10.19%  |
| Bison Integrated Camera                               | 7         | 6.48%   |
| Sunplus Integrated_Webcam_HD                          | 5         | 4.63%   |
| Realtek Integrated_Webcam_HD                          | 4         | 3.7%    |
| Microdia Integrated_Webcam_HD                         | 4         | 3.7%    |
| Chicony HD WebCam                                     | 4         | 3.7%    |
| Syntek Integrated Camera                              | 3         | 2.78%   |
| Microdia Integrated Webcam                            | 3         | 2.78%   |
| Lite-On Integrated Camera                             | 3         | 2.78%   |
| Chicony Lenovo Integrated Camera (0.3MP)              | 3         | 2.78%   |
| Realtek USB Camera                                    | 2         | 1.85%   |
| IMC Networks USB2.0 HD UVC WebCam                     | 2         | 1.85%   |
| IMC Networks Realtek PC Camera                        | 2         | 1.85%   |
| IMC Networks EasyCamera                               | 2         | 1.85%   |
| Chicony TOSHIBA Web Camera - HD                       | 2         | 1.85%   |
| Chicony Realtek DMFT RGB                              | 2         | 1.85%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam   | 2         | 1.85%   |
| Bison SunplusIT Integrated Camera                     | 2         | 1.85%   |
| Z-Star Webcam                                         | 1         | 0.93%   |
| Syntek Lenovo EasyCamera                              | 1         | 0.93%   |
| Suyin USB 2.0 Camera                                  | 1         | 0.93%   |
| Suyin Laptop_Integrated_Webcam_FHD                    | 1         | 0.93%   |
| Sunplus Laptop_Integrated_Webcam_HD                   | 1         | 0.93%   |
| Sunplus Laptop_Integrated_Webcam_FHD                  | 1         | 0.93%   |
| Sunplus Integrated HD Webcam                          | 1         | 0.93%   |
| Sunplus Hy HD Camera                                  | 1         | 0.93%   |
| Sunplus Dell Integrated Webcam                        | 1         | 0.93%   |
| Sunplus Asus Webcam                                   | 1         | 0.93%   |
| SIMPLO USB 2.0 Camera                                 | 1         | 0.93%   |
| Shenzhen Kingcome Optoelectronic USB2.0 HD UVC WebCam | 1         | 0.93%   |
| Realtek USB 2.0 PC Camera                             | 1         | 0.93%   |
| Realtek Integrated_Webcam_FHD                         | 1         | 0.93%   |
| Realtek Integrated Webcam HD                          | 1         | 0.93%   |
| Quanta Realtek DMFT RGB                               | 1         | 0.93%   |
| Quanta Integrated Webcam                              | 1         | 0.93%   |
| Quanta HD WebCam                                      | 1         | 0.93%   |
| Microdia Integrated_Webcam_FHD                        | 1         | 0.93%   |
| Microdia Dell Integrated HD Webcam                    | 1         | 0.93%   |
| Lite-On Realtek DMFT RGB                              | 1         | 0.93%   |
| IMC Networks UVC VGA Webcam                           | 1         | 0.93%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 12        | 35.29%  |
| Synaptics                  | 7         | 20.59%  |
| AuthenTec                  | 5         | 14.71%  |
| Shenzhen Goodix Technology | 3         | 8.82%   |
| LighTuning Technology      | 3         | 8.82%   |
| Elan Microelectronics      | 2         | 5.88%   |
| Upek                       | 1         | 2.94%   |
| Broadcom                   | 1         | 2.94%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 5         | 14.71%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 3         | 8.82%   |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 3         | 8.82%   |
| Shenzhen Goodix Fingerprint Reader                                           | 3         | 8.82%   |
| Validity Sensors Synaptics WBDI                                              | 2         | 5.88%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 2         | 5.88%   |
| Elan Fingerprint Sensor                                                      | 2         | 5.88%   |
| AuthenTec AES2810                                                            | 2         | 5.88%   |
| AuthenTec AES1660                                                            | 2         | 5.88%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 1         | 2.94%   |
| Validity Sensors VFS491                                                      | 1         | 2.94%   |
| Validity Sensors VFS451 Fingerprint Reader                                   | 1         | 2.94%   |
| Validity Sensors VFS Fingerprint sensor                                      | 1         | 2.94%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 1         | 2.94%   |
| Synaptics UWP WBDI Device                                                    | 1         | 2.94%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 1         | 2.94%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 1         | 2.94%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 2.94%   |
| AuthenTec AES2550 Fingerprint Sensor                                         | 1         | 2.94%   |

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
| 2     | 52        | 30.59%  |
| 1     | 51        | 30%     |
| 3     | 27        | 15.88%  |
| 0     | 18        | 10.59%  |
| 4     | 15        | 8.82%   |
| 6     | 4         | 2.35%   |
| 5     | 2         | 1.18%   |
| 7     | 1         | 0.59%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 118       | 40.97%  |
| Bluetooth                | 48        | 16.67%  |
| Net/wireless             | 34        | 11.81%  |
| Fingerprint reader       | 28        | 9.72%   |
| Card reader              | 26        | 9.03%   |
| Firewire controller      | 14        | 4.86%   |
| Sound                    | 5         | 1.74%   |
| Graphics card            | 5         | 1.74%   |
| Storage                  | 4         | 1.39%   |
| Storage/raid             | 3         | 1.04%   |
| Network                  | 2         | 0.69%   |
| Net/ethernet             | 1         | 0.35%   |

